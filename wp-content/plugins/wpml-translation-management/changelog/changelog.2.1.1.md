# Features
* [wpmltm-972] Improved the repairing of broken database states implemented for Translation Polling, to cover more cases

# Fixes
* [wpmltm-992] Disabled admin notice about missing PHP required setting, when not in a WPML page, and if the `ICL_HIDE_TRANSLATION_SERVICES` constant is not set to true. Also added the ability to hide that notice.
* [wpmltm-970] Fix issue with message for missing php settings/extensions not hiding
* [wpmltm-963] Calculation of words count is now done through multiple AJAX calls and with proper progress feedback
* [wpmltm-959] Escape html in Post titles under the Translation jobs page
* [wpmltm-1008] Fixed an issue causing users that were translators but did not have administrator capabilities to not be able to access Translation Management functionality on sites that were set to only have hidden secondary languages.