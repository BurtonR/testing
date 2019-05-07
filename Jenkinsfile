node {
    stage('first') {
        sh label: 'hi there', returnStdout: true, script: 'echo hello'
    }
    stage('second') {
        sh label: 'who dis', returnStdout: true, script: 'echo world'
    }
    stage('third') {
        def stringsToEcho = ["BurtonR.Thing1.Website.nuspec", "BurtonR.Thing2.API.nuspec", "BurtonR.Thing3.API2.nuspec", "BurtonR.Thing4.Database.nuspec"]
        for (s in stringsToEcho) {
            sh label: 'repeat', returnStdout: true, script: "echo ${s}"
        }
    }
}
