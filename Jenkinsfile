pipeline {
agent any
stages {
stage('Checkout') {
steps {
// Récupère le code depuis le dépôt GitHub
git
'https://github.com/yourusername/yourrepository.git'
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
