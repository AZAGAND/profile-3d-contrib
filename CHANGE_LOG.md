# Change Log

## 2025-09-13, 0.9.1 release

* Fixed "week" to be calculated correctly even when the start date is not a Sunday. #126
* Changed node version from 20 to 24. #119
* Changed actions/checkout version from v4 to v5. #119
* Added translations to the README file. #116
* Updated the version of the dependent packages (via package-lock.json).

## 2025-03-13, 0.9.0 release

* You can now specify `darkMode` definitions in custom JSON files that can be specified in `SETTINGS_JSON`. This allows you to generate svg that supports both light mode and dark mode. The light mode type and dark mode type must match. See `sample-settings/green.dual.json` for details.
* The latest version can now be specified with the `latest` branch.

## 2025-03-09, 0.8.0 release

* Added environment variable `GITHUB_ENDPOINT`.
* Added environment variable `YEAR`.

## 2025-03-05, 0.7.2 release

* Changed node version from 16 to 20.
* Changed actions/checkout version from v3 to v4.
* Update dependent libraries(see package.json).

## 2023-01-11, 0.7.1 release

* Changed node version from 12 to 16.
* Changed actions/checkout version from v2 to v3.

## 2022-08-10, 0.7.0 release

* Added Spanish README.
* Enabled to specify the output destination file name when using settings json
* Multiple custom definitions can be specified in the settings json.
* Made it possible to change the label with a custom definition.
* Added pie_lang_only and radar_contrib_only modes.
* fix: performance bitmap mode.
* fix: growing animation of settings json

## 2022-02-12, 0.6.0 release

* Added git block version.
* New support for setting json file.

## 2022-01-29, 0.5.0 release

* Use logarithm to calculate the height of the bars.

## 2022-01-09, 0.4.0 release

* Added night green version.

## 2021-12-22, 0.3.1 release

* Changed the maximum number of contributors to 9999

## 2021-12-22, 0.3.0 release

* Added season version for the Southern Hemisphere.
* Added night view version.
* Added night rainbow version.

## 2021-05-11, 0.2.0 release

* The repositories to be aggregated are only those owned by the user.
* Allow the number of repositories to be aggregated to be defined by environment variables.
  * `MAX_REPOS` : (optional) max repositories, default 100
* Make the colors of the four seasons mode every week and make a gradation.
  * The image colors of each season are as follows.
    * spring flowers
    * summer leaves
    * autumn leaves
    * winter snow
* Label the radar chart scale with "1-, 10, 100, 1K, 10K+".
* Supports Halloween mode on github.
* The USERNAME can also be specified from the argument.
  * Usage: `node dist/index.js <USER-NAME>` without env `USERNAME`

## 2021-05-09, 0.1.0 release

First release.
