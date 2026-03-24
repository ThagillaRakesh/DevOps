pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git 'https://github.com/ThagillaRakesh/DevOps.git'
            }
        }

        stage('Run Leap Year Code') {
            steps {
                sh '''
                python3 leap.py << EOF
                2024
                EOF
                '''
            }
        }
    }
}
