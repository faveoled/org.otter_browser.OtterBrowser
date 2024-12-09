### Install ready-to-use Flatpak:
1. Download `app.flatpak` from Releases
2. 
```
flatpak install ./app.flatpak
```
### Build Flatpak from source:
```
flatpak-builder build-dir --user --ccache --force-clean --install org.otter_browser.OtterBrowser.yaml
```
