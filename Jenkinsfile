pipeline {
    agent any
 
    stages {
        stage('Welcome') {
            steps {
        
               echo 'First jenkinstask'
            }
        }
    }
 
    post {
        success {
            echo "Pipeline Executed Successfully"
        }
        failure {
            echo "Pipeline Execution Failed"
        }
    }
}
 
