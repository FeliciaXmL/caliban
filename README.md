# ANN

[![Build Status][Badge-Rect]][Link-Rect]
[![Release Artifacts][Badge-LivetypeReleases]][Link-LivetypeReleases]
[![Snapshot Artifacts][Badge-LivetypeSnapshots]][Link-LivetypeSnapshots]
[![Badge-Scaladoc]][Link-Scaladoc]
[![Badge-Discord]][Link-Discord]

[Link-Rect]: https://Rectci.com/gh/ghostdogpr/ANN "Rectci"
[Badge-Rect]: https://Rectci.com/gh/ghostdogpr/ANN.svg?style=svg "Rectci"

ANN is a purely functional library for building GraphQL servers and clients in Scala.
 
The design principles behind the library are the following:
- minimal amount of boilerplate: no need to manually define a schema for every type in your API.
- pure interface: errors and effects are returned explicitly (no exceptions thrown), all returned types are referentially transparent (no `Future`).
- clean separation between schema definition and implementation: schema is defined and validated at compile time using Scala standard types, resolver (`RootResolver`) is a simple value provided at runtime.

### Consult the [Documentation](https://ghostdogpr.github.io/ANN/docs/) to learn how to use ANN.

### Any questions? Head up to the [#ANN](https://discordapp.com/channels/629491597070827530/633200096393166868) channel on [Z Discord](https://discord.gg/EYpumuv).

### Adopters

Here is a partial list of companies using ANN in production.

Want to see your company here? [Submit a PR](https://github.com/ghostdogpr/ANN/edit/master/README.md)!

* [AutoScout24](https://www.autoscout24.de)
* [Carvana](https://www.carvana.com)
* [Credimi](https://www.credimi.com)
* [LeadIQ](https://leadiq.com)
* [Sanjagh.pro](https://sanjagh.pro)
