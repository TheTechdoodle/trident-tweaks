This plugin adds configuration to change various mechanics of tridents.

Permissions:
 - tridenttweaks.cmd\
   Allows the player to use the /tridenttweaks command
 - tridenttweaks.reload\
   Permission to reload the config

Commands:
 - /tridenttweaks reload\
   Reloads the config

Config:
```yaml
# Make the impaling enchantment act as it does on bedrock edition: deals extra damage to mobs touching water or rain
enable-bedrock-impaling: true

# If a trident enchanted with loyalty is heading into the void (such as in the end), this will save it and make it return
enable-void-saving: true

# If a trident is thrown from the offhand, it will try to go back to the offhand when it's picked up
enable-offhand-return: true

# Disables tridents enchanted with loyalty from going through portals
# (which makes the trident not return until the player goes through the portal)
disable-loyalty-portals: true
```