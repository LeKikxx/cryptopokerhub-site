# Bluesky Auth Token

## Status
- Date: 2026-02-13
- Email: cryptopokerhub@proton.me
- Username: pokergrinder25

## Next Action
Créer le compte via API REST (pas de phone verification), puis poster.

## Login
```bash
curl -X POST https://bsky.social/xrpc/com.atproto.server.createSession \
  -H "Content-Type: application/json" \
  -d '{"identifier":"pokergrinder25.bsky.social","password":"MOT_DE_PASSE"}
```
