pipeline {
    agent {
        label 'demoAgent'
    }

    stages {
        stage('Test') {
            steps {
                echo "202206071400"
            }
        }
    }
    
    post {
        always {
            echo 'pipeline is done!!!'
        }
    }
}
