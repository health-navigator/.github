## Description
This feature adds the ability to generate a daily wisdom quote for users. This includes a new quote generator function and endpoint that will provide a different quote to users each day.

## Changes
- Added `quoteGenerator.js` in `src/utils` for generating random wisdom quotes.
- Created a new route `api/quote/daily` which uses the quote generator to send a daily wisdom quote.
- Updated the user dashboard component to display the daily quote.

## Testing
New unit and integration tests written and passed successfully. Manual tests in local dev environment yielded expected results / No changes to the existing tests were required for this feature.

## Background Context
Implemented a random selection algorithm for the Daily Wisdom feature in `quoteGenerator.js`. This solution provides an efficient and scalable way to provide different wisdom quotes to users each day. Considered other algorithms but chose this for its simplicity and performance benefits. Potential trade-off could be repetitiveness of quotes if the database isn't large enough.

## Screenshots
(in GitHub, you can directly paste screenshots into most text fields. To do this, simply press Ctrl + V (or Command + V on Mac) where you'd like the screenshot to appear in the text. GitHub will automatically upload and embed the image for you)
![image](https://github.com/health-navigator/test/assets/139250775/aeaa096c-fdff-4465-bb52-428c653ad7c4)

## Related Tasks
- [Task #11: Single Source of Truth + Kanban board for Tech](https://www.notion.so/Single-Source-of-Truth-Kanban-board-for-Tech-b27ef45417394885b94c009b041afaec?pvs=4)
- [Task #73: DSEC Terraform](https://www.notion.so/Setup-Notion-97993643cf6f49c393af4d77e05f014a?pvs=21)

##
Resolves [#42](https://www.notion.so/c492efa8c6f9461a9228890eb7f569cf?pvs=21)
