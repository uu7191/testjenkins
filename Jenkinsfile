// Declarative //
pipeline {
agent { dockerfile true }
stages {
stage('Test') {
steps {
sh 'node --version'
sh 'svn --version'
sh 'df -h'
sh 'traceroute www.google.com'
sh 'docker images'  
}
}
}
}
// Script //
