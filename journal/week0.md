# Getting the AWS CLI Working
    We'll be using the AWS CLI often in this bootcamp, so we'll proceed to installing this account.

# Install AWS CLI
    We are going to install the AWS CLI when our Gitpod enviroment lanuches.
    We are are going to set AWS CLI to use partial autoprompt mode to make it easier to debug CLI commands.
    The bash commands we are using are the same as the [AWS CLI Install Instructions]https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html
    Update our .gitpod.yml to include the following task.



# We'll also run these commands indivually to perform the install manually

# Create a new User and Generate AWS Credentials
    Go to  IAM Users Console, create a new user
    Enable console access for the user
    Create a new Admin Group and apply AdministratorAccess
    Create the user and go find and click into the user
    Click on Security Credentials and Create Access Key
    Choose AWS CLI Access
    Download the CSV with the credentials