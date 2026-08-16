pipeline {
    agent {
        label "java-agent-slave"
    }
    stages {
        stage ("This is Stage1") {
            steps {
                echo "Welcome to Jenkins Pipeline"
            }
        }
        stage ("This is Stage2") {
            steps {
                echo "Welcome to Git SCM"
            }
        }
    }
}
