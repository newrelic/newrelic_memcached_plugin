## New Relic Memcached Extension

### Instructions for running the Memcached extension agent

1. Go to the tags list and find the latest tar.gz
1. Download and extract the source
1. Run `bundle install` to install required gems
1. Copy `config/template_newrelic_plugin.yml` to `config/newrelic_plugin.yml`
1. Edit `config/newrelic_plugin.yml` by replacing "YOUR_LICENSE_KEY_HERE" with your New Relic license key
1. Edit the `config/newrelic_plugin.yml` file by changing the name and endpoint fields to match your memcached server configuration
1. Execute `./newrelic_memcached_agent`
