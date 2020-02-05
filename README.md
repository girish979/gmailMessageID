# Get Message Id
#### Google Script to fetch MessageId of gmail message

## Deployment
- Go to https://script.google.com/create and Create a new Project script from below
- Replace the content of New Project `code.gs`  with the code from repositoy
- Go to View & select `manifest file`
- Replace the content of New Project `code.gs`  with the code from repositoy
- Go to publish->deploy form manifest
- Install Addon after creating or manually using below steps
  - copy GetID
  - Go to gmail settings->addons->enable developer api
  - paste getID
  - refresh Gmail

## Reference
- https://developers.google.com/apps-script/reference/gmail/gmail-draft
- https://developers.google.com/apps-script/reference/gmail/gmail-draft#getMessageId()
- https://developers.google.com/apps-script/reference/gmail/gmail-message#getId()
