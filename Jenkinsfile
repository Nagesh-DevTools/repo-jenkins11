@Library('my-shared-lib') _

pipeline {
    agent any
    stages {
        stage('Demo') {
            steps {
                // This calls the Groovy script in your Shared Library vars/ folder
                sayHello('Gemini') 
            }
        }
    }
}
