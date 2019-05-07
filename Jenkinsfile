node {
    stage('first') {
        steps {        
        sh label: 'hi there', returnStdout: true, script: 'echo hello'
        }
    }
    stage('second') {
        steps {
            sh label: 'who dis', returnStdout: true, script: 'echo world'
        }
    }
}
