pipeline{
    agent{label 'jenkins-slave'}
    triggers{
        pollSCM('@midnight')
    }
    stages{
        stage('sample'){
            steps{
               echo "I'll run every minute"
               sh "date"
            }
        }
    }
}
