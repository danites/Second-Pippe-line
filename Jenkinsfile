node { 
    stage('SCM Checkout'){
    git 'https://github.com/danites/SpringBootWithXmlRestAppVer'
    }
    stage('Compile-Package'){
        //maven set up
      def mvnhome = tool name: 'maven-3.6', type: 'maven'
       //def javaHome = tool name: 'java8', type: 'jdk'
        sh "${mvnhome}/bin/mvn package"
    }
}
