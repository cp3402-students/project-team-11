Describe your development and deployment workflow in enough detail that anew team member or someone taking over the project
could follow to successfully develop theme updates locally, then test and deploy them to your staging and live sites. 
This should include aspectssuch as project management, version control, testing and automation. Do not provide private details like passwords.

# Deployment
The Purpose of this document is to describe development and deployment workflow in detail to successfully create, test and deploy theme updates
to staging and live site.

## Workflow
* Collaboration
  * GitHub
  * Trello
  * Discord
  
* Development
  * PHP Storm
  * VS Code

* Deployment
  * WordPress   
  * Docker
  * Duplicator plugin for WordPress for transfering database
  * FileZilla

Docker was used to create a locally hosted website to create new content and make changes. Duplicator was used to copy the database to and from the live site and locally hosted site and FileZilla to move the files. Themes are wroked on locally using docker and then when pushed to GitHub, a GitHub workflow is used to update the theme files on the website for autonomy, this method can take a while to upload. Using the builtin theme exporter in WordPress can be used for a more instant change if needed.
