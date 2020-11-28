# zeiver

This project is about the zeiver chatbot.

## Prerequisites

The only tools you need for contribute are:

- Connection to the Webserver
- A text editor tool, Visual studio code (recommanded)
- A fttp client, FileZilla (recommanded)

## Install

To install the project, just clone it:

``` bash
$ git clone git@github.com:Xchenot/zeiver.git
```

install google cloud sdk 
https://cloud.google.com/sdk/docs/install#linux


sudo vim /etc/profile
export GOOGLE_APPLICATION_CREDENTIALS="/Users/xavie/Documents/secrets/zeiver-7bf91a919a71.json"
or
export GOOGLE_APPLICATION_CREDENTIALS="/home/pi/projects/zeiver/env/zeiver-7bf91a919a71.json"

## Testing

curl -X POST \
-H "Authorization: Bearer "$(gcloud auth application-default print-access-token) \
-H "Content-Type: application/json; charset=utf-8" \
-d @request.json \
https://dialogflow.googleapis.com/v3beta1/projects/zeiver/locations/us/agents/c7cb8806-ce62-4b90-94dc-9a5f3bbcc8fe/sessions/qnq5t:detectIntent


## Deploying

## Destroying

## Unlocking

## Bash History

## Troubleshooting