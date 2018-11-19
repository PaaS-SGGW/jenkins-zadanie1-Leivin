pipeline {
    agent any
    stages {
        stage('Heroku push') {
            steps {
                echo "Updating heroku...again."
				sh "git push heroku master"
            }
        }
    }
}
