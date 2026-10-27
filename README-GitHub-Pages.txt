Fight — GitHub Pages deployment

1. Upload index.html, index-multiplayer.html, and .nojekyll to the ROOT of https://github.com/hello1235632/Fight
2. Commit the files to the main branch.
3. Open repository Settings -> Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select Branch: main and Folder: /(root), then click Save.
6. Wait for the deployment to finish. The site URL should be:
   https://hello1235632.github.io/Fight/

The game uses the existing multiplayer implementation. Online multiplayer relies on the PeerJS Cloud signaling service; GitHub Pages only hosts the static HTML and is not itself a multiplayer signaling server. The local-network QR mode remains available as in the original file.
