pipeline {
    agent {
        lable "java-agent-slave"
    }
    stages {
        stage ("This is Stage1")
            steps {
                echo "Welcome to the Jenkins Pipeline"
            }
            stage ("This is Stage2")
            steps {
                echo "Welcome to the Git SCM"
            }
    }
}
