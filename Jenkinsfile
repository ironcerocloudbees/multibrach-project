pipeline {
    agent any
    
    properties([parameters([string(defaultValue: 'defaultValue1', name: 'param1')])])
    
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
