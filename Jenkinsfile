pipeline {
    agent any

    stages {
        stage('mail content') {
            steps {
                emailext body: 'echo README_hw5=$(cat README.md)', subject: 'README content', to: 'someonenewnew7@gmail.com'
            }
        }
    }
}

