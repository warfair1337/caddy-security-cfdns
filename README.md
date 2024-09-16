# Caddyserver with Cloudflare and Caddy-Security

This image was created for use with Unraid, but it works just as well for any docker implementation.
I try to keep this package updated regularly to keep up with Caddy development and releases.

This image is compiled with the following addons:
* Cloudflare
* Caddy Security

The Unraid templates assumes EntraID (previously Azure AD) is being used as the Identity Provider (IdP)
Documentation is WIP.

/local/path/caddy/config:/config
/local/path/caddy/data:/data
/local/path/caddy/Caddyfile:/etc/caddy/Caddyfile
CLOUDFLARE_API_TOKEN
AZURE_TENANT_ID
AZURE_CLIENT_ID
AZURE_CLIENT_SECRET

