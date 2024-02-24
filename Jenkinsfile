pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/22011996/pipelinejenkins.git'
                sh "python3 main.py"
		sh "java Demo.java"
            }
        }
    }
}
