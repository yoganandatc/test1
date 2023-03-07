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
      steps {
        echo "This is the test stage 1"
      }
        steps {
        echo "This is the test stage 2"
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
        
  
  
  
  
