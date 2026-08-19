pipeline {
    agent {
        node {
            label "linux && go1.26"
        }
    }
    stages {
        stage("Hello") {
            steps {
                echo "Hello from pipeline"
            }
        }
    }
}