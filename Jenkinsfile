pipeline {
    agent { label 'slave-agent' }

    stages {
        stage('Hello') {
            steps {
                echo 'Test Jenkin'
                git branch: 'main', url: 'https://github.com/mhnguyen034/todolist.git'
            }
        }
    }
}