pipeline {

agent any

stages {

stage('Build') {

steps {

bat 'javac firstfile.java'
bat 'java -version'
}

}

stage('Run') {

steps {

bat 'java firstfile'
}
}
}
}
