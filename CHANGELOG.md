# Changelog

## [9.0.0](https://github.com/PatrickSpies/nestjs-otel/compare/v8.1.0...v9.0.0) (2026-09-01)


### ⚠ BREAKING CHANGES

* making metric decorators to comply with otel naming convention standard
* major cleanup, removing temporary middleware features
* 
* Too many changes since I last commited to this project.
* updates to latest metric sdk and drop node-sdk dependency
* support latest metric sdk
* Anything related to metrics sdk has changed. OTEL now has a stable spec and all the projects are moving towards new interfaces.
* removes nodeSDKConfiguration option

### Features

* add  current span, traceable and baggage decorators ([0d4039b](https://github.com/PatrickSpies/nestjs-otel/commit/0d4039b63793c1e8617878c60447c310bafbf99e))
* add defaultLabels support ([6efb0a5](https://github.com/PatrickSpies/nestjs-otel/commit/6efb0a540546bd78d0ea582e949beb3c77be3288))
* add http size and server abort metrics ([ba64308](https://github.com/PatrickSpies/nestjs-otel/commit/ba64308e7c986cddceed06f2248476c66747f4c6))
* add metric decorators ([9931c5e](https://github.com/PatrickSpies/nestjs-otel/commit/9931c5e5e6e0fd2b32f09c902160d732a058f3d6))
* add metric decorators ([9263bd0](https://github.com/PatrickSpies/nestjs-otel/commit/9263bd0844e203920375ca04a4876fe60e8ea2a7))
* add overloads to Span decorator ([665753b](https://github.com/PatrickSpies/nestjs-otel/commit/665753b73b6750e4b06e4a7cd468f2b0455b43ac))
* add support for capturing method return values in span decorator ([09c8eea](https://github.com/PatrickSpies/nestjs-otel/commit/09c8eea288fd93ef9a273f86952cb258ee2c59a6))
* add wide events support for tracing ([c907a6d](https://github.com/PatrickSpies/nestjs-otel/commit/c907a6d3fdb132fb368b718fccc6d4eeb27d3797))
* add wide events support for tracing ([378f884](https://github.com/PatrickSpies/nestjs-otel/commit/378f88440029c7d6b515b050ecb64d1ca4277c5c))
* allow passing options to Span decorator without explicit name ([b73a213](https://github.com/PatrickSpies/nestjs-otel/commit/b73a213b75d6d293dc2c3aeac1b1a8a813dfa4a0))
* **build:** update dependencies ([c2f8b7b](https://github.com/PatrickSpies/nestjs-otel/commit/c2f8b7b9fbe116953521fb6b5d7f4648d09d7712))
* bumps major version ([fc9aacb](https://github.com/PatrickSpies/nestjs-otel/commit/fc9aacb39a8f3340ec4b4a22ad6c5eb61c9dc71e))
* changes license to Apache2 ([5129fdb](https://github.com/PatrickSpies/nestjs-otel/commit/5129fdba49a834437faddda20044afd3d91ea7a7))
* ename value recorder on decorators and update readme ([646e2ea](https://github.com/PatrickSpies/nestjs-otel/commit/646e2eacd07127f9658b302c09d3056b3b2e1771))
* export MetricService ([6ed93ae](https://github.com/PatrickSpies/nestjs-otel/commit/6ed93ae526dec7ed1c7f4eacb043c2df7168fc70))
* improves api metrics middleware ([2930172](https://github.com/PatrickSpies/nestjs-otel/commit/29301729dfcd0f721f21d19538acdf9868ed75d3))
* improves api metrics middleware ([df50305](https://github.com/PatrickSpies/nestjs-otel/commit/df503056087f1c128fe4999fbb77f8b45a6a1a74))
* major cleanup, removing temporary middleware features ([68deeee](https://github.com/PatrickSpies/nestjs-otel/commit/68deeeef64243067ac7a300edece115cefddfc90))
* Make metrics exporter generic ([2021db0](https://github.com/PatrickSpies/nestjs-otel/commit/2021db0f872f3c8c422e2972dca04e7c658f6249))
* making metric decorators to comply with otel naming convention standard ([39f3778](https://github.com/PatrickSpies/nestjs-otel/commit/39f37789462843c3256ddfa840b9b9471fe3524d))
* metric prefixes ([4c047b8](https://github.com/PatrickSpies/nestjs-otel/commit/4c047b8abdaa6a0c6b63a6b8a8aeb6ff1d8d702f))
* metric prefixes ([7b6928a](https://github.com/PatrickSpies/nestjs-otel/commit/7b6928ab7ff4146fdb95a928b5babcb1d0490de8))
* **metrics:** added Gauge metric to service and decorators ([a1aced4](https://github.com/PatrickSpies/nestjs-otel/commit/a1aced4d6096e5881b0eec5108dad3605690118e))
* **metrics:** option for ignoring undefined routes ([fd4a221](https://github.com/PatrickSpies/nestjs-otel/commit/fd4a221145460004a307cf17fceaf11bd87ee5ba))
* **metrics:** option for ignoring undefined routes ([15577e8](https://github.com/PatrickSpies/nestjs-otel/commit/15577e83c7b3ea7642dc7eba65517361edfe3a54))
* **metrics:** option to ignore specific routes ([6723a86](https://github.com/PatrickSpies/nestjs-otel/commit/6723a86c0ca93b95d4fb8925526cbdd7957d8acb))
* **metrics:** option to ignore specific routes ([b8a05f1](https://github.com/PatrickSpies/nestjs-otel/commit/b8a05f1ef46b9e077f8c4edbad59f91b00d3a49e))
* **middleware:** backward compatibility for nestjs v10 and proper support for v11 middleware ([cde1480](https://github.com/PatrickSpies/nestjs-otel/commit/cde1480d45334d086e3c5ae9b5e0cb3b4cf8a591))
* **middleware:** backward compatibility for nestjs v10 and proper support for v11 middleware ([f22d1e5](https://github.com/PatrickSpies/nestjs-otel/commit/f22d1e5b03271c8f5d34831054eb1a6bdcd93682))
* node-sdk to be defined by the user instead of through the lib ([34603c5](https://github.com/PatrickSpies/nestjs-otel/commit/34603c577d6b4a39a4088ae0d10c1aa93f589bcc))
* node-sdk to be defined by the user instead of through the lib ([5156324](https://github.com/PatrickSpies/nestjs-otel/commit/5156324b64cee8fccd2d06eaf5d155e22a5c0fbf))
* remove unused constant and reorganize pkgs ([d37fc28](https://github.com/PatrickSpies/nestjs-otel/commit/d37fc28c7bc3944399cda157a6ee87a5b83919e3))
* removes prometheus Interface and use metrics instead ([f3fd29e](https://github.com/PatrickSpies/nestjs-otel/commit/f3fd29eab94cb6ab4302d7990d25a3bcc3250f56))
* sets meter provider globally on sdk ([4be57ef](https://github.com/PatrickSpies/nestjs-otel/commit/4be57ef02eeff516ef5b7ceb88731e2de570f553))
* span decorator can use method params ([57f105d](https://github.com/PatrickSpies/nestjs-otel/commit/57f105dba039982057f17129f7847f4f337482cf))
* span decorator has access to function params ([c653dc7](https://github.com/PatrickSpies/nestjs-otel/commit/c653dc7ce4f28d1ca8df9009aa7601f054d39a96))
* support all metric types from otel spec ([36a7c5f](https://github.com/PatrickSpies/nestjs-otel/commit/36a7c5f2f895157b3e675a7a6ff6693fea6cc8f2))
* support forRootAsync ([8cb00a4](https://github.com/PatrickSpies/nestjs-otel/commit/8cb00a455e65e1de9b893291720c037b29a847aa))
* support latest metric sdk ([e8d2e96](https://github.com/PatrickSpies/nestjs-otel/commit/e8d2e96da5161cd5c4ee78290244144f5849ec8b))
* support otel 2.x and drop support for nestjs10 ([5eaa042](https://github.com/PatrickSpies/nestjs-otel/commit/5eaa0426a9b348ba0cc631e0cc3c6d1024c89739))
* **tracing:** pass options with span decorator ([782ae5f](https://github.com/PatrickSpies/nestjs-otel/commit/782ae5ff766c992d44478f6afcf363fe89515957))
* **tracing:** pass options with span decorator ([3424b88](https://github.com/PatrickSpies/nestjs-otel/commit/3424b884e949792679dac79f7b3624cc6e67b110))
* update api metrics to use route match path instead of full route ([ad51bac](https://github.com/PatrickSpies/nestjs-otel/commit/ad51bac1b0121257434cc4543853227669f15aca)), closes [#48](https://github.com/PatrickSpies/nestjs-otel/issues/48)
* update api metrics to use route match path instead of full route and fixes forRootAsync ([7cdbd24](https://github.com/PatrickSpies/nestjs-otel/commit/7cdbd2466567e54a716e07fb929c983975e4f413))
* update dependencies to latest ([385e3db](https://github.com/PatrickSpies/nestjs-otel/commit/385e3db485633257a498e25005086bf5b60331ac))
* update deps ([94715b4](https://github.com/PatrickSpies/nestjs-otel/commit/94715b4694bc261ae16a3f778cd03bbc7e28ea1e))
* update metric spec to the latest otel lib ([6ed63ae](https://github.com/PatrickSpies/nestjs-otel/commit/6ed63aefbc1e39da9659d6e232a4883f7ed93dac))
* update packages ([163ba38](https://github.com/PatrickSpies/nestjs-otel/commit/163ba38a1d231aee66b2c2f53356f2d1fd37d3ee))
* update packages ([d0f92fb](https://github.com/PatrickSpies/nestjs-otel/commit/d0f92fb64e56005537e7a4b06357685fe290baf9))
* update packages ([28fdc69](https://github.com/PatrickSpies/nestjs-otel/commit/28fdc6944901376dcd93037982b52f255799d207))
* update packages to compply with latest otel metric spec ([943ca06](https://github.com/PatrickSpies/nestjs-otel/commit/943ca06ea62e95d8a07af63030609f226b78c4b8))
* update peer dependency to allow support for both v7 and v8 of NestJs ([647eb89](https://github.com/PatrickSpies/nestjs-otel/commit/647eb8906675414a05d14640c2374be1e8837f0e))
* update peer dependency to allow support for both v7 and v8 of NestJS ([dab7acc](https://github.com/PatrickSpies/nestjs-otel/commit/dab7acc507f605aa3d71443158506e741cc08d3c))
* update remaining counters ([d11f6d9](https://github.com/PatrickSpies/nestjs-otel/commit/d11f6d98cf25639c01e24c9007a43d3e06c32738))
* update to stable packages ([76b577c](https://github.com/PatrickSpies/nestjs-otel/commit/76b577c754728c19fb5fad6bae382f53e9a4d004))
* updates to latest metric sdk and drop node-sdk dependency ([46c2df3](https://github.com/PatrickSpies/nestjs-otel/commit/46c2df35a99810931f13a689c6e80b6135f4958c))
* **wide-events:** capture error stack and accumulate timer durations ([02e6526](https://github.com/PatrickSpies/nestjs-otel/commit/02e6526a97a7ffcb7074e966ae387b838bba5f6f))
* **wide-events:** target trace root span via span processor ([a9b3778](https://github.com/PatrickSpies/nestjs-otel/commit/a9b377834f2f2e212710564101b07310d33234f0))


### Bug Fixes

* [#231](https://github.com/PatrickSpies/nestjs-otel/issues/231) Remove unnecessary files from package bundle ([8940ec7](https://github.com/PatrickSpies/nestjs-otel/commit/8940ec78e8a9c759508d2114b57b8cfeef2a7679))
* [#231](https://github.com/PatrickSpies/nestjs-otel/issues/231) Remove unnecessary files from package bundle ([faa521b](https://github.com/PatrickSpies/nestjs-otel/commit/faa521b9ce5895a444008f59022dca6009142121))
* **#171:** fixes missing observation callback for observable metrics ([7d89c1f](https://github.com/PatrickSpies/nestjs-otel/commit/7d89c1f910b28d0661da6f2989ddea4b9bdcc643)), closes [#171](https://github.com/PatrickSpies/nestjs-otel/issues/171)
* `Span` being incompatible with `MethodDecorator` type ([388bd50](https://github.com/PatrickSpies/nestjs-otel/commit/388bd505d1bb0a0982f04ebf2c0e4fcbe3a14a41))
* `Span` being incompatible with `MethodDecorator` type ([75dbf0e](https://github.com/PatrickSpies/nestjs-otel/commit/75dbf0ece685f5b9d466769368985618828a40a5))
* add chatmodes and fix updown decorator bug ([b16d7b8](https://github.com/PatrickSpies/nestjs-otel/commit/b16d7b83da1d872c171a681587a6866b25e6e72e))
* bump nestjs requirement to 9.x ([24cde7c](https://github.com/PatrickSpies/nestjs-otel/commit/24cde7c7da4243288d1b42b6aeddb109b7353aa2))
* dont eagerly trigger on functions that return thennable objects ([811c3be](https://github.com/PatrickSpies/nestjs-otel/commit/811c3be67b1f445edebddf17a934638829610943))
* dont eagerly trigger on functions that return thennable objects ([afee4ff](https://github.com/PatrickSpies/nestjs-otel/commit/afee4ff7df733ca381fe6a2de1910e106330f006))
* enable nestjs 7.x as peer dependency ([e6c6a1e](https://github.com/PatrickSpies/nestjs-otel/commit/e6c6a1e9dd2ae0f906dea2775faaf7a51daeb755))
* error nodeMetrics is not a function ([cf7d0fc](https://github.com/PatrickSpies/nestjs-otel/commit/cf7d0fc2e0d728470b5b259932bfad4be8f6aa3c))
* eslint setup ([14d9870](https://github.com/PatrickSpies/nestjs-otel/commit/14d9870d9aacee325a7338dd764ccfef404b7ad5))
* exports MetricService on core module ([e8096a6](https://github.com/PatrickSpies/nestjs-otel/commit/e8096a65a262a1213e3f7117b74f657b812fbed0))
* fix/metric annotation wrongly typed ([3f8b4a4](https://github.com/PatrickSpies/nestjs-otel/commit/3f8b4a4e1e5193ef47cdfbe5d4af8981b78a9b84))
* fixes forRootAsync usage ([a390f0e](https://github.com/PatrickSpies/nestjs-otel/commit/a390f0e564227b5e9019d1b8da19e4966e3d7ddf))
* forRootAsync uses the wrong module again ([f587225](https://github.com/PatrickSpies/nestjs-otel/commit/f5872257430fc54a3a1f8d320dec701be73a27a9))
* forRootAsync uses the wrong module and empty options breaks the configure method ([c2dc102](https://github.com/PatrickSpies/nestjs-otel/commit/c2dc102d41f2ddc1ca3e8a814e7243fc4cc4b773))
* getSpan returning undefined, enable strict null checks ([#361](https://github.com/PatrickSpies/nestjs-otel/issues/361)) ([b7f7cbd](https://github.com/PatrickSpies/nestjs-otel/commit/b7f7cbd2fb04d897cc702f02cfac24288fda27f1))
* invalid values for error count metrics ([7b13c0b](https://github.com/PatrickSpies/nestjs-otel/commit/7b13c0bb557b05d20da5e85bf3cd3b946cbc7f0f))
* latency buckets are not matching the expected time unit in milliseconds ([cfcae07](https://github.com/PatrickSpies/nestjs-otel/commit/cfcae079379f6a31c6d6f6fe17ff152637b55c82))
* latency buckets are not matching the expected time unit in milliseconds ([c269bac](https://github.com/PatrickSpies/nestjs-otel/commit/c269bac0826360e30bde656c9a9f0826a588c813))
* linting ([1961f18](https://github.com/PatrickSpies/nestjs-otel/commit/1961f18ae1203a4e721e72caeb9f425f1937d918))
* **linting:** fixes all linting warnings and errors ([f824c70](https://github.com/PatrickSpies/nestjs-otel/commit/f824c70fa4d20503d5e45fffad5f4c254ac5443a))
* **linting:** replace unnamed function with arrow function ([12fa02c](https://github.com/PatrickSpies/nestjs-otel/commit/12fa02c081ef85ddde7208c7b865efcaa05bab6f))
* make sure decorators keep metadata ([2cd8024](https://github.com/PatrickSpies/nestjs-otel/commit/2cd8024cd8806c36b3c591430ce43afd703f9f19))
* **metric:** fixes metric service not properly reusing existing metrics ([5001ed0](https://github.com/PatrickSpies/nestjs-otel/commit/5001ed0c3f2c8221a8d17b3f3cec15f6850d5cd2))
* **metric:** fixes metric service not properly reusing existing metrics ([9f24fd8](https://github.com/PatrickSpies/nestjs-otel/commit/9f24fd8a76e6ee0060468de1326265c1fb7b4824))
* metrics for fastify platform ([4b61e70](https://github.com/PatrickSpies/nestjs-otel/commit/4b61e7079d5470088b92d459e7923e4460dd606c))
* **metrics:** add missing commas in example config in README.md ([7b159c6](https://github.com/PatrickSpies/nestjs-otel/commit/7b159c603bc9655b270f9447414cdab473b31526))
* **metrics:** make sure metadata is kept ([de7ca0f](https://github.com/PatrickSpies/nestjs-otel/commit/de7ca0f387dbe44142c58c827ccd777348ae491b))
* **middleware:** fixes api middleware when no requesting invalid route ([2a008d9](https://github.com/PatrickSpies/nestjs-otel/commit/2a008d9ab605a1660c0e5015bd7d635813e3fc57))
* preserve class name decorated with OtelInstanceCounter ([b44fa37](https://github.com/PatrickSpies/nestjs-otel/commit/b44fa37fe8a30bbebbc443699cec5b7717dae259))
* preserve method and class name decorated with OtelXxxCounter ([4019981](https://github.com/PatrickSpies/nestjs-otel/commit/40199819c5b154a7d270f80d08de6173077aad16))
* preserve method name decorated with OtelMethodCounter ([9164a87](https://github.com/PatrickSpies/nestjs-otel/commit/9164a8799b0d023e5bc7e4022c750a6c88157fdd))
* properly configure provenance for build & update dev packages ([5b8b5b7](https://github.com/PatrickSpies/nestjs-otel/commit/5b8b5b71815ddaddad64a905ab2b140f08b2432d))
* properly configure provenance for build & update dev packages ([19657ba](https://github.com/PatrickSpies/nestjs-otel/commit/19657ba4f7e827af75ee0bf4f961af42cf009bd4))
* properly ignore /metrics path on middleware ([45973a4](https://github.com/PatrickSpies/nestjs-otel/commit/45973a4abd8270acc789aeecfe93a8b05f98b30a))
* removed .npmrc file, as it only had default values ([c27a8af](https://github.com/PatrickSpies/nestjs-otel/commit/c27a8af8d757ec67113158a3ee466adca32c9b04))
* removed MeterProvider.addMetricReader deprecation ([17d348d](https://github.com/PatrickSpies/nestjs-otel/commit/17d348d530f1803500771dfd0b6f1f87f0001c76))
* resolve problems with conditional dependency and default configs and add jest config ([1f1fb12](https://github.com/PatrickSpies/nestjs-otel/commit/1f1fb12dcc2df42f2f3082031f31248c246128c1))
* rework param decorators to get correct type ([3ba9fe9](https://github.com/PatrickSpies/nestjs-otel/commit/3ba9fe91f5615e95fe32b517c99ebaa865348461))
* should support both 9 and 10 versions ([50f2273](https://github.com/PatrickSpies/nestjs-otel/commit/50f22736d44c5ce690a55b0c605ff4becc97b5a6))
* span decorator preserves original method name ([b8784c5](https://github.com/PatrickSpies/nestjs-otel/commit/b8784c5b102f9e1b88d6a2e7cf6b395245657aed))
* span decorator preserves original method name ([84de475](https://github.com/PatrickSpies/nestjs-otel/commit/84de475e8ac41a61684c31b35d61889fb6206fbe))
* support nestjs 11 ([5a49545](https://github.com/PatrickSpies/nestjs-otel/commit/5a49545b167439284dbb65b054b1b3c695fb8ede))
* support nestjs 11 ([229ca4f](https://github.com/PatrickSpies/nestjs-otel/commit/229ca4fd9ebf2af897588ac48c5cb4f569e85455))
* **tracing:** make sure metadata is kept ([c34ae56](https://github.com/PatrickSpies/nestjs-otel/commit/c34ae561e73daea879f6871f2f781a565d03a95a))
* **tracing:** record exception and set correct span status ([616c12b](https://github.com/PatrickSpies/nestjs-otel/commit/616c12b157f7736e9fd45cd38bf9a4c21c11e140))
* **tracing:** span status not correctly set on exceptions ([db4515e](https://github.com/PatrickSpies/nestjs-otel/commit/db4515e6d72ef892ffcf6f2afe3021f27756e2a9))
* **tracing:** use startActiveSpan to ensure span in correct context ([65c0b7a](https://github.com/PatrickSpies/nestjs-otel/commit/65c0b7a35787ab36d43d0f7959254dcfdc631498))
* **tracing:** use startActiveSpan to ensure span in correct context ([d608b84](https://github.com/PatrickSpies/nestjs-otel/commit/d608b84e582b41105c6871ee2e7174f7a0116d96))
* update packages and remove outdated examples ([7150dcf](https://github.com/PatrickSpies/nestjs-otel/commit/7150dcface6c500bbd4c7a8ee5778843d5afa9ba))
* update readme and trigger vulnerabilities fixes ([a85c429](https://github.com/PatrickSpies/nestjs-otel/commit/a85c429552d7b25aa70961c454c7c9ee86302ba4))
* update readme and trigger vulnerabilities fixes ([6a698b1](https://github.com/PatrickSpies/nestjs-otel/commit/6a698b117630dd98d60e31b1a88082e4bd346371))
* update release please permissions ([8db8736](https://github.com/PatrickSpies/nestjs-otel/commit/8db873692c5dc31f994f7d51f34bfae4fff990da))
* updates package-lock.json with default node 14 np version ([3301753](https://github.com/PatrickSpies/nestjs-otel/commit/330175321fc58e1ce269061101a537a3f0cc45bf))


### Reverts

* replace arrow function back with unnamed function ([383cae6](https://github.com/PatrickSpies/nestjs-otel/commit/383cae6844228e620072f7e79bbe55f37a362389))
* replace arrow function back with unnamed function ([3e7ac1f](https://github.com/PatrickSpies/nestjs-otel/commit/3e7ac1f160e1454f7c36470aafd7e8bfa7ee47b5))

## [8.1.0](https://github.com/pragmaticivan/nestjs-otel/compare/v8.0.3...v8.1.0) (2026-06-18)


### Features

* add wide events support for tracing ([c907a6d](https://github.com/pragmaticivan/nestjs-otel/commit/c907a6d3fdb132fb368b718fccc6d4eeb27d3797))
* add wide events support for tracing ([378f884](https://github.com/pragmaticivan/nestjs-otel/commit/378f88440029c7d6b515b050ecb64d1ca4277c5c))
* **wide-events:** capture error stack and accumulate timer durations ([02e6526](https://github.com/pragmaticivan/nestjs-otel/commit/02e6526a97a7ffcb7074e966ae387b838bba5f6f))
* **wide-events:** target trace root span via span processor ([a9b3778](https://github.com/pragmaticivan/nestjs-otel/commit/a9b377834f2f2e212710564101b07310d33234f0))

## [8.0.3](https://github.com/pragmaticivan/nestjs-otel/compare/v8.0.2...v8.0.3) (2026-05-15)


### Bug Fixes

* dont eagerly trigger on functions that return thennable objects ([811c3be](https://github.com/pragmaticivan/nestjs-otel/commit/811c3be67b1f445edebddf17a934638829610943))
* dont eagerly trigger on functions that return thennable objects ([afee4ff](https://github.com/pragmaticivan/nestjs-otel/commit/afee4ff7df733ca381fe6a2de1910e106330f006))

## [8.0.2](https://github.com/pragmaticivan/nestjs-otel/compare/v8.0.1...v8.0.2) (2026-01-21)


### Bug Fixes

* update readme and trigger vulnerabilities fixes ([a85c429](https://github.com/pragmaticivan/nestjs-otel/commit/a85c429552d7b25aa70961c454c7c9ee86302ba4))
* update readme and trigger vulnerabilities fixes ([6a698b1](https://github.com/pragmaticivan/nestjs-otel/commit/6a698b117630dd98d60e31b1a88082e4bd346371))

## [8.0.1](https://github.com/pragmaticivan/nestjs-otel/compare/v8.0.0...v8.0.1) (2025-12-12)


### Bug Fixes

* properly configure provenance for build & update dev packages ([5b8b5b7](https://github.com/pragmaticivan/nestjs-otel/commit/5b8b5b71815ddaddad64a905ab2b140f08b2432d))
* properly configure provenance for build & update dev packages ([19657ba](https://github.com/pragmaticivan/nestjs-otel/commit/19657ba4f7e827af75ee0bf4f961af42cf009bd4))

## [8.0.0](https://github.com/pragmaticivan/nestjs-otel/compare/v7.0.1...v8.0.0) (2025-12-11)


### ⚠ BREAKING CHANGES

* making metric decorators to comply with otel naming convention standard
* major cleanup, removing temporary middleware features

### Features

* add  current span, traceable and baggage decorators ([0d4039b](https://github.com/pragmaticivan/nestjs-otel/commit/0d4039b63793c1e8617878c60447c310bafbf99e))
* add support for capturing method return values in span decorator ([09c8eea](https://github.com/pragmaticivan/nestjs-otel/commit/09c8eea288fd93ef9a273f86952cb258ee2c59a6))
* major cleanup, removing temporary middleware features ([68deeee](https://github.com/pragmaticivan/nestjs-otel/commit/68deeeef64243067ac7a300edece115cefddfc90))
* making metric decorators to comply with otel naming convention standard ([39f3778](https://github.com/pragmaticivan/nestjs-otel/commit/39f37789462843c3256ddfa840b9b9471fe3524d))

## [7.0.1](https://github.com/pragmaticivan/nestjs-otel/compare/v7.0.0...v7.0.1) (2025-08-05)


### Bug Fixes

* add chatmodes and fix updown decorator bug ([b16d7b8](https://github.com/pragmaticivan/nestjs-otel/commit/b16d7b83da1d872c171a681587a6866b25e6e72e))

## [7.0.0](https://github.com/pragmaticivan/nestjs-otel/compare/v6.2.0...v7.0.0) (2025-06-25)


### ⚠ BREAKING CHANGES

* 

### Features

* add overloads to Span decorator ([665753b](https://github.com/pragmaticivan/nestjs-otel/commit/665753b73b6750e4b06e4a7cd468f2b0455b43ac))
* allow passing options to Span decorator without explicit name ([b73a213](https://github.com/pragmaticivan/nestjs-otel/commit/b73a213b75d6d293dc2c3aeac1b1a8a813dfa4a0))
* **metrics:** added Gauge metric to service and decorators ([a1aced4](https://github.com/pragmaticivan/nestjs-otel/commit/a1aced4d6096e5881b0eec5108dad3605690118e))
* span decorator can use method params ([57f105d](https://github.com/pragmaticivan/nestjs-otel/commit/57f105dba039982057f17129f7847f4f337482cf))
* span decorator has access to function params ([c653dc7](https://github.com/pragmaticivan/nestjs-otel/commit/c653dc7ce4f28d1ca8df9009aa7601f054d39a96))
* support otel 2.x and drop support for nestjs10 ([5eaa042](https://github.com/pragmaticivan/nestjs-otel/commit/5eaa0426a9b348ba0cc631e0cc3c6d1024c89739))


### Bug Fixes

* preserve class name decorated with OtelInstanceCounter ([b44fa37](https://github.com/pragmaticivan/nestjs-otel/commit/b44fa37fe8a30bbebbc443699cec5b7717dae259))
* preserve method and class name decorated with OtelXxxCounter ([4019981](https://github.com/pragmaticivan/nestjs-otel/commit/40199819c5b154a7d270f80d08de6173077aad16))
* preserve method name decorated with OtelMethodCounter ([9164a87](https://github.com/pragmaticivan/nestjs-otel/commit/9164a8799b0d023e5bc7e4022c750a6c88157fdd))
* span decorator preserves original method name ([b8784c5](https://github.com/pragmaticivan/nestjs-otel/commit/b8784c5b102f9e1b88d6a2e7cf6b395245657aed))
* span decorator preserves original method name ([84de475](https://github.com/pragmaticivan/nestjs-otel/commit/84de475e8ac41a61684c31b35d61889fb6206fbe))

## [6.2.0](https://github.com/pragmaticivan/nestjs-otel/compare/v6.1.2...v6.2.0) (2025-03-02)


### Features

* **middleware:** backward compatibility for nestjs v10 and proper support for v11 middleware ([f22d1e5](https://github.com/pragmaticivan/nestjs-otel/commit/f22d1e5b03271c8f5d34831054eb1a6bdcd93682))

## [6.1.2](https://github.com/pragmaticivan/nestjs-otel/compare/v6.1.1...v6.1.2) (2025-01-17)


### Bug Fixes

* support nestjs 11 ([229ca4f](https://github.com/pragmaticivan/nestjs-otel/commit/229ca4fd9ebf2af897588ac48c5cb4f569e85455))

### [6.1.1](https://www.github.com/pragmaticivan/nestjs-otel/compare/v6.1.0...v6.1.1) (2024-05-26)


### Bug Fixes

* removed MeterProvider.addMetricReader deprecation ([17d348d](https://www.github.com/pragmaticivan/nestjs-otel/commit/17d348d530f1803500771dfd0b6f1f87f0001c76))
* rework param decorators to get correct type ([3ba9fe9](https://www.github.com/pragmaticivan/nestjs-otel/commit/3ba9fe91f5615e95fe32b517c99ebaa865348461))

## [6.1.0](https://www.github.com/pragmaticivan/nestjs-otel/compare/v6.0.0...v6.1.0) (2024-05-09)


### Features

* metric prefixes ([7b6928a](https://www.github.com/pragmaticivan/nestjs-otel/commit/7b6928ab7ff4146fdb95a928b5babcb1d0490de8))

## [6.0.0](https://www.github.com/pragmaticivan/nestjs-otel/compare/v5.1.5...v6.0.0) (2024-05-08)


### ⚠ BREAKING CHANGES

* Too many changes since I last commited to this project.

### Features

* bumps major version ([fc9aacb](https://www.github.com/pragmaticivan/nestjs-otel/commit/fc9aacb39a8f3340ec4b4a22ad6c5eb61c9dc71e))


### Bug Fixes

* `Span` being incompatible with `MethodDecorator` type ([75dbf0e](https://www.github.com/pragmaticivan/nestjs-otel/commit/75dbf0ece685f5b9d466769368985618828a40a5))

### [5.1.5](https://www.github.com/pragmaticivan/nestjs-otel/compare/v5.1.4...v5.1.5) (2023-09-04)


### Bug Fixes

* latency buckets are not matching the expected time unit in milliseconds ([c269bac](https://www.github.com/pragmaticivan/nestjs-otel/commit/c269bac0826360e30bde656c9a9f0826a588c813))

### [5.1.4](https://www.github.com/pragmaticivan/nestjs-otel/compare/v5.1.3...v5.1.4) (2023-06-28)


### Bug Fixes

* should support both 9 and 10 versions ([50f2273](https://www.github.com/pragmaticivan/nestjs-otel/commit/50f22736d44c5ce690a55b0c605ff4becc97b5a6))

### [5.1.3](https://www.github.com/pragmaticivan/nestjs-otel/compare/v5.1.2...v5.1.3) (2023-06-21)


### Bug Fixes

* [#231](https://www.github.com/pragmaticivan/nestjs-otel/issues/231) Remove unnecessary files from package bundle ([faa521b](https://www.github.com/pragmaticivan/nestjs-otel/commit/faa521b9ce5895a444008f59022dca6009142121))

### [5.1.2](https://www.github.com/pragmaticivan/nestjs-otel/compare/v5.1.1...v5.1.2) (2023-05-05)


### Bug Fixes

* invalid values for error count metrics ([7b13c0b](https://www.github.com/pragmaticivan/nestjs-otel/commit/7b13c0bb557b05d20da5e85bf3cd3b946cbc7f0f))

### [5.1.1](https://www.github.com/pragmaticivan/nestjs-otel/compare/v5.1.0...v5.1.1) (2023-04-21)


### Bug Fixes

* update packages and remove outdated examples ([7150dcf](https://www.github.com/pragmaticivan/nestjs-otel/commit/7150dcface6c500bbd4c7a8ee5778843d5afa9ba))
* update release please permissions ([8db8736](https://www.github.com/pragmaticivan/nestjs-otel/commit/8db873692c5dc31f994f7d51f34bfae4fff990da))

## [5.1.0](https://www.github.com/pragmaticivan/nestjs-otel/compare/v5.0.0...v5.1.0) (2023-04-05)


### Features

* update to stable packages ([76b577c](https://www.github.com/pragmaticivan/nestjs-otel/commit/76b577c754728c19fb5fad6bae382f53e9a4d004))

## [5.0.0](https://www.github.com/pragmaticivan/nestjs-otel/compare/v4.0.1...v5.0.0) (2022-11-27)


### ⚠ BREAKING CHANGES

* updates to latest metric sdk and drop node-sdk dependency

### Features

* update packages ([163ba38](https://www.github.com/pragmaticivan/nestjs-otel/commit/163ba38a1d231aee66b2c2f53356f2d1fd37d3ee))
* update packages ([d0f92fb](https://www.github.com/pragmaticivan/nestjs-otel/commit/d0f92fb64e56005537e7a4b06357685fe290baf9))
* update packages ([28fdc69](https://www.github.com/pragmaticivan/nestjs-otel/commit/28fdc6944901376dcd93037982b52f255799d207))
* updates to latest metric sdk and drop node-sdk dependency ([46c2df3](https://www.github.com/pragmaticivan/nestjs-otel/commit/46c2df35a99810931f13a689c6e80b6135f4958c))


### Bug Fixes

* getSpan returning undefined, enable strict null checks ([#361](https://www.github.com/pragmaticivan/nestjs-otel/issues/361)) ([b7f7cbd](https://www.github.com/pragmaticivan/nestjs-otel/commit/b7f7cbd2fb04d897cc702f02cfac24288fda27f1))

### [4.0.1](https://www.github.com/pragmaticivan/nestjs-otel/compare/v4.0.0...v4.0.1) (2022-08-29)


### Bug Fixes

* bump nestjs requirement to 9.x ([24cde7c](https://www.github.com/pragmaticivan/nestjs-otel/commit/24cde7c7da4243288d1b42b6aeddb109b7353aa2))

## [4.0.0](https://www.github.com/pragmaticivan/nestjs-otel/compare/v3.0.4...v4.0.0) (2022-08-29)


### ⚠ BREAKING CHANGES

* support latest metric sdk

### Features

* **build:** update dependencies ([c2f8b7b](https://www.github.com/pragmaticivan/nestjs-otel/commit/c2f8b7b9fbe116953521fb6b5d7f4648d09d7712))
* support latest metric sdk ([e8d2e96](https://www.github.com/pragmaticivan/nestjs-otel/commit/e8d2e96da5161cd5c4ee78290244144f5849ec8b))
* **tracing:** pass options with span decorator ([3424b88](https://www.github.com/pragmaticivan/nestjs-otel/commit/3424b884e949792679dac79f7b3624cc6e67b110))
* update remaining counters ([d11f6d9](https://www.github.com/pragmaticivan/nestjs-otel/commit/d11f6d98cf25639c01e24c9007a43d3e06c32738))


### Bug Fixes

* forRootAsync uses the wrong module and empty options breaks the configure method ([c2dc102](https://www.github.com/pragmaticivan/nestjs-otel/commit/c2dc102d41f2ddc1ca3e8a814e7243fc4cc4b773))

### [3.0.4](https://www.github.com/pragmaticivan/nestjs-otel/compare/v3.0.3...v3.0.4) (2022-03-29)


### Bug Fixes

* **metrics:** make sure metadata is kept ([de7ca0f](https://www.github.com/pragmaticivan/nestjs-otel/commit/de7ca0f387dbe44142c58c827ccd777348ae491b))
* **tracing:** make sure metadata is kept ([c34ae56](https://www.github.com/pragmaticivan/nestjs-otel/commit/c34ae561e73daea879f6871f2f781a565d03a95a))

### [3.0.3](https://www.github.com/pragmaticivan/nestjs-otel/compare/v3.0.2...v3.0.3) (2022-03-25)


### Bug Fixes

* **tracing:** record exception and set correct span status ([616c12b](https://www.github.com/pragmaticivan/nestjs-otel/commit/616c12b157f7736e9fd45cd38bf9a4c21c11e140))

### [3.0.2](https://www.github.com/pragmaticivan/nestjs-otel/compare/v3.0.1...v3.0.2) (2022-03-24)


### Bug Fixes

* **tracing:** use startActiveSpan to ensure span in correct context ([d608b84](https://www.github.com/pragmaticivan/nestjs-otel/commit/d608b84e582b41105c6871ee2e7174f7a0116d96))

### [3.0.1](https://www.github.com/pragmaticivan/nestjs-otel/compare/v3.0.0...v3.0.1) (2022-01-03)


### Bug Fixes

* **#171:** fixes missing observation callback for observable metrics ([7d89c1f](https://www.github.com/pragmaticivan/nestjs-otel/commit/7d89c1f910b28d0661da6f2989ddea4b9bdcc643)), closes [#171](https://www.github.com/pragmaticivan/nestjs-otel/issues/171)

## [3.0.0](https://www.github.com/pragmaticivan/nestjs-otel/compare/v2.6.1...v3.0.0) (2021-12-30)


### ⚠ BREAKING CHANGES

* Anything related to metrics sdk has changed. OTEL now has a stable spec and all the projects are moving towards new interfaces.

### Features

* ename value recorder on decorators and update readme ([646e2ea](https://www.github.com/pragmaticivan/nestjs-otel/commit/646e2eacd07127f9658b302c09d3056b3b2e1771))
* support all metric types from otel spec ([36a7c5f](https://www.github.com/pragmaticivan/nestjs-otel/commit/36a7c5f2f895157b3e675a7a6ff6693fea6cc8f2))
* update metric spec to the latest otel lib ([6ed63ae](https://www.github.com/pragmaticivan/nestjs-otel/commit/6ed63aefbc1e39da9659d6e232a4883f7ed93dac))
* update packages to compply with latest otel metric spec ([943ca06](https://www.github.com/pragmaticivan/nestjs-otel/commit/943ca06ea62e95d8a07af63030609f226b78c4b8))

### [2.6.1](https://www.github.com/pragmaticivan/nestjs-otel/compare/v2.6.0...v2.6.1) (2021-10-13)


### Reverts

* replace arrow function back with unnamed function ([3e7ac1f](https://www.github.com/pragmaticivan/nestjs-otel/commit/3e7ac1f160e1454f7c36470aafd7e8bfa7ee47b5))

## [2.6.0](https://www.github.com/pragmaticivan/nestjs-otel/compare/v2.5.2...v2.6.0) (2021-10-12)


### Features

* **metrics:** option for ignoring undefined routes ([15577e8](https://www.github.com/pragmaticivan/nestjs-otel/commit/15577e83c7b3ea7642dc7eba65517361edfe3a54))
* **metrics:** option to ignore specific routes ([b8a05f1](https://www.github.com/pragmaticivan/nestjs-otel/commit/b8a05f1ef46b9e077f8c4edbad59f91b00d3a49e))


### Bug Fixes

* eslint setup ([14d9870](https://www.github.com/pragmaticivan/nestjs-otel/commit/14d9870d9aacee325a7338dd764ccfef404b7ad5))
* linting ([1961f18](https://www.github.com/pragmaticivan/nestjs-otel/commit/1961f18ae1203a4e721e72caeb9f425f1937d918))
* **linting:** replace unnamed function with arrow function ([12fa02c](https://www.github.com/pragmaticivan/nestjs-otel/commit/12fa02c081ef85ddde7208c7b865efcaa05bab6f))
* **metrics:** add missing commas in example config in README.md ([7b159c6](https://www.github.com/pragmaticivan/nestjs-otel/commit/7b159c603bc9655b270f9447414cdab473b31526))

### [2.5.2](https://www.github.com/pragmaticivan/nestjs-otel/compare/v2.5.1...v2.5.2) (2021-10-07)


### Bug Fixes

* enable nestjs 7.x as peer dependency ([e6c6a1e](https://www.github.com/pragmaticivan/nestjs-otel/commit/e6c6a1e9dd2ae0f906dea2775faaf7a51daeb755))

### [2.5.1](https://www.github.com/pragmaticivan/nestjs-otel/compare/v2.5.0...v2.5.1) (2021-10-06)


### Bug Fixes

* metrics for fastify platform ([4b61e70](https://www.github.com/pragmaticivan/nestjs-otel/commit/4b61e7079d5470088b92d459e7923e4460dd606c))

## [2.5.0](https://www.github.com/pragmaticivan/nestjs-otel/compare/v2.4.0...v2.5.0) (2021-09-26)


### Features

* add defaultLabels support ([6efb0a5](https://www.github.com/pragmaticivan/nestjs-otel/commit/6efb0a540546bd78d0ea582e949beb3c77be3288))

## [2.4.0](https://www.github.com/pragmaticivan/nestjs-otel/compare/v2.3.0...v2.4.0) (2021-08-24)


### Features

* add http size and server abort metrics ([ba64308](https://www.github.com/pragmaticivan/nestjs-otel/commit/ba64308e7c986cddceed06f2248476c66747f4c6))

## [2.3.0](https://www.github.com/pragmaticivan/nestjs-otel/compare/v2.2.0...v2.3.0) (2021-08-13)


### Features

* update peer dependency to allow support for both v7 and v8 of NestJs ([647eb89](https://www.github.com/pragmaticivan/nestjs-otel/commit/647eb8906675414a05d14640c2374be1e8837f0e))


### Bug Fixes

* error nodeMetrics is not a function ([cf7d0fc](https://www.github.com/pragmaticivan/nestjs-otel/commit/cf7d0fc2e0d728470b5b259932bfad4be8f6aa3c))
* removed .npmrc file, as it only had default values ([c27a8af](https://www.github.com/pragmaticivan/nestjs-otel/commit/c27a8af8d757ec67113158a3ee466adca32c9b04))
* updates package-lock.json with default node 14 np version ([3301753](https://www.github.com/pragmaticivan/nestjs-otel/commit/330175321fc58e1ce269061101a537a3f0cc45bf))

## [2.2.0](https://www.github.com/pragmaticivan/nestjs-otel/compare/v2.1.0...v2.2.0) (2021-08-02)


### Features

* update dependencies to latest ([385e3db](https://www.github.com/pragmaticivan/nestjs-otel/commit/385e3db485633257a498e25005086bf5b60331ac))

## [2.1.0](https://www.github.com/pragmaticivan/nestjs-otel/compare/v2.0.0...v2.1.0) (2021-07-28)


### Features

* add metric decorators ([9263bd0](https://www.github.com/pragmaticivan/nestjs-otel/commit/9263bd0844e203920375ca04a4876fe60e8ea2a7))

## [2.0.0](https://www.github.com/pragmaticivan/nestjs-otel/compare/v1.8.2...v2.0.0) (2021-07-28)


### ⚠ BREAKING CHANGES

* removes nodeSDKConfiguration option

### Features

* node-sdk to be defined by the user instead of through the lib ([5156324](https://www.github.com/pragmaticivan/nestjs-otel/commit/5156324b64cee8fccd2d06eaf5d155e22a5c0fbf))

### [1.8.2](https://www.github.com/pragmaticivan/nestjs-otel/compare/v1.8.1...v1.8.2) (2021-07-25)


### Bug Fixes

* **metric:** fixes metric service not properly reusing existing metrics ([9f24fd8](https://www.github.com/pragmaticivan/nestjs-otel/commit/9f24fd8a76e6ee0060468de1326265c1fb7b4824))

### [1.8.1](https://www.github.com/pragmaticivan/nestjs-otel/compare/v1.8.0...v1.8.1) (2021-07-25)


### Bug Fixes

* **middleware:** fixes api middleware when no requesting invalid route ([2a008d9](https://www.github.com/pragmaticivan/nestjs-otel/commit/2a008d9ab605a1660c0e5015bd7d635813e3fc57))

## [1.8.0](https://www.github.com/pragmaticivan/nestjs-otel/compare/v1.7.0...v1.8.0) (2021-07-24)


### Features

* update api metrics to use route match path instead of full route ([ad51bac](https://www.github.com/pragmaticivan/nestjs-otel/commit/ad51bac1b0121257434cc4543853227669f15aca)), closes [#48](https://www.github.com/pragmaticivan/nestjs-otel/issues/48)


### Bug Fixes

* fixes forRootAsync usage ([a390f0e](https://www.github.com/pragmaticivan/nestjs-otel/commit/a390f0e564227b5e9019d1b8da19e4966e3d7ddf))

## [1.7.0](https://www.github.com/pragmaticivan/nestjs-otel/compare/v1.6.0...v1.7.0) (2021-07-14)


### Features

* remove unused constant and reorganize pkgs ([d37fc28](https://www.github.com/pragmaticivan/nestjs-otel/commit/d37fc28c7bc3944399cda157a6ee87a5b83919e3))

## [1.6.0](https://www.github.com/pragmaticivan/nestjs-otel/compare/v1.5.0...v1.6.0) (2021-06-30)


### Features

* changes license to Apache2 ([5129fdb](https://www.github.com/pragmaticivan/nestjs-otel/commit/5129fdba49a834437faddda20044afd3d91ea7a7))

## [1.5.0](https://www.github.com/pragmaticivan/nestjs-otel/compare/v1.4.0...v1.5.0) (2021-06-30)


### Features

* support forRootAsync ([8cb00a4](https://www.github.com/pragmaticivan/nestjs-otel/commit/8cb00a455e65e1de9b893291720c037b29a847aa))

## [1.4.0](https://www.github.com/pragmaticivan/nestjs-otel/compare/v1.3.0...v1.4.0) (2021-06-29)


### Features

* removes prometheus Interface and use metrics instead ([f3fd29e](https://www.github.com/pragmaticivan/nestjs-otel/commit/f3fd29eab94cb6ab4302d7990d25a3bcc3250f56))
* sets meter provider globally on sdk ([4be57ef](https://www.github.com/pragmaticivan/nestjs-otel/commit/4be57ef02eeff516ef5b7ceb88731e2de570f553))

## [1.3.0](https://www.github.com/pragmaticivan/nestjs-otel/compare/v1.2.3...v1.3.0) (2021-06-28)


### Features

* improves api metrics middleware ([df50305](https://www.github.com/pragmaticivan/nestjs-otel/commit/df503056087f1c128fe4999fbb77f8b45a6a1a74))

### [1.2.3](https://www.github.com/pragmaticivan/nestjs-otel/compare/v1.2.2...v1.2.3) (2021-06-27)


### Bug Fixes

* properly ignore /metrics path on middleware ([45973a4](https://www.github.com/pragmaticivan/nestjs-otel/commit/45973a4abd8270acc789aeecfe93a8b05f98b30a))

### [1.2.2](https://www.github.com/pragmaticivan/nestjs-otel/compare/v1.2.1...v1.2.2) (2021-06-27)


### Bug Fixes

* resolve problems with conditional dependency and default configs and add jest config ([1f1fb12](https://www.github.com/pragmaticivan/nestjs-otel/commit/1f1fb12dcc2df42f2f3082031f31248c246128c1))

### [1.2.1](https://www.github.com/pragmaticivan/nestjs-otel/compare/v1.2.0...v1.2.1) (2021-06-25)


### Bug Fixes

* exports MetricService on core module ([e8096a6](https://www.github.com/pragmaticivan/nestjs-otel/commit/e8096a65a262a1213e3f7117b74f657b812fbed0))

## [1.2.0](https://www.github.com/pragmaticivan/nestjs-otel/compare/v1.1.0...v1.2.0) (2021-06-25)


### Features

* export MetricService ([6ed93ae](https://www.github.com/pragmaticivan/nestjs-otel/commit/6ed93ae526dec7ed1c7f4eacb043c2df7168fc70))

## [1.1.0](https://www.github.com/pragmaticivan/nestjs-otel/compare/v1.0.0...v1.1.0) (2021-06-25)


### Features

* use lts npm match for 14.x ([9088eac](https://www.github.com/pragmaticivan/nestjs-otel/commit/9088eac2308e8d3320353ff5da7587fb45ae7657))


### Bug Fixes

* removes latest npm requirement ([9dd42f8](https://www.github.com/pragmaticivan/nestjs-otel/commit/9dd42f85e8fc309967f66e8619de265fa0e9bfdb))

## 1.0.0 (2021-06-25)


### Features

* first commit ([0c07ff5](https://www.github.com/pragmaticivan/nestjs-otel/commit/0c07ff52bd4df8b04f8951c67cb88f96f5f31957))
