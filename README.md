lib-bourbon
===

This is a replica of [Thoughtbot's Sass Bourbon library](https://github.com/thoughtbot/bourbon) but provided in a format that can be used as a submodule for other git projects to avoid having to add Bourbon files to source control.

Usage
---

### Adding as a submodule

To add this library as a submodule, execute the following commands inside of your project. This will add this library as a submodule and checkout the current 4.1.x version into a folder called "bourbon."

	git submodule add -b v4_1 https://github.com/Sujevo/lib-bourbon bourbon
	git submodule update --remote

You may replace `v4_1` with `v3_2` if you would like to use Bourbon version 3.2.x. This repository will always use the most up to date version for the respective branch.

### Current Hosted Versions

- Version 4.1.0 (v4_1) - December 2014
- Version 4.0.2 (v4_0) - May 2014
- Version 3.2.3 (v3_2) - May 2014

## Credits

[![thoughtbot](http://images.thoughtbot.com/bourbon/thoughtbot-logo.svg)](http://thoughtbot.com)

Bourbon is maintained and funded by [thoughtbot, inc](http://thoughtbot.com). Tweet your questions or suggestions to [@bourbonsass](https://twitter.com/bourbonsass) and while you’re at it follow us too.

## License

Copyright © 2011–2014 [thoughtbot, inc](http://thoughtbot.com). Bourbon is free software, and may be redistributed under the terms specified in the [license](https://github.com/thoughtbot/bourbon/blob/master/LICENSE.md).
