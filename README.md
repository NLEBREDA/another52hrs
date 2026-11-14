# Another 52 hrs — GitHub Pages build

This folder contains the existing Godot Web export. The `index.html`, `.js`, `.wasm`,
and `.pck` files must remain together in the repository root.

## Publish with GitHub Pages

1. Create a new GitHub repository, for example `another-52-hrs`.
2. Extract this ZIP on your computer.
3. Upload **the contents of this folder** to the repository root (not the containing folder).
4. Commit the files to the `main` branch.
5. In the repository, open **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select branch `main` and folder `/ (root)`, then Save.
8. Wait for GitHub Pages to publish. Open the URL shown in Settings → Pages.

The game is served from `index.html`. Do not open it as a local file; WebAssembly games
need to be served over HTTP/HTTPS.

## Notes

- This is the pre-existing web export from the supplied Godot project, packaged for GitHub Pages.
- The Godot source project is not included in this deployment ZIP.
- If you change the Godot project, export it again using the Web preset and replace these files.
