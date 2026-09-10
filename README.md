# Pink Rabbit Client Portal

Client portal for **Pink Rabbit Cosmetics**, built and maintained by
Howell'n & Partners.

Single static page, no build step. Open `index.html` or serve the folder.

## Sections

| Page | URL | What it holds |
|---|---|---|
| Home | `/` | Portal landing |
| Dashboard | `/#dashboard` | Metrics, launch readiness, first-30-days explainer |
| Campaigns | `/#campaigns` | What's running, creative, channel order, lash styles |
| Timeline | `/#timeline` | Gantt through February, monthly rhythm |
| Notes | `/#notes` | Client notes, emailed to Brooke and Abby |

## Editing

Everything you'll change lives in the `CONFIG` block at the top of the
`<script>` in `index.html`:

- `EMAILS` - who the Notes form writes to. **Replace the Abby placeholder.**
- `CAMPAIGNS` - campaign cards. Flip `status` to `'live'` when one goes live;
  add artwork paths to `creative`.
- `LAUNCH` - the go-live date the countdown reads from.

Other content (launch readiness, lash styles, Gantt bars, milestones) sits in
plainly named arrays further down: `READY`, `STYLES`, `LANES`, `MILES`.

## Publishing

GitHub Pages: Settings -> Pages -> Deploy from branch -> `main` / root.
