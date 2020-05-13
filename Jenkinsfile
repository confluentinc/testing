def config = jobConfig {
    nodeLabel = defaultNodeLabel()
}

def job {
    stage('Demo') {
        echo 'Demo job using jenkins-common utilities'
        sh 'ls .'
    }
}

runJob config, job
