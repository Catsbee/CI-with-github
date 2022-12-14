pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                python -m pip install --upgrade pip
                pip install -r requirements.txt
            }
        }
    }
}
