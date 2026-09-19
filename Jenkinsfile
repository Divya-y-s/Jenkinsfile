pipeline{
    agent none
    stages{
        stage('Build'){
            agent slave1
            steps{
                sh 'ls -lrt'

            }
    

        }
    
        stage('Test'){
            agent slave2
        steps{
            echo 'This is testing'

           }
       }
    stage('Deploy'){
        steps{
            agent any
            echo 'deploying'

          }
       }
    

    }

}