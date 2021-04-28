# SubRevisionHistory

This repository contains an app (App.html) that queries a Rally Subscription object for revisions made between two dates.  

For large subscriptions, the initial model loads may take some time, during which the Get Revisions button is disabled.  Once the button is enabled, select a start and end date and click the button to load the data.  

Again for large subscriptions, the initial revisions query may time out, and no data will be returned.  If this happens, simply click the Get Revisions button again, and the request will likely succeed because enough data has been cached that the request will not time out.

https://github.com/nmusaelian-rally/revisions

https://github.com/wrackzone/rally-revision-history-example

https://github.com/RallyTechServices/portfolio-predictability-productivity

##### NOTE: These apps are provided in an AS-IS state and should be validated by the users planning to implement them in a production environment.  These apps are not supported by the Rally Support team.  If you find an issue with the app, please report the issue via GitHub repositiory by creating a new issue.  
