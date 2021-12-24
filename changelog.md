### v0.10.8
This is honestly a lot of content to work on. We hope that this release makes your Christmas a bit better. If you fancy playing Endless Sky on Christmas, that is.
- Added planets to several systems:
   - Raidei
   - Sorusep
   - Ladosak
- Internal:
   - Added new changelog file
   - Changed name of hails.txt
   - Alphabetized system nodes
   - Ignore imgui.ini (used by the ES Editor)
   - Revamped .gitignore
   - Change identifier of CSSF names
      - Backwards compatibility maintained: `anti.sayari` redirects you to `cssf`
- Improved CSSF nameset with:
   - Names of Touhou series games & characters
- New landable planets:
   - Peliru, Minjuuk
   - Perechra, Pelitol
   - Defal VII Station, Defal
   - Merschre, Littike
   - Kestrix I, Ghesie
   - Kestrix II, Ghesie
   - Kestrix III, Ghesie
- Improved Ghesie:
   - Added SPA patrol
   - Added 3 new moons orbiting a gas giant (all of them are inhabited)
   - Derelict Republic ships sometimes spawn in Ghesie and surrounding systems
   - Buffed Pirate fleets
   - Added it's own dedicated patrol fleet
- Improved GHCV dialog:
   - Added a log entry for John, the person who talks to you when the dialogue triggers
- Improved hails:
   - Added more hails to the SPA
   - Added Linux user hails
   - Weighted hail phrases
- New names:
   - Namesets of people in tech (includes open-source project leaders)
- Weighted ship name phrases
- Defined confusion for SPA fleets
- Add fleet variants with SPA gunboats
- New variants:
   - Added the SPA Gunboat with proton guns
   - Added the SPA Cruiser, with more turrets than a normal Cruiser.
   - Added 
- Pirate ships now use vanilla names
- Bug fixes:
   - Fix incorrect fleet names
   - Remove misspelling of SPA govt name
   - Fix bad phrases in SPA names
   - Allow data missions in SPA space
   - Fix bad capitalization of names
- Added trade prices to most of the Illumina Regions
- Add source code files as variants of Data drives commodity
- Added SPA Cruiser exploration fleet with gunboats
### v0.10.7
- Added more SPA friendly and hostile hails.
- Balance Amidala stats
- Improve GitHub code vault story dialog.
   - Do not imply that all proprietary projects are corporate
   - Fixed bad goto label in GitHub Code Vault story
   - Make Linus Torvalds log entry more concise
   - Clarify role of GitHub in it's log entry
- General typo fixes
   - Fix incorrect spelling of "Markaai" in Markaai planet description
- New ships
   - SPA variant of the Republic Navy Cruiser
      - Uses Hai atomic engines
      - Uses Wanderer energy generators (Blue Sun Reactor)
      - Has additional turret and gun slots
      - Sells for approx. $51m in SPA territory
      - Has a Jump Drive
   - SPA variant of the Republic Navy Gunboat
      - Uses Hai atomic engines
      - Same number of slots
      - Comes with interference plating
      - Has a Jump Drive
      - Uses Wanderer energy generators (Red Sun Reactor)
      - Sells for approx. $13m in SPA territory
- New names
   - Added Indonesian place names for ships.
   - Added nameset of notable people in tech (e.g Linus Torvalds, Bill Gates, etc.), mostly leaders of open source projects and Debian project leaders
   - Added full names of characters (e.g. *S.P.S Freya Winters*, instead of *S.P.S Winters*)
- Fleets all over the place
   - Added CSSF fleets to Republic space, will spawn often and attack SPA fleets in these systems:
      - Delta Velorum
      - Turais
      - Algorel
      - Phecda
      - Merak
      - Denebola
      - Sol
      - Mizar
      - Arcturus
      - Rutilicus
      - Menkent
      - Hiljaak
      - Limen
      - Mora
      - Zosma
      - Dubhe
      - Alphard
      - Talita
      - Miaplacidus
      - Vindemiatrix
      - Muhlifain
      - Algorel
      - Cor Caroli
      - Turais
      - Menkent
      - Vega
      - Altai
      - Delta Capricorni
      - Scheat
      - Ruchbah
      - Tania Australis
- Internal changes
   - Split name lists over multiple files
   - Deleted events.txt and moved it to a separate file (it only contained the GHCV* dialog)

* GHCV = **G**it**h**ub **C**ode **V**ault

#### Pull requests
* feature/better-amidala by @a-random-lemurian in https://github.com/a-random-lemurian/Lemurias-Extra-ES-Stuff/pull/13
* Merge feature/name reorganization into dev by @a-random-lemurian in https://github.com/a-random-lemurian/Lemurias-Extra-ES-Stuff/pull/18
* Merge GitHub Code Vault story into dev by @a-random-lemurian in https://github.com/a-random-lemurian/Lemurias-Extra-ES-Stuff/pull/19


**Git log**: https://github.com/a-random-lemurian/Lemurias-Extra-ES-Stuff/compare/v0.10.6...v0.10.7

### v0.10.6
- Added more SPA hails
- Added Linux user spaceport news
- Added Debian hat retrieval mission (triggers in 3014)
- Added log entries about GitHub and Linus Torvalds
- Added file for (boring) legal disclaimers
- Removed GH workflows
- Renamed SPA jobs file, no campaign right now

### v0.10.5
- New entry in logbook upon trigger of `githubCodeVault` event and dialog
- SPA fleets... in Republic Navy livery have been added. They manifest in huge numbers just like regular SPA fleets.
- Amidalas now use Hai Bufaer Atomic engines
- Amidalas no longer use Heavy Laser Turrets