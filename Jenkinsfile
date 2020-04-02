pipeline {
    agent {
        docker {
            image "ruby"
        }
    }
    stages {
        stage("Build"){
            steps{
                sh "bundle install"
            }
        }
        stage("Testes"){
            steps{
                sh "echo 'Simulando um teste automatizad'"
            }
        }
    }
}