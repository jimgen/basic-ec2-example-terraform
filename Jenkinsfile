node {
	stage 'Checkout'
		checkout scm

	stage 'Build'
		sh '''
                       terraform init
                       terraform apply
        '''
}