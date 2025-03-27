# api-backend
Create a simple API on nginx with simple backend on k8s for demos

## Forward engineered with the help of Grok
https://x.com/i/grok/share/d3CSEtNoHPjIjE4HvwnyvZmkE

## Requirements
Uses k8s, nginx ingress, nginx, flask, gunicon

### Caveats
- need to add path to gunicorn bin export, in .zprofile(on a Macbook): PATH="$PATH:/Users/robinsmith/Library/Python/3.9/bin"
- flag web requests during testing: gunicorn --access-logfile - --bind 127.0.0.1:5000 api:app
