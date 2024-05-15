pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                // Clone the repository
                git url: 'https://github.com/conqdat/test-jenkin.git', branch: 'main'
            }
        }
    }
}
