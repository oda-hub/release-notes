# Release notes 21.10.0002

`21.10.0002` is a patch release. For details on the current feature relese please release notes of [21.10.0000](https://github.com/oda-hub/release-notes/tree/deff2eaf328978e66d9a8494050ca8bf983aa102).

We fixed several bugs and improved user experience, as described below.

## User experience

* Somewhat more detailed message in case of issues with the request
* Fixed bug preventing access to ISGRI light curve with OSA11.2-beta
* Frontend form can now accept up to 500 ScW. It means that request URLs for requests this size will also work
* When API code in the email can not be embedded in the email, it will be attached (before, it was ommited)
* Improved performance in high load, with multiple simultanous users
* Fixed bug preventing correct generation of request URL when user catalog was provided as a fits file
* Improved performance of the name resolved

## Known limitations

Please consult https://github.com/oda-hub/known-issues for the list of known issues.

You may be intersted to inspect [full list of closed issues](https://github.com/issues?q=org%3Aoda-hub+milestone%3Av21.10.0002) for this release.
