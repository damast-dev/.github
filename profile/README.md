<p align="center"><img src="logo.png" width="96" alt="Damast logo"></p>
<h1 align="center">Damast</h1>
<p align="center"><b>Every commit a layer.</b><br>Self-hosted git with the GitHub habits your team already has. Built on Forgejo.</p>

Most of us learned to work together on GitHub. When a team moves to a self-hosted forge, every habit that doesn't carry over becomes a small daily papercut: a pairing partner who gets no credit, a collaborator who can push code but can't publish the package it builds, a workflow that needs a personal token for something GitHub does out of the box.

[Forgejo](https://forgejo.org) is a great forge that deliberately goes its own way. Damast is a soft fork that makes the other choice: **where Forgejo and GitHub work differently, Damast leans toward GitHub.** It's an opinionated fork, and that's the point. It's also a reversible one. Damast never touches Forgejo's tables, so you can switch in with one image name and go back the same way.

### What Damast adds today

- **Co-authors get the credit.** `Co-authored-by` trailers show up as people, with avatar and profile link, on every commit.
- **Packages belong to their repository.** Repo write publishes, repo read downloads, and Actions publish with their built-in token.

Everything else is Forgejo, following every release within a day.

### Projects

| | |
|---|---|
| [**damast**](https://github.com/damast-dev/damast) | The forge. Start here: why it exists, what's different, how to switch and how to go back. |
| [**mast**](https://github.com/damast-dev/mast) | The command line, like `gh` for Damast. A soft fork of forgejo-cli that works with Damast and Forgejo alike. |
| [**damast.dev**](https://github.com/damast-dev/damast.dev) | The website at [damast.dev](https://damast.dev). |

### Is it for you?

If your team works the GitHub way and wants to host its own forge, try it. If you chose Forgejo *because* it isn't GitHub, stay with Forgejo. You'll like it better, and that's fine.

What do you miss from GitHub? [Tell us in an issue.](https://github.com/damast-dev/damast/issues/new)

<sub>GPL-3.0-or-later, like Forgejo. Damast is not affiliated with or endorsed by the Forgejo project. Thanks to everyone who builds Forgejo, without whom none of this would exist.</sub>
