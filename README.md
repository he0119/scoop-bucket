# Scoop Bucket

<!-- Uncomment the following line after replacing placeholders -->
[![Tests](https://github.com/he0119/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/he0119/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/he0119/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/he0119/scoop-bucket/actions/workflows/excavator.yml)

Bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## How do I use this template?

1. Generate your own copy of this repository with the "Use this template"
   button.
2. Allow all GitHub Actions:
   - Navigate to `Settings` - `Actions` - `General` - `Actions permissions`.
   - Select `Allow all actions and reusable workflows`.
   - Then `Save`.
3. Allow writing to the repository from within GitHub Actions:
   - Navigate to `Settings` - `Actions` - `General` - `Workflow permissions`.
   - Select `Read and write permissions`.
   - Then `Save`.
4. Document the bucket in `README.md`.
5. Replace the placeholder repository string in `bin/auto-pr.ps1`.
6. Create new manifests by copying `bucket/app-name.json.template` to
   `bucket/<app-name>.json`.
7. Commit and push changes.
8. If you'd like your bucket to be indexed on `https://scoop.sh`, add the
   topic `scoop-bucket` to your repository.

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add he0119 https://github.com/he0119/scoop-bucket
scoop install he0119/<manifestname>
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.

## Credits

- [ZvonimirSun](https://github.com/ZvonimirSun/scoop-iszy): manifest for [clash-for-windows](https://github.com/Fndroid/clash_for_windows_pkg)
- [hoilc](https://github.com/hoilc/scoop-lemon): manifest for [Zotero Beta](https://www.zotero.org/support/beta_builds)
- [wsw0108](https://github.com/wsw0108/scoop-bucket): manifest for [im-select](https://github.com/daipeihust/im-select)
- [kkzzhizhou](https://github.com/kkzzhizhou/scoop-apps): manifest for [vscode185](https://code.visualstudio.com/)
- [ZephyrY7](https://github.com/ZephyrY7/zault): manifest for [钱迹](https://qianjiapp.com/)
