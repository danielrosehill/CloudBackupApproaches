## Trello export approach

**Updated:** 12/05/20
**Type:** On-demand
**Output format:** Single JSON file

Trello's user data export approach is fairly rudimentary.

To access it, navigate into the account settings page:

![](/images/trello2.png)

Scroll down towards the bottom of the screen and you will find a menu item called 'Personal Data Export'

![](/images/trello1.png)

Clicking that button will output a single block of JSON right in the browser:

![](/images/trello3.png)

If you inspect the JSON you will notice that there are some paths to user images in S3 buckets:

![](/images/trello4.png)

Unfortunately these are not publicly accessible:

![](/images/trello5.png)
