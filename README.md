# Plist Parser
A PHP Class for Parsing OS X plist files, adapted from [a gist by michaelfox](https://gist.github.com/michaelfox/888563).

## Usage
This original block of code was included in the original gist.

	$plist = Plist::from_file("~/Music/iTunes/iTunes Music Library.xml");
	print_r($plist->as_array());