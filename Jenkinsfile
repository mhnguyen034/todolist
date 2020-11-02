pipeline {
    agent { label 'slave-agent-3' }

    stages {
        stage('Hello') {
            steps {
                echo 'Test Jenkin'
                git 'https://github.com/mhnguyen034/todolist.git'
            }
        }
    }
}