pipeline {
    agent any
    
    options([parameters([string(defaultValue: 'defaultValue1', name: 'param1')])])
    
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
