<svg viewBox="0 0 1000 170" fill="none" xmlns="http://www.w3.org/2000/svg">
  <style>
    text { font-family: 'SFMono-Regular', Consolas, 'Liberation Mono', Menlo, monospace; }
    .tbl { font-size: 14px; fill: #E6EDF3; font-weight: 700; }
    .sub { font-size: 11px; fill: #8B949E; }
    .cap { font-size: 12px; fill: #3FB950; }
    .flow { stroke: #E0B341; stroke-width: 2; stroke-dasharray: 6 6; animation: dash 1.2s linear infinite; }
    @keyframes dash { to { stroke-dashoffset: -12; } }
  </style>

  <rect x="2" y="2" width="996" height="166" rx="10" fill="#0D1117" stroke="#30363D"/>
  <text x="24" y="30" class="cap">sumit_prajapat=# EXPLAIN ANALYZE how_i_ship;   -- every project, end to end</text>

  <!-- boxes -->
  <g>
    <rect x="28"  y="56" width="138" height="62" rx="8" fill="#161B22" stroke="#3FB950"/>
    <text x="97"  y="82" text-anchor="middle" class="tbl">raw_data</text>
    <text x="97"  y="102" text-anchor="middle" class="sub">csv · api · files</text>

    <rect x="190" y="56" width="138" height="62" rx="8" fill="#161B22" stroke="#3FB950"/>
    <text x="259" y="82" text-anchor="middle" class="tbl">azure_blob</text>
    <text x="259" y="102" text-anchor="middle" class="sub">landing zone</text>

    <rect x="352" y="56" width="138" height="62" rx="8" fill="#161B22" stroke="#3FB950"/>
    <text x="421" y="82" text-anchor="middle" class="tbl">data_factory</text>
    <text x="421" y="102" text-anchor="middle" class="sub">ETL pipelines</text>

    <rect x="514" y="56" width="138" height="62" rx="8" fill="#161B22" stroke="#3FB950"/>
    <text x="583" y="82" text-anchor="middle" class="tbl">postgresql</text>
    <text x="583" y="102" text-anchor="middle" class="sub">star schema</text>

    <rect x="676" y="56" width="150" height="62" rx="8" fill="#161B22" stroke="#3FB950"/>
    <text x="751" y="82" text-anchor="middle" class="tbl">power_bi + ml</text>
    <text x="751" y="102" text-anchor="middle" class="sub">DAX · scikit-learn</text>

    <rect x="850" y="56" width="122" height="62" rx="8" fill="#161B22" stroke="#E0B341"/>
    <text x="911" y="82" text-anchor="middle" class="tbl" fill="#E0B341">decisions</text>
    <text x="911" y="102" text-anchor="middle" class="sub">one headline</text>
  </g>

  <!-- animated flow arrows -->
  <line x1="166" y1="87" x2="190" y2="87" class="flow"/>
  <line x1="328" y1="87" x2="352" y2="87" class="flow"/>
  <line x1="490" y1="87" x2="514" y2="87" class="flow"/>
  <line x1="652" y1="87" x2="676" y2="87" class="flow"/>
  <line x1="826" y1="87" x2="850" y2="87" class="flow"/>

  <text x="24" y="152" class="sub">Execution time: shipped. Rows affected: every stakeholder in the room.</text>
</svg>
