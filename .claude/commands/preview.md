# Preview Local Server

Start a local development server to preview the site.

## Steps
1. Check if port 8000 is available
2. Start Python HTTP server in background
3. Report URL to user

```bash
# Kill any existing server on 8000
lsof -ti:8000 | xargs kill -9 2>/dev/null || true
# Start server
python3 -m http.server 8000 &
echo "Server running at http://localhost:8000"
```

Open http://localhost:8000 in browser to preview.