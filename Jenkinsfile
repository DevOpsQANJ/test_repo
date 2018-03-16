properties([parameters([string(defaultValue: 'plop', description: '', name: 'param')]), pipelineTriggers([cron('H/1 * * * *')])])
timestamps {
  node {
    ansiColor('xterm') {
      stage('building'){
        echo "param = ${params.param}"
        echo 'ok2'
      }
    }
  }
}

