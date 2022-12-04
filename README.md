# EFCReport

A WoW 1.12.1 addon for reporting (E)FC location in Warsong Gulch. 

Forked from  [cubenicke/EFCReport](https://github.com/cubenicke/EFCReport) and made some 
improvements, most notably:

1. Added support for the [RetroWoW](https://retro-wow.org) server.
2. Added the ability to right-click any button to tell your team where you're going.

![efcr](https://user-images.githubusercontent.com/613122/48218786-fc23d980-e38a-11e8-8e8d-20051e61fc4b.PNG)

## Install

1. Download [latest version](https://github.com/Pizzahawaiii/EFCReport/archive/refs/heads/main.zip).
2. Extract the `EFCReport-master` folder into your `<WoW>/Interface/AddOns` directory.
3. Rename the `EFCReport-master` folder to `EFCReport`.

## Use

Left-click a button to tell your team where the EFC is.

Right-click a button to tell your team where you're going yourself.

```
/efcr   - Show/Hide (Is automatically shown in WSG)
/efcr dim - Toggles dimmed look when mouse is out of bounds
/efcr scale [0.00 - 1.00] - Set size of EFCReport frame
```

## Notes

The alliance/horde buttons are flipped around, depending on which side you're fighting
for. The enemy base is always at the top while your own base is at the bottom.

A bit confusingly, the east/west buttons are also flipped depending on your faction to
correctly represent their "position" relative to the other buttons. For example, if
you're playing on the alliance side, your own berserker hut is to the left when you
exit your base (hence the zerk button is on the left). But the button pointing to the
left actually corresponds to east (because the alliance zerk hut is in the east of
the WSG map).

This can be confusing for example when you're running towards your base and you see
the EFC in the far east. They're actually on your right side, but you have to click
the left arrow. The easiest way to deal with this that I found is to always imagine
yourself standing in your base, facing the enemy base.

## Contribute

If you face any problems or have general suggestions, please create 
[an issue](https://github.com/Pizzahawaiii/EFCReport/issues) or contact me in-game.

Any code contributions and improvements are welcome. Just fork the repo and create 
a pull request.

## Authors

- [cubenicke](https://github.com/cubenicke)
- Pizzahawaii @ [RetroWoW](https://retro-wow.org)
