## ![Birthday Calendar Extractor for Facebook](public/icons/icon.48.png) [Birthday Calendar Extractor for Facebook](https://chrome.google.com/webstore/detail/birthday-calendar-extract/imielmggcccenhgncmpjlehemlinhjjo)

This extension helps to create a calendar with all your facebook friends birthdays.

Generated calendar file saved in `ICS` or `CSV` formats.

### Important!
**There is no easy way to remove birthday events from the calendar later!**

At your calendar I suggest creating a new Birthday themed sub-calendar and use it for imports. 

### How to use
Click on extension icon and select on of required formats:
* Generate Google Calendar - ICS is a universal calendar format used by Microsoft Outlook, Google Calendar, and Apple Calendar.
* Generate Excel file - CSV
* Remove from Google Calendar - Generated file used to remove all already exported birthday events.

At the end of the process file named `birthday-calendar.ics` will be downloaded automatically to your Downloads folder.

Use generated file to export your friends' birthdays to your calendar program.

I suggest creating a new Birthday themed sub-calendar and use it for imports.

###FAQ
Q: I accidentally saved birthdays to my main calendar, how to reverse it?

A: On a format selection screen select "Remove form Google Calendar" and import the generated file to Google Calendar.
### Changelog
2.2.0
- Remove imported events from Google Calendar
- Export as CSV
- Migration to rxjs

2.1.0
- Works with both new and old Facebook.
- Makes ajax requests instead of scrolling birthday page down.
- Using Vue.js to generate pages.
- Fixed issue with missing persons on month joints.

2.0.0
- All the events are recurring now, and will be repeated yearly. 
- Events will appear as 'FREE' instead of 'BUSY'
- Added Share button

1.0.1
- Fixed typos

1.0.0
- All the functionality moved to browser action
- Bug Fix: When Facebook interface set to 'English (UK)' calendar generated wrong dates.
- Supported facebook languages: English (UK), English (US), Русский, Українська, עברית

### Things to improve
It is open source, feel free to check it here: https://github.com/zagushka/birthday-calendar-extractor
* Option to edit birthdays before generating the calendar file.
* Leap years February 29 birthdays.
* Get rid of [luxon](https://moment.github.io/luxon/) to reduce bundle size.
* Direct export to Google Calendar.

