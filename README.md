# threesistersai.com

Public website for 3SistersAI — AI training and automation for healthcare and education organizations.

Static site hosted on GitHub Pages. No build step: edit the HTML, commit, push, and the live site updates in about a minute.

## Structure

| Path | Page |
|---|---|
| `index.html` | Home |
| `training/index.html` | Training programs + upcoming sessions |
| `automation/index.html` | Automation + booking CTA |
| `guide/index.html` | Free guide opt-in (form posts to Supabase) |
| `guide/thanks/index.html` | Guide download page |
| `assets/` | Stylesheet, logo, lead magnet PDF |

## Editing

Copy and structure are maintained via Claude Code in the private 3SistersAI workspace. The site source of truth for launch steps: `outputs/ops/website-launch-guide.md` in that workspace.

**Never commit the Supabase service_role key here.** The only key that belongs in this repo is the anon public key in `guide/index.html`.
