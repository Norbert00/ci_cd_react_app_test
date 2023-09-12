pipeline {
    agnet {
        docker {
            image "node:slim"
        }
    }
    stages {
        stage("Run") {
            steps {
                sh 'npx create-react-app my-app --template cra-template-my-test-app-v1'
            }
        }
    }
}