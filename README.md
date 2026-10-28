# Fieldbook launcher

A tiny installable web app that gives the Fieldbook CRM:
- a short address, for example `https://<your-github-username>.github.io/fieldbook/`;
- an app icon on tablets and phones (Android and iPad / iPhone).

It doesn't store any CRM data. It just opens the Apps Script portal set in `config.js`.

## Put it on GitHub Pages (5 minutes, free)
1. On github.com, create a **public** repository named `fieldbook`.
2. Upload every file in this folder, keeping the `icons/` folder.
3. Open **Settings → Pages**. Under *Build and deployment*, set *Source* to **Deploy from a branch**, the branch to **main**, and the folder to **/ (root)**. Press **Save**.
4. After about a minute the site is live at `https://<your-github-username>.github.io/fieldbook/`. That's the link to share.

Optional: to use your own domain, such as `crm.yourcompany.in`, add it under **Settings → Pages → Custom domain**. Then create a CNAME record at your domain provider pointing to `<your-github-username>.github.io`.

## Install on each tablet
- **Android (Chrome):** open the link and tap **Install on this device**. If that button doesn't appear, use **⋮ → Add to Home screen / Install app**.
- **iPad / iPhone (Safari):** open the link, then tap **Share → Add to Home Screen**.

Tapping the Fieldbook icon goes straight into the CRM. Tick **Keep me signed in on this device** once, and for the next 30 days opening the app takes one tap on **Continue**.

## If the portal URL changes
Edit the one line in `config.js` and upload it again. Installed icons pick up the change automatically.
