// // An example of showing Declarative Pipeline
// pipeline {
//     agent { label 'ws' }

//     environment { 
//         ENV_URL  = "pipeline.learning.com"             // Declaring pipeline at Pipeline level
//         SSH_CREDENTIALS = credentials('SSH_CRED') 
//     }

//     triggers { pollSCM('*/1 * * * *') }

//     parameters {
//         string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
//         text(name: 'BIOGRAPHY', defaultValue: '', description: 'Enter some information about the person')
//         booleanParam(name: 'TOGGLE', defaultValue: true, description: 'Toggle this value')
//         choice(name: 'CHOICE', choices: ['One', 'Two', 'Three'], description: 'Pick something')
//         password(name: 'PASSWORD', defaultValue: 'SECRET', description: 'Enter a password')
//     }

//     tools {
//        maven 'maven-3.9.0' 
//     }
    
//     stages { 

//          stage('Example on parallel stages') {
//             parallel {
//                 stage('One') {
//                     steps {
//                         sh "env"
//                         sh "echo printing the git repo name $GIT_URL"
//                         sh "cat .git/config"
//                         sh "cat /home/centos/file.txt"
//                         sh "echo STAGE ONE"
//                         sh "sleep 1"
//                     }
//                 }
//                 stage('Two') {
//                     steps {
//                         sh "echo STAGE TWO"
//                         sh "sleep 1"
//                     }
//                 }
//                 stage('Three') {
//                     steps {
//                         sh "echo STAGE THREE"
//                         sh "sleep 1"
//                     }
//                 }
//             }
//         }

//         stage('Testing mvn commands') {
//             steps {
//                 sh "mvn --version"
//             }
//         }
        
//         stage( 'stage Name - 1') {
//             steps {
//               sh "echo I am using Pipeline Syntax help"
//             }
//         } 

//         stage( 'stage Name - 2') {
//             steps {
//               sh "echo Printing the environment variable $ENV_URL"
//             }
//         } 

//         stage( 'Final Stagee ; Needs Attention') {
//             input {
//                 message "Should we continue?"
//                 ok "Yes, we should."
//                 submitter "alice,bob"
//                 parameters {
//                     string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
//                 }
//             }
//              environment {
//                    ENV_URL = "staging.learning.com"
//               }

//             steps {
//               sh '''
//               echo I am using Pipeline syntax help
//               echo demo to show multiple lines
//               echo printing multiple lines with a single usage of sh command
//               echo Printing the environment variable $ENV_URL
//               '''
//               }
//         } 
//      }
     
     
// }


node {
    stage('Test') {
        print 'Welcome to scripted pipelines'
    }
}