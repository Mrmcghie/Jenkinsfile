pipeline {
  agent any
  stages {
    stage ('Build') { 
      steps {
      sh 'echo "HELLO WORLD" '
      sh 'echo "Hello Maryland" '
      sh '''
      echo "This will list current dir content from latest"
        ls -lh
        '''
      }
    }
  }
}
