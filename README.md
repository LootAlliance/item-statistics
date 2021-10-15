# Loot Item Statistics
For generating statistics for Loot (and other derivative) items, to provide a standardised logic differentiating each bag for dApps to build games more on top of. 

## Statistics ##
- Strength
- Vitality
- Intelligence
- Agility
- Dexterity
- Constitution
- Wisdom
- ..?

# End Goal #
To deploy an upgradable contract with getters for item/bags returning statistics that can evolve with the LootVerse

# Calculation #
available input features are:
- greatness (Loot contract randomiser uses this to determine other inputs)
- suffix (e.g. of Power)
- prefix (e.g. Blight Moon)
- augmentation (e.g. +1 or not; this is dependent on greatness though)
- rarity

## Modifiers ##
Community Acceptance (e.g influence of Divine Robes)
Lost Mana
