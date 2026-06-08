<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Château de l'Infini — Registre disciplinaire</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@latest/dist/tabler-icons.min.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <style>
    :root {
      --font-sans: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, sans-serif;
      --border-radius-lg: 14px;
      --border-radius-md: 8px;
      --color-text-primary: #1a1831;
      --color-text-secondary: #6b6b8a;
      --color-background-primary: #ffffff;
      --color-background-secondary: #f4f3fb;
      --color-border-secondary: #e0dff0;
      --color-border-tertiary: #ece9f8;
    }

    * { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      font-family: var(--font-sans);
      background: var(--color-background-secondary);
      min-height: 100vh;
      display: flex;
      align-items: flex-start;
      justify-content: center;
      padding: 1.5rem 1rem 3rem;
    }

    .app-shell {
      width: 100%;
      max-width: 520px;
    }
  </style>
</head>
<body>
  <div class="app-shell">

<style>
@import url('https://fonts.googleapis.com/css2?family=Cinzel:wght@400;500;700&display=swap');

.ds-root{font-family:var(--font-sans);padding:0 0 2rem;}

.ds-hero{background:#26215C;border-radius:var(--border-radius-lg);padding:2rem 1.75rem 1.5rem;margin-bottom:1.5rem;position:relative;overflow:hidden;}
.ds-hero::before{content:'';position:absolute;top:-40px;right:-40px;width:160px;height:160px;border-radius:50%;border:1px solid rgba(174,169,236,0.18);}
.ds-hero::after{content:'';position:absolute;top:-10px;right:-10px;width:100px;height:100px;border-radius:50%;border:1px solid rgba(174,169,236,0.10);}
.ds-hero-inner{display:flex;align-items:center;gap:16px;}
.ds-crest{width:52px;height:52px;border-radius:50%;border:1.5px solid #AFA9EC;display:flex;align-items:center;justify-content:center;flex-shrink:0;}
.ds-hero-title{font-family:'Cinzel',serif;font-size:18px;font-weight:700;color:#EEEDFE;letter-spacing:0.04em;line-height:1.3;}
.ds-hero-sub{font-size:12px;color:#AFA9EC;margin-top:3px;letter-spacing:0.06em;text-transform:uppercase;}
.ds-hero-divider{height:1px;background:rgba(174,169,236,0.2);margin:1.25rem 0;}
.ds-stats{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;}
.ds-stat{text-align:center;}
.ds-stat-num{font-family:'Cinzel',serif;font-size:22px;font-weight:700;color:#EEEDFE;}
.ds-stat-lbl{font-size:11px;color:#7F77DD;margin-top:2px;letter-spacing:0.04em;}

.ds-nav{display:flex;gap:0;margin-bottom:1.5rem;border:0.5px solid var(--color-border-secondary);border-radius:var(--border-radius-lg);overflow:hidden;}
.ds-nav-btn{flex:1;padding:11px 8px;border:none;background:transparent;color:var(--color-text-secondary);cursor:pointer;font-size:13px;font-family:var(--font-sans);display:flex;align-items:center;justify-content:center;gap:6px;border-right:0.5px solid var(--color-border-tertiary);transition:background 0.15s,color 0.15s;}
.ds-nav-btn:last-child{border-right:none;}
.ds-nav-btn.active{background:#26215C;color:#EEEDFE;}
.ds-nav-btn:not(.active):hover{background:var(--color-background-secondary);}

.sec{display:none;}.sec.on{display:block;}

.search-wrap{display:flex;align-items:center;gap:8px;background:var(--color-background-secondary);border:0.5px solid var(--color-border-secondary);border-radius:var(--border-radius-md);padding:9px 13px;margin-bottom:1rem;}
.search-wrap input{border:none;background:transparent;outline:none;flex:1;font-size:14px;color:var(--color-text-primary);font-family:var(--font-sans);}

.loi-item{border:0.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-lg);margin-bottom:8px;background:var(--color-background-primary);overflow:hidden;cursor:pointer;transition:border-color 0.15s;}
.loi-item:hover{border-color:var(--color-border-secondary);}
.loi-head{display:flex;align-items:center;gap:12px;padding:12px 16px;}
.loi-num{width:26px;height:26px;border-radius:50%;background:#EEEDFE;color:#3C3489;display:flex;align-items:center;justify-content:center;font-size:11px;font-weight:500;flex-shrink:0;}
.loi-name{flex:1;font-size:13px;font-weight:500;color:var(--color-text-primary);}
.pill{font-size:11px;padding:3px 9px;border-radius:50px;border:0.5px solid;white-space:nowrap;font-weight:500;}
.pill-g{background:#FCEBEB;color:#791F1F;border-color:#F09595;}
.pill-m{background:#FAEEDA;color:#633806;border-color:#FAC775;}
.pill-l{background:#EAF3DE;color:#27500A;border-color:#C0DD97;}
.loi-body{display:none;padding:0 16px 14px;border-top:0.5px solid var(--color-border-tertiary);}
.loi-item.open .loi-body{display:block;}
.loi-item.open .loi-head{border-bottom:0.5px solid var(--color-border-tertiary);}
.sanction-line{display:flex;gap:10px;align-items:flex-start;padding:7px 0;border-bottom:0.5px solid var(--color-border-tertiary);}
.sanction-line:last-child{border-bottom:none;}
.sanction-tag{font-size:11px;color:#7F77DD;font-weight:500;min-width:100px;padding-top:1px;}
.sanction-val{font-size:13px;color:var(--color-text-secondary);}

.form-block{background:var(--color-background-primary);border:0.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-lg);padding:1.25rem;margin-bottom:1rem;}
.form-block-title{font-size:13px;font-weight:500;color:var(--color-text-primary);margin-bottom:1rem;display:flex;align-items:center;gap:8px;}
.form-block-title span{display:flex;align-items:center;justify-content:center;width:24px;height:24px;border-radius:50%;background:#EEEDFE;color:#3C3489;flex-shrink:0;}
.field-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px;}
.field{display:flex;flex-direction:column;gap:4px;}
.field label{font-size:11px;color:var(--color-text-secondary);letter-spacing:0.03em;}
.field input,.field select,.field textarea{border:0.5px solid var(--color-border-secondary);border-radius:var(--border-radius-md);padding:8px 10px;font-size:13px;background:var(--color-background-secondary);color:var(--color-text-primary);outline:none;font-family:var(--font-sans);}
.field textarea{resize:vertical;min-height:60px;}
.field-full{grid-column:1/-1;}

.preview-card{border:1px solid #3C3489;border-radius:var(--border-radius-lg);overflow:hidden;margin-bottom:1rem;}
.preview-header{background:#26215C;padding:1.25rem 1.5rem;display:flex;align-items:center;gap:14px;}
.preview-avatar{width:44px;height:44px;border-radius:50%;border:1.5px solid #AFA9EC;display:flex;align-items:center;justify-content:center;flex-shrink:0;}
.preview-name{font-family:'Cinzel',serif;font-size:15px;font-weight:700;color:#EEEDFE;}
.preview-grade{font-size:12px;color:#AFA9EC;margin-top:2px;}
.preview-body{padding:1.25rem 1.5rem;background:var(--color-background-primary);}
.preview-grid{display:grid;grid-template-columns:1fr 1fr;gap:8px;margin-bottom:12px;}
.preview-cell{background:var(--color-background-secondary);border-radius:var(--border-radius-md);padding:10px 12px;}
.preview-cell-lbl{font-size:11px;color:var(--color-text-secondary);margin-bottom:3px;}
.preview-cell-val{font-size:13px;font-weight:500;color:var(--color-text-primary);}
.sanction-highlight{background:#FCEBEB;border:0.5px solid #F09595;border-radius:var(--border-radius-md);padding:12px 14px;margin-bottom:12px;}
.sanction-highlight-lbl{font-size:11px;color:#A32D2D;margin-bottom:4px;letter-spacing:0.04em;text-transform:uppercase;}
.sanction-highlight-val{font-size:14px;font-weight:500;color:#791F1F;}
.preview-footer{display:flex;align-items:center;justify-content:space-between;padding-top:10px;border-top:0.5px solid var(--color-border-tertiary);}
.stamp{border:1.5px solid #A32D2D;border-radius:var(--border-radius-md);padding:4px 14px;font-family:'Cinzel',serif;font-size:12px;font-weight:700;color:#A32D2D;letter-spacing:0.08em;}
.preview-date{font-size:11px;color:var(--color-text-secondary);}

.btn-row{display:flex;gap:8px;flex-wrap:wrap;margin-top:1rem;}
.btn-primary{padding:9px 18px;background:#26215C;color:#EEEDFE;border:none;border-radius:var(--border-radius-md);cursor:pointer;font-size:13px;font-family:var(--font-sans);display:inline-flex;align-items:center;gap:6px;}
.btn-secondary{padding:9px 18px;background:transparent;border:0.5px solid var(--color-border-secondary);color:var(--color-text-secondary);border-radius:var(--border-radius-md);cursor:pointer;font-size:13px;font-family:var(--font-sans);display:inline-flex;align-items:center;gap:6px;}

.rec-card{border:0.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-lg);margin-bottom:8px;background:var(--color-background-primary);overflow:hidden;}
.rec-top{display:flex;align-items:center;gap:12px;padding:12px 16px;}
.rec-av{width:36px;height:36px;border-radius:50%;background:#EEEDFE;color:#3C3489;display:flex;align-items:center;justify-content:center;font-size:12px;font-weight:500;flex-shrink:0;}
.rec-name{font-size:14px;font-weight:500;color:var(--color-text-primary);}
.rec-sub{font-size:12px;color:var(--color-text-secondary);}
.rec-body{padding:0 16px 12px;display:grid;grid-template-columns:1fr 1fr;gap:6px;}
.rec-field{font-size:12px;}
.rec-field-lbl{color:#7F77DD;margin-bottom:1px;}
.rec-field-val{color:var(--color-text-secondary);}
.rec-field-wide{grid-column:1/-1;}
.btn-del{background:transparent;border:none;color:var(--color-text-secondary);cursor:pointer;padding:4px;margin-left:auto;}
.btn-del:hover{color:#A32D2D;}

.filter-row{display:flex;gap:8px;margin-bottom:1rem;flex-wrap:wrap;}
.filter-row select{font-size:13px;padding:7px 10px;border-radius:var(--border-radius-md);border:0.5px solid var(--color-border-secondary);background:var(--color-background-secondary);color:var(--color-text-primary);font-family:var(--font-sans);}
.empty{text-align:center;padding:3rem 1rem;color:var(--color-text-secondary);font-size:14px;}

.overlay{display:none;min-height:480px;background:rgba(0,0,0,0.5);border-radius:var(--border-radius-lg);align-items:flex-start;justify-content:center;padding:2rem 1rem;}
.overlay.open{display:flex;}
.modal{background:var(--color-background-primary);border-radius:var(--border-radius-lg);border:0.5px solid var(--color-border-secondary);padding:1.5rem;width:100%;max-width:440px;}
.modal-title{font-family:'Cinzel',serif;font-size:15px;font-weight:700;color:var(--color-text-primary);margin-bottom:1.25rem;}
.modal-actions{display:flex;gap:8px;justify-content:flex-end;margin-top:1rem;}
.modal-actions button{padding:8px 16px;border-radius:var(--border-radius-md);cursor:pointer;font-size:13px;font-family:var(--font-sans);}
</style>

<div class="ds-root">

<div class="ds-hero">
  <div class="ds-hero-inner">
    <div class="ds-crest"><i class="ti ti-shield" style="font-size:24px;color:#AFA9EC;" aria-hidden="true"></i></div>
    <div>
      <div class="ds-hero-title">Château de l'Infini</div>
      <div class="ds-hero-sub">Registre disciplinaire démoniaque</div>
    </div>
  </div>
  <div class="ds-hero-divider"></div>
  <div class="ds-stats">
    <div class="ds-stat"><div class="ds-stat-num" id="s-lois">22</div><div class="ds-stat-lbl">Lois</div></div>
    <div class="ds-stat"><div class="ds-stat-num" id="s-total">0</div><div class="ds-stat-lbl">Infractions</div></div>
    <div class="ds-stat"><div class="ds-stat-num" id="s-fautifs">0</div><div class="ds-stat-lbl">Démons fautifs</div></div>
  </div>
</div>

<div class="ds-nav">
  <button class="ds-nav-btn active" onclick="go('lois',this)"><i class="ti ti-book" aria-hidden="true"></i> Lois</button>
  <button class="ds-nav-btn" onclick="go('sanction',this)"><i class="ti ti-file-description" aria-hidden="true"></i> Émettre</button>
  <button class="ds-nav-btn" onclick="go('historique',this)"><i class="ti ti-clock-history" aria-hidden="true"></i> Historique</button>
</div>

<div id="lois" class="sec on">
  <div class="search-wrap">
    <i class="ti ti-search" style="font-size:16px;color:var(--color-text-secondary);" aria-hidden="true"></i>
    <input type="text" id="q" placeholder="Rechercher une loi..." oninput="renderLois()">
  </div>
  <div id="lois-list"></div>
</div>

<div id="sanction" class="sec">
  <div class="form-block">
    <div class="form-block-title"><span><i class="ti ti-user" style="font-size:14px;" aria-hidden="true"></i></span> Identité du démon</div>
    <div class="field-grid">
      <div class="field"><label>Prénom</label><input type="text" id="f-prenom" placeholder="Ex : Akaza" oninput="upv()"></div>
      <div class="field"><label>Nom</label><input type="text" id="f-nom" placeholder="Ex : Kizuki" oninput="upv()"></div>
      <div class="field"><label>Grade / Rang</label><input type="text" id="f-grade" placeholder="Ex : Lune Supérieure 3" oninput="upv()"></div>
      <div class="field"><label>Pouvoir / Art du sang</label><input type="text" id="f-pouvoir" placeholder="Ex : Destruction totale" oninput="upv()"></div>
    </div>
  </div>
  <div class="form-block">
    <div class="form-block-title"><span><i class="ti ti-gavel" style="font-size:14px;" aria-hidden="true"></i></span> Infraction commise</div>
    <div class="field-grid">
      <div class="field field-full"><label>Loi enfreinte</label><select id="f-loi" onchange="upv()"><option value="">— Sélectionner une loi —</option></select></div>
      <div class="field"><label>Type d'infraction</label><select id="f-type" onchange="upv()"><option>1re infraction</option><option>Récidive</option><option>2e infraction</option></select></div>
      <div class="field"><label>Date</label><input type="date" id="f-date" oninput="upv()"></div>
      <div class="field field-full"><label>Notes / Contexte</label><textarea id="f-notes" placeholder="Témoins, circonstances..." oninput="upv()"></textarea></div>
    </div>
  </div>

  <p style="font-size:12px;font-weight:500;color:var(--color-text-secondary);letter-spacing:0.06em;text-transform:uppercase;margin-bottom:10px;">Aperçu de la fiche officielle</p>
  <div class="preview-card">
    <div class="preview-header">
      <div class="preview-avatar"><i class="ti ti-shield" style="font-size:20px;color:#AFA9EC;" aria-hidden="true"></i></div>
      <div style="flex:1;">
        <div class="preview-name" id="pv-nom">— Nom du démon —</div>
        <div class="preview-grade" id="pv-grade">Grade non renseigné</div>
      </div>
      <span class="pill" id="pv-pill" style="display:none;"></span>
    </div>
    <div class="preview-body">
      <div class="preview-grid">
        <div class="preview-cell"><div class="preview-cell-lbl">Pouvoir</div><div class="preview-cell-val" id="pv-pouvoir">—</div></div>
        <div class="preview-cell"><div class="preview-cell-lbl">Type d'infraction</div><div class="preview-cell-val" id="pv-type">—</div></div>
        <div class="preview-cell" style="grid-column:1/-1;"><div class="preview-cell-lbl">Loi enfreinte</div><div class="preview-cell-val" id="pv-loi">—</div></div>
      </div>
      <div class="sanction-highlight" id="pv-sanction-wrap" style="display:none;">
        <div class="sanction-highlight-lbl">Sanction appliquée</div>
        <div class="sanction-highlight-val" id="pv-sanction"></div>
      </div>
      <div class="preview-cell" id="pv-notes-wrap" style="display:none;margin-bottom:12px;"><div class="preview-cell-lbl">Notes</div><div class="preview-cell-val" id="pv-notes" style="font-weight:400;"></div></div>
      <div class="preview-footer">
        <span class="preview-date" id="pv-date"></span>
        <span class="stamp">SANCTIONNÉ</span>
      </div>
    </div>
  </div>
  <div class="btn-row">
    <button class="btn-primary" onclick="saveFiche()"><i class="ti ti-device-floppy" aria-hidden="true"></i> Enregistrer</button>
    <button class="btn-secondary" onclick="window.print()"><i class="ti ti-printer" aria-hidden="true"></i> Imprimer</button>
  </div>
</div>

<div id="historique" class="sec">
  <div class="filter-row">
    <select id="fl-sev" onchange="renderHisto()"><option value="">Toutes sévérités</option><option>Légère</option><option>Moyenne</option><option>Grave</option></select>
    <select id="fl-loi" onchange="renderHisto()"><option value="">Toutes les lois</option></select>
  </div>
  <div id="histo-list"></div>
  <div class="overlay" id="modal">
    <div class="modal">
      <div class="modal-title">Nouvelle infraction</div>
      <div class="field-grid">
        <div class="field"><label>Prénom</label><input type="text" id="m-prenom" placeholder="Prénom"></div>
        <div class="field"><label>Nom</label><input type="text" id="m-nom" placeholder="Nom"></div>
        <div class="field"><label>Rang</label><input type="text" id="m-rang" placeholder="Lune Inf. 4"></div>
        <div class="field"><label>Pouvoir</label><input type="text" id="m-pouvoir" placeholder="Art du sang..."></div>
        <div class="field field-full"><label>Loi enfreinte</label><select id="m-loi"><option value="">— Sélectionner —</option></select></div>
        <div class="field field-full"><label>Type</label><select id="m-type"><option>1re infraction</option><option>Récidive</option><option>2e infraction</option></select></div>
        <div class="field field-full"><label>Notes</label><textarea id="m-notes" placeholder="Contexte..."></textarea></div>
      </div>
      <div class="modal-actions">
        <button style="background:transparent;border:0.5px solid var(--color-border-secondary);color:var(--color-text-secondary);" onclick="closeModal()">Annuler</button>
        <button style="background:#26215C;color:#EEEDFE;border:none;" onclick="saveModal()">Enregistrer</button>
      </div>
    </div>
  </div>
  <button class="btn-primary" onclick="openModal()"><i class="ti ti-plus" aria-hidden="true"></i> Ajout rapide</button>
</div>

</div>

<script>
const LOIS=[
  {t:"Courir dans le Château de l'Infini",s:"Légère",p:[{l:"1re infraction",v:"Sceau de la Droiture"},{l:"Récidive",v:"10 min de cachot + 5 000 yens ou rétrogradation"}]},
  {t:"S'interférer dans les combats d'entraînement",s:"Moyenne",p:[{l:"Sanction",v:"15 min de cachot + Sceau de la Droiture"}]},
  {t:"Dégrader le Château de l'Infini",s:"Grave",p:[{l:"Sanction",v:"20 min de cachot + 10 000 yens + rétrogradation"}]},
  {t:"Manquer de respect à ses supérieurs ou à d'autres démons",s:"Moyenne",p:[{l:"Sanction",v:"20 min de cachot + 2 000 yens ou rétrogradation"}]},
  {t:"Utiliser ses pouvoirs sanguinaires dans le Château",s:"Grave",p:[{l:"Sanction",v:"20 min de cachot + 10 000 yens ou rétrogradation"}]},
  {t:"Ne pas se prosterner face à une Lune",s:"Moyenne",p:[{l:"Sanction",v:"Sceau de la Droiture + 5 000 yens ou rétrogradation"}]},
  {t:"Accéder à des zones interdites",s:"Grave",p:[{l:"1re infraction",v:"Sceau de la Droiture"},{l:"Récidive",v:"30 min de cachot + 5 000 yens + rétrogradation"}]},
  {t:"Se camoufler au sein du Château",s:"Grave",p:[{l:"Sanction",v:"20 min de cachot + 10 000 yens ou rétrogradation"}]},
  {t:"Entrer dans la salle des Lunes sans autorisation",s:"Grave",p:[{l:"Sanction",v:"30 min de cachot + rétrogradation ou Peine de Mort"}]},
  {t:"Ignorer un appel d'un supérieur",s:"Moyenne",p:[{l:"Sanction",v:"40 min de cachot + tâche disciplinaire supplémentaire"}]},
  {t:"Mentir ou dissimuler une infraction",s:"Grave",p:[{l:"Sanction",v:"50 min de cachot + 5 000 yens ou rétrogradation"}]},
  {t:"Tenter de falsifier son rang",s:"Grave",p:[{l:"Sanction",v:"1 heure de cachot + rétrogradation immédiate ou Peine de Mort"}]},
  {t:"Refuser un ordre direct d'un supérieur",s:"Grave",p:[{l:"Sanction",v:"30 min de cachot + 5 000 yens ou Sceau de la Droiture + rétrogradation"}]},
  {t:"Être en retard à un entraînement obligatoire",s:"Légère",p:[{l:"1re infraction",v:"Avertissement"},{l:"Récidive",v:"20 min de cachot"}]},
  {t:"Tenter de tromper un supérieur",s:"Grave",p:[{l:"Sanction",v:"Sceau de la Droiture + 50 min de cachot + 10 000 yens ou rétrogradation"}]},
  {t:"Ignorer les ordres directs des Lunes",s:"Grave",p:[{l:"Sanction",v:"Sceau de la Droiture + rétrogradation immédiate ou Peine de Mort"}]},
  {t:"S'opposer à une sanction disciplinaire",s:"Moyenne",p:[{l:"Sanction",v:"Sceau de la Droiture + amende de 5 000 yens"}]},
  {t:"Perturber les réunions officielles",s:"Moyenne",p:[{l:"Sanction",v:"30 min de cachot + Sceau de la Droiture"}]},
  {t:"Utiliser un langage inapproprié",s:"Légère",p:[{l:"1re infraction",v:"Sceau de la Droiture"},{l:"Récidive",v:"Sceau de la Droiture + rétrogradation"}]},
  {t:"Refuser d'exécuter une tâche attribuée",s:"Moyenne",p:[{l:"1re infraction",v:"Sceau de la Droiture"},{l:"Récidive",v:"30 min de cachot + 10 000 yens + rétrogradation"}]},
  {t:"Non-respect d'un traité",s:"Grave",p:[{l:"1re infraction",v:"20 min de cachot + 10 000 yens ou rétrogradation"},{l:"Récidive",v:"Rétrogradation + marque de la droiture"}]},
  {t:"S'entraîner devant le Château de l'Infini",s:"Légère",p:[{l:"1re infraction",v:"Avertissement"},{l:"2e infraction",v:"20 min de cachot + 10 000 yens ou rétrogradation"},{l:"Récidive",v:"30 min de cachot + 20 000 yens + rétrogradation"}]}
];

let DB=[];
try{const r=localStorage.getItem('ci_v3');if(r)DB=JSON.parse(r);}catch(e){}
const save=()=>{try{localStorage.setItem('ci_v3',JSON.stringify(DB));}catch(e){}};

function pc(s){return s==='Grave'?'pill-g':s==='Moyenne'?'pill-m':'pill-l';}
function gs(loi,type){const l=LOIS.find(x=>x.t===loi);if(!l)return null;return l.p.find(p=>p.l===type)||l.p.find(p=>p.l==='Sanction')||l.p[0];}
function fmtDate(v){if(!v)return new Date().toLocaleDateString('fr-FR',{day:'2-digit',month:'long',year:'numeric'});return new Date(v).toLocaleDateString('fr-FR',{day:'2-digit',month:'long',year:'numeric'});}

function go(id,btn){
  document.querySelectorAll('.sec').forEach(s=>s.classList.remove('on'));
  document.querySelectorAll('.ds-nav-btn').forEach(b=>b.classList.remove('active'));
  document.getElementById(id).classList.add('on');
  btn.classList.add('active');
  if(id==='historique')renderHisto();
  updateStats();
}

function updateStats(){
  document.getElementById('s-total').textContent=DB.length;
  document.getElementById('s-fautifs').textContent=new Set(DB.map(i=>(i.prenom+' '+i.nom).trim())).size;
}

function renderLois(){
  const q=(document.getElementById('q').value||'').toLowerCase();
  const c=document.getElementById('lois-list');
  c.innerHTML='';
  LOIS.forEach((l,i)=>{
    if(q&&!l.t.toLowerCase().includes(q))return;
    const d=document.createElement('div');
    d.className='loi-item';
    d.innerHTML=`<div class="loi-head"><div class="loi-num">${i+1}</div><div class="loi-name">${l.t}</div><span class="pill ${pc(l.s)}">${l.s}</span><i class="ti ti-chevron-down" style="font-size:15px;color:var(--color-text-secondary);" aria-hidden="true"></i></div><div class="loi-body">${l.p.map(p=>`<div class="sanction-line"><span class="sanction-tag">${p.l}</span><span class="sanction-val">${p.v}</span></div>`).join('')}</div>`;
    d.querySelector('.loi-head').onclick=()=>d.classList.toggle('open');
    c.appendChild(d);
  });
}

function populateSels(){
  ['f-loi','m-loi','fl-loi'].forEach(id=>{
    const el=document.getElementById(id);if(!el)return;
    const isFilter=id==='fl-loi';
    el.innerHTML=isFilter?'<option value="">Toutes les lois</option>':'<option value="">— Sélectionner —</option>';
    LOIS.forEach(l=>{const o=document.createElement('option');o.value=l.t;o.textContent=l.t.length>55?l.t.slice(0,52)+'…':l.t;el.appendChild(o);});
  });
}

function upv(){
  const prenom=document.getElementById('f-prenom').value.trim();
  const nom=document.getElementById('f-nom').value.trim();
  const grade=document.getElementById('f-grade').value.trim();
  const pouvoir=document.getElementById('f-pouvoir').value.trim();
  const loi=document.getElementById('f-loi').value;
  const type=document.getElementById('f-type').value;
  const notes=document.getElementById('f-notes').value.trim();
  const dateV=document.getElementById('f-date').value;
  const full=[prenom,nom].filter(Boolean).join(' ')||'— Nom du démon —';
  document.getElementById('pv-nom').textContent=full;
  document.getElementById('pv-grade').textContent=grade||'Grade non renseigné';
  document.getElementById('pv-pouvoir').textContent=pouvoir||'—';
  document.getElementById('pv-type').textContent=type;
  document.getElementById('pv-loi').textContent=loi||'—';
  const l=LOIS.find(x=>x.t===loi);
  const pill=document.getElementById('pv-pill');
  if(l){pill.textContent=l.s;pill.className='pill '+pc(l.s);pill.style.display='';}else{pill.style.display='none';}
  const sc=loi?gs(loi,type):null;
  const sw=document.getElementById('pv-sanction-wrap');
  if(sc){sw.style.display='';document.getElementById('pv-sanction').textContent=sc.v;}else{sw.style.display='none';}
  const nw=document.getElementById('pv-notes-wrap');
  if(notes){nw.style.display='';document.getElementById('pv-notes').textContent=notes;}else{nw.style.display='none';}
  document.getElementById('pv-date').textContent=fmtDate(dateV);
}

function saveFiche(){
  const prenom=document.getElementById('f-prenom').value.trim();
  const nom=document.getElementById('f-nom').value.trim();
  if(!prenom&&!nom){alert('Veuillez renseigner le nom du démon.');return;}
  const loi=document.getElementById('f-loi').value;
  if(!loi){alert('Veuillez sélectionner une loi.');return;}
  DB.push({prenom,nom,grade:document.getElementById('f-grade').value.trim(),pouvoir:document.getElementById('f-pouvoir').value.trim(),loi,type:document.getElementById('f-type').value,notes:document.getElementById('f-notes').value.trim(),date:fmtDate(document.getElementById('f-date').value)});
  save();updateStats();
  alert('Infraction enregistrée avec succès.');
}

function openModal(){document.getElementById('modal').classList.add('open');}
function closeModal(){document.getElementById('modal').classList.remove('open');}
function saveModal(){
  const prenom=document.getElementById('m-prenom').value.trim();
  const nom=document.getElementById('m-nom').value.trim();
  const loi=document.getElementById('m-loi').value;
  if(!prenom&&!nom){alert('Veuillez renseigner le nom.');return;}
  if(!loi){alert('Veuillez sélectionner une loi.');return;}
  DB.push({prenom,nom,grade:document.getElementById('m-rang').value.trim(),pouvoir:document.getElementById('m-pouvoir').value.trim(),loi,type:document.getElementById('m-type').value,notes:document.getElementById('m-notes').value.trim(),date:new Date().toLocaleDateString('fr-FR')});
  save();closeModal();renderHisto();updateStats();
  ['m-prenom','m-nom','m-rang','m-pouvoir','m-notes'].forEach(id=>document.getElementById(id).value='');
}

function deleteRec(idx){if(!confirm('Supprimer cette infraction ?'))return;DB.splice(idx,1);save();renderHisto();updateStats();}

function renderHisto(){
  const sf=document.getElementById('fl-sev').value;
  const lf=document.getElementById('fl-loi').value;
  let data=DB.map((d,i)=>({...d,_i:i}));
  if(sf)data=data.filter(d=>{const l=LOIS.find(x=>x.t===d.loi);return l&&l.s===sf;});
  if(lf)data=data.filter(d=>d.loi===lf);
  const c=document.getElementById('histo-list');
  if(data.length===0){c.innerHTML='<div class="empty"><i class="ti ti-mood-smile" style="font-size:32px;display:block;margin:0 auto 8px;" aria-hidden="true"></i>Aucune infraction enregistrée</div>';return;}
  c.innerHTML='';
  data.slice().reverse().forEach(d=>{
    const l=LOIS.find(x=>x.t===d.loi);
    const sev=l?l.s:'';
    const sc=d.loi?gs(d.loi,d.type):null;
    const full=[d.prenom,d.nom].filter(Boolean).join(' ')||'Inconnu';
    const init=full.split(' ').map(w=>w[0]).join('').slice(0,2).toUpperCase();
    const div=document.createElement('div');
    div.className='rec-card';
    div.innerHTML=`<div class="rec-top"><div class="rec-av">${init}</div><div style="flex:1;"><div class="rec-name">${full}</div><div class="rec-sub">${d.grade||'Rang non précisé'}${d.pouvoir?' · '+d.pouvoir:''}</div></div><span class="pill ${pc(sev)}" style="margin-right:6px;">${sev}</span><button class="btn-del" onclick="deleteRec(${d._i})" aria-label="Supprimer"><i class="ti ti-trash" aria-hidden="true"></i></button></div><div class="rec-body"><div class="rec-field rec-field-wide"><div class="rec-field-lbl">Loi enfreinte</div><div class="rec-field-val">${d.loi}</div></div>${sc?`<div class="rec-field rec-field-wide"><div class="rec-field-lbl">Sanction</div><div class="rec-field-val">${sc.v}</div></div>`:''}<div class="rec-field"><div class="rec-field-lbl">Type</div><div class="rec-field-val">${d.type}</div></div><div class="rec-field"><div class="rec-field-lbl">Date</div><div class="rec-field-val">${d.date}</div></div>${d.notes?`<div class="rec-field rec-field-wide"><div class="rec-field-lbl">Notes</div><div class="rec-field-val">${d.notes}</div></div>`:''}</div>`;
    c.appendChild(div);
  });
}

document.getElementById('f-date').value=new Date().toISOString().split('T')[0];
populateSels();renderLois();updateStats();upv();
</script>

  </div>
</body>
</html>
