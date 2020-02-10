pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        echo 'test'
        emailext(subject: 'test', body: 'test', from: 'test@storenext.co.il', to: 'gads@storenext.co.il')
      }
    }

  }
}