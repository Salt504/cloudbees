pipeline{

    agent any

    stages{
        stage("Mostrar version"){
            steps{
                sh 'echo "Las version de APP_JAVA-PRO es $( grep "APP_JAVA-PRO" release.yaml | cut -d ":" -f2 ) xd" '
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
