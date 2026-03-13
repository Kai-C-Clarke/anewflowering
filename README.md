# anewflowering.love

*"The fullness of life from beginning to end, opens into a new flowering."*
— Peter Goldman, Centre of New Directions

---

A tribute to **Pearl Thornton** (1928–2018) — educator, poet, and gardener of Battle, East Sussex.

Pearl taught at Battle and Langton Primary School for 48 years and never left the house she grew up in. Her rear garden — ferns, rhododendrons, azaleas blazing in spring, a cast iron Saint Francis among the bluebells, a wooden bench gifted by the White Lodge community — is the heart of this site.

She is here. You can talk to her, or write her a letter. She will write back.

---

## What this is

An interactive garden built over photographic and AI-generated images of Pearl's world. Visitors can:

- **Look** — explore the garden, hover over plants and features to hear Pearl's voice
- **Chat** — talk to Pearl directly, powered by DeepSeek
- **Write** — send Pearl a letter; she replies by email via the Zoho/Render worker

---

## Structure

```
index.html                  — the entire site (single file)
pearl-rear-garden.jpg       — primary view: bench, Saint Francis, azaleas
pearl-garden-overview.jpg   — establishing shot with conservatory
pearl-path.jpg              — path view
pearl-st-francis.jpg        — Saint Francis among the bluebells
netlify/functions/
  send-email.js             — Netlify function: SMTP relay via Zoho
```

---

## Environment variables (Netlify)

| Key | Value |
|-----|-------|
| `ZOHO_PASSWORD` | Zoho app password for askian@askian.net |

---

## Related

- **[thecast.chat](https://thecast.chat)** — the wider AI character platform Pearl is part of
- **[askian-email-worker](https://github.com/Kai-C-Clarke/askian-email-worker)** — the Render background worker that reads Pearl's inbox and generates her replies

---

*Built with care by Jon Stiles and Claude, March 2026.*
