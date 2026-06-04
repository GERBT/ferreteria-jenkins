pipeline {
    agent any

    stages {

        stage('Instalar Dependencias') {
            steps {
                bat 'py -m pip install -r requirements.txt'
            }
        }

        stage('Ejecutar Pruebas') {
            steps {
                bat 'py -m pytest test_app.py'
            }
        }

    }
}