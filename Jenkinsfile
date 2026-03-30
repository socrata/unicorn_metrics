@Library('socrata-pipeline-library@sarahs/build-gem-every-time') _

commonPipeline(
    jobName: 'unicorn_metrics',
    languageOptions: [
        ruby: [
            version: '2.3.1',
        ],
    ],
    projects: [
        [
            name: 'unicorn_metrics',
            language: 'ruby',
            paths: [
                buildContext: '.',
                versionFile: 'VERSION',
            ],
            type: 'library',
        ]
    ],
    teamsChannelWebhookId: 'WORKFLOW_EGRESS_AUTOMATION',
)
