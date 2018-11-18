pipeline {
    agent any
    stages {
        stage('Heroku push') {
            steps {
                echo "Updating heroku..."
				sh "git push heroku master"
            }
        }
    }
}
