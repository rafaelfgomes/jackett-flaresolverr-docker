# Jackett + Flaresolverr Service

Jackett works as a proxy server: it translates queries from apps (Sonarr, Radarr, SickRage, CouchPotato, Mylar3, Lidarr, DuckieTV, qBittorrent, Nefarious, NZBHydra2 etc.) into tracker-site-specific http queries, parses the html or json response, and then sends results back to the requesting software.

FlareSolverr is a proxy server to bypass Cloudflare and DDoS-GUARD protection.

For more information about Jackett, visit the [Jackett documentation][Jackett Github].

For more information about FlareSolverr, visit the [FlareSolverr documentation][Flaresolverr Github].

## How to install and run

- First make a copy of the ".env.example" file and rename it to ".env";
- Fill the required variables in the .env file;

After that you can run the command:

`docker-compose up -d`

[Jackett Github]: https://github.com/Jackett/Jackett

[Flaresolverr Github]: https://github.com/FlareSolverr/FlareSolverr
