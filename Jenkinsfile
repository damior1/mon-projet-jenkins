pipeline {
    agent any 
    stages {
        stage('Compilation') {
            steps {
                echo 'Compilation du code Java en cours...'
                sh 'javac Main.java'
            }
        }
        stage('Exécution') {
            steps {
                echo 'Lancement de l application...'
                sh 'java Main'
            }
        }
    }
}
