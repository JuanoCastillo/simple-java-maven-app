pipeline {
    /*
    agent {
        docker {
            image 'maven:3.8.1-adoptopenjdk-11' 
            args '-v /root/.m2:/root/.m2' 
        }
    }
    */
    agent any

    stages {
        stage('Build') { 
            dir("C:/Git/taller_jcastisi_BeDOs/simple-java-maven-app")
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}