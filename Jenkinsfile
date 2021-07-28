pipeline {
  agent any
  triggers {
    cron('H/15 * * * *')
  }
  stages {
    stage('echo') {
      steps {
        echo 'hey this is my first triggerv3.0'
      }
    }

  }
}
