# Fork build notes

This fork is built from upstream `storytold/lightcraft` at v0.2.1+ with no source changes.

The build includes the complete Traditional Chinese (`zh-hant`) UI catalog
(`crates/ui-egui/locales/zh-hant.json`, 1248 strings, full coverage with zero
missing or empty entries). The language can be selected in the app language
menu as "繁體中文（台灣）".

Note: upstream v0.2.1 predates the Traditional Chinese catalog, which is why
this fork build exists.
