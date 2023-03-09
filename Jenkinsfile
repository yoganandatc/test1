pipeline {
  agent any 
  stages {
    stage ( 'BUILD') {
      steps {
        echo "This is the build stage"
      }
    }
    stage ( 'TEST') {
      parallel {
        stage ( 'testing on chrome') {
      steps {
        echo "This is the test stage 1"
      }
        }
        stage ( 'testing on opera') {
        steps {
        echo "This is the test stage 2"
        }
        }
        stage ( 'testing on safari') {
        steps {
        echo "This is the test stage 3"
        }
        }
      }
    }
  
    stage ( 'DEPLOY') {
      steps {
        echo "This is the deploy stage"
      }
    }
  }
}
        
  
  
  
  
