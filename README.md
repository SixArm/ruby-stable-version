# Ruby stable version

Print the current Ruby stable version.

Example:

    $ ruby-stable-version
    2.3.1

This implementation has three steps:

  * Fetch the Ruby website download page
  * Search the HTML to match a link to a download file,
  * Extract the version string, such as "2.3.1".

This implementation intentionally uses just shell tools,
because we want the script to be as portable as possible.

## Tracking

* Command: ruby-stable-version
* Contact: Joel Parker Henderson (joel@joelparkerhenderson.com)
* License: BSD, MIT, GPL
* Created: 2014-12-06
* Updated: 2016-09-02
