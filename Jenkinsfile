pipeline{

    agent any

    stages{
        stage("Mostrar version"){
            steps{
                sh '''
                COMANDO = `cut -d ":" -f1 release.yaml`
                
                echo "$COMANDO"
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
