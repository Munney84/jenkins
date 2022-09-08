pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        sh 'echo "HELLO CLARENCE"'
        sh '''
        echo "This is the second branch, b2"
        ls -lh
        uname -a
        '''
      }
    }
    stage ('Test') {
      steps {
        sh 'echo "HELLO TEST"'
        sh '''
        echo "This is a different test"
        pwd
        '''
      }
    }
  }
}
