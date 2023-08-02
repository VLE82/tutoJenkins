node {
    stage('clone') {
        git 'https://github.com/VLE82/tutoJenkins.git'
    }
    stage('build') {
        sh 'javac Main.java'
    }
    stage('run') {
        sh 'java Main'
    }
    
}
