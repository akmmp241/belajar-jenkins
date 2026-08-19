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

        stage("Test") {
            steps {
                echo "Test"
            }
        }

        stage("Deploy") {
            steps {
                echo "Deploy"
            }
        }
    }

    post {
        always {
            echo "selalu jalan"
        }

        success {
            echo "jalan kalo sukses"
        }

        failure {
            echo "jalan kalo gagal"
        }

        cleanup {
            echo "selalu jalan juga"
        }
    }
}