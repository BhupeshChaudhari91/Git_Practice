pipeline{
    agent any
    stages{
        stage("Build") {
            steps {
               git 'https://github.com/BhupeshChaudhari91/newmavenproject.git'
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
