pipeline {
    agent any // Tells Jenkins it can run this job on any available processor resource
 
    stages {
        stage('Deploy to Production') {
            steps {
                echo '🚀 Commencing deployment to Nginx web directory...'
                // The heavy lifting command: copies the file into the web server folder
                sh 'cp index.html /var/www/html/index.html'
                echo '✅ Deployment completed successfully!'
            }
        }
    }
}
