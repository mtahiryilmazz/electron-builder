# [](https://github.com/electron-userland/electron-builder/compare/v20.43.0...v) (2022-09-23)


### Bug Fixes

* ([#5685](https://github.com/electron-userland/electron-builder/issues/5685)) check if icons subdir exists in build resources, otherwise don't prepend it to fallback sources ([#5686](https://github.com/electron-userland/electron-builder/issues/5686)) ([8df250b](https://github.com/electron-userland/electron-builder/commit/8df250b4645924942883ba6ad1418da994116521))
* (mac) Fix intel mac upgrade flow when both x64 and arm64 published ([#6212](https://github.com/electron-userland/electron-builder/issues/6212)) ([0c21cd6](https://github.com/electron-userland/electron-builder/commit/0c21cd69663a7eebe0687eaba9eea851cc2fea9e))
* ${arch} causes a build fail ([#5905](https://github.com/electron-userland/electron-builder/issues/5905)) ([014cbf5](https://github.com/electron-userland/electron-builder/commit/014cbf5f98a25d6537f9f2b49e90cc401a2f3bce)), closes [#5857](https://github.com/electron-userland/electron-builder/issues/5857)
* Add "arm" as an alias for armv7l as process.arch outputs arm on armv7l hosts ([#6845](https://github.com/electron-userland/electron-builder/issues/6845)) ([d3452b0](https://github.com/electron-userland/electron-builder/commit/d3452b0427cb45035f6ed7f1266691db4accd5c4))
* add `recursive: true` to `fs.rm` wnen removing locales ([#5961](https://github.com/electron-userland/electron-builder/issues/5961)) ([c9b78f9](https://github.com/electron-userland/electron-builder/commit/c9b78f958daf778747843dd2d671628f9cbb8ef6))
* add appCannotBeClosed text for zh_CN ([#6287](https://github.com/electron-userland/electron-builder/issues/6287)) ([10b4727](https://github.com/electron-userland/electron-builder/commit/10b47273c32c32df17dfb910feb4a7704c83da91))
* add missing %U in desktop file of appimages ([#4909](https://github.com/electron-userland/electron-builder/issues/4909)) ([d96b3d3](https://github.com/electron-userland/electron-builder/commit/d96b3d39c4caf959cc929f562f70e4de3983420b)), closes [#4035](https://github.com/electron-userland/electron-builder/issues/4035)
* add product scope to keygen provider ([#6975](https://github.com/electron-userland/electron-builder/issues/6975)) ([8279d05](https://github.com/electron-userland/electron-builder/commit/8279d053d520e7506d84bf9710972b998e70b752))
* add product scope to keygen publisher ([#6990](https://github.com/electron-userland/electron-builder/issues/6990)) ([c3407a2](https://github.com/electron-userland/electron-builder/commit/c3407a202d4dc1599b2cb90a7ff3d56e8e32309e))
* Add support for nested file extensions (such as `.dmg.blockmap`) to Keygen publisher ([#6234](https://github.com/electron-userland/electron-builder/issues/6234)) ([369f1fa](https://github.com/electron-userland/electron-builder/commit/369f1fa793c28d8743e19ef07ce6eb091c191fb0)), closes [#6229](https://github.com/electron-userland/electron-builder/issues/6229)
* add warning to macCodeSign when skipping code signing on M1 macOS device ([#6522](https://github.com/electron-userland/electron-builder/issues/6522)) ([8730027](https://github.com/electron-userland/electron-builder/commit/87300278d24e8304caa4b053b883843a2447dab2))
* Added Changelog and Readme writing  to excluded files ([39f6b84](https://github.com/electron-userland/electron-builder/commit/39f6b84a62c8f5ab21b991ebd786aa8427d6e354))
* Added missing `event-update-not-available` in UpdaterEvents ([#5923](https://github.com/electron-userland/electron-builder/issues/5923)) ([dc359de](https://github.com/electron-userland/electron-builder/commit/dc359de5019807a014c62468385dfb14bbb5bd83))
* Added support for overriding ‘strict-verify’ electron-osx-sign property. ([#5261](https://github.com/electron-userland/electron-builder/issues/5261)) ([c554f25](https://github.com/electron-userland/electron-builder/commit/c554f25d7533f23e57c3f4fe11fa0ca54f7cfc29)), closes [#1480](https://github.com/electron-userland/electron-builder/issues/1480)
* Adding libxtst6 to base dockerfile image. Fixes: [#5907](https://github.com/electron-userland/electron-builder/issues/5907) ([#5913](https://github.com/electron-userland/electron-builder/issues/5913)) ([096e109](https://github.com/electron-userland/electron-builder/commit/096e10939c506c41e9cc9d5d69534aaad6e76fd2))
* Adding snapStore to AllPublishOptions for generating Configuration schema ([#6193](https://github.com/electron-userland/electron-builder/issues/6193)) ([7f933d0](https://github.com/electron-userland/electron-builder/commit/7f933d0004a0a5f808a2a1c71dca7362cab2728e))
* allow $schema property in electron-builder.json ([#3963](https://github.com/electron-userland/electron-builder/issues/3963)) ([1d9d5ed](https://github.com/electron-userland/electron-builder/commit/1d9d5ed9e470432c6bab6a4d66490a5134ca2464)), closes [#3962](https://github.com/electron-userland/electron-builder/issues/3962)
* allow CSC_LINK to have a mime-type prefix before extracting it to a p12 ([#7119](https://github.com/electron-userland/electron-builder/issues/7119)) ([323618f](https://github.com/electron-userland/electron-builder/commit/323618f79108a8bb829dc1e84e933ace90940010))
* Allow disabling of webinstaller files to avoid confusion with actual installers ([#6575](https://github.com/electron-userland/electron-builder/issues/6575)) ([5e381c5](https://github.com/electron-userland/electron-builder/commit/5e381c556d12ce185bb7ea720380509c1ddc5cf7))
* allow user to define explicit `buildNumber` in config, useful for fpm `--iteration` flag ([#7075](https://github.com/electron-userland/electron-builder/issues/7075)) ([8166267](https://github.com/electron-userland/electron-builder/commit/8166267d487cd26b154e28cf60d89102a487a353))
* allowing + symbols for expanding macros. necessary for '+nightly' builds ([#5990](https://github.com/electron-userland/electron-builder/issues/5990)) ([8e6f008](https://github.com/electron-userland/electron-builder/commit/8e6f008d2f93e06aebb00402500e02a37edb0bd0))
* any "node_module/____" glob pattern selects far too many node dependencies ([#6080](https://github.com/electron-userland/electron-builder/issues/6080)) ([72ffc25](https://github.com/electron-userland/electron-builder/commit/72ffc25063fc6d8f67e941ed7fc3b5991efb5448)), closes [#6045](https://github.com/electron-userland/electron-builder/issues/6045)
* **app-builder-lib:** Allow using lowercase value for certificateSha1 ([#4684](https://github.com/electron-userland/electron-builder/issues/4684)) ([5390bb6](https://github.com/electron-userland/electron-builder/commit/5390bb6a3b16ceab3dd4456f717fd8e978f4217c)), closes [#4631](https://github.com/electron-userland/electron-builder/issues/4631)
* **app-builder-lib:** bump @electron/universal to 1.2.1 ([#6750](https://github.com/electron-userland/electron-builder/issues/6750)) ([370f84b](https://github.com/electron-userland/electron-builder/commit/370f84bb2f32f28c374b63e1c795e4850f971274))
* **app-builder-lib:** change slash to backslash in NSIS's APP_PACKAGE_NAME ([#6772](https://github.com/electron-userland/electron-builder/issues/6772)) ([e861352](https://github.com/electron-userland/electron-builder/commit/e86135236908961b1269708ca645a66c7ff19287))
* **app-builder-lib:** channel alternation for github is not working ([#6449](https://github.com/electron-userland/electron-builder/issues/6449)) ([df7a425](https://github.com/electron-userland/electron-builder/commit/df7a4255d219aea7a1236fd5693f7c13460099ad))
* **app-builder-lib:** export missing TS types ([#6692](https://github.com/electron-userland/electron-builder/issues/6692)) ([93181a7](https://github.com/electron-userland/electron-builder/commit/93181a78f2893ea4929aea8878343336931b3a04))
* **app-builder-lib:** macOS packager uses static icon name ([#6308](https://github.com/electron-userland/electron-builder/issues/6308)) ([fce1a1f](https://github.com/electron-userland/electron-builder/commit/fce1a1fab66e3f5cd741a4cecc4af8377aea9dd8))
* **app-builder-lib:** Overriding OutgoingHttpHeaders schema props ([#6775](https://github.com/electron-userland/electron-builder/issues/6775)) ([e9a87a7](https://github.com/electron-userland/electron-builder/commit/e9a87a738ceb2b9e14cbc85b4c62e11edab3d0cf)), closes [#6635](https://github.com/electron-userland/electron-builder/issues/6635)
* **app-builder-lib:** signing certificate selection by sha1 ([#4499](https://github.com/electron-userland/electron-builder/issues/4499)) ([1f2865b](https://github.com/electron-userland/electron-builder/commit/1f2865b1f317ab4671b76f490584749518120176))
* **app-builder-lib:** use DigiCert timestamp server as default ([#3965](https://github.com/electron-userland/electron-builder/issues/3965)) ([09a6cdd](https://github.com/electron-userland/electron-builder/commit/09a6cddb515d5114514ea29adb66e44b7471292d))
* **app-builder-lib:** yarn install break on 'electron-builder install-app-deps' when used pnp ([#4147](https://github.com/electron-userland/electron-builder/issues/4147)) ([0fe8f12](https://github.com/electron-userland/electron-builder/commit/0fe8f1279112fa8bcb1e795e2fcd3594accc0b1f))
* **AppImage:** Add default argument --no-sandbox ([#4496](https://github.com/electron-userland/electron-builder/issues/4496)) ([ede6d50](https://github.com/electron-userland/electron-builder/commit/ede6d50ddb6c23fe6bbb056bd80509c8f2ea0116))
* **appx:** App sandbox not enabled (ITMS-90296) ([#4244](https://github.com/electron-userland/electron-builder/issues/4244)) ([e48681e](https://github.com/electron-userland/electron-builder/commit/e48681eeee6a48cf68deb6a0a0f1c5c13507d870))
* **appx:** Default rfc3161TimeStampServer to http://timestamp.digicert.com ([#5147](https://github.com/electron-userland/electron-builder/issues/5147)) ([34d1752](https://github.com/electron-userland/electron-builder/commit/34d17524e257721df07018943bc50b9a4a24e7e6))
* **appx:** Invalid code signing tool path when building for windows 10 arm64 ([#4879](https://github.com/electron-userland/electron-builder/issues/4879)) ([d898c4e](https://github.com/electron-userland/electron-builder/commit/d898c4e99ad2b917d7aafe6bcba2d2404e872e03))
* **arm64:** fix pacman build, pacman & rpm artifact names ([#5304](https://github.com/electron-userland/electron-builder/issues/5304)) ([069eba1](https://github.com/electron-userland/electron-builder/commit/069eba17fdbe5f33a78117f79b5f9f5e90a941b6))
* **auto-updater:** Log the raw version string ([#4947](https://github.com/electron-userland/electron-builder/issues/4947)) ([8f99057](https://github.com/electron-userland/electron-builder/commit/8f990576f58e50351cb3abdfdb577690d02145f8))
* automatically regenerate schema if any config option changes in app-builder-lib ([51f5d49](https://github.com/electron-userland/electron-builder/commit/51f5d4915c4aa69f3253a41e1d7b4ab9f2328732))
* binary detection signing ([#5493](https://github.com/electron-userland/electron-builder/issues/5493)) ([a6e86b5](https://github.com/electron-userland/electron-builder/commit/a6e86b593048b4eb3047b7c3a54d02d0521b02d2)), closes [#5465](https://github.com/electron-userland/electron-builder/issues/5465)
* build fails with istextorbinary error stacktrace ([#5668](https://github.com/electron-userland/electron-builder/issues/5668)) ([#5851](https://github.com/electron-userland/electron-builder/issues/5851)) ([1011919](https://github.com/electron-userland/electron-builder/commit/10119197292c74234e76bdfba011ae2d7579dc85))
* **builder-util-runtime:** fix description when request 404 ([#3964](https://github.com/electron-userland/electron-builder/issues/3964)) ([9087f4f](https://github.com/electron-userland/electron-builder/commit/9087f4ff368068ff80ec5f684c4800c9bdda83cd))
* **builder-util:** enable proxy handling in NodeHttpExecutor ([#6410](https://github.com/electron-userland/electron-builder/issues/6410)) ([#6286](https://github.com/electron-userland/electron-builder/issues/6286)) ([#5906](https://github.com/electron-userland/electron-builder/issues/5906)) ([04a8435](https://github.com/electron-userland/electron-builder/commit/04a84352b2b3fbb3c54533a8428bfd103df0af21))
* **builder-util:** Retry flaky builder operations ([b03f2c1](https://github.com/electron-userland/electron-builder/commit/b03f2c1bf32b87f5b37829ef9c774acae96c232e)), closes [#4657](https://github.com/electron-userland/electron-builder/issues/4657)
* building native modules does not fall back to building from source if prebuilt not found ([cd28eb0](https://github.com/electron-userland/electron-builder/commit/cd28eb093f0bf5969ad87c64773cc0714dc8d8ea)), closes [#4016](https://github.com/electron-userland/electron-builder/issues/4016)
* cached update validation failing on undefined filename ([#4929](https://github.com/electron-userland/electron-builder/issues/4929)) ([4a9e5ef](https://github.com/electron-userland/electron-builder/commit/4a9e5efedf380053c2dd2abea74d1031348ffd11)), closes [#4928](https://github.com/electron-userland/electron-builder/issues/4928)
* Change DEBUG_LOGGING env var for nsis installers as part of `customNsisBinary` config ([#6729](https://github.com/electron-userland/electron-builder/issues/6729)) ([0a30846](https://github.com/electron-userland/electron-builder/commit/0a308469f269dc5294f29f2c422d9936175c0880)), closes [#6715](https://github.com/electron-userland/electron-builder/issues/6715)
* CI unit tests ([#5489](https://github.com/electron-userland/electron-builder/issues/5489)) ([637334d](https://github.com/electron-userland/electron-builder/commit/637334ddbadebf503a45f79adf0b481fcba98679))
* ci-tests ([#5523](https://github.com/electron-userland/electron-builder/issues/5523)) ([ced6e50](https://github.com/electron-userland/electron-builder/commit/ced6e50b93c621de5de07838205d739010e2526b))
* close file stream when error in httpExecutor ([#7094](https://github.com/electron-userland/electron-builder/issues/7094)) ([1023a93](https://github.com/electron-userland/electron-builder/commit/1023a93e92eaa26bf33b52edda5b22e56ed1ec18))
* codesign all binary-like files ([#5322](https://github.com/electron-userland/electron-builder/issues/5322)) ([27ea1b2](https://github.com/electron-userland/electron-builder/commit/27ea1b2b9ce47a234e82772e09adf0bc7931e0df))
* compiler error and test updates ([#5449](https://github.com/electron-userland/electron-builder/issues/5449)) ([0dec1b8](https://github.com/electron-userland/electron-builder/commit/0dec1b8c198f1f9ca0124649883945ba561d11d3))
* config on command must coerce string ([faba9e3](https://github.com/electron-userland/electron-builder/commit/faba9e365a0a4d2402d91ca9bd5a5288cb78f0f7)), closes [#4086](https://github.com/electron-userland/electron-builder/issues/4086)
* console log data for electron-updater blockmaps are far too large ([#6143](https://github.com/electron-userland/electron-builder/issues/6143)) ([ae363e5](https://github.com/electron-userland/electron-builder/commit/ae363e51957d0abfc7d848f51aa23c7e5faf5f33))
* **deb:** Build on an armv7l architecture ends up with "Cannot set machine from deb_arch 'armv7l' ([095a05d](https://github.com/electron-userland/electron-builder/commit/095a05d13eef4bfba15f666a5358b1aa88e8ee10)), closes [#3349](https://github.com/electron-userland/electron-builder/issues/3349)
* **deb:** chmod SUID bit on chrome-sandbox for debs ([#4163](https://github.com/electron-userland/electron-builder/issues/4163)) ([7c2881e](https://github.com/electron-userland/electron-builder/commit/7c2881e52930082136f6e4b7950c3611e0e07100))
* **deb:** deb fails to install on the new Debian Buster ([3bf2091](https://github.com/electron-userland/electron-builder/commit/3bf20914bf946df0e46729ef0bf586d9f3f6a423)), closes [#4033](https://github.com/electron-userland/electron-builder/issues/4033)
* **deb:** do not use quotes for safe Exec ([d7aa12d](https://github.com/electron-userland/electron-builder/commit/d7aa12dec88aa60eb721e96e2a5ce248423c459a)), closes [#2759](https://github.com/electron-userland/electron-builder/issues/2759)
* **debian:** corrected path for binary in package ([#4002](https://github.com/electron-userland/electron-builder/issues/4002)) ([f1e9456](https://github.com/electron-userland/electron-builder/commit/f1e9456bc4acb0707bc397e021796ee74a44c8e8))
* **deploy:** consolidating versioning commands into package.json ([6066681](https://github.com/electron-userland/electron-builder/commit/6066681077c8ba730155751b83b4550add9b0dcf))
* **deploy:** deactivate husky hooks for automatic versioning PR ([#6041](https://github.com/electron-userland/electron-builder/issues/6041)) ([0d4d305](https://github.com/electron-userland/electron-builder/commit/0d4d3056b440cc45a1f1a15ea4a27c688cb0e96e))
* **deploy:** Fixing zulip send message action ([41d5cae](https://github.com/electron-userland/electron-builder/commit/41d5cae325cba3031bc25148b1ff5927bc441913))
* **deploy:** remove zulip release message ([695f89a](https://github.com/electron-userland/electron-builder/commit/695f89a7b18e100c15ac47f837ae10ee600710ac))
* **deploy:** Removing schema generation since it doesn't compile during release ([7e28c11](https://github.com/electron-userland/electron-builder/commit/7e28c11ec894c9ce7664a2ea3bfdb3e96f09d983))
* **deploy:** Update package.json script name ([e22fc16](https://github.com/electron-userland/electron-builder/commit/e22fc16cd196ab0f3cc7b2f9bdaae237e64121a8))
* DigitalOcean Spaces doesn't support multiple range requests ([#4690](https://github.com/electron-userland/electron-builder/issues/4690)) ([f5cc292](https://github.com/electron-userland/electron-builder/commit/f5cc29248096d4bdd2924e5a6d16772aaeb87dd9))
* disable AppImage target by default if build on Windows ([4f05bad](https://github.com/electron-userland/electron-builder/commit/4f05bad648c95befccdd14d9e60179ab1ec71fcb))
* **dmb:** fix injecting dmg license with dmg-license package instead of deprecated Rez tool ([#5424](https://github.com/electron-userland/electron-builder/issues/5424)) ([9e7b3c3](https://github.com/electron-userland/electron-builder/commit/9e7b3c39ad3c59b88d78e3f5a5948cf4ced3f92a))
* DMG assembly on Apple Silicon ([#4606](https://github.com/electron-userland/electron-builder/issues/4606)) ([#5724](https://github.com/electron-userland/electron-builder/issues/5724)) ([469b85f](https://github.com/electron-userland/electron-builder/commit/469b85fa2a2660eaba1eafbbd528abec2b1f50d9))
* **dmg-builder:** exec python fail on Macos12.3 ([#6789](https://github.com/electron-userland/electron-builder/issues/6789)) ([76f3a1d](https://github.com/electron-userland/electron-builder/commit/76f3a1d102be04c0517a08826b8b1337478f766d))
* **dmg-builder:** fix dmg-license is incompatible with linux and win32 ([#5473](https://github.com/electron-userland/electron-builder/issues/5473)) ([2b116d1](https://github.com/electron-userland/electron-builder/commit/2b116d138e9effa3314fe6ff4474b639f7fddf47))
* **dmg-builder:** Support python 3 since python 2 was removed from MacOS 12.3 ([#6617](https://github.com/electron-userland/electron-builder/issues/6617)) ([2def112](https://github.com/electron-userland/electron-builder/commit/2def112bc1ac42046b921206825871b82ebf0955)), closes [#6606](https://github.com/electron-userland/electron-builder/issues/6606)
* **dmg-builder:** the "import" unbound issue for python 2/3 ([#6672](https://github.com/electron-userland/electron-builder/issues/6672)) ([3a4b64a](https://github.com/electron-userland/electron-builder/commit/3a4b64abb58f01e8a80e496b6c4681455b2434ca))
* dmg-license optional dependency ([#6244](https://github.com/electron-userland/electron-builder/issues/6244)) ([8ccb2da](https://github.com/electron-userland/electron-builder/commit/8ccb2da5d4c641b971f6a7403d3b2e3a3b844a05))
* dmg-license-dependency ([#6248](https://github.com/electron-userland/electron-builder/issues/6248)) ([f359035](https://github.com/electron-userland/electron-builder/commit/f3590355c61dab05a6c92c5951aae8e59503d693))
* **dmg:** Adding ‘sign’ dmg option to scheme.json to fix build errors ([#3941](https://github.com/electron-userland/electron-builder/issues/3941)) ([766ecff](https://github.com/electron-userland/electron-builder/commit/766ecff197866355770dc80c1a12caf6600015eb))
* **dmg:** adding 10% on size for temporary dmg used in hdiutil  ([#4171](https://github.com/electron-userland/electron-builder/issues/4171)) ([1d21620](https://github.com/electron-userland/electron-builder/commit/1d2162093f6639165934849a073144832541bfbe)), closes [#3301](https://github.com/electron-userland/electron-builder/issues/3301)
* **dmg:** cannot build DMG on macOS 10.15 ([8f099f5](https://github.com/electron-userland/electron-builder/commit/8f099f53421fde604105208d28edec67d8358c6c)), closes [#3990](https://github.com/electron-userland/electron-builder/issues/3990)
* **dmg:** correctly encode Unicode characters in DMG licenses ([#4428](https://github.com/electron-userland/electron-builder/issues/4428)) ([ba92854](https://github.com/electron-userland/electron-builder/commit/ba92854eaaa5931a569f52bf77269934105fc161))
* **dmg:** Escaping special characters in DMG entries ([#5987](https://github.com/electron-userland/electron-builder/issues/5987)) ([c368f62](https://github.com/electron-userland/electron-builder/commit/c368f62b3aa63962826c38d65d0ad43aad9ec7e1))
* **dmg:** new version of mac_alias ([#5460](https://github.com/electron-userland/electron-builder/issues/5460)) ([a8acb58](https://github.com/electron-userland/electron-builder/commit/a8acb583bc3c6fb1ff0dca2f07d1eefa26b1780a))
* **dmg:** require().split is not a function ([dfcd010](https://github.com/electron-userland/electron-builder/commit/dfcd010c1e3d7593404832fa8c4c53baddaa8a3b)), closes [#4639](https://github.com/electron-userland/electron-builder/issues/4639)
* do not show MessageBox when app was killed (on not running) ([#6043](https://github.com/electron-userland/electron-builder/issues/6043)) ([0561674](https://github.com/electron-userland/electron-builder/commit/0561674b6c491ee1cfa0ba838f5c5d59ce205124))
* **docker:** fix install of wine ([#4622](https://github.com/electron-userland/electron-builder/issues/4622)) ([6f7eb12](https://github.com/electron-userland/electron-builder/commit/6f7eb121c4f478323dbaa32ddfcd1d707e0807f6))
* **docker:** osslsigncode with curl4 ([4e454f8](https://github.com/electron-userland/electron-builder/commit/4e454f8b4390a4bcc38a30f065e0ed1eba2acee9))
* **docker:** upgrade libcurl3 to libcurl4 ([#4479](https://github.com/electron-userland/electron-builder/issues/4479)) ([a215a83](https://github.com/electron-userland/electron-builder/commit/a215a83e7bce553760cb8033f44dcdc31e1b3316)), closes [#4478](https://github.com/electron-userland/electron-builder/issues/4478)
* **docs:** Fixing formatting of code groups and previews ([#6601](https://github.com/electron-userland/electron-builder/issues/6601)) ([b01d522](https://github.com/electron-userland/electron-builder/commit/b01d5225631115f6f301cb113b044fd10ebb5256)), closes [#6597](https://github.com/electron-userland/electron-builder/issues/6597) [#6574](https://github.com/electron-userland/electron-builder/issues/6574)
* **docs:** link to SquirrelWindowsOptions in configuration ([#6724](https://github.com/electron-userland/electron-builder/issues/6724)) ([4eaab19](https://github.com/electron-userland/electron-builder/commit/4eaab1936429ac69dafcc7cfbf53caa85c241a11))
* **docs:** minor grammar/formatting fixes ([#6107](https://github.com/electron-userland/electron-builder/issues/6107)) ([b9b275f](https://github.com/electron-userland/electron-builder/commit/b9b275fff0763faf110a8dcb3c8313963710bbeb))
* **docs:** typo of docs/generated/NsisOptions.md ([#7120](https://github.com/electron-userland/electron-builder/issues/7120)) ([740c411](https://github.com/electron-userland/electron-builder/commit/740c41146f875feaa730d18f8353b11416dab1e0))
* **docs:** Update link for "Desktop File" ([#6532](https://github.com/electron-userland/electron-builder/issues/6532)) ([cd79c53](https://github.com/electron-userland/electron-builder/commit/cd79c53828759cf19cd361a48ef6fd57fff0e2f1))
* Downgrading nsis to v3.0.4.1 since v3.0.4.2 throws false virus positives ([#6334](https://github.com/electron-userland/electron-builder/issues/6334)) ([#6447](https://github.com/electron-userland/electron-builder/issues/6447)) ([d20bcf0](https://github.com/electron-userland/electron-builder/commit/d20bcf0cea4e4cb49aab08f820131a2d6b083a2c))
* Duplicate values during deep assign of extra files ([#7019](https://github.com/electron-userland/electron-builder/issues/7019)) ([98d3a63](https://github.com/electron-userland/electron-builder/commit/98d3a6361d500e85e443ee292529c27f0b4a0b59))
* **electron-publish:** Allow GH integration tokens ([#4225](https://github.com/electron-userland/electron-builder/issues/4225)) ([8e0a57d](https://github.com/electron-userland/electron-builder/commit/8e0a57d36a002fde5621f11edae17ee4eeeb8cba)), closes [#4176](https://github.com/electron-userland/electron-builder/issues/4176)
* **electron-publish:** socket hang up error 422 issues in github publish ([#6563](https://github.com/electron-userland/electron-builder/issues/6563)) ([39da9ed](https://github.com/electron-userland/electron-builder/commit/39da9edd2df5c147ef2d868f022484a8b2e0466a))
* **electron-publish:** Unable to publish assets to Github (ReleaseAsset asset_already_exists) ([1bd73c9](https://github.com/electron-userland/electron-builder/commit/1bd73c9ced651320e082b62b6e06c043bdb32750)), closes [#3559](https://github.com/electron-userland/electron-builder/issues/3559)
* **electron-publish:** wait after github error ([6fc9fc5](https://github.com/electron-userland/electron-builder/commit/6fc9fc5c3e7071f99e0b6e7493a18471efaf9604))
* **electron-updater:** `null` object error when MacUpdater logs server port before it is listening ([#6149](https://github.com/electron-userland/electron-builder/issues/6149)) ([ca0e845](https://github.com/electron-userland/electron-builder/commit/ca0e8454b876c9fa0c95dbadf2461419e3a8b697))
* **electron-updater:** cannot download differentially..: Error: Maximum allowed size is 5 MB ([c5c2eeb](https://github.com/electron-userland/electron-builder/commit/c5c2eeb80b9f357c18b486e94524580016009bd3)), closes [#3564](https://github.com/electron-userland/electron-builder/issues/3564)
* **electron-updater:** do not install on quit when autoInstallOnAppQuit is set to false ([#5681](https://github.com/electron-userland/electron-builder/issues/5681)) ([8f84591](https://github.com/electron-userland/electron-builder/commit/8f845916d1f44e347fa36cfd95bc1fa1fe14c455))
* **electron-updater:** electron-updater must not depend on builder-util ([1533909](https://github.com/electron-userland/electron-builder/commit/153390943433da0bb3229e585a1171255d240132))
* **electron-updater:** expose "isUpdaterActive" ([b83f580](https://github.com/electron-userland/electron-builder/commit/b83f5801771585c18524c3cee74e59de5fa9ab30)), closes [#4028](https://github.com/electron-userland/electron-builder/issues/4028)
* **electron-updater:** fix backward compatibility for GitHub provider without channels ([#6998](https://github.com/electron-userland/electron-builder/issues/6998)) ([d6115bc](https://github.com/electron-userland/electron-builder/commit/d6115bc5d066d6eee2638015be0c804b31ffcc18))
* **electron-updater:** fix import errors ([#6140](https://github.com/electron-userland/electron-builder/issues/6140)) ([a3f2cd1](https://github.com/electron-userland/electron-builder/commit/a3f2cd1565771c8ce6c5a4b40d1c88316a75dff3)), closes [#6134](https://github.com/electron-userland/electron-builder/issues/6134)
* **electron-updater:** forbid back tick ([82d6602](https://github.com/electron-userland/electron-builder/commit/82d66026fd04f8115d7a06221fbe058ff56a283a)), closes [#4701](https://github.com/electron-userland/electron-builder/issues/4701)
* **electron-updater:** Forbid using of quotes in a file names. ([dead150](https://github.com/electron-userland/electron-builder/commit/dead150769463adbff38b19e9099df6547db0e24))
* **electron-updater:** reduce electron-updater size ([8025fb4](https://github.com/electron-userland/electron-builder/commit/8025fb49f27e01b7f5aeb4f5220270f031d5c3ce)), closes [#3953](https://github.com/electron-userland/electron-builder/issues/3953)
* **electron-updater:** search 'arm64' in name and url to fix updates from Github private repos ([1580ea6](https://github.com/electron-userland/electron-builder/commit/1580ea691c4b82ea80c6420d806bc4bfaef5fd38))
* **electron-updater:** small cleanup and add more debug logging for MacUpdater to investigate [#6120](https://github.com/electron-userland/electron-builder/issues/6120) ([#6122](https://github.com/electron-userland/electron-builder/issues/6122)) ([ae81dfa](https://github.com/electron-userland/electron-builder/commit/ae81dfae519435355fc079c76fc16ac25216bf38))
* **electron-updater:** use app version as version for blockmap url instead of parsed semver ([5efafa8](https://github.com/electron-userland/electron-builder/commit/5efafa84e3927f688e5843cd1306cbfe098bb6e7))
* **electron-updater:** use tag name instead of version when resolving GitHub files ([#6117](https://github.com/electron-userland/electron-builder/issues/6117)) ([dcf03a6](https://github.com/electron-userland/electron-builder/commit/dcf03a67a8a0d4cec4422cda0aa2585f7f54a384))
* **electron-updater:** when AllowDowngrade is true and latest version is older, take the update ([#4218](https://github.com/electron-userland/electron-builder/issues/4218)) ([5bf4498](https://github.com/electron-userland/electron-builder/commit/5bf44987412189783e9b7ebbc35376ce471362c6))
* enable NPM_NO_BIN_LINKS for yarn 1.x.x ([#4915](https://github.com/electron-userland/electron-builder/issues/4915)) ([873089e](https://github.com/electron-userland/electron-builder/commit/873089ec30937a628de7f7f6f5d76ce54d0c4f95))
* ensure that proper electron version will be used ([9947dd9](https://github.com/electron-userland/electron-builder/commit/9947dd93f7a2ec4c2fb2322c51486b8d2966677b)), closes [#3984](https://github.com/electron-userland/electron-builder/issues/3984)
* ensure that setgid and setuid flags are cleared ([80b8d91](https://github.com/electron-userland/electron-builder/commit/80b8d919f861b57c98b08438da0c24b120821c82)), closes [#3608](https://github.com/electron-userland/electron-builder/issues/3608)
* escape instead of error ([#5116](https://github.com/electron-userland/electron-builder/issues/5116)) ([e2cc9f9](https://github.com/electron-userland/electron-builder/commit/e2cc9f95798df0db47412a5d94b032a8c6ad2882))
* Escape version in NSIS Updater during replace ([#5655](https://github.com/electron-userland/electron-builder/issues/5655)) ([77c215d](https://github.com/electron-userland/electron-builder/commit/77c215d1b1913982a7c9a62b1b5098d95a37272d))
* extend http file limit ([#5843](https://github.com/electron-userland/electron-builder/issues/5843)) ([9305fef](https://github.com/electron-userland/electron-builder/commit/9305fefa1265ec1a244b0003bd4489731d5f15a4)), closes [#4676](https://github.com/electron-userland/electron-builder/issues/4676)
* fix husky not create hooks and improve lint when commit ([#5716](https://github.com/electron-userland/electron-builder/issues/5716)) ([18e0c24](https://github.com/electron-userland/electron-builder/commit/18e0c242ec879a0d9582f50a36ce5ea5d9834a51))
* fixes for server auth for MacUpdater ([#6587](https://github.com/electron-userland/electron-builder/issues/6587)) ([8746f91](https://github.com/electron-userland/electron-builder/commit/8746f910d136fb9b531e688d0a646eeb9528adc6))
* fixing downloadPromise not resolving on Mac. ([#5802](https://github.com/electron-userland/electron-builder/issues/5802)) ([d57453c](https://github.com/electron-userland/electron-builder/commit/d57453cffc8e502fb1c95a9287dee2dd5cdd4b73))
* github provider prerelease check incorrectly casts undefined to String. Fixes [#6809](https://github.com/electron-userland/electron-builder/issues/6809) ([#6810](https://github.com/electron-userland/electron-builder/issues/6810)) ([817e68b](https://github.com/electron-userland/electron-builder/commit/817e68ba54f4fa60fec789fcfcfb527473a610fc))
* improve `downloadUpdate` typing to match the doc ([#7099](https://github.com/electron-userland/electron-builder/issues/7099)) ([cd21b09](https://github.com/electron-userland/electron-builder/commit/cd21b0918843fe1269ddaf8dde099c8faeb54b80))
* include SnapStoreOptions into schema ([7aed22e](https://github.com/electron-userland/electron-builder/commit/7aed22e44ef7adddf0e148cee2cf7c954b74b391))
* incompatible Windows sign tool in end user environment.  ([#6817](https://github.com/electron-userland/electron-builder/issues/6817)) ([2860d13](https://github.com/electron-userland/electron-builder/commit/2860d132fc837813627e6508e05b18ed5e5dedfc))
* Inconsistent versions of builder-util-runtime ([9ba8ade](https://github.com/electron-userland/electron-builder/commit/9ba8ade66593c3e15df72156379ab0858d88ff6b)), closes [#3887](https://github.com/electron-userland/electron-builder/issues/3887)
* Invalid code signing for MAS build due to ordering of certificate check ([#7040](https://github.com/electron-userland/electron-builder/issues/7040)) ([#7089](https://github.com/electron-userland/electron-builder/issues/7089)) ([a1d86fd](https://github.com/electron-userland/electron-builder/commit/a1d86fd75bbc7b252403c16966430a2e3562205d))
* latest node-gyp with old Electron versions ([#6402](https://github.com/electron-userland/electron-builder/issues/6402)) ([f41d5f3](https://github.com/electron-userland/electron-builder/commit/f41d5f397ade8f6199d56bb4275b05a0a0e65bca))
* linking CLI `version` output with package.json ([#6097](https://github.com/electron-userland/electron-builder/issues/6097)) ([a4eae34](https://github.com/electron-userland/electron-builder/commit/a4eae34f38444e0f30cf94af869e9e84c406a469))
* **linux:** do not write empty Comment in desktop file ([3f90401](https://github.com/electron-userland/electron-builder/commit/3f904012b0073f52a2c6b58fc515da3757a56e96))
* **linux:** executable path in Debian postinst script ([#5941](https://github.com/electron-userland/electron-builder/issues/5941)) ([4a5132f](https://github.com/electron-userland/electron-builder/commit/4a5132f25f64e1d0907e77e6fc309edf01d1b04b)), closes [#5933](https://github.com/electron-userland/electron-builder/issues/5933)
* **linux:** Linux icon is not set if path is not explicitly defined in config ([#5385](https://github.com/electron-userland/electron-builder/issues/5385)) ([9fd950b](https://github.com/electron-userland/electron-builder/commit/9fd950bc046ca1748950f63894993947da8185c5))
* **linux:** mutually exclusive exec command args ([#6384](https://github.com/electron-userland/electron-builder/issues/6384)) ([5468c18](https://github.com/electron-userland/electron-builder/commit/5468c188f30f65352ca651e1f5fa9f8915c48c6b))
* **linux:** remove 24/96 icon sizes - not required in general ([bb7d0f6](https://github.com/electron-userland/electron-builder/commit/bb7d0f6824d150183fe6ef13e242b59bc97c3f3d))
* Lock wine version to v6 in docker image ([#6816](https://github.com/electron-userland/electron-builder/issues/6816)) ([8f57a90](https://github.com/electron-userland/electron-builder/commit/8f57a90c885254bf442e7eea5b8f450bd400eac4)), closes [#6780](https://github.com/electron-userland/electron-builder/issues/6780)
* Look for the Amazon cred header to remove auth header ([#5594](https://github.com/electron-userland/electron-builder/issues/5594)) ([46a8840](https://github.com/electron-userland/electron-builder/commit/46a8840bb4b3ed9b81ac65d3351debc4e34f30ce))
* **mac:** add needed helpers for electron 6.0.0 ([#4111](https://github.com/electron-userland/electron-builder/issues/4111)) ([c36f6c8](https://github.com/electron-userland/electron-builder/commit/c36f6c844692a8bb2e9f974fd0cd3fcdd79a444c))
* **mac:** adding arch suffix to pkg target to enable non-universal pkg builds ([#5847](https://github.com/electron-userland/electron-builder/issues/5847)) ([#5897](https://github.com/electron-userland/electron-builder/issues/5897)) ([9f9e20c](https://github.com/electron-userland/electron-builder/commit/9f9e20c86bcaed94ff5d6c63e7480bd8163a0e0e))
* **mac:** Allow arm64 macs to update to x64 version if no arm64 version available ([#5524](https://github.com/electron-userland/electron-builder/issues/5524)) ([dc5c2f8](https://github.com/electron-userland/electron-builder/commit/dc5c2f8e772da4a9e6f1cf9578c70f60ddc36b37))
* **mac:** allow Mac Developer certs for non Mac App Store builds ([#6956](https://github.com/electron-userland/electron-builder/issues/6956)) ([4e90504](https://github.com/electron-userland/electron-builder/commit/4e905046e632b396735b78618fbc01331448f088)), closes [#6564](https://github.com/electron-userland/electron-builder/issues/6564)
* **mac:** always include a secure timestamp with your code-signing signature ([2e7ee22](https://github.com/electron-userland/electron-builder/commit/2e7ee226763a25e934958a065462a7d69fc020d8))
* **mac:** Cannot find module '../../electron-osx-sign/util-identities' ([4bc0559](https://github.com/electron-userland/electron-builder/commit/4bc0559b3957674ab4280dfc9197a9ebeb8fd53c)), closes [#4067](https://github.com/electron-userland/electron-builder/issues/4067)
* **mac:** ensure that created temporary keychain doesn't pollute system even if not deleted correctly ([97684ca](https://github.com/electron-userland/electron-builder/commit/97684ca2c81c2b71d56a641c822f507a4d4accfc)), closes [#3685](https://github.com/electron-userland/electron-builder/issues/3685)
* **mac:** executables within app.asar.unpacked are not being signed correctly in OSX 10.14.5 ([519bb47](https://github.com/electron-userland/electron-builder/commit/519bb4762437eba1a153211c55e328debc04ffc2)), closes [#3940](https://github.com/electron-userland/electron-builder/issues/3940)
* **mac:** fix "Contents/Info.plist" don't have identical SHAs when creating a universal build ([#5550](https://github.com/electron-userland/electron-builder/issues/5550)) ([0ba839b](https://github.com/electron-userland/electron-builder/commit/0ba839b72b6a13178ad5bc4b03a47f9aca980650))
* **mac:** identifier missing from pkgbuild ([#4558](https://github.com/electron-userland/electron-builder/issues/4558)) ([d216473](https://github.com/electron-userland/electron-builder/commit/d2164732fee19b28018bf3a39c799be3c72bd8f7))
* **mac:** Invalid Bundle Identifier Electron Helper (GPU, Plugin, and Rende… ([#4154](https://github.com/electron-userland/electron-builder/issues/4154)) ([2eabee0](https://github.com/electron-userland/electron-builder/commit/2eabee08f6e53490dc0903ce3d01179c3e3ade59)), closes [#4151](https://github.com/electron-userland/electron-builder/issues/4151)
* **mac:** make tempFile unique for each call to getProvisioningProfileAsync ([#4269](https://github.com/electron-userland/electron-builder/issues/4269)) ([f858f9e](https://github.com/electron-userland/electron-builder/commit/f858f9e0b43de8d646cce7ac4e9c00f773c2f131)), closes [#4204](https://github.com/electron-userland/electron-builder/issues/4204)
* **macos:** added keychain flag to getProvisioningProfileAsync ([#4332](https://github.com/electron-userland/electron-builder/issues/4332)) ([965392b](https://github.com/electron-userland/electron-builder/commit/965392bd5e800d50b5ea8c647b1dc00ef1f31495))
* **mac:** Pass platformName and options in doPack ([#5511](https://github.com/electron-userland/electron-builder/issues/5511)) ([f78e3f4](https://github.com/electron-userland/electron-builder/commit/f78e3f48d7cde71fd52fe1024c114bbe23f83562))
* **mac:** remove internet-enable from macOS 10.15 ([#4405](https://github.com/electron-userland/electron-builder/issues/4405)) ([#4531](https://github.com/electron-userland/electron-builder/issues/4531)) ([8dd587f](https://github.com/electron-userland/electron-builder/commit/8dd587facd5b57ab1c8f3ab10db1a77b01a8acf1))
* **mac:** remove not required com.apple.security.cs.allow-dyld-environment-variables ([f6b6e23](https://github.com/electron-userland/electron-builder/commit/f6b6e23d31a86737b61f10ca4dc19cbc95b99ab0))
* **mac:** Remove redundant signing op for mas and mas-dev targets ([#4321](https://github.com/electron-userland/electron-builder/issues/4321)) ([5692281](https://github.com/electron-userland/electron-builder/commit/56922819f0be39fffb31bbb50437ad4fcdde7365))
* **mac:** should normalize unicode strings from file system before used in string compare ([#4841](https://github.com/electron-userland/electron-builder/issues/4841)) ([37a17f2](https://github.com/electron-userland/electron-builder/commit/37a17f222b4802282c0638c163f76df35983c8d3))
* **mac:** signing cert filter incorrectly selects certificates ([#6094](https://github.com/electron-userland/electron-builder/issues/6094)) ([#6101](https://github.com/electron-userland/electron-builder/issues/6101)) ([#6105](https://github.com/electron-userland/electron-builder/issues/6105)) ([4a177dc](https://github.com/electron-userland/electron-builder/commit/4a177dc01c9119443426f1eb500afb836fd4f381))
* **mac:** Update entitlements.plist to be compliant with electron-notarize requirements ([#4491](https://github.com/electron-userland/electron-builder/issues/4491)) ([692091b](https://github.com/electron-userland/electron-builder/commit/692091b981f120274aa2941ab038137dceddef92))
* **mac:** use `uname -a` to get arch before testing 'process.arch' on mac silicon  ([#6381](https://github.com/electron-userland/electron-builder/issues/6381)) ([828fcd3](https://github.com/electron-userland/electron-builder/commit/828fcd378c2df28763893ef68f92d5b1a72fead3))
* **mac:** Workaround for hdiutil randomly failing ([#5431](https://github.com/electron-userland/electron-builder/issues/5431)) ([#5464](https://github.com/electron-userland/electron-builder/issues/5464)) ([53270cf](https://github.com/electron-userland/electron-builder/commit/53270cfe4eb2de1ac55e4b281c2c53483d4d1f2e))
* **mas:** Allow signing with "3rd Party Mac Developer Application" ([#6970](https://github.com/electron-userland/electron-builder/issues/6970)) ([28c07b4](https://github.com/electron-userland/electron-builder/commit/28c07b4392161732ee221dbb3f3a3633899cfa33))
* **mas:** Cannot create MAS build ([1acd5b3](https://github.com/electron-userland/electron-builder/commit/1acd5b315d742353c44a2d71e436ac28d0d8438d)), closes [#4048](https://github.com/electron-userland/electron-builder/issues/4048)
* **mas:** set hardenedRuntime to false by default for mas and mas-dev ([#4548](https://github.com/electron-userland/electron-builder/issues/4548)) ([f1e3242](https://github.com/electron-userland/electron-builder/commit/f1e324204eb40b36b017bac4f9c873361325f0a3))
* Merge arrays from same config key in cascading electron-builder configs, such as `files` ([#6841](https://github.com/electron-userland/electron-builder/issues/6841)) ([9dc13ba](https://github.com/electron-userland/electron-builder/commit/9dc13ba2c1e7a852d3f743833f1bde17b62f1806))
* mime lib import is incorrect ([37b84fb](https://github.com/electron-userland/electron-builder/commit/37b84fb1b5d77390a7536a2def672d995a451580)), closes [#5861](https://github.com/electron-userland/electron-builder/issues/5861)
* more clear error if cannot extract publisher name from code signing certificate ([1254197](https://github.com/electron-userland/electron-builder/commit/12541978d252f7c87679a134264865dbc71b1d94))
* moving typed-emitter from devDependency to dependencies ([#6889](https://github.com/electron-userland/electron-builder/issues/6889)) ([869ec27](https://github.com/electron-userland/electron-builder/commit/869ec27fd1d99b9913875cb4d7ae7c733c1f3e25))
* **msi:** fix broken shortcut icon when using msi target, adding msi option `iconId` ([#6247](https://github.com/electron-userland/electron-builder/issues/6247)) ([a9ec90d](https://github.com/electron-userland/electron-builder/commit/a9ec90d539fdbb5786692629275b1a89bfd7aec4))
* **msi:** manually escape XML special characters when building project.wxs XML ([#6878](https://github.com/electron-userland/electron-builder/issues/6878)) ([2ece89a](https://github.com/electron-userland/electron-builder/commit/2ece89a08e7fb74a11ba3d0f5980b2a57c8b34ad))
* **multipleRangeDownloader:** when response ends nothing more happens ([#4817](https://github.com/electron-userland/electron-builder/issues/4817)) ([0443055](https://github.com/electron-userland/electron-builder/commit/0443055f0359e16d77837c3d46dd88e412129e62))
* nsis update fails for private github repos ([#4568](https://github.com/electron-userland/electron-builder/issues/4568)) ([beb2729](https://github.com/electron-userland/electron-builder/commit/beb272906c49175da4ae97746fcb5f72d5d0acf8))
* nsis web build ([#4620](https://github.com/electron-userland/electron-builder/issues/4620)) ([d5a00c3](https://github.com/electron-userland/electron-builder/commit/d5a00c3e519a995a1540c8b9e89a4be7432db7f8))
* nsis-web target set APP_PACKAGE_URL_IS_INCOMPLETE when specifying appPackageUrl ([#6964](https://github.com/electron-userland/electron-builder/issues/6964)) ([b0e1b6f](https://github.com/electron-userland/electron-builder/commit/b0e1b6f8af95bc371c0bc91df65965f3f60f3a87))
* **nsis-web:** connectivity issues with nsis-web ([0ee226b](https://github.com/electron-userland/electron-builder/commit/0ee226baf89dd5f951dc3678e3b74c09df87385b)), closes [#2049](https://github.com/electron-userland/electron-builder/issues/2049)
* **nsis:** Building NSIS installers broken after switching from 22.10.5 to 22.11.1 ([#5873](https://github.com/electron-userland/electron-builder/issues/5873)) ([3e6c10f](https://github.com/electron-userland/electron-builder/commit/3e6c10f2d227c3de001170f1ea6e0b590b5a9794)), closes [#5863](https://github.com/electron-userland/electron-builder/issues/5863)
* **nsis:** change Russian locale from "game" to "application" ([#4743](https://github.com/electron-userland/electron-builder/issues/4743)) ([ffa2a4e](https://github.com/electron-userland/electron-builder/commit/ffa2a4e8328275fe03ec408b6c9909694bc7ae10))
* **nsis:** check that out file is not blocked ([39faac5](https://github.com/electron-userland/electron-builder/commit/39faac55ff669a0db2c4cae7e954b1252ed9c404))
* **nsis:** cleanup temporary 7z folder ([#6793](https://github.com/electron-userland/electron-builder/issues/6793)) ([85a3e55](https://github.com/electron-userland/electron-builder/commit/85a3e5595e64346514dd7f5fade42e3632a18ee0))
* **nsis:** cs locale typos in messages ([#5358](https://github.com/electron-userland/electron-builder/issues/5358)) ([0fb69b5](https://github.com/electron-userland/electron-builder/commit/0fb69b5d11e5c8aa707b7af709a0ab52f5019a9f))
* **nsis:** Decide to use elevate.exe for installer when update using nsis packElevateHelper option in electron-builder config ([#6787](https://github.com/electron-userland/electron-builder/issues/6787)) ([eb456a8](https://github.com/electron-userland/electron-builder/commit/eb456a87b0603dcc0e6d777c2b8e1c2e7b64d3a6))
* **nsis:** differential download ([#5948](https://github.com/electron-userland/electron-builder/issues/5948)) ([39ac82f](https://github.com/electron-userland/electron-builder/commit/39ac82f89a1a95b924bf1b9651ce143dd219687d))
* **nsis:** Do not abort when uninstaller fails ([#5292](https://github.com/electron-userland/electron-builder/issues/5292)) ([ea9281b](https://github.com/electron-userland/electron-builder/commit/ea9281b77bb484bce67cfc94ef5d85004927b124))
* **nsis:** don't kill ourselves when upgrading ([#5445](https://github.com/electron-userland/electron-builder/issues/5445)) ([a1a3ef3](https://github.com/electron-userland/electron-builder/commit/a1a3ef325d0ea5d6dec250dc8b1e0007b890d28a))
* **nsis:** Error handling if uninstaller cannot be launched ([#4674](https://github.com/electron-userland/electron-builder/issues/4674)) ([442493b](https://github.com/electron-userland/electron-builder/commit/442493b0539d7e33a26d84cdcdd8ca687b0246d2))
* **nsis:** fix cli config error when use Boolean value in -c.nsis config ([#4528](https://github.com/electron-userland/electron-builder/issues/4528)) ([ac8e9aa](https://github.com/electron-userland/electron-builder/commit/ac8e9aa57d32940eb0c9566a89de57890a9df904))
* **nsis:** fix spawnAndWrite reject in util ([#4566](https://github.com/electron-userland/electron-builder/issues/4566)) ([2229b28](https://github.com/electron-userland/electron-builder/commit/2229b28107e8ce65461674a11f0c971feb961ec9))
* **nsis:** fix typo in German installer message ([#6960](https://github.com/electron-userland/electron-builder/issues/6960)) ([6e90c84](https://github.com/electron-userland/electron-builder/commit/6e90c8459111ec046b91f8ae5da1990af0bbe942))
* **nsis:** generate uninstaller without elevating ([#5575](https://github.com/electron-userland/electron-builder/issues/5575)) ([#6013](https://github.com/electron-userland/electron-builder/issues/6013)) ([b00aea3](https://github.com/electron-userland/electron-builder/commit/b00aea32107cd379b8489f7abea493d16fe38197))
* **nsis:** Ignore other users processes during per-user installation ([#6472](https://github.com/electron-userland/electron-builder/issues/6472)) ([e3d06af](https://github.com/electron-userland/electron-builder/commit/e3d06afae1236d44e4b6e670b453b260b1f74d84)), closes [#6104](https://github.com/electron-userland/electron-builder/issues/6104)
* **nsis:** improve Windows installer task kill process (related to child processes) ([39e6783](https://github.com/electron-userland/electron-builder/commit/39e678333a7f2f79e6cbd840167adee1179b64db)), closes [#2894](https://github.com/electron-userland/electron-builder/issues/2894)
* **nsis:** keep injected logger state ([#5596](https://github.com/electron-userland/electron-builder/issues/5596)) ([be4a1fb](https://github.com/electron-userland/electron-builder/commit/be4a1fb05b6734800aa97652e856de1308e4a2f2))
* **nsis:** new translations for various strings in nsis messages template ([#6827](https://github.com/electron-userland/electron-builder/issues/6827)) ([fa72861](https://github.com/electron-userland/electron-builder/commit/fa72861f6cd2de97d191f1b2bbfddc6edf48ab6d))
* **nsis:** NSIS Uninstaller registry entry format change ([#4069](https://github.com/electron-userland/electron-builder/issues/4069)) ([7518aee](https://github.com/electron-userland/electron-builder/commit/7518aee8e1abe0516071b350748e84dc47e35cf7))
* **nsis:** nsis-web: Windows 7 and above is required when installing on Windows 7 ([d451308](https://github.com/electron-userland/electron-builder/commit/d4513087c4514d974865efd6b2f0f4e880491093)), closes [#2420](https://github.com/electron-userland/electron-builder/issues/2420)
* **nsis:** output files sometimes locked by virus scanners ([#5005](https://github.com/electron-userland/electron-builder/issues/5005)) ([#5143](https://github.com/electron-userland/electron-builder/issues/5143)) ([a6d00ab](https://github.com/electron-userland/electron-builder/commit/a6d00ab4f5b146f6e9669395f4dac5b5469804e4))
* **nsis:** per-machine installs must properly elevate during silent install/updates ([#6450](https://github.com/electron-userland/electron-builder/issues/6450)) ([661a652](https://github.com/electron-userland/electron-builder/commit/661a6522520e9ea59549cb7e18986fcfb58e873a)), closes [#6438](https://github.com/electron-userland/electron-builder/issues/6438) [#6073](https://github.com/electron-userland/electron-builder/issues/6073) [#6425](https://github.com/electron-userland/electron-builder/issues/6425) [#5468](https://github.com/electron-userland/electron-builder/issues/5468)
* **NSIS:** prevent partial overwrites during `Nsis7z::Extract` ([#6547](https://github.com/electron-userland/electron-builder/issues/6547)) ([bea51d6](https://github.com/electron-userland/electron-builder/commit/bea51d6a8bb828d9b34734908f13b667aa55b0e9))
* **nsis:** retry closing the app until success ([#5902](https://github.com/electron-userland/electron-builder/issues/5902)) ([d307c21](https://github.com/electron-userland/electron-builder/commit/d307c21b34abee1cd2b8dcd3e705995914dda70f))
* **nsis:** revert to 3.0.4.1 ([9c43cc3](https://github.com/electron-userland/electron-builder/commit/9c43cc369a764d361d9d9a22d607febd1d451d92)), closes [#4793](https://github.com/electron-userland/electron-builder/issues/4793)
* **nsis:** setting item `preCompressedFileExtensions` is invalid ([c3d6de4](https://github.com/electron-userland/electron-builder/commit/c3d6de46ace5b10a1c85cabbebc029751077741e)), closes [#3967](https://github.com/electron-userland/electron-builder/issues/3967)
* **nsis:** should close app when `Silent` and `ONE_CLICK` ([#6100](https://github.com/electron-userland/electron-builder/issues/6100)) ([baf640d](https://github.com/electron-userland/electron-builder/commit/baf640da459dc667240e6015deaf11adb2155063))
* **nsis:** specify full path to system's find ([#6771](https://github.com/electron-userland/electron-builder/issues/6771)) ([e6c2a62](https://github.com/electron-userland/electron-builder/commit/e6c2a629839184d4f9d3fa99b580d8c96911ea65))
* **nsis:** Update zh-tw translation ([#6773](https://github.com/electron-userland/electron-builder/issues/6773)) ([5a0bab1](https://github.com/electron-userland/electron-builder/commit/5a0bab115f4ede3f21e23e847c0d2dd7ecc99b16))
* **nsis:** use revertible+atomic rmdir on update and add user-confirmed retry loop ([#6551](https://github.com/electron-userland/electron-builder/issues/6551)) ([7b2a5e1](https://github.com/electron-userland/electron-builder/commit/7b2a5e1f19921e9da4aaaea8c01c78740f29f9dd))
* obtaining a certificate from the store when sha1 is not specified in the configuration ([#4666](https://github.com/electron-userland/electron-builder/issues/4666)) ([07693b3](https://github.com/electron-userland/electron-builder/commit/07693b3d528a6475888d60fb491c1bda139deb12))
* optionally package nested node_modules ([#3185](https://github.com/electron-userland/electron-builder/issues/3185)) ([#5911](https://github.com/electron-userland/electron-builder/issues/5911)) ([13bdf74](https://github.com/electron-userland/electron-builder/commit/13bdf74121168183a2484527e5a904db41c5c407))
* Optionally remove DISABLE_WAYLAND for snaps via allowNativeWayland option ([#6961](https://github.com/electron-userland/electron-builder/issues/6961)) ([4c867aa](https://github.com/electron-userland/electron-builder/commit/4c867aa017a7ce2bf88138634b6d1e9a3bf34854))
* **packager:** wait for artifactCreated completion event before starting an upload ([#6625](https://github.com/electron-userland/electron-builder/issues/6625)) ([c561af8](https://github.com/electron-userland/electron-builder/commit/c561af810d5de52bec57709cbaebca2ac92c55fc))
* parallel release creation with keygen publisher ([#6989](https://github.com/electron-userland/electron-builder/issues/6989)) ([7ad5101](https://github.com/electron-userland/electron-builder/commit/7ad5101b4a72df411b76cc500a6a0dca85bf6540))
* pin Keygen.io integration to v1.0 ([#6909](https://github.com/electron-userland/electron-builder/issues/6909)) ([0b6db59](https://github.com/electron-userland/electron-builder/commit/0b6db59ec10dfe05903f29d6790972f55746bef7))
* **pkg:** Add support for PKG background images in dark mode ([#4489](https://github.com/electron-userland/electron-builder/issues/4489)) ([a23e3d2](https://github.com/electron-userland/electron-builder/commit/a23e3d271708bd293bd39c16bafa7385780258cf))
* **pkg:** support electron 7 ([fc31199](https://github.com/electron-userland/electron-builder/commit/fc311995c196f1063ceb2d0bb0af61beac6038e8))
* **portable:** Disable CRCCheck for portable windows executable ([ec937b2](https://github.com/electron-userland/electron-builder/commit/ec937b2764ba9d884232c72d5fc9db7699e0bb16))
* pre-gyp for darwin targets if build on Linux or in Docker ([#5193](https://github.com/electron-userland/electron-builder/issues/5193)) ([f44206d](https://github.com/electron-userland/electron-builder/commit/f44206dc177521a37ac17f0699bab9eae0412712))
* prefetch command for arm ([f12a090](https://github.com/electron-userland/electron-builder/commit/f12a090f7a9cfc23980599091834668db69da181))
* prevent infinite looping of overwriteArtifact during Github publishing ([#6958](https://github.com/electron-userland/electron-builder/issues/6958)) ([8ffd9d4](https://github.com/electron-userland/electron-builder/commit/8ffd9d42d89634be76fd4554f659f2b2512f2081))
* Problem building multiple mac targets: TypeError: pattern.startsWith is not a function ([#5739](https://github.com/electron-userland/electron-builder/issues/5739)) ([a89edcb](https://github.com/electron-userland/electron-builder/commit/a89edcb0ff39a1465237a97619519bf55c519b20)), closes [#3012](https://github.com/electron-userland/electron-builder/issues/3012)
* Provide update command for project package manager ([#4167](https://github.com/electron-userland/electron-builder/issues/4167)) ([0348b9f](https://github.com/electron-userland/electron-builder/commit/0348b9f009d7f41c85e62e43f3163c0738c7edb4))
* **publish:** Bitbucket publish can have username different from owner ([#6293](https://github.com/electron-userland/electron-builder/issues/6293)) ([8ebfc96](https://github.com/electron-userland/electron-builder/commit/8ebfc96276bffe0bc1ad394c5ae6843976e01709))
* **publish:** isCi detection fails due to incorrect import ([#5876](https://github.com/electron-userland/electron-builder/issues/5876)) ([739721d](https://github.com/electron-userland/electron-builder/commit/739721d4ebbb94151634e3f84bb5e40f6258ed5c)), closes [#5875](https://github.com/electron-userland/electron-builder/issues/5875)
* quit on decompression errors in NSIS ([#5888](https://github.com/electron-userland/electron-builder/issues/5888)) ([ef981ab](https://github.com/electron-userland/electron-builder/commit/ef981ab1f6d6494c25dceb90f882d991815ac396))
* quitAndInstall not working on macOS with autoInstallOnAppQuit=false ([#6390](https://github.com/electron-userland/electron-builder/issues/6390)) ([a5e8073](https://github.com/electron-userland/electron-builder/commit/a5e8073e21b1ff791905cdb4ab011a724533d8c1))
* re-export some of "builder-util-runtime" types directly from "electron-updater". ([#5675](https://github.com/electron-userland/electron-builder/issues/5675)) ([#5869](https://github.com/electron-userland/electron-builder/issues/5869)) ([4a136a3](https://github.com/electron-userland/electron-builder/commit/4a136a3877e0c83d0b2d5441351b39e6340589c5))
* Re-fetch downloads if cache directory has changed ([#4958](https://github.com/electron-userland/electron-builder/issues/4958)) ([6827109](https://github.com/electron-userland/electron-builder/commit/6827109c007b16d486d57ae32bc262434e246089)), closes [#4955](https://github.com/electron-userland/electron-builder/issues/4955) [#4955](https://github.com/electron-userland/electron-builder/issues/4955)
* Reactivating bitbucket integration test for nsis updater ([#6680](https://github.com/electron-userland/electron-builder/issues/6680)) ([6fcd477](https://github.com/electron-userland/electron-builder/commit/6fcd47767af8a95ab018fe0d8a07d2c53a72067d))
* Reducing node version to be >=14 as opposed to explicitly 14.17.0 (the current max node 14 version) ([#5893](https://github.com/electron-userland/electron-builder/issues/5893)) ([#5896](https://github.com/electron-userland/electron-builder/issues/5896)) ([b6413a8](https://github.com/electron-userland/electron-builder/commit/b6413a85c6ca14861bc3521caafc6de317e2ecba))
* regenerating docs and schema ([f70abf1](https://github.com/electron-userland/electron-builder/commit/f70abf1628223e1cc0d687471ad36b4a2ee66ebe))
* regenerating schema to account for electron-universal options `x64ArchFiles` ([#6983](https://github.com/electron-userland/electron-builder/issues/6983)) ([adeaa34](https://github.com/electron-userland/electron-builder/commit/adeaa347c03b8947b0812ecef23398c0822646bb))
* remove @electron-builder/test from changeset ([e101e8d](https://github.com/electron-userland/electron-builder/commit/e101e8d190d7e3046222e88c32a62d727dadd808))
* Remove additional xml closing tag ([#4078](https://github.com/electron-userland/electron-builder/issues/4078)) ([4076dc9](https://github.com/electron-userland/electron-builder/commit/4076dc985651d13fe2149f01e71617723e8b619a))
* remove deprecated --arch, --platform, --draft, --prerelease ([68ffd54](https://github.com/electron-userland/electron-builder/commit/68ffd54aca4dc65f3f932a6580d744ae656ecbaf))
* remove deprecated `build` bin script ([bea9db9](https://github.com/electron-userland/electron-builder/commit/bea9db9daf8463b41b52d0a0edae051110fc29e5))
* remove host property from headers when signed by aws4.sign ([#4848](https://github.com/electron-userland/electron-builder/issues/4848)) ([0f0363b](https://github.com/electron-userland/electron-builder/commit/0f0363bd902d64504586dad2af522d161dec56a2)), closes [#4758](https://github.com/electron-userland/electron-builder/issues/4758)
* removing double exec of `checkForUpdates` that causes error thrown: "The command is disabled and cannot be executed" ([#5989](https://github.com/electron-userland/electron-builder/issues/5989)) ([71d3704](https://github.com/electron-userland/electron-builder/commit/71d37044d348ab0cd8f0f9f7754bf6ebaa4b996c))
* rendering extended node_modules in jsdoc ([#6843](https://github.com/electron-userland/electron-builder/issues/6843)) ([481a7ed](https://github.com/electron-userland/electron-builder/commit/481a7ed2b77e7e1b448f27e58fedeac53b107ffc))
* replace deprecated --cache-min option ([#6165](https://github.com/electron-userland/electron-builder/issues/6165)) ([c02ccbb](https://github.com/electron-userland/electron-builder/commit/c02ccbb9739a6fb2840625a825f6be33136567f0))
* replace deprecated interface ([#5049](https://github.com/electron-userland/electron-builder/issues/5049)) ([11874be](https://github.com/electron-userland/electron-builder/commit/11874be71223c4a846cbbaca4c9046a4fd08cf99))
* replace update-notifier with simple-update notifier due to dependency vulnerability ([#7078](https://github.com/electron-userland/electron-builder/issues/7078)) ([48cbb12](https://github.com/electron-userland/electron-builder/commit/48cbb120dc11994889f4aa61c8431531ce274006))
* requireProviderClass should be aware about snapStore ([10e4383](https://github.com/electron-userland/electron-builder/commit/10e4383d468457dff0b874e0cd4217a26bea4641))
* rerunning test-linux to update snapshot for upstream dep that now uses additional depedencies ([#6403](https://github.com/electron-userland/electron-builder/issues/6403)) ([434d388](https://github.com/electron-userland/electron-builder/commit/434d3887cb651ef93ce214dc7b8edeab6a298096))
* respect the signDlls flag ([#5133](https://github.com/electron-userland/electron-builder/issues/5133)) ([db6e762](https://github.com/electron-userland/electron-builder/commit/db6e7620260741a35557ba13429ac10a4f4cf5d9))
* Revert "feat: Upgrade to Ubuntu 22.04 and python 3.10" ([#7109](https://github.com/electron-userland/electron-builder/issues/7109)) ([7d606af](https://github.com/electron-userland/electron-builder/commit/7d606aff59c964dc0af93c0f235abb0f3e258dea))
* set github release name to match the app version ([#6840](https://github.com/electron-userland/electron-builder/issues/6840)) ([e9ba750](https://github.com/electron-userland/electron-builder/commit/e9ba75005dda39f03c04e37a5d46a1bbe634c189))
* sign macOS objects depth-first (close [#4932](https://github.com/electron-userland/electron-builder/issues/4932)) ([#4993](https://github.com/electron-userland/electron-builder/issues/4993)) ([7f8d59c](https://github.com/electron-userland/electron-builder/commit/7f8d59cee5ae28699a21fbb5413e5ead0b5f3880))
* signing of playwright ([#5451](https://github.com/electron-userland/electron-builder/issues/5451)) ([5075068](https://github.com/electron-userland/electron-builder/commit/50750683b11d5670a182bd72f7cab14023e2b030))
* signing of user-defined binaries on mac when resolved as relative path ([#6660](https://github.com/electron-userland/electron-builder/issues/6660)) ([4c6d154](https://github.com/electron-userland/electron-builder/commit/4c6d1546d4942aa9d9a93b7309e8ed279f6378d2))
* skip unstable installer tests to unblock master CI pipeline ([#6544](https://github.com/electron-userland/electron-builder/issues/6544)) ([5648e05](https://github.com/electron-userland/electron-builder/commit/5648e05a9efa61f81e788ecf538a617df9f65fe1))
* **snap:** add missing %U in desktop file of snap builds ([#5001](https://github.com/electron-userland/electron-builder/issues/5001)) ([df5d050](https://github.com/electron-userland/electron-builder/commit/df5d050e47f2030e48e65c0e3b542c3aec61e9de))
* **snap:** allow snapcraft edge version ([d11c760](https://github.com/electron-userland/electron-builder/commit/d11c7607228159dfdd756f000310ed463d62652b)), closes [#4142](https://github.com/electron-userland/electron-builder/issues/4142)
* **snap:** command line arguments are not supported ([a7e1aec](https://github.com/electron-userland/electron-builder/commit/a7e1aeccda23043325f482a64d9c8a74d96b2292)), closes [#2880](https://github.com/electron-userland/electron-builder/issues/2880) [#3035](https://github.com/electron-userland/electron-builder/issues/3035) [#3253](https://github.com/electron-userland/electron-builder/issues/3253)
* **snap:** confinement classic not allowed with plugs ([efbc41e](https://github.com/electron-userland/electron-builder/commit/efbc41e1359207391a9e70e436560f1fe22ef8d6)), closes [#2730](https://github.com/electron-userland/electron-builder/issues/2730)
* **snap:** detect snapcraft version if quoted ([d18909b](https://github.com/electron-userland/electron-builder/commit/d18909bd3afdbcdfb49850c286ffe2845b45e24c))
* **snap:** Problem with armhf/armv7l (raspberry pi) when creating snaps ([9754269](https://github.com/electron-userland/electron-builder/commit/9754269a98f5b8baa3c06f23f827423fcc29c3f1)), closes [#3976](https://github.com/electron-userland/electron-builder/issues/3976)
* **snap:** remove snap debugging ([#4589](https://github.com/electron-userland/electron-builder/issues/4589)) ([0ca2ccc](https://github.com/electron-userland/electron-builder/commit/0ca2cccb6f007348e6ef0f9c6dddf752ac411314))
* **snap:** Snap does not launch when Ubuntu uses Wayland ([2278c2a](https://github.com/electron-userland/electron-builder/commit/2278c2a347bb9e6d00f2f59719eb784ac9857c10)), closes [#4007](https://github.com/electron-userland/electron-builder/issues/4007)
* SnapStoreOptions required properties ([#6327](https://github.com/electron-userland/electron-builder/issues/6327)) ([#6333](https://github.com/electron-userland/electron-builder/issues/6333)) ([54ee4e7](https://github.com/electron-userland/electron-builder/commit/54ee4e72c5db859b9a00104179786567a0e977ff))
* **snap:** stricter filtering for xcb libraries ([#5205](https://github.com/electron-userland/electron-builder/issues/5205)) ([#5206](https://github.com/electron-userland/electron-builder/issues/5206)) ([9164f4d](https://github.com/electron-userland/electron-builder/commit/9164f4d328efd03da6b8c2f17b3535dcbdbb9cca))
* **snap:** use correct arch triplet for arm ([5b1fa2e](https://github.com/electron-userland/electron-builder/commit/5b1fa2ef1d54dddcb366bd4efe604b128434c7fa))
* **snap:** use correct arch triplet for arm ([85c32f3](https://github.com/electron-userland/electron-builder/commit/85c32f392449627dfee014d5740df4f1d75db0e1)), closes [#3977](https://github.com/electron-userland/electron-builder/issues/3977)
* specify protocol as https to complete proxy support fix ([#6516](https://github.com/electron-userland/electron-builder/issues/6516)) ([344bb23](https://github.com/electron-userland/electron-builder/commit/344bb232d71e608b881a04fc98dca0858e42ddfc)), closes [#6286](https://github.com/electron-userland/electron-builder/issues/6286)
* **squirrel.windows:** Fixed Squirrel Windows Description Error ([#4292](https://github.com/electron-userland/electron-builder/issues/4292)) ([555fad2](https://github.com/electron-userland/electron-builder/commit/555fad24a0a4543e36900b3da9f321b862b4fd8c))
* strip extra fields out that are not allowed when creating snap.yaml ([#7104](https://github.com/electron-userland/electron-builder/issues/7104)) ([#7110](https://github.com/electron-userland/electron-builder/issues/7110)) ([0a7025e](https://github.com/electron-userland/electron-builder/commit/0a7025e5184e3333d077db1f7e782d6a768ecdea))
* Stub CircleCI config since we can't disable it from dashboard ([#6543](https://github.com/electron-userland/electron-builder/issues/6543)) ([22fb8c6](https://github.com/electron-userland/electron-builder/commit/22fb8c63ac196c61c6b449e6e5e95d91117f8894))
* Support Windows 11 in VMs ([#6185](https://github.com/electron-userland/electron-builder/issues/6185)) ([f6a3053](https://github.com/electron-userland/electron-builder/commit/f6a3053563bd50dc77010d2910086c81acdf613e))
* test snap update for abi_registry.json ([#5823](https://github.com/electron-userland/electron-builder/issues/5823)) ([6237e67](https://github.com/electron-userland/electron-builder/commit/6237e670a8ddd99ec8c076db86361c06c04eedd4))
* typo in `fileMatcher`'s default patterns ([#5705](https://github.com/electron-userland/electron-builder/issues/5705)) ([c0ae89c](https://github.com/electron-userland/electron-builder/commit/c0ae89c004ea546ae6e0a73ec0f04e038169197c))
* Unable to find latest version on GitHub ([#6822](https://github.com/electron-userland/electron-builder/issues/6822)) ([bfe29a5](https://github.com/electron-userland/electron-builder/commit/bfe29a5e991c2719032877bd7225b15b6b836221))
* unzipping of the blockmap ([#5025](https://github.com/electron-userland/electron-builder/issues/5025)) ([a887d23](https://github.com/electron-userland/electron-builder/commit/a887d2371821827d59966fb72a9b9c3225bedd90))
* Update assistedMessages.yml with korean entries ([#6309](https://github.com/electron-userland/electron-builder/issues/6309)) ([e29a6b8](https://github.com/electron-userland/electron-builder/commit/e29a6b8b36695a2ed9d2f9a57e4c1c74587d1b16))
* Update BintrayProvider.ts ([#4921](https://github.com/electron-userland/electron-builder/issues/4921)) ([65bb441](https://github.com/electron-userland/electron-builder/commit/65bb44168ee9c2be50905f7932a87bbde491f10b))
* Update certificate validation on Windows to check full DN ([#6576](https://github.com/electron-userland/electron-builder/issues/6576)) ([53467c7](https://github.com/electron-userland/electron-builder/commit/53467c724dacc11fc270cebaba22f8cf84dff24f))
* update check failing with TypeError ([#5877](https://github.com/electron-userland/electron-builder/issues/5877)) ([7884b50](https://github.com/electron-userland/electron-builder/commit/7884b502c1daa720857a4b8428ea2cdfd0e377d8))
* Update deprecated env var ([#4451](https://github.com/electron-userland/electron-builder/issues/4451)) ([e182787](https://github.com/electron-userland/electron-builder/commit/e18278707752363a9e46924d31046422f7f845b7))
* update repo in CONTRIBUTING.md ([#5726](https://github.com/electron-userland/electron-builder/issues/5726)) ([da85087](https://github.com/electron-userland/electron-builder/commit/da85087143d2c6a63faab4c44c28dc625326e9ee))
* Update version.ts to match package.json ([#5882](https://github.com/electron-userland/electron-builder/issues/5882)) ([e148234](https://github.com/electron-userland/electron-builder/commit/e1482347228896b0825737df045fffa6e688e7b6))
* Updater "Error: Could not connect to the server." in macOS ([#6743](https://github.com/electron-userland/electron-builder/issues/6743)) ([27f18aa](https://github.com/electron-userland/electron-builder/commit/27f18aa1d890f3a82e856f4834b8387066fb697f))
* **updater:** Remove checks for app-update.yml when auto-updates are not supported ([#6616](https://github.com/electron-userland/electron-builder/issues/6616)) ([86e6d15](https://github.com/electron-userland/electron-builder/commit/86e6d1509f9b9c76c559e9c3a12b7a1595fe3ac4)), closes [#6322](https://github.com/electron-userland/electron-builder/issues/6322)
* **updater:** Support Electron 11 and below (Node < 14) ([#6594](https://github.com/electron-userland/electron-builder/issues/6594)) ([edc4b03](https://github.com/electron-userland/electron-builder/commit/edc4b030703ee3929b31608a496798635169f5b1)), closes [#6000](https://github.com/electron-userland/electron-builder/issues/6000)
* updating electron-osx-sign ([#6021](https://github.com/electron-userland/electron-builder/issues/6021)) ([6f63092](https://github.com/electron-userland/electron-builder/commit/6f630927ca949d8bdcde06e4eafaa63ce3636d5a)), closes [#6010](https://github.com/electron-userland/electron-builder/issues/6010) [#5190](https://github.com/electron-userland/electron-builder/issues/5190)
* updating integration test for prerelease flag ([#7072](https://github.com/electron-userland/electron-builder/issues/7072)) ([f205998](https://github.com/electron-userland/electron-builder/commit/f205998999ff615c9ea63184520a1efbbff5a785))
* updating nsis script to properly identify arm64 vs x64 vs ia32 package files within universal installers. ([#5558](https://github.com/electron-userland/electron-builder/issues/5558)) ([60f7fe3](https://github.com/electron-userland/electron-builder/commit/60f7fe367c54f7c1274e2628534f43cb9a93fcf6))
* use junction in windows to solve Error: EPERM: operation not per… ([#6529](https://github.com/electron-userland/electron-builder/issues/6529)) ([f7b3869](https://github.com/electron-userland/electron-builder/commit/f7b386986ec30f7e4cd3e3f68e078a773940a51c))
* use product name for safe github artifact name if possible ([07b3caa](https://github.com/electron-userland/electron-builder/commit/07b3caa411fc821a56bfb476860c13dc3f413a11))
* using regex to determine yarn version to account for newer releases of yarn (i.e. yarn 3). fixes: [#6069](https://github.com/electron-userland/electron-builder/issues/6069) ([#6071](https://github.com/electron-userland/electron-builder/issues/6071)) ([1e19aba](https://github.com/electron-userland/electron-builder/commit/1e19abaecb3fd7b6ff0932b46ee129e04d1496b3))
* **win/mac:** Small security fixes for electron-updater ([#6589](https://github.com/electron-userland/electron-builder/issues/6589)) ([633ee5d](https://github.com/electron-userland/electron-builder/commit/633ee5dc292174ed1486c53af93320f20cf02169))
* windows async signing ([9162711](https://github.com/electron-userland/electron-builder/commit/91627116fdffd5d5faec23e149392283b9979a22))
* **windows:** detect node path correctly on windows with cross-spawn ([#6069](https://github.com/electron-userland/electron-builder/issues/6069)) ([#6172](https://github.com/electron-userland/electron-builder/issues/6172)) ([6c945bd](https://github.com/electron-userland/electron-builder/commit/6c945bd59749d3fdd91f50ea4131ee22e82f72a2))
* **windows:** fix encoding issues while verifying signatures ([#5071](https://github.com/electron-userland/electron-builder/issues/5071)) ([70a0b80](https://github.com/electron-userland/electron-builder/commit/70a0b802b6225adb592f799c7cb129759d4b1c5c))
* **win:** Include swiftshader in signing directories for windows ([#6682](https://github.com/electron-userland/electron-builder/issues/6682)) ([e6312cb](https://github.com/electron-userland/electron-builder/commit/e6312cb54e5d957289d5c07b506491fcaea9e334))
* **win:** Sign all your asar unpacked binaries ([771b081](https://github.com/electron-userland/electron-builder/commit/771b081a34bf20bd51547111b319c2a261728d85)), closes [#3997](https://github.com/electron-userland/electron-builder/issues/3997)
* **win:** Windows update fails for custom paths that require admin rights ([#6073](https://github.com/electron-userland/electron-builder/issues/6073)) ([45fc0a0](https://github.com/electron-userland/electron-builder/commit/45fc0a003abc58969bb3a5d6ab1e3b61a9ad1a8d))
* workaround vite replacing process.env in updater ([#6160](https://github.com/electron-userland/electron-builder/issues/6160)) ([a3c72b2](https://github.com/electron-userland/electron-builder/commit/a3c72b2481ebaacfd717a7c492c119bcb9b7fc36))
* Wrap the nsProcess include in a !ifndef ([#6996](https://github.com/electron-userland/electron-builder/issues/6996)) ([5301525](https://github.com/electron-userland/electron-builder/commit/53015253939f450468a6d8e0405697ea70c2a138))
* write blockmap file for mac zip archives ([#6023](https://github.com/electron-userland/electron-builder/issues/6023)) ([0447b24](https://github.com/electron-userland/electron-builder/commit/0447b2457beb03648f1e7e841cd0a8d12d7e4aea)), closes [#4299](https://github.com/electron-userland/electron-builder/issues/4299)
* wrong permissions on Linux results ([30c3904](https://github.com/electron-userland/electron-builder/commit/30c3904d3cff6e2166c49068b4f72ed47e3daf96)), closes [#2682](https://github.com/electron-userland/electron-builder/issues/2682)


### chore

* v23.0.0 alpha ([#6556](https://github.com/electron-userland/electron-builder/issues/6556)) ([a138a86](https://github.com/electron-userland/electron-builder/commit/a138a86fb7b59098f5dac0c0a6b59c034eb9b222)), closes [#4898](https://github.com/electron-userland/electron-builder/issues/4898) [#6232](https://github.com/electron-userland/electron-builder/issues/6232) [#6259](https://github.com/electron-userland/electron-builder/issues/6259) [#6511](https://github.com/electron-userland/electron-builder/issues/6511) [#6506](https://github.com/electron-userland/electron-builder/issues/6506) [#6507](https://github.com/electron-userland/electron-builder/issues/6507) [#6514](https://github.com/electron-userland/electron-builder/issues/6514) [#6508](https://github.com/electron-userland/electron-builder/issues/6508) [#6508](https://github.com/electron-userland/electron-builder/issues/6508) [#3683](https://github.com/electron-userland/electron-builder/issues/3683) [#6201](https://github.com/electron-userland/electron-builder/issues/6201) [#6530](https://github.com/electron-userland/electron-builder/issues/6530) [#6550](https://github.com/electron-userland/electron-builder/issues/6550)


### Features

* add `beforePack` hook ([#6176](https://github.com/electron-userland/electron-builder/issues/6176)) ([6f42f64](https://github.com/electron-userland/electron-builder/commit/6f42f646c9d36405c9d69ca45dda51baabdec4bd))
* add afterPack call after macOS universal package is created ([#6887](https://github.com/electron-userland/electron-builder/issues/6887)) ([4d590d3](https://github.com/electron-userland/electron-builder/commit/4d590d302f6c3baacf9dabf338904fef337960a6))
* add custom download completed notification ([#4952](https://github.com/electron-userland/electron-builder/issues/4952)) ([3ffea83](https://github.com/electron-userland/electron-builder/commit/3ffea83eaf399a6cab0db460f9777fea4e1631bd))
* add custom macro for checking uninstallation results ([#5712](https://github.com/electron-userland/electron-builder/issues/5712)) ([e425020](https://github.com/electron-userland/electron-builder/commit/e4250206e936dbcad7ddd19f32e7688afce1239e))
* add Electron branding options ([#5727](https://github.com/electron-userland/electron-builder/issues/5727)) ([0de5f1f](https://github.com/electron-userland/electron-builder/commit/0de5f1f7d4496462726d1305ad0aeec43d337c30))
* Add installDir property for NsisUpdater ([#6907](https://github.com/electron-userland/electron-builder/issues/6907)) ([e7f2867](https://github.com/electron-userland/electron-builder/commit/e7f286776643823f9c906738aade1d71eb1bdd9c))
* add nsis option `removeDefaultUninstallWelcomePage` to remove the default uninstall welcome page ([#7141](https://github.com/electron-userland/electron-builder/issues/7141)) ([d71a579](https://github.com/electron-userland/electron-builder/commit/d71a5790a94cd56b6e033b656b4892ec31f14b9d))
* add option removePackageKeywords ([#5814](https://github.com/electron-userland/electron-builder/issues/5814)) ([dcf570f](https://github.com/electron-userland/electron-builder/commit/dcf570f5fedbd26e33fa58d8926609918b43b9a1))
* add support for executableName to non-Linux Platforms ([#5409](https://github.com/electron-userland/electron-builder/issues/5409)) ([106b680](https://github.com/electron-userland/electron-builder/commit/106b68010f2daa0fb7d370c889b4a5494fa2887f))
* added support for shortVersion and shortVersionWindows strings in package.json ([#4517](https://github.com/electron-userland/electron-builder/issues/4517)) ([71726a7](https://github.com/electron-userland/electron-builder/commit/71726a7849e2960884f0874003a3071e0e9713e3))
* adding Bitbucket publisher and autoupdater ([#6228](https://github.com/electron-userland/electron-builder/issues/6228)) ([a945321](https://github.com/electron-userland/electron-builder/commit/a94532164709a545c0f6551fdc336dbc5377bda8))
* Adding Keygen as an official publisher/updater for electron-builder ([#6167](https://github.com/electron-userland/electron-builder/issues/6167)) ([f45110c](https://github.com/electron-userland/electron-builder/commit/f45110cbf66572d5748d21fc24dc26cabd06f35f))
* Adding timeout to publisher config for api requests and uploads ([#7028](https://github.com/electron-userland/electron-builder/issues/7028)) ([e7179b5](https://github.com/electron-userland/electron-builder/commit/e7179b57bdba192acfdb439c03099e6629e98f6a))
* allow custom makensis and nsis logging ([#6024](https://github.com/electron-userland/electron-builder/issues/6024)) ([a99a7c8](https://github.com/electron-userland/electron-builder/commit/a99a7c87ffd7ffaaa5fae1a17f731a59aac60581)), closes [#5119](https://github.com/electron-userland/electron-builder/issues/5119)
* allow customization of bundleIdentifier for the new Electron 6+ renderer processes ([#4692](https://github.com/electron-userland/electron-builder/issues/4692)) ([8b1cebc](https://github.com/electron-userland/electron-builder/commit/8b1cebca3cc2e076c1bb95687938cfbecad4334b)), closes [#4691](https://github.com/electron-userland/electron-builder/issues/4691)
* allow python path to be configurable ([#5894](https://github.com/electron-userland/electron-builder/issues/5894)) ([529670d](https://github.com/electron-userland/electron-builder/commit/529670d5cebb1dc21cfdf129a68d38f36fb15f40)), closes [#5889](https://github.com/electron-userland/electron-builder/issues/5889)
* Allow specifying additional WiX compiler options ([#5813](https://github.com/electron-userland/electron-builder/issues/5813)) ([4e2909c](https://github.com/electron-userland/electron-builder/commit/4e2909cdf56aabd11330dc55f57993efadf55d87))
* Allow the AppUpdater to be forced into dev mode, allowing it to be activated when the app is not packaged ([#7117](https://github.com/electron-userland/electron-builder/issues/7117)) ([0c52841](https://github.com/electron-userland/electron-builder/commit/0c528411fb8a7de23e974f44e36c5e69bd3bb167))
* **app-builder-lib:** the pkg interface adds the must-close attribute ([#4380](https://github.com/electron-userland/electron-builder/issues/4380)) ([#4382](https://github.com/electron-userland/electron-builder/issues/4382)) ([4d88848](https://github.com/electron-userland/electron-builder/commit/4d8884867b66018cd97481a7759b39d11fe0e378))
* **appimage:** remove desktop integration in favour of AppImageLauncher ([eb27d9c](https://github.com/electron-userland/electron-builder/commit/eb27d9c5802af0a90507df77846b426c8046e0a7))
* Apple Silicon Universal Support ([#5481](https://github.com/electron-userland/electron-builder/issues/5481)) ([ca20151](https://github.com/electron-userland/electron-builder/commit/ca20151c3416324d2413f451dea0c9e3853bab79))
* **appx:** add support for custom extensions in appmanifest.xml ([6d7b25c](https://github.com/electron-userland/electron-builder/commit/6d7b25cf7c3ec89273b01d9b24003851b76a26c6)), closes [#4707](https://github.com/electron-userland/electron-builder/issues/4707)
* **appx:** add support for modifying .appx manifest ([#4613](https://github.com/electron-userland/electron-builder/issues/4613)) ([d5d21da](https://github.com/electron-userland/electron-builder/commit/d5d21da12f5efaf02659ce8d32c48440f6cf91ff))
* **appx:** added missing support for AppX fileAssociations ([#4302](https://github.com/electron-userland/electron-builder/issues/4302)) ([b16a890](https://github.com/electron-userland/electron-builder/commit/b16a89014adcd01e492670c3976dcf105e77a284))
* build additional arch-specific nsis installers when ${arch} template is provided ([#5718](https://github.com/electron-userland/electron-builder/issues/5718)) ([7194c38](https://github.com/electron-userland/electron-builder/commit/7194c388f64cf9074e7ae14e74a7783da76ea284))
* clear error if rpmbuild is not installed, update deps for deb and rpm ([c605b6a](https://github.com/electron-userland/electron-builder/commit/c605b6ad1f787550d0088eafc11a678cf617de54))
* Custom electronDist callback ([#5527](https://github.com/electron-userland/electron-builder/issues/5527)) ([4f4e018](https://github.com/electron-userland/electron-builder/commit/4f4e0187715a57a358ab8ccfefef3fd0f8186584))
* **docker:** update nodejs to 14.17.0 ([#5900](https://github.com/electron-userland/electron-builder/issues/5900)) ([f53fa7f](https://github.com/electron-userland/electron-builder/commit/f53fa7fc2f3ead90a5fb075e5087bd7ea78a297f))
* **docker:** update to Ubuntu 20.04 LTS ([#5855](https://github.com/electron-userland/electron-builder/issues/5855)) ([ca81c65](https://github.com/electron-userland/electron-builder/commit/ca81c6502e8def93e2178d34b767647a445819cc))
* **electron-updater:** allow custom update providers ([#5984](https://github.com/electron-userland/electron-builder/issues/5984)) ([86a538b](https://github.com/electron-userland/electron-builder/commit/86a538b9b8bed87628772174c66e40aa7dcb4a99)), closes [#3656](https://github.com/electron-userland/electron-builder/issues/3656)
* **electron-updater:** export updaters for configurability ([#4250](https://github.com/electron-userland/electron-builder/issues/4250)) ([9df845e](https://github.com/electron-userland/electron-builder/commit/9df845e30180fc984e7098f3ed3d3b0fa9415558))
* **electron-updater:** follow `autoInstallOnAppQuit = false` on macOS ([#5271](https://github.com/electron-userland/electron-builder/issues/5271)) ([1643d56](https://github.com/electron-userland/electron-builder/commit/1643d569600a197858585e895e3176948d3eec85))
* electron/universal has a new minimatch option 'x64ArchFiles' ([#6913](https://github.com/electron-userland/electron-builder/issues/6913)) ([f3a56ef](https://github.com/electron-userland/electron-builder/commit/f3a56ef6f8132e0a7cc18ec58d1d6103683916dd))
* **linux:** add fileAssociation support for fpm target ([c11fa1f](https://github.com/electron-userland/electron-builder/commit/c11fa1f1033aeb7c378856d7db93369282d363f5))
* **linux:** add slots option for snap builds ([#5047](https://github.com/electron-userland/electron-builder/issues/5047)) ([e87bd28](https://github.com/electron-userland/electron-builder/commit/e87bd281cf27c0f86cb0f2541033b96fcb1bc64d))
* **linux:** Package name can be specified using packageName option ([#5530](https://github.com/electron-userland/electron-builder/issues/5530)) ([#5588](https://github.com/electron-userland/electron-builder/issues/5588)) ([622aaef](https://github.com/electron-userland/electron-builder/commit/622aaefd1537f0bfdcf15fc6204b3eea97dc64ce))
* **linux:** support to set executableArgs in linux config ([#4364](https://github.com/electron-userland/electron-builder/issues/4364)) ([7cf6894](https://github.com/electron-userland/electron-builder/commit/7cf6894c0be7781e3e714987cdcb2e0b4d939d2d))
* **mac:** add loginhelper entitlement option ([#5023](https://github.com/electron-userland/electron-builder/issues/5023)) ([7109e88](https://github.com/electron-userland/electron-builder/commit/7109e88e7fc0200185c23b27944eb340f132a319))
* **mac:** add LSHandlerRank ([5129266](https://github.com/electron-userland/electron-builder/commit/512926648068deaab8d0a2ce8085ab63de999412)), closes [#4614](https://github.com/electron-userland/electron-builder/issues/4614)
* **mac:** Add timestamp authority server to osx-sign options ([#6074](https://github.com/electron-userland/electron-builder/issues/6074)) ([41cb248](https://github.com/electron-userland/electron-builder/commit/41cb24869381de73a9663a17ec91d2747e099cf9))
* macOS default architecture ([#5495](https://github.com/electron-userland/electron-builder/issues/5495)) ([#5504](https://github.com/electron-userland/electron-builder/issues/5504)) ([5203d7e](https://github.com/electron-userland/electron-builder/commit/5203d7eb15726605e8987aeed7a5ccedc8152e04))
* **mac:** set hardenedRuntime to true by default, set gatekeeper-assess by default to false ([c8c37f2](https://github.com/electron-userland/electron-builder/commit/c8c37f20c624e5d73298d6bfa02660bb03ccbcea)), closes [#3383](https://github.com/electron-userland/electron-builder/issues/3383)
* **mac:** supplying a value for the ‘ignore’ electron-osx-sign property ([aa3625d](https://github.com/electron-userland/electron-builder/commit/aa3625d5f6b719b6a7634c4c7ba0aad1ffe7d3d6)), closes [#5262](https://github.com/electron-userland/electron-builder/issues/5262)
* make `--no-sandbox` optional for building with AppImage ([#6429](https://github.com/electron-userland/electron-builder/issues/6429)) ([e95afc1](https://github.com/electron-userland/electron-builder/commit/e95afc1ab8c1a09fc8c9496084fc9f49b185469e))
* Make electron-builder compatible with electron-nightly. ([#4473](https://github.com/electron-userland/electron-builder/issues/4473)) ([35bff8c](https://github.com/electron-userland/electron-builder/commit/35bff8cb87ba5d92687853604b751cfb7abc77bc)), closes [#1](https://github.com/electron-userland/electron-builder/issues/1)
* make it possible to ignore release time when publish to github ([#5179](https://github.com/electron-userland/electron-builder/issues/5179)) ([fca50ae](https://github.com/electron-userland/electron-builder/commit/fca50aea42fc054b87bbe943bbe5c1c235a186e1))
* **mas:** Apple Silicon support ([#5484](https://github.com/electron-userland/electron-builder/issues/5484)) ([6b7d305](https://github.com/electron-userland/electron-builder/commit/6b7d30555d8f88a3a908a25adb3e8836ccdf5bc8))
* NSIS uninstaller reader ([#4305](https://github.com/electron-userland/electron-builder/issues/4305)) ([#4355](https://github.com/electron-userland/electron-builder/issues/4355)) ([6443179](https://github.com/electron-userland/electron-builder/commit/64431790c1f0483a5094ce962efd3b4bffaab2ec))
* NSIS uninstaller uncompressed support ([#4305](https://github.com/electron-userland/electron-builder/issues/4305)) ([#4415](https://github.com/electron-userland/electron-builder/issues/4415)) ([eb32b22](https://github.com/electron-userland/electron-builder/commit/eb32b227e659eba62c308bf28ff59803d2c434d8))
* **nsis:** add new interface to show custom page after change installation directory and before install start, like other running options. ([#4219](https://github.com/electron-userland/electron-builder/issues/4219)) ([a9a4c53](https://github.com/electron-userland/electron-builder/commit/a9a4c53d3182bc0e2a504331429976afe778a3d0))
* **nsis:** czech language for nsis scripts ([#5270](https://github.com/electron-userland/electron-builder/issues/5270)) ([16c81a0](https://github.com/electron-userland/electron-builder/commit/16c81a098b90def5f302618d8207c123c2a88dbb))
* **nsis:** traditional Chinese version of messages during installation ([#4571](https://github.com/electron-userland/electron-builder/issues/4571)) ([bc68444](https://github.com/electron-userland/electron-builder/commit/bc68444e1dd9a1a4d905a659ee9f9980713201e3))
* **nsis:** update to 3.0.5 ([071cf47](https://github.com/electron-userland/electron-builder/commit/071cf47da102f32a106c34bf236bbb704515990f))
* **nsis:** Windows on ARM support ([#4228](https://github.com/electron-userland/electron-builder/issues/4228)) ([d738644](https://github.com/electron-userland/electron-builder/commit/d738644d6e55b027c81e9b7cdd27dc5af9189b0a))
* on macOS and windows build x64 snap and appimage regardless of machine arch ([72dd264](https://github.com/electron-userland/electron-builder/commit/72dd264b4e545070b88affcc7653a6546b562869))
* **portable:** adding splash image to portable nsis package ([91e6183](https://github.com/electron-userland/electron-builder/commit/91e6183bfd27191083872bcf07a0db51f9470e1e)), closes [#4425](https://github.com/electron-userland/electron-builder/issues/4425)
* **portable:** Adding support for unique dir on each portable app launch ([#6093](https://github.com/electron-userland/electron-builder/issues/6093)) ([f8e16db](https://github.com/electron-userland/electron-builder/commit/f8e16db5393f663724e9c03ceab87698a252c934)), closes [#5764](https://github.com/electron-userland/electron-builder/issues/5764) [#5382](https://github.com/electron-userland/electron-builder/issues/5382) [#4105](https://github.com/electron-userland/electron-builder/issues/4105)
* rebuild native node modules using prebuild-install directly if possible, do not build from sources if paltform/arch is not compatible ([d55e830](https://github.com/electron-userland/electron-builder/commit/d55e8301eb718cff5ebfe1b367f7fd8208d83e9f))
* **snap:** ability to specify slot properties ([#5313](https://github.com/electron-userland/electron-builder/issues/5313)) ([1235c4e](https://github.com/electron-userland/electron-builder/commit/1235c4e4b372fef90409d8f60ea9886e41ffdb87))
* **snap:** add appPartStage and layout options for Snap Store ([#5073](https://github.com/electron-userland/electron-builder/issues/5073)) ([ff117bc](https://github.com/electron-userland/electron-builder/commit/ff117bc81904b5219b84ec2cfc464d7c99c8e90c))
* **snap:** add Snap `title` option ([#5350](https://github.com/electron-userland/electron-builder/issues/5350)) ([2801de7](https://github.com/electron-userland/electron-builder/commit/2801de7f6c8cc5a89534d983f39807f21e0cc94f))
* **snap:** add support for snap autostart option ([#4237](https://github.com/electron-userland/electron-builder/issues/4237)) ([9a5b950](https://github.com/electron-userland/electron-builder/commit/9a5b95058b40b12fdcf9df5089d16535806cfe75))
* **snap:** electron 5 support ([66b1225](https://github.com/electron-userland/electron-builder/commit/66b1225ab67cb9778c973c2a626ceffff12ec4c3)), closes [#3872](https://github.com/electron-userland/electron-builder/issues/3872) [#3923](https://github.com/electron-userland/electron-builder/issues/3923)
* **snap:** electron 5 support (part 2) ([48f5878](https://github.com/electron-userland/electron-builder/commit/48f58788693ae664035862bdb7d120fead3732a1)), closes [#3701](https://github.com/electron-userland/electron-builder/issues/3701) [#3677](https://github.com/electron-userland/electron-builder/issues/3677) [#3608](https://github.com/electron-userland/electron-builder/issues/3608) [#3326](https://github.com/electron-userland/electron-builder/issues/3326) [#2887](https://github.com/electron-userland/electron-builder/issues/2887)
* **snap:** publishing to Snapcraft ([ff242ab](https://github.com/electron-userland/electron-builder/commit/ff242ab865f65987da4d95183a99c6fbaa7d3b78)), closes [#3187](https://github.com/electron-userland/electron-builder/issues/3187)
* **snap:** template for armhf (arm 32-bit) ([6853b37](https://github.com/electron-userland/electron-builder/commit/6853b37b321bbf34b3bd6c9ec7ff88545b37291f))
* support nested node_modules ([#4371](https://github.com/electron-userland/electron-builder/issues/4371)) ([e9c70d5](https://github.com/electron-userland/electron-builder/commit/e9c70d50bb3b824e6ffe99965ec6acede55d2844)), closes [#4366](https://github.com/electron-userland/electron-builder/issues/4366)
* support resolving of `latest` version for electron-nightly ([244abfb](https://github.com/electron-userland/electron-builder/commit/244abfbaaed2999bdf2c7ae688f7db99c1cba2c2))
* unpack electron on remote server ([76b92e0](https://github.com/electron-userland/electron-builder/commit/76b92e0a928e7f93212089954a1eb66366920d6d))
* update rcedit, use rcedit x64 on Windows x64 ([5cb085d](https://github.com/electron-userland/electron-builder/commit/5cb085de5cabd3cc6335d79fcc0caeb3c7993b4a)), closes [#3889](https://github.com/electron-userland/electron-builder/issues/3889)
* **updater:** Add Channel Support for Github with PreRelease ([#6505](https://github.com/electron-userland/electron-builder/issues/6505)) ([#1722](https://github.com/electron-userland/electron-builder/issues/1722)) ([#4988](https://github.com/electron-userland/electron-builder/issues/4988)) ([1de0adb](https://github.com/electron-userland/electron-builder/commit/1de0adbd615b3b3d26faeb6a449f522355b36041))
* Upgrade docker images to Ubuntu 22.04 and python 3.10 ([#6922](https://github.com/electron-userland/electron-builder/issues/6922)) ([03cc9b9](https://github.com/electron-userland/electron-builder/commit/03cc9b96e0be07ef3450e3992eafcb7fe903a853))
* upgrade keygen integration to v1.1 ([#6941](https://github.com/electron-userland/electron-builder/issues/6941)) ([14503ce](https://github.com/electron-userland/electron-builder/commit/14503ceb99c1a31c54a261a1ae60a34980f36a50))
* use `mergeASARs` API by @electron/universal ([#6578](https://github.com/electron-userland/electron-builder/issues/6578)) ([81132a8](https://github.com/electron-userland/electron-builder/commit/81132a857b24bfdb01fc44eba75fc89fa2885545))
* Use tar instead of 7zip to preserve file permissions in tar.gz packages ([#6791](https://github.com/electron-userland/electron-builder/issues/6791)) ([95910f8](https://github.com/electron-userland/electron-builder/commit/95910f87195f501eadda95c52cfa8e1816d211b6))
* win custom sign should have same signature of doSign ([#4833](https://github.com/electron-userland/electron-builder/issues/4833)) ([f938de5](https://github.com/electron-userland/electron-builder/commit/f938de5aae09cb832a6f7f742e64a0d6c025fb9f))


### Reverts

* Revert "fix: codesign all binary-like files (#5322)" (#5488) ([0262278](https://github.com/electron-userland/electron-builder/commit/026227888f8c537855abf6d6aa2141a692a6bc8e)), closes [#5322](https://github.com/electron-userland/electron-builder/issues/5322) [#5488](https://github.com/electron-userland/electron-builder/issues/5488)
* Revert "fix: Update BintrayProvider.ts (#4921)" (#4973) ([ee59eed](https://github.com/electron-userland/electron-builder/commit/ee59eed4b48eff87786715a30d1865d9186c24d9)), closes [#4921](https://github.com/electron-userland/electron-builder/issues/4921) [#4973](https://github.com/electron-userland/electron-builder/issues/4973)
* Revert "fix(nsis): NSIS Uninstaller registry entry format change (#4069)" (#4443) ([b8d6905](https://github.com/electron-userland/electron-builder/commit/b8d6905582b28a9b36f11308f9a72ebc32dc2c86)), closes [#4069](https://github.com/electron-userland/electron-builder/issues/4069) [#4443](https://github.com/electron-userland/electron-builder/issues/4443)
* Revert "fix(appx): App sandbox not enabled (ITMS-90296) (#4244)" (#4414) ([d55f880](https://github.com/electron-userland/electron-builder/commit/d55f8803034afe594c875b5aed8d4b29b510f1f7)), closes [#4244](https://github.com/electron-userland/electron-builder/issues/4244) [#4414](https://github.com/electron-userland/electron-builder/issues/4414)


### BREAKING CHANGES

* Removing Bintray support since it was sunset. Ref: https://jfrog.com/blog/into-the-sunset-bintray-jcenter-gocenter-and-chartcenter/

* fix: force strip path separators for backslashes on Windows

* fix: Force authentication for local Mac Squirrel update server
* Fail-fast for signature verification failures. Adding `-LiteralPath` to update file for injected wildcards

* Adding changeset and eslint

* Fix error: `-OUTPUTCHARSET is disabled for non Win32 platforms.`
* Admins using advertisement must apply an MST to re-enable it. See #6508.
* remove MSI option `iconId`

* fix: stabilizing tests by moving updater tests to its own node to explicitly segment env.___TOKEN integration tests from other standard unit tests

* chore: synchronizing docs and schema plus prettier

* Adding changset to set as alpha

* Updating changeset documentation



# [](https://github.com/electron-userland/electron-builder/compare/v23.5.0...v) (2022-09-08)


### Bug Fixes

* allow CSC_LINK to have a mime-type prefix before extracting it to a p12 ([#7119](https://github.com/electron-userland/electron-builder/issues/7119)) ([323618f](https://github.com/electron-userland/electron-builder/commit/323618f79108a8bb829dc1e84e933ace90940010))
* **docs:** typo of docs/generated/NsisOptions.md ([#7120](https://github.com/electron-userland/electron-builder/issues/7120)) ([740c411](https://github.com/electron-userland/electron-builder/commit/740c41146f875feaa730d18f8353b11416dab1e0))
* Revert "feat: Upgrade to Ubuntu 22.04 and python 3.10" ([#7109](https://github.com/electron-userland/electron-builder/issues/7109)) ([7d606af](https://github.com/electron-userland/electron-builder/commit/7d606aff59c964dc0af93c0f235abb0f3e258dea))
* strip extra fields out that are not allowed when creating snap.yaml ([#7104](https://github.com/electron-userland/electron-builder/issues/7104)) ([#7110](https://github.com/electron-userland/electron-builder/issues/7110)) ([0a7025e](https://github.com/electron-userland/electron-builder/commit/0a7025e5184e3333d077db1f7e782d6a768ecdea))


### Features

* Allow the AppUpdater to be forced into dev mode, allowing it to be activated when the app is not packaged ([#7117](https://github.com/electron-userland/electron-builder/issues/7117)) ([0c52841](https://github.com/electron-userland/electron-builder/commit/0c528411fb8a7de23e974f44e36c5e69bd3bb167))



# [](https://github.com/electron-userland/electron-builder/compare/v23.4.0...v) (2022-08-31)


### Bug Fixes

* allow user to define explicit `buildNumber` in config, useful for fpm `--iteration` flag ([#7075](https://github.com/electron-userland/electron-builder/issues/7075)) ([8166267](https://github.com/electron-userland/electron-builder/commit/8166267d487cd26b154e28cf60d89102a487a353))
* close file stream when error in httpExecutor ([#7094](https://github.com/electron-userland/electron-builder/issues/7094)) ([1023a93](https://github.com/electron-userland/electron-builder/commit/1023a93e92eaa26bf33b52edda5b22e56ed1ec18))
* improve `downloadUpdate` typing to match the doc ([#7099](https://github.com/electron-userland/electron-builder/issues/7099)) ([cd21b09](https://github.com/electron-userland/electron-builder/commit/cd21b0918843fe1269ddaf8dde099c8faeb54b80))
* Invalid code signing for MAS build due to ordering of certificate check ([#7040](https://github.com/electron-userland/electron-builder/issues/7040)) ([#7089](https://github.com/electron-userland/electron-builder/issues/7089)) ([a1d86fd](https://github.com/electron-userland/electron-builder/commit/a1d86fd75bbc7b252403c16966430a2e3562205d))
* replace update-notifier with simple-update notifier due to dependency vulnerability ([#7078](https://github.com/electron-userland/electron-builder/issues/7078)) ([48cbb12](https://github.com/electron-userland/electron-builder/commit/48cbb120dc11994889f4aa61c8431531ce274006))
* updating integration test for prerelease flag ([#7072](https://github.com/electron-userland/electron-builder/issues/7072)) ([f205998](https://github.com/electron-userland/electron-builder/commit/f205998999ff615c9ea63184520a1efbbff5a785))



# [](https://github.com/electron-userland/electron-builder/compare/v23.3.3...v) (2022-07-28)


### Features

* Adding timeout to publisher config for api requests and uploads ([#7028](https://github.com/electron-userland/electron-builder/issues/7028)) ([e7179b5](https://github.com/electron-userland/electron-builder/commit/e7179b57bdba192acfdb439c03099e6629e98f6a))



# [](https://github.com/electron-userland/electron-builder/compare/v23.3.2...v) (2022-07-21)


### Bug Fixes

* Duplicate values during deep assign of extra files ([#7019](https://github.com/electron-userland/electron-builder/issues/7019)) ([98d3a63](https://github.com/electron-userland/electron-builder/commit/98d3a6361d500e85e443ee292529c27f0b4a0b59))



# [](https://github.com/electron-userland/electron-builder/compare/v23.3.1...v) (2022-07-16)


### Bug Fixes

* **electron-updater:** fix backward compatibility for GitHub provider without channels ([#6998](https://github.com/electron-userland/electron-builder/issues/6998)) ([d6115bc](https://github.com/electron-userland/electron-builder/commit/d6115bc5d066d6eee2638015be0c804b31ffcc18))
* Wrap the nsProcess include in a !ifndef ([#6996](https://github.com/electron-userland/electron-builder/issues/6996)) ([5301525](https://github.com/electron-userland/electron-builder/commit/53015253939f450468a6d8e0405697ea70c2a138))



# [](https://github.com/electron-userland/electron-builder/compare/v23.3.0...v) (2022-07-07)


### Bug Fixes

* add product scope to keygen publisher ([#6990](https://github.com/electron-userland/electron-builder/issues/6990)) ([c3407a2](https://github.com/electron-userland/electron-builder/commit/c3407a202d4dc1599b2cb90a7ff3d56e8e32309e))
* parallel release creation with keygen publisher ([#6989](https://github.com/electron-userland/electron-builder/issues/6989)) ([7ad5101](https://github.com/electron-userland/electron-builder/commit/7ad5101b4a72df411b76cc500a6a0dca85bf6540))


### Features

* Add installDir property for NsisUpdater ([#6907](https://github.com/electron-userland/electron-builder/issues/6907)) ([e7f2867](https://github.com/electron-userland/electron-builder/commit/e7f286776643823f9c906738aade1d71eb1bdd9c))



# [](https://github.com/electron-userland/electron-builder/compare/v23.2.0...v) (2022-07-04)


### Bug Fixes

* add product scope to keygen provider ([#6975](https://github.com/electron-userland/electron-builder/issues/6975)) ([8279d05](https://github.com/electron-userland/electron-builder/commit/8279d053d520e7506d84bf9710972b998e70b752))
* automatically regenerate schema if any config option changes in app-builder-lib ([51f5d49](https://github.com/electron-userland/electron-builder/commit/51f5d4915c4aa69f3253a41e1d7b4ab9f2328732))
* **mac:** allow Mac Developer certs for non Mac App Store builds ([#6956](https://github.com/electron-userland/electron-builder/issues/6956)) ([4e90504](https://github.com/electron-userland/electron-builder/commit/4e905046e632b396735b78618fbc01331448f088)), closes [#6564](https://github.com/electron-userland/electron-builder/issues/6564)
* **mas:** Allow signing with "3rd Party Mac Developer Application" ([#6970](https://github.com/electron-userland/electron-builder/issues/6970)) ([28c07b4](https://github.com/electron-userland/electron-builder/commit/28c07b4392161732ee221dbb3f3a3633899cfa33))
* nsis-web target set APP_PACKAGE_URL_IS_INCOMPLETE when specifying appPackageUrl ([#6964](https://github.com/electron-userland/electron-builder/issues/6964)) ([b0e1b6f](https://github.com/electron-userland/electron-builder/commit/b0e1b6f8af95bc371c0bc91df65965f3f60f3a87))
* **nsis:** fix typo in German installer message ([#6960](https://github.com/electron-userland/electron-builder/issues/6960)) ([6e90c84](https://github.com/electron-userland/electron-builder/commit/6e90c8459111ec046b91f8ae5da1990af0bbe942))
* Optionally remove DISABLE_WAYLAND for snaps via allowNativeWayland option ([#6961](https://github.com/electron-userland/electron-builder/issues/6961)) ([4c867aa](https://github.com/electron-userland/electron-builder/commit/4c867aa017a7ce2bf88138634b6d1e9a3bf34854))
* prevent infinite looping of overwriteArtifact during Github publishing ([#6958](https://github.com/electron-userland/electron-builder/issues/6958)) ([8ffd9d4](https://github.com/electron-userland/electron-builder/commit/8ffd9d42d89634be76fd4554f659f2b2512f2081))
* regenerating docs and schema ([f70abf1](https://github.com/electron-userland/electron-builder/commit/f70abf1628223e1cc0d687471ad36b4a2ee66ebe))
* regenerating schema to account for electron-universal options `x64ArchFiles` ([#6983](https://github.com/electron-userland/electron-builder/issues/6983)) ([adeaa34](https://github.com/electron-userland/electron-builder/commit/adeaa347c03b8947b0812ecef23398c0822646bb))


### Features

* upgrade keygen integration to v1.1 ([#6941](https://github.com/electron-userland/electron-builder/issues/6941)) ([14503ce](https://github.com/electron-userland/electron-builder/commit/14503ceb99c1a31c54a261a1ae60a34980f36a50))



# [](https://github.com/electron-userland/electron-builder/compare/v23.1.0...v) (2022-06-17)


### Bug Fixes

* pin Keygen.io integration to v1.0 ([#6909](https://github.com/electron-userland/electron-builder/issues/6909)) ([0b6db59](https://github.com/electron-userland/electron-builder/commit/0b6db59ec10dfe05903f29d6790972f55746bef7))


### Features

* electron/universal has a new minimatch option 'x64ArchFiles' ([#6913](https://github.com/electron-userland/electron-builder/issues/6913)) ([f3a56ef](https://github.com/electron-userland/electron-builder/commit/f3a56ef6f8132e0a7cc18ec58d1d6103683916dd))
* Upgrade docker images to Ubuntu 22.04 and python 3.10 ([#6922](https://github.com/electron-userland/electron-builder/issues/6922)) ([03cc9b9](https://github.com/electron-userland/electron-builder/commit/03cc9b96e0be07ef3450e3992eafcb7fe903a853))



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.9...v) (2022-05-29)


### Bug Fixes

* moving typed-emitter from devDependency to dependencies ([#6889](https://github.com/electron-userland/electron-builder/issues/6889)) ([869ec27](https://github.com/electron-userland/electron-builder/commit/869ec27fd1d99b9913875cb4d7ae7c733c1f3e25))
* **msi:** manually escape XML special characters when building project.wxs XML ([#6878](https://github.com/electron-userland/electron-builder/issues/6878)) ([2ece89a](https://github.com/electron-userland/electron-builder/commit/2ece89a08e7fb74a11ba3d0f5980b2a57c8b34ad))
* **nsis:** new translations for various strings in nsis messages template ([#6827](https://github.com/electron-userland/electron-builder/issues/6827)) ([fa72861](https://github.com/electron-userland/electron-builder/commit/fa72861f6cd2de97d191f1b2bbfddc6edf48ab6d))


### Features

* add afterPack call after macOS universal package is created ([#6887](https://github.com/electron-userland/electron-builder/issues/6887)) ([4d590d3](https://github.com/electron-userland/electron-builder/commit/4d590d302f6c3baacf9dabf338904fef337960a6))



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.8...v) (2022-05-06)


### Bug Fixes

* Add "arm" as an alias for armv7l as process.arch outputs arm on armv7l hosts ([#6845](https://github.com/electron-userland/electron-builder/issues/6845)) ([d3452b0](https://github.com/electron-userland/electron-builder/commit/d3452b0427cb45035f6ed7f1266691db4accd5c4))
* incompatible Windows sign tool in end user environment.  ([#6817](https://github.com/electron-userland/electron-builder/issues/6817)) ([2860d13](https://github.com/electron-userland/electron-builder/commit/2860d132fc837813627e6508e05b18ed5e5dedfc))
* Lock wine version to v6 in docker image ([#6816](https://github.com/electron-userland/electron-builder/issues/6816)) ([8f57a90](https://github.com/electron-userland/electron-builder/commit/8f57a90c885254bf442e7eea5b8f450bd400eac4)), closes [#6780](https://github.com/electron-userland/electron-builder/issues/6780)
* Merge arrays from same config key in cascading electron-builder configs, such as `files` ([#6841](https://github.com/electron-userland/electron-builder/issues/6841)) ([9dc13ba](https://github.com/electron-userland/electron-builder/commit/9dc13ba2c1e7a852d3f743833f1bde17b62f1806))
* rendering extended node_modules in jsdoc ([#6843](https://github.com/electron-userland/electron-builder/issues/6843)) ([481a7ed](https://github.com/electron-userland/electron-builder/commit/481a7ed2b77e7e1b448f27e58fedeac53b107ffc))
* set github release name to match the app version ([#6840](https://github.com/electron-userland/electron-builder/issues/6840)) ([e9ba750](https://github.com/electron-userland/electron-builder/commit/e9ba75005dda39f03c04e37a5d46a1bbe634c189))
* Unable to find latest version on GitHub ([#6822](https://github.com/electron-userland/electron-builder/issues/6822)) ([bfe29a5](https://github.com/electron-userland/electron-builder/commit/bfe29a5e991c2719032877bd7225b15b6b836221))



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.7...v) (2022-04-24)


### Bug Fixes

* github provider prerelease check incorrectly casts undefined to String. Fixes [#6809](https://github.com/electron-userland/electron-builder/issues/6809) ([#6810](https://github.com/electron-userland/electron-builder/issues/6810)) ([817e68b](https://github.com/electron-userland/electron-builder/commit/817e68ba54f4fa60fec789fcfcfb527473a610fc))



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.6...v) (2022-04-19)


### Bug Fixes

* **nsis:** cleanup temporary 7z folder ([#6793](https://github.com/electron-userland/electron-builder/issues/6793)) ([85a3e55](https://github.com/electron-userland/electron-builder/commit/85a3e5595e64346514dd7f5fade42e3632a18ee0))
* **nsis:** Decide to use elevate.exe for installer when update using nsis packElevateHelper option in electron-builder config ([#6787](https://github.com/electron-userland/electron-builder/issues/6787)) ([eb456a8](https://github.com/electron-userland/electron-builder/commit/eb456a87b0603dcc0e6d777c2b8e1c2e7b64d3a6))


### Features

* Use tar instead of 7zip to preserve file permissions in tar.gz packages ([#6791](https://github.com/electron-userland/electron-builder/issues/6791)) ([95910f8](https://github.com/electron-userland/electron-builder/commit/95910f87195f501eadda95c52cfa8e1816d211b6))



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.4...v) (2022-04-13)


### Bug Fixes

* **app-builder-lib:** Overriding OutgoingHttpHeaders schema props ([#6775](https://github.com/electron-userland/electron-builder/issues/6775)) ([e9a87a7](https://github.com/electron-userland/electron-builder/commit/e9a87a738ceb2b9e14cbc85b4c62e11edab3d0cf)), closes [#6635](https://github.com/electron-userland/electron-builder/issues/6635)
* **dmg-builder:** exec python fail on Macos12.3 ([#6789](https://github.com/electron-userland/electron-builder/issues/6789)) ([76f3a1d](https://github.com/electron-userland/electron-builder/commit/76f3a1d102be04c0517a08826b8b1337478f766d))
* **nsis:** Update zh-tw translation ([#6773](https://github.com/electron-userland/electron-builder/issues/6773)) ([5a0bab1](https://github.com/electron-userland/electron-builder/commit/5a0bab115f4ede3f21e23e847c0d2dd7ecc99b16))



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.4...v) (2022-04-11)


### Bug Fixes

* **app-builder-lib:** Overriding OutgoingHttpHeaders schema props ([#6775](https://github.com/electron-userland/electron-builder/issues/6775)) ([e9a87a7](https://github.com/electron-userland/electron-builder/commit/e9a87a738ceb2b9e14cbc85b4c62e11edab3d0cf)), closes [#6635](https://github.com/electron-userland/electron-builder/issues/6635)
* **nsis:** Update zh-tw translation ([#6773](https://github.com/electron-userland/electron-builder/issues/6773)) ([5a0bab1](https://github.com/electron-userland/electron-builder/commit/5a0bab115f4ede3f21e23e847c0d2dd7ecc99b16))



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.3...v) (2022-04-08)


### Bug Fixes

* **app-builder-lib:** bump @electron/universal to 1.2.1 ([#6750](https://github.com/electron-userland/electron-builder/issues/6750)) ([370f84b](https://github.com/electron-userland/electron-builder/commit/370f84bb2f32f28c374b63e1c795e4850f971274))
* **app-builder-lib:** change slash to backslash in NSIS's APP_PACKAGE_NAME ([#6772](https://github.com/electron-userland/electron-builder/issues/6772)) ([e861352](https://github.com/electron-userland/electron-builder/commit/e86135236908961b1269708ca645a66c7ff19287))
* **nsis:** specify full path to system's find ([#6771](https://github.com/electron-userland/electron-builder/issues/6771)) ([e6c2a62](https://github.com/electron-userland/electron-builder/commit/e6c2a629839184d4f9d3fa99b580d8c96911ea65))
* Updater "Error: Could not connect to the server." in macOS ([#6743](https://github.com/electron-userland/electron-builder/issues/6743)) ([27f18aa](https://github.com/electron-userland/electron-builder/commit/27f18aa1d890f3a82e856f4834b8387066fb697f))



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.2...v) (2022-03-19)


### Bug Fixes

* Change DEBUG_LOGGING env var for nsis installers as part of `customNsisBinary` config ([#6729](https://github.com/electron-userland/electron-builder/issues/6729)) ([0a30846](https://github.com/electron-userland/electron-builder/commit/0a308469f269dc5294f29f2c422d9936175c0880)), closes [#6715](https://github.com/electron-userland/electron-builder/issues/6715)
* **docs:** link to SquirrelWindowsOptions in configuration ([#6724](https://github.com/electron-userland/electron-builder/issues/6724)) ([4eaab19](https://github.com/electron-userland/electron-builder/commit/4eaab1936429ac69dafcc7cfbf53caa85c241a11))



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.1...v) (2022-03-05)


### Bug Fixes

* **app-builder-lib:** export missing TS types ([#6692](https://github.com/electron-userland/electron-builder/issues/6692)) ([93181a7](https://github.com/electron-userland/electron-builder/commit/93181a78f2893ea4929aea8878343336931b3a04))
* Reactivating bitbucket integration test for nsis updater ([#6680](https://github.com/electron-userland/electron-builder/issues/6680)) ([6fcd477](https://github.com/electron-userland/electron-builder/commit/6fcd47767af8a95ab018fe0d8a07d2c53a72067d))
* **win:** Include swiftshader in signing directories for windows ([#6682](https://github.com/electron-userland/electron-builder/issues/6682)) ([e6312cb](https://github.com/electron-userland/electron-builder/commit/e6312cb54e5d957289d5c07b506491fcaea9e334))



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.0...v) (2022-02-25)


### Bug Fixes

* **dmg-builder:** the "import" unbound issue for python 2/3 ([#6672](https://github.com/electron-userland/electron-builder/issues/6672)) ([3a4b64a](https://github.com/electron-userland/electron-builder/commit/3a4b64abb58f01e8a80e496b6c4681455b2434ca))
* signing of user-defined binaries on mac when resolved as relative path ([#6660](https://github.com/electron-userland/electron-builder/issues/6660)) ([4c6d154](https://github.com/electron-userland/electron-builder/commit/4c6d1546d4942aa9d9a93b7309e8ed279f6378d2))



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.0-alpha.4...v) (2022-02-19)



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.0-alpha.3...v) (2022-02-17)


### Bug Fixes

* **packager:** wait for artifactCreated completion event before starting an upload ([#6625](https://github.com/electron-userland/electron-builder/issues/6625)) ([c561af8](https://github.com/electron-userland/electron-builder/commit/c561af810d5de52bec57709cbaebca2ac92c55fc))



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.0-alpha.2...v) (2022-02-06)


### Bug Fixes

* **dmg-builder:** Support python 3 since python 2 was removed from MacOS 12.3 ([#6617](https://github.com/electron-userland/electron-builder/issues/6617)) ([2def112](https://github.com/electron-userland/electron-builder/commit/2def112bc1ac42046b921206825871b82ebf0955)), closes [#6606](https://github.com/electron-userland/electron-builder/issues/6606)
* **docs:** Fixing formatting of code groups and previews ([#6601](https://github.com/electron-userland/electron-builder/issues/6601)) ([b01d522](https://github.com/electron-userland/electron-builder/commit/b01d5225631115f6f301cb113b044fd10ebb5256)), closes [#6597](https://github.com/electron-userland/electron-builder/issues/6597) [#6574](https://github.com/electron-userland/electron-builder/issues/6574)
* fixes for server auth for MacUpdater ([#6587](https://github.com/electron-userland/electron-builder/issues/6587)) ([8746f91](https://github.com/electron-userland/electron-builder/commit/8746f910d136fb9b531e688d0a646eeb9528adc6))
* **updater:** Remove checks for app-update.yml when auto-updates are not supported ([#6616](https://github.com/electron-userland/electron-builder/issues/6616)) ([86e6d15](https://github.com/electron-userland/electron-builder/commit/86e6d1509f9b9c76c559e9c3a12b7a1595fe3ac4)), closes [#6322](https://github.com/electron-userland/electron-builder/issues/6322)
* **updater:** Support Electron 11 and below (Node < 14) ([#6594](https://github.com/electron-userland/electron-builder/issues/6594)) ([edc4b03](https://github.com/electron-userland/electron-builder/commit/edc4b030703ee3929b31608a496798635169f5b1)), closes [#6000](https://github.com/electron-userland/electron-builder/issues/6000)
* **win/mac:** Small security fixes for electron-updater ([#6589](https://github.com/electron-userland/electron-builder/issues/6589)) ([633ee5d](https://github.com/electron-userland/electron-builder/commit/633ee5dc292174ed1486c53af93320f20cf02169))


### Features

* **updater:** Add Channel Support for Github with PreRelease ([#6505](https://github.com/electron-userland/electron-builder/issues/6505)) ([#1722](https://github.com/electron-userland/electron-builder/issues/1722)) ([#4988](https://github.com/electron-userland/electron-builder/issues/4988)) ([1de0adb](https://github.com/electron-userland/electron-builder/commit/1de0adbd615b3b3d26faeb6a449f522355b36041))



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.0-alpha.2...v) (2022-01-31)


### Bug Fixes

* fixes for server auth for MacUpdater ([#6587](https://github.com/electron-userland/electron-builder/issues/6587)) ([8746f91](https://github.com/electron-userland/electron-builder/commit/8746f910d136fb9b531e688d0a646eeb9528adc6))
* **updater:** Support Electron 11 and below (Node < 14) ([#6594](https://github.com/electron-userland/electron-builder/issues/6594)) ([edc4b03](https://github.com/electron-userland/electron-builder/commit/edc4b030703ee3929b31608a496798635169f5b1)), closes [#6000](https://github.com/electron-userland/electron-builder/issues/6000)
* **win/mac:** Small security fixes for electron-updater ([#6589](https://github.com/electron-userland/electron-builder/issues/6589)) ([633ee5d](https://github.com/electron-userland/electron-builder/commit/633ee5dc292174ed1486c53af93320f20cf02169))


### Features

* **updater:** Add Channel Support for Github with PreRelease ([#6505](https://github.com/electron-userland/electron-builder/issues/6505)) ([#1722](https://github.com/electron-userland/electron-builder/issues/1722)) ([#4988](https://github.com/electron-userland/electron-builder/issues/4988)) ([1de0adb](https://github.com/electron-userland/electron-builder/commit/1de0adbd615b3b3d26faeb6a449f522355b36041))



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.12...v) (2022-01-28)


### Bug Fixes

* Allow disabling of webinstaller files to avoid confusion with actual installers ([#6575](https://github.com/electron-userland/electron-builder/issues/6575)) ([5e381c5](https://github.com/electron-userland/electron-builder/commit/5e381c556d12ce185bb7ea720380509c1ddc5cf7))
* **docs:** Update link for "Desktop File" ([#6532](https://github.com/electron-userland/electron-builder/issues/6532)) ([cd79c53](https://github.com/electron-userland/electron-builder/commit/cd79c53828759cf19cd361a48ef6fd57fff0e2f1))
* **electron-publish:** socket hang up error 422 issues in github publish ([#6563](https://github.com/electron-userland/electron-builder/issues/6563)) ([39da9ed](https://github.com/electron-userland/electron-builder/commit/39da9edd2df5c147ef2d868f022484a8b2e0466a))
* fixes for server auth for MacUpdater ([#6587](https://github.com/electron-userland/electron-builder/issues/6587)) ([8746f91](https://github.com/electron-userland/electron-builder/commit/8746f910d136fb9b531e688d0a646eeb9528adc6))
* **NSIS:** prevent partial overwrites during `Nsis7z::Extract` ([#6547](https://github.com/electron-userland/electron-builder/issues/6547)) ([bea51d6](https://github.com/electron-userland/electron-builder/commit/bea51d6a8bb828d9b34734908f13b667aa55b0e9))
* **nsis:** use revertible+atomic rmdir on update and add user-confirmed retry loop ([#6551](https://github.com/electron-userland/electron-builder/issues/6551)) ([7b2a5e1](https://github.com/electron-userland/electron-builder/commit/7b2a5e1f19921e9da4aaaea8c01c78740f29f9dd))
* skip unstable installer tests to unblock master CI pipeline ([#6544](https://github.com/electron-userland/electron-builder/issues/6544)) ([5648e05](https://github.com/electron-userland/electron-builder/commit/5648e05a9efa61f81e788ecf538a617df9f65fe1))
* Stub CircleCI config since we can't disable it from dashboard ([#6543](https://github.com/electron-userland/electron-builder/issues/6543)) ([22fb8c6](https://github.com/electron-userland/electron-builder/commit/22fb8c63ac196c61c6b449e6e5e95d91117f8894))
* Update certificate validation on Windows to check full DN ([#6576](https://github.com/electron-userland/electron-builder/issues/6576)) ([53467c7](https://github.com/electron-userland/electron-builder/commit/53467c724dacc11fc270cebaba22f8cf84dff24f))
* use junction in windows to solve Error: EPERM: operation not per… ([#6529](https://github.com/electron-userland/electron-builder/issues/6529)) ([f7b3869](https://github.com/electron-userland/electron-builder/commit/f7b386986ec30f7e4cd3e3f68e078a773940a51c))


### chore

* v23.0.0 alpha ([#6556](https://github.com/electron-userland/electron-builder/issues/6556)) ([a138a86](https://github.com/electron-userland/electron-builder/commit/a138a86fb7b59098f5dac0c0a6b59c034eb9b222)), closes [#4898](https://github.com/electron-userland/electron-builder/issues/4898) [#6232](https://github.com/electron-userland/electron-builder/issues/6232) [#6259](https://github.com/electron-userland/electron-builder/issues/6259) [#6511](https://github.com/electron-userland/electron-builder/issues/6511) [#6506](https://github.com/electron-userland/electron-builder/issues/6506) [#6507](https://github.com/electron-userland/electron-builder/issues/6507) [#6514](https://github.com/electron-userland/electron-builder/issues/6514) [#6508](https://github.com/electron-userland/electron-builder/issues/6508) [#6508](https://github.com/electron-userland/electron-builder/issues/6508) [#3683](https://github.com/electron-userland/electron-builder/issues/3683) [#6201](https://github.com/electron-userland/electron-builder/issues/6201) [#6530](https://github.com/electron-userland/electron-builder/issues/6530) [#6550](https://github.com/electron-userland/electron-builder/issues/6550)


### Features

* **updater:** Add Channel Support for Github with PreRelease ([#6505](https://github.com/electron-userland/electron-builder/issues/6505)) ([#1722](https://github.com/electron-userland/electron-builder/issues/1722)) ([#4988](https://github.com/electron-userland/electron-builder/issues/4988)) ([1de0adb](https://github.com/electron-userland/electron-builder/commit/1de0adbd615b3b3d26faeb6a449f522355b36041))
* use `mergeASARs` API by @electron/universal ([#6578](https://github.com/electron-userland/electron-builder/issues/6578)) ([81132a8](https://github.com/electron-userland/electron-builder/commit/81132a857b24bfdb01fc44eba75fc89fa2885545))


### BREAKING CHANGES

* Removing Bintray support since it was sunset. Ref: https://jfrog.com/blog/into-the-sunset-bintray-jcenter-gocenter-and-chartcenter/

* fix: force strip path separators for backslashes on Windows

* fix: Force authentication for local Mac Squirrel update server
* Fail-fast for signature verification failures. Adding `-LiteralPath` to update file for injected wildcards

* Adding changeset and eslint

* Fix error: `-OUTPUTCHARSET is disabled for non Win32 platforms.`
* Admins using advertisement must apply an MST to re-enable it. See #6508.
* remove MSI option `iconId`

* fix: stabilizing tests by moving updater tests to its own node to explicitly segment env.___TOKEN integration tests from other standard unit tests

* chore: synchronizing docs and schema plus prettier

* Adding changset to set as alpha

* Updating changeset documentation



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.12...v) (2022-01-26)


### Bug Fixes

* Allow disabling of webinstaller files to avoid confusion with actual installers ([#6575](https://github.com/electron-userland/electron-builder/issues/6575)) ([5e381c5](https://github.com/electron-userland/electron-builder/commit/5e381c556d12ce185bb7ea720380509c1ddc5cf7))
* **docs:** Update link for "Desktop File" ([#6532](https://github.com/electron-userland/electron-builder/issues/6532)) ([cd79c53](https://github.com/electron-userland/electron-builder/commit/cd79c53828759cf19cd361a48ef6fd57fff0e2f1))
* **electron-publish:** socket hang up error 422 issues in github publish ([#6563](https://github.com/electron-userland/electron-builder/issues/6563)) ([39da9ed](https://github.com/electron-userland/electron-builder/commit/39da9edd2df5c147ef2d868f022484a8b2e0466a))
* **NSIS:** prevent partial overwrites during `Nsis7z::Extract` ([#6547](https://github.com/electron-userland/electron-builder/issues/6547)) ([bea51d6](https://github.com/electron-userland/electron-builder/commit/bea51d6a8bb828d9b34734908f13b667aa55b0e9))
* **nsis:** use revertible+atomic rmdir on update and add user-confirmed retry loop ([#6551](https://github.com/electron-userland/electron-builder/issues/6551)) ([7b2a5e1](https://github.com/electron-userland/electron-builder/commit/7b2a5e1f19921e9da4aaaea8c01c78740f29f9dd))
* skip unstable installer tests to unblock master CI pipeline ([#6544](https://github.com/electron-userland/electron-builder/issues/6544)) ([5648e05](https://github.com/electron-userland/electron-builder/commit/5648e05a9efa61f81e788ecf538a617df9f65fe1))
* Stub CircleCI config since we can't disable it from dashboard ([#6543](https://github.com/electron-userland/electron-builder/issues/6543)) ([22fb8c6](https://github.com/electron-userland/electron-builder/commit/22fb8c63ac196c61c6b449e6e5e95d91117f8894))
* Update certificate validation on Windows to check full DN ([#6576](https://github.com/electron-userland/electron-builder/issues/6576)) ([53467c7](https://github.com/electron-userland/electron-builder/commit/53467c724dacc11fc270cebaba22f8cf84dff24f))
* use junction in windows to solve Error: EPERM: operation not per… ([#6529](https://github.com/electron-userland/electron-builder/issues/6529)) ([f7b3869](https://github.com/electron-userland/electron-builder/commit/f7b386986ec30f7e4cd3e3f68e078a773940a51c))


### chore

* v23.0.0 alpha ([#6556](https://github.com/electron-userland/electron-builder/issues/6556)) ([a138a86](https://github.com/electron-userland/electron-builder/commit/a138a86fb7b59098f5dac0c0a6b59c034eb9b222)), closes [#4898](https://github.com/electron-userland/electron-builder/issues/4898) [#6232](https://github.com/electron-userland/electron-builder/issues/6232) [#6259](https://github.com/electron-userland/electron-builder/issues/6259) [#6511](https://github.com/electron-userland/electron-builder/issues/6511) [#6506](https://github.com/electron-userland/electron-builder/issues/6506) [#6507](https://github.com/electron-userland/electron-builder/issues/6507) [#6514](https://github.com/electron-userland/electron-builder/issues/6514) [#6508](https://github.com/electron-userland/electron-builder/issues/6508) [#6508](https://github.com/electron-userland/electron-builder/issues/6508) [#3683](https://github.com/electron-userland/electron-builder/issues/3683) [#6201](https://github.com/electron-userland/electron-builder/issues/6201) [#6530](https://github.com/electron-userland/electron-builder/issues/6530) [#6550](https://github.com/electron-userland/electron-builder/issues/6550)


### Features

* use `mergeASARs` API by @electron/universal ([#6578](https://github.com/electron-userland/electron-builder/issues/6578)) ([81132a8](https://github.com/electron-userland/electron-builder/commit/81132a857b24bfdb01fc44eba75fc89fa2885545))


### BREAKING CHANGES

* Removing Bintray support since it was sunset. Ref: https://jfrog.com/blog/into-the-sunset-bintray-jcenter-gocenter-and-chartcenter/

* fix: force strip path separators for backslashes on Windows

* fix: Force authentication for local Mac Squirrel update server
* Fail-fast for signature verification failures. Adding `-LiteralPath` to update file for injected wildcards

* Adding changeset and eslint

* Fix error: `-OUTPUTCHARSET is disabled for non Win32 platforms.`
* Admins using advertisement must apply an MST to re-enable it. See #6508.
* remove MSI option `iconId`

* fix: stabilizing tests by moving updater tests to its own node to explicitly segment env.___TOKEN integration tests from other standard unit tests

* chore: synchronizing docs and schema plus prettier

* Adding changset to set as alpha

* Updating changeset documentation



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.12...v) (2022-01-19)


### Bug Fixes

* **docs:** Update link for "Desktop File" ([#6532](https://github.com/electron-userland/electron-builder/issues/6532)) ([cd79c53](https://github.com/electron-userland/electron-builder/commit/cd79c53828759cf19cd361a48ef6fd57fff0e2f1))
* **electron-publish:** socket hang up error 422 issues in github publish ([#6563](https://github.com/electron-userland/electron-builder/issues/6563)) ([39da9ed](https://github.com/electron-userland/electron-builder/commit/39da9edd2df5c147ef2d868f022484a8b2e0466a))
* **NSIS:** prevent partial overwrites during `Nsis7z::Extract` ([#6547](https://github.com/electron-userland/electron-builder/issues/6547)) ([bea51d6](https://github.com/electron-userland/electron-builder/commit/bea51d6a8bb828d9b34734908f13b667aa55b0e9))
* **nsis:** use revertible+atomic rmdir on update and add user-confirmed retry loop ([#6551](https://github.com/electron-userland/electron-builder/issues/6551)) ([7b2a5e1](https://github.com/electron-userland/electron-builder/commit/7b2a5e1f19921e9da4aaaea8c01c78740f29f9dd))
* skip unstable installer tests to unblock master CI pipeline ([#6544](https://github.com/electron-userland/electron-builder/issues/6544)) ([5648e05](https://github.com/electron-userland/electron-builder/commit/5648e05a9efa61f81e788ecf538a617df9f65fe1))
* Stub CircleCI config since we can't disable it from dashboard ([#6543](https://github.com/electron-userland/electron-builder/issues/6543)) ([22fb8c6](https://github.com/electron-userland/electron-builder/commit/22fb8c63ac196c61c6b449e6e5e95d91117f8894))
* use junction in windows to solve Error: EPERM: operation not per… ([#6529](https://github.com/electron-userland/electron-builder/issues/6529)) ([f7b3869](https://github.com/electron-userland/electron-builder/commit/f7b386986ec30f7e4cd3e3f68e078a773940a51c))


### chore

* v23.0.0 alpha ([#6556](https://github.com/electron-userland/electron-builder/issues/6556)) ([a138a86](https://github.com/electron-userland/electron-builder/commit/a138a86fb7b59098f5dac0c0a6b59c034eb9b222)), closes [#4898](https://github.com/electron-userland/electron-builder/issues/4898) [#6232](https://github.com/electron-userland/electron-builder/issues/6232) [#6259](https://github.com/electron-userland/electron-builder/issues/6259) [#6511](https://github.com/electron-userland/electron-builder/issues/6511) [#6506](https://github.com/electron-userland/electron-builder/issues/6506) [#6507](https://github.com/electron-userland/electron-builder/issues/6507) [#6514](https://github.com/electron-userland/electron-builder/issues/6514) [#6508](https://github.com/electron-userland/electron-builder/issues/6508) [#6508](https://github.com/electron-userland/electron-builder/issues/6508) [#3683](https://github.com/electron-userland/electron-builder/issues/3683) [#6201](https://github.com/electron-userland/electron-builder/issues/6201) [#6530](https://github.com/electron-userland/electron-builder/issues/6530) [#6550](https://github.com/electron-userland/electron-builder/issues/6550)


### BREAKING CHANGES

* Removing Bintray support since it was sunset. Ref: https://jfrog.com/blog/into-the-sunset-bintray-jcenter-gocenter-and-chartcenter/

* fix: force strip path separators for backslashes on Windows

* fix: Force authentication for local Mac Squirrel update server
* Fail-fast for signature verification failures. Adding `-LiteralPath` to update file for injected wildcards

* Adding changeset and eslint

* Fix error: `-OUTPUTCHARSET is disabled for non Win32 platforms.`
* Admins using advertisement must apply an MST to re-enable it. See #6508.
* remove MSI option `iconId`

* fix: stabilizing tests by moving updater tests to its own node to explicitly segment env.___TOKEN integration tests from other standard unit tests

* chore: synchronizing docs and schema plus prettier

* Adding changset to set as alpha

* Updating changeset documentation



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.12...v) (2022-01-17)


### Bug Fixes

* **docs:** Update link for "Desktop File" ([#6532](https://github.com/electron-userland/electron-builder/issues/6532)) ([cd79c53](https://github.com/electron-userland/electron-builder/commit/cd79c53828759cf19cd361a48ef6fd57fff0e2f1))
* **NSIS:** prevent partial overwrites during `Nsis7z::Extract` ([#6547](https://github.com/electron-userland/electron-builder/issues/6547)) ([bea51d6](https://github.com/electron-userland/electron-builder/commit/bea51d6a8bb828d9b34734908f13b667aa55b0e9))
* **nsis:** use revertible+atomic rmdir on update and add user-confirmed retry loop ([#6551](https://github.com/electron-userland/electron-builder/issues/6551)) ([7b2a5e1](https://github.com/electron-userland/electron-builder/commit/7b2a5e1f19921e9da4aaaea8c01c78740f29f9dd))
* skip unstable installer tests to unblock master CI pipeline ([#6544](https://github.com/electron-userland/electron-builder/issues/6544)) ([5648e05](https://github.com/electron-userland/electron-builder/commit/5648e05a9efa61f81e788ecf538a617df9f65fe1))
* Stub CircleCI config since we can't disable it from dashboard ([#6543](https://github.com/electron-userland/electron-builder/issues/6543)) ([22fb8c6](https://github.com/electron-userland/electron-builder/commit/22fb8c63ac196c61c6b449e6e5e95d91117f8894))
* use junction in windows to solve Error: EPERM: operation not per… ([#6529](https://github.com/electron-userland/electron-builder/issues/6529)) ([f7b3869](https://github.com/electron-userland/electron-builder/commit/f7b386986ec30f7e4cd3e3f68e078a773940a51c))


### chore

* v23.0.0 alpha ([#6556](https://github.com/electron-userland/electron-builder/issues/6556)) ([a138a86](https://github.com/electron-userland/electron-builder/commit/a138a86fb7b59098f5dac0c0a6b59c034eb9b222)), closes [#4898](https://github.com/electron-userland/electron-builder/issues/4898) [#6232](https://github.com/electron-userland/electron-builder/issues/6232) [#6259](https://github.com/electron-userland/electron-builder/issues/6259) [#6511](https://github.com/electron-userland/electron-builder/issues/6511) [#6506](https://github.com/electron-userland/electron-builder/issues/6506) [#6507](https://github.com/electron-userland/electron-builder/issues/6507) [#6514](https://github.com/electron-userland/electron-builder/issues/6514) [#6508](https://github.com/electron-userland/electron-builder/issues/6508) [#6508](https://github.com/electron-userland/electron-builder/issues/6508) [#3683](https://github.com/electron-userland/electron-builder/issues/3683) [#6201](https://github.com/electron-userland/electron-builder/issues/6201) [#6530](https://github.com/electron-userland/electron-builder/issues/6530) [#6550](https://github.com/electron-userland/electron-builder/issues/6550)


### BREAKING CHANGES

* Removing Bintray support since it was sunset. Ref: https://jfrog.com/blog/into-the-sunset-bintray-jcenter-gocenter-and-chartcenter/

* fix: force strip path separators for backslashes on Windows

* fix: Force authentication for local Mac Squirrel update server
* Fail-fast for signature verification failures. Adding `-LiteralPath` to update file for injected wildcards

* Adding changeset and eslint

* Fix error: `-OUTPUTCHARSET is disabled for non Win32 platforms.`
* Admins using advertisement must apply an MST to re-enable it. See #6508.
* remove MSI option `iconId`

* fix: stabilizing tests by moving updater tests to its own node to explicitly segment env.___TOKEN integration tests from other standard unit tests

* chore: synchronizing docs and schema plus prettier

* Adding changset to set as alpha

* Updating changeset documentation



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.12...v) (2022-01-11)


### Bug Fixes

* **docs:** Update link for "Desktop File" ([#6532](https://github.com/electron-userland/electron-builder/issues/6532)) ([cd79c53](https://github.com/electron-userland/electron-builder/commit/cd79c53828759cf19cd361a48ef6fd57fff0e2f1))
* use junction in windows to solve Error: EPERM: operation not per… ([#6529](https://github.com/electron-userland/electron-builder/issues/6529)) ([f7b3869](https://github.com/electron-userland/electron-builder/commit/f7b386986ec30f7e4cd3e3f68e078a773940a51c))



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.11...v) (2021-12-31)


### Bug Fixes

* add warning to macCodeSign when skipping code signing on M1 macOS device ([#6522](https://github.com/electron-userland/electron-builder/issues/6522)) ([8730027](https://github.com/electron-userland/electron-builder/commit/87300278d24e8304caa4b053b883843a2447dab2))
* specify protocol as https to complete proxy support fix ([#6516](https://github.com/electron-userland/electron-builder/issues/6516)) ([344bb23](https://github.com/electron-userland/electron-builder/commit/344bb232d71e608b881a04fc98dca0858e42ddfc)), closes [#6286](https://github.com/electron-userland/electron-builder/issues/6286)



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.10...v) (2021-12-21)


### Bug Fixes

* **nsis:** Ignore other users processes during per-user installation ([#6472](https://github.com/electron-userland/electron-builder/issues/6472)) ([e3d06af](https://github.com/electron-userland/electron-builder/commit/e3d06afae1236d44e4b6e670b453b260b1f74d84)), closes [#6104](https://github.com/electron-userland/electron-builder/issues/6104)



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.8...v) (2021-11-30)


### Bug Fixes

* **app-builder-lib:** channel alternation for github is not working ([#6449](https://github.com/electron-userland/electron-builder/issues/6449)) ([df7a425](https://github.com/electron-userland/electron-builder/commit/df7a4255d219aea7a1236fd5693f7c13460099ad))
* **mac:** use `uname -a` to get arch before testing 'process.arch' on mac silicon  ([#6381](https://github.com/electron-userland/electron-builder/issues/6381)) ([828fcd3](https://github.com/electron-userland/electron-builder/commit/828fcd378c2df28763893ef68f92d5b1a72fead3))
* **nsis:** per-machine installs must properly elevate during silent install/updates ([#6450](https://github.com/electron-userland/electron-builder/issues/6450)) ([661a652](https://github.com/electron-userland/electron-builder/commit/661a6522520e9ea59549cb7e18986fcfb58e873a)), closes [#6438](https://github.com/electron-userland/electron-builder/issues/6438) [#6073](https://github.com/electron-userland/electron-builder/issues/6073) [#6425](https://github.com/electron-userland/electron-builder/issues/6425) [#5468](https://github.com/electron-userland/electron-builder/issues/5468)



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.8...v) (2021-11-30)


### Bug Fixes

* **nsis:** per-machine installs must properly elevate during silent install/updates ([#6450](https://github.com/electron-userland/electron-builder/issues/6450)) ([661a652](https://github.com/electron-userland/electron-builder/commit/661a6522520e9ea59549cb7e18986fcfb58e873a)), closes [#6438](https://github.com/electron-userland/electron-builder/issues/6438) [#6073](https://github.com/electron-userland/electron-builder/issues/6073) [#6425](https://github.com/electron-userland/electron-builder/issues/6425) [#5468](https://github.com/electron-userland/electron-builder/issues/5468)



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.7...v) (2021-11-26)


### Bug Fixes

* Downgrading nsis to v3.0.4.1 since v3.0.4.2 throws false virus positives ([#6334](https://github.com/electron-userland/electron-builder/issues/6334)) ([#6447](https://github.com/electron-userland/electron-builder/issues/6447)) ([d20bcf0](https://github.com/electron-userland/electron-builder/commit/d20bcf0cea4e4cb49aab08f820131a2d6b083a2c))


### Features

* make `--no-sandbox` optional for building with AppImage ([#6429](https://github.com/electron-userland/electron-builder/issues/6429)) ([e95afc1](https://github.com/electron-userland/electron-builder/commit/e95afc1ab8c1a09fc8c9496084fc9f49b185469e))



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.6...v) (2021-11-11)


### Bug Fixes

* **builder-util:** enable proxy handling in NodeHttpExecutor ([#6410](https://github.com/electron-userland/electron-builder/issues/6410)) ([#6286](https://github.com/electron-userland/electron-builder/issues/6286)) ([#5906](https://github.com/electron-userland/electron-builder/issues/5906)) ([04a8435](https://github.com/electron-userland/electron-builder/commit/04a84352b2b3fbb3c54533a8428bfd103df0af21))



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.5...v) (2021-11-09)


### Bug Fixes

* latest node-gyp with old Electron versions ([#6402](https://github.com/electron-userland/electron-builder/issues/6402)) ([f41d5f3](https://github.com/electron-userland/electron-builder/commit/f41d5f397ade8f6199d56bb4275b05a0a0e65bca))
* **linux:** mutually exclusive exec command args ([#6384](https://github.com/electron-userland/electron-builder/issues/6384)) ([5468c18](https://github.com/electron-userland/electron-builder/commit/5468c188f30f65352ca651e1f5fa9f8915c48c6b))
* quitAndInstall not working on macOS with autoInstallOnAppQuit=false ([#6390](https://github.com/electron-userland/electron-builder/issues/6390)) ([a5e8073](https://github.com/electron-userland/electron-builder/commit/a5e8073e21b1ff791905cdb4ab011a724533d8c1))
* rerunning test-linux to update snapshot for upstream dep that now uses additional depedencies ([#6403](https://github.com/electron-userland/electron-builder/issues/6403)) ([434d388](https://github.com/electron-userland/electron-builder/commit/434d3887cb651ef93ce214dc7b8edeab6a298096))



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.4...v) (2021-10-13)


### Bug Fixes

* SnapStoreOptions required properties ([#6327](https://github.com/electron-userland/electron-builder/issues/6327)) ([#6333](https://github.com/electron-userland/electron-builder/issues/6333)) ([54ee4e7](https://github.com/electron-userland/electron-builder/commit/54ee4e72c5db859b9a00104179786567a0e977ff))



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.3...v) (2021-10-03)


### Bug Fixes

* add appCannotBeClosed text for zh_CN ([#6287](https://github.com/electron-userland/electron-builder/issues/6287)) ([10b4727](https://github.com/electron-userland/electron-builder/commit/10b47273c32c32df17dfb910feb4a7704c83da91))
* **app-builder-lib:** macOS packager uses static icon name ([#6308](https://github.com/electron-userland/electron-builder/issues/6308)) ([fce1a1f](https://github.com/electron-userland/electron-builder/commit/fce1a1fab66e3f5cd741a4cecc4af8377aea9dd8))
* **publish:** Bitbucket publish can have username different from owner ([#6293](https://github.com/electron-userland/electron-builder/issues/6293)) ([8ebfc96](https://github.com/electron-userland/electron-builder/commit/8ebfc96276bffe0bc1ad394c5ae6843976e01709))
* Update assistedMessages.yml with korean entries ([#6309](https://github.com/electron-userland/electron-builder/issues/6309)) ([e29a6b8](https://github.com/electron-userland/electron-builder/commit/e29a6b8b36695a2ed9d2f9a57e4c1c74587d1b16))



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.2...v) (2021-09-25)


### Bug Fixes

* **msi:** fix broken shortcut icon when using msi target, adding msi option `iconId` ([#6247](https://github.com/electron-userland/electron-builder/issues/6247)) ([a9ec90d](https://github.com/electron-userland/electron-builder/commit/a9ec90d539fdbb5786692629275b1a89bfd7aec4))



# [](https://github.com/electron-userland/electron-builder/compare/v22.13.1...v) (2021-09-10)


### Bug Fixes

* (mac) Fix intel mac upgrade flow when both x64 and arm64 published ([#6212](https://github.com/electron-userland/electron-builder/issues/6212)) ([0c21cd6](https://github.com/electron-userland/electron-builder/commit/0c21cd69663a7eebe0687eaba9eea851cc2fea9e))
* Add support for nested file extensions (such as `.dmg.blockmap`) to Keygen publisher ([#6234](https://github.com/electron-userland/electron-builder/issues/6234)) ([369f1fa](https://github.com/electron-userland/electron-builder/commit/369f1fa793c28d8743e19ef07ce6eb091c191fb0)), closes [#6229](https://github.com/electron-userland/electron-builder/issues/6229)
* **deploy:** Removing schema generation since it doesn't compile during release ([7e28c11](https://github.com/electron-userland/electron-builder/commit/7e28c11ec894c9ce7664a2ea3bfdb3e96f09d983))
* **deploy:** Update package.json script name ([e22fc16](https://github.com/electron-userland/electron-builder/commit/e22fc16cd196ab0f3cc7b2f9bdaae237e64121a8))
* dmg-license optional dependency ([#6244](https://github.com/electron-userland/electron-builder/issues/6244)) ([8ccb2da](https://github.com/electron-userland/electron-builder/commit/8ccb2da5d4c641b971f6a7403d3b2e3a3b844a05))
* dmg-license-dependency ([#6248](https://github.com/electron-userland/electron-builder/issues/6248)) ([f359035](https://github.com/electron-userland/electron-builder/commit/f3590355c61dab05a6c92c5951aae8e59503d693))


### Features

* adding Bitbucket publisher and autoupdater ([#6228](https://github.com/electron-userland/electron-builder/issues/6228)) ([a945321](https://github.com/electron-userland/electron-builder/commit/a94532164709a545c0f6551fdc336dbc5377bda8))



# [](https://github.com/electron-userland/electron-builder/compare/v22.13.1...v) (2021-09-09)


### Bug Fixes

* (mac) Fix intel mac upgrade flow when both x64 and arm64 published ([#6212](https://github.com/electron-userland/electron-builder/issues/6212)) ([0c21cd6](https://github.com/electron-userland/electron-builder/commit/0c21cd69663a7eebe0687eaba9eea851cc2fea9e))
* Add support for nested file extensions (such as `.dmg.blockmap`) to Keygen publisher ([#6234](https://github.com/electron-userland/electron-builder/issues/6234)) ([369f1fa](https://github.com/electron-userland/electron-builder/commit/369f1fa793c28d8743e19ef07ce6eb091c191fb0)), closes [#6229](https://github.com/electron-userland/electron-builder/issues/6229)
* **deploy:** Removing schema generation since it doesn't compile during release ([7e28c11](https://github.com/electron-userland/electron-builder/commit/7e28c11ec894c9ce7664a2ea3bfdb3e96f09d983))
* **deploy:** Update package.json script name ([e22fc16](https://github.com/electron-userland/electron-builder/commit/e22fc16cd196ab0f3cc7b2f9bdaae237e64121a8))
* dmg-license optional dependency ([#6244](https://github.com/electron-userland/electron-builder/issues/6244)) ([8ccb2da](https://github.com/electron-userland/electron-builder/commit/8ccb2da5d4c641b971f6a7403d3b2e3a3b844a05))


### Features

* adding Bitbucket publisher and autoupdater ([#6228](https://github.com/electron-userland/electron-builder/issues/6228)) ([a945321](https://github.com/electron-userland/electron-builder/commit/a94532164709a545c0f6551fdc336dbc5377bda8))



# [](https://github.com/electron-userland/electron-builder/compare/v22.13.1...v) (2021-09-08)


### Bug Fixes

* (mac) Fix intel mac upgrade flow when both x64 and arm64 published ([#6212](https://github.com/electron-userland/electron-builder/issues/6212)) ([0c21cd6](https://github.com/electron-userland/electron-builder/commit/0c21cd69663a7eebe0687eaba9eea851cc2fea9e))
* Add support for nested file extensions (such as `.dmg.blockmap`) to Keygen publisher ([#6234](https://github.com/electron-userland/electron-builder/issues/6234)) ([369f1fa](https://github.com/electron-userland/electron-builder/commit/369f1fa793c28d8743e19ef07ce6eb091c191fb0)), closes [#6229](https://github.com/electron-userland/electron-builder/issues/6229)
* **deploy:** Removing schema generation since it doesn't compile during release ([7e28c11](https://github.com/electron-userland/electron-builder/commit/7e28c11ec894c9ce7664a2ea3bfdb3e96f09d983))
* **deploy:** Update package.json script name ([e22fc16](https://github.com/electron-userland/electron-builder/commit/e22fc16cd196ab0f3cc7b2f9bdaae237e64121a8))


### Features

* adding Bitbucket publisher and autoupdater ([#6228](https://github.com/electron-userland/electron-builder/issues/6228)) ([a945321](https://github.com/electron-userland/electron-builder/commit/a94532164709a545c0f6551fdc336dbc5377bda8))



# [](https://github.com/electron-userland/electron-builder/compare/v22.13.1...v) (2021-09-01)


### Bug Fixes

* (mac) Fix intel mac upgrade flow when both x64 and arm64 published ([#6212](https://github.com/electron-userland/electron-builder/issues/6212)) ([0c21cd6](https://github.com/electron-userland/electron-builder/commit/0c21cd69663a7eebe0687eaba9eea851cc2fea9e))



# [](https://github.com/electron-userland/electron-builder/compare/v22.13.0...v) (2021-08-27)


### Bug Fixes

* Adding snapStore to AllPublishOptions for generating Configuration schema ([#6193](https://github.com/electron-userland/electron-builder/issues/6193)) ([7f933d0](https://github.com/electron-userland/electron-builder/commit/7f933d0004a0a5f808a2a1c71dca7362cab2728e))
* Support Windows 11 in VMs ([#6185](https://github.com/electron-userland/electron-builder/issues/6185)) ([f6a3053](https://github.com/electron-userland/electron-builder/commit/f6a3053563bd50dc77010d2910086c81acdf613e))



# [](https://github.com/electron-userland/electron-builder/compare/v22.12.1...v) (2021-08-25)


### Features

* add `beforePack` hook ([#6176](https://github.com/electron-userland/electron-builder/issues/6176)) ([6f42f64](https://github.com/electron-userland/electron-builder/commit/6f42f646c9d36405c9d69ca45dda51baabdec4bd))
* Adding Keygen as an official publisher/updater for electron-builder ([#6167](https://github.com/electron-userland/electron-builder/issues/6167)) ([f45110c](https://github.com/electron-userland/electron-builder/commit/f45110cbf66572d5748d21fc24dc26cabd06f35f))



# [](https://github.com/electron-userland/electron-builder/compare/v22.12.0...v) (2021-08-22)


### Bug Fixes

* console log data for electron-updater blockmaps are far too large ([#6143](https://github.com/electron-userland/electron-builder/issues/6143)) ([ae363e5](https://github.com/electron-userland/electron-builder/commit/ae363e51957d0abfc7d848f51aa23c7e5faf5f33))
* **deploy:** remove zulip release message ([695f89a](https://github.com/electron-userland/electron-builder/commit/695f89a7b18e100c15ac47f837ae10ee600710ac))
* **electron-updater:** `null` object error when MacUpdater logs server port before it is listening ([#6149](https://github.com/electron-userland/electron-builder/issues/6149)) ([ca0e845](https://github.com/electron-userland/electron-builder/commit/ca0e8454b876c9fa0c95dbadf2461419e3a8b697))
* **electron-updater:** fix import errors ([#6140](https://github.com/electron-userland/electron-builder/issues/6140)) ([a3f2cd1](https://github.com/electron-userland/electron-builder/commit/a3f2cd1565771c8ce6c5a4b40d1c88316a75dff3)), closes [#6134](https://github.com/electron-userland/electron-builder/issues/6134)
* replace deprecated --cache-min option ([#6165](https://github.com/electron-userland/electron-builder/issues/6165)) ([c02ccbb](https://github.com/electron-userland/electron-builder/commit/c02ccbb9739a6fb2840625a825f6be33136567f0))
* **windows:** detect node path correctly on windows with cross-spawn ([#6069](https://github.com/electron-userland/electron-builder/issues/6069)) ([#6172](https://github.com/electron-userland/electron-builder/issues/6172)) ([6c945bd](https://github.com/electron-userland/electron-builder/commit/6c945bd59749d3fdd91f50ea4131ee22e82f72a2))
* workaround vite replacing process.env in updater ([#6160](https://github.com/electron-userland/electron-builder/issues/6160)) ([a3c72b2](https://github.com/electron-userland/electron-builder/commit/a3c72b2481ebaacfd717a7c492c119bcb9b7fc36))



# [](https://github.com/electron-userland/electron-builder/compare/v22.12.0...v) (2021-08-12)


### Bug Fixes

* console log data for electron-updater blockmaps are far too large ([#6143](https://github.com/electron-userland/electron-builder/issues/6143)) ([ae363e5](https://github.com/electron-userland/electron-builder/commit/ae363e51957d0abfc7d848f51aa23c7e5faf5f33))
* **electron-updater:** fix import errors ([#6140](https://github.com/electron-userland/electron-builder/issues/6140)) ([a3f2cd1](https://github.com/electron-userland/electron-builder/commit/a3f2cd1565771c8ce6c5a4b40d1c88316a75dff3)), closes [#6134](https://github.com/electron-userland/electron-builder/issues/6134)



# [](https://github.com/electron-userland/electron-builder/compare/v22.11.11...v) (2021-08-09)


### Bug Fixes

* **electron-updater:** search 'arm64' in name and url to fix updates from Github private repos ([1580ea6](https://github.com/electron-userland/electron-builder/commit/1580ea691c4b82ea80c6420d806bc4bfaef5fd38))
* **electron-updater:** small cleanup and add more debug logging for MacUpdater to investigate [#6120](https://github.com/electron-userland/electron-builder/issues/6120) ([#6122](https://github.com/electron-userland/electron-builder/issues/6122)) ([ae81dfa](https://github.com/electron-userland/electron-builder/commit/ae81dfae519435355fc079c76fc16ac25216bf38))
* **electron-updater:** use tag name instead of version when resolving GitHub files ([#6117](https://github.com/electron-userland/electron-builder/issues/6117)) ([dcf03a6](https://github.com/electron-userland/electron-builder/commit/dcf03a67a8a0d4cec4422cda0aa2585f7f54a384))
* **nsis:** should close app when `Silent` and `ONE_CLICK` ([#6100](https://github.com/electron-userland/electron-builder/issues/6100)) ([baf640d](https://github.com/electron-userland/electron-builder/commit/baf640da459dc667240e6015deaf11adb2155063))


### Features

* allow custom makensis and nsis logging ([#6024](https://github.com/electron-userland/electron-builder/issues/6024)) ([a99a7c8](https://github.com/electron-userland/electron-builder/commit/a99a7c87ffd7ffaaa5fae1a17f731a59aac60581)), closes [#5119](https://github.com/electron-userland/electron-builder/issues/5119)
* **portable:** Adding support for unique dir on each portable app launch ([#6093](https://github.com/electron-userland/electron-builder/issues/6093)) ([f8e16db](https://github.com/electron-userland/electron-builder/commit/f8e16db5393f663724e9c03ceab87698a252c934)), closes [#5764](https://github.com/electron-userland/electron-builder/issues/5764) [#5382](https://github.com/electron-userland/electron-builder/issues/5382) [#4105](https://github.com/electron-userland/electron-builder/issues/4105)



#  (2021-07-29)


### Bug Fixes

* **deploy:** Fixing zulip send message action ([41d5cae](https://github.com/electron-userland/electron-builder/commit/41d5cae325cba3031bc25148b1ff5927bc441913))
* **docs:** minor grammar/formatting fixes ([#6107](https://github.com/electron-userland/electron-builder/issues/6107)) ([b9b275f](https://github.com/electron-userland/electron-builder/commit/b9b275fff0763faf110a8dcb3c8313963710bbeb))
* linking CLI `version` output with package.json ([#6097](https://github.com/electron-userland/electron-builder/issues/6097)) ([a4eae34](https://github.com/electron-userland/electron-builder/commit/a4eae34f38444e0f30cf94af869e9e84c406a469))
* **mac:** signing cert filter incorrectly selects certificates ([#6094](https://github.com/electron-userland/electron-builder/issues/6094)) ([#6101](https://github.com/electron-userland/electron-builder/issues/6101)) ([#6105](https://github.com/electron-userland/electron-builder/issues/6105)) ([4a177dc](https://github.com/electron-userland/electron-builder/commit/4a177dc01c9119443426f1eb500afb836fd4f381))



# [](https://github.com/electron-userland/electron-builder/compare/v22.11.9...v) (2021-07-24)


### Bug Fixes

* any "node_module/____" glob pattern selects far too many node dependencies ([#6080](https://github.com/electron-userland/electron-builder/issues/6080)) ([72ffc25](https://github.com/electron-userland/electron-builder/commit/72ffc25063fc6d8f67e941ed7fc3b5991efb5448)), closes [#6045](https://github.com/electron-userland/electron-builder/issues/6045)
* remove @electron-builder/test from changeset ([e101e8d](https://github.com/electron-userland/electron-builder/commit/e101e8d190d7e3046222e88c32a62d727dadd808))
* using regex to determine yarn version to account for newer releases of yarn (i.e. yarn 3). fixes: [#6069](https://github.com/electron-userland/electron-builder/issues/6069) ([#6071](https://github.com/electron-userland/electron-builder/issues/6071)) ([1e19aba](https://github.com/electron-userland/electron-builder/commit/1e19abaecb3fd7b6ff0932b46ee129e04d1496b3))
* **win:** Windows update fails for custom paths that require admin rights ([#6073](https://github.com/electron-userland/electron-builder/issues/6073)) ([45fc0a0](https://github.com/electron-userland/electron-builder/commit/45fc0a003abc58969bb3a5d6ab1e3b61a9ad1a8d))


### Features

* **mac:** Add timestamp authority server to osx-sign options ([#6074](https://github.com/electron-userland/electron-builder/issues/6074)) ([41cb248](https://github.com/electron-userland/electron-builder/commit/41cb24869381de73a9663a17ec91d2747e099cf9))



# [](https://github.com/electron-userland/electron-builder/compare/v22.11.8...v) (2021-07-14)


### Bug Fixes

* **deploy:** consolidating versioning commands into package.json ([6066681](https://github.com/electron-userland/electron-builder/commit/6066681077c8ba730155751b83b4550add9b0dcf))
* **deploy:** deactivate husky hooks for automatic versioning PR ([#6041](https://github.com/electron-userland/electron-builder/issues/6041)) ([0d4d305](https://github.com/electron-userland/electron-builder/commit/0d4d3056b440cc45a1f1a15ea4a27c688cb0e96e))
* do not show MessageBox when app was killed (on not running) ([#6043](https://github.com/electron-userland/electron-builder/issues/6043)) ([0561674](https://github.com/electron-userland/electron-builder/commit/0561674b6c491ee1cfa0ba838f5c5d59ce205124))
* **nsis:** generate uninstaller without elevating ([#5575](https://github.com/electron-userland/electron-builder/issues/5575)) ([#6013](https://github.com/electron-userland/electron-builder/issues/6013)) ([b00aea3](https://github.com/electron-userland/electron-builder/commit/b00aea32107cd379b8489f7abea493d16fe38197))
* updating electron-osx-sign ([#6021](https://github.com/electron-userland/electron-builder/issues/6021)) ([6f63092](https://github.com/electron-userland/electron-builder/commit/6f630927ca949d8bdcde06e4eafaa63ce3636d5a)), closes [#6010](https://github.com/electron-userland/electron-builder/issues/6010) [#5190](https://github.com/electron-userland/electron-builder/issues/5190)
* write blockmap file for mac zip archives ([#6023](https://github.com/electron-userland/electron-builder/issues/6023)) ([0447b24](https://github.com/electron-userland/electron-builder/commit/0447b2457beb03648f1e7e841cd0a8d12d7e4aea)), closes [#4299](https://github.com/electron-userland/electron-builder/issues/4299)



**Here changelog only for previous major releases and without detailed explanations.**
To see changes for current major release, please use [GiHub releases](https://github.com/electron-userland/electron-builder/releases).

<a name=""></a>
# [19.10.0](https://github.com/electron-userland/electron-builder/compare/v19.9.1...v) (2017-06-28)


### Bug Fixes

* 19.8.0 broke ignoring folders ([50fe277](https://github.com/electron-userland/electron-builder/commit/50fe277)), closes [#1741](https://github.com/electron-userland/electron-builder/issues/1741)


### Features

* **Squirrel.Windows:** name option ([02dd8a1](https://github.com/electron-userland/electron-builder/commit/02dd8a1)), closes [#1743](https://github.com/electron-userland/electron-builder/issues/1743)
* **nsis:** option to not create desktop shortcut ([350e241](https://github.com/electron-userland/electron-builder/commit/350e241)), closes [#1597](https://github.com/electron-userland/electron-builder/issues/1597)
* allow to use files in the output directory to be included into the app ([95c75fc](https://github.com/electron-userland/electron-builder/commit/95c75fc))
* do not force build from sources by default ([86be5d7](https://github.com/electron-userland/electron-builder/commit/86be5d7)), closes [#1703](https://github.com/electron-userland/electron-builder/issues/1703)



<a name="19.9.1"></a>
## [19.9.1](https://github.com/electron-userland/electron-builder/compare/v19.9.0...v19.9.1) (2017-06-24)


### Features

* Support setting boolean properties with --extraMetadata ([9e77231](https://github.com/electron-userland/electron-builder/commit/9e77231)), closes [#1674](https://github.com/electron-userland/electron-builder/issues/1674)



<a name="19.9.0"></a>
# [19.9.0](https://github.com/electron-userland/electron-builder/compare/v19.8.0...v19.9.0) (2017-06-24)


### Bug Fixes

* **electron-updater:** MacUpdater — set Content-Length for responses, write 200 only if request to origin server is ok ([af2f559](https://github.com/electron-userland/electron-builder/commit/af2f559)), closes [#1719](https://github.com/electron-userland/electron-builder/issues/1719)


### Features

* add channel to file macros ([6aa3809](https://github.com/electron-userland/electron-builder/commit/6aa3809)), closes [#1701](https://github.com/electron-userland/electron-builder/issues/1701)



<a name="19.8.0"></a>
# [19.8.0](https://github.com/electron-userland/electron-builder/compare/v19.7.3...v19.8.0) (2017-06-23)


### Features

* ignore dll/exe files from node_modules if target platform not windows ([945a517](https://github.com/electron-userland/electron-builder/commit/945a517)), closes [#1738](https://github.com/electron-userland/electron-builder/issues/1738)



<a name="19.7.3"></a>
## [19.7.3](https://github.com/electron-userland/electron-builder/compare/v19.7.2...v19.7.3) (2017-06-22)


### Bug Fixes

* **AppImage:** AppImage artifact name does not use `artifactName` template ([a02fbd7](https://github.com/electron-userland/electron-builder/commit/a02fbd7)), closes [#1726](https://github.com/electron-userland/electron-builder/issues/1726)



<a name="19.7.2"></a>
## [19.7.2](https://github.com/electron-userland/electron-builder/compare/v19.7.0...v19.7.2) (2017-06-22)


### Bug Fixes

* electron-builder install-app-deps does not honor build.directories.app ([6db68be](https://github.com/electron-userland/electron-builder/commit/6db68be)), closes [#1721](https://github.com/electron-userland/electron-builder/issues/1721)
* **electron-updater:** Auto update does not work on machines with Powershell version < 3 ([5e09db4](https://github.com/electron-userland/electron-builder/commit/5e09db4)), closes [#1732](https://github.com/electron-userland/electron-builder/issues/1732)
* **mac:** clean macOsVersion before gte comparison (#1733) ([7ff95ca](https://github.com/electron-userland/electron-builder/commit/7ff95ca))
* **windows:** Get-PfxCertificate hangs ([6f8b94b](https://github.com/electron-userland/electron-builder/commit/6f8b94b)), closes [#1735](https://github.com/electron-userland/electron-builder/issues/1735)


### Features

* allow to set electronDist as path to local folder with electron builds zipped ([e79a28c](https://github.com/electron-userland/electron-builder/commit/e79a28c)), closes [#1716](https://github.com/electron-userland/electron-builder/issues/1716)



<a name="19.7.0"></a>
# [19.7.0](https://github.com/electron-userland/electron-builder/compare/v19.6.3...v19.7.0) (2017-06-21)


### Bug Fixes

* **auto-updater:** do not require app-update.yml file ([c03d98f](https://github.com/electron-userland/electron-builder/commit/c03d98f))


### Features

* **deployment:** set electron-updater releaseNotes at build time ([f6a2fc8](https://github.com/electron-userland/electron-builder/commit/f6a2fc8)), closes [#1511](https://github.com/electron-userland/electron-builder/issues/1511)



<a name="19.6.3"></a>
## [19.6.3](https://github.com/electron-userland/electron-builder/compare/v19.6.2...v19.6.3) (2017-06-21)


### Bug Fixes

* Runtime error for a build on window feat. electron-compile (forge) ([89a55ee](https://github.com/electron-userland/electron-builder/commit/89a55ee)), closes [#1686](https://github.com/electron-userland/electron-builder/issues/1686)



<a name="19.6.2"></a>
## [19.6.2](https://github.com/electron-userland/electron-builder/compare/v19.6.1...v19.6.2) (2017-06-21)


### Features

* **mac:** Ignore Contents/PlugIns ([a4b76b4](https://github.com/electron-userland/electron-builder/commit/a4b76b4)), closes [#1699](https://github.com/electron-userland/electron-builder/issues/1699)



<a name="19.6.1"></a>
## [19.6.1](https://github.com/electron-userland/electron-builder/compare/v19.6.0...v19.6.1) (2017-06-20)


### Bug Fixes

* keep shortcuts only if old uninstaller app support it ([8660093](https://github.com/electron-userland/electron-builder/commit/8660093)), closes [#1704](https://github.com/electron-userland/electron-builder/issues/1704)



<a name="19.6.0"></a>
# [19.6.0](https://github.com/electron-userland/electron-builder/compare/v19.5.1...v19.6.0) (2017-06-20)


### Features

* **mac:** upgrade osslsigncode, do not require wine ([ed662e8](https://github.com/electron-userland/electron-builder/commit/ed662e8)), closes [#1713](https://github.com/electron-userland/electron-builder/issues/1713) [#1707](https://github.com/electron-userland/electron-builder/issues/1707)
* **nsis:** Add flag to force start on silent install ([f24c389](https://github.com/electron-userland/electron-builder/commit/f24c389)), closes [#1545](https://github.com/electron-userland/electron-builder/issues/1545) [#1712](https://github.com/electron-userland/electron-builder/issues/1712)



<a name="19.5.1"></a>
## [19.5.1](https://github.com/electron-userland/electron-builder/compare/v19.5.0...v19.5.1) (2017-06-18)


### Bug Fixes

* **mac:** MacOS Sierra Command failed: codesign; The specified item could not be found in the keychain ([239d16d](https://github.com/electron-userland/electron-builder/commit/239d16d)), closes [#1457](https://github.com/electron-userland/electron-builder/issues/1457)


### Features

* **mac:** resize icons for Linux using sips on macOS to avoid graphicsmagick dependency ([e5817bc](https://github.com/electron-userland/electron-builder/commit/e5817bc))



<a name="19.5.0"></a>
# [19.5.0](https://github.com/electron-userland/electron-builder/compare/v19.4.2...v19.5.0) (2017-06-17)


### Bug Fixes

* **mac:** use hash instead of identity name to sign ([ee90ff2](https://github.com/electron-userland/electron-builder/commit/ee90ff2)), closes [#1629](https://github.com/electron-userland/electron-builder/issues/1629)


### Features

* **appx:** languages ([86af4cd](https://github.com/electron-userland/electron-builder/commit/86af4cd)), closes [#1684](https://github.com/electron-userland/electron-builder/issues/1684)
* **electron-updater:** staged rollouts ([5bae61e](https://github.com/electron-userland/electron-builder/commit/5bae61e)), closes [#1639](https://github.com/electron-userland/electron-builder/issues/1639)
* **pkg:** build pkg that doesn't require admin install ([a3a23f2](https://github.com/electron-userland/electron-builder/commit/a3a23f2))



<a name="19.4.2"></a>
## [19.4.2](https://github.com/electron-userland/electron-builder/compare/v19.4.1...v19.4.2) (2017-06-16)


### Bug Fixes

* **nsis:** missed "Installing, please wait" text ([c5d3441](https://github.com/electron-userland/electron-builder/commit/c5d3441)), closes [#1630](https://github.com/electron-userland/electron-builder/issues/1630)


### Features

* **deployment:** do not publish if Pull Request — support APPVEYOR_PULL_REQUEST_NUMBER ([b0fb872](https://github.com/electron-userland/electron-builder/commit/b0fb872))



<a name="19.4.1"></a>
## [19.4.1](https://github.com/electron-userland/electron-builder/compare/v19.4.0...v19.4.1) (2017-06-16)


### Bug Fixes

* **electron-updater:** No notification in case of an error during signature verification ([a9e03ce](https://github.com/electron-userland/electron-builder/commit/a9e03ce)), closes [#1680](https://github.com/electron-userland/electron-builder/issues/1680) [#1681](https://github.com/electron-userland/electron-builder/issues/1681)


### Code Refactoring

* merge electron-builder-core into electron-builder, transform node-gyp-rebuild bin to subcommand ([a8c9ffd](https://github.com/electron-userland/electron-builder/commit/a8c9ffd))


### Features

* **appx:** Improve support for AppX assets ([666dec7](https://github.com/electron-userland/electron-builder/commit/666dec7))


### BREAKING CHANGES

* Please use `node-gyp-rebuild` as `electron-buider node-gyp-rebuild` now



<a name="19.3.0"></a>
# [19.3.0](https://github.com/electron-userland/electron-builder/compare/v19.2.7...v19.3.0) (2017-06-15)


### Features

* **nsis:** custom uninstaller display name in the control panel ([fda6ee9](https://github.com/electron-userland/electron-builder/commit/fda6ee9))
* react-cra detection, shareable config support — extends ([28f0266](https://github.com/electron-userland/electron-builder/commit/28f0266))



<a name="19.2.7"></a>
## [19.2.7](https://github.com/electron-userland/electron-builder/compare/v19.2.3...v19.2.7) (2017-06-14)


### Bug Fixes

* The zip Windows target includes the application code inside a "win-unpacked" directory ([4e6ece4](https://github.com/electron-userland/electron-builder/commit/4e6ece4)), closes [#1666](https://github.com/electron-userland/electron-builder/issues/1666)
* correctly pack cache folder for electron-compile ([419cf91](https://github.com/electron-userland/electron-builder/commit/419cf91)), closes [#1465](https://github.com/electron-userland/electron-builder/issues/1465)
* ignore node_modules without package.json ([5e24859](https://github.com/electron-userland/electron-builder/commit/5e24859)), closes [#1671](https://github.com/electron-userland/electron-builder/issues/1671)



<a name="19.2.3"></a>
## [19.2.3](https://github.com/electron-userland/electron-builder/compare/v19.2.2...v19.2.3) (2017-06-14)


### Bug Fixes

* do not copy electronDist using hard links ([c04dd20](https://github.com/electron-userland/electron-builder/commit/c04dd20)), closes [#1670](https://github.com/electron-userland/electron-builder/issues/1670)


### Features

* check that electron-builder version is not outdated for all subcommands ([d9ecfe5](https://github.com/electron-userland/electron-builder/commit/d9ecfe5))



<a name="19.2.2"></a>
## [19.2.2](https://github.com/electron-userland/electron-builder/compare/v19.1.0...v19.2.2) (2017-06-13)


### Bug Fixes

* macOS failing when there is no old icon (#1658) ([ac44fcd](https://github.com/electron-userland/electron-builder/commit/ac44fcd))
* **nsis:** Keep existing desktop/menu/taskbar shortcuts after update ([2f3d7d8](https://github.com/electron-userland/electron-builder/commit/2f3d7d8)), closes [#1653](https://github.com/electron-userland/electron-builder/issues/1653)


### Features

* install-app-deps.ts subcommand ([5e0a646](https://github.com/electron-userland/electron-builder/commit/5e0a646))



<a name="19.1.0"></a>
# [19.1.0](https://github.com/electron-userland/electron-builder/compare/v19.0.2...v19.1.0) (2017-06-12)


### Features

* electron-builder bin executable ([54ac796](https://github.com/electron-userland/electron-builder/commit/54ac796))



<a name="19.0.2"></a>
## [19.0.2](https://github.com/electron-userland/electron-builder/compare/v19.0.0...v19.0.2) (2017-06-12)


### Bug Fixes

* **electron-updater:** update sign verification error ([e713bbe](https://github.com/electron-userland/electron-builder/commit/e713bbe)), closes [#1641](https://github.com/electron-userland/electron-builder/issues/1641)
* Appx name changed ([dd0b208](https://github.com/electron-userland/electron-builder/commit/dd0b208)), closes [#1650](https://github.com/electron-userland/electron-builder/issues/1650)



<a name="19.0.0"></a>
# [19.0.0](https://github.com/electron-userland/electron-builder/compare/v18.8.0...v19.0.0) (2017-06-12)


### Features

* prune submodule package.json dependencies ([1145cb9](https://github.com/electron-userland/electron-builder/commit/1145cb9)), closes [#1539](https://github.com/electron-userland/electron-builder/issues/1539)
* **nsis:** add APP_EXECUTABLE_DIR ([8e957c8](https://github.com/electron-userland/electron-builder/commit/8e957c8)), closes [#1612](https://github.com/electron-userland/electron-builder/issues/1612)



<a name="18.8.0"></a>
# [18.8.0](https://github.com/electron-userland/electron-builder/compare/v18.7.0...v18.8.0) (2017-06-12)


### Features

* update makeappx tool, use powershell on Windows to get publisher name, allow to build appx on Windows Server 2012 R2 ([4d7e1b5](https://github.com/electron-userland/electron-builder/commit/4d7e1b5))



<a name="18.7.0"></a>
# [18.7.0](https://github.com/electron-userland/electron-builder/compare/v18.6.2...v18.7.0) (2017-06-08)


### Bug Fixes

* **electron-updater:** check for EACCES error when try to install on auto updated windows (#1636) ([9ef77b9](https://github.com/electron-userland/electron-builder/commit/9ef77b9))


### Features

* do not require "author" ([e700b78](https://github.com/electron-userland/electron-builder/commit/e700b78))
* **nsis:** Option to not pack "elevate.exe" ([69c3614](https://github.com/electron-userland/electron-builder/commit/69c3614)), closes [#1620](https://github.com/electron-userland/electron-builder/issues/1620) [#1621](https://github.com/electron-userland/electron-builder/issues/1621)


### Performance Improvements

* use fcopy ([d9a8015](https://github.com/electron-userland/electron-builder/commit/d9a8015))



<a name="18.6.2"></a>
## [18.6.2](https://github.com/electron-userland/electron-builder/compare/v18.6.0...v18.6.2) (2017-06-07)


### Bug Fixes

* install-app-deps, attempt 2 ([8715f44](https://github.com/electron-userland/electron-builder/commit/8715f44)), closes [#1626](https://github.com/electron-userland/electron-builder/issues/1626)
* **electron-updater:** isSilent is optional ([12473d0](https://github.com/electron-userland/electron-builder/commit/12473d0))



<a name="18.6.0"></a>
# [18.6.0](https://github.com/electron-userland/electron-builder/compare/v18.5.1...v18.6.0) (2017-06-06)


### Bug Fixes

* **electron-updater:** MacUpdater — close proxy server after download ([39ae0a4](https://github.com/electron-userland/electron-builder/commit/39ae0a4))
* **nsis:** Cloning packager.config to prevent override ([5b8abcb](https://github.com/electron-userland/electron-builder/commit/5b8abcb)), closes [#1340](https://github.com/electron-userland/electron-builder/issues/1340) [#1340](https://github.com/electron-userland/electron-builder/issues/1340)
* install-app-deps ([21a5be5](https://github.com/electron-userland/electron-builder/commit/21a5be5)), closes [#1626](https://github.com/electron-userland/electron-builder/issues/1626)


### Features

* grab latest electron version from github if not specified ([a826df2](https://github.com/electron-userland/electron-builder/commit/a826df2))
* **appimage:** artifactName support for AppImage ([0ea43a3](https://github.com/electron-userland/electron-builder/commit/0ea43a3)), closes [#775](https://github.com/electron-userland/electron-builder/issues/775)
* **docker:** upgrade to zesty ([da1734e](https://github.com/electron-userland/electron-builder/commit/da1734e))
* **electron-updater:** ensure that update only to the application signed with same cert ([66771d3](https://github.com/electron-userland/electron-builder/commit/66771d3)), closes [#1187](https://github.com/electron-userland/electron-builder/issues/1187)



<a name="18.5.1"></a>
## [18.5.1](https://github.com/electron-userland/electron-builder/compare/v18.5.0...v18.5.1) (2017-06-05)


### Features

* **electon-updater:** autoUpdater download-progress event is not called on macOS ([a75bac8](https://github.com/electron-userland/electron-builder/commit/a75bac8)), closes [#1167](https://github.com/electron-userland/electron-builder/issues/1167)



<a name="18.5.0"></a>
# [18.5.0](https://github.com/electron-userland/electron-builder/compare/v18.4.0...v18.5.0) (2017-06-05)


### Features

* **nsis:** Slovak(sk) translation ([09495f9](https://github.com/electron-userland/electron-builder/commit/09495f9))
* do not override HOME env on reinstall deps, use devdir for nodegyp ([ae0f668](https://github.com/electron-userland/electron-builder/commit/ae0f668))
* use base64 to encode sha512 checksum in the update info ([4451107](https://github.com/electron-userland/electron-builder/commit/4451107))
* **nsis:** Slovak(sk) translation for assisted installer ([63f019f](https://github.com/electron-userland/electron-builder/commit/63f019f)), closes [#1617](https://github.com/electron-userland/electron-builder/issues/1617)



<a name="18.4.0"></a>
# [18.4.0](https://github.com/electron-userland/electron-builder/compare/v18.3.5...v18.4.0) (2017-06-04)


### Bug Fixes

* **deployment:** latest.yml is completely empty when uploaded to S3 bucket ([4b25ca2](https://github.com/electron-userland/electron-builder/commit/4b25ca2)), closes [#1582](https://github.com/electron-userland/electron-builder/issues/1582)
* **deployment:** s3 publisher md5 integrity ([b57dc8a](https://github.com/electron-userland/electron-builder/commit/b57dc8a))
* **tar:** fix invalid sym-/hardlink targets in archive (#1614) ([b31ebff](https://github.com/electron-userland/electron-builder/commit/b31ebff)), closes [#1614](https://github.com/electron-userland/electron-builder/issues/1614)


### Features

* asar integrity (macos only for now) ([3e28ae2](https://github.com/electron-userland/electron-builder/commit/3e28ae2))
* asar integrity: add externalAllowed option ([e0d7974](https://github.com/electron-userland/electron-builder/commit/e0d7974))
* asar integrity: base64, externalAllowed ([9a7ac65](https://github.com/electron-userland/electron-builder/commit/9a7ac65))
* docker with node 8 ([df1feb5](https://github.com/electron-userland/electron-builder/commit/df1feb5))



<a name="18.3.5"></a>
## [18.3.5](https://github.com/electron-userland/electron-builder/compare/v18.3.0...v18.3.5) (2017-06-01)


### Bug Fixes

* **deployment:** check for errors ([4c71fc0](https://github.com/electron-userland/electron-builder/commit/4c71fc0))
* Identity validation option is incorrect ([97699b1](https://github.com/electron-userland/electron-builder/commit/97699b1)), closes [#1603](https://github.com/electron-userland/electron-builder/issues/1603)
* **dmg:** move hidden directories out of view ([452085b](https://github.com/electron-userland/electron-builder/commit/452085b)), closes [#1121](https://github.com/electron-userland/electron-builder/issues/1121)



<a name="18.3.0"></a>
# [18.3.0](https://github.com/electron-userland/electron-builder/compare/v18.2.1...v18.3.0) (2017-05-31)


### Bug Fixes

* more clear handling of onTagOrDraft ([817340a](https://github.com/electron-userland/electron-builder/commit/817340a))
* **deployment:** different channels for different publish providers ([81fd398](https://github.com/electron-userland/electron-builder/commit/81fd398))


### Features

* **linux:** add missing Exec variable for passing URLs as arguments ([4a87e67](https://github.com/electron-userland/electron-builder/commit/4a87e67)), closes [#1592](https://github.com/electron-userland/electron-builder/issues/1592)



<a name="18.2.1"></a>
## [18.2.1](https://github.com/electron-userland/electron-builder/compare/v18.1.1...v18.2.1) (2017-05-30)


### Bug Fixes

* trim the whole string, otherwise detection of windows-like path is not robust ([e63e8fa](https://github.com/electron-userland/electron-builder/commit/e63e8fa)), closes [#1596](https://github.com/electron-userland/electron-builder/issues/1596)


### Features

* support relative (to project dir) path in the CSC_LINK ([381e8c0](https://github.com/electron-userland/electron-builder/commit/381e8c0)), closes [#1596](https://github.com/electron-userland/electron-builder/issues/1596)



<a name="18.1.1"></a>
## [18.1.1](https://github.com/electron-userland/electron-builder/compare/v18.1.0...v18.1.1) (2017-05-30)


### Bug Fixes

* **appx:** AppX build fails ([9e9ed4f](https://github.com/electron-userland/electron-builder/commit/9e9ed4f)), closes [#1515](https://github.com/electron-userland/electron-builder/issues/1515)


### Features

* PUBLISH_FOR_PULL_REQUEST ([7d8e097](https://github.com/electron-userland/electron-builder/commit/7d8e097))



<a name="18.1.0"></a>
# [18.1.0](https://github.com/electron-userland/electron-builder/compare/v18.0.1...v18.1.0) (2017-05-27)


### Features

* remove "Space required" text for NSIS installer ([565740c](https://github.com/electron-userland/electron-builder/commit/565740c)), closes [#1566](https://github.com/electron-userland/electron-builder/issues/1566)
* **nsis:** custom uninstall application icon ([e4e5cc7](https://github.com/electron-userland/electron-builder/commit/e4e5cc7)), closes [#1585](https://github.com/electron-userland/electron-builder/issues/1585)



<a name="18.0.1"></a>
## [18.0.1](https://github.com/electron-userland/electron-builder/compare/v18.0.0...v18.0.1) (2017-05-24)


### Bug Fixes

* "status 401: Unauthorized" issue with dl.bintray.com ([52995df](https://github.com/electron-userland/electron-builder/commit/52995df)), closes [#1581](https://github.com/electron-userland/electron-builder/issues/1581)



<a name="18.0.0"></a>
# [18.0.0](https://github.com/electron-userland/electron-builder/compare/v17.10.0...v18.0.0) (2017-05-23)


### Bug Fixes

* **config:** use json5 parser for json5 build configs ([94d89eb](https://github.com/electron-userland/electron-builder/commit/94d89eb)), closes [#1569](https://github.com/electron-userland/electron-builder/issues/1569) [#1578](https://github.com/electron-userland/electron-builder/issues/1578)


### Code Refactoring

* **updater:** prepare to support private github repo, nuts and so on on macOS ([a41936b](https://github.com/electron-userland/electron-builder/commit/a41936b)), closes [#1575](https://github.com/electron-userland/electron-builder/issues/1575) [#1571](https://github.com/electron-userland/electron-builder/issues/1571) [#1577](https://github.com/electron-userland/electron-builder/issues/1577)


### Features

* **mac:** allow passing through binaries and requirements options ([a2e58c0](https://github.com/electron-userland/electron-builder/commit/a2e58c0)), closes [#1574](https://github.com/electron-userland/electron-builder/issues/1574)
* **snap:** Snap for extra after parts and build packages support (#1565) ([22b5ba5](https://github.com/electron-userland/electron-builder/commit/22b5ba5))


### BREAKING CHANGES

* **updater:** remove compatibility with very old electron-updater version (< 0.10.0)



<a name="17.10.0"></a>
# [17.10.0](https://github.com/electron-userland/electron-builder/compare/v17.9.0...v17.10.0) (2017-05-21)


### Features

* **nsis:** custom uninstall application icon ([eb181b9](https://github.com/electron-userland/electron-builder/commit/eb181b9)), closes [#1550](https://github.com/electron-userland/electron-builder/issues/1550)



<a name="17.9.0"></a>
# [17.9.0](https://github.com/electron-userland/electron-builder/compare/v17.8.0...v17.9.0) (2017-05-20)


### Bug Fixes

* electron-builder 17.5.0, 17.8.0: cannot find module 'debug' ([5835654](https://github.com/electron-userland/electron-builder/commit/5835654)), closes [#1564](https://github.com/electron-userland/electron-builder/issues/1564)


### Features

* **electron-updater:** isSilent param of quitAndInstall method #1545 ([daeefa6](https://github.com/electron-userland/electron-builder/commit/daeefa6))
* **nsis:** add korean messages for one-click installer (#1556) ([9fce636](https://github.com/electron-userland/electron-builder/commit/9fce636))



<a name="17.8.0"></a>
# [17.8.0](https://github.com/electron-userland/electron-builder/compare/v17.7.0...v17.8.0) (2017-05-15)


### Bug Fixes

* Automatic unpack detection in scoped packages unpacks the entire scope ([3558b22](https://github.com/electron-userland/electron-builder/commit/3558b22)), closes [#1540](https://github.com/electron-userland/electron-builder/issues/1540)


### Features

* **nsis:** finnish nsis lang ([c88d991](https://github.com/electron-userland/electron-builder/commit/c88d991))
* **squirrel.windows:** Update Squirrel.Windows to 1.6.0 ([c4bb492](https://github.com/electron-userland/electron-builder/commit/c4bb492)), closes [#1535](https://github.com/electron-userland/electron-builder/issues/1535)



<a name="17.7.0"></a>
# [17.7.0](https://github.com/electron-userland/electron-builder/compare/v17.6.0...v17.7.0) (2017-05-13)


### Features

* **nsis:** add ja translation for one-click installer (#1543) ([90d0da1](https://github.com/electron-userland/electron-builder/commit/90d0da1))



<a name="17.6.0"></a>
# [17.6.0](https://github.com/electron-userland/electron-builder/compare/v17.5.0...v17.6.0) (2017-05-13)


### Features

* **nsis:** NSIS - nested start menu folders ([fafc7ba](https://github.com/electron-userland/electron-builder/commit/fafc7ba)), closes [#1538](https://github.com/electron-userland/electron-builder/issues/1538)
* **nsis:** ko lang ([89a5233](https://github.com/electron-userland/electron-builder/commit/89a5233)), closes [#1504](https://github.com/electron-userland/electron-builder/issues/1504)



<a name="17.5.0"></a>
# [17.5.0](https://github.com/electron-userland/electron-builder/compare/v17.4.0...v17.5.0) (2017-05-08)


### Features

* local path to custom electron build (windows support) ([521aea6](https://github.com/electron-userland/electron-builder/commit/521aea6)), closes [#1534](https://github.com/electron-userland/electron-builder/issues/1534) [#1342](https://github.com/electron-userland/electron-builder/issues/1342)



<a name="17.4.0"></a>
# [17.4.0](https://github.com/electron-userland/electron-builder/compare/v17.3.1...v17.4.0) (2017-05-08)


### Features

* **electron-updater:** add proxy authentication support to electron-updater ([a892a5b](https://github.com/electron-userland/electron-builder/commit/a892a5b)), closes [#1530](https://github.com/electron-userland/electron-builder/issues/1530)
* **nsis:** add de, it, fr, hu, pl translations for one-click installer ([d8aa078](https://github.com/electron-userland/electron-builder/commit/d8aa078))



<a name="17.3.1"></a>
## [17.3.1](https://github.com/electron-userland/electron-builder/compare/v17.3.0...v17.3.1) (2017-05-05)


### Bug Fixes

* Make sure the documentation for this option clearly states the security implications of turning it on #1524 ([b0ce309](https://github.com/electron-userland/electron-builder/commit/b0ce309))
* Use of extraResources prevents node_modules from being included in asar ([0fbad33](https://github.com/electron-userland/electron-builder/commit/0fbad33)), closes [#867](https://github.com/electron-userland/electron-builder/issues/867)



<a name="17.3.0"></a>
# [17.3.0](https://github.com/electron-userland/electron-builder/compare/v17.2.0...v17.3.0) (2017-05-04)


### Bug Fixes

* **electron-updater:** electron-updater v1.14.* throws cannot find module 'debug' ([78d9b33](https://github.com/electron-userland/electron-builder/commit/78d9b33)), closes [#1521](https://github.com/electron-userland/electron-builder/issues/1521)


### Features

* ${buildVersion} macro in artifactName config ([23f0b37](https://github.com/electron-userland/electron-builder/commit/23f0b37)), closes [#1527](https://github.com/electron-userland/electron-builder/issues/1527)
* **mac:** allow build for pull requests / code sign artifacts ([9dbc789](https://github.com/electron-userland/electron-builder/commit/9dbc789)), closes [#1524](https://github.com/electron-userland/electron-builder/issues/1524)



<a name="17.2.0"></a>
# [17.2.0](https://github.com/electron-userland/electron-builder/compare/v17.1.2...v17.2.0) (2017-05-02)


### Features

* **forge:** support electron-forge 3.0 API ([002a714](https://github.com/electron-userland/electron-builder/commit/002a714))
* **nsis:** multi-lang one-click installer (including custom string) ([f01415a](https://github.com/electron-userland/electron-builder/commit/f01415a))



<a name="17.1.2"></a>
## [17.1.2](https://github.com/electron-userland/electron-builder/compare/v17.1.1...v17.1.2) (2017-04-26)


### Bug Fixes

* Cannot copy files from parent directory of build output ([7f00714](https://github.com/electron-userland/electron-builder/commit/7f00714)), closes [#1482](https://github.com/electron-userland/electron-builder/issues/1482)



<a name="17.1.1"></a>
## [17.1.1](https://github.com/electron-userland/electron-builder/compare/v17.1.0...v17.1.1) (2017-04-24)


### Bug Fixes

* **auto-updater:** Autoupdates to lower version with allowPrerelease=true using GitHub releases ([36fc3db](https://github.com/electron-userland/electron-builder/commit/36fc3db)), closes [#1497](https://github.com/electron-userland/electron-builder/issues/1497)
* **dmg:** license ([5a163df](https://github.com/electron-userland/electron-builder/commit/5a163df)), closes [#1491](https://github.com/electron-userland/electron-builder/issues/1491)



<a name="17.1.0"></a>
# [17.1.0](https://github.com/electron-userland/electron-builder/compare/v17.0.3...v17.1.0) (2017-04-23)


### Features

* **dmg:** dmg license ([d6f0c57](https://github.com/electron-userland/electron-builder/commit/d6f0c57)), closes [#1491](https://github.com/electron-userland/electron-builder/issues/1491)



<a name="17.0.3"></a>
## [17.0.3](https://github.com/electron-userland/electron-builder/compare/v17.0.1...v17.0.3) (2017-04-22)


### Bug Fixes

* Upload release failed. Response status: 401 Unauthorized ([257a7dd](https://github.com/electron-userland/electron-builder/commit/257a7dd)), closes [#1385](https://github.com/electron-userland/electron-builder/issues/1385)
* **electron-updater:** Incorrect comparison of version numbers (electron-updater) ([17ac619](https://github.com/electron-userland/electron-builder/commit/17ac619)), closes [#1488](https://github.com/electron-userland/electron-builder/issues/1488)


### Features

* **electron-updater:** GitHub: Allow pre-release builds to be auto updated ([f275831](https://github.com/electron-userland/electron-builder/commit/f275831)), closes [#1391](https://github.com/electron-userland/electron-builder/issues/1391)
* support additional certificate file (#1467) ([19c8ee4](https://github.com/electron-userland/electron-builder/commit/19c8ee4))



<a name="17.0.1"></a>
## [17.0.1](https://github.com/electron-userland/electron-builder/compare/v17.0.0...v17.0.1) (2017-04-16)


### Bug Fixes

* handle sync spawn error ([4351b56](https://github.com/electron-userland/electron-builder/commit/4351b56)), closes [#1460](https://github.com/electron-userland/electron-builder/issues/1460)
* handle sync spawn error ([af14809](https://github.com/electron-userland/electron-builder/commit/af14809)), closes [#1438](https://github.com/electron-userland/electron-builder/issues/1438)


### Features

* **electron-updater:** Make it possible to "auto-downgrade" the application on channel change ([a3c4a9e](https://github.com/electron-userland/electron-builder/commit/a3c4a9e)), closes [#1149](https://github.com/electron-userland/electron-builder/issues/1149)



<a name="17.0.0"></a>
# [17.0.0](https://github.com/electron-userland/electron-builder/compare/v16.8.4...v17.0.0) (2017-04-15)


### Features

* automatically set channel to version prerelease component ([831186f](https://github.com/electron-userland/electron-builder/commit/831186f)), closes [#1182](https://github.com/electron-userland/electron-builder/issues/1182)


### BREAKING CHANGES

* if app version is `0.12.1-alpha.1`, file `alpha.yml` will be generated instead of `latest.yml`



<a name="16.8.4"></a>
## [16.8.4](https://github.com/electron-userland/electron-builder/compare/v16.8.3...v16.8.4) (2017-04-15)


### Bug Fixes

* Rebuild stucks on Windows ([2c52ed2](https://github.com/electron-userland/electron-builder/commit/2c52ed2)), closes [#1472](https://github.com/electron-userland/electron-builder/issues/1472)



<a name="16.8.3"></a>
## [16.8.3](https://github.com/electron-userland/electron-builder/compare/v16.8.2...v16.8.3) (2017-04-12)


### Bug Fixes

* **rebuild:** Log stdout and stderr (#1450) ([ada9cac](https://github.com/electron-userland/electron-builder/commit/ada9cac))
* **snap:** fix appindicator icons with snap build (#1453) ([2ab769d](https://github.com/electron-userland/electron-builder/commit/2ab769d)), closes [#1453](https://github.com/electron-userland/electron-builder/issues/1453) [#1452](https://github.com/electron-userland/electron-builder/issues/1452)
* do not use scoped electron-download ([8c79f60](https://github.com/electron-userland/electron-builder/commit/8c79f60)), closes [#1458](https://github.com/electron-userland/electron-builder/issues/1458)


### Features

* **electron-updater:** Location of app-update.yml in the dev mode ([8c73f57](https://github.com/electron-userland/electron-builder/commit/8c73f57)), closes [#1254](https://github.com/electron-userland/electron-builder/issues/1254)


### Performance Improvements

* **nsis:** run tasks in parallel ([6f56905](https://github.com/electron-userland/electron-builder/commit/6f56905))



<a name="16.8.2"></a>
## [16.8.2](https://github.com/electron-userland/electron-builder/compare/v16.8.1...v16.8.2) (2017-04-09)


### Bug Fixes

* **nsis:** move generated custom messages to separate files (to avoid stdin encoding issues on Windows) ([5b83860](https://github.com/electron-userland/electron-builder/commit/5b83860)), closes [#1447](https://github.com/electron-userland/electron-builder/issues/1447)



<a name="16.8.1"></a>
## [16.8.1](https://github.com/electron-userland/electron-builder/compare/v16.8.0...v16.8.1) (2017-04-09)


### Bug Fixes

* fix incorrect rebuild target in install-app-deps ([88e52ad](https://github.com/electron-userland/electron-builder/commit/88e52ad))



<a name="16.8.0"></a>
# [16.8.0](https://github.com/electron-userland/electron-builder/compare/v16.7.1...v16.8.0) (2017-04-08)


### Bug Fixes

* **nsis:** build portable in parallel to nsis ([918a317](https://github.com/electron-userland/electron-builder/commit/918a317)), closes [#1340](https://github.com/electron-userland/electron-builder/issues/1340)


### Features

* **muon:** Rebuilding the native dependencies for muon ([3232f65](https://github.com/electron-userland/electron-builder/commit/3232f65)), closes [#1404](https://github.com/electron-userland/electron-builder/issues/1404)
* **portable:** ExecutionLevel for nsis portable ([3f8caab](https://github.com/electron-userland/electron-builder/commit/3f8caab)), closes [#1440](https://github.com/electron-userland/electron-builder/issues/1440)



<a name="16.7.1"></a>
## [16.7.1](https://github.com/electron-userland/electron-builder/compare/v16.7.0...v16.7.1) (2017-04-07)


### Bug Fixes

* **deb:** add libxss1 to depends by default ([897fcf2](https://github.com/electron-userland/electron-builder/commit/897fcf2))
* **s3:** S3-DEPLOY with parenthesis / spaces in product name broken in 1.6.2 ([26ae6ec](https://github.com/electron-userland/electron-builder/commit/26ae6ec)), closes [#1439](https://github.com/electron-userland/electron-builder/issues/1439)



<a name="16.7.0"></a>
# [16.7.0](https://github.com/electron-userland/electron-builder/compare/v16.6.2...v16.7.0) (2017-04-05)


### Bug Fixes

* **linux:** depends for deb in LinuxOptions ([d58d323](https://github.com/electron-userland/electron-builder/commit/d58d323)), closes [#1420](https://github.com/electron-userland/electron-builder/issues/1420)


### Features

* **nsis:** add --no-desktop-shortcut argument (#1432) ([e1e3832](https://github.com/electron-userland/electron-builder/commit/e1e3832))



<a name="16.6.2"></a>
## [16.6.2](https://github.com/electron-userland/electron-builder/compare/v16.6.1...v16.6.2) (2017-04-04)


### Bug Fixes

* **deployment:** S3 won't upload app files ([4149031](https://github.com/electron-userland/electron-builder/commit/4149031)), closes [#1331](https://github.com/electron-userland/electron-builder/issues/1331)



<a name="16.6.1"></a>
## [16.6.1](https://github.com/electron-userland/electron-builder/compare/v16.6.0...v16.6.1) (2017-04-01)


### Bug Fixes

* **auto-updater:** respect vPrefixedTagName for auto update ([624311b](https://github.com/electron-userland/electron-builder/commit/624311b)), closes [#1417](https://github.com/electron-userland/electron-builder/issues/1417)
* ignore files in the node_modules during read_installed ([37f84b9](https://github.com/electron-userland/electron-builder/commit/37f84b9)), closes [#1424](https://github.com/electron-userland/electron-builder/issues/1424)


### Features

* **mac:** mac build zip file name does not follow build.artifactName ([1affc61](https://github.com/electron-userland/electron-builder/commit/1affc61)), closes [#1398](https://github.com/electron-userland/electron-builder/issues/1398)
* retry code sign if failed due to network failure ([9b60518](https://github.com/electron-userland/electron-builder/commit/9b60518)), closes [#1414](https://github.com/electron-userland/electron-builder/issues/1414)



<a name="16.6.0"></a>
# [16.6.0](https://github.com/electron-userland/electron-builder/compare/v16.5.1...v16.6.0) (2017-03-29)



<a name="16.5.1"></a>
## [16.5.1](https://github.com/electron-userland/electron-builder/compare/v16.5.0...v16.5.1) (2017-03-28)


### Bug Fixes

* **nsis:** StartApp doesn't work if menuCategory used ([683d58c](https://github.com/electron-userland/electron-builder/commit/683d58c)), closes [#1151](https://github.com/electron-userland/electron-builder/issues/1151) [#1412](https://github.com/electron-userland/electron-builder/issues/1412)



<a name="16.5.0"></a>
# [16.5.0](https://github.com/electron-userland/electron-builder/compare/v16.4.2...v16.5.0) (2017-03-28)


### Features

* Enforce a proper application location ([958a7ae](https://github.com/electron-userland/electron-builder/commit/958a7ae)), closes [#1301](https://github.com/electron-userland/electron-builder/issues/1301) [#1298](https://github.com/electron-userland/electron-builder/issues/1298)
* **linux:** support any icon name ([5a2631c](https://github.com/electron-userland/electron-builder/commit/5a2631c)), closes [#1399](https://github.com/electron-userland/electron-builder/issues/1399)



<a name="16.4.2"></a>
## [16.4.2](https://github.com/electron-userland/electron-builder/compare/v16.4.1...v16.4.2) (2017-03-27)


### Bug Fixes

* Asar: false, causing exception on app startup with v16.4.0 ([7c6b4ab](https://github.com/electron-userland/electron-builder/commit/7c6b4ab)), closes [#1409](https://github.com/electron-userland/electron-builder/issues/1409)



<a name="16.4.1"></a>
## [16.4.1](https://github.com/electron-userland/electron-builder/compare/v16.4.0...v16.4.1) (2017-03-27)


### Bug Fixes

* removing devDependencies from package.json breaks levelup in electron ([0278efb](https://github.com/electron-userland/electron-builder/commit/0278efb)), closes [#1408](https://github.com/electron-userland/electron-builder/issues/1408)



<a name="16.4.0"></a>
# [16.4.0](https://github.com/electron-userland/electron-builder/compare/v16.3.0...v16.4.0) (2017-03-25)


### Bug Fixes

* ${arch} missing from app-update.yml ([77558e6](https://github.com/electron-userland/electron-builder/commit/77558e6)), closes [#1389](https://github.com/electron-userland/electron-builder/issues/1389)
* Builds fail on building .deb using packaged fpm on Travis ([037fba6](https://github.com/electron-userland/electron-builder/commit/037fba6)), closes [#1402](https://github.com/electron-userland/electron-builder/issues/1402)
* electron-updater throws "Cannot find namespace 'debug'" on TypeScript compile ([0f0de81](https://github.com/electron-userland/electron-builder/commit/0f0de81)), closes [#1405](https://github.com/electron-userland/electron-builder/issues/1405)


### Features

* electronCompile option to disable electron-compile integration ([b4462a2](https://github.com/electron-userland/electron-builder/commit/b4462a2))



<a name="16.3.0"></a>
# [16.3.0](https://github.com/electron-userland/electron-builder/compare/v16.2.1...v16.3.0) (2017-03-24)


### Bug Fixes

* compile using electron-compile not in place, but using cache ([08893e3](https://github.com/electron-userland/electron-builder/commit/08893e3)), closes [#807](https://github.com/electron-userland/electron-builder/issues/807)


### Features

* Allow to use ~/.aws/credentials file as alternative to env variables ([2e59959](https://github.com/electron-userland/electron-builder/commit/2e59959)), closes [#1320](https://github.com/electron-userland/electron-builder/issues/1320)



<a name="16.2.1"></a>
## [16.2.1](https://github.com/electron-userland/electron-builder/compare/v16.2.0...v16.2.1) (2017-03-23)


### Bug Fixes

* one file in asar archive got corrupted ([e208f53](https://github.com/electron-userland/electron-builder/commit/e208f53)), closes [#1400](https://github.com/electron-userland/electron-builder/issues/1400)
* use Muon version in the log message if pack for Muon ([4241521](https://github.com/electron-userland/electron-builder/commit/4241521))



<a name="16.2.0"></a>
# [16.2.0](https://github.com/electron-userland/electron-builder/compare/v16.1.0...v16.2.0) (2017-03-22)


### Bug Fixes

* use lowercased safe artifact name if app name is lowercased ([bfd6635](https://github.com/electron-userland/electron-builder/commit/bfd6635))


### Features

* electron-forge support ([d99a27e](https://github.com/electron-userland/electron-builder/commit/d99a27e))



<a name="16.1.0"></a>
# [16.1.0](https://github.com/electron-userland/electron-builder/compare/v16.0.1...v16.1.0) (2017-03-22)


### Bug Fixes

* Download update from public Github repo failed on Mac ([16bc53c](https://github.com/electron-userland/electron-builder/commit/16bc53c)), closes [#1388](https://github.com/electron-userland/electron-builder/issues/1388)


### Features

* muon support ([4f555da](https://github.com/electron-userland/electron-builder/commit/4f555da)), closes [#1394](https://github.com/electron-userland/electron-builder/issues/1394)
* support file transformers not only for asar ([58061ec](https://github.com/electron-userland/electron-builder/commit/58061ec))



<a name="16.0.1"></a>
## [16.0.1](https://github.com/electron-userland/electron-builder/compare/v16.0.0...v16.0.1) (2017-03-21)


### Bug Fixes

* detect electron-compile in the dev deps ([0b8bff4](https://github.com/electron-userland/electron-builder/commit/0b8bff4))



<a name="16.0.0"></a>
# [16.0.0](https://github.com/electron-userland/electron-builder/compare/v15.6.3...v16.0.0) (2017-03-21)


### Bug Fixes

* S3 urls on mac ([55ebed1](https://github.com/electron-userland/electron-builder/commit/55ebed1)), closes [#1386](https://github.com/electron-userland/electron-builder/issues/1386)


### Features

* electron-compile support ([0b9b1fd](https://github.com/electron-userland/electron-builder/commit/0b9b1fd)), closes [#807](https://github.com/electron-userland/electron-builder/issues/807)



<a name="15.6.3"></a>
## [15.6.3](https://github.com/electron-userland/electron-builder/compare/v15.6.1...v15.6.3) (2017-03-18)


### Bug Fixes

* **updater:** GitHub private repo for windows (#1382) ([51d6e41](https://github.com/electron-userland/electron-builder/commit/51d6e41))
* improve debuggability — print effective config if debug enabled ([927ac40](https://github.com/electron-userland/electron-builder/commit/927ac40))



<a name="15.6.1"></a>
## [15.6.1](https://github.com/electron-userland/electron-builder/compare/v15.6.0...v15.6.1) (2017-03-17)


### Bug Fixes

* S3 URLs (#1373) (#1374) ([ac75e8c](https://github.com/electron-userland/electron-builder/commit/ac75e8c)), closes [#1373](https://github.com/electron-userland/electron-builder/issues/1373)



<a name="15.6.0"></a>
# [15.6.0](https://github.com/electron-userland/electron-builder/compare/v15.5.0...v15.6.0) (2017-03-16)


### Bug Fixes

* productName with utf8 characters cause dmg icon position error ([fbf787c](https://github.com/electron-userland/electron-builder/commit/fbf787c)), closes [#1234](https://github.com/electron-userland/electron-builder/issues/1234)
* removeAuthHeader must strip auth only for AWS ([d7a6760](https://github.com/electron-userland/electron-builder/commit/d7a6760))


### Features

* Multi language support for LICENCES ([bbdc29a](https://github.com/electron-userland/electron-builder/commit/bbdc29a))



<a name="15.5.0"></a>
# [15.5.0](https://github.com/electron-userland/electron-builder/compare/v15.4.3...v15.5.0) (2017-03-15)


### Bug Fixes

* **updater:** github private repo ([fb24e26](https://github.com/electron-userland/electron-builder/commit/fb24e26)), closes [#1370](https://github.com/electron-userland/electron-builder/issues/1370)


### Features

* private GitHub provider ([ce1df10](https://github.com/electron-userland/electron-builder/commit/ce1df10)), closes [#1266](https://github.com/electron-userland/electron-builder/issues/1266)
* **nsis:** do not prompt user to close app before installing on update ([e5682a0](https://github.com/electron-userland/electron-builder/commit/e5682a0)), closes [#1368](https://github.com/electron-userland/electron-builder/issues/1368)



<a name="15.4.3"></a>
## [15.4.3](https://github.com/electron-userland/electron-builder/compare/v15.4.2...v15.4.3) (2017-03-13)


### Bug Fixes

* --ia32 parameter not working as expected anymore ([c37bd00](https://github.com/electron-userland/electron-builder/commit/c37bd00)), closes [#1348](https://github.com/electron-userland/electron-builder/issues/1348)



<a name="15.4.2"></a>
## [15.4.2](https://github.com/electron-userland/electron-builder/compare/v15.4.1...v15.4.2) (2017-03-13)


### Bug Fixes

* artifactName for portable ([8f6247a](https://github.com/electron-userland/electron-builder/commit/8f6247a)), closes [#1340](https://github.com/electron-userland/electron-builder/issues/1340)



<a name="15.4.1"></a>
## [15.4.1](https://github.com/electron-userland/electron-builder/compare/v15.4.0...v15.4.1) (2017-03-13)


### Bug Fixes

* Platform-specific build option targets ignored since 15.2.0 ([2e7b668](https://github.com/electron-userland/electron-builder/commit/2e7b668)), closes [#1355](https://github.com/electron-userland/electron-builder/issues/1355)



<a name="15.4.0"></a>
# [15.4.0](https://github.com/electron-userland/electron-builder/compare/v15.3.0...v15.4.0) (2017-03-12)


### Features

* Don't build when CI run is a pull request ([e1dda14](https://github.com/electron-userland/electron-builder/commit/e1dda14)), closes [#1354](https://github.com/electron-userland/electron-builder/issues/1354)



<a name="15.3.0"></a>
# [15.3.0](https://github.com/electron-userland/electron-builder/compare/v15.2.0...v15.3.0) (2017-03-11)


### Bug Fixes

* **AppImage:** remove nss lib ([0601352](https://github.com/electron-userland/electron-builder/commit/0601352))
* Missing peer dependency: ajv@>=5.0.3-beta.0 ([6d890ee](https://github.com/electron-userland/electron-builder/commit/6d890ee)), closes [#1344](https://github.com/electron-userland/electron-builder/issues/1344)


### Features

* **deployment:** expand macros in all publish options (#1349) ([24fdf1d](https://github.com/electron-userland/electron-builder/commit/24fdf1d))
* **nsis:** always add plugin dir to override nsis plugins ([e8d1d0d](https://github.com/electron-userland/electron-builder/commit/e8d1d0d))



<a name="15.2.0"></a>
# [15.2.0](https://github.com/electron-userland/electron-builder/compare/v15.1.1...v15.2.0) (2017-03-08)


### Bug Fixes

* **linux:** Add dependencies for supporting Electron Tray (libappindicator) & Notifications (libnotify) for more Linux targets (#1339) ([79c94bd](https://github.com/electron-userland/electron-builder/commit/79c94bd)), closes [#1338](https://github.com/electron-userland/electron-builder/issues/1338)


### Features

* Different architectures for different platforms ([f2056fa](https://github.com/electron-userland/electron-builder/commit/f2056fa)), closes [#1314](https://github.com/electron-userland/electron-builder/issues/1314)



<a name="15.1.1"></a>
## [15.1.1](https://github.com/electron-userland/electron-builder/compare/v15.1.0...v15.1.1) (2017-03-06)


### Bug Fixes

* **deployment:** disable automatic detection for S3 ([c4744af](https://github.com/electron-userland/electron-builder/commit/c4744af)), closes [#1334](https://github.com/electron-userland/electron-builder/issues/1334)



<a name="15.1.0"></a>
# [15.1.0](https://github.com/electron-userland/electron-builder/compare/v15.0.1...v15.1.0) (2017-03-06)


### Features

* How to set build_number/FileVersion manually ([3ee8a59](https://github.com/electron-userland/electron-builder/commit/3ee8a59)), closes [#1337](https://github.com/electron-userland/electron-builder/issues/1337)



<a name="15.0.1"></a>
## [15.0.1](https://github.com/electron-userland/electron-builder/compare/v15.0.0...v15.0.1) (2017-03-05)


### Bug Fixes

* writeAsarFile — use close event instead of end ([3f41497](https://github.com/electron-userland/electron-builder/commit/3f41497))



<a name="15.0.0"></a>
# [15.0.0](https://github.com/electron-userland/electron-builder/compare/v14.5.2...v15.0.0) (2017-02-28)


### Bug Fixes

* dmg/pkg in the out dir, not in the subdir mac ([0bba4fe](https://github.com/electron-userland/electron-builder/commit/0bba4fe))
* ensure that out dir exists ([8dd6cd5](https://github.com/electron-userland/electron-builder/commit/8dd6cd5))
* **auto-updater:** handle errors during emit ([ef9b5a6](https://github.com/electron-userland/electron-builder/commit/ef9b5a6)), closes [#1310](https://github.com/electron-userland/electron-builder/issues/1310)


### Features

* **deployment:** support foo/bar repo as short form of owner foo and repo bar ([9d0e1fe](https://github.com/electron-userland/electron-builder/commit/9d0e1fe)), closes [#1227](https://github.com/electron-userland/electron-builder/issues/1227)
* **electron-updater:** find installer exe in bintray artifacts not so strict ([9ac818f](https://github.com/electron-userland/electron-builder/commit/9ac818f)), closes [#1305](https://github.com/electron-userland/electron-builder/issues/1305)


### BREAKING CHANGES

* dmg/pkg in the out dir, not in the subdir mac



<a name="14.5.2"></a>
## [14.5.2](https://github.com/electron-userland/electron-builder/compare/v14.5.1...v14.5.2) (2017-02-28)


### Bug Fixes

* **dmg:** pass -ov flag to overwrite existing dmg ([f4398a7](https://github.com/electron-userland/electron-builder/commit/f4398a7)), closes [#1308](https://github.com/electron-userland/electron-builder/issues/1308)



<a name="14.5.1"></a>
## [14.5.1](https://github.com/electron-userland/electron-builder/compare/v14.5.0...v14.5.1) (2017-02-27)


### Bug Fixes

* directories.output is ignored when building .dmg for a prepackaged app ([3e2798f](https://github.com/electron-userland/electron-builder/commit/3e2798f)), closes [#1308](https://github.com/electron-userland/electron-builder/issues/1308)



<a name="14.5.0"></a>
# [14.5.0](https://github.com/electron-userland/electron-builder/compare/v14.4.2...v14.5.0) (2017-02-27)


### Features

* Allow usage of environmental variables in extraFiles and extraResources ([cfc2715](https://github.com/electron-userland/electron-builder/commit/cfc2715)), closes [#1307](https://github.com/electron-userland/electron-builder/issues/1307)



<a name="14.4.2"></a>
## [14.4.2](https://github.com/electron-userland/electron-builder/compare/v14.4.1...v14.4.2) (2017-02-26)


### Bug Fixes

* **nsis:** update metainfo for nsis-web doesn't use github safe artifact name ([965be90](https://github.com/electron-userland/electron-builder/commit/965be90)), closes [#1227](https://github.com/electron-userland/electron-builder/issues/1227)



<a name="14.4.1"></a>
## [14.4.1](https://github.com/electron-userland/electron-builder/compare/v14.4.0...v14.4.1) (2017-02-25)


### Bug Fixes

* **deployment:** Publishing always fails on circleci #1303 (#1304) ([81b7e46](https://github.com/electron-userland/electron-builder/commit/81b7e46)), closes [#1303](https://github.com/electron-userland/electron-builder/issues/1303)



<a name="14.4.0"></a>
# [14.4.0](https://github.com/electron-userland/electron-builder/compare/v14.3.0...v14.4.0) (2017-02-24)


### Bug Fixes

* Issue with extraFiles not being valid ([f137193](https://github.com/electron-userland/electron-builder/commit/f137193)), closes [#1302](https://github.com/electron-userland/electron-builder/issues/1302)


### Features

* **windows:** Portable Build ([6292855](https://github.com/electron-userland/electron-builder/commit/6292855)), closes [#1157](https://github.com/electron-userland/electron-builder/issues/1157)



<a name="14.3.0"></a>
# [14.3.0](https://github.com/electron-userland/electron-builder/compare/v14.2.0...v14.3.0) (2017-02-24)


### Bug Fixes

* **snap:** allow to set `classic` confinement ([f1d524a](https://github.com/electron-userland/electron-builder/commit/f1d524a))


### Features

* **nsis:** Add option to define custom files to be removed instead of just nuking installation directory ([09f7fde](https://github.com/electron-userland/electron-builder/commit/09f7fde))



<a name="14.2.0"></a>
# [14.2.0](https://github.com/electron-userland/electron-builder/compare/v14.1.1...v14.2.0) (2017-02-24)


### Bug Fixes

* **deployment:** warn if cannot resolve repository ([3fa6259](https://github.com/electron-userland/electron-builder/commit/3fa6259))
* **linux:** use executableName as specified and do not lowercase it ([79077bf](https://github.com/electron-userland/electron-builder/commit/79077bf)), closes [#1291](https://github.com/electron-userland/electron-builder/issues/1291)
* **nsis:** Incorrect app-update.yml for Windows 32bit ([5cfc693](https://github.com/electron-userland/electron-builder/commit/5cfc693)), closes [#1282](https://github.com/electron-userland/electron-builder/issues/1282)


### Features

* **windows:** Support passing the `sha1` of a certificate in Windows codesign ([4be81dc](https://github.com/electron-userland/electron-builder/commit/4be81dc)), closes [#1297](https://github.com/electron-userland/electron-builder/issues/1297)



<a name="14.1.1"></a>
## [14.1.1](https://github.com/electron-userland/electron-builder/compare/v14.1.0...v14.1.1) (2017-02-22)


### Bug Fixes

* Build with prepackaged app doesn't do anything for mac #1284 ([0be724d](https://github.com/electron-userland/electron-builder/commit/0be724d))



<a name="14.1.0"></a>
# [14.1.0](https://github.com/electron-userland/electron-builder/compare/v14.0.1...v14.1.0) (2017-02-22)


### Features

* **AppImage:** Fedora support ([ca7745d](https://github.com/electron-userland/electron-builder/commit/ca7745d))



<a name="14.0.1"></a>
## [14.0.1](https://github.com/electron-userland/electron-builder/compare/v14.0.0...v14.0.1) (2017-02-22)


### Features

* validate config using JSON schema ([d65f8c3](https://github.com/electron-userland/electron-builder/commit/d65f8c3)), closes [#1292](https://github.com/electron-userland/electron-builder/issues/1292) [#1290](https://github.com/electron-userland/electron-builder/issues/1290)



<a name="14.0.0"></a>
# [14.0.0](https://github.com/electron-userland/electron-builder/compare/v13.11.1...v14.0.0) (2017-02-21)


### Features

* **AppImage:** ElementaryOS and libappindicator1 support by default ([580eeaa](https://github.com/electron-userland/electron-builder/commit/580eeaa)), closes [#1082](https://github.com/electron-userland/electron-builder/issues/1082)



<a name="13.11.1"></a>
## [13.11.1](https://github.com/electron-userland/electron-builder/compare/v13.11.0...v13.11.1) (2017-02-20)


### Bug Fixes

* **mac:** dist app quit unexpectedly caused by productName ([3a1042a](https://github.com/electron-userland/electron-builder/commit/3a1042a)), closes [#1278](https://github.com/electron-userland/electron-builder/issues/1278)



<a name="13.11.0"></a>
# [13.11.0](https://github.com/electron-userland/electron-builder/compare/v13.10.1...v13.11.0) (2017-02-19)


### Features

* icon relative or to build resources, or to project ([3f3419a](https://github.com/electron-userland/electron-builder/commit/3f3419a)), closes [#1276](https://github.com/electron-userland/electron-builder/issues/1276)



<a name="13.10.1"></a>
## [13.10.1](https://github.com/electron-userland/electron-builder/compare/v13.10.0...v13.10.1) (2017-02-18)



<a name="13.10.0"></a>
# [13.10.0](https://github.com/electron-userland/electron-builder/compare/v13.9.0...v13.10.0) (2017-02-17)


### Bug Fixes

* increase maxBuffer for xorriso child process (#1274) ([bce672e](https://github.com/electron-userland/electron-builder/commit/bce672e))


### Features

* make description optional (just a warning) ([ae036c6](https://github.com/electron-userland/electron-builder/commit/ae036c6))
* **electron-updater:** abort download ([91613a9](https://github.com/electron-userland/electron-builder/commit/91613a9)), closes [#1150](https://github.com/electron-userland/electron-builder/issues/1150)
* **nsis:** NSIS Special Builds set NSIS_MAX_STRLEN flag ([498db5d](https://github.com/electron-userland/electron-builder/commit/498db5d)), closes [#1267](https://github.com/electron-userland/electron-builder/issues/1267)



<a name="13.9.0"></a>
# [13.9.0](https://github.com/electron-userland/electron-builder/compare/v13.8.2...v13.9.0) (2017-02-15)


### Features

* **snap:** snapcraft 2.26 support ([9c69ce4](https://github.com/electron-userland/electron-builder/commit/9c69ce4)), closes [#1265](https://github.com/electron-userland/electron-builder/issues/1265)
* Different icons for application/file extension with same name on macOS and Windows ([04f11f6](https://github.com/electron-userland/electron-builder/commit/04f11f6)), closes [#1268](https://github.com/electron-userland/electron-builder/issues/1268)



<a name="13.8.2"></a>
## [13.8.2](https://github.com/electron-userland/electron-builder/compare/v13.8.1...v13.8.2) (2017-02-15)


### Bug Fixes

* electron-builder.* config file resolution ([481dfa2](https://github.com/electron-userland/electron-builder/commit/481dfa2))



<a name="13.8.1"></a>
## [13.8.1](https://github.com/electron-userland/electron-builder/compare/v13.8.0...v13.8.1) (2017-02-15)


### Bug Fixes

* ${os} pattern in artifactName does not follow wiki ([38339b9](https://github.com/electron-userland/electron-builder/commit/38339b9)), closes [#1263](https://github.com/electron-userland/electron-builder/issues/1263)
* artifactName option does not work in build section ([6224060](https://github.com/electron-userland/electron-builder/commit/6224060)), closes [#1262](https://github.com/electron-userland/electron-builder/issues/1262)


### Features

* **mac:** The extra entries for `Info.plist` ([1a33a34](https://github.com/electron-userland/electron-builder/commit/1a33a34))



<a name="13.8.0"></a>
# [13.8.0](https://github.com/electron-userland/electron-builder/compare/v13.7.0...v13.8.0) (2017-02-15)


### Bug Fixes

* from as file and to as dir ([3bb2ab8](https://github.com/electron-userland/electron-builder/commit/3bb2ab8)), closes [#1245](https://github.com/electron-userland/electron-builder/issues/1245)


### Features

* **nsis:** metro sidebar, customizable sidebar ([969c0eb](https://github.com/electron-userland/electron-builder/commit/969c0eb)), closes [#1248](https://github.com/electron-userland/electron-builder/issues/1248)



<a name="13.7.0"></a>
# [13.7.0](https://github.com/electron-userland/electron-builder/compare/v13.6.0...v13.7.0) (2017-02-14)


### Bug Fixes

* **electron-updater:** fix missed path in the log messages ([8a75cbb](https://github.com/electron-userland/electron-builder/commit/8a75cbb))
* **squirrel.windows:** sign the Squirrel.Windows executableStub ([c732db2](https://github.com/electron-userland/electron-builder/commit/c732db2)), closes [#1251](https://github.com/electron-userland/electron-builder/issues/1251)


### Features

* **nsins:** create pre initialization hook in installer.nsi (#1255) ([7ed9d7a](https://github.com/electron-userland/electron-builder/commit/7ed9d7a))
* **nsis:** option to delete app data on manual uninstall ([2e1b21e](https://github.com/electron-userland/electron-builder/commit/2e1b21e)), closes [#885](https://github.com/electron-userland/electron-builder/issues/885)



<a name="13.6.0"></a>
# [13.6.0](https://github.com/electron-userland/electron-builder/compare/v13.5.0...v13.6.0) (2017-02-13)


### Bug Fixes

* Incorrect error message ([bc0952e](https://github.com/electron-userland/electron-builder/commit/bc0952e)), closes [#1236](https://github.com/electron-userland/electron-builder/issues/1236)
* **deployment:** NSIS Web Installer update info is not generated #1207 ([9f7c825](https://github.com/electron-userland/electron-builder/commit/9f7c825))
* **electron-updater:** Github Update Fails Due to Undefined ([591873a](https://github.com/electron-userland/electron-builder/commit/591873a)), closes [#1228](https://github.com/electron-userland/electron-builder/issues/1228)
* **nsis:** Custom NSIS Script !include could not find nsh file ([3fbf113](https://github.com/electron-userland/electron-builder/commit/3fbf113)), closes [#1239](https://github.com/electron-userland/electron-builder/issues/1239)


### Features

* **electron-updater:** include full GitHub request url in the error message ([a7d2992](https://github.com/electron-userland/electron-builder/commit/a7d2992))
* **linux:** assert that linux.icon is a directory ([5352b8c](https://github.com/electron-userland/electron-builder/commit/5352b8c)), closes [#1242](https://github.com/electron-userland/electron-builder/issues/1242)
* --config option ([472ef7e](https://github.com/electron-userland/electron-builder/commit/472ef7e)), closes [#1229](https://github.com/electron-userland/electron-builder/issues/1229)
* --config option ([a9f2ad8](https://github.com/electron-userland/electron-builder/commit/a9f2ad8))



<a name="13.5.0"></a>
# [13.5.0](https://github.com/electron-userland/electron-builder/compare/v13.4.0...v13.5.0) (2017-02-10)


### Features

* **nsis:** unicode option High Windows defender CPU usage when accessing NSIS installer ([0e9059c](https://github.com/electron-userland/electron-builder/commit/0e9059c)), closes [#1165](https://github.com/electron-userland/electron-builder/issues/1165)



<a name="13.4.0"></a>
# [13.4.0](https://github.com/electron-userland/electron-builder/compare/v13.3.1...v13.4.0) (2017-02-10)


### Bug Fixes

* identity = null is not respected ([3df2638](https://github.com/electron-userland/electron-builder/commit/3df2638)), closes [#1233](https://github.com/electron-userland/electron-builder/issues/1233)


### Features

* artifact file name pattern for pkg and dmg ([22746bd](https://github.com/electron-userland/electron-builder/commit/22746bd)), closes [#966](https://github.com/electron-userland/electron-builder/issues/966)
* **nsis:** NSIS Web Installer ([7041b5d](https://github.com/electron-userland/electron-builder/commit/7041b5d)), closes [#1207](https://github.com/electron-userland/electron-builder/issues/1207)



<a name="13.3.1"></a>
## [13.3.1](https://github.com/electron-userland/electron-builder/compare/v13.2.0...v13.3.1) (2017-02-09)


### Features

* **deb:** "Priority" attribute for .deb packages ([6497678](https://github.com/electron-userland/electron-builder/commit/6497678)), closes [#1088](https://github.com/electron-userland/electron-builder/issues/1088)
* **pkg:** preinstall and postinstall scripts ([2eb1298](https://github.com/electron-userland/electron-builder/commit/2eb1298)), closes [#1166](https://github.com/electron-userland/electron-builder/issues/1166)
* GitHub Enterprise support ([7cae06a](https://github.com/electron-userland/electron-builder/commit/7cae06a)), closes [#1225](https://github.com/electron-userland/electron-builder/issues/1225)
* **snap:** custom plugs ([3aed0b5](https://github.com/electron-userland/electron-builder/commit/3aed0b5)), closes [#1226](https://github.com/electron-userland/electron-builder/issues/1226)



<a name="13.2.0"></a>
# [13.2.0](https://github.com/electron-userland/electron-builder/compare/v13.1.0...v13.2.0) (2017-02-08)


### Bug Fixes

* **deployment:** log about uploading if non TTY stream ([4546b1c](https://github.com/electron-userland/electron-builder/commit/4546b1c))


### Features

* **nsis:** artifact file name pattern ([3d39fa6](https://github.com/electron-userland/electron-builder/commit/3d39fa6)), closes [#1221](https://github.com/electron-userland/electron-builder/issues/1221) [#1219](https://github.com/electron-userland/electron-builder/issues/1219)



<a name="13.1.0"></a>
# [13.1.0](https://github.com/electron-userland/electron-builder/compare/v13.0.0...v13.1.0) (2017-02-07)


### Features

* S3 AWS Publishing ([fd4fc0f](https://github.com/electron-userland/electron-builder/commit/fd4fc0f))
* cancellable and progressable publishing ([a24f12c](https://github.com/electron-userland/electron-builder/commit/a24f12c))



<a name="13.0.0"></a>
# [13.0.0](https://github.com/electron-userland/electron-builder/compare/v12.3.1...v13.0.0) (2017-02-04)


### Bug Fixes

* **nsis:** Application Icon Missing from "Remove Programs" and "Settings->Apps & Features" ([9c62be9](https://github.com/electron-userland/electron-builder/commit/9c62be9)), closes [#1108](https://github.com/electron-userland/electron-builder/issues/1108)


### Features

* Remove scripts, devDependencies and build from package.json ([ab41fcf](https://github.com/electron-userland/electron-builder/commit/ab41fcf)), closes [#1212](https://github.com/electron-userland/electron-builder/issues/1212)


### BREAKING CHANGES

* `scripts`, `devDependencies` and `build` automatically removed from package.json



<a name="12.3.1"></a>
## [12.3.1](https://github.com/electron-userland/electron-builder/compare/v12.3.0...v12.3.1) (2017-02-03)


### Bug Fixes

* macOS Auto updater using old update ([4e63640](https://github.com/electron-userland/electron-builder/commit/4e63640)), closes [#1200](https://github.com/electron-userland/electron-builder/issues/1200)
* **electron-updater:** channel & channelFile mismatch for macOS GenericProvider publishing (#1203) (#1206) ([f23daff](https://github.com/electron-userland/electron-builder/commit/f23daff))



<a name="12.3.0"></a>
# [12.3.0](https://github.com/electron-userland/electron-builder/compare/v12.2.0...v12.3.0) (2017-02-02)


### Bug Fixes

* **deployment:** Artifacts still get pushed to github releases marked as published ([3987b06](https://github.com/electron-userland/electron-builder/commit/3987b06)), closes [#1197](https://github.com/electron-userland/electron-builder/issues/1197)


### Features

* **electron-updater:** add releaseNotes and releaseName to autoUpdate ([45c93bf](https://github.com/electron-userland/electron-builder/commit/45c93bf)), closes [#1174](https://github.com/electron-userland/electron-builder/issues/1174)
* build prepackaged app.asar ([60e1406](https://github.com/electron-userland/electron-builder/commit/60e1406)), closes [#1102](https://github.com/electron-userland/electron-builder/issues/1102)



<a name="12.2.0"></a>
# [12.2.0](https://github.com/electron-userland/electron-builder/compare/v12.1.0...v12.2.0) (2017-02-01)


### Bug Fixes

* **electron-updater:** Autoupdater problem on mac if space in the URL ([e5d58e2](https://github.com/electron-userland/electron-builder/commit/e5d58e2)), closes [#1192](https://github.com/electron-userland/electron-builder/issues/1192)


### Features

* **linux:** ability to specify custom path to linux icon set ([a2f64bb](https://github.com/electron-userland/electron-builder/commit/a2f64bb)), closes [#1176](https://github.com/electron-userland/electron-builder/issues/1176)
* ${os} and ${arch} in publish.url ([6863896](https://github.com/electron-userland/electron-builder/commit/6863896)), closes [#1194](https://github.com/electron-userland/electron-builder/issues/1194)



<a name="12.1.0"></a>
# [12.1.0](https://github.com/electron-userland/electron-builder/compare/v12.0.3...v12.1.0) (2017-01-31)


### Bug Fixes

* always revalidate cache ([02a96f4](https://github.com/electron-userland/electron-builder/commit/02a96f4)), closes [#1186](https://github.com/electron-userland/electron-builder/issues/1186)


### Features

* allow `./` in the file pattern ([1152f2b](https://github.com/electron-userland/electron-builder/commit/1152f2b))
* file mappings ([55e2f0d](https://github.com/electron-userland/electron-builder/commit/55e2f0d)), closes [#1119](https://github.com/electron-userland/electron-builder/issues/1119)



<a name="12.0.3"></a>
## [12.0.3](https://github.com/electron-userland/electron-builder/compare/v12.0.2...v12.0.3) (2017-01-29)


### Features

* **nsis:** Pass --update flag to uninstaller when auto updating an application ([505a63d](https://github.com/electron-userland/electron-builder/commit/505a63d)), closes [#1162](https://github.com/electron-userland/electron-builder/issues/1162)



<a name="12.0.2"></a>
## [12.0.2](https://github.com/electron-userland/electron-builder/compare/v12.0.1...v12.0.2) (2017-01-29)


### Bug Fixes

* **deployment:** warn "A release is already published" instead of error ([5d64693](https://github.com/electron-userland/electron-builder/commit/5d64693)), closes [#1183](https://github.com/electron-userland/electron-builder/issues/1183)
* **nsis:** add `+` as safe symbol for product name ([e7e2a82](https://github.com/electron-userland/electron-builder/commit/e7e2a82))
* deepAssign error without config ([5d72c10](https://github.com/electron-userland/electron-builder/commit/5d72c10)), closes [#1177](https://github.com/electron-userland/electron-builder/issues/1177)


### Features

* **electron-updater:** add requestHeaders option ([dd1320d](https://github.com/electron-userland/electron-builder/commit/dd1320d)), closes [#1175](https://github.com/electron-userland/electron-builder/issues/1175)



<a name="12.0.1"></a>
## [12.0.1](https://github.com/electron-userland/electron-builder/compare/v12.0.0...v12.0.1) (2017-01-27)


### Bug Fixes

* **deployment:** Error on CI build when GH_TOKEN not set for external PRs ([ee32575](https://github.com/electron-userland/electron-builder/commit/ee32575)), closes [#1178](https://github.com/electron-userland/electron-builder/issues/1178)



<a name="12.0.0"></a>
# [12.0.0](https://github.com/electron-userland/electron-builder/compare/v11.7.0...v12.0.0) (2017-01-26)


### Features

* **nsis:** use productName rather than name for install path if matches /^[-_0-9a-zA-Z ]+$/ ([2539cfb](https://github.com/electron-userland/electron-builder/commit/2539cfb)), closes [#1100](https://github.com/electron-userland/electron-builder/issues/1100) [#767](https://github.com/electron-userland/electron-builder/issues/767) [#1104](https://github.com/electron-userland/electron-builder/issues/1104)


### BREAKING CHANGES

* **nsis:** installation path change



<a name="11.7.0"></a>
# [11.7.0](https://github.com/electron-userland/electron-builder/compare/v11.6.1...v11.7.0) (2017-01-26)


### Features

* **nsis:** Show welcome and finish page duing uninstall (#1173) ([aa43344](https://github.com/electron-userland/electron-builder/commit/aa43344))



<a name="11.6.1"></a>
## [11.6.1](https://github.com/electron-userland/electron-builder/compare/v11.6.0...v11.6.1) (2017-01-25)


### Bug Fixes

* Error during signing when running as Windows SYSTEM user ([688111e](https://github.com/electron-userland/electron-builder/commit/688111e)), closes [#1164](https://github.com/electron-userland/electron-builder/issues/1164)



<a name="11.6.0"></a>
# [11.6.0](https://github.com/electron-userland/electron-builder/compare/v11.5.2...v11.6.0) (2017-01-25)


### Features

* **electron-updater:** cannot use updater without administrator privileges ([7c2973d](https://github.com/electron-userland/electron-builder/commit/7c2973d)), closes [#1133](https://github.com/electron-userland/electron-builder/issues/1133)



<a name="11.5.2"></a>
## [11.5.2](https://github.com/electron-userland/electron-builder/compare/v11.5.1...v11.5.2) (2017-01-24)


### Bug Fixes

* **deployment:** another fix for "only first artifact is uploaded to GitHub" ([93b4d59](https://github.com/electron-userland/electron-builder/commit/93b4d59)), closes [#1133](https://github.com/electron-userland/electron-builder/issues/1133)
* **nsis:** Must be error if file association is set, but perMachine not ([96c8ed9](https://github.com/electron-userland/electron-builder/commit/96c8ed9)), closes [#772](https://github.com/electron-userland/electron-builder/issues/772)



<a name="11.5.1"></a>
## [11.5.1](https://github.com/electron-userland/electron-builder/compare/v11.5.0...v11.5.1) (2017-01-21)


### Bug Fixes

* Arch & pacman use i686 instead of i386 and pkg.tar.xz (#1148) ([5fe94ee](https://github.com/electron-userland/electron-builder/commit/5fe94ee))


### Features

* **deployment:** Only first artifact is uploaded to GitHub ([e3ab55b](https://github.com/electron-userland/electron-builder/commit/e3ab55b)), closes [#1133](https://github.com/electron-userland/electron-builder/issues/1133)
* **electron-updater:** NSIS autoUpdater.setFeedURL throws error ([eb6a453](https://github.com/electron-userland/electron-builder/commit/eb6a453)), closes [#1105](https://github.com/electron-userland/electron-builder/issues/1105)



<a name="11.5.0"></a>
# [11.5.0](https://github.com/electron-userland/electron-builder/compare/v11.4.4...v11.5.0) (2017-01-18)


### Bug Fixes

* make file association name optional ([248855c](https://github.com/electron-userland/electron-builder/commit/248855c)), closes [#1069](https://github.com/electron-userland/electron-builder/issues/1069)


### Features

* **electron-updater:** Port support for downloads, Protocol support for generic backend ([8d883f1](https://github.com/electron-userland/electron-builder/commit/8d883f1))



<a name="11.4.4"></a>
## [11.4.4](https://github.com/electron-userland/electron-builder/compare/v11.4.3...v11.4.4) (2017-01-17)


### Bug Fixes

* **publish:** resolve any publish configuration — not only string ([98c2c8e](https://github.com/electron-userland/electron-builder/commit/98c2c8e))



<a name="11.4.3"></a>
## [11.4.3](https://github.com/electron-userland/electron-builder/compare/v11.4.1...v11.4.3) (2017-01-16)


### Bug Fixes

* generate latest-mac.json for github in the github directory ([8670d5a](https://github.com/electron-userland/electron-builder/commit/8670d5a))
* **snap:** interface 'platform' doesn't exist ([ade922c](https://github.com/electron-userland/electron-builder/commit/ade922c)), closes [#1123](https://github.com/electron-userland/electron-builder/issues/1123)



<a name="11.4.1"></a>
## [11.4.1](https://github.com/electron-userland/electron-builder/compare/v11.4.0...v11.4.1) (2017-01-16)


### Bug Fixes

* **AppImage:** include libappindicator1 in AppImage ([df7d316](https://github.com/electron-userland/electron-builder/commit/df7d316)), closes [#1082](https://github.com/electron-userland/electron-builder/issues/1082)



<a name="11.4.0"></a>
# [11.4.0](https://github.com/electron-userland/electron-builder/compare/v11.3.0...v11.4.0) (2017-01-15)


### Bug Fixes

* **squirrel.windows:** Crash after autoupdate downloads nuget package ([d10ba78](https://github.com/electron-userland/electron-builder/commit/d10ba78)), closes [#1101](https://github.com/electron-userland/electron-builder/issues/1101)


### Features

* **electron-updater:** Electron Auto Updater MacOS support ([067d5c7](https://github.com/electron-userland/electron-builder/commit/067d5c7))
* Separate build config from package.json ([ecfdc65](https://github.com/electron-userland/electron-builder/commit/ecfdc65)), closes [#1109](https://github.com/electron-userland/electron-builder/issues/1109)



<a name="11.3.0"></a>
# [11.3.0](https://github.com/electron-userland/electron-builder/compare/v11.2.5...v11.3.0) (2017-01-14)


### Bug Fixes

* **docker:** add missing libcurl3 for osslsigncode (#1116) ([f0a553a](https://github.com/electron-userland/electron-builder/commit/f0a553a))
* **electron-updater:** Add better error handling for github releases (#1114) ([9dc5bc9](https://github.com/electron-userland/electron-builder/commit/9dc5bc9)), closes [#1112](https://github.com/electron-userland/electron-builder/issues/1112)



<a name="11.2.5"></a>
## [11.2.5](https://github.com/electron-userland/electron-builder/compare/v11.2.4...v11.2.5) (2017-01-12)


### Bug Fixes

* **codeSign:** signing with "Mac Developer" failed #1103 ([88682e8](https://github.com/electron-userland/electron-builder/commit/88682e8))



<a name="11.2.4"></a>
## [11.2.4](https://github.com/electron-userland/electron-builder/compare/v11.2.1...v11.2.4) (2017-01-11)



<a name="11.2.1"></a>
## [11.2.1](https://github.com/electron-userland/electron-builder/compare/v11.2.0...v11.2.1) (2017-01-09)


### Bug Fixes

* do not fail if cannot rebuild optional dep ([f67b7d2](https://github.com/electron-userland/electron-builder/commit/f67b7d2)), closes [#1075](https://github.com/electron-userland/electron-builder/issues/1075)



<a name="11.2.0"></a>
# [11.2.0](https://github.com/electron-userland/electron-builder/compare/v11.1.1...v11.2.0) (2017-01-08)


### Bug Fixes

* **electron-auto-updater:** uncaught SHA2 checksum mismatch exception ([cb87588](https://github.com/electron-userland/electron-builder/commit/cb87588))


### Features

* linked dirs outside of projects (e.g. linked modules) ([2364a1c](https://github.com/electron-userland/electron-builder/commit/2364a1c)), closes [#675](https://github.com/electron-userland/electron-builder/issues/675)



<a name="11.1.1"></a>
## [11.1.1](https://github.com/electron-userland/electron-builder/compare/v1.1.1...v11.1.1) (2017-01-06)


### Bug Fixes

* to preserve compatibility with old electron-auto-updater (< 0.10.0), we upload file with path specific for GitHub ([c06f3f4](https://github.com/electron-userland/electron-builder/commit/c06f3f4))



<a name="11.1.0"></a>
# [11.1.0](https://github.com/electron-userland/electron-builder/compare/v11.0.0...v11.1.0) (2017-01-05)


### Features

* **nsis:** Change installation directory when not using 'oneClick' with NSIS ([06b0103](https://github.com/electron-userland/electron-builder/commit/06b0103)), closes [#596](https://github.com/electron-userland/electron-builder/issues/596)



<a name="11.0.0"></a>
# [11.0.0](https://github.com/electron-userland/electron-builder/compare/v10.17.2...v11.0.0) (2017-01-05)


### Bug Fixes

* **electron-builder-http:** electron-auto-updater request can download so fast that the first few chunks arrive before ensureDirPromise has finished for configurePipes to run ([cb85790](https://github.com/electron-userland/electron-builder/commit/cb85790)), closes [#1081](https://github.com/electron-userland/electron-builder/issues/1081)
* electron-builder not generating "latest.yml" file ([0f1fc4d](https://github.com/electron-userland/electron-builder/commit/0f1fc4d)), closes [#925](https://github.com/electron-userland/electron-builder/issues/925)


### Code Refactoring

* extract electron-builder-squirrel-windows ([6256432](https://github.com/electron-userland/electron-builder/commit/6256432))


### Features

* add beforeBuild callback (#1085) ([35a8cdf](https://github.com/electron-userland/electron-builder/commit/35a8cdf)), closes [#982](https://github.com/electron-userland/electron-builder/issues/982)


### BREAKING CHANGES

* To use Squirrel.Windows please install `electron-builder-squirrel-windows` dependency.



<a name="10.17.2"></a>
## [10.17.2](https://github.com/electron-userland/electron-builder/compare/v10.17.0...v10.17.2) (2017-01-04)


### Bug Fixes

* Unhandled rejection SyntaxError: Unexpected token ... ([0c81bf7](https://github.com/electron-userland/electron-builder/commit/0c81bf7)), closes [#1076](https://github.com/electron-userland/electron-builder/issues/1076)
* use transformer to notify about progress ([7fa56bc](https://github.com/electron-userland/electron-builder/commit/7fa56bc)), closes [#1077](https://github.com/electron-userland/electron-builder/issues/1077)
* **dmg:** Can't locate Mac/Finder/DSStore.pm in [@INC](https://github.com/INC) ([8d0e230](https://github.com/electron-userland/electron-builder/commit/8d0e230)), closes [#1079](https://github.com/electron-userland/electron-builder/issues/1079)



<a name="10.17.0"></a>
# [10.17.0](https://github.com/electron-userland/electron-builder/compare/v10.16.0...v10.17.0) (2017-01-03)


### Bug Fixes

* asarUnpack unpacks parent directory when file is specified ([82f16d1](https://github.com/electron-userland/electron-builder/commit/82f16d1)), closes [#1071](https://github.com/electron-userland/electron-builder/issues/1071)


### Features

* **linux:** use ${macro} syntax for linux templates ([fe137fc](https://github.com/electron-userland/electron-builder/commit/fe137fc))



<a name="10.16.0"></a>
# [10.16.0](https://github.com/electron-userland/electron-builder/compare/v10.15.2...v10.16.0) (2017-01-02)


### Features

* **nsis:** allow submenu in start menu in programfiles ([e3faaf1](https://github.com/electron-userland/electron-builder/commit/e3faaf1)), closes [#1063](https://github.com/electron-userland/electron-builder/issues/1063)



<a name="10.15.2"></a>
## [10.15.2](https://github.com/electron-userland/electron-builder/compare/v10.15.1...v10.15.2) (2016-12-31)


### Bug Fixes

* **dmg:** Unable to build with custom path ([3bf8c93](https://github.com/electron-userland/electron-builder/commit/3bf8c93)), closes [#847](https://github.com/electron-userland/electron-builder/issues/847) [#1054](https://github.com/electron-userland/electron-builder/issues/1054)
* **docker:** Docker - wine - bad exe format for rcedit.exe ([920c230](https://github.com/electron-userland/electron-builder/commit/920c230))
* **electron-auto-updater:** Checking for updates from github was failing ([3401630](https://github.com/electron-userland/electron-builder/commit/3401630)), closes [#1038](https://github.com/electron-userland/electron-builder/issues/1038)


### Features

* **docker:** Install chrome & xvfb to allow for e2e testing ([43add64](https://github.com/electron-userland/electron-builder/commit/43add64))



<a name="10.15.1"></a>
## [10.15.1](https://github.com/electron-userland/electron-builder/compare/v10.15.0...v10.15.1) (2016-12-29)


### Bug Fixes

* **linux:** executable breakes if productName given ([2906227](https://github.com/electron-userland/electron-builder/commit/2906227)), closes [#1060](https://github.com/electron-userland/electron-builder/issues/1060)



<a name="10.15.0"></a>
# [10.15.0](https://github.com/electron-userland/electron-builder/compare/v10.14.0...v10.15.0) (2016-12-28)


### Features

* build in distributable format prepackaged directory ([1c59534](https://github.com/electron-userland/electron-builder/commit/1c59534))



<a name="10.14.0"></a>
# [10.14.0](https://github.com/electron-userland/electron-builder/compare/v10.13.1...v10.14.0) (2016-12-28)


### Features

* Adding download-progress event to AutoUpdater (#1042) ([b3a0be0](https://github.com/electron-userland/electron-builder/commit/b3a0be0)), closes [#958](https://github.com/electron-userland/electron-builder/issues/958)



<a name="10.13.1"></a>
## [10.13.1](https://github.com/electron-userland/electron-builder/compare/v10.13.0...v10.13.1) (2016-12-27)


### Bug Fixes

* **appimage:** Linux AppImage target doesn't reuse the launcher icon ([96895cf](https://github.com/electron-userland/electron-builder/commit/96895cf)), closes [#1003](https://github.com/electron-userland/electron-builder/issues/1003)
* **appimage:** USE_SYSTEM_XORRISO env to force usage of system xorriso ([03e43d1](https://github.com/electron-userland/electron-builder/commit/03e43d1))



<a name="10.13.0"></a>
# [10.13.0](https://github.com/electron-userland/electron-builder/compare/v10.12.0...v10.13.0) (2016-12-26)


### Bug Fixes

* **electron-auto-updater:** queue checkForUpdates ([62e0bcb](https://github.com/electron-userland/electron-builder/commit/62e0bcb)), closes [#1045](https://github.com/electron-userland/electron-builder/issues/1045)


### Features

* **snaps:** build snaps on macOs #509 ([f343def](https://github.com/electron-userland/electron-builder/commit/f343def))



<a name="10.12.0"></a>
# [10.12.0](https://github.com/electron-userland/electron-builder/compare/v10.11.0...v10.12.0) (2016-12-25)


### Bug Fixes

* **snap:** reduce deps #509 ([1fc26a5](https://github.com/electron-userland/electron-builder/commit/1fc26a5))


### Features

* **snap:** ubuntu-app-platform (disabled by default) ([a0c0d8e](https://github.com/electron-userland/electron-builder/commit/a0c0d8e))



<a name="10.11.0"></a>
# [10.11.0](https://github.com/electron-userland/electron-builder/compare/v10.10.0...v10.11.0) (2016-12-24)


### Bug Fixes

* Removing the abort trigger from httpExecutor (#1040) ([741df23](https://github.com/electron-userland/electron-builder/commit/741df23)), closes [#1039](https://github.com/electron-userland/electron-builder/issues/1039)
* sha2 checksum error is not catchable ([c10531b](https://github.com/electron-userland/electron-builder/commit/c10531b)), closes [#1010](https://github.com/electron-userland/electron-builder/issues/1010)


### Features

* Build snap packages for Linux ([a7aa979](https://github.com/electron-userland/electron-builder/commit/a7aa979)), closes [#509](https://github.com/electron-userland/electron-builder/issues/509)
* NSIS Updater API to Start Downloading ([eff85c3](https://github.com/electron-userland/electron-builder/commit/eff85c3)), closes [#972](https://github.com/electron-userland/electron-builder/issues/972)



<a name="10.10.0"></a>
# [10.10.0](https://github.com/electron-userland/electron-builder/compare/v10.9.3...v10.10.0) (2016-12-21)


### Features

* LSTypeIsPackage for file associations ([dcf3dbb](https://github.com/electron-userland/electron-builder/commit/dcf3dbb)), closes [#995](https://github.com/electron-userland/electron-builder/issues/995)



<a name="10.9.3"></a>
## [10.9.3](https://github.com/electron-userland/electron-builder/compare/v10.9.2...v10.9.3) (2016-12-21)


### Bug Fixes

* Trim suffix from wine version (#1033) ([090150c](https://github.com/electron-userland/electron-builder/commit/090150c)), closes [#1033](https://github.com/electron-userland/electron-builder/issues/1033) [#1031](https://github.com/electron-userland/electron-builder/issues/1031) [#953](https://github.com/electron-userland/electron-builder/issues/953)



<a name="10.9.2"></a>
## [10.9.2](https://github.com/electron-userland/electron-builder/compare/v10.9.1...v10.9.2) (2016-12-20)


### Bug Fixes

* Stub Executables missing in Squirrel.Windows 1.5.1 ([0ce1a3c](https://github.com/electron-userland/electron-builder/commit/0ce1a3c)), closes [#1011](https://github.com/electron-userland/electron-builder/issues/1011)



<a name="10.9.1"></a>
## [10.9.1](https://github.com/electron-userland/electron-builder/compare/v10.9.0...v10.9.1) (2016-12-20)


### Bug Fixes

* order of platform and arch npm env vars (#1029) ([f01a9f7](https://github.com/electron-userland/electron-builder/commit/f01a9f7)), closes [/github.com/electron-userland/electron-builder/issues/1027#issuecomment-268066701](https://github.com//github.com/electron-userland/electron-builder/issues/1027/issues/issuecomment-268066701)



<a name="10.9.0"></a>
# [10.9.0](https://github.com/electron-userland/electron-builder/compare/v10.8.1...v10.9.0) (2016-12-19)


### Features

* 32 bit appx  ([01604cf](https://github.com/electron-userland/electron-builder/commit/01604cf))
* **appx:** more customizable manifest fields ([cdc7219](https://github.com/electron-userland/electron-builder/commit/cdc7219))
* Set platform npm environment variable ([9249fcd](https://github.com/electron-userland/electron-builder/commit/9249fcd)), closes [#1027](https://github.com/electron-userland/electron-builder/issues/1027)
* Use Electron.Net to send http requests for auto updater ([569dd8b](https://github.com/electron-userland/electron-builder/commit/569dd8b)), closes [#959](https://github.com/electron-userland/electron-builder/issues/959) [#1024](https://github.com/electron-userland/electron-builder/issues/1024)



<a name="10.8.1"></a>
## [10.8.1](https://github.com/electron-userland/electron-builder/compare/v10.8.0...v10.8.1) (2016-12-15)


### Bug Fixes

* yarn detection ([1aaeb30](https://github.com/electron-userland/electron-builder/commit/1aaeb30))



<a name="10.8.0"></a>
# [10.8.0](https://github.com/electron-userland/electron-builder/compare/v10.7.1...v10.8.0) (2016-12-14)


### Bug Fixes

* update nsis to 3.0.1 ([f32d2dc](https://github.com/electron-userland/electron-builder/commit/f32d2dc)), closes [#850](https://github.com/electron-userland/electron-builder/issues/850)
* update nsis to 3.0.1 ([c6044a3](https://github.com/electron-userland/electron-builder/commit/c6044a3)), closes [#850](https://github.com/electron-userland/electron-builder/issues/850)


### Features

* update Squirrel.Windows to 1.5.1 ([97f6e0e](https://github.com/electron-userland/electron-builder/commit/97f6e0e))



<a name="10.7.1"></a>
## [10.7.1](https://github.com/electron-userland/electron-builder/compare/v10.7.0...v10.7.1) (2016-12-14)


### Bug Fixes

* **electron-auto-updater:** load default provider only if custom was not set ([a457d0d](https://github.com/electron-userland/electron-builder/commit/a457d0d))
* ENOENT for symlinks because directory was not created ([76de8f7](https://github.com/electron-userland/electron-builder/commit/76de8f7)), closes [#1002](https://github.com/electron-userland/electron-builder/issues/1002) [#998](https://github.com/electron-userland/electron-builder/issues/998)



<a name="10.7.0"></a>
# [10.7.0](https://github.com/electron-userland/electron-builder/compare/v10.6.1...v10.7.0) (2016-12-12)


### Features

* force application signing ([4faa3fb](https://github.com/electron-userland/electron-builder/commit/4faa3fb)), closes [#975](https://github.com/electron-userland/electron-builder/issues/975)



<a name="10.6.1"></a>
## [10.6.1](https://github.com/electron-userland/electron-builder/compare/v10.6.0...v10.6.1) (2016-12-07)


### Bug Fixes

* improve error message for case of wrongly set electron* dependencies (#986) ([4635ab0](https://github.com/electron-userland/electron-builder/commit/4635ab0))



<a name="10.6.0"></a>
# [10.6.0](https://github.com/electron-userland/electron-builder/compare/v10.5.0...v10.6.0) (2016-12-06)


### Features

* First start after update will start with a flag (#979) ([cb85297](https://github.com/electron-userland/electron-builder/commit/cb85297)), closes [#970](https://github.com/electron-userland/electron-builder/issues/970)



<a name="10.5.0"></a>
# [10.5.0](https://github.com/electron-userland/electron-builder/compare/v10.4.3...v10.5.0) (2016-12-03)


### Features

* custom NSIS installer icon (#969) ([75dd2cb](https://github.com/electron-userland/electron-builder/commit/75dd2cb)), closes [#964](https://github.com/electron-userland/electron-builder/issues/964)



<a name="10.4.3"></a>
## [10.4.3](https://github.com/electron-userland/electron-builder/compare/v10.4.2...v10.4.3) (2016-12-02)


### Bug Fixes

* use productName for FileDescription on Windows (#965) ([3b6af52](https://github.com/electron-userland/electron-builder/commit/3b6af52)), closes [#783](https://github.com/electron-userland/electron-builder/issues/783)



<a name="10.4.2"></a>
## [10.4.2](https://github.com/electron-userland/electron-builder/compare/v10.4.1...v10.4.2) (2016-12-02)


### Bug Fixes

* write remaining files to unpack (#961) ([cbf4e04](https://github.com/electron-userland/electron-builder/commit/cbf4e04))



<a name="10.4.1"></a>
## [10.4.1](https://github.com/electron-userland/electron-builder/compare/v10.4.0...v10.4.1) (2016-12-01)


### Bug Fixes

* **mac:** build.fileAssociations icon links to original file in output ([d289f4b](https://github.com/electron-userland/electron-builder/commit/d289f4b)), closes [#954](https://github.com/electron-userland/electron-builder/issues/954)



<a name="10.4.0"></a>
# [10.4.0](https://github.com/electron-userland/electron-builder/compare/v10.3.0...v10.4.0) (2016-11-30)


### Bug Fixes

* wine version processing (#955) ([da16181](https://github.com/electron-userland/electron-builder/commit/da16181))


### Features

* win code sign timestamp server option ([c2eb8c2](https://github.com/electron-userland/electron-builder/commit/c2eb8c2)), closes [#951](https://github.com/electron-userland/electron-builder/issues/951)



<a name="10.3.0"></a>
# [10.3.0](https://github.com/electron-userland/electron-builder/compare/v10.2.0...v10.3.0) (2016-11-30)


### Bug Fixes

* Not a valid Win32 application ([5d4b747](https://github.com/electron-userland/electron-builder/commit/5d4b747)), closes [#844](https://github.com/electron-userland/electron-builder/issues/844)


### Features

* ability to disable hard links on a CI server ([92af262](https://github.com/electron-userland/electron-builder/commit/92af262))
* exclude yarn-error.log and .jshintrc, remove LICENSE outside of .app ([6c90f30](https://github.com/electron-userland/electron-builder/commit/6c90f30))



<a name="10.2.0"></a>
# [10.2.0](https://github.com/electron-userland/electron-builder/compare/v10.1.0...v10.2.0) (2016-11-29)


### Features

* **nsis:** use name instead of product name as inst dir ([640fea0](https://github.com/electron-userland/electron-builder/commit/640fea0)), closes [#926](https://github.com/electron-userland/electron-builder/issues/926) [#941](https://github.com/electron-userland/electron-builder/issues/941) [#810](https://github.com/electron-userland/electron-builder/issues/810) [#928](https://github.com/electron-userland/electron-builder/issues/928)



<a name="10.1.0"></a>
# [10.1.0](https://github.com/electron-userland/electron-builder/compare/v10.0.0...v10.1.0) (2016-11-28)


### Features

* use hardlinks if possible, do not create empty dirs ([3f97b86](https://github.com/electron-userland/electron-builder/commit/3f97b86)), closes [#732](https://github.com/electron-userland/electron-builder/issues/732)



<a name="10.0.0"></a>
# [10.0.0](https://github.com/electron-userland/electron-builder/compare/v9.2.0...v10.0.0) (2016-11-26)


### Bug Fixes

* Unable to build package because of asarUnpack ([e3cfa8e](https://github.com/electron-userland/electron-builder/commit/e3cfa8e)), closes [#937](https://github.com/electron-userland/electron-builder/issues/937)


### Features

* if only ignored patterns are specified — all not ignored files is copied ([a55c573](https://github.com/electron-userland/electron-builder/commit/a55c573)), closes [#927](https://github.com/electron-userland/electron-builder/issues/927)


### BREAKING CHANGES

* asar.unpackDir, asar.unpack, asar-unpack-dir, asar-unpack were removed — please use build.asarUnpack instead



<a name="9.2.0"></a>
# [9.2.0](https://github.com/electron-userland/electron-builder/compare/v9.1.0...v9.2.0) (2016-11-25)


### Features

* **nsis:** NSIS with oneClick set to true does not relaunch the app after update ([00a8d36](https://github.com/electron-userland/electron-builder/commit/00a8d36)), closes [#884](https://github.com/electron-userland/electron-builder/issues/884)
* **windows:** Windows Store support (AppX target) ([f4d7a2e](https://github.com/electron-userland/electron-builder/commit/f4d7a2e)), closes [#782](https://github.com/electron-userland/electron-builder/issues/782)



<a name="9.1.0"></a>
# [9.1.0](https://github.com/electron-userland/electron-builder/compare/v9.0.1...v9.1.0) (2016-11-19)


### Features

* electronDownload instead of download #921 ([8463bef](https://github.com/electron-userland/electron-builder/commit/8463bef))
* rename LICENSE from electron dist to LICENSE.electron.txt ([e05cd17](https://github.com/electron-userland/electron-builder/commit/e05cd17)), closes [#916](https://github.com/electron-userland/electron-builder/issues/916)



<a name="9.0.1"></a>
## [9.0.1](https://github.com/electron-userland/electron-builder/compare/v9.0.0...v9.0.1) (2016-11-19)


### Bug Fixes

* snap support, desktop integration attempt #509 ([223a6aa](https://github.com/electron-userland/electron-builder/commit/223a6aa))



<a name="9.0.0"></a>
# [9.0.0](https://github.com/electron-userland/electron-builder/compare/v8.7.0...v9.0.0) (2016-11-19)


### Bug Fixes

* **mac:** App rejected when Mac Developer certificate is in keychain #890 ([386853a](https://github.com/electron-userland/electron-builder/commit/386853a))


### Features

* **deb:** Replace ia32 arch name with i386 in package filename ([73e54c4](https://github.com/electron-userland/electron-builder/commit/73e54c4)), closes [#915](https://github.com/electron-userland/electron-builder/issues/915)
* **linux:** lowercased linux executable ([ff7a8c3](https://github.com/electron-userland/electron-builder/commit/ff7a8c3))


### BREAKING CHANGES

* **deb:** Replace ia32 arch name with i386 in package filename
* **linux:** Linux executable name is always lowercased



<a name="8.7.0"></a>
# [8.7.0](https://github.com/electron-userland/electron-builder/compare/v8.6.0...v8.7.0) (2016-11-18)


### Features

* **linux:** Build snap packages for Linux #509 ([1bd54f7](https://github.com/electron-userland/electron-builder/commit/1bd54f7))



<a name="8.6.0"></a>
# [8.6.0](https://github.com/electron-userland/electron-builder/compare/v8.5.3...v8.6.0) (2016-11-15)


### Bug Fixes

* Auto updater "error" event does not contain error message ([7be5391](https://github.com/electron-userland/electron-builder/commit/7be5391)), closes [#900](https://github.com/electron-userland/electron-builder/issues/900)
* auto-unpacked files are not copied ([5f2a1c6](https://github.com/electron-userland/electron-builder/commit/5f2a1c6)), closes [#843](https://github.com/electron-userland/electron-builder/issues/843)


### Features

* Surround [version]-[revision] with underscores rather than dashes in filenames ([1057499](https://github.com/electron-userland/electron-builder/commit/1057499)), closes [#803](https://github.com/electron-userland/electron-builder/issues/803)


### BREAKING CHANGES

* Debian binary package naming convention is [name]_[version]-[revision]_[arch].deb



<a name="8.5.3"></a>
## [8.5.3](https://github.com/electron-userland/electron-builder/compare/v8.5.2...v8.5.3) (2016-11-13)


### Bug Fixes

* **mas:** mas app crashing after signing ([87f5ea7](https://github.com/electron-userland/electron-builder/commit/87f5ea7)), closes [#897](https://github.com/electron-userland/electron-builder/issues/897)



<a name="8.5.2"></a>
## [8.5.2](https://github.com/electron-userland/electron-builder/compare/v8.5.1...v8.5.2) (2016-11-12)


### Bug Fixes

* **nsis:** NSIS installer "CHECK_APP_RUNNING" breaks if installer has same executable file name as app ([ec3c15d](https://github.com/electron-userland/electron-builder/commit/ec3c15d)), closes [#894](https://github.com/electron-userland/electron-builder/issues/894)



<a name="8.5.1"></a>
## [8.5.1](https://github.com/electron-userland/electron-builder/compare/v8.5.0...v8.5.1) (2016-11-12)


### Bug Fixes

* regression — additionalArgs is not passed to npm rebuild ([92ad554](https://github.com/electron-userland/electron-builder/commit/92ad554))



<a name="8.5.0"></a>
# [8.5.0](https://github.com/electron-userland/electron-builder/compare/v8.4.1...v8.5.0) (2016-11-12)


### Bug Fixes

* Auto updater "error" event does not contain error message ([1b52c94](https://github.com/electron-userland/electron-builder/commit/1b52c94)), closes [#900](https://github.com/electron-userland/electron-builder/issues/900)


### Features

* **api:** Get or Specify Final Build exe or dmg file names ([f31a20d](https://github.com/electron-userland/electron-builder/commit/f31a20d)), closes [#899](https://github.com/electron-userland/electron-builder/issues/899)



<a name="8.4.1"></a>
## [8.4.1](https://github.com/electron-userland/electron-builder/compare/v8.4.0...v8.4.1) (2016-11-12)


### Bug Fixes

* Changing Icons (not updating on dist output) ([b6951ad](https://github.com/electron-userland/electron-builder/commit/b6951ad)), closes [#840](https://github.com/electron-userland/electron-builder/issues/840)



<a name="8.4.0"></a>
# [8.4.0](https://github.com/electron-userland/electron-builder/compare/v8.3.0...v8.4.0) (2016-11-12)


### Features

* more performant and reliable npm rebuild ([20026f1](https://github.com/electron-userland/electron-builder/commit/20026f1))



<a name="8.3.0"></a>
# [8.3.0](https://github.com/electron-userland/electron-builder/compare/v8.2.1...v8.3.0) (2016-11-11)


### Features

* asarUnpack ([8a8ccad](https://github.com/electron-userland/electron-builder/commit/8a8ccad))



<a name="8.2.1"></a>
## [8.2.1](https://github.com/electron-userland/electron-builder/compare/v8.2.0...v8.2.1) (2016-11-11)


### Bug Fixes

* **linux:** report "Building ..." ([ff8a436](https://github.com/electron-userland/electron-builder/commit/ff8a436))
* No error if no valid cert to sign mac app ([22f73c0](https://github.com/electron-userland/electron-builder/commit/22f73c0)), closes [#897](https://github.com/electron-userland/electron-builder/issues/897)



<a name="8.2.0"></a>
# [8.2.0](https://github.com/electron-userland/electron-builder/compare/v8.1.0...v8.2.0) (2016-11-11)


### Bug Fixes

* App rejected when Mac Developer certificate is in keychain ([9edadb5](https://github.com/electron-userland/electron-builder/commit/9edadb5)), closes [#890](https://github.com/electron-userland/electron-builder/issues/890)


### Features

* ignore *.d.ts by default, include package.json in any case ([6ce683f](https://github.com/electron-userland/electron-builder/commit/6ce683f))



<a name="8.1.0"></a>
# [8.1.0](https://github.com/electron-userland/electron-builder/compare/v8.0.0...v8.1.0) (2016-11-10)


### Bug Fixes

* flatDependencies regression ([edc39a8](https://github.com/electron-userland/electron-builder/commit/edc39a8)), closes [#895](https://github.com/electron-userland/electron-builder/issues/895)


### Features

* install-app-deps rebuilds native deps for any project structure ([6532e9f](https://github.com/electron-userland/electron-builder/commit/6532e9f))



<a name="8.0.0"></a>
# [8.0.0](https://github.com/electron-userland/electron-builder/compare/v7.26.0...v8.0.0) (2016-11-10)


### Chores

* remove "osx" name support — use "mac" instead ([aa05ac0](https://github.com/electron-userland/electron-builder/commit/aa05ac0))


### Features

* nsis target for windows by default ([1bc8d57](https://github.com/electron-userland/electron-builder/commit/1bc8d57))
* rebuild native dependencies for any project structure ([b1ea8cd](https://github.com/electron-userland/electron-builder/commit/b1ea8cd))


### BREAKING CHANGES

* "nsis" target is default now. Not "squirrel" (Squirrel.Windows)
If you have existing app, please set "build.win.target" to "squirrel".
Auto-update — please see https://github.com/electron-userland/electron-builder/wiki/Auto-Update
* remove "osx" name support — use "mac" instead
* rebuild native dependencies for any project structure



<a name="7.26.0"></a>
# [7.26.0](https://github.com/electron-userland/electron-builder/compare/v7.25.0...v7.26.0) (2016-11-09)


### Features

* Yarn Support (rebuild) ([94cc7be](https://github.com/electron-userland/electron-builder/commit/94cc7be)), closes [#861](https://github.com/electron-userland/electron-builder/issues/861)


### Performance Improvements

* dev or extra deps ([e89934d](https://github.com/electron-userland/electron-builder/commit/e89934d))
* walk dir ([525bb91](https://github.com/electron-userland/electron-builder/commit/525bb91))



<a name="7.25.0"></a>
# [7.25.0](https://github.com/electron-userland/electron-builder/compare/v7.24.2...v7.25.0) (2016-11-08)


### Features

* **nsis:** Specify install dir based on architecture (#889) ([895411f](https://github.com/electron-userland/electron-builder/commit/895411f))



<a name="7.24.2"></a>
## [7.24.2](https://github.com/electron-userland/electron-builder/compare/v7.24.1...v7.24.2) (2016-11-07)


### Bug Fixes

* Cannot use NSIS StrFunc header ([4cbdc31](https://github.com/electron-userland/electron-builder/commit/4cbdc31)), closes [#888](https://github.com/electron-userland/electron-builder/issues/888)



<a name="7.24.1"></a>
## [7.24.1](https://github.com/electron-userland/electron-builder/compare/v7.24.0...v7.24.1) (2016-11-07)


### Bug Fixes

* github as a provider — latest.yml is not published ([e920584](https://github.com/electron-userland/electron-builder/commit/e920584)), closes [#868](https://github.com/electron-userland/electron-builder/issues/868)



<a name="7.24.0"></a>
# [7.24.0](https://github.com/electron-userland/electron-builder/compare/v7.23.2...v7.24.0) (2016-11-06)


### Features

* **mac:** macOS pkg installer ([265ad20](https://github.com/electron-userland/electron-builder/commit/265ad20)), closes [#52](https://github.com/electron-userland/electron-builder/issues/52)


### Performance Improvements

* **mas:** flat on electron-builder side ([adacf1e](https://github.com/electron-userland/electron-builder/commit/adacf1e))



<a name="7.23.2"></a>
## [7.23.2](https://github.com/electron-userland/electron-builder/compare/v7.23.1...v7.23.2) (2016-11-06)


### Bug Fixes

* github as a provider — latest.yml is not generated ([9d31b42](https://github.com/electron-userland/electron-builder/commit/9d31b42)), closes [#868](https://github.com/electron-userland/electron-builder/issues/868)



<a name="7.23.1"></a>
## [7.23.1](https://github.com/electron-userland/electron-builder/compare/v7.23.0...v7.23.1) (2016-11-05)


### Bug Fixes

* typo in handling of npmArgs (#883) ([f4728c3](https://github.com/electron-userland/electron-builder/commit/f4728c3))



<a name="7.23.0"></a>
# [7.23.0](https://github.com/electron-userland/electron-builder/compare/v7.22.1...v7.23.0) (2016-11-05)


### Bug Fixes

* "contains executable code" — change log to debug ([08913b6](https://github.com/electron-userland/electron-builder/commit/08913b6)), closes [#879](https://github.com/electron-userland/electron-builder/issues/879)


### Features

* add ability to specify additional npm rebuild args (#881) ([eec5b32](https://github.com/electron-userland/electron-builder/commit/eec5b32))
* use cache dir per OS convention ([786250c](https://github.com/electron-userland/electron-builder/commit/786250c))
* use cache dir per OS convention ([20a247c](https://github.com/electron-userland/electron-builder/commit/20a247c))


### Performance Improvements

* walk dir, limit concurrency to 8 (was 32) ([540ee5e](https://github.com/electron-userland/electron-builder/commit/540ee5e))



<a name="7.22.1"></a>
## [7.22.1](https://github.com/electron-userland/electron-builder/compare/v7.22.0...v7.22.1) (2016-11-05)


### Bug Fixes

* update v8 headers URL (#878) ([3bc99e1](https://github.com/electron-userland/electron-builder/commit/3bc99e1))



<a name="7.22.0"></a>
# [7.22.0](https://github.com/electron-userland/electron-builder/compare/v7.21.0...v7.22.0) (2016-11-04)


### Features

* ignore __tests__, tests, example, examples by default ([970caf4](https://github.com/electron-userland/electron-builder/commit/970caf4)), closes [#823](https://github.com/electron-userland/electron-builder/issues/823)



<a name="7.21.0"></a>
# [7.21.0](https://github.com/electron-userland/electron-builder/compare/v7.20.0...v7.21.0) (2016-11-04)


### Bug Fixes

* do not use --no-bin-links by default due to npm bug ([7ab1ba1](https://github.com/electron-userland/electron-builder/commit/7ab1ba1)), closes [#869](https://github.com/electron-userland/electron-builder/issues/869)


### Features

* GitHub publish provider ([9e18cb1](https://github.com/electron-userland/electron-builder/commit/9e18cb1)), closes [#868](https://github.com/electron-userland/electron-builder/issues/868)



<a name="7.20.0"></a>
# [7.20.0](https://github.com/electron-userland/electron-builder/compare/v7.19.1...v7.20.0) (2016-11-03)


### Bug Fixes

* RangeError: Maximum call stack size exceeded ([c5627f8](https://github.com/electron-userland/electron-builder/commit/c5627f8)), closes [#826](https://github.com/electron-userland/electron-builder/issues/826)


### Features

* **linux:** be more restrictive with executable name ([c3136ad](https://github.com/electron-userland/electron-builder/commit/c3136ad)), closes [#806](https://github.com/electron-userland/electron-builder/issues/806)



<a name="7.19.1"></a>
## [7.19.1](https://github.com/electron-userland/electron-builder/compare/v7.19.0...v7.19.1) (2016-11-03)


### Bug Fixes

* **nsis:** machine-wide assisted NSIS installer launches application as administrator ([7ea3d62](https://github.com/electron-userland/electron-builder/commit/7ea3d62)), closes [#864](https://github.com/electron-userland/electron-builder/issues/864)



<a name="7.19.0"></a>
# [7.19.0](https://github.com/electron-userland/electron-builder/compare/v7.18.1...v7.19.0) (2016-11-03)


### Features

* rebuild with --no-bin-links option ([cf24b01](https://github.com/electron-userland/electron-builder/commit/cf24b01)), closes [#869](https://github.com/electron-userland/electron-builder/issues/869)



<a name="7.18.1"></a>
## [7.18.1](https://github.com/electron-userland/electron-builder/compare/v7.18.0...v7.18.1) (2016-11-02)


### Bug Fixes

* **AppImage:** AppImages fail to run if appimaged process is running ([224c00e](https://github.com/electron-userland/electron-builder/commit/224c00e)), closes [#827](https://github.com/electron-userland/electron-builder/issues/827)



<a name="7.18.0"></a>
# [7.18.0](https://github.com/electron-userland/electron-builder/compare/v7.17.1...v7.18.0) (2016-11-02)


### Features

* **nsis:** assisted installer — respect /allusers ([4536e91](https://github.com/electron-userland/electron-builder/commit/4536e91)), closes [#845](https://github.com/electron-userland/electron-builder/issues/845)



<a name="7.17.1"></a>
## [7.17.1](https://github.com/electron-userland/electron-builder/compare/v7.17.0...v7.17.1) (2016-11-02)


### Bug Fixes

* restore dmg.title support ([bc64791](https://github.com/electron-userland/electron-builder/commit/bc64791)), closes [#834](https://github.com/electron-userland/electron-builder/issues/834)
* **nsis:** machine-wide one-click NSIS installer launches application as administrator ([4ac12bf](https://github.com/electron-userland/electron-builder/commit/4ac12bf)), closes [#864](https://github.com/electron-userland/electron-builder/issues/864)



<a name="7.17.0"></a>
# [7.17.0](https://github.com/electron-userland/electron-builder/compare/v7.16.0...v7.17.0) (2016-11-01)


### Features

* generic publish provider ([ad3f299](https://github.com/electron-userland/electron-builder/commit/ad3f299)), closes [#529](https://github.com/electron-userland/electron-builder/issues/529)



<a name="7.16.0"></a>
# [7.16.0](https://github.com/electron-userland/electron-builder/compare/v7.15.2...v7.16.0) (2016-10-31)


### Bug Fixes

* Code Sign with Mac Developer certificates ([7ab9ca6](https://github.com/electron-userland/electron-builder/commit/7ab9ca6)), closes [#812](https://github.com/electron-userland/electron-builder/issues/812)
* attempt to fix "old version dir is empty" ([5c7c4ac](https://github.com/electron-userland/electron-builder/commit/5c7c4ac))


### Features

* **nsis-auto-updater:** auto install on quit ([a3bba92](https://github.com/electron-userland/electron-builder/commit/a3bba92))
* initial yarn support (avoid --cache-min) ([ba1cd4b](https://github.com/electron-userland/electron-builder/commit/ba1cd4b)), closes [#861](https://github.com/electron-userland/electron-builder/issues/861)
* use warning emoji instead of plain text ([772b297](https://github.com/electron-userland/electron-builder/commit/772b297))



<a name="7.15.2"></a>
## [7.15.2](https://github.com/electron-userland/electron-builder/compare/v7.15.1...v7.15.2) (2016-10-28)


### Bug Fixes

* DMG background resource must be resolved using project dir ([8d37b7e](https://github.com/electron-userland/electron-builder/commit/8d37b7e)), closes [#858](https://github.com/electron-userland/electron-builder/issues/858)
* prevent ".directories.output option ignored in package.json" ([e748369](https://github.com/electron-userland/electron-builder/commit/e748369)), closes [#852](https://github.com/electron-userland/electron-builder/issues/852)



<a name="7.15.1"></a>
## [7.15.1](https://github.com/electron-userland/electron-builder/compare/v7.15.0...v7.15.1) (2016-10-28)


### Bug Fixes

* bintray repo setting has no effect, always defaults to generic ([48051cb](https://github.com/electron-userland/electron-builder/commit/48051cb)), closes [#857](https://github.com/electron-userland/electron-builder/issues/857)



<a name="7.15.0"></a>
# [7.15.0](https://github.com/electron-userland/electron-builder/compare/v7.14.2...v7.15.0) (2016-10-27)


### Bug Fixes

* rename .app-update.json to app-update.yml #529 ([f69d202](https://github.com/electron-userland/electron-builder/commit/f69d202))
* use own copy of bluebird library (scoped) ([686dc6b](https://github.com/electron-userland/electron-builder/commit/686dc6b))
* **dmg:** do not use -quiet #854 ([74e2006](https://github.com/electron-userland/electron-builder/commit/74e2006))


### Features

*  add ability to specify bintray user ([716ebc6](https://github.com/electron-userland/electron-builder/commit/716ebc6)), closes [#848](https://github.com/electron-userland/electron-builder/issues/848)
* WIN_CSC_KEY_PASSWORD #822 ([99a5f0a](https://github.com/electron-userland/electron-builder/commit/99a5f0a))
* handle available native deps when building on non-native platforms ([81c6bdf](https://github.com/electron-userland/electron-builder/commit/81c6bdf)), closes [#842](https://github.com/electron-userland/electron-builder/issues/842)
* warn when skipping mac app signing due to unsupported platform ([7c810a7](https://github.com/electron-userland/electron-builder/commit/7c810a7)), closes [#849](https://github.com/electron-userland/electron-builder/issues/849)


### Performance Improvements

* lazy imports, get rid of tsAwaiter ([a33e004](https://github.com/electron-userland/electron-builder/commit/a33e004))



<a name="7.14.2"></a>
## [7.14.2](https://github.com/electron-userland/electron-builder/compare/v7.14.1...v7.14.2) (2016-10-18)


### Bug Fixes

* **nsis:** EULA ([a0e7131](https://github.com/electron-userland/electron-builder/commit/a0e7131)), closes [#829](https://github.com/electron-userland/electron-builder/issues/829)



<a name="7.14.1"></a>
## [7.14.1](https://github.com/electron-userland/electron-builder/compare/v7.14.0...v7.14.1) (2016-10-17)


### Bug Fixes

* **bintray:** do not require explicit publish=always (regression) #529 ([6f20e8d](https://github.com/electron-userland/electron-builder/commit/6f20e8d))



<a name="7.14.0"></a>
# [7.14.0](https://github.com/electron-userland/electron-builder/compare/v7.13.1...v7.14.0) (2016-10-17)


### Features

* Code signing for windows and mac in macOS ([d238635](https://github.com/electron-userland/electron-builder/commit/d238635)), closes [#822](https://github.com/electron-userland/electron-builder/issues/822)



<a name="7.13.1"></a>
## [7.13.1](https://github.com/electron-userland/electron-builder/compare/v7.13.0...v7.13.1) (2016-10-16)


### Bug Fixes

* **nsis:** correctly await update info writing and archive creation #529 ([b1ae7d5](https://github.com/electron-userland/electron-builder/commit/b1ae7d5))



<a name="7.13.0"></a>
# [7.13.0](https://github.com/electron-userland/electron-builder/compare/v7.12.2...v7.13.0) (2016-10-13)


### Features

* **dmg:** check appId, dmg.icon, dmg.contents.path ([36ed865](https://github.com/electron-userland/electron-builder/commit/36ed865)), closes [#821](https://github.com/electron-userland/electron-builder/issues/821)



<a name="7.12.2"></a>
## [7.12.2](https://github.com/electron-userland/electron-builder/compare/v7.12.1...v7.12.2) (2016-10-11)


### Bug Fixes

* **dmg:** Perl error when building DMG ([2f1a6e7](https://github.com/electron-userland/electron-builder/commit/2f1a6e7)), closes [#815](https://github.com/electron-userland/electron-builder/issues/815)



<a name="7.12.1"></a>
## [7.12.1](https://github.com/electron-userland/electron-builder/compare/v7.12.0...v7.12.1) (2016-10-10)


### Bug Fixes

* **squirrel.windows:** include output to error message #804 ([5762d0f](https://github.com/electron-userland/electron-builder/commit/5762d0f))



<a name="7.12.0"></a>
# [7.12.0](https://github.com/electron-userland/electron-builder/compare/v7.11.4...v7.12.0) (2016-10-10)


### Features

* bintray publisher configuration ([1a9caa8](https://github.com/electron-userland/electron-builder/commit/1a9caa8))



<a name="7.11.4"></a>
## [7.11.4](https://github.com/electron-userland/electron-builder/compare/v7.11.3...v7.11.4) (2016-10-07)


### Bug Fixes

* **dmg:** type: "file" is not required anymore for app file ([96d9206](https://github.com/electron-userland/electron-builder/commit/96d9206))



<a name="7.11.3"></a>
## [7.11.3](https://github.com/electron-userland/electron-builder/compare/v7.11.2...v7.11.3) (2016-10-07)


### Bug Fixes

* **nsis:** broken nsis ([993dac7](https://github.com/electron-userland/electron-builder/commit/993dac7)), closes [#800](https://github.com/electron-userland/electron-builder/issues/800)



<a name="7.11.2"></a>
## [7.11.2](https://github.com/electron-userland/electron-builder/compare/v7.11.1...v7.11.2) (2016-10-06)


### Bug Fixes

* make install-app-deps also handle skip build flag ([3e34110](https://github.com/electron-userland/electron-builder/commit/3e34110)), closes [#797](https://github.com/electron-userland/electron-builder/issues/797)



<a name="7.11.1"></a>
## [7.11.1](https://github.com/electron-userland/electron-builder/compare/v7.11.0...v7.11.1) (2016-10-06)


### Bug Fixes

* **mac:** Mac archive tar.* doesn't run after extraction ([a185040](https://github.com/electron-userland/electron-builder/commit/a185040)), closes [#784](https://github.com/electron-userland/electron-builder/issues/784)



<a name="7.11.0"></a>
# [7.11.0](https://github.com/electron-userland/electron-builder/compare/v7.10.3...v7.11.0) (2016-10-06)


### Features

* make a setting for --build-from-option flag ([4898eb1](https://github.com/electron-userland/electron-builder/commit/4898eb1)), closes [#787](https://github.com/electron-userland/electron-builder/issues/787) [#790](https://github.com/electron-userland/electron-builder/issues/790)



<a name="7.10.3"></a>
## [7.10.3](https://github.com/electron-userland/electron-builder/compare/v7.10.2...v7.10.3) (2016-10-05)


### Bug Fixes

* **mac:** background image isn't displayed in macOS sierra ([c16ecad](https://github.com/electron-userland/electron-builder/commit/c16ecad)), closes [#789](https://github.com/electron-userland/electron-builder/issues/789)



<a name="7.10.2"></a>
## [7.10.2](https://github.com/electron-userland/electron-builder/compare/v7.10.1...v7.10.2) (2016-10-02)


### Bug Fixes

* **deb:** Can't run generated app due to wrong permission ([c45adca](https://github.com/electron-userland/electron-builder/commit/c45adca)), closes [#786](https://github.com/electron-userland/electron-builder/issues/786)
* **nsis:** do not delete app data by default ([64937b2](https://github.com/electron-userland/electron-builder/commit/64937b2)), closes [#769](https://github.com/electron-userland/electron-builder/issues/769)



<a name="7.10.1"></a>
## [7.10.1](https://github.com/electron-userland/electron-builder/compare/v7.10.0...v7.10.1) (2016-09-30)


### Bug Fixes

* update fpm to 1.6.3 ([7a5252c](https://github.com/electron-userland/electron-builder/commit/7a5252c))



<a name="7.10.0"></a>
# [7.10.0](https://github.com/electron-userland/electron-builder/compare/v7.9.0...v7.10.0) (2016-09-25)


### Features

* Support for Electron for ARM ([6735da5](https://github.com/electron-userland/electron-builder/commit/6735da5)), closes [#778](https://github.com/electron-userland/electron-builder/issues/778)



<a name="7.9.0"></a>
# [7.9.0](https://github.com/electron-userland/electron-builder/compare/v7.8.0...v7.9.0) (2016-09-23)


### Features

* support --extraMetadata.directories ([1a310e3](https://github.com/electron-userland/electron-builder/commit/1a310e3))



<a name="7.8.0"></a>
# [7.8.0](https://github.com/electron-userland/electron-builder/compare/v7.7.0...v7.8.0) (2016-09-23)


### Features

* prune even if two-package.json structure not used ([26b8dac](https://github.com/electron-userland/electron-builder/commit/26b8dac)), closes [#770](https://github.com/electron-userland/electron-builder/issues/770)



<a name="7.7.0"></a>
# [7.7.0](https://github.com/electron-userland/electron-builder/compare/v7.6.0...v7.7.0) (2016-09-23)


### Features

* option to use appId to identify package instead of name #773 ([6f3d365](https://github.com/electron-userland/electron-builder/commit/6f3d365)), closes [#753](https://github.com/electron-userland/electron-builder/issues/753)



<a name="7.6.0"></a>
# [7.6.0](https://github.com/electron-userland/electron-builder/compare/v7.5.0...v7.6.0) (2016-09-22)


### Features

* support --extraMetadata.build.directories ([44ad719](https://github.com/electron-userland/electron-builder/commit/44ad719))



<a name="7.5.0"></a>
# [7.5.0](https://github.com/electron-userland/electron-builder/compare/v7.4.0...v7.5.0) (2016-09-21)


### Features

* **nsis:** option NSIS warnings as errors ([9762991](https://github.com/electron-userland/electron-builder/commit/9762991)), closes [#763](https://github.com/electron-userland/electron-builder/issues/763)



<a name="7.4.0"></a>
# [7.4.0](https://github.com/electron-userland/electron-builder/compare/v7.3.0...v7.4.0) (2016-09-20)


### Features

* specify path to custom Electron build (Electron.app) ([3132610](https://github.com/electron-userland/electron-builder/commit/3132610)), closes [#760](https://github.com/electron-userland/electron-builder/issues/760)



<a name="7.3.0"></a>
# [7.3.0](https://github.com/electron-userland/electron-builder/compare/v7.2.0...v7.3.0) (2016-09-19)


### Features

* support asar in package.json's `main` even when not packaging to asar during the build ([d9bc4e0](https://github.com/electron-userland/electron-builder/commit/d9bc4e0)), closes [#759](https://github.com/electron-userland/electron-builder/issues/759)



<a name="7.2.0"></a>
# [7.2.0](https://github.com/electron-userland/electron-builder/compare/v7.1.0...v7.2.0) (2016-09-19)


### Features

* ignore .gitignore,.gitattributes,.editorconfig,.idea by default ([70abaa3](https://github.com/electron-userland/electron-builder/commit/70abaa3))



<a name="7.1.0"></a>
# [7.1.0](https://github.com/electron-userland/electron-builder/compare/v7.0.1...v7.1.0) (2016-09-19)


### Bug Fixes

* **mac:** forbid "Mac Developer" cert ([32a59f7](https://github.com/electron-userland/electron-builder/commit/32a59f7))


### Features

* use iconutil on macOS to convert icns to iconset ([1ad417f](https://github.com/electron-userland/electron-builder/commit/1ad417f))



<a name="7.0.1"></a>
## [7.0.1](https://github.com/electron-userland/electron-builder/compare/v7.0.0...v7.0.1) (2016-09-18)


### Bug Fixes

* Don't throw an error if version doesn't start with `v´ ([ec8e69e](https://github.com/electron-userland/electron-builder/commit/ec8e69e)), closes [#743](https://github.com/electron-userland/electron-builder/issues/743)



<a name="7.0.0"></a>
# [7.0.0](https://github.com/electron-userland/electron-builder/compare/v6.7.7...v7.0.0) (2016-09-16)


### Bug Fixes

* **deb:** 64 bit deb release artifact filename ([84225d7](https://github.com/electron-userland/electron-builder/commit/84225d7)), closes [#747](https://github.com/electron-userland/electron-builder/issues/747)


### BREAKING CHANGES

* **deb:** x64 deb now has `amd64` arch suffix (previously was no prefix for x64).



<a name="6.7.7"></a>
## [6.7.7](https://github.com/electron-userland/electron-builder/compare/v6.7.6...v6.7.7) (2016-09-16)


### Bug Fixes

* **nsis:** handle unquoted UninstallString #735 ([77f3277](https://github.com/electron-userland/electron-builder/commit/77f3277))



<a name="6.7.6"></a>
## [6.7.6](https://github.com/electron-userland/electron-builder/compare/v6.7.5...v6.7.6) (2016-09-15)


### Bug Fixes

* **nsis:** apostrophe in product name ([63c67ef](https://github.com/electron-userland/electron-builder/commit/63c67ef)), closes [#750](https://github.com/electron-userland/electron-builder/issues/750)



<a name="6.7.5"></a>
## [6.7.5](https://github.com/electron-userland/electron-builder/compare/v6.7.4...v6.7.5) (2016-09-14)


### Bug Fixes

* **nsis:** _? must be last #735 ([517a90b](https://github.com/electron-userland/electron-builder/commit/517a90b))



<a name="6.7.4"></a>
## [6.7.4](https://github.com/electron-userland/electron-builder/compare/v6.7.3...v6.7.4) (2016-09-14)


### Bug Fixes

* **mac:** throw sign error correctly ([cca23b4](https://github.com/electron-userland/electron-builder/commit/cca23b4)), closes [#737](https://github.com/electron-userland/electron-builder/issues/737)
* **nsis:** get InstallLocation from UninstallerString if not found #735 ([431922e](https://github.com/electron-userland/electron-builder/commit/431922e))



<a name="6.7.3"></a>
## [6.7.3](https://github.com/electron-userland/electron-builder/compare/v6.7.2...v6.7.3) (2016-09-11)


### Bug Fixes

* proxy config from npm #585 ([29f6436](https://github.com/electron-userland/electron-builder/commit/29f6436))
* **nsis:** correct fix of #722 (NSIS Installer Not Working on Second Invocation) ([e35933d](https://github.com/electron-userland/electron-builder/commit/e35933d)), closes [#722](https://github.com/electron-userland/electron-builder/issues/722)



<a name="6.7.2"></a>
## [6.7.2](https://github.com/electron-userland/electron-builder/compare/v6.7.1...v6.7.2) (2016-09-11)


### Bug Fixes

* Build fails with TimeOut exception: proxy ([dd61408](https://github.com/electron-userland/electron-builder/commit/dd61408)), closes [#585](https://github.com/electron-userland/electron-builder/issues/585)



<a name="6.7.1"></a>
## [6.7.1](https://github.com/electron-userland/electron-builder/compare/v6.7.0...v6.7.1) (2016-09-10)


### Bug Fixes

* **nsis:** remove old < 6.4.1 versions ([cb538c1](https://github.com/electron-userland/electron-builder/commit/cb538c1)), closes [#735](https://github.com/electron-userland/electron-builder/issues/735)



<a name="6.7.0"></a>
# [6.7.0](https://github.com/electron-userland/electron-builder/compare/v6.6.1...v6.7.0) (2016-09-10)


### Features

* Hidden 'dotfiles' within an extraResources folder aren't copied ([7877f71](https://github.com/electron-userland/electron-builder/commit/7877f71)), closes [#733](https://github.com/electron-userland/electron-builder/issues/733)



<a name="6.6.1"></a>
## [6.6.1](https://github.com/electron-userland/electron-builder/compare/v6.6.0...v6.6.1) (2016-09-09)


### Bug Fixes

* **nsis:** no app icon in Add/Remove program ([e6c1efe](https://github.com/electron-userland/electron-builder/commit/e6c1efe)), closes [#738](https://github.com/electron-userland/electron-builder/issues/738)



<a name="6.6.0"></a>
# [6.6.0](https://github.com/electron-userland/electron-builder/compare/v6.5.2...v6.6.0) (2016-09-09)


### Features

* support CFBundleTypeRole for MacOS CFBundleURLTypes ([888581a](https://github.com/electron-userland/electron-builder/commit/888581a)), closes [#736](https://github.com/electron-userland/electron-builder/issues/736)



<a name="6.5.2"></a>
## [6.5.2](https://github.com/electron-userland/electron-builder/compare/v6.5.1...v6.5.2) (2016-09-08)


### Bug Fixes

* Version `6.3.5` makes build pass even when it fails ([a1b2b0e](https://github.com/electron-userland/electron-builder/commit/a1b2b0e)), closes [#721](https://github.com/electron-userland/electron-builder/issues/721)
* **mas:** Warning when using entitlements.mas.plist ([5031116](https://github.com/electron-userland/electron-builder/commit/5031116)), closes [#729](https://github.com/electron-userland/electron-builder/issues/729)



<a name="6.5.1"></a>
## [6.5.1](https://github.com/electron-userland/electron-builder/compare/v6.5.0...v6.5.1) (2016-09-07)


### Bug Fixes

* **nsis:** uninstaller path should be not quoted #722 ([63ee4cf](https://github.com/electron-userland/electron-builder/commit/63ee4cf))



<a name="6.5.0"></a>
# [6.5.0](https://github.com/electron-userland/electron-builder/compare/v6.4.1...v6.5.0) (2016-09-07)


### Bug Fixes

* Cleanup fail after build ([2e35205](https://github.com/electron-userland/electron-builder/commit/2e35205)), closes [#724](https://github.com/electron-userland/electron-builder/issues/724)
* **nsis:** finally — NSIS Installer Not Working on Second Invocation ([211d63f](https://github.com/electron-userland/electron-builder/commit/211d63f)), closes [#722](https://github.com/electron-userland/electron-builder/issues/722)


### Features

* **linux:** Categories desktop entry ([87616c0](https://github.com/electron-userland/electron-builder/commit/87616c0)), closes [#727](https://github.com/electron-userland/electron-builder/issues/727) [#641](https://github.com/electron-userland/electron-builder/issues/641)



<a name="6.4.1"></a>
## [6.4.1](https://github.com/electron-userland/electron-builder/compare/v6.4.0...v6.4.1) (2016-09-04)


### Bug Fixes

* NSIS Installer Not Working on Second Invocation ([0f1869b](https://github.com/electron-userland/electron-builder/commit/0f1869b))
* NSIS Installer Not Working on Second Invocation #722 ([1b90ec6](https://github.com/electron-userland/electron-builder/commit/1b90ec6))



<a name="6.4.0"></a>
# [6.4.0](https://github.com/electron-userland/electron-builder/compare/v6.3.5...v6.4.0) (2016-09-02)


### Features

* bintray publisher ([138e8e2](https://github.com/electron-userland/electron-builder/commit/138e8e2)), closes [#577](https://github.com/electron-userland/electron-builder/issues/577)



<a name="6.3.5"></a>
## [6.3.5](https://github.com/electron-userland/electron-builder/compare/v6.3.4...v6.3.5) (2016-09-02)


### Bug Fixes

* incorrect log message "ci detected" ([eb827ea](https://github.com/electron-userland/electron-builder/commit/eb827ea))



<a name="6.3.4"></a>
## [6.3.4](https://github.com/electron-userland/electron-builder/compare/v6.3.3...v6.3.4) (2016-09-02)


### Bug Fixes

* **squirrel.windows:** remove RELEASES because Squirrel.Windows doesn't check ([0c592e8](https://github.com/electron-userland/electron-builder/commit/0c592e8)), closes [#713](https://github.com/electron-userland/electron-builder/issues/713)



<a name="6.3.3"></a>
## [6.3.3](https://github.com/electron-userland/electron-builder/compare/v6.3.2...v6.3.3) (2016-09-01)


### Bug Fixes

* **squirrel.windows:** use GH_TOKEN ([e102e3e](https://github.com/electron-userland/electron-builder/commit/e102e3e)), closes [#714](https://github.com/electron-userland/electron-builder/issues/714)



<a name="6.3.2"></a>
## [6.3.2](https://github.com/electron-userland/electron-builder/compare/v6.3.1...v6.3.2) (2016-09-01)


### Bug Fixes

* **mac:** build mac targets on non-macOs ([1398af4](https://github.com/electron-userland/electron-builder/commit/1398af4))
* **squirrel.windows:** The base package release does not exist ([3b1ad57](https://github.com/electron-userland/electron-builder/commit/3b1ad57)), closes [#713](https://github.com/electron-userland/electron-builder/issues/713)



<a name="6.3.1"></a>
## [6.3.1](https://github.com/electron-userland/electron-builder/compare/v6.3.0...v6.3.1) (2016-08-30)


### Bug Fixes

* **nsis:** NSIS perMachine fails if UAC prompt is enabled ([b739f42](https://github.com/electron-userland/electron-builder/commit/b739f42)), closes [#712](https://github.com/electron-userland/electron-builder/issues/712)
* **nsis:** set locale id for legalTrademarks ([91addfe](https://github.com/electron-userland/electron-builder/commit/91addfe)), closes [#672](https://github.com/electron-userland/electron-builder/issues/672)



<a name="6.3.0"></a>
# [6.3.0](https://github.com/electron-userland/electron-builder/compare/v6.2.0...v6.3.0) (2016-08-29)


### Bug Fixes

* **nsis:** no custom icon ([b7b18bc](https://github.com/electron-userland/electron-builder/commit/b7b18bc))


### Features

* **nsis:** assisted per-machine only installer ([a4eeade](https://github.com/electron-userland/electron-builder/commit/a4eeade))



<a name="6.2.0"></a>
# [6.2.0](https://github.com/electron-userland/electron-builder/compare/v6.1.0...v6.2.0) (2016-08-29)


### Features

* **mac:** rename electron.icns to productName.icns ([8fa482e](https://github.com/electron-userland/electron-builder/commit/8fa482e))



<a name="6.1.0"></a>
# [6.1.0](https://github.com/electron-userland/electron-builder/compare/v6.0.3...v6.1.0) (2016-08-29)


### Features

* A crossplatform way to create file associations ([f8840e1](https://github.com/electron-userland/electron-builder/commit/f8840e1)), closes [#409](https://github.com/electron-userland/electron-builder/issues/409)



<a name="6.0.3"></a>
## [6.0.3](https://github.com/electron-userland/electron-builder/compare/v6.0.2...v6.0.3) (2016-08-29)


### Bug Fixes

* **squirrel.windows:** stdout maxBuffer exceeded ([0b84868](https://github.com/electron-userland/electron-builder/commit/0b84868)), closes [#709](https://github.com/electron-userland/electron-builder/issues/709)



<a name="6.0.2"></a>
## [6.0.2](https://github.com/electron-userland/electron-builder/compare/v6.0.1...v6.0.2) (2016-08-27)


### Bug Fixes

* pattern **/*.js still copies all files ([51309bf](https://github.com/electron-userland/electron-builder/commit/51309bf)), closes [#701](https://github.com/electron-userland/electron-builder/issues/701)



<a name="6.0.1"></a>
## [6.0.1](https://github.com/electron-userland/electron-builder/compare/v6.0.0...v6.0.1) (2016-08-27)


### Bug Fixes

* close write steam on finish ([a6b7573](https://github.com/electron-userland/electron-builder/commit/a6b7573)), closes [#706](https://github.com/electron-userland/electron-builder/issues/706)



<a name="6.0.0"></a>
# [6.0.0](https://github.com/electron-userland/electron-builder/compare/v5.35.0...v6.0.0) (2016-08-27)


### Bug Fixes

* add undocumented dereference as workaround of #675 ([9fe326d](https://github.com/electron-userland/electron-builder/commit/9fe326d))
* rename linux to linux-unpacked #670 ([5d404ea](https://github.com/electron-userland/electron-builder/commit/5d404ea))


### Features

* set AppImage as default target for Linux ([8f55a2d](https://github.com/electron-userland/electron-builder/commit/8f55a2d))


### BREAKING CHANGES

* default target for Linux changed from `deb` to `AppImage`



<a name="5.35.0"></a>
# [5.35.0](https://github.com/electron-userland/electron-builder/compare/v5.34.1...v5.35.0) (2016-08-26)


### Features

* support from/to paths in file patterns for extraFiles and extraResources ([308438f](https://github.com/electron-userland/electron-builder/commit/308438f)), closes [#650](https://github.com/electron-userland/electron-builder/issues/650)



<a name="5.34.1"></a>
## [5.34.1](https://github.com/electron-userland/electron-builder/compare/v5.34.0...v5.34.1) (2016-08-22)


### Bug Fixes

* auto-unpack doesn't create file parent dirs ([26c8360](https://github.com/electron-userland/electron-builder/commit/26c8360)), closes [#689](https://github.com/electron-userland/electron-builder/issues/689)



<a name="5.34.0"></a>
# [5.34.0](https://github.com/electron-userland/electron-builder/compare/v5.33.0...v5.34.0) (2016-08-22)


### Bug Fixes

* Getting AppVeyor to Generate an Installer (Build Artifacts) ([bc9d437](https://github.com/electron-userland/electron-builder/commit/bc9d437)), closes [#674](https://github.com/electron-userland/electron-builder/issues/674)


### Features

* custom app scheme ([b7121c5](https://github.com/electron-userland/electron-builder/commit/b7121c5)), closes [#575](https://github.com/electron-userland/electron-builder/issues/575)



<a name="5.33.0"></a>
# [5.33.0](https://github.com/electron-userland/electron-builder/compare/v5.32.1...v5.33.0) (2016-08-22)


### Features

* add node-gyp-rebuild #683 ([e3a5899](https://github.com/electron-userland/electron-builder/commit/e3a5899))



<a name="5.32.1"></a>
## [5.32.1](https://github.com/electron-userland/electron-builder/compare/v5.32.0...v5.32.1) (2016-08-20)


### Bug Fixes

* XDG_DATA_DIRS is missing when starting AppImage on Fedora 24 ([92d4895](https://github.com/electron-userland/electron-builder/commit/92d4895)), closes [#682](https://github.com/electron-userland/electron-builder/issues/682)



<a name="5.32.0"></a>
# [5.32.0](https://github.com/electron-userland/electron-builder/compare/v5.31.1...v5.32.0) (2016-08-20)


### Features

* nodeGypRebuild ([6d433ad](https://github.com/electron-userland/electron-builder/commit/6d433ad)), closes [#683](https://github.com/electron-userland/electron-builder/issues/683)



<a name="5.31.1"></a>
## [5.31.1](https://github.com/electron-userland/electron-builder/compare/v5.31.0...v5.31.1) (2016-08-20)


### Bug Fixes

* pass --build-from-source to force native dep compilation ([ef5f146](https://github.com/electron-userland/electron-builder/commit/ef5f146)), closes [#647](https://github.com/electron-userland/electron-builder/issues/647)



<a name="5.31.0"></a>
# [5.31.0](https://github.com/electron-userland/electron-builder/compare/v5.30.0...v5.31.0) (2016-08-20)


### Features

* **nsis:** per-machine installer automatically removes per-user installation ([834434c](https://github.com/electron-userland/electron-builder/commit/834434c)), closes [#621](https://github.com/electron-userland/electron-builder/issues/621) [#672](https://github.com/electron-userland/electron-builder/issues/672)



<a name="5.30.0"></a>
# [5.30.0](https://github.com/electron-userland/electron-builder/compare/v5.29.0...v5.30.0) (2016-08-19)


### Features

* **nsis:** one-click installer automatically removes old version #621 ([682ddde](https://github.com/electron-userland/electron-builder/commit/682ddde))



<a name="5.29.0"></a>
# [5.29.0](https://github.com/electron-userland/electron-builder/compare/v5.28.2...v5.29.0) (2016-08-17)


### Features

* **nsis:** per-machine installer automatically removes old version #621 ([2c3d8c2](https://github.com/electron-userland/electron-builder/commit/2c3d8c2))



<a name="5.28.2"></a>
## [5.28.2](https://github.com/electron-userland/electron-builder/compare/v5.28.1...v5.28.2) (2016-08-17)


### Bug Fixes

* skip rcedit for .msi installer ([d40e0b5](https://github.com/electron-userland/electron-builder/commit/d40e0b5)), closes [#677](https://github.com/electron-userland/electron-builder/issues/677)



<a name="5.28.1"></a>
## [5.28.1](https://github.com/electron-userland/electron-builder/compare/v5.28.0...v5.28.1) (2016-08-17)


### Bug Fixes

* disable dual-signing for .msi installer ([903148b](https://github.com/electron-userland/electron-builder/commit/903148b))



<a name="5.28.0"></a>
# [5.28.0](https://github.com/electron-userland/electron-builder/compare/v5.27.0...v5.28.0) (2016-08-16)


### Features

* **nsis:** custom icon for file association #409 ([09497cc](https://github.com/electron-userland/electron-builder/commit/09497cc))



<a name="5.27.0"></a>
# [5.27.0](https://github.com/electron-userland/electron-builder/compare/v5.26.0...v5.27.0) (2016-08-16)


### Features

* NSIS sign uninstaller ([17c0a82](https://github.com/electron-userland/electron-builder/commit/17c0a82)), closes [#526](https://github.com/electron-userland/electron-builder/issues/526)



<a name="5.26.0"></a>
# [5.26.0](https://github.com/electron-userland/electron-builder/compare/v5.25.1...v5.26.0) (2016-08-12)


### Bug Fixes

* Build fails due to peer dependency errors ([fcecbf0](https://github.com/electron-userland/electron-builder/commit/fcecbf0)), closes [#611](https://github.com/electron-userland/electron-builder/issues/611)
* Do not trash old build artifacts ([361b369](https://github.com/electron-userland/electron-builder/commit/361b369)), closes [#586](https://github.com/electron-userland/electron-builder/issues/586)
* do not required email for all Linux targets ([ddfa6fc](https://github.com/electron-userland/electron-builder/commit/ddfa6fc))


### Features

* Changing build attributes for different environment ([b9d0139](https://github.com/electron-userland/electron-builder/commit/b9d0139)), closes [#639](https://github.com/electron-userland/electron-builder/issues/639)



<a name="5.25.1"></a>
## [5.25.1](https://github.com/electron-userland/electron-builder/compare/v5.25.0...v5.25.1) (2016-08-12)


### Bug Fixes

* Bump electron-wininstaller-fixed to Squirrel 1.4.4 ([8008734](https://github.com/electron-userland/electron-builder/commit/8008734))



<a name="5.25.0"></a>
# [5.25.0](https://github.com/electron-userland/electron-builder/compare/v5.24.1...v5.25.0) (2016-08-11)


### Bug Fixes

* remove outdated license check ([8665ef4](https://github.com/electron-userland/electron-builder/commit/8665ef4))


### Features

* bundle osslsigncode for Linux ([fc8d6c6](https://github.com/electron-userland/electron-builder/commit/fc8d6c6))



<a name="5.24.1"></a>
## [5.24.1](https://github.com/electron-userland/electron-builder/compare/v5.24.0...v5.24.1) (2016-08-10)


### Bug Fixes

* Some files in app.asar get corrupted ([ee2f7c8](https://github.com/electron-userland/electron-builder/commit/ee2f7c8)), closes [#662](https://github.com/electron-userland/electron-builder/issues/662)



<a name="5.24.0"></a>
# [5.24.0](https://github.com/electron-userland/electron-builder/compare/v5.23.2...v5.24.0) (2016-08-09)


### Features

* **nsis:** multilang installer ([50d27bf](https://github.com/electron-userland/electron-builder/commit/50d27bf)), closes [#643](https://github.com/electron-userland/electron-builder/issues/643) [#646](https://github.com/electron-userland/electron-builder/issues/646)
*  EV certificate code signing (custom /n and /tr) ([e008c19](https://github.com/electron-userland/electron-builder/commit/e008c19)), closes [#627](https://github.com/electron-userland/electron-builder/issues/627) [#590](https://github.com/electron-userland/electron-builder/issues/590)
*  remove OriginalFilename, add LegalTrademarks, add ProductVersion for NSIS ([6a906ac](https://github.com/electron-userland/electron-builder/commit/6a906ac)), closes [#655](https://github.com/electron-userland/electron-builder/issues/655)



<a name="5.23.2"></a>
## [5.23.2](https://github.com/electron-userland/electron-builder/compare/v5.23.1...v5.23.2) (2016-08-05)


### Bug Fixes

* **AppImage:** app bin detection ([06def89](https://github.com/electron-userland/electron-builder/commit/06def89))



<a name="5.23.1"></a>
## [5.23.1](https://github.com/electron-userland/electron-builder/compare/v5.23.0...v5.23.1) (2016-08-05)


### Bug Fixes

* one-click CHECK_APP_RUNNING before SetSilent ([282fc72](https://github.com/electron-userland/electron-builder/commit/282fc72))
* one-click installer — Uninstall Confirm Dialog Option for One-click Windows NSIS #618 ([b3c49cb](https://github.com/electron-userland/electron-builder/commit/b3c49cb))



<a name="5.23.0"></a>
# [5.23.0](https://github.com/electron-userland/electron-builder/compare/v5.22.2...v5.23.0) (2016-08-04)


### Features

* prevent error "Unable to find a valid app" ([1778a8d](https://github.com/electron-userland/electron-builder/commit/1778a8d)), closes [#633](https://github.com/electron-userland/electron-builder/issues/633)
* support electron package https://github.com/electron-userland/electron-prebuilt/issues/160 ([aa0682f](https://github.com/electron-userland/electron-builder/commit/aa0682f))



<a name="5.22.2"></a>
## [5.22.2](https://github.com/electron-userland/electron-builder/compare/v5.22.1...v5.22.2) (2016-08-04)


### Bug Fixes

* Can't build on OSX (x64) since electron-builder 5.19.0 ([753cd08](https://github.com/electron-userland/electron-builder/commit/753cd08)), closes [#635](https://github.com/electron-userland/electron-builder/issues/635)



<a name="5.22.1"></a>
## [5.22.1](https://github.com/electron-userland/electron-builder/compare/v5.20.0...v5.22.1) (2016-08-02)


### Bug Fixes

* AppImage does not run when invoked in unpacked form ([9731225](https://github.com/electron-userland/electron-builder/commit/9731225)), closes [#592](https://github.com/electron-userland/electron-builder/issues/592)
* Failing to sign the Windows build on Linux ([a6a0cd6](https://github.com/electron-userland/electron-builder/commit/a6a0cd6)), closes [#578](https://github.com/electron-userland/electron-builder/issues/578)
* NSIS Installer hangs when being run silently ([d0a4f90](https://github.com/electron-userland/electron-builder/commit/d0a4f90)), closes [#616](https://github.com/electron-userland/electron-builder/issues/616)
* Windows NSIS One-Click Setup Launched while App already running in background ([918a6c0](https://github.com/electron-userland/electron-builder/commit/918a6c0)), closes [#617](https://github.com/electron-userland/electron-builder/issues/617)
* don't take in account just directory `app` without `package.json` ([3418239](https://github.com/electron-userland/electron-builder/commit/3418239))
* extraMetadata — deep assign ([6a5c4bb](https://github.com/electron-userland/electron-builder/commit/6a5c4bb))


### Features

* --extraMetadata for conditional compilation ([da700d4](https://github.com/electron-userland/electron-builder/commit/da700d4)), closes [#494](https://github.com/electron-userland/electron-builder/issues/494)
* Uninstall Confirm Dialog Option for One-click Windows NSIS ([e99047d](https://github.com/electron-userland/electron-builder/commit/e99047d)), closes [#618](https://github.com/electron-userland/electron-builder/issues/618)



<a name="5.20.0"></a>
# [5.20.0](https://github.com/electron-userland/electron-builder/compare/v5.19.1...v5.20.0) (2016-07-29)


### Features

* Make sure compiled app has same hash on different computers ([d773077](https://github.com/electron-userland/electron-builder/commit/d773077)), closes [#604](https://github.com/electron-userland/electron-builder/issues/604)



<a name="5.19.1"></a>
## [5.19.1](https://github.com/electron-userland/electron-builder/compare/v5.19.0...v5.19.1) (2016-07-29)


### Bug Fixes

* Certificate file for sign was gone (provides with file://) under windows ([04a88b0](https://github.com/electron-userland/electron-builder/commit/04a88b0)), closes [#619](https://github.com/electron-userland/electron-builder/issues/619)



<a name="5.19.0"></a>
# [5.19.0](https://github.com/electron-userland/electron-builder/compare/v5.18.0...v5.19.0) (2016-07-28)


### Features

* don't pack into asar node module that contains executable/binary files ([e975881](https://github.com/electron-userland/electron-builder/commit/e975881)), closes [#602](https://github.com/electron-userland/electron-builder/issues/602)



<a name="5.18.0"></a>
# [5.18.0](https://github.com/electron-userland/electron-builder/compare/v5.17.1...v5.18.0) (2016-07-28)


### Bug Fixes

* remove "Warning: homepage" ([0fd6a3e](https://github.com/electron-userland/electron-builder/commit/0fd6a3e))


### Features

* NSIS script customization — script option ([a807b17](https://github.com/electron-userland/electron-builder/commit/a807b17)), closes [#583](https://github.com/electron-userland/electron-builder/issues/583)



<a name="5.17.1"></a>
## [5.17.1](https://github.com/electron-userland/electron-builder/compare/v5.17.0...v5.17.1) (2016-07-27)


### Bug Fixes

* do not use scoped asara package ([c53074c](https://github.com/electron-userland/electron-builder/commit/c53074c)), closes [#610](https://github.com/electron-userland/electron-builder/issues/610)



<a name="5.17.0"></a>
# [5.17.0](https://github.com/electron-userland/electron-builder/compare/v5.16.0...v5.17.0) (2016-07-27)


### Features

* NSIS script customization #583 ([63beaaf](https://github.com/electron-userland/electron-builder/commit/63beaaf))



<a name="5.16.0"></a>
# [5.16.0](https://github.com/electron-userland/electron-builder/compare/v5.15.0...v5.16.0) (2016-07-22)


### Features

* exclude **/node_modules/*/{README.md,README,readme.md,readme,test} by default ([5895583](https://github.com/electron-userland/electron-builder/commit/5895583)), closes [#591](https://github.com/electron-userland/electron-builder/issues/591) [#606](https://github.com/electron-userland/electron-builder/issues/606)
* exclude extraResources/extraFiles for one-package dir ([3aaf025](https://github.com/electron-userland/electron-builder/commit/3aaf025)), closes [#599](https://github.com/electron-userland/electron-builder/issues/599)



<a name="5.15.0"></a>
# [5.15.0](https://github.com/electron-userland/electron-builder/compare/v5.14.2...v5.15.0) (2016-07-21)


### Features

* **Linux:** app icon is not required ([ec0bda5](https://github.com/electron-userland/electron-builder/commit/ec0bda5)), closes [#593](https://github.com/electron-userland/electron-builder/issues/593)



<a name="5.14.2"></a>
## [5.14.2](https://github.com/electron-userland/electron-builder/compare/v5.14.1...v5.14.2) (2016-07-20)


### Bug Fixes

* **nsis:** fix all nsis warnings ([9a3fd5e](https://github.com/electron-userland/electron-builder/commit/9a3fd5e))



<a name="5.14.1"></a>
## [5.14.1](https://github.com/electron-userland/electron-builder/compare/v5.14.0...v5.14.1) (2016-07-19)


### Bug Fixes

* **AppImage:** AppImage should have arch in filename ([e7d4f76](https://github.com/electron-userland/electron-builder/commit/e7d4f76)), closes [#594](https://github.com/electron-userland/electron-builder/issues/594)



<a name="5.14.0"></a>
# [5.14.0](https://github.com/electron-userland/electron-builder/compare/v5.13.1...v5.14.0) (2016-07-18)


### Features

* file associations ([fd1e7da](https://github.com/electron-userland/electron-builder/commit/fd1e7da)), closes [#563](https://github.com/electron-userland/electron-builder/issues/563)



<a name="5.13.1"></a>
## [5.13.1](https://github.com/electron-userland/electron-builder/compare/v5.13.0...v5.13.1) (2016-07-14)


### Bug Fixes

* win codesign on windows 7 ([d78c69c](https://github.com/electron-userland/electron-builder/commit/d78c69c)), closes [#581](https://github.com/electron-userland/electron-builder/issues/581) [#584](https://github.com/electron-userland/electron-builder/issues/584)



<a name="5.13.0"></a>
# [5.13.0](https://github.com/electron-userland/electron-builder/compare/v5.12.1...v5.13.0) (2016-07-13)


### Features

* **Squirrel.Windows:** Automatic remoteReleases configuration ([d6aa555](https://github.com/electron-userland/electron-builder/commit/d6aa555)), closes [#561](https://github.com/electron-userland/electron-builder/issues/561)
* **nsis:** run after finish flag for one-click installer ([50039ea](https://github.com/electron-userland/electron-builder/commit/50039ea)), closes [#574](https://github.com/electron-userland/electron-builder/issues/574)



<a name="5.12.1"></a>
## [5.12.1](https://github.com/electron-userland/electron-builder/compare/v5.12.0...v5.12.1) (2016-07-11)


### Bug Fixes

* **nsis:** per machine assisted installer ([1bd32a7](https://github.com/electron-userland/electron-builder/commit/1bd32a7)), closes [#564](https://github.com/electron-userland/electron-builder/issues/564)



<a name="5.12.0"></a>
# [5.12.0](https://github.com/electron-userland/electron-builder/compare/v5.11.3...v5.12.0) (2016-07-09)


### Bug Fixes

* **nsis:** install per current user even if run as administrator ([a01f481](https://github.com/electron-userland/electron-builder/commit/a01f481))


### Features

* **nsis:** per machine one-click installer #564 ([9f52848](https://github.com/electron-userland/electron-builder/commit/9f52848))



<a name="5.11.3"></a>
## [5.11.3](https://github.com/electron-userland/electron-builder/compare/v5.11.2...v5.11.3) (2016-07-09)


### Bug Fixes

* **AppImage:** bundle xorriso ([a1bf645](https://github.com/electron-userland/electron-builder/commit/a1bf645))



<a name="5.11.2"></a>
## [5.11.2](https://github.com/electron-userland/electron-builder/compare/v5.11.1...v5.11.2) (2016-07-07)


### Bug Fixes

* **AppImage:** do not pack into archive, add `.AppImage` suffix ([f59c7bd](https://github.com/electron-userland/electron-builder/commit/f59c7bd))



<a name="5.11.1"></a>
## [5.11.1](https://github.com/electron-userland/electron-builder/compare/v5.11.0...v5.11.1) (2016-07-07)


### Bug Fixes

* **nsis:** ia32 Extracting wrong archive ([56b3450](https://github.com/electron-userland/electron-builder/commit/56b3450)), closes [#567](https://github.com/electron-userland/electron-builder/issues/567)



<a name="5.11.0"></a>
# [5.11.0](https://github.com/electron-userland/electron-builder/compare/v5.10.5...v5.11.0) (2016-07-07)


### Bug Fixes

* AppImage desktop icons ([9a69286](https://github.com/electron-userland/electron-builder/commit/9a69286))
* **AppImage:** use app name as a executable name ([159446b](https://github.com/electron-userland/electron-builder/commit/159446b))


### Features

* Build AppImage for Linux ([a9afdd4](https://github.com/electron-userland/electron-builder/commit/a9afdd4)), closes [#504](https://github.com/electron-userland/electron-builder/issues/504)
* multi-cert p12 ([de01c6d](https://github.com/electron-userland/electron-builder/commit/de01c6d)), closes [#560](https://github.com/electron-userland/electron-builder/issues/560)
* **mac:** Add build-version override property ([0b0ed62](https://github.com/electron-userland/electron-builder/commit/0b0ed62)), closes [#565](https://github.com/electron-userland/electron-builder/issues/565)



<a name="5.10.5"></a>
## [5.10.5](https://github.com/electron-userland/electron-builder/compare/v5.10.4...v5.10.5) (2016-07-03)


### Bug Fixes

* CSC_INSTALLER_KEY_PASSWORD environment variable isn't picked up #560 ([3fdd1f8](https://github.com/electron-userland/electron-builder/commit/3fdd1f8))
* CSC_INSTALLER_LINK environment variable isn't picked up #560 ([1c2632d](https://github.com/electron-userland/electron-builder/commit/1c2632d))



<a name="5.10.4"></a>
## [5.10.4](https://github.com/electron-userland/electron-builder/compare/v5.10.3...v5.10.4) (2016-07-02)


### Bug Fixes

* non-English characters confuse rcedit: Unable to load file on windows build (from linux) ([233fafe](https://github.com/electron-userland/electron-builder/commit/233fafe)), closes [#384](https://github.com/electron-userland/electron-builder/issues/384)



<a name="5.10.3"></a>
## [5.10.3](https://github.com/electron-userland/electron-builder/compare/v5.10.2...v5.10.3) (2016-07-01)


### Bug Fixes

* Ignore .DS_Store Files ([152b987](https://github.com/electron-userland/electron-builder/commit/152b987)), closes [#545](https://github.com/electron-userland/electron-builder/issues/545)
* dereference copied app files only for windows targets ([bf2aafb](https://github.com/electron-userland/electron-builder/commit/bf2aafb))



<a name="5.10.2"></a>
## [5.10.2](https://github.com/electron-userland/electron-builder/compare/v5.10.1...v5.10.2) (2016-06-28)


### Bug Fixes

* **nsis:** installerHeaderIcon ([00e8da8](https://github.com/electron-userland/electron-builder/commit/00e8da8)), closes [#525](https://github.com/electron-userland/electron-builder/issues/525)



<a name="5.10.1"></a>
## [5.10.1](https://github.com/electron-userland/electron-builder/compare/v5.10.0...v5.10.1) (2016-06-27)


### Bug Fixes

* Build failing when productName contains a slash ([726e574](https://github.com/electron-userland/electron-builder/commit/726e574)), closes [#539](https://github.com/electron-userland/electron-builder/issues/539)



<a name="5.10.0"></a>
# [5.10.0](https://github.com/electron-userland/electron-builder/compare/v5.9.0...v5.10.0) (2016-06-26)


### Features

* **publisher:** Check that tag name starts with "v" #340 ([bb71621](https://github.com/electron-userland/electron-builder/commit/bb71621))



<a name="5.9.0"></a>
# [5.9.0](https://github.com/electron-userland/electron-builder/compare/v5.8.0...v5.9.0) (2016-06-26)


### Features

* **nsis:** Different Icon for installer / App ? (Windows) ([65650ea](https://github.com/electron-userland/electron-builder/commit/65650ea)), closes [#525](https://github.com/electron-userland/electron-builder/issues/525)



<a name="5.8.0"></a>
# [5.8.0](https://github.com/electron-userland/electron-builder/compare/v5.7.0...v5.8.0) (2016-06-26)


### Bug Fixes

* **mas:** cannot find mas installer ([5ba6276](https://github.com/electron-userland/electron-builder/commit/5ba6276)), closes [#535](https://github.com/electron-userland/electron-builder/issues/535)


### Features

* **nsis:** 32 bit + 64 bit installer ([bbd0bd6](https://github.com/electron-userland/electron-builder/commit/bbd0bd6)), closes [#528](https://github.com/electron-userland/electron-builder/issues/528) [#536](https://github.com/electron-userland/electron-builder/issues/536)



<a name="5.7.0"></a>
# [5.7.0](https://github.com/electron-userland/electron-builder/compare/v5.6.3...v5.7.0) (2016-06-24)


### Bug Fixes

* don't throw release must be a draft if onTag policy was guessed ([26c89f0](https://github.com/electron-userland/electron-builder/commit/26c89f0))


### Features

* **nsis:** MUI_HEADERIMAGE #525 ([3f43c0a](https://github.com/electron-userland/electron-builder/commit/3f43c0a))



<a name="5.6.3"></a>
## [5.6.3](https://github.com/electron-userland/electron-builder/compare/v5.6.2...v5.6.3) (2016-06-23)


### Bug Fixes

* Installation Has Failed - Seems to be an issue with the RELEASES file ([7c84f5f](https://github.com/electron-userland/electron-builder/commit/7c84f5f)), closes [#534](https://github.com/electron-userland/electron-builder/issues/534)



<a name="5.6.2"></a>
## [5.6.2](https://github.com/electron-userland/electron-builder/compare/v5.6.1...v5.6.2) (2016-06-23)


### Bug Fixes

* Creating an MSI on Windows fails ([d1ee7de](https://github.com/electron-userland/electron-builder/commit/d1ee7de)), closes [#485](https://github.com/electron-userland/electron-builder/issues/485)



<a name="5.6.1"></a>
## [5.6.1](https://github.com/electron-userland/electron-builder/compare/v5.6.0...v5.6.1) (2016-06-22)


### Bug Fixes

* `build --target dir` doesn't work ([f880157](https://github.com/electron-userland/electron-builder/commit/f880157)), closes [#531](https://github.com/electron-userland/electron-builder/issues/531)



<a name="5.6.0"></a>
# [5.6.0](https://github.com/electron-userland/electron-builder/compare/v5.5.0...v5.6.0) (2016-06-21)


### Features

* specified icon not being used when generating osx build ([74388bb](https://github.com/electron-userland/electron-builder/commit/74388bb)), closes [#519](https://github.com/electron-userland/electron-builder/issues/519)



<a name="5.5.0"></a>
# [5.5.0](https://github.com/electron-userland/electron-builder/compare/v5.4.4...v5.5.0) (2016-06-19)


### Features

* finish NSIS installer look and feel ([e50e3c8](https://github.com/electron-userland/electron-builder/commit/e50e3c8))



<a name="5.4.4"></a>
## [5.4.4](https://github.com/electron-userland/electron-builder/compare/v5.4.3...v5.4.4) (2016-06-17)


### Bug Fixes

* NSIS LZMA compression is slower and worse then external 7z compression ([e1e6d67](https://github.com/electron-userland/electron-builder/commit/e1e6d67))
* ignore dev deps if ignore func specified ([0944985](https://github.com/electron-userland/electron-builder/commit/0944985))
* validate bin checksum ([0f9d2e1](https://github.com/electron-userland/electron-builder/commit/0f9d2e1))


### Performance Improvements

* create asar without intermediate copy ([95c8a0c](https://github.com/electron-userland/electron-builder/commit/95c8a0c))



<a name="5.4.3"></a>
## [5.4.3](https://github.com/electron-userland/electron-builder/compare/v5.4.2...v5.4.3) (2016-06-16)


### Bug Fixes

* allow passing absolute and relative path as userAppDir option (#515) ([df096f0](https://github.com/electron-userland/electron-builder/commit/df096f0))



<a name="5.4.2"></a>
## [5.4.2](https://github.com/electron-userland/electron-builder/compare/v5.4.1...v5.4.2) (2016-06-16)


### Bug Fixes

* ignore com.apple.idms.appleid.prd. certs ([b69d3ab](https://github.com/electron-userland/electron-builder/commit/b69d3ab)), closes [#510](https://github.com/electron-userland/electron-builder/issues/510)



<a name="5.4.1"></a>
## [5.4.1](https://github.com/electron-userland/electron-builder/compare/v5.4.0...v5.4.1) (2016-06-14)


### Bug Fixes

* don't use deb default deps for other targets #502 ([c3679e7](https://github.com/electron-userland/electron-builder/commit/c3679e7))



<a name="5.4.0"></a>
# [5.4.0](https://github.com/electron-userland/electron-builder/compare/v5.3.0...v5.4.0) (2016-06-14)


### Features

* NSIS target (#495) ([d8762db](https://github.com/electron-userland/electron-builder/commit/d8762db)), closes [#472](https://github.com/electron-userland/electron-builder/issues/472) [#493](https://github.com/electron-userland/electron-builder/issues/493)



<a name="5.3.0"></a>
# [5.3.0](https://github.com/electron-userland/electron-builder/compare/v5.2.1...v5.3.0) (2016-06-14)


### Features

* adding dot asar option (#496) ([3fc7a89](https://github.com/electron-userland/electron-builder/commit/3fc7a89))



<a name="5.2.1"></a>
## [5.2.1](https://github.com/electron-userland/electron-builder/compare/v5.2.0...v5.2.1) (2016-06-12)


### Bug Fixes

* don't try to build OS X x64 ([ee64432](https://github.com/electron-userland/electron-builder/commit/ee64432))



<a name="5.2.0"></a>
# [5.2.0](https://github.com/electron-userland/electron-builder/compare/v5.1.0...v5.2.0) (2016-06-11)


### Features

* Ability to set author/CompanyName programmatically ([63c2529](https://github.com/electron-userland/electron-builder/commit/63c2529)), closes [#455](https://github.com/electron-userland/electron-builder/issues/455)
* Add Ability to Create Pre-Releases and Releases ([e5b0c04](https://github.com/electron-userland/electron-builder/commit/e5b0c04)), closes [#446](https://github.com/electron-userland/electron-builder/issues/446)



<a name="5.1.0"></a>
# [5.1.0](https://github.com/electron-userland/electron-builder/compare/v5.0.3...v5.1.0) (2016-06-10)


### Bug Fixes

* Builder attempts to sign OSX app even though no signing is specified ([24f6045](https://github.com/electron-userland/electron-builder/commit/24f6045)), closes [#481](https://github.com/electron-userland/electron-builder/issues/481) [#484](https://github.com/electron-userland/electron-builder/issues/484)


### Features

* Windows targets `7z`, `zip`, `tar.xz`, `tar.lz`, `tar.gz`, `tar.bz2` ([1c983d4](https://github.com/electron-userland/electron-builder/commit/1c983d4))



<a name="5.0.3"></a>
## [5.0.3](https://github.com/electron-userland/electron-builder/compare/v5.0.2...v5.0.3) (2016-06-10)


### Bug Fixes

* Asar: true failing on Windows for electron-builder 5.x ([317a330](https://github.com/electron-userland/electron-builder/commit/317a330)), closes [#482](https://github.com/electron-userland/electron-builder/issues/482)



<a name="5.0.2"></a>
## [5.0.2](https://github.com/electron-userland/electron-builder/compare/v5.0.1...v5.0.2) (2016-06-09)


### Bug Fixes

* mas target — Identity name is specified, but no valid identity with this name in the keychain ([b091a13](https://github.com/electron-userland/electron-builder/commit/b091a13)), closes [#479](https://github.com/electron-userland/electron-builder/issues/479)



<a name="5.0.1"></a>
## [5.0.1](https://github.com/electron-userland/electron-builder/compare/v5.0.0...v5.0.1) (2016-06-09)


### Bug Fixes

* restore `--platform` and `--arch` CLI ([7f9e6e3](https://github.com/electron-userland/electron-builder/commit/7f9e6e3))



<a name="5.0.0"></a>
# [5.0.0](https://github.com/electron-userland/electron-builder/compare/v4.2.6...v5.0.0) (2016-06-08)


### Bug Fixes

* efficient implementation of copy extra files/resources ([5853514](https://github.com/electron-userland/electron-builder/commit/5853514))


### Features

* Development dependencies are never copied in any case ([6d4ab11](https://github.com/electron-userland/electron-builder/commit/6d4ab11))
* files option ([0f7624d](https://github.com/electron-userland/electron-builder/commit/0f7624d))


### BREAKING CHANGES

* prune by default, hidden files are not copied by default anymore



<a name="4.2.6"></a>
## [4.2.6](https://github.com/electron-userland/electron-builder/compare/v4.2.5...v4.2.6) (2016-06-06)


### Bug Fixes

* OS X code signing — cert type prefix must be added, restore non-Apple cert support ([97e16a2](https://github.com/electron-userland/electron-builder/commit/97e16a2)), closes [#458](https://github.com/electron-userland/electron-builder/issues/458)



<a name="4.2.5"></a>
## [4.2.5](https://github.com/electron-userland/electron-builder/compare/v4.2.4...v4.2.5) (2016-06-06)


### Bug Fixes

* Fallback to CSC_KEY_PASSWORD if certificatePassword not given ([aea6505](https://github.com/electron-userland/electron-builder/commit/aea6505)), closes [#475](https://github.com/electron-userland/electron-builder/issues/475)



<a name="4.2.4"></a>
## [4.2.4](https://github.com/electron-userland/electron-builder/compare/v4.2.3...v4.2.4) (2016-06-06)


### Bug Fixes

* Squirrel-packed executable not signed ([eb10afb](https://github.com/electron-userland/electron-builder/commit/eb10afb)), closes [#449](https://github.com/electron-userland/electron-builder/issues/449)



<a name="4.2.3"></a>
## [4.2.3](https://github.com/electron-userland/electron-builder/compare/v4.2.2...v4.2.3) (2016-06-05)


### Bug Fixes

* building windows 32 bit and 64 bit simultaneously ([cec4b3d](https://github.com/electron-userland/electron-builder/commit/cec4b3d)), closes [#470](https://github.com/electron-userland/electron-builder/issues/470)



<a name="4.2.2"></a>
## [4.2.2](https://github.com/electron-userland/electron-builder/compare/v4.2.1...v4.2.2) (2016-06-03)


### Bug Fixes

* 4.2.1 Doesn't Include `.node` Files ([12ba8b7](https://github.com/electron-userland/electron-builder/commit/12ba8b7)), closes [#468](https://github.com/electron-userland/electron-builder/issues/468)



<a name="4.2.1"></a>
## [4.2.1](https://github.com/electron-userland/electron-builder/compare/v4.2.0...v4.2.1) (2016-06-03)


### Bug Fixes

* Application entry can't be found ([a7b2932](https://github.com/electron-userland/electron-builder/commit/a7b2932)), closes [#371](https://github.com/electron-userland/electron-builder/issues/371)
* icudtl.dat: file changed as we read it ([567c813](https://github.com/electron-userland/electron-builder/commit/567c813)), closes [#460](https://github.com/electron-userland/electron-builder/issues/460)
* warn "It is not possible to build OS X app on Windows" ([f6c47f7](https://github.com/electron-userland/electron-builder/commit/f6c47f7)), closes [#422](https://github.com/electron-userland/electron-builder/issues/422)



<a name="4.2.0"></a>
# [4.2.0](https://github.com/electron-userland/electron-builder/compare/v4.1.0...v4.2.0) (2016-06-02)


### Bug Fixes

* Don´t throw error if Release is not a Draft and build triggered by Tag ([0f060c1](https://github.com/electron-userland/electron-builder/commit/0f060c1)), closes [#429](https://github.com/electron-userland/electron-builder/issues/429)
* entitlements file names according to new electron-osx-sign conventions ([ecdff3c](https://github.com/electron-userland/electron-builder/commit/ecdff3c))
* log github publisher user and project #425 ([c2c3ef6](https://github.com/electron-userland/electron-builder/commit/c2c3ef6))
* move npmRebuild to build ([1110596](https://github.com/electron-userland/electron-builder/commit/1110596))
* update electron-osx-sign to 0.4 beta ([bf93b24](https://github.com/electron-userland/electron-builder/commit/bf93b24))
* windows codesign on Linux ([7166580](https://github.com/electron-userland/electron-builder/commit/7166580))


### Features

* `--dist` by default ([ae3f1bb](https://github.com/electron-userland/electron-builder/commit/ae3f1bb)), closes [#413](https://github.com/electron-userland/electron-builder/issues/413)


### BREAKING CHANGES

* See new entitlements paths in the wiki



<a name="4.1.0"></a>
# [4.1.0](https://github.com/electron-userland/electron-builder/compare/v4.0.0...v4.1.0) (2016-05-30)


### Features

* user-friendly MAS code signing ([fe53388](https://github.com/electron-userland/electron-builder/commit/fe53388))



<a name="4.0.0"></a>
# [4.0.0](https://github.com/electron-userland/electron-builder/compare/v3.27.0...v4.0.0) (2016-05-29)


### Features

* `--dist` by default and remove this flag in favour of `--target=dir #413 ([a5e4571](https://github.com/electron-userland/electron-builder/commit/a5e4571))
* extraFiles ([ca120e3](https://github.com/electron-userland/electron-builder/commit/ca120e3))
* option to skip installAppDependencies ([67ed60b](https://github.com/electron-userland/electron-builder/commit/67ed60b)), closes [#442](https://github.com/electron-userland/electron-builder/issues/442)


### BREAKING CHANGES

* `extraResources` copying files to `resources` on Linux/Windows, not to root directory as before. To copy to the root please use new option `extraFiles`.
* `appDir` CLI is removed — use [directories.app](https://github.com/electron-userland/electron-builder/wiki/Options#MetadataDirectories-app) in the development package.json. `sign` CLI is removed — use [build.osx.identity](https://github.com/electron-userland/electron-builder/wiki/Options#OsXBuildOptions-identity) in the development package.json.



<a name="3.27.0"></a>
# [3.27.0](https://github.com/electron-userland/electron-builder/compare/v3.26.3...v3.27.0) (2016-05-26)


### Features

* **windows:** specification of signing algorithms (#435) ([73e7c14](https://github.com/electron-userland/electron-builder/commit/73e7c14)), closes [#374](https://github.com/electron-userland/electron-builder/issues/374) [#416](https://github.com/electron-userland/electron-builder/issues/416)
* support finding electron version in build.electronVersion or electron-prebuilt-compile ([4c1f06d](https://github.com/electron-userland/electron-builder/commit/4c1f06d))



<a name="3.26.3"></a>
## [3.26.3](https://github.com/electron-userland/electron-builder/compare/v3.26.2...v3.26.3) (2016-05-23)


### Bug Fixes

* import bundled certs into login.keychain ([bffbbf1](https://github.com/electron-userland/electron-builder/commit/bffbbf1)), closes [#398](https://github.com/electron-userland/electron-builder/issues/398)



<a name="3.26.2"></a>
## [3.26.2](https://github.com/electron-userland/electron-builder/compare/v3.26.1...v3.26.2) (2016-05-23)


### Bug Fixes

* check that description is not empty ([a3bbb3f](https://github.com/electron-userland/electron-builder/commit/a3bbb3f)), closes [#392](https://github.com/electron-userland/electron-builder/issues/392)



<a name="3.26.1"></a>
## [3.26.1](https://github.com/electron-userland/electron-builder/compare/v3.26.0...v3.26.1) (2016-05-23)


### Bug Fixes

* forbid name in the build ([e4eefb2](https://github.com/electron-userland/electron-builder/commit/e4eefb2)), closes [#360](https://github.com/electron-userland/electron-builder/issues/360)



<a name="3.26.0"></a>
# [3.26.0](https://github.com/electron-userland/electron-builder/compare/v3.25.0...v3.26.0) (2016-05-23)


### Features

* **linux:** sh, rpm, freebsd, pacman, p5p, apk, 7z, zip, tar.xz, tar.gz, tar.bz2, tar.lz ([50d31f1](https://github.com/electron-userland/electron-builder/commit/50d31f1)), closes [#414](https://github.com/electron-userland/electron-builder/issues/414)



<a name="3.25.0"></a>
# [3.25.0](https://github.com/electron-userland/electron-builder/compare/v3.24.0...v3.25.0) (2016-05-18)


### Bug Fixes

* Trouble building delta package for Squirrel.Windows on OSX ([cc8278a](https://github.com/electron-userland/electron-builder/commit/cc8278a)), closes [#407](https://github.com/electron-userland/electron-builder/issues/407)


### Features

* **osx:** Optional DMG background ([4088b13](https://github.com/electron-userland/electron-builder/commit/4088b13))
* The function to be run after pack (but before pack into distributable format and sign) ([7f32573](https://github.com/electron-userland/electron-builder/commit/7f32573)), closes [#397](https://github.com/electron-userland/electron-builder/issues/397)
* check asar existence and integrity (#401) ([4a9af55](https://github.com/electron-userland/electron-builder/commit/4a9af55))



<a name="3.24.0"></a>
# [3.24.0](https://github.com/electron-userland/electron-builder/compare/v3.23.0...v3.24.0) (2016-05-15)


### Features

* **linux:** Install libappindicator1 and libnotify as a dependency of the linux package ([05baad5](https://github.com/electron-userland/electron-builder/commit/05baad5))



<a name="3.23.0"></a>
# [3.23.0](https://github.com/electron-userland/electron-builder/compare/v3.22.2...v3.23.0) (2016-05-14)


### Features

* bundle Certum cert ([2e0894f](https://github.com/electron-userland/electron-builder/commit/2e0894f)), closes [#398](https://github.com/electron-userland/electron-builder/issues/398)



<a name="3.22.2"></a>
## [3.22.2](https://github.com/electron-userland/electron-builder/compare/v3.22.1...v3.22.2) (2016-05-14)


### Bug Fixes

* **linux:** use full path in .desktop file (#405) ([1164ca1](https://github.com/electron-userland/electron-builder/commit/1164ca1))
* incorrect nupkg file if created on windows ([a5a23ae](https://github.com/electron-userland/electron-builder/commit/a5a23ae)), closes [#402](https://github.com/electron-userland/electron-builder/issues/402) [#351](https://github.com/electron-userland/electron-builder/issues/351)



<a name="3.22.1"></a>
## [3.22.1](https://github.com/electron-userland/electron-builder/compare/v3.22.0...v3.22.1) (2016-05-13)


### Bug Fixes

* win ia32 out dir name — unexpanded $arch ([8d9b952](https://github.com/electron-userland/electron-builder/commit/8d9b952))



<a name="3.22.0"></a>
# [3.22.0](https://github.com/electron-userland/electron-builder/compare/v3.21.0...v3.22.0) (2016-05-13)


### Features

* revert "Releases file for Windows not uploaded to Github #190" ([079989a](https://github.com/electron-userland/electron-builder/commit/079989a))



<a name="3.21.0"></a>
# [3.21.0](https://github.com/electron-userland/electron-builder/compare/v3.20.0...v3.21.0) (2016-05-12)


### Bug Fixes

* Cannot upload prerelease version ([05121df](https://github.com/electron-userland/electron-builder/commit/05121df)), closes [#395](https://github.com/electron-userland/electron-builder/issues/395)


### Features

* Squirrel.Windows doesn't escape " in the description ([6977557](https://github.com/electron-userland/electron-builder/commit/6977557)), closes [#378](https://github.com/electron-userland/electron-builder/issues/378)



<a name="3.20.0"></a>
# [3.20.0](https://github.com/electron-userland/electron-builder/compare/v3.19.0...v3.20.0) (2016-05-11)


### Bug Fixes

* http download to destination if no parent dirs created ([b5505fc](https://github.com/electron-userland/electron-builder/commit/b5505fc))


### Features

* dual code-sign windows app + timestamped ([b71d2f3](https://github.com/electron-userland/electron-builder/commit/b71d2f3))



<a name="3.19.0"></a>
# [3.19.0](https://github.com/electron-userland/electron-builder/compare/v3.18.0...v3.19.0) (2016-05-10)


### Features

* Code signing windows app using SHA256 ([032ba05](https://github.com/electron-userland/electron-builder/commit/032ba05)), closes [#386](https://github.com/electron-userland/electron-builder/issues/386)



<a name="3.18.0"></a>
# [3.18.0](https://github.com/electron-userland/electron-builder/compare/v3.17.1...v3.18.0) (2016-05-09)


### Bug Fixes

* user-friendly error message "Error: buffer is not ico" ([7ac6ca2](https://github.com/electron-userland/electron-builder/commit/7ac6ca2)), closes [#349](https://github.com/electron-userland/electron-builder/issues/349)


### Features

* base64-encoded P12 file instead of https link ([3ab0e57](https://github.com/electron-userland/electron-builder/commit/3ab0e57))
* cleanup unused fpm versions ([633d006](https://github.com/electron-userland/electron-builder/commit/633d006))
* use self-contained fpm on Linux — don't need to install ruby anymore ([7d5b747](https://github.com/electron-userland/electron-builder/commit/7d5b747))



<a name="3.17.1"></a>
## [3.17.1](https://github.com/electron-userland/electron-builder/compare/v3.17.0...v3.17.1) (2016-05-05)


### Bug Fixes

* bundle StartSSL certs ([16d3805](https://github.com/electron-userland/electron-builder/commit/16d3805))
* osx code sign regression ([2d0f5f1](https://github.com/electron-userland/electron-builder/commit/2d0f5f1)), closes [#377](https://github.com/electron-userland/electron-builder/issues/377)



<a name="3.17.0"></a>
# [3.17.0](https://github.com/electron-userland/electron-builder/compare/v3.16.1...v3.17.0) (2016-05-04)


### Features

* use self-containe fpm on OS X — don't need to install ruby anymore ([e7cee5e](https://github.com/electron-userland/electron-builder/commit/e7cee5e))



<a name="3.16.1"></a>
## [3.16.1](https://github.com/electron-userland/electron-builder/compare/v3.16.0...v3.16.1) (2016-05-03)


### Bug Fixes

* check wine version ([d77c8da](https://github.com/electron-userland/electron-builder/commit/d77c8da)), closes [#352](https://github.com/electron-userland/electron-builder/issues/352)



<a name="3.16.0"></a>
# [3.16.0](https://github.com/electron-userland/electron-builder/compare/v3.15.0...v3.16.0) (2016-05-02)


### Features

* add Jenkins build number support (#373) ([eebe882](https://github.com/electron-userland/electron-builder/commit/eebe882))



<a name="3.15.0"></a>
# [3.15.0](https://github.com/electron-userland/electron-builder/compare/v3.14.0...v3.15.0) (2016-05-02)


### Features

* iconUrl git-lfs support, os x identity/installerIdentity options ([974f7f3](https://github.com/electron-userland/electron-builder/commit/974f7f3)), closes [#332](https://github.com/electron-userland/electron-builder/issues/332)
* osx entitlements location by convention ([af1165b](https://github.com/electron-userland/electron-builder/commit/af1165b))



<a name="3.14.0"></a>
# [3.14.0](https://github.com/electron-userland/electron-builder/compare/v3.13.1...v3.14.0) (2016-04-29)


### Features

* build mas + other targets, osx 7z ([c46e1f5](https://github.com/electron-userland/electron-builder/commit/c46e1f5))



<a name="3.13.1"></a>
## [3.13.1](https://github.com/electron-userland/electron-builder/compare/v3.13.0...v3.13.1) (2016-04-28)


### Bug Fixes

* statFileInPackage in platformPackager.js creates wrong path ([7373131](https://github.com/electron-userland/electron-builder/commit/7373131)), closes [#365](https://github.com/electron-userland/electron-builder/issues/365)



<a name="3.13.0"></a>
# [3.13.0](https://github.com/electron-userland/electron-builder/compare/v3.12.0...v3.13.0) (2016-04-28)


### Bug Fixes

* add debug log to investigate "Cannot build app with 3.6.2+" #360 ([1970550](https://github.com/electron-userland/electron-builder/commit/1970550))


### Features

* DMG — use bzip2 compression (old: 40MB, new: 36MB) ([e0c3b92](https://github.com/electron-userland/electron-builder/commit/e0c3b92))



<a name="3.12.0"></a>
# [3.12.0](https://github.com/electron-userland/electron-builder/compare/v3.11.0...v3.12.0) (2016-04-27)


### Bug Fixes

* Windows shortcut doesn't work when `productName` contains a space ([f99d61e](https://github.com/electron-userland/electron-builder/commit/f99d61e)), closes [#339](https://github.com/electron-userland/electron-builder/issues/339)


### Features

* check application package ([27faf73](https://github.com/electron-userland/electron-builder/commit/27faf73)), closes [#303](https://github.com/electron-userland/electron-builder/issues/303)



<a name="3.11.0"></a>
# [3.11.0](https://github.com/electron-userland/electron-builder/compare/v3.10.0...v3.11.0) (2016-04-25)


### Features

* mac app store ([260ca0b](https://github.com/electron-userland/electron-builder/commit/260ca0b)), closes [#332](https://github.com/electron-userland/electron-builder/issues/332)



<a name="3.10.0"></a>
# [3.10.0](https://github.com/electron-userland/electron-builder/compare/v3.9.0...v3.10.0) (2016-04-23)


### Features

* import startssl certs by default ([0f19455](https://github.com/electron-userland/electron-builder/commit/0f19455))



<a name="3.9.0"></a>
# [3.9.0](https://github.com/electron-userland/electron-builder/compare/v3.8.0...v3.9.0) (2016-04-21)


### Features

* build.osx.target to specify dmg, zip or both ([23df6a1](https://github.com/electron-userland/electron-builder/commit/23df6a1)), closes [#322](https://github.com/electron-userland/electron-builder/issues/322)



<a name="3.8.0"></a>
# [3.8.0](https://github.com/electron-userland/electron-builder/compare/v3.7.0...v3.8.0) (2016-04-20)


### Features

* accept multiple default app dirs ([ea5f842](https://github.com/electron-userland/electron-builder/commit/ea5f842)), closes [#344](https://github.com/electron-userland/electron-builder/issues/344)



<a name="3.7.0"></a>
# [3.7.0](https://github.com/electron-userland/electron-builder/compare/v3.6.3...v3.7.0) (2016-04-20)


### Features

* Windows code signing from OS X ([9134f61](https://github.com/electron-userland/electron-builder/commit/9134f61)), closes [#314](https://github.com/electron-userland/electron-builder/issues/314)



<a name="3.6.3"></a>
## [3.6.3](https://github.com/electron-userland/electron-builder/compare/v3.6.2...v3.6.3) (2016-04-19)


### Bug Fixes

* Looks for linux homepage in the development package.json not in the application package.json ([3da6893](https://github.com/electron-userland/electron-builder/commit/3da6893)), closes [#334](https://github.com/electron-userland/electron-builder/issues/334)



<a name="3.6.2"></a>
## [3.6.2](https://github.com/electron-userland/electron-builder/compare/v3.6.1...v3.6.2) (2016-04-19)


### Bug Fixes

* get rid of nuget to pack win ([c987439](https://github.com/electron-userland/electron-builder/commit/c987439))



<a name="3.6.1"></a>
## [3.6.1](https://github.com/electron-userland/electron-builder/compare/v3.6.0...v3.6.1) (2016-04-17)


### Bug Fixes

* deb package description according to spec ([3c6ec3f](https://github.com/electron-userland/electron-builder/commit/3c6ec3f)), closes [#327](https://github.com/electron-userland/electron-builder/issues/327)



<a name="3.6.0"></a>
# [3.6.0](https://github.com/electron-userland/electron-builder/compare/v3.5.2...v3.6.0) (2016-04-16)


### Bug Fixes

* check that noMsi specified as bool ([8266b22](https://github.com/electron-userland/electron-builder/commit/8266b22)), closes [#316](https://github.com/electron-userland/electron-builder/issues/316)


### Features

* Allow to specify custom build-version for electron-packager ([c866084](https://github.com/electron-userland/electron-builder/commit/c866084)), closes [#323](https://github.com/electron-userland/electron-builder/issues/323)



<a name="3.5.2"></a>
## [3.5.2](https://github.com/electron-userland/electron-builder/compare/v3.5.1...v3.5.2) (2016-04-15)


### Bug Fixes

* check that electron-packager create out directory ([e015b61](https://github.com/electron-userland/electron-builder/commit/e015b61)), closes [#301](https://github.com/electron-userland/electron-builder/issues/301)



<a name="3.5.1"></a>
## [3.5.1](https://github.com/electron-userland/electron-builder/compare/v3.5.0...v3.5.1) (2016-04-14)


### Bug Fixes

* Error while creating delta nupkg for Windows: System.DllNotFoundException: msdelta.dl #294 ([574add7](https://github.com/electron-userland/electron-builder/commit/574add7)), closes [#294](https://github.com/electron-userland/electron-builder/issues/294)



<a name="3.5.0"></a>
# [3.5.0](https://github.com/electron-userland/electron-builder/compare/v3.4.0...v3.5.0) (2016-04-10)


### Features

* if build/install-spinner.gif exists, set loadingGif to it ([85a6fba](https://github.com/electron-userland/electron-builder/commit/85a6fba)), closes [#292](https://github.com/electron-userland/electron-builder/issues/292)



<a name="3.4.0"></a>
# [3.4.0](https://github.com/electron-userland/electron-builder/compare/v3.3.1...v3.4.0) (2016-04-09)


### Features

* Ability to customize the output directory ([78bddc7](https://github.com/electron-userland/electron-builder/commit/78bddc7)), closes [#272](https://github.com/electron-userland/electron-builder/issues/272)



<a name="3.3.1"></a>
## [3.3.1](https://github.com/electron-userland/electron-builder/compare/v3.3.0...v3.3.1) (2016-04-08)


### Bug Fixes

* vendor/osx/7za seems to be broken ([422a032](https://github.com/electron-userland/electron-builder/commit/422a032)), closes [#296](https://github.com/electron-userland/electron-builder/issues/296)



<a name="3.3.0"></a>
# [3.3.0](https://github.com/electron-userland/electron-builder/compare/v3.2.0...v3.3.0) (2016-04-05)


### Features

* use 7za to produce Squirrel.mac zip (smaller size — the same time to compress) ([2dd5d7c](https://github.com/electron-userland/electron-builder/commit/2dd5d7c))



<a name="3.2.0"></a>
# [3.2.0](https://github.com/electron-userland/electron-builder/compare/v3.1.2...v3.2.0) (2016-04-02)


### Features

* Linux deb — specify license, package url #242 ([c62683a](https://github.com/electron-userland/electron-builder/commit/c62683a))



<a name="3.1.2"></a>
## [3.1.2](https://github.com/electron-userland/electron-builder/compare/v3.1.1...v3.1.2) (2016-04-01)


### Bug Fixes

* Windows installer metadata is incorrect #278 ([b151ffc](https://github.com/electron-userland/electron-builder/commit/b151ffc)), closes [#278](https://github.com/electron-userland/electron-builder/issues/278)
* check windows icon to avoid unclear error messages in the 3rd-part tools ([6ad853d](https://github.com/electron-userland/electron-builder/commit/6ad853d)), closes [#243](https://github.com/electron-userland/electron-builder/issues/243)



<a name="3.1.0"></a>
# [3.1.0](https://github.com/electron-userland/electron-builder/compare/v3.0.2...v3.1.0) (2016-03-25)


### Features

* prefix dist: as marker to package in a distributable format ([fa7cc85](https://github.com/electron-userland/electron-builder/commit/fa7cc85)), closes [#267](https://github.com/electron-userland/electron-builder/issues/267)



<a name="3.0.2"></a>
## [3.0.2](https://github.com/electron-userland/electron-builder/compare/v3.0.1...v3.0.2) (2016-03-25)


### Bug Fixes

* Error publishing to github when building on travis #261 ([92f7a38](https://github.com/electron-userland/electron-builder/commit/92f7a38)), closes [#261](https://github.com/electron-userland/electron-builder/issues/261)



<a name="3.0.1"></a>
## [3.0.1](https://github.com/electron-userland/electron-builder/compare/v3.0.0...v3.0.1) (2016-03-24)


### Bug Fixes

* copy extra resources to NuGet package ([65d8126](https://github.com/electron-userland/electron-builder/commit/65d8126)), closes [#230](https://github.com/electron-userland/electron-builder/issues/230)



<a name="3.0.0"></a>
# [3.0.0](https://github.com/electron-userland/electron-builder/compare/v2.11.0...v3.0.0) (2016-03-23)


### Bug Fixes

* Linux build fails at icon conversion #239 ([c778e2b](https://github.com/electron-userland/electron-builder/commit/c778e2b)), closes [#239](https://github.com/electron-userland/electron-builder/issues/239)
* Problems downloading electron #180 ([0265db9](https://github.com/electron-userland/electron-builder/commit/0265db9)), closes [#180](https://github.com/electron-userland/electron-builder/issues/180)
* update winstaller to fix build windows on OS X ([c2bd66b](https://github.com/electron-userland/electron-builder/commit/c2bd66b))
* zip, dmg and exe filenames do not use productName as intended ([bfca0a7](https://github.com/electron-userland/electron-builder/commit/bfca0a7))


### Code Refactoring

* remove deprecated API (<2.8) ([eadd09b](https://github.com/electron-userland/electron-builder/commit/eadd09b))


### Features

* copy extra resources to packaged app ([cbe3ff8](https://github.com/electron-userland/electron-builder/commit/cbe3ff8))
* linux icons from custom dir, generate missing from ICNS ([7ac4b84](https://github.com/electron-userland/electron-builder/commit/7ac4b84))
* remove support of `build` in the application package.json ([46dbfe1](https://github.com/electron-userland/electron-builder/commit/46dbfe1)), closes [#251](https://github.com/electron-userland/electron-builder/issues/251)


### BREAKING CHANGES

* `build` is allowed since 3.0 only in the development package.json
* Deprecated <2.8 API has been removed



<a name="2.9.5"></a>
## [2.9.5](https://github.com/electron-userland/electron-builder/compare/v2.9.4...v2.9.5) (2016-03-13)


### Bug Fixes

* Windows nupkg downloaded twice each time / also keeps downloading latest release #234 ([3c90af6](https://github.com/electron-userland/electron-builder/commit/3c90af6)), closes [#234](https://github.com/electron-userland/electron-builder/issues/234)



<a name="2.9.4"></a>
## [2.9.4](https://github.com/electron-userland/electron-builder/compare/v2.9.3...v2.9.4) (2016-03-13)


### Bug Fixes

* Github publishing not working on Linux #229 ([841f397](https://github.com/electron-userland/electron-builder/commit/841f397))
* delete release again if failed with "405 Not Allowed" (3 times) ([ebf783c](https://github.com/electron-userland/electron-builder/commit/ebf783c))
* ignore newline when parsing common name in .p12 certificates ([dee8303](https://github.com/electron-userland/electron-builder/commit/dee8303))
* npm install doesn't rebuild native dependencies if arch changed — rebuild must be used ([5bcc95a](https://github.com/electron-userland/electron-builder/commit/5bcc95a))
* reupload again if failed with "502 Bad Gateway" (3 times) ([f131e33](https://github.com/electron-userland/electron-builder/commit/f131e33))



<a name="2.9.0"></a>
# [2.9.0](https://github.com/electron-userland/electron-builder/compare/v2.8.6...v2.9.0) (2016-03-09)


### Bug Fixes

* **windows:** Releases file for Windows not uploaded to Github ([9f4fba9](https://github.com/electron-userland/electron-builder/commit/9f4fba9)), closes [#190](https://github.com/electron-userland/electron-builder/issues/190)
* **windows:** do not rename artifacts twice ([9c87ffd](https://github.com/electron-userland/electron-builder/commit/9c87ffd))
* Getting "no such file or directory, rename ..." #208 ([1b6012e](https://github.com/electron-userland/electron-builder/commit/1b6012e)), closes [#208](https://github.com/electron-userland/electron-builder/issues/208)


### Features

* Allow custom .p12 certificates ([6918916](https://github.com/electron-userland/electron-builder/commit/6918916)), closes [#216](https://github.com/electron-userland/electron-builder/issues/216)
* use productName from app/package.json if present #204 ([5d376e1](https://github.com/electron-userland/electron-builder/commit/5d376e1)), closes [#204](https://github.com/electron-userland/electron-builder/issues/204) [#223](https://github.com/electron-userland/electron-builder/issues/223)



<a name="2.8.4"></a>
## [2.8.4](https://github.com/electron-userland/electron-builder/compare/v2.8.3...v2.8.4) (2016-03-03)


### Bug Fixes

* Configure build resources directory #184 ([5df87d3](https://github.com/electron-userland/electron-builder/commit/5df87d3)), closes [#184](https://github.com/electron-userland/electron-builder/issues/184) [#196](https://github.com/electron-userland/electron-builder/issues/196)



<a name="2.8.3"></a>
## [2.8.3](https://github.com/electron-userland/electron-builder/compare/v2.8.2...v2.8.3) (2016-02-25)


### Bug Fixes

* **nsis:** error on win when APP_OUT_FILE has spaces ([f4e1b41](https://github.com/electron-userland/electron-builder/commit/f4e1b41))



<a name="2.8.2"></a>
## [2.8.2](https://github.com/electron-userland/electron-builder/compare/v2.8.1...v2.8.2) (2016-02-23)


### Bug Fixes

* remove unused dependency lodash.camelcase ([c7be41b](https://github.com/electron-userland/electron-builder/commit/c7be41b))



<a name="2.8.1"></a>
## [2.8.1](https://github.com/electron-userland/electron-builder/compare/v2.8.0...v2.8.1) (2016-02-23)


### Bug Fixes

* move read-package-json to production dependencies ([ac10716](https://github.com/electron-userland/electron-builder/commit/ac10716))



<a name="2.8.0"></a>
# [2.8.0](https://github.com/electron-userland/electron-builder/compare/v2.7.2...v2.8.0) (2016-02-23)


### Features

* use read-package-json as a correct fix of Linux maintainer .deb package field ([3fba451](https://github.com/electron-userland/electron-builder/commit/3fba451))

