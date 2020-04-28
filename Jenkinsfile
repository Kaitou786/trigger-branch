pipeline{
    agent{label 'jenkins-slave'}
    triggers{
        pollSCM(
            scmpoll_spec: '@midnight', 
            ignorePostCommitHooks: true
        )
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
