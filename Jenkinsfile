pipeline {
    stages {
        stage ("Checkout") {
            steps {
                git url: "git@github.com:taco2000/greenhouse.git"
            }
        }

        stage ("Compile") {
            steps {
                sh "mvn clean compile"
            }
            
        }

        stage ("Unit Test") {
            steps {
                sh "mvn test"
            }
        }
    }
}


