    pipeline {  
        agent any  
        stages {  
                stage ('Build') {  
                    steps {  
                            echo 'Running build phase...'
                            g++ test.cpp
                            ./a.out
                    }  
                }  
        }  
    }  
