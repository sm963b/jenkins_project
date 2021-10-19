pipeline {
    agent any

    stages {
        stage("build") {
            steps {
                //Where the script goes to run on Jenkins agent
                echo 'Building the application'
                }
            }
        stage("test") {
            steps {
                echo 'Testing the application.'
            }
        }
        stage("deploy") {
            steps {
                echo 'Deploying the application.'
            }
        }
        stage("Github return") {
            steps {
                echo "Are you returning from Github?"
                echo "I mean is Github triggering a build?"
            }
        }
        stage("Running my script") {
            steps {
                script {
                    println("I'm in the dev branch hustling.")
                }
            }
        }
    }
}
