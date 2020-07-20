# Open Source Submissions

# Acceptance criteria

At this time, we are accepting communities which meet the following criteria on Discord's [Open Source repo](https://github.com/discord/discord-open-source/blob/master/README.md).

## Adding your project

1. Fork the repo
2.  Add your logo into [`/logos`](https://github.com/discordapp/discord-open-source/tree/master/logos)

    * Logo dimensions should be either `72x72` for SVG or `144x144` for PNG.
    * Logo should be minified.
    * Logo should be monochromatic and white like Discord's [Open Source page](https://discord.com/open-source).
    * SVGs should contain only vector shapes — no raster graphics.

3.  Add your community to [`communities.json`](https://github.com/OpenSource-It1/open-source/blob/master/communities.json), like so:

```json
{
  "logo": "your-logo.svg",
  "title": "Name of your project",
  "description": "Description of your project",
  "inviteCode": "The public invite code to your project, usually the code after https://discord.gg/",
  "githubUrl": "The URL of your GitHub organization or project repository.",
  "discordLink": "If your project has been added to Discord's Open Source repo, send the PR here."
}
```

4.  Submit a PR with your change, and if all is well, we'll merge it and showcase it in the server + write about it on our blog!
