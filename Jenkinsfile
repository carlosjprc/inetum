//Pipeline Declarativo
pipeline {
    // Ejecutar desde cualquier agente (nodo) disponible
    agent any 
  
    // Fases
    stages {
        stage("Build") {
            // Pasos de la fase
            steps {
                echo "Building artifact";
            }
        }
        stage("Testing") {
            // Pasos de la fase
            steps {
                echo "Tests Unitarios";
                echo "Tests Integracion";
                echo "Tests Aceptacion";
            }
        }
        stage("Deploy") {
            // Pasos de la fase
            steps {
                echo "Deploying artifact";
            }
        }
    }
}
