pipeline {
    agent any
    stages {
        stage('Heroku push') {
            steps {
                echo "Updating heroku...again."
				bat "git push heroku master"
            }
        }
    }
}
