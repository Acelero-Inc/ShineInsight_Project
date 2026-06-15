# ShineInsight Project — Critical Path Chart

A shareable, browser-based Gantt chart showing the critical path for the ShineInsight project launch. Built as a single HTML file. No login, no software, no dependencies.

**Live URL:** https://acelero-inc.github.io/ShineInsight_Project

---

## What this is

An interactive critical path chart for the executive team. It shows every task, owner, and deadline between June 15 and September 20, 2026. The red "Today" line updates automatically based on the viewer's current date every time the page is opened.

---

## Files in this repo

| File | What it is |
|---|---|
| `index.html` | The chart. This is the only file you need to edit. |
| `README.md` | This guide. |

---

## How to update the chart

All task data lives in the `sections` array near the bottom of `index.html`. Open the file in any text editor (TextEdit on Mac, Notepad on Windows) and find the block that looks like this:

```
{ label: "MBI Health", sub: "Follows ERSEA", start: "2026-07-20", end: "2026-07-26", owner: "jen" },
```

**To change a date:** Edit the `start` or `end` value. Dates must stay in `"YYYY-MM-DD"` format.

**To change a task name:** Edit the `label` value.

**To change the subtitle line:** Edit the `sub` value.

**Do not change** the `owner` value unless you also update the color class. Owner values are: `katie`, `kim`, `jen`, `jesse`, `all`.

Save the file when done.

---

## How to publish your changes

1. Open **GitHub Desktop**
2. You'll see `index.html` listed under Changes
3. Type a short summary in the **Summary** field (example: `Update MBI Health end date`)
4. Click **Commit to main**
5. Click **Push origin**

The live URL updates within about 30 seconds. No other steps needed.

---

## Owners and color coding

| Color | Owner | Scope |
|---|---|---|
| Purple | Katie Connor | Enrollment logic |
| Green | Kim Munoz | Health, Education, DMH, Role Types |
| Orange | Jennifer Lin | Data migration, PIR, MBI, MVP Reports |
| Yellow | Jesse Deutsch | Feedback list |
| Gray | All team | September launch sprint |
| Red bar | Hard deadline | September 20 launch |

---

## Access

To give a teammate edit access to this repository:

1. Go to the repo on github.com
2. Click **Settings > Collaborators**
3. Click **Add people** and enter their GitHub username or email
4. Set their role to **Write**

They will receive an email invite. Once accepted, they clone the repo in GitHub Desktop and follow the same update steps above.

---

## Questions?

Contact the project lead or open an Issue in this repository.
