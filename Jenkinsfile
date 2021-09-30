pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build'
        sleep(unit: 'SECONDS', time: 30)
      }
    }

    stage('Test') {
      steps {
        echo 'This is the "Test" stage'
        pwd(tmp: true)
      }
    }

    stage('Release') {
      steps {
        echo 'This is the "Release" stage'
      }
    }

    stage('Deploy') {
      steps {
        echo 'This is the "Deploy" stage'
      }
    }

  }
}