# citizen-nav

A tiny public bounce page for iPhone Shortcuts.

Open:

`https://matthewglennthomas.github.io/citizen-nav/nav.html?lat=32.205171&lng=-110.917547`

The page immediately redirects to:

`shortcuts://run-shortcut?name=Set%20car%20navigation%20or%20url&input=text&text=32.205171%2C-110.917547`

Safari will ask “Open in Shortcuts?” — that’s expected. If the automatic jump is blocked, use the button on the page.

Query parameters:

- `lat` and `lng` (required; `lon` / `long` also accepted)
- `name` (optional; defaults to `Set car navigation or url`)

No login, ads, or tracking. Used by Tucson Citizen traffic alerts.
