pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/IcePunyisa/Test.git', branch: 'main')
      }
    }

    stage('Release') {
      steps {
        echo 'Ready to release etc.'
      }
    }

  }
}
