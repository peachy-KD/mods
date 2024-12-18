## Unleashed Style Physics v1.9.8
- Modern Sonic - Hurdle Jump is less floaty
  - Velocity - 9 → 10
  - LimitHeight - 0.9 → 0.8
  - FallVelocity - 2.3 → 5
- Classic Sonic - set air acceleration values to same as they are in final game's "low speed" mode - controls closer to vanilla now & less sensitive than in recent versions of this mod
  - AccelRate - 3 → 2.5
  - DecelRate - 0.3 → 0.53
  - BrakeRate - 0.6 → 0.82

## Unleashed Style Physics v1.9.7d0
- Modern Sonic - fixed Light Speed Dash speed for "Alternate" physics setting (3D speed set to same as 2D like in Unleashed)
- Modern Sonic - fixed 3D Homing Attack air drag for "Alternate" setting (3.6 → 1)
- (misc) Modern Sonic - power-ups (High Speed, Invincible) have correct duration

## Unleashed Style Physics v1.9.7d
- Modern Sonic - new config option added to use a variation on Generations physics settings; when enabled, handling will be similar to the original game, but with tweaks similar to the ones made to Classic Sonic for this mod (e.g. longer Jump Dash, slightly less friction, air acceleration adjustments, etc.). Basically, like with Classic Sonic, the concept is "what if you used this physics file in Unleashed?"

## Unleashed Style Physics v1.9.7c-0
- Classic and Modern Sonic's modified physics can now be toggled off
- (misc) elaborated more on Classic's changes in this mod in "about2.txt"

## Unleashed Style Physics v1.9.7c
- Modern Sonic - reverted "DriftFinishVelocity" back to default (0 → 20) (leaving this Generations-specific parameter alone actually seemed to be more accurate [or at least handle slightly more smoothly], oops!)
- Classic Sonic - small adjustments

## Unleashed Style Physics v1.9.7b
- Modern Sonic - "DriftFinishVelocity" nullified (20 → 0)
- Unleashed Project Cool Edge bobsleigh handling reverted to original UP release's

## Unleashed Style Physics v1.9.7a
- rounding adjustments for certain parameters
- removed some unnecessary files

## Unleashed Style Physics v1.9.7
- adjusted mod to use appended archive support that was introduced in HMM 7.11 (filesize is reduced and potential compatibility with other mods is increased)
- Unleashed Project support re-implemented. The following changes were made:
  - removed redundant physics overrides for Sonic
  - Bobsleigh in Cool Edge depletes less Ring Energy when Boosting (33.6 → 18)

## Unleashed Style Physics v1.9.6
- set "RingDropAdditionalNum" back to default value (0 → 10)
- Classic Sonic - air decel rate decreased slightly (1 → 0.86), air brake rate increased slightly (0.7 → 1.08)
- Modern Sonic - Drift 'low speed' mode while boarding effectively disabled
- other adjustments

## Unleashed Style Physics v1.9.5a
- fixed Homing Attack settings being incorrectly set from init 1.9.5 release

## Unleashed Style Physics v1.9.5
- Classic Sonic - air decel rate increased (0.4 → 1)
- Classic Sonic - air brake rate slightly decreased (1 → 0.7)
- removed more overrides for Sonic during Egg Dragoon and Silver boss fights
- removed unnecessary/redundant files (White Space overrides, Seaside Hill M5 overrides)

## Unleashed Style Physics v1.9.4b
- set Boost multipliers at Lv0 back to original Unleashed/Generations values (1.5 3D, 1.6 2D → 1.4 3D, 1.5 2D)

## Unleashed Style Physics v1.9.4
- Classic Sonic - slope stand ability set to Generations value (60 → 10) (fixes an issue where Sonic can clip into the wall in one path on Seaside Hill 1)
- underwater physics adjusted:
  - gravity scale - 0.27 → 0.65 (default value);
  - Jump- and Homing Attack-related params set to be same as they are in 2D outside water;
  - "PadInputForceCoeffInAir" - 0.6 → 1 (default value)
- Modern Sonic - Hurdle Jump/short hop parameters unique to Generations adjusted, based directly on default values:
  - rise velocity - 12 → 9 (reduced by 25%);
  - height limit - 1.2 → 0.9 (reduced by 25%);
  - flying time - 0.4 → 0.1 (reduced by 75%);
  - fall velocity - 9.2 → 2.3 (reduced by 75%)
- Classic Sonic - Spin Attack rebound set back to Generations final value (17.5 → 14.7)
- removed more redundant parameter settings
- Classic Sonic - set more parameters to their Generations final values

## Unleashed Style Physics v1.9.3
- Chaos Energy gain by Rings set to base Unleashed value (0.03 → 0.02)
- Classic Sonic - aerial handling adjusted for Metal Sonic fight

## Unleashed Style Physics v1.9.2
- Classic Sonic - fixed a White Space parameter not getting set
- Modern Sonic - fixed a parameter getting set to Classic Sonic's value

## Unleashed Style Physics v1.9.1
- Classic Sonic - handling based (mostly) on Generations final Classic Sonic (again)

## Unleashed Style Physics v1.9
- Modern Sonic - Hurdle Jump/short hop set approximately to Generations final values
- Classic Sonic - handling based on Unleashed Sonic
