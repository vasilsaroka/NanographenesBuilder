[![GitHub (pre-)release](https://img.shields.io/github/release/vasilsaroka/NanographenesBuilder/all.svg)](https://github.com/vasilsaroka/NanographenesBuilder/releases)
[![GitHub Downloads (all assets, latest release)](https://img.shields.io/github/downloads-pre/vasilsaroka/NanographenesBuilder/latest/total?label=downloads%20latest)](https://github.com/vasilsaroka/NanographenesBuilder/releases)
[![GitHub Downloads (all assets, specific tag)](https://img.shields.io/github/downloads/vasilsaroka/NanographenesBuilder/v1.0.0/total?label=downloads%20v1.0.0)](https://github.com/vasilsaroka/NanographenesBuilder/releases/tag/v1.0.0)
[![Github All Releases](https://img.shields.io/github/downloads/vasilsaroka/NanographenesBuilder/total?label=downloads%20all)](https://github.com/vasilsaroka/NanographenesBuilder/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Support TBpack](https://img.shields.io/static/v1?label=support&message=5$&color=green&style=flat&logo=paypal)](https://paypal.me/vasilsaroka?locale.x=en_GB)


# NanographenesBuilder
Wolfram Mathematica graphical user interface (GUI) or mini-app for building benzenoid hydrocarbons with on-the-fly graph theory analysis and export to .XYZ file

## Requirements
The code was developed and tested under
 - OS: Microsoft Windows 11 Home
 - Mathematica 14.2.1 for Microsoft Windows (64-bit) (March 17, 2025).

## Installation
This repository contains only a notebook with core functions in `.../Core` folder.

The GUI distributed in [releases](https://github.com/vasilsaroka/NanographenesBuilder/releases) does not require installation. It can be run as a regular Mathematica Notebook (.nb), which contains a dynamical content and requires enabling upon the start:
<p align="center">
<img align="center" src="https://github.com/vasilsaroka/NanographenesBuilder/blob/main/Demo/Enable_Dynamics_button.png" alt="Enable_Dynamics_button" width="1000"/>
</p>
Once dynamical content is enabled, the GUI must be active and responsive out-of-the-box.

## Demo
The starting screen of the GUI looks as follows:
<p align="center">
<img src="https://github.com/vasilsaroka/NanographenesBuilder/blob/main/Demo/WelcomeScreen.png" alt="Welcome_screen" width="400"/>
</p>

The basic use and idea behind are explained in detail in the LinkedIn article [A computational essay on topological frustration and graph theory](https://www.linkedin.com/pulse/computational-essay-topological-frustration-graph-theory-vasil-saroka-epcvf/) and a cross-post on Wolfram Community [Graph-theoretic topological frustration in nanographenes: matchings, deficit, and decomposition](https://community.wolfram.com/groups/-/m/t/3737934). The latter contains the built-in GUI in the relevant section "Wolfram Language app". A quick start is
<p align="center">
<img src="https://github.com/vasilsaroka/NanographenesBuilder/blob/main/Demo/NanographenesBuilder5g.gif" alt="Basic_use" width="400"/>
</p>

## WLJS Notebooks
   Thanks to [@JerryI](https://github.com/JerryI/) we have also a [WLJS version](https://wljs.io/) of the GUI, which is slightly faster and dynamically more agile. It has also such nice features as zooming of the basic canvas. 
   
   ### WLJS Notebook Demo
   The demo produced half-way through WLJS version development by [@JerryI](https://github.com/JerryI/):
   <p align="center">
   <img src="https://github.com/vasilsaroka/NanographenesBuilder/blob/main/Demo/WLJS_promo.gif" alt="WLJS_promo" width="800"/>
   </p>
   
   For the final version, please, see the blog-post [Building an Interactive Nanographene Constructor](https://wljs.io/blog/graphene-app/).

## Supporting the project
   We believe that everyone deserves access to reliable, science-based knowledge. That's why we keep our product accessible to all, no matter their location or financial situation. By doing this, we empower more people to educate themselves and contribute to global wellbeing. Unlike major corporations, we are not backed by trillionaire owners; our work is entirely powered by our curiousity. Therefore, your donations are really appreciated for keeping us going. Anyone [making a donation](https://paypal.me/vasilsaroka?locale.x=en_GB) is entitled to request a Mathematica version without watermarks. 
