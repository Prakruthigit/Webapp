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
                 sh '''export M2_HOME=\'/opt/maven\'
                       export PATH="$M2_HOME/bin:$PATH"
                        mvn clean package'''
            }
        }
        
        
    }
}
    
   


