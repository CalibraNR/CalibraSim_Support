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

We will ask for the **debug report**, a .zip the aircraft creates for you:

1. Right after the problem happens, open the tablet and go to **Options > Support > Save debug report**.
2. The .zip is saved in `Output/Calibra A330-200/debug` (inside your X-Plane 12 folder).
3. Drag it into the issue form. Add screenshots if they help.

Save it right after the problem, without reloading the aircraft or closing X-Plane (it covers the last 30 minutes).
No tablet? In X-Plane's Settings > Keyboard, bind the command `a330v3/debug/save` to a key and press it. The report
already has your versions, operating system and plugin list.

### Your debug report is public here

Everything posted in this repository can be read by anyone. Before you attach the report:

- It replaces your user and computer names, and does not include your SimBrief Pilot ID. Look through the files
  anyway and remove anything you do not want to share.
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
| `needs-log` | We cannot look into it without the debug report (.zip). |

This is a freeware project. We answer every report, but we do not promise dates for fixes or new features.

---

The A330-200 by Calibra Simulations is built on the default Laminar Research A330-300 and distributed with permission
from Laminar Research. It is not an official Laminar Research or Airbus product, and neither company provides support
for it.
