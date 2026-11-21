# ZASAonSK Apps — source for AltStore, SideStore, Feather and LiveContainer

Open-source iOS apps that are not on the App Store. Add this source to your sideloading app and install or update them from there.

## Add the source

Tap a button on your iPhone. It opens the app and adds the source:

<table align="center">
  <tr>
    <td align="center" width="140">
      <a href="https://intradeus.github.io/http-protocol-redirector?r=altstore://source?url=https://raw.githubusercontent.com/ZASAonSK/altstore-repo/main/altstore.json"><img src="https://raw.githubusercontent.com/altstoreio/AltStore/56854e66fef2eac32dad88dcbad1dc131d430e60/AltStore/Resources/Icons.xcassets/Classic/Original.appiconset/Group%2023.png" width="72" alt="Add to AltStore"><br><sub><b>Add to AltStore</b></sub></a>
    </td>
    <td align="center" width="140">
      <a href="https://intradeus.github.io/http-protocol-redirector?r=sidestore://source?url=https://raw.githubusercontent.com/ZASAonSK/altstore-repo/main/altstore.json"><img src="https://raw.githubusercontent.com/SideStore/SideStore/4f3d18d98c5fbee72c80f787ceb2e8e09ded60a6/AltStore/Resources/Icons.xcassets/AppIcon.appiconset/1024.png" width="72" alt="Add to SideStore"><br><sub><b>Add to SideStore</b></sub></a>
    </td>
    <td align="center" width="140">
      <a href="https://intradeus.github.io/http-protocol-redirector?r=feather://source/https://raw.githubusercontent.com/ZASAonSK/altstore-repo/main/altstore.json"><img src="https://raw.githubusercontent.com/claration/feather/d264a7641dc948630b31af4b6d7f85249a198515/Feather/Resources/Assets.xcassets/AppIcon.appiconset/feather.png" width="72" alt="Add to Feather"><br><sub><b>Add to Feather</b></sub></a>
    </td>
    <td align="center" width="140">
      <a href="https://intradeus.github.io/http-protocol-redirector?r=livecontainer://source?url=https://raw.githubusercontent.com/ZASAonSK/altstore-repo/main/altstore.json"><img src="https://raw.githubusercontent.com/LiveContainer/LiveContainer/b0f53e8934df325970e9b6ff52932a43b585c424/Resources/Assets.xcassets/AppIcon.appiconset/AppIcon1024.png" width="72" alt="Add to LiveContainer"><br><sub><b>Add to LiveContainer</b></sub></a>
    </td>
  </tr>
</table>

The buttons open the app through a small redirect page (`intradeus.github.io/http-protocol-redirector`), because GitHub does not allow links that start with `altstore://`. If a button does nothing, add the source by hand: copy this URL and paste it into **Sources → +** in the app.

```
https://raw.githubusercontent.com/ZASAonSK/altstore-repo/main/altstore.json
```

## Apps

| | App | Description | |
| --- | --- | --- | --- |
| <img src="https://raw.githubusercontent.com/ZASAonSK/BudsBattery/main/Assets.xcassets/AppIcon.appiconset/icon-1024.png" width="48" alt="Buds Battery"> | **Buds Battery** | Battery levels of Samsung Galaxy Buds on iPhone: left earbud, right earbud and case. | [Source code](https://github.com/ZASAonSK/BudsBattery) |

`altstore.json` is updated automatically by the release workflow of each app; do not edit it by hand.
