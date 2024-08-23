pipeline{
    agent any
    
    stages{
        stage("abcd"){

            steps{
                script{
                    git branch: 'topic1', credentialsId: 'pat', url: 'https://github.com/dia1199/example-branches.git'
                    ls
                    pwd
                    sh 'cp /var/lib/jenkins/workspace/Demoproject/index.html /var/www/html'

                }

            }
        }
    }
}
