pipeline {
    agent {
        docker {
            image 'ubuntu:jammy'
            //image 'tfg2asircanaveral2024/3.6-convertir-xlsx-a-csv:latest'
            //args '-v ./ficheros-xlsx-1:/ficheros1 -v ./ficheros-xlsx-2:/ficheros2 --env FICHEROS_XLSX="/ficheros1,/ficheros2"'
        }
    }

    stages {
        stage('Convertir') {
            steps {
                sh 'ls -lR'
                sh 'rm ficheros-xlsx-1/*'
                sh 'ls -lR'
                sh 'hostname'
                sh 'pwd'
            }
        }
    }
}