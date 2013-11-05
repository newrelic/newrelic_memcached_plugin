## New Relic Memcached Extension

Beta Notes
-------------
This is a beta release of the Memcached plugin, please contact alarson@newrelic.com with any feedback or questions.

Prerequisites
-------------
- A New Relic account. Signup for a free account at [http://newrelic.com](http://newrelic.com)
- A server running Memcached v1.4 or greater. Download the latest version of Memcached for free [here](https://code.google.com/p/memcached/downloads/list).
- Ruby version 1.8.7 or better

Running the Agent
----------------------------------

1. Go to [the tags list](https://github.com/newrelic-platform/newrelic_memcached_plugin/tags) by clicking on the file name and selecting `Raw` from the gray menu bar
1. Extract the downloaded archive to the location you want to run the Memcached agent from
1. Run `bundle install` to install required gems
1. Copy `config/template_newrelic_plugin.yml` to `config/newrelic_plugin.yml`
1. Edit `config/newrelic_plugin.yml` by replacing "YOUR_LICENSE_KEY_HERE" with your New Relic license key
1. Edit the `config/newrelic_plugin.yml` file by changing the name and endpoint fields to match your Memcached server configuration
1. Execute `./newrelic_memcached_agent`
1. Go back to the Extensions list and after a brief period you will see an entry for 'Memcached'

Source Code
-----------

This plugin can be found at [https://github.com/newrelic-platform/newrelic_memcached_plugin](https://github.com/newrelic-platform/newrelic_memcached_plugin)