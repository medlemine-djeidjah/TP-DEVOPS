pipeline {
agent any
stages {
stage('Checkout') {
steps {
// Récupère le code depuis le dépôt GitHub
git
'https://github.com/medlemine-djeidjah/TP-DEVOPS'
}
}
stage('Compile') {
steps {
script {
// Compile le code Java
sh 'javac HelloWorld.java'

}
}
}
stage('Run') {
steps {
script {
// Exécute le code Java compilé

sh 'java HelloWorld'

}
}
}
}
}
