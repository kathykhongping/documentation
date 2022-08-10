# SendGrid Connector


## Doc draft

Author: Kathy Khong 

# Introduction

The SendGrid connector to enhances your registration flow by enabling multiple capabilities for contact creation and email delivery.
With SendGrid, you will be able to:
  * Create a contact
  * Update an exisiting contact
  * Read a contact using an id 
  * Import a contact job status 
  * Create a Single Send 
  * Schedule a Single Send 

  Twilio SendGrid is a cloud-based SMTP service that provides email delivery at scale, allowing you to send email without the cost and complexity of maintaining your own email servers.

  For more information, see [Twilio SendGrid Documentation.](https://docs.sendgrid.com/) 

# Setup

## Setting up the connector
In DaVinci, add a SendGrid connection. For help, see [Adding a Connection.](https://docs.pingidentity.com/bundle/davinci/page/srw1637101394177.html) 

## Connector Configuration 

### API Key 
You must create your first API key using the [Twilio SendGrid App.](https://signup.sendgrid.com/)

# Using the connector in a flow

Once a SendGrid connector has been added you can click to configure the connector's capabilities. 

# Capabilities

Leave this section blank: it will be generated automatically


# Troubleshooting 

## Common solutions

### Error when deleting a contact
Only one of ids OR Delete all contacts should be set, not both.

### Error when scheduling a Single Send using a Single Send id
Single Send email config must have either a custom unsubscribe url OR suppression group id to schedule. In additon, the email config HTML Content  and Sender id must contain a valid value to be able to schedule the Single Send. 



### Testing capabilities

You can test each capability individually. For help, see [Testing capabilities](https://docs.google.com/document/d/1Sc9tD5tn9dl79qOWup0k3eKk5hrNVI8lZPAdm8loeiA/edit#).


# Limitations

[Optional section]

[Describe any issues or limitations.]

