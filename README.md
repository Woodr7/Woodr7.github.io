Link pages for the Bar League app's venue sticker QR codes.

- `/gaming/start/?venue=…&venueId=…&sport=darts|pool` — sticker link. With Bar League installed, iOS opens the app (universal link) and starts a game at that bar. Without it, this page sends you to the App Store.
- `/.well-known/apple-app-site-association` — tells iOS the Bar League app handles `/gaming/*`.
