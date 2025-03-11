# Aegis
A smart reverse proxy for your web based applications.
Rooted in mythology (the shield of Zeus), this reverse proxy provides divine-level protection and elegance.

## Goals
* [ ] SSL Provisioning
* [ ] SSL Renewals
* [ ] Smart Health Checks (to include language version, framework version(s), os version, etc) to flag outdated or vulnerable apps
* [ ] Client Authentication (two rotatable api keys, maybe cookie based auth as well in an auth and forward pattern)
* [ ] Client Metrics (which client is calling which http routes and when)
* [ ] Rate Limiting (per client configuration on a request per second measurement)
* [ ] Configuration Import / Export (ability to read/write a single file to configure all settings)
