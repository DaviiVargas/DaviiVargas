<!doctype html>
<html lang="pt-BR">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Davi Gabriel Vargas | Analista de dados</title>
<meta name="description" content="Portfólio de Davi Gabriel Vargas, analista de dados. Dashboards em Power BI, automação com Python e análises ligadas a problemas de negócio.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,400;12..96,600;12..96,800&family=IBM+Plex+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
:root{--bg:#edf1f5;--surface:#fff;--ink:#101820;--muted:#4b5b6b;--brand:#0b5d63;--mark:#f2c230;--line:#cfd8e1;--on-brand:#fff}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#0d1519;--surface:#15222a;--ink:#e8eef2;--muted:#9fb0bd;--brand:#4fc3c9;--mark:#f2c230;--line:#26363f;--on-brand:#06222a}}
:root[data-theme="dark"]{--bg:#0d1519;--surface:#15222a;--ink:#e8eef2;--muted:#9fb0bd;--brand:#4fc3c9;--mark:#f2c230;--line:#26363f;--on-brand:#06222a}
*{box-sizing:border-box}
html{scroll-behavior:smooth;scroll-padding-top:72px}
body{margin:0;background:var(--bg);color:var(--ink);font:400 1.05rem/1.65 "Bricolage Grotesque",system-ui,sans-serif}
a{color:inherit}
:focus-visible{outline:3px solid var(--mark);outline-offset:3px}
.wrap{max-width:1080px;margin:0 auto;padding:0 24px}
header{position:sticky;top:0;z-index:5;background:color-mix(in srgb,var(--bg) 88%,transparent);backdrop-filter:blur(8px);border-bottom:1px solid var(--line)}
header .wrap{display:flex;align-items:center;justify-content:space-between;gap:16px;min-height:60px}
nav ul{display:flex;gap:20px;list-style:none;margin:0;padding:0;flex-wrap:wrap}
nav a{text-decoration:none;font-weight:600;font-size:.95rem;color:var(--muted)}
nav a:hover{color:var(--ink)}
.logo{font-weight:800;text-decoration:none;letter-spacing:-.01em}
#tema{background:none;border:1px solid var(--line);color:var(--ink);width:38px;height:38px;border-radius:50%;cursor:pointer;font-size:1.1rem}
.hero{padding:72px 0 56px;display:grid;grid-template-columns:1.3fr 1fr;gap:48px;align-items:center}
h1{font-size:clamp(2.6rem,7vw,5rem);line-height:1;letter-spacing:-.03em;font-weight:800;margin:0 0 20px}
.hero p{max-width:46ch;color:var(--muted);font-size:1.15rem;margin:0 0 28px}
.btns{display:flex;gap:12px;flex-wrap:wrap}
.btn{display:inline-block;padding:12px 22px;border-radius:999px;font-weight:600;text-decoration:none;border:2px solid var(--brand)}
.btn.main{background:var(--brand);color:var(--on-brand)}
.btn:hover{background:var(--mark);border-color:var(--mark);color:#101820}
.foto{aspect-ratio:4/5;border-radius:28px;background:var(--surface);border:2px dashed var(--line);display:grid;place-items:center;text-align:center;color:var(--muted);padding:24px;font-size:.95rem;overflow:hidden}
.foto img{width:100%;height:100%;object-fit:cover}
section{padding:56px 0;border-top:1px solid var(--line)}
.q{font:500 .9rem/1.4 "IBM Plex Mono",monospace;color:var(--brand);margin:0 0 10px;overflow-wrap:anywhere}
h2{font-size:clamp(1.9rem,4vw,2.8rem);letter-spacing:-.02em;line-height:1.1;margin:0 0 10px}
.sub{color:var(--muted);margin:0 0 32px;max-width:56ch}
.sobre{display:grid;grid-template-columns:1fr 1fr;gap:40px}
.sobre p{margin:0 0 14px;max-width:62ch}
.facts{display:grid;gap:12px;align-content:start}
.fact{background:var(--surface);border:1px solid var(--line);border-radius:16px;padding:16px 20px}
.fact b{display:block;font-size:1.05rem}
.fact span{color:var(--muted);font-size:.95rem}
.skills{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:20px}
.skill{background:var(--surface);border:1px solid var(--line);border-radius:20px;padding:24px}
.skill h3{margin:0 0 12px;font-size:1.15rem}
.tags{display:flex;flex-wrap:wrap;gap:8px;padding:0;margin:0;list-style:none}
.tags li{font:500 .85rem "IBM Plex Mono",monospace;background:color-mix(in srgb,var(--brand) 12%,transparent);color:var(--brand);padding:4px 10px;border-radius:8px}
.tl{list-style:none;margin:0;padding:0 0 0 28px;border-left:3px solid var(--brand)}
.tl li{position:relative;padding-bottom:28px}
.tl li::before{content:"";position:absolute;left:-37px;top:8px;width:15px;height:15px;border-radius:50%;background:var(--mark);border:3px solid var(--bg)}
.tl time{font:500 .85rem "IBM Plex Mono",monospace;color:var(--muted)}
.tl h3{margin:2px 0 4px;font-size:1.2rem}
.tl p{margin:0;color:var(--muted);max-width:60ch}
.proj{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:24px}
.card{background:var(--surface);border:1px solid var(--line);border-radius:20px;overflow:hidden;text-align:left;padding:0;cursor:pointer;color:inherit;font:inherit}
.card:hover{border-color:var(--brand)}
.thumb{aspect-ratio:16/9;background:linear-gradient(135deg,var(--brand),color-mix(in srgb,var(--brand) 40%,var(--mark)));display:grid;place-items:center;color:var(--on-brand);font-weight:800;font-size:1.3rem;padding:16px;text-align:center}
.thumb img{width:100%;height:100%;object-fit:cover}
.card div.t{padding:20px}
.card h3{margin:0 0 6px;font-size:1.2rem}
.card p{margin:0 0 12px;color:var(--muted);font-size:.98rem}
dialog{border:0;border-radius:24px;max-width:760px;width:calc(100% - 32px);padding:0;background:var(--surface);color:var(--ink)}
dialog::backdrop{background:rgba(5,12,16,.7)}
.dlg{padding:32px}
.dlg .thumb{border-radius:16px;margin-bottom:20px}
.dlg h3{font-size:1.6rem;margin:0 0 8px}
.dlg h4{margin:20px 0 4px}
.dlg p,.dlg ul{margin:0;color:var(--muted)}
.fechar{float:right;background:none;border:1px solid var(--line);color:var(--ink);width:38px;height:38px;border-radius:50%;cursor:pointer;font-size:1rem}
.contato a.link{display:inline-block;font-size:clamp(1.3rem,3.2vw,2rem);font-weight:800;margin:6px 24px 6px 0}
footer{padding:32px 0 48px;color:var(--muted);font-size:.9rem;border-top:1px solid var(--line)}
@media (max-width:760px){.hero,.sobre{grid-template-columns:1fr}.foto{max-width:340px}nav ul{gap:12px}}
@media (prefers-reduced-motion:reduce){html{scroll-behavior:auto}}
</style>
</head>
<body>
<header>
  <div class="wrap">
    <a class="logo" href="#inicio">Davi Vargas</a>
    <nav aria-label="Principal">
      <ul>
        <li><a href="#sobre">Sobre</a></li>
        <li><a href="#competencias">Competências</a></li>
        <li><a href="#curriculo">Currículo</a></li>
        <li><a href="#projetos">Projetos</a></li>
        <li><a href="#contato">Contato</a></li>
      </ul>
    </nav>
    <button id="tema" type="button" aria-label="Alternar tema claro e escuro">◐</button>
  </div>
</header>

<main>
<div class="wrap hero" id="inicio">
  <div>
    <h1>Davi Gabriel Vargas</h1>
    <p>Analista de dados. Transformo problemas de negócio em dashboards, análises e automações que a equipe consegue usar no dia a dia.</p>
    <div class="btns">
      <a class="btn main" href="#projetos">Ver projetos</a>
      <a class="btn" href="#contato">Falar comigo</a>
      <a class="btn" href="curriculo.pdf">Baixar currículo</a>
    </div>
  </div>
  <div class="foto">
    <!-- Troque este bloco por: <img src="assets/foto.jpg" alt="Descreva sua foto"> -->
    <span>Sua foto aqui<br>(assets/foto.jpg)</span>
  </div>
</div>

<section id="sobre"><div class="wrap">
  <p class="q">SELECT * FROM sobre_mim;</p>
  <h2>Resumo executivo</h2>
  <div class="sobre">
    <div>
      <p>[Edite] Sou analista de dados e trabalho com Power BI para transformar filas, indicadores e planilhas em painéis que apoiam decisões.</p>
      <p>[Edite] Estou aprofundando Python para automatizar processos repetitivos e liberar tempo para análises que realmente mudam um resultado.</p>
      <p>[Edite] Gosto de começar pelo problema de negócio e só depois escolher a ferramenta.</p>
    </div>
    <div class="facts">
      <div class="fact"><b>Analista de dados</b><span>[Edite: formação e área]</span></div>
      <div class="fact"><b>Power BI e Python</b><span>Dashboards e automação de processos</span></div>
      <div class="fact"><b>[Cidade, UF]</b><span>[Edite: disponibilidade e modelo de trabalho]</span></div>
    </div>
  </div>
</div></section>

<section id="competencias"><div class="wrap">
  <p class="q">SELECT * FROM competencias ORDER BY destaque DESC;</p>
  <h2>Minhas competências</h2>
  <p class="sub">O que eu levo para o time: técnica, clareza e cuidado com o detalhe.</p>
  <div class="skills">
    <div class="skill"><h3>Análise e BI</h3><ul class="tags"><li>Power BI</li><li>DAX</li><li>Excel</li><li>Storytelling com dados</li></ul></div>
    <div class="skill"><h3>Programação</h3><ul class="tags"><li>Python (em estudo)</li><li>Pandas</li><li>SQL</li></ul></div>
    <div class="skill"><h3>Negócio</h3><ul class="tags"><li>Indicadores e metas</li><li>Documentação de processos</li><li>Comunicação com liderança</li></ul></div>
  </div>
</div></section>

<section id="curriculo"><div class="wrap">
  <p class="q">FROM curriculo ORDER BY data DESC;</p>
  <h2>Histórico de dados</h2>
  <p class="sub">Minha formação e minha experiência.</p>
  <ol class="tl">
    <li><time>[Ano] – atual</time><h3>Analista de dados · [Empresa]</h3><p>[Edite: o que você entrega, com um número se tiver. Ex.: painel que reduziu X% de retrabalho.]</p></li>
    <li><time>[Ano] – [Ano]</time><h3>[Cargo anterior] · [Empresa]</h3><p>[Edite]</p></li>
    <li><time>[Ano] – [Ano]</time><h3>[Curso] · [Instituição]</h3><p>[Edite]</p></li>
  </ol>
</div></section>

<section id="projetos"><div class="wrap">
  <p class="q">SELECT * FROM projetos WHERE status = 'pronto';</p>
  <h2>Relatórios e dashboards</h2>
  <p class="sub">Análises que construí para resolver problemas reais e mostrar como eu penso os dados.</p>
  <div class="proj">
    <button class="card" type="button" data-p="0">
      <div class="thumb">Fila de chamados</div>
      <div class="t"><h3>Dashboard executivo de chamados</h3><p>Painel em Power BI para acompanhar a fila de atendimento e entender por que tantos chamados expiram sem resposta.</p><ul class="tags"><li>Power BI</li><li>DAX</li></ul></div>
    </button>
    <button class="card" type="button" data-p="1">
      <div class="thumb">Automação em Python</div>
      <div class="t"><h3>[Nome do projeto 2]</h3><p>[Edite: uma frase com o problema e o resultado.]</p><ul class="tags"><li>Python</li><li>Pandas</li></ul></div>
    </button>
    <button class="card" type="button" data-p="2">
      <div class="thumb">Análise exploratória</div>
      <div class="t"><h3>[Nome do projeto 3]</h3><p>[Edite: uma frase com o problema e o resultado.]</p><ul class="tags"><li>SQL</li><li>Excel</li></ul></div>
    </button>
  </div>
</div></section>

<section id="contato" class="contato"><div class="wrap">
  <p class="q">INNER JOIN voce ON interesse;</p>
  <h2>Vamos conversar?</h2>
  <p class="sub">Tem um problema de negócio que precisa de dados? Me chama.</p>
  <a class="link" href="https://www.linkedin.com/in/davi-gabriel-vargas/" target="_blank" rel="noopener">LinkedIn</a>
  <a class="link" href="mailto:seu@email.com">E-mail</a>
  <a class="link" href="https://github.com/seu-usuario" target="_blank" rel="noopener">GitHub</a>
</div></section>
</main>

<footer><div class="wrap">© <span id="ano"></span> Davi Gabriel Vargas</div></footer>

<dialog id="dlg" aria-labelledby="dt"><div class="dlg">
  <button class="fechar" type="button" id="fechar" aria-label="Fechar">✕</button>
  <div class="thumb" id="dimg"></div>
  <h3 id="dt"></h3>
  <p id="dd"></p>
  <h4>Problema</h4><p id="dp"></p>
  <h4>O que eu fiz</h4><p id="df"></p>
  <h4>Resultado</h4><p id="dr"></p>
</div></dialog>

<script>
const projetos=[
 {t:"Dashboard executivo de chamados",d:"Power BI · DAX",p:"Muitos chamados da fila expiravam sem atendimento e ninguém enxergava onde o gargalo estava.",f:"[Edite: modelagem dos dados, medidas DAX, visões por fila, prazo e responsável.]",r:"[Edite: o que mudou depois do painel, de preferência com número.]",i:"Fila de chamados"},
 {t:"[Nome do projeto 2]",d:"Python · Pandas",p:"[Edite]",f:"[Edite]",r:"[Edite]",i:"Automação em Python"},
 {t:"[Nome do projeto 3]",d:"SQL · Excel",p:"[Edite]",f:"[Edite]",r:"[Edite]",i:"Análise exploratória"}
];
const dlg=document.getElementById("dlg"),$=id=>document.getElementById(id);
document.querySelectorAll(".card").forEach(c=>c.addEventListener("click",()=>{
  const p=projetos[+c.dataset.p];
  $("dt").textContent=p.t;$("dd").textContent=p.d;$("dp").textContent=p.p;$("df").textContent=p.f;$("dr").textContent=p.r;$("dimg").textContent=p.i;
  dlg.showModal();
}));
$("fechar").addEventListener("click",()=>dlg.close());
dlg.addEventListener("click",e=>{if(e.target===dlg)dlg.close()});
$("ano").textContent=new Date().getFullYear();
const root=document.documentElement;
$("tema").addEventListener("click",()=>{
  const escuro=root.dataset.theme?root.dataset.theme==="dark":matchMedia("(prefers-color-scheme:dark)").matches;
  root.dataset.theme=escuro?"light":"dark";
});
</script>
</body>
</html>
