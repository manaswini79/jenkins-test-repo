//Jenkinsfile (Declarative Pipeline)
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'echo "Welcome"'
                bat '''
                    echo "The multiline shell steps are working"
                    dir
                '''
            }
        }
    }
}
