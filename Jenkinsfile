pipeline {
    agent any
    stages {
       stage('clone the app') {
            steps {
                echo 'clone to app'
                sh 'git clone https://github.com/dharmawip/hello.git'
            }
        }
        stage('Example Build') {
            steps {
                echo 'Hello World'
            }
        }
       stage('Example test') {
            steps {
                echo 'test'
            }
       }
        stage('Example Deploy') {
            steps {
                echo 'Deploying'
            }
        }
    }
}
