# ![logo](https://raw.githubusercontent.com/azerothcore/azerothcore.github.io/master/images/logo-github.png) AzerothCore
- Latest build status with azerothcore: [![Build Status](https://travis-ci.org/azerothcore/mod-npc-titles-tokens.svg?branch=master)](https://travis-ci.org/azerothcore/mod-npc-titles-tokens)

# ViperDev Modules

Npc Token Titles

This is a module for AzerothCore that results in titles per token in an npc.

Current Features:

Npc gives a list of titles for what can be purchased with a token (Default Token 37829), you can change the token in the .cpp to your own token too. 

The model currently requires:

AzerothCore v1.0.1 +

How to install

### 1) Simply place the module in a folder of your AzerothCore source folder.

You can clone via git in the azerothcore / modules directory or:

git clone https://github.com/vhipercode/mod-npctitles-tokens.git

You can download the module, unzip a folder and update it in the azerothcore / modules directory.

### 2) sql - Npc title (token).sql -> DB world

### 3) Rerun the game and launch a clean build of AzerothCore

### 4) Finally enter the game and add the title npc .npc add 200012

### 5) Add Currency .add 37829 (Brewfest Prize Token)

