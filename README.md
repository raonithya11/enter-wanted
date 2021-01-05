<img src="https://devmounta.in/img/logowhiteblue.png" width="250" align="right">

# Enter Wanted Test

This project is to create a web form that will generate the text to submit to the NCIC to add a warrant.

It is assumed that if incorrect entry occurs, the proper error message will be displayed to assist the user in correcting their mistakes.

Development on the application has been focused only on completing the form and validations, stylistic concerns are not being addressed at this time.

### The requirements are as follows for each field, and the results:

* Header: Required, 9-19 characters in length, any allowed
* MKE: Required, 2-4 alpha/special characters in length
* Originating Agency Identifier: Required, 9 alphanumeric characters in length
* Name: Reqired, 3-30 characters in length, any allowed
* Sex: Required, 1 character in length, alphabet only
* Race: Required, 1 character in length, alphabet only
* Height: Required, 3 characters in length, numeric only
* Weight: Required, 3 characters in length, numeric only
* Hair: Required, 4-10 characters in length, alphabet only
* Offense: Required, 5-15 characters in length, any allowed
* Date of Warrant/Violation, 8 characters in length, numeric in MMDDYYYY format
* Drivers License: Optional, 1-20 characters in length, any characters allowed, if included requires DL State & DL Expiration Year
* DL State: Optional, 2 characters in length, State Abbreviations only, if included requires Drivers License & DL Year
* DL Year: Optional, 4 characters in length, numeric in YYYY format, if included requires Drivers License & DL State

Upon successful entry, a text blob will be created, which consists of each of the values entered, separated by a '.' - any optional fields left blank will still be denoted in the blob by an additional '.'

## Project Instructions
At your instructor's direction, you will design/implement test cases to cover this functionality.

At another time, also at your instructor's direction, execute the previously created tests, tracking all bugs discovered.

Get your [testing templates here](https://docs.google.com/spreadsheets/d/1G6fFXoie0U2RRnxUGK-cfW6qOUEmZd-cF8W33yRyuVs/edit?usp=sharing).

## Contributions

If you see a problem or a typo, please fork, make the necessary changes, and create a pull request so we can review your changes and merge them into the master repo and branch.

## Copyright

© DevMountain LLC, 2017. Unauthorized use and/or duplication of this material without express and written permission from DevMountain, LLC is strictly prohibited. Excerpts and links may be used, provided that full and clear credit is given to DevMountain with appropriate and specific direction to the original content.

<p align="center">
<img src="https://devmounta.in/img/logowhiteblue.png" width="250">
</p>
