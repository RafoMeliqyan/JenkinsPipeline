pipeline {
    agent any
    stages {
        stage('Checkout') {
          steps {
            bat "git clone https://github.com/RafoMeliqyan/JenkinsPipeline"
          }
        }

        stage('Build') {
          steps {
            bat "mvn package"
          }
        }

    }

}