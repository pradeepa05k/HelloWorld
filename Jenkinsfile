pipeline {
  agent any {
    stages {
      stage("Build") {
        steps {
          echo 'From Jenkins File'
        }
      }
      stage('Two') {
        steps {
          input('Do you want to continue?')
        }
      }
    }    
  }
}
