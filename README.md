# Q-Sys-Designs
A collection of Q-Sys Design files

Free to use for public, private or commercial purposes under an MIT licence

## Art-Net Lighting Controller

A channel based lighting desk built in Q-Sys to send Art-Net messages. 

![Art-Net Lighting Controller](https://github.com/spiraltechnica/Q-Sys-Designs/blob/main/Art-Net%20Lighting%20Controller/ArtNetLightingController.png)

Art-Net messaging code originally based of off code from https://github.com/locimation/qsys-plugins by Locimation

## DateTime Picker

A datetime picker implemented for the QSC Q-SYS platform, providing a customizable calendar interface for selecting dates and times.

![DateTime Picker](https://raw.githubusercontent.com/spiraltechnica/Q-Sys-Designs/main/DateTime%20Picker/datetime%20picker.png)

Features include:

- 12-hour clock format with AM/PM support.
- Uses system clock to determine date and time.
- Interactive selection of day, hour, minute, and second.
- Navigation between months and years using next and previous month buttons.
- Display of days from the previous and next months.
- Highlighting of the currently selected day.
- "Now" function to select the current day and time when triggered.
- ISO 8601 support: "DateTimeInput" text field can accept ISO 8601 formatted dates, with output text fields in both human-readable and ISO 8601 formats.
- Color customization for days from the current, previous, and next months as variables in the Text Controller lua code file.

Made in Q-SYS Designer 9.4.5 LTS
