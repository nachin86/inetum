
pipeline{
    
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building artifact"
            }
        }
         stage('Testing') {
            steps {
                echo "Tests unitarios"
                echo "Tests integración"
                echo "Tests aceptación"
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploy"
            }
        }
    }
    
}
