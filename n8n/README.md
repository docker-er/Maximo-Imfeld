n8n

- Description

It receives data from a web form using a webhook and stores it in Google sheets and It uses an external API to enrich the stored data.

- How it works

* Webhook receives user input (name and message)
* Edit Fields formats the data
* (If) checks that the message is not empty
* HTTP Request fetches data from the external API
* Google Sheets stores all the information

- Why it is useful?

It automates data collection from a website and verifies certain factors.

Challenges

* Understanding 8n8 interface
* Understanding how data flows between nodes
* Handling data overwriting after the HTTP Request
* Correctly mapping fields for Google Sheets
