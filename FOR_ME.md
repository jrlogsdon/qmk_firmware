Steps encountered while troubleshooting:
Follow [steps](https://docs.qmk.fm/#/newbs_getting_started) with the caveat
 - don't install qmk as a user, instead at virtual environment level
 - `python3 -m venv .venv` --> `source .venv/bin/activate` --> `python3 -m pip install qmk`
 - Then run `qmk setup`
 - Make the keyboard. For instance, `make moonlander:jlogs` which creates the binary to flash
 - Finally, flash via `qmk flash moonlander_jlogs.bin`


