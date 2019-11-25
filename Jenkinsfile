pipeline {
    agent any
    stages {
        stage('check conflits') {
            steps {
              sh label: '', script: '''git status
cd mergingconflits
git checkout master
git pull
git merge origin/conflicts1
sh demo.sh'''
            }
        }
    }
}
