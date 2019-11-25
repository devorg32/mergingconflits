pipeline {
    agent any
    stages {
        stage('check conflits') {
            steps {
              sh label: '', script: '''git clone https://github.com/devorg32/mergingconflits.git
cd mergingconflits
git checkout master
git merge origin/conflicts1
sh demo.sh'''
            }
        }
    }
}
