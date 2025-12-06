pipeline {
    parameters{
        booleanParam(name: 'autoApprove',defaultValue: false, description: 'Automatically run apply after geerating plan?')
    }
    environment {
        aws_access_key_id = credentials('access_key_id')
        aws_secret_key = credentials('secret_key')
    }
    agent {label 'master'}
}