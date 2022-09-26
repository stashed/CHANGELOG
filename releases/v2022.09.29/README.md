# Stash v2022.09.29 (2022-09-26)


## [stashed/apimachinery](https://github.com/stashed/apimachinery)

### [v0.23.0](https://github.com/stashed/apimachinery/releases/tag/v0.23.0)

- [92b9a652](https://github.com/stashed/apimachinery/commit/92b9a652) Add backup retry helpers + use `metav1.Duration` for `TimeOut` (#188)
- [a5ba7404](https://github.com/stashed/apimachinery/commit/a5ba7404) Revert to restic 0.13.1 (#190)
- [8821fa34](https://github.com/stashed/apimachinery/commit/8821fa34) Test against Kubernetes 1.25.0 (#189)
- [6b79486c](https://github.com/stashed/apimachinery/commit/6b79486c) Fix RestoreSession phase calculation (#187)
- [cb39527c](https://github.com/stashed/apimachinery/commit/cb39527c) Add re-try logic for failed backup session (#182)
- [b8925184](https://github.com/stashed/apimachinery/commit/b8925184) Check for CronJob/VolumeSnapshot version only once (#186)
- [a3b5eb90](https://github.com/stashed/apimachinery/commit/a3b5eb90) Remove slack link
- [40ce6cb2](https://github.com/stashed/apimachinery/commit/40ce6cb2) Handle status conversion for CronJob/VolumeSnapshot (#185)
- [55dff331](https://github.com/stashed/apimachinery/commit/55dff331) Use restic 0.14.0 (#184)
- [522f4e18](https://github.com/stashed/apimachinery/commit/522f4e18) Use k8s 1.25.1 libs (#183)
- [a68816b4](https://github.com/stashed/apimachinery/commit/a68816b4) Acquire license from license-proxyserver if available (#181)
- [f76f80b6](https://github.com/stashed/apimachinery/commit/f76f80b6) Fix namespace defaulting in restore target ref (#180)
- [ffd3a856](https://github.com/stashed/apimachinery/commit/ffd3a856) Make PostBackupHook and PostRestoreHook pointer to avoid defaulting (#179)
- [2e6ad371](https://github.com/stashed/apimachinery/commit/2e6ad371) Add target related constants + re-organize constants (#177)
- [c8f94328](https://github.com/stashed/apimachinery/commit/c8f94328) Fix issue in sending backupsession and restoresession success metrics. (#178)



## [stashed/cli](https://github.com/stashed/cli)

### [v0.23.0](https://github.com/stashed/cli/releases/tag/v0.23.0)

- [55cd97a6](https://github.com/stashed/cli/commit/55cd97a6) Prepare for release v0.23.0 (#171)
- [c6df635c](https://github.com/stashed/cli/commit/c6df635c) Revert to restic 0.13.1 (#170)
- [b522f73f](https://github.com/stashed/cli/commit/b522f73f) Use restic 0.14.0 (#169)
- [b03af4b2](https://github.com/stashed/cli/commit/b03af4b2) Use k8s 1.25.1 libs (#168)



## [stashed/enterprise](https://github.com/stashed/enterprise)

### [v0.23.0](https://github.com/stashed/enterprise/releases/tag/v0.23.0)

- [4cb35fb1](https://github.com/stashed/enterprise/commit/4cb35fb1) Prepare for release v0.23.0 (#205)
- [88cf38fc](https://github.com/stashed/enterprise/commit/88cf38fc) Implement retry logic for failed backup + use `metav1.Duration` for `TimeOut` (#204)
- [3951fa2c](https://github.com/stashed/enterprise/commit/3951fa2c) Revert to restic 0.13.1 (#203)
- [81ec3c07](https://github.com/stashed/enterprise/commit/81ec3c07) Refactor codebase (#195)
- [ca228c24](https://github.com/stashed/enterprise/commit/ca228c24) Validate `TimeOut`  field in Backup and Restore (#202)
- [657982b5](https://github.com/stashed/enterprise/commit/657982b5) Fix unit tests
- [a348041f](https://github.com/stashed/enterprise/commit/a348041f) Check for CronJob/VolumeSnapshot version only once (#201)
- [a5550bb0](https://github.com/stashed/enterprise/commit/a5550bb0) Handle CronJob api type dynamically (#200)
- [79ba1c50](https://github.com/stashed/enterprise/commit/79ba1c50) Handle status conversion for CronJob/VolumeSnapshot (#199)
- [521b7e4e](https://github.com/stashed/enterprise/commit/521b7e4e) Use restic 0.14.0 (#198)
- [60b48411](https://github.com/stashed/enterprise/commit/60b48411) Use VolumeSnapshot api dynamically (#197)
- [cf034b8b](https://github.com/stashed/enterprise/commit/cf034b8b) Use k8s 1.25.1 libs (#196)
- [f2c419a7](https://github.com/stashed/enterprise/commit/f2c419a7) Acquire license from license-proxyserver if available (#194)
- [316cd592](https://github.com/stashed/enterprise/commit/316cd592) Fix total host calculation for VolumeSnapshot (#189)
- [7fdce67e](https://github.com/stashed/enterprise/commit/7fdce67e) Fix label passing to restore job (#193)
- [0052217d](https://github.com/stashed/enterprise/commit/0052217d) Fix hook defaulting issue (#192)
- [d78cfc50](https://github.com/stashed/enterprise/commit/d78cfc50) Add support for multiple blueprint name in target annotations (#190)
- [07327ac2](https://github.com/stashed/enterprise/commit/07327ac2) Set BackupSession Duration before sending metrics. (#191)
- [52ceac2b](https://github.com/stashed/enterprise/commit/52ceac2b) Cancel concurrent CI runs



## [stashed/postgres](https://github.com/stashed/postgres)

### [10.14-v18](https://github.com/stashed/postgres/releases/tag/10.14-v18)

- [21c2297c](https://github.com/stashed/postgres/commit/21c2297c) Prepare for release 10.14-v18 (#1112)
- [f88623ae](https://github.com/stashed/postgres/commit/f88623ae) [cherry-pick] Revert to restic 0.13.1 (#1105) (#1106)
- [2095d664](https://github.com/stashed/postgres/commit/2095d664) [cherry-pick] Use restic 0.14.0 (#1098) (#1099)
- [05343728](https://github.com/stashed/postgres/commit/05343728) [cherry-pick] Use k8s 1.25.1 libs (#1091) (#1092)
- [b47ffe3a](https://github.com/stashed/postgres/commit/b47ffe3a) [cherry-pick] Acquire license from license-proxyserver if available (#1084) (#1085)


### [11.9-v18](https://github.com/stashed/postgres/releases/tag/11.9-v18)

- [d94521f0](https://github.com/stashed/postgres/commit/d94521f0) Prepare for release 11.9-v18 (#1113)
- [80d58dcf](https://github.com/stashed/postgres/commit/80d58dcf) [cherry-pick] Revert to restic 0.13.1 (#1105) (#1107)
- [0f80a028](https://github.com/stashed/postgres/commit/0f80a028) [cherry-pick] Use restic 0.14.0 (#1098) (#1100)
- [1dc3d12a](https://github.com/stashed/postgres/commit/1dc3d12a) [cherry-pick] Use k8s 1.25.1 libs (#1091) (#1093)
- [8bb7face](https://github.com/stashed/postgres/commit/8bb7face) [cherry-pick] Acquire license from license-proxyserver if available (#1084) (#1086)



## [stashed/stash](https://github.com/stashed/stash)

### [v0.23.0](https://github.com/stashed/stash/releases/tag/v0.23.0)

- [2df11f82](https://github.com/stashed/stash/commit/2df11f82) Prepare for release v0.23.0 (#1486)
- [ee8134e5](https://github.com/stashed/stash/commit/ee8134e5) Port changes from Stash Enterprise edition
- [f209179c](https://github.com/stashed/stash/commit/f209179c) Fix snapshot test failure
- [583a8f56](https://github.com/stashed/stash/commit/583a8f56) Port changes from Stash Enterprise edition
- [d8e8f4c9](https://github.com/stashed/stash/commit/d8e8f4c9) Revert to restic 0.13.1 (#1483)
- [57de24c7](https://github.com/stashed/stash/commit/57de24c7) Test against Kubernetes 1.25.0 (#1482)
- [bf1826c8](https://github.com/stashed/stash/commit/bf1826c8) Validate `TimeOut` in backup and restore (#1481)
- [1ae696dd](https://github.com/stashed/stash/commit/1ae696dd) Fix unit tests
- [41064183](https://github.com/stashed/stash/commit/41064183) Check for CronJob/VolumeSnapshot version only once (#1479)
- [fc4e2602](https://github.com/stashed/stash/commit/fc4e2602) Handle CronJob api type dynamically (#1478)
- [7c055aec](https://github.com/stashed/stash/commit/7c055aec) Handle status conversion for CronJob/VolumeSnapshot (#1477)
- [fb80667d](https://github.com/stashed/stash/commit/fb80667d) Use restic 0.14.0 (#1476)
- [4ce5e18d](https://github.com/stashed/stash/commit/4ce5e18d) Use VolumeSnapshot api dynamically (#1475)
- [b0519c85](https://github.com/stashed/stash/commit/b0519c85) Fix linter warnings
- [779297d4](https://github.com/stashed/stash/commit/779297d4) Use k8s 1.25.1 libs (#1474)
- [8c87f9fc](https://github.com/stashed/stash/commit/8c87f9fc) Acquire license from license-proxyserver if available (#1472)
- [63cac4e9](https://github.com/stashed/stash/commit/63cac4e9) Fix total host calculation for VolumeSnapshot
- [aca8fde0](https://github.com/stashed/stash/commit/aca8fde0) Remove unused variable
- [6bbd94ba](https://github.com/stashed/stash/commit/6bbd94ba) Remove unnecessary else
- [d28750a3](https://github.com/stashed/stash/commit/d28750a3) Fix total host calculation for VolumeSnapshot
- [42f39b5b](https://github.com/stashed/stash/commit/42f39b5b) Fix label passing to backup/restore jobs (#1470)
- [2b445ce1](https://github.com/stashed/stash/commit/2b445ce1) Fix hook defaulting issue
- [12436ad2](https://github.com/stashed/stash/commit/12436ad2) Fix hook defaulting issue
- [e2f44131](https://github.com/stashed/stash/commit/e2f44131) Support multiple backup invoker against a target
- [7fafed89](https://github.com/stashed/stash/commit/7fafed89) Support multiple backup invoker against a target
- [e4e7b69e](https://github.com/stashed/stash/commit/e4e7b69e) Set BackupSession duration before sending metrics. (#1466)
- [cd9bcecc](https://github.com/stashed/stash/commit/cd9bcecc) Cancel concurrent ci runs



## [stashed/ui-server](https://github.com/stashed/ui-server)

### [v0.5.0](https://github.com/stashed/ui-server/releases/tag/v0.5.0)

- [13db95c](https://github.com/stashed/ui-server/commit/13db95c) Prepare for release v0.5.0 (#17)
- [2382c83](https://github.com/stashed/ui-server/commit/2382c83) Use k8s 1.25.1 libs (#16)
- [7fabd18](https://github.com/stashed/ui-server/commit/7fabd18) Cancel concurrent CI runs



