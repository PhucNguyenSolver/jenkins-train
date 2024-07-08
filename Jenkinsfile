pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                git 'https://github.com/PhucNguyenSolver/jenkins-train.git'

                // just echo back
                sh "echo FU"
            }
        }
    }
}
