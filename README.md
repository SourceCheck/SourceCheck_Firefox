# [SourceCheck](http://sourcecheck.it/) for Firefox (0.0.1)
Trust your information.

SourceCheck for Firefox is not yet released, please wait until
1.0.0 to install it. Don't run it yet unless you are a developer.

## Platforms
- [Firefox](https://github.com/SourceCheck/SourceCheck_Firefox)
- [Chrome](https://github.com/dustmoo/sourcecheck_chrome)

## Build
### Requirements:
  - [Firefox 38 or onwards](https://firefox.com/)
  - [jpm](https://developer.mozilla.org/en-US/Add-ons/SDK/Tools/jpm)

```
$ git clone https://github.com/SourceCheck/SourceCheck_Firefox
$ jpm run
```

**Build Errors:**
  - JPM undefined No Firefox binary found at null

    If you get this error you need to specify a Firefox binary using
    the -b option.

    Documented here: https://developer.mozilla.org/en-US/Add-ons/SDK/Tools/jpm#jpm_run

    *ex (on Debian):*
    ```
    $ jpm run -b /usr/lib/firefox/firefox
    ```

### Developing:

*For the user:*
- [Check](https://github.com/SourceCheck/SourceCheck_Firefox/issues) to make sure your issue hasn't already been reported
- Serch through recent reddit posts on [/r/SourceCheck](http://www.reddit.com/r/sourcecheck)
- Submit a [new GitHub issue](https://github.com/SourceCheck/SourceCheck_Firefox/issues/new)
- Clearly explain the problem/feature request/idea

*For the developer:*
- Follow the [Mozilla Coding Style](https://developer.mozilla.org/en-US/docs/Mozilla/Developer_guide/Coding_Style)
- Make a change
- Commit it using Git
- Submit a pull request
- Respond to community comments
- Have your patch landed by a maintainer
