# <p align=center> ReSound </p>

![Version](https://img.shields.io/badge/Available_for-1.8.0+-blue)
![Mod Version](https://img.shields.io/badge/Mod_Version-2.0.0.0-orange)
![Supports](https://img.shields.io/badge/Supports-RealPlume_&_Waterfall-blueviolet)
![License](https://img.shields.io/badge/License-GPL_3.0-red)

## Description

ReSound is a sound & stock/realplume/waterfall effect replacement patch.

Stock jet engines ship with placeholder audio that carries almost no sense of scale: a Wheesley and a Goliath sound like the same appliance at different volumes. ReSound replaces the whole `EFFECTS` block on air-breathing and multi-mode engines with clips modelled on their real world counterparts, so each engine gets startup, spool, cruise, afterburner and shutdown audio that matches what it actually is. The sound sets cover the CFM56, GE90, GE F404, TFE731 and Rolls-Royce Olympus, plus a dedicated set for the RAPIER's fan and rocket modes.

Every patch is written in several variants and the right one is selected at load time depending on what else is installed: bare stock, RealPlume, StockWaterfallEffects, or Waterfall. Nothing has to be configured by hand. Where an engine is left without a plume under StockWaterfallEffects, ReSound supplies its own Waterfall effect for it, currently the Valkyrie and the B.R.O.A.D.S.W.O.R.D from Near Future Aeronautics.

## Installation

To install, place the GameData folder inside your Kerbal Space Program folder. If asked to overwrite files, please do so.

**REMOVE ANY OLD VERSIONS BEFORE INSTALLING**.

## Dependencies

* [ModuleManager](https://github.com/sarbian/ModuleManager) by sarbian and ialdabaoth. Every config in ReSound is a ModuleManager patch, so nothing is applied without it.

## Supported Mods

Patches are applied only for the parts that are present, so any subset of these can be installed:

* Stock jet and multi-mode engines: Juno, Wheesley, Panther, Whiplash, Goliath, RAPIER
* Mk2 Expansion by SuicidalInsanity
* Mk3 Expansion by SuicidalInsanity
* Near Future Aeronautics by Nertea

Effect mods detected and adapted to:

* RealPlume
* StockWaterfallEffects
* Waterfall

## Licensing

This work is licensed as follows:

* [GPL 3.0](https://www.gnu.org/licenses/gpl-3.0.html). See [here](./LICENSE)
	+ You are free to:
		- Use : unpack and use the material in any computer or device
		- Redistribute : redistribute the original package in any medium
		- Adapt : Reuse, modify or incorporate source code into your works (and redistribute it!)
	+ Under the following terms:
		- You retain any copyright notices
		- You recognise and respect any trademarks
		- You don't impersonate the authors, neither redistribute a derivative that could be misrepresented as theirs
		- You credit the author and republish the copyright notices on your works where the code is used
		- You relicense (and fully comply) your works using GPL 3.0
			- Please note that upgrading the license to any posterior GPL IS NOT ALLOWED for this work, as the author DID NOT added the "or (at your option) any later version" on the license.
		- You don't mix your work with GPL incompatible works.

Releases prior to 2.0.0.0 remain licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/). Additionally, check [this statement from CC](https://creativecommons.org/2015/10/08/cc-by-sa-4-0-now-one-way-compatible-with-gplv3/).

Please note the copyrights and trademarks in [NOTICE](./NOTICE)

## Credits

### Maintenance

* aspctt - mod configs, StockWaterfallEffects and Waterfall support, project maintenance

### Predecessors

ReSound began as a fork of JetSoundsUpdated and is no longer connected to it. The work carried over from that line is credited below.

* linuxgurugamer - JetSoundsUpdated, the repository ReSound was forked from
* JeanTheDragon - legacy engine sound configs
* theonegalen - legacy RealPlume compatibility, PlumeParty
* JadeOfMaar - RealPlume config fixes and ModuleManager pass corrections

### Change Log

Full release history is in [CHANGE_LOG](./CHANGE_LOG.md).
