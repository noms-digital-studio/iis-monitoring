Hub Monitoring
====
Monitoring for the HUB, this use smashing which is forked from Dashing, as Dashing is no longer being maintained.

Currently only setup to monitor CircleCI builds, and Health.

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
http://localhost:3030/health

Heroku
----
https://hub-monitor.herokuapp.com/circle
https://hub-monitor.herokuapp.com/health


Further Reading on Smashing
----
Check out http://smashing.github.io/ for more information.