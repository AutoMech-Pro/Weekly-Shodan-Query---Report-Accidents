# Weekly-Shodan-Query---Report-Accidents
Explains the workflow concept: Monitoring IPs for unexpected open ports.
Lists Prerequisites: n8n, Shodan API key, etc.
Provides a Step-by-Step Guide:
Trigger: Schedule.
Data Source: Mocking data with a Code node (best for tutorials).
Looping: Using Split In Batches.
API Request: Configuring the Shodan HTTP request.
Logic: A JavaScript snippet to compare "Actual" vs "Expected" ports.
Alerting: Options for TheHive (original intent) and Slack (easier alternative).
This guide is self-contained and directly addresses the prompt.
