
node{
    
    stage('clone git project') {
    
    git branch: 'main', url: 'https://github.com/akulabharath01/mahalogin.git'
}

stage('maven targets') {
    sh 'mvn install'
}
    
}
