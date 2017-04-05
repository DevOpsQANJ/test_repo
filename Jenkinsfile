properties([parameters([string(defaultValue: 'plop', description: '', name: 'param')]), pipelineTriggers([cron('H/1 * * * *')])])
node {

  stage('building'){
    echo "param = ${params.param}"
    echo 'ok2'
  }
}

