# Hamilton

**Hamilton**, an awesome iOS event registration app!

## Getting Started

### Development Setup (OSX)

1. Install [CocoaPods](http://cocoapods.org)

		gem install cocoapods
		pod setup

2. Install Dependencies for Hamilton

		pod install

3. Open Xcode workspace via Xcode

		Hamilton.xcworkspace

4. Build/Run project from xCode

### About the group structure inside xcode

* Hamilton - App delegate, storyboards, and other top level classes
* Hamilton/API - API clients and other networking code
* Hamilton/Controllers - View Controllers
* Hamilton/Models - Data models, entities, core business logic. It doesn't matter if it's a CoreData entity or just a plain object, if it's core logic it goes here
* Hamilton/Views - Custom views and table view cells
* Hamilton/Support - Category methods, macros, and other supporting code that doesn't have another home
* Resources/Images.xcassets - Add images here
* Lib - code that is isolated from this project

### How to Contribute

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

