pipeline {
    agent { label 'slave-agent' }

    stages {
        stage('Hello') {
            steps {
                echo 'Test Jenkin'
                git 'https://github.com/mhnguyen034/todolist.git'
            }
        }
    }
}