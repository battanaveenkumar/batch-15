node{
  stage('scm checkout'){
    git 'https://github.com/battanaveenkumar/batch-15'
  }
  stage('compile-package'){
    bat 'mvn package'
  }
}
