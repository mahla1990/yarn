pipeline {

    agent any
  
    
    stages {        
        stage('Build'){
            steps {   
                nodejs(Node10-17){
                    sh "yarn install"
                    sh "yarn build"
                    sh "yarn PATH"
                }
            }
        }    
    }

     
}
