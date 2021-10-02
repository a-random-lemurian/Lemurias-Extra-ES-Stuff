# Internal code conventions
* Use camelCase.
## Fleet, mission names
### Fleet
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