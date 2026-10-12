
```aura width=800 height=340 link="https://github.com/MoonRodri" inline align=center
<div style={{ display: 'flex', width: '100%', height: '100%', position: 'relative', overflow: 'hidden', borderRadius: '28px 28px 0 0', background: '#05060d', fontFamily: 'Inter, sans-serif' }}>
  <style>{`
    @keyframes drA { 0%, 100% { transform: translate(0, 0); opacity: 0.7; } 50% { transform: translate(34px, -18px); opacity: 1; } }
    @keyframes drB { 0%, 100% { transform: translate(0, 0); opacity: 0.65; } 50% { transform: translate(-30px, 16px); opacity: 1; } }
    @keyframes scanx { 0% { transform: translate(0, 0); } 100% { transform: translate(1200px, 0); } }
    #scanband { animation: scanx 4.5s linear infinite; }
    @keyframes pls { 0%, 100% { transform: scale(1); opacity: 0.6; } 50% { transform: scale(1.18); opacity: 0.9; } }
    #o1 { animation: drA 8s ease-in-out infinite 0s; }
    #o2 { animation: drB 9s ease-in-out infinite 0.3s; }
    #o3 { animation: drA 7s ease-in-out infinite 0.6s; }
    #o4 { animation: pls 6s ease-in-out infinite 0s; transform-box: fill-box; transform-origin: center; }
    #o5 { animation: drB 9s ease-in-out infinite 0.3s; }

    @keyframes spin { to { transform: rotate(360deg); } }
    #ring { transform-box: fill-box; transform-origin: center; animation: spin 20s linear infinite; }
    @keyframes bar { 0%, 100% { opacity: 0.25; } 50% { opacity: 1; } }
    #sb1 { animation: bar 1.6s ease-in-out infinite; } #sb2 { animation: bar 1.6s ease-in-out infinite 0.2s; }
    #sb3 { animation: bar 1.6s ease-in-out infinite 0.4s; } #sb4 { animation: bar 1.6s ease-in-out infinite 0.6s; }
    @keyframes halo { 0% { opacity: 0.6; } 100% { opacity: 1; } }
    #mh { animation: halo 6s ease-in-out infinite alternate; }
  `}</style>
  <svg width="800" height="340" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="bgR" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(255,59,78,0.5)" /><stop offset="100%" stopColor="rgba(255,59,78,0)" /></radialGradient>
      <radialGradient id="bgC" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(25,227,242,0.45)" /><stop offset="100%" stopColor="rgba(25,227,242,0)" /></radialGradient>
      <radialGradient id="bgD" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(170,28,56,0.45)" /><stop offset="100%" stopColor="rgba(170,28,56,0)" /></radialGradient>
      <radialGradient id="bgT" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(15,165,179,0.38)" /><stop offset="100%" stopColor="rgba(15,165,179,0)" /></radialGradient>
      <linearGradient id="bgScan" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" stopColor="rgba(25,227,242,0)" /><stop offset="40%" stopColor="rgba(25,227,242,0.12)" /><stop offset="50%" stopColor="rgba(255,120,140,0.45)" /><stop offset="60%" stopColor="rgba(25,227,242,0.12)" /><stop offset="100%" stopColor="rgba(25,227,242,0)" /></linearGradient>
      <linearGradient id="bgBorder" gradientUnits="userSpaceOnUse" x1="0" y1="0" x2="0" y2="1556"><stop offset="0%" stopColor="#19e3f2" /><stop offset="100%" stopColor="#ff3b4e" /></linearGradient>
      <pattern id="bgGrid" width="40" height="40" patternUnits="userSpaceOnUse"><path d="M 40 0 L 0 0 0 40" fill="none" stroke="rgba(25,227,242,0.07)" strokeWidth="0.5" /></pattern>
    </defs>
    <g transform="translate(0 0)">
      <rect x="0" y="0" width="800" height="340" fill="url(#bgGrid)" />
      <circle cx="131" cy="31" r="1.4" fill="#7ef0fa" opacity="0.3"><animate attributeName="opacity" values="0;0.51;0.51;0" keyTimes="0;0.4;0.6;1" dur="5.2s" begin="-6.6s" repeatCount="indefinite" /></circle>
      <circle cx="236" cy="111" r="0.6" fill="#7ef0fa" opacity="0.3"><animate attributeName="opacity" values="0;0.53;0.53;0" keyTimes="0;0.4;0.6;1" dur="6.3s" begin="-0.6s" repeatCount="indefinite" /></circle>
      <circle cx="511" cy="163" r="2.2" fill="#ffffff" opacity="0.3"><animate attributeName="opacity" values="0;0.25;0.25;0" keyTimes="0;0.4;0.6;1" dur="7.6s" begin="-6.7s" repeatCount="indefinite" /></circle>
      <circle cx="745" cy="311" r="2.1" fill="#ffffff" opacity="0.3"><animate attributeName="opacity" values="0;0.38;0.38;0" keyTimes="0;0.4;0.6;1" dur="8.6s" begin="-1.1s" repeatCount="indefinite" /></circle>
      <circle cx="238" cy="278" r="1.8" fill="#7ef0fa" opacity="0.3"><animate attributeName="opacity" values="0;0.39;0.39;0" keyTimes="0;0.4;0.6;1" dur="5.8s" begin="-7.2s" repeatCount="indefinite" /></circle>
      <circle cx="491" cy="122" r="0.9" fill="#ffffff" opacity="0.3"><animate attributeName="opacity" values="0;0.27;0.27;0" keyTimes="0;0.4;0.6;1" dur="9.5s" begin="-4.5s" repeatCount="indefinite" /></circle>
      <circle cx="203" cy="80" r="1.1" fill="#7ef0fa" opacity="0.3"><animate attributeName="opacity" values="0;0.29;0.29;0" keyTimes="0;0.4;0.6;1" dur="8.4s" begin="-4.0s" repeatCount="indefinite" /></circle>
      <ellipse id="o1" cx="200" cy="140" rx="180" ry="110" fill="url(#bgR)" />
      <ellipse id="o2" cx="620" cy="160" rx="160" ry="95" fill="url(#bgC)" />
      <ellipse id="o3" cx="420" cy="110" rx="140" ry="90" fill="url(#bgD)" />
      <ellipse id="o4" cx="100" cy="180" rx="120" ry="80" fill="url(#bgT)" />
      <ellipse id="o5" cx="400" cy="359" rx="300" ry="55" fill="url(#bgR)" />
      <rect id="scanband" x="-400" y="120" width="400" height="40" fill="url(#bgScan)" opacity="0.35" />
      <path d="M 0.75 340 V 28 A 28 28 0 0 1 28 0.75 H 772 A 28 28 0 0 1 799.25 28 V 340" fill="none" stroke="url(#bgBorder)" strokeWidth="1.5" strokeOpacity="0.55" />
    </g>
  </svg>
  {(() => {
    const BIO = 'Learning Software Development by building random fun things.';
    const FIXED_PHASE = null;
    const SYN = 29.530588853;
    const days = (Date.now() - Date.UTC(2000, 0, 6, 18, 14)) / 86400000;
    const live = (((days % SYN) + SYN) % SYN) / SYN;
    const p = FIXED_PHASE === null ? live : FIXED_PHASE;
    const c = Math.cos(2 * Math.PI * p);
    const lit = (1 - c) / 2;
    const names = ['new moon', 'waxing crescent', 'first quarter', 'waxing gibbous', 'full moon', 'waning gibbous', 'last quarter', 'waning crescent'];
    const label = names[Math.floor(p * 8 + 0.5) % 8];
    const cx = 690, cy = 172, r = 48;
    const waxing = p < 0.5;
    const gib = c < 0;
    const rx = Math.abs(c) * r;
    const s1 = waxing ? 1 : 0;
    const s2 = waxing ? (gib ? 1 : 0) : (gib ? 0 : 1);
    const d = `M ${cx} ${cy - r} A ${r} ${r} 0 0 ${s1} ${cx} ${cy + r} A ${rx} ${r} 0 0 ${s2} ${cx} ${cy - r} Z`;
    const t = new Date();
    const pad = (n) => String(n).padStart(2, '0');
    const sync = 'SYNC // ' + pad(t.getUTCHours()) + ':' + pad(t.getUTCMinutes()) + ':' + pad(t.getUTCSeconds()) + ' UTC';
    const u = github && github.user ? github.user : null;
    const name = (u && (u.name || u.login)) || 'Rodri';
    const nameSize = name.length <= 9 ? 56 : name.length <= 13 ? 46 : 38;
    const login = (u && u.login) || 'MoonRodri';
    const bio = BIO || (u && u.bio) || '';
    const loc = u && u.location;
    const foll = u ? u.followers : null;
    const avatar = (u && u.avatarUrl) || 'https://github.com/MoonRodri.png';
    return [
      <svg width="800" height="340" style={{ position: 'absolute', top: 0, left: 0 }}>
        <defs>
          <radialGradient id="mBody" cx="35%" cy="30%" r="85%"><stop offset="0%" stopColor="#ffffff" /><stop offset="55%" stopColor="#c8f8fc" /><stop offset="100%" stopColor="#5fc3cf" /></radialGradient>
          <radialGradient id="mDark" cx="40%" cy="35%" r="80%"><stop offset="0%" stopColor="#3a1219" /><stop offset="100%" stopColor="#160a0d" /></radialGradient>
          <radialGradient id="mHalo" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(25,227,242,0.4)" /><stop offset="100%" stopColor="rgba(25,227,242,0)" /></radialGradient>
          <clipPath id="mLit"><path d={d} /></clipPath>
        </defs>
        <path d="M 34 64 L 34 34 L 64 34" fill="none" stroke="#19e3f2" strokeWidth="2" strokeOpacity="0.8" strokeLinecap="round" />
        <path d="M 766 64 L 766 34 L 736 34" fill="none" stroke="#19e3f2" strokeWidth="2" strokeOpacity="0.8" strokeLinecap="round" />
        <rect id="sb1" x="696" y="38" width="4" height="8" fill="#19e3f2" />
        <rect id="sb2" x="704" y="34" width="4" height="12" fill="#19e3f2" />
        <rect id="sb3" x="712" y="30" width="4" height="16" fill="#19e3f2" />
        <rect id="sb4" x="720" y="26" width="4" height="20" fill="#19e3f2" />
        <g id="ring">
          <circle cx="130" cy="174" r="88" fill="none" stroke="#19e3f2" strokeWidth="2" strokeDasharray="150 403" strokeLinecap="round" />
          <circle cx="130" cy="174" r="88" fill="none" stroke="#ff3b4e" strokeWidth="2" strokeDasharray="70 483" strokeDashoffset="-300" strokeLinecap="round" />
        </g>
        <circle cx="130" cy="174" r="80" fill="none" stroke="rgba(244,238,240,0.16)" strokeWidth="1" />
        <g opacity={0.4 + 0.6 * lit}><circle id="mh" cx={cx} cy={cy} r="105" fill="url(#mHalo)" /></g>
        <g transform={`rotate(-16 ${cx} ${cy})`}>
          <ellipse cx={cx} cy={cy} rx="88" ry="26" fill="none" stroke="rgba(255,59,78,0.4)" strokeWidth="1" strokeDasharray="2 6" />
          <circle cx={cx + 88} cy={cy} r="3.5" fill="#ff3b4e">
            <animateMotion dur="14s" repeatCount="indefinite" path="M 0 0 a 88 26 0 1 0 -176 0 a 88 26 0 1 0 176 0" />
          </circle>
        </g>
        <circle cx={cx} cy={cy} r={r} fill="url(#mDark)" />
        <circle cx={cx} cy={cy} r={r} fill="none" stroke="rgba(25,227,242,0.5)" strokeWidth="1.2" />
        <path d={d} fill="url(#mBody)" />
        <g clipPath="url(#mLit)" fill="rgba(60,150,165,0.35)">
          <circle cx={cx - 17} cy={cy - 13} r="8" /><circle cx={cx + 13} cy={cy + 12} r="10" /><circle cx={cx - 8} cy={cy + 24} r="5" />
        </g>
      </svg>,
      <img src={avatar} width={148} height={148} style={{ position: 'absolute', left: 56, top: 100, width: 148, height: 148, borderRadius: 74, objectFit: 'cover' }} />,
      <div style={{ display: 'flex', position: 'absolute', left: 78, top: 27 }}>
        <span style={{ fontSize: 13, color: '#19e3f2', letterSpacing: 1.5 }}>{sync}</span>
      </div>,
      <div style={{ display: 'flex', position: 'absolute', left: 242, top: 96, width: 380, height: 66 }}>
        <span style={{ fontSize: nameSize, fontWeight: 700, color: '#f4eef0', letterSpacing: -1, textShadow: '0 0 12px rgba(25,227,242,0.8), 0 0 30px rgba(255,59,78,0.4)' }}>{name}</span>
      </div>,
      <div style={{ display: 'flex', position: 'absolute', left: 242, top: 168 }}>
        <span style={{ fontSize: 18, color: '#19e3f2' }}>{'@' + login}</span>
      </div>,
      <div style={{ display: 'flex', position: 'absolute', left: 242, top: 200, width: 360 }}>
        <span style={{ fontSize: 17, color: '#a9a3ad', lineHeight: 1.45 }}>{bio}</span>
      </div>,
      <div style={{ display: 'flex', position: 'absolute', left: 242, top: 266 }}>
        {loc ? (
          <div style={{ display: 'flex', alignItems: 'center', marginRight: 18 }}>
            <div style={{ width: 8, height: 8, background: '#ff3b4e', marginRight: 8 }} />
            <span style={{ fontSize: 14, color: '#f4eef0' }}>{loc}</span>
          </div>
        ) : null}
        {foll !== null ? (
          <div style={{ display: 'flex', alignItems: 'center' }}>
            <div style={{ width: 8, height: 8, background: '#19e3f2', marginRight: 8 }} />
            <span style={{ fontSize: 14, color: '#f4eef0' }}>{foll + ' followers'}</span>
          </div>
        ) : null}
      </div>,
      <div style={{ display: 'flex', position: 'absolute', left: cx - 120, top: cy + r + 26, width: 240, justifyContent: 'center' }}>
        <span style={{ fontSize: 13, color: '#a9a3ad' }}>{'MOON // ' + label + ' ' + Math.round(lit * 100) + '%'}</span>
      </div>
    ];
  })()}
</div>
```

```aura width=800 height=744 inline align=center
(() => {
  const STACK = [
    { title: 'Mobile Development', color: 'cyan', items: ['Kotlin', 'Android Studio', 'Dart & Flutter'] },
    { title: 'Backend & Data', color: 'red', items: ['Java', 'Spring Boot', 'MySQL', 'PostgreSQL', 'Python'] },
    { title: 'Other tools', color: 'soft', items: ['Git', 'HTML', 'CSS', 'JavaScript', 'MongoDB', 'Ollama', 'Agentic AI'] },
  ];
  const TONES = { cyan: ['#19e3f2', '25,227,242'], red: ['#ff3b4e', '255,59,78'], soft: ['#7ef0fa', '126,240,250'] };
  const RINGS = [[50, 16], [88, 28], [126, 44]];
  return (
<div style={{ display: 'flex', flexDirection: 'column', width: '100%', height: '100%', position: 'relative', overflow: 'hidden', background: '#05060d', fontFamily: 'Inter, sans-serif' }}>
  <style>{`
    @keyframes drA { 0%, 100% { transform: translate(0, 0); opacity: 0.7; } 50% { transform: translate(34px, -18px); opacity: 1; } }
    @keyframes drB { 0%, 100% { transform: translate(0, 0); opacity: 0.65; } 50% { transform: translate(-30px, 16px); opacity: 1; } }
    @keyframes scanx { 0% { transform: translate(0, 0); } 100% { transform: translate(1200px, 0); } }
    #scanband { animation: scanx 4.5s linear infinite; }
    @keyframes pls { 0%, 100% { transform: scale(1); opacity: 0.6; } 50% { transform: scale(1.18); opacity: 0.9; } }
    #o5 { animation: drB 9s ease-in-out infinite 0.3s; }
    #o6 { animation: drA 8s ease-in-out infinite 0s; }
    #o7 { animation: drA 7s ease-in-out infinite 0.6s; }
`}</style>
  <svg width="800" height="744" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="bgR" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(255,59,78,0.5)" /><stop offset="100%" stopColor="rgba(255,59,78,0)" /></radialGradient>
      <radialGradient id="bgC" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(25,227,242,0.45)" /><stop offset="100%" stopColor="rgba(25,227,242,0)" /></radialGradient>
      <radialGradient id="bgD" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(170,28,56,0.45)" /><stop offset="100%" stopColor="rgba(170,28,56,0)" /></radialGradient>
      <radialGradient id="bgT" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(15,165,179,0.38)" /><stop offset="100%" stopColor="rgba(15,165,179,0)" /></radialGradient>
      <linearGradient id="bgScan" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" stopColor="rgba(25,227,242,0)" /><stop offset="40%" stopColor="rgba(25,227,242,0.12)" /><stop offset="50%" stopColor="rgba(255,120,140,0.45)" /><stop offset="60%" stopColor="rgba(25,227,242,0.12)" /><stop offset="100%" stopColor="rgba(25,227,242,0)" /></linearGradient>
      <linearGradient id="bgBorder" gradientUnits="userSpaceOnUse" x1="0" y1="0" x2="0" y2="1556"><stop offset="0%" stopColor="#19e3f2" /><stop offset="100%" stopColor="#ff3b4e" /></linearGradient>
      <pattern id="bgGrid" width="40" height="40" patternUnits="userSpaceOnUse"><path d="M 40 0 L 0 0 0 40" fill="none" stroke="rgba(25,227,242,0.07)" strokeWidth="0.5" /></pattern>
    </defs>
    <g transform="translate(0 -340)">
      <rect x="0" y="340" width="800" height="744" fill="url(#bgGrid)" />
      <circle cx="363" cy="870" r="2.1" fill="#ffffff" opacity="0.3"><animate attributeName="opacity" values="0;0.51;0.51;0" keyTimes="0;0.4;0.6;1" dur="7.7s" begin="-2.1s" repeatCount="indefinite" /></circle>
      <circle cx="638" cy="741" r="1.6" fill="#ffffff" opacity="0.3"><animate attributeName="opacity" values="0;0.34;0.34;0" keyTimes="0;0.4;0.6;1" dur="5.6s" begin="-1.0s" repeatCount="indefinite" /></circle>
      <circle cx="643" cy="1076" r="0.7" fill="#ffffff" opacity="0.3"><animate attributeName="opacity" values="0;0.45;0.45;0" keyTimes="0;0.4;0.6;1" dur="10.8s" begin="-6.8s" repeatCount="indefinite" /></circle>
      <circle cx="618" cy="510" r="1.5" fill="#ffffff" opacity="0.3"><animate attributeName="opacity" values="0;0.44;0.44;0" keyTimes="0;0.4;0.6;1" dur="8.1s" begin="-5.5s" repeatCount="indefinite" /></circle>
      <circle cx="527" cy="712" r="1.0" fill="#7ef0fa" opacity="0.3"><animate attributeName="opacity" values="0;0.5;0.5;0" keyTimes="0;0.4;0.6;1" dur="11.0s" begin="-7.8s" repeatCount="indefinite" /></circle>
      <circle cx="255" cy="362" r="1.1" fill="#7ef0fa" opacity="0.3"><animate attributeName="opacity" values="0;0.28;0.28;0" keyTimes="0;0.4;0.6;1" dur="8.4s" begin="-1.2s" repeatCount="indefinite" /></circle>
      <circle cx="76" cy="520" r="2.1" fill="#7ef0fa" opacity="0.3"><animate attributeName="opacity" values="0;0.46;0.46;0" keyTimes="0;0.4;0.6;1" dur="5.8s" begin="-0.1s" repeatCount="indefinite" /></circle>
      <circle cx="373" cy="758" r="1.7" fill="#ffffff" opacity="0.3"><animate attributeName="opacity" values="0;0.31;0.31;0" keyTimes="0;0.4;0.6;1" dur="7.7s" begin="-8.1s" repeatCount="indefinite" /></circle>
      <circle cx="111" cy="999" r="0.8" fill="#ffffff" opacity="0.3"><animate attributeName="opacity" values="0;0.25;0.25;0" keyTimes="0;0.4;0.6;1" dur="10.9s" begin="-9.5s" repeatCount="indefinite" /></circle>
      <circle cx="772" cy="921" r="2.2" fill="#7ef0fa" opacity="0.3"><animate attributeName="opacity" values="0;0.37;0.37;0" keyTimes="0;0.4;0.6;1" dur="6.3s" begin="-9.4s" repeatCount="indefinite" /></circle>
      <circle cx="659" cy="603" r="0.7" fill="#ffffff" opacity="0.3"><animate attributeName="opacity" values="0;0.32;0.32;0" keyTimes="0;0.4;0.6;1" dur="8.5s" begin="-6.6s" repeatCount="indefinite" /></circle>
      <circle cx="299" cy="706" r="2.1" fill="#ffffff" opacity="0.3"><animate attributeName="opacity" values="0;0.29;0.29;0" keyTimes="0;0.4;0.6;1" dur="10.0s" begin="-4.2s" repeatCount="indefinite" /></circle>
      <circle cx="500" cy="487" r="1.0" fill="#7ef0fa" opacity="0.3"><animate attributeName="opacity" values="0;0.31;0.31;0" keyTimes="0;0.4;0.6;1" dur="6.5s" begin="-8.1s" repeatCount="indefinite" /></circle>
      <circle cx="581" cy="499" r="2.2" fill="#7ef0fa" opacity="0.3"><animate attributeName="opacity" values="0;0.36;0.36;0" keyTimes="0;0.4;0.6;1" dur="7.7s" begin="-0.5s" repeatCount="indefinite" /></circle>
      <circle cx="691" cy="650" r="1.9" fill="#ffffff" opacity="0.3"><animate attributeName="opacity" values="0;0.44;0.44;0" keyTimes="0;0.4;0.6;1" dur="8.4s" begin="-4.2s" repeatCount="indefinite" /></circle>
      <circle cx="465" cy="946" r="0.7" fill="#7ef0fa" opacity="0.3"><animate attributeName="opacity" values="0;0.51;0.51;0" keyTimes="0;0.4;0.6;1" dur="11.0s" begin="-8.0s" repeatCount="indefinite" /></circle>
      <circle cx="411" cy="486" r="0.7" fill="#7ef0fa" opacity="0.3"><animate attributeName="opacity" values="0;0.46;0.46;0" keyTimes="0;0.4;0.6;1" dur="6.4s" begin="-5.5s" repeatCount="indefinite" /></circle>
      <ellipse id="o5" cx="400" cy="359" rx="300" ry="55" fill="url(#bgR)" />
      <ellipse id="o6" cx="650" cy="538" rx="180" ry="100" fill="url(#bgT)" />
      <ellipse id="o7" cx="400" cy="948" rx="260" ry="75" fill="url(#bgD)" />

      <path d="M 0.75 340 V 1084" fill="none" stroke="url(#bgBorder)" strokeWidth="1.5" strokeOpacity="0.55" />
      <path d="M 799.25 340 V 1084" fill="none" stroke="url(#bgBorder)" strokeWidth="1.5" strokeOpacity="0.55" />
    </g>
  </svg>
  <svg width="800" height="744" style={{ position: 'absolute', top: 0, left: 0 }}>
    <g>
      <defs><radialGradient id="stCore" cx="35%" cy="30%" r="85%"><stop offset="0%" stopColor="#ffffff" /><stop offset="100%" stopColor="#7a5a60" /></radialGradient></defs>
      {RINGS.map(([rr], gi) => (
        <circle cx="620" cy="174" r={rr} fill="none" stroke={(TONES[(STACK[gi] || STACK[0]).color] || TONES.cyan)[0]} strokeOpacity="0.35" strokeWidth="1.2" />
      ))}
      <circle cx="620" cy="174" r="16" fill="url(#stCore)" />
      <circle cx="620" cy="174" r="22" fill="none" stroke="rgba(244,238,240,0.25)" strokeWidth="1" />
      {RINGS.map(([rr, dur], gi) => {
        const g = STACK[gi];
        if (!g) return null;
        const col = (TONES[g.color] || TONES.cyan)[0];
        return Array.from({ length: g.items.length }).map((_, i) => (
          <circle cx={620 + rr} cy="174" r="5" fill={col}>
            <animateMotion dur={dur + 's'} begin={'-' + ((dur * i) / g.items.length) + 's'} repeatCount="indefinite" path={`M 0 0 a ${rr} ${rr} 0 1 0 ${-2 * rr} 0 a ${rr} ${rr} 0 1 0 ${2 * rr} 0`} />
          </circle>
        ));
      })}
    </g>
    <g transform="translate(0 360)">
      {(() => {
        
    const raw = (typeof process !== 'undefined' && process.env && process.env.CONTRIB_WEEKS) || '';
    let weeks = [];
    try { weeks = JSON.parse(raw); } catch (e) { weeks = []; }
    const hasData = Array.isArray(weeks) && weeks.length > 0;
    if (!hasData) weeks = Array.from({ length: 53 }).map(() => [0, 0, 0, 0, 0, 0, 0]);
    weeks = weeks.slice(-53);
    const flat = weeks.flat().filter((x) => x >= 0);
    const total = flat.reduce((a, b) => a + b, 0);
    const best = flat.length ? Math.max(...flat) : 0;
    let streak = 0;
    { let i = flat.length - 1; if (i >= 0 && flat[i] === 0) i--; while (i >= 0 && flat[i] > 0) { streak++; i--; } }

        const P = 13.5, X0 = 40, Y0 = 86;
        const maxc = Math.max(1, best);
        const lvl = (c) => (c <= 0 ? 0 : Math.min(4, Math.max(1, Math.ceil((4 * c) / maxc))));
        const COLORS = ['rgba(244,238,240,0.07)', '#0f6d78', '#19e3f2', '#ff7a88', '#ff3b4e'];
        const cells = [];
        weeks.forEach((wk, w) => wk.forEach((c, dd) => {
          if (c < 0) return;
          cells.push(<rect x={X0 + w * P} y={Y0 + dd * P} width="10.5" height="10.5" rx="2.5" fill={COLORS[lvl(c)]} />);
        }));
        const sums = weeks.map((wk) => wk.reduce((a, c) => a + (c > 0 ? c : 0), 0));
        const smax = Math.max(1, ...sums);
        const pts = sums.map((s, i) => [X0 + i * P + 5, 270 - (s / smax) * 56]);
        let d = 'M ' + pts[0][0] + ' ' + pts[0][1];
        for (let i = 1; i < pts.length - 1; i++) {
          const mx = (pts[i][0] + pts[i + 1][0]) / 2, my = (pts[i][1] + pts[i + 1][1]) / 2;
          d += ' Q ' + pts[i][0] + ' ' + pts[i][1] + ' ' + mx + ' ' + my;
        }
        const last = pts[pts.length - 1];
        d += ' L ' + last[0] + ' ' + last[1];
        const area = d + ' L ' + last[0] + ' 276 L ' + pts[0][0] + ' 276 Z';
        return [
          <defs>
            <linearGradient id="pLine" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" stopColor="#19e3f2" /><stop offset="100%" stopColor="#ff3b4e" /></linearGradient>
            <linearGradient id="pArea" x1="0%" y1="0%" x2="0%" y2="100%"><stop offset="0%" stopColor="rgba(25,227,242,0.22)" /><stop offset="100%" stopColor="rgba(25,227,242,0)" /></linearGradient>
          </defs>,
          ...cells,
          <path d={area} fill="url(#pArea)" />,
          <line x1="40" y1="276" x2="755" y2="276" stroke="rgba(244,238,240,0.12)" strokeWidth="1" />,
          <path d={d} fill="none" stroke="url(#pLine)" strokeWidth="2" strokeLinejoin="round" strokeLinecap="round" />,
          <rect x="40" y="196" width="1.5" height="84" fill="#ff3b4e" opacity="0.85">
            <animateTransform attributeName="transform" type="translate" values="0 0; 714 0; 714 0" keyTimes="0; 0.85; 1" dur="8s" repeatCount="indefinite" />
          </rect>
        ];
      })()}
    </g>
  </svg>
  <div style={{ display: 'flex', position: 'relative', width: '100%', height: 360 }}>
    <div style={{ display: 'flex', alignItems: 'center', position: 'absolute', left: 40, top: 28 }}><div style={{ width: 9, height: 9, background: '#ff3b4e', marginRight: 10 }} /><span style={{ fontSize: 22, fontWeight: 700, color: '#f4eef0' }}>Stack</span></div>
    <div style={{ display: 'flex', flexDirection: 'column', position: 'absolute', left: 40, top: 72, width: 456 }}>
      {STACK.map((g, gi) => {
        const tone = TONES[g.color] || TONES.cyan;
        return (
          <div style={{ display: 'flex', flexDirection: 'column', marginTop: gi === 0 ? 0 : 18 }}>
            <div style={{ display: 'flex', alignItems: 'center' }}>
              <div style={{ width: 10, height: 10, background: tone[0], marginRight: 10 }} />
              <span style={{ fontSize: 18, fontWeight: 700, color: tone[0] }}>{g.title}</span>
            </div>
            <div style={{ display: 'flex', flexWrap: 'wrap', marginTop: 10 }}>
              {g.items.map((t) => (
                <span style={{ fontSize: 14, color: '#f4eef0', padding: '5px 12px', borderRadius: 6, border: '1px solid rgba(' + tone[1] + ',0.5)', background: 'rgba(' + tone[1] + ',0.08)', marginRight: 8, marginBottom: 8 }}>{t}</span>
              ))}
            </div>
          </div>
        );
      })}
    </div>
  </div>
  <div style={{ display: 'flex', position: 'relative', width: '100%', height: 300 }}>
    <div style={{ display: 'flex', position: 'absolute', left: 40, top: 0, width: 720, height: 1, background: 'linear-gradient(90deg, rgba(25,227,242,0), rgba(25,227,242,0.45), rgba(255,59,78,0.45), rgba(255,59,78,0))' }} />
    <div style={{ display: 'flex', alignItems: 'center', position: 'absolute', left: 40, top: 28 }}><div style={{ width: 9, height: 9, background: '#ff3b4e', marginRight: 10 }} /><span style={{ fontSize: 22, fontWeight: 700, color: '#f4eef0' }}>Activity pulse</span></div>
    {(() => {
      
    const raw = (typeof process !== 'undefined' && process.env && process.env.CONTRIB_WEEKS) || '';
    let weeks = [];
    try { weeks = JSON.parse(raw); } catch (e) { weeks = []; }
    const hasData = Array.isArray(weeks) && weeks.length > 0;
    if (!hasData) weeks = Array.from({ length: 53 }).map(() => [0, 0, 0, 0, 0, 0, 0]);
    weeks = weeks.slice(-53);
    const flat = weeks.flat().filter((x) => x >= 0);
    const total = flat.reduce((a, b) => a + b, 0);
    const best = flat.length ? Math.max(...flat) : 0;
    let streak = 0;
    { let i = flat.length - 1; if (i >= 0 && flat[i] === 0) i--; while (i >= 0 && flat[i] > 0) { streak++; i--; } }

      const stat = (n, label, color) => (
        <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'flex-end', marginLeft: 26 }}>
          <span style={{ fontSize: 22, fontWeight: 700, color: '#f4eef0' }}>{String(n)}</span>
          <span style={{ fontSize: 13, color: color }}>{label}</span>
        </div>
      );
      return [
        <div style={{ display: 'flex', position: 'absolute', left: 40, top: 56 }}>
          <span style={{ fontSize: 13, color: '#a9a3ad' }}>Contributions over the last 12 months</span>
        </div>,
        <div style={{ display: 'flex', position: 'absolute', right: 40, top: 18 }}>
          {hasData ? [stat(total, 'contributions', '#19e3f2'), stat(streak, 'day streak', '#ff3b4e'), stat(best, 'best day', '#19e3f2')] : null}
        </div>,
        !hasData ? (
          <div style={{ display: 'flex', position: 'absolute', left: 40, top: 200, width: 720 }}>
            <span style={{ fontSize: 14, color: '#a9a3ad' }}>Waiting for contribution data. Add the "Fetch contribution calendar" step to the workflow.</span>
          </div>
        ) : null
      ];
    })()}
  </div>
  <div style={{ display: 'flex', position: 'relative', width: '100%', height: 84 }}>
    <div style={{ display: 'flex', position: 'absolute', left: 40, top: 0, width: 720, height: 1, background: 'linear-gradient(90deg, rgba(25,227,242,0), rgba(25,227,242,0.45), rgba(255,59,78,0.45), rgba(255,59,78,0))' }} />
    <div style={{ display: 'flex', alignItems: 'center', position: 'absolute', left: 40, top: 28 }}><div style={{ width: 9, height: 9, background: '#ff3b4e', marginRight: 10 }} /><span style={{ fontSize: 22, fontWeight: 700, color: '#f4eef0' }}>Projects</span></div>
    <div style={{ display: 'flex', position: 'absolute', left: 170, top: 33 }}>
      <span style={{ fontSize: 14, color: '#a9a3ad' }}>Click a card to open the repo</span>
    </div>
  </div>
</div>
  );
})()
```

```aura width=400 height=196 link="https://github.com/MoonRodri/Dynalar_frontend_v1" inline align=center
(() => {
  const PROJECT = {
    repo: 'Dynalar_frontend_v1',
    title: 'Dynalar',
    subtitle: 'Android app',
    description: 'Dental clinic management app. Android client in Kotlin and Jetpack Compose.',
    tags: ['Kotlin', 'Compose', 'Spring Boot'],
    icon: 'phone',
    accent: 'cyan',
  };
  const live = github && github.repos ? github.repos.find((r) => r.name === PROJECT.repo) : null;
  const title = PROJECT.title || PROJECT.repo;
  const desc = PROJECT.description || (live && live.description) || '';
  const tags = (PROJECT.tags || (live && live.language ? [live.language] : [])).slice(0, 4);
  const red = PROJECT.accent === 'red';
  const COL = red ? '#ff3b4e' : '#19e3f2';
  const RGB = red ? '255,59,78' : '25,227,242';
  const ICONS = {
    folder: ['M3 7h6l2 2h10v10H3z'],
    code: ['M8 8 3 12l5 4', 'M16 8l5 4-5 4', 'M14 5l-4 14'],
    phone: ['M7 2.5h10a1 1 0 0 1 1 1v17a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1v-17a1 1 0 0 1 1-1z', 'M10.5 18.5h3'],
    ai: ['M8 8h8v8H8z', 'M12 3v3', 'M12 18v3', 'M3 12h3', 'M18 12h3', 'M9.5 5l.5 3', 'M14.5 5l-.5 3'],
    game: ['M6 9h12a3.5 3.5 0 0 1 3.4 4.3l-.7 3a2.6 2.6 0 0 1-4.5.9L15 16H9l-1.2 1.2a2.6 2.6 0 0 1-4.5-.9l-.7-3A3.5 3.5 0 0 1 6 9z', 'M8 11.5v3', 'M6.5 13h3'],
    cart: ['M3 4h3l2.5 11h9.5L20 7H7', 'M9.5 19.5h.01', 'M17 19.5h.01'],
    chart: ['M4 20V11', 'M10 20V4', 'M16 20v-6', 'M2 20h20'],
    globe: ['M12 3a9 9 0 1 0 0 18 9 9 0 0 0 0-18z', 'M3 12h18', 'M12 3c3 3 3 15 0 18', 'M12 3c-3 3-3 15 0 18'],
  };
  const paths = ICONS[PROJECT.icon] || ICONS.folder;
  return (
    <div style={{ display: 'flex', width: '100%', height: '100%', position: 'relative', overflow: 'hidden', background: '#05060d', fontFamily: 'Inter, sans-serif' }}>
      <style>{`
    @keyframes drA { 0%, 100% { transform: translate(0, 0); opacity: 0.7; } 50% { transform: translate(34px, -18px); opacity: 1; } }
    @keyframes drB { 0%, 100% { transform: translate(0, 0); opacity: 0.65; } 50% { transform: translate(-30px, 16px); opacity: 1; } }
    @keyframes scanx { 0% { transform: translate(0, 0); } 100% { transform: translate(1200px, 0); } }
    #scanband { animation: scanx 4.5s linear infinite; }
    @keyframes pls { 0%, 100% { transform: scale(1); opacity: 0.6; } 50% { transform: scale(1.18); opacity: 0.9; } }

        @keyframes cb { 0%, 100% { opacity: 0.45; } 50% { opacity: 1; } }
        #cb1 { animation: cb 3s ease-in-out infinite; } #cb2 { animation: cb 3s ease-in-out infinite 0.4s; }
        #cb3 { animation: cb 3s ease-in-out infinite 0.8s; } #cb4 { animation: cb 3s ease-in-out infinite 1.2s; }
      `}</style>
      <svg width="400" height="196" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="bgR" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(255,59,78,0.5)" /><stop offset="100%" stopColor="rgba(255,59,78,0)" /></radialGradient>
      <radialGradient id="bgC" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(25,227,242,0.45)" /><stop offset="100%" stopColor="rgba(25,227,242,0)" /></radialGradient>
      <radialGradient id="bgD" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(170,28,56,0.45)" /><stop offset="100%" stopColor="rgba(170,28,56,0)" /></radialGradient>
      <radialGradient id="bgT" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(15,165,179,0.38)" /><stop offset="100%" stopColor="rgba(15,165,179,0)" /></radialGradient>
      <linearGradient id="bgScan" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" stopColor="rgba(25,227,242,0)" /><stop offset="40%" stopColor="rgba(25,227,242,0.12)" /><stop offset="50%" stopColor="rgba(255,120,140,0.45)" /><stop offset="60%" stopColor="rgba(25,227,242,0.12)" /><stop offset="100%" stopColor="rgba(25,227,242,0)" /></linearGradient>
      <linearGradient id="bgBorder" gradientUnits="userSpaceOnUse" x1="0" y1="0" x2="0" y2="1556"><stop offset="0%" stopColor="#19e3f2" /><stop offset="100%" stopColor="#ff3b4e" /></linearGradient>
      <pattern id="bgGrid" width="40" height="40" patternUnits="userSpaceOnUse"><path d="M 40 0 L 0 0 0 40" fill="none" stroke="rgba(25,227,242,0.07)" strokeWidth="0.5" /></pattern>
    </defs>
    <g transform="translate(0 -1084)">
      <rect x="0" y="1084" width="400" height="196" fill="url(#bgGrid)" />
      <circle cx="302" cy="1100" r="1.3" fill="#7ef0fa" opacity="0.3"><animate attributeName="opacity" values="0;0.48;0.48;0" keyTimes="0;0.4;0.6;1" dur="8.8s" begin="-3.0s" repeatCount="indefinite" /></circle>
      <circle cx="313" cy="1140" r="1.5" fill="#ffffff" opacity="0.3"><animate attributeName="opacity" values="0;0.41;0.41;0" keyTimes="0;0.4;0.6;1" dur="7.8s" begin="-5.7s" repeatCount="indefinite" /></circle>


      <path d="M 0.75 1084 V 1280" fill="none" stroke="url(#bgBorder)" strokeWidth="1.5" strokeOpacity="0.55" />
    </g>
  </svg>
      <svg width="400" height="196" style={{ position: 'absolute', top: 0, left: 0 }}>
        <rect x="16" y="12" width="368" height="172" rx="14" fill="rgba(6,8,16,0.92)" />
        <rect x="16" y="12" width="368" height="172" rx="14" fill="none" stroke={COL} strokeOpacity="0.28" strokeWidth="1" />
        <path id="cb1" d="M 16 28 L 16 12 L 32 12" fill="none" stroke={COL} strokeWidth="2" strokeLinecap="round" />
        <path id="cb2" d="M 368 12 L 384 12 L 384 28" fill="none" stroke={COL} strokeWidth="2" strokeLinecap="round" />
        <path id="cb3" d="M 16 168 L 16 184 L 32 184" fill="none" stroke={COL} strokeWidth="2" strokeLinecap="round" />
        <path id="cb4" d="M 384 168 L 384 184 L 368 184" fill="none" stroke={COL} strokeWidth="2" strokeLinecap="round" />
        <rect x="32" y="28" width="38" height="38" rx="9" fill={'rgba(' + RGB + ',0.12)'} stroke={COL} strokeOpacity="0.45" />
        <g transform="translate(40 36) scale(0.92)" fill="none" stroke={COL} strokeWidth="1.8" strokeLinecap="round" strokeLinejoin="round">
          {paths.map((pd) => <path d={pd} />)}
        </g>
        <g transform="translate(346 32)" fill="none" stroke="rgba(244,238,240,0.55)" strokeWidth="1.8" strokeLinecap="round" strokeLinejoin="round">
          <path d="M1 13 13 1" /><path d="M4 1h9v9" />
        </g>
      </svg>
      <div style={{ display: 'flex', flexDirection: 'column', position: 'absolute', left: 82, top: 28, width: 250 }}>
        <span style={{ fontSize: 20, fontWeight: 700, color: '#f4eef0', lineHeight: 1.15 }}>{title}</span>
        <span style={{ fontSize: 13, color: COL, marginTop: 4 }}>{PROJECT.subtitle || ''}</span>
      </div>
      <div style={{ display: 'flex', position: 'absolute', left: 32, top: 82, width: 336, height: 62, overflow: 'hidden' }}>
        <span style={{ fontSize: 14, color: '#a9a3ad', lineHeight: 1.45 }}>{desc}</span>
      </div>
      <div style={{ display: 'flex', position: 'absolute', left: 32, top: 152 }}>
        {tags.map((tg) => (
          <span style={{ fontSize: 12, color: '#f4eef0', padding: '3px 9px', borderRadius: 6, border: '1px solid rgba(' + RGB + ',0.5)', marginRight: 6 }}>{tg}</span>
        ))}
      </div>
    </div>
  );
})()
```

```aura width=400 height=196 link="https://github.com/MoonRodri/SuperHero-rag-chatbot" inline align=center
(() => {
  const PROJECT = {
    repo: 'SuperHero-rag-chatbot',
    title: 'SuperHero RAG chatbot',
    subtitle: 'Python / AI',
    description: 'A chatbot that answers questions using retrieval augmented generation.',
    tags: ['Python', 'RAG'],
    icon: 'ai',
    accent: 'red',
  };
  const live = github && github.repos ? github.repos.find((r) => r.name === PROJECT.repo) : null;
  const title = PROJECT.title || PROJECT.repo;
  const desc = PROJECT.description || (live && live.description) || '';
  const tags = (PROJECT.tags || (live && live.language ? [live.language] : [])).slice(0, 4);
  const red = PROJECT.accent === 'red';
  const COL = red ? '#ff3b4e' : '#19e3f2';
  const RGB = red ? '255,59,78' : '25,227,242';
  const ICONS = {
    folder: ['M3 7h6l2 2h10v10H3z'],
    code: ['M8 8 3 12l5 4', 'M16 8l5 4-5 4', 'M14 5l-4 14'],
    phone: ['M7 2.5h10a1 1 0 0 1 1 1v17a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1v-17a1 1 0 0 1 1-1z', 'M10.5 18.5h3'],
    ai: ['M8 8h8v8H8z', 'M12 3v3', 'M12 18v3', 'M3 12h3', 'M18 12h3', 'M9.5 5l.5 3', 'M14.5 5l-.5 3'],
    game: ['M6 9h12a3.5 3.5 0 0 1 3.4 4.3l-.7 3a2.6 2.6 0 0 1-4.5.9L15 16H9l-1.2 1.2a2.6 2.6 0 0 1-4.5-.9l-.7-3A3.5 3.5 0 0 1 6 9z', 'M8 11.5v3', 'M6.5 13h3'],
    cart: ['M3 4h3l2.5 11h9.5L20 7H7', 'M9.5 19.5h.01', 'M17 19.5h.01'],
    chart: ['M4 20V11', 'M10 20V4', 'M16 20v-6', 'M2 20h20'],
    globe: ['M12 3a9 9 0 1 0 0 18 9 9 0 0 0 0-18z', 'M3 12h18', 'M12 3c3 3 3 15 0 18', 'M12 3c-3 3-3 15 0 18'],
  };
  const paths = ICONS[PROJECT.icon] || ICONS.folder;
  return (
    <div style={{ display: 'flex', width: '100%', height: '100%', position: 'relative', overflow: 'hidden', background: '#05060d', fontFamily: 'Inter, sans-serif' }}>
      <style>{`
    @keyframes drA { 0%, 100% { transform: translate(0, 0); opacity: 0.7; } 50% { transform: translate(34px, -18px); opacity: 1; } }
    @keyframes drB { 0%, 100% { transform: translate(0, 0); opacity: 0.65; } 50% { transform: translate(-30px, 16px); opacity: 1; } }
    @keyframes scanx { 0% { transform: translate(0, 0); } 100% { transform: translate(1200px, 0); } }
    #scanband { animation: scanx 4.5s linear infinite; }
    @keyframes pls { 0%, 100% { transform: scale(1); opacity: 0.6; } 50% { transform: scale(1.18); opacity: 0.9; } }

        @keyframes cb { 0%, 100% { opacity: 0.45; } 50% { opacity: 1; } }
        #cb1 { animation: cb 3s ease-in-out infinite; } #cb2 { animation: cb 3s ease-in-out infinite 0.4s; }
        #cb3 { animation: cb 3s ease-in-out infinite 0.8s; } #cb4 { animation: cb 3s ease-in-out infinite 1.2s; }
      `}</style>
      <svg width="400" height="196" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="bgR" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(255,59,78,0.5)" /><stop offset="100%" stopColor="rgba(255,59,78,0)" /></radialGradient>
      <radialGradient id="bgC" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(25,227,242,0.45)" /><stop offset="100%" stopColor="rgba(25,227,242,0)" /></radialGradient>
      <radialGradient id="bgD" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(170,28,56,0.45)" /><stop offset="100%" stopColor="rgba(170,28,56,0)" /></radialGradient>
      <radialGradient id="bgT" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(15,165,179,0.38)" /><stop offset="100%" stopColor="rgba(15,165,179,0)" /></radialGradient>
      <linearGradient id="bgScan" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" stopColor="rgba(25,227,242,0)" /><stop offset="40%" stopColor="rgba(25,227,242,0.12)" /><stop offset="50%" stopColor="rgba(255,120,140,0.45)" /><stop offset="60%" stopColor="rgba(25,227,242,0.12)" /><stop offset="100%" stopColor="rgba(25,227,242,0)" /></linearGradient>
      <linearGradient id="bgBorder" gradientUnits="userSpaceOnUse" x1="0" y1="0" x2="0" y2="1556"><stop offset="0%" stopColor="#19e3f2" /><stop offset="100%" stopColor="#ff3b4e" /></linearGradient>
      <pattern id="bgGrid" width="40" height="40" patternUnits="userSpaceOnUse"><path d="M 40 0 L 0 0 0 40" fill="none" stroke="rgba(25,227,242,0.07)" strokeWidth="0.5" /></pattern>
    </defs>
    <g transform="translate(-400 -1084)">
      <rect x="400" y="1084" width="400" height="196" fill="url(#bgGrid)" />
      <circle cx="742" cy="1143" r="0.8" fill="#ff8a96" opacity="0.3"><animate attributeName="opacity" values="0;0.46;0.46;0" keyTimes="0;0.4;0.6;1" dur="7.1s" begin="-9.9s" repeatCount="indefinite" /></circle>


      <path d="M 799.25 1084 V 1280" fill="none" stroke="url(#bgBorder)" strokeWidth="1.5" strokeOpacity="0.55" />
    </g>
  </svg>
      <svg width="400" height="196" style={{ position: 'absolute', top: 0, left: 0 }}>
        <rect x="16" y="12" width="368" height="172" rx="14" fill="rgba(6,8,16,0.92)" />
        <rect x="16" y="12" width="368" height="172" rx="14" fill="none" stroke={COL} strokeOpacity="0.28" strokeWidth="1" />
        <path id="cb1" d="M 16 28 L 16 12 L 32 12" fill="none" stroke={COL} strokeWidth="2" strokeLinecap="round" />
        <path id="cb2" d="M 368 12 L 384 12 L 384 28" fill="none" stroke={COL} strokeWidth="2" strokeLinecap="round" />
        <path id="cb3" d="M 16 168 L 16 184 L 32 184" fill="none" stroke={COL} strokeWidth="2" strokeLinecap="round" />
        <path id="cb4" d="M 384 168 L 384 184 L 368 184" fill="none" stroke={COL} strokeWidth="2" strokeLinecap="round" />
        <rect x="32" y="28" width="38" height="38" rx="9" fill={'rgba(' + RGB + ',0.12)'} stroke={COL} strokeOpacity="0.45" />
        <g transform="translate(40 36) scale(0.92)" fill="none" stroke={COL} strokeWidth="1.8" strokeLinecap="round" strokeLinejoin="round">
          {paths.map((pd) => <path d={pd} />)}
        </g>
        <g transform="translate(346 32)" fill="none" stroke="rgba(244,238,240,0.55)" strokeWidth="1.8" strokeLinecap="round" strokeLinejoin="round">
          <path d="M1 13 13 1" /><path d="M4 1h9v9" />
        </g>
      </svg>
      <div style={{ display: 'flex', flexDirection: 'column', position: 'absolute', left: 82, top: 28, width: 250 }}>
        <span style={{ fontSize: 20, fontWeight: 700, color: '#f4eef0', lineHeight: 1.15 }}>{title}</span>
        <span style={{ fontSize: 13, color: COL, marginTop: 4 }}>{PROJECT.subtitle || ''}</span>
      </div>
      <div style={{ display: 'flex', position: 'absolute', left: 32, top: 82, width: 336, height: 62, overflow: 'hidden' }}>
        <span style={{ fontSize: 14, color: '#a9a3ad', lineHeight: 1.45 }}>{desc}</span>
      </div>
      <div style={{ display: 'flex', position: 'absolute', left: 32, top: 152 }}>
        {tags.map((tg) => (
          <span style={{ fontSize: 12, color: '#f4eef0', padding: '3px 9px', borderRadius: 6, border: '1px solid rgba(' + RGB + ',0.5)', marginRight: 6 }}>{tg}</span>
        ))}
      </div>
    </div>
  );
})()
```

```aura width=400 height=196 link="https://github.com/MoonRodri/Brawl-Stars-v0-" inline align=center
(() => {
  const PROJECT = {
    repo: 'Brawl-Stars-v0-',
    title: 'Brawl Stars v0',
    subtitle: 'Java game',
    description: 'Light version of Brawl Stars for two players, game is fun!',
    tags: ['Java'],
    icon: 'game',
    accent: 'red',
  };
  const live = github && github.repos ? github.repos.find((r) => r.name === PROJECT.repo) : null;
  const title = PROJECT.title || PROJECT.repo;
  const desc = PROJECT.description || (live && live.description) || '';
  const tags = (PROJECT.tags || (live && live.language ? [live.language] : [])).slice(0, 4);
  const red = PROJECT.accent === 'red';
  const COL = red ? '#ff3b4e' : '#19e3f2';
  const RGB = red ? '255,59,78' : '25,227,242';
  const ICONS = {
    folder: ['M3 7h6l2 2h10v10H3z'],
    code: ['M8 8 3 12l5 4', 'M16 8l5 4-5 4', 'M14 5l-4 14'],
    phone: ['M7 2.5h10a1 1 0 0 1 1 1v17a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1v-17a1 1 0 0 1 1-1z', 'M10.5 18.5h3'],
    ai: ['M8 8h8v8H8z', 'M12 3v3', 'M12 18v3', 'M3 12h3', 'M18 12h3', 'M9.5 5l.5 3', 'M14.5 5l-.5 3'],
    game: ['M6 9h12a3.5 3.5 0 0 1 3.4 4.3l-.7 3a2.6 2.6 0 0 1-4.5.9L15 16H9l-1.2 1.2a2.6 2.6 0 0 1-4.5-.9l-.7-3A3.5 3.5 0 0 1 6 9z', 'M8 11.5v3', 'M6.5 13h3'],
    cart: ['M3 4h3l2.5 11h9.5L20 7H7', 'M9.5 19.5h.01', 'M17 19.5h.01'],
    chart: ['M4 20V11', 'M10 20V4', 'M16 20v-6', 'M2 20h20'],
    globe: ['M12 3a9 9 0 1 0 0 18 9 9 0 0 0 0-18z', 'M3 12h18', 'M12 3c3 3 3 15 0 18', 'M12 3c-3 3-3 15 0 18'],
  };
  const paths = ICONS[PROJECT.icon] || ICONS.folder;
  return (
    <div style={{ display: 'flex', width: '100%', height: '100%', position: 'relative', overflow: 'hidden', background: '#05060d', fontFamily: 'Inter, sans-serif' }}>
      <style>{`
    @keyframes drA { 0%, 100% { transform: translate(0, 0); opacity: 0.7; } 50% { transform: translate(34px, -18px); opacity: 1; } }
    @keyframes drB { 0%, 100% { transform: translate(0, 0); opacity: 0.65; } 50% { transform: translate(-30px, 16px); opacity: 1; } }
    @keyframes scanx { 0% { transform: translate(0, 0); } 100% { transform: translate(1200px, 0); } }
    #scanband { animation: scanx 4.5s linear infinite; }
    @keyframes pls { 0%, 100% { transform: scale(1); opacity: 0.6; } 50% { transform: scale(1.18); opacity: 0.9; } }
    #o9 { animation: drA 8s ease-in-out infinite 0.5s; }

        @keyframes cb { 0%, 100% { opacity: 0.45; } 50% { opacity: 1; } }
        #cb1 { animation: cb 3s ease-in-out infinite; } #cb2 { animation: cb 3s ease-in-out infinite 0.4s; }
        #cb3 { animation: cb 3s ease-in-out infinite 0.8s; } #cb4 { animation: cb 3s ease-in-out infinite 1.2s; }
      `}</style>
      <svg width="400" height="196" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="bgR" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(255,59,78,0.5)" /><stop offset="100%" stopColor="rgba(255,59,78,0)" /></radialGradient>
      <radialGradient id="bgC" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(25,227,242,0.45)" /><stop offset="100%" stopColor="rgba(25,227,242,0)" /></radialGradient>
      <radialGradient id="bgD" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(170,28,56,0.45)" /><stop offset="100%" stopColor="rgba(170,28,56,0)" /></radialGradient>
      <radialGradient id="bgT" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(15,165,179,0.38)" /><stop offset="100%" stopColor="rgba(15,165,179,0)" /></radialGradient>
      <linearGradient id="bgScan" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" stopColor="rgba(25,227,242,0)" /><stop offset="40%" stopColor="rgba(25,227,242,0.12)" /><stop offset="50%" stopColor="rgba(255,120,140,0.45)" /><stop offset="60%" stopColor="rgba(25,227,242,0.12)" /><stop offset="100%" stopColor="rgba(25,227,242,0)" /></linearGradient>
      <linearGradient id="bgBorder" gradientUnits="userSpaceOnUse" x1="0" y1="0" x2="0" y2="1556"><stop offset="0%" stopColor="#19e3f2" /><stop offset="100%" stopColor="#ff3b4e" /></linearGradient>
      <pattern id="bgGrid" width="40" height="40" patternUnits="userSpaceOnUse"><path d="M 40 0 L 0 0 0 40" fill="none" stroke="rgba(25,227,242,0.07)" strokeWidth="0.5" /></pattern>
    </defs>
    <g transform="translate(0 -1280)">
      <rect x="0" y="1280" width="400" height="196" fill="url(#bgGrid)" />
      <circle cx="22" cy="1410" r="1.7" fill="#7ef0fa" opacity="0.3"><animate attributeName="opacity" values="0;0.44;0.44;0" keyTimes="0;0.4;0.6;1" dur="5.1s" begin="-5.3s" repeatCount="indefinite" /></circle>
      <ellipse id="o9" cx="380" cy="1526" rx="260" ry="70" fill="url(#bgR)" />

      <path d="M 0.75 1280 V 1476" fill="none" stroke="url(#bgBorder)" strokeWidth="1.5" strokeOpacity="0.55" />
    </g>
  </svg>
      <svg width="400" height="196" style={{ position: 'absolute', top: 0, left: 0 }}>
        <rect x="16" y="12" width="368" height="172" rx="14" fill="rgba(6,8,16,0.92)" />
        <rect x="16" y="12" width="368" height="172" rx="14" fill="none" stroke={COL} strokeOpacity="0.28" strokeWidth="1" />
        <path id="cb1" d="M 16 28 L 16 12 L 32 12" fill="none" stroke={COL} strokeWidth="2" strokeLinecap="round" />
        <path id="cb2" d="M 368 12 L 384 12 L 384 28" fill="none" stroke={COL} strokeWidth="2" strokeLinecap="round" />
        <path id="cb3" d="M 16 168 L 16 184 L 32 184" fill="none" stroke={COL} strokeWidth="2" strokeLinecap="round" />
        <path id="cb4" d="M 384 168 L 384 184 L 368 184" fill="none" stroke={COL} strokeWidth="2" strokeLinecap="round" />
        <rect x="32" y="28" width="38" height="38" rx="9" fill={'rgba(' + RGB + ',0.12)'} stroke={COL} strokeOpacity="0.45" />
        <g transform="translate(40 36) scale(0.92)" fill="none" stroke={COL} strokeWidth="1.8" strokeLinecap="round" strokeLinejoin="round">
          {paths.map((pd) => <path d={pd} />)}
        </g>
        <g transform="translate(346 32)" fill="none" stroke="rgba(244,238,240,0.55)" strokeWidth="1.8" strokeLinecap="round" strokeLinejoin="round">
          <path d="M1 13 13 1" /><path d="M4 1h9v9" />
        </g>
      </svg>
      <div style={{ display: 'flex', flexDirection: 'column', position: 'absolute', left: 82, top: 28, width: 250 }}>
        <span style={{ fontSize: 20, fontWeight: 700, color: '#f4eef0', lineHeight: 1.15 }}>{title}</span>
        <span style={{ fontSize: 13, color: COL, marginTop: 4 }}>{PROJECT.subtitle || ''}</span>
      </div>
      <div style={{ display: 'flex', position: 'absolute', left: 32, top: 82, width: 336, height: 62, overflow: 'hidden' }}>
        <span style={{ fontSize: 14, color: '#a9a3ad', lineHeight: 1.45 }}>{desc}</span>
      </div>
      <div style={{ display: 'flex', position: 'absolute', left: 32, top: 152 }}>
        {tags.map((tg) => (
          <span style={{ fontSize: 12, color: '#f4eef0', padding: '3px 9px', borderRadius: 6, border: '1px solid rgba(' + RGB + ',0.5)', marginRight: 6 }}>{tg}</span>
        ))}
      </div>
    </div>
  );
})()
```

```aura width=400 height=196 link="https://github.com/Rorro101004/Nextech" inline align=center
(() => {
  const PROJECT = {
    repo: 'Nextech',
    title: 'Nextech',
    subtitle: 'Team project',
    description: 'Collaborative platform to connect the tech community and manage tech events.',
    tags: ['PHP', 'CSS'],
    icon: 'globe',
    accent: 'cyan',
  };
  const live = github && github.repos ? github.repos.find((r) => r.name === PROJECT.repo) : null;
  const title = PROJECT.title || PROJECT.repo;
  const desc = PROJECT.description || (live && live.description) || '';
  const tags = (PROJECT.tags || (live && live.language ? [live.language] : [])).slice(0, 4);
  const red = PROJECT.accent === 'red';
  const COL = red ? '#ff3b4e' : '#19e3f2';
  const RGB = red ? '255,59,78' : '25,227,242';
  const ICONS = {
    folder: ['M3 7h6l2 2h10v10H3z'],
    code: ['M8 8 3 12l5 4', 'M16 8l5 4-5 4', 'M14 5l-4 14'],
    phone: ['M7 2.5h10a1 1 0 0 1 1 1v17a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1v-17a1 1 0 0 1 1-1z', 'M10.5 18.5h3'],
    ai: ['M8 8h8v8H8z', 'M12 3v3', 'M12 18v3', 'M3 12h3', 'M18 12h3', 'M9.5 5l.5 3', 'M14.5 5l-.5 3'],
    game: ['M6 9h12a3.5 3.5 0 0 1 3.4 4.3l-.7 3a2.6 2.6 0 0 1-4.5.9L15 16H9l-1.2 1.2a2.6 2.6 0 0 1-4.5-.9l-.7-3A3.5 3.5 0 0 1 6 9z', 'M8 11.5v3', 'M6.5 13h3'],
    cart: ['M3 4h3l2.5 11h9.5L20 7H7', 'M9.5 19.5h.01', 'M17 19.5h.01'],
    chart: ['M4 20V11', 'M10 20V4', 'M16 20v-6', 'M2 20h20'],
    globe: ['M12 3a9 9 0 1 0 0 18 9 9 0 0 0 0-18z', 'M3 12h18', 'M12 3c3 3 3 15 0 18', 'M12 3c-3 3-3 15 0 18'],
  };
  const paths = ICONS[PROJECT.icon] || ICONS.folder;
  return (
    <div style={{ display: 'flex', width: '100%', height: '100%', position: 'relative', overflow: 'hidden', background: '#05060d', fontFamily: 'Inter, sans-serif' }}>
      <style>{`
    @keyframes drA { 0%, 100% { transform: translate(0, 0); opacity: 0.7; } 50% { transform: translate(34px, -18px); opacity: 1; } }
    @keyframes drB { 0%, 100% { transform: translate(0, 0); opacity: 0.65; } 50% { transform: translate(-30px, 16px); opacity: 1; } }
    @keyframes scanx { 0% { transform: translate(0, 0); } 100% { transform: translate(1200px, 0); } }
    #scanband { animation: scanx 4.5s linear infinite; }
    @keyframes pls { 0%, 100% { transform: scale(1); opacity: 0.6; } 50% { transform: scale(1.18); opacity: 0.9; } }
    #o8 { animation: drB 9s ease-in-out infinite 0.2s; }
    #o9 { animation: drA 8s ease-in-out infinite 0.5s; }

        @keyframes cb { 0%, 100% { opacity: 0.45; } 50% { opacity: 1; } }
        #cb1 { animation: cb 3s ease-in-out infinite; } #cb2 { animation: cb 3s ease-in-out infinite 0.4s; }
        #cb3 { animation: cb 3s ease-in-out infinite 0.8s; } #cb4 { animation: cb 3s ease-in-out infinite 1.2s; }
      `}</style>
      <svg width="400" height="196" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="bgR" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(255,59,78,0.5)" /><stop offset="100%" stopColor="rgba(255,59,78,0)" /></radialGradient>
      <radialGradient id="bgC" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(25,227,242,0.45)" /><stop offset="100%" stopColor="rgba(25,227,242,0)" /></radialGradient>
      <radialGradient id="bgD" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(170,28,56,0.45)" /><stop offset="100%" stopColor="rgba(170,28,56,0)" /></radialGradient>
      <radialGradient id="bgT" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(15,165,179,0.38)" /><stop offset="100%" stopColor="rgba(15,165,179,0)" /></radialGradient>
      <linearGradient id="bgScan" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" stopColor="rgba(25,227,242,0)" /><stop offset="40%" stopColor="rgba(25,227,242,0.12)" /><stop offset="50%" stopColor="rgba(255,120,140,0.45)" /><stop offset="60%" stopColor="rgba(25,227,242,0.12)" /><stop offset="100%" stopColor="rgba(25,227,242,0)" /></linearGradient>
      <linearGradient id="bgBorder" gradientUnits="userSpaceOnUse" x1="0" y1="0" x2="0" y2="1556"><stop offset="0%" stopColor="#19e3f2" /><stop offset="100%" stopColor="#ff3b4e" /></linearGradient>
      <pattern id="bgGrid" width="40" height="40" patternUnits="userSpaceOnUse"><path d="M 40 0 L 0 0 0 40" fill="none" stroke="rgba(25,227,242,0.07)" strokeWidth="0.5" /></pattern>
    </defs>
    <g transform="translate(-400 -1280)">
      <rect x="400" y="1280" width="400" height="196" fill="url(#bgGrid)" />

      <ellipse id="o8" cx="700" cy="1428" rx="160" ry="80" fill="url(#bgT)" />
      <ellipse id="o9" cx="380" cy="1526" rx="260" ry="70" fill="url(#bgR)" />

      <path d="M 799.25 1280 V 1476" fill="none" stroke="url(#bgBorder)" strokeWidth="1.5" strokeOpacity="0.55" />
    </g>
  </svg>
      <svg width="400" height="196" style={{ position: 'absolute', top: 0, left: 0 }}>
        <rect x="16" y="12" width="368" height="172" rx="14" fill="rgba(6,8,16,0.92)" />
        <rect x="16" y="12" width="368" height="172" rx="14" fill="none" stroke={COL} strokeOpacity="0.28" strokeWidth="1" />
        <path id="cb1" d="M 16 28 L 16 12 L 32 12" fill="none" stroke={COL} strokeWidth="2" strokeLinecap="round" />
        <path id="cb2" d="M 368 12 L 384 12 L 384 28" fill="none" stroke={COL} strokeWidth="2" strokeLinecap="round" />
        <path id="cb3" d="M 16 168 L 16 184 L 32 184" fill="none" stroke={COL} strokeWidth="2" strokeLinecap="round" />
        <path id="cb4" d="M 384 168 L 384 184 L 368 184" fill="none" stroke={COL} strokeWidth="2" strokeLinecap="round" />
        <rect x="32" y="28" width="38" height="38" rx="9" fill={'rgba(' + RGB + ',0.12)'} stroke={COL} strokeOpacity="0.45" />
        <g transform="translate(40 36) scale(0.92)" fill="none" stroke={COL} strokeWidth="1.8" strokeLinecap="round" strokeLinejoin="round">
          {paths.map((pd) => <path d={pd} />)}
        </g>
        <g transform="translate(346 32)" fill="none" stroke="rgba(244,238,240,0.55)" strokeWidth="1.8" strokeLinecap="round" strokeLinejoin="round">
          <path d="M1 13 13 1" /><path d="M4 1h9v9" />
        </g>
      </svg>
      <div style={{ display: 'flex', flexDirection: 'column', position: 'absolute', left: 82, top: 28, width: 250 }}>
        <span style={{ fontSize: 20, fontWeight: 700, color: '#f4eef0', lineHeight: 1.15 }}>{title}</span>
        <span style={{ fontSize: 13, color: COL, marginTop: 4 }}>{PROJECT.subtitle || ''}</span>
      </div>
      <div style={{ display: 'flex', position: 'absolute', left: 32, top: 82, width: 336, height: 62, overflow: 'hidden' }}>
        <span style={{ fontSize: 14, color: '#a9a3ad', lineHeight: 1.45 }}>{desc}</span>
      </div>
      <div style={{ display: 'flex', position: 'absolute', left: 32, top: 152 }}>
        {tags.map((tg) => (
          <span style={{ fontSize: 12, color: '#f4eef0', padding: '3px 9px', borderRadius: 6, border: '1px solid rgba(' + RGB + ',0.5)', marginRight: 6 }}>{tg}</span>
        ))}
      </div>
    </div>
  );
})()
```

```aura width=800 height=80 inline align=center
<div style={{ display: 'flex', flexDirection: 'column', width: '100%', height: '100%', position: 'relative', overflow: 'hidden', borderRadius: '0 0 28px 28px', background: '#05060d', fontFamily: 'Inter, sans-serif' }}>
  <style>{`
    @keyframes drA { 0%, 100% { transform: translate(0, 0); opacity: 0.7; } 50% { transform: translate(34px, -18px); opacity: 1; } }
    @keyframes drB { 0%, 100% { transform: translate(0, 0); opacity: 0.65; } 50% { transform: translate(-30px, 16px); opacity: 1; } }
    @keyframes scanx { 0% { transform: translate(0, 0); } 100% { transform: translate(1200px, 0); } }
    #scanband { animation: scanx 4.5s linear infinite; }
    @keyframes pls { 0%, 100% { transform: scale(1); opacity: 0.6; } 50% { transform: scale(1.18); opacity: 0.9; } }
    #o8 { animation: drB 9s ease-in-out infinite 0.2s; }
    #o9 { animation: drA 8s ease-in-out infinite 0.5s; }
`}</style>
  <svg width="800" height="80" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="bgR" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(255,59,78,0.5)" /><stop offset="100%" stopColor="rgba(255,59,78,0)" /></radialGradient>
      <radialGradient id="bgC" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(25,227,242,0.45)" /><stop offset="100%" stopColor="rgba(25,227,242,0)" /></radialGradient>
      <radialGradient id="bgD" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(170,28,56,0.45)" /><stop offset="100%" stopColor="rgba(170,28,56,0)" /></radialGradient>
      <radialGradient id="bgT" cx="50%" cy="50%" r="50%"><stop offset="0%" stopColor="rgba(15,165,179,0.38)" /><stop offset="100%" stopColor="rgba(15,165,179,0)" /></radialGradient>
      <linearGradient id="bgScan" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" stopColor="rgba(25,227,242,0)" /><stop offset="40%" stopColor="rgba(25,227,242,0.12)" /><stop offset="50%" stopColor="rgba(255,120,140,0.45)" /><stop offset="60%" stopColor="rgba(25,227,242,0.12)" /><stop offset="100%" stopColor="rgba(25,227,242,0)" /></linearGradient>
      <linearGradient id="bgBorder" gradientUnits="userSpaceOnUse" x1="0" y1="0" x2="0" y2="1556"><stop offset="0%" stopColor="#19e3f2" /><stop offset="100%" stopColor="#ff3b4e" /></linearGradient>
      <pattern id="bgGrid" width="40" height="40" patternUnits="userSpaceOnUse"><path d="M 40 0 L 0 0 0 40" fill="none" stroke="rgba(25,227,242,0.07)" strokeWidth="0.5" /></pattern>
    </defs>
    <g transform="translate(0 -1476)">
      <rect x="0" y="1476" width="800" height="80" fill="url(#bgGrid)" />
      <circle cx="38" cy="1491" r="1.0" fill="#ffffff" opacity="0.3"><animate attributeName="opacity" values="0;0.5;0.5;0" keyTimes="0;0.4;0.6;1" dur="6.5s" begin="-6.6s" repeatCount="indefinite" /></circle>
      <circle cx="706" cy="1518" r="1.7" fill="#7ef0fa" opacity="0.3"><animate attributeName="opacity" values="0;0.29;0.29;0" keyTimes="0;0.4;0.6;1" dur="8.5s" begin="-0.4s" repeatCount="indefinite" /></circle>
      <ellipse id="o8" cx="700" cy="1428" rx="160" ry="80" fill="url(#bgT)" />
      <ellipse id="o9" cx="380" cy="1526" rx="260" ry="70" fill="url(#bgR)" />

      <path d="M 0.75 1476 V 1528 A 28 28 0 0 0 28 1555.25 H 772 A 28 28 0 0 0 799.25 1528 V 1476" fill="none" stroke="url(#bgBorder)" strokeWidth="1.5" strokeOpacity="0.55" />
    </g>
  </svg>
  <svg width="800" height="80" style={{ position: 'absolute', top: 0, left: 0 }}>
    <g transform="translate(0 0)">
      <path d="M 34 16 L 34 46 L 64 46" fill="none" stroke="#19e3f2" strokeWidth="2" strokeOpacity="0.8" strokeLinecap="round" />
      <path d="M 766 16 L 766 46 L 736 46" fill="none" stroke="#19e3f2" strokeWidth="2" strokeOpacity="0.8" strokeLinecap="round" />
      <rect id="eq0" x="64" y="34" width="6" height="6" fill="#ff3b4e" /><rect id="eq1" x="76" y="29" width="6" height="11" fill="#19e3f2" /><rect id="eq2" x="88" y="24" width="6" height="16" fill="#19e3f2" /><rect id="eq3" x="100" y="33" width="6" height="7" fill="#ff3b4e" /><rect id="eq4" x="112" y="28" width="6" height="12" fill="#19e3f2" /><rect id="eq5" x="124" y="23" width="6" height="17" fill="#19e3f2" /><rect id="eq6" x="136" y="32" width="6" height="8" fill="#ff3b4e" /><rect id="eq7" x="148" y="27" width="6" height="13" fill="#19e3f2" />
    </g>
  </svg>
  <div style={{ display: 'flex', position: 'relative', width: '100%', height: 80 }}>
    <div style={{ display: 'flex', position: 'absolute', left: 40, top: 0, width: 720, height: 1, background: 'linear-gradient(90deg, rgba(25,227,242,0), rgba(25,227,242,0.45), rgba(255,59,78,0.45), rgba(255,59,78,0))' }} />
    <style>{`
      @keyframes eq { 0%, 100% { opacity: 0.25; } 50% { opacity: 1; } }
      #eq0 {{ animation: eq 1.8s ease-in-out infinite 0.0s; }} #eq1 {{ animation: eq 1.8s ease-in-out infinite 0.15s; }} #eq2 {{ animation: eq 1.8s ease-in-out infinite 0.3s; }} #eq3 {{ animation: eq 1.8s ease-in-out infinite 0.44999999999999996s; }} #eq4 {{ animation: eq 1.8s ease-in-out infinite 0.6s; }} #eq5 {{ animation: eq 1.8s ease-in-out infinite 0.75s; }} #eq6 {{ animation: eq 1.8s ease-in-out infinite 0.8999999999999999s; }} #eq7 {{ animation: eq 1.8s ease-in-out infinite 1.05s; }} 
    `}</style>
    <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'flex-end', position: 'absolute', right: 96, top: 22, width: 460 }}>
      <span style={{ fontSize: 13, color: '#a9a3ad' }}>Rebuilt every day at 06:00 UTC with readme-aura</span>
      <span style={{ fontSize: 13, color: '#19e3f2', marginTop: 4, letterSpacing: 1 }}>CH-07 // LNK-03 // TRANSFER</span>
    </div>
  </div>
</div>
```
