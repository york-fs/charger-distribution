# Charger Distribution Board

![Revision](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fyork-fs.github.io%2Fcharger-distribution%2Finfo.json&query=%24.revision&label=Revision)
![Pad Count](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fyork-fs.github.io%2Fcharger-distribution%2Finfo.json&query=%24.pad_count&label=Pad%20Count)
![Via Count](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fyork-fs.github.io%2Fcharger-distribution%2Finfo.json&query=%24.via_count&label=Via%20Count)
![ERC Status](https://img.shields.io/endpoint?url=https%3A%2F%2Fyork-fs.github.io%2Fcharger-distribution%2Ferc.json)
![DRC Status](https://img.shields.io/endpoint?url=https%3A%2F%2Fyork-fs.github.io%2Fcharger-distribution%2Fdrc.json)

The charger distribution board lives in the charging box and interfaces with the TSAC distribution via a 23-pin AMPSEAL
connector.

[Latest Release](https://github.com/york-fs/charger-distribution/releases/latest)
[Interactive BOM](https://york-fs.github.io/charger-distribution/ibom.html)

![Render Preview](https://york-fs.github.io/charger-distribution/render.jpg)

## Cloning

A recursive clone must be used to download the `kicad-library` repository:

    git clone --recursive https://github.com/york-fs/charger-distribution.git
