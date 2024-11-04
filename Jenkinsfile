pipeline {
    agent {
        docker {
            image 'maven:3.9.9-ibmjava'
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
