node('master') {
    stage('Build') {
        echo 'Running Build automation'
        sh 'gradlew build --no-daemon'
        archiveArtifacts 'dist/trainSchedule.zip'
    }
}
