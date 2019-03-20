node {
    stage('SCM') {
        git 'https://github.com/awsdevopsssp/HelloDevops.git'
    }
    stage('Hello World') {
        sh "./HelloDevops.sh"
    }
    stage('Hello Devops') {
        sh "./Devops.sh"
    }
    stage('Cleaning Workspace') {
        cleanWs()
    }
}
