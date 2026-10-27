# Release notes

What each build of AigoPilot brought, newest first. Every build here is on [aigopilot.com](https://aigopilot.com/), and installed studios and agents update to it by themselves within a day.

All builds of October 2026 carry the version number 0.1.0, so they are named here by their date.

## 0.1.0, build of 25 October 2026

Windows studio, macOS studio and macOS agent. (The Linux build of 23 October below is the current one for Linux.)

**New**
- Mail: every email the studio sends waits in an outbox first, with **Cancel** and **Send now**. Nothing leaves before the wait is over unless you say so.
- Mail: a new order for the mail column puts accepted offers first, and each reply to an offer is marked by how it answers it.
- Mail: when an AI answer needs a code from your list (a licence key, a coupon), the studio puts it in itself, and only where one belongs.
- Codex: when Codex wants to use an app or an MCP tool, you get a card to allow it or not. An allow holds for that session only.
- The voice assistant now searches only within the tool and project of the session you are in.

**Fixed**
- A finished turn no longer hides what the session told you at its end.
- A prompt written while a session is still in the middle of a step now waits for that step instead of being sent twice.
- A permission card no longer reads the value of a parameter as a file path.
- The tool chooser of a handover shows the tool's sign instead of an empty box.
- Mail drafts no longer write an answer to an email that needs none.

## 0.1.0, Linux build of 23 October 2026

- Signing in to Claude Code, Codex or Grok from the AppImage now opens the tool's own sign-in correctly.

## 0.1.0, build of 22 October 2026: first public release

The studio goes on sale for **Windows, macOS and Linux**. The agents for Windows and macOS, out since early October, update to this build too.

**The studio**
- One window for Claude Code, Codex and Grok sessions across all your projects, using the official command-line tools and your own accounts.
- Sessions you started elsewhere (VS Code, a terminal) are found and shown with their conversations.
- Questions and permission requests in one column. Each request comes with a plain explanation: what it deletes, who wrote the file and when, whether it goes outside the project or to the network.
- A project in full permission mode only asks about deletes outside the project, irreversible actions and installs.
- Search through earlier conversations, and see the files each session changed.
- Continue a long conversation in a fresh linked session, or move a project from one tool to another with one shared instructions file.
- Files panel for each project, with previews.
- Project map: one click draws how a project is built.
- Voice typing, with what was heard corrected by your own model, in every box that has a microphone.
- Notifications on the desktop when a session finishes or needs you.
- English and Japanese.

**On macOS**
- The full studio, not only the agent. Apple silicon, macOS 13.3 or newer, signed and notarized. An agent already on the Mac is taken over by the studio with its pairings.

**On Linux**
- The full studio and the agent in one program, as an AppImage or a .deb, for x86_64 with glibc 2.35 or newer (Ubuntu 22.04, Debian 12, Fedora, Arch, Linux Mint 21, RHEL 9 and others of the same age). A server without a desktop can run as an agent.

**Mail and the business side**
- Mailboxes per project, sorted by what matters, with AI drafts you approve, answer templates, and a button to write an answer again with your own note.
- Marketplace plugins: SearchPlan (keyword research, now with pictures for posts and pages), Social Studio (posts, carousels and narrated videos for your own accounts, in any language), Chat Agent for your website's visitors, and a free connection to Bing Webmaster Tools.
- Every service writes in the language of your work, whatever language the studio is shown in.

## Earlier: agents for Windows and macOS

Before the studio went on sale, the agents for Windows and macOS were released on their own, so a computer could be paired and worked on from a studio elsewhere. They have updated themselves to every build since.

## Not released yet

- The iPhone app is in testing and not on the App Store or TestFlight yet.
- Google Search Console and Google Analytics connections are in development.

[Website](https://aigopilot.com/) · [Platforms](platforms-and-availability.md) · [Changes to this repository](changelog.md)
