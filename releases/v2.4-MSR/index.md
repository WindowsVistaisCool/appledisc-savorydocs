# v2.4-MSR SavoryBot - Application system revamp
## Bug Fixes/Updates
- Change verify to v3 (add button)
- More organization of the code
- Change IGN to go through `hystats.util.toUUID` for the `skycrypt` URL and back through `hystats.util.toName` for the embed field

## Additions
- Add buttons for applications so moderators can accept applications directly.

## Deletions
- Remove `=app accept` and `=app deny` in favor of the new buttons.
- Remove the `skycrypt` parameter in the `/apply` slash command because the IGN can be used in the link.

## Unfixed issues
- Add namemc/verification update (#11)
- More moderation tools (#32)

## Future plans
- Add cogs for v2.5 release (`commandListener.py` and `main.py` are still way too messy)
- Add interaction games
- Add more features from hypixel API
- Make functionality for `/staffmenu` and `/usermenu`
- Remove the `=app` command entirely and include a button on the application message itself for deleting applications
- v3.0

### Notes:
This is a smaller release and there are a few bugs. There aren't that many new features, but hopefully, the next release will include the menu functionality.
