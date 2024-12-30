###
Step 1: Change SSL.
Step 2: Change Host and Port in docker file.
Step 3: Change username and password DB.
Step 4: Change Host in nginx.conf and ./nginx/conf.d
Step 5: Link Confluence to Jira
Step 6: Create user directory Confluence, add ip range docker to list in App User Management Jira
Step 7: add confluence-users and confluence-administrators group in Jira
Step 8: Disable Internal Directory in Confluence

### Jira Software Data Center
run [jira-compose.yml](/jira-compose.yml)

```bash
docker-compose -f jira-compose.yml up -d
```
> Use `http://<ip>:8080`

### Confluence Server

run [confluence-compose.yml](/confluence-compose.yml)

```bash
docker-compose -f confluence-compose.yml up -d
```
> Use `http://<ip>:8090`


## Activate (Crack) 

Moved Here : [activateAtlassianSoftware.md](activateAtlassianSoftware.md)

##  Use Reverse Proxy

Moved Here : [Reverse-Proxy-for-Atlassian.md](Reverse-Proxy-for-Atlassian.md)


