# Calibra Simulations Support

Support tracker for the **A330-200 by Calibra Simulations**, a freeware aircraft for X-Plane 12.

This repository holds no aircraft files. It is where you report a problem or ask for help, and where we keep track of
what is being looked at.

## Before you open an issue

1. Read the `README` that comes in the package. It covers installation, the optional engines and the known issues.
2. Check that the aircraft was installed over a **copy** of the default Airbus A330-300, not over the original folder.
3. Try again with third-party plugins and scripts disabled. Many reports turn out to be a conflict with another add-on.
4. If you can, try the same thing on the default A330-300. If it happens there too, it comes from the default aircraft
   or from X-Plane.
5. Search the [existing issues](../../issues?q=is%3Aissue). Someone may have reported it already.

## Open an issue

Use the [issue forms](../../issues/new/choose):

- **Bug report**: something does not work as described.
- **Installation or usage help**: you are not sure how to install or use something.

We will ask for two files:

- `version.txt`, from the aircraft folder.
- `Log.txt`, from the X-Plane 12 folder, **from the same session in which the problem happened**. X-Plane overwrites
  this file every time it starts.

### Your Log.txt is public here

Everything posted in this repository can be read by anyone. Before you attach `Log.txt`:

- Delete **every** line that contains `Pilot ID`. If you use SimBrief on the MCDU there are several of them, all
  starting with `A330 MCDU:`. Searching the file for your own Pilot ID number is a quick way to check.
- Remove anything else you do not want to share, such as your user name in folder paths.

Never post your SimBrief Pilot ID. We will never ask for it.

## What we support

- The official, unmodified package, on the X-Plane versions listed in its `README`. Reports from other versions are
  welcome, but compatibility with untested versions is not guaranteed.
- We do not send single aircraft files. If a file is damaged or missing, download the official package again.
- The GE and PW engines are free mods by Carda, downloaded from the author's own pages. Questions about the mods
  themselves go to their author.
- Third-party liveries are supported by their authors.

## How reports are handled

Each report gets one of these labels after we look at it:

| Label | Meaning |
|---|---|
| `calibra-bug` | A defect in our package. It goes to the fix list. |
| `laminar-default` | Also happens on the default A330-300 or comes from X-Plane. We report these upstream. |
| `usage-install` | Installation or usage. Answered here and added to the FAQ when it is common. |
| `third-party-conflict` | Caused by another plugin, script or add-on. |
| `needs-log` | We cannot look into it without `Log.txt` and `version.txt`. |

This is a freeware project. We answer every report, but we do not promise dates for fixes or new features.

---

The A330-200 by Calibra Simulations is built on the default Laminar Research A330-300 and distributed with permission
from Laminar Research. It is not an official Laminar Research or Airbus product, and neither company provides support
for it.
