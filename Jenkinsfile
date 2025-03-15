pipeline{
    agent any
    stages{
        stage("Build") {
            steps {
               echo "Hello Jenkins 1"
            }
        }
        stage("Test") {
            steps {
                sleep 10
            }
        }
        stage("Deploy") {
            steps {
                echo "Hello Jenkins 2"
            }
        }
    }
}
