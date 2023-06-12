    pipeline {  
        agent any  
        stages {  
                stage ('Build') {  
                    steps {  
                            echo 'Running build phase...'
                            sh 'g++ test.cpp'
                            sh './a.out'
                            archiveArtifacts artifacts: 'a.out', fingerprint: true
                    }  
                }  
        }  
    }  
