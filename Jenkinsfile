pipeline {
    agent none
    stages {
        stage "This is Build Stage" {
            agent {
                label "java-agent-slave"
            }
            steps {
                echo "Build is Completed"
            }
        }
        stage "This is Code Quality Stage" {
            agent {
                label "node-agent-slave"
            }
            steps {
                echo "Code Quality is Good"
            }
        }
    }
}
