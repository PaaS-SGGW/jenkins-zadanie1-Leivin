pipeline {
    agent any
    stages {
        stage('Heroku push') {
            steps {
                echo "Updating heroku master branch..."
				sh "git push heroku master"
            }
        }
    }
}
