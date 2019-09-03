node{
  stage('SCM Checkout'){
    git 'https://github.com/iTechJ/ci'
  }
  stage('Compile-Package'){
    sh 'mvn clean package'
  }
}
