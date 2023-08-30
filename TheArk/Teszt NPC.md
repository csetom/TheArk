---
---
!Daitengu

Most powerful class of tengu, each of whom lives on a separate mountain

!!Hit Points: <input size=1 >/54

### Speed:30
|Guard|27|
|Resolve|28|
|Toughness|28|

!!Atributes:
|Energy|9|d8|
|Might|10|d|
|Will|10|d|

!!Attacks
*Energy (+3d10) vs Guard
**_Range: 75_

*Might (+4d8) vs Guard

``
$VAR1 = [
          {
            'banes' => {
                         'forced move' => 'Forced Move',
                         'knockdown' => 'Knockdown',
                         'immobile' => 'Immobile'
                       },
            'name' => 'Halberd',
            'wealth' => 2,
            'range' => 0,
            'melee' => bless( do{\(my $o = 1)}, 'JSON::PP::Boolean' ),
            'hands' => 2,
            'properties' => {
                              'reach' => 'Reach',
                              'forceful' => 'Forceful'
                            }
          },
          {
            'properties' => {
                              'forceful' => 'Forceful',
                              'precise' => 'Precise'
                            },
            'hands' => 3,
            'melee' => $VAR1->[0]{'melee'},
            'banes' => {
                         'immobile' => 'Immobile',
                         'disarmed' => 'Disarmed',
                         'persistent damage' => 'Persistent Damage'
                       },
            'name' => 'Short Spear',
            'wealth' => 1,
            'range' => 50
          }
        ];

``

!!Feats
***Evasive Footwork:** When you move from a space adjacent to an enemy to another space not adjacent to that enemy, the enemy does not get the usual opportunity attack.
***Multi-Attack Specialist VI:** Reduce the multi-attack disadvantage penalty by 6. Before attacking, you may declare that you are multi-attacking, and must state how many extra attacks (maximum of 1 + half your level, rounded up) you would like to make. ALL of your attacks this round suffer disadvantage equal to 3 times the number of additional attacks you declare (i.e., if you make 2 attacks, you suffer disadvantage 3; 3 attacks suffers disadvantage 6).
***Potent Bane (Stunned):** When a target makes a resist roll to shake off your invocation of the chosen bane, they have disadvantage 1.

_Tengu (天狗, "heavenly dog") are a type of legendary creature found in Japanese folk religion and are also considered a type of Shinto god (kami) or yōkai (supernatural beings). Although they take their name from a dog-like Chinese demon (Tiangou), the tengu were originally thought to take the forms of birds of prey, and they are traditionally depicted with both human and avian characteristics. The earliest tengu were pictured with beaks, but this feature has often been humanized as an unnaturally long nose, which today is widely considered the tengu's defining characteristic in the popular imagination._

!!Banes
***Blinded**: _(Resist ends (Fail x 3 = 1 minute))_
**Energy (+3d10) vs. Guard
***Deafened**: _(Resist ends (Fail x 3 = 1 minute))_
**Energy (+3d10) vs. Toughness
***Demoralized**: _(Resist (minor) ends (Fail x 3 = 1 minute))_
**Energy (+3d10) vs. Resolve at Power Level 8
***Demoralized**: _(Resist (minor) ends (Fail x 3 = 1 minute))_
**Might (+4d8) vs. Resolve at Power Level 8
***Disarmed**: _(Instantaneous)_
**Energy (+3d10) vs. Guard at Power Level 6
***Disarmed**: _(Instantaneous)_
**Might (+4d8) vs. Guard at Power Level 6
***Fear**: _(Special)_
**Might (+4d8) vs. Resolve
***Forced Move**: _(Instantaneous)_
**Energy (+3d10) vs. Guard at Power Level 8
***Forced Move**: _(Instantaneous)_
**Might (+4d8) vs. Guard at Power Level 8
***Immobile**: _(Resist ends (special) (Fail x 3 = 1 minute))_
**Energy (+3d10) vs. Toughness
***Immobile**: _(Resist ends (special) (Fail x 3 = 1 minute))_
**Might (+4d8) vs. Guard
***Knockdown**: _(Instantaneous)_
**Energy (+3d10) vs. Guard
***Knockdown**: _(Instantaneous)_
**Might (+4d8) vs. Guard
***Persistent Damage**: _(Resist ends (Fail x 3 = 1 minute))_
**Energy (+3d10) vs. Guard at Power Level 9
***Provoked**: _(Resist (minor) ends (Fail x 3 = 1 minute))_
**Energy (+3d10) vs. Resolve at Power Level 9
***Provoked**: _(Resist (minor) ends (Fail x 3 = 1 minute))_
**Might (+4d8) vs. Resolve at Power Level 9
***Silenced**: _(Resist ends (Fail x 3 = 1 minute))_
**Might (+4d8) vs. Toughness
***Slowed**: _(Resist ends (Fail x 3 = 1 minute))_
**Energy (+3d10) vs. Guard
***Slowed**: _(Resist ends (Fail x 3 = 1 minute))_
**Might (+4d8) vs. Guard
***Stunned**: _(Resist ends (Fail x 3 = 1 minute))_
**Energy (+3d10) vs. Toughness
***Stunned**: _(Resist ends (Fail x 3 = 1 minute))_
**Might (+4d8) vs. Toughness
!!Boons:
***Aura**
**Energy (+3d10) up to Power Level 8
***Barrier**
**Energy (+3d10) up to Power Level 9
***Light**
**Energy (+3d10) up to Power Level 9
***Resistance**
**Energy (+3d10) up to Power Level 9
***Summon Creature**
**Energy (+3d10) up to Power Level 9
~                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      
~                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      
~                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      
~                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      
~                                                                                                        