pipeline {
       agent any
       stages {
       stage('Checkout') {
              steps {
            git 'https://github.com/miamioh-roseaw/325-module2.git'
              }
       }
       stage('Run Hello Script') {
              steps {
            sh 'python3 hello.py'
              }
       }
       }
}
