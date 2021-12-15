pipeline {
    agent any
    stages {
        stage('Imprimir mensaje de bienvenida') {
            steps {
                echo 'Hola Mundo :D'
            }
        }
        stage('Creando nuevo archivo') {
            steps {
                sh 'touch nuevoarchivo.txt'
            }
        }
        stage('abriendo navegador'){
            steps{
                firefox https://www.youtube.com/watch?v=ml-npkj_LxM&ab_channel=Porta 
           }
        }
    }
}
