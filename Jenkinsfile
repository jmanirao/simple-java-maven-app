pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
                echo 'building the application ...'
            }
        }
         stage('Test') { 
            steps {
                echo 'building the application ...'
            }
        }
        stage('Deploy') { 
            steps {
                echo 'building the application ...'
            }
        }
    }
}
