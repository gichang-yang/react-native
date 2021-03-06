Thanks for submitting a PR! Please read these instructions carefully:

- [x] Explain the **motivation** for making this change.
- [x] Provide a **test plan** demonstrating that the code is solid.
- [x] Match the **code formatting** of the rest of the codebase.
- [x] Target the `master` branch, NOT a "stable" branch.

## Motivation (required)
I want to use 'react-native' more comfortable.

What existing problem does the pull request solve?
---------------------------------------------------------------------
->in this version, 'button' component couldn't change text size in 'ios'. so, I added button's props 
"textSizeIOS",be able to change button's text size(May be it's similar 'change button size' in ios.)
-------------------------------------------------------------

 .  

## Test Plan (required)

A good test plan has the exact commands you ran and their output, provides screenshots or videos if the pull request changes UI or updates the website. See [What is a Test Plan?][1] to learn more.  

If you have added code that should be tested, add tests.
-----------------------------------------------------------------
Ans:
# **->testing video is here. text size is 10,20 and 30.
[IMG_1944.MOV.zip](https://github.com/facebook/react-native/files/981039/IMG_1944.MOV.zip)**
--------------------------------------------------------------------

## Next Steps

Sign the [CLA][2], if you haven't already.

Small pull requests are much easier to review and more likely to get merged. Make sure the PR does only one thing, otherwise please split it.

Make sure all **tests pass** on both [Travis][3] and [Circle CI][4]. PRs that break tests are unlikely to be merged.

For more info, see the ["Pull Requests"][5] section of our "Contributing" guidelines.

[1]: https://medium.com/@martinkonicek/what-is-a-test-plan-8bfc840ec171#.y9lcuqqi9
[2]: https://code.facebook.com/cla
[3]: https://travis-ci.org/facebook/react-native
[4]: http://circleci.com/gh/facebook/react-native
[5]: https://github.com/facebook/react-native/blob/master/CONTRIBUTING.md#pull-requests
