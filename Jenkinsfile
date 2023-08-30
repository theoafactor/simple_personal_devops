pipeline {
    agent any

    stages {
        stage("getting the source code"){
            steps{
                echo "Getting the source code"
            }
        }

        stage("building the image"){
            steps{
                echo "Build the image"
            }
        }

        stage("running the image container"){
            steps{
                echo "container is running ...__-"
            }
        }

        stage("host website"){
            steps{
                sh """

                    cd /var/www

                    mkdir website

                    cd website

                    git clone https://github.com/theoafactor/simple_personal_devops.git .

                    

                    """

            }
        }
    }
}