node {
    stage 'Checkout'

    checkout scm

    stage 'Gradle Static Analysis'
    withSonarQubeEnv {
        sh "ls"
    }
}    
