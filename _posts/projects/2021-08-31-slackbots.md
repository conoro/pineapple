---
layout: project
permalink: /:title/
category: projects

meta:
  keywords: "Tines, Slack, Slackbot"

project:
  title: "Slack Interactive Bot Example"
  type: "Chatbots"
  url: "https://snowy-pond-6977.tines.io/stories/158/diagram"
  logo: "/assets/images/projects/slackbots/logo.png"
  tech: "Slack, Tines"

agency:
  title: "Tines CS"
  url: "https://snowy-pond-6977.tines.io/stories/158/diagram"
  year: "2021"

images:
  - image:
    url: "/assets/images/projects/slackbots/slackbot.png"
    alt: "Slackbot Story"
  - image:
    url: "/assets/images/projects/slackbots/Slack_Interactive_Bot_Example_Tines.gif"
    alt: "Video highlight"
  - image:
    url: "/assets/images/projects/slackbots/slackbot2.png"
    alt: "Form Input"
---
<p>Demo Story for handling Slack Interactive Responses

To test this Story, either Run the Agent called "Run to kick off test", or submit a form.
This Jira ticket can be used for testing: https://tinesio.atlassian.net/browse/DEMO-2558


When enabling a Slack App to allow Interactive Content, a single Webhook URL must be provided. This webhook will receive all interactive responses related to this Slack App. 


This story will take a given email address, and send that user a custom message with the option to confirm or deny that action.
If the user denies the action, then a Jira ticket will be updated noting this response.
If a user confirms the action, they will be presented with a modal view allowing them to add some extra context about the action taken. Once submitted, the Jira ticket will be updated with the additional information. If the user closes this dialog before submitting a response, the Jira ticket will be updated to include that detail.

After either submitting a response, or denying the activity, the original Slack message will be overwritten with a message confirming the response and providing the Incident ID.</p>
