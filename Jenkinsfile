pipeline{

agent {

	label{
			label "built-in"
			customWorkspace "/data/project"
	}
}

stages {

	stage('demo')

	{
		steps {
				echo "This is master branch"
				sh "mkdir test"
			}
	}


}
}
