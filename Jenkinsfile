pipeline {
    agent none
    stages {
        stage ("Build Stage") {
            agent {
                label "java-agent-slave"
            }
            steps {
                echo "Building my application"
            }
        }
        stage ("Code Quality Stage") {
            agent {
                label "node-agent-slave"
            }
            steps {
                echo "Sonar completed, SRC looks good"

            }
        }
    }
}
