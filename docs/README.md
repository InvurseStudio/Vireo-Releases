# Update feed

This folder is the repository's GitHub Pages site (Settings › Pages: `main`, `/docs`).
Vireo 0.9.1 and later read their updates from `appcast.xml` here
(`https://invursestudio.github.io/Vireo-app/appcast.xml`), so each release holds only
the DMG. The Vireo repository's `Mac/publish-release.sh` opens a pull request that updates
it; merge that pull request after publishing the release it points at.
