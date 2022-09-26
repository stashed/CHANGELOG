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



