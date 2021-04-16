## Triode-Car

[BPI-TriodeCar is a product designed for education on entry-level engineering](https://es.aliexpress.com/item/1005002490348201.html?spm=5261.ProductManageOnline.0.0.21634edftI1T4f)

## Note

This is only a beta version

## Usage

### ``CarDirection``

Use the ``CarDirection`` blocks to control the car

```blocks 
basic.forever(() => {
    triodecar.CarDirection(triodecar.direction.foward)
})
```

### ``readPatrol``

Use the ``readPatrol`` blocks to control the car

```blocks 
basic.forever(() => {
    serial.writeLine("" + (triodecar.readPatrol(triodecar.Patrol.PatrolLeft)))
})
```
## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/BPI-STEAM/pxt-triodecar** and import

## Edit this project ![Build status badge](https://github.com/BPI-STEAM/pxt-triodecar/workflows/MakeCode/badge.svg)

To edit this repository in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/BPI-STEAM/pxt-triodecar** and click import

#### Metadata (used for search, rendering)

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
