pipeline {
    agent any
    stages {
        stage('Setup') {
            steps {
                script {
                    sh 'chmod +x mvnw' // Ce code fonctionne uniquement sur des agents Unix/Linux.
                }
            }
        }
        // Ajoute tes autres stages ici
    }
}
