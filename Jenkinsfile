pipeline{
    agent any
    
    environment {
        App_Name = "appName"
        ENV = "Production"
        PORT = "8080"
    }
    stages{
        stage('Print'){ 
            steps{
                echo "App Name: ${env.App_Name}"
                echo "Environment: ${env.ENV}"
                echo "Port: ${env.PORT}"
            }



        }

    }
}