{::nomarkdown}
<style>
  .monk {
    --ink: #1a1510;
    --muted: #5c5348;
    --paper: #f4efe4;
    --felt: #1b4332;
    --card: #f7f3ea;
    --line: #e4dccb;
    --signal: #14181c;
    margin: 0 auto;
    max-width: 52rem;
    padding: 2.5rem 1.25rem 3.5rem;
    color: var(--ink);
    font-family: Georgia, "Iowan Old Style", Palatino, serif;
  }
  .monk * { box-sizing: border-box; }
  .monk h1 {
    margin: 0;
    font-size: clamp(2.4rem, 6vw, 3.4rem);
    font-weight: 700;
    letter-spacing: 0.08em;
    line-height: 1;
  }
  .monk .lede {
    max-width: 36rem;
    margin: 0.85rem 0 0;
    color: var(--muted);
    font-size: 1.15rem;
    line-height: 1.5;
  }
  .monk .apps {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1rem;
    margin-top: 2rem;
  }
  .monk article {
    display: flex;
    flex-direction: column;
    min-height: 22rem;
    padding: 1.35rem 1.35rem 1.2rem;
    border-radius: 1.1rem;
    text-decoration: none;
  }
  .monk .belot { background: var(--felt); color: #f3e6c9; }
  .monk .morse { background: var(--signal); color: #f4efe4; }
  .monk .mark { height: 4.6rem; margin-bottom: 1.1rem; }
  .monk h2 {
    margin: 0;
    font-size: 1.7rem;
    line-height: 1.15;
    font-weight: 700;
  }
  .monk article p {
    margin: 0.55rem 0 0;
    line-height: 1.45;
    font-size: 1.05rem;
  }
  .monk .belot p { color: #d7cbb4; }
  .monk .morse p { color: #c5c1b8; }
  .monk .actions {
    display: flex;
    flex-wrap: wrap;
    gap: 0.45rem 0.9rem;
    align-items: center;
    margin-top: auto;
    padding-top: 1.4rem;
  }
  .monk .play {
    display: inline-block;
    padding: 0.45rem 0.8rem;
    border-radius: 999px;
    background: #f3e6c9;
    color: #1a1510;
    font-family: system-ui, sans-serif;
    font-size: 0.82rem;
    font-weight: 700;
    letter-spacing: 0.02em;
    text-decoration: none;
  }
  .monk .morse .play { background: #f4efe4; }
  .monk .legal {
    color: inherit;
    font-family: system-ui, sans-serif;
    font-size: 0.82rem;
    text-underline-offset: 0.18em;
  }
  .monk .belot .legal { color: #e7dcc6; }
  .monk .morse .legal { color: #ddd8cf; }
  .monk footer {
    margin-top: 1.5rem;
    color: var(--muted);
    font-size: 0.95rem;
  }
  .tape { display: flex; align-items: center; gap: 0.38rem; height: 4.6rem; }
  .tape i {
    display: block;
    background: #f4efe4;
    border-radius: 999px;
  }
  .tape .dot { width: 0.55rem; height: 0.55rem; }
  .tape .dash { width: 1.35rem; height: 0.42rem; }
  .tape .space { width: 0.55rem; background: transparent; }
  @media (max-width: 720px) {
    .monk .apps { grid-template-columns: 1fr; }
    .monk article { min-height: 0; }
  }
</style>
<div class="monk">
  <h1>MONK</h1>
  <p class="lede">Two apps on Google Play. The privacy policy, terms, and legal notice for each one are on this site.</p>
  <div class="apps">
    <article class="belot">
      <svg class="mark" viewBox="0 0 52 60" width="52" height="60" aria-hidden="true">
        <rect width="52" height="60" fill="#F3E6C9"/>
        <rect x="8" width="3" height="60" fill="#C23B22"/>
        <rect x="25.25" y="6" width="1.5" height="48" fill="#D4C4A0"/>
        <g fill="#1A1510">
          <rect x="14" y="14" width="8" height="2"/>
          <rect x="14" y="22" width="8" height="2"/>
          <rect x="14" y="30" width="8" height="2"/>
          <rect x="32" y="14" width="8" height="2"/>
          <rect x="32" y="22" width="8" height="2"/>
          <rect x="32" y="30" width="8" height="2"/>
        </g>
      </svg>
      <h2>Belot Score</h2>
      <p>Score pad for Moldovan Belot. Two columns or three players. The cards stay at the table.</p>
      <div class="actions">
        <a class="play" href="https://play.google.com/store/apps/details?id=com.production.monk.belotscore">Google Play</a>
        <a class="legal" href="belot-privacy-policy.html">Privacy</a>
        <a class="legal" href="belot-terms.html">Terms</a>
        <a class="legal" href="belot-imprint.html">Legal notice</a>
      </div>
    </article>
    <article class="morse">
      <div class="tape" aria-hidden="true">
        <i class="dot"></i><i class="dot"></i><i class="dot"></i>
        <i class="space"></i>
        <i class="dash"></i><i class="dash"></i><i class="dash"></i>
        <i class="space"></i>
        <i class="dot"></i><i class="dot"></i><i class="dot"></i>
      </div>
      <h2>Morse Code Translator</h2>
      <p>Text to Morse and Morse to text. Hear it, feel it, and quiz yourself on the alphabet.</p>
      <div class="actions">
        <a class="play" href="https://play.google.com/store/apps/details?id=com.programming.monk.morsecodetranslator">Google Play</a>
        <a class="legal" href="morse-privacy.html">Privacy</a>
        <a class="legal" href="morse-terms.html">Terms</a>
        <a class="legal" href="morse-imprint.html">Legal notice</a>
      </div>
    </article>
  </div>
  <footer>Cristian Lungu, Berlin</footer>
</div>
{:/nomarkdown}
