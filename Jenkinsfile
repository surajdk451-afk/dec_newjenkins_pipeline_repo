pipeline{
    agent any
    
    stages{
        stage('STAGE1'){
            steps{
                echo "this is the stage 1"
                sh'''
                    sleep 5
                    echo "this is linux command" 
                '''
            }
        }    stage('build'){
            steps{
                echo "building java code"
                sh'''
                    #!/bin/bash
                    mvn clean install
                '''
                }   
    }   }   }   
            
            
}               