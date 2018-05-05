pipeline {
  agent any
  stages {
    stage('send_sms') {
      steps {
        sh './sms_send'
        echo 'Dang this better work'
      }
    }
  }
}