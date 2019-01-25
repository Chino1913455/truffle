The changes listed below only encompass the changes since v5.0.0-beta.2.  See the release notes for [v5.0.0-beta.0](https://github.com/trufflesuite/truffle/releases/tag/v5.0.0-beta.0), [v5.0.0-beta.1](https://github.com/trufflesuite/truffle/releases/tag/v5.0.0-beta.1), and [v5.0.0-beta.2](https://github.com/trufflesuite/truffle/releases/tag/v5.0.0-beta.2) for each release's changelog.

#### New Features
+ [#1445](https://github.com/trufflesuite/truffle/pull/1445) Support unboxing from github branches and into subdirectories. (@CruzMolina)
+ [#1480](https://github.com/trufflesuite/truffle/pull/1480) Update CompilerSupplier to be able to handle solc version constraints. (@eggplantzzz)
+ [#1490](https://github.com/trufflesuite/truffle/pull/1490) Network id check and verification during migrations. (@eggplantzzz)
+ [#1500](https://github.com/trufflesuite/truffle/pull/1500) Add command to remove all debugger breakpoints. (@haltman-at)

#### Bug Fixes / Improvements
+ [#1265](https://github.com/trufflesuite/truffle/pull/1265) Add module for easy decoding of TruffleContract objects. (@seesemichaelj)
+ [#1424](https://github.com/trufflesuite/truffle/pull/1424) Reorganize the truffle-contract package. (@eggplantzzz)
+ [#1453](https://github.com/trufflesuite/truffle/pull/1453) Update README.md. (@jtakalai)
+ [#1460](https://github.com/trufflesuite/truffle/pull/1460) Tweak options for sane library to fix crashes. (@eggplantzzz)
+ [#1462](https://github.com/trufflesuite/truffle/pull/1462) Fix `truffle help <command>` lag. (@CruzMolina)
+ [#1465](https://github.com/trufflesuite/truffle/pull/1465) Upgrade test contracts to 0.5.0 and fix all resulting problems. (@haltman-at)
+ [#1466](https://github.com/trufflesuite/truffle/pull/1466) Fix intermittent failures of variable ID tests by removing fixed source IDs. (@haltman-at)
+ [#1467](https://github.com/trufflesuite/truffle/pull/1467) Fix BYOC/Solc Config Bug. (@CruzMolina)
+ [#1468](https://github.com/trufflesuite/truffle/pull/1468) Keep precompiles from affecting function depth. (@haltman-at)
+ [#1469](https://github.com/trufflesuite/truffle/pull/1469) Memoize `config.provider` to try and reuse providers. (@gnidan)
+ [#1471](https://github.com/trufflesuite/truffle/pull/1471) Restructure and fix bug with `truffle unbox`. (@eggplantzzz)
+ [#1476](https://github.com/trufflesuite/truffle/pull/1476) Suppress anonymous output parameters from `data.current.identifiers`. (@haltman-at)
+ [#1479](https://github.com/trufflesuite/truffle/pull/1479) Add an integration test for init command. (@eggplantzzz)
+ [#1481](https://github.com/trufflesuite/truffle/pull/1481) Add !<...> syntax to debugger watch expressions. (@gnidan)
+ [#1483](https://github.com/trufflesuite/truffle/pull/1483) Unabbreviate variable name for better style! (@gnidan)
+ [#1484](https://github.com/trufflesuite/truffle/pull/1484) Compartmentalize Assert.sol & Add Legacy SafeSend.sol. (@CruzMolina)
+ [#1488](https://github.com/trufflesuite/truffle/pull/1488) Correct check for `undefined` and `null` in truffle config. (@eggplantzzz)
+ [#1489](https://github.com/trufflesuite/truffle/pull/1489) Fix bug where contracts are incorrectly ignored. (@IIIIllllIIIIllllIIIIllllIIIIllllIIIIll)
+ [#1493](https://github.com/trufflesuite/truffle/pull/1493) Function depth workaround conditional on using solc version <0.5.1. (@haltman-at)
+ [#1494](https://github.com/trufflesuite/truffle/pull/1494) Strip mapping metadata from decoder output in debugger. (@gnidan)
+ [#1497](https://github.com/trufflesuite/truffle/pull/1497) Prevent the debugger reset command from being repeated with enter. (@haltman-at)
+ [#1498](https://github.com/trufflesuite/truffle/pull/1498) Revert provider memoization introduced in [#1469](https://github.com/trufflesuite/truffle/pull/1469). (@eggplantzzz)
+ [#1503](https://github.com/trufflesuite/truffle/pull/1503) Fix reduce function error in CompilerSupplier. (@eggplantzzz)
+ [#1510](https://github.com/trufflesuite/truffle/pull/1510) Vyper compiler output - handle both Windows and linux line endings. (@sgryphon)
+ [#1519](https://github.com/trufflesuite/truffle/pull/1519) Handle asynchronous 3rd party plugins (2.0). (@daniyarchambylov & @CruzMolina)
+ [#1520](https://github.com/trufflesuite/truffle/pull/1520) Add message to confirm that all breakpoints have been removed. (@haltman-at)
+ [#1521](https://github.com/trufflesuite/truffle/pull/1521) Fix truffle-hdwallet-provider webpack config. (@CruzMolina)
+ [#1522](https://github.com/trufflesuite/truffle/pull/1522) Refactor version utility methods and update version logging. (@eggplantzzz)
+ [#1524](https://github.com/trufflesuite/truffle/pull/1524) Stop saving this.mnemonic in truffle-hdwallet-provider. (@gnidan)
+ [#1526](https://github.com/trufflesuite/truffle/pull/1526) Update tests for unboxing. (@eggplantzzz)
+ [#1528](https://github.com/trufflesuite/truffle/pull/1528) Fix bug with the network id check during migrations. (@eggplantzzz)
+ [#1529](https://github.com/trufflesuite/truffle/pull/1529) Fix bug with CompilerSupplier method. (@eggplantzzz)
+ [#1537](https://github.com/trufflesuite/truffle/pull/1537) Use stringification which can handle `null` when reporting logs. (@coventry)
+ [#1539](https://github.com/trufflesuite/truffle/pull/1539) Fix bug with `truffle version`. (@eggplantzzz)
+ [#1542](https://github.com/trufflesuite/truffle/pull/1542) Update help for test command. (@eggplantzzz)
+ [#1547](https://github.com/trufflesuite/truffle/pull/1547) Stabilize options.solc. (@CruzMolina)

#### Dependency Updates
+ [#1464](https://github.com/trufflesuite/truffle/pull/1426) Add configstore dependency to truffle-config package.json. (@seesemichaelj)
+ [#1492](https://github.com/trufflesuite/truffle/pull/1492) Upgrade ganache-core & ganache-cli to latest versions. (@CruzMolina)
+ [#1495](https://github.com/trufflesuite/truffle/pull/1495) Temporarily use Truffle Web3 fork. (@eggplantzzz)
+ [#1513](https://github.com/trufflesuite/truffle/pull/1513) Use beta 37 version of Web3. (@eggplantzzz)
+ [#1515](https://github.com/trufflesuite/truffle/pull/1515) Homogenize package dependencies. (@gnidan)
+ [#1525](https://github.com/trufflesuite/truffle/pull/1525) Add missing app-module-path dependency. (@CruzMolina)
+ [#1530](https://github.com/trufflesuite/truffle/pull/1530) Specify solc v0.5.0 for Truffle. (@CruzMolina)
+ [#1548](https://github.com/trufflesuite/truffle/pull/1548) Add dev dependencies for truffle-hdwallet-provider. (@CruzMolina)