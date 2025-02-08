# Go Router Improvements

## Version 0.1

### Router
* All fetch.go TODOs
* All import.go TODOs
* All router.go TODOs
* All templ.go TODOs
* All utils TODOs

* Clean Up File Reading
  * Make Consistent Flow
  * Use of AbsPath vs Relative in actual builds
* Setup Flow for DEBUG mode
* Cleanup Logs
* Create Server Functionality in Router
* Update ReadMe
* Add Tests

### CLI
* Add Basic BubbleTea Interface
* Add Config to Configure HTMX as Asset in Install Flow
* Allow Root File Path to be Chosen
* Find a way to Test

## Version 0.2

### Router
* Add in Flow for API Versioning
* Use FOP Structure for Config
* Implement Ctx Object
* Add SSR to Serve Templ
* Review Middleware Interface
* Improve Cancel Request Flow
* Create Config File for All Options
  * i.e. what supported assets
  * module name
  * version
  * etc...
* Create a Page Router
  * Allows you to add page config to entire router primariliy for nested layouts
* Add scss support

### CLI
* Add DB to Router Creation, will Support
  * PostGres
  * SqlLite

## Version 0.3

### Router
* Create a Utility for Working with OAuth
* Socket Integration