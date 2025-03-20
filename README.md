# notPlancha's bucket

My bucket with apps that I didn't found in other buckets or in winget or in chocolatey (mostly).

## Add bucket

```pwsh
scoop bucket add notPlancha https://github.com/notPlancha/bucket
# scoop install notPlancha/app
```

## Developing

There's some useful ps1 files, here's the important ones:

- `checkhashes.ps1 <package>` checks if the hash of the download is the same of the manifest
- `checkurls.ps1 <package>` checks if the urls of the downloads work
- `formatjson.ps1` formats the manifests in an uniform way
- `checkver.ps1 <package>` can be use to check if the version it collcts is correct
-  `missing-checkver.ps1 <package>`
`<package>` is always optional



Here's some tips:
- Make sure to use latest pwsh.
- Scoop currently has an issue which affects my autoupdate (related to checkver) ([#6274](https://github.com/ScoopInstaller/Scoop/pull/6274)), use [my scoop instead](https://github.com/notPlancha/scoop) for development. You can check https://github.com/notPlancha/scoop-install to see how to install it or substitute the regular scoop version.
- check the issues tab
- To finally test the changes you can do:

```pwsh
scoop install ./bucket/<package>.json # like scoop install ./bucket/viper.json
```


## Apps

- [Iriun Webcam](https://iriun.com/)
- [Windows Update MiniTool](https://www.majorgeeks.com/files/details/windows_update_minitool.html)
- [sticker-convert](https://github.com/laggykiller/sticker-convert)
- [LoR Master Tracker](https://lormaster.com/)
- [Bio7](https://bio7.org/)
- [NightLight Desktop](https://nightlight.gg/desktop)
- [ARMGDDN Browser](https://cs.rin.ru/forum/viewtopic.php?f=14&t=140593)
- [Rat Scanner](https://ratscanner.com/)
- [Tinn-R Editor](https://sourceforge.net/projects/tinn-r/)
- [RKWard](https://rkward.kde.org/)
- [Viper](https://github.com/0neGal/viper)
- [Deceive](https://github.com/molenzwiebel/Deceive/)
- [Daac2Disk](https://lpdaac.usgs.gov/tools/daac2diskscripts/)
- [gitrewrite](https://github.com/heinrichti/GitRewrite)
- [dups](https://github.com/Navid2zp/dups)
- [Myth Mod Manager](https://modworkshop.net/mod/43276)
- [Rstudio](https://posit.co/downloads/) without R
