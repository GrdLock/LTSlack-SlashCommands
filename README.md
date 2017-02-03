# LTSlack-SlashCommands

**Please note that this is effectively a proof of concept for the LabTech REST API.

This script, will act as a bridge between the JSON requests of Slack and the JSON responses of the LabTech REST API.

Type /lt [computer name or computer ID] in chat and it will pull relevant information about the machine.

Type /lt client [client name] in chat and it will pull the specified client's address and phone/fax number

# Installation Instructions

1. Download the ltslack.php file and lt-config.php file.
2. Place on a LAMP web server
3. Create a new slack slash command integration at https://SLACKTEAM.slack.com/apps/A0F82E8CA-slash-commands
4. Set command to /lt (or other if you prefer)
5. Set the URL to http://www.domain.com/ltslack.php
6. Set Method to GET
7. Copy the token
8. Set a name, icon, and autocomplete text if wanted.
9. Modify the lt-config.php file with your companies values and timezone.
10. Test it in Slack!