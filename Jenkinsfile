pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Git Clone') {
            steps {
                echo 'Cloning  :)'
                git branch: 'main', credentialsId: 'MyNodeJsApp', url: 'https://github.com/akramLh005/JenkinsRepo.git'
            }
        }
    
        
    }
}
