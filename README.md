# go-gmail

##Step 1: Turn on the Gmail API
Create a new Cloud Platform project and automatically enable the Gmail API
At end of enabling the Gmail file we will end up creating a credentials.json to your working directory. 

##Step 2: Prepare the workspace
    Set the GOPATH environment variable to your working directory.
    Get the Gmail API Go client library and OAuth2 package using the following commands:

    go get -u google.golang.org/api/gmail/v1
    go get -u golang.org/x/oauth2/google


