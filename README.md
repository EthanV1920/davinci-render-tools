# davinci-render-tools
This is a collection of tools that are ment to help with the post production process when using Davinci Resolve 17.

## Included Tools
- Render Notify
- Render Monitor

## Render Notify

Render Notify uses the Davinci Resolves built in api in order to monitor the completion status of a render in Davinci Resolve and pushed a webhook upon completion with a json package attached with informaiton about the render.

## Render Monitor

Render Monitor uses the Davinci Resolve built in api along with the Crontab utility in Mac OS in order to detect active renders and report the status of the render by pushing webhooks to IFTTT and then populating a spreadsheet based on parsed data from a json package that is sent with the webhook push. 
