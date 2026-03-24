pipeline {
    agent any

    stages {
         
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
