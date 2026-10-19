# UniDock privacy

This build has no accounts, analytics, advertising SDK, crash uploader, update
checker, or app-managed background network requests.

Notes, reminders, preferences, and a local startup/graphics diagnostic log stay
on this PC. The app reads Windows media-session metadata and artwork to display
and control the current player. The Sound widget reads and changes the selected
Windows audio output's volume and mute state.

File-shelf entries reference files you drop onto the app. Removing a shelf
reference does not delete the original. Copy and paste only access the clipboard
when you request those actions; the app does not collect clipboard history.

Choosing Browser opens a website in your default browser. Apps launched from
UniDock, Windows services, your browser, and your media player have their own
network behavior and privacy policies.

Data is normally stored in `%LOCALAPPDATA%\UniDock`. Open the data folder
from the app's context menu. Uninstall preserves notes and reminders. To remove
them, exit the app and remove that folder yourself.

Existing development-build users may continue using their original
`%LOCALAPPDATA%\NotchDock` folder so their notes and preferences stay available.

Support reports are manual. Avoid posting notes, reminders, media history,
personal file paths, or unreviewed screenshots in public bug reports.
