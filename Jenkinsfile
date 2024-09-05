pipeline {
    agent any

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
    
   


