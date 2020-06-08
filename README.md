# Blues-Unboxing-3
*Blue's Unboxing 3 is a complete rewrite of Blue's Unboxing 2. This addon allows players to purchase keys and crates and open those crates just like in CS:GO with no config files required, all configuration is done easily in a sleek in-game menu.*
**Please ensure you have installed the [Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=1369926934&searchtext=blue%27s+unboxing+3) content.**

## Credits
* CODE BLUE - Programming, sound, concept.
* Atlas - UI Layout and concept/design
* doesNootCompute (Vloxan) - Helping test and make sure things are all good
* Danny - Helping test a lot of things and suggesting ideas during development.
* freemmaann - Handled workshop stuff due to an issue my end. Thanks <3

## Features
* Easy to use
* Clean, modern UI completely with sleek animations.
* In-game editors for all item types!
* Admin menu to see and edit other peoples inventories.
* Supported item types: Points (1 and 2), Pointshop Items (1 and 2), DarkRP, entities, weapons, cases, keys and custom Lua.
* Custom LUA items execute custom LUA when the items are unboxed/used allowing for all sorts of items (and integrating custom addons with unboxing)
* Optimized
* Preview cases before purchasing
* MySQL and SQLite support.
* Random case drops with chances, so not everyone has to get a crate each time its dropped
* Keys and cases are treated as items now, meaning you can unbox keys and crates from other crates.
* Keys are now able to open multiple cases, meaning you can have a "Christmas Series" and unlock all of them to save having a bunch of keys.
* Items now have an option to be rank restricted, by doing this you restrict items to be used and sold only by people of that rank, this makes it much better for donation setups as you can restrict it to donator only when purchasing etc.
* Console commands for wiping inventories, giving out items to all or 1 players and a few more so it works with Prometheus and GExtention.
* Icon editors work like blue's decals. You can use Custom images or models for any icons, no more default icons!
* Super easier to understand chance system for easy configuration.
* Supports multiple currencies, including custom.
* Easy to expand on, so you can customize it to how you want.
* Community Market for items (Coming soon, want to release without it first)

## Functionality

### UI
With a brand new UI designed by Atlast, aimed to steer away from CS:GO, unboxing in Garry's Mod is now easy for both server owners and players!

### In-Game Case Editor
A big change from Blue's Unboxing 2 is that all case editors are now in-game meaning no more 1000 line configs! Only those with the ranks assigned in the config file can use the in-game case editor. To access the in-game editor, just open up the unboxing UI and select the configuration box. For a tutorial regarding creating cases filled with items, please visit the 'Media' section below.

### Customisable Icons
*Please note that when I refer to 'items' in this section, you can also use the same technique with case/keys/entities/weapons/etc*
Want your server to stand out from other servers running Blue's Unboxing 3? Now with three ways to add icons to your cases/keys/items, you can easily make your unboxing screen stand out from the crowd!

#### Model
 To use a model inside of Garry's Mod to represent your items, simply find the items actual model (you might have to dig around a bit in the spawn menu) and paste it into the field called 'Model or ID' on the item creation screen as well as selecting the 'Model' option in the drop-down box.

### Imgur ID
 To use an image to represent your items, upload that image to http://imgur.com by selecting 'New post' in the top left corner. Once uploaded, right click the image and select 'Open image in new tab. Ensuring the newly opened tab URL has 'i.' in front of the 'imgur.com' then copy the text after the 'i.imgur.com/' and before '.jpg'. Paste that ID into the field called 'Model or ID' and make sure you select the 'Imgur ID' drop-down box above.

### Default Icon
If you want to use a premade icon for the items. Simply select the option in the drop-down box titled 'Default Weapon Icon'.

## FAQ

### Do I need the workshop for this?
> Unfortunately yes, this addon uses some custom sounds, fonts and materials.

### Does this support MySQL?
> Yes! Unlike the original, this now has full MySQL support.

### Can I use this with donation addons?
> Yes, this has full Lua exposure as well as console commands


