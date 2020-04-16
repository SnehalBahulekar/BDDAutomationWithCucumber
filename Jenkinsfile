pipeline {
    agent any
    tools{
maven 'maven 3'
jdk 'java 8'
}
    stages{
    stage ("Compile")
    {
    steps{
    sh "mvn -version"
    sh "mvn clean install"
    }
    }
    }
}
