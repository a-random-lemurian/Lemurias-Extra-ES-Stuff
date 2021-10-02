# Internal code conventions
* Use camelCase.

This style of variable naming for Endless Sky shall be named "Lemurian Dot Variables", or LDV.
## Fleet, mission names
### Fleet
```
faction.purpose.name.num
```
* `faction`: fleet's faction. use short names for long full names (free worlds becomes fw, sayari plushie authority becomes spa)
* `purpose`: purpose of fleet such as mining, fighting wars, or trading
* `name`: any kind of name
* `num`: for specifying different variants if more precise control instead of `variant #num` desired
### Mission names
`st` Story missions
`fl` Flavor text (e.g Free Worlds secession dialogue)
`fi` Fighting missions
`pi` Pirate missions (e.g smuggling)
`tr` Transport missions
`ex` Exploration missions
`ms` Miscellaneous missions
```
tr.cargo.size.pirateRisk.num
```
#### Attributes
* `cargo`: Type of cargo, camelCase.
  `bunks`, `cargo`, or commodity name. Use bunks for passenger.
* `size`: `huge, xxlrg, xlrg, lrg, med, sml`.
  
| tons | `size` attr |
|---|---|
| 0-200 | sml
201-600| med
601-1200 | lrg
1201-2000 | xlrg
2001-3000 | xxlrg
3001+ | huge

* `pirateRisk`: `lrg, med, sml`, involvement of capital ships is considered `lrg`, medium warships `med`, interceptors and small warships `sml`
* `num`: increments up, used for offering missions more than one at a time
* 