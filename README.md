# Release notes 21.10.0003

`21.10.0003` is a patch release. For details on the current feature relese please see release notes of [21.10.0000](https://github.com/oda-hub/release-notes/tree/21.10.0000).

We fixed several bugs and improved user experience, as described below.
Some of the changes simplify process of running large requests (over 20k ScW). 
Note that for now, requests of this size can be only submitted upon special agreement.

## User experience improvements

* Some improvements in error reporting in frontend an API.
* More clear note in the email about expiration time of the URL in the cases when these URLs are temporary.
* When the URLs provided in job email and in the frontend are persistent they are more consistent: parameters in the URL are converted to default formats before being inserted to the URL (e.g. time will be always represented as ISOT).
* Some stability improvements

## Known limitations

Please consult https://github.com/oda-hub/known-issues for the list of known issues.

You may be intersted to inspect [full list of closed issues](https://github.com/issues?q=org%3Aoda-hub+milestone%3Av21.10.0003) for this release.
