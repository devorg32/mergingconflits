pipeline {
    agent any
    stages {
        stage('check conflits') {
            steps {
              sh label: '', script: '''git clone https://github.com/cjpcloud/warrepo.git 
cd warrepo
git checkout master
git merge origin/mahesh 
sh demo.sh'''
            }
        }
    }
}
