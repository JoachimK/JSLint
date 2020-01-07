This is a fork of

*JSLint, The JavaScript Code Quality Tool*

originally by [Douglas Crockford][2].

For more information about JSLint visit the [original repository][1] or the [website][6].

The main reason for this fork was to be able to use JSLint in an extension for [Adobe Brackets][3] which includes this repository as a submodule.
You can find the extension here: [https://github.com/JoachimK/brackets-continuous-compilation][4]

To make it easier to integrate, I modified the original implementation to work as a [require.js module][5].

I also plan to make some changes to the JSLint function (mainly add information to the error objects) to make it more useful as an API for other tools wanting to report the errors in different ways.

I you can make use of any of this feel free to fork the repo.


[1]: https://github.com/douglascrockford/JSLint
[2]: http://crockford.com
[3]: https://github.com/adobe/brackets
[4]: https://github.com/JoachimK/brackets-continuous-compilation
[5]: http://requirejs.org/
[6]: http://jslint.com
