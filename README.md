# hr-scripts

## Dependencies
* Babashka
* GUM
* [Bamboodle](https://github.com/sw1nn/bamboodle.git)

## How to use

* Add an entry to unix password store for <username>/juxtpro.bamboohr.com
* Execute `bb time_off.bb`
* View your timesheet or add days for a project between a range.

## How it currently works

* **Will** ignore weekends
* **WON't** ignore booked holidays
* Only works for the current month

## Future Work

* Grab the juxt.land functionality for deciding appropiate dates to fill in (half days required)
* Make projects with task ids work
