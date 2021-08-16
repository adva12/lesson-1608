properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("clone")
    {
        git branch: 'main',  url: 'https://github.com/adva12/lesson-1608.git'
    }
    stage("show files")
    {
        bat "dir"
        
    }
}
