pipeline {
    agent any
    stages {
        stage('Heroku push') {
            steps {
                echo "Updating heroku...again."
				bat "git remote add heroku https://git.heroku.com/leivin-jenkins.git"
				bat "git push heroku master"
            }
        }
    }
}
