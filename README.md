

# Setting up Integrations with Fiberplane



- Fiberplane is a tool for managing and visualizing your microservices architecture. 

- It provides both a CLI and a REST API for setting up integrations with various tools and platforms.

- Fiberplane's CLI allows you to manage your Fiberplane account and the services that you are monitoring.

- You can also use the CLI to set up integrations with other tools and platforms that you use in your microservices architecture.

- The available integrations include tools like Datadog, New Relic, and Prometheus, as well as messaging platforms like Slack and Microsoft Teams.

# Setting Up Integrations with Fiberplane CLI

## Step 1: Install the Fiberplane CLI To install the Fiberplane CLI, follow these steps: 

 1] Go to the Fiberplane documentation website. 

 2] Select your operating system and follow the installation instructions.
 
 ## Step 2: Log in to Your Fiberplane Account
 
 To log in to your Fiberplane account using the CLI, run the following command:

 ```fp login```
 
 ![Screenshot from 2023-02-28 00-32-18](https://user-images.githubusercontent.com/113115756/221657992-686dd549-b070-4206-8e7d-6945b4ea447d.png)
 
 Enter your Fiberplane email address and password when prompted.

## Step 3: View Available Integrations

To see a list of available integrations in Fiberplane, run the following command:

```fp integrations```


![Screenshot from 2023-02-28 00-33-50](https://user-images.githubusercontent.com/113115756/221658284-8bdb5092-5bf7-4bdf-b54e-e90348767e2a.png)

This will show you a list of all the integrations that Fiberplane supports.

## Step 4: Add an Integration

To add an integration, use the following command:

![Screenshot from 2023-02-28 00-35-31](https://user-images.githubusercontent.com/113115756/221658625-54250b96-840b-4a1b-aa4c-5dd80552b571.png)

Replace ```[integration-name]``` with the name of the integration you want to add (e.g., `datadog`,` newrelic`, `prometheus`, etc.).

You will then be prompted to enter the configuration values for the integration. These values will vary depending on the integration you are adding.

For example, to add an integration with Datadog, run the following command:

![Screenshot from 2023-02-28 00-37-15](https://user-images.githubusercontent.com/113115756/221658991-7015697c-61da-4ed9-bc7a-8f20f2756060.png)

You will then be prompted to enter your Datadog API key and application key.

# Setting Up Integrations with Fiberplane REST API

Fiberplane also provides a REST API that you can use to set up integrations with other tools and platforms.

## Step 1: Get Your Fiberplane API Key

To use the Fiberplane REST API, you'll need to get your Fiberplane API key. Here's how:

1] Log in to your Fiberplane account.

2] Click on your user profile icon in the top right corner of the screen.

3] Click on "API Keys".

4] Click on "Generate a New Key".

## Step 2: Make a POST Request to the Integrations Endpoint

To create an integration using the Fiberplane REST API, make a POST request to the `/integrations` endpoint with the necessary configuration values.

Here's an example request:

![Screenshot from 2023-02-28 00-41-12](https://user-images.githubusercontent.com/113115756/221659859-b2a67b6c-8d9b-4e28-b63d-8132603c49ce.png)

Replace '<your-api-key>'  with your Fiberplane API key,' <your-datadog-api-key>' with your Datadog API key, and '<your-datadog-app-key>' with your Datadog application key.


# Available Integrations

The available integrations in Fiberplane include tools like Datadog, 

New Relic, and Prometheus, as well as messaging platforms like Slack and Microsoft Teams. 

You can find more information about each integration in the Fiberplane documentation.


# Benefits of Integrating with Fiberplane

Integrating with Fiberplane can help you streamline your microservices monitoring and management 

by consolidating data from multiple tools and platforms in one place. With Fiberplane, 

you can visualize and manage your microservices architecture in conjunction with the integrated 

tool or platform, making it easier to identify issues and optimize performance.


# Conclusion

Setting up integrations with Fiberplane can help you streamline your microservices monitoring and 

management by consolidating data from multiple tools and platforms in one place.

Whether you choose to use the CLI or the REST API, Fiberplane provides a simple and easy-to-use interface 

for integrating with other tools and platforms.


`Feel free to customize this README file as needed to fit your specific use case and preferences. Good luck with your integrations!`
