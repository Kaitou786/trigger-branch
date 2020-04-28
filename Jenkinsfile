pipeline{
    agent{label 'jenkins-slave'}
    triggers{
        cron('* * * * *')
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
