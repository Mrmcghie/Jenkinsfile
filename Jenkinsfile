pipeline {
  agent any
  stages {
    stage ('Build') { git clone
      steps {
      sh 'echo "HELLO WORLD"'
      sh '''
        echo "This will list current dir content from latest"
        ls -lh
        '''
      }
    }
  }
}
