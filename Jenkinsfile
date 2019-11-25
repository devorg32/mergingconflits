pipeline {
    agent any
    stages {
        stage('check conflits') {
            steps {
<<<<<<< HEAD

              sh label: '', script: '''git status
=======
              sh label: '', script: '''git status
              
>>>>>>> origin/conflicts1
cd mergingconflits
git checkout master
git pull
git merge origin/conflicts1
sh demo.sh'''
            }
        }
    }
}
