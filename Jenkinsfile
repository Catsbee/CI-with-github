pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                virtualenv venv --distribute
                . venv/bin/activate 
                pip install -r requirements.txt
            }
        }
    }
}
