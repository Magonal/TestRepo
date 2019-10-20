pipeline {
    agent any
    environment {
        branch = 'master'
    }
    
    stages {
        stage('checkout git') {
            steps {
                //git branch: branch, credentialsId: 'GitCredentials', url: scmUrl
                echo "checkout git"
            }
        }

        stage('build') {
            steps {
                //sh 'mvn clean package -DskipTests=true'
                echo "build"
            }
        }
    }

}
