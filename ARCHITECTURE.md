# Site publishing flow

## Daily flow
1. 06:00 generate fresh briefing artifacts (`briefings/YYYY-MM-DD.md`, `.json`, links)
2. 07:00 publish to Notion backup
3. 07:00 render HTML briefing page into `openclaw_daily_briefing/briefings/`
4. 07:00 update site index/archive
5. 07:00 commit + push to GitHub repo
6. GitHub Pages deploys the updated dashboard

## Roles
- Notion: backup/archive surface
- GitHub Pages site: primary reading surface
- Telegram: optional notifier with links only

## Weekend travel
- One top recommendation may be rendered as a mini HTML app in `apps/`
- The app is linked from the dashboard and can evolve independently
