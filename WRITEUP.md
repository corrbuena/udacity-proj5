# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

Cost: 
Given the specifications of the project, the cost for the Azure VM is around $3.74 per month assuming that is it up 24/7. While the web app, is in free tier so it will not cost anything. 

Scalability:
The VM setup can accommodate manual scaling and custom complex setups while in the web app, there is no scaling in the free tier but it can easily be upgraded. 

Availability:
Using the VM, the application will be accessible 24/7 with a dedicated compute. While for the web app, it is limited to 60 CPU minutes/day. Another thing to consider is the VM setup requires manual setup for uptime, backups and monitoring while for the web app, availability is built-in. 

Workflow:
VM setup allows for full control but you would have to setup manually. It requires setting up SSH to deploy. While for the web app, you can simply deploy using Github. 

As a new developer, I would choose to deploy the app using the app service because it is ideal for begginners. It removes the complications arising from deploying and setting up infrastructures as well as managing it. Through this, in a few clicks, you can already deploy your app and see it live in minutes. It is also cost effective for beginners like me because there are free tiers that can be used ideal for learning and small projects like this. Even though there is no scaling available unlike the VM setup, this can easily be done by upgrading. Thus, the pros of using the VM for this project is outweighed by using a web app. Although, if the project becomes complex that it will require OS-level configurations and we need persistent compute with no timeouts, then it would be best to reconsider. 

### Assess app changes that would change your decision.

For me to change my decision, the complexity of the deployed application should be significant that it would require custom infratructure setups. Another reason would be the level of expertise. If the team can support deploying the application without an app service, it could be great to to minimize cost and allow for high customization.
