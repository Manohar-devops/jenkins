pipeline {
    agent {
        label "java-agent-slave"
    }
    stages {
        stage ("Build Stage") {
            steps {
                echo "This is steps from stage under stages"
                sh hostname -i
            }
        }
        stage ("Scripted Stage") {
            steps {
                echo "This is 2nd step from 2nd stage"
                // Write custom code
                script {
                    //Define variable
                    def x = 10
                    if (x==10) {
                        println("Yes, the value is $x")
                    }
                    else
                        println("Enter the correct valu")
                }
            }
