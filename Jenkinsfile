pipeline {
    agent any
    stages {
        stage ('Compile Stage') {

            steps {
                    mvn clean compile
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
