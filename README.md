<h1>Foo Rui Qin</h1>

<p>I study computer science at DigiPen/SIT in Singapore and am looking for software engineering internships. Before this, I studied accountancy and finance. My projects focus on C++ game engine tools and backend systems.</p>
<p>Assetwise is where the finance background shows up. TikTok 2020 is what happened when I realised I’d missed a whole corner of lockdown internet.</p>

<p><a href="https://foo-rq.github.io/">Portfolio</a> / <a href="mailto:ruiqinfoo@gmail.com">Email</a> / <a href="https://www.linkedin.com/in/rui-qin-foo/">LinkedIn</a> / <a href="assets/resume.pdf">Résumé</a></p>

<p><a href="#grapeengine"><img src="assets/grapeengine-profile.png" width="49%" alt="Explore GrapeEngine, our team’s C++ game engine and editor."></a> <a href="#assetwise"><img src="assets/assetwise-profile.png" width="49%" alt="Explore Assetwise, my portfolio analysis application."></a></p>
<p><a href="#grapeengine">GrapeEngine</a> / <a href="#assetwise">Assetwise</a> / <a href="#tiktok-2020">TikTok 2020</a> / <a href="#more-engineering-work">More engineering work</a></p>

<a name="grapeengine"></a>
<h2>GrapeEngine</h2>
<p>Our team built a C++ game engine and editor for <em>Echoes Below</em>. The editor lets the team assemble levels and edit game entities and their components.</p>
<p>I built the memory-pool allocator and worked on cached resource loading and editor tools, including selection, copy/paste, undo and prefabs.</p>
<p><a href="https://foo-rq.github.io/grapeengine.html">Read the project write-up</a> / <a href="https://github.com/Chaotic-Grapes/GrapeEngine">Browse the engine source</a> / <a href="assets/grapeengine-editor-demo.mp4?raw=true">Open the 20-second editor demo (MP4)</a></p>
<details>
<summary>My engine work, in more detail</summary>
<p>I built a memory-pool allocator with an address-ordered free list. I also worked on resource caching, entity/component editing and prefab tools.</p>
<a href="assets/grapeengine-editor.png"><img src="assets/grapeengine-editor.png" width="860" alt="Full GrapeEngine editor screenshot with scene hierarchy, component inspector and asset browser."></a>
<p><sub>Team project. The editor screenshot and normal-speed, muted recording come from team footage. My contributions are described above.</sub></p>
<p>C++ / Dear ImGui / CMake</p>
</details>

<a name="assetwise"></a>
<h2>Assetwise</h2>
<p>Assetwise is a portfolio analysis web app for building practice portfolios and comparing allocations. It shows when funds hold the same companies and puts estimated risk and growth beside each proposed change.</p>
<p>I built the Python/FastAPI backend, plain JavaScript interface and SQLite portfolio storage. Saves catch conflicting edits rather than overwrite a newer version.</p>
<p><a href="https://foo-rq.github.io/assetwise.html">Explore Assetwise</a></p>
<details>
<summary>See a portfolio comparison</summary>
<p><a href="assets/assetwise-portfolio.png">Open the full portfolio screenshot</a></p>
<a href="assets/assetwise-comparison-live.png"><img src="assets/assetwise-comparison-live.png" width="580" alt="Current and proposed allocations with lower modelled growth and volatility shown side by side."></a>
<p>The estimates make the trade-off visible: less estimated risk can also mean less estimated growth.</p>
<p>Python / FastAPI / SQLite / JavaScript</p>
</details>
<p><sub>Independent project, still in development. The archive covers 46 stocks and funds from 2013 to 2017. No live prices or real trades.</sub></p>

<a name="tiktok-2020"></a>
<h2>TikTok 2020</h2>
<p>I didn’t use TikTok during lockdown. When I came across videos from that year later, I wanted to keep scrolling through 2020.</p>
<p>TikTok 2020 is a browser app for archived videos and comments, with a feed, Discover, search and saved likes. I built it with plain JavaScript.</p>
<p><a href="assets/tiktok-portfolio-demo.mp4?raw=true"><img src="assets/tiktok-portfolio-poster.jpg" width="30%" alt="Watch the TikTok 2020 app demo."></a> <a href="assets/tiktok-discover.jpg"><img src="assets/tiktok-profile-discover.png" width="30%" alt="Open the full-size Discover screenshot."></a> <a href="assets/tiktok-comments.jpg"><img src="assets/tiktok-profile-comments.png" width="30%" alt="Open the full-size archived comments screenshot."></a></p>
<p><a href="https://foo-rq.github.io/tiktok-2020.html">Read the project write-up</a> / <a href="assets/tiktok-portfolio-demo.mp4?raw=true">Open the 18-second app demo (MP4)</a> / <a href="https://github.com/foo-rq/tiktok-2020">Browse the source</a></p>
<p><sub>Independent project, plain JavaScript. The demo shows playback, sound, comments, swiping, Discover, search and Inbox. Videos and comments belong to their original creators.</sub></p>

<a name="more-engineering-work"></a>
<h2>More engineering work</h2>
<h3>Spatia</h3>
<p><a href="assets/spatia-editor-sample.png"><img src="assets/spatia-editor-sample.png" width="580" alt="Spatia’s team editor with a local sample exhibition. Open full-size screenshot."></a></p>
<p><sub>Spatia team editor, running locally with a sample exhibition.</sub></p>
<p>A team-built browser editor for creating and publishing interactive 3D exhibitions. I worked on shared TypeScript/C# document validation, draft recovery and revision-aware autosave, plus publication access and asset administration. The project is ongoing.</p>
<p><a href="https://foo-rq.github.io/spatia.html">Read about my Spatia work</a></p>
<details><summary>More about my Spatia work</summary><p>My work also includes serialization and reconstruction, IndexedDB recovery, import/export, protected asset delivery and deployment checks. The screenshot shows the team application with a local sample exhibition.</p><p>TypeScript / C# / PostgreSQL</p></details>
<h3>TradingSystem</h3>
<p><a href="assets/trading-markets.png"><img src="assets/trading-markets.png" width="580" alt="TradingSystem’s team interface with simulated prices. Open full-size screenshot."></a></p>
<p><sub>TradingSystem team interface, using simulated market data.</sub></p>
<p>A team-built simulated trading platform, with a C++ server and web interface for viewing markets and placing orders. I added concurrent client handling, atomic settlement and persisted order sequencing so price-time priority survives a restart.</p>
<p><a href="https://foo-rq.github.io/trading-system.html">Read about my trading backend work</a></p>
<details><summary>More about my trading backend work</summary><p>I worked on per-connection client workers, checked settlement writes and rollback handling. Related work includes persisting the latest price and validating JWT expiry.</p><p>C++ / Winsock / SQLite</p><p>The screenshot shows the team interface with simulated data. My contribution is to the backend.</p></details>

<hr>
<p>I’ve also been a C/C++ teaching assistant at DigiPen and a finance intern at GetGo. I’m looking for software engineering internships, especially in systems and backend development.</p>
<p><a href="mailto:ruiqinfoo@gmail.com">Get in touch</a> / <a href="assets/resume.pdf">Read my résumé</a></p>
<p><sub>Some source repositories remain private. Team-project descriptions refer to my contributions.</sub></p>
