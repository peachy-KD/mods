## Unleashed Style Physics v1.9.7a
- Rounding adjustments
  - Sonic no longer gets stuck on Egg Dragoon walls
- removed some unnecessary files from the zip download

## Unleashed Style Physics v1.9.7
- Adjusted mod to use appended archive support that was introduced in HMM 7.11 (filesize is reduced and potential compatibility with other mods is increased)
- Unleashed Project support re-implemented. The following changes were made:
  - removed redundant physics overrides for Sonic
  - Bobsleigh/Board in Cool Edge depletes less Chaos Energy when Boosting (33.6 → 18)

## Unleashed Style Physics v1.9.6
- set "RingDropAdditionalNum" back to default value (0 → 10)
- Modern Sonic - set "DriftFinishVelocity" back to default value (0 → 20)
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

## Unleashed Style Physics v1.9.4c
- set Boost multipliers at Lv0 back to original Unleashed/Generations values (1.5 3D, 1.6 2D → 1.4 3D, 1.5 2D)

## Unleashed Style Physics v1.9.4b
- Classic Sonic - Super Sonic acceleration set back to Generations final value (25 → 10)

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
- Egg Dragoon fight uses Generations final "WallJumpReady" settings
- Removed all Unleashed Project-related files (would recommend going to the mod folder and deleting the "stages_unleashed" folder if it's still present)
- Classic Sonic - handling based on Unleashed Sonic
