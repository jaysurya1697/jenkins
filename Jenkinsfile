pipeline{
    agent any
    stages{
        stage('multiple branches'){
            steps{
                echo "Hello! This is ${env.BRANCH_NAME}"
            }
        }
        stage('changes in UAT'){
            steps{
                echo "There is a change in ${env.BRANCH_NAME} branch"
            }
        }
    }
}
