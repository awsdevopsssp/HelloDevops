node {
    stage('SCM') {
        git 'https://github.com/awsdevopsssp/HelloDevops.git'
    }
    stage('Run Script') {
        sh "./HelloDevops.sh"
    }
    stage('Cleaning Workspace') {
        cleanWs()
    }
}
