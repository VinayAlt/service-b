@Library('jenkins-shared-lib') _
microservicePipeline(
  serviceName    : 'service-a',
  gitUrl         : 'https://github.com/VinayAlt/service-b.git',
  gitBranch      : 'main',

  awsCredId      : 'aws-creds',
  awsRegion      : 'ap-south-1',
  accountId      : '784074784226',

  ecrRepo        : 'service-b',
  k8sPath        : 'k8s',
  k8sNamespace   : 'default',
  deploymentName : 'opentelemetry-demo-frontend',

  dockerAgent    : 'built-in',     // where Docker works
  deployAgent    : 'built-in',  // where kubectl works
  clusterName    : 'YOUR-EKS-CLUSTER-NAME' // optional: auto-kubeconfig
)
