pipeline{

    agent any

    stages{
        stage("Mostrar version"){
            steps{
                echo "Las version de APP_JAVA-PRO es $(`cut -d ":" -f2 release.yaml`) xd"
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
