pipeline {
    agent {
        label 'M414301_Agent_mvs-w10-bld078'
    }

    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'main', url: 'https://github.com/Babita-27/DEMO1.git'
            }
        }

        stage('Build and Run') {
            steps {
                sh 'echo Hello, World!'
            }
        }
    }
}
