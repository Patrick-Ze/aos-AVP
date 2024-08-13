# NOVA: opeN sOurce Video plAyer

[![GitHub release](https://img.shields.io/github/v/release/nova-video-player/aos-AVP.svg?logo=github&label=GitHub&cacheSeconds=3600)](https://github.com/moneytoo/Player/releases/latest)
[![GitHub downloads](https://img.shields.io/github/downloads/nova-video-player/aos-AVP/total?logo=github&cacheSeconds=3600)](https://github.com/nova-video-player/aos-AVP/releases/latest)
[![Google Play version](https://img.shields.io/endpoint?color=green&logo=google-play&logoColor=white&url=https%3A%2F%2Fplay.cuzi.workers.dev%2Fplay%3Fi%3Dorg.courville.nova%26gl%3DUS%26hl%3Den%26l%3DGoogle%2520Play%26m%3D%24version)](https://play.google.com/store/apps/details?id=org.courville.nova)
[![Google Play rating](https://img.shields.io/endpoint?color=green&logo=google-play&url=https%3A%2F%2Fplay.cuzi.workers.dev%2Fplay%3Fi%3Dorg.courville.nova%26l%3Drating%26m%3D%25E2%2598%2585%2520%24rating)](https://play.google.com/store/apps/details?id=org.courville.nova)
[![Google Play downloads](https://img.shields.io/endpoint?color=green&logo=google-play&logoColor=white&url=https%3A%2F%2Fplay.cuzi.workers.dev%2Fplay%3Fi%3Dorg.courville.nova%26gl%3DUS%26hl%3Den%26l%3Ddownloads%26m%3D%24totalinstalls)](https://play.google.com/store/apps/details?id=org.courville.nova)
[![Get it on Amazon Appstore](https://badgen.net/badge/Get%20it%20on/Amazon%20Appstore/689f38)](https://www.amazon.fr/dp/B07P1Q1DG9)
[![Get it on F-Droid](https://img.shields.io/f-droid/v/org.courville.nova?logo=f-droid&label=F-Droid&cacheSeconds=3600)](https://f-droid.org/packages/org.courville.nova)
[![Get it on IzzyOnDroid](https://img.shields.io/endpoint?url=https://apt.izzysoft.de/fdroid/api/v1/shield/org.courville.nova&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAMAAABg3Am1AAADAFBMVEUA0////wAA0v8A0v8A0////wD//wAFz/QA0/8A0/8A0/8A0/8A0v///wAA0/8A0/8A0/8A0/8A0//8/gEA0/8A0/8B0/4A0/8A0/8A0/+j5QGAwwIA0//C9yEA0/8A0/8A0/8A0/8A0/8A0/+n4SAA0/8A0/8A0/+o6gCw3lKt7QCv5SC+422b3wC19AC36zAA0/+d1yMA0/8A0/+W2gEA0/+w8ACz8gCKzgG7+QC+9CFLfwkA0/8A0////wAA0/8A0/8A0/8A0/+f2xym3iuHxCGq5BoA1P+m2joI0vONyiCz3mLO7oYA0/8M1Piq3Ei78CbB8EPe8LLj9Ly751G77zWQ1AC96UYC0fi37CL//wAA0/8A0////wD//wCp3jcA0/+j3SGj2i/I72Sx4zHE8FLB8zak1kYeycDI6nRl3qEA0/7V7psA0v6WzTa95mGi2RvB5XkPy9zH5YJ3uwGV1yxVihRLiwdxtQ1ZkAf//wD//wD//wD//wD//wCn5gf//wD//wD//wD//wD//wAA0/+h4A3R6p8A0/+X1w565OD6/ARg237n9csz2vPz+gNt37V/vifO8HW68B/L6ZOCwxXY8KRQsWRzhExAtG/E612a1Rd/pTBpmR9qjysduKVhmxF9mTY51aUozK+CsDSA52T//wD//wAA0////wD//wBJ1JRRxFWjzlxDyXRc0pGT1wCG0CWB3VGUzSTh8h6c0TSr5CCJ5FFxvl6s4H3m8xML0/DA5CvK51EX1N+Y2gSt4Dag3ChE3fax2ki68yO57NF10FRZnUPl88eJxhuCxgCz5EOLwEGf1DFutmahzGW98x0W1PGk3R154MHE6bOn69qv3gy92oG90o+Hn07B7rhCmiyMwECv1nO+0pQfwrCo57xF2daXsVhKrEdenQAduaee1Bsjr42z5D9RoCXy+QNovXpy2Z5MtWDO/TiSukaF3UtE1K6j3B4YwLc5wXlzpyIK0u5zy3uJqg4pu5RTpkZmpVKyAP8A0wBHcExHcEyBUSeEAAABAHRSTlP///9F9wjAAxD7FCEGzBjd08QyEL39abMd6///8P/ZWAnipIv/cC6B//7////////L/1Dz/0D///////86/vYnquY3/v///5T//v///17///////////////84S3QNB/8L/////////////7r/////NP////9l/////wPD4yis/x7Ym2lWSP+em////0n////////v///////////////////7//7pdGN3Urr6/+v/6aT////+//H/o2P/1v+7r7jp4PM/3p4g////g///K///481LxO///v////9w////8v/////9/p3J///a+P9v/5KR/+n///+p/xf//8P//wAAe7FyaAAABCZJREFUSMdj+E8iYKBUgwIHnwQ3N7cEHxcH+///VayoAE0Dh41qR7aBnCIQ8MsJKHH9/99czYYMWlA0cIkJGjMgAKfq//9RNYzIgLcBWYOTiCgDMhDn+B9bh6LebiWyH6L5UZQzONoAHWSHoqEpDkkDsyKqelv1//9rG1HUN9YihZK9AKp6BkG+/6xNqA5ajhSsCkrIipmYGGRa//9vQXVQXSySBnkWJOUMfn5Myuz/G3hR1NdEIUUchwiy+bkTsg4dbW/fu6W/e1c3XMMy5JiOZkFxUFZo74mgKTqaKXu0+2HqVwkja3BH9kFu361JwcHTfPJD4mdfe8ULAdVRyGlJAcVFfg+CQOozZ4XrJ85+JgwBsVXIGriQw5Tp4ZScezd8JiWnBupru30qwJZa+ZAjmWlC8fUZM4qB6kPnLNSPLMWqQQ5ZQ5aOzs1HmamBaQHzFs6y+qAmJCTE8f9/QgKSBg4DJPWc6zVDQkIC09JkZSPD38kukpExFpT4z67uYI/QwCOOCCK/izvu5CWl6AcEWMnKWml7LWbKZfH9/99UkknQHhGsynDz+65eWXv3/JmJrq5eXienVlRUfH/z8VvCf45soKQIH1yDEQsszrp6gwq9C73T87xcXadKl5TkFev4A/2tygmSBqYXqAYJmK+ZuoJydDR1vP09DA0NOy2kpdML81+U/heCpH1JU3jig7lJ5nKOT4i/t6ZHkqGzs4lJmIVHfrj+JR4HqLQSD0yDkCNEpGNn5ix9D03/eJdElTZdKV2TpNOhkwt8YUlNUgimgV0dLMBvf1gz1MolPd5FRcVNSkpDQ8owJeBCDyIhrIDnOD5QcuIU+3/2QKSs9laQ+noNLS0zLWdtqyP7mBAFAw88TwsJgMuJYweBGjYngtWbmeuZOW+bvNQToUFOAlFqOBk4Ov3/L7Z60/aN0p1tUhpa5nqWlub7C3p2I9QzyAghlUvczOz/1fhzPT3XSIfpSmmYAdVbmm1gV0dSz8DSilpUQsqCddIWIA3meuZaJqdMJZEzl6gRqgZIWZAxUdoizERXN8yi5MltcZTChzMaRQM3JNUWHS8rL/+yaPGvMmvr5ywoGoxtkDWwQ+Pb89ycBeWfGSJeL/la+RS1eOPnRtbQKgMRjZg+t8x6PkP273nWQAoFOPAgaeAThKXAmXMrK39Kmr5fsuBlBqoXfJGLe3VbmHjG9Mczi9T//3h7vygXtcDlQtJg44iQiIjIBRbGPO7gghPJy0ZIxT2HOLIUgwxQzsgYrUR350HSIMaJLidhgKY+mw+pflBDrX8E7OGBjPCAPc76gQFSTqAIiYrb/8dRP4CyosJ/rmwU5XIxHMilt4QBJwsSkBMClxOQULBlkRRwEONmR2kJcDGjADX2/+xO8r5iqjExqmLyrWpcPFRta1BfAwCtyN3XpuJ4RgAAAABJRU5ErkJggg==
)](https://apt.izzysoft.de/fdroid/index/apk/org.courville.nova)
[![Crowdin](https://badges.crowdin.net/nova-video-player/localized.svg)](https://crowdin.com/project/nova-video-player)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/nova-video-player/aos-AVP/blob/nova/LICENSE.txt)
[![Reddit Nova Community](https://img.shields.io/reddit/subreddit-subscribers/novavideoplayer?style=social)](https://www.reddit.com/r/NovaVideoPlayer/)
[![Chat on irc](https://img.shields.io/badge/irc.libera.chat-%23novavideoplayer-blue.svg)](https://web.libera.chat/)
![Build status](https://github.com/nova-video-player/aos-Video/workflows/NOVA%20CI/badge.svg)
[![Donate](https://img.shields.io/badge/liberapay-donate-yellow.svg?logo=liberapay)](https://liberapay.com/NovaVideoPlayer/donate)

## Overview

NOVA is an open source video player for Android. It consists in a fork of the original Archos Video Player Community Edition that is hosted here: https://github.com/archos-sa/aos-AVP intended to support new features.

Latest application FAQ can be found [here](https://github.com/nova-video-player/aos-AVP/blob/nova/faq/faq.md).

This is the entry point repo. Its purpose is to provide the manifest to fetch all needed git repos with sources and then bootstrap the build environment.

More interesting sources can be found there:
- Video https://github.com/nova-video-player/aos-Video
- MediaLib https://github.com/nova-video-player/aos-MediaLib
- FileCoreLibrary  https://github.com/nova-video-player/aos-FileCoreLibrary
- avos https://github.com/nova-video-player/aos-avos

For the full list, please look at this manifest https://github.com/nova-video-player/aos-AVP/default.xml

## Building

Get the repo tool (https://source.android.com/source/downloading), then type:
```
mkdir aos; cd aos
repo init -u https://github.com/nova-video-player/aos-AVP -b nova
repo sync -j4
repo forall -c 'git checkout -t $REPO_REMOTE/$REPO_RREV'
make
```

Alternatively, for those not under Linux with a properly installed Android SDK/NDK, you can launch the video player build through:
```
cd Video
./gradlew -Puniversal assembleNoamazonRelease
```

In order to speed up the build, build is performed using dav1d, ffmpeg and other pre-built binaries and using local git clone of ffmpeg and dav1d repos. In order to trigger full update rebuild, you need in case of version upstep to manually do:
```
rm -rf native/torrentd/libs
cd native/dav1d-android-builder; git clean -fdx; rm -rf built-*
cd native/ffmpeg-android-builder; git clean -fdx; rm -rf dist-*
```

Note that the following packages are required to build:
```
sudo curl https://storage.googleapis.com/git-repo-downloads/repo > /usr/local/bin/repo
sudo chmod a+x /usr/local/bin/repo
sudo apt install build-essential wget curl unzip openjdk-8-jdk python git pkg-config meson nasm
```

Recent versions of nasm (≥2.13) and meson (≥0.47) are now required for building ffmpeg/dav1d.
Nasm can be installed with:
```
wget http://www.nasm.us/pub/nasm/releasebuilds/2.14.02/nasm-2.14.02.tar.bz2
tar xjvf nasm-2.14.02.tar.bz2
cd nasm-2.14.02
./autogen.sh
PATH="$HOME/bin:$PATH" ./configure
PATH="$HOME/bin:$PATH" make
sudo make install
```
Latest meson can be installed via:
```
sudo apt install -y pkg-config python3 python3-pip python3-setuptools ninja-build
sudo pip3 install --upgrade pip
pip3 install --user meson==0.53.2
```

Alternatively, you can use the provided docker image to build nova:
```
cd nova/AVP/docker
docker build -t nova .
docker run --rm -ti --entrypoint=/bin/bash nova
make
```

Travis-ci build configuration file is also provided here: https://github.com/nova-video-player/aos-Fdroid/blob/master/.travis.yml

Binaries prebuilt of torrentd, ffmpeg, dav1d have been committed in order to reduce compilation time and remove nasm, meson dependencies. If you need to regenerate torrentd, ffmpeg and dav1d libs, please run `make clean_prebuilt`.

## Latest stable apk

The compiled application is available for installation on Google Play: https://play.google.com/store/apps/details?id=org.courville.nova

[<img src="https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png" alt="Get it on Google Play" height="80" align="center">](https://play.google.com/store/apps/details?id=org.courville.nova)

or on Amazon Appstore: https://www.amazon.fr/dp/B07P1Q1DG9 

[<img src="https://images-na.ssl-images-amazon.com/images/G/01/mobile-apps/devportal2/res/images/amazon-appstore-badge-english-black.png" alt="Get it on Amazon Appstore" height="50" align="center">](http://www.amazon.com/gp/mas/dl/android?p=org.courville.nova)

or on F-Droid https://f-droid.org/packages/org.courville.nova

[<img src="https://fdroid.gitlab.io/artwork/badge/get-it-on.png" alt="Get it on F-Droid" height="80" align="center">](https://f-droid.org/packages/org.courville.nova)

or on IzzyOnDroid https://apt.izzysoft.de/fdroid/index/apk/org.courville.nova

[<img src="https://gitlab.com/IzzyOnDroid/repo/-/raw/master/assets/IzzyOnDroid.png" alt="Get it on IzzyOnDroid" height="80" align="center">](https://apt.izzysoft.de/fdroid/index/apk/org.courville.nova)

Releases are also published on github: https://github.com/nova-video-player/aos-AVP/releases

## Scraping and Scrobbling

Scraping and scrobbling features rely on external services such as **TMDb** (https://www.themoviedb.org/), **TheTVDB** (http://thetvdb.com/) and **Trakt** (https://trakt.tv).

In order to enable NOVA video player to perform these tasks, you need to register to this services and enable the API and inject the corresponding keys inside the following files: *MediaLib/src/community/res/values/donottranslate.xml*
replacing the fake values below:
```xml
    <?xml version="1.0" encoding="utf-8"?>
    <resources xmlns:android="http://schemas.android.com/apk/res/android">
        <string name="tvdb_api_key">0123456789ABCDEF</string>
        <string name="tmdb_api_key">0123456789abcdef0123456789abcdef</string>
        <string name="trakt_api_key">0123456789abcdef0123456789abcdef0123456789abcdef0123456789abcdef</string>
        <string name="trakt_api_secret">0123456789abcdef0123456789abcdef0123456789abcdef0123456789abcdef</string>
    </resources>
```

Please note that enabling **TheTVDB** API registration can be completed following this link: https://www.thetvdb.com/?tab=apiregister


To create a **Trakt** api, first register to trakt then add a new app
https://trakt.tv/oauth/applications

Redirect URI should be
http://localhost
and be aware to grant all permissions.

## Localization

You are welcome to contribute to the translation of the application at https://crowdin.com/project/nova-video-player

## Donate

Any contribution to show your gratitude and appreciation is always welcome, keeping the small team of developers working on their personal time motivated and aware that their dedication means something.

Three main platforms are proposed for that purpose: [liberapay](https://liberapay.com/NovaVideoPlayer/donate), [github sponsor](https://github.com/sponsors/courville) and [opencollective](https://opencollective.com/novavideoplayer).

Funds collected are essentially used to buy devices on which problems are reported for analysis and fix in order to cope with Android fragmentation.

Please bear in mind that the work carried out here results from a small community effort done with good will on scarce personal time.
If need be, we might in the future introduce some extra bounty programs for specific feature development requests.

## Support community and chat room

[NovaVideoPlayer reddit community](https://www.reddit.com/r/NovaVideoPlayer) community is used as the support community for the Nova Video Player application.
It is possible to chat with Nova Video Player developers on #novavideoplayer liberachat IRC channel (https://web.libera.chat/).

