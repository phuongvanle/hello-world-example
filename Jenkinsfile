node(docker) {
checkout scm
stage('build') {
withMaven(jdk: 'Default Java', maven: 'Default Maven') {
sh 'mvn clean install'
}
}
}
