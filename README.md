# Cloudflare Rules
My Rules of Cloudflare Firewall for Block Bad Bot and Exploiting

# 1. Bad Bot - Action Block [(open)](https://github.com/SocolSRT/cloudflare-rules/blob/main/Bad%20Bot%20-%20Block.txt)
> * Blocks popular bad User Agent
> * Blocks connections by port (usually only bots do this)
> * Blocks outdated versions HTTP (1.0)
> * Blocks bad threats flagged by cloudflare
> * Blocks bad method requests
> * Blocks suspicious X-Forwarded-For
> * Blocks requests from the Tor network
> * Blocks ASN list of most known proxy scraping sites
> * Blocks non-standard cookies

# 2. Exploiting (Beta) - Action Block [(open)](https://github.com/SocolSRT/cloudflare-rules/blob/main/Exploiting%20Check%20-%20Block.txt)
> * Blocking queries with SQL vulnerabilities
> * Blocking queries with XSS vulnerabilities
> * Block popular PHP vulnerabilities
> 
> ...

# 3. Threat Check - Action Challenge [(open)](https://github.com/SocolSRT/cloudflare-rules/blob/main/Threat%20Check%20-%20Challenge.txt)
> * Checking for outdated versions HTTP (1.1, 1.2)
> * Checking countries that allow a lot of malicious traffic
> * Checking bad threats flagged by cloudflare
> * Checking for insecure requests (Not SSL requests)
> * Checking requests of unknown origin (Not have referer)

# How to use?
*Copy the expression and paste it into your expression builder*
![image](https://user-images.githubusercontent.com/55624740/161973398-05e74f0c-f72c-4c71-afa4-46987801f3c8.png)

# Not enough Cloudflare?
* Free WAF for websites
[[Learn more and download here]](https://safeness.su/web-firewall/)
* Free Firewall for servers
[[Learn more and download here]](https://safeness.su/firewall/)

# Would you like to support me financially?
* My Bitcoin wallet - *14AA4FAdUYnTVTx5pSQjq2h8UJoA8Na89R*
* My Litecoin wallet - *MSevKqUirTvQTkGxYechhNmBgAtDiZJq2x*
