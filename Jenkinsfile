pipeline {
    agent any

    parameters {
        string(name: 'param1', defaultValue: 'defaultValue1', description: 'Parameter 1')
    }

    stages {
        stage('Hello') {
            steps {
                echo "Hello ${params.param1}"
            }
        }
    }
}
