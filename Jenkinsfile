//  An example of showing Declarative Pipeline
pipeline {
     agent any 
     stages { 
        
        stage( 'stage Name - 1') {
            steps {
              sh "echo I am using Pipeline Syntax help"
            }
        } 

        stage( 'stage Name - 2') {
            steps {
              sh "echo I am executing stage-2"
            }
        } 

        stage( 'stage Name - 3') {
            steps {
              sh '''
              echo I am using Pipeline syntax help
              echo demo to show multiple lines
              echo printing multiple lines with a single usage of sh command
              '''
            }
        } 
     }
     
     
}