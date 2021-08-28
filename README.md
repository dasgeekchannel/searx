# searx
Config files for Searx server on Digital Ocean droplet

- [uwsgi] Searx.ini file is used for uwsgi with no logging enabled and workers = 4 additions to default. Location of config on server ex: /etc/uwsgi/apps-enabled
- [settings.yml] config file for settings.yml to enable engines and configure presets server ex location: /usr/local/searx/searx-src/searx


Additional Info:

- If you folloe my video on setting up Searx using nginx, you can use this command to refresh server once settings are changed in settings.yml or searx.ini
      $ sudo -H service uwsgi restart searx
- Instruction to acquire Youtube API for settings.yml to improve results. See this site here: https://rapidapi.com/blog/how-to-get-youtube-api-key/
