# WanderingBundler
Adds bundles (with loot!) to the Wandering Trader's offers for Minecraft 1.19.

The bundles are filled at random from six themed loot tables: Food, candles, fireworks, caving, deep diving, and plants. There is some rare loot such as wither roses and spore blossoms and the Heart of the Sea, but not in quantities that would break the game. Also allows more opportunities to obtain tedious items such as sponges and calcite (which can only currently be obtained by mining a geode!). The loot tables can be edited, and input/feedback/ideas are greatly appreciated!

CONFIGURING THIS PACK:

By default, the Wandering Trader will always have a bundle in his trade offers. However, if you would like him to offer the bundle less often, you can configure this to any percentage you'd like. Do this with the command "/scoreboard players set bundler.chance bundler.chance xx" (place the percentage likelihood you would like in place of the "xx"). For example, to have the Wandering Trader offer a bundle 50% of the time, run the command "/scoreboard players set bundler.chance bundler.chance 50". Or, for two out of three Wandering Traders to offer a bundle, run "/scoreboard players set bundler.chance bundler.chance 66". In a future release I intend to learn how to have these commands run from a book.

!!!IMPORTANT NOTE!!!

IF YOU ARE USING THIS WITH VANILLA TWEAKS' "WANDERING TRADES" BLOCK TRADES DATAPACK:
If you experience issues you must edit the file in Wandering Bundler / data / functions / bundle_sales / functions / add_bundle_trade
Comment out (with "#") the first set of commands, and remove the "#" from the second set of commands. This will force this pack to wait until Vanilla Tweaks finishes doing far more math than it needs to in order to add its trades before adding the bundle trade.
