### JavaScript / Front-end libraries
codemirror/codemirror – CodeMirror 5 (syntax highlighting editor)  
jquery/inputmask – Input masking for form fields  
jquery/intl-tel-input – International telephone input widget  
jquery/rateit – Star rating plugin  
jquery/select2 – Enhanced select boxes  
jquery/textcounter – Character/word counter  
jquery/timepicker – Time selection widget  
progress-tracker/progress-tracker – Step/progress bar UI  
signature_pad/signature_pad – Canvas-based signature capture  
tabby/tabby – Accessible tabs  
tippyjs/tippyjs – Tooltip library  
popperjs/popperjs – Popper.js positioning engine (dependency for Tippy, etc.)  
recurser/jquery-simple-color – Simple color picker  
bgrins/spectrum – Spectrum color picker  

### PHP libraries  
bacon/bacon-qr-code – QR code generation backend  
cweagans/composer-patches – Composer patch management  
composer/installers – Custom installer paths  
pantheon-systems/drupal-integrations – Pantheon platform integration  
drush/drush – Drupal CLI tool  

### Custom / VCS packages  
upenn/penn403 – Custom module from GitHub (University of Pennsylvania 403 handler)  

# Drupal Composer Patches


## **drupal/endroid_qr_code**
- `patches/endroid_qr_code.patch` — Fixes QR code generation issues.

## **drupal/duration_field**
- `patches/duration_number_attributes.patch` — Adds numeric field attributes.

## **drupal/custom_view_filters**
- `patches/date_range_picker.patch` — Enables date range picker for timestamp filters.

## **drupal/core**
- [3049332_d10.3.0.patch](https://www.drupal.org/files/issues/2024-06-26/3049332_d10.3.0.patch) — Fix for `getEntityTypeId` errors.
- [3204558-13.patch](https://www.drupal.org/files/issues/2024-11-19/core_views-timestamp_date_filter-3204558-13.patch) — Fixes Views timestamp/date filters.
- [2833734-allow-attachment-pager-42.patch](https://www.drupal.org/files/issues/2020-11-29/2833734-allow-attachment-pager-42.patch) — Enables Views attachment pager.
- [3352384-43.patch](https://www.drupal.org/files/issues/2023-08-07/TypeError_htmlspecialchars_ArgumentNustBeTypeString_ArrayGiven-3352384-43.patch) — Fixes `htmlspecialchars()` type error.

## **drupal/simplesamlphp_auth**
- `patches/saml_auth.patch` — Makes SAML attributes dynamically update in Drupal.
- [Merge Request #33](https://git.drupalcode.org/project/simplesamlphp_auth/-/merge_requests/33.diff) — Fix for Masquerade module compatibility.

## **drupal/clientside_validation**
- `patches/no_link_issue.patch` — Prevents link elements from triggering validation issues.

## **drupal/smart_date**
- `patches/smart_value1.patch` — Fixes incorrect numeric error message output.

## **drupal/ckeditor_media_resize**
- [3531299--mr-16.patch](https://www.drupal.org/files/issues/2025-06-28/ckeditor_media_resize--2025-06-28--3531299--mr-16.patch) — Restores CKEditor 5 media resize functionality.
