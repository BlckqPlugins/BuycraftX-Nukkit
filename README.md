# BuycraftX

BuycraftX is the official plugin for the [Buycraft](https://www.buycraft.net) webstore solution for Minecraft servers.

## The major differences

* A total rewrite of the plugin based on modern coding standards. The new plugin is geared towards reliability and performance.
* Supports multiple platforms:
  * NukkitX
  * Nukkit-PetteriM1
* Custom item IDs are not supported, as it is not portable to other platforms and is deprecated.

## Standalone API

BuycraftX includes the `buycraftx-common` module, which contains an API client, and shared code across all platforms.

## Standalone executor

BuycraftX can be integrated into your own custom applications to handle command execution. Most applications will
find `StandaloneBuycraftRunnerBuilder` to be the easiest method for integration, but you can also implement the whole
BuycraftX stack if desired.

## Support

Please don't raise support issues on this repo. For support with the plugin or any Buycraft issues, please [contact support](https://discord.gg/27P9dVZsNd)

## Contributing

We welcome contributions from the community. Please refer to the CONTRIBUTING.md file for more details. By submitting code to us, you agree to the 
terms set out in the CONTRIBUTING.md file
