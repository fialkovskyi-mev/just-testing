pipeline {
    agent { docker { image 'node:alpine' } }
    stages {
        stage('build') {
            steps {
                echo "My branch is: ${env.BRANCH_NAME}"
                sh 'npm --version'
            }
        }
    }
}
