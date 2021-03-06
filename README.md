# For end users
* Play store link: https://play.google.com/store/apps/details?id=sanskritcode.sanskritdictionaryupdater
* [Ratings Certificate](https://iarcweb.azurewebsites.net/Dashboard/Certificate/74e40614-671c-421e-9969-1c80da21a267)
* Signed apk is also [released](https://github.com/sanskrit-coders/stardict-dictionary-updater/releases) in this repository.

# For code contributors
See comment in MainActivity.java for a rough understanding of the code.

Review notifications setup: https://support.google.com/googleplay/android-developer/answer/138230?hl=en

# For dictionary contributors
* Just open an issue in the most appropriate project (stardict-sanskrit, stardict-hindI, stardict-kannada, stardict-pAlI, stardict-tamiL, stardict-telugu), or if there is no match, in this project.

## To contribute new dictionary repositories
* We will just need to list your dictionary repository in <dictioanryIndices.md>. Open an issue in this project.
* Creating your dictionary repository:
  * Just follow the pattern you observe in, say [this repo](<https://raw.githubusercontent.com/sanskrit-coders/stardict-sanskrit/master/sa-head/tars/tars.MD>).
  * Note that the filename of your dictionary should have two parts, separated by __, as in `kRdanta-rUpa-mAlA__2016-02-20_23-22-27`.
    * The first part should be the actual dictionary name, the second the timestamp.
  * All stardict and other dictionary files should have names matching the dictionary name specified above.
