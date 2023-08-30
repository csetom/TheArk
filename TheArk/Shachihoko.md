---
tags: Encounters
---
!Shachihoko

Tiger-carp hybrid

!!Hit Points: <input size=1 >/24

### Speed:30
|Guard|18|
|Resolve|17|
|Toughness|15|

!!Atributes:
|Might|6|2d10|
|Movement|6|2d10|
|Protection|4|2d6|

!!Attacks
*Might (+2d8) vs Guard

```
$VAR1 = [
          {
            'properties' => {
                              'reach' => 'Reach',
                              'forceful' => 'Forceful'
                            },
            'melee' => bless( do{\(my $o = 1)}, 'JSON::PP::Boolean' ),
            'name' => 'Glaive',
            'range' => 0,
            'banes' => {
                         'knockdown' => 'Knockdown',
                         'forced move' => 'Forced Move',
                         'immobile' => 'Immobile'
                       },
            'wealth' => 2,
            'hands' => 2
          },
          {
            'name' => 'Naginata',
            'properties' => {
                              'reach' => 'Reach',
                              'forceful' => 'Forceful'
                            },
            'melee' => $VAR1->[0]{'melee'},
            'wealth' => 2,
            'hands' => 2,
            'range' => 0,
            'banes' => {
                         'immobile' => 'Immobile',
                         'forced move' => 'Forced Move',
                         'knockdown' => 'Knockdown'
                       }
          }
        ];

```
*Movement (+2d8) vs Guard
**_Range: 50_

!!Feats
***Bane Focus (Fear):** Whenever a damaging attack exceeds the target's defense by 5 or more, you may automatically inflict that bane. When making a bane attack to inflict the chosen bane, you gain advantage 2 on the bane attack roll.
***Damage Resistance I (Precise):** Your defense scores are increased by 3 against the chosen damage type.

_A shachihoko (鯱鉾 or 鯱) or shachi (鯱) is an animal in Japanese folklore with the head of a tiger and the body of a carp. It was believed that this animal could cause the rain to fall, and as such, temples and castles were often adorned with roof ornaments (shibi) crafted in the form of a shachihoko, in order to protect them from fire._

!!Banes
***Demoralized**: _(Resist (minor) ends (Fail x 3 = 1 minute))_
**Might (+2d8) vs. Resolve at Power Level 6
***Disarmed**: _(Instantaneous)_
**Might (+2d8) vs. Guard at Power Level 6
***Disarmed**: _(Instantaneous)_
**Movement (+2d8) vs. Guard at Power Level 6
***Fear**: _(Special)_
**Might (+2d8) vs. Resolve
***Forced Move**: _(Instantaneous)_
**Might (+2d8) vs. Guard at Power Level 6
***Forced Move**: _(Instantaneous)_
**Movement (+2d8) vs. Guard at Power Level 6
***Immobile**: _(Resist ends (special) (Fail x 3 = 1 minute))_
**Might (+2d8) vs. Guard
***Immobile**: _(Resist ends (special) (Fail x 3 = 1 minute))_
**Movement (+2d8) vs. Guard
***Knockdown**: _(Instantaneous)_
**Might (+2d8) vs. Guard
***Knockdown**: _(Instantaneous)_
**Movement (+2d8) vs. Guard
***Nullify**: _(Instantaneous)_
**Protection (+1d10) vs. Resolve at Power Level 4
***Provoked**: _(Resist (minor) ends (Fail x 3 = 1 minute))_
**Might (+2d8) vs. Resolve at Power Level 6
***Silenced**: _(Resist ends (Fail x 3 = 1 minute))_
**Might (+2d8) vs. Toughness
***Slowed**: _(Resist ends (Fail x 3 = 1 minute))_
**Might (+2d8) vs. Guard
***Slowed**: _(Resist ends (Fail x 3 = 1 minute))_
**Movement (+2d8) vs. Guard
***Stunned**: _(Resist ends (Fail x 3 = 1 minute))_
**Might (+2d8) vs. Toughness
!!Boons:
***Absorb Object**
**Movement (+2d8) 
***Aura**
**Movement (+2d8) up to Power Level 6 
***Aura**
**Protection (+1d10) up to Power Level 4 
***Barrier**
**Protection (+1d10) up to Power Level 3 
***Flight**
**Movement (+2d8) up to Power Level 6 
***Haste**
**Movement (+2d8) up to Power Level 6 
***Resistance**
**Movement (+2d8) up to Power Level 5 
***Resistance**
**Protection (+1d10) up to Power Level 3 
***Restoration**
**Protection (+1d10) up to Power Level 4 
***Sustenance**
**Protection (+1d10) up to Power Level 4 
***Telekinesis**
**Movement (+2d8) up to Power Level 5 
***Teleport**
**Movement (+2d8) up to Power Level 5 
