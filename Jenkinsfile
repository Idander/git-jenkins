node{
    stage("1"){
        checkout([$class: 'GitSCM', branches: [[name: '*/feature*']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/Idander/git-jenkins.git']]])
        bat "dir"
    }
}
