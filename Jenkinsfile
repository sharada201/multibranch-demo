pipeline{
    agent any
    stages{
        stage("Deploy Dev"){
            when {
                branch 'development'
            }
            steps{
                echo "Deploying to Dev environment"
                echo "Deployment on dev done"
            }
        }
        stage("Deploy Staging"){
            when {
                branch 'staging'
            }
            steps{
                echo "Deploying to Staging environment"
                echo "Deployment on staging done"
            }
        }

        stage("Deploy Prod"){
            when {
                branch 'master'
            }
            steps{
                echo "Deploying to Prod environment"
                echo "Deployment on prod done"
            }
        }
    }
}
