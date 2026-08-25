# OrangeFox for Ulefone Power Armor 18T

Unofficial OrangeFox build workflow for:

- Ulefone Power Armor 18T
- Ulefone Power Armor 18T Ultra

The workflow reuses the device trees maintained in:

- https://github.com/Mietel/Power_Armor_18T
- https://github.com/Mietel/Power_Armor_18T_Ultra

## Build

Open **Actions**, select **OrangeFox Build**, choose a device, and run it.
The workflow uses the OrangeFox `fox_14.1` manifest and builds the recovery
as a boot image because both device trees use `BOARD_USES_RECOVERY_AS_BOOT`.

This is an unofficial build. Test with `fastboot boot` first and keep the
matching stock boot image available for recovery.
