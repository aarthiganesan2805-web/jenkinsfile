pipeline {
agent any
stages { 
 
        stage('Clone Code') { 
            steps { 
                git branch: 'main', url:'https://github.com/aarthiganesan2805-web/jenkinsfile/blob/main/jenkinsfile'
            } 
        } 
 
        stage('Compile Code') { 
            steps { 
                bat 'demo.java' 
            } 
        } 
 
        stage('Run Code') { 
            steps { 
                bat 'demo'
}
}
}
}
