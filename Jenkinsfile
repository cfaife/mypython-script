pipeline{
    agent {
        node {
            label 'docker-python-template'
        }
    }
    
    stages {
        stage('build') {
            steps {
                echo "building...."
            }
        }
        stage('test') {
            steps {
                echo "testing...."
            }
        }
        stage('deploy') {
            steps {
                echo "deploying...."
            }
        }
    }
}