node {
    // some block
    stage('SCM') {
    git branch: 'GL_Main', credentialsId: 'git', url: 'https://github.com/rajitPranay/sample_new.git'
    }
    stage('Build') {
    sh 'mvn clean package'
    }
}
