# Deployment Steps for Smart Farming AI Agent

1. Login to IBM Watsonx Cloud
2. Go to Agent Lab and create a new Agent
3. Choose `llama-3-3-70b-instruct` model (Granite-compatible)
4. In the instructions box, define the assistant’s behavior for farming queries
5. ACreate a vector index under **Knowledge** and upload `Farming.docx`
6. Test queries like:
   - "Best crop to grow in August?"
   - "What is the tomato mandi price today?"
7. Preview and verify responses in English and Hindi
8. Click **Deploy Agent**
9. Go to the **API Reference** tab and copy the cURL snippet
10. Save the cURL command in `api_snippet_curl.txt`
