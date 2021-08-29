# Frequent Questions

The purpose of this page is to answer commonly asked questions regarding the BetterDiscord client mod and installer.

This page should not be treated as documentation.

_:warning: **Still under construction**. Some links may either work improperly or not be added._

---

## BetterDiscord

<details>
<summary>How do I install BetterDiscord?</summary>

> 1. Download our installer from [here](https://betterdiscord.app) and open it.
> 2. Agree to the license.
> 3. Select "Install BetterDiscord" from the list of options.
> 4. Choose your current Discord build.
> 5. Click the "Install" button, and Discord should restart with BetterDiscord installed.
> 
> ![InstallBD](https://user-images.githubusercontent.com/63931154/131234284-a97e0b81-66e1-4a06-8711-5000b4ee5c09.gif)
</details>


<details>
<summary>How do I uninstall BetterDiscord?</summary>

> 1. Run the installer you used to originally download BetterDiscord. If you don't have that, you can get it [here](https://betterdiscord.app).
> 2. Agree to the license.
> 3. Select "Uninstall BetterDiscord" from the list of options.
> 4. Choose your current Discord build.
> 5. Click the "Uninstall" button, and Discord should restart with BetterDiscord removed.
> 
> ![UninstallBD](https://user-images.githubusercontent.com/63931154/131234291-b7acc16c-a7e6-45ff-ac5b-658c39a7999e.gif)
</details>


<details>
<summary>The installer isn't working.</summary>

> 1. Run the installer you used to originally download BetterDiscord. If you don't have that, you can get it [here](https://betterdiscord.app).
> 2. Agree to the license.
> 3. Select "Repair BetterDiscord" from the list of options.
> 4. Choose your current Discord build.
> 5. Click the "Repair" button and see if that resolves the issue.
> If that doesn't work, try removing your plugins.
> 
> If neither of those instructions worked, join our [Discord community](https://discord.gg/0Tmfo5ZbORCRqbAd) for support.
</details>


<details>
<summary>Does this work on mobile?</summary>

> **No.** Mobile builds of Discord are built on entirely different frameworks, and are not compatible with BetterDiscord.
</details>


<details>
<summary>Does this work on browser/chromebook?</summary>

> **No.** BetterDiscord requires the full desktop app to load.
</details>


<details>
<summary>Can I use BetterDiscord on Linux?</summary>

> **Yes.** You can either use the AppImage build of our [GUI installer](https://betterdiscord.app/), or attempt a [manual injection](https://github.com/BetterDiscord/BetterDiscord#manual-installation).
</details>


<details>
<summary>How do Twitch emotes work?</summary>

> **Typing the name** of most BTTV, FFZ and Twitch subscriber emotes in chat will show the emote image in it's place (e.g. <code>DansGame</code>).  
> Only BetterDiscord users can see these emotes.
</details>


<details>
<summary>BetterDiscord is causing Discord to crash on startup.</summary>

> This is **likely caused by a broken plugin.** Locate your plugins folder and delete whichever plugin might be causing the crash.  
> If that doesn't work, try completely wiping your BetterDiscord data folder and reinstalling.  
> If neither of those instructions worked, join our [Discord community](https://discord.gg/0Tmfo5ZbORCRqbAd) for support.
</details>


### TOS / Bans / Safety

<details>
<summary>Is this against the terms of service?</summary>

> **Yes.** BetterDiscord violates Discord's terms of service by modifying the client, although there is no evidence that Discord either cares or takes actions against users who modify their client.
> Your account is not at risk for simply using BetterDiscord alone.  
> Abusing the service or using plugins which further violate the [Terms of Service](https://discord.com/terms) can get your account terminated, however.  
> All plugins from our official website are safe.
</details>


<details>
<summary>Can BetterDiscord get me banned?</summary>

> As mentioned in the last question, **Discord does not hand out bans for simply using BetterDiscord.**  
> If you abuse the service to further violate Discord's policies, you risk account suspension.
</details>


<details>
<summary>Is BetterDiscord safe?</summary>

> **BetterDiscord contains no malicious code**, nor does it collect any meaningful user data without your knowledge.  
> The source code for both the [client mod](https://github.com/BetterDiscord/BetterDiscord) and [installer](https://github.com/BetterDiscord/installer) are freely available for anyone to view on GitHub.
</details>


<details>
<summary>Can Discord detect if I am using BetterDiscord?</summary>

> BetterDiscord runs entirely clientside, and **Discord has no clientside checks for such modifications.**  
> Even if they did, Discord has not been known to ban for client modding, nor has there ever been a proven ban case for client modding alone.  
> Using unofficial plugins which utilize server-side API calls can get your account flagged for selfbotting, however.
</details>


---

## Themes

<details>
<summary>How do I download themes?</summary>

> 1. Find a theme you like from our [themes](https://betterdiscord.app/themes) page.
> 2. Click the "Download" button on the theme you want.
> 3. Ensure you have BetterDiscord installed. If you don't, refer to question #1.
> 4. Open your Discord user settings. Near the very bottom, there should be a themes tab. Click it.
> 5. At the top of the themes page, click the "Open themes folder" button.
> 6. Drag the file you downloaded into the themes folder that opened.
</details>


<details>
<summary>I can't find a theme that I like.</summary>

> If you are knowledgeable of CSS, you can edit the preset variables of most themes using a text editor.  
> Otherwise, you can customize themes with a [theme generator](https://bdeditor.dev/).
</details>


<details>
<summary>How safe are themes?</summary>

> **Themes are** for the most part **harmless** and pose no threat to you.
</details>


<details>
<summary>My theme looks broken.</summary>

> If your theme is partially broken, you should contact the developer.  
> Themes need consistent management and will break over time if the author doesn't update it frequently.
</details>


<details>
<summary>My theme is not showing up on the themes tab.</summary>

> Make sure the **file name** of your theme **does not contain a number at the end** (e.g. <code>Addon.theme (1).css</code>).All themes must end in <code>.theme.css</code>.  
> Downloading an addon twice is a common reason for the addon not showing up in settings.
</details>


---

## Plugins

<details>
<summary>How do I download plugins?</summary>

> 1. Find a plugin you like from our [plugins](https://betterdiscord.app/plugins) page.
> 2. Click the "Download" button on the plugin you want.
> 3. Ensure you have BetterDiscord installed. If you don't, refer to question #1.
> 4. Open your Discord user settings. Near the very bottom, there should be a plugins tab. Click it.
> 5. At the top of the plugins page, click the "Open plugins folder" button.
> 6. Drag the file you downloaded into the plugins folder that opened.
</details>


<details>
<summary>How safe are plugins?</summary>

> Plugins should be treated like any other program installed on your computer. They have direct access to both your account and filesystem.  
> All **plugins from our official repository are checked for malicious code** and must follow our guidelines.  
> Anything downloaded outside of this website is out of our control.
</details>


<details>
<summary>Can I see deleted messages?</summary>

> **No.** Message loggers are in violation Discord's [API terms](https://discord.com/developers/docs/legal) and [privacy policy](https://discord.com/privacy), and can result in account termination.  
> We will not provide such plugins.
</details>


<details>
<summary>Is there an account switching plugin?</summary>

> **No.** Account switchers put users at unnessecary risk by storing either their account token or email/password combo.  
> We will not provide such plugins.
</details>


<details>
<summary>Can I delete all of my messages in a DM/Server?</summary>

> **No.** Automating requests through Discord's API will get your account flagged for selfbotting which can result in account termination.  
> Additionally, sending requests in rapid succession is a form of API spam which increases the odds of being flagged. As such, we will not provide any plugins that do this.
</details>


<details>
<summary>Can I get free nitro with this?</summary>

> **No.** BetterDiscord is a client-side modification, not a hacking tool.  
> Attempting to bypass server-side permissions (for example, screenshare quality) can result in account termination.
</details>


<details>
<summary>Do you have an automatic status changer plugin?</summary>

> **No.** Automating server-side actions through Discord's API **is considered selfbotting, and therefore highly bannable** under Discord's [API terms](https://discord.com/developers/docs/legal).  
> Additionally, using such a plugin spam's Discord's API with HTTP requests which will get your account flagged and terminated.
</details>


<details>
<summary>My plugin is not showing up on the plugins tab.</summary>

> Make sure the **file name** of your plugin **does not contain a number at the end** (e.g. <code>Addon.plugin (1).js</code>). All plugins must end in <code>.plugin.js</code>.  
> Downloading an addon twice is a common reason for the addon not showing up in settings.
</details>
