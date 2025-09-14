# Localization Keys Displayed Instead of Content

## Description

The schedule page displays raw localization keys instead of properly translated text content. Users see technical translation keys like `olessons.title.schedule` instead of readable text.

## Observed Issues

- Page title shows: `olessons.title.schedule`
- Warning message shows: `olessons.warning.no_schedule_title`  
- Description shows: `olessons.warning.no_schedule_desc`
- Navigation buttons show: `olessons.action.prev_week` and `olessons.button.next_week`

## Expected Behavior

All text elements should display properly localized content in the user's selected language instead of raw translation keys.

## Environment

- **URL:** www.bilimclass.kz/2025/schedule/
- **Date:** September 9, 2025
- **Browser:** Firefox
  
## Priority

**High** - This affects user experience across multiple languages and makes the interface unusable.

## Additional Notes

This appears to be a widespread localization system failure affecting the entire schedule page functionality.
