pipeline {
    agent {
        node {
            label "linux && java21"
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