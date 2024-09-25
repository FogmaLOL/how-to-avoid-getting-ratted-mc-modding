# GitHub Repo on How to Avoid Getting Ratted in the Minecraft Community

## How Do I Know If a Mod Is a RAT?

1. **Use a website like [RatRater2](https://ktibow.github.io/RatRater2)** and drag in the mod you want to download. If it says it’s a RAT, don’t run it. If it says it’s obfuscated, it’s most likely a RAT unless it’s a paid mod (it can still be a RAT). Note that RAT checkers may not always detect the RAT.

2. **You can also use a tool like [JavaDecompiler](https://github.com/java-decompiler/jd-gui/releases/download/v1.6.6/jd-gui-1.6.6.jar)** to look through the code. If you find methods like `player.getSession().getSessionId` or `Method_310` when compiled, or if it tries to access files like `C:\Users\*yourusername*\.lunarclient\settings\game/accounts.json` or `%appdata%/feather/accounts.json`, it’s trying to steal your client token. If it tries to contact an API like `https://ipapi.co/` or if it has a Discord webhook that looks like `https://discord.com/api/webhooks/xxxxx/xxxx`, or a remote server using an IPv6 local IP address that looks like `192.xxx.xxx`, it is likely malicious.

## Discord Verify Scam

The Discord verify scam is common in Hypixel-Skyblock. It usually relies on a person inviting you to a Discord server advertised as a place for help, giveaways, etc. A Discord bot may ask you to verify your Minecraft account with your username and email. It will send a reset password or access request to your email, asking for an OTP (one-time password) or session ID, allowing them to log into your Minecraft account or even steal your entire Microsoft account.

## Still Want to Do Malware Analysis?

Use a VPN or proxy with a VM like VMware. Refer to this [video](https://www.youtube.com/watch?v=7kcqDy7aeGg) for guidance. Use an alternative account or software like TLauncher to prevent them from getting your Session-ID for Minecraft. It may seem safe to run it offline, but it may set itself to autostart, allowing them to start the RAT as soon as you boot your computer.

## Pretend to Be a VM

Some advanced malware may have anti-debug features that check for programs like Process Hacker or ProcMon. It may also check for specific usernames, IP addresses, HWID, disk names, etc. Consider using software like "Dolus." Watch this [video](https://www.youtube.com/watch?v=lgLLvnBIVdc) for more information.

## Do Your Background Research and Trust Trusted Sites

If it is on websites or software like Modrinth or CurseForge, it’s most likely not a RAT because they check through the code to ensure it’s not malware and verify that the person you are trusting is not impersonating someone else.

## Credits, V.1.0

- **Fogma**: Creating the repo and writing all the content.
- **3000IQPlay**: Some of the content comes from him. [GitHub](https://github.com/3000IQPlay/IQ-Docs?tab=readme-ov-file)
