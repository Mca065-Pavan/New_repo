pipeline {
    agent any

    stages {

        stage('Compile Java') {
            steps {
                // Compile the Java file
                sh 'javac Hi.java'
            }
        }

        stage('Run Java') {
            steps {
                // Execute the compiled class
                // The 'sh' step returns the output to the Jenkins console
                sh 'java Hi'
            }
        }
    }
}

