[//]: # "NOTE: THIS FILE WAS AUTOGENERATED FROM README.md"

# Spotless

If you happen to be using Gradle, the [Spotless](https://github.com/diffplug/spotless/tree/main/plugin-gradle) plugin has support for black. Spotless gives you the option to

- [ratchet](https://github.com/diffplug/spotless/tree/main/plugin-gradle#ratchet) your formatting so that only files which have changed since `origin/main` get formatted
- slurp copyright info from [git history](https://github.com/diffplug/spotless/tree/main/plugin-gradle#license-header)
- seamlessly integrate with [prettier](https://github.com/diffplug/spotless/tree/main/plugin-gradle#prettier), [clang-format](https://github.com/diffplug/spotless/tree/main/plugin-gradle#clang-format), and other formatters if your project happens to be polyglot
- (Spotless also has a maven plugin, but waiting on an easy PR for black support)