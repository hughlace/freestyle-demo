pipeline{
    agent
    
    stages {

        stage('run.sh') {

            steps {
                sh '''
                sh run.sh
                '''
            }

        }
         stage('echo') {

            steps {
                sh '''
                echo "hello world"
                '''
            }

        }

    }

}