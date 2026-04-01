pipeline {
    agent any

    stages {
        stage('GitHub Clone') {
            steps {
                echo 'Connected to GitHub 🚀'
            }
        }

        stage('Docker Check') {
            steps {
                sh 'docker ps'
            }
        }

        stage('Success') {
            steps {
                echo 'Pipeline just updated from GitHub, all is connedted lol 🎉'
            }
        }
    }
}
