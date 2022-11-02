pipeline{
    
    agent any

    stages{
        stage("Mostrar version"){
            steps{
                Nombre: cut '-d ":" -f1 release.yaml'
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
