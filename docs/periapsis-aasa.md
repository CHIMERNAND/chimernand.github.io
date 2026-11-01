# Periapsis and AASA

Periapsis 1.0 is offline and has no Universal Links or App Clip. The root
`/.well-known/apple-app-site-association` does **not** need a Periapsis entry for 1.0.

If a future version adds invites or an App Clip, add:

```json
{
  "appIDs": ["H6JN5UFH44.com.drewclarke.periapsis"],
  "components": [{ "/": "/periapsis-site/*", "comment": "Periapsis site paths" }]
}
```

under `applinks.details`, and enable Associated Domains in the Apple portal.
