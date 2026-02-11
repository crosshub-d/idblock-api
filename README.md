# Crosshub API - API Documentation

Static API documentation for Crosshub API v1.0.

## Quick Links

- **Live API**: https://api.crosshub.id
- **Swagger UI**: https://api.crosshub.id/swagger
- **Scalar UI**: https://api.crosshub.id/scalar

## Files

| File | Description |
|------|-------------|
| `index.html` | Main documentation |
| `openapi.json` | OpenAPI spec (JSON) |
| `openapi.yaml` | OpenAPI spec (YAML) |

## Local Preview

```bash
cd static-docs
python3 -m http.server 3000
# Open http://localhost:3000
```

## Deployment

### Netlify
```bash
netlify deploy --prod --dir=static-docs
```

### Vercel
```bash
vercel --prod static-docs
```

### GitHub Pages
```bash
cd static-docs
git init && git add . && git commit -m "docs"
git push origin HEAD:gh-pages --force
```

## Stats

- **Endpoints**: 39
- **Tags**: N/A

Generated: 2026-02-11T08:32:22.946Z
