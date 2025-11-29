pipeline{
    agent any
    stages{
        stage('multiple branches'){
            steps{
                echo "Hello! This is ${env.BRANCH_NAME}"
            }
        }
        stage('Text file'){
            steps{
                sh 'touch hello.txt'
            }
        }
        
    }
}
