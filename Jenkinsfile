@Library("share-library-jenkins@main") _

import dickysetiadi.jenkins.Output;

pipeline {
    agent any
    stages {
            stage("hello groovy") {
                steps {
                    script {
                        output.hello("Groovy")
                    }
                }
            }
            stage("hello world") {
                steps {
                    script {
                        hello.world()
                    }
                }
            }
        }
}