<svg viewBox="0 0 1000 240" fill="none" xmlns="http://www.w3.org/2000/svg">
  <style>
    text { font-family: 'SFMono-Regular', Consolas, 'Liberation Mono', Menlo, monospace; }
    .tbl { font-size: 14px; fill: #E6EDF3; font-weight: 700; }
    .sub { font-size: 11px; fill: #8B949E; }
    .ann { font-size: 10px; fill: #58A6FF; }
    .cap { font-size: 12px; fill: #3FB950; }
    .cmt { font-size: 12px; fill: #8B949E; }
    .gate { font-size: 11px; fill: #E0B341; }
    .flow { stroke: #E0B341; stroke-width: 2; stroke-dasharray: 6 6; animation: dash 1.2s linear infinite; }
    @keyframes dash { to { stroke-dashoffset: -12; } }
  </style>

  <rect x="2" y="2" width="996" height="236" rx="10" fill="#0D1117" stroke="#30363D"/>
  <text x="24" y="30" class="cap">sumit_prajapat=# EXPLAIN ANALYZE how_i_ship;   -- largest end-to-end run: 9M+ NAV rows</text>

  <!-- stage boxes -->
  <g>
    <rect x="28"  y="52" width="138" height="76" rx="8" fill="#161B22" stroke="#3FB950"/>
    <text x="97"  y="76" text-anchor="middle" class="tbl">raw_data</text>
    <text x="97"  y="94" text-anchor="middle" class="sub">csv · api · files</text>
    <text x="97"  y="112" text-anchor="middle" class="ann">(rows=raw, untrusted)</text>

    <rect x="190" y="52" width="138" height="76" rx="8" fill="#161B22" stroke="#3FB950"/>
    <text x="259" y="76" text-anchor="middle" class="tbl">azure_blob</text>
    <text x="259" y="94" text-anchor="middle" class="sub">landing zone</text>
    <text x="259" y="112" text-anchor="middle" class="ann">(immutable source)</text>

    <rect x="352" y="52" width="138" height="76" rx="8" fill="#161B22" stroke="#3FB950"/>
    <text x="421" y="76" text-anchor="middle" class="tbl">data_factory</text>
    <text x="421" y="94" text-anchor="middle" class="sub">ETL pipelines</text>
    <text x="421" y="112" text-anchor="middle" class="ann">(typed · scheduled)</text>

    <rect x="514" y="52" width="138" height="76" rx="8" fill="#161B22" stroke="#3FB950"/>
    <text x="583" y="76" text-anchor="middle" class="tbl">postgresql</text>
    <text x="583" y="94" text-anchor="middle" class="sub">star schema</text>
    <text x="583" y="112" text-anchor="middle" class="ann">(facts + dims, indexed)</text>

    <rect x="676" y="52" width="150" height="76" rx="8" fill="#161B22" stroke="#3FB950"/>
    <text x="751" y="76" text-anchor="middle" class="tbl">power_bi + ml</text>
    <text x="751" y="94" text-anchor="middle" class="sub">DAX · scikit-learn</text>
    <text x="751" y="112" text-anchor="middle" class="ann">(40+ measures · Prophet)</text>

    <rect x="850" y="52" width="122" height="76" rx="8" fill="#161B22" stroke="#E0B341"/>
    <text x="911" y="76" text-anchor="middle" class="tbl" fill="#E0B341">decisions</text>
    <text x="911" y="94" text-anchor="middle" class="sub">one headline</text>
    <text x="911" y="112" text-anchor="middle" class="ann">(quantified)</text>
  </g>

  <!-- animated flow arrows -->
  <line x1="166" y1="90" x2="190" y2="90" class="flow"/>
  <line x1="328" y1="90" x2="352" y2="90" class="flow"/>
  <line x1="490" y1="90" x2="514" y2="90" class="flow"/>
  <line x1="652" y1="90" x2="676" y2="90" class="flow"/>
  <line x1="826" y1="90" x2="850" y2="90" class="flow"/>

  <!-- quality gates row -->
  <text x="28" y="168" class="cmt">-- quality gates:</text>
  <rect x="168" y="150" width="106" height="26" rx="13" fill="none" stroke="#E0B341"/>
  <text x="221" y="167" text-anchor="middle" class="gate">grain checks</text>
  <rect x="286" y="150" width="100" height="26" rx="13" fill="none" stroke="#E0B341"/>
  <text x="336" y="167" text-anchor="middle" class="gate">null audits</text>
  <rect x="398" y="150" width="70" height="26" rx="13" fill="none" stroke="#E0B341"/>
  <text x="433" y="167" text-anchor="middle" class="gate">dedup</text>
  <rect x="480" y="150" width="168" height="26" rx="13" fill="none" stroke="#E0B341"/>
  <text x="564" y="167" text-anchor="middle" class="gate">reconcile to source</text>
  <rect x="660" y="150" width="176" height="26" rx="13" fill="none" stroke="#E0B341"/>
  <text x="748" y="167" text-anchor="middle" class="gate">artifact-vs-signal test</text>

  <!-- plan footer -->
  <text x="28" y="206" class="cmt">Planning Time: design the schema first.   Execution Time: shipped.</text>
  <text x="28" y="226" class="cmt">Rows affected: every stakeholder in the room.</text>
</svg>
