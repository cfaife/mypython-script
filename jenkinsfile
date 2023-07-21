pipeline{
    agent {
        node {
            label 'docker-agent-alpine'
        }
    }
    triggers {
        pollSCM '*/5 * * * *'
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