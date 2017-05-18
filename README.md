# walksacramento

# Purpose

Quickly and easily add "walk audit" details and publish the results, as a map,
to the public. We did this by adding a map to the
[WalkSacramento](walksacramento.org) website showing locations and descriptions
of walk audits.

# Implementation

We used a [Google Fusion Table](fusiontables.google.com) to allow
WalkSacramento's staff to enter information about walk audits into the Fusion
Table "database". Among the information is an address, which can be geo-encoded
and used for displaying the walk audits in Google Maps.

We also updated the WalkSacramento home page to show a Google Map with icons
for each walk audit (representing the "barrier type"), and a balloon of details
about that walk audit. (The website is built in WordPress; we embedded an
iframe with the URL to Google Maps, as provided by Fusion Tables.)

