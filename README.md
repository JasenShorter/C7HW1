Open AWS Console

Open EC2

Create New Security Group

	Go to Network & Security

	Open Security 

	Type Name

	Type Describe
	
	Go to inbound rules

	Select HTTP

	Select source IPV-4

	Add new Inbound rule for SSH

		We need ssh so we can successfully connect to the server

	Ignore the Outbound rule. Do not edit

	No Tags needed here. Skip

	Click create security Group

Create a New Instance

	Go to Instances

	Go to launch instance

	Name instance

	Don't touch app and OS

	Key Pair - Set to default

	Name Key

	Click create keypair

	Select existing security

	Go to advance details

	Copy over ec2script txt file in the user data window copied from GitHub

	Click orange launch instance button

	Click on Green i-000 number

	Click copy button on DNS to copy the URL for the instance

	Open a new internet browser

	type in http:// then paste in DNS 

	Click enter and launch the instance

Tear Down

	Go to your EC2 Instance. 

	Go to Action

	Click "Terminate Instance".



	