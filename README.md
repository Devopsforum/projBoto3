# projBoto3
Boto3 automation of AWS instances using python


#once the project setup done run the below commands
'pip3 install pipenv'

'pipenv install boto3'

'pipenv install -d ipython'

#once the above steps executed without any fail run the below command.
'pipenv run ipython'

#the ipython editor will open and then run the below commands.

'import boto3 
#as we alsready install the boto3 in the above steps now we are importing that for scripting purpose.


'session = boto3.Session(profile_name='shotty')'

'ec2 = session.resource('ec2')'
'for i in ec2.instances.all()'

#the above lines of code tell that we are executing the session for the user-profile shotty which we created in our previous steps at the #time of AWS setup.
