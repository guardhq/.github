<picture>
  <img src="banner.svg" alt="Guard" width="100%" />
</picture>

<p align="center">
  <a href="https://discord.com/oauth2/authorize?client_id=1371550732934971542&permissions=634814288358647&integration_type=0&scope=bot+applications.commands">
    <img src="https://img.shields.io/badge/Add_Guard-6870FF?style=for-the-badge&logo=discord&logoColor=white" alt="Add Guard" />
  </a>
  <a href="https://discord.gg/vamQMmYBNN">
    <img src="https://img.shields.io/badge/Support_server-24263A?style=for-the-badge&logo=discord&logoColor=white" alt="Support server" />
  </a>
</p>

Guard keeps Discord servers safe from scams, raids and hacked accounts, and gives moderators the tools to deal with the rest. You set it up once with `/settings` and it does the work in the background.

### What it does
<table>
  <tr>
    <td width="50%" valign="top"><b>AutoMod</b><br /><sub>Rules for spam, scam links, blocked words, invites, mass mentions and more. Each server picks what happens.</sub></td>
    <td width="50%" valign="top"><b>Scam protection</b><br /><sub>Catches phishing links, fake Steam and Discord sites, and short links that hide where they go.</sub></td>
  </tr>
  <tr>
    <td valign="top"><b>Honeypot</b><br /><sub>A trap channel that catches hacked accounts on their first message. The real owner can come back once their account is safe.</sub></td>
    <td valign="top"><b>Anti-raid</b><br /><sub>Spots a flood of new accounts, pauses invites and removes them.</sub></td>
  </tr>
  <tr>
    <td valign="top"><b>Verification</b><br /><sub>A captcha inside Discord before new members can see the server.</sub></td>
    <td valign="top"><b>Anti-nuke</b><br /><sub>If an admin account gets hacked and starts deleting channels or banning people, Guard stops it and rebuilds what was lost.</sub></td>
  </tr>
  <tr>
    <td valign="top"><b>Moderation</b><br /><sub>Cases, reports, ban appeals, temporary roles and channel mutes.</sub></td>
    <td valign="top"><b>Audit logs</b><br /><sub>Messages, members, roles, channels and more, posted to the channels you choose.</sub></td>
  </tr>
</table>

### Open source

The pieces Guard is built on are public. Issues and pull requests are welcome.

| Package | What it is | |
| --- | --- | --- |
| [`@guardbot/framework`](https://github.com/guardbotgg/framework) | A framework for building Discord bots with discord.js: commands, components, listeners and hot reload. | [![npm](https://img.shields.io/npm/v/@guardbot/framework?color=6870FF&label=npm)](https://www.npmjs.com/package/@guardbot/framework) |
| [`@guardbot/chalk`](https://github.com/guardbotgg/chalk) | A simple colored logger for apps. | [![npm](https://img.shields.io/npm/v/@guardbot/chalk?color=6870FF&label=npm)](https://www.npmjs.com/package/@guardbot/chalk) |
| [`@guardbot/sanitizer`](https://github.com/guardbotgg/sanitizer) | Turns fancy fonts and look-alike letters back into plain text, so filters can't be dodged. | [![npm](https://img.shields.io/npm/v/@guardbot/sanitizer?color=6870FF&label=npm)](https://www.npmjs.com/package/@guardbot/sanitizer) |

### Get in touch
Questions, bugs and ideas go in our [support server](https://discord.gg/vamQMmYBNN).

<a href="https://discord.gg/vamQMmYBNN">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://discordwidgets.vercel.app/widgets/invite/vamQMmYBNN?theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://discordwidgets.vercel.app/widgets/invite/vamQMmYBNN?theme=light" />
    <img src="https://discordwidgets.vercel.app/widgets/invite/vamQMmYBNN?theme=dark" alt="Join the Guard support server" />
  </picture>
</a>
