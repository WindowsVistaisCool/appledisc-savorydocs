# v2.5.2 Semi Stable Patch - Cogs patch 2
## Bug Fixes/Updates
- Update status again
- Change the way cog loading is done
- Changed the `load` function in each cog to `setup`
- Moved checks to their own module

## Additions
- Added a list in the config file for cogs (easy management of what gets loaded or not)

## Deletions
- Remove cog loading from main file

## Unfixed issues
- Conflicting components and slash commands (#56)
- JSON needs to be converted to a mySQL DB (#57)
- Lots (check issues for more info)

## Future plans
- Planned issues (that I'm too lazy to type here)
- Add interaction games
- Add more features from hypixel API
- Remove the `=app` command entirely and include a button on the application message itself for deleting applications
- v3.0

### Notes:
This took way too much time to release, but hopefully the bot is mostly stable at this point.
