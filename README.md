# Introduction
This is the PA to Services Method website.  It is meant to describe the method of executing PCFS service transactions and transitioning the opportunity to PCF for PAs.

# Running locally
This site uses Hugo for templating.  To run the site locally:

1. Clone this repo
1. [Install Hugo](https://gohugo.io/getting-started/installing/)
1. From the root directory of this site run `hugo server -D`
1. Open a browser and navigate to `http://localhost:1313`

# Deploying to Cloud Foundry
To deploy this site to a Cloud Foundry instance:

1. Clone this repo
1. Install the [cf cli](https://github.com/cloudfoundry/cli/releases)
1. Target and login to your Cloud Foundry instance with the cf cli
1. [Install Hugo](https://gohugo.io/getting-started/installing/)
1. From the root directory of this site run `hugo`
1. Change to the `public` directory created
1. Modify the `manifest.yml` file as needed
1. Deploy the application with the command `cf push`
1. Get the URL for the site from the output, and open it in a browser