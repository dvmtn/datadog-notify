Datadog Notifier
================

A simple shell script for creating events in Datadog.
A great companion to Monit or other ops tools where you may want things reporting.

Prerequisites
-------------
1. [Curl](http://curl.haxx.se/)
2. [Datadog API Key](https://app.datadoghq.com/account/settings#api)

Setup
-----
1. Put the script somewhere you can execute it from
2. Export the environment variable `DATADOG_API_KEY` into the environment the script will be run in
3. Invoke it! `datadog-notify 'Event Title' 'A short message' 'optional:tags key:value'`
4. Enjoy seeing your deployments, service restarts and other events along side your monitoring stats!
