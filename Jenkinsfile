pipeline {
    agent any
    stages {

        stage("Performing Lint checks") {
            steps {
                sh "echo installing JSLINT"
                sh "npm install jslint"
                sh "ls -ltr node_modules/jslint/bin/"
                sh "./node_modules/jslint/bin/jslint.js catalogue/server.js"
            }
        }
        stage("Downloading dependencies") {
            steps {
                sh "npm install"
            }
        }
    }
}