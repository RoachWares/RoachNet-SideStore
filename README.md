<p align="center">
  <img src="https://roachnet.org/assets/readme/roachnet-sidestore.png" width="100%" alt="RoachNet for iOS Sideloaded Source, for SideStore and AltStore.">
</p>

# RoachNet for iOS Sideloaded Source

The app source that installs [RoachNet for iOS](https://github.com/RoachWares/RoachNet-iOS), the iPhone and iPad companion to RoachNet on your Mac, through SideStore or AltStore. The app ships unsigned, and SideStore or AltStore signs it with your own Apple ID.

**RoachNetiOS 0.3.1** · iOS 17 or later · [Install guide](https://roachnet.org/docs/get-started/ios/)

## Add the source

In SideStore or AltStore, add:

```text
https://raw.githubusercontent.com/RoachWares/RoachNet-SideStore/main/apps.json
```

Then install **RoachNetiOS** from the source list. Updates show up in the same source. With AltStore, keep AltServer running on your Mac, and refresh the app before its signing window runs out.

> [!NOTE]
> With a free Apple ID, a signature lasts 7 days. Apple's other sideloading limits still apply, and the [SideStore docs](https://docs.sidestore.io/) cover them.

## What's in this repository

| Path | What it is |
| --- | --- |
| `apps.json` | The source: the app, its version, size and download, in the format SideStore and AltStore read |
| `assets` | The app's icon and the screenshots the source shows |

It changes with each RoachNet iOS release.

## Help

Email [support@roachwares.org](mailto:support@roachwares.org) with the companion's version and your iOS version. [Documentation](https://roachnet.org/docs/).

---

<sub>Made by RoachWares LLC. RoachNet · offline on purpose.</sub>
