# Contributing to Sac AI Hub

Thanks for being part of the Sacramento AI community. Here's how to add yourself or contribute content.

---

## Add yourself as a member

1. Fork this repo
2. Open `src/data/members.json`
3. Add an entry following this format:

```json
{
  "name": "Your Name",
  "github": "https://github.com/yourusername",
  "role": "What you do",
  "bio": "One or two sentences about you.",
  "tags": ["tag1", "tag2"]
}
```

4. Submit a pull request with title: `feat: add member [Your Name]`

---

## Add an event

1. Open `src/data/events.json`
2. Add an entry:

```json
{
  "title": "Event Name",
  "date": "YYYY-MM-DD",
  "time": "6:00 PM",
  "location": "Sacramento, CA",
  "description": "What's happening.",
  "link": "https://eventlink.com"
}
```

3. PR title: `feat: add event [Event Name]`

---

## Add a resource

1. Open `src/data/resources.json`
2. Add an entry:

```json
{
  "title": "Resource Name",
  "url": "https://example.com",
  "description": "What it is and why it's useful.",
  "category": "tools | learning | community | research"
}
```

3. PR title: `feat: add resource [Resource Name]`

---

## Code contributions

- Open an issue first to discuss bigger changes
- Keep PRs focused — one thing per PR
- Run `npm run build` before submitting to make sure nothing breaks

---

## Questions

Open an issue or start a Discussion on GitHub.
