<h1>Foo Rui Qin</h1>

<p>I’m a computer science student at DigiPen/SIT in Singapore, looking for software engineering internships. I work on C++ game engine tools, backend systems and web applications.</p>
<p>Before computer science, I studied accountancy and finance. I’ve also been a C/C++ teaching assistant at DigiPen.</p>

<p><a href="https://foo-rq.github.io/">Portfolio</a> / <a href="mailto:ruiqinfoo@gmail.com">Email</a> / <a href="https://www.linkedin.com/in/rui-qin-foo/">LinkedIn</a></p>

<p><a href="#grapeengine"><img src="assets/grapeengine-profile.png" width="49%" alt="Explore GrapeEngine, our team’s C++ game engine and editor."></a> <a href="#assetwise"><img src="assets/assetwise-profile.png" width="49%" alt="Explore Assetwise, my portfolio analysis application."></a></p>
<p><a href="#grapeengine">GrapeEngine</a> / <a href="#coin-rush">Coin Rush</a> / <a href="#assetwise">Assetwise</a> / <a href="#spatia">Spatia</a> / <a href="#tradingsystem">TradingSystem</a> / <a href="#tiktok-2020">TikTok 2020</a></p>

<a name="grapeengine"></a>
<h2>GrapeEngine</h2>
<p><sub>Team project / Technical lead / C++, Dear ImGui, CMake</sub></p>
<p>Our team built a C++ game engine and editor for <em>Echoes Below</em>. The editor lets the team assemble levels and edit game entities and their components.</p>
<p>I built the memory-pool allocator and worked on cached resource loading and editor tools, including selection, copy/paste, undo and prefabs.</p>
<p><a href="https://foo-rq.github.io/grapeengine.html">Read the project write-up</a> / <a href="https://github.com/Chaotic-Grapes/GrapeEngine">Browse the engine source</a> / <a href="assets/grapeengine-editor-demo.mp4?raw=true">Open the 20-second editor demo (MP4)</a></p>
<details>
<summary>My engine work, in more detail</summary>
<p>I built a memory-pool allocator with an address-ordered free list. I also worked on resource caching, entity/component editing and prefab tools.</p>
<a href="assets/grapeengine-editor.png"><img src="assets/grapeengine-editor.png" width="860" alt="Full GrapeEngine editor screenshot with scene hierarchy, component inspector and asset browser."></a>
<p><sub>Team project. The editor screenshot and normal-speed, muted recording come from team footage. My contributions are described above.</sub></p>
</details>

<a name="coin-rush"></a>
<h2>Coin Rush</h2>
<p><sub>Team project / C, Cyclone DDS, OpenSSL</sub></p>
<p><a href="https://foo-rq.github.io/coin-rush.html"><img src="assets/coin-rush-menu.png" width="420" alt="Coin Rush menu with create-room and join-room controls. View the project write-up."></a></p>
<p>A team-built C game for two to five players: catch coins, dodge bombs and settle a tie with another round. I worked on DDS networking and security, match progression and Linux profiling.</p>
<p><a href="https://foo-rq.github.io/coin-rush.html">Read the project write-up</a> / <a href="https://github.com/jingwen121/LLPAssignment">Browse the team source</a></p>
<details><summary>More about my networking and profiling work</summary><p>I configured certificate identities, signed topic permissions and encrypted DDS traffic. I compared four variants with Linux perf over 100 runs each, measuring 14.19% lower mean batch runtime for SSE2 than scalar. A teammate implemented SIMD; my work here was profiling and analysis. This measures the batch workload, not game frame rate.</p></details>

<a name="assetwise"></a>
<h2>Assetwise</h2>
<p><sub>Independent project / Python, FastAPI, SQLite, JavaScript</sub></p>
<p>Assetwise is a portfolio analysis web app for building practice portfolios and comparing allocations. It shows when funds hold the same companies and puts estimated risk and growth beside each proposed change.</p>
<p>I built the Python/FastAPI backend, plain JavaScript interface and SQLite portfolio storage. Saves catch conflicting edits rather than overwrite a newer version.</p>
<p><a href="https://foo-rq.github.io/assetwise.html">Read the project write-up</a> / <a href="https://github.com/foo-rq/assetwise">Browse the source</a></p>
<details>
<summary>See a portfolio comparison</summary>
<a href="assets/assetwise-comparison-live.png"><img src="assets/assetwise-comparison-live.png" width="580" alt="Current and proposed allocations with lower modelled growth and volatility shown side by side."></a>
<p>The estimates make the trade-off visible: less estimated risk can also mean less estimated growth.</p>
</details>

<a name="spatia"></a>
<h2>Spatia</h2>
<p><sub>Team project, ongoing / TypeScript, C#, PostgreSQL</sub></p>
<p><a href="assets/spatia-editor-sample.png"><img src="assets/spatia-editor-sample.png" width="580" alt="Spatia’s team editor with a local sample exhibition."></a></p>
<p>A team-built browser editor for creating and publishing interactive 3D exhibitions. I worked on shared TypeScript/C# document validation, draft recovery and revision-aware autosave, plus publication access and asset administration. The project is ongoing.</p>
<p><a href="https://foo-rq.github.io/spatia.html">Read about my Spatia work</a></p>
<details><summary>More about my Spatia work</summary><p>My work also includes serialization and reconstruction, IndexedDB recovery, import/export, protected asset delivery and deployment checks. The screenshot shows the team application with a local sample exhibition.</p></details>
<a name="tradingsystem"></a>
<h2>TradingSystem</h2>
<p><sub>Team project / C++, Winsock, SQLite</sub></p>
<p><a href="assets/trading-markets.png"><img src="assets/trading-markets.png" width="580" alt="TradingSystem’s team interface with simulated prices."></a></p>
<p>A team-built simulated trading platform, with a C++ server and web interface for viewing markets and placing orders. I added concurrent client handling, atomic settlement and persisted order sequencing so price-time priority survives a restart.</p>
<p><a href="https://foo-rq.github.io/trading-system.html">Read about my trading backend work</a></p>
<details><summary>More about my trading backend work</summary><p>I worked on per-connection client workers, checked settlement writes and rollback handling. Related work includes persisting the latest price and validating JWT expiry.</p><p>The screenshot shows the team interface with simulated data. My contribution is to the backend.</p></details>

<a name="tiktok-2020"></a>
<h2>TikTok 2020</h2>
<p><sub>Independent project / JavaScript, HTML, CSS</sub></p>
<p>TikTok 2020 is a browser app for archived videos and comments. I built the feed, Discover, search and saved likes with plain JavaScript.</p>
<p>I wasn’t on TikTok during lockdown, so I built this to browse the videos I’d missed.</p>
<p><a href="assets/tiktok-portfolio-demo.mp4?raw=true"><img src="assets/tiktok-portfolio-poster.jpg" width="30%" alt="Watch the TikTok 2020 app demo."></a> <a href="assets/tiktok-discover.jpg"><img src="assets/tiktok-profile-discover.png" width="30%" alt="TikTok 2020 Discover screen."></a> <a href="assets/tiktok-comments.jpg"><img src="assets/tiktok-profile-comments.png" width="30%" alt="TikTok 2020 archived comments."></a></p>
<p><a href="https://foo-rq.github.io/tiktok-2020.html">Read the project write-up</a> / <a href="assets/tiktok-portfolio-demo.mp4?raw=true">Open the 18-second app demo (MP4)</a> / <a href="https://github.com/foo-rq/tiktok-2020">Browse the source</a></p>
<p><sub>Independent project, plain JavaScript. The demo shows playback, sound, comments, swiping, Discover, search and Inbox. Videos and comments belong to their original creators.</sub></p>

<hr>
<p><a href="mailto:ruiqinfoo@gmail.com">Get in touch</a></p>
<p><sub>Some source repositories remain private. Team-project descriptions refer to my contributions.</sub></p>
