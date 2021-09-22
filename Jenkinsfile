pipeline {
  agent any 
  stages {
    stage('SCM Checkout'){
      steps {
        git 'https://github.com/chaksamu/my-app'
      }
    }
    stage ('Compile Package'){
      steps {
        sh 'mvn package'
      }
    }
  }
}

