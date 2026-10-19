# Wave Assist (Geode mod, Windows)

## 1. Install Geode (one time)
Download the installer from https://geode-sdk.org, run it and pick your Geometry Dash folder.

## 2. Build the mod (free, in the cloud)
1. Create a free GitHub account, then a new **public** repository.
2. "Add file" -> "Upload files" -> drag in everything from this folder.
   The `.github` folder is hidden on some PCs: turn on "Show hidden items" in File Explorer (View menu) so it gets uploaded too.
3. Open the **Actions** tab. If asked, click "I understand my workflows, enable them".
   The "Build Geode Mod" run starts after your next upload, or press "Run workflow".
4. When it shows a green check (about 5-10 min), open the run, download **Build Output** and unzip it.
5. Copy `community.wave-assist.geode` into `Geometry Dash/geode/mods`, then restart GD.

If the run shows a red X, open it, copy the error text and send it to me.

## 3. Settings
In game: Geode button -> Wave Assist -> gear icon.

Targets Geode 5.11.2 / GD 2.2081. If your GD version is different, change the numbers in `mod.json`.
