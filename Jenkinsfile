pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            sh '''#!bin/bash
cd /www/blue-ocean-study

echo "you are the apple of my eye" >> test.txt
echo "chrisyu are big stupid man" >> test.txt'''
            dir(path: '/www/blue-ocean-study2')
          }
        }

        stage('stage2') {
          steps {
            sh '''mkdir /www/blue-ocean-study3

echo "blue-ocean-study3" >> test.txt'''
          }
        }

      }
    }

  }
}