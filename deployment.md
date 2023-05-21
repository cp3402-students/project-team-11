Describe your development and deployment workflow in enough detail that anew team member or someone taking over the project
could follow to successfully develop theme updates locally, then test and deploy them to your staging and live sites. 
This should include aspectssuch as project management, version control, testing and automation. Do not provide private detailslike passwords.

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

* Deployment
  * WordPress   
  * Docker
  * Duplicator plugin for WordPress

We used Docker to create a locally hosted website to create new content and make changes. Duplicator was used to copy the database to the live site and ... to move the files. 
