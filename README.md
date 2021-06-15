# WanderingBundler
Adds bundles (with loot!) to the Wandering Trader's offers for Minecraft 1.17.

The bundles are filled at random from six themed loot tables: Food, candles, fireworks, caving, deep diving, and plants. There is some rare loot such as wither roses and spore blossoms and the Heart of the Sea, but not in quantities that would break the game. Also allows more opportunities to obtain tedious items such as sponges and calcite (which can only currently be obtained by mining a geode!). The loot tables can be edited, and input/feedback/ideas are greatly appreciated!

!!!IMPORTANT NOTE!!!

IF YOU ARE USING THIS WITH VANILLA TWEAKS' "WANDERING TRADES" BLOCK TRADES DATAPACK:
If you experience issues you must edit the file in Wandering Bundler / data / functions / bundle_sales / functions / add_bundle_trade
Comment out (with "#") the first set of commands, and remove the "#" from the second set of commands. This will force this pack to wait until Vanilla Tweaks finishes doing far more math than it needs to in order to add its trades before adding the bundle trade.
