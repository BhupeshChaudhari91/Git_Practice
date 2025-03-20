pipeline{
    agent any
    stages{
        stage("SCM Checkout") {
            steps {
               git 'https://github.com/BhupeshChaudhari91/newmavenproject.git'
            }
        }
        stage("Deploy") {
            steps {
                echo "Hello Jenkins 2"
            }
        }
    }
}
