pipeline {
  agent any
  /*  triggers {
   cron('H/15 * * * *')
  }*/
  stages {
    stage('echo') {
      steps {
        echo 'hello from the echo STAGE'
      }
    }
    stage('after TRIGGER') {
      steps {
        def var1 = pwd

        echo 'hello from the after TRIGGER STAGE / pwd = ${var1}'
      }
    }

  }
}
