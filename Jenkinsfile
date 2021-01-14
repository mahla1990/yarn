pipeline {
    agent any
    stages {        
        stage('Build'){
            steps {   
                echo 'running yarn...........................'
                nodejs('Node10-17') {
                    sh "yarn install"
                    sh "yarn build"
                    sh "yarn PATH"

                }
            }
        }    
    }

     
}
