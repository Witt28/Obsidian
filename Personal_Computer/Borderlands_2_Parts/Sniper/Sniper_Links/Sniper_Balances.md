## Weapon Balances

The Weapon Balance defines what parts a certain weapon can have. Balances themselves do not affect stats, but are they very important for the actual generation of weapons.

## Weapon Type Definitions

Like the name might suggest, the definition essentially defines all the unique properties of each weapon type. There are 5 non-unique definitions, one per manufacturer.

#### Dahl

×2 Crit Damage  
**On Zoom:**  
+2 Burst Count  
+3 Impulse Accuracy  
÷2 Min Accuracy  
−0.8 Weapon Spread

#### Hyperion (BL2)

+12 Accuracy Regen  
×2 Crit Damage  
−2 Max Accuracy  
+60% Projectile Speed  
**On Zoom:**  
−5.5 Accuracy Regen  
−3 Max Accuracy  
÷2 Min Accuracy  
−0.8 Weapon Spread

#### Hyperion (TPS)

+12 Accuracy Regen  
×2 Crit Damage  
−2 Max Accuracy  
+60% Projectile Speed  
**On Zoom:**  
−5.5 Accuracy Regen  
−1 Max Accuracy  
÷2 Min Accuracy  
−0.8 Weapon Spread

#### Jakobs

+2 Accuracy Regen  
×2.6 Crit Damage  
+2 Max Accuracy  
×1.3 Projectile Speed  
**On Zoom:**  
÷2 Min Accuracy  
−0.7 Weapon Spread

#### Maliwan

×2 Crit Damage  
+25% Status Chance Modifier  
+0.2 Status Effect Damage  
**On Zoom:**  
÷2 Min Accuracy  
−0.8 Weapon Spread

#### Vladof

×2 Crit Damage  
**On Zoom:**  
÷2 Min Accuracy  
−0.7 Weapon Spread

Definitions are also very important if you’re trying to calculate exact stats.

Expand To start with, they define the base values used by all stats stored on the weapon.

<table><thead><tr><th></th><th>Dahl</th><th>Hyperion</th><th>Jakobs</th><th>Maliwan</th><th>Vladof</th><th>Hot Mama<sup>1</sup></th></tr></thead><tbody><tr><th>Burst Impulse Scale</th><td>+0.1</td><td>0</td><td>0</td><td>0</td><td>0</td><td>0</td></tr><tr><th>Burst Interval Scale</th><td>+0.8</td><td>+0.8</td><td>+0.15</td><td>+0.8</td><td>+0.8</td><td>+0.15</td></tr><tr><th>Fire Interval</th><td>+0.15</td><td>+1</td><td>+0.3</td><td>+0.7</td><td>+0.25</td><td>+0.3</td></tr><tr><th>Impulse Accuracy</th><td>+7</td><td>−3.5</td><td>+9</td><td>+8</td><td>+4</td><td>+9</td></tr><tr><th>Mag Size</th><td>+6</td><td>+5</td><td>+6</td><td>+5</td><td>+8</td><td>+6</td></tr><tr><th>Projectile Count</th><td>+1</td><td>+1</td><td>+1</td><td>+1</td><td>+1</td><td>+1</td></tr><tr><th>Reload Time</th><td>+4</td><td>+4</td><td>+5</td><td>+4</td><td>+4</td><td>+5</td></tr><tr><th>Shot Cost</th><td>+1</td><td>+1</td><td>+1</td><td>+1</td><td>+1</td><td>+1</td></tr><tr><th>Status Chance Base</th><td>+1.5</td><td>+1.5</td><td>+1.5</td><td>+1.5</td><td>+1.5</td><td>+1.5</td></tr><tr><th>Status Effect Damage</th><td>+8×β</td><td>+8×β</td><td>+8×β</td><td>+8×β</td><td>+8×β</td><td>+8×β</td></tr><tr><th>Weapon Damage</th><td>+25.6×β</td><td>+29.6×β</td><td>+32×β</td><td>+26.4×β</td><td>+24×β</td><td>+32×β</td></tr><tr><th>Weapon Spread</th><td>+1</td><td>+0.8</td><td>+0.8</td><td>+1</td><td>+1</td><td>+0.8</td></tr><tr><th>Zoom FOV</th><td>+36</td><td>+30</td><td>+32</td><td>+34</td><td>+38</td><td>+32</td></tr></tbody><tfoot><tr><td colspan="7">This table is not exhaustive.</td></tr></tfoot></table>

They also define all grade bonuses, and how exactly they get converted into standard bonuses.

<table><thead><tr><th></th><th>Dahl</th><th>Hyperion</th><th>Jakobs</th><th>Maliwan</th><th>Vladof</th><th>Hot Mama<sup>1</sup></th></tr></thead><tbody><tr><th>Accuracy Regen</th><td colspan="1">0 +0.05</td><td colspan="1">0 −0.05</td><td colspan="4">0 +0.05</td></tr><tr><th>Burst Impulse Scale</th><td colspan="6">0 −0.05</td></tr><tr><th>Fire Interval</th><td colspan="6">0 −0.03</td></tr><tr><th>Impulse Accuracy</th><td colspan="1">0 −0.05</td><td colspan="1">0 +0.05</td><td colspan="4">0 −0.05</td></tr><tr><th>Mag Size</th><td colspan="6">0 +0.05</td></tr><tr><th>Max Accuracy</th><td colspan="6">0 −0.05</td></tr><tr><th>Min Accuracy</th><td colspan="6">0 −0.05</td></tr><tr><th>Reload Time</th><td colspan="6">0 −0.05</td></tr><tr><th>Weapon Damage</th><td colspan="6">0 +0.03</td></tr><tr><th>Weapon Spread</th><td colspan="6">0 −0.05</td></tr><tr><th>Zoom FOV</th><td colspan="6">0 −0.13</td></tr></tbody></table>

<sup>1</sup>The Hot Mama uses it’s own unique definition, listed in this section to help you calculate it’s stats.