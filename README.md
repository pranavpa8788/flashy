# Logable

## Essential

* Create logs
    * Based on timers

    * Query at the end of timer for units (specified in config) completed
    * Query if you want to skip (default should be no)

    * Modifications (edit logs)

    * View statistics

* Reminders
    * Active checker: if inactive, stop logging with gtk (pyqt) warning popup on screen
    * Remind if the threshold hour has been reached (argument at beginning of command?)

* Auto timetable
    * Suggestions, with warnings

    * Priority 
        * Based on classes (casual, urgent, etc which may have parent priority)
        * Graphical preview of timetable

* Ability to set goals in terms of specified unit (example: pages)

## EXTRA

* Attach folders to categories (autostart without arguments)

* Autostart (no args, use prev args with prompt for confirmation first)

* Debug flag (logging module)

* Show work left in stats

* Keep number of args less and simple (more finetuning in config?)

* Calculate avg time taken for chunk (later display in time table)

* Use TUI first

* Send to phone function (for timetable, maybe even automatically triggered)

* Automatically adjust suggestions based on events of that day's schedule
