# Changelog

### [2.18.4](https://www.github.com/datavzrd/datavzrd/compare/v2.18.3...v2.18.4) (2023-04-17)


### Bug Fixes

* Fix custom formatter ([#409](https://www.github.com/datavzrd/datavzrd/issues/409)) ([ea53bf2](https://www.github.com/datavzrd/datavzrd/commit/ea53bf26873d6cea6b36121979056cd0db579628))

### [2.18.3](https://www.github.com/datavzrd/datavzrd/compare/v2.18.2...v2.18.3) (2023-03-30)


### Bug Fixes

* Fix table plot for wide tables ([#404](https://www.github.com/datavzrd/datavzrd/issues/404)) ([c8a92ce](https://www.github.com/datavzrd/datavzrd/commit/c8a92ce8bad029bc4abb6834c45a3a97d6145055))
* Pre-calculate numeric heatmap domain ([#402](https://www.github.com/datavzrd/datavzrd/issues/402)) ([b91129a](https://www.github.com/datavzrd/datavzrd/commit/b91129a169b204ad9eb64c4bf998f93583c45ee7))

### [2.18.2](https://www.github.com/datavzrd/datavzrd/compare/v2.18.1...v2.18.2) (2023-03-30)


### Bug Fixes

* Fix domain detection with NA values ([#400](https://www.github.com/datavzrd/datavzrd/issues/400)) ([915c8c8](https://www.github.com/datavzrd/datavzrd/commit/915c8c837e4b3987e5a15ad252917808c74bec18))

### [2.18.1](https://www.github.com/datavzrd/datavzrd/compare/v2.18.0...v2.18.1) (2023-03-22)


### Miscellaneous Chores

* release 2.18.1 ([37ec953](https://www.github.com/datavzrd/datavzrd/commit/37ec9535a006706fe24cc67872f6dd786a75c649))

## [2.18.0](https://www.github.com/datavzrd/datavzrd/compare/v2.17.1...v2.18.0) (2023-03-01)


### Features

* Remove print option in favour of vega plot view ([#366](https://www.github.com/datavzrd/datavzrd/issues/366)) ([f2bd9a0](https://www.github.com/datavzrd/datavzrd/commit/f2bd9a008c08801153773e05467015d3ba01b78e))


### Bug Fixes

* Fix new-window keyword ([#369](https://www.github.com/datavzrd/datavzrd/issues/369)) ([efd2290](https://www.github.com/datavzrd/datavzrd/commit/efd22905ddc536987705ffa248c11b52c6acf1c7))
* Generate default column spec automatically for columns that are not specified via the config ([#364](https://www.github.com/datavzrd/datavzrd/issues/364)) ([b849743](https://www.github.com/datavzrd/datavzrd/commit/b849743d7c1a0e3219518ed6a0d8efe9a07f94f6))

### [2.17.1](https://www.github.com/datavzrd/datavzrd/compare/v2.17.0...v2.17.1) (2023-02-14)


### Bug Fixes

* Fix non-working filter if brush is dragged outside of plot ([#359](https://www.github.com/datavzrd/datavzrd/issues/359)) ([54138ed](https://www.github.com/datavzrd/datavzrd/commit/54138ed311758146efb9e7f376122840eab6218c))

## [2.17.0](https://www.github.com/datavzrd/datavzrd/compare/v2.16.2...v2.17.0) (2023-02-13)


### Features

* Add debug mode ([#354](https://www.github.com/datavzrd/datavzrd/issues/354)) ([d386da2](https://www.github.com/datavzrd/datavzrd/commit/d386da2abca5507165f15bd4eb9c950ce6618c86))


### Bug Fixes

* Fix rendering of header rows after page change ([#358](https://www.github.com/datavzrd/datavzrd/issues/358)) ([ecbe148](https://www.github.com/datavzrd/datavzrd/commit/ecbe14891164e0a1ec10d22488e7de03e34b9d30))

### [2.16.2](https://www.github.com/datavzrd/datavzrd/compare/v2.16.1...v2.16.2) (2023-02-08)


### Bug Fixes

* Fix custom plots on multi page views ([#351](https://www.github.com/datavzrd/datavzrd/issues/351)) ([1618cf5](https://www.github.com/datavzrd/datavzrd/commit/1618cf5840fd66e5657f50cd37370c7072231183))

### [2.16.1](https://www.github.com/datavzrd/datavzrd/compare/v2.16.0...v2.16.1) (2023-02-08)


### Bug Fixes

* Accept double quotes on regexes ([#346](https://www.github.com/datavzrd/datavzrd/issues/346)) ([1c32c10](https://www.github.com/datavzrd/datavzrd/commit/1c32c101fff44649b7526787be8528cea6dfb24c))
* Fix js for multiple header ellipsis usage ([#342](https://www.github.com/datavzrd/datavzrd/issues/342)) ([70aa282](https://www.github.com/datavzrd/datavzrd/commit/70aa282a7b08a884dc9865b84a7fd662886442c6))
* Improve context when calculating links between datasets ([#349](https://www.github.com/datavzrd/datavzrd/issues/349)) ([e29cff1](https://www.github.com/datavzrd/datavzrd/commit/e29cff11f1bee171629891bd1c849fc640a6316e))
* Show ellipsis as tooltip ([#350](https://www.github.com/datavzrd/datavzrd/issues/350)) ([a77509a](https://www.github.com/datavzrd/datavzrd/commit/a77509ac22c9d01ba40d42275013f206ef9b5b3e))

## [2.16.0](https://www.github.com/datavzrd/datavzrd/compare/v2.15.0...v2.16.0) (2023-02-06)


### Features

* Add --overwrite-output option ([#336](https://www.github.com/datavzrd/datavzrd/issues/336)) ([a24f648](https://www.github.com/datavzrd/datavzrd/commit/a24f64866f7252278c9ba36121c7bc20cb1f2d9d))


### Bug Fixes

* Turn off webview controls by default ([#335](https://www.github.com/datavzrd/datavzrd/issues/335)) ([55245ff](https://www.github.com/datavzrd/datavzrd/commit/55245ff2c07da743d6ba41134eae3aba67e32384))

## [2.15.0](https://www.github.com/datavzrd/datavzrd/compare/v2.14.1...v2.15.0) (2023-02-02)


### Features

* Add row sharing option ([#323](https://www.github.com/datavzrd/datavzrd/issues/323)) ([3dad613](https://www.github.com/datavzrd/datavzrd/commit/3dad6137e5ad1d6a6541e6b0ce0a0307aa46a13d))


### Performance Improvements

* Remove html search pages for views that don't use them ([#324](https://www.github.com/datavzrd/datavzrd/issues/324)) ([965eec0](https://www.github.com/datavzrd/datavzrd/commit/965eec091610f660ec26503c89414f7e38fc194f))

### [2.14.1](https://www.github.com/datavzrd/datavzrd/compare/v2.14.0...v2.14.1) (2023-01-23)


### Bug Fixes

* Round domains according to precision ([#319](https://www.github.com/datavzrd/datavzrd/issues/319)) ([a67c687](https://www.github.com/datavzrd/datavzrd/commit/a67c687b60744b43ec8e9c5c304d985ed3402c43))


### Performance Improvements

* Compress data for plot views with lz-string ([#312](https://www.github.com/datavzrd/datavzrd/issues/312)) ([f45f1fc](https://www.github.com/datavzrd/datavzrd/commit/f45f1fcba7add4f812b7ab1c513624046187ecb7))

## [2.14.0](https://www.github.com/datavzrd/datavzrd/compare/v2.13.0...v2.14.0) (2023-01-16)


### Features

* Add ellipsis option for header definitions ([#310](https://www.github.com/datavzrd/datavzrd/issues/310)) ([e9c82ed](https://www.github.com/datavzrd/datavzrd/commit/e9c82edddb188e3de218d6d01d7db273204309de))

## [2.13.0](https://www.github.com/datavzrd/datavzrd/compare/v2.12.0...v2.13.0) (2023-01-11)


### Features

* Add label keyword to column spec ([#305](https://www.github.com/datavzrd/datavzrd/issues/305)) ([b940656](https://www.github.com/datavzrd/datavzrd/commit/b94065600bb8ae3db3cefd5505720935c095d5de))


### Bug Fixes

* allow to access row in data function of custom plot ([#308](https://www.github.com/datavzrd/datavzrd/issues/308)) ([ad78d32](https://www.github.com/datavzrd/datavzrd/commit/ad78d3273694507229d66ce6f58f6a745952d943))
* Fix headers for views without detail mode and no header labels ([#309](https://www.github.com/datavzrd/datavzrd/issues/309)) ([e731876](https://www.github.com/datavzrd/datavzrd/commit/e731876e4ac5ae5df64c4850dc3406c85593d9af))
* Remove validation error when values exceed given domain and clamp is set to true ([#304](https://www.github.com/datavzrd/datavzrd/issues/304)) ([3c5e9fd](https://www.github.com/datavzrd/datavzrd/commit/3c5e9fd8527cfe842cc8be6410f20f44fd18aa4e))

## [2.12.0](https://www.github.com/datavzrd/datavzrd/compare/v2.11.1...v2.12.0) (2023-01-09)


### Features

* Add log scale value validation for plots ([#299](https://www.github.com/datavzrd/datavzrd/issues/299)) ([258c506](https://www.github.com/datavzrd/datavzrd/commit/258c506f7e0253424be9332bb71cc74479fc3dde))


### Bug Fixes

* Fix column classification for tables with additional header rows ([#298](https://www.github.com/datavzrd/datavzrd/issues/298)) ([756fdd0](https://www.github.com/datavzrd/datavzrd/commit/756fdd044b5180a885683280c13d77d7755d1286))
* Fix precision keyword for bar and tick plots ([#301](https://www.github.com/datavzrd/datavzrd/issues/301)) ([bb1e763](https://www.github.com/datavzrd/datavzrd/commit/bb1e7634542f8f70159453b6a773ec07902af97e))

### [2.11.1](https://www.github.com/datavzrd/datavzrd/compare/v2.11.0...v2.11.1) (2022-12-20)


### Bug Fixes

* Add missing clamp parameter to heatmap plot ([#294](https://www.github.com/datavzrd/datavzrd/issues/294)) ([c6b0ee3](https://www.github.com/datavzrd/datavzrd/commit/c6b0ee34fce555ba980a225c45bdc4f00478a5f9))
* Fix wrong data values for tick and bar plots ([#290](https://www.github.com/datavzrd/datavzrd/issues/290)) ([3d5086a](https://www.github.com/datavzrd/datavzrd/commit/3d5086aa9ccef1e6b5eeb4177edaa051660d46c7))

## [2.11.0](https://www.github.com/datavzrd/datavzrd/compare/v2.10.1...v2.11.0) (2022-12-07)


### Features

* Optimize NA value recognition ([#280](https://www.github.com/datavzrd/datavzrd/issues/280)) ([69ce037](https://www.github.com/datavzrd/datavzrd/commit/69ce037190074ae639af5f47ccb212f774d84151))

### [2.10.1](https://www.github.com/datavzrd/datavzrd/compare/v2.10.0...v2.10.1) (2022-12-01)


### Bug Fixes

* Don't show empty values an NaN for numeric columns ([#278](https://www.github.com/datavzrd/datavzrd/issues/278)) ([4806d0c](https://www.github.com/datavzrd/datavzrd/commit/4806d0cc415a2cefb7b3ce334712f0a9d5e73bf1))

## [2.10.0](https://www.github.com/datavzrd/datavzrd/compare/v2.9.0...v2.10.0) (2022-11-30)


### Features

* Make excel export option configurable per dataset ([#276](https://www.github.com/datavzrd/datavzrd/issues/276)) ([c73a6b4](https://www.github.com/datavzrd/datavzrd/commit/c73a6b4beb2d36e5ff94679fe082bd26378847f6))

## [2.9.0](https://www.github.com/datavzrd/datavzrd/compare/v2.8.1...v2.9.0) (2022-11-17)


### Features

* Allow specifying a path to a custom js function ([#267](https://www.github.com/datavzrd/datavzrd/issues/267)) ([1eb1453](https://www.github.com/datavzrd/datavzrd/commit/1eb145338b551285926ff8449ebd90664688f2d3))


### Bug Fixes

* Fix error when rendering empty multi header files ([#268](https://www.github.com/datavzrd/datavzrd/issues/268)) ([9c2b464](https://www.github.com/datavzrd/datavzrd/commit/9c2b4649cc6ab170a048d7a7154625b28f5be309))

### [2.8.1](https://www.github.com/koesterlab/datavzrd/compare/v2.8.0...v2.8.1) (2022-11-11)


### Bug Fixes

* Fix row height ([#264](https://www.github.com/koesterlab/datavzrd/issues/264)) ([0af7952](https://www.github.com/koesterlab/datavzrd/commit/0af7952d92bf5c027378cfa3e46b223c8c31ebae))

## [2.8.0](https://www.github.com/koesterlab/datavzrd/compare/v2.7.2...v2.8.0) (2022-11-11)


### Features

* Add basic excel export option ([#258](https://www.github.com/koesterlab/datavzrd/issues/258)) ([b684381](https://www.github.com/koesterlab/datavzrd/commit/b684381ad64286ce54e93f354a02001b9d0fe7dc))
* Panic if log scale includes zero ([#262](https://www.github.com/koesterlab/datavzrd/issues/262)) ([eb35932](https://www.github.com/koesterlab/datavzrd/commit/eb359325fc2dde93f437f09f9cb1749174595301))
* Validate domains of plots ([#260](https://www.github.com/koesterlab/datavzrd/issues/260)) ([fb3d87a](https://www.github.com/koesterlab/datavzrd/commit/fb3d87af17a71ba263a2f0fe04a3191f28a9065b))

### [2.7.2](https://www.github.com/koesterlab/datavzrd/compare/v2.7.1...v2.7.2) (2022-11-04)


### Bug Fixes

* Fix overlapping fonts by removing line breaks ([#249](https://www.github.com/koesterlab/datavzrd/issues/249)) ([077afdd](https://www.github.com/koesterlab/datavzrd/commit/077afdd654bb88d77c7363ff893d2ab784510ad9))

### [2.7.1](https://www.github.com/koesterlab/datavzrd/compare/v2.7.0...v2.7.1) (2022-11-02)


### Bug Fixes

* more lighweight UI

## [2.7.0](https://www.github.com/koesterlab/datavzrd/compare/v2.6.1...v2.7.0) (2022-10-28)


### Features

* Add config keyword plot-view-legend ([#241](https://www.github.com/koesterlab/datavzrd/issues/241)) ([0f74b72](https://www.github.com/koesterlab/datavzrd/commit/0f74b7261a5ccef447f472a4b4fc2b46d5d002d5))
* Add new keyword bars ([#242](https://www.github.com/koesterlab/datavzrd/issues/242)) ([fc1add6](https://www.github.com/koesterlab/datavzrd/commit/fc1add6aa4bcdd58fd95ff9d38b081f915751248))

### [2.6.1](https://www.github.com/koesterlab/datavzrd/compare/v2.6.0...v2.6.1) (2022-10-25)


### Bug Fixes

* Add context to error when parsing numeric domain ([#238](https://www.github.com/koesterlab/datavzrd/issues/238)) ([3e166cd](https://www.github.com/koesterlab/datavzrd/commit/3e166cd0eb7d71df02f788e2813b65453389049b))
* Fix wrong classification of empty columns ([#239](https://www.github.com/koesterlab/datavzrd/issues/239)) ([c02335d](https://www.github.com/koesterlab/datavzrd/commit/c02335d4fce596b37de867716548a99b4ea33777))

## [2.6.0](https://www.github.com/koesterlab/datavzrd/compare/v2.5.2...v2.6.0) (2022-10-24)


### Features

* Merge legends when domains are equal ([#227](https://www.github.com/koesterlab/datavzrd/issues/227)) ([aa220cb](https://www.github.com/koesterlab/datavzrd/commit/aa220cb786e071b400220d4f67ce3f8cb7e3e241))


### Bug Fixes

* Fix precision behaviour for zero and negative values ([#234](https://www.github.com/koesterlab/datavzrd/issues/234)) ([6b13cda](https://www.github.com/koesterlab/datavzrd/commit/6b13cdac83c005a6b255339b43b3b38a90bd41af))

### [2.5.2](https://www.github.com/koesterlab/datavzrd/compare/v2.5.1...v2.5.2) (2022-10-20)


### Bug Fixes

* Fix precision for non-scientific notation ([#225](https://www.github.com/koesterlab/datavzrd/issues/225)) ([9105d77](https://www.github.com/koesterlab/datavzrd/commit/9105d7748f783ff06848b87b494e3ba504cab184))

### [2.5.1](https://www.github.com/koesterlab/datavzrd/compare/v2.5.0...v2.5.1) (2022-10-13)


### Bug Fixes

* Reformat button help text ([66384bf](https://www.github.com/koesterlab/datavzrd/commit/66384bfbc452990bb62341f36f3a9c49ef32cb67))

## [2.5.0](https://www.github.com/koesterlab/datavzrd/compare/v2.4.0...v2.5.0) (2022-10-13)


### Features

* Add ability to export whole table to vega-lite heatmap ([#218](https://www.github.com/koesterlab/datavzrd/issues/218)) ([44a9644](https://www.github.com/koesterlab/datavzrd/commit/44a9644e264f8f5ba5b4d5f6e15a49605abc481f))


### Bug Fixes

* Align text marks of heatmap table ([#220](https://www.github.com/koesterlab/datavzrd/issues/220)) ([9c7333e](https://www.github.com/koesterlab/datavzrd/commit/9c7333e9a6b2b16250fd7f5bc9eca02f1ed2592c))


### Performance Improvements

* Remove unused data field from heatmap spec ([#221](https://www.github.com/koesterlab/datavzrd/issues/221)) ([74e9b4e](https://www.github.com/koesterlab/datavzrd/commit/74e9b4eb6fe873ab79bae6d48f091bcb514b9e91))

## [2.4.0](https://www.github.com/koesterlab/datavzrd/compare/v2.3.2...v2.4.0) (2022-10-11)


### Features

* Add minify_js to decrease file sizes ([#210](https://www.github.com/koesterlab/datavzrd/issues/210)) ([7515317](https://www.github.com/koesterlab/datavzrd/commit/7515317e6bcf56df2142b45dce72fe91f0c7341d))
* Add new heatmap option clamp ([#216](https://www.github.com/koesterlab/datavzrd/issues/216)) ([7e07df1](https://www.github.com/koesterlab/datavzrd/commit/7e07df111fbe7c17e028212437067e81e46464b9))

### [2.3.2](https://www.github.com/koesterlab/datavzrd/compare/v2.3.1...v2.3.2) (2022-10-10)


### Bug Fixes

* Fix brush filter domain for numeric heatmap plots ([#214](https://www.github.com/koesterlab/datavzrd/issues/214)) ([2de96a8](https://www.github.com/koesterlab/datavzrd/commit/2de96a85970588c03431e3363a4b9dd8a8ccd993))

### [2.3.1](https://www.github.com/koesterlab/datavzrd/compare/v2.3.0...v2.3.1) (2022-10-04)


### Bug Fixes

* Deny unknown fields for configs ([#208](https://www.github.com/koesterlab/datavzrd/issues/208)) ([7ca295f](https://www.github.com/koesterlab/datavzrd/commit/7ca295f3f5da131b04ec53fe916da13e29319fd4))
* Fix entering of unreachable code when data contains empty columns ([#212](https://www.github.com/koesterlab/datavzrd/issues/212)) ([c1df3fa](https://www.github.com/koesterlab/datavzrd/commit/c1df3fa1c0d621720399df2d51e962528eff29df))

## [2.3.0](https://www.github.com/koesterlab/datavzrd/compare/v2.2.0...v2.3.0) (2022-09-28)


### Features

* Align text markers of tick plots ([#203](https://www.github.com/koesterlab/datavzrd/issues/203)) ([ca3113d](https://www.github.com/koesterlab/datavzrd/commit/ca3113dd924409dd012f3eca382f4a06ef7696ac))


### Bug Fixes

* Fix column classification for NA values ([#206](https://www.github.com/koesterlab/datavzrd/issues/206)) ([f1df6db](https://www.github.com/koesterlab/datavzrd/commit/f1df6db89c50e84c86983848a3274cb2f5c21fc3))
* Fix navbar for tables wider than viewport ([#207](https://www.github.com/koesterlab/datavzrd/issues/207)) ([a5cca79](https://www.github.com/koesterlab/datavzrd/commit/a5cca793bed28d2c2e5046454f1765afb8246f9f))

## [2.2.0](https://www.github.com/koesterlab/datavzrd/compare/v2.1.0...v2.2.0) (2022-09-14)


### Features

* Add optional labeling for headers ([#183](https://www.github.com/koesterlab/datavzrd/issues/183)) ([731732a](https://www.github.com/koesterlab/datavzrd/commit/731732a1e578181f2949ab2faf0ec57b2700c692))

## [2.1.0](https://www.github.com/koesterlab/datavzrd/compare/v2.0.0...v2.1.0) (2022-09-09)


### Features

* Add precision keyword for displaying numeric values ([#179](https://www.github.com/koesterlab/datavzrd/issues/179)) ([a899ff2](https://www.github.com/koesterlab/datavzrd/commit/a899ff212d17e5b21d41cd29bdba729ee4eb77ca))

## [2.0.0](https://www.github.com/koesterlab/datavzrd/compare/v1.19.0...v2.0.0) (2022-09-02)


### ⚠ BREAKING CHANGES

* Add heatmap option for additional headers (#174)
* Rename header-rows setting into headers (#176)

### Features

* Add heatmap option for additional headers ([#174](https://www.github.com/koesterlab/datavzrd/issues/174)) ([6f91cd8](https://www.github.com/koesterlab/datavzrd/commit/6f91cd8e8b899228d170dfffb5af3567acc76acc))

## [1.19.0](https://www.github.com/koesterlab/datavzrd/compare/v1.18.1...v1.19.0) (2022-08-24)


### Features

* Add PDF generation for current view ([#171](https://www.github.com/koesterlab/datavzrd/issues/171)) ([4f2a4c4](https://www.github.com/koesterlab/datavzrd/commit/4f2a4c45a48824b39aacdf462d351ab6107009b4))
* Allow rendering custom content into any heatmap cell ([#172](https://www.github.com/koesterlab/datavzrd/issues/172)) ([8c5ba92](https://www.github.com/koesterlab/datavzrd/commit/8c5ba92453f8fc29a71921fc0b1386e9d017e0d7))

### [1.18.1](https://www.github.com/koesterlab/datavzrd/compare/v1.18.0...v1.18.1) (2022-08-16)


### Bug Fixes

* Show empty values in separate category in histograms ([#166](https://www.github.com/koesterlab/datavzrd/issues/166)) ([6780625](https://www.github.com/koesterlab/datavzrd/commit/67806254f0c47bba556feac79e5f1a25e70f58ea))

## [1.18.0](https://www.github.com/koesterlab/datavzrd/compare/v1.17.1...v1.18.0) (2022-08-15)


### Features

* Add new render-html keyword and allow integration of aux-libraries ([#163](https://www.github.com/koesterlab/datavzrd/issues/163)) ([9e8dc4e](https://www.github.com/koesterlab/datavzrd/commit/9e8dc4ec808e639750bd1d043c680c47163eabeb))


### Bug Fixes

* Fix test case for html config deserialization ([7512fd4](https://www.github.com/koesterlab/datavzrd/commit/7512fd4f1e9334224c66832b9bd15b8b170fc400))
* Fix usage of page-size for single page views ([#162](https://www.github.com/koesterlab/datavzrd/issues/162)) ([648bcd3](https://www.github.com/koesterlab/datavzrd/commit/648bcd346d19ace7a8210fb6bea7e3512a102266))

### [1.17.1](https://www.github.com/koesterlab/datavzrd/compare/v1.17.0...v1.17.1) (2022-08-04)


### Bug Fixes

* Remove detail view when columns are hidden ([#158](https://www.github.com/koesterlab/datavzrd/issues/158)) ([ea06cae](https://www.github.com/koesterlab/datavzrd/commit/ea06caee1296b0b4b46b3c02d5fc0284afc5429b))

## [1.17.0](https://www.github.com/koesterlab/datavzrd/compare/v1.16.2...v1.17.0) (2022-06-27)


### Features

* Show tick plots and heatmaps in display-mode: detail ([#150](https://www.github.com/koesterlab/datavzrd/issues/150)) ([b7c1dd1](https://www.github.com/koesterlab/datavzrd/commit/b7c1dd140cbfeaa72d70853f3b80c8685b7a747b))
* Support multiple datasets for render-plot views ([#156](https://www.github.com/koesterlab/datavzrd/issues/156)) ([1e66ff5](https://www.github.com/koesterlab/datavzrd/commit/1e66ff5b6cb47a5fdfb5a39e22e17cc4cbd11454))


### Bug Fixes

* Fix custom plots in detail mode ([#154](https://www.github.com/koesterlab/datavzrd/issues/154)) ([776fc25](https://www.github.com/koesterlab/datavzrd/commit/776fc25e21c65d9ef9b3f356c9b6f6f365a2e48c))

### [1.16.2](https://www.github.com/koesterlab/datavzrd/compare/v1.16.1...v1.16.2) (2022-05-24)


### Bug Fixes

* Fix clear-filter button ([ab3e206](https://www.github.com/koesterlab/datavzrd/commit/ab3e206f749554ddaed586dc200859807080d712))
* Fix cut off dropdown linkouts ([5d785cd](https://www.github.com/koesterlab/datavzrd/commit/5d785cdeeb307aa94f0f632226661d9795399590))

### [1.16.1](https://www.github.com/koesterlab/datavzrd/compare/v1.16.0...v1.16.1) (2022-05-23)


### Bug Fixes

* Fix column highlighting for firefox ([#145](https://www.github.com/koesterlab/datavzrd/issues/145)) ([dfdfb58](https://www.github.com/koesterlab/datavzrd/commit/dfdfb589901c3935c3176e6880f3b368abeab6c2))

## [1.16.0](https://www.github.com/koesterlab/datavzrd/compare/v1.15.0...v1.16.0) (2022-05-23)


### Features

* Allow aux-domain-columns for non-numeric column heatmaps ([#141](https://www.github.com/koesterlab/datavzrd/issues/141)) ([a4f0c74](https://www.github.com/koesterlab/datavzrd/commit/a4f0c745aa5382cb63a8e8bfd72d64ea7cb32128))
* Always display empty heatmap values in white ([5863fe0](https://www.github.com/koesterlab/datavzrd/commit/5863fe0861e749ec648f3433b6fd687ef8cb1a34))
* Improve view navigation ([#135](https://www.github.com/koesterlab/datavzrd/issues/135)) ([2d54e8f](https://www.github.com/koesterlab/datavzrd/commit/2d54e8f618ec8f30ce711e2a44983c36a49ad829))

## [1.15.0](https://www.github.com/koesterlab/datavzrd/compare/v1.14.4...v1.15.0) (2022-05-19)


### Features

* Add new display-mode: hidden ([#140](https://www.github.com/koesterlab/datavzrd/issues/140)) ([67e895d](https://www.github.com/koesterlab/datavzrd/commit/67e895d36ee2fb3613dae0a31b34417c7f696a53))
* Improve brush-filters ([#134](https://www.github.com/koesterlab/datavzrd/issues/134)) ([b577fe1](https://www.github.com/koesterlab/datavzrd/commit/b577fe1c66a47c1c738ce4f2c295db05846ac4b2))
* Improve detail formatter ([#137](https://www.github.com/koesterlab/datavzrd/issues/137)) ([4a30886](https://www.github.com/koesterlab/datavzrd/commit/4a308866390c76decf1986fc62a404e94435dfb3))

### [1.14.4](https://www.github.com/koesterlab/datavzrd/compare/v1.14.3...v1.14.4) (2022-05-18)


### Bug Fixes

* Prevent panic in case of render-table definitions for non-existent columns ([#128](https://www.github.com/koesterlab/datavzrd/issues/128)) ([4f40d41](https://www.github.com/koesterlab/datavzrd/commit/4f40d413fb031d413efd5b9845baeed3db5aa6e1))

### [1.14.3](https://www.github.com/koesterlab/datavzrd/compare/v1.14.2...v1.14.3) (2022-05-18)


### Bug Fixes

* Modify table header height to new brush filters ([25a98f4](https://www.github.com/koesterlab/datavzrd/commit/25a98f47be036451e337ac79dd9c8981dce3b52b))

### [1.14.2](https://www.github.com/koesterlab/datavzrd/compare/v1.14.1...v1.14.2) (2022-05-16)


### Bug Fixes

* Include aux domains in filter brush domain ([#126](https://www.github.com/koesterlab/datavzrd/issues/126)) ([4157457](https://www.github.com/koesterlab/datavzrd/commit/4157457143a593a224761320c01058a76797d280))
* Include heatmap domains for filter brushes ([#124](https://www.github.com/koesterlab/datavzrd/issues/124)) ([2503b30](https://www.github.com/koesterlab/datavzrd/commit/2503b30855dbef6cf9244d3687bcd3f8b5c2e5e4))

### [1.14.1](https://www.github.com/koesterlab/datavzrd/compare/v1.14.0...v1.14.1) (2022-05-11)


### Bug Fixes

* Fix clear filter button ([91d3ab2](https://www.github.com/koesterlab/datavzrd/commit/91d3ab2607dbd4dab9fb1f02080b3fc355b6fcda))

## [1.14.0](https://www.github.com/koesterlab/datavzrd/compare/v1.13.3...v1.14.0) (2022-05-11)


### Features

* Add clear filter button ([4c1d977](https://www.github.com/koesterlab/datavzrd/commit/4c1d9772e38ee706d6f1f4dc3caac81cbf5fd2ca))


### Bug Fixes

* Align headers and filter brushes ([45ecb72](https://www.github.com/koesterlab/datavzrd/commit/45ecb722b7eb53303340286a45057020e61ac575))
* Use derive for default implementation of AuxDomainColumns ([#120](https://www.github.com/koesterlab/datavzrd/issues/120)) ([3c546e0](https://www.github.com/koesterlab/datavzrd/commit/3c546e0a54e932aacf8f323c84b6ae3848fd8730))
* Use integers for filter brushes if possible ([24fe4b5](https://www.github.com/koesterlab/datavzrd/commit/24fe4b529fc38ad4321c9c0b9436a819ec94ea1c))
* Use tick domain for filter brush if present ([#119](https://www.github.com/koesterlab/datavzrd/issues/119)) ([b4c743e](https://www.github.com/koesterlab/datavzrd/commit/b4c743e37115c6ece694b7b1e475b69ebb41a26c))

### [1.13.3](https://www.github.com/koesterlab/datavzrd/compare/v1.13.2...v1.13.3) (2022-05-11)


### Bug Fixes

* Limit maximum characters in axis labels for brush filters ([#117](https://www.github.com/koesterlab/datavzrd/issues/117)) ([504fc75](https://www.github.com/koesterlab/datavzrd/commit/504fc75ea992404f64ee286818dca6993684ca7b))

### [1.13.2](https://www.github.com/koesterlab/datavzrd/compare/v1.13.1...v1.13.2) (2022-05-10)


### Bug Fixes

* Fix brush filter for columns including whitespaces ([#115](https://www.github.com/koesterlab/datavzrd/issues/115)) ([3cb2d23](https://www.github.com/koesterlab/datavzrd/commit/3cb2d23bed58b3cff21b088ffb4b092bfcbd4f97))

### [1.13.1](https://www.github.com/koesterlab/datavzrd/compare/v1.13.0...v1.13.1) (2022-05-10)


### Bug Fixes

* Remove debug statement ([9e3790b](https://www.github.com/koesterlab/datavzrd/commit/9e3790ba9f509c71f6e752097b66919d8f47126f))
* Show error messages from config validation properly ([#113](https://www.github.com/koesterlab/datavzrd/issues/113)) ([11ca681](https://www.github.com/koesterlab/datavzrd/commit/11ca681d33621c76eafc675d933d6729e91a69d5))

## [1.13.0](https://www.github.com/koesterlab/datavzrd/compare/v1.12.0...v1.13.0) (2022-05-09)


### Features

* Allow usage of regexes for aux-domain-columns ([#111](https://www.github.com/koesterlab/datavzrd/issues/111)) ([dc54c85](https://www.github.com/koesterlab/datavzrd/commit/dc54c850fadd09f25295be504b83852b7e74b173))
* Validate given default-view ([#110](https://www.github.com/koesterlab/datavzrd/issues/110)) ([fc52714](https://www.github.com/koesterlab/datavzrd/commit/fc5271402d887b3b66635ccb8c0fe7d33fbb491c))

## [1.12.0](https://www.github.com/koesterlab/datavzrd/compare/v1.11.1...v1.12.0) (2022-05-09)


### Features

* New keyword aux-domain-columns ([#108](https://www.github.com/koesterlab/datavzrd/issues/108)) ([086f91b](https://www.github.com/koesterlab/datavzrd/commit/086f91b54b454c9899c7e113a23ba4fa1b6e5ef4))

### [1.11.1](https://www.github.com/koesterlab/datavzrd/compare/v1.11.0...v1.11.1) (2022-05-05)


### Bug Fixes

* Remove linkouts from table if non-existent ([#106](https://www.github.com/koesterlab/datavzrd/issues/106)) ([9430a78](https://www.github.com/koesterlab/datavzrd/commit/9430a786e7114bda0f997fca8ede42896dee0eaa))

## [1.11.0](https://www.github.com/koesterlab/datavzrd/compare/v1.10.3...v1.11.0) (2022-05-05)


### Features

* Add brush filter for numeric columns ([#103](https://www.github.com/koesterlab/datavzrd/issues/103)) ([6f97429](https://www.github.com/koesterlab/datavzrd/commit/6f9742961cc9123e5ee26ab32d85cee02055f24a))

### [1.10.3](https://www.github.com/koesterlab/datavzrd/compare/v1.10.2...v1.10.3) (2022-04-29)


### Bug Fixes

* Activate popovers after page change ([6319230](https://www.github.com/koesterlab/datavzrd/commit/6319230655b8462e897bb0226724868fbfa3cf6c))

### [1.10.2](https://www.github.com/koesterlab/datavzrd/compare/v1.10.1...v1.10.2) (2022-04-29)


### Bug Fixes

* Fix breaking interaction between formatting urls and filtering data ([02e3e5e](https://www.github.com/koesterlab/datavzrd/commit/02e3e5eb628c3e199a79ea5d2f64b12ef3f1fe1d))

### [1.10.1](https://www.github.com/koesterlab/datavzrd/compare/v1.10.0...v1.10.1) (2022-04-29)


### Bug Fixes

* Fix wrong url linking arguments for single page views ([4f14492](https://www.github.com/koesterlab/datavzrd/commit/4f144926c780ca417e875f55fc6bf0ad89b5446b))

## [1.10.0](https://www.github.com/koesterlab/datavzrd/compare/v1.9.0...v1.10.0) (2022-04-29)


### Features

* Allow missing values in other tables with keyword optional ([#98](https://www.github.com/koesterlab/datavzrd/issues/98)) ([b0c7920](https://www.github.com/koesterlab/datavzrd/commit/b0c79200dff3eeff92bd60c6b2f1b2becc971d39))
* Single page views for small tables ([#95](https://www.github.com/koesterlab/datavzrd/issues/95)) ([ecd7019](https://www.github.com/koesterlab/datavzrd/commit/ecd70198380e0b837632332fb75667b395f76f6c))

## [1.9.0](https://www.github.com/koesterlab/datavzrd/compare/v1.8.0...v1.9.0) (2022-04-13)


### Features

* Allow combining ellipsis with heatmap ([#93](https://www.github.com/koesterlab/datavzrd/issues/93)) ([6a7d8a1](https://www.github.com/koesterlab/datavzrd/commit/6a7d8a1f2ecdcbd27bd4a7f3959a611d445c0142))

## [1.8.0](https://www.github.com/koesterlab/datavzrd/compare/v1.7.0...v1.8.0) (2022-04-06)


### Features

* Remove pin-columns keyword ([#91](https://www.github.com/koesterlab/datavzrd/issues/91)) ([55aa0f5](https://www.github.com/koesterlab/datavzrd/commit/55aa0f5a0e860874c9281b13f8417da255777e4e))


### Bug Fixes

* fixed linkout button rendering bug ([933dd34](https://www.github.com/koesterlab/datavzrd/commit/933dd34fc2572ade9536b327a121de8b2063be0e))
* tune link button visuals ([becea59](https://www.github.com/koesterlab/datavzrd/commit/becea59de5f915de570daff68aaf47f3212610fc))

## [1.7.0](https://www.github.com/koesterlab/datavzrd/compare/v1.6.0...v1.7.0) (2022-04-06)


### Features

* Style table ([#88](https://www.github.com/koesterlab/datavzrd/issues/88)) ([bffa4a3](https://www.github.com/koesterlab/datavzrd/commit/bffa4a36b4387fa023d00f4d4b952dfc6d5f8f8d))
* Validate linkouts ([#87](https://www.github.com/koesterlab/datavzrd/issues/87)) ([63a8494](https://www.github.com/koesterlab/datavzrd/commit/63a84945a84a724e3d8bd6cb46a52873c78cffb2))

## [1.6.0](https://www.github.com/koesterlab/datavzrd/compare/v1.5.0...v1.6.0) (2022-04-06)


### Features

* Add config validation ([#80](https://www.github.com/koesterlab/datavzrd/issues/80)) ([fd094a3](https://www.github.com/koesterlab/datavzrd/commit/fd094a366d31f55327de6a5a7d8e7cc4c020c5d3))
* Add new keyword hidden ([#83](https://www.github.com/koesterlab/datavzrd/issues/83)) ([1e93444](https://www.github.com/koesterlab/datavzrd/commit/1e934442fb8de432e742d6b8bd5185b4daaab3c5))
* Resize linkout buttons ([#85](https://www.github.com/koesterlab/datavzrd/issues/85)) ([db89115](https://www.github.com/koesterlab/datavzrd/commit/db89115597d94299f5048f6d68a8c05bd06dc637))
* Resize tick plots ([#84](https://www.github.com/koesterlab/datavzrd/issues/84)) ([700c0b7](https://www.github.com/koesterlab/datavzrd/commit/700c0b7b5fb0c3985fa0ba781850fe271044d89c))
* Validate plot scale types ([#86](https://www.github.com/koesterlab/datavzrd/issues/86)) ([4d79364](https://www.github.com/koesterlab/datavzrd/commit/4d79364b186080af6d8c4de30532a1055ff2ce03))

## [1.5.0](https://www.github.com/koesterlab/datavzrd/compare/v1.4.1...v1.5.0) (2022-04-04)


### Features

* Add ellipsis keyword ([#78](https://www.github.com/koesterlab/datavzrd/issues/78)) ([1b5757e](https://www.github.com/koesterlab/datavzrd/commit/1b5757ec9726608b08c4496084136a3d482da258))

### [1.4.1](https://www.github.com/koesterlab/datavzrd/compare/v1.4.0...v1.4.1) (2022-03-29)


### Bug Fixes

* Do not show empty tick plots ([#76](https://www.github.com/koesterlab/datavzrd/issues/76)) ([85d2721](https://www.github.com/koesterlab/datavzrd/commit/85d27219986741575f02b01ad8f998977a4455a2))

## [1.4.0](https://www.github.com/koesterlab/datavzrd/compare/v1.3.1...v1.4.0) (2022-03-29)


### Features

* Add default-view keyword ([#73](https://www.github.com/koesterlab/datavzrd/issues/73)) ([8ae2bc6](https://www.github.com/koesterlab/datavzrd/commit/8ae2bc6dc1fbc9aab372a69256ae6e80a4dce8b9))
* Remove hovering from table ([#75](https://www.github.com/koesterlab/datavzrd/issues/75)) ([224cfd0](https://www.github.com/koesterlab/datavzrd/commit/224cfd067ee3f1844069798ed2e3fc099c883a0d))

### [1.3.1](https://www.github.com/koesterlab/datavzrd/compare/v1.3.0...v1.3.1) (2022-03-26)


### Bug Fixes

* Missing columns when in detail mode for link-url ([#71](https://www.github.com/koesterlab/datavzrd/issues/71)) ([24223c5](https://www.github.com/koesterlab/datavzrd/commit/24223c553a5346b2caa7ab84c04662478e1e9df8))
* Show custom plots in detail view ([#70](https://www.github.com/koesterlab/datavzrd/issues/70)) ([e8c5075](https://www.github.com/koesterlab/datavzrd/commit/e8c50750c0aae6160a31fdc59a0a5e65d286588a))

## [1.3.0](https://www.github.com/koesterlab/datavzrd/compare/v1.2.2...v1.3.0) (2022-03-25)


### Features

* support for regular expressions to match column names ([#65](https://www.github.com/koesterlab/datavzrd/issues/65)) ([542fe4a](https://www.github.com/koesterlab/datavzrd/commit/542fe4a7dcf48a33496abf970eda72d11641febe))


### Bug Fixes

* Adjust header height to content ([8f7f5ba](https://www.github.com/koesterlab/datavzrd/commit/8f7f5ba20678e9183959defe891f6249af80e5c6))
* Highlight rows with border so it doesn't interfere with heatmaps ([#67](https://www.github.com/koesterlab/datavzrd/issues/67)) ([29e310c](https://www.github.com/koesterlab/datavzrd/commit/29e310ca3ae250ab628aea30313637beb9bd8fa4))
* Improve error message for missing columns without optional: true ([#63](https://www.github.com/koesterlab/datavzrd/issues/63)) ([3517b3e](https://www.github.com/koesterlab/datavzrd/commit/3517b3e3fde18f4418c8d3ab3ad5c3ef8bd92a1a))
* No linebreaks in numeric cells ([#62](https://www.github.com/koesterlab/datavzrd/issues/62)) ([3d59973](https://www.github.com/koesterlab/datavzrd/commit/3d59973f049f23c28353da05fa98ee0c67b072c9))
* Remove ellipsis from datavzrd ([#64](https://www.github.com/koesterlab/datavzrd/issues/64)) ([89916d1](https://www.github.com/koesterlab/datavzrd/commit/89916d128301b47bcc3fecbab47ce48c384c1329))

### [1.2.2](https://www.github.com/koesterlab/datavzrd/compare/v1.2.1...v1.2.2) (2022-03-23)


### Bug Fixes

* Adjust header height to content ([#59](https://www.github.com/koesterlab/datavzrd/issues/59)) ([d5307c1](https://www.github.com/koesterlab/datavzrd/commit/d5307c17d988cbc4839c0aefff0bf538f75612f4))

### [1.2.1](https://www.github.com/koesterlab/datavzrd/compare/v1.2.0...v1.2.1) (2022-03-22)


### Bug Fixes

* Do not require empty data for plots ([#56](https://www.github.com/koesterlab/datavzrd/issues/56)) ([e420a8a](https://www.github.com/koesterlab/datavzrd/commit/e420a8a96dd35a463064ce9067e575f665deb727))
* Fix empty files with linkouts ([#54](https://www.github.com/koesterlab/datavzrd/issues/54)) ([63b527a](https://www.github.com/koesterlab/datavzrd/commit/63b527ad4b6fed84293c028d9c77cf85f8e87580))
* Fix example config ([#55](https://www.github.com/koesterlab/datavzrd/issues/55)) ([2da1706](https://www.github.com/koesterlab/datavzrd/commit/2da1706738864b386fe07ffe93f0d024d8679d45))

## [1.2.0](https://www.github.com/koesterlab/datavzrd/compare/v1.1.0...v1.2.0) (2022-03-22)


### Features

* New keyword display-mode ([#51](https://www.github.com/koesterlab/datavzrd/issues/51)) ([cabba0e](https://www.github.com/koesterlab/datavzrd/commit/cabba0e1ff68e9b9cdef92b6ad85d73824fa90a6))


### Performance Improvements

* Render plots via javascript ([#53](https://www.github.com/koesterlab/datavzrd/issues/53)) ([e87fe98](https://www.github.com/koesterlab/datavzrd/commit/e87fe9829b7bd8342f9006e9e9bdc19d0d03df8d))

## [1.1.0](https://www.github.com/koesterlab/datavzrd/compare/v1.0.2...v1.1.0) (2022-03-16)


### ⚠ BREAKING CHANGES

* Refactor item to view (#46)

### Features

* Add domain keyword for ticks and heatmap ([#41](https://www.github.com/koesterlab/datavzrd/issues/41)) ([843b7b5](https://www.github.com/koesterlab/datavzrd/commit/843b7b5b7b43c625341d826688c51856372438fa))
* Add optional keyword for render-table ([#43](https://www.github.com/koesterlab/datavzrd/issues/43)) ([6d245d1](https://www.github.com/koesterlab/datavzrd/commit/6d245d1436423f7e877e62d3140084cbe3906835))
* Make entire row available to link-to-url ([#44](https://www.github.com/koesterlab/datavzrd/issues/44)) ([2f1e87f](https://www.github.com/koesterlab/datavzrd/commit/2f1e87fcac736c5ee9af0af38947473497adc632))
* New keyword spec-path ([#48](https://www.github.com/koesterlab/datavzrd/issues/48)) ([726868d](https://www.github.com/koesterlab/datavzrd/commit/726868df47fc279f07bc4b0bd2b6cdec532b95ce))


### Bug Fixes

* Fix broken plots for headers with whitespaces ([#40](https://www.github.com/koesterlab/datavzrd/issues/40)) ([7bb9b59](https://www.github.com/koesterlab/datavzrd/commit/7bb9b596e49a671071bb2460d80bd3815c049585))


### Code Refactoring

* Refactor item to view ([#46](https://www.github.com/koesterlab/datavzrd/issues/46)) ([1d86341](https://www.github.com/koesterlab/datavzrd/commit/1d86341f0564e5350b05cfd9f30c6eff70524aed))


### Miscellaneous Chores

* release 1.1.0 ([9c111f3](https://www.github.com/koesterlab/datavzrd/commit/9c111f369da24073c47466020e38e18f5bda8b83))

### [1.0.2](https://www.github.com/koesterlab/datavzrd/compare/v1.0.1...v1.0.2) (2022-03-10)


### Bug Fixes

* Fix custom plots ([075688a](https://www.github.com/koesterlab/datavzrd/commit/075688a4db07a929fc88928e422be2d34e8b33bc))

### [1.0.1](https://www.github.com/koesterlab/datavzrd/compare/v1.0.0...v1.0.1) (2022-03-09)


### Bug Fixes

* Fix example config ([d280358](https://www.github.com/koesterlab/datavzrd/commit/d280358dc94d0048a2f5ea216007da9695d99bad))
* No error for empty csv files ([#37](https://www.github.com/koesterlab/datavzrd/issues/37)) ([ce6ea18](https://www.github.com/koesterlab/datavzrd/commit/ce6ea187a6be70634c20ffb3a9d27761153b2054))
* use smaller font sizes and less padding ([#34](https://www.github.com/koesterlab/datavzrd/issues/34)) ([7f17009](https://www.github.com/koesterlab/datavzrd/commit/7f170099f3a50b230e21d44d991ecc341559acf7))

## [1.0.0](https://www.github.com/koesterlab/datavzrd/compare/v0.3.0...v1.0.0) (2022-02-21)


### ⚠ BREAKING CHANGES

* Rename schema to spec and scheme to color-scheme (#31)

### Code Refactoring

* Rename schema to spec and scheme to color-scheme ([#31](https://www.github.com/koesterlab/datavzrd/issues/31)) ([b9fca5f](https://www.github.com/koesterlab/datavzrd/commit/b9fca5f2cb6b145b55527bef2eed95c1359ef467))

## [0.3.0](https://www.github.com/koesterlab/datavzrd/compare/v0.2.0...v0.3.0) (2022-02-18)


### Features

* Allow user to use width: container in vega-lite specs ([#30](https://www.github.com/koesterlab/datavzrd/issues/30)) ([c65693b](https://www.github.com/koesterlab/datavzrd/commit/c65693b12c51dcb9d63466172776d2348c4ecabd))
* Create output directory if it does not exist ([#27](https://www.github.com/koesterlab/datavzrd/issues/27)) ([08eafbe](https://www.github.com/koesterlab/datavzrd/commit/08eafbe671c78ee7b88413194b2f8e2982b696d9))


### Bug Fixes

* Minor cosmetic changes ([#29](https://www.github.com/koesterlab/datavzrd/issues/29)) ([e813018](https://www.github.com/koesterlab/datavzrd/commit/e813018a09cc45375109ce78f1fbe6b54879c435))

## [0.2.0](https://www.github.com/koesterlab/datavzrd/compare/v0.1.2...v0.2.0) (2022-02-16)


### Features

* Add example report ([#21](https://www.github.com/koesterlab/datavzrd/issues/21)) ([4e266a0](https://www.github.com/koesterlab/datavzrd/commit/4e266a09f3bfa0250604ca67e8531022a8ac8ced))
* Show proper error message for non existing output directory ([#26](https://www.github.com/koesterlab/datavzrd/issues/26)) ([008524f](https://www.github.com/koesterlab/datavzrd/commit/008524f2748fe37cece68fe65700e2deda13bcb2))
* Show proper error message for wrong file paths ([#25](https://www.github.com/koesterlab/datavzrd/issues/25)) ([c0e7539](https://www.github.com/koesterlab/datavzrd/commit/c0e75396cfa08e9c9745b79acdaf5a618632d318))


### Bug Fixes

* Complete error message for wrong config file path ([#24](https://www.github.com/koesterlab/datavzrd/issues/24)) ([b0dc4aa](https://www.github.com/koesterlab/datavzrd/commit/b0dc4aa8b568a555a70e2b48e9bf57da4c1149c8))

### [0.1.2](https://www.github.com/koesterlab/datavzrd/compare/v0.1.1...v0.1.2) (2022-02-15)


### Bug Fixes

* add missing license ([a0a3473](https://www.github.com/koesterlab/datavzrd/commit/a0a34735ca044033f42b72b7cbe975ea9e1357e9))
* Display correct column on missing value ([#19](https://www.github.com/koesterlab/datavzrd/issues/19)) ([bacbe5b](https://www.github.com/koesterlab/datavzrd/commit/bacbe5b8819b54990a4243fe3b24342ee581f870))

### [0.1.1](https://www.github.com/koesterlab/datavzrd/compare/v0.1.0...v0.1.1) (2022-02-15)


### Bug Fixes

* updated release process ([e8463f7](https://www.github.com/koesterlab/datavzrd/commit/e8463f7db8d946898a36f5d7001984515322ad1c))

## 0.1.0 (2022-02-15)


### Features

* Add heatmap keyword ([#12](https://www.github.com/koesterlab/datavzrd/issues/12)) ([d8e3582](https://www.github.com/koesterlab/datavzrd/commit/d8e35822b4d63a78b81a5e1e8344d0259006fcf6))
* add infrastructure for column index and row address ([#1](https://www.github.com/koesterlab/datavzrd/issues/1)) ([7df380c](https://www.github.com/koesterlab/datavzrd/commit/7df380c11f07bf48b199de5c67448ae053435d54))
* Add optional description for tables ([#8](https://www.github.com/koesterlab/datavzrd/issues/8)) ([3a6dcf6](https://www.github.com/koesterlab/datavzrd/commit/3a6dcf6f00979bdd771cb11b68ef450b7bd169c9))
* Add optional report name ([#15](https://www.github.com/koesterlab/datavzrd/issues/15)) ([aa2713a](https://www.github.com/koesterlab/datavzrd/commit/aa2713a7c9266dadd91ced8f8e8346990ad57cb1))
* Add pin-columns keyword ([#16](https://www.github.com/koesterlab/datavzrd/issues/16)) ([8869e57](https://www.github.com/koesterlab/datavzrd/commit/8869e57625df8bcc4c64504568a545da69dee155))
* Add tick plots ([#10](https://www.github.com/koesterlab/datavzrd/issues/10)) ([4b87407](https://www.github.com/koesterlab/datavzrd/commit/4b874079045919379175b36a489093d4fa2ec6e1))
* Add vega-controls option ([#11](https://www.github.com/koesterlab/datavzrd/issues/11)) ([9adeebb](https://www.github.com/koesterlab/datavzrd/commit/9adeebb108060cc1c876cae3f1b59f174ef605c9))
* Allow multiple header rows ([#6](https://www.github.com/koesterlab/datavzrd/issues/6)) ([79b7e38](https://www.github.com/koesterlab/datavzrd/commit/79b7e38a8b1d8e2871674947d0e45bd20b3791e2))
* Autofocus input in search dialog ([#14](https://www.github.com/koesterlab/datavzrd/issues/14)) ([9cf8a66](https://www.github.com/koesterlab/datavzrd/commit/9cf8a661057a667b4f3e235b4fd264ea2164e818))
* Don't show unreasonable plots ([#7](https://www.github.com/koesterlab/datavzrd/issues/7)) ([983d333](https://www.github.com/koesterlab/datavzrd/commit/983d3332cd751316b9828ef36bbce87b19e62a29))
* Let user access columns in config via index ([c9885b5](https://www.github.com/koesterlab/datavzrd/commit/c9885b5572e1c56a00086837f2b2106134907c93))
* Restructure config and add plot items ([#13](https://www.github.com/koesterlab/datavzrd/issues/13)) ([a3fe4c5](https://www.github.com/koesterlab/datavzrd/commit/a3fe4c557e0c536db282f4516956b5c573eb9e91))
* Support custom plots ([#9](https://www.github.com/koesterlab/datavzrd/issues/9)) ([7a57824](https://www.github.com/koesterlab/datavzrd/commit/7a5782484cd470b78ced9529bfac959db7252c21))
