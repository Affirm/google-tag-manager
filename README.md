## Overview
Affirm’s Google Tag Manager Template will allow merchants to easily embed promotional messages, the Affirm logo, and a VCN checkout by simply adding the HTML classes/ids to a form within Google Tag Manager. The merchant will upload the template into their Google Tag Manager which will create tags with form fields. The merchant will enter their Affirm public API key, environment (sandbox or production) and classes/ids to configure their store. The Tag will embed the configuration into the store website’s window object for merchant.js to reference.

Merchant.js (hosted separately by Affirm) will be included in the head of the Merchant’s HTML code and will read the configurations to call AffirmJS and manipulate the DOM according to the classes and IDs given by the merchant.

Affirm has been invited to join the Google Tag Manager Tag Vendor Program which allows tag providers to natively integrate with Google Tag Manager's tag templating system. Google will host the Affirm Template on their marketplace for merchants to easily find.

## How to Update

To update the Google template you need to make changes in the Google Template Editor within Google Tag Manager, export the template and then upload the file to the Affirm Google Tag Manager repository. The metadata data must be updated to reflect the new version, please refer to these [guidelines](https://developers.google.com/tag-manager/templates/gallery#update_your_template). The changes will take effect in less than 24 hours.
