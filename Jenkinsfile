pipeline {
  agent any
  triggers {
   cron('H/15 * * * *')
  }
  stages {
    stage('echo') {
      steps {
        echo 'hello from the trigger'
        echo 'hello from the trigger again :D'
      }
    }

  }
}
