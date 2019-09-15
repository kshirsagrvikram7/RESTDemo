node{
  stage('SCM Checkout'){
    git 'https://github.com/kshirsagrvikram7/RESTDemo.git'
  }
  stage('Compile-package'){
    sh 'maven package'
  }
}
