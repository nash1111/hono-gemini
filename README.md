### run local
```
bun install
bun run dev
```

### put secrets on local
```
cp .dev.vars.example .dev.vars
# edit .dev.vars
# GEMINI_API_KEY = "YOUR_GEMINI_API_KEY"
```

### put secrets on cloudflare
```
wrangler secret put GEMINI_API_KEY
```


