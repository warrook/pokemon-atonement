# Loose Ideas
- In [src/fake_rtc.c](../../src/fake_rtc.c), time does not tick if `OW_FLAG_PAUSE_TIME` is set, and there's a manual time set function too. This would solve one of my problems of playing at all hours and being stuck always at night because it's realtime. Enable the fake clock in [overworld.h](../../include/config/overworld.h), and set the flag here too.

# Pokemon Possibilities
- Mega Evo for Nidoking and Nidoqueen
- Houndour and Poochyena lines have overlap (scary dog). Poochyena line should be regional and be a dueling counterpart to Houndour. (May also need a mega evo for parity). Dark/Ground would make sense for a hyena.
- I still think a Lunatone/Solrock fusion would be cool
- Regional Lapras might be interesting?
- Bug/Dragon
    - Venonat > Venocoon > Venogon?
    - Yanmega retyping? Mega Yanmega (lol)?
    - Surskit > Masquerain > Doppelcane?
    - A difficult bug fakemon, like Larvesta or Snom but Dragon and somehow not a dragonfly
        - [this dragon-headed thing](https://en.wikipedia.org/wiki/Phrictus_quinquepartitus)

# Dex
\* = Mega evolution
\** = Two megas?!

## Gen 1
1. *P_FAMILY_WEEDLE       Bug/Poison
1. P_FAMILY_NIDORAN      Poison/Ground
1. *P_FAMILY_CLEFAIRY     Fairy
1. P_FAMILY_VULPIX       Fire
1. P_FAMILY_ZUBAT        Poison/Flying
1. P_FAMILY_MEOWTH       Steel
1. P_FAMILY_MANKEY       Fighting/Ghost
1. P_FAMILY_GROWLITHE    Fire
1. P_FAMILY_MACHOP       Fighting
1. P_FAMILY_MAGNEMITE    Steel/Electric
1. P_FAMILY_DROWZEE      Psychic
1. P_FAMILY_CHANSEY      Normal
1. P_FAMILY_HORSEA       Water/Dragon
1. *P_FAMILY_STARYU       Water/Psychic
1. *P_FAMILY_SCYTHER      Bug/Flying
1. P_FAMILY_LAPRAS       Water/Ice
1. P_FAMILY_DITTO        Normal
1. P_FAMILY_EEVEE        Normal etc
1. P_FAMILY_SNORLAX      Normal

## Gen 2
20. P_FAMILY_TOGEPI       Fairy
1. P_FAMILY_HOPPIP       Grass/Flying <!-- - Yanma? -->
1. P_FAMILY_MISDREAVUS   Ghost
1. P_FAMILY_UNOWN        Psychic
1. P_FAMILY_SWINUB       Ice/Ground
1. *P_FAMILY_HOUNDOUR     Dark/Fire

## Gen 3
26. P_FAMILY_POOCHYENA    Dark
1. P_FAMILY_ZIGZAGOON    Normal/Dark
1. **P_FAMILY_RALTS        Psychic/Fairy
1. P_FAMILY_NINCADA      Bug/Ground/Flying/Ghost
1. P_FAMILY_SKITTY       Normal **This one isn't in the spreadsheet**
1. *P_FAMILY_ARON         Steel/Rock
1. P_FAMILY_WAILMER      Water
1. P_FAMILY_LUNATONE     Psychic/Rock
1. P_FAMILY_SOLROCK      Psychic/Rock
1. P_FAMILY_DUSKULL      Ghost
1. P_FAMILY_CHIMECHO     Psychic
1. P_FAMILY_SPHEAL       Water/Ice

## Gen 4
38. P_FAMILY_SHINX        Electric
1. P_FAMILY_BUIZEL       Water
1. P_FAMILY_SHELLOS      Water/Ground
1. P_FAMILY_DRIFLOON     Ghost/Flying
1. *P_FAMILY_BUNEARY      Normal
1. P_FAMILY_BRONZOR      Psychic/Steel
1. P_FAMILY_SPIRITOMB    Ghost/Dark
1. **P_FAMILY_GIBLE        Dragon/Ground
1. **P_FAMILY_RIOLU        Fighting/Steel
1. P_FAMILY_CROAGUNK     Poison/Fighting
1. *P_FAMILY_SNOVER       Grass/Ice

## Gen 5
49. P_FAMILY_PURRLOIN     Dark
1. P_FAMILY_MUNNA        Psychic
1. *P_FAMILY_DRILBUR      Ground/Steel
1. P_FAMILY_SEWADDLE     Grass/Bug
1. P_FAMILY_COTTONEE     Grass/Fairy
1. *P_FAMILY_SCRAGGY      Fighting/Dark
1. P_FAMILY_TRUBBISH     Poison
1. P_FAMILY_ZORUA        Dark
1. P_FAMILY_VANILLITE    Ice
1. P_FAMILY_FRILLISH     Water/Ghost
1. P_FAMILY_KLINK        Steel
1. P_FAMILY_TYNAMO       Electric
1. *P_FAMILY_LITWICK      Ghost/Fire
1. P_FAMILY_AXEW         Dragon
1. *P_FAMILY_GOLETT       Ghost/Ground
1. P_FAMILY_PAWNIARD     Steel/Dark
1. P_FAMILY_DEINO        Dark/Dragon

## Gen 6
66. *P_FAMILY_FROAKIE      Water/Dark
1. P_FAMILY_SCATTERBUG   Bug/Flying
1. P_FAMILY_SKIDDO       Grass
1. P_FAMILY_PANCHAM      Fighting/Dark
1. *P_FAMILY_ESPURR       Psychic
1. P_FAMILY_HONEDGE      Ghost/Steel
1. *P_FAMILY_INKAY        Dark/Psychic
1. *P_FAMILY_SKRELP       Poison/Dragon
1. P_FAMILY_CLAUNCHER    Water
1. P_FAMILY_KLEFKI       Steel/Fairy

## Gen 7
76. P_FAMILY_LITTEN       Fire/Dark
1. P_FAMILY_YUNGOOS      Normal
1. P_FAMILY_CUTIEFLY     Bug/Fairy
1. P_FAMILY_ROCKRUFF     Rock
1. P_FAMILY_STUFFUL      Normal/Fighting
1. *P_FAMILY_WIMPOD       Bug/Water
1. P_FAMILY_MINIOR       Rock/Flying
1. P_FAMILY_MELTAN       Steel

## Gen 8
84. P_FAMILY_SKWOVET      Normal
1. P_FAMILY_CHEWTLE      Water/Rock
1. P_FAMILY_ROLYCOLY     Rock/Fire
1. P_FAMILY_ARROKUDA     Water
1. P_FAMILY_CLOBBOPUS    Fighting
1. *P_FAMILY_FALINKS       Fighting

## Gen 9
90. P_FAMILY_SPRIGATITO   Grass/Dark
1. P_FAMILY_NYMBLE       Bug/Dark
1. P_FAMILY_PAWMI        Electric/Fighting
1. P_FAMILY_TANDEMAUS    Normal
1. P_FAMILY_SMOLIV       Normal/Grass
1. P_FAMILY_TADBULB      Electric
1. P_FAMILY_WATTREL      Electric/Flying
1. P_FAMILY_BRAMBLIN     Grass/Ghost
1. P_FAMILY_FLITTLE      Psychic
1. P_FAMILY_VAROOM       Poison/Steel
1. *P_FAMILY_GLIMMET      Rock/Poison
1. P_FAMILY_GREAVARD     Ghost
1. P_FAMILY_CETODDLE     Ice
1. *P_FAMILY_FRIGIBAX     Ice/Dragon

## Fake
> ## Files to touch when adding
> See [tutorial](../tutorials/how_to_new_pokemon.md) for more info.
> 
> - 🗂️ [graphics/pokemon/`?`/](../../graphics/pokemon/): graphics files
> - include/
>   - constants/
>       - [cries.h](../../include/constants/cries.h): cry ID from [sound/direct_sound_data.inc](../../sound/direct_sound_data.inc)
>       - [pokedex.h](../../include/constants/pokedex.h): `NATIONAL_DEX_?` to `NationalDexOrder` and `NATIONAL_DEX_COUNT`; `HOENN_DEX_?` and `HOENN_DEX_COUNT`
>       - [species.h](../../include/constants/species.h): `SPECIES_?` constant
> - sound/
>   - 🗂️ [direct_sound_samples/cries/](../../sound/direct_sound_samples/cries/): cry files, converted with [a command](../tutorials/how_to_new_pokemon.md#5-define-its-cry)
>   - [cry_tables.inc](../../sound/cry_tables.inc): `cry` and `cry_reverse`
>   - [direct_sound_data.inc](../../sound/direct_sound_data.inc): register cry `.bin`
> - src/
>   - data/
>       - [graphics/pokemon.h](../../src/data/graphics/pokemon.h): register battle graphics and overworld graphics file paths
>       - [object_events/object_event_pic_tables_followers.h](../../src/data/object_events/object_event_pic_tables_followers.h): register overworld graphics
>       - pokemon/
>           - [all_learnables.json](../../src/data/pokemon/all_learnables.json): teachable learnset
>           - [pokedex_orders.h](../../src/data/pokemon/pokedex_orders.h): `NATIONAL_DEX_?`
>           - [level_up_learnsets/gen_9.h](../../src/data/pokemon/level_up_learnsets/gen_9.h): level-up learnsets
>           - [species_info.h](../../src/data/pokemon/species_info.h): `SPECIES_?` information
>           - [form_species_table.h](../../src/data/pokemon/form_species_tables.h): species form table, if relevant
>           - [form_change_tables.h](../../src/data/pokemon/form_change_tables.h): species form *change* table, if relevant (see [form_change_types.h](../../include/constants/form_change_types.h) for options)
>   - [pokemon.c](../../src/pokemon.c): `HOENN_TO_NATIONAL(`?`)`
> 
> *According to documentation, this is* fewer *files than were once required to edit.*


1. Grass starters
2. Fire starters
3. Water starters
1. [Tosi](https://en.wiktionary.org/wiki/tosi#Finnish)[tella](https://en.wiktionary.org/wiki/-tella#Finnish)        Psychic/Ghost
1. [Vimma](https://en.wiktionary.org/wiki/vimma#Finnish)                  Fire/Ghost
2. [Hulluus](https://en.wiktionary.org/wiki/hulluus#Finnish)               Poison/Ghost
3. [Kammo](https://en.wiktionary.org/wiki/kammo#Finnish)                Ice/Ghost