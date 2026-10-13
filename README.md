# My Notebook

A small Windows desktop app for keeping Claude prompts, with gauges for your Claude usage limits.

- Prompts are organised in folders and saved as `.md` files in `Documents\My Notebook\Prompts`
- Copy a prompt with one click, export it as `.md`, or back everything up to JSON
- 5-hour and weekly usage gauges: either live from your claude.ai account or counted by hand
- Lives in the system tray; **Alt+N** shows or hides it
- Updates itself automatically

## Download

Go to the **[latest release](https://github.com/jacobgbroussard-code/my-notebook-releases/releases/latest)**,
download **My-Notebook-Setup-x.y.z.exe** and double-click it. It installs in a few seconds and opens the app,
with shortcuts on your desktop and in the Start menu. No admin rights needed.

**"Windows protected your PC"?** The installer isn't code-signed yet, so Windows SmartScreen doesn't
recognise it. Click **More info → Run anyway**.

To uninstall: Settings → Apps → My Notebook → Uninstall. Your prompts in `Documents\My Notebook\Prompts` are kept.

## Updates

The app checks this page for new versions when it starts and every 30 minutes, downloads them in the
background and shows **⬆ Update ready** at the bottom right. Click it, or just quit and reopen the app.

## Live usage (optional)

Click **🔗 Live usage** and sign in to claude.ai in the window that opens. The gauges then show your real
5-hour and weekly limits.

- You sign in on claude.ai's own page; the app never sees your password.
- The login stays on your PC only. **⚙ → Disconnect** signs it out.
- This uses an unofficial claude.ai endpoint (the one the claude.ai usage page uses). It may stop working
  if claude.ai changes, and it is not an Anthropic product.

## Privacy

Everything stays on your computer. The app only talks to github.com (update checks) and claude.ai
(if you turn on live usage).

---

This repository only hosts the downloads. The source code is kept in a separate private repository.
