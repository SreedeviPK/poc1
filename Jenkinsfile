node{
  stage('SCM Checkout'){
    git 'https://github.com/SreedeviPK/poc1'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
}
