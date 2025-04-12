pipeline {
    agent {
        node {
            label "linux && java17"
        }
    }
    stages {
        stage("Build") {
            steps {
                echo("Run Build 1")
                sleep(5)
                echo("Run Build 2")
                echo("Run Build 3")
            }
        }
        stage("Test") {
            steps {
                echo("Run Test 1")
                sleep(5)
                echo("Run Test 2")
                echo("Run Test 3")
            }
        }
        stage("Deploy") {
            steps {
                echo("Run Deploy 1")
                sleep(3)
                echo("Run Deploy 2")
                echo("Run Deploy 3")
            }
        }
    }
    post { 
        always {
            echo "Steps is running"
        }
        success {
            echo "Successfully running"
        }
        failure {
            echo "Failed running"
        }
        cleanup {
            echo "Cleaning up"
        }
    }
}