# LeechBlock Configuration

[LeechBlock](https://www.proginosko.com/leechblock/) is a browser extension that lets you block or limit access to distracting websites.

## Getting Started

### 1. Install LeechBlock
Install the LeechBlock extension for your browser, then come back here.

### 2. Import Settings
All my custom settings are saved in `LeechBlockOptions.txt`. To use them:
1. Open the LeechBlock options page in your browser
2. Scroll to the **Import/Export** section
3. Click **Import** and select `LeechBlockOptions.txt`

This will apply all the pre-configured block rules automatically.

---

## Custom Block Pages

Instead of the default block screen, I use custom pages hosted on GitHub Pages. These are already referenced in the imported settings.

### 🌙 Sleeping Time Page
Shown when accessing blocked sites during designated sleep/rest hours.

[View Page](https://nil1st.github.io/Leechblock/MyCustomPage.html?source=$S&from=$U)

### ⏱️ 30-Minute Limit Page
Shown when you've used up your 30-minute daily allowance on a site.

[View Page](https://nil1st.github.io/Leechblock/focus.html?source=$S&from=$U)

> **Note:** The `$S` and `$U` parameters are automatically filled in by LeechBlock — they pass the blocked site name and the URL you tried to visit into the page.

---
