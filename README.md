Coding Exercise
===============

Please provide scripts and associated tests that would provision the latest version of Postgres cluster for a production environment.  We use AWS on all of our services, so please demonstrate how you'd do this for that environment.
We don't want vendor lock-in, so if you use any AWS services to do this, please do so in a way that'd be easy to use on another environment too.
The database should allow easy updates from automated tools such as flyway etc, and prevent destructive changes such as database or column drops.

If you don't have enough time to complete things like:
 - monitoring and alerting
 - backups
Please indicate the tools you'd use and how you would implement this. 


You can use any technology you deem fit to fully automate the provisioning of a cluster.
