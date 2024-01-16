<link rel='stylesheet' href="assets/style.css">
<link rel='stylesheet' href="https://unpkg.com/leaflet@1.5.1/dist/leaflet.css" integrity="sha512-xwE/Az9zrjBIphAcBb3F6JVqxf46+CDLwfLMHloNu6KEQCAWi6HcDUbeOfBIptF7tcCzusKFjFw2yuvEpDL9wQ==" crossorigin="">
<script type="text/javascript" src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script type="text/javascript"  src="https://unpkg.com/leaflet@1.5.1/dist/leaflet.js"></script>
<script type="text/javascript" src="assets/actions.js"></script>

![Build Status](https://github.com/CBIIT/c3d-model/actions/workflows/model-test-and-deploy.yml/badge.svg)

# Childhood Cancer Clinical Data Model

[View model on GitHub Pages](https://cbiit.github.io/c3d-model/)


Zoom to Node: <select id="node_select">
  <option value="">Zoom to Node</option>
</select>
<div id="model"></div>

<p>
<a href="./model-desc/c3d-model.svg">SVG file (in view above)</a>
<p>
<a href="./model-desc">Additional model files</a>
<div id='graph' style='display:off;'>
<svg width="1329pt" height="1033pt"
 viewBox="0.00 0.00 1329.00 1033.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1029)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1029 1325,-1029 1325,4 -4,4"/>
<!-- participant -->
<g id="node1" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M499.5,-351.5C499.5,-351.5 803.5,-351.5 803.5,-351.5 809.5,-351.5 815.5,-357.5 815.5,-363.5 815.5,-363.5 815.5,-454.5 815.5,-454.5 815.5,-460.5 809.5,-466.5 803.5,-466.5 803.5,-466.5 499.5,-466.5 499.5,-466.5 493.5,-466.5 487.5,-460.5 487.5,-454.5 487.5,-454.5 487.5,-363.5 487.5,-363.5 487.5,-357.5 493.5,-351.5 499.5,-351.5"/>
<text text-anchor="middle" x="535.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="583.5,-351.5 583.5,-466.5 "/>
<text text-anchor="middle" x="594" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="604.5,-351.5 604.5,-466.5 "/>
<text text-anchor="middle" x="699.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="604.5,-443.5 794.5,-443.5 "/>
<text text-anchor="middle" x="699.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="604.5,-420.5 794.5,-420.5 "/>
<text text-anchor="middle" x="699.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="604.5,-397.5 794.5,-397.5 "/>
<text text-anchor="middle" x="699.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="604.5,-374.5 794.5,-374.5 "/>
<text text-anchor="middle" x="699.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="794.5,-351.5 794.5,-466.5 "/>
<text text-anchor="middle" x="805" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node4" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M251,-.5C251,-.5 470,-.5 470,-.5 476,-.5 482,-6.5 482,-12.5 482,-12.5 482,-218.5 482,-218.5 482,-224.5 476,-230.5 470,-230.5 470,-230.5 251,-230.5 251,-230.5 245,-230.5 239,-224.5 239,-218.5 239,-218.5 239,-12.5 239,-12.5 239,-6.5 245,-.5 251,-.5"/>
<text text-anchor="middle" x="267" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="295,-.5 295,-230.5 "/>
<text text-anchor="middle" x="305.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="316,-.5 316,-230.5 "/>
<text text-anchor="middle" x="388.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="316,-207.5 461,-207.5 "/>
<text text-anchor="middle" x="388.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="316,-184.5 461,-184.5 "/>
<text text-anchor="middle" x="388.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="316,-161.5 461,-161.5 "/>
<text text-anchor="middle" x="388.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="316,-138.5 461,-138.5 "/>
<text text-anchor="middle" x="388.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="316,-115.5 461,-115.5 "/>
<text text-anchor="middle" x="388.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="316,-92.5 461,-92.5 "/>
<text text-anchor="middle" x="388.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="316,-69.5 461,-69.5 "/>
<text text-anchor="middle" x="388.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="316,-46.5 461,-46.5 "/>
<text text-anchor="middle" x="388.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="316,-23.5 461,-23.5 "/>
<text text-anchor="middle" x="388.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="461,-.5 461,-230.5 "/>
<text text-anchor="middle" x="471.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge5" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M594.355,-351.364C562.2555,-318.9888 520.9223,-277.3005 481.9556,-237.999"/>
<polygon fill="#000000" stroke="#000000" points="484.2362,-235.3281 474.7099,-230.6911 479.2653,-240.2567 484.2362,-235.3281"/>
<text text-anchor="middle" x="557" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- diagnosis -->
<g id="node2" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M541,-633.5C541,-633.5 906,-633.5 906,-633.5 912,-633.5 918,-639.5 918,-645.5 918,-645.5 918,-966.5 918,-966.5 918,-972.5 912,-978.5 906,-978.5 906,-978.5 541,-978.5 541,-978.5 535,-978.5 529,-972.5 529,-966.5 529,-966.5 529,-645.5 529,-645.5 529,-639.5 535,-633.5 541,-633.5"/>
<text text-anchor="middle" x="571" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="613,-633.5 613,-978.5 "/>
<text text-anchor="middle" x="623.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="634,-633.5 634,-978.5 "/>
<text text-anchor="middle" x="765.5" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="634,-955.5 897,-955.5 "/>
<text text-anchor="middle" x="765.5" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="634,-932.5 897,-932.5 "/>
<text text-anchor="middle" x="765.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="634,-909.5 897,-909.5 "/>
<text text-anchor="middle" x="765.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification</text>
<polyline fill="none" stroke="#000000" points="634,-886.5 897,-886.5 "/>
<text text-anchor="middle" x="765.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="634,-863.5 897,-863.5 "/>
<text text-anchor="middle" x="765.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="634,-840.5 897,-840.5 "/>
<text text-anchor="middle" x="765.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="634,-817.5 897,-817.5 "/>
<text text-anchor="middle" x="765.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_verification_status</text>
<polyline fill="none" stroke="#000000" points="634,-794.5 897,-794.5 "/>
<text text-anchor="middle" x="765.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="634,-771.5 897,-771.5 "/>
<text text-anchor="middle" x="765.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="634,-748.5 897,-748.5 "/>
<text text-anchor="middle" x="765.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="634,-725.5 897,-725.5 "/>
<text text-anchor="middle" x="765.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="634,-702.5 897,-702.5 "/>
<text text-anchor="middle" x="765.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="634,-679.5 897,-679.5 "/>
<text text-anchor="middle" x="765.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="634,-656.5 897,-656.5 "/>
<text text-anchor="middle" x="765.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="897,-633.5 897,-978.5 "/>
<text text-anchor="middle" x="907.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M692.1815,-633.3135C682.1405,-577.9483 671.6052,-519.8577 663.7721,-476.6668"/>
<polygon fill="#000000" stroke="#000000" points="667.1703,-475.7904 661.9419,-466.5755 660.2827,-477.0396 667.1703,-475.7904"/>
<text text-anchor="middle" x="724" y="-557.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- reference_file -->
<g id="node3" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M12,-282.5C12,-282.5 313,-282.5 313,-282.5 319,-282.5 325,-288.5 325,-294.5 325,-294.5 325,-523.5 325,-523.5 325,-529.5 319,-535.5 313,-535.5 313,-535.5 12,-535.5 12,-535.5 6,-535.5 0,-529.5 0,-523.5 0,-523.5 0,-294.5 0,-294.5 0,-288.5 6,-282.5 12,-282.5"/>
<text text-anchor="middle" x="58" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="116,-282.5 116,-535.5 "/>
<text text-anchor="middle" x="126.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="137,-282.5 137,-535.5 "/>
<text text-anchor="middle" x="220.5" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="137,-512.5 304,-512.5 "/>
<text text-anchor="middle" x="220.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="137,-489.5 304,-489.5 "/>
<text text-anchor="middle" x="220.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="137,-466.5 304,-466.5 "/>
<text text-anchor="middle" x="220.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="137,-443.5 304,-443.5 "/>
<text text-anchor="middle" x="220.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="137,-420.5 304,-420.5 "/>
<text text-anchor="middle" x="220.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="137,-397.5 304,-397.5 "/>
<text text-anchor="middle" x="220.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="137,-374.5 304,-374.5 "/>
<text text-anchor="middle" x="220.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="137,-351.5 304,-351.5 "/>
<text text-anchor="middle" x="220.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="137,-328.5 304,-328.5 "/>
<text text-anchor="middle" x="220.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="137,-305.5 304,-305.5 "/>
<text text-anchor="middle" x="220.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="304,-282.5 304,-535.5 "/>
<text text-anchor="middle" x="314.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge4" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M206.4973,-282.4496C212.2628,-270.8062 218.5967,-259.467 225.5,-249 227.8479,-245.4401 230.3032,-241.899 232.8492,-238.384"/>
<polygon fill="#000000" stroke="#000000" points="235.7592,-240.337 238.9464,-230.2329 230.1538,-236.1441 235.7592,-240.337"/>
<text text-anchor="middle" x="286" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- survival -->
<g id="node5" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M948,-737C948,-737 1309,-737 1309,-737 1315,-737 1321,-743 1321,-749 1321,-749 1321,-863 1321,-863 1321,-869 1315,-875 1309,-875 1309,-875 948,-875 948,-875 942,-875 936,-869 936,-863 936,-863 936,-749 936,-749 936,-743 942,-737 948,-737"/>
<text text-anchor="middle" x="973" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="1010,-737 1010,-875 "/>
<text text-anchor="middle" x="1020.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1031,-737 1031,-875 "/>
<text text-anchor="middle" x="1165.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="1031,-852 1300,-852 "/>
<text text-anchor="middle" x="1165.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="1031,-829 1300,-829 "/>
<text text-anchor="middle" x="1165.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="1031,-806 1300,-806 "/>
<text text-anchor="middle" x="1165.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="1031,-783 1300,-783 "/>
<text text-anchor="middle" x="1165.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="1031,-760 1300,-760 "/>
<text text-anchor="middle" x="1165.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="1300,-737 1300,-875 "/>
<text text-anchor="middle" x="1310.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1072.7797,-736.5752C1034.5317,-691.2225 981.1578,-632.2426 927.5,-587 876.7112,-544.1764 814.9816,-503.4618 762.7909,-471.8071"/>
<polygon fill="#000000" stroke="#000000" points="764.5375,-468.7733 754.1667,-466.6059 760.9224,-474.7675 764.5375,-468.7733"/>
<text text-anchor="middle" x="939" y="-557.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- sample -->
<g id="node6" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M148,-587.5C148,-587.5 499,-587.5 499,-587.5 505,-587.5 511,-593.5 511,-599.5 511,-599.5 511,-1012.5 511,-1012.5 511,-1018.5 505,-1024.5 499,-1024.5 499,-1024.5 148,-1024.5 148,-1024.5 142,-1024.5 136,-1018.5 136,-1012.5 136,-1012.5 136,-599.5 136,-599.5 136,-593.5 142,-587.5 148,-587.5"/>
<text text-anchor="middle" x="170" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="204,-587.5 204,-1024.5 "/>
<text text-anchor="middle" x="214.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="225,-587.5 225,-1024.5 "/>
<text text-anchor="middle" x="357.5" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="225,-1001.5 490,-1001.5 "/>
<text text-anchor="middle" x="357.5" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="225,-978.5 490,-978.5 "/>
<text text-anchor="middle" x="357.5" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="225,-955.5 490,-955.5 "/>
<text text-anchor="middle" x="357.5" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="225,-932.5 490,-932.5 "/>
<text text-anchor="middle" x="357.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification</text>
<polyline fill="none" stroke="#000000" points="225,-909.5 490,-909.5 "/>
<text text-anchor="middle" x="357.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="225,-886.5 490,-886.5 "/>
<text text-anchor="middle" x="357.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="225,-863.5 490,-863.5 "/>
<text text-anchor="middle" x="357.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_verification_status</text>
<polyline fill="none" stroke="#000000" points="225,-840.5 490,-840.5 "/>
<text text-anchor="middle" x="357.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="225,-817.5 490,-817.5 "/>
<text text-anchor="middle" x="357.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="225,-794.5 490,-794.5 "/>
<text text-anchor="middle" x="357.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="225,-771.5 490,-771.5 "/>
<text text-anchor="middle" x="357.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="225,-748.5 490,-748.5 "/>
<text text-anchor="middle" x="357.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="225,-725.5 490,-725.5 "/>
<text text-anchor="middle" x="357.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="225,-702.5 490,-702.5 "/>
<text text-anchor="middle" x="357.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="225,-679.5 490,-679.5 "/>
<text text-anchor="middle" x="357.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="225,-656.5 490,-656.5 "/>
<text text-anchor="middle" x="357.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="225,-633.5 490,-633.5 "/>
<text text-anchor="middle" x="357.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="225,-610.5 490,-610.5 "/>
<text text-anchor="middle" x="357.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="490,-587.5 490,-1024.5 "/>
<text text-anchor="middle" x="500.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M504.0511,-587.4671C538.0445,-546.3227 571.0796,-506.3381 597.2343,-474.6813"/>
<polygon fill="#000000" stroke="#000000" points="600.0608,-476.7553 603.732,-466.8168 594.6644,-472.2967 600.0608,-476.7553"/>
<text text-anchor="middle" x="564" y="-557.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M335.2324,-587.0472C341.355,-472.7872 348.6246,-337.1213 353.7909,-240.7072"/>
<polygon fill="#000000" stroke="#000000" points="357.2911,-240.7943 354.3313,-230.6213 350.3011,-240.4197 357.2911,-240.7943"/>
<text text-anchor="middle" x="388" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
</g>
</svg>
</div>
