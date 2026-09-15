# CLNR Notion Assets

Standalone branded widgets for CLNR Studios Notion production templates.

Each widget is hosted independently on GitHub Pages and can be embedded by URL. Widgets should not depend on Notion content to render; customization is passed through URL query parameters so the same component can be reused across clients and duplicated templates.

## Standalone widgets

- `/production-status/` — series status monitor
- `/production-progress/?status=preproduction` — animated production-stage bar
- `/shoot-countdown/?date=2026-09-18T09:00:00-07:00&episode=EP%2003&call=09:00%20AM&location=STUDIO%20A` — shoot countdown
- `/episode-slate/?status=editing&clip=A004_C001&title=Episode%20Title&episode=EP%2004&owner=Editor&version=V1&format=4K%20%2F%2024%20FPS` — episode slate
- `/review-monitor/?state=client%20review&title=EP%2004%20%C2%B7%20CUT%20V2&reviewer=Client&deadline=SEP%2017&status=waiting%20on%20client` — review monitor
- `/post-house/?title=EP%2004%20%C2%B7%20V1&editor=Assigned&color=In%20Progress&audio=Pending&review=Not%20Sent&progress=62` — post-production monitor
- `/delivery-terminal/?title=EP%2001%20%C2%B7%20FINAL%20EXPORT&platform=Instagram&release=SEP%2022&export=4K%20H.264&status=Ready` — delivery terminal
- `/client-welcome/?client=Client%20%C3%97%20CLNR&series=Series%20Name&producer=CLNR%20Studios&phase=Pre-Production&milestone=Shoot%20Day` — client welcome panel
- `/rooms/` — production room launcher

## System components

- `/clock/` — CLNR control clock
- `/section/` — reusable section-title system

## Production-stage values

The progress widget accepts these template-friendly values:

- `preproduction`
- `shooting`
- `editing`
- `completed`

Example:

`https://clnrstudios.github.io/CLNR-Notion-Assets/production-progress/?status=editing`

## Brand direction

Use CLNR's white, red, and deep green system with restrained production-interface language. Components should feel like production instruments: spacious, precise, minimal, camera-inspired, and consistent across client workspaces.
