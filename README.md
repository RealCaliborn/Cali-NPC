# Cali-NPC V3

An NPC encounter mod for Space Engineers. It adds seven factions — hostile alien nomads, zealot military fleets, neutral AI-cult merchants, separatist paramilitaries, fighter-police, a private security corporation's automated sentinels, and a background arms cartel — wired together with reputation arcs, mayday distress events, trade stations, and boss encounters.

## Steam Workshop

This mod is distributed and played through Steam Workshop. This repository is a **source mirror**, not the primary distribution channel.

- **Cali-NPC V3** (main mod): https://steamcommunity.com/sharedfiles/filedetails/?id=3378893295
- **Cali-NPC V3 - Block Dependencies** (companion bundle): https://steamcommunity.com/sharedfiles/filedetails/?id=3758821426

Subscribe to both on Workshop to play — the dependency bundle carries the block and weapon assets the encounters need. The bundle repackages third-party Workshop assets and is therefore distributed only through Steam Workshop, not mirrored here.

## Documentation

The full player reference — factions, every ship with complete armament tables, danger tiers, weapons index, encounter and salvage guides — lives in the **[project wiki](https://github.com/RealCaliborn/Cali-NPC/wiki)**.

## Built on

- **[Modular Encounters Systems](https://steamcommunity.com/workshop/filedetails/?id=1521905890)** by MeridiusIX — the spawner/AI framework this mod is built on; nothing in Cali-NPC V3 spawns without it.
- **WeaponCore 3.0** and RivalAI behaviors, used for weapon systems and NPC AI logic respectively.

## Factions

| Tag | Faction | Disposition |
|-----|---------|-------------|
| VOID | Void Walkers | Hostile — nomadic raiders and capital predators |
| PRTH | Poseidon's Wrath | Hostile — zealot military waging holy war |
| ECHO | Enclave for Control of the Human Order | Neutral — merchants, cargo traffic, trade stations |
| GIRR | Gerry's Independent Republican Regiment | Hostile — paramilitary separatists |
| GKNT | Golden Knights | Neutral — fighter-police with an ally track |
| BASS | Blackmoon Allied Security Services | Hostile — automated security sentinels |
| ASTRA | Allied Astronautical | Background lore — arms dealers, no encounters of their own |

## Repository layout

- `Data/` — encounter definitions (behaviors, prefabs, spawngroups, triggers) per faction, plus shared/common encounter data.
- `Audio/` — voice and sound assets used by encounter behaviors.
- `metadata.mod` — Workshop mod metadata.

## License

This repository is licensed under the [MIT License](LICENSE) — reuse, fork, and build on it with attribution.

The sound effects in `Audio/` were sourced over the years from royalty-free / license-free sound libraries; they are redistributed here on that basis rather than under original authorship. The dependency bundle (Workshop ID 3758821426) contains third-party assets and is deliberately not part of this repository or its license.
