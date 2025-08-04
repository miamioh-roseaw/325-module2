pipeline {
       agent any
       stages {
       stage('Checkout') {
              steps {
            git 'https://github.com/yourusername/325-module2.git'
              }
       }
       stage('Run Hello Script') {
              steps {
            sh 'python3 hello.py'
              }
       }
       }
}
