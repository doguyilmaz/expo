---
"expo-app-intents": patch
---

[iOS] `donateIntentAsync` decodes the params from the JavaScript object straight to the intent's `DonationParams` record, so a `@Record` type works as `DonationParams`.
