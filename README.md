# redirect
The main intention of this is to redirect to a local app, but it also works to redirect to anyware

**So why is useful?**
let's take this case. I want to open an obsidian.md (located in my local computer) from notion.so. obsidian local url link might look something like this `obsidian://open?vault=MyVault&file=MyFile`. Notion **only** accepts **http or https** urls.

redirecting url = https://strooper1234.github.io/redirect?
obsidian url = obsidian://open?vault=MyVault&file=MyFile

using Github Pages we can redirect like this https://strooper1234.github.io/redirect?obsidian://open?vault=MyVault&file=MyFile
