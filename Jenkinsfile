stage('checkout'){
    node('slave1'){
        checkout scm
    }
}
stage('build'){
    node('slave1'){
        sh "${gradle4}/bin/gradle clean jar"
    }
}
