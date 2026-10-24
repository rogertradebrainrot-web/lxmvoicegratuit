# lxmvoicegratuit
lxm voicemod gratuit 
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>LXM – Modificateur de voix 100 % gratuit pour Windows</title>
<meta name="description" content="LXM : 1000 voix, anti-bruit, musique et Discord. Un modificateur de voix 100 % gratuit pour Windows, créé par Rayhan Karim Mahdi.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@500;700;800&display=swap" rel="stylesheet">
<style>
:root{--bg:#f4f1ff;--ink:#17123a;--mute:#585180;--card:#ffffff;--line:#d9d2f5;--a:#2f7bff;--b:#a52bff;--c:#ff3d9a;--d:#1fb8d6;--glow:rgba(165,43,255,.18);color-scheme:light;
  box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#07051a;--ink:#f1eeff;--mute:#a7a1d1;--card:rgba(255,255,255,.06);--line:rgba(255,255,255,.14);--d:#4fe3ff;--glow:rgba(165,43,255,.35);color-scheme:dark}}
:root[data-theme="dark"]{--bg:#07051a;--ink:#f1eeff;--mute:#a7a1d1;--card:rgba(255,255,255,.06);--line:rgba(255,255,255,.14);--d:#4fe3ff;--glow:rgba(165,43,255,.35);color-scheme:dark}
html{scroll-padding-top:calc(76px + env(safe-area-inset-top,0px));scroll-behavior:smooth}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font-family:"Bricolage Grotesque",system-ui,"Segoe UI",sans-serif;line-height:1.55;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0 0 auto;height:env(safe-area-inset-top,0px);background:var(--bg);z-index:30}
.blob{position:fixed;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(55vw 45vw at 12% -5%,var(--glow),transparent 62%),radial-gradient(45vw 40vw at 100% 20%,rgba(47,123,255,.2),transparent 60%),radial-gradient(50vw 45vw at 50% 110%,rgba(255,61,154,.18),transparent 60%)}
a{color:inherit}
.wrap{max-width:1080px;margin:0 auto;padding:0 20px}
header{position:sticky;top:env(safe-area-inset-top,0px);z-index:40;backdrop-filter:blur(14px);background:color-mix(in srgb,var(--bg) 78%,transparent);border-bottom:1px solid var(--line)}
.bar{display:flex;align-items:center;gap:18px;height:64px}
.logo{display:inline-flex;align-items:center;gap:.3em;font-weight:800;font-size:1.6rem;letter-spacing:-.04em;text-decoration:none;font-style:italic}
.logo svg{width:1.15em;height:1.15em}
.logo span{background:linear-gradient(90deg,var(--ink),var(--d),var(--b));-webkit-background-clip:text;background-clip:text;color:transparent;padding-right:.1em}
nav{margin-left:auto;display:flex;gap:6px;align-items:center}
nav a{padding:8px 14px;border-radius:999px;text-decoration:none;font-weight:600;color:var(--mute)}
nav a:hover{color:var(--ink);background:var(--card)}
.btn{display:inline-flex;align-items:center;justify-content:center;gap:10px;padding:14px 26px;border-radius:999px;border:0;font:inherit;font-weight:800;font-size:1.05rem;cursor:pointer;text-decoration:none;color:#fff;background:linear-gradient(90deg,var(--a),var(--b),var(--c));background-size:200% 100%;box-shadow:0 12px 34px var(--glow);transition:transform .2s,background-position .4s}
.btn:hover{transform:translateY(-2px);background-position:100% 0}
.btn.ghost{background:var(--card);color:var(--ink);border:1px solid var(--line);box-shadow:none}
.btn[aria-disabled="true"]{opacity:.45;cursor:not-allowed;transform:none;filter:grayscale(.4)}
:focus-visible{outline:3px solid var(--d);outline-offset:3px}
.hero{padding:76px 0 56px;text-align:center}
.pill{display:inline-block;padding:7px 16px;border-radius:999px;border:1px solid var(--line);background:var(--card);font-weight:700;color:var(--mute);margin-bottom:22px}
h1{font-size:clamp(2.5rem,7.5vw,5rem);line-height:1.02;letter-spacing:-.04em;margin:0 0 18px;font-weight:800}
h1 em{font-style:normal;background:linear-gradient(90deg,var(--a),var(--b),var(--c));-webkit-background-clip:text;background-clip:text;color:transparent}
.lead{max-width:640px;margin:0 auto 30px;font-size:1.2rem;color:var(--mute)}
.cta{display:flex;gap:14px;justify-content:center;flex-wrap:wrap}
.wave{display:flex;gap:6px;height:84px;align-items:center;justify-content:center;margin:46px 0 0}
.wave i{width:9px;height:100%;border-radius:6px;background:linear-gradient(var(--d),var(--c));transform-origin:center;animation:eq 1s ease-in-out infinite alternate}
@keyframes eq{from{transform:scaleY(.12)}to{transform:scaleY(1)}}
section{padding:56px 0}
h2{font-size:clamp(1.8rem,4.5vw,2.8rem);letter-spacing:-.03em;margin:0 0 10px;line-height:1.1}
.sub{color:var(--mute);margin:0 0 32px;max-width:620px}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:16px}
.card{background:var(--card);border:1px solid var(--line);border-radius:22px;padding:22px;transition:transform .25s,border-color .25s}
.card:hover{transform:translateY(-4px);border-color:var(--b)}
.card .ic{font-size:2rem;margin-bottom:8px}
.card h3{margin:0 0 6px;font-size:1.2rem}.card p{margin:0;color:var(--mute)}
.steps{counter-reset:s;display:grid;gap:14px;max-width:760px}
.steps li{list-style:none;counter-increment:s;display:flex;gap:16px;align-items:flex-start;background:var(--card);border:1px solid var(--line);border-radius:18px;padding:16px 18px}
.steps li::before{content:counter(s);flex:none;width:34px;height:34px;border-radius:50%;display:grid;place-items:center;font-weight:800;color:#fff;background:linear-gradient(135deg,var(--a),var(--c))}
.steps{padding:0;margin:0}
.install{background:var(--card);border:1px solid var(--line);border-radius:30px;padding:clamp(22px,5vw,46px);text-align:center;box-shadow:0 30px 80px var(--glow)}
.install .big{font-size:3.2rem}
.chk{display:flex;gap:12px;align-items:flex-start;justify-content:center;max-width:560px;margin:22px auto;text-align:left;cursor:pointer}
.chk input{width:24px;height:24px;flex:none;margin-top:2px;accent-color:var(--b)}
.link{background:none;border:0;padding:0;font:inherit;color:var(--b);text-decoration:underline;cursor:pointer;font-weight:700}
#after{display:none;text-align:left;max-width:640px;margin:28px auto 0;padding:20px;border-radius:18px;border:1px dashed var(--b)}
#after.on{display:block}#after ol{margin:10px 0 0;padding-left:22px}#after li{margin:6px 0}
#notice{display:none;margin-top:16px;color:var(--c);font-weight:700}
.meta{display:flex;gap:10px 22px;flex-wrap:wrap;justify-content:center;color:var(--mute);font-size:.95rem;margin-top:18px}
details{background:var(--card);border:1px solid var(--line);border-radius:16px;padding:14px 18px;margin-bottom:10px}
summary{cursor:pointer;font-weight:700}details p{color:var(--mute);margin:10px 0 0}
footer{border-top:1px solid var(--line);padding:34px 0 40px;text-align:center;color:var(--mute)}
footer b{color:var(--ink)}
dialog{max-width:680px;width:calc(100% - 32px);max-height:84vh;border:1px solid var(--line);border-radius:24px;background:var(--bg);color:var(--ink);padding:0;box-shadow:0 40px 100px rgba(0,0,0,.45)}
dialog::backdrop{background:rgba(5,3,20,.65);backdrop-filter:blur(4px)}
.dh{display:flex;align-items:center;padding:18px 22px;border-bottom:1px solid var(--line)}.dh h3{margin:0;font-size:1.3rem;flex:1}
.dh button{background:none;border:0;font-size:1.4rem;color:var(--mute);cursor:pointer}
.db{padding:6px 22px 8px;overflow:auto;max-height:56vh}.db h4{margin:18px 0 4px}.db p{margin:0;color:var(--mute)}
.df{display:flex;gap:10px;justify-content:flex-end;padding:16px 22px;border-top:1px solid var(--line)}
.up{position:fixed;right:14px;bottom:calc(14px + env(safe-area-inset-bottom,0px));z-index:35}
@media (max-width:640px){nav a:not(.keep){display:none}.hero{padding-top:48px}}
@media (prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important;scroll-behavior:auto!important}}
</style>
</head>
<body>
<svg width="0" height="0" style="position:absolute" aria-hidden="true"><defs>
<linearGradient id="g1" x1="0" y1="0" x2="1" y2="1"><stop offset="0" stop-color="#2f7bff"/><stop offset=".5" stop-color="#a52bff"/><stop offset="1" stop-color="#ff3d9a"/></linearGradient>
<symbol id="lm" viewBox="0 0 64 64"><rect width="64" height="64" rx="18" fill="url(#g1)"/><rect width="64" height="30" rx="18" fill="#fff" opacity=".18"/><g fill="#fff"><rect x="5.5" y="25" width="5" height="14" rx="2.5"/><rect x="13.5" y="18" width="5" height="28" rx="2.5"/><rect x="21.5" y="10" width="5" height="44" rx="2.5"/><rect x="29.5" y="5" width="5" height="54" rx="2.5"/><rect x="37.5" y="12" width="5" height="40" rx="2.5"/><rect x="45.5" y="19" width="5" height="26" rx="2.5"/><rect x="53.5" y="26" width="5" height="12" rx="2.5"/></g></symbol></defs></svg>
<div class="blob" aria-hidden="true"></div>

<header><div class="wrap bar">
  <a class="logo" href="#top" aria-label="LXM, accueil"><svg viewBox="0 0 64 64" aria-hidden="true"><use href="#lm"/></svg><span>LXM</span></a>
  <nav aria-label="Navigation"><a href="#fonctions">Fonctions</a><a href="#comment">Comment ça marche</a><a href="#faq">Questions</a><a class="btn keep" href="#installer" style="padding:9px 18px;font-size:.95rem;color:#fff">Installer</a></nav>
</div></header>

<main id="top">
<div class="wrap hero">
  <span class="pill">🎉 Bienvenue sur LXM</span>
  <h1>Change ta voix.<br><em>Tout est gratuit.</em></h1>
  <p class="lead">Plus de 1000 voix, anti-bruit, musique et compatibilité Discord. Aucun abonnement, aucune pub, aucune voix verrouillée.</p>
  <div class="cta"><a class="btn" href="#installer">⬇️ Commencer maintenant</a><a class="btn ghost" href="#fonctions">Découvrir</a></div>
  <div class="wave" aria-hidden="true" id="wave"></div>
</div>

<section id="fonctions"><div class="wrap">
  <h2>Tout ce qu’il te faut, sans payer</h2>
  <p class="sub">Une application Windows complète, pensée pour jouer, discuter et s’amuser avec ta voix.</p>
  <div class="grid">
    <div class="card"><div class="ic">🎚️</div><h3>1000 voix</h3><p>Robot, monstre, fée, dragon, radio, cathédrale… triées par catégories, avec favoris et recherche.</p></div>
    <div class="card"><div class="ic">🧪</div><h3>Studio</h3><p>Crée ta propre voix avec des curseurs : hauteur, écho, réverbération, distorsion, filtres.</p></div>
    <div class="card"><div class="ic">🔇</div><h3>Anti-bruit</h3><p>Un filtre apprend le bruit de ta pièce (ventilateur, souffle) et le retire pendant que tu parles.</p></div>
    <div class="card"><div class="ic">🎵</div><h3>Musique</h3><p>Ajoute tes fichiers audio, lance-les et fais-les entendre à tout le monde sur Discord.</p></div>
    <div class="card"><div class="ic">💬</div><h3>Discord et jeux</h3><p>Fonctionne avec un micro virtuel : choisis-le dans Discord, ton jeu ou ton logiciel de stream.</p></div>
    <div class="card"><div class="ic">⌨️</div><h3>Raccourcis</h3><p>Change de voix en pleine partie avec Ctrl+Alt+1 à 9. Mode muet et sons à envoyer inclus.</p></div>
  </div>
</div></section>

<section id="comment"><div class="wrap">
  <h2>Comment ça marche</h2>
  <p class="sub">Trois étapes, moins de cinq minutes.</p>
  <ol class="steps">
    <li><div><b>Installe LXM</b><br><span style="color:var(--mute)">Télécharge l’installateur, lance-le, et laisse la case du micro virtuel cochée.</span></div></li>
    <li><div><b>Crée ton compte</b><br><span style="color:var(--mute)">Choisis ta langue, un pseudo et ton adresse email. Tout reste sur ton ordinateur.</span></div></li>
    <li><div><b>Parle avec une autre voix</b><br><span style="color:var(--mute)">Active le micro, choisis une voix, puis sélectionne « CABLE Output » comme micro dans Discord.</span></div></li>
  </ol>
</div></section>

<section id="installer"><div class="wrap">
  <div class="install">
    <div class="big">🚀</div>
    <h2>Prêt à commencer ?</h2>
    <p class="sub" style="margin:0 auto">Accepte les conditions d’utilisation pour débloquer le téléchargement.</p>
    <label class="chk" for="ok"><input type="checkbox" id="ok"><span>J’ai lu et j’accepte les <button type="button" class="link" id="openT">conditions d’utilisation</button> de LXM.</span></label>
    <a class="btn" id="dl" href="#installer" role="button" aria-disabled="true">⬇️ Télécharger LXM pour Windows</a>
    <p id="notice" role="status">Le lien de téléchargement n’a pas encore été ajouté par le créateur du site.</p>
    <div class="meta"><span>🪟 Windows 10 ou 11 (64 bits)</span><span>💾 ≈ 111 Mo</span><span>🆓 100 % gratuit</span><span>Version 9.0</span></div>
    <div id="after"><b>Après le téléchargement :</b>
      <ol>
        <li>Ouvre le fichier <b>LXM-Setup.exe</b>.</li>
        <li>Si Windows affiche « Windows a protégé votre ordinateur », clique sur <b>Informations complémentaires</b>, puis <b>Exécuter quand même</b>. L’application n’est pas signée par un éditeur payant, c’est normal.</li>
        <li>Garde coché le <b>micro virtuel</b> pour utiliser LXM sur Discord, puis redémarre ton PC.</li>
        <li>Lance LXM, choisis ta langue et crée ton compte.</li>
      </ol></div>
  </div>
</div></section>

<section id="faq"><div class="wrap">
  <h2>Questions fréquentes</h2><p class="sub">Les réponses courtes.</p>
  <details><summary>C’est vraiment gratuit ?</summary><p>Oui. Toutes les voix, tous les outils et la musique sont accessibles sans payer, sans abonnement et sans publicité.</p></details>
  <details><summary>Pourquoi un micro virtuel ?</summary><p>Pour que Discord et les jeux reçoivent ta voix transformée. L’installateur propose de le mettre en place (VB-Cable, un logiciel tiers gratuit).</p></details>
  <details><summary>Mes données sont-elles envoyées quelque part ?</summary><p>Ton pseudo et ton email restent enregistrés sur ton ordinateur. Ta voix est traitée localement et n’est pas envoyée sur internet.</p></details>
  <details><summary>Ça marche sur Mac ou téléphone ?</summary><p>Pas pour le moment : LXM est prévu pour Windows 10 et 11.</p></details>
</div></section>
</main>

<footer><div class="wrap">
  <a class="logo" href="#top" style="font-size:1.4rem"><svg viewBox="0 0 64 64" aria-hidden="true"><use href="#lm"/></svg><span>LXM</span></a>
  <p style="margin:14px 0 4px">Créé par <b>Rayhan Karim Mahdi</b></p>
  <p style="margin:0">© 2026 LXM · Tous droits réservés · <button type="button" class="link" id="openT2">Conditions d’utilisation</button></p>
</div></footer>

<dialog id="terms" aria-labelledby="tt">
  <div class="dh"><h3 id="tt">Conditions d’utilisation de LXM</h3><button type="button" id="x" aria-label="Fermer">✕</button></div>
  <div class="db">
    <p style="margin-top:14px">Dernière mise à jour : octobre 2026. En téléchargeant ou en utilisant LXM, tu acceptes les conditions ci-dessous.</p>
    <h4>1. Qui est derrière LXM</h4><p>LXM est un logiciel de modification de voix pour Windows, créé par Rayhan Karim Mahdi (« le créateur »).</p>
    <h4>2. Gratuité</h4><p>LXM est gratuit au moment du téléchargement : sans abonnement, sans publicité et sans voix payante.</p>
    <h4>3. Licence d’utilisation</h4><p>Le créateur te donne le droit d’utiliser LXM pour ton usage personnel. Il est interdit de revendre LXM, de le redistribuer sous un autre nom ou de s’en attribuer la création sans accord écrit.</p>
    <h4>4. Usage responsable</h4><p>Tu es seul responsable de ce que tu dis avec LXM. Il est interdit de l’utiliser pour usurper l’identité de quelqu’un, harceler, menacer, arnaquer, tromper des personnes ou tenir des propos illégaux.</p>
    <h4>5. Musique et droits d’auteur</h4><p>Tu ne dois ajouter et diffuser que des musiques dont tu possèdes les droits ou dont l’usage est autorisé. Diffuser de la musique protégée sur Discord ou en stream peut enfreindre des droits d’auteur : cette responsabilité est la tienne.</p>
    <h4>6. Données personnelles</h4><p>Le pseudo et l’adresse email saisis dans LXM sont enregistrés sur ton ordinateur et ne sont pas envoyés par l’application. Ta voix est traitée localement. L’affichage peut charger une police depuis Google Fonts. Si tu coches le micro virtuel, l’installateur télécharge VB-Cable depuis le site de VB-Audio, un logiciel tiers soumis à ses propres conditions.</p>
    <h4>7. Aucune garantie</h4><p>LXM est fourni « tel quel », sans garantie de fonctionnement continu ou sans erreur. Dans les limites permises par la loi, le créateur n’est pas responsable des dommages liés à l’utilisation du logiciel.</p>
    <h4>8. Marques</h4><p>LXM n’est affilié à aucune autre marque ou service cité (comme Discord ou VB-Audio). Ces noms appartiennent à leurs propriétaires.</p>
    <h4>9. Évolution des conditions</h4><p>Ces conditions peuvent évoluer. La version affichée sur ce site fait foi.</p>
    <h4>10. Contact</h4><p>Pour toute question, contacte le créateur, Rayhan Karim Mahdi.</p>
  </div>
  <div class="df"><button type="button" class="btn ghost" id="no" style="padding:11px 20px">Fermer</button><button type="button" class="btn" id="yes" style="padding:11px 22px">J’accepte</button></div>
</dialog>

<script>
// ➜ Colle ici le lien de téléchargement de LXM-Setup.exe (GitHub Releases, Google Drive, ton hébergeur…)
const DOWNLOAD_URL = "";

const $ = id => document.getElementById(id);
const dl = $('dl'), ok = $('ok'), terms = $('terms');
$('wave').innerHTML = Array.from({length: 23}, (_, i) => `<i style="animation-delay:${(i * 0.07).toFixed(2)}s;animation-duration:${(0.7 + (i % 5) * 0.12).toFixed(2)}s"></i>`).join('');

function refresh() {
  const on = ok.checked;
  dl.setAttribute('aria-disabled', on ? 'false' : 'true');
  if (DOWNLOAD_URL && on) { dl.href = DOWNLOAD_URL; dl.setAttribute('download', 'LXM-Setup.exe'); }
  else { dl.removeAttribute('download'); dl.href = '#installer'; }
  try { localStorage.setItem('lxm-terms', on ? '1' : '0'); } catch (e) {}
}
try { ok.checked = localStorage.getItem('lxm-terms') === '1'; } catch (e) {}
refresh();
ok.addEventListener('change', refresh);
dl.addEventListener('click', e => {
  if (dl.getAttribute('aria-disabled') === 'true') { e.preventDefault(); $('notice').style.display = 'block'; $('notice').textContent = 'Accepte d’abord les conditions d’utilisation.'; ok.focus(); return; }
  if (!DOWNLOAD_URL) { e.preventDefault(); $('notice').style.display = 'block'; $('notice').textContent = 'Le lien de téléchargement n’a pas encore été ajouté par le créateur du site.'; }
  else { $('notice').style.display = 'none'; }
  $('after').classList.add('on');
});
const open = () => terms.showModal ? terms.showModal() : terms.setAttribute('open', '');
$('openT').onclick = $('openT2').onclick = open;
$('x').onclick = $('no').onclick = () => terms.close();
$('yes').onclick = () => { ok.checked = true; refresh(); terms.close(); };
terms.addEventListener('click', e => { if (e.target === terms) terms.close(); });
</script>
</body>
</html>
