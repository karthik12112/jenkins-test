pipeline {
    agent any
    environment {
        version="2.0"
        name="test"
    }
    stages {
        stage('Build Master') {
            when{
              branch 'master'
            }
            steps {
                echo "hello "
            }
        }
        stage('Build Dev') {
            when{
              branch 'dev'
            }
            steps {
                echo "hello world"
            }
        }
    }
}
