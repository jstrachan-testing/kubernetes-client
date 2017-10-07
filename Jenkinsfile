node {
    stage('Release') { 
        git 'https://github.com/jstrachan-testing/kubernetes-client.git'

    }

    stage('UpdateBot') {
        // now lets make pull requests on downstream projects
        ansiColor('xterm') {
          updateBotPush
        }
        echo "awesome eh?"
    }
}
    
