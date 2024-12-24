## Unleashed Style Physics v1.9.9
- Alternate Modern physics: added a Super Sonic speed param that was accidentally missed before
  - Super Sonic 2D "MaxVelocityBasis": 145 → 60.0997
- Classic Sonic: High Speed, Pink Spikes use default handling values
  - acceleration using High Speed: +4 → +25
  - acceleration on Spikes: 5.3 → 7
  - Spikes max speed relative to standard: 65% → 100%
- (misc) re-organized and re-worded settings

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
  - Bobsleigh in Cool Edge depletes less Ring Energy when Boosting (33.6 → 18)
- Classic and Modern Sonic's modified physics can now be toggled off
- Modern Sonic: new config option "Alternate" added to use a variation on Generations physics settings; when enabled, handling will be similar to the original game, but with tweaks similar to the ones made to Classic Sonic for this mod (e.g. longer Jump Dash, slightly less friction, air acceleration adjustments, etc.). Basically, like with Classic Sonic, the concept is "what if you used this physics file in Unleashed?"
- (misc) elaborated more on Classic's changes in this mod in "about2.txt"
- (misc) Modern Sonic: power-ups (High Speed, Invincible) have correct duration

## Unleashed Style Physics v1.9.6
- set "RingDropAdditionalNum" back to default value (0 → 10)
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
  - gravity scale: 0.27 → 0.65 (default value);
  - Jump- and Homing Attack-related params set to be same as they are in 2D outside water;
  - "PadInputForceCoeffInAir": 0.6 → 1 (default value)
- Modern Sonic: Hurdle Jump/short hop parameters unique to Generations adjusted, based directly on default values:
  - rise velocity: 12 → 9 (reduced by 25%);
  - height limit: 1.2 → 0.9 (reduced by 25%);
  - flying time: 0.4 → 0.1 (reduced by 75%);
  - fall velocity: 9.2 → 2.3 (reduced by 75%)
- Classic Sonic: Spin Attack rebound set back to Generations final value (17.5 → 14.7)
- removed more redundant parameter settings
- Classic Sonic: set more parameters to their Generations final values

## Unleashed Style Physics v1.9.3
- Boost gain by Rings set to base Unleashed value (0.04 → 0.02)
- Classic Sonic: aerial handling adjusted for Metal Sonic fight

## Unleashed Style Physics v1.9.2
- Classic Sonic: fixed a White Space parameter not getting set
- Modern Sonic: fixed a parameter getting set to Classic Sonic's value

## Unleashed Style Physics v1.9.1
- Classic Sonic: handling based (mostly) on Generations final Classic Sonic (again)

## Unleashed Style Physics v1.9
- Modern Sonic: Hurdle Jump/short hop set approximately to Generations final values
- Classic Sonic: handling based on Unleashed Sonic
