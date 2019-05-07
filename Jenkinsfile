node {
    stage('first') {
        sh label: 'hi there', returnStdout: true, script: 'echo hello'
    }
    stage('second') {
        sh label: 'who dis', returnStdout: true, script: 'echo world'
    }
    stage('third') {
        def stringsToEcho = ["a", "b", "c", "d"]
        for (s in stringsToEcho) {
            echo ${s}
        }
    }
}
