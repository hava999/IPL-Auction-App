# IPL Apps

This folder contains two separate browser apps:

- [index.html](/Users/harshavaradhi/Documents/Claude/Artifacts/ipl-auction-app/index.html): IPL auction app
- [ipl-league-host.html](/Users/harshavaradhi/Documents/Claude/Artifacts/ipl-auction-app/ipl-league-host.html): league table and fixture host app

## Host The Auction App Online

The auction app is a static website, so the easiest way to share it is with GitHub Pages.

### 1. Create a GitHub repository

Create a new repository, for example:

`ipl-auction-app`

### 2. Upload these files

At minimum, upload:

- `index.html`
- `ipl-league-host.html`
- `league-samples/` if you want the league test assets online too

### 3. Turn on GitHub Pages

In GitHub:

1. Open the repository
2. Go to `Settings`
3. Open `Pages`
4. Under `Build and deployment`, choose:
   `Deploy from a branch`
5. Select:
   Branch: `main`
   Folder: `/ (root)`
6. Save

GitHub will publish the site and give you a URL like:

`https://yourusername.github.io/ipl-auction-app/`

### 4. Share the auction app

Share this URL with friends:

`https://yourusername.github.io/ipl-auction-app/`

The league host app will be at:

`https://yourusername.github.io/ipl-auction-app/ipl-league-host.html`

## How To Play The Auction Online

1. Everyone opens the auction URL in a browser.
2. One person clicks `Host the Auction`.
3. The host shares the 6-character room code.
4. Each friend joins as a bidder with:
   - their name
   - their team name
   - the room code
5. Once all teams join, the host starts the auction.

## Important Notes

- The host must keep the auction tab open the whole time.
- If the host refreshes or closes the tab, the room will disconnect.
- A laptop or desktop is better than a phone for the host.
- Everyone should use a modern browser on HTTPS.
- This app uses PeerJS/WebRTC, so some strict networks or VPNs may interfere with connections.

## Optional Alternatives

If you do not want GitHub Pages, you can also host the same files on:

- Vercel
- Netlify

They work because this project is static HTML.

## Sources

- [GitHub Pages docs](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)
- [PeerJS docs](https://peerjs.com/docs/)
- [PeerJS FAQ](https://peerjs.com/client/faq)
