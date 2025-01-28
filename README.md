# SN_GENAI_ASSIST
Make calls to ChatGPT from UI page launched from UI Action

I used [this community article](https://www.servicenow.com/community/developer-articles/chatgpt-integration-with-servicenow-latest-api-guide/ta-p/3141956)  Claude and ChatGPT to build this in a PDI.

In order to make API calls you will need to add your API token in the HTTP Method. Default POST> HTTP Request > Authorization > Value should be "Bearer {api key}"

I did not test on a funded account. Line 26 of client script of UI Page ask_genai_dialogue_page may need to have formating modified.
