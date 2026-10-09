# Hi, I'm gandolh

I write TypeScript web apps for myself and a few people around me.

<table>
<tr>
<td width="50%" valign="top"><a href="https://github.com/gandolh/game-engine"><img src="https://raw.githubusercontent.com/gandolh/game-engine/main/docs/images/four-games.webp" alt="Four game screens in a grid: a pixel-art farm on islands, an isometric village, a 3D town beside population charts, and a knight facing a small dragon above a math problem"></a><br><b>game-engine</b><br>Four browser games on one deterministic engine</td>
<td width="50%" valign="top"><a href="https://github.com/gandolh/ImbatranimOS"><img src="https://raw.githubusercontent.com/gandolh/ImbatranimOS/main/docs/images/desktop.gif" alt="A Windows 7-style desktop in a browser tab: Start opens a Terminal that runs whoami, then File Manager and System Monitor open and are dragged into place"></a><br><b>ImbatranimOS</b><br>A Linux container behind a Windows 7-style desktop</td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://github.com/gandolh/3D-sandbox"><img src="https://raw.githubusercontent.com/gandolh/3D-sandbox/main/docs/images/wall-inspector.webp" alt="A lime-plastered house with a tiled roof in a 3D viewport, with one wall selected and its length, height and windows listed in an inspector panel"></a><br><b>Solstice</b><br>A house and its plot under the real sun, for any place and date</td>
<td width="50%" valign="top"><a href="https://github.com/gandolh/atrium"><img src="https://raw.githubusercontent.com/gandolh/atrium/main/docs/images/hero.webp" alt="A library page with a Continue card for Pride and Prejudice, filter chips for Books, Music and Video, and a grid of book covers"></a><br><b>Atrium</b><br>One household's books, music and video on its own server</td>
</tr>
</table>

**Status:** Everything here is personal software and still changing. Most of the apps sit behind a sign-in, so the links in the next section are the parts a visitor can open.

## Open in a browser

- [Farm Valley](https://gandolh.ro/farm-valley/), [Citadel](https://gandolh.ro/citadel/) and [Hollow](https://gandolh.ro/hollow/) are three of the four games in [game-engine](https://github.com/gandolh/game-engine). In Farm Valley 21 farmers compete for gold and you mostly watch. Citadel is a settlement builder. Hollow follows a society across generations, in 3D.
- [Fourteen Renderings](https://gandolh.ro/design-study/) is one blog drawn in 14 design styles. It lives in [presentation-sites](https://github.com/gandolh/presentation-sites) next to five Romanian-language sites, among them a [nail salon](https://gandolh.ro/saloon/) and a [parish](https://gandolh.ro/churchix/).
- [ImbatranimOS](https://github.com/gandolh/ImbatranimOS) has one owner, so my copy only shows you a sign-in screen. Its README starts your own with Docker Compose.

## Projects

| Repo | What it is | Where it stands |
|---|---|---|
| [game-engine](https://github.com/gandolh/game-engine) | A deterministic TypeScript game engine and the four browser games built on it. Any run replays exactly from its seed. | Three games online, MateQuest local only |
| [ImbatranimOS](https://github.com/gandolh/ImbatranimOS) | Alpine Linux in a Docker container, used through a Windows 7-style desktop in any browser. The name is Romanian for "we're getting old". | v1, in daily use |
| [atrium](https://github.com/gandolh/atrium) | A library for one household's books, music and video, with notebooks and LaTeX documents in the same place. | Deployed, sign-in only |
| [3D-sandbox](https://github.com/gandolh/3D-sandbox) | Solstice, a browser editor and path tracer that shows a house and its plot under the real sun. | Runs locally only |
| [ward-auth](https://github.com/gandolh/ward-auth) | Ward, the sign-in service for the other apps. You get one account, and a grant per app decides what you can open. | In production |
| [public-resource-map](https://github.com/gandolh/public-resource-map) | A map of parks, libraries, clinics and museums in Timișoara and București that shows what is on at each. | Proof of concept, events are synthetic |
| [sports-app](https://github.com/gandolh/sports-app) | A calisthenics trainer for beginners at home with no equipment. It picks today's session for you. | Deployed, sign-in does not finish yet |
| [newspapper](https://github.com/gandolh/newspapper) | Write Instagram news posts in a small markup language, preview the 1080×1080 slides as you type and export them as JPEGs. | Deployed, one user |
| [Satchel](https://github.com/gandolh/Satchel) | A small messenger for a few friends, with an ideas inbox that Claude Code reads from the command line. | Built, not deployed |
| [just-a-bot](https://github.com/gandolh/just-a-bot) | A Discord bot for one server, with a play-money casino, party games, a text RPG and a quote book. | Running, no public invite |
| [presentation-sites](https://github.com/gandolh/presentation-sites) | Static Astro sites for small businesses in Gorj, plus Churchix, a platform for parish sites. | Six sites live |
| [postern](https://github.com/gandolh/postern) | Gmail-style webmail that talks JMAP to a Stalwart mail server. | Plan only, nothing built yet |

## How I work

Every project in that table has a `corpus/` folder, a wiki the model maintains. It records each decision with its reason, and work goes in as a written brief before anything gets built. I ask the questions and approve the plan. Opus plans and reviews, Sonnet builds most of the chunks, and a brief is done only after a review.

The skills that run this are in [my-personal-skills](https://github.com/gandolh/my-personal-skills). [the-board](https://github.com/gandolh/the-board) shows where each brief stands across all the projects. Satchel's ideas inbox is how I hand Claude Code a thought from my phone.

Most of the apps are a Fastify API on SQLite with a React client. Ward handles sign-in for four of them so far.

## Older work

[hackathons](https://github.com/gandolh/hackathons) and [mini-projects](https://github.com/gandolh/mini-projects) each merge several earlier repos into one and keep their commit history. The first holds Nutrisha, an AI meal planner my team built at ITFest. The second has a GitLab-style diff viewer for local repos and a TSP solver that uses A* with an MST heuristic.

[GenerativeArt](https://github.com/gandolh/GenerativeArt) is p5.js sketches. [Studying](https://github.com/gandolh/Studying) is where I try languages and tools, and it has Assembly, Common Lisp, Rust, Go and a Linux device driver in it. [Bibliotech](https://github.com/gandolh/Bibliotech) is a REST API for a library that I wrote as homework in three days.
