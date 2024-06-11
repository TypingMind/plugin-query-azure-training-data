# Query Training Data from Azure AI Search (Cognitive Search)

This plugin connects TypingMind to your training data in Azure AI Search (Cognitive Search).

## How to use

When the user ask the AI a question but the AI does not have the answer, the AI will query the training data in Azure AI Search to find the answer.

Sometimes, you need to ask the AI to specifically search from the training data if the AI does not do it automatically.

Example:

    > "search from training data for the latest refund policy"
    > "who is the founder of the company (search from training data)"

## Configuration

To use this plugin, you need to have an Azure AI Search service and an index with training data.

**[Step-by-step Guide](https://docs.typingmind.com/plugins/set-up-query-training-data-azure-ai-search)** 

To get started with Azure AI Search, follow the [official documentation](https://docs.microsoft.com/en-us/azure/search/search-what-is-azure-search).

**Note:** if you use this plugin in client side, the CORS setting must be set to "All" in the Azure AI Search service. Go to Azure Portal -> Azure AI Search -> Indexes -> CORS -> Select "All" in the "Allowed origin type" section.
