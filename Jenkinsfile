pipeline {
    agent any

    stages {
        stage('Verify Python Installation') {
            steps {
                bat 'python --version'   // Check Python version on Windows
                bat 'pip --version'      // Check pip version on Windows
            }
        }

        // stage('Install Dependencies') {
        //     steps {
        //         bat 'pip install -r requirements.txt'  // Install dependencies using pip
        //     }
        // }
    }
}