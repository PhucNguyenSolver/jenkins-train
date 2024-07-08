pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                git branch: 'main', credentialsId: 'd330ff2a-2355-4e07-a0e8-6e5b0263d950', poll: false, url: 'https://github.com/PhucNguyenSolver/jenkins-train'

                // just echo back
                sh "echo FU"
            }
        }
    }
}
