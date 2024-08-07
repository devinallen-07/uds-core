# Changelog

All notable changes to this project will be documented in this file.

## [0.25.1](https://github.com/defenseunicorns/uds-core/compare/v0.25.0...v0.25.1) (2024-08-06)


### Bug Fixes

* switch metrics-server to optional everywhere ([#641](https://github.com/defenseunicorns/uds-core/issues/641)) ([43c5bd5](https://github.com/defenseunicorns/uds-core/commit/43c5bd5bff896e9fd65f5b878563672e3a22100b))


### Miscellaneous

* add debug logs for istio injection logic ([#602](https://github.com/defenseunicorns/uds-core/issues/602)) ([9075436](https://github.com/defenseunicorns/uds-core/commit/9075436c37c847bd06f7e527506ecd41e4c4db0e))
* add support for public clients and disabling standard auth flow ([#630](https://github.com/defenseunicorns/uds-core/issues/630)) ([38151d7](https://github.com/defenseunicorns/uds-core/commit/38151d74d245d0b56ea7325a69514a832d7cf496))
* **deps:** update dependency defenseunicorns/uds-common to v0.11.0 ([#617](https://github.com/defenseunicorns/uds-core/issues/617)) ([997cf37](https://github.com/defenseunicorns/uds-core/commit/997cf37250bd72930d053ea87bba8a56c6fe052b))
* **deps:** update dependency weaveworks/eksctl to v0.188.0 ([#623](https://github.com/defenseunicorns/uds-core/issues/623)) ([3081044](https://github.com/defenseunicorns/uds-core/commit/3081044eddd8b2d043d7039907945b67990718ed))
* **deps:** update uds to v0.14.0 ([#612](https://github.com/defenseunicorns/uds-core/issues/612)) ([7fe927e](https://github.com/defenseunicorns/uds-core/commit/7fe927e4e0df19acbf2975b8d9c9e3068e0f82c5))
* update codeowners ([#637](https://github.com/defenseunicorns/uds-core/issues/637)) ([eec5017](https://github.com/defenseunicorns/uds-core/commit/eec5017bad0a06b5e2b5f023b5a2602aaf20f789))

## [0.25.0](https://github.com/defenseunicorns/uds-core/compare/v0.24.1...v0.25.0) (2024-08-02)


### ⚠ BREAKING CHANGES

* change metric server to optional (https://github.com/defenseunicorns/uds-core/pull/611)

### Features

* add json logging for keycloak ([#610](https://github.com/defenseunicorns/uds-core/issues/610)) ([29ed934](https://github.com/defenseunicorns/uds-core/commit/29ed934859c31dd557788f182a06736c5249f384))
* **istio:** add configurable TLS version ([#624](https://github.com/defenseunicorns/uds-core/issues/624)) ([cd2b87e](https://github.com/defenseunicorns/uds-core/commit/cd2b87e1819153df1c025afe0d3f7a3392e32217))


### Bug Fixes

* account for keycloak HA ports ([#619](https://github.com/defenseunicorns/uds-core/issues/619)) ([434f349](https://github.com/defenseunicorns/uds-core/commit/434f349fe6fda234875622a93de3939d0082eb78))
* add google saml to slim-dev ([#613](https://github.com/defenseunicorns/uds-core/issues/613)) ([f2164e1](https://github.com/defenseunicorns/uds-core/commit/f2164e10aae0a87dbd73cfe189f1154f850895e3))
* address network policy generation inter-namespace bug ([#564](https://github.com/defenseunicorns/uds-core/issues/564)) ([9b14c2c](https://github.com/defenseunicorns/uds-core/commit/9b14c2ca31d7c05540dcfdfff7247bb31ed6b924))
* reference root scope ([#633](https://github.com/defenseunicorns/uds-core/issues/633)) ([5de6915](https://github.com/defenseunicorns/uds-core/commit/5de69159f1f8370fc6b5553c2b9b05af52621027))


### Miscellaneous

* change metric server to optional (https://github.com/defenseunicorns/uds-core/pull/611) ([bc2d673](https://github.com/defenseunicorns/uds-core/commit/bc2d673b81724449a6c7523b1ba6950009c0c888))
* **deps:** update dependency defenseunicorns/uds-common to v0.9.0 ([#592](https://github.com/defenseunicorns/uds-core/issues/592)) ([44ea2d7](https://github.com/defenseunicorns/uds-core/commit/44ea2d7db07b1b91318ec5a8d6b048c3c8f3a565))
* **deps:** update dependency weaveworks/eksctl to v0.187.0 ([#539](https://github.com/defenseunicorns/uds-core/issues/539)) ([9002a94](https://github.com/defenseunicorns/uds-core/commit/9002a945bbe7f9e9f75ca3f3909ffecedbbc995a))
* **deps:** update githubactions ([#553](https://github.com/defenseunicorns/uds-core/issues/553)) ([2a9e29a](https://github.com/defenseunicorns/uds-core/commit/2a9e29aa506dffc1c8db5b5fc2272ffc974a0988))
* **deps:** update grafana curl image to v8.9.0 ([#596](https://github.com/defenseunicorns/uds-core/issues/596)) ([64f9408](https://github.com/defenseunicorns/uds-core/commit/64f9408fb792b931b4eddc4669559d8f99aab7dc))
* **deps:** update grafana helm chart to v8.3.6 ([#594](https://github.com/defenseunicorns/uds-core/issues/594)) ([1f2005b](https://github.com/defenseunicorns/uds-core/commit/1f2005bff139a1738c6cf217d79c0c6396e1a347))
* **deps:** update istio to v1.22.3 ([#580](https://github.com/defenseunicorns/uds-core/issues/580)) ([7aba89e](https://github.com/defenseunicorns/uds-core/commit/7aba89e8951b27f26495c6b13fbe25b02808ee19))
* **deps:** update lula to v0.4.4 ([#615](https://github.com/defenseunicorns/uds-core/issues/615)) ([b02b305](https://github.com/defenseunicorns/uds-core/commit/b02b305fdac5e415af1b78668f45fdde7be4b67a))
* **deps:** update neuvector-updater/curl to v8.9.0 ([#597](https://github.com/defenseunicorns/uds-core/issues/597)) ([b4bd660](https://github.com/defenseunicorns/uds-core/commit/b4bd66086b217871b17cadcff7bd1617c829279d))
* **deps:** update promtail configmap-reload to v0.13.1 ([#608](https://github.com/defenseunicorns/uds-core/issues/608)) ([d98bbae](https://github.com/defenseunicorns/uds-core/commit/d98bbae27de52b9ece2981b79d5bd6ba2b09d5e0))
* **deps:** update promtail helm chart to v6.16.4 ([#574](https://github.com/defenseunicorns/uds-core/issues/574)) ([bf9f65c](https://github.com/defenseunicorns/uds-core/commit/bf9f65ca482da38c6cd09a6a519d545511326d43))
* **deps:** update to identity-config 0.5.2 ([#635](https://github.com/defenseunicorns/uds-core/issues/635)) ([6474d16](https://github.com/defenseunicorns/uds-core/commit/6474d16eb0cc6f08f2d4c35e9d642add62c6ae34))
* **deps:** update uds cli to v0.13.1 ([#569](https://github.com/defenseunicorns/uds-core/issues/569)) ([4339c89](https://github.com/defenseunicorns/uds-core/commit/4339c892c56bdcabf7809cde7c7898348c1d9132))
* **deps:** update zarf to v0.36.1 ([#562](https://github.com/defenseunicorns/uds-core/issues/562)) ([058cfb3](https://github.com/defenseunicorns/uds-core/commit/058cfb3b45d9f944e2f2c615fef82ae1a98d2413))
* disable telemetry/analytics for loki/grafana ([#601](https://github.com/defenseunicorns/uds-core/issues/601)) ([ad785bc](https://github.com/defenseunicorns/uds-core/commit/ad785bcac2e11ccdc4fbdb14bee9bb1fdbd536cb))
* update zarf to new repo location, 0.37.0 ([#631](https://github.com/defenseunicorns/uds-core/issues/631)) ([29f9fd0](https://github.com/defenseunicorns/uds-core/commit/29f9fd0277bc0ab4cd6073e4c5b73123586946e1))

## [0.24.1](https://github.com/defenseunicorns/uds-core/compare/v0.24.0...v0.24.1) (2024-07-22)


### Bug Fixes

* **ci:** snapshot release publish, passthrough test on upgrade ([#575](https://github.com/defenseunicorns/uds-core/issues/575)) ([d4afe00](https://github.com/defenseunicorns/uds-core/commit/d4afe0065b76ec7c44e9d00b1f95b46b189043f0))
* **ci:** workflow permissions ([cacf1b5](https://github.com/defenseunicorns/uds-core/commit/cacf1b5d8bccd16a8c2381fbd0912715a78a22c2))
* only allow istio gateways to set x509 client certificate header ([#572](https://github.com/defenseunicorns/uds-core/issues/572)) ([5c62279](https://github.com/defenseunicorns/uds-core/commit/5c622795b9becb7ef6f65b807486ade0fd44bea1))
* **sso:** delete orphaned SSO secrets ([#578](https://github.com/defenseunicorns/uds-core/issues/578)) ([5a6b9ef](https://github.com/defenseunicorns/uds-core/commit/5a6b9effca83f4f19344c813cf96d474ff5fdeb4))
* unicorn flavor proxy image reference ([#590](https://github.com/defenseunicorns/uds-core/issues/590)) ([db081fa](https://github.com/defenseunicorns/uds-core/commit/db081fa41c0db6557c3b66bbfa0b5064dc7226e3))
* update monitor mutation to not overwrite explicitly defined scrape class ([#582](https://github.com/defenseunicorns/uds-core/issues/582)) ([7e550d3](https://github.com/defenseunicorns/uds-core/commit/7e550d3577546d73e32a62dac018e048972d46eb))


### Miscellaneous

* **deps:** update grafana chart + sidecar image ([#567](https://github.com/defenseunicorns/uds-core/issues/567)) ([85b6de4](https://github.com/defenseunicorns/uds-core/commit/85b6de4b140a2076cdc72626bce2d24aab90c26c))
* **deps:** update pepr to v0.32.7 ([#556](https://github.com/defenseunicorns/uds-core/issues/556)) ([e594f13](https://github.com/defenseunicorns/uds-core/commit/e594f1366bb6a920a9cd7a945bc41ae39382f8b8))
* **deps:** update uds-identity-config to v0.5.1 ([#591](https://github.com/defenseunicorns/uds-core/issues/591)) ([b9c5bd3](https://github.com/defenseunicorns/uds-core/commit/b9c5bd34c75b6fe7063d8bf4bd15496f73e87861))
* **deps:** update uds-k3d to v0.8.0 ([#581](https://github.com/defenseunicorns/uds-core/issues/581)) ([fab8919](https://github.com/defenseunicorns/uds-core/commit/fab89198a9118f51e372b589e02fca89d6db4112))
* **loki:** default query settings, config as secret ([#579](https://github.com/defenseunicorns/uds-core/issues/579)) ([5fa889c](https://github.com/defenseunicorns/uds-core/commit/5fa889c51a59786330fd4f7b914b532b4c56b1b3))
* **oscal:** begin integration of composed oscal with validations ([#496](https://github.com/defenseunicorns/uds-core/issues/496)) ([047fd30](https://github.com/defenseunicorns/uds-core/commit/047fd3041a8eecc29c8f61e1f3c2c70622ec9e88))

## [0.24.0](https://github.com/defenseunicorns/uds-core/compare/v0.23.0...v0.24.0) (2024-07-12)


### ⚠ BREAKING CHANGES

* set istio passthrough gateway as optional component (https://github.com/defenseunicorns/uds-core/pull/547)

### Features

* add unicorn flavor to uds-core ([#507](https://github.com/defenseunicorns/uds-core/issues/507)) ([a412581](https://github.com/defenseunicorns/uds-core/commit/a412581c6295658cd61a8f4fc182357c0780bef6))
* added standalone dns service for loki ([#548](https://github.com/defenseunicorns/uds-core/issues/548)) ([e2efdf9](https://github.com/defenseunicorns/uds-core/commit/e2efdf9b059f698369721412409509cc702593bc))
* enable authservice integration ([#201](https://github.com/defenseunicorns/uds-core/issues/201)) ([1d4df64](https://github.com/defenseunicorns/uds-core/commit/1d4df64d12882b9a4ff01b5144c1edc7fc2351d2))
* set istio passthrough gateway as optional component (https://github.com/defenseunicorns/uds-core/pull/547) ([e1cab61](https://github.com/defenseunicorns/uds-core/commit/e1cab61a170dff73fa97000f922cc373a0a70ee5))
* update to using default scrapeclass for tls config ([#517](https://github.com/defenseunicorns/uds-core/issues/517)) ([258bb6b](https://github.com/defenseunicorns/uds-core/commit/258bb6b41a07081412393b625438c5634ae88d79))


### Bug Fixes

* decouple `devMode` and postgres egress ([#554](https://github.com/defenseunicorns/uds-core/issues/554)) ([1a98779](https://github.com/defenseunicorns/uds-core/commit/1a987796edab5929f90973944bd3888670342973))
* grafana logout not working in some environments ([#559](https://github.com/defenseunicorns/uds-core/issues/559)) ([ccb9d9e](https://github.com/defenseunicorns/uds-core/commit/ccb9d9e0670a477cdcd87f435db85f0c76e1ccda))
* initial creation of child logging ([#533](https://github.com/defenseunicorns/uds-core/issues/533)) ([00a5140](https://github.com/defenseunicorns/uds-core/commit/00a5140df6205143d89c15249eb28b3502a2c901))
* podmonitor mTLS mutations ([#566](https://github.com/defenseunicorns/uds-core/issues/566)) ([eb613e1](https://github.com/defenseunicorns/uds-core/commit/eb613e1ad462681248b85778173d65d9358d427f))


### Miscellaneous

* add util function for purging orphans ([#565](https://github.com/defenseunicorns/uds-core/issues/565)) ([e84229a](https://github.com/defenseunicorns/uds-core/commit/e84229ad355b60935dc077bb23f1c91f0fa212ec))
* allow istio proxy injection in zarf ignored namespaces (https://github.com/defenseunicorns/uds-core/pull/513) ([8921b58](https://github.com/defenseunicorns/uds-core/commit/8921b5897b7a34d9065417f66c1cc24817116ba2))
* **deps:** update githubactions upload-artifact to v4.3.4 ([#543](https://github.com/defenseunicorns/uds-core/issues/543)) ([20889f2](https://github.com/defenseunicorns/uds-core/commit/20889f2936597360c91b067d2c0d07d6c94646a4))
* **deps:** update grafana helm chart to v8.3.2 ([#542](https://github.com/defenseunicorns/uds-core/issues/542)) ([8ec260c](https://github.com/defenseunicorns/uds-core/commit/8ec260c7644241fb7fe8163ea8b74240320d417e))
* **deps:** update pepr dependencies (jest, uds-common) ([#537](https://github.com/defenseunicorns/uds-core/issues/537)) ([547c0bf](https://github.com/defenseunicorns/uds-core/commit/547c0bfb5197fb129e023d2d02fa3a306790364a))
* **deps:** update promtail helm chart to v6.16.3 ([#538](https://github.com/defenseunicorns/uds-core/issues/538)) ([48b3fea](https://github.com/defenseunicorns/uds-core/commit/48b3feac221f90316e025b57151d8241dbd455c4))

## [0.23.0](https://github.com/defenseunicorns/uds-core/compare/v0.22.2...v0.23.0) (2024-07-04)


### ⚠ BREAKING CHANGES

* remove emulated gitlab endpoints from keycloak ([#483](https://github.com/defenseunicorns/uds-core/issues/483))

### Features

* identity group auth ([#497](https://github.com/defenseunicorns/uds-core/issues/497)) ([d71d83e](https://github.com/defenseunicorns/uds-core/commit/d71d83ed4d6e6a35724e70fc5a27cb7ff6e1adaa))


### Bug Fixes

* **docs:** re-ordered small paragraphs, clarified wording, and added links to tech homepages ([#531](https://github.com/defenseunicorns/uds-core/issues/531)) ([6b2b46b](https://github.com/defenseunicorns/uds-core/commit/6b2b46b46dcb0d25bc13ca7e166bba4fb531da15))
* **docs:** removed double-link which broke the markdown formatting in pr template ([#532](https://github.com/defenseunicorns/uds-core/issues/532)) ([f41ced4](https://github.com/defenseunicorns/uds-core/commit/f41ced483cc8f8ca1f2cfba3ae3fb58a218f7afc))
* **docs:** uds-config.yaml example in k3d-slim-dev README ([#530](https://github.com/defenseunicorns/uds-core/issues/530)) ([2e1c53e](https://github.com/defenseunicorns/uds-core/commit/2e1c53e939b99794c8e6994f20282974bd139917))
* operator retries and error logging ([#511](https://github.com/defenseunicorns/uds-core/issues/511)) ([cae5aab](https://github.com/defenseunicorns/uds-core/commit/cae5aabed589d28680f0f36bd4afe8e2d235c8b4))


### Miscellaneous

* **deps:** update checkout action to latest sha ([#481](https://github.com/defenseunicorns/uds-core/issues/481)) ([c6f0137](https://github.com/defenseunicorns/uds-core/commit/c6f0137bb9a1e11f98d426cec8c98eb4005f160a))
* **deps:** update dependency weaveworks/eksctl to v0.183.0 ([#499](https://github.com/defenseunicorns/uds-core/issues/499)) ([9cb8e4d](https://github.com/defenseunicorns/uds-core/commit/9cb8e4d7c86611918e502de0a7e7e25921523cbc))
* **deps:** update grafana to 11.1.0 ([#380](https://github.com/defenseunicorns/uds-core/issues/380)) ([499058a](https://github.com/defenseunicorns/uds-core/commit/499058aedbbda33f88fffd94178ceb68529d5c85))
* **deps:** update istio to v1.22.2 ([#512](https://github.com/defenseunicorns/uds-core/issues/512)) ([dcdadb4](https://github.com/defenseunicorns/uds-core/commit/dcdadb49255a5052dcb3fe079335976b758b32f9))
* **deps:** update jest to v29.1.5 ([#485](https://github.com/defenseunicorns/uds-core/issues/485)) ([9c392b9](https://github.com/defenseunicorns/uds-core/commit/9c392b9b88c84e3c3763878e6beb1800c43ded25))
* **deps:** update neuvector to 5.3.3 ([#467](https://github.com/defenseunicorns/uds-core/issues/467)) ([261057d](https://github.com/defenseunicorns/uds-core/commit/261057d2bf142c3167fdf0d0bd68bc2fb47d22df))
* **deps:** update pepr to 0.32.2 ([#473](https://github.com/defenseunicorns/uds-core/issues/473)) ([ab4bee9](https://github.com/defenseunicorns/uds-core/commit/ab4bee906f020d86b90c0b984789be55f8b4c08b))
* **deps:** update pepr to 0.32.3 ([#494](https://github.com/defenseunicorns/uds-core/issues/494)) ([2e28897](https://github.com/defenseunicorns/uds-core/commit/2e2889784043b21463e72643eb890054645dd439))
* **deps:** update pepr to 0.32.6 ([#516](https://github.com/defenseunicorns/uds-core/issues/516)) ([a9d3eec](https://github.com/defenseunicorns/uds-core/commit/a9d3eecce3e007958b45ac2e627cbece84ad48ac))
* **deps:** update promtail to 3.1.0 ([#335](https://github.com/defenseunicorns/uds-core/issues/335)) ([4457fce](https://github.com/defenseunicorns/uds-core/commit/4457fce6f46626047e37a17b87dbdc675bcfd709))
* **deps:** update uds to v0.12.0 ([#521](https://github.com/defenseunicorns/uds-core/issues/521)) ([8e587ff](https://github.com/defenseunicorns/uds-core/commit/8e587ffc210bdb2351748383e058cf86ced8b7a9))
* **deps:** update uds-common tasks to 0.6.1 ([#498](https://github.com/defenseunicorns/uds-core/issues/498)) ([4aa6e33](https://github.com/defenseunicorns/uds-core/commit/4aa6e3372f6d1a5df1e2ae51a3129603a8b0b29b))
* **deps:** update zarf to v0.35.0 ([#490](https://github.com/defenseunicorns/uds-core/issues/490)) ([86957cf](https://github.com/defenseunicorns/uds-core/commit/86957cfe19564ec8ddccec7e496af4469def322a))
* docs linting changes ([#505](https://github.com/defenseunicorns/uds-core/issues/505)) ([0fe2015](https://github.com/defenseunicorns/uds-core/commit/0fe20151713363f572a50601016e06e60230990f))
* remove emulated gitlab endpoints from keycloak ([#483](https://github.com/defenseunicorns/uds-core/issues/483)) ([495960c](https://github.com/defenseunicorns/uds-core/commit/495960ce8d40cf2ef7c0f0021b653db6fc6383bb))
* update docs for group auth and readme for docs site ([#540](https://github.com/defenseunicorns/uds-core/issues/540)) ([ace7041](https://github.com/defenseunicorns/uds-core/commit/ace7041e500b72f00b4a5c23d7413a46aa359504))

## [0.22.2](https://github.com/defenseunicorns/uds-core/compare/v0.22.1...v0.22.2) (2024-06-13)


### Bug Fixes

* check if exemption exists before cleanup ([#468](https://github.com/defenseunicorns/uds-core/issues/468)) ([735288b](https://github.com/defenseunicorns/uds-core/commit/735288b87f2dff3c1bb28e9e20aac812d644aa4d))
* pepr operator derived netpol name collisions ([#480](https://github.com/defenseunicorns/uds-core/issues/480)) ([de60e25](https://github.com/defenseunicorns/uds-core/commit/de60e252526d73e439f5665b27f84e8773c24949))
* typo in comment ([#462](https://github.com/defenseunicorns/uds-core/issues/462)) ([582b1f4](https://github.com/defenseunicorns/uds-core/commit/582b1f4754ee3282696ea3b018322a1b3497a7d4))


### Miscellaneous

* **deps:** update checkout to v4.1.7 ([#478](https://github.com/defenseunicorns/uds-core/issues/478)) ([e91a0a3](https://github.com/defenseunicorns/uds-core/commit/e91a0a35252581554d9ed587e4ef72c2c88a3586))
* **deps:** update githubactions to v4.1.3 ([#471](https://github.com/defenseunicorns/uds-core/issues/471)) ([2a9f44d](https://github.com/defenseunicorns/uds-core/commit/2a9f44d20dce66fa474e47ba0c93eaa7fa9ad406))
* **deps:** update uds to v0.11.1 ([#472](https://github.com/defenseunicorns/uds-core/issues/472)) ([12fd798](https://github.com/defenseunicorns/uds-core/commit/12fd79894e71ee06181ccd6f2ac98b84d935066c))
* **deps:** update uds to v0.11.2 ([#479](https://github.com/defenseunicorns/uds-core/issues/479)) ([f967f9a](https://github.com/defenseunicorns/uds-core/commit/f967f9a4bf8d718b9ece96d882db4d9c800f5f0f))
* **deps:** update velero to v1.30.2 ([#476](https://github.com/defenseunicorns/uds-core/issues/476)) ([89bbda9](https://github.com/defenseunicorns/uds-core/commit/89bbda9e640014bede116c254381cab8995df12f))

## [0.22.1](https://github.com/defenseunicorns/uds-core/compare/v0.22.0...v0.22.1) (2024-06-06)


### Bug Fixes

* add saml configuration to k3d standard bundle ([#425](https://github.com/defenseunicorns/uds-core/issues/425)) ([15b41d7](https://github.com/defenseunicorns/uds-core/commit/15b41d7ca506dd913316c41321aa9a3133755ab4))
* de-duplicate renovate matches ([#435](https://github.com/defenseunicorns/uds-core/issues/435)) ([4f9dbbb](https://github.com/defenseunicorns/uds-core/commit/4f9dbbbff0bbe1fe348ae7e6c55f97a505f730a9))
* default keycloak realm envs ([#455](https://github.com/defenseunicorns/uds-core/issues/455)) ([3a2b48f](https://github.com/defenseunicorns/uds-core/commit/3a2b48fefb11afcf20f6826fbdef8c43daaf4639))
* exemption race conditions ([#407](https://github.com/defenseunicorns/uds-core/issues/407)) ([d1b3b56](https://github.com/defenseunicorns/uds-core/commit/d1b3b5669976eb23ca8f88cd5b15a12c56102eca))
* integrated docs ([#431](https://github.com/defenseunicorns/uds-core/issues/431)) ([72238fa](https://github.com/defenseunicorns/uds-core/commit/72238faed167a4e90e4d332e17909510efd98a58))
* keycloak schema for package cr ([#436](https://github.com/defenseunicorns/uds-core/issues/436)) ([e32ce9a](https://github.com/defenseunicorns/uds-core/commit/e32ce9af9176ba8fef702a8c6aac84c15f9ab374))
* networkpolicy for keycloak smtp egress ([4059954](https://github.com/defenseunicorns/uds-core/commit/4059954ed92502f10c1b5b769988a363adc06318))
* nightly testing eks config architecture ([#452](https://github.com/defenseunicorns/uds-core/issues/452)) ([a0bbd1f](https://github.com/defenseunicorns/uds-core/commit/a0bbd1f0bf84f03d59866f9797555a08dc8034d6))
* remove deprecated registry login and add env setup ([#443](https://github.com/defenseunicorns/uds-core/issues/443)) ([ca6b76f](https://github.com/defenseunicorns/uds-core/commit/ca6b76f3a66efb6b2e81832aff771ca06bdff68a))
* remove go mod ([#441](https://github.com/defenseunicorns/uds-core/issues/441)) ([0de9693](https://github.com/defenseunicorns/uds-core/commit/0de969333923afb8fd4639547901c7d7f5c6a6f7))
* remove no-tea and update uds version ([#446](https://github.com/defenseunicorns/uds-core/issues/446)) ([434844b](https://github.com/defenseunicorns/uds-core/commit/434844b827e01808b504abf5ee6af83fba813cb6))
* use updated k3s ([#426](https://github.com/defenseunicorns/uds-core/issues/426)) ([1da1c49](https://github.com/defenseunicorns/uds-core/commit/1da1c49e314c73e6fd1f2ef2940aff983262ec6b))


### Miscellaneous

* add checks before killing pods when updating istio annotations ([#457](https://github.com/defenseunicorns/uds-core/issues/457)) ([a62f9a0](https://github.com/defenseunicorns/uds-core/commit/a62f9a0e04bb538a8018a3f866c88e8b93c59826))
* add debug logs to save logs for easier searching ([#430](https://github.com/defenseunicorns/uds-core/issues/430)) ([319101b](https://github.com/defenseunicorns/uds-core/commit/319101b61e4793037aab6c96b92c9d834763e9b8))
* add velero csi plugin ([#424](https://github.com/defenseunicorns/uds-core/issues/424)) ([c7e49e9](https://github.com/defenseunicorns/uds-core/commit/c7e49e91d9f7810ddc0368f146d43d3c94c782ad))
* **deps:** update githubactions ([#413](https://github.com/defenseunicorns/uds-core/issues/413)) ([ebd834e](https://github.com/defenseunicorns/uds-core/commit/ebd834e56ae9adabe14d9772e4a4d9c305da173c))
* **deps:** update istio to v1.22.1 ([#405](https://github.com/defenseunicorns/uds-core/issues/405)) ([ad4b861](https://github.com/defenseunicorns/uds-core/commit/ad4b861158eecfac1d09a37ea3776e31a1c387cb))
* **deps:** update jest to v29.1.4 ([#438](https://github.com/defenseunicorns/uds-core/issues/438)) ([c3ecc8b](https://github.com/defenseunicorns/uds-core/commit/c3ecc8b83b8c65f09600ab937a1c140c4a5f7db1))
* **deps:** update keycloak to v0.4.4 ([#460](https://github.com/defenseunicorns/uds-core/issues/460)) ([936f40b](https://github.com/defenseunicorns/uds-core/commit/936f40bf078bb06d94ebd51585b4eb7669d426b4))
* **deps:** update keycloak to v0.4.5 ([#461](https://github.com/defenseunicorns/uds-core/issues/461)) ([3592012](https://github.com/defenseunicorns/uds-core/commit/35920121bcdfbdf9b708eb3308ea34763a31246a))
* **deps:** update keycloak to v24.0.5 ([#453](https://github.com/defenseunicorns/uds-core/issues/453)) ([6b0c6fc](https://github.com/defenseunicorns/uds-core/commit/6b0c6fc91f238e367c9f2d54f0daaf9d8065794e))
* **deps:** update keycloak to v24.0.5 ([#454](https://github.com/defenseunicorns/uds-core/issues/454)) ([89911f0](https://github.com/defenseunicorns/uds-core/commit/89911f0ca01ac421a254b79e25124525f464cf51))
* **deps:** update pepr ([#419](https://github.com/defenseunicorns/uds-core/issues/419)) ([d8f0309](https://github.com/defenseunicorns/uds-core/commit/d8f0309b4f9661b1c5bc2d5e574697ee9579e387))
* **deps:** update pepr to v0.4.5 ([#447](https://github.com/defenseunicorns/uds-core/issues/447)) ([f1dba17](https://github.com/defenseunicorns/uds-core/commit/f1dba17076a7c6052ed67e07bdb560fda7604b80))
* **deps:** update prometheus-stack ([#422](https://github.com/defenseunicorns/uds-core/issues/422)) ([a96193e](https://github.com/defenseunicorns/uds-core/commit/a96193e257701dfaf6fccc34246ef3f31e639f3e))
* **deps:** update uds-common to v0.4.4 ([#442](https://github.com/defenseunicorns/uds-core/issues/442)) ([bf6debd](https://github.com/defenseunicorns/uds-core/commit/bf6debdd0d50f6cde11288cd70d8bdf1dcdaaaa0))
* **deps:** update uds-k3d to v0.7.0 ([#428](https://github.com/defenseunicorns/uds-core/issues/428)) ([23b59a2](https://github.com/defenseunicorns/uds-core/commit/23b59a260b2c60791614ca4d39a33e65476e19ee))
* **deps:** update velero ([#408](https://github.com/defenseunicorns/uds-core/issues/408)) ([ffbefda](https://github.com/defenseunicorns/uds-core/commit/ffbefda74777466ef74ad1d5cffff1f4895f323d))
* **deps:** update velero ([#440](https://github.com/defenseunicorns/uds-core/issues/440)) ([4b1a3ea](https://github.com/defenseunicorns/uds-core/commit/4b1a3ead81a80b49e5ccfeb2e4130a4aaebb53a4))
* **deps:** update velero to v6.6.0 ([#456](https://github.com/defenseunicorns/uds-core/issues/456)) ([aff37c1](https://github.com/defenseunicorns/uds-core/commit/aff37c194e321f6a6c92f1bc11fd796cf9f0a9ab))
* **deps:** update zarf to v0.34.0 ([#434](https://github.com/defenseunicorns/uds-core/issues/434)) ([9badf9d](https://github.com/defenseunicorns/uds-core/commit/9badf9d4b9b6f904b1b7a478be5355416dc7fbe0))

## [0.22.0](https://github.com/defenseunicorns/uds-core/compare/v0.21.1...v0.22.0) (2024-05-22)


### Features

* add `expose` service entry for internal cluster traffic ([#356](https://github.com/defenseunicorns/uds-core/issues/356)) ([1bde4cc](https://github.com/defenseunicorns/uds-core/commit/1bde4ccf302864b0c38d093742ca683b96cebe89))
* add reconciliation retries for CRs ([#423](https://github.com/defenseunicorns/uds-core/issues/423)) ([424b57b](https://github.com/defenseunicorns/uds-core/commit/424b57ba91906e1c60e6e92927e37b34d657ad01))
* uds common renovate config ([#391](https://github.com/defenseunicorns/uds-core/issues/391)) ([035786c](https://github.com/defenseunicorns/uds-core/commit/035786cadcd9c1fbaf7e0a798f9c13104a1a9a14))
* uds core docs ([#414](https://github.com/defenseunicorns/uds-core/issues/414)) ([a35ca7b](https://github.com/defenseunicorns/uds-core/commit/a35ca7b484ab59572d8205a625db5447a8771e44))


### Bug Fixes

* mismatched exemption/policy for DropAllCapabilities ([#384](https://github.com/defenseunicorns/uds-core/issues/384)) ([d8ec278](https://github.com/defenseunicorns/uds-core/commit/d8ec27827e2e2e7d85b4eba6b738f4b126264dd9))
* pepr mutation annotation overwrite ([#385](https://github.com/defenseunicorns/uds-core/issues/385)) ([6e56b2a](https://github.com/defenseunicorns/uds-core/commit/6e56b2afec8f54f8c0a4aa4b89fef1d1c754b627))
* renovate config grouping, test-infra ([#411](https://github.com/defenseunicorns/uds-core/issues/411)) ([05fd407](https://github.com/defenseunicorns/uds-core/commit/05fd407e9c3bf6a0bac33de64e892ce2a63275ac))
* renovate pepr comment ([#410](https://github.com/defenseunicorns/uds-core/issues/410)) ([a825388](https://github.com/defenseunicorns/uds-core/commit/a82538817765ad21adb5f6bba283951bf4c23272))


### Miscellaneous

* **deps:** update keycloak ([#390](https://github.com/defenseunicorns/uds-core/issues/390)) ([3e82c4e](https://github.com/defenseunicorns/uds-core/commit/3e82c4ece470a5eea81d937b2b38c455934212e1))
* **deps:** update keycloak to v24.0.4 ([#397](https://github.com/defenseunicorns/uds-core/issues/397)) ([c0420ea](https://github.com/defenseunicorns/uds-core/commit/c0420ea750b3a7dfc8ea6adab5225f76178ef953))
* **deps:** update keycloak to v24.0.4 ([#402](https://github.com/defenseunicorns/uds-core/issues/402)) ([e454576](https://github.com/defenseunicorns/uds-core/commit/e454576a6de53e833d6b925308f09d6007166dde))
* **deps:** update neuvector to v9.4 ([#381](https://github.com/defenseunicorns/uds-core/issues/381)) ([20d4170](https://github.com/defenseunicorns/uds-core/commit/20d4170386d2437826abafc68d87d91dc457022a))
* **deps:** update pepr to 0.31.0 ([#360](https://github.com/defenseunicorns/uds-core/issues/360)) ([fbd61ea](https://github.com/defenseunicorns/uds-core/commit/fbd61ea9665133619aec81726b189449226d8459))
* **deps:** update prometheus-stack ([#348](https://github.com/defenseunicorns/uds-core/issues/348)) ([49cb11a](https://github.com/defenseunicorns/uds-core/commit/49cb11a058a9209cee7019fa552b8c0b2ef73368))
* **deps:** update prometheus-stack ([#392](https://github.com/defenseunicorns/uds-core/issues/392)) ([2e656f5](https://github.com/defenseunicorns/uds-core/commit/2e656f5dc3de2e6561ac313cb1bae478635b86b3))
* **deps:** update uds to v0.10.4 ([#228](https://github.com/defenseunicorns/uds-core/issues/228)) ([1750b23](https://github.com/defenseunicorns/uds-core/commit/1750b2304e3c6f0ce6a60f1ef2873ce8a6ce1502))
* **deps:** update uds-k3d to v0.6.0 ([#398](https://github.com/defenseunicorns/uds-core/issues/398)) ([288f009](https://github.com/defenseunicorns/uds-core/commit/288f00990a715087c9bf1fffd0a63ecf33125a5a))
* **deps:** update velero ([#350](https://github.com/defenseunicorns/uds-core/issues/350)) ([e7cb33e](https://github.com/defenseunicorns/uds-core/commit/e7cb33ea9a13ab9550aab45d8ee437a1ba595d38))
* **deps:** update zarf to v0.33.2 ([#394](https://github.com/defenseunicorns/uds-core/issues/394)) ([201a37b](https://github.com/defenseunicorns/uds-core/commit/201a37b12277880058c14fc05b3c0d4aecbf31e0))

## [0.21.1](https://github.com/defenseunicorns/uds-core/compare/v0.21.0...v0.21.1) (2024-05-02)


### Bug Fixes

* slim-dev monitoring handling ([#383](https://github.com/defenseunicorns/uds-core/issues/383)) ([79927aa](https://github.com/defenseunicorns/uds-core/commit/79927aa58cbb12c849e52b50c00b74629b100b31))


### Miscellaneous

* updating keycloak chart version to align with image ([#378](https://github.com/defenseunicorns/uds-core/issues/378)) ([a60fe2a](https://github.com/defenseunicorns/uds-core/commit/a60fe2afed9f7cff3bcad6b0f563232b47e8025b))

## [0.21.0](https://github.com/defenseunicorns/uds-core/compare/v0.20.0...v0.21.0) (2024-04-30)


### Features

* add `monitor` to operator, fix monitoring setup ([#256](https://github.com/defenseunicorns/uds-core/issues/256)) ([bf67722](https://github.com/defenseunicorns/uds-core/commit/bf67722d4e7e02d44dd29c4436e9a8d2ef960fa5))


### Bug Fixes

* loki s3 overrides ([#365](https://github.com/defenseunicorns/uds-core/issues/365)) ([3545066](https://github.com/defenseunicorns/uds-core/commit/354506647d65b0484332695abbbd58d91d9e7427))
* update neuvector values for least privilege ([#373](https://github.com/defenseunicorns/uds-core/issues/373)) ([7f4de4f](https://github.com/defenseunicorns/uds-core/commit/7f4de4f729e60a258abc40ce34f9c397fae99181))


### Miscellaneous

* add debug logging to endpointslice watch ([#359](https://github.com/defenseunicorns/uds-core/issues/359)) ([da3eb5a](https://github.com/defenseunicorns/uds-core/commit/da3eb5ab4f5e6ced50f838456999995d5be601b7))
* **deps:** update grafana to v7.3.9 ([#353](https://github.com/defenseunicorns/uds-core/issues/353)) ([4a70f40](https://github.com/defenseunicorns/uds-core/commit/4a70f407d5e06919aaa0dc5901f49f7f1b166c9d))
* **deps:** update istio to v1.21.2 ([#258](https://github.com/defenseunicorns/uds-core/issues/258)) ([51c6540](https://github.com/defenseunicorns/uds-core/commit/51c65405c87ed3c147bdd90172ab0588dc8e5db1))
* **deps:** update keycloak ([#349](https://github.com/defenseunicorns/uds-core/issues/349)) ([2ef1813](https://github.com/defenseunicorns/uds-core/commit/2ef181333d2fd853bb8eee2c5deb82430d68c861))
* **deps:** update keycloak to v0.4.2 ([#375](https://github.com/defenseunicorns/uds-core/issues/375)) ([b0bb8e4](https://github.com/defenseunicorns/uds-core/commit/b0bb8e47f78886186514f188a99ff38463a5eac3))
* **deps:** update zarf to v0.33.1 ([#368](https://github.com/defenseunicorns/uds-core/issues/368)) ([296e547](https://github.com/defenseunicorns/uds-core/commit/296e54729c20c9ecee21677daec874a2c8b57b57))
* move api service watch to reconcile ([#362](https://github.com/defenseunicorns/uds-core/issues/362)) ([1822bca](https://github.com/defenseunicorns/uds-core/commit/1822bca6c397a5c8ea64b9355a9ba4f51fde4518))
* refactor promtail extraScrapeConfigs into scrapeConfigs ([#367](https://github.com/defenseunicorns/uds-core/issues/367)) ([2220272](https://github.com/defenseunicorns/uds-core/commit/222027240148e669edf40483d145ffc15567b1b7))
* trigger eks nightly when related files are updated ([#366](https://github.com/defenseunicorns/uds-core/issues/366)) ([6d6e4e0](https://github.com/defenseunicorns/uds-core/commit/6d6e4e0debbca3498cbc21db405eec48b3bcc240))

## [0.20.0](https://github.com/defenseunicorns/uds-core/compare/v0.19.0...v0.20.0) (2024-04-20)


### Features

* add keycloak sso realm values ([#352](https://github.com/defenseunicorns/uds-core/issues/352)) ([74436ea](https://github.com/defenseunicorns/uds-core/commit/74436ea78684a74044efdee14564a6582e659998))
* add saml and attribute/mapper support for keycloak in uds pepr operator ([#328](https://github.com/defenseunicorns/uds-core/issues/328)) ([c53d4ee](https://github.com/defenseunicorns/uds-core/commit/c53d4ee1227d71b60a35419f7c8c9396d71b9508))
* enable sso for neuvector ([#351](https://github.com/defenseunicorns/uds-core/issues/351)) ([597353e](https://github.com/defenseunicorns/uds-core/commit/597353e294e3dc5c06a8d572414e188f9845af8e))
* keycloak PVC customization ([#341](https://github.com/defenseunicorns/uds-core/issues/341)) ([f8eae2a](https://github.com/defenseunicorns/uds-core/commit/f8eae2a20e02faac6e2c441845a82febeaab3b89))


### Bug Fixes

* add nightly uds-bundle.yaml to release-please extras for updates ([#346](https://github.com/defenseunicorns/uds-core/issues/346)) ([d1b3071](https://github.com/defenseunicorns/uds-core/commit/d1b3071182b48ef4905bb040d203fa42d7bbf76f))


### Miscellaneous

* **deps:** update grafana ([#339](https://github.com/defenseunicorns/uds-core/issues/339)) ([52e6c1b](https://github.com/defenseunicorns/uds-core/commit/52e6c1b3bb003402710bc0fa85419538f38b388f))
* **deps:** update neuvector ([#333](https://github.com/defenseunicorns/uds-core/issues/333)) ([010e287](https://github.com/defenseunicorns/uds-core/commit/010e287dbf3a712d19e54bfbbaa87807585130d7))
* **deps:** update pepr ([#340](https://github.com/defenseunicorns/uds-core/issues/340)) ([e71ba4a](https://github.com/defenseunicorns/uds-core/commit/e71ba4ab4eb1ea1cc482b507fef4e0e2735bbd1f))
* **deps:** update prometheus-stack ([#301](https://github.com/defenseunicorns/uds-core/issues/301)) ([143eca3](https://github.com/defenseunicorns/uds-core/commit/143eca3ecc2e3c39765312dc3c5384c87a13d7da))
* **deps:** update to keycloak 24 ([#336](https://github.com/defenseunicorns/uds-core/issues/336)) ([1153ba0](https://github.com/defenseunicorns/uds-core/commit/1153ba09ac062d3477a4ee396376be83493ad3c5))
* **deps:** update uds-identity-config to 0.4.1 ([#355](https://github.com/defenseunicorns/uds-core/issues/355)) ([8485931](https://github.com/defenseunicorns/uds-core/commit/84859316ea92ef9ec7807a702ee246e11b73567b))

## [0.19.0](https://github.com/defenseunicorns/uds-core/compare/v0.18.0...v0.19.0) (2024-04-12)


### Features

* add nightly testing eks ([#250](https://github.com/defenseunicorns/uds-core/issues/250)) ([543b09d](https://github.com/defenseunicorns/uds-core/commit/543b09d103a43c474da6a8c950404cc1f373b03f))


### Bug Fixes

* drop path normalization to MERGE_SLASHES to allow apps to handle encoded slashes ([#330](https://github.com/defenseunicorns/uds-core/issues/330)) ([26e965f](https://github.com/defenseunicorns/uds-core/commit/26e965fd71dd325bd8df451ce317456bf2d15073))
* loki bucket configuration service_account and namespace ([#332](https://github.com/defenseunicorns/uds-core/issues/332)) ([9518634](https://github.com/defenseunicorns/uds-core/commit/9518634b24f2d5c285e598f8620849bbc6288ba4))


### Miscellaneous

* **deps:** update grafana ([#257](https://github.com/defenseunicorns/uds-core/issues/257)) ([c98e566](https://github.com/defenseunicorns/uds-core/commit/c98e5661c3e6fb84bf17fc64170f5dd39779dda7))
* **deps:** update metrics-server ([#298](https://github.com/defenseunicorns/uds-core/issues/298)) ([691fd87](https://github.com/defenseunicorns/uds-core/commit/691fd87ae3e523c897d0461c4a0384b2bb7c8c03))
* **deps:** update pepr ([#324](https://github.com/defenseunicorns/uds-core/issues/324)) ([2ef0f96](https://github.com/defenseunicorns/uds-core/commit/2ef0f96da7476b487d72d4bb7ce4bd50fdb0b182))
* **deps:** update pepr to v0.28.7 ([#321](https://github.com/defenseunicorns/uds-core/issues/321)) ([e7206bb](https://github.com/defenseunicorns/uds-core/commit/e7206bb93ce23a3ae611e410106890df3eafdea1))
* **deps:** update promtail ([#74](https://github.com/defenseunicorns/uds-core/issues/74)) ([6a112b5](https://github.com/defenseunicorns/uds-core/commit/6a112b5226250f1a17023b2c1225d404cf8feeee))
* **deps:** update zarf to v0.32.6 ([#282](https://github.com/defenseunicorns/uds-core/issues/282)) ([443426d](https://github.com/defenseunicorns/uds-core/commit/443426d05b9bd1d15fb4632efa26219250270895))
* **deps:** update zarf to v0.33.0 ([#325](https://github.com/defenseunicorns/uds-core/issues/325)) ([f2a2a66](https://github.com/defenseunicorns/uds-core/commit/f2a2a665309c812b4300047d1c90ff3833a8eba6))
* update codeowners ([#338](https://github.com/defenseunicorns/uds-core/issues/338)) ([c419574](https://github.com/defenseunicorns/uds-core/commit/c41957409607c6335ebf6bd4ff30a1a9336a4870))

## [0.18.0](https://github.com/defenseunicorns/uds-core/compare/v0.17.0...v0.18.0) (2024-03-29)


### Features

* switch loki to simple scalable ([#156](https://github.com/defenseunicorns/uds-core/issues/156)) ([1661b15](https://github.com/defenseunicorns/uds-core/commit/1661b154657eba1b30fc5bcec64179cbf6037c03))


### Bug Fixes

* add kubeapi egress for neuvector enforcer ([#291](https://github.com/defenseunicorns/uds-core/issues/291)) ([87fc886](https://github.com/defenseunicorns/uds-core/commit/87fc886bc736104a9a3c3aefc4c7d232ed74a4f2))
* pepr ironbank renovate update ([#299](https://github.com/defenseunicorns/uds-core/issues/299)) ([287e40d](https://github.com/defenseunicorns/uds-core/commit/287e40db5d65f7472a9e9216aae91f3ad92403d9))
* release workflow k3d image ([#316](https://github.com/defenseunicorns/uds-core/issues/316)) ([e7835e0](https://github.com/defenseunicorns/uds-core/commit/e7835e071f56af148792fbde250100af8e8ca0b8))
* unwanted exemption deletions ([#290](https://github.com/defenseunicorns/uds-core/issues/290)) ([50b0cd4](https://github.com/defenseunicorns/uds-core/commit/50b0cd4211964a90139347558028d6c461956da9))


### Miscellaneous

* add debug output to release workflow ([#285](https://github.com/defenseunicorns/uds-core/issues/285)) ([5f96865](https://github.com/defenseunicorns/uds-core/commit/5f968651fb4f0da563d9c388efab761863f9ea08))
* **deps:** update dependency defenseunicorns/uds-common to v0.3.6 ([#261](https://github.com/defenseunicorns/uds-core/issues/261)) ([1b5398b](https://github.com/defenseunicorns/uds-core/commit/1b5398b7b778ead8ac3265080ae0bd2b5761066e))
* **deps:** update githubactions ([#242](https://github.com/defenseunicorns/uds-core/issues/242)) ([1eb2e2c](https://github.com/defenseunicorns/uds-core/commit/1eb2e2cd2018f0cd8fb55d8e6576b7e36fa8c3cf))
* **deps:** update pepr to v0.28.6 ([#300](https://github.com/defenseunicorns/uds-core/issues/300)) ([86b43e4](https://github.com/defenseunicorns/uds-core/commit/86b43e478521aa88a3a4843948ca96b9cbe55985))
* **deps:** update prometheus-stack ([#190](https://github.com/defenseunicorns/uds-core/issues/190)) ([f9a605a](https://github.com/defenseunicorns/uds-core/commit/f9a605a4c828128fc19f0bdb1d2443f65fb87b8a))
* **deps:** update uds-k3d to v0.6.0 ([#240](https://github.com/defenseunicorns/uds-core/issues/240)) ([6a26523](https://github.com/defenseunicorns/uds-core/commit/6a2652368fde3a3bdbe5bb81fd258830dfaeb5c8))
* **deps:** update velero ([#260](https://github.com/defenseunicorns/uds-core/issues/260)) ([f352008](https://github.com/defenseunicorns/uds-core/commit/f35200833a4d4d50de9f632f6918320f7d8fff5e))
* **main:** release 0.18.0 ([#286](https://github.com/defenseunicorns/uds-core/issues/286)) ([40e6b7b](https://github.com/defenseunicorns/uds-core/commit/40e6b7b711ddbd956058eda8490355568faddaec))
* support headless keycloak admin user ([#307](https://github.com/defenseunicorns/uds-core/issues/307)) ([a0e51b6](https://github.com/defenseunicorns/uds-core/commit/a0e51b649822619b63478b140bb5dbbebeb20ff3))

## [0.17.0](https://github.com/defenseunicorns/uds-core/compare/v0.16.1...v0.17.0) (2024-03-22)


### Features

* introduce sso secret templating ([#276](https://github.com/defenseunicorns/uds-core/issues/276)) ([e0832ec](https://github.com/defenseunicorns/uds-core/commit/e0832ec2ee825dc1725483350e3b9295937b8feb))


### Bug Fixes

* add keycloak to dev bundle and rename ([#262](https://github.com/defenseunicorns/uds-core/issues/262)) ([f9b905c](https://github.com/defenseunicorns/uds-core/commit/f9b905c7c2b7e4a6a43e7c83918e3157008433d3))
* registration robot check form id ([#269](https://github.com/defenseunicorns/uds-core/issues/269)) ([c6419b9](https://github.com/defenseunicorns/uds-core/commit/c6419b962eb5a02462e9060a66f7765689cfeb8f))
* sticky sessions for keycloak in ha ([#281](https://github.com/defenseunicorns/uds-core/issues/281)) ([5ccd557](https://github.com/defenseunicorns/uds-core/commit/5ccd5576afc34d8b24061887f91ce284ec5857a1))


### Miscellaneous

* align mutation annotations ([#268](https://github.com/defenseunicorns/uds-core/issues/268)) ([f18ad4d](https://github.com/defenseunicorns/uds-core/commit/f18ad4db94a77f4229cc9267e0129f6aa3381c9a))
* **deps:** update loki ([#209](https://github.com/defenseunicorns/uds-core/issues/209)) ([03ca499](https://github.com/defenseunicorns/uds-core/commit/03ca499bd5d9cac800bd36dca80340ceac3f3009))
* **deps:** update pepr to v0.28.6 ([#254](https://github.com/defenseunicorns/uds-core/issues/254)) ([54ef7de](https://github.com/defenseunicorns/uds-core/commit/54ef7ded349d060b1732b381124fe29e3e8fe85b))
* **deps:** update zarf to v0.32.5 ([#243](https://github.com/defenseunicorns/uds-core/issues/243)) ([ee93612](https://github.com/defenseunicorns/uds-core/commit/ee9361224767c1a708b6f8e2c266af710facea8d))
* typo fix in README.md ([#280](https://github.com/defenseunicorns/uds-core/issues/280)) ([f9727e0](https://github.com/defenseunicorns/uds-core/commit/f9727e0b638e853bbae131d02019a2efb5286b0a))

## [0.16.1](https://github.com/defenseunicorns/uds-core/compare/v0.16.0...v0.16.1) (2024-03-16)


### Bug Fixes

* arm64 packages / bundles creation ([#264](https://github.com/defenseunicorns/uds-core/issues/264)) ([425fa18](https://github.com/defenseunicorns/uds-core/commit/425fa184fca6bcebd1eea431dce7112cadae2f44))

## [0.16.0](https://github.com/defenseunicorns/uds-core/compare/v0.15.1...v0.16.0) (2024-03-15)


### Features

* add velero package ([#210](https://github.com/defenseunicorns/uds-core/issues/210)) ([a272945](https://github.com/defenseunicorns/uds-core/commit/a27294585f0d50732b63672d0c2baf14948e29d1))
* **operator:** add events and improve lifecycle ops ([#245](https://github.com/defenseunicorns/uds-core/issues/245)) ([502c044](https://github.com/defenseunicorns/uds-core/commit/502c044547048a380b1f73dead0b8ab1b14a4b4f))


### Bug Fixes

* ocsp lookup egress policy ([#255](https://github.com/defenseunicorns/uds-core/issues/255)) ([77c38f2](https://github.com/defenseunicorns/uds-core/commit/77c38f22e9a77d9db81504f4c172fdc535c0929e))


### Miscellaneous

* add flavor to pepr build task ([#238](https://github.com/defenseunicorns/uds-core/issues/238)) ([29bf8a3](https://github.com/defenseunicorns/uds-core/commit/29bf8a3b83255c7548201f3ea19e22452a1d1d4a))
* **deps:** update grafana ([#144](https://github.com/defenseunicorns/uds-core/issues/144)) ([6987927](https://github.com/defenseunicorns/uds-core/commit/698792728faf8cfeabaf7a7c735c91229cc0c07f))
* **deps:** update neuvector ([#73](https://github.com/defenseunicorns/uds-core/issues/73)) ([50f6c90](https://github.com/defenseunicorns/uds-core/commit/50f6c90ca31d5bf984e44fd1ded7c5cfcb968064))
* test artifacts before publish ([#198](https://github.com/defenseunicorns/uds-core/issues/198)) ([9732f32](https://github.com/defenseunicorns/uds-core/commit/9732f325624244f4d34c127a949c6ce5951ff6ab))

## [0.15.1](https://github.com/defenseunicorns/uds-core/compare/v0.15.0...v0.15.1) (2024-03-11)


### Bug Fixes

* **keycloak:** only use PVC for devMode ([#241](https://github.com/defenseunicorns/uds-core/issues/241)) ([a6e6023](https://github.com/defenseunicorns/uds-core/commit/a6e6023134dc5171441a2043701ed91309e1b32c))


### Miscellaneous

* annotate mutations in policies ([#236](https://github.com/defenseunicorns/uds-core/issues/236)) ([cc9db50](https://github.com/defenseunicorns/uds-core/commit/cc9db500bb1033a516104f409fa05b3a1101d832))
* **deps:** update zarf to v0.32.4 ([#203](https://github.com/defenseunicorns/uds-core/issues/203)) ([05c903e](https://github.com/defenseunicorns/uds-core/commit/05c903ea43243401d9cc2928ba5eb66ff6201c94))

## [0.15.0](https://github.com/defenseunicorns/uds-core/compare/v0.14.5...v0.15.0) (2024-03-07)


### Features

* add policy exemptions ([#165](https://github.com/defenseunicorns/uds-core/issues/165)) ([196df88](https://github.com/defenseunicorns/uds-core/commit/196df88b01347e530eb1cb49df7440d62c986e0e))


### Miscellaneous

* **deps:** update dependency defenseunicorns/uds-common to v0.2.2 ([#232](https://github.com/defenseunicorns/uds-core/issues/232)) ([083ae0c](https://github.com/defenseunicorns/uds-core/commit/083ae0c45667e5b9064cbff781fbe4e5bc0d2991))
* **deps:** update githubactions to de90cc6 ([#215](https://github.com/defenseunicorns/uds-core/issues/215)) ([f79eed0](https://github.com/defenseunicorns/uds-core/commit/f79eed03b2495d9f3e11edb433291ce8a3aa55ee))

## [0.14.5](https://github.com/defenseunicorns/uds-core/compare/v0.14.4...v0.14.5) (2024-03-06)


### Bug Fixes

* valueFrom in KeyCloak statefulset.yaml ([#229](https://github.com/defenseunicorns/uds-core/issues/229)) ([189a5ce](https://github.com/defenseunicorns/uds-core/commit/189a5ce3a9dd16fe9646a293ca3948db21eb5d78))

## [0.14.4](https://github.com/defenseunicorns/uds-core/compare/v0.14.3...v0.14.4) (2024-03-05)


### Bug Fixes

* remove spec from secret yaml ([#226](https://github.com/defenseunicorns/uds-core/issues/226)) ([e4b5848](https://github.com/defenseunicorns/uds-core/commit/e4b58487f736f588944f7c039b8654f9006e04f1))

## [0.14.3](https://github.com/defenseunicorns/uds-core/compare/v0.14.2...v0.14.3) (2024-03-05)


### Bug Fixes

* **keycloak:** add missing postgres host and port secret keys ([#224](https://github.com/defenseunicorns/uds-core/issues/224)) ([0c4d775](https://github.com/defenseunicorns/uds-core/commit/0c4d7758cfb077ff592fea907795402485b6c9f5))

## [0.14.2](https://github.com/defenseunicorns/uds-core/compare/v0.14.1...v0.14.2) (2024-03-04)


### Bug Fixes

* basic validations for packages ([#208](https://github.com/defenseunicorns/uds-core/issues/208)) ([9eba3af](https://github.com/defenseunicorns/uds-core/commit/9eba3afb7e288c13f75f93d5712d50a3b9e7b92d))
* keycloak volume permissions, UI update ([#223](https://github.com/defenseunicorns/uds-core/issues/223)) ([4454d3e](https://github.com/defenseunicorns/uds-core/commit/4454d3efcefe6bfa81628d330434afcc246fad65))
* kubeapi netpol generation now also includes the ip from the kubernetes service ([#219](https://github.com/defenseunicorns/uds-core/issues/219)) ([0a83d02](https://github.com/defenseunicorns/uds-core/commit/0a83d02f5782d911e3bb63935b0cac70030e5c9b))


### Miscellaneous

* **deps:** update uds to v0.9.2 ([#200](https://github.com/defenseunicorns/uds-core/issues/200)) ([e4b54fe](https://github.com/defenseunicorns/uds-core/commit/e4b54febc4d7914e962db92b7a0490a3735af4e5))
* **deps:** update uds-k3d to v0.5.0 ([#186](https://github.com/defenseunicorns/uds-core/issues/186)) ([164bf5f](https://github.com/defenseunicorns/uds-core/commit/164bf5f8bd58899f5ec1a179d6d409cfb46b850f))

## [0.14.1](https://github.com/defenseunicorns/uds-core/compare/v0.14.0...v0.14.1) (2024-03-04)


### Bug Fixes

* hotfix for publishing workflows ([#217](https://github.com/defenseunicorns/uds-core/issues/217)) ([5fefa01](https://github.com/defenseunicorns/uds-core/commit/5fefa017d382b7c5557e613b81cd84b27bda85f0))

## [0.14.0](https://github.com/defenseunicorns/uds-core/compare/v0.13.1...v0.14.0) (2024-03-04)


### Features

* add keycloak ([#147](https://github.com/defenseunicorns/uds-core/issues/147)) ([f99d3d5](https://github.com/defenseunicorns/uds-core/commit/f99d3d5d4f89264a21dd76d8847e1cef0325d127))


### Miscellaneous

* **deps:** update dependency defenseunicorns/uds-common to v0.2.1 ([#205](https://github.com/defenseunicorns/uds-core/issues/205)) ([1b01407](https://github.com/defenseunicorns/uds-core/commit/1b01407c4ae3a707db381b07e1364c572c76eceb))
* **deps:** update githubactions to v19 ([#204](https://github.com/defenseunicorns/uds-core/issues/204)) ([d65acd4](https://github.com/defenseunicorns/uds-core/commit/d65acd4e2d37907685ba9083ff98988b4ea1d452))
* **deps:** update loki to v5.43.3 ([#199](https://github.com/defenseunicorns/uds-core/issues/199)) ([40f1554](https://github.com/defenseunicorns/uds-core/commit/40f155469670a4b7290819fc09d28ff1fcc06a81))
* **deps:** update metrics-server ([#123](https://github.com/defenseunicorns/uds-core/issues/123)) ([fb25a97](https://github.com/defenseunicorns/uds-core/commit/fb25a970d6e3b51432164fab05ea2d19d1a638ef))

## [0.13.1](https://github.com/defenseunicorns/uds-core/compare/v0.13.0...v0.13.1) (2024-02-21)


### Bug Fixes

* revert "chore: support deselection of metrics-server" ([#196](https://github.com/defenseunicorns/uds-core/issues/196)) ([25a408d](https://github.com/defenseunicorns/uds-core/commit/25a408daeb7f6daada11c21e451f973ebe92c07c))

## [0.13.0](https://github.com/defenseunicorns/uds-core/compare/v0.12.0...v0.13.0) (2024-02-20)


### Features

* add authservice to uds-core ([#153](https://github.com/defenseunicorns/uds-core/issues/153)) ([b0b33b9](https://github.com/defenseunicorns/uds-core/commit/b0b33b98ae12fe233c922bba55c9328212c2e578))


### Bug Fixes

* validating/mutating webhook networkpolicies and mtls ([#192](https://github.com/defenseunicorns/uds-core/issues/192)) ([b01e629](https://github.com/defenseunicorns/uds-core/commit/b01e62960985dd7cb318372abff296fb96f1012b))


### Miscellaneous

* add security.md ([#189](https://github.com/defenseunicorns/uds-core/issues/189)) ([bf7c1d2](https://github.com/defenseunicorns/uds-core/commit/bf7c1d28e077cf52d4f765b50d7efb8ce5d60fff))
* **deps:** update githubactions ([#179](https://github.com/defenseunicorns/uds-core/issues/179)) ([7797e25](https://github.com/defenseunicorns/uds-core/commit/7797e259b9691099cce9e151ce1ebf9f9f181435))
* **deps:** update githubactions to ebc4d7e ([#183](https://github.com/defenseunicorns/uds-core/issues/183)) ([77357e7](https://github.com/defenseunicorns/uds-core/commit/77357e72cc0344e61fedcab7197aabdd7e4fd2a0))
* **deps:** update githubactions to v3 ([#181](https://github.com/defenseunicorns/uds-core/issues/181)) ([70c5ddf](https://github.com/defenseunicorns/uds-core/commit/70c5ddf1ee0e5017bee4057d96b320812a964f88))
* **deps:** update istio to v1.20.3 ([#163](https://github.com/defenseunicorns/uds-core/issues/163)) ([e45de0e](https://github.com/defenseunicorns/uds-core/commit/e45de0e5917a2ca6c3e30e593e2d9a8d393849a9))
* **deps:** update loki to v5.43.0 ([#180](https://github.com/defenseunicorns/uds-core/issues/180)) ([bab5f7a](https://github.com/defenseunicorns/uds-core/commit/bab5f7aba3644c0e478a17338df4e074b0c1a6a2))
* **deps:** update loki to v5.43.1 ([#182](https://github.com/defenseunicorns/uds-core/issues/182)) ([6cc5fc7](https://github.com/defenseunicorns/uds-core/commit/6cc5fc7f5a07d848cfe4f18dc9a7e2a4cd91b1cf))
* **deps:** update loki to v5.43.2 ([#191](https://github.com/defenseunicorns/uds-core/issues/191)) ([0ec0cd4](https://github.com/defenseunicorns/uds-core/commit/0ec0cd4d6cdc7b4eb1eea33f4da7b144ecbc29a5))
* **deps:** update pepr to v0.25.0 ([#164](https://github.com/defenseunicorns/uds-core/issues/164)) ([e7b8212](https://github.com/defenseunicorns/uds-core/commit/e7b8212b6a8ed2e16b47264687e0c39d2f0a3455))
* **deps:** update uds to v0.9.0 ([#173](https://github.com/defenseunicorns/uds-core/issues/173)) ([b91a90d](https://github.com/defenseunicorns/uds-core/commit/b91a90db987e108a5a093a326428bbd0b5f9446e))
* **deps:** update zarf to v0.32.3 ([#155](https://github.com/defenseunicorns/uds-core/issues/155)) ([2f0a1a7](https://github.com/defenseunicorns/uds-core/commit/2f0a1a77043ce298e765e6999cf11a97f36e4ecc))
* support deselection of metrics-server ([#193](https://github.com/defenseunicorns/uds-core/issues/193)) ([289a0fe](https://github.com/defenseunicorns/uds-core/commit/289a0fee5315e8c4a70b3afe66165dd00a7dfbc1))

## [0.12.0](https://github.com/defenseunicorns/uds-core/compare/v0.11.1...v0.12.0) (2024-02-09)


### Features

* introduce advancedHTTP for expose field & change podLabels to selector ([#154](https://github.com/defenseunicorns/uds-core/issues/154)) ([1079267](https://github.com/defenseunicorns/uds-core/commit/107926791149989a782254b8798b7c57a35cfcaf))


### Miscellaneous

* **deps:** pin dependencies ([#79](https://github.com/defenseunicorns/uds-core/issues/79)) ([bfab11e](https://github.com/defenseunicorns/uds-core/commit/bfab11e345941d23dfeb928917f38e36a2f75bc9))
* remove retry-action action on registry1 docker login ([#160](https://github.com/defenseunicorns/uds-core/issues/160)) ([eea0c93](https://github.com/defenseunicorns/uds-core/commit/eea0c93a0ff172bfc5a76d3eaca143ffc0d9fbe2))

## [0.11.1](https://github.com/defenseunicorns/uds-core/compare/v0.11.0...v0.11.1) (2024-02-08)


### Bug Fixes

* non-vendored zarf command refs ([#157](https://github.com/defenseunicorns/uds-core/issues/157)) ([fe183a9](https://github.com/defenseunicorns/uds-core/commit/fe183a9ae367bc2d7ea7d629e7c15877aabe38cd))

## [0.11.0](https://github.com/defenseunicorns/uds-core/compare/v0.10.0...v0.11.0) (2024-02-07)


### Features

* added initial oscal files ([#145](https://github.com/defenseunicorns/uds-core/issues/145)) ([9600d5f](https://github.com/defenseunicorns/uds-core/commit/9600d5f159e4a04e8f71313f8ed118b87efbb9a1))


### Bug Fixes

* network policy to allow metrics-server ingress ([#148](https://github.com/defenseunicorns/uds-core/issues/148)) ([f1d434a](https://github.com/defenseunicorns/uds-core/commit/f1d434a68ef1f2a29ab3b13608bc16ce78211ed4))


### Miscellaneous

* **deps:** update grafana to v7.2.5 ([#136](https://github.com/defenseunicorns/uds-core/issues/136)) ([a271270](https://github.com/defenseunicorns/uds-core/commit/a271270f2d3f3488aa9664ef5ad69a4d239c5d22))
* **deps:** update grafana to v7.3.0 ([#142](https://github.com/defenseunicorns/uds-core/issues/142)) ([5e960c0](https://github.com/defenseunicorns/uds-core/commit/5e960c0479e6fc96244db0230296c94e936e57d8))
* **deps:** update loki ([#131](https://github.com/defenseunicorns/uds-core/issues/131)) ([61250b0](https://github.com/defenseunicorns/uds-core/commit/61250b02eca7ca57d7f346c1da5b63f19de17c49))
* **deps:** update pepr to v0.24.1 ([#134](https://github.com/defenseunicorns/uds-core/issues/134)) ([6474a1c](https://github.com/defenseunicorns/uds-core/commit/6474a1c0a16c8d87248acb1b3f7d79b76a354fc8))
* **deps:** update prometheus-stack ([#128](https://github.com/defenseunicorns/uds-core/issues/128)) ([625622a](https://github.com/defenseunicorns/uds-core/commit/625622a44c101f0a9c1beffd66eb259dc1f1eedc))
* **deps:** update uds to v0.8.1 ([#141](https://github.com/defenseunicorns/uds-core/issues/141)) ([fa79065](https://github.com/defenseunicorns/uds-core/commit/fa79065265a5ee2b8f6f6a55d1c2904bbaf42fff))
* **deps:** update zarf to v0.32.2 ([#133](https://github.com/defenseunicorns/uds-core/issues/133)) ([91502c6](https://github.com/defenseunicorns/uds-core/commit/91502c6321334c6d31ce5fd1cd8f2fe6f77c09ae))
* readme updates & use UDS CLI for zarf ([#137](https://github.com/defenseunicorns/uds-core/issues/137)) ([21de0ce](https://github.com/defenseunicorns/uds-core/commit/21de0cee2d70d67ca17b1d45c642e9ca4e1617ce))
* renovate updates ([#140](https://github.com/defenseunicorns/uds-core/issues/140)) ([b71a013](https://github.com/defenseunicorns/uds-core/commit/b71a013bea30c9ca5e39f1dc6485fffaa86ca6b1))

## [0.10.0](https://github.com/defenseunicorns/uds-core/compare/v0.9.2...v0.10.0) (2024-01-26)


### Features

* add Istio VirtualService Requestmatch to UDS Operator ([#129](https://github.com/defenseunicorns/uds-core/issues/129)) ([a207197](https://github.com/defenseunicorns/uds-core/commit/a20719726991d3b981a372b705b776948f6fbc30))


### Miscellaneous

* **deps:** update grafana to v10.3.1 ([#132](https://github.com/defenseunicorns/uds-core/issues/132)) ([09e028c](https://github.com/defenseunicorns/uds-core/commit/09e028c63093a6f5fdfd0b1be800b07c0eb9de77))
* **deps:** update istio to v1.20.2 ([#75](https://github.com/defenseunicorns/uds-core/issues/75)) ([671f977](https://github.com/defenseunicorns/uds-core/commit/671f977ff183010ce75e323532db500dcd4aa69c))

## [0.9.2](https://github.com/defenseunicorns/uds-core/compare/v0.9.1...v0.9.2) (2024-01-24)


### Miscellaneous

* **deps:** update grafana ([#80](https://github.com/defenseunicorns/uds-core/issues/80)) ([ccb2c12](https://github.com/defenseunicorns/uds-core/commit/ccb2c1280313fe69198ecab5fea5b38fc650f699))
* **deps:** update loki ([#72](https://github.com/defenseunicorns/uds-core/issues/72)) ([98134bb](https://github.com/defenseunicorns/uds-core/commit/98134bba1f6078a867aae2ae28f4152ba7b1a8e5))
* **deps:** update pepr ([#116](https://github.com/defenseunicorns/uds-core/issues/116)) ([bfa7352](https://github.com/defenseunicorns/uds-core/commit/bfa7352ebe962ef1ed091f4a5799ed4974e086ef))
* **deps:** update prometheus-stack ([#81](https://github.com/defenseunicorns/uds-core/issues/81)) ([19bedb6](https://github.com/defenseunicorns/uds-core/commit/19bedb60cd2f99615c4b5673623ff0ff6fafb73f))
* **deps:** update uds to v0.6.2 ([#107](https://github.com/defenseunicorns/uds-core/issues/107)) ([7b7220e](https://github.com/defenseunicorns/uds-core/commit/7b7220e708cf2dca25cc592b8932661620d9610d))
* **deps:** update uds-k3d to v0.3.1 ([#89](https://github.com/defenseunicorns/uds-core/issues/89)) ([5d54cd1](https://github.com/defenseunicorns/uds-core/commit/5d54cd1efe5eee4c19caf347882725e0aa20e50a))
* refactor ci for releases to remove certain artifacts ([#125](https://github.com/defenseunicorns/uds-core/issues/125)) ([c08a062](https://github.com/defenseunicorns/uds-core/commit/c08a062bb3f3ede6860c3d7f34136b3e82b78715))

## [0.9.1](https://github.com/defenseunicorns/uds-core/compare/v0.9.0...v0.9.1) (2024-01-22)


### Bug Fixes

* update missing flavor create inputs in publish step ([#118](https://github.com/defenseunicorns/uds-core/issues/118)) ([a0233eb](https://github.com/defenseunicorns/uds-core/commit/a0233eb45e2d39035f483f3ed8fb3f396e5030d8))

## [0.9.0](https://github.com/defenseunicorns/uds-core/compare/v0.8.1...v0.9.0) (2024-01-21)


### Features

* add Zarf Flavors to support Iron Bank & upstream images ([#63](https://github.com/defenseunicorns/uds-core/issues/63)) ([232c256](https://github.com/defenseunicorns/uds-core/commit/232c2566b96be0285c24b8b5787350897e72332f))

## [0.8.1](https://github.com/defenseunicorns/uds-core/compare/v0.8.0...v0.8.1) (2024-01-18)


### Bug Fixes

* remove loki gateway anti-affinity ([#111](https://github.com/defenseunicorns/uds-core/issues/111)) ([2cba42e](https://github.com/defenseunicorns/uds-core/commit/2cba42e3a83a25ae7a45f3c3d6a35bdc7bba0b58))

## [0.8.0](https://github.com/defenseunicorns/uds-core/compare/v0.7.4...v0.8.0) (2024-01-16)


### Features

* add UDS Operator and consolidate UDS Policies ([#66](https://github.com/defenseunicorns/uds-core/issues/66)) ([395c1c4](https://github.com/defenseunicorns/uds-core/commit/395c1c4aec324d0d939cc410a6bb92129b26653b))


### Miscellaneous

* adding unit test for registerExemptions() ([#105](https://github.com/defenseunicorns/uds-core/issues/105)) ([5e71fcf](https://github.com/defenseunicorns/uds-core/commit/5e71fcf4751d2e3f6a1e55583ccf76c0fdc76856))
* **deps:** update pepr to v0.22.2 ([#104](https://github.com/defenseunicorns/uds-core/issues/104)) ([0555353](https://github.com/defenseunicorns/uds-core/commit/0555353e5a5dec2aa8685a3987852d1c3788f28c))

## [0.7.4](https://github.com/defenseunicorns/uds-core/compare/v0.7.3...v0.7.4) (2024-01-13)


### Bug Fixes

* change pepr error policy to reject ([#99](https://github.com/defenseunicorns/uds-core/issues/99)) ([10772e2](https://github.com/defenseunicorns/uds-core/commit/10772e2c64f1e4b965b6b644b0008c81025029e9))


### Miscellaneous

* **deps:** update pepr to v0.22.0 ([#102](https://github.com/defenseunicorns/uds-core/issues/102)) ([941902d](https://github.com/defenseunicorns/uds-core/commit/941902dcfc2ec1d5340d658f75811b3369489c56))

## [0.7.3](https://github.com/defenseunicorns/uds-core/compare/v0.7.2...v0.7.3) (2024-01-11)


### Bug Fixes

* add test for disallow selinux options and handle checking for us… ([#96](https://github.com/defenseunicorns/uds-core/issues/96)) ([88b969e](https://github.com/defenseunicorns/uds-core/commit/88b969e2aa4dea8b76dbe397d77c53941f7cfbc8))


### Miscellaneous

* **deps:** update uds to v0.5.3, zarf to v0.32.1, and uds-k3d to 0.3.0 ([#77](https://github.com/defenseunicorns/uds-core/issues/77)) ([596f9d8](https://github.com/defenseunicorns/uds-core/commit/596f9d8df51c3df1aa87fd0e09d9e69c87473bf0))
* open the aperture for pr workflow triggering ([#90](https://github.com/defenseunicorns/uds-core/issues/90)) ([d8a72f2](https://github.com/defenseunicorns/uds-core/commit/d8a72f2f2f3e507a4be7f217e23b737e3d4c35ce))
* simplify promtail values for scrape configs ([#94](https://github.com/defenseunicorns/uds-core/issues/94)) ([6c2513b](https://github.com/defenseunicorns/uds-core/commit/6c2513be89f064b44516b1d89c0d6005dd1d4d30))

## [0.7.2](https://github.com/defenseunicorns/uds-core/compare/v0.7.1...v0.7.2) (2024-01-09)


### Bug Fixes

* wait on istio proxies ([#87](https://github.com/defenseunicorns/uds-core/issues/87)) ([51cd5a0](https://github.com/defenseunicorns/uds-core/commit/51cd5a012cc1d095a89b30a22910d3d7ad49885d))


### Miscellaneous

* kick off ci ([1afc3a4](https://github.com/defenseunicorns/uds-core/commit/1afc3a4203cce1a1c81b15e7ba6caad1a9c63131))

## [0.7.1](https://github.com/defenseunicorns/uds-core/compare/v0.7.0...v0.7.1) (2024-01-08)


### Bug Fixes

* loki local storage ([#84](https://github.com/defenseunicorns/uds-core/issues/84)) ([b9505bb](https://github.com/defenseunicorns/uds-core/commit/b9505bbb42b5369c62d7cbfb05e1efb8b8a6200f))


### Miscellaneous

* **deps:** update pepr ([#76](https://github.com/defenseunicorns/uds-core/issues/76)) ([50de920](https://github.com/defenseunicorns/uds-core/commit/50de920bcf03092d16a11ebf77ede70987a7cdcf))

## [0.7.0](https://github.com/defenseunicorns/uds-core/compare/v0.6.2...v0.7.0) (2024-01-05)


### Features

* update security policy to use provided user, group, and fsgroup ([#82](https://github.com/defenseunicorns/uds-core/issues/82)) ([6d641ce](https://github.com/defenseunicorns/uds-core/commit/6d641ce67210999bacda0e855269dca61e7c6a7b))


### Miscellaneous

* initial renovate config ([#67](https://github.com/defenseunicorns/uds-core/issues/67)) ([2cd19d8](https://github.com/defenseunicorns/uds-core/commit/2cd19d871a95491950d43fea8e8fd2e8c290cd55))

## [0.6.2](https://github.com/defenseunicorns/uds-core/compare/v0.6.1...v0.6.2) (2023-12-11)


### Miscellaneous

* add minio deploy time bundle variable override definitions ([#58](https://github.com/defenseunicorns/uds-core/issues/58)) ([ca28e7b](https://github.com/defenseunicorns/uds-core/commit/ca28e7b4c4a42769934cc8ad69361ff29a348cc5))
* refactor validate.yaml file name and task name ([#62](https://github.com/defenseunicorns/uds-core/issues/62)) ([92a04ea](https://github.com/defenseunicorns/uds-core/commit/92a04ea1096448995ccc0dd9d77a32a5061e06f0))

## [0.6.1](https://github.com/defenseunicorns/uds-core/compare/v0.6.0...v0.6.1) (2023-12-07)


### Bug Fixes

* resolve istio job termination container status logic issue ([#55](https://github.com/defenseunicorns/uds-core/issues/55)) ([c0142c2](https://github.com/defenseunicorns/uds-core/commit/c0142c213446a37185cdf9dec5ae60aaae8ba194))

## [0.6.0](https://github.com/defenseunicorns/uds-core/compare/v0.5.0...v0.6.0) (2023-12-05)


### Features

* introduce Pepr common policies ([#50](https://github.com/defenseunicorns/uds-core/issues/50)) ([54182b4](https://github.com/defenseunicorns/uds-core/commit/54182b4db691d86ce80379be272d924d105b0d07))


### Miscellaneous

* conform to latest uds bundle schema ([#52](https://github.com/defenseunicorns/uds-core/issues/52)) ([14dad38](https://github.com/defenseunicorns/uds-core/commit/14dad3819187d4f8e13f7bbc191dca74a29b9c98))

## [0.5.0](https://github.com/defenseunicorns/uds-core/compare/v0.4.1...v0.5.0) (2023-11-19)


### Features

* expose tls certs as UDS bundle variables ([#48](https://github.com/defenseunicorns/uds-core/issues/48)) ([c1f8286](https://github.com/defenseunicorns/uds-core/commit/c1f828650ef2c53a3fd9ed477950046020c5d375))

## [0.4.1](https://github.com/defenseunicorns/uds-core/compare/v0.4.0...v0.4.1) (2023-11-17)


### Bug Fixes

* metrics-server mTLS fix ([#44](https://github.com/defenseunicorns/uds-core/issues/44)) ([4853522](https://github.com/defenseunicorns/uds-core/commit/4853522c9504c87dcbd8319d689ecb0a1cb42c0b))


### Miscellaneous

* dep updates for UDS CLI & Pepr ([#46](https://github.com/defenseunicorns/uds-core/issues/46)) ([1037634](https://github.com/defenseunicorns/uds-core/commit/10376349e350bd32f3bf32577d8f8089c09ac6cc))

## [0.4.0](https://github.com/defenseunicorns/uds-core/compare/v0.3.0...v0.4.0) (2023-11-16)


### Features

* add monitoring and logging ([#33](https://github.com/defenseunicorns/uds-core/issues/33)) ([c6d9aec](https://github.com/defenseunicorns/uds-core/commit/c6d9aece4984421e1ccbf476cd0d40fb701e4e50))

## [0.3.0](https://github.com/defenseunicorns/uds-core/compare/v0.2.0...v0.3.0) (2023-11-15)


### Features

* add metrics-server ([#35](https://github.com/defenseunicorns/uds-core/issues/35)) ([8216ab9](https://github.com/defenseunicorns/uds-core/commit/8216ab982be79dc393a2e0db359370b32e660150))

## [0.2.0](https://github.com/defenseunicorns/uds-core/compare/v0.1.3...v0.2.0) (2023-11-13)


### Features

* add pepr capability for istio + jobs ([#12](https://github.com/defenseunicorns/uds-core/issues/12)) ([c32a703](https://github.com/defenseunicorns/uds-core/commit/c32a70390f443c90796978ad4c42bbb4b17eb226))
* embed tls certs in istio package ([#32](https://github.com/defenseunicorns/uds-core/issues/32)) ([fb04fee](https://github.com/defenseunicorns/uds-core/commit/fb04feec9657f449366389a0e0a474a8cdeecb2c))

## [0.1.3](https://github.com/defenseunicorns/uds-core/compare/v0.1.2...v0.1.3) (2023-11-10)


### Miscellaneous

* bump zarf & uds-k3d deps ([#30](https://github.com/defenseunicorns/uds-core/issues/30)) ([dd28ab3](https://github.com/defenseunicorns/uds-core/commit/dd28ab3acd163aaccdfb76fbf9726c02a2ff0050))

## [0.1.2](https://github.com/defenseunicorns/uds-core/compare/v0.1.1...v0.1.2) (2023-11-09)


### Miscellaneous

* fix missing deps in tag and release workflow ([#28](https://github.com/defenseunicorns/uds-core/issues/28)) ([1e1af76](https://github.com/defenseunicorns/uds-core/commit/1e1af762e8eb1dd331cbd681e48ecc95ec3184d2))

## [0.1.1](https://github.com/defenseunicorns/uds-core/compare/v0.1.0...v0.1.1) (2023-11-09)


### Features

* Add istio and preliminary ci ([#3](https://github.com/defenseunicorns/uds-core/issues/3)) ([fbd7453](https://github.com/defenseunicorns/uds-core/commit/fbd745392340dbc978b27f0d321f3375882c1c40))
* add prometheus-stack (monitoring) capability ([#2](https://github.com/defenseunicorns/uds-core/issues/2)) ([e438ab6](https://github.com/defenseunicorns/uds-core/commit/e438ab6089bc9d8c6640fa002285d38ddc3022df))
* release-please integration ([#25](https://github.com/defenseunicorns/uds-core/issues/25)) ([bf3c53b](https://github.com/defenseunicorns/uds-core/commit/bf3c53b2ddac4e02e31aa3429029dd9f1c9595e3))


### Bug Fixes

* complete incomplete deploy task ([#21](https://github.com/defenseunicorns/uds-core/issues/21)) ([45ff5e5](https://github.com/defenseunicorns/uds-core/commit/45ff5e5d7b6a50cdfcfabb174349ab539a8accd9))


### Miscellaneous

* add commit lint workflow ([#19](https://github.com/defenseunicorns/uds-core/issues/19)) ([776a632](https://github.com/defenseunicorns/uds-core/commit/776a6325821329b2cbd97da2f40a30447cd48efc))
* remove version from neuvector zarf.yaml ([#11](https://github.com/defenseunicorns/uds-core/issues/11)) ([fbc8d51](https://github.com/defenseunicorns/uds-core/commit/fbc8d51e2b4146d394184d7596cd9a54219dc001))
* update release please extra-files to be explicit ([#26](https://github.com/defenseunicorns/uds-core/issues/26)) ([23f4999](https://github.com/defenseunicorns/uds-core/commit/23f49995771fb05cd18e7a077bf90e86ca5b7471))

## [0.0.0] - YYYY-MM-DD
PRE RELEASE

### Added
- Initial CHANGELOG.md
- CODEOWNERS
- CONTRIBUTING.md
- DEVELOPMENT_MAINTENANCE.md
- LICENSE
- READEME.md
- zarf.yaml
