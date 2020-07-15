# shadowsocksR

**A fork of [sun8911879/shadowsocksR](https://github.com/sun8911879/shadowsocksR).**

[shadowsocksR](https://github.com/mzz2017/shadowsocksR) is a shadowsocksR for Go library

* shadowsocksR is based on [avege](https://github.com/avege/avege) and [shadowsocksR for Python](https://github.com/shadowsocksr-backup/shadowsocksr) changes. 
* Repair avege SSR communication BUG and streamline version. Is a normal use version.

#### Use

See 'example/main.go' for detailed usage.

#### SS Encrypting algorithm

* aes-128-cfb
* aes-192-cfb
* aes-256-cfb
* aes-128-ctr
* aes-192-ctr
* aes-256-ctr
* aes-128-ofb
* aes-192-ofb
* aes-256-ofb
* des-cfb
* bf-cfb
* cast5-cfb
* rc4-md5
* chacha20
* chacha20-ietf
* salsa20
* camellia-128-cfb
* camellia-192-cfb
* camellia-256-cfb
* idea-cfb
* rc2-cfb
* seed-cfb
* none

#### SSR Obfs

- plain
- http_simple
- http_post
- random_head
- tls1.2_ticket_auth

#### SSR Protocol

- origin
- verify_sha1 aka. one time auth(OTA)
- auth_sha1_v4
- auth_aes128_md5
- auth_aes128_sha1
- auth_chain_a
- auth_chain_b

## Todo (help wanted)

* Optimize performance

### Thanks avege project
* [avege](https://github.com/avege/avege)

### Reference
* [avege](https://github.com/avege/avege)
* [shadowsocks-go](https://github.com/shadowsocks/shadowsocks-go)
* [go-shadowsocks2](https://github.com/shadowsocks/go-shadowsocks2)
* [ShadowsocksR](https://github.com/shadowsocksr-backup/shadowsocksr)
* [shadowsocksr-libev](https://github.com/shadowsocksrr/shadowsocksr-libev)