# CBC analysis template

Template for analyses repositories. For more information see https://compbiocore-brown.slab.com/posts/data-organisation-for-analysis-repos-fdi2cddd. Folders that should be present in all such repositories are:

 * **metadata:** files such as sample manifests, YAML control files
 * **scripts:** additional scripts created for analysis of data

Optional directories are:

 * **notebooks:** notebooks for processed data
 * **results:** any files that will be provided to the collaborator

Note: This template comes with a pre-written github action workflow that will work out-of-the-box as is and automates the process of updating docker images for your analysis, pubishing these updates, and image versioning. To ensure this workflow works for your new repo, you will need to create **two** github secrets for your repo named:

* **GH_USERNAME -** this is your guthub username
* **GH_TOKEN -** this is a personal access token (if you need to make one and are unsure how, please see: ) https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) 

# CBC Project Information

```
title:
tags:
analysts:
git_repo_url:
resources_used:
summary:
project_id:
```
