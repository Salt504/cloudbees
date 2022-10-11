pipeline { 

    agent{
        label "jenkins-jenkins-agent"
    }
    stages{
        stage("Primero grande"){
            parallel{

                stage("Primero pequeño"){

                    steps{
                        echo "JAJAJAJAJA"
                    }
                }

                stage("Segundo pequeño"){

                    steps{
                        echo "JIJIJIJIJI"
                    }
                }

                stage("Tercero pequeño"){

                    steps{
                        echo "JOJO"
                    }

                }

                stage("Cuarto pequeño"){

                    steps{
                        echo "JESJESJES"
                    }
                }
            }
        }

        stage("Segundo grande"){

            parallel{

                stage("Quinto pequeño"){

                    steps{
                        echo "Yo no me lucro"
                    }
                }

                stage("Sexto pequeño"){

                    steps{
                        echo "Yo no me lucro demasiado"
                    }
                }

                stage("Septimo pequeño"){

                    steps{
                        echo "Yo si me lucro"
                    }
                }

                stage("Octavo pequeño"){

                    steps{
                        echo "Yo no me debería lucrar"
                    }
                }

                stage("Noveno pequeño"){

                    steps{
                        echo "Dejame empaz"
                    }
                }

                stage("Décimo pequeño"){

                    steps{
                        echo "Yo no me lucro joder"
                    }
                }

                stage("Undécimo pequeño"){

                    steps{
                        echo "Yo no quiero me lucrar"
                    }
                }
            }
        }

        stage("Tercer grande"){

            steps{
                echo "DIOS QUE GUAPO LOCO"
            }
        }

        stage("Cuarto grande"){

            steps{
                echo "Funciona el jodido trigger, loquete"
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
        failure{
            echo "Argo ha fallao"
        }
    }
}