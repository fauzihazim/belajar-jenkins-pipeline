pipeline {
    agent {
        node {
            label "linux && java17"
        }
    }
    stages {
        stage("Hello") {
            steps {
                always {
                    echo "Steps is running"
                }
                success {
                    echo "Successfully running"
                }
                failed {
                    echo "Failed running"
                }
                cleanup {
                    echo "Cleaning up"
                }
            }
        }
    }
}