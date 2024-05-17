pipeline {
    agent {
        docker {
            image 'tfg2asircanaveral2024/4.8.3-convertir-xlsx-a-csv'
            // si el usuario del contenedor no fuese Root, no se tendrían permisos de escritura sobre el Workspace, y por tanto no sería posible crear los archivos CSV
            args '--user root'
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