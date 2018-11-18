pipeline {
    agent any
    stages {
        stage('Heroku push') {
            steps {
                echo "Updating heroku master branch..."
				git push heroku master
            }
        }
    }
}
