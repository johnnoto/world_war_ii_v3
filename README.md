## world_war_ii_v3

TripleA map for World War II v3, with three scenarios:

**Installing.** Download the [ZIP](https://github.com/johnnoto/world_war_ii_v3/archive/refs/heads/master.zip)
and unzip it. In your TripleA `downloadedMaps` folder, delete the official `world_war_ii_v3` folder if you have one,
and put this folder there in its place, then restart TripleA. This map uses the same name as the official
World War II v3 map, so only one of the two can be installed at a time; if both are present TripleA may pick
either one, and France will show up in the wrong colours. Everyone in an online game needs this version installed.

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
- **Historical economics.** Germany's war economy and the Soviet trade agreement, US Neutrality Acts.

Full rules are in the game notes (`map/games/WW2v3-1939.notes.html`).

Map-wide files added for the 1939 scenario: `map/politicstext.properties`, `map/notifications.properties`,
`map/units/French/`, `map/units/Neutral/`, `map/flags/French*.png`, a French entry in `map/capitols.txt`
and `color.French` in `map/map.properties`. They do not affect the 1941 and 1942 scenarios.
