<a name="0.1.5"></a>
## 0.1.5 (2018-08-21)


#### Features

*   hacky support of ROCKET_LOG=off ([584f758b](https://github.com/mozilla-services/megaphone/commit/584f758bfe9ca3aec83d39848b3d441baa22b092), closes [#54](https://github.com/mozilla-services/megaphone/issues/54))



<a name="0.1.4"></a>
## 0.1.4 (2018-06-27)


#### Chore

*   include /app/version.json per dockerflow ([d5978e3c](https://github.com/mozilla-services/megaphone/commit/d5978e3c9a475208965537c21d88681277876890))

#### Features

*   warn log for ACL related errors ([109476a5](https://github.com/mozilla-services/megaphone/commit/109476a5e6313de761a593b5e4dcbd18a93f34c4), closes [#48](https://github.com/mozilla-services/megaphone/issues/48))
*   render a unique errno code per error ([57025884](https://github.com/mozilla-services/megaphone/commit/57025884993b16dfdf779d414ccda9afa353dc78), closes [#46](https://github.com/mozilla-services/megaphone/issues/46))
*   validate the PUT input ([6fbf572d](https://github.com/mozilla-services/megaphone/commit/6fbf572d685a32c7b60fbb0b7531422fbbd0781d), closes [#24](https://github.com/mozilla-services/megaphone/issues/24))
*   add a docker compose setup ([2c1aa8f1](https://github.com/mozilla-services/megaphone/commit/2c1aa8f1441d8b66eb23c8370c18806738fdc674), closes [#43](https://github.com/mozilla-services/megaphone/issues/43))
*   create a logging setup via slog/slog-mozlog-json ([c7353f7e](https://github.com/mozilla-services/megaphone/commit/c7353f7e167a34aa7617cc23ac9489f395d77ff4), closes [#9](https://github.com/mozilla-services/megaphone/issues/9))



<a name="0.1.3"></a>
## 0.1.3 (2018-05-17)


#### Bug Fixes

*   lheartbeat -> lbheartbeat ([2d8bf644](https://github.com/mozilla-services/megaphone/commit/2d8bf644ba65bd6aaa65a70510a33db6dfaaac8e), closes [#40](https://github.com/mozilla-services/megaphone/issues/40))



<a name="0.1.2"></a>
## 0.1.2 (2018-05-16)


#### Features

*   upgrade to rocket 0.3.10 ([45d3b004](https://github.com/mozilla-services/megaphone/commit/45d3b0047fa5843049518ea7df780eb442bd89f1), closes [#36](https://github.com/mozilla-services/megaphone/issues/36))



<a name="0.1.1"></a>
## 0.1.1 (2018-04-06)


#### Chore

*   install openssh-client git & git on docker-in-docker ([f81d556a](https://github.com/mozilla-services/megaphone/commit/f81d556a415d7e775e358373df22e125d0c37406))



<a name="0.1.0"></a>
## 0.1.0 (2018-04-05)


#### Bug Fixes

*   use mysql, not postgres ([0130713f](https://github.com/mozilla-services/megaphone/commit/0130713fac7f30b986043f7d0ea74e40a234cecb))

#### Features

*   peg Docker build to rust nightly-2018-04-04 ([f17d4924](https://github.com/mozilla-services/megaphone/commit/f17d4924e2f0a74026540e47cbc3a669acc071f9), closes [#25](https://github.com/mozilla-services/megaphone/issues/25))
*   peg builds w/ a Cargo.lock ([e359991f](https://github.com/mozilla-services/megaphone/commit/e359991f235b7f5c1e9eee5e1ef0f51d2419d3a2), closes [#29](https://github.com/mozilla-services/megaphone/issues/29))
*   add a .clog.toml and CONTRIBUTING.md ([f2a33e7a](https://github.com/mozilla-services/megaphone/commit/f2a33e7a578a67da593aa6491396e0a184d101c1), closes [#27](https://github.com/mozilla-services/megaphone/issues/27))
*   switch REPLACE INTO -> INSERT ON DUPLICATE KEY UPDATE ([f09af1c0](https://github.com/mozilla-services/megaphone/commit/f09af1c0cdf807deae7863ad034b3e2caf5c0ec5), closes [#19](https://github.com/mozilla-services/megaphone/issues/19))
*   return WWW-Authenticate on 401s ([348f3e91](https://github.com/mozilla-services/megaphone/commit/348f3e919380c5d3f7ea8913c6d1fbced593feb9), closes [#21](https://github.com/mozilla-services/megaphone/issues/21))
*   use diesel's embedded migrations ([64e00c83](https://github.com/mozilla-services/megaphone/commit/64e00c83e43542ff86dfdcbd8e674395b858ce6e), closes [#17](https://github.com/mozilla-services/megaphone/issues/17))
*   cleanup Config usage ([e5ddf43e](https://github.com/mozilla-services/megaphone/commit/e5ddf43ef1ac910b1202fc6c687fd1d828fafb0c), closes [#16](https://github.com/mozilla-services/megaphone/issues/16))
*   handle auth via Bearer tokens ([91e28568](https://github.com/mozilla-services/megaphone/commit/91e28568b2b28f51642b29d649c23b3f71b3e767), closes [#7](https://github.com/mozilla-services/megaphone/issues/7))
*   add Dockerflow styled health/version checks ([cb616611](https://github.com/mozilla-services/megaphone/commit/cb61661172906fed34ce0b1ba12ee7796fde61f4), closes [#11](https://github.com/mozilla-services/megaphone/issues/11))
*   add a Dockerfile based on debian stretch-slim ([e66b6cc9](https://github.com/mozilla-services/megaphone/commit/e66b6cc98905823ab36b808bf1b8d06c6da74a02), closes [#12](https://github.com/mozilla-services/megaphone/issues/12))
*   initial prototype from the wip branch ([9e6f9b28](https://github.com/mozilla-services/megaphone/commit/9e6f9b289b12df6e5f10ac4a0f1d07ffce5b2777))



<a name="0.1.0"></a>
## 0.1.0 (2018-04-05)


#### Bug Fixes

*   use mysql, not postgres ([0130713f](https://github.com/mozilla-services/megaphone/commit/0130713fac7f30b986043f7d0ea74e40a234cecb))

#### Features

*   peg Docker build to rust nightly-2018-04-04 ([f17d4924](https://github.com/mozilla-services/megaphone/commit/f17d4924e2f0a74026540e47cbc3a669acc071f9), closes [#25](https://github.com/mozilla-services/megaphone/issues/25))
*   peg builds w/ a Cargo.lock ([e359991f](https://github.com/mozilla-services/megaphone/commit/e359991f235b7f5c1e9eee5e1ef0f51d2419d3a2), closes [#29](https://github.com/mozilla-services/megaphone/issues/29))
*   add a .clog.toml and CONTRIBUTING.md ([f2a33e7a](https://github.com/mozilla-services/megaphone/commit/f2a33e7a578a67da593aa6491396e0a184d101c1), closes [#27](https://github.com/mozilla-services/megaphone/issues/27))
*   switch REPLACE INTO -> INSERT ON DUPLICATE KEY UPDATE ([f09af1c0](https://github.com/mozilla-services/megaphone/commit/f09af1c0cdf807deae7863ad034b3e2caf5c0ec5), closes [#19](https://github.com/mozilla-services/megaphone/issues/19))
*   return WWW-Authenticate on 401s ([348f3e91](https://github.com/mozilla-services/megaphone/commit/348f3e919380c5d3f7ea8913c6d1fbced593feb9), closes [#21](https://github.com/mozilla-services/megaphone/issues/21))
*   use diesel's embedded migrations ([64e00c83](https://github.com/mozilla-services/megaphone/commit/64e00c83e43542ff86dfdcbd8e674395b858ce6e), closes [#17](https://github.com/mozilla-services/megaphone/issues/17))
*   cleanup Config usage ([e5ddf43e](https://github.com/mozilla-services/megaphone/commit/e5ddf43ef1ac910b1202fc6c687fd1d828fafb0c), closes [#16](https://github.com/mozilla-services/megaphone/issues/16))
*   handle auth via Bearer tokens ([91e28568](https://github.com/mozilla-services/megaphone/commit/91e28568b2b28f51642b29d649c23b3f71b3e767), closes [#7](https://github.com/mozilla-services/megaphone/issues/7))
*   add Dockerflow styled health/version checks ([cb616611](https://github.com/mozilla-services/megaphone/commit/cb61661172906fed34ce0b1ba12ee7796fde61f4), closes [#11](https://github.com/mozilla-services/megaphone/issues/11))
*   add a Dockerfile based on debian stretch-slim ([e66b6cc9](https://github.com/mozilla-services/megaphone/commit/e66b6cc98905823ab36b808bf1b8d06c6da74a02), closes [#12](https://github.com/mozilla-services/megaphone/issues/12))
*   initial prototype from the wip branch ([9e6f9b28](https://github.com/mozilla-services/megaphone/commit/9e6f9b289b12df6e5f10ac4a0f1d07ffce5b2777))



