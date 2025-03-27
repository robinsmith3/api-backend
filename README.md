# api-backend
Create a simple API on nginx with simple backend on k8s for demos

## Forward engineered with the help of Grok
https://x.com/i/grok/share/d3CSEtNoHPjIjE4HvwnyvZmkE

## Requirements
Uses k8s, nginx ingress, nginx, _flask_, gunicon

### Caveats
- need to add path to gunicorn bin, export from .zprofile(on a Macbook): PATH="$PATH:/Users/robinsmith/Library/Python/3.9/bin"
- flag web requests during testing: gunicorn --access-logfile - --bind 127.0.0.1:5000 api:app
- for testing nginx.conf(on a Macbook) is here: /opt/homebrew/etc/nginx/nginx.conf
- nginx.conf for testing locally on a Mac is in this repo
