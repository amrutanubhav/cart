@Library('robot-shared-library') _
pipeline {
    agent any
    stages {

        stage("Performing Lint checks") {
            steps {
                script {

                    sample.info("starting","devops.com")
                }
                // sh "echo installing JSLINT"
                // sh "npm install jslint"
                // sh "ls -ltr node_modules/jslint/bin/"
                // sh "./node_modules/jslint/bin/jslint.js server.js"
                sh "echo lint checks done"
            }
        }
        stage("Downloading dependencies") {
            steps {
                sh "npm install"
            }
        }
    }
}