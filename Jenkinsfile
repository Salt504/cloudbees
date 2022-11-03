pipeline{

    agent any

    stages{
        stage("Mostrar version"){
            steps{
                sh '''
                for LINEA in `cat mama.txt`
                do
                COMANDO = `cut -d ":" -f1 release.yaml`
                COMANDODOS = `cut -d ":" -f2 release.yaml`
                echo "Las versiones de $COMANDO son $COMANDO2 xd"
                done
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
