pipeline
	{
	agent any
	stages
		{
		stage("Git")
			{
			steps
				{
				git clone https://github.com/22011996/pipelinejenkins.git
				}
			}
		stage("Run")
			{
			steps
				{
				sh 'java Demo.java'
				}
			
			}
		stage("Run")
			{
			steps
				{
				sh 'python main.py'
				}
			}
		}
	}
