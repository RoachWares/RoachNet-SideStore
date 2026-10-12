# RoachNet SideStore + AltStore Source

This repo publishes the shared AltSource feed for `RoachNetiOS`. SideStore and AltStore can both use this source URL.

Primary source URL:

`https://raw.githubusercontent.com/RoachWares/RoachNet-SideStore/main/apps.json`

What it carries:

- `RoachNetiOS` release metadata
- direct IPA install URL
- app permissions for QR pairing, local companion networking, local speech, Bluetooth, foreground location and Face ID
- screenshots and icon assets for SideStore and AltStore

Website links should point users to:

- shared source URL: `https://raw.githubusercontent.com/RoachWares/RoachNet-SideStore/main/apps.json`
- direct IPA: `https://github.com/RoachWares/RoachNet-iOS/releases/latest/download/RoachNetiOS-v0.3.0-unsigned.ipa`

The source exists so the iOS install lane feels like the rest of RoachNet: one clear path, no mystery files, no guessing which IPA is current. Add the same source URL in SideStore or AltStore; if the source path is not available, download the IPA and import it manually.
