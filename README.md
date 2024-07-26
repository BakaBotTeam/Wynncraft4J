<div align="center">
<img src="https://cdn.wynncraft.com/img/logo.png">
<h1>Wynncraft4J • Java API Wrapper</h1>
<img src="https://flat.badgen.net/github/stars/oHate/Wynncraft4J">
<img src="https://flat.badgen.net/github/release/oHate/Wynncraft4J">
<img src="https://flat.badgen.net/github/license/oHate/Wynncraft4J">
</div>

# Installation

We do not provide a online maven repo, you need to compile it and install it manually.

# v3 API Progress

### Player Module
- [x] /player/\<str:username/uuid\>
- [x] /player/\<str:username/uuid\>?fullResult
- [x] /player/\<str:username/uuid\>/characters
- [x] /player/\<str:username/uuid\>/characters/\<str:characterUuid\>
- [x] /player/\<str:username/uuid\>/characters/\<str:characterUuid\>/abilities
- [ ] /player&server=\<str/int:WC1/1, WC2/2\>

### Guild Module
- [x] /guild/\<str:guildName\> 
- [x] /guild/prefix/\<str:guildName\> 
- [x] /guild/uuid/\<str:uuid\>
- [x] /guild/list/guild
- [x] /guild/list/territory

### Item Module
**WIP:** base, identifications, and requirements
- [x] /item/database
- [x] /item/search (Simple)
- [x] /item/search (Advanced)
- [x] /item/metadata