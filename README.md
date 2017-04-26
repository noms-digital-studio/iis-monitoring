IIS Monitoring
====
Monitoring for the IIS project.

The project is based on Smashing.

Build
----
```
gem install bundler
bundle install
```

Run
----
```
smashing start
```

Local
----
http://localhost:3030/circle


Heroku
----
https://iis-monitoring.herokuapp.com/circle


Further Reading on Smashing
----
Check out http://smashing.github.io/ for more information.


Deployment Configuration
----

Requires the following environment variables

 * CIRCLE_CI_TOKEN - a valid circle API access token
 
 
Dashboard Configuration
----

1. Edit dashboards/circle.erb to add projects to the build monitor
3. Edit the projects element in jobs/circle_ci.rb to match your changes to CI statuses shown in circle.erb
4. Edit the projects element in jobs/health.rb to match your changes to app health statuses shown in health.erb