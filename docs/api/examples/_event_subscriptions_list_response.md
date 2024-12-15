<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"event_subscriptions": [
		{
			"created_at": "2024-12-15T10:06:26Z",
			"description": "ip policy creations",
			"destinations": [
				{
					"id": "ed_2qFTBKzzPlgATs0DMfGGx57bTgb",
					"uri": "https://api.ngrok.com/event_destinations/ed_2qFTBKzzPlgATs0DMfGGx57bTgb"
				}
			],
			"id": "esb_2qFTBOUwa1ZmcIncvjei56eYbcb",
			"metadata": "{\"environment\": \"staging\"}",
			"sources": [
				{
					"type": "ip_policy_created.v0",
					"uri": "https://api.ngrok.com/event_subscriptions/esb_2qFTBOUwa1ZmcIncvjei56eYbcb/sources/ip_policy_created.v0"
				}
			],
			"uri": "https://api.ngrok.com/event_subscriptions/esb_2qFTBOUwa1ZmcIncvjei56eYbcb"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/event_subscriptions"
}
```
