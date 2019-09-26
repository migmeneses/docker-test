pipeline {
    agent { dockerfile true }
    stages {
        stage('Build') {
            docker { image 'migmeneses/nodedj-webapp'}
        }
    }
}
