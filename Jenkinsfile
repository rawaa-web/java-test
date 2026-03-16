pipeline {
 agent any

 stages {

 stage('Checkout') {
 steps {
 git 'https://github.com/TON_USERNAME/jenkins-java-demo.git'
 }
 }

 stage('Compile') {
 steps {
 sh 'javac HelloWorld.java'
 }
 }

 stage('Run') {
 steps {
 sh 'java HelloWorld'
 }
 }

 }
}
