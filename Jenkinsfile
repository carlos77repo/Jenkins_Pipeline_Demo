pipeline {
    agent any
    stages {
        stage ('Compile Stage') {

            steps {
                    sh 'mvn clean compile'
            }
        }
        stage ('Testing Stage') {

            steps {
                    bat 'mvn test'
            }
        }
        stage ('Install Stage') {
            steps {
                    echo 'mvn install'
            }
        }
    }
}
