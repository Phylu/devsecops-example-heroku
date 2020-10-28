environment {
  CRASHTEST_WEBHOOK = credentials('crashtest-webhook')
}

stage('Run Crashtest Security Scan') {
  steps {
    sh './start_crashtest_jenkins.sh $CRASHTEST_WEBHOOK'
 }
}