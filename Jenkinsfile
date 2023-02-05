@Library('robot-shared-library') _

nodejs("cart")



//........................ below is the actual declarative pipeline script.....................................
// pipeline {
//     agent any
//     stages {

//         stage("Performing Lint checks") {
//             steps {
//                 script {

//                     nodejs.lintchecks()
//                 }
//                 sh "echo installing JSLINT"
//                 sh "npm install jslint"
//                 sh "ls -ltr node_modules/jslint/bin/"
//                 sh "./node_modules/jslint/bin/jslint.js server.js"
//                 sh "echo lint checks done"
//             }
//         }
//         stage("Downloading dependencies") {
//             steps {
//                 sh "npm install"
//             }
//         }
//     }
// }