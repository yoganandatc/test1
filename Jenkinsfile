pipeline {
    agent any
    stages {
            stage ('BUILD') {
                parallel {
                    stage ('Build-1'){
                step {
                    echo "this is build 1"
                }
            }
            Stage ('TEST'){
                parallel {
                    stage ('test-1'){
                        steps{
                            echo "this is test1"
                        }
                    }
                    stage ('test-2'){
                        steps{
                            echo "this is test2"
                        }
                    }
                    }stage ('test-3'){
                        steps{
                            echo "this is test3"
                        }
                    }
                }
            }
                    stage ('build-2'){
                        steps{
                            echo "this is build2"
                        }
                    }
                    stage ('build-3'){
                        steps{
                            echo "this is buiid3"
                        }
                }
            }
        }
    }
    

  
