pipeline {
    agent any

    stages {

        stage('Instalar Dependencias') {
            steps {
                bat '"C:\\Users\\Usuario\\AppData\\Local\\Programs\\Python\\Python314\\python.exe" -m pip install -r requirements.txt'
            }
        }

        stage('Ejecutar Pruebas') {
            steps {
                bat '"C:\\Users\\Usuario\\AppData\\Local\\Programs\\Python\\Python314\\python.exe" -m pytest test_app.py'
            }
        }

    }
}