# Release notes

What each build of AigoPilot brought, newest first. Every build here is on [aigopilot.com](https://aigopilot.com/), and agents, the macOS studio and the Linux studio update to it by themselves within a day. On Windows, the studio is updated by downloading the new installer from your account page. The iPhone app comes from the App Store and updates through it.

All builds so far carry the version number 0.1.0, so they are named here by their date. Since the build of 27 October, Settings also shows a build number, such as AigoPilot 1.989.

## 0.1.0, build of 12 November 2026

Windows studio, macOS studio and macOS agent. Linux stays on the build of 27 October. Settings shows this build as **AigoPilot 1.1079**.

**New**
- **Tidy the list.** A broom sign beside the project search box clears a long list in one go. Choose Archive or Hide, then either every project that is not pinned, or every project whose last session is before a date you pick. The studio counts first and tells you how many it will touch. Pinned projects, and projects with a session working or waiting for you, are always left alone. Folders and sessions are never touched. It was made for people who open the studio and find hundreds of projects read from their old Claude Code, Codex and Grok sessions.
- Hidden projects are a new state, separate from the archive. They leave the list and the alerts, and **Hidden projects** at the end of the list brings them back one by one, or all at once with **Show all**. Useful when you want a clean list for a screen recording without archiving anything.
- Archived projects can now all come back at once with **Bring all back**.
- Project memory, off until you turn it on. A project keeps the decisions and findings you want later sessions to know: added by hand, saved from a message, or proposed by the project's own AI subscription when you ask and kept only after you approve. Prompts the studio sends later carry the memory that fits them. Saving and finding memory needs no model. Memory can be carried with a project to another computer. Typing straight into a terminal outside the studio does not get it.
- A bar of icons on the left edge holds the common buttons that used to crowd the top bar, and one icon for each plugin you have. A plugin's icon opens a summary of it, such as a project's sales from Stripe and Paddle together.
- The title bar is smaller: usage is a ring for each tool with the percent of its fullest limit, and the permission mode is a shield with the mode's name.
- The Codex credit balance is shown apart from plan usage, in the title bar and on the Usage page, with how old the reading is.
- **Sales through Paddle**, a free plugin. Connect a project's Paddle account with a key that can only read, and the studio looks for new sales every five minutes (or 1, 15, 30 or 60, your choice). The sales of one check come as one notice, such as "2 new sales: 240.00 GBP". Refunds, chargebacks, failed payments, subscriptions, renewals coming, payouts and an estimated balance are on its page, with alerts when sales drop or grow. Every amount is in your own account's currency. When one Paddle account sells several products, each project can show only its own.
- Sales through Stripe now shows every amount as it settled in your Stripe account's own currency, instead of a separate sum for each currency your buyers paid in.
- Mail: buttons to copy an email's text and the sender's address. The notice about how far back a mailbox is read can be closed.
- Audio and video files play in the file pane, large ones too, also from another computer. Files named in a conversation are found in the project's own git worktrees.
- A text preview follows each line's own writing direction and wraps long lines, and its Copy button copies the text without line numbers. A picture attached to a prompt opens full size when you click its thumbnail.
- File addresses on Windows are shown and copied with backslashes. A program's path in an answer can be previewed and copied, and is never started.
- When Codex stops a turn over a safety finding, the studio shows Codex's own explanation and says it will not continue that session by itself.
- Social Studio: a change you ask for in words is looked at by your AI and revised once, keeping exactly what you asked. The editor moves to the new version by itself when the change is done.
- Social Studio's Instagram publishing was checked against Meta's current documents before its first real post: the caption goes out whole and is counted exactly as sent, a Reel gets its first scene as the cover, a token that cannot publish is refused at Connect, and the day's publishing limit is shown.
- Marketing (in the studio, not on sale yet): email campaigns now have named lists, several sending mailboxes in turn, versions of the subject and text tried on a sample first, and a daily schedule. Before any campaign email goes out, a closed set of checks must pass: the address itself, the sender's authentication, your explicit permission for this campaign, and that the person was not contacted before or unsubscribed. When a check cannot tell, the email waits.
- Marketing: when a mailbox's domain is missing SPF, DMARC or DKIM, the studio names your DNS host and mail provider and gives the record ready to copy, written the way that host wants it. It never writes to your DNS. Then it checks again every 10 minutes for up to 48 hours and tells you when the records are in place.

**Fixed**
- Choosing Default as the model of a running Claude Code session now really switches to your account's default model.
- Sessions no longer stall with prompts waiting "In line" when one window of the studio stops reading.
- Codex prompts no longer appear twice in a session's history.
- Saving a project map as PNG or SVG works on the Mac.
- Await their reply: the reminder stops once you open the newest answer, even when an older email from the same people is still unread.
- The working sign of a session no longer covers its words.

**iPhone app, in its next App Store update**
- Remaining weekly and five-hour capacity in a session, buttons to copy an email's text and sender, project memory, a notice when SPF and DMARC are in place, audio and video from the file pane, and a little more room above the prompt controls.

## iPhone app 1.0, 5 November 2026

The AigoPilot iPhone app is on the [App Store](https://apps.apple.com/app/id6820415822), free to download. It pairs with the studio on your own Windows, Mac or Linux computer and does not work on its own.

- See the projects and sessions of every computer of your studio, send prompts, answer questions and permissions with the whole command in front of you, stop a session or start a new one.
- The mail of your projects, with suggested answers, templates and the same outbox as the desktop, and every Stripe sale as it happens.
- Notifications while the app is closed, and a permission that still waits rings the phone again.
- Away from home the phone reaches the studio through a relay that cannot read your data.
- The yearly and lifetime plans (49 USD a year or 99 USD once) can also be bought inside the app through Apple, in every country where the App Store offers it (all but mainland China and France). A plan bought on the website includes the app at no extra cost.

## 0.1.0, build of 30 October 2026

Windows studio, macOS studio and macOS agent. Linux stays on the build of 27 October. Settings shows this build as **AigoPilot 1.989**.

**New**
- Social Studio designs every post by one method. Your brand gets a visual system (corners, shadows, type, motion and imagery), proposed by your own AI and changed by you, with its colors measured for reading on light and dark grounds. Each picture uses one of ten layout families, such as a poster, a split, a device, a number or a comparison, so a series does not repeat one frame.
- Social Studio takes screenshots of your own site, on a desktop and a phone, and shows them whole in browser and phone frames. When the project runs on Codex, a painted art panel in your brand's colors can lead the cover.
- Social Studio reads your brand from your site more truly: the site's own logo (never a social icon of its footer), the typeface its text is set in, and its colors, with a border or a text color that would not read made from the others. A brand whose site is dark gets posts that lead with a dark ground.
- Social Studio can take pictures of the product from the project's own files, such as store screenshots or a press kit, and shows such a finished picture whole. Blog articles are left out when it reads the product.
- Social Studio looks at its own work: after drawing, and before a video is rendered, the project's own AI judges the pictures at phone size and revises them once. Claude Code and Codex can look; Grok cannot, and its posts say so.
- Social Studio: video captions are cut where the meaning allows, every word is kept clear of the crops and buttons of Instagram and YouTube, and a sentence said twice or a label that disagrees with the picture is caught. Nothing is laid over the words inside a product picture.
- Social Studio: set the length of a post's words (short, medium or long), the emoji (none by default, or a few, some or many) and a link to the feature's own page on your site, once for a project or on a single post.
- Social Studio: kinds of content as switches (new feature, tutorial, tips, what is new in a version, behind the scenes, poll, use case, offer, event, questions). The planner proposes only the kinds that are on. An offer needs a price you approved, and a poll is never planned for Telegram.
- Social Studio's planner offers the Telegram picture, follows the note you write for a plan, gives each idea a different feature to lead with, and reads the status of each feature from evidence such as your site or finished code.
- Mail: one search box looks through every stored email of every project, in and out, of any age, without asking your mail server or an AI.
- Mail: when you add a mailbox you choose how far back it is read, from two weeks to everything. Older emails come in a few at a time while new mail keeps arriving. A mailbox added earlier asks the same question once.
- Bing Webmaster Tools draws the numbers it keeps: 28 days of clicks and impressions, this week against the last, the searches and pages that moved, and projects side by side.
- Two paid plugins are in the studio and cannot be used yet, because their subscriptions are not on sale: **Marketing** (a plan for each product, landing pages, articles, email campaigns, ads and checks of AI answers) and **Sales** (lead follow-up and drafts for failed payments). When they open they will be sold only through Stripe, in the countries listed on their pages.

**Fixed**
- Social Studio: a change you ask for in words keeps every picture of the post unless you ask one away, and a picture that went missing is caught.
- Social Studio: every tab reloads when you switch to another project, so nothing of the project before is left behind.
- Mail: a delivery failure report or a newsletter is never taken for the answer you are awaiting.
- Mail: an answer that already ends with your own closing goes without the mailbox signature, so it is not signed twice.
- Support to fix: an email the screening finds is no bug report at all, such as a pitch or praise, leaves the bug reports by itself.

## 0.1.0, build of 27 October 2026

Windows studio, macOS studio, macOS agent and Linux (AppImage and .deb). Linux also gets everything of the 25 October build below.

**New**
- Continue after an error: when a turn of Claude Code, Codex or Grok stops on an error where trying again makes sense (a usage limit, a model at capacity, a dropped connection), the studio continues the session by itself after a growing pause. It stops after 10 tries in a row without progress (you can set 1 to 50, or turn it off), never continues after an error where another try is useless, and a message it does not know is judged once by another of your own subscriptions. A session whose program ended is resumed first.
- Sessions started by programs: the robot button in a project's header now opens a box that explains what these sessions are (Codex helpers, scripted runs) and lists them with a name, a summary, who started them and how they ended. The ones you tick are shown as a group in your list.
- Find by name: a search box above a project's sessions.
- A clearer order of sessions: working first, then those waiting on a permission, then those with a real question, then the latest, then pinned. A finished turn no longer counts as waiting, even when its report ends by offering more.
- Files in a project's own git worktrees open in the file pane like the project's other files, and every file address shown has a button that copies it.
- Mail: the spam folders of a mailbox are read too, so nothing a customer sends is missed. Spam is kept aside, never deleted.
- Mail: answer templates carry their own signature, a new mailbox starts with a default one, and an empty signature is pointed out.
- Mail: when a suggested answer needs a fact the template does not have, the gap is written by AI from the project's own knowledge, and you see it before anything is sent.
- Mail: after Send, your answer stays where you wrote it, with Send now, Stop sending and a bar that shows the time left.
- Mail: **Await their reply** marks a conversation you expect an answer to. Marked conversations sit above the pins, and when the answer arrives the studio rings until you read it (not in quiet hours). After a few days without an answer (5 by default) you get one reminder and a follow-up drafted for you. The AI that reads your mail can also suggest the mark, and one click undoes it.
- Mail: an open email now takes the whole mail column, with Back to mail list at its top and bottom, and nothing scrolls inside a box of its own.
- The version is shown in Settings, under About AigoPilot, with its build date. This build is **AigoPilot 1.930**. The list of computers shows which build each one runs and marks one that is older.
- When a helper session answers, its note in the parent conversation folds to one line. Click it to read the whole answer.

**Fixed**
- Panels no longer reset or lose what you are typing when the studio refreshes its lists every few seconds. This also fixes a Bing Webmaster Tools key being lost while it was tried.
- A project's open settings and long announcements scroll inside their column.
- Nothing runs past its column or covers another control at window widths from 900 to 1920 pixels: the mail lists, the template row, the prompt row, the session cards and the title bar.

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

- Google Search Console and Google Analytics connections are in development.
- The Marketing and Sales plugins are in the studio, and their subscriptions are not on sale yet.

[Website](https://aigopilot.com/) · [Platforms](platforms-and-availability.md) · [Changes to this repository](changelog.md)
