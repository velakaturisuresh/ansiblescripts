pipeline {
    agent any
    stages {
        stage('checkout') {
            steps {
           cleanWs()

            sh '''
              git clone https://github.com/velakaturisuresh/mavenproject.git
              pwd
              cd mavenproject/my_application
              mvn clean install
             '''
                
            }
        }
    }
}
