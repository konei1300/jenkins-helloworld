#Jenkinsfile
node {
    stage('Clone') {
        git 'https://github.com/konei1300/jenkins-helloworld.git'
    }
    stage('Build') {
        sh 'javac Main.java'
    }
    stage('Run') {
        sh 'java Main'
    }
}
