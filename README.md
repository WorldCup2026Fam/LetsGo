# LetsGo
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Family World Cup Pool 2026 🏆</title>
<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Barlow:ital,wght@0,400;0,600;0,700;1,400&family=Barlow+Condensed:wght@700;900&display=swap" rel="stylesheet"/>
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
:root{--g:#00a550;--gd:#007a3d;--gold:#f5c518;--goldd:#c9a000;--red:#e63946;--navy:#0d1b2a;--navy2:#152236;--navy3:#1e3048;--white:#f0f4f8;--gray:#7a8899;--border:rgba(255,255,255,0.08);}
body{font-family:'Barlow',sans-serif;background:var(--navy);color:var(--white);min-height:100vh;overflow-x:hidden}
body::before{content:'';position:fixed;inset:0;background:repeating-linear-gradient(0deg,rgba(255,255,255,0.012) 0,rgba(255,255,255,0.012) 1px,transparent 1px,transparent 48px),repeating-linear-gradient(90deg,rgba(255,255,255,0.012) 0,rgba(255,255,255,0.012) 1px,transparent 1px,transparent 48px);pointer-events:none;z-index:0}
header{position:relative;z-index:5;background:linear-gradient(135deg,#004d20 0%,#006b2e 40%,var(--navy2) 100%);border-bottom:3px solid var(--gold)}
.hinner{max-width:1100px;margin:0 auto;padding:24px 20px 18px;display:flex;align-items:center;justify-content:space-between;gap:12px;flex-wrap:wrap}
h1{font-family:'Bebas Neue',sans-serif;font-size:clamp(2rem,5vw,3.6rem);letter-spacing:3px;line-height:1;background:linear-gradient(135deg,#fff 20%,var(--gold));-webkit-background-clip:text;-webkit-text-fill-color:transparent}
.sub{color:rgba(255,255,255,0.55);font-size:.8rem;letter-spacing:2px;text-transform:uppercase;margin-top:4px}
.ball{font-size:3rem;animation:spin 10s linear infinite;display:inline-block;filter:drop-shadow(0 0 10px rgba(245,197,24,.4))}
@keyframes spin{to{transform:rotate(360deg)}}
nav{position:relative;z-index:5;background:var(--navy2);border-bottom:1px solid var(--border);display:flex;justify-content:center;flex-wrap:wrap;gap:4px;padding:8px 12px}
.nav-btn{font-family:'Barlow Condensed',sans-serif;font-size:1rem;font-weight:700;letter-spacing:1.5px;text-transform:uppercase;background:transparent;color:var(--gray);border:2px solid transparent;border-radius:6px;padding:8px 18px;cursor:pointer;transition:.2s all}
.nav-btn:hover{color:var(--white);border-color:var(--border)}
.nav-btn.active{color:var(--gold);border-color:var(--gold);background:rgba(245,197,24,.07)}
main{position:relative;z-index:1;max-width:1100px;margin:0 auto;padding:28px 16px 80px}
.page{display:none}.page.active{display:block}
.stitle{font-family:'Bebas Neue',sans-serif;font-size:2.2rem;letter-spacing:3px;color:var(--gold);margin-bottom:4px}
.ssub{color:var(--gray);font-size:.82rem;letter-spacing:1.5px;text-transform:uppercase;margin-bottom:20px}
.card{background:var(--navy2);border:1px solid var(--border);border-radius:12px;padding:22px}
.info-box{background:rgba(255,255,255,.04);border:1px solid var(--border);border-radius:10px;padding:13px 16px;margin-bottom:20px;font-size:.85rem;line-height:1.6;color:rgba(255,255,255,.7)}
.info-box strong{color:var(--gold)}

/* SETUP */
.setup-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(300px,1fr));gap:18px}
.team-card{background:var(--navy2);border:2px solid var(--border);border-radius:14px;padding:20px;transition:border-color .2s}
.team-card.full{border-color:var(--g)}
.tc-head{display:flex;align-items:center;gap:10px;margin-bottom:12px}
.tc-mascot{font-size:2.2rem;line-height:1}
.tc-name{font-family:'Barlow Condensed',sans-serif;font-size:1.25rem;font-weight:700;letter-spacing:1px;background:transparent;border:none;border-bottom:2px solid var(--border);color:var(--white);width:100%;padding:3px 2px;outline:none;transition:.2s}
.tc-name:focus{border-bottom-color:var(--gold)}
.mascot-row{display:flex;flex-wrap:wrap;gap:5px;margin-bottom:12px}
.mb{font-size:1.3rem;background:rgba(255,255,255,.04);border:2px solid transparent;border-radius:7px;padding:3px 7px;cursor:pointer;transition:.15s}
.mb:hover,.mb.sel{border-color:var(--gold);background:rgba(245,197,24,.1)}
.slots{display:flex;flex-direction:column;gap:7px;margin-bottom:8px}
.slot{display:flex;align-items:center;gap:7px;background:rgba(255,255,255,.04);border:1px solid var(--border);border-radius:8px;padding:7px 10px;font-size:.88rem}
.sbadge{font-size:.62rem;font-weight:700;letter-spacing:1px;padding:2px 5px;border-radius:3px;font-family:'Barlow Condensed',sans-serif;white-space:nowrap}
.sbadge.t10{background:var(--gold);color:var(--navy)}.sbadge.any{background:var(--g);color:#fff}
.slot-flag{font-size:1.1rem}
.slot-name{flex:1;color:var(--gray);font-style:italic;font-size:.85rem}
.slot-name.on{color:var(--white);font-style:normal;font-weight:600}
.slot-rm{background:none;border:none;color:var(--red);cursor:pointer;font-size:.9rem;padding:0 3px;opacity:.6;transition:.15s}
.slot-rm:hover{opacity:1}
.pick-btn{width:100%;color:#fff;border:none;border-radius:8px;font-family:'Barlow Condensed',sans-serif;font-size:.92rem;font-weight:700;letter-spacing:1px;padding:9px;cursor:pointer;transition:.2s;margin-top:4px}
.pick-btn.t10{background:linear-gradient(135deg,var(--gold),var(--goldd));color:var(--navy)}
.pick-btn.any{background:linear-gradient(135deg,var(--g),var(--gd))}
.pick-btn:disabled{opacity:.3;cursor:not-allowed}
.pick-btn:not(:disabled):hover{opacity:.85}
.player-section{margin-top:11px;border-top:1px solid var(--border);padding-top:11px}
.player-label{font-size:.7rem;font-weight:700;letter-spacing:1.5px;text-transform:uppercase;color:var(--gray);margin-bottom:5px}
.player-input{width:100%;background:rgba(255,255,255,.06);border:1px solid var(--border);border-radius:8px;color:var(--white);font-size:.88rem;padding:7px 10px;outline:none;transition:.2s}
.player-input:focus{border-color:var(--gold)}
.player-hint{font-size:.7rem;color:var(--gray);margin-top:3px;font-style:italic}

/* MODAL */
.overlay{position:fixed;inset:0;z-index:1000;background:rgba(0,0,0,.8);backdrop-filter:blur(5px);display:flex;align-items:center;justify-content:center;padding:16px;animation:fi .2s}
@keyframes fi{from{opacity:0}to{opacity:1}}
.modal{background:var(--navy2);border:1px solid var(--border);border-radius:16px;padding:24px;width:100%;max-width:640px;max-height:84vh;overflow-y:auto;animation:su .25s ease}
@keyframes su{from{transform:translateY(28px);opacity:0}to{transform:translateY(0);opacity:1}}
.modal h3{font-family:'Bebas Neue',sans-serif;font-size:1.6rem;letter-spacing:2px;color:var(--gold);margin-bottom:3px}
.modal-sub{font-size:.78rem;color:var(--gray);margin-bottom:12px;letter-spacing:1px;text-transform:uppercase}
.mbanner{border-radius:8px;padding:9px 13px;margin-bottom:13px;font-size:.82rem}
.mbanner.gold{background:rgba(245,197,24,.1);border:1px solid rgba(245,197,24,.3);color:var(--gold)}
.mbanner.green{background:rgba(0,165,80,.1);border:1px solid rgba(0,165,80,.3);color:#4ddb8e}
.msearch{width:100%;background:rgba(255,255,255,.07);border:1px solid var(--border);border-radius:8px;color:var(--white);font-size:.92rem;padding:8px 12px;outline:none;margin-bottom:13px;transition:.2s}
.msearch:focus{border-color:var(--gold)}
.glabel{font-family:'Barlow Condensed',sans-serif;font-size:.73rem;font-weight:700;letter-spacing:2px;color:var(--gold);text-transform:uppercase;margin:10px 0 6px;padding-bottom:4px;border-bottom:1px solid var(--border)}
.cgrid{display:grid;grid-template-columns:repeat(auto-fill,minmax(145px,1fr));gap:6px}
.cbtn{display:flex;align-items:center;gap:7px;background:rgba(255,255,255,.05);border:2px solid transparent;border-radius:8px;padding:7px 9px;cursor:pointer;color:var(--white);font-size:.83rem;font-weight:600;text-align:left;transition:.15s;width:100%}
.cbtn.is-top10{border-color:rgba(245,197,24,.25);background:rgba(245,197,24,.05)}
.cbtn:hover{border-color:var(--g);background:rgba(0,165,80,.12)}
.cbtn.taken{opacity:.28;cursor:not-allowed;pointer-events:none}
.mclose{margin-top:16px;width:100%;background:rgba(255,255,255,.06);border:1px solid var(--border);color:var(--gray);border-radius:8px;padding:9px;cursor:pointer;font-size:.92rem;transition:.15s}
.mclose:hover{color:var(--white);border-color:var(--gray)}

/* STANDINGS */
.std-actions{display:flex;gap:10px;margin-bottom:18px;flex-wrap:wrap}
.btn{font-family:'Barlow Condensed',sans-serif;font-size:.95rem;font-weight:700;letter-spacing:1px;border-radius:8px;padding:9px 20px;cursor:pointer;border:2px solid transparent;transition:.2s}
.btn-gold{background:var(--gold);color:var(--navy)}.btn-gold:hover{background:var(--goldd)}
.btn-outline{background:transparent;color:var(--gold);border-color:var(--gold)}.btn-outline:hover{background:rgba(245,197,24,.1)}
.btn-green{background:var(--g);color:#fff}.btn-green:hover{background:var(--gd)}
.btn-red{background:var(--red);color:#fff}.btn-red:hover{opacity:.85}
table{width:100%;border-collapse:collapse}
th{font-family:'Barlow Condensed',sans-serif;font-size:.73rem;letter-spacing:2px;text-transform:uppercase;color:var(--gold);padding:9px 13px;text-align:left;border-bottom:2px solid var(--border)}
td{padding:11px 13px;border-bottom:1px solid var(--border);vertical-align:middle}
tr:hover td{background:rgba(255,255,255,.02)}
.rank{font-family:'Bebas Neue',sans-serif;font-size:1.4rem;width:34px;height:34px;border-radius:50%;display:flex;align-items:center;justify-content:center;background:rgba(255,255,255,.07)}
.rank.r1{background:var(--gold);color:var(--navy)}.rank.r2{background:#9aa5b4;color:var(--navy)}.rank.r3{background:#b87333;color:#fff}
.tname{font-family:'Barlow Condensed',sans-serif;font-size:1.1rem;font-weight:700}
.cpills{display:flex;gap:4px;flex-wrap:wrap;margin-top:3px}
.pill{font-size:.7rem;background:rgba(255,255,255,.07);border-radius:4px;padding:2px 7px;color:var(--gray)}
.pill.top10{background:rgba(245,197,24,.15);color:var(--gold)}
.player-pill{font-size:.7rem;background:rgba(0,165,80,.15);border-radius:4px;padding:2px 7px;color:#4ddb8e;margin-top:3px;display:inline-block}
.pts{font-family:'Bebas Neue',sans-serif;font-size:1.8rem;color:var(--gold);text-align:right}
.pts-breakdown{font-size:.68rem;color:var(--gray);text-align:right;line-height:1.5;margin-top:2px}

/* RESULTS TAB */
.phase-tabs{display:flex;gap:6px;flex-wrap:wrap;margin-bottom:22px}
.phase-tab{font-family:'Barlow Condensed',sans-serif;font-size:.85rem;font-weight:700;letter-spacing:1px;text-transform:uppercase;background:rgba(255,255,255,.05);border:2px solid var(--border);border-radius:7px;color:var(--gray);padding:7px 16px;cursor:pointer;transition:.15s}
.phase-tab:hover{color:var(--white);border-color:var(--gray)}
.phase-tab.active{color:var(--gold);border-color:var(--gold);background:rgba(245,197,24,.08)}
.scoring-key{display:flex;flex-wrap:wrap;gap:8px;margin-bottom:20px}
.sk-item{background:rgba(255,255,255,.05);border:1px solid var(--border);border-radius:7px;padding:6px 12px;font-size:.76rem;color:var(--gray);display:flex;align-items:center;gap:6px}
.sk-pts{font-family:'Bebas Neue',sans-serif;font-size:1.1rem;color:var(--gold)}
.group-section{margin-bottom:28px}
.group-header{font-family:'Bebas Neue',sans-serif;font-size:1.3rem;letter-spacing:2px;color:var(--white);margin-bottom:10px;padding-bottom:6px;border-bottom:1px solid var(--border);display:flex;align-items:center;gap:10px}
.group-header .gh-flags{display:flex;gap:4px;font-size:1.1rem}
.matches-list{display:flex;flex-direction:column;gap:8px}
.match-row{background:var(--navy3);border:1px solid var(--border);border-radius:10px;padding:12px 14px;display:flex;align-items:center;gap:10px;flex-wrap:wrap}
.match-team{display:flex;align-items:center;gap:6px;font-size:.88rem;font-weight:600;min-width:110px}
.match-team.right{flex-direction:row-reverse;text-align:right}
.match-flag{font-size:1.2rem}
.match-vs{font-family:'Bebas Neue',sans-serif;font-size:.9rem;color:var(--gray);letter-spacing:1px;flex-shrink:0}
.score-box{display:flex;align-items:center;gap:6px;margin:0 4px}
.score-input{width:44px;background:rgba(255,255,255,.08);border:1px solid var(--border);border-radius:6px;color:var(--white);text-align:center;font-size:1.1rem;font-family:'Bebas Neue',sans-serif;padding:4px 2px;outline:none;transition:.2s}
.score-input:focus{border-color:var(--gold);background:rgba(245,197,24,.08)}
.score-dash{font-family:'Bebas Neue',sans-serif;font-size:1.1rem;color:var(--gray)}
.save-match-btn{margin-left:auto;font-family:'Barlow Condensed',sans-serif;font-size:.8rem;font-weight:700;letter-spacing:1px;background:var(--g);color:#fff;border:none;border-radius:6px;padding:5px 12px;cursor:pointer;transition:.2s;white-space:nowrap}
.save-match-btn:hover{background:var(--gd)}
.match-status{font-size:.72rem;border-radius:4px;padding:2px 8px;font-weight:700;letter-spacing:.5px;white-space:nowrap}
.match-status.played{background:rgba(0,165,80,.2);color:#4ddb8e}
.match-status.pending{background:rgba(255,255,255,.06);color:var(--gray)}
.match-pts-badge{font-size:.7rem;background:rgba(245,197,24,.15);color:var(--gold);border-radius:4px;padding:2px 7px;font-weight:700}
.knockout-match{background:var(--navy3);border:1px solid var(--border);border-radius:10px;padding:14px 16px;margin-bottom:10px}
.ko-label{font-family:'Barlow Condensed',sans-serif;font-size:.7rem;font-weight:700;letter-spacing:2px;text-transform:uppercase;color:var(--gray);margin-bottom:8px}
.ko-teams{display:flex;align-items:center;gap:10px;flex-wrap:wrap}
.ko-team{display:flex;align-items:center;gap:7px;font-size:.9rem;font-weight:600;min-width:120px}
.ko-vs{font-family:'Bebas Neue',sans-serif;font-size:.9rem;color:var(--gray);letter-spacing:1px}
.ko-score{display:flex;align-items:center;gap:5px}
.winner-select{background:rgba(255,255,255,.07);border:1px solid var(--border);border-radius:7px;color:var(--white);font-size:.85rem;padding:6px 10px;outline:none;cursor:pointer;transition:.2s;margin-left:auto}
.winner-select:focus{border-color:var(--gold)}
.phase-notice{background:rgba(255,255,255,.04);border:1px solid var(--border);border-radius:9px;padding:12px 16px;margin-bottom:18px;font-size:.83rem;color:rgba(255,255,255,.6);line-height:1.6}
.phase-notice strong{color:var(--white)}

/* FACTS */
.fsearch{width:100%;max-width:400px;background:rgba(255,255,255,.07);border:1px solid var(--border);border-radius:8px;color:var(--white);font-size:.92rem;padding:9px 13px;outline:none;margin-bottom:20px}
.fsearch:focus{border-color:var(--gold)}
.facts-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(300px,1fr));gap:16px}
.fcard{background:var(--navy2);border:1px solid var(--border);border-radius:13px;overflow:hidden}
.fhead{display:flex;align-items:center;gap:11px;padding:14px 17px 12px;border-bottom:1px solid var(--border);background:rgba(255,255,255,.02)}
.fflag{font-size:2rem}.fcname{font-family:'Bebas Neue',sans-serif;font-size:1.4rem;letter-spacing:2px}
.ftop10-tag{font-size:.62rem;background:var(--gold);color:var(--navy);border-radius:3px;padding:2px 6px;font-family:'Barlow Condensed',sans-serif;font-weight:700;letter-spacing:1px;margin-left:auto}
.ftabs{display:flex;border-bottom:1px solid var(--border)}
.ftab{flex:1;background:none;border:none;border-bottom:2px solid transparent;color:var(--gray);font-size:.77rem;font-weight:600;letter-spacing:1px;text-transform:uppercase;padding:8px;cursor:pointer;transition:.15s}
.ftab.active{color:var(--gold);border-bottom-color:var(--gold)}
.fbody{padding:13px 17px;font-size:.86rem;line-height:1.65;color:rgba(255,255,255,.8);min-height:105px}
.rtitle{font-family:'Barlow Condensed',sans-serif;font-size:.98rem;font-weight:700;color:var(--gold);margin-bottom:6px}
.ilist{list-style:none;margin-bottom:8px}.ilist li::before{content:'•';color:var(--g);margin-right:6px}
.rsteps{color:var(--gray);font-size:.8rem;line-height:1.6;margin-top:5px}

/* SMACK */
.sfeed{display:flex;flex-direction:column;gap:11px;margin-bottom:18px}
.sbubble{background:var(--navy2);border:1px solid var(--border);border-radius:12px;padding:13px 17px;animation:pop .3s cubic-bezier(.175,.885,.32,1.275)}
@keyframes pop{from{transform:scale(.92) translateY(8px);opacity:0}to{transform:scale(1) translateY(0);opacity:1}}
.shead{display:flex;align-items:center;gap:9px;margin-bottom:6px}
.smascot{font-size:1.4rem}.steam{font-family:'Barlow Condensed',sans-serif;font-weight:700;font-size:.92rem;color:var(--gold)}
.stime{font-size:.7rem;color:var(--gray);margin-left:auto}
.stext{font-size:.88rem;line-height:1.5}
.scompose{display:flex;gap:8px;flex-wrap:wrap;align-items:center}
.ssel,.sinput{background:rgba(255,255,255,.07);border:1px solid var(--border);border-radius:8px;color:var(--white);font-size:.88rem;padding:8px 11px;outline:none}
.ssel{cursor:pointer}.sinput{flex:1;min-width:160px}
.sinput:focus,.ssel:focus{border-color:var(--gold)}

/* CONFETTI */
.cp{position:fixed;top:-20px;border-radius:3px;animation:cf linear forwards;pointer-events:none;z-index:9999}
@keyframes cf{to{transform:translateY(110vh) rotate(720deg);opacity:0}}
.empty{text-align:center;padding:48px 20px;color:var(--gray)}
.empty .ei{font-size:3.2rem;margin-bottom:11px}
.empty h3{font-family:'Bebas Neue',sans-serif;font-size:1.5rem;letter-spacing:2px;color:rgba(255,255,255,.22);margin-bottom:5px}
@media(max-width:580px){.hinner{padding:16px 14px 12px}.stitle{font-size:1.8rem}.match-team{min-width:80px}.ko-team{min-width:90px}}
</style>
</head>
<body>
<div id="confetti-host"></div>
<header>
  <div class="hinner">
    <div><h1>⚽ Family World Cup Pool</h1><div class="sub">FIFA World Cup 2026 · USA / Canada / Mexico</div></div>
    <span class="ball">⚽</span>
  </div>
</header>
<nav id="nav">
  <button class="nav-btn active" data-p="setup">🏗 Setup</button>
  <button class="nav-btn" data-p="results">⚽ Results</button>
  <button class="nav-btn" data-p="standings">🏆 Standings</button>
  <button class="nav-btn" data-p="facts">🌎 Country Facts</button>
  <button class="nav-btn" data-p="smack">💬 Smack Talk</button>
</nav>
<main>
  <div id="pg-setup" class="page active"></div>
  <div id="pg-results" class="page"></div>
  <div id="pg-standings" class="page"></div>
  <div id="pg-facts" class="page"></div>
  <div id="pg-smack" class="page"></div>
</main>
<script>
// ── DATA ─────────────────────────────────────────────────────────────────────
var MASCOTS=['🦁','🐯','🦅','🐺','🦊','🐉','🦈','🐻','🦋','🦏','🦍','🦜','🐊','🦩','🦚'];
var TOP10=['France','Spain','Argentina','England','Portugal','Brazil','Netherlands','Morocco','Belgium','Germany'];
var GROUPS={
  'Group A':[{n:'Mexico',f:'🇲🇽'},{n:'South Africa',f:'🇿🇦'},{n:'South Korea',f:'🇰🇷'},{n:'Czechia',f:'🇨🇿'}],
  'Group B':[{n:'Canada',f:'🇨🇦'},{n:'Bosnia and Herzegovina',f:'🇧🇦'},{n:'Qatar',f:'🇶🇦'},{n:'Switzerland',f:'🇨🇭'}],
  'Group C':[{n:'Brazil',f:'🇧🇷'},{n:'Morocco',f:'🇲🇦'},{n:'Haiti',f:'🇭🇹'},{n:'Scotland',f:'🏴󠁧󠁢󠁳󠁣󠁴󠁿'}],
  'Group D':[{n:'USA',f:'🇺🇸'},{n:'Paraguay',f:'🇵🇾'},{n:'Australia',f:'🇦🇺'},{n:'Turkiye',f:'🇹🇷'}],
  'Group E':[{n:'Germany',f:'🇩🇪'},{n:'Curacao',f:'🇨🇼'},{n:'Ivory Coast',f:'🇨🇮'},{n:'Ecuador',f:'🇪🇨'}],
  'Group F':[{n:'Netherlands',f:'🇳🇱'},{n:'Japan',f:'🇯🇵'},{n:'Sweden',f:'🇸🇪'},{n:'Tunisia',f:'🇹🇳'}],
  'Group G':[{n:'Belgium',f:'🇧🇪'},{n:'Egypt',f:'🇪🇬'},{n:'Iran',f:'🇮🇷'},{n:'New Zealand',f:'🇳🇿'}],
  'Group H':[{n:'Spain',f:'🇪🇸'},{n:'Cape Verde',f:'🇨🇻'},{n:'Saudi Arabia',f:'🇸🇦'},{n:'Serbia',f:'🇷🇸'}],
  'Group I':[{n:'France',f:'🇫🇷'},{n:'Senegal',f:'🇸🇳'},{n:'Iraq',f:'🇮🇶'},{n:'Norway',f:'🇳🇴'}],
  'Group J':[{n:'Argentina',f:'🇦🇷'},{n:'Algeria',f:'🇩🇿'},{n:'Austria',f:'🇦🇹'},{n:'Jordan',f:'🇯🇴'}],
  'Group K':[{n:'Portugal',f:'🇵🇹'},{n:'DR Congo',f:'🇨🇩'},{n:'Uzbekistan',f:'🇺🇿'},{n:'Colombia',f:'🇨🇴'}],
  'Group L':[{n:'England',f:'🏴󠁧󠁢󠁥󠁮󠁧󠁿'},{n:'Croatia',f:'🇭🇷'},{n:'Ghana',f:'🇬🇭'},{n:'Panama',f:'🇵🇦'}],
};
var ALL=Object.values(GROUPS).flat();
function isTop10(n){return TOP10.indexOf(n)>=0;}
function flagFor(n){var c=ALL.find(function(x){return x.n===n;});return c?c.f:'🌐';}

// POINTS SYSTEM
var PTS={groupWin:3,groupDraw:1,groupLoss:0,r32:5,r16:10,qf:15,sf:20,runnerUp:25,champion:40};

// Generate group stage matches (each team plays every other team in group once)
function makeGroupMatches(){
  var matches={};
  Object.keys(GROUPS).forEach(function(g){
    var teams=GROUPS[g];matches[g]=[];
    for(var i=0;i<teams.length;i++){
      for(var j=i+1;j<teams.length;j++){
        matches[g].push({id:g+'_'+i+'_'+j,home:teams[i],away:teams[j],homeScore:null,awayScore:null,played:false});
      }
    }
  });
  return matches;
}

// Knockout rounds — initially empty, winners get filled in by admin
function makeKnockout(){
  return {
    r32: Array.from({length:16},function(_,i){return{id:'r32_'+i,home:null,away:null,winner:null,label:'Match '+(i+1)};}),
    r16: Array.from({length:8}, function(_,i){return{id:'r16_'+i,home:null,away:null,winner:null,label:'Match '+(i+1)};}),
    qf:  Array.from({length:4}, function(_,i){return{id:'qf_'+i, home:null,away:null,winner:null,label:'Match '+(i+1)};}),
    sf:  Array.from({length:2}, function(_,i){return{id:'sf_'+i, home:null,away:null,winner:null,label:'Match '+(i+1)};}),
    fin: [{id:'fin_0',home:null,away:null,winner:null,runnerUp:null,label:'The Final'}],
  };
}

// ── STATE ─────────────────────────────────────────────────────────────────────
var teams=[];
for(var i=0;i<9;i++) teams.push({id:i,name:'Team '+(i+1),mascot:MASCOTS[i],countries:[],player:'',points:0});
var smack=[{tid:0,text:"We're coming for that trophy! 🏆",time:'Earlier'},{tid:1,text:"Dream on. Our picks are GOAT tier. 🐐",time:'Earlier'}];
var groupMatches=makeGroupMatches();
var knockout=makeKnockout();
var curPage='setup',factTabs={},factsQ='',pickerTeam=-1,pickerMode='top10',pickerQ='',resultsPhase='group';

try{
  var sv=localStorage.getItem('wcp26v4');
  if(sv){
    var p=JSON.parse(sv);
    teams=p.t||teams;smack=p.s||smack;
    if(p.gm)groupMatches=p.gm;
    if(p.ko)knockout=p.ko;
  }
}catch(e){}

function saveState(){try{localStorage.setItem('wcp26v4',JSON.stringify({t:teams,s:smack,gm:groupMatches,ko:knockout}));}catch(e){}}

// ── SCORING ENGINE ────────────────────────────────────────────────────────────
function calcPoints(){
  // Returns {teamId: {total, breakdown[]}}
  var result={};
  teams.forEach(function(t){result[t.id]={total:0,breakdown:[]};});

  function addPts(countryName,pts,reason){
    teams.forEach(function(t){
      t.countries.forEach(function(c){
        if(c.n===countryName){
          result[t.id].total+=pts;
          result[t.id].breakdown.push(flagFor(countryName)+' '+countryName+': +'+pts+' ('+reason+')');
        }
      });
    });
  }

  // Group stage
  Object.keys(groupMatches).forEach(function(g){
    groupMatches[g].forEach(function(m){
      if(!m.played||m.homeScore===null||m.awayScore===null)return;
      var hs=+m.homeScore,as=+m.awayScore;
      if(hs>as){addPts(m.home.n,PTS.groupWin,'group win');addPts(m.away.n,PTS.groupLoss,'group loss');}
      else if(as>hs){addPts(m.away.n,PTS.groupWin,'group win');addPts(m.home.n,PTS.groupLoss,'group loss');}
      else{addPts(m.home.n,PTS.groupDraw,'group draw');addPts(m.away.n,PTS.groupDraw,'group draw');}
    });
  });

  // Knockout rounds
  var rounds=[
    {key:'r32',pts:PTS.r32,label:'Round of 32'},
    {key:'r16',pts:PTS.r16,label:'Round of 16'},
    {key:'qf', pts:PTS.qf, label:'Quarter-final'},
    {key:'sf', pts:PTS.sf, label:'Semi-final'},
  ];
  rounds.forEach(function(rd){
    knockout[rd.key].forEach(function(m){
      if(m.winner)addPts(m.winner,rd.pts,rd.label+' win');
    });
  });
  // Final
  knockout.fin.forEach(function(m){
    if(m.winner)addPts(m.winner,PTS.champion,'CHAMPION!');
    if(m.runnerUp)addPts(m.runnerUp,PTS.runnerUp,'Runner-up');
  });

  return result;
}

// ── UTILS ─────────────────────────────────────────────────────────────────────
function esc(s){return String(s).replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;').replace(/"/g,'&quot;');}
function takenSet(xid){var s=new Set();teams.forEach(function(t){if(t.id!==xid)t.countries.forEach(function(c){s.add(c.n);});});return s;}
function confetti(n){n=n||80;var cols=['#f5c518','#00a550','#e63946','#fff','#0096ff','#ff6b35','#8338ec'];var host=document.getElementById('confetti-host');for(var i=0;i<n;i++){(function(){var el=document.createElement('div');el.className='cp';var sz=8+Math.random()*10;el.style.cssText='left:'+Math.random()*100+'vw;width:'+sz+'px;height:'+(sz*(0.4+Math.random()*0.8))+'px;background:'+cols[Math.floor(Math.random()*cols.length)]+';transform:rotate('+Math.random()*360+'deg);animation-duration:'+(1.5+Math.random()*2)+'s;animation-delay:'+(Math.random()*0.5)+'s;';host.appendChild(el);el.addEventListener('animationend',function(){el.remove();});})();}}

// ── NAV ───────────────────────────────────────────────────────────────────────
function goPage(p){curPage=p;document.querySelectorAll('.nav-btn').forEach(function(b){b.classList.toggle('active',b.dataset.p===p);});document.querySelectorAll('.page').forEach(function(d){d.classList.remove('active');});document.getElementById('pg-'+p).classList.add('active');renderPage(p);}
document.getElementById('nav').addEventListener('click',function(e){var b=e.target.closest('.nav-btn');if(b)goPage(b.dataset.p);});
function renderPage(p){if(p==='setup')renderSetup();else if(p==='results')renderResults();else if(p==='standings')renderStandings();else if(p==='facts')renderFacts();else if(p==='smack')renderSmack();}

// ── SETUP ─────────────────────────────────────────────────────────────────────
function renderSetup(){
  var el=document.getElementById('pg-setup');
  var html='<div class="stitle">Team Setup</div><div class="ssub">9 teams · 2 countries each · 1 Top-10 ranked + 1 any other</div>';
  html+='<div class="info-box">Each team picks <strong>2 countries</strong>: one from the <strong>🌟 Top 10 ranked nations</strong> (France, Spain, Argentina, England, Portugal, Brazil, Netherlands, Morocco, Belgium, Germany), and one <strong>any other country</strong>. Also pick a <strong>⭐ star player to watch</strong>.</div>';
  html+='<div class="setup-grid">';
  teams.forEach(function(t){
    var full=t.countries.length===2;
    var c10=t.countries.find(function(c){return isTop10(c.n);});
    var cAny=t.countries.find(function(c){return !isTop10(c.n);});
    html+='<div class="team-card'+(full?' full':'')+'"><div class="tc-head"><span class="tc-mascot">'+t.mascot+'</span><input class="tc-name" value="'+esc(t.name)+'" placeholder="Team name" maxlength="20" data-tid="'+t.id+'"></div>';
    html+='<div class="mascot-row">';
    MASCOTS.forEach(function(m){html+='<button class="mb'+(m===t.mascot?' sel':'')+'" data-tid="'+t.id+'" data-m="'+m+'">'+m+'</button>';});
    html+='</div><div class="slots">';
    html+='<div class="slot"><span class="sbadge t10">🌟 TOP 10</span><span class="slot-flag">'+(c10?c10.f:'🌐')+'</span><span class="slot-name'+(c10?' on':'')+'">'+esc(c10?c10.n:'Pick a Top 10 country')+'</span>'+(c10?'<button class="slot-rm" data-tid="'+t.id+'" data-mode="top10">✕</button>':'')+'</div>';
    html+='<div class="slot"><span class="sbadge any">⚽ ANY</span><span class="slot-flag">'+(cAny?cAny.f:'🌐')+'</span><span class="slot-name'+(cAny?' on':'')+'">'+esc(cAny?cAny.n:'Pick any other country')+'</span>'+(cAny?'<button class="slot-rm" data-tid="'+t.id+'" data-mode="any">✕</button>':'')+'</div>';
    html+='</div>';
    if(!c10)html+='<button class="pick-btn t10" data-tid="'+t.id+'" data-mode="top10">🌟 Pick Top 10 Country</button>';
    if(!cAny)html+='<button class="pick-btn any" data-tid="'+t.id+'" data-mode="any" style="margin-top:6px">⚽ Pick Any Country</button>';
    if(full)html+='<div style="text-align:center;font-size:.82rem;color:var(--g);margin-top:7px;font-weight:700">✅ Countries selected!</div>';
    html+='<div class="player-section"><div class="player-label">⭐ Player to Watch</div><input class="player-input" placeholder="e.g. Mbappé, Bellingham, Haaland..." value="'+esc(t.player||'')+'" data-tid="'+t.id+'" maxlength="40"><div class="player-hint">The star player your team is rooting for</div></div>';
    html+='</div>';
  });
  html+='</div>';
  el.innerHTML=html;
  el.querySelectorAll('.tc-name').forEach(function(i){i.addEventListener('input',function(){teams[+this.dataset.tid].name=this.value;saveState();});});
  el.querySelectorAll('.mb').forEach(function(b){b.addEventListener('click',function(){teams[+this.dataset.tid].mascot=this.dataset.m;saveState();renderSetup();});});
  el.querySelectorAll('.slot-rm').forEach(function(b){b.addEventListener('click',function(){var tid=+this.dataset.tid,mode=this.dataset.mode;teams[tid].countries=teams[tid].countries.filter(function(c){return mode==='top10'?!isTop10(c.n):isTop10(c.n);});saveState();renderSetup();});});
  el.querySelectorAll('.pick-btn').forEach(function(b){b.addEventListener('click',function(){if(!this.disabled){pickerTeam=+this.dataset.tid;pickerMode=this.dataset.mode;pickerQ='';openPicker();}});});
  el.querySelectorAll('.player-input').forEach(function(i){i.addEventListener('input',function(){teams[+this.dataset.tid].player=this.value;saveState();});});
}

// ── PICKER ────────────────────────────────────────────────────────────────────
function openPicker(){
  var taken=takenSet(pickerTeam);var isT10=pickerMode==='top10';var tname=teams[pickerTeam].name;
  function build(){
    var q=pickerQ.toLowerCase();
    var html='<div class="modal"><h3>'+(isT10?'🌟 Pick Top 10 Country':'⚽ Pick Any Country')+'</h3><div class="modal-sub">For: '+esc(tname)+'</div>';
    html+='<div class="mbanner '+(isT10?'gold':'green')+'">'+(isT10?'🌟 Only <strong>Top 10 ranked nations</strong> shown — pick your powerhouse!':'⚽ Pick <strong>any country NOT in the Top 10</strong> — your dark horse!')+'</div>';
    html+='<input class="msearch" id="msearch" placeholder="Search..." value="'+esc(pickerQ)+'">';
    Object.keys(GROUPS).forEach(function(g){
      var vis=GROUPS[g].filter(function(c){return(!q||c.n.toLowerCase().includes(q))&&(isT10?isTop10(c.n):!isTop10(c.n));});
      if(!vis.length)return;
      html+='<div class="glabel">'+g+'</div><div class="cgrid">';
      vis.forEach(function(c){var tk=taken.has(c.n);html+='<button class="cbtn'+(isTop10(c.n)?' is-top10':'')+(tk?' taken':'')+'" data-n="'+esc(c.n)+'" data-f="'+c.f+'"'+(tk?' disabled':'')+'>'+c.f+' '+esc(c.n)+'</button>';});
      html+='</div>';
    });
    html+='<button class="mclose" id="mclose">Close</button></div>';
    return html;
  }
  var ov=document.createElement('div');ov.className='overlay';ov.innerHTML=build();document.body.appendChild(ov);
  function attach(){
    var ms=document.getElementById('msearch');
    if(ms){ms.focus();ms.setSelectionRange(ms.value.length,ms.value.length);ms.addEventListener('input',function(){pickerQ=this.value;ov.innerHTML=build();attach();});}
    ov.querySelectorAll('.cbtn:not(.taken)').forEach(function(b){b.addEventListener('click',function(){teams[pickerTeam].countries=teams[pickerTeam].countries.filter(function(c){return isT10?!isTop10(c.n):isTop10(c.n);});teams[pickerTeam].countries.push({n:this.dataset.n,f:this.dataset.f});saveState();ov.remove();renderSetup();});});
    var mc=document.getElementById('mclose');if(mc)mc.addEventListener('click',function(){ov.remove();renderSetup();});
    ov.addEventListener('click',function(e){if(e.target===ov){ov.remove();renderSetup();}});
  }
  attach();
}

// ── RESULTS ───────────────────────────────────────────────────────────────────
function renderResults(){
  var el=document.getElementById('pg-results');
  var html='<div class="stitle">⚽ Match Results</div><div class="ssub">Enter scores · Points update automatically</div>';

  // Scoring key
  html+='<div class="scoring-key">';
  html+='<div class="sk-item"><span class="sk-pts">'+PTS.groupWin+'</span> Group Win</div>';
  html+='<div class="sk-item"><span class="sk-pts">'+PTS.groupDraw+'</span> Group Draw</div>';
  html+='<div class="sk-item"><span class="sk-pts">'+PTS.r32+'</span> Round of 32</div>';
  html+='<div class="sk-item"><span class="sk-pts">'+PTS.r16+'</span> Round of 16</div>';
  html+='<div class="sk-item"><span class="sk-pts">'+PTS.qf+'</span> Quarter-final</div>';
  html+='<div class="sk-item"><span class="sk-pts">'+PTS.sf+'</span> Semi-final</div>';
  html+='<div class="sk-item"><span class="sk-pts">'+PTS.runnerUp+'</span> Runner-up</div>';
  html+='<div class="sk-item"><span class="sk-pts">'+PTS.champion+'</span> Champion 🏆</div>';
  html+='</div>';

  // Phase tabs
  html+='<div class="phase-tabs">';
  ['group','r32','r16','qf','sf','fin'].forEach(function(ph){
    var labels={group:'Group Stage',r32:'Round of 32',r16:'Round of 16',qf:'Quarter-Finals',sf:'Semi-Finals',fin:'Final'};
    html+='<button class="phase-tab'+(resultsPhase===ph?' active':'')+'" data-ph="'+ph+'">'+labels[ph]+'</button>';
  });
  html+='</div>';

  if(resultsPhase==='group'){
    html+='<div class="phase-notice">Enter the score for each group stage match. <strong>Win = '+PTS.groupWin+' pts, Draw = '+PTS.groupDraw+' pt.</strong> Click Save after each match.</div>';
    Object.keys(groupMatches).forEach(function(g){
      html+='<div class="group-section"><div class="group-header">'+g+' <span class="gh-flags">';
      GROUPS[g].forEach(function(c){html+=c.f;});
      html+='</span></div><div class="matches-list">';
      groupMatches[g].forEach(function(m){
        var played=m.played;
        html+='<div class="match-row">';
        html+='<div class="match-team"><span class="match-flag">'+m.home.f+'</span>'+esc(m.home.n)+'</div>';
        html+='<div class="score-box"><input class="score-input" type="number" min="0" max="20" value="'+(m.homeScore!==null?m.homeScore:'')+'" placeholder="0" data-mid="'+m.id+'" data-side="home"><span class="score-dash">–</span><input class="score-input" type="number" min="0" max="20" value="'+(m.awayScore!==null?m.awayScore:'')+'" placeholder="0" data-mid="'+m.id+'" data-side="away"></div>';
        html+='<div class="match-team right">'+esc(m.away.n)+' <span class="match-flag">'+m.away.f+'</span></div>';
        html+='<button class="save-match-btn" data-mid="'+m.id+'">Save</button>';
        html+='<span class="match-status '+(played?'played':'pending')+'">'+(played?'✓ Played':'Pending')+'</span>';
        html+='</div>';
      });
      html+='</div></div>';
    });
  } else if(resultsPhase==='fin'){
    html+='<div class="phase-notice">Select the <strong>Champion</strong> and <strong>Runner-up</strong> from the Final. Champion = <strong>'+PTS.champion+' pts</strong>, Runner-up = <strong>'+PTS.runnerUp+' pts</strong>.</div>';
    var fin=knockout.fin[0];
    html+='<div class="knockout-match"><div class="ko-label">⚽ The Final</div>';
    html+='<div style="margin-bottom:12px"><label style="font-size:.8rem;color:var(--gray);display:block;margin-bottom:5px;font-family:Barlow Condensed,sans-serif;letter-spacing:1px;text-transform:uppercase">🏆 Champion</label>';
    html+='<select class="winner-select" id="fin-champion" style="width:100%;margin-left:0">';
    html+='<option value="">— Select Champion —</option>';
    ALL.forEach(function(c){html+='<option value="'+esc(c.n)+'"'+(fin.winner===c.n?' selected':'')+'>'+c.f+' '+esc(c.n)+'</option>';});
    html+='</select></div>';
    html+='<div><label style="font-size:.8rem;color:var(--gray);display:block;margin-bottom:5px;font-family:Barlow Condensed,sans-serif;letter-spacing:1px;text-transform:uppercase">🥈 Runner-up</label>';
    html+='<select class="winner-select" id="fin-runnerup" style="width:100%;margin-left:0">';
    html+='<option value="">— Select Runner-up —</option>';
    ALL.forEach(function(c){html+='<option value="'+esc(c.n)+'"'+(fin.runnerUp===c.n?' selected':'')+'>'+c.f+' '+esc(c.n)+'</option>';});
    html+='</select></div>';
    if(fin.winner)html+='<div style="margin-top:14px;padding:12px;background:rgba(245,197,24,.1);border:1px solid rgba(245,197,24,.3);border-radius:8px;text-align:center"><div style="font-size:2rem">🏆</div><div style="font-family:Bebas Neue,sans-serif;font-size:1.4rem;color:var(--gold);letter-spacing:2px">'+flagFor(fin.winner)+' '+esc(fin.winner)+' — WORLD CHAMPIONS!</div></div>';
    html+='</div>';
  } else {
    var phLabels={r32:'Round of 32',r16:'Round of 16',qf:'Quarter-Finals',sf:'Semi-Finals'};
    var phPts={r32:PTS.r32,r16:PTS.r16,qf:PTS.qf,sf:PTS.sf};
    html+='<div class="phase-notice">Select the <strong>winner</strong> of each match. The winning country\'s pool team earns <strong>'+phPts[resultsPhase]+' points</strong>. Type country names into the dropdowns — they\'ll be filled in as the tournament progresses.</div>';
    knockout[resultsPhase].forEach(function(m,mi){
      html+='<div class="knockout-match"><div class="ko-label">'+esc(m.label)+'</div><div class="ko-teams">';
      // Home team selector
      html+='<select class="winner-select" data-ko="'+resultsPhase+'" data-idx="'+mi+'" data-side="home" style="min-width:150px">';
      html+='<option value="">— Team A —</option>';
      ALL.forEach(function(c){html+='<option value="'+esc(c.n)+'"'+(m.home===c.n?' selected':'')+'>'+c.f+' '+esc(c.n)+'</option>';});
      html+='</select>';
      html+='<span class="ko-vs">VS</span>';
      // Away team selector
      html+='<select class="winner-select" data-ko="'+resultsPhase+'" data-idx="'+mi+'" data-side="away" style="min-width:150px">';
      html+='<option value="">— Team B —</option>';
      ALL.forEach(function(c){html+='<option value="'+esc(c.n)+'"'+(m.away===c.n?' selected':'')+'>'+c.f+' '+esc(c.n)+'</option>';});
      html+='</select>';
      // Winner selector
      html+='<select class="winner-select" data-ko="'+resultsPhase+'" data-idx="'+mi+'" data-side="winner" style="min-width:160px;border-color:rgba(245,197,24,.3)">';
      html+='<option value="">— Pick Winner —</option>';
      if(m.home)html+='<option value="'+esc(m.home)+'"'+(m.winner===m.home?' selected':'')+'>'+flagFor(m.home)+' '+esc(m.home)+'</option>';
      if(m.away)html+='<option value="'+esc(m.away)+'"'+(m.winner===m.away?' selected':'')+'>'+flagFor(m.away)+' '+esc(m.away)+'</option>';
      html+='</select>';
      if(m.winner)html+='<span class="match-pts-badge">+'+phPts[resultsPhase]+' pts</span>';
      html+='</div></div>';
    });
  }

  el.innerHTML=html;

  // Phase tab events
  el.querySelectorAll('.phase-tab').forEach(function(b){
    b.addEventListener('click',function(){resultsPhase=this.dataset.ph;renderResults();});
  });

  // Group match save
  el.querySelectorAll('.save-match-btn').forEach(function(b){
    b.addEventListener('click',function(){
      var mid=this.dataset.mid;
      var hIn=el.querySelector('.score-input[data-mid="'+mid+'"][data-side="home"]');
      var aIn=el.querySelector('.score-input[data-mid="'+mid+'"][data-side="away"]');
      if(!hIn||!aIn)return;
      var hs=hIn.value.trim(),as=aIn.value.trim();
      if(hs===''||as===''){alert('Please enter both scores before saving.');return;}
      // Find and update match
      Object.keys(groupMatches).forEach(function(g){
        groupMatches[g].forEach(function(m){
          if(m.id===mid){m.homeScore=+hs;m.awayScore=+as;m.played=true;}
        });
      });
      saveState();renderResults();
    });
  });

  // Knockout team / winner selects
  el.querySelectorAll('select[data-ko]').forEach(function(sel){
    sel.addEventListener('change',function(){
      var rnd=this.dataset.ko,idx=+this.dataset.idx,side=this.dataset.side;
      var val=this.value||null;
      knockout[rnd][idx][side]=val;
      // If winner changed and doesn't match home/away, clear it
      if(side==='winner'){knockout[rnd][idx].winner=val;}
      else{// If team changed, clear winner if it no longer matches
        var m=knockout[rnd][idx];
        if(m.winner&&m.winner!==m.home&&m.winner!==m.away)m.winner=null;
      }
      saveState();renderResults();
    });
  });

  // Final selects
  var fc=document.getElementById('fin-champion');
  var fr=document.getElementById('fin-runnerup');
  if(fc)fc.addEventListener('change',function(){knockout.fin[0].winner=this.value||null;saveState();renderResults();});
  if(fr)fr.addEventListener('change',function(){knockout.fin[0].runnerUp=this.value||null;saveState();renderResults();});
}

// ── STANDINGS ─────────────────────────────────────────────────────────────────
function renderStandings(){
  var el=document.getElementById('pg-standings');
  var scored=calcPoints();
  // Update team points from scoring engine
  teams.forEach(function(t){t.points=scored[t.id].total;});
  var sorted=teams.slice().sort(function(a,b){return b.points-a.points;});
  var allPicked=teams.every(function(t){return t.countries.length===2;});
  var html='<div class="stitle">🏆 Standings</div><div class="ssub">Points update automatically from match results</div>';
  if(!allPicked)html+='<div style="background:rgba(245,197,24,.1);border:1px solid var(--gold);border-radius:10px;padding:13px 18px;margin-bottom:18px;color:var(--gold);font-size:.88rem;">⚠️ Not all teams have picked their 2 countries yet!</div>';
  html+='<div class="std-actions"><button class="btn btn-gold" id="celBtn">🎉 Celebrate!</button></div>';
  html+='<div class="card"><table><thead><tr><th style="width:46px">#</th><th>Team</th><th style="text-align:right">Points</th></tr></thead><tbody>';
  sorted.forEach(function(t,i){
    var rc=i===0?'r1':i===1?'r2':i===2?'r3':'';
    var bd=scored[t.id].breakdown;
    html+='<tr><td><div class="rank '+rc+'">'+(i+1)+'</div></td><td><div style="display:flex;align-items:center;gap:10px"><span style="font-size:1.6rem">'+t.mascot+'</span><div><div class="tname">'+esc(t.name)+'</div><div class="cpills">';
    t.countries.forEach(function(c){html+='<span class="pill'+(isTop10(c.n)?' top10':'')+'">'+c.f+' '+esc(c.n)+(isTop10(c.n)?' 🌟':'')+'</span>';});
    if(!t.countries.length)html+='<span class="pill" style="color:var(--red)">No countries yet</span>';
    html+='</div>'+(t.player?'<div><span class="player-pill">⭐ '+esc(t.player)+'</span></div>':'')+'</div></div></td>';
    html+='<td><div class="pts">'+t.points+' pts</div>';
    if(bd.length)html+='<div class="pts-breakdown">'+bd.map(function(b){return esc(b);}).join('<br>')+'</div>';
    html+='</td></tr>';
  });
  html+='</tbody></table></div>';
  el.innerHTML=html;
  document.getElementById('celBtn').addEventListener('click',function(){confetti(120);});
}

// ── FACTS ─────────────────────────────────────────────────────────────────────
var FACTS={
  'France':{fact:"France are 2-time World Cup champions (1998, 2018) and 2022 runners-up. Ranked #1, Les Bleus have Mbappé, Griezmann and an incredibly deep squad. Perpetual favorites at every tournament.",recipe:{name:'🥐 Croque Monsieur',ing:['4 thick bread slices','4 slices good ham','150g Gruyère grated','Béchamel: butter, flour, milk, nutmeg','Dijon mustard'],steps:'Make béchamel. Spread mustard on bread, layer ham and cheese, top with béchamel and more cheese. Bake 400°F for 15 min until golden and bubbling.'}},
  'Spain':{fact:"Spain won the 2010 World Cup with tiki-taka mastery and claimed Euro 2024 with a brilliant young generation. Lamine Yamal and Pedri make them the most exciting team in the world right now.",recipe:{name:'🥘 Paella Valenciana',ing:['2 cups bomba rice','Chicken and rabbit (or seafood)','Saffron, smoked paprika','Green beans, butter beans, tomato, 1L chicken stock'],steps:'Bloom saffron in stock. Brown meat in paella pan. Add tomato and paprika. Add rice, pour in stock. Cook on high then reduce — do NOT stir. Let socarrat crust form on the bottom.'}},
  'Argentina':{fact:"Reigning World Cup champions (2022)! Messi finally got his crown in the most dramatic final in history. Three titles total (1978, 1986, 2022). Lautaro Martínez and Julián Álvarez lead the next era.",recipe:{name:'🥩 Asado',ing:['Short ribs, flank steak, chorizo, morcilla','Coarse salt only','Chimichurri: parsley, garlic, oregano, olive oil, red wine vinegar'],steps:'Build wood fire, let coals develop. Salt meat generously. Grill low and slow — patience is everything. Serve with chimichurri. Open a Malbec.'}},
  'England':{fact:"England invented football and won their only World Cup in 1966. Jude Bellingham, Bukayo Saka, and Phil Foden have given England their most exciting generation in decades.",recipe:{name:'🐟 Fish & Chips',ing:['4 thick cod fillets','Beer batter: 1.5 cups flour, 1 cup cold beer, salt','4 large potatoes for chips','Malt vinegar, mushy peas, tartar sauce'],steps:'Double fry chips: first 300°F, then 375°F. Make beer batter (lumpy is fine!). Fry fish at 375°F until deep golden. Salt immediately. Serve with malt vinegar.'}},
  'Portugal':{fact:"Euro 2016 champions. Cristiano Ronaldo scored at 5 consecutive World Cups. Bruno Fernandes, Bernardo Silva and Leão now form the backbone of a technically gifted squad.",recipe:{name:'🐟 Bacalhau à Brás',ing:['500g salt cod (soaked 48hr)','4 beaten eggs, 1 onion, 3 garlic cloves','Fried shoestring potatoes, black olives, parsley'],steps:'Shred soaked cod. Sauté onion and garlic. Add cod and potatoes. Pour in eggs off heat, fold until just creamy. Garnish with olives and parsley.'}},
  'Brazil':{fact:"Brazil are the most successful World Cup nation with 5 titles and the only team to appear in every tournament. Vinicius Jr. and Rodrygo now lead the Seleção. Joga bonito is their identity.",recipe:{name:'🍖 Churrasco Picanha',ing:['2 lbs picanha (top sirloin cap)','Coarse sea salt only','Chimichurri to serve'],steps:'Score fat cap in crosshatch. Fold into C-shape on skewer. Season with coarse salt only. Grill over charcoal rotating constantly 20-30 min. Slice thin against the grain.'}},
  'Netherlands':{fact:"Three World Cup finals, zero wins (1974, 1978, 2010). Inventors of Total Football under Johan Cruyff. The Oranje always arrive with technical brilliance and always find new ways to break your heart.",recipe:{name:'🧇 Stroopwafels',ing:['2 cups flour, ½ cup butter, ¼ cup sugar, 1 egg, 1 tsp yeast','Caramel: ½ cup butter, ½ cup dark syrup, 1 cup brown sugar, 1 tsp cinnamon'],steps:'Make dough, rest 1 hr. Press balls in waffle iron until golden. Immediately split each waffle. Spread warm caramel between layers. Best eaten over a hot mug of coffee.'}},
  'Morocco':{fact:"Morocco made history at the 2022 World Cup — the first African nation to reach the semi-finals! They eliminated Spain and Portugal. The Atlas Lions are now genuine World Cup contenders.",recipe:{name:'🫕 Lamb Tagine',ing:['2 lbs lamb shoulder cubed','Onion, garlic, ginger, ras el hanout','Preserved lemon, green olives, dried apricots, chickpeas','Cilantro, parsley, couscous to serve'],steps:'Brown lamb. Sauté aromatics, add spices. Return meat, add preserved lemon and olives. Cook low and slow 2 hrs. Add apricots last 30 min. Serve over couscous.'}},
  'Belgium':{fact:"Belgium's golden generation peaked at 3rd place in 2018. De Bruyne, Lukaku, and Courtois made them one of the most talented squads ever assembled. Now rebuilding with a new generation.",recipe:{name:'🍟 Belgian Frites + Andalouse Sauce',ing:['Russet potatoes cut THICK','Beef fat or neutral oil for frying','Andalouse: ½ cup mayo, 2 tbsp tomato paste, ¼ red pepper diced, squeeze lemon'],steps:'Double fry potatoes: 325°F then 375°F. Salt immediately. Mix Andalouse ingredients. Serve in a paper cone.'}},
  'Germany':{fact:"Four-time World Cup champions (1954, 1974, 1990, 2014). Their 7-1 demolition of Brazil in 2014 remains one of the most shocking results in history. Rebuilding with Wirtz and Musiala.",recipe:{name:'🌭 Currywurst',ing:['4 bratwurst sausages','1 cup ketchup, 2 tbsp curry powder','1 tsp smoked paprika, dash Worcestershire'],steps:'Grill bratwurst until charred. Simmer ketchup with curry powder and paprika. Slice sausage, pour sauce over. Serve with fries and a bread roll.'}},
  'Mexico':{fact:"El Tri have qualified for 17 World Cups and co-host 2026! Their group games at the legendary Estadio Azteca will be electric. Mexico's fans are among the most passionate in the world.",recipe:{name:'🥑 Guacamole Auténtico',ing:['3 ripe avocados, 1 lime juiced','½ white onion diced, 2 serrano peppers minced','Fresh cilantro, salt to taste'],steps:'Mash avocados coarsely — keep it chunky! Fold in all ingredients. Serve immediately with tortilla chips. Never use a food processor.'}},
  'South Africa':{fact:"South Africa hosted the 2010 World Cup — the first on African soil — with iconic vuvuzela energy. Bafana Bafana ('The Boys The Boys') return to the world stage in 2026.",recipe:{name:'🍖 Braai',ing:['Lamb chops, boerewors sausage, chicken','Coarse salt, coriander spice','Pap (maize porridge) and chakalaka relish to serve'],steps:"South Africa's sacred tradition. Build wood fire in a drum braai. Never use gas! Grill boerewors in a coil. Season simply. Serve with pap and chakalaka. A social event, not just a meal."}},
  'South Korea':{fact:"South Korea's finest World Cup was 2002 when they co-hosted and reached the semi-finals — the best ever by an Asian team. They've qualified for every World Cup since 1986.",recipe:{name:'🌶️ Bibimbap',ing:['2 cups steamed rice','Sautéed spinach, bean sprouts, carrots, zucchini','Bulgogi beef, 2 fried eggs (sunny side up)','Gochujang paste, sesame oil, sesame seeds'],steps:'Prepare each topping separately. Arrange beautifully over rice. Top with egg and bulgogi. Add gochujang to taste. Drizzle sesame oil. Mix vigorously before eating.'}},
  'Czechia':{fact:"Czechia (formerly Czechoslovakia) reached the World Cup final twice (1934, 1962) and Euro final in 1996. A proud Central European football nation. Patrik Schick leads their current generation.",recipe:{name:'🥩 Svíčková',ing:['2 lbs beef sirloin','Carrots, parsnip, celery, onion for braising','Cream sauce with lemon juice and spices','Knedlíky (bread dumplings), cranberry sauce'],steps:'Braise beef low and slow 3-4 hrs. Blend sauce, add cream. Slice beef, pour sauce over. Serve with bread dumplings, cranberry sauce, and whipped cream.'}},
  'Canada':{fact:"Canada qualified for 2022 for the first time in 36 years AND co-hosts 2026! Alphonso Davies, Jonathan David, and a golden generation have transformed Canadian football.",recipe:{name:'🍟 Poutine',ing:['4 large russet potatoes (thick fries)','2 cups beef gravy, 2 cups fresh cheese curds','Salt and pepper'],steps:'Double fry potatoes until golden and crispy. Heat gravy until bubbling. Layer fries, add cheese curds, immediately smother with hot gravy. The heat slightly melts the curds. Serve at once.'}},
  'Bosnia and Herzegovina':{fact:"Bosnia and Herzegovina made their World Cup debut in 2014 and return in 2026! A passionate Balkan football culture — qualifying again is a massive national achievement.",recipe:{name:'🥩 Ćevapi',ing:['500g ground beef and lamb mixed','3 garlic cloves, salt, pepper, pinch baking soda','Somun flatbread, ajvar spread, raw onion, sour cream'],steps:'Mix meats with garlic and seasonings. Form into small finger sausages. Refrigerate 1 hr. Grill over high heat 8-10 min. Serve inside warm somun with ajvar and onion.'}},
  'Qatar':{fact:"Qatar hosted the 2022 World Cup — the first in the Middle East — transforming football infrastructure in the Gulf. Al-Annabi made their World Cup debut as hosts.",recipe:{name:'🍚 Machboos',ing:['Whole chicken cut up, 2 cups basmati rice','Baharat spices, onion, garlic, tomatoes','Raisins and fried onions to garnish'],steps:'Brown chicken with aromatics and spices. Parboil rice. Layer rice over chicken. Steam together on lowest heat 25 min. Garnish with raisins and fried onions.'}},
  'Switzerland':{fact:"Switzerland regularly qualifies and are always a solid, hard-to-beat team. Granit Xhaka leads a technically skilled, multicultural squad. They are never easy to beat.",recipe:{name:'🫕 Cheese Fondue',ing:['200g Gruyère grated, 200g Emmental grated','1 garlic clove, 300ml dry white wine','1 tbsp cornstarch + 2 tbsp Kirsch','Crusty bread and cornichons to dip'],steps:'Rub pot with garlic. Heat wine to simmer. Add cheese in handfuls, stirring in figure-8. Stir in cornstarch-Kirsch. Season with nutmeg. Keep stirring. Keep warm.'}},
  'Haiti':{fact:"Haiti makes their second World Cup appearance in 2026, having last qualified in 1974. Qualifying is a massive national achievement and cause for celebration. The Grenadiers play with incredible passion.",recipe:{name:'🍖 Griot (Fried Pork)',ing:['2 lbs pork shoulder cubed','Epis marinade: garlic, scotch bonnet, green onion, parsley, lime juice','Pikliz (spicy pickled slaw), rice and black beans to serve'],steps:'Marinate pork in epis overnight. Braise until tender. Fry until deeply caramelized and crispy. Serve with pikliz, rice, and black bean sauce.'}},
  'Scotland':{fact:"Scotland played in the first international match vs England in 1872. They've qualified for 8 World Cups, never advancing past the group stage. A fiercely proud football nation.",recipe:{name:'🥃 Cranachan',ing:['300ml double cream, 3 tbsp Scottish single malt whisky','3 tbsp heather honey, 100g pinhead oatmeal toasted','300g fresh raspberries'],steps:'Toast oatmeal. Whip cream to soft peaks. Fold in whisky and honey. Layer cream, raspberries, and oatmeal in glasses. Refrigerate 30 min. Top with raspberries. Slàinte Mhath!'}},
  'USA':{fact:"The USMNT co-hosts 2026 with a massive home advantage. Christian Pulisic leads a young, hungry squad. Soccer is booming in America and this could be the cultural tipping point for the sport.",recipe:{name:'🍔 Classic Cheeseburger',ing:['1 lb ground beef 80/20, 4 slices American cheese','4 brioche buns, lettuce, tomato, onion, pickles','Special sauce: mayo + ketchup + relish'],steps:'Form 4 patties, season with salt & pepper. Grill on high 3-4 min per side. Melt cheese in last minute. Toast buns. Build with all toppings and sauce.'}},
  'Paraguay':{fact:"Paraguay reached the World Cup quarter-finals in 2010, eliminated by eventual champions Spain. The Albirroja always make life difficult for big teams with physical, organized football.",recipe:{name:'🍖 Sopa Paraguaya',ing:["500g fresh farmer's cheese",'1 cup cornmeal, 1 cup milk, 3 eggs','1 onion sautéed in butter, salt to taste'],steps:"Paraguay's famous 'solid soup' — a savory cornbread. Mix all ingredients. Pour into buttered dish. Bake at 375°F for 45 min until golden. Serve warm alongside grilled meats."}},
  'Australia':{fact:"The Socceroos had their best World Cup in 2022, reaching the quarter-finals. Football is growing rapidly Down Under and the national team has never been more competitive.",recipe:{name:'🥧 Aussie Meat Pie',ing:['Shortcrust pastry base, puff pastry lid','500g ground beef, 1 onion','Beef stock, Worcestershire, tomato paste, flour','Tomato sauce (ketchup) to pour on top'],steps:'Brown mince with onion. Add stock, tomato paste, Worcestershire, thicken with flour. Cool completely. Line tin with shortcrust, fill, top with puff. Egg wash. Bake 390°F for 25-30 min.'}},
  'Turkiye':{fact:"Türkiye finished 3rd at the 2002 World Cup. Hakan Şükür scored the fastest World Cup goal ever — 11 seconds! Arda Güler of Real Madrid leads an exciting new generation.",recipe:{name:'🥙 Doner Kebab',ing:['Lamb and beef mixed, marinated overnight in yogurt and spices','Flatbread or pide, ezme (spicy tomato salad)','Garlicky yogurt sauce, pickled cabbage'],steps:'Roast marinated meat on vertical spit until caramelized. Shave thin. Serve in warm flatbread with all garnishes. The yogurt sauce is mandatory.'}},
  'Curacao':{fact:"Curaçao is one of the exciting newcomers to the 2026 World Cup! A small Caribbean island nation of just 160,000 people making their World Cup debut. A true fairy tale qualification.",recipe:{name:'🧀 Keshi Yena',ing:['1 whole Edam cheese (hollowed out)','Spiced chicken filling: onion, peppers, olives, capers, raisins, tomato paste, eggs to bind'],steps:"Hollow out an Edam cheese. Mix spiced cooked chicken filling with egg. Stuff the cheese shell. Bake at 350°F for 30-40 min until set and golden. Unmold and slice at the table."}},
  'Ivory Coast':{fact:"The Ivory Coast have appeared in 4 World Cups. Their golden generation featured Didier Drogba — one of Africa's greatest players ever. The Elephants always play with passion.",recipe:{name:'🍲 Kedjenou',ing:['1 whole chicken jointed','Onion, garlic, ginger, scotch bonnet, eggplant','Thyme, bay leaves, tomatoes — NO water added'],steps:"Place all ingredients in a sealed clay pot — no water. Cook over very low heat 1.5 hrs, shaking occasionally but never opening. Serve over attiéké (cassava couscous)."}},
  'Ecuador':{fact:"Ecuador opened the 2022 World Cup by defeating hosts Qatar 2-0. Enner Valencia scored all 3 of their tournament goals — becoming a national hero overnight.",recipe:{name:'🍲 Seco de Pollo',ing:['1 whole chicken jointed, 1 bottle beer','Ají amarillo, onion, garlic, cumin, tomatoes, cilantro','Yellow rice, avocado, fried plantains to serve'],steps:'Marinate chicken in beer and spices overnight. Brown pieces well. Simmer in blended pepper-tomato sauce 45 min. Serve over yellow rice with plantains and avocado.'}},
  'Japan':{fact:"Japan has qualified for every World Cup since 1998 and sensationally defeated Germany and Spain in 2022. The Samurai Blue always punch above their weight.",recipe:{name:'🍛 Chicken Katsu Curry',ing:['2 chicken breasts, panko coated and fried','Japanese curry roux (S&B Golden Curry)','Onion, carrot, potato, steamed Japanese rice'],steps:'Coat chicken in flour→egg→panko. Deep fry at 350°F until golden. Simmer vegetables, add curry roux until thick. Slice katsu over rice with curry poured alongside.'}},
  'Sweden':{fact:"Sweden's greatest World Cup was 1958 when they hosted and finished runners-up. Zlatan Ibrahimović is their all-time greatest player. A new generation now carries the flag.",recipe:{name:'🍢 Swedish Meatballs (Köttbullar)',ing:['500g ground beef and pork','1 onion grated, 1 egg, breadcrumbs soaked in milk, allspice','Cream gravy: butter, flour, beef stock, heavy cream','Lingonberry jam and pickled cucumber to serve'],steps:'Mix meats with onion, egg, soaked breadcrumbs, and spices. Roll into small balls. Brown in butter. Make gravy in same pan. Simmer meatballs in gravy 10 min. Serve with mashed potatoes and lingonberry jam.'}},
  'Tunisia':{fact:"Tunisia was the first African nation to win a World Cup match, defeating Mexico in 1978. The Eagles of Carthage have appeared in 6 World Cups and notably defeated France in 2022.",recipe:{name:'🥟 Brik',ing:['Thin pastry sheets, 1 whole egg per brik','Tuna, capers, harissa, parsley for filling','Oil for frying'],steps:"Lay pastry flat. Add filling, leaving a well. Crack a whole egg into the well — yolk must stay intact. Fold into a triangle. Fry until golden. The runny yolk inside is the prize."}},
  'Egypt':{fact:"Egypt have won the Africa Cup of Nations a record 7 times. Mohamed Salah — Liverpool legend — is their greatest modern player. The Pharaohs have a passionate football culture going back generations.",recipe:{name:'🫘 Koshari',ing:['Equal parts: rice, lentils, elbow macaroni','Crispy fried onions (lots!)','Dakka sauce: tomatoes, garlic, vinegar, cumin, chili','Spiced chickpeas'],steps:"Cook each element separately. Layer in bowl: lentil-rice, then macaroni. Pour spiced tomato dakka sauce. Pile on crispy onions and chickpeas. Add hot sauce to taste."}},
  'Iran':{fact:"Iran are Asia's most World Cup-qualified team with 6 appearances. They dramatically defeated England 6-2 in their 2022 opener. Football is deeply embedded in Persian culture.",recipe:{name:'🍚 Ghormeh Sabzi',ing:['500g lamb or beef cubed','Mixed herbs: fenugreek, parsley, leek (sautéed very dark in butter)','Kidney beans, 4 dried limes, onion, turmeric, saffron'],steps:'Fry herbs in butter until very dark and fragrant — the crucial step. Brown meat with onion. Add herbs, beans, dried limes, and water. Simmer 2 hours. Serve over saffron rice with tahdig.'}},
  'New Zealand':{fact:"New Zealand — the All Whites — are back at their second World Cup! They famously went undefeated at the 2010 World Cup without advancing. A rugby nation growing passionate about football.",recipe:{name:'🥝 Pavlova',ing:['4 egg whites at room temperature','1 cup caster sugar, 1 tsp white vinegar, 1 tsp cornstarch','Whipped cream, kiwi fruit, strawberries, passionfruit'],steps:'Beat egg whites to stiff peaks. Gradually add sugar until glossy. Fold in vinegar and cornstarch. Pile on parchment in a round. Bake at 275°F for 75 min. Cool in oven. Top with cream and fresh fruit.'}},
  'Cape Verde':{fact:"Cape Verde — the Blue Sharks — are making waves in African football! Their 2026 World Cup qualification is a historic achievement for this Atlantic island archipelago.",recipe:{name:'🐟 Cachupa Rica',ing:['Hominy corn and mixed beans (soaked overnight)','Linguiça sausage, chouriço, pork ribs, salt fish','Onion, garlic, tomato paste, bay leaves, cabbage, sweet potato'],steps:"Cape Verde's national dish — a slow-cooked stew that feeds a village. Cook hominy with meats and beans low and slow 3+ hours. Add vegetables last hour. Even better fried in a pan the next day."}},
  'Saudi Arabia':{fact:"Saudi Arabia produced one of the greatest World Cup upsets EVER — defeating Argentina 2-1 in 2022. Their high defensive line trap stunned Messi and company. A historically remarkable result.",recipe:{name:'🍗 Kabsa',ing:['Whole chicken cut up, 2 cups basmati rice','Kabsa spices: cardamom, cinnamon, cloves, black lime, cumin','Onion, garlic, tomatoes, raisins, toasted almonds'],steps:'Brown chicken with aromatics and spices. Cook rice in flavored stock. Layer rice over chicken. Steam on lowest heat 30 min. Fluff and garnish with raisins and almonds.'}},
  'Serbia':{fact:"Serbia have qualified for 3 World Cups as an independent nation. Aleksandar Mitrović is their record-breaking all-time top scorer. Known for producing exceptional goalkeeping talent.",recipe:{name:'🥩 Ćevapčići',ing:['300g ground beef, 200g ground pork','3 garlic cloves, salt, pepper, pinch baking soda','Lepinja flatbread, ajvar, raw onion, sour cream'],steps:'Mix meats with garlic and baking soda. Form into small finger sausages. Refrigerate 1 hour. Grill over high heat 8-10 min. Serve in warm lepinja with ajvar.'}},
  'Senegal':{fact:"Senegal eliminated defending champions France in 2002 and reached the quarter-finals. Sadio Mané — their greatest player — leads the Lions of Teranga. Always threatening on the big stage.",recipe:{name:'🍚 Thiéboudienne',ing:['Whole fish (grouper or snapper)','Broken rice, tomato paste, tamarind, guedj (dried fish)','Cabbage, cassava, carrots, eggplant, habanero'],steps:"Cook fish and vegetables in rich tomato-tamarind broth. Remove. Cook rice in the flavored broth until absorbed and a crust (the prized yakh!) forms on the bottom."}},
  'Iraq':{fact:"Iraq are making their 5th World Cup appearance in 2026! The Lions of Mesopotamia have a deeply passionate football culture. Qualifying despite tremendous challenges makes this especially meaningful.",recipe:{name:'🐟 Masgouf',ing:['1 large whole fish (3-4 lbs)','Olive oil, turmeric, tamarind paste, onion, garlic, flatbread to serve'],steps:"Iraq's iconic open-fire grilled fish. Split fish open like a book. Marinate in olive oil, turmeric, and tamarind. Prop vertically around an open fire and slow-cook 2-3 hours. Baghdad's signature dish."}},
  'Norway':{fact:"Norway famously defeated Brazil 2-1 in 1998. Now Erling Haaland — arguably the world's best striker — leads them back to the World Cup for the first time since 1998. The Haaland era begins!",recipe:{name:'🐟 Gravlaks (Cured Salmon)',ing:['1 lb fresh salmon fillet','3 tbsp coarse salt, 3 tbsp sugar, 1 tbsp crushed white pepper','Large bunch fresh dill, mustard-dill sauce to serve'],steps:'Mix salt, sugar, and pepper. Press dill onto salmon. Coat with cure mix. Wrap tightly. Refrigerate 48 hours, turning every 12 hrs. Slice paper-thin. Serve with mustard-dill sauce on dark rye bread.'}},
  'Algeria':{fact:"Algeria beat West Germany in 1982 in one of the World Cup's greatest upsets. They won the 2019 Africa Cup of Nations. Their passionate supporters are among the most vocal in world football.",recipe:{name:'🫕 Couscous Tfaya',ing:['Semolina couscous (steamed 3 times)','Lamb or chicken, chickpeas, root vegetables','Tfaya: caramelized onions + raisins + butter + cinnamon + saffron'],steps:"Steam couscous three times over broth for true fluffiness. Braise meat in spiced broth. Make tfaya by caramelizing onions with raisins and spices until jammy. Layer on a large communal platter."}},
  'Austria':{fact:"Austria's 'Wunderteam' was the best in Europe in the 1930s. David Alaba and Marko Arnautović lead a talented modern generation back to the World Cup.",recipe:{name:'🥩 Wiener Schnitzel',ing:['4 veal cutlets pounded very thin','Flour, beaten egg, coarse breadcrumbs (do NOT press in!)','Lard or clarified butter for frying','Lemon wedges, lingonberry jam, potato salad'],steps:'Pound cutlets very thin. Coat lightly: flour → egg → breadcrumbs. Fry in generous fat at 350°F, gently swirl pan. Golden in 3-4 min per side. Serve immediately with lemon.'}},
  'Jordan':{fact:"Jordan are making their World Cup debut in 2026 — a historic first for the Nashama! The nation has been rapidly developing football and qualifying is an enormous national achievement.",recipe:{name:'🍖 Mansaf',ing:['Lamb pieces or whole leg','Jameed (fermented dried yogurt) dissolved in water — essential!','Basmati rice with turmeric and ghee, shrak flatbread','Toasted almonds and pine nuts to garnish'],steps:"Braise lamb in jameed broth until very tender. Layer shrak on a huge platter, then rice, then lamb. Pour hot jameed sauce over everything. Garnish with nuts. Eat communally."}},
  'Portugal':{fact:"Euro 2016 champions. Cristiano Ronaldo scored at 5 consecutive World Cups. Bruno Fernandes and Bernardo Silva lead a technically gifted squad.",recipe:{name:'🐟 Bacalhau à Brás',ing:['500g salt cod (soaked 48hr), 4 beaten eggs','1 onion, 3 garlic cloves, fried shoestring potatoes, black olives, parsley'],steps:'Shred cod. Sauté onion and garlic. Add cod and potatoes. Pour eggs in off heat, fold until just creamy. Garnish with olives and parsley.'}},
  'DR Congo':{fact:"DR Congo (formerly Zaire) made their World Cup debut in 1974 and return in 2026! The Leopards have one of the most passionate football cultures in Africa. A remarkable qualification story.",recipe:{name:'🍲 Poulet à la Moambe',ing:['1 whole chicken cut up','Moambe (palm butter paste) — essential!','Onion, garlic, chili, salt, rice or fufu to serve'],steps:"Brown chicken. Make sauce with moambe paste, water, garlic, and chili — cook until oil rises to the top. Simmer chicken in sauce 45 min until very tender. Serve over rice."}},
  'Uzbekistan':{fact:"Uzbekistan are making their World Cup debut in 2026 — a historic first for Central Asia! Eldor Shomurodov of Roma is their star player. One of the great stories of this World Cup cycle.",recipe:{name:'🍚 Plov (Uzbek Rice)',ing:['500g lamb or beef cubed, 2 cups long-grain rice','3 carrots julienned, 2 onions sliced','Whole garlic heads, cumin, coriander, neutral oil'],steps:"Fry onion until dark. Add meat and brown. Add carrots and fry. Make zirvak broth with water and spices. Rest rice on top. Cook until absorbed. Do not stir. Uzbekistan's sacred national dish."}},
  'Colombia':{fact:"James Rodríguez won the 2014 World Cup Golden Boot with a stunning tournament. Colombia have a passionate football culture and are always capable of surprising anyone.",recipe:{name:'🍲 Bandeja Paisa',ing:['Slow-cooked red beans with pork belly, white rice','Chicharrón, chorizo, ground beef, fried egg, avocado, arepa, sweet plantain'],steps:'Prepare each component separately. Arrange everything on the largest plate you own — no combining. A feast, not a meal.'}},
  'England':{fact:"One World Cup (1966). Invented football. Jude Bellingham, Saka, and Foden give England their most exciting generation in decades. Always the hope, sometimes the heartbreak.",recipe:{name:'🐟 Fish & Chips',ing:['Thick cod fillets, beer batter, thick potatoes','Malt vinegar, mushy peas, tartar sauce'],steps:'Double fry chips. Beer-batter fish (lumpy is fine). Fry until golden. Salt immediately. Serve with vinegar.'}},
  'Croatia':{fact:"Croatia reached the World Cup final in 1998 (3rd) and 2022 (3rd). A nation of just 4 million producing world-class midfielders. Luka Modrić still leads them.",recipe:{name:'🍗 Peka (Bell Dish)',ing:['Chicken or lamb, potatoes, zucchini, peppers, tomatoes','Rosemary, garlic, olive oil, white wine'],steps:'Layer vegetables and meat in cast iron. Drizzle oil and wine. Cover tightly. Cook under coals or at 425°F for 90 min — never open while cooking.'}},
  'Ghana':{fact:"Ghana's Black Stars came agonizingly close to becoming the first African semi-finalist in 2010 before Luis Suárez's infamous handball. Their 2026 squad is hungry for redemption.",recipe:{name:'🍲 Jollof Rice (Ghana Style)',ing:['Long grain rice, blended tomatoes, red peppers, scotch bonnet, onion','Chicken stock, tomato paste, thyme, bay leaves, bouillon'],steps:'Fry tomato paste in oil until darkened. Add blended pepper mix and fry 20-30 min. Add stock and rice. Cook on very low heat — the bottom scorch (party jollof) is the prize.'}},
  'Panama':{fact:"Panama are making their second World Cup appearance! They debuted in 2018 and Román Torres scored their historic first ever World Cup goal. Their fans are famously loud and passionate.",recipe:{name:'🍲 Ropa Vieja',ing:['2 lbs flank steak (boiled and shredded)','Onion, garlic, tomatoes, red and green peppers, cumin, achiote','White rice and fried green plantains (patacones) to serve'],steps:'Boil flank steak until tender, shred into long strands. Sauté vegetables with achiote and cumin. Add shredded beef, cook 15 min. Serve over rice with crispy patacones.'}}
};

function renderFacts(){
  var el=document.getElementById('pg-facts');
  el.innerHTML='<div class="stitle">🌎 Country Facts & Recipes</div><div class="ssub">All 48 nations · Football history & traditional recipes</div><input class="fsearch" id="fsearch" placeholder="🔍 Search countries..." value="'+esc(factsQ)+'"><div class="facts-grid" id="facts-grid"></div>';
  document.getElementById('fsearch').addEventListener('input',function(){factsQ=this.value;renderFactsGrid();});
  renderFactsGrid();
}
function renderFactsGrid(){
  var grid=document.getElementById('facts-grid');if(!grid)return;
  var q=factsQ.toLowerCase();var html='';
  ALL.forEach(function(c){
    if(q&&!c.n.toLowerCase().includes(q))return;
    var d=FACTS[c.n];if(!d)return;
    var tab=factTabs[c.n]||'fact';var top=isTop10(c.n);
    html+='<div class="fcard"><div class="fhead"><span class="fflag">'+c.f+'</span><span class="fcname">'+esc(c.n)+'</span>'+(top?'<span class="ftop10-tag">🌟 TOP 10</span>':'')+'</div>';
    html+='<div class="ftabs"><button class="ftab'+(tab==='fact'?' active':'')+'" data-cn="'+esc(c.n)+'" data-tab="fact">⚽ Football</button><button class="ftab'+(tab==='recipe'?' active':'')+'" data-cn="'+esc(c.n)+'" data-tab="recipe">🍽️ Recipe</button></div>';
    html+='<div class="fbody">';
    if(tab==='fact')html+='<p>'+esc(d.fact)+'</p>';
    else html+='<div class="rtitle">'+d.recipe.name+'</div><ul class="ilist">'+d.recipe.ing.map(function(i){return'<li>'+esc(i)+'</li>';}).join('')+'</ul><p class="rsteps">'+esc(d.recipe.steps)+'</p>';
    html+='</div></div>';
  });
  if(!html)html='<div class="empty"><div class="ei">🔍</div><h3>No countries found</h3><p>Try a different search</p></div>';
  grid.innerHTML=html;
  grid.querySelectorAll('.ftab').forEach(function(b){b.addEventListener('click',function(){factTabs[this.dataset.cn]=this.dataset.tab;renderFactsGrid();});});
}

// ── SMACK TALK ────────────────────────────────────────────────────────────────
function renderSmack(){
  var el=document.getElementById('pg-smack');
  var html='<div class="stitle">💬 Smack Talk Board</div><div class="ssub">Family trash talk · Keep it (mostly) friendly</div><div class="sfeed">';
  if(!smack.length)html+='<div class="empty"><div class="ei">💬</div><h3>Silence...</h3><p>Be the first to talk smack</p></div>';
  else smack.slice().reverse().forEach(function(msg){var t=teams.find(function(x){return x.id===msg.tid;})||teams[0];html+='<div class="sbubble"><div class="shead"><span class="smascot">'+t.mascot+'</span><span class="steam">'+esc(t.name)+'</span><span class="stime">'+esc(msg.time)+'</span></div><div class="stext">'+esc(msg.text)+'</div></div>';});
  html+='</div><div class="card" style="margin-bottom:14px"><div style="font-family:Barlow Condensed,sans-serif;font-size:.78rem;letter-spacing:2px;color:var(--gray);text-transform:uppercase;margin-bottom:11px">Drop your message</div><div class="scompose"><select class="ssel" id="sselect">';
  teams.forEach(function(t){html+='<option value="'+t.id+'">'+t.mascot+' '+esc(t.name)+'</option>';});
  html+='</select><input class="sinput" id="sinput" placeholder="Talk your smack..." maxlength="140"><button class="btn btn-green" id="ssend">Send 🔥</button></div></div><button class="btn btn-outline" id="sclear" style="font-size:.78rem;padding:6px 14px">🗑️ Clear All</button>';
  el.innerHTML=html;
  function send(){var txt=document.getElementById('sinput').value.trim();var tid=+document.getElementById('sselect').value;if(!txt)return;smack.push({tid:tid,text:txt,time:'Just now'});saveState();document.getElementById('sinput').value='';renderSmack();}
  document.getElementById('ssend').addEventListener('click',send);
  document.getElementById('sinput').addEventListener('keydown',function(e){if(e.key==='Enter')send();});
  document.getElementById('sclear').addEventListener('click',function(){if(confirm('Clear all smack talk?')){smack=[];saveState();renderSmack();}});
}

// ── INIT ──────────────────────────────────────────────────────────────────────
renderPage('setup');
</script>
</body>
</html>
