pipeline{
    agent any
	stages{
	    stage('Deploying sample application to EKS cluster') {
              steps{
                 script{
                    sh 'kubectl apply -f app.yaml -n default'
                }
            }
    }
}
