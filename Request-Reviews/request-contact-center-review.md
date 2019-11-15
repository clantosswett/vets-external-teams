# Contact Center

### General

* All applications on the Veteran-facing Services Platform include a phone number Veterans can call to ask questions about the application's functionality.
* **Before applications (or new features) launch on the Veteran-facing Services Platform, all teams must send a Product Guide and Product Video to the Contact Center to ensure that Contact Center Representatives are prepared to answer questions about the functionality.**
* **VFS teams should initiate the Contact Center Review when**
  1. The complete and final build is on staging and you're confident it's ready to launch,
  1. After they've completed the [Prepare for Contact Center Review](#prepare-for-contact-center-review) steps, and
  1. At least 2 weeks prior to the launch date.
    * If your team thinks it will have trouble meeting the "2 weeks prior to launch" date, reach out to your DSVA Contact to determine how to move forward.

## Prepare for Contact Center Review

### Step 1: Create the Product Guide

*If you're building a brand new service*:

  1. Create a Product Guide that covers all the functionality, the main user flow(s), any error conditions, and how the user can resolve those errors.
  1. The Product Guide must be a Word document or a PDF.
  1. Create a new folder in your team's Product folder called ```Contact Center.``` Store the Product Guide there.

*If you're building new features for an existing service*:

  1. You'll need to update the existing Product Guide.
      * If you can't find the existing Product Guide on Github, ask your DSVA Contact to find it for you.
  1. Store the updated Product Guide in its original location.

*Examples*:

[Example Product Guide 1](../Templates/sample-product-guide-1.pdf)
[Example Product Guide 2](../Templates/sample-product-guide-2.pdf)

### Step 2: Create the Product Video

*For new services and updates to existing services*:

  1. Create a Product Video (with audio) that steps through the primary user flows.
  1. Review your Product Video with your DSVA Contact to make sure you've covered everything.
  1. Create a transcript of the audio from the Product Video. The transcript must be a Word document or a PDF.

## Request Contact Center Review

1. File an issue in ```va.gov-team repo```.
    * Title: ```Request Contact Center Review```
    * Labels:
      * ```call center```
      * ```external-request```
      * ```[your team's Github label]```, e.g., "BAH-526"
    * Assign the issue to: ```Chante Lantos-Swett``` and ```Kimberley Daniels```
    * Comment: Include the following information.
      * **Context**: Provide a high-level description of the functionality for which you're requesting this review, for example:
        * ```Functionality adds a new dataset to the Facility Locator so users can search for and view non-VA health providers on the map, as well as in list and detail views.```
      * **URL**: ```link to your project on staging```
      * **Product Guide**: ```link to the Product Guide on Github```
      * **Product Video**: ```link to the Product Video on VA YouTube channel```
      * **Product Video Transcript**: ```link to the Product Video Transcript on Github```      

1. **Within 3 business days**, DSVA will send your Product Guide, Product Video, and Product Video Transcript to the Contact Center.
    * If you don't hear anything after 3 business days, reach out to your DSVA Contact.
1. After sending your team's materials to the Contact Center, DSVA will close the Github issue.
    * Github will send the person who created the Github issue a notification. This is your team's signal that this pre-launch activity is complete.
