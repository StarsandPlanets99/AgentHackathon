# Bring autonomous agents into the enterprise

In this hackathon, you explore how to use autonomous agents in the enterprise to transform processes and drive innovation. By examining real-world use cases and the key components of Copilot Studio, you can gain insights into the transformative power of AI-driven agents. As a result, you can apply their capabilities in your organization to bring innovation and efficiency



# Key components of Copilot Studio
Before you create autonomous agents, it's important that you understand Copilot Studio foundational elements to harness its capabilities. The following table includes the key components of Copilot Studio.


| Component    | Key Capabilities                                                                 |
|--------------|----------------------------------------------------------------------------------|
| **Knowledge** | Allows the agent to use predefined documents, FAQs, or external data sources to provide instructions for the agent to respond.   |
| **Topics**    | Manages the conversation flows by defining intents, triggers, and responses for user queries.         |
| **Actions**   | Defines what the agent can do, such as triggering an action or workflow, calling an API, sending an email, or integrating with external systems to trigger an external workflow.  |
| **Triggers**  | Event-based starting points that initiate an automated flow, which help define specific conditions that activate specific actions. |
| **Activity**  | Tracks and logs interactions, providing visibility into user engagement with the agent.  |
| **Analytics** | Provides insights and performance metrics on agent usage, effectiveness, and user interactions.  |
| **Channels**  | Configures deployment options, which allows the agent to be accessible on various platforms like Microsoft Teams or internal and external websites. |

# Lab Overview

In this lab, you use Copilot Studio to create an agent that helps HR with onboarding a new employee. This exercise requires you to create a Microsoft Dataverse table. 

## Scenario
- Provide general information and answer queries that relate to employee onboarding.
- Submit a request automatically to onboard a new employee through the system.
- Send an onboarding request approval email automatically to the hiring manager that includes tasks, such as:
  - Procuring a laptop
  - Setting up an email account
  - Other onboarding essentials
- Analyze the response for approval after the hiring manager responds to the email. Then, based on the response, take action to:
  - Send an email to the IT/procurement team to procure a laptop and set up their access.
- Wait for the IT/procurement team to confirm procurement and then email the new employee with onboarding instructions.
