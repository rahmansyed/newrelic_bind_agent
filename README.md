## BIND Agent Install

1. Download the latest version from `https://bitbucket.org/dready/newrelic_bind_plugin`
2. Extract to the location you want to run the BIND agent from
3. Copy `config/template_newrelic_plugin.yml` to `config/newrelic_plugin.yml`
4. Edit `config/newrelic_plugin.yml` and replace "YOUR_LICENSE_KEY_HERE" with your New Relic license key
5. Create a plugin in New Relic
6. Edit `newrelic_bind_agent` and replace "PUT YOUR GUID HERE" with the GUID that was generated when you created the plugin
7. run `./newrelic_bind_agent`
