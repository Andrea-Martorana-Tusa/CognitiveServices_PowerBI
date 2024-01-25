# CognitiveServices_PowerBI

In this repository you find out the files and material related to my session "Playing with Cognitive Services and Power BI".
You can reuse it for testing on your own.

NB!:The Power BI files need a Premium or Premium Per User capacity to run. You can open them, but need to reconnect to your account with a Premium capacity.

The files 
- Script function for image caption no Premium.txt
- Script function for image tag no Premium.txt
- Script function for language services no Premium v2.txt
- Script function for language services no Premium v3.txt

contain the M code used to call the services without having a Premium capacity. But a subscription to the Azure AI Services is needed to call the services. More details in the attached pdf presentation.

------------------------------------------------------------------
Follow the Microsoft tutorial: Extract Key phrases from text stored in Power BI. https://learn.microsoft.com/en-us/azure/ai-services/language-service/key-phrase-extraction/tutorials/integrate-power-bi

For Text Analytics: check out the dismission of the current API version (v2) and the adoption of the new format (v3). More info here:
https://learn.microsoft.com/en-us/azure/ai-services/language-service/concepts/migrate-language-service-latest
https://learn.microsoft.com/en-us/rest/api/language/text-analysis-runtime/analyze-text?view=rest-language-2023-04-01&tabs=HTTP

