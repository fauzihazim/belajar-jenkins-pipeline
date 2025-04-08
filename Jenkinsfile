pipeline {
    agent {
        node {
            label "linux && java17"
        }
    }
    stages {
        stage("Hello") {
            steps {
                echo "run stages Hello"
                echo "Hello World"
                echo "Hello Pipeline"
            }
        }
    }
}