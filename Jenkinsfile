@Library('lib-test') _

import com.example.test

pipeline {
    options {
        buildDiscarder(logRotator(numToKeepStr: "5"))
    }
    agent any

    stages {       

        stage('Test') {
            steps {
                script {
                    def ts = new test()
                    def result = test.summ(2, 5)
                    println result
                }
		echo "wwwwgg123"
            }
        }  
    }
}
