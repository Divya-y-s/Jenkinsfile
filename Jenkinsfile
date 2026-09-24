pipeline {
    agent any
    triggers {
        pollSCM('H */2 * * *')
    }

    stages {
        stage("Git Checkout") {
            steps {
                git(
                    branch: 'jenkins-branch',
                    credentialsId: 'ac782aa4-af92-41d4-8c98-182070727806',
                    url: 'https://github.com/Divya-y-s/Jenkinsfile.git'
                
                )
            }
       }
        
    }

}