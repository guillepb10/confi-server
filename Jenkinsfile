#!groovy

stage('Checkout Global Library') {
    node{
        label 'ecs-slave'
    }
    steps {
        sh 'git clone https://github/guillepb10/scm.git'
        load 'scm/src/main/groovy/base.groovy'
    }
}