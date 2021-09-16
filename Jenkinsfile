@Library('pipeline-libraries@ci-libraries') _
dockerCIPipeline(
        agent: 'master',
        postmanCollectionFilename: 'TA-APIEndPointsValidation.postman_collection.json',
        env:  [ "test", "preprod" ]
    )