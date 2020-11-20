pipeline {
  agent any
    triggers {
      githubPush()
    }
  stages {
    stage('echo') {
      steps {
        echo 'hello from the echo STAGE'
      }
    }
    stage('after TRIGGER') {
      steps {
        echo 'hello from the after TRIGGER STAGE'
      }
    }
  }
}
