# ollama + webui

## .env example

I access the webui using a caddy reverse proxy. ENABLE_SIGNUP needs to be true to setup the admin account, can (should) be disabled after.

```
# ollama
OLLAMA_HOST=0.0.0.0
OLLAMA_PORT=11434
OLLAMA_BASE_URL=http://ollama:11434
OLLAMA_KEEP_ALIVE=30m

# webui
CUSTOM_NAME=timefactory
ENABLE_OLLAMA_API=true
ENABLE_SIGNUP=false
WEBUI_PORT=8080
```
