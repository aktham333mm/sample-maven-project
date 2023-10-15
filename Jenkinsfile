pipeline{
 agent any
 stage('mvn build') {
  steps {
    withMaven(globalMavenSettingsConfig: '', jdk: '', maven: 'maven3', mavenSettingsConfig: '', traceability: true) {
    sh 'mvn clean install'
  }
}




}
