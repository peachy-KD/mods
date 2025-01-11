## Unleashed Style Physics v1.9.9c
- corrected directory listing from the previous release
- Modern Sonic: hurdle jump (fast short hop) edited again, should appear smoother than previous versions
  - flying time: 0.1 → 0.01
  - jump velocity: 12 → 8.1
  - jump height limit: 0.8 → 1.2 (.exe default)
  - fall velocity: 5 → 5.3
- Classic Sonic: air max speed reduced (12 → 9)
- [misc] Modern Sonic prototype physics: corrected underwater jump height (17 → 19)
- [misc] internally stated more of the physics settings; may be useful if you would like to edit them

Hope you have a great 2025!

## Unleashed Style Physics v1.9.9a
- Modern Sonic: swapped the "alternate" Generations physics for a take on the Unleashed Preview Build's (select "Prototype" in the options to use this set); some changes include:
  - higher jump (3D 17 → 18, 2D 17 → 19)
  - higher air acceleration & deceleration rates in 2D (accel. 1.2 → 2, decel. 0.2 → 1)
  - slower forward Drift acceleration (2 → 1.2)
  - slower Light Speed Dash (min. speed 50 → 30, max. 80 → 60)
  - when Boosting, Ring Energy depletes slightly more at first (4 → 5), but slightly less over time (6 → 5)
  - Drifting generates very slightly more Ring Energy (7 → ~7.5)
  - Air Boost drops faster (gravity rate 0.5 → 1, levitation time 1 → 0.1)
  - Wall Jump is faster (front force 15 → 21.4), but requires more speed to start (border -8 → -15)
  - Boost steers easier (side decrease force 80 → 10)
  - Boost and Stomping are "stronger" (Boost strength 200 → 5000, Stomping 200 → 1000). I don't know what this does
- Modern Sonic: hurdle jump velocity increased (10 → 12 [.exe default])
 
## Unleashed Style Physics v1.9.9
- alternate Modern physics: added a Super Sonic speed param that was accidentally missed before
  - Super Sonic 2D "MaxVelocityBasis": 145 → 60.0997
- Classic Sonic: High Speed Shoes & Pink Spikes use .exe default handling values
  - acceleration using High Speed: +4 → +25
  - High Speed time reduced: 15 → 5
  - acceleration using Spikes: 5.3 → 7
  - Spikes max speed relative to standard: 65% → 100%
- [misc] re-organized and re-worded settings

## Unleashed Style Physics v1.9.8
- Modern Sonic: Hurdle Jump is less floaty
  - jump velocity: 9 → 10
  - height limit: 0.9 → 0.8
  - fall velocity: 2.3 → 5
- Classic Sonic: set air acceleration values to same as they are in final game's "low speed" mode - controls closer to vanilla now & less sensitive than in recent versions of this mod
  - acceleration rate: 3 → 2.5
  - deceleration rate: 0.3 → 0.53
  - brake rate: 0.6 → 0.82

## Unleashed Style Physics v1.9.7
- adjusted mod to use appended archive support that was introduced in HMM 7.11 (filesize is reduced and potential compatibility with other mods is increased)
- Unleashed Project support re-implemented. The following changes were made:
  - removed redundant physics overrides for Sonic
  - Bobsleigh in Cool Edge depletes less Ring Energy when Boosting (33.6 → 15)
- Classic and Modern Sonic's modified physics can now be toggled off
- Modern Sonic: new config option "Alternate" added to use a variation on Generations physics settings
- [misc] elaborated more on Classic's changes in this mod in "about2.txt"

## Unleashed Style Physics v1.9.6
- set "RingDropAdditionalNum" back to .exe default value (0 → 10)
- Classic Sonic: air decel rate decreased slightly (1 → 0.86), air brake rate increased slightly (0.7 → 1.08)
- Modern Sonic: Drift 'low speed' mode while boarding effectively disabled
- other adjustments

## Unleashed Style Physics v1.9.5
- Classic Sonic: air decel rate increased (0.4 → 1)
- Classic Sonic: air brake rate slightly decreased (1 → 0.7)
- removed more overrides for Sonic during Egg Dragoon and Silver boss fights
- removed unnecessary/redundant files (White Space overrides, Seaside Hill M5 overrides)

## Unleashed Style Physics v1.9.4
- Classic Sonic: slope stand ability set to Generations value (60 → 10) (fixes an issue where Sonic can clip into the wall in one path on Seaside Hill 1)
- underwater physics adjusted:
  - gravity scale: 0.27 → 0.65 (.exe default value);
  - Jump- and Homing Attack-related params set to be same as they are in 2D outside water;
  - "PadInputForceCoeffInAir": 0.6 → 1 (.exe default value)
- Modern Sonic: Hurdle Jump/short hop parameters unique to Generations adjusted, based directly on .exe default values:
  - rise velocity: 12 → 9 (reduced by 25%);
  - height limit: 1.2 → 0.9 (reduced by 25%);
  - flying time: 0.4 → 0.1 (reduced by 75%);
  - fall velocity: 9.2 → 2.3 (reduced by 75%)
- Classic Sonic: Spin Attack rebound set back to Generations final value (17.5 → 14.7)
- removed more redundant parameter settings
- Classic Sonic: set more parameters to their Generations final values

## Unleashed Style Physics v1.9.3
- Ring Energy increase set to base Unleashed value (0.04 → 0.02)
- Classic Sonic: aerial handling adjusted for Metal Sonic fight

## Unleashed Style Physics v1.9.2
- Classic Sonic: fixed a White Space parameter not getting set
- Modern Sonic: fixed a parameter getting set to Classic Sonic's value

## Unleashed Style Physics v1.9.1
- Classic Sonic: handling based (mostly) on Generations final Classic Sonic (again)

## Unleashed Style Physics v1.9
- Modern Sonic: Hurdle Jump/short hop set approximately to Generations final values
- Classic Sonic: handling based on Unleashed Sonic
