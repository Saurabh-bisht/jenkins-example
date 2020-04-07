node{
    stage('SCM Checkout'){
        git 'https://github.com/Saurabh-bisht/jenkins-example'
    }
    
    stage('Compile Package'){
        sh 'mvn package'
    }
}
