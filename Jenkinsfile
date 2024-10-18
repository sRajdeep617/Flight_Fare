pipeline {
    agent any

    stages {
        stage('Verify Python Installation') {
            steps {
                bat '"C:\Users\rajdeep\Downloads\python-3.12.4-amd64.exe" --version'   // Check Python version on Windows
                bat '"C:\Users\rajdeep\Downloads\python-3.12.4-amd64.exe" --version'      // Check pip version on Windows
            }
        }

        // stage('Install Dependencies') {
        //     steps {
        //         bat 'pip install -r requirements.txt'  // Install dependencies using pip
        //     }
        // }
    }
}