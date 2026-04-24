# Sample Android App

A sample Android project used for testing [Transync](https://github.com/kaisarnajar-driod/translation-automation-tool) — the translation automation tool.

## Clone

```bash
git clone git@github.com:kaisarnajar-driod/sample-android-app.git
```

## String Resources

- **Format:** Android XML
- **Path:** `app/src/main/res/values/strings.xml`
- **Translated output:** `app/src/main/res/values-{lang}/strings.xml`

### Example (`strings.xml`)

```xml
<?xml version="1.0" encoding="utf-8"?>
<resources>
    <string name="label_studio_disclaimer_subtitle">Free consultation and custom fitting are required with an optician at selected Lenskart showrooms.</string>
    <string name="sub_title_empty_view">Lenskart is working hard to expand pickup points across the country. We are coming soon to your locality.</string>
    <string name="label_unserviceable_to_fourth_floor">We\'ll be unable to provide service to floors located on the 4th floor and higher if there is no elevator available.</string>
    <string name="label_pupillary_distance_click_suggestion">Keep your face aligned &amp; capture a picture to find your Pupillary Distance (PD)</string>
    <string name="msg_successfully_password_sent">Check your email - A link to reset password has been sent to your email</string>
</resources>
```

## Add to Transync

```bash
transync add sample-android-app git@github.com:kaisarnajar-driod/sample-android-app.git \
  --strings-path app/src/main/res/values/strings.xml \
  --languages hi,ar,fr,es
```
