@Library('lib-test') _

import example.Test

pipeline {
    options {
        buildDiscarder(logRotator(numToKeepStr: "5"))
    }
    agent any

    stages {       

        stage('Test') {
            steps {
                script {
                    def ts = new Test()
                    def result = ts.summ(2, 5)
                    println result
                }
		echo "wwwwgg123"
            }
        }  
    }
}
