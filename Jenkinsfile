pipeline{

    agent any

    stages{
        stage("Mostrar version"){
            steps{
                Nombre: sh cut -d ":" -f1 release.yaml
                echo "$Nombre"
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
