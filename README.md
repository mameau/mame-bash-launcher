# mame-bash-launcher
profile launcher for PCs in MAME

my profiled launcher for MAME computers, this was built for my use

it wont setup the space for you

check `settings/general` for basic setup info

```
MAMEBASE=${HOME}/games/emulator-mame
PROFILES=./profiles
MAMELOCAL=/mnt/mame-media
NVRAMPATH=${MAMELOCAL}/nvram
FLOPPATH=${MAMELOCAL}/floppies
HDDPATH=${MAMELOCAL}/hdd
CDPATH=${MAMELOCAL}/cdrom
```

check one of the `profiles` for an example on how to set one up

layout
```
machines/
slots/
profiles/
settings
./rmame
```

running
```
./rmame win95
```

