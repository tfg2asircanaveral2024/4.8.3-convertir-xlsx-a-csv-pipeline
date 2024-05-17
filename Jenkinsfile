pipeline {
    agent {
        docker {
            image 'tfg2asircanaveral2024/4.8.3-convertir-xlsx-a-csv'
            args '-u 0'
        }
    }

    stages {
        stage('Convertir') {
            steps {
                sh '/script-mostrar-csv.sh'
            }
        }
    }
}