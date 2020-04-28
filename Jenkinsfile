pipeline{
    agent{label 'jenkins-slave'}
    triggers{
        pollSCM('* * * * *')
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
