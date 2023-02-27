

# Setting up Integrations with Fiberplane

# Using the CLI

- Fiberplane is a tool for managing and visualizing your microservices architecture. 

- It provides both a CLI and a REST API for setting up integrations with various tools and platforms.

- Fiberplane's CLI allows you to manage your Fiberplane account and the services that you are monitoring.

- You can also use the CLI to set up integrations with other tools and platforms that you use in your microservices architecture.

- The available integrations include tools like Datadog, New Relic, and Prometheus, as well as messaging platforms like Slack and Microsoft Teams.

## To set up an integration using Fiberplane's CLI, follow these steps.

1] Install the Fiberplane CLI by following the instructions provided in the Fiberplane documentation.

2] Log in to your Fiberplane account using the CLI by running the command `fp login`.

3] Use the `fp integrations` command to see a list of available integrations.

4] Use the `fp integrations` add command to add an integration.You will need to provide the 
   necessary configuration values for the integration you are adding.
   
   ## Example
   
   For example, if you wanted to add an integration with Datadog, you would run the command `fp integrations add datadog ` and 
   
   then provide your Datadog API key, application key, and other configuration values as prompted. Once the integration is set up, 
   
   Fiberplane will automatically start sending data to your Datadog account, and you can use Datadog to monitor and visualize your 
   
   microservices metrics alongside other data you're tracking.
