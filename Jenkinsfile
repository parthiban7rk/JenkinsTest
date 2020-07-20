pipeline {
    agent any 
    stages {
        stage('Compile') { 
            steps {
                bat "javac C:\\Program Files (x86)\\Jenkins\\workspace\\HelloWorldPipeline\\JenkinsTest\\HelloWorld.java"
            }
        }
        stage('Test') { 
            steps {
                bat "java C:\\Program Files (x86)\\Jenkins\\workspace\\HelloWorldPipeline\\JenkinsTest\\HelloWorld.java"
            }
        }
    }
}