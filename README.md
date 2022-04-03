# Minecraft:HACKED

[Minecraft:HACKED](https://www.youtube.com/playlist?list=PLhixgUqwRTjwvBI-hmbZ2rpkAl4lutnJG) is a video series by [@LiveOverflow](https://twitter.com/LiveOverflow) exploring various technical areas of Minecraft.It's a weird series trying to combine classic "Let's Plays" with "Hacking Tutorials".

We are exploring how servers work, how modding support is implemented, we develop our own hacks, audit minecraft for vulnerabilities and much more...

![Minecraft:HACKED Thumbnail](https://img.youtube.com/vi/Ekcseve-mOg/maxresdefault.jpg)

## Episodes

1. **I Spent 100 Days Hacking Minecraft** [video](https://www.youtube.com/watch?v=Ekcseve-mOg&list=PLhixgUqwRTjwvBI-hmbZ2rpkAl4lutnJG&index=1)
   - Minecraft network protocol basics
   - Minecraft python proxy
   - Teleport hack [file](/01_protocol_proxy/teleport_proxy.py)
2. **Minecraft, But It's Reverse Engineered...**
   - Reverse engineering obfuscated java
   - How Minecraft servers are implemented
3. **Minecraft Hacker VS Herobrine**
   - How Minecraft (client) mods work
   - Modifying Java with mixins
   - Java bytecode manipulation
4. **Flying Without Elytra**
   - Auto fish mod
   - Fly hack
   - Bypassing server flying detection
5. **Crafting a Minecraft 0day...**
   - Auditing the minecraft protocol
   - Discovering a minecraft protocol vulnerability
6. **TBA**

## Troubleshooting
**`Auth failed: [<twisted.python.failure.Failure OpenSSL.SSL.Error: [('SSL routines', 'tls_process_server_certificate', 'certificate verify failed')]>]`**

If you're using Windows, there are multiple ways to fix this.
 - Change the server to offline mode
 - Install WSL2, use a virtual machine with linux or just run it on a linux server.

**1.18.2 doesn't seem to be supported**

This is due to a change in the Minecraft protocol between 1.18(.1) and 1.18.2. A temporary but buggy fix is on the Quarry github issues page: [#134](https://github.com/barneygale/quarry/issues/134)


## Credits

Thanks to all my supporters on [Patreon](https://www.patreon.com/liveoverflow) and [YouTube Members](https://www.youtube.com/c/LiveOverflow/join) for supporting weird projects like this.

Additional thank you to the whole technical Minecraft community. In no particular order (hopefully I didn't miss anybody):

- All https://wiki.vg contributors
- 19MisterX98
- jellejurre and jurrejelle
- xpple
- Earthcomputer
- SilicatYT
- BananaRedPanda
- PR0CESS FX
- Mumfrey
- Silk
- Neil
- vktec
- _various anonymous people_
