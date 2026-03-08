pipeline {
    agent any
    stages {
        stage ('STAGE1') {
            steps {
               sh'''sleep 5
                   echo "this is the first stage"
               '''
            }
            
    
        }
        stage ('STAGE2') {
            steps {
                sh'''
                    #!/bin/bash
                    pwd
                    ls -lrt
                    sleep 5
                    echo "this is the second stage"
                '''
            }

        }                
    }
}
