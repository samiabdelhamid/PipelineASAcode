pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build completed'
        timeout(time: 5, unit: 'NANOSECONDS') {
          sh 'sleep 10'
        }
      }
    }
    stage('Test') {
      steps {
        echo 'Testing Running'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deplloy done'
      }
    }

  }
}