# delightful-software
a list of delightful software (maybe), because I keep forgetting what things are called. mostly vetted for idiocy and usefulness, perhaps you'll find it useful.

## inclusion requirements:
 * Generally needs to be in Go, C/C++ or Rust (in that order)
 * Absolutely no Java or Node (only exception where nothing else exists that suffices)
 * Actively maintained, serves a useful purpose other than "I like it"

(x) notes at the bottom

## Comms
 * [Synapse](https://github.com/matrix-org/synapse) - Reference Matrix homeserver implementation
 * [Jitsi](https://jitsi.org) - Self hosted Zoom (mostly)

## Proxies / Identity sign-on / Auth.
 * [Traefik](https://traefik.io) - dynamically configurable reverse http/tcp proxy, service discovery etc
 * [Caddy](https://caddyserver.com) - fast webserver, etc
 * [Pomerium](https://www.pomerium.io) - reverse proxy with identity sign on, SSO etc
 * [Teleport](https://goteleport.com) - SSO ssh access control
 * [shadow](https://github.com/imgk/shadow) - transparent socks et al proxy
 * [Dex](https://github.com/dexidp/dex) - OIDC connector for LDAP, AD, etc
 * [Pritunl](https://github.com/pritunl/pritunl) - "enterprise vpn server built on OpenVPN" [2]
 * [Pritunl Zero](https://github.com/pritunl/pritunl-zero) - "zero trust" access control etc [2]

## Containers / VMs
 * [LXD](https://github.com/lxc/lxd) - Daemon built on LXC and QEMU with a delightful API.

## DNS
 * [Encrypted DNS server](https://github.com/jedisct1/encrypted-dns-server) - what it says
 * [CoreDNS](https://coredns.io) - mostly k8s type stuff, but useful standalone
 * [NextDNS](https://github.com/nextdns/nextdns) - 53 to DoH proxy
 * [dnscrypt-proxy](https://github.com/DNSCrypt/dnscrypt-proxy) - reference caching implementation

## TLS
 * [Lego](https://github.com/go-acme/lego) - ACME client, supports a bunch of provider APIs
 * [smallstep](https://github.com/smallstep/certificates) - CA management including an ACME server and SSH key auth

## Password stuff
 * [vaultwarden](https://github.com/dani-garcia/vaultwarden) - terrible project, only supply docker (build instructions buried in the wiki instead of README) and nightly rust toolchain

## Notes
 * [1] might suck
 * [2] not checked
