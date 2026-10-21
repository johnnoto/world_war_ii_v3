## world_war_ii_v3

TripleA map for World War II v3, with three scenarios:

**Installing.** Download the [ZIP](https://github.com/johnnoto/world_war_ii_v3/archive/refs/heads/master.zip),
unzip it and put the folder in your TripleA `downloadedMaps` folder, then restart TripleA. The map's name is
`world_war_ii_v3_1939`, so it installs alongside the official World War II v3 map instead of replacing it.
Everyone in an online game needs this map installed, at the same version.

| Scenario | File | Start |
|---|---|---|
| World War II v3 1939 | `map/games/WW2v3-1939.xml` | 1 September 1939: the invasion of Poland |
| World War II v3 1941 | `map/games/WW2v3-1941.xml` | Spring 1941 |
| World War II v3 1942 | `map/games/WW2v3-1942.xml` | Spring 1942 |

### The 1939 scenario

- **Eight powers.** France joins the original seven as a playable nation, with its own units and flag.
- **Historical starting position.** Borders, armies and fleets as of September 1939: the Wehrmacht massed on
  Poland, the Graf Spee loose in the South Atlantic, the Kwantung Army in Manchuria, the US Pacific Fleet
  still on the West Coast.
- **Neutral countries can be invaded.** Poland, the Low Countries, Norway, Finland, the Baltic States,
  Yugoslavia and Greece, Persia and Iceland have their own armies.
- **Diplomacy.** The USSR, Italy, Japan and the USA start at peace with some or all of the belligerents and
  enter the war through declarations in the Politics phase, each available from its historical date
  (Italy June 1940, Barbarossa June 1941, Pearl Harbor December 1941, and so on). Powers fighting a common
  enemy ally automatically.
- **Events.** The Fall of France and Vichy, the Liberation of Paris, Romania and Bulgaria joining the Axis,
  the Dutch and Belgian governments in exile, and Germany and Italy declaring war on the USA after Pearl Harbor.
- **Victory by surrender.** Play until one side concedes, or switch on victory cities under Game Options (recommended: Axis 13, Allies 15).
- **Historical economics.** Germany's war economy and the Soviet trade agreement, US Neutrality Acts.

Full rules are in the game notes (`map/games/WW2v3-1939.notes.html`).

Map-wide files added for the 1939 scenario: `map/politicstext.properties`, `map/notifications.properties`,
`map/units/French/`, `map/units/Neutral/`, `map/flags/French*.png`, a French entry in `map/capitols.txt`
and `color.French` in `map/map.properties`. They do not affect the 1941 and 1942 scenarios.
