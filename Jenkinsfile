pipeline {
    agent any
    environment {
        JAVA_HOME = tool name: 'JAVA_21', type: 'jdk'
        PATH = "${env.JAVA_HOME}/bin:${env.PATH}"
    }

    stages {
        
        stage('Git_clone') {
            steps {
                // Get some code from a GitHub repository
                git 'https://github.com/Prakruthigit/Webapp.git'
            }
           
        }
        
        stage('Build') {
            steps {
                 sh "java -version"
            }
        }
        
        
    }
}
    
   


