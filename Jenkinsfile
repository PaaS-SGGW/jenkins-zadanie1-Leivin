pipeline {
    agent any
    stages {
        stage('Heroku push') {
            steps {
                echo "Updating heroku...again."
				bat "heroku git:remote -a leivin-jenkins"
				bat "git push heroku master"
            }
        }
    }
}
