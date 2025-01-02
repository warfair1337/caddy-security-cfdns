# Caddyserver with Caddy-Security and CloudFlare

This image was created for use with Unraid, but it works just as well for any docker implementation. \
I try to keep this package updated regularly to keep up with Caddy development and releases. \

### This image is compiled with the following addons:
* Cloudflare
* Caddy Security

This Unraid templates assumes EntraID (previously Azure AD) is being used as the Identity Provider (IdP)

### Docker paths
/local/path/caddy/config:/config \
/local/path/caddy/data:/data \
/local/path/caddy/Caddyfile:/etc/caddy/Caddyfile \

### API-token for ACME certificate issuance using Cloudflare
CLOUDFLARE_API_TOKEN 

### Tenant ID, client id and client secret
ENTRA_TENANT_ID \
ENTRA_CLIENT_ID \
ENTRA_CLIENT_SECRET

