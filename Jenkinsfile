pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('stage1') {
      steps {
        sh '''cd /www/blue-ocean-study

echo "you are the apple of my eye" >> test.txt
echo "chrisyu are big stupid man" >> test.txt'''
      }
    }

  }
}