## Triode-Car

[BPI-TriodeCar is a product designed for education on entry-level engineering](https://www.aliexpress.com/item/1005002522563487.html?spm=2114.12010612.8148356.23.4c7c599eTzy5vr)

## Note

This is only a beta version

You can see more information here http://wiki.banana-pi.org/BPI_Triode-Car_kit

Here are some of our videos  

Triode Car #1 - A Beginning to Something Big https://www.youtube.com/watch?v=qcR-Haovyr4

Triode Car #2 - Installing Colorful Resistors! https://www.youtube.com/watch?v=z6adIa8id5Y

## Usage

### ``||CarDirection||``

Use the ``||CarDirection||`` blocks to control the car

```blocks 
basic.forever(() => {
    triodecar.CarDirection(triodecar.direction.foward)
})
```

### ``||ReadLDR||``

Use the ``||ReadLDR||`` blocks to control the car

```blocks 
basic.forever(() => {
    serial.writeLine("" + (triodecar.ReadLDR(triodecar.Patrol.PatrolLeft)))
})
```

<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
