pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                checkout scmGit(branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/ironcerocloudbees/multibrach-project.git']])
            }
        }
    }
}
