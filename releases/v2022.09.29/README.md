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



## [stashed/elasticsearch](https://github.com/stashed/elasticsearch)

### [5.6.4-v19](https://github.com/stashed/elasticsearch/releases/tag/5.6.4-v19)

- [966a449b](https://github.com/stashed/elasticsearch/commit/966a449b) Prepare for release 5.6.4-v19 (#1268)
- [69530abc](https://github.com/stashed/elasticsearch/commit/69530abc) [cherry-pick] Revert to restic 0.13.1 (#1257) (#1258)
- [5202ddcf](https://github.com/stashed/elasticsearch/commit/5202ddcf) [cherry-pick] Use restic 0.14.0 (#1246) (#1247)
- [831f0550](https://github.com/stashed/elasticsearch/commit/831f0550) [cherry-pick] Use k8s 1.25.1 libs (#1235) (#1236)
- [c310969d](https://github.com/stashed/elasticsearch/commit/c310969d) [cherry-pick] Acquire license from license-proxyserver if available (#1224) (#1225)


### [6.2.4-v19](https://github.com/stashed/elasticsearch/releases/tag/6.2.4-v19)

- [6ba65875](https://github.com/stashed/elasticsearch/commit/6ba65875) Prepare for release 6.2.4-v19 (#1269)
- [de0252b1](https://github.com/stashed/elasticsearch/commit/de0252b1) [cherry-pick] Revert to restic 0.13.1 (#1257) (#1259)
- [4ca1fe5d](https://github.com/stashed/elasticsearch/commit/4ca1fe5d) [cherry-pick] Use restic 0.14.0 (#1246) (#1248)
- [3cb020f6](https://github.com/stashed/elasticsearch/commit/3cb020f6) [cherry-pick] Use k8s 1.25.1 libs (#1235) (#1237)
- [e6a3931e](https://github.com/stashed/elasticsearch/commit/e6a3931e) [cherry-pick] Acquire license from license-proxyserver if available (#1224) (#1226)


### [6.3.0-v19](https://github.com/stashed/elasticsearch/releases/tag/6.3.0-v19)

- [35be503d](https://github.com/stashed/elasticsearch/commit/35be503d) Prepare for release 6.3.0-v19 (#1270)
- [a83a0f92](https://github.com/stashed/elasticsearch/commit/a83a0f92) [cherry-pick] Revert to restic 0.13.1 (#1257) (#1260)
- [4fc1c5ea](https://github.com/stashed/elasticsearch/commit/4fc1c5ea) [cherry-pick] Use restic 0.14.0 (#1246) (#1249)
- [f5f6bd25](https://github.com/stashed/elasticsearch/commit/f5f6bd25) [cherry-pick] Use k8s 1.25.1 libs (#1235) (#1238)
- [3fb18e38](https://github.com/stashed/elasticsearch/commit/3fb18e38) [cherry-pick] Acquire license from license-proxyserver if available (#1224) (#1227)


### [6.4.0-v19](https://github.com/stashed/elasticsearch/releases/tag/6.4.0-v19)

- [bb078f5b](https://github.com/stashed/elasticsearch/commit/bb078f5b) Prepare for release 6.4.0-v19 (#1271)
- [3326965e](https://github.com/stashed/elasticsearch/commit/3326965e) [cherry-pick] Revert to restic 0.13.1 (#1257) (#1261)
- [7a38f82a](https://github.com/stashed/elasticsearch/commit/7a38f82a) [cherry-pick] Use restic 0.14.0 (#1246) (#1250)
- [4c080247](https://github.com/stashed/elasticsearch/commit/4c080247) [cherry-pick] Use k8s 1.25.1 libs (#1235) (#1239)
- [a0a65026](https://github.com/stashed/elasticsearch/commit/a0a65026) [cherry-pick] Acquire license from license-proxyserver if available (#1224) (#1228)


### [6.5.3-v19](https://github.com/stashed/elasticsearch/releases/tag/6.5.3-v19)

- [7a026075](https://github.com/stashed/elasticsearch/commit/7a026075) Prepare for release 6.5.3-v19 (#1272)
- [75e486af](https://github.com/stashed/elasticsearch/commit/75e486af) [cherry-pick] Revert to restic 0.13.1 (#1257) (#1262)
- [cb9bd0fa](https://github.com/stashed/elasticsearch/commit/cb9bd0fa) [cherry-pick] Use restic 0.14.0 (#1246) (#1251)
- [150cf448](https://github.com/stashed/elasticsearch/commit/150cf448) [cherry-pick] Use k8s 1.25.1 libs (#1235) (#1240)
- [60dbba03](https://github.com/stashed/elasticsearch/commit/60dbba03) [cherry-pick] Acquire license from license-proxyserver if available (#1224) (#1229)


### [6.8.0-v19](https://github.com/stashed/elasticsearch/releases/tag/6.8.0-v19)

- [d158623c](https://github.com/stashed/elasticsearch/commit/d158623c) Prepare for release 6.8.0-v19 (#1273)
- [918b5f8f](https://github.com/stashed/elasticsearch/commit/918b5f8f) [cherry-pick] Revert to restic 0.13.1 (#1257) (#1263)
- [350384af](https://github.com/stashed/elasticsearch/commit/350384af) [cherry-pick] Use restic 0.14.0 (#1246) (#1252)
- [61d07df4](https://github.com/stashed/elasticsearch/commit/61d07df4) [cherry-pick] Use k8s 1.25.1 libs (#1235) (#1241)
- [dab04aa8](https://github.com/stashed/elasticsearch/commit/dab04aa8) [cherry-pick] Acquire license from license-proxyserver if available (#1224) (#1230)


### [7.2.0-v19](https://github.com/stashed/elasticsearch/releases/tag/7.2.0-v19)

- [b5b166a1](https://github.com/stashed/elasticsearch/commit/b5b166a1) Prepare for release 7.2.0-v19 (#1275)
- [ac13c36b](https://github.com/stashed/elasticsearch/commit/ac13c36b) [cherry-pick] Revert to restic 0.13.1 (#1257) (#1265)
- [7aa291c7](https://github.com/stashed/elasticsearch/commit/7aa291c7) [cherry-pick] Use restic 0.14.0 (#1246) (#1254)
- [4240c297](https://github.com/stashed/elasticsearch/commit/4240c297) [cherry-pick] Use k8s 1.25.1 libs (#1235) (#1243)
- [e32f9641](https://github.com/stashed/elasticsearch/commit/e32f9641) [cherry-pick] Acquire license from license-proxyserver if available (#1224) (#1232)
- [9ed8203d](https://github.com/stashed/elasticsearch/commit/9ed8203d) Prepare for release 7.2.0-v18 (#1220)


### [7.3.2-v19](https://github.com/stashed/elasticsearch/releases/tag/7.3.2-v19)

- [27366a89](https://github.com/stashed/elasticsearch/commit/27366a89) Prepare for release 7.3.2-v19 (#1276)
- [20f7d0c0](https://github.com/stashed/elasticsearch/commit/20f7d0c0) [cherry-pick] Revert to restic 0.13.1 (#1257) (#1266)
- [9051b5e8](https://github.com/stashed/elasticsearch/commit/9051b5e8) [cherry-pick] Use restic 0.14.0 (#1246) (#1255)
- [3af9b3c9](https://github.com/stashed/elasticsearch/commit/3af9b3c9) [cherry-pick] Use k8s 1.25.1 libs (#1235) (#1244)
- [b866149e](https://github.com/stashed/elasticsearch/commit/b866149e) [cherry-pick] Acquire license from license-proxyserver if available (#1224) (#1233)
- [6d92e35f](https://github.com/stashed/elasticsearch/commit/6d92e35f) Prepare for release 7.3.2-v18 (#1221)


### [7.14.0-v5](https://github.com/stashed/elasticsearch/releases/tag/7.14.0-v5)

- [c0f3296c](https://github.com/stashed/elasticsearch/commit/c0f3296c) Prepare for release 7.14.0-v5 (#1274)
- [fe1ba0d3](https://github.com/stashed/elasticsearch/commit/fe1ba0d3) [cherry-pick] Revert to restic 0.13.1 (#1257) (#1264)
- [d1735e73](https://github.com/stashed/elasticsearch/commit/d1735e73) [cherry-pick] Use restic 0.14.0 (#1246) (#1253)
- [19670067](https://github.com/stashed/elasticsearch/commit/19670067) [cherry-pick] Use k8s 1.25.1 libs (#1235) (#1242)
- [2759db09](https://github.com/stashed/elasticsearch/commit/2759db09) [cherry-pick] Acquire license from license-proxyserver if available (#1224) (#1231)
- [49ba85f7](https://github.com/stashed/elasticsearch/commit/49ba85f7) Prepare for release 7.14.0-v4 (#1219)


### [8.2.0-v2](https://github.com/stashed/elasticsearch/releases/tag/8.2.0-v2)

- [0c1ae9ff](https://github.com/stashed/elasticsearch/commit/0c1ae9ff) Prepare for release 8.2.0-v2 (#1277)
- [1c020913](https://github.com/stashed/elasticsearch/commit/1c020913) [cherry-pick] Revert to restic 0.13.1 (#1257) (#1267)
- [fc81884f](https://github.com/stashed/elasticsearch/commit/fc81884f) [cherry-pick] Use restic 0.14.0 (#1246) (#1256)
- [7689cccc](https://github.com/stashed/elasticsearch/commit/7689cccc) [cherry-pick] Use k8s 1.25.1 libs (#1235) (#1245)
- [5d5cbcd3](https://github.com/stashed/elasticsearch/commit/5d5cbcd3) [cherry-pick] Acquire license from license-proxyserver if available (#1224) (#1234)
- [e3026385](https://github.com/stashed/elasticsearch/commit/e3026385) Prepare for release 8.2.0-v1 (#1222)



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



## [stashed/mongodb](https://github.com/stashed/mongodb)

### [3.4.17-v19](https://github.com/stashed/mongodb/releases/tag/3.4.17-v19)

- [3a90213c](https://github.com/stashed/mongodb/commit/3a90213c) Prepare for release 3.4.17-v19 (#1663)
- [dcc89b05](https://github.com/stashed/mongodb/commit/dcc89b05) [cherry-pick] Revert to restic 0.13.1 (#1649) (#1650)
- [d9d43b0b](https://github.com/stashed/mongodb/commit/d9d43b0b) [cherry-pick] Use restic 0.14.0 (#1635) (#1636)
- [c838b452](https://github.com/stashed/mongodb/commit/c838b452) [cherry-pick] Use k8s 1.25.1 libs (#1621) (#1622)
- [78fb76b1](https://github.com/stashed/mongodb/commit/78fb76b1) [cherry-pick] Acquire license from license-proxyserver if available (#1607) (#1608)


### [3.4.22-v19](https://github.com/stashed/mongodb/releases/tag/3.4.22-v19)

- [bd473140](https://github.com/stashed/mongodb/commit/bd473140) Prepare for release 3.4.22-v19 (#1664)
- [ee17bd96](https://github.com/stashed/mongodb/commit/ee17bd96) Revert to restic 0.13.1 (#1649) (#1651)
- [5a3562ae](https://github.com/stashed/mongodb/commit/5a3562ae) [cherry-pick] Use restic 0.14.0 (#1635) (#1637)
- [d660184a](https://github.com/stashed/mongodb/commit/d660184a) [cherry-pick] Use k8s 1.25.1 libs (#1621) (#1623)
- [3d73c7f8](https://github.com/stashed/mongodb/commit/3d73c7f8) [cherry-pick] Acquire license from license-proxyserver if available (#1607) (#1609)


### [3.6.13-v19](https://github.com/stashed/mongodb/releases/tag/3.6.13-v19)

- [36b22e54](https://github.com/stashed/mongodb/commit/36b22e54) Prepare for release 3.6.13-v19 (#1665)
- [0b579101](https://github.com/stashed/mongodb/commit/0b579101) Revert to restic 0.13.1 (#1649) (#1652)
- [f335db0d](https://github.com/stashed/mongodb/commit/f335db0d) [cherry-pick] Use restic 0.14.0 (#1635) (#1638)
- [a194f438](https://github.com/stashed/mongodb/commit/a194f438) [cherry-pick] Use k8s 1.25.1 libs (#1621) (#1624)
- [a389cd0c](https://github.com/stashed/mongodb/commit/a389cd0c) [cherry-pick] Acquire license from license-proxyserver if available (#1607) (#1610)



## [stashed/postgres](https://github.com/stashed/postgres)

### [9.6.19-v18](https://github.com/stashed/postgres/releases/tag/9.6.19-v18)

- [82f3ce67](https://github.com/stashed/postgres/commit/82f3ce67) Prepare for release 9.6.19-v18 (#1117)
- [2010667b](https://github.com/stashed/postgres/commit/2010667b) [cherry-pick] Revert to restic 0.13.1 (#1105) (#1111)
- [ebbbcbac](https://github.com/stashed/postgres/commit/ebbbcbac) [cherry-pick] Use restic 0.14.0 (#1098) (#1104)
- [c010f284](https://github.com/stashed/postgres/commit/c010f284) [cherry-pick] Use k8s 1.25.1 libs (#1091) (#1097)
- [3f12e462](https://github.com/stashed/postgres/commit/3f12e462) [cherry-pick] Acquire license from license-proxyserver if available (#1084) (#1090)


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


### [12.4-v18](https://github.com/stashed/postgres/releases/tag/12.4-v18)

- [9aeadf3d](https://github.com/stashed/postgres/commit/9aeadf3d) Prepare for release 12.4-v18 (#1114)
- [dc133e24](https://github.com/stashed/postgres/commit/dc133e24) [cherry-pick] Revert to restic 0.13.1 (#1105) (#1108)
- [b076014d](https://github.com/stashed/postgres/commit/b076014d) [cherry-pick] Use restic 0.14.0 (#1098) (#1101)
- [0d9bb51a](https://github.com/stashed/postgres/commit/0d9bb51a) [cherry-pick] Use k8s 1.25.1 libs (#1091) (#1094)
- [4c40d495](https://github.com/stashed/postgres/commit/4c40d495) [cherry-pick] Acquire license from license-proxyserver if available (#1084) (#1087)


### [13.1-v15](https://github.com/stashed/postgres/releases/tag/13.1-v15)

- [d5514c07](https://github.com/stashed/postgres/commit/d5514c07) Prepare for release 13.1-v15 (#1115)
- [6ae5c873](https://github.com/stashed/postgres/commit/6ae5c873) [cherry-pick] Revert to restic 0.13.1 (#1105) (#1109)
- [a99069cf](https://github.com/stashed/postgres/commit/a99069cf) [cherry-pick] Use restic 0.14.0 (#1098) (#1102)
- [085f7ae0](https://github.com/stashed/postgres/commit/085f7ae0) [cherry-pick] Use k8s 1.25.1 libs (#1091) (#1095)
- [ee7e4c40](https://github.com/stashed/postgres/commit/ee7e4c40) [cherry-pick] Acquire license from license-proxyserver if available (#1084) (#1088)


### [14.0-v7](https://github.com/stashed/postgres/releases/tag/14.0-v7)

- [334d54bb](https://github.com/stashed/postgres/commit/334d54bb) Prepare for release 14.0-v7 (#1116)
- [84426fe5](https://github.com/stashed/postgres/commit/84426fe5) [cherry-pick] Revert to restic 0.13.1 (#1105) (#1110)
- [d5225dd7](https://github.com/stashed/postgres/commit/d5225dd7) [cherry-pick] Use restic 0.14.0 (#1098) (#1103)
- [b382b035](https://github.com/stashed/postgres/commit/b382b035) [cherry-pick] Use k8s 1.25.1 libs (#1091) (#1096)
- [bf7ebaec](https://github.com/stashed/postgres/commit/bf7ebaec) [cherry-pick] Acquire license from license-proxyserver if available (#1084) (#1089)



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



