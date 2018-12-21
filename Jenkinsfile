pipeline {
    agent {
      label "builder-aws-cdk"
    }
    stages {
      stage('cdk deploy') {
        steps {
            sh "/usr/bin/cdk deploy"
}
}
}
}
