# todo

## Resolver
- [x] Create a DNS Resolver struct
- [x] Add methods to initialise the config, set defaults
- [x] Add a resolve method
- [x] Make it separate from Hub
- [x] Parse output into separate fields
- [x] Test IPv6/IPv4 only options
- [x] Add DOH support
- [x] Add DOT support
- [x] Add DNS protocol on TCP mode support.
  - [x] Change lookup method.
- [x] Major records supported
- [x] Support multiple resolvers
  - [x] Take multiple transport options and initialise resolvers accordingly.
- [x] Add timeout support
- [x] Support SOA/NXDOMAIN

## CLI Features
- [x] `ndots` support
- [x] `search list` support
- [x] JSON output
- [x] Colorized output
- [x] Table output
- [x] Parsing options free-form

## CLI Grunt
- [x] Query args
- [x] Neatly package them to load args in different functions
- [x] Upper case is not mandatory for query type/classes
- [x] Output
- [x] Custom Help Text
  - [x] Add examples
  - [x] Colorize
  - [x] Add different commands
- [x] Add client transport options
- [x] Fix an issue while loading free form args, where the same records are being added twice
- [x] Remove urfave/cli in favour of `pflag + koanf`
- [x] Flags - Remove unneeded ones

## Documentation
- [x] README
  - [x] Usage
  - [x] Installation
  - [x] Features


## Release Checklist
- [x] Goreleaser
  - [x] Snap
  - [x] Docker
---
# Future Release

- [x] Support obscure protocol tweaks in `dig`
- [x] Support more DNS Record Types
- [x] Shell completions
  - [x] zsh
  - [x] fish
- [x] Homebrew - Goreleaser
- [x] Add `dig +short` short output
- [x] Add `--strategy` for picking nameservers.
- [x] Separate Authority/Answer in JSON output.
- [x] Error on NXDomain (Related upstream [bug](https://github.com/miekg/dns/issues/1198))
- [x] Reverse Lookup (dig -x)
- [x] Shell completion proper
- [x] CLI docs
- [x] Merge those as misc docs or usage
- [x] Example Guide

- [ ] Add tests for Resolvers.
- [ ] Add tests for CLI Output.
- [ ] Add support for `dig +trace` like functionality.
- [ ] Explore `dig.rc` kinda file
