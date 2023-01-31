# Review v0.0.1

Recommendations for review of `cw-native-vesting` v0.0.1 (https://github.com/Pupmos/cw-native-vesting/tree/v0.0.1)

* Compare `tgrade-vesting-account` to `cw-native-vesting`
  * ensure the migration away from tgrade bindings did not have unintended consequences.
  * `tgrade-vesting-account`: https://github.com/confio/poe-contracts/tree/main/contracts/tgrade-vesting-account
* Read over each function, ensuring the implementation does what it says it does, or matches the tgrade implementation roughly 
* Review github release workflow, ensuring that it should generate optimized build artifacts as expected 
* Verify the checksums produced in the `v0.0.1` build: https://github.com/Pupmos/cw-native-vesting/releases/tag/v0.0.1

## Bonus
* If anyone would like to reimplement the multitest suite in a manner compatible with the default cosmwasm runtime, that would be much appreciated.
  * See issue https://github.com/Pupmos/cw-native-vesting/issues/1
