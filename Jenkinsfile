pipeline {
    agent any
    stages {
        stage ('Compile Stage') {

            steps {
                    sh 'mvn clean install'
            }
        }
        stage ('Testing Stage') {

            steps {
                    echo 'mvn test'
            }
        }
        stage ('Install Stage') {
            steps {
                    echo 'mvn install'
            }
        }
    }
}
