/* <!doctype html><html><head><meta charset=utf8><meta name=viewport content="width=device-width,initial-scale=1,viewport-fit=cover"><style>:root{color-scheme:light;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}html{scroll-padding-top:env(safe-area-inset-top,0px)}body{margin:0;padding:0;font:14px -apple-system,BlinkMacSystemFont,sans-serif;background:#fff;color:#000}img{max-width:100%}[hidden]:not([hidden=until-found i]){display:none!important}</style></head><body> */
<title>김수진</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:wght@400;500&family=IBM+Plex+Sans+KR:wght@300;400;500;600&display=swap">
<style>
:root {
  --bg: #f6f6f5;
  --surface: #ffffff;
  --fg: #111111;
  --muted: #6b6b68;
  --line: #deddda;
  --accent: #111111;
  --accent-fg: #f6f6f5;
  --font-body: "IBM Plex Sans KR", "Apple SD Gothic Neo", "Malgun Gothic", system-ui, sans-serif;
  --font-mono: "IBM Plex Mono", ui-monospace, "SFMono-Regular", Menlo, monospace;
}
@media (prefers-color-scheme: dark) {
  :root:not([data-theme="light"]) {
    --bg: #0e0e0d; --surface: #181817; --fg: #efefec; --muted: #9a9a95;
    --line: #2b2b29; --accent: #efefec; --accent-fg: #0e0e0d; color-scheme: dark;
  }
}
:root[data-theme="dark"] {
  --bg: #0e0e0d; --surface: #181817; --fg: #efefec; --muted: #9a9a95;
  --line: #2b2b29; --accent: #efefec; --accent-fg: #0e0e0d; color-scheme: dark;
}
* { box-sizing: border-box; }
body {
  background: var(--bg); color: var(--fg);
  font-family: var(--font-body); font-size: 15px; line-height: 1.7;
  padding-inline: 20px; padding-block: 56px 40px;
  -webkit-font-smoothing: antialiased;
}
.page { max-width: 440px; margin-inline: auto; display: flex; flex-direction: column; gap: 40px; }

.profile { display: flex; flex-direction: column; align-items: center; gap: 14px; text-align: center; }
.avatar {
  width: 104px; height: 104px; border-radius: 50%;
  background: var(--surface); border: 1px solid var(--line);
  display: grid; place-items: center;
  font-weight: 300; font-size: 40px;
}
.avatar img { width: 100%; height: 100%; border-radius: 50%; object-fit: cover; }
h1 { margin: 0; font-size: 28px; font-weight: 600; letter-spacing: -0.02em; text-wrap: balance; }
.role { font-family: var(--font-mono); font-size: 12px; letter-spacing: 0.08em; text-transform: uppercase; color: var(--muted); }
.bio { margin: 0; max-width: 34ch; color: var(--fg); text-wrap: pretty; }

.links { display: flex; flex-direction: column; gap: 10px; padding: 0; margin: 0; list-style: none; }
.links a {
  display: flex; align-items: center; justify-content: space-between; gap: 12px;
  padding: 15px 18px; border: 1px solid var(--line); border-radius: 999px;
  background: var(--surface); color: var(--fg); text-decoration: none; font-weight: 500;
  transition: background .15s, color .15s, border-color .15s;
}
.links a span.handle { font-family: var(--font-mono); font-size: 12px; color: var(--muted); font-weight: 400; }
.links a:hover, .links a:focus-visible { background: var(--accent); color: var(--accent-fg); border-color: var(--accent); }
.links a:hover span.handle, .links a:focus-visible span.handle { color: var(--accent-fg); opacity: .75; }
a:focus-visible, button:focus-visible { outline: 2px solid var(--accent); outline-offset: 3px; }

h2 {
  margin: 0 0 14px; font-family: var(--font-mono); font-size: 12px; font-weight: 500;
  letter-spacing: 0.1em; text-transform: uppercase; color: var(--muted);
  display: flex; align-items: center; gap: 12px;
}
h2::after { content: ""; flex: 1; height: 1px; background: var(--line); }

.timeline { list-style: none; margin: 0; padding: 0; display: flex; flex-direction: column; gap: 18px; }
.timeline li { display: grid; grid-template-columns: 96px minmax(0, 1fr); gap: 14px; }
.when { font-family: var(--font-mono); font-size: 12px; color: var(--muted); padding-top: 3px; font-variant-numeric: tabular-nums; }
.what strong { display: block; font-weight: 500; }
.what span { color: var(--muted); font-size: 14px; }

.contact { display: flex; align-items: center; justify-content: space-between; gap: 12px; flex-wrap: wrap;
  padding: 16px 18px; border: 1px solid var(--line); border-radius: 14px; background: var(--surface); }
.contact code { font-family: var(--font-mono); font-size: 13px; user-select: all; overflow-wrap: anywhere; min-width: 0; }
.copy { font: inherit; font-family: var(--font-mono); font-size: 12px; padding: 6px 12px; border-radius: 999px;
  border: 1px solid var(--line); background: transparent; color: var(--fg); cursor: pointer; }
.copy:hover { background: var(--accent); color: var(--accent-fg); border-color: var(--accent); }

footer { text-align: center; font-family: var(--font-mono); font-size: 11px; color: var(--muted); }
@media (prefers-reduced-motion: reduce) { * { transition: none !important; } }
</style>

<main class="page">
  <section class="profile">
    <div class="avatar" aria-hidden="true">Kim</div>
    <h1>Kim sujin</h1>
    <div class="role">Network Security · Incheon</div>
    <p class="bio">세상을 연결하는 중...</p>
  </section>

  <section aria-label="링크">
    <ul class="links">
      <li><a href="https://instagram.com/dyuldim" target="_blank" rel="noopener">Instagram <span class="handle">@dyuldim</span></a></li>
      <li><a href="https://github.com/dalnim64" target="_blank" rel="noopener">GitHub <span class="handle">/dalnim64</span></a></li>
    </ul>
  </section>

  <section>
    <h2>Education</h2>
    <ul class="timeline">
      <li><div class="when">2026 — </div><div class="what"><strong>CWU 컴퓨터공학과 재학</strong><span>인천</span></div></li>
      <li><div class="when">2023 — 2025</div><div class="what"><strong>SRIHS 정보보호과 졸업</strong><span>서울</span></div></li>
    </ul>
  </section>

  <section>
    <h2>Club</h2>
    <ul class="timeline">
      <li><div class="when">2023 — 2025</div><div class="what"><strong>Nefus 21st</strong></div></li>
    </ul>
  </section>

  <section>
    <h2>Contact</h2>
    <div class="contact">
      <code id="email">groovluu@gmail.com</code>
      <button class="copy" id="copy" type="button">복사</button>
    </div>
  </section>

  <footer>.</footer>
</main>

<script>
(function () {
  var btn = document.getElementById("copy");
  var el = document.getElementById("email");
  btn.addEventListener("click", function () {
    function select() {
      var r = document.createRange(); r.selectNodeContents(el);
      var s = window.getSelection(); s.removeAllRanges(); s.addRange(r);
    }
    function done() { btn.textContent = "복사됨"; setTimeout(function () { btn.textContent = "복사"; }, 1500); }
    try {
      navigator.clipboard.writeText(el.textContent).then(done, select);
    } catch (e) { select(); }
  });
})();
</script>

</body></html>
