# Stash v2021.10.11 (2021-10-09)


## [appscode/stash-enterprise](https://github.com/appscode/stash-enterprise)

### [v0.16.0](https://github.com/appscode/stash-enterprise/releases/tag/v0.16.0)

- [34fe50bb](https://github.com/appscode/stash-enterprise/commit/34fe50bb) Prepare for release v0.16.0 (#126)
- [4807ec4c](https://github.com/appscode/stash-enterprise/commit/4807ec4c) Fix jwt-go security vulnerability (#125)
- [f1160998](https://github.com/appscode/stash-enterprise/commit/f1160998) Merge pull request #123 from appscode/etcd-permission
- [ce3cd3f8](https://github.com/appscode/stash-enterprise/commit/ce3cd3f8) Add support for ETCD restore flow
- [834d8c13](https://github.com/appscode/stash-enterprise/commit/834d8c13) Use nats.go v1.13.0 (#124)
- [446ee320](https://github.com/appscode/stash-enterprise/commit/446ee320) Update dependencies to publish SiteInfo (#122)
- [5d56e0f6](https://github.com/appscode/stash-enterprise/commit/5d56e0f6) Support passing args to restic backup/restore command (#120)
- [f10ab0dc](https://github.com/appscode/stash-enterprise/commit/f10ab0dc) Fix license-reader ClusterRoleBinding not cleaning up properly
- [dffe5c41](https://github.com/appscode/stash-enterprise/commit/dffe5c41) Update go.mod
- [c124a770](https://github.com/appscode/stash-enterprise/commit/c124a770) Undo changes of jobs.go
- [cc7f4827](https://github.com/appscode/stash-enterprise/commit/cc7f4827) fix clusterrolebinding issue
- [13ed9752](https://github.com/appscode/stash-enterprise/commit/13ed9752) Log warning if Community License is used with non-demo namespace (#119)
- [0026511c](https://github.com/appscode/stash-enterprise/commit/0026511c) Merge pull request #117 from appscode/fix-cronjob-name-prefix
- [ba3f466c](https://github.com/appscode/stash-enterprise/commit/ba3f466c) Use `stash-trigger` as backup triggering CronJob name prefix
- [d353c393](https://github.com/appscode/stash-enterprise/commit/d353c393) Use official restic v0.12.1 (#116)
- [e9b1db7e](https://github.com/appscode/stash-enterprise/commit/e9b1db7e) Update repository config (#115)
- [ea1895fc](https://github.com/appscode/stash-enterprise/commit/ea1895fc) Update dependencies (#114)



## [stashed/apimachinery](https://github.com/stashed/apimachinery)

### [v0.16.0](https://github.com/stashed/apimachinery/releases/tag/v0.16.0)

- [e5b1aaea](https://github.com/stashed/apimachinery/commit/e5b1aaea) Fix jwt-go security vulnerability (#129)
- [065a6d36](https://github.com/stashed/apimachinery/commit/065a6d36) Fix jwt-go security vulnerability (#128)
- [561988c6](https://github.com/stashed/apimachinery/commit/561988c6) Add condition for indicating restore completion (#127)
- [3ddabb57](https://github.com/stashed/apimachinery/commit/3ddabb57) Add "Running" phase for the individual restore host (#126)
- [1c75b4ce](https://github.com/stashed/apimachinery/commit/1c75b4ce) Support passing arguments to restic backup/restore command (#121)
- [307b411a](https://github.com/stashed/apimachinery/commit/307b411a) Update dependencies to publish SiteInfo (#125)
- [ce72641a](https://github.com/stashed/apimachinery/commit/ce72641a) Update dependencies to publish SiteInfo (#124)
- [322437d9](https://github.com/stashed/apimachinery/commit/322437d9) Show actual repo size instead of logical size (#123)
- [5e773145](https://github.com/stashed/apimachinery/commit/5e773145) Return new labels by EnsureKubeDBIntegration function  (#122)
- [908628b7](https://github.com/stashed/apimachinery/commit/908628b7) Update repository config (#120)
- [a7994a77](https://github.com/stashed/apimachinery/commit/a7994a77) Add `ADDON_IMAGE` variable for Etcd Addons
- [16529919](https://github.com/stashed/apimachinery/commit/16529919) Run `make fmt`
- [78077d32](https://github.com/stashed/apimachinery/commit/78077d32) Merge branch 'master' into etcd-flag
- [163e7863](https://github.com/stashed/apimachinery/commit/163e7863) Set RESTIC_PROGRESS_FPS in restic wrapper shell
- [b0983010](https://github.com/stashed/apimachinery/commit/b0983010) Merge branch 'master' into progress-fps
- [72b73523](https://github.com/stashed/apimachinery/commit/72b73523) Log warning if Community License is used with non-demo namespace (#119)
- [2eecfe50](https://github.com/stashed/apimachinery/commit/2eecfe50) Merge branch 'master' into etcd-flag
- [b0141c12](https://github.com/stashed/apimachinery/commit/b0141c12) Add addon image flag
- [c1e37507](https://github.com/stashed/apimachinery/commit/c1e37507) Set RESTIC_PROGRESS_FPS in restic wrapper shell
- [fda29913](https://github.com/stashed/apimachinery/commit/fda29913) Merge pull request #116 from stashed/fix-cronjob-name-prefix
- [8cbe8b9d](https://github.com/stashed/apimachinery/commit/8cbe8b9d) Add constants for backup triggering CronJob
- [78e6bc8c](https://github.com/stashed/apimachinery/commit/78e6bc8c) Use official restic v0.12.1 (#115)
- [01704d74](https://github.com/stashed/apimachinery/commit/01704d74) Update repository config (#114)
- [d9f1899d](https://github.com/stashed/apimachinery/commit/d9f1899d) Update dependencies (#113)
- [639e36ec](https://github.com/stashed/apimachinery/commit/639e36ec) Update dependencies (#112)
- [ffb5a0c7](https://github.com/stashed/apimachinery/commit/ffb5a0c7) Update dependencies (#111)
- [cdbb8e52](https://github.com/stashed/apimachinery/commit/cdbb8e52) Update repository config (#110)
- [ae94693a](https://github.com/stashed/apimachinery/commit/ae94693a) Update repository config (#109)



## [stashed/cli](https://github.com/stashed/cli)

### [v0.16.0](https://github.com/stashed/cli/releases/tag/v0.16.0)

- [1fb811f](https://github.com/stashed/cli/commit/1fb811f) Prepare for release v0.16.0 (#142)
- [c1b8251](https://github.com/stashed/cli/commit/c1b8251) Fix jwt-go security vulnerability (#141)
- [23689bb](https://github.com/stashed/cli/commit/23689bb) Fix jwt-go security vulnerability (#140)
- [fc3ffb8](https://github.com/stashed/cli/commit/fc3ffb8) Set restic docker image tag from Makefile during build (#137)
- [56a8b85](https://github.com/stashed/cli/commit/56a8b85) Update dependencies to publish SiteInfo (#139)
- [d8df9e8](https://github.com/stashed/cli/commit/d8df9e8) Update dependencies to publish SiteInfo (#138)
- [c7fb370](https://github.com/stashed/cli/commit/c7fb370) Log warning if Community License is used with non-demo namespace (#136)
- [11397c0](https://github.com/stashed/cli/commit/11397c0) Use official restic v0.12.1 (#135)
- [24ae84f](https://github.com/stashed/cli/commit/24ae84f) Update dependencies (#134)
- [91ab122](https://github.com/stashed/cli/commit/91ab122) Update repository config (#133)
- [47ca564](https://github.com/stashed/cli/commit/47ca564) Update dependencies (#132)
- [3d1a293](https://github.com/stashed/cli/commit/3d1a293) Update dependencies (#131)
- [f9b4bcc](https://github.com/stashed/cli/commit/f9b4bcc) Update dependencies (#130)
- [b2331c7](https://github.com/stashed/cli/commit/b2331c7) Update README.md



## [stashed/postgres](https://github.com/stashed/postgres)

### [10.14-v11](https://github.com/stashed/postgres/releases/tag/10.14-v11)

- [022910d2](https://github.com/stashed/postgres/commit/022910d2) Prepare for release 10.14-v11 (#930)
- [df4ea88e](https://github.com/stashed/postgres/commit/df4ea88e) [cherry-pick] Fix jwt-go security vulnerability (#923) (#924)
- [37492e25](https://github.com/stashed/postgres/commit/37492e25) [cherry-pick] Fix jwt-go security vulnerability (#916) (#917)
- [c36fd40d](https://github.com/stashed/postgres/commit/c36fd40d) [cherry-pick] Update dependencies to publish SiteInfo (#910) (#911)
- [40364b31](https://github.com/stashed/postgres/commit/40364b31) [cherry-pick] Update dependencies to publish SiteInfo (#904) (#905)
- [c7e6e42d](https://github.com/stashed/postgres/commit/c7e6e42d) [cherry-pick] Log warning if Community License is used with non-demo namespace (#897) (#898)
- [a7a14804](https://github.com/stashed/postgres/commit/a7a14804) [cherry-pick] Use official restic v0.12.1 (#891) (#892)
- [62f39a5a](https://github.com/stashed/postgres/commit/62f39a5a) [cherry-pick] Update repository config (#885) (#886)
- [c8c626dd](https://github.com/stashed/postgres/commit/c8c626dd) [cherry-pick] Update dependencies (#879) (#880)
- [8cca6897](https://github.com/stashed/postgres/commit/8cca6897) [cherry-pick] Update dependencies (#873) (#874)
- [2b8823ac](https://github.com/stashed/postgres/commit/2b8823ac) [cherry-pick] Update dependencies (#867) (#868)
- [de1290b4](https://github.com/stashed/postgres/commit/de1290b4) [cherry-pick] Use user nobody (#862)
- [9d8e96ed](https://github.com/stashed/postgres/commit/9d8e96ed) [cherry-pick] Update repository config (#856) (#857)
- [49ab6354](https://github.com/stashed/postgres/commit/49ab6354) [cherry-pick] Update repository config (#850) (#851)
- [ac88e3c1](https://github.com/stashed/postgres/commit/ac88e3c1) [cherry-pick] Update README.md (#845)


### [11.9-v11](https://github.com/stashed/postgres/releases/tag/11.9-v11)

- [809eb881](https://github.com/stashed/postgres/commit/809eb881) Prepare for release 11.9-v11 (#931)
- [f8df2138](https://github.com/stashed/postgres/commit/f8df2138) [cherry-pick] Fix jwt-go security vulnerability (#923) (#925)
- [a5fcf2d7](https://github.com/stashed/postgres/commit/a5fcf2d7) [cherry-pick] Fix jwt-go security vulnerability (#916) (#918)
- [bc9b05a7](https://github.com/stashed/postgres/commit/bc9b05a7) [cherry-pick] Update dependencies to publish SiteInfo (#910) (#912)
- [eba577ca](https://github.com/stashed/postgres/commit/eba577ca) [cherry-pick] Update dependencies to publish SiteInfo (#904) (#906)
- [dd7e5b3c](https://github.com/stashed/postgres/commit/dd7e5b3c) [cherry-pick] Log warning if Community License is used with non-demo namespace (#897) (#899)
- [dbc851fe](https://github.com/stashed/postgres/commit/dbc851fe) [cherry-pick] Use official restic v0.12.1 (#891) (#893)
- [96c10215](https://github.com/stashed/postgres/commit/96c10215) [cherry-pick] Update repository config (#885) (#887)
- [89f96f4f](https://github.com/stashed/postgres/commit/89f96f4f) [cherry-pick] Update dependencies (#879) (#881)
- [540665e0](https://github.com/stashed/postgres/commit/540665e0) [cherry-pick] Update dependencies (#873) (#875)
- [89108c2e](https://github.com/stashed/postgres/commit/89108c2e) [cherry-pick] Update dependencies (#867) (#869)
- [6fb330f8](https://github.com/stashed/postgres/commit/6fb330f8) [cherry-pick] Use user nobody (#863)
- [057473bc](https://github.com/stashed/postgres/commit/057473bc) [cherry-pick] Update repository config (#856) (#858)
- [9387dbe7](https://github.com/stashed/postgres/commit/9387dbe7) [cherry-pick] Update repository config (#850) (#852)
- [0dda31f0](https://github.com/stashed/postgres/commit/0dda31f0) [cherry-pick] Update README.md (#846)



## [stashed/stash](https://github.com/stashed/stash)

### [v0.16.0](https://github.com/stashed/stash/releases/tag/v0.16.0)

- [535efca8](https://github.com/stashed/stash/commit/535efca8) Prepare for release v0.16.0 (#1394)
- [7c26c7dd](https://github.com/stashed/stash/commit/7c26c7dd) Fix jwt-go security vulnerability (#1393)
- [8f63f724](https://github.com/stashed/stash/commit/8f63f724) Add support for ETCD restore flow (#1392)
- [5665ea7e](https://github.com/stashed/stash/commit/5665ea7e) Use nats.go v1.13.0 (#1391)
- [cc2da916](https://github.com/stashed/stash/commit/cc2da916) Setup SiteInfo publisher (#1390)
- [8daab52d](https://github.com/stashed/stash/commit/8daab52d) Update dependencies to publish SiteInfo (#1389)
- [50b58218](https://github.com/stashed/stash/commit/50b58218) Support passing args to restic backup/restore command (#1385)
- [28d878ed](https://github.com/stashed/stash/commit/28d878ed) Update dependencies to publish SiteInfo (#1387)
- [c063a536](https://github.com/stashed/stash/commit/c063a536) Fix license-reader ClusterRoleBinding not cleaning up properly  (#1386)
- [e09bd7b0](https://github.com/stashed/stash/commit/e09bd7b0) Log warning if Community License is used with non-demo namespace (#1383)
- [3da6094c](https://github.com/stashed/stash/commit/3da6094c) Use stash-trigger as backup triggering CronJob name prefix #1382
- [e08ce8f6](https://github.com/stashed/stash/commit/e08ce8f6) Use `stash-trigger` as backup triggering CronJob name prefix
- [5027ae41](https://github.com/stashed/stash/commit/5027ae41) Use official restic v0.12.1 (#1381)
- [f23d8f42](https://github.com/stashed/stash/commit/f23d8f42) Update repository config (#1379)
- [0348419d](https://github.com/stashed/stash/commit/0348419d) Update dependencies (#1378)
- [0f6400d5](https://github.com/stashed/stash/commit/0f6400d5) Update repository config (#1375)



