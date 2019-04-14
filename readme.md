# go-webloop

[![Build Status](https://travis-ci.com/brettski/go-webloop.svg?branch=master)](https://travis-ci.com/brettski/go-webloop)

Not the webhook, but the...

Add webhook to catch hooks from ActiveCampaign when for new client adds and post basic information to Slack inbound webhook

Environment varables:

* AC_ACCOUNT_NAME: ActiveCampaign account name as found in url.
* SLACK_WEBHOOK_URL: Url to post slack message to
* AC_API_KEY: Active Campaign API key
* AIRTABLE_ACCOUNT_ID: Airtable account id for API URI
* AIRTABLE_API_KEY: Airtable API key
* COUNSELOR_SLUGS: Slug value of released ticket(s)

gcp referece:  

* `gcloud app deploy`

Looking for a good way to store secrets for GCP app engine. No clean way to set environment vars