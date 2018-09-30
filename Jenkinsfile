node{
    stage('SCM checkout'){
        git 'https://github.com/imran2191/simple-java-maven-app.git'
    }
    stage('compile package'){
        sh 'mvn package'
    }
}
