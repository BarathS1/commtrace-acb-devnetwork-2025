# commtrace-acb-devnetwork-2025
Inspiration

This project was driven by the need to strengthen security and compliance within multi-channel enterprise communications. Recognizing the potential for sensitive information to unintentionally circulate through platforms like Teams and Outlook, the goal was to create an automated solution that detects issues and quickly notifies the right people, thereby fostering trust.
 
What it does

The integration automatically captures messages from Microsoft Teams and Outlook, then leverages AI to sort and analyze them. It identifies messages containing sensitive information, promptly flags them, generates alerts in a designated Slack channel.
 
How we built it

Message Intake: Implemented Microsoft connectors to retrieve messages from Teams and Outlook.

Categorization: Used an AI text classifier to label messages .

Sensitive Content Detection: Applied a combination of custom rules and AI algorithms to identify personal, confidential, or policy-violating content.

Alerting: Established automated Slack notifications via incoming webhooks and dispatched .
 
Challenges we ran into

Security: Ensuring robust protection for both data in transit and at rest was fundamental, especially for messages flagged as sensitive.

Real-Time Cross-Platform Sync: Achieving smooth integration between Teams, Outlook, and Slack involved blending native tools and custom webhooks, since existing solutions often lack full two-way synchronization.
 
What we learned

Discovered effective techniques for AI-driven message categorization and sensitivity detection.

Mastered integrating Teams, Outlook, and Slack using APIs, Power Automate, and webhooks for streamlined automated workflows.
 
What's next for client communication monitoring

Expand the automation capabilities by adding workflows for automated reminders, calendar alerts, and escalation processes for flagged content within Slack and Outlook. Consider enhancing training and onboarding by leveraging Slack AI to deliver helpful resources and answers to frequent team questions.

 
