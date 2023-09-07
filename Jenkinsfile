pipeline {
    agent any
    environment {
        PERSON_NAME = 'Dave' // Replace 'Dave' with the name of the person you want to greet
    }
    stages {
        stage('Greet Person') {
            steps {
                script {
                    echo "Hello, ${PERSON_NAME}!"
                }
            }
        }
    }
}
