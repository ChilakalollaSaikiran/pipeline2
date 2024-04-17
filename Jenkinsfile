pipeline {
    agent any
    parameters {
        string(name:'Greeting',defaultValue:'Hello',description:'How should i greet world?')
    }
    stages {
        stage('Example') {
            steps {
                echo "${params.Greeting}welcome to jenkins world?"
            }
        }
    }
}
