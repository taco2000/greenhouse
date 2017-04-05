pipeline {
    stages {
        stage "Checkout" {
            git url: "git@github.com:taco2000/greenhouse.git"
        }

        stage "Compile" {
            sh "mvn clean compile"
        }

        stage "Unit Test" {
            sh "mvn test"
        }
    }
}


