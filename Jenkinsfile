pipeline {
    agent any

    stages {
        stage('Building image') {
            steps {
                echo 'Building..'
               docker build . -t basicimage:latest
            }
        }
    }
}
