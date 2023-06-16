@Library("share-library-jenkins@main") _

import dickysetiadi.jenkins.output;

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
        } 
        stages {
            stage("hello world") {
                steps {
                    script {
                        hello.world()
                    }
                }
            }
        }
    }