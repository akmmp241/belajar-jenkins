pipeline {
    agent {
        node {
            label "linux && go1.26"
        }
    }
    stages {
        stage("Build") {
            steps {
                echo "Build"
            }
        }

        stages("Test") {
            steps {
                echo "Test"
            }
        }

        stages("Deploy") {
            steps {
                echo "Deploy"
            }
        }
    }
}