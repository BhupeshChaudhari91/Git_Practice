pipeline{
    agent any
    stages{
        stage("SCM Checkout") {
            steps {
               git 'https://github.com/BhupeshChaudhari91/Git_Practice.git'
            }
        }
        stage("Deploy") {
            steps {
                echo "Hello Jenkins 2"
            }
        }
    }
}
