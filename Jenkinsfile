node{
    stage('SCM Checkout'){
      git 'https://github.com/vijayakumar1/maven_testing.git'
    }
    stage('Compile-Package'){
      def mvnHome= tool name: 'Maven', type: 'maven'
      sh "${mvnHome}/bin/mvn install"
    }
}
