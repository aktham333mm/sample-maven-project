pipeline{
 agent any
 stages{
 stage('mvn build') {
  steps {
    withMaven(globalMavenSettingsConfig: '', jdk: '', maven: 'maven3', mavenSettingsConfig: '', traceability: true) {
    sh 'mvn clean install'
  }
}

 }


}
}
