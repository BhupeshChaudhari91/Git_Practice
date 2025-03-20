pipipeline{
    agent any
    stages{
        stage("SCM Checkout") {
            steps {
               git 'https://github.com/BhupeshChaudhari91/Git_Practice.git'
            }
        }
        stage("Compile the Code") {
            steps {
                withMaven(globalMavenSettingsConfig: '', jdk: 'JDK_HOME', maven: 'MVN_HOME', mavenSettingsConfig: '', traceability: true)
                sh 'mvn compile'
            }
        }
    }
}
