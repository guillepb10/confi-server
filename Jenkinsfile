#!groovy

stage('Checkout Global Library') {
    node{
        label 'ecs-slave'
    }

    sh 'git clone https://github/guillepb10/scm.git'
    def base = load 'scm/src/main/groovy/base.groovy'
    base.run();
}