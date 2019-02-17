node { 
    stage('SCM Checkout'){
    git 'https://github.com/danites/SpringBootWithXmlRestAppVer'
    }
    stage('Compile-Package'){
        //maven set up
      def mvnhome = tool name: 'maven-3.6', type: 'maven'
        sh "${mvnhome}/bin/mvn package"
    }
}
