# Configuration Files

### `horizon.yml`

```yaml
# This is the main configuration file for Horizon.
# 
# Created by GideonWhite1029
# Boosty: https://boosty.to/gideonwhite1029


settings:
  features:
    no-chat-reports: true 
    use-vanilla-random: false 
    vanilla-hopper: false # Returns vanilla hopper behavior
    spectator-dont-get-advancement: false
    fast-resume: true # Creates a file with information for quickly starting and loading the server (WARNING, may cause lags on the server)
    update-suppression-crash-fix: false # Includes the ability to suppress updates (At the moment there is no mechanism that uses the update suppressor for 1.20.6+)
    cce-update-suppression: false # Includes the ability to suppress updates (At the moment there is no mechanism that uses the update suppressor for 1.20.6+)
    no-tnt-place-update: false # Disables TNT update when it is posted
    instant-block-updater-reintroduced: false # Enables instant block updates
    redstone-wire-dont-connect-if-on-trapdoor: false # If the redstone is on the hatch, it will not turn on
    optimized-powered-rails: false # Speeds up behavior/on/off of powered rails by 4 times
    copper-bulb-1-gt-delay: false # Copper bulb has 1 redstone teak
    crafter-1-gt-delay: false # Crafter has 1 redstone teak
    disable-packet-limit: true # Disables the packet sending limit (Useful if you are using Litematic to insert a large building into the world)
    disableMovedWronglyThreshold: false # Disables any Moved Wrongly Threshold
  utils:
    hopper-counter: false # Adds the /counter command
    use_virtual_thread_for_async_scheduler: false # Use virtual streams instead of regular ones
    stick-change-armorstand-arm-status: false # The stick can change the position of the armorstand's arms
  protocols:
    appleskin-protocol: false # AppleSkin mod support
    jade-protocol: false # Jade mod support
    horizon-carpet-support: false # Carpet mod support
    syncmatica: # Syncmatica mod support
      enable: false
      quota: false # Enable quota for the number of blocks in the schematic
      quota-limit: 40000000
  fakeplayer:
    enable: true
    unable-fakeplayer-names:
    - player-name
    limit: 10
    prefix: ''
    suffix: ''
    always-send-data: true
    resident-fakeplayer: false
    open-fakeplayer-inventory: false
    skip-sleep-check: false
    spawn-phantom: false
    regen-amount: 0.01
    use-action: true
    modify-config: false
  optimization:
    fasterChunkSerialization: false
    optimizeNoiseGeneration: false
    configurable-mc-67: true # Allows mobs and other entities to pass through a nether portal
config-version: 3
```