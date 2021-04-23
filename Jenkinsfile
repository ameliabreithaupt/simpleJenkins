pipeline{
    agent any
    stages{
        stage("Check Node Version"){
            steps{
                sh "node --version"
            }
        }
        stage("Install Dependancies"){
            steps{
                sh "npm --version"
                sh "npm install"
            }
        }
        stage("Test"){
            steps{
                sh "node app.js"
            }
        }
        stage("Release the Version"){
            steps {
                echo "Released the Version"
            }
        }
    }
}
