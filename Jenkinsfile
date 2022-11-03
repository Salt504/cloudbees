pipeline{

    agent any

    stages{
        stage("Mostrar version"){
            steps{
                sh '''
                COMANDO = `cut -d ":" -f1 release.yaml`
                COMANDO2 = `cut -d ":" -f2 release.yaml`
                echo "Las versiones de $COMANDO son $COMANDO2 xd"
                '''
            }
        }
    }

    post{
        always{
            echo "Ziempre tt"
        }
        success{
            echo "Funsiona to"
        }
    }
}
