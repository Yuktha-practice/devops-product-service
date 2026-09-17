@Library('devops-shared-library') _

devopsPipeline(
    application: 'devops-product-service',
    type: 'java',
    ecrRepository: 'devops-product-service',
    awsRegion: 'eu-north-1'
)