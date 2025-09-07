pipeline{
    agent{
        docker { image 'nod:16-alpine'}
    }
    stage('Test'){
        steps{
            sh 'node --version'
        }
    }
}