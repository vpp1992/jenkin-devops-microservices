/* groovylint-disable DuplicateStringLiteral */
//SCRIPTED
//declartive
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build'

            }
        }

        stage('Test') {
            steps {
                echo 'Test'
            }
        }

        stage('Integration Test') {
            steps {
                echo 'Integration Test'
            }
        }

        post
        {
            always{
                echo 'i am awesome .i run always'
            }

            success{

                echo 'i run when you are succesfuly'
            }

            failure{
                echo 'i run when i am failure'
            }
        }
    }
}
