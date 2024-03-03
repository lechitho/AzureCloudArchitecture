# Azure Cloud Architecture

# Table of Contents
* [Azure Background Task - Azure function vs Azure WebJobs](#azure-background-tasks)
* [Azure Storage - Azure Cache for Redis vs Table Storage](#azure-storage)
## Azure Background Task
<details>
    <summary><b>Azure function vs Azure WebJobs</b></summary>
    ❔ <b>What are Azure Functions?</b><br/>
    - Azure Functions is a serverless compute service.<br/><br/>
    ✅<b>When to use?</b><br/>
    - For small, event-driven tasks.<br/>
    - For integrating with other Azure services.<br/>
    - When you need to run a piece of code in response to various events like HTTP requests, queue triggers, etc.<br/><br/>
    👍<b>Features offered:</b><br/>
    - Provides automatic scaling.<br/>
    - Easy integration with other Azure services.<br/>
    - Supports multiple programming languages.<br/>
    - Charges based on consumption (pay-per-use billing model).<br/><br/>
    🚫<b>Not recommended for:</b><br/>
    - Long-running processes.<br/>
    - Applications requiring a dedicated hosting environment.<br/><br/>
    Azure Functions is well-suited for microservices architecture and scenarios where you need agility and fast deployments.<br/><br/>
    ❔ <b>What are Azure WebJobs?</b><br/>
    - A feature of Azure App Service used for background processing.<br/><br/>
    ✅<b>When to use?</b><br/>
    - For tasks that run in response to a trigger like a queue message.<br/>
    - For continuous processing in the background.<br/>
    - For tasks that need to run on a schedule.<br/><br/>
    👍<b>Features offered:</b><br/>
    - Can run continuously or on a schedule.<br/>
    - Integrates well with Azure App Services.<br/>
    - Supports multiple programming languages.<br/>
    - Can leverage the capabilities of Azure App Service like logging, settings, etc.<br/><br/>
    🚫<b>Not suitable for:</b><br/>
    - Serverless scenarios where you don’t want to manage infrastructure.<br/>
    - Event-driven tasks that require instant scalability.<br/><br/>
    Azure WebJobs fits well in scenarios where you have an existing App Service and need to perform background tasks related to your web application.<br/><br/>
    ✅Azure Functions is more about quick, serverless computing for event-driven tasks, while Azure WebJobs is better for continuous background tasks in an App Service environment.<br/><br/>


[⬆ Back to top](#table-of-contents)
</details>

## Azure Storage
<details>
    <summary><b>Azure Cache for Redis vs Azure Table Storage</b></summary>

[⬆ Back to top](#table-of-contents)
</details>