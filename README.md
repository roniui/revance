# ReVanced Magisk Module
[![Latest Version](https://img.shields.io/github/v/release/roniui/revance?style=flat-square&color=blue&label=Release)](https://github.com/roniui/revance/releases/latest)
[![CI](https://github.com/j-hc/revanced-magisk-module/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/j-hc/revanced-magisk-module/actions/workflows/ci.yml)

Extensive ReVanced builder  

Get the [latest CI release](https://github.com/roniui/revance/releases).


<details><summary><big>Features</big></summary>
<ul>
 <li>Support all present and future <a href="https://github.com/MorpheApp/morphe-patches">Morphe</a> apps</li>
 <li> Can build non-root APKs</li>
 <li> Updated with the latest versions of patches</li>
 <li> Optimize APKs and modules for size</li>
 
Note that the <a href="../../actions/workflows/ci.yml">CI workflow</a> is scheduled to build the modules and APKs everyday using GitHub Actions if there is a change in Morphe patches. You may want to disable it.
</details>

## To include/exclude patches or patch other apps

 * Star the repo :eyes:
 * Use the repo as a [template](https://github.com/new?template_name=revance&template_owner=roniui)
 * Customize [`config.toml`](./config.toml) using [rvmm-config-gen](https://j-hc.github.io/rvmm-config-gen/)
 * Run the build [workflow](../../actions/workflows/build.yml)
 * Grab your modules and APKs from [releases](../../releases)

also see here [`CONFIG.md`](./CONFIG.md)

## Credits 

[j-hc](https://github.com/j-hc/revanced-magisk-module)
