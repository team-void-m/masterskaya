# masterskaya

Landing page of the vibe-coding workshop, live at https://makscee.ru/course. One static `index.html` plus `assets/` and `fonts/`; see `AGENTS.md` for the rules.

How it is served: GitHub Pages builds `main` (https://team-void-m.github.io/masterskaya/); mcow's Caddy (homelab `ansible/playbooks/templates/Caddyfile.j2`) proxies `makscee.ru/course` to it. Because of that the page's own paths start with `/course/`, so the Pages URL above shows it without fonts and images.
