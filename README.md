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

## Add to Transync

```bash
transync add sample-android-app git@github.com:kaisarnajar-driod/sample-android-app.git \
  --strings-path app/src/main/res/values/strings.xml \
  --languages hi,ar,fr,es
```
