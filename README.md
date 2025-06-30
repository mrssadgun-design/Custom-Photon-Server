# Custom Photon Server

A BepInEx mod for R.E.P.O that allows players to connect to custom or self-hosted Photon servers by overriding the R.E.P.O's default Photon App IDs. It provides an in-game menu to easily configure the server settings.

-----

## 🖼️ In-Game Menu

<p align="center">
  <img  src="https://github.com/Hiradpi/Custom-Photon-Server/blob/main/images/1.png"/>
</p>

-----

## ✨ Features

  * **Custom Photon App IDs:** Set your own `AppIdRealtime` and `AppIdVoice` to redirect the game's networking to your server.
  * **In-Game Configuration:** A user-friendly menu integrated with `MenuLib` and `REPOConfig` to change settings.
  * **Clipboard Import:** Quickly import a Photon App ID from your clipboard.
  * **Steam App ID Override:** Optionally change the Steam App ID, useful for development and testing (e.g., using Steam's Spacewar `480` ID).
-----

## ⚙️ Dependencies

To use or build this mod, you'll need the following dependencies:

  * **[BepInEx](https://github.com/BepInEx/BepInEx)**: The modding framework for Unity games.
  * **[HarmonyX](https://github.com/BepInEx/HarmonyX)**: For patching game methods at runtime.
  * **Unity Modules**:
      * `UnityEngine.dll`
      * `UnityEngine.CoreModule.dll`
      * `UnityEngine.UI.dll`
  * **Photon Networking**:
      * `PhotonRealtime.dll`
      * `PhotonUnityNetworking.dll`
  * **Steamworks**:
      * A compatible Steamworks library (e.g., `Steamworks.NET` or `Facepunch.Steamworks`).
  * **MenuLib**:
      * the `MenuLib.dll` you can get from [here](https://thunderstore.io/c/repo/p/nickklmao/MenuLib/).
  * **REPOconfig**:
      * The specific `REPOconfig.dll` you can get from [here](https://thunderstore.io/c/repo/p/nickklmao/REPOConfig/).
  * **TextMeshPro**:
      * `Unity.TextMeshPro.dll`

-----

## 🛠️ Installation

1.  Make sure you have **BepInEx** installed.
2.  Make sure you have **MenuLib** and **REPOConfig** in your plugins folder.
3.  Download the latest release of `CustomPhotonServer.dll` from the **[Releases](https://github.com/Hiradpi/Custom-Photon-Server/releases/download/1.0.2/CustomPhotonServer.dll)** page.
4.  Place the downloaded `.dll` file into your game's `BepInEx/plugins` folder.
5.  Launch the game, and the mod's configuration options should appear in the game's mod settings menu.

-----

## 🚀 Usage

1.  After installing the mod, run the game and navigate to the mod settings menu.
2.  Find the **Custom Photon Server** section.
3.  Toggle the **Enable** option to activate the mod.
4.  Enter your custom **AppId Realtime** and **AppId Voice** into the respective input fields.
      * You can also use the **Import from clipboard** button if you have a valid App ID copied.
5.  Click **Save** to apply the changes. The game will now attempt to connect using your specified Photon App IDs.
6.  (Optional) If you need to test with a different Steam application context, enable the **Change SteamAppId** option. This will initialize Steam with the test App ID `480` (Spacewar).

-----

## 🤝 Contributing

Contributions, issues, and feature requests are welcome\! Feel free to check the **[issues page](https://github.com/Hiradpi/Custom-Photon-Server/issues)**. Please read the contribution guidelines before making a pull request.
