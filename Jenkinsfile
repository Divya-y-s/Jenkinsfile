pipeline{
    agent none
    stages{
        stage('Build'){
            agent{label 'slave1'}
            steps{
                sh 'ls -lrt'

            }
    

        }
    
        stage('Test'){
            
            agent { label 'slave2'}
        steps{
            echo 'This is testing'

           }
       }
    stage('Deploy'){

        agent any
        steps{
            
            echo 'deploying'

          }
       }
    

    }

}