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
                echo 'Trigger build'
            }
        }
    }
}

