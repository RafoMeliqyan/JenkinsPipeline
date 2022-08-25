pipeline {
    agent any
    stages {
        stage('Checkout') {
          steps {
            git "https://github.com/RafoMeliqyan/JenkinsPipeline"
          }
        }

        stage('Build') {
          steps {
            bat "mvn clean install"
          }
        }

    }

}