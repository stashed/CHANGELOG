# Stash v2022.02.22 (2022-02-11)


## [stashed/apimachinery](https://github.com/stashed/apimachinery)

### [v0.18.0](https://github.com/stashed/apimachinery/releases/tag/v0.18.0)

- [79d844fb](https://github.com/stashed/apimachinery/commit/79d844fb) Refactor restore invoker status updater logic (#152)
- [49e0fc85](https://github.com/stashed/apimachinery/commit/49e0fc85) Update SiteInfo (#151)
- [7c80de5c](https://github.com/stashed/apimachinery/commit/7c80de5c) Publish GenericResource (#150)
- [0906fab7](https://github.com/stashed/apimachinery/commit/0906fab7) Add stash-crd-installer image to install CRDs on helm pre-install hook (#145)
- [9c528743](https://github.com/stashed/apimachinery/commit/9c528743) Add phase field to backupconfiguration status. (#144)
- [3e17dd8d](https://github.com/stashed/apimachinery/commit/3e17dd8d) Refactor `metrics.go` file + Add `pushgatewayURL` singletone (#149)
- [553a63a8](https://github.com/stashed/apimachinery/commit/553a63a8) Add `GetCaPath()` method (#148)
- [3f6beb6d](https://github.com/stashed/apimachinery/commit/3f6beb6d) Update repository config (#147)
- [d7bf57bf](https://github.com/stashed/apimachinery/commit/d7bf57bf) Refactor invoker package (#146)
- [7da4b19c](https://github.com/stashed/apimachinery/commit/7da4b19c) Add method to create ResticWrapper from existing shell (#143)
- [68c89614](https://github.com/stashed/apimachinery/commit/68c89614) Show Snapshot ID in kubectl list command (#141)
- [8017cd43](https://github.com/stashed/apimachinery/commit/8017cd43) Review ui apis (#142)
- [d19cc472](https://github.com/stashed/apimachinery/commit/d19cc472) Modify BackupOverview API (#140)
- [c60601b5](https://github.com/stashed/apimachinery/commit/c60601b5) Add helper method for UsagePolicy (#139)
- [bc75d16a](https://github.com/stashed/apimachinery/commit/bc75d16a) Add support for cross-namespace repository (#136)
- [e845509f](https://github.com/stashed/apimachinery/commit/e845509f) Add ui types (#137)
- [6402d026](https://github.com/stashed/apimachinery/commit/6402d026) Allow cross namespace referencing for Repository + Cleanup old APIs (#135)
- [e914179d](https://github.com/stashed/apimachinery/commit/e914179d) Update repository config (#134)



## [stashed/enterprise](https://github.com/stashed/enterprise)

### [v0.18.0](https://github.com/stashed/enterprise/releases/tag/v0.18.0)

- [fcf0f4f5](https://github.com/stashed/enterprise/commit/fcf0f4f5) Prepare for release v0.18.0 (#147)
- [55a9a92d](https://github.com/stashed/enterprise/commit/55a9a92d) Update UID generation for GenericResource (#146)
- [cb30a32f](https://github.com/stashed/enterprise/commit/cb30a32f) Refactor restore process status handling + add cross namespace tests (#145)
- [3f50cb35](https://github.com/stashed/enterprise/commit/3f50cb35) Update SiteInfo (#144)
- [ac18da55](https://github.com/stashed/enterprise/commit/ac18da55) Publish GenericResource (#143)
- [efcb6727](https://github.com/stashed/enterprise/commit/efcb6727) Expose original UID for audit events
- [301f2a56](https://github.com/stashed/enterprise/commit/301f2a56) Always set type meta for GenericResource
- [ccfc9ccf](https://github.com/stashed/enterprise/commit/ccfc9ccf) Publish GenericResource (#142)
- [477401a6](https://github.com/stashed/enterprise/commit/477401a6) Don't register CRDs from operator + allow passing crd-installer tag (#138)
- [fc98dd68](https://github.com/stashed/enterprise/commit/fc98dd68) Add validation webhooks for double opt-in check (#137)
- [1fb0d151](https://github.com/stashed/enterprise/commit/1fb0d151) Always keep the last completed backup (when `backupHistoryLimit > 0`) even if outside of history limit (#141)
- [db7fdbf3](https://github.com/stashed/enterprise/commit/db7fdbf3) Add support for custom Pushgateway (#140)
- [83940a05](https://github.com/stashed/enterprise/commit/83940a05) Use refactored invoker package (#139)
- [7a2d8610](https://github.com/stashed/enterprise/commit/7a2d8610) Cleanup legacy code + Support cross namespace Repository reference (#136)



## [stashed/stash](https://github.com/stashed/stash)

### [v0.18.0](https://github.com/stashed/stash/releases/tag/v0.18.0)

- [9536bc1b](https://github.com/stashed/stash/commit/9536bc1b) Prepare for release v0.18.0 (#1421)
- [0c84840e](https://github.com/stashed/stash/commit/0c84840e) Update UID generation for GenericResource (#1420)
- [2162c125](https://github.com/stashed/stash/commit/2162c125) Refactor restore process status handling + add cross namespace tests (#1419)
- [080ebfcf](https://github.com/stashed/stash/commit/080ebfcf) Update SiteInfo (#1418)
- [2727c071](https://github.com/stashed/stash/commit/2727c071) Publish GenericResource (#1416)
- [dd6b10f0](https://github.com/stashed/stash/commit/dd6b10f0) Expose original UID for generic resource
- [a121b8c3](https://github.com/stashed/stash/commit/a121b8c3) Always set type meta for GenericResource
- [9300292a](https://github.com/stashed/stash/commit/9300292a) Publish GenericResource (#1415)
- [ffe0d847](https://github.com/stashed/stash/commit/ffe0d847) Don't register CRDs from operator + allow passing crd-installer tag (#1409)
- [eb69ad4e](https://github.com/stashed/stash/commit/eb69ad4e) Port UsagePolicy validation related changes from Enterprise operator (#1414)
- [06988c00](https://github.com/stashed/stash/commit/06988c00) Always keep the last completed BackupSession (when `backupHistoryLimit > 0`) even if outside of history limit (#1413)
- [c81cf41b](https://github.com/stashed/stash/commit/c81cf41b) Add support for custom Pusgateway (#1412)
- [127017c9](https://github.com/stashed/stash/commit/127017c9) Update repository config (#1411)
- [1e41192e](https://github.com/stashed/stash/commit/1e41192e) Cleanup legacy code + Port changes from enterprise operator (#1410)
- [1ca2129b](https://github.com/stashed/stash/commit/1ca2129b) Update repository config (#1407)
- [849c782a](https://github.com/stashed/stash/commit/849c782a) Fix invalid task name in restore task resolver (#1406)



