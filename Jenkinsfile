pipeline {
    agent any
    environment {
        PERSON_NAME = 'John' // Replace 'John' with the name of the person you want to greet
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
