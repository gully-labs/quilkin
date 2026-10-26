<!-- gully-header:start -->
<a href="https://gullychain.xyz"><img src="https://gullychain.xyz/brand/repos/quilkin.svg" alt="GullyChain · Quilkin" width="100%"></a>

<p align="center">
  <a href="https://gullychain.xyz"><img src="https://img.shields.io/badge/gullychain.xyz-01D9FA?style=for-the-badge&labelColor=000000&logo=googlechrome&logoColor=000000" alt="Website"></a>
  <a href="https://app.gullychain.xyz"><img src="https://img.shields.io/badge/App-0A0F1A?style=for-the-badge&labelColor=000000&logo=googlechrome&logoColor=01D9FA" alt="App"></a>
  <a href="https://docs.gullychain.xyz"><img src="https://img.shields.io/badge/Docs-0A0F1A?style=for-the-badge&labelColor=000000&logo=readthedocs&logoColor=01D9FA" alt="Docs"></a>
  <a href="https://x.com/Gully_Labs"><img src="https://img.shields.io/badge/@Gully__Labs-0A0F1A?style=for-the-badge&labelColor=000000&logo=x&logoColor=white" alt="X"></a>
  <a href="https://t.me/GullyChain"><img src="https://img.shields.io/badge/Telegram-0A0F1A?style=for-the-badge&labelColor=000000&logo=telegram&logoColor=26A5E4" alt="Telegram"></a>
  <a href="https://discord.com/invite/tY2ErsNNBp"><img src="https://img.shields.io/badge/Discord-0A0F1A?style=for-the-badge&labelColor=000000&logo=discord&logoColor=5865F2" alt="Discord"></a>
  <a href="https://github.com/gully-labs"><img src="https://img.shields.io/badge/GitHub-0A0F1A?style=for-the-badge&labelColor=000000&logo=github&logoColor=white" alt="GitHub"></a>
</p>

<p align="center"><b>Quilkin: UDP proxy for Gully Studio game servers.</b></p>

<p align="center"><sub>Maintained by <a href="https://gullylabs.xyz">Gully Labs</a> as part of <a href="https://gullychain.xyz">GullyChain</a>. Fork of <a href="https://github.com/EmbarkStudios/quilkin">EmbarkStudios/quilkin</a>, used under its Apache-2.0 licence. Not affiliated with or endorsed by Embark Studios.</sub></p>

---
<!-- gully-header:end -->

<p  align="center">
    <img src="./docs/logos/logo-white.png" alt="Quilkin logo" height="220">
</p>

[![GitHub](https://img.shields.io/github/license/EmbarkStudios/quilkin)](./LICENSE)
[![Container image](https://img.shields.io/badge/ghcr.io-embarkstudios%2Fquilkin-2496ed)](https://github.com/EmbarkStudios/quilkin/pkgs/container/quilkin)
[![Release](https://img.shields.io/github/v/release/EmbarkStudios/quilkin)](https://github.com/EmbarkStudios/quilkin/releases)
[![Discord](https://img.shields.io/discord/773975408265134100)](https://discord.gg/mfBNZjBDnc)

Quilkin is a non-transparent UDP proxy specifically designed for use with large scale multiplayer dedicated game
servers deployments that ensures security, access control, telemetry data, metrics and more without the end user
having to custom build and integrate this functionality into their game clients and servers directly.

## Announcements

* [Embark Studios: Say hi to Quilkin, an open-source UDP proxy](https://medium.com/embarkstudios/say-hi-to-quilkin-an-open-source-udp-proxy-88577c795204)
* [Google Cloud: Introducing Quilkin: open-source UDP proxies built for game server communication](https://cloud.google.com/blog/products/gaming/introducing-quilkin)

## Project State

Project is currently in *beta* status, meaning that it is being actively developed, and being used in production
systems, but that the API may break and functionality may be changed or removed between releases.

## Documentation

### Development

> This documentation is for the development version of Quilkin, currently active on the `main` branch. To view the
> documentation for a specific release, see `https://embarkstudios.github.io/quilkin/<tag>/book/`.

* [Guide](https://embarkstudios.github.io/quilkin/main/book/)
* [Api](https://embarkstudios.github.io/quilkin/main/api/quilkin/)
* [Macros](https://embarkstudios.github.io/quilkin/main/api/quilkin_macros/)

## Code of Conduct

Participation in this project comes under the [Contributor Covenant Code of Conduct](code-of-conduct.md)

## Development and Contribution

Please read the [contributing](CONTRIBUTING.md) guide for directions on writing code and submitting Pull Requests.

Quilkin is in active development - we would love your help in shaping its future!

## Community

There are lots of ways to engage with the Quilkin community:

* Here on [Github](https://github.com/EmbarkStudios/quilkin) via
  [issues](https://github.com/EmbarkStudios/quilkin/issues) and
  [pull requests](https://github.com/EmbarkStudios/quilkin/pulls).
* Join our [Discord chat server](https://discord.gg/mfBNZjBDnc).

## Credits

Many concepts and architectural decisions were initially inspired by [Envoy Proxy](https://www.envoyproxy.io/).
Huge thanks to that team for the inspiration they provided with all their hard work.

## Licence

Apache 2.0

<img src="./docs/logos/mascot.png" alt="Quilly, the Quilkin mascot" height="200" align="right">
