node{
  stage('SCM Checkout'){
    git 'https://github.com/SreedeviPK/poc1'
  }
  stage('Compile-Package'){
    def mvnHome= tool name: 'MAVENHOME', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }
}
