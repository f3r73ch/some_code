pipeline {
  agent any
  stages {
    stage('echo') {
      steps {
        echo 'hello from the trigger'
      }
    }

    stage('after echo') {
      steps {
        echo 'after echo stage'
      }
    }

  }
  triggers {
    cron('H/15 * * * *')
  }
}