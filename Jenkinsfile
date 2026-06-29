pipeline {

    agent any


    stages {


        stage('Checkout') {

            steps {

                echo "Building branch: ${env.BRANCH_NAME}"

            }

        }


        stage('Build') {

            steps {

                echo "Running build for ${env.BRANCH_NAME}"

            }

        }


        stage('Test') {

            steps {

                echo "Testing ${env.BRANCH_NAME}"

            }

        }


    }

}
