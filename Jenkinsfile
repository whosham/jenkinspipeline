pipeline {
  agent any
  triggers {
   cron('H/15 * * * *')  
  }
  stages {
    stage('echo') {
      steps {
        echo 'Hello from triggerr'
      }
    }

  }
}
