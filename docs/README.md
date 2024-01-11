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
<svg width="1330pt" height="1033pt"
 viewBox="0.00 0.00 1330.00 1033.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1029)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1029 1326,-1029 1326,4 -4,4"/>
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
<g id="edge3" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M594.355,-351.364C562.2555,-318.9888 520.9223,-277.3005 481.9556,-237.999"/>
<polygon fill="#000000" stroke="#000000" points="484.2362,-235.3281 474.7099,-230.6911 479.2653,-240.2567 484.2362,-235.3281"/>
<text text-anchor="middle" x="557" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- survival -->
<g id="node2" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M542,-737C542,-737 903,-737 903,-737 909,-737 915,-743 915,-749 915,-749 915,-863 915,-863 915,-869 909,-875 903,-875 903,-875 542,-875 542,-875 536,-875 530,-869 530,-863 530,-863 530,-749 530,-749 530,-743 536,-737 542,-737"/>
<text text-anchor="middle" x="567" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="604,-737 604,-875 "/>
<text text-anchor="middle" x="614.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="625,-737 625,-875 "/>
<text text-anchor="middle" x="759.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="625,-852 894,-852 "/>
<text text-anchor="middle" x="759.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="625,-829 894,-829 "/>
<text text-anchor="middle" x="759.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="625,-806 894,-806 "/>
<text text-anchor="middle" x="759.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="625,-783 894,-783 "/>
<text text-anchor="middle" x="759.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="625,-760 894,-760 "/>
<text text-anchor="middle" x="759.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="894,-737 894,-875 "/>
<text text-anchor="middle" x="904.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M710.1327,-736.8479C697.0605,-663.7536 676.5759,-549.2132 663.6042,-476.681"/>
<polygon fill="#000000" stroke="#000000" points="667.0311,-475.9615 661.8252,-466.7338 660.1404,-477.1939 667.0311,-475.9615"/>
<text text-anchor="middle" x="719" y="-557.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
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
<g id="edge2" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M206.4973,-282.4496C212.2628,-270.8062 218.5967,-259.467 225.5,-249 227.8479,-245.4401 230.3032,-241.899 232.8492,-238.384"/>
<polygon fill="#000000" stroke="#000000" points="235.7592,-240.337 238.9464,-230.2329 230.1538,-236.1441 235.7592,-240.337"/>
<text text-anchor="middle" x="286" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- sample -->
<g id="node5" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M149,-587.5C149,-587.5 500,-587.5 500,-587.5 506,-587.5 512,-593.5 512,-599.5 512,-599.5 512,-1012.5 512,-1012.5 512,-1018.5 506,-1024.5 500,-1024.5 500,-1024.5 149,-1024.5 149,-1024.5 143,-1024.5 137,-1018.5 137,-1012.5 137,-1012.5 137,-599.5 137,-599.5 137,-593.5 143,-587.5 149,-587.5"/>
<text text-anchor="middle" x="171" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="205,-587.5 205,-1024.5 "/>
<text text-anchor="middle" x="215.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="226,-587.5 226,-1024.5 "/>
<text text-anchor="middle" x="358.5" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="226,-1001.5 491,-1001.5 "/>
<text text-anchor="middle" x="358.5" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="226,-978.5 491,-978.5 "/>
<text text-anchor="middle" x="358.5" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="226,-955.5 491,-955.5 "/>
<text text-anchor="middle" x="358.5" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="226,-932.5 491,-932.5 "/>
<text text-anchor="middle" x="358.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification</text>
<polyline fill="none" stroke="#000000" points="226,-909.5 491,-909.5 "/>
<text text-anchor="middle" x="358.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="226,-886.5 491,-886.5 "/>
<text text-anchor="middle" x="358.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="226,-863.5 491,-863.5 "/>
<text text-anchor="middle" x="358.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_verification_status</text>
<polyline fill="none" stroke="#000000" points="226,-840.5 491,-840.5 "/>
<text text-anchor="middle" x="358.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="226,-817.5 491,-817.5 "/>
<text text-anchor="middle" x="358.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="226,-794.5 491,-794.5 "/>
<text text-anchor="middle" x="358.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="226,-771.5 491,-771.5 "/>
<text text-anchor="middle" x="358.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="226,-748.5 491,-748.5 "/>
<text text-anchor="middle" x="358.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="226,-725.5 491,-725.5 "/>
<text text-anchor="middle" x="358.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="226,-702.5 491,-702.5 "/>
<text text-anchor="middle" x="358.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="226,-679.5 491,-679.5 "/>
<text text-anchor="middle" x="358.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="226,-656.5 491,-656.5 "/>
<text text-anchor="middle" x="358.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="226,-633.5 491,-633.5 "/>
<text text-anchor="middle" x="358.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="226,-610.5 491,-610.5 "/>
<text text-anchor="middle" x="358.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="491,-587.5 491,-1024.5 "/>
<text text-anchor="middle" x="501.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M504.5006,-587.4671C538.3904,-546.3227 571.3248,-506.3381 597.3998,-474.6813"/>
<polygon fill="#000000" stroke="#000000" points="600.2214,-476.7608 603.8776,-466.8168 594.8182,-472.3103 600.2214,-476.7608"/>
<text text-anchor="middle" x="564" y="-557.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M335.9154,-587.0472C341.8724,-472.7872 348.9455,-337.1213 353.9722,-240.7072"/>
<polygon fill="#000000" stroke="#000000" points="357.4725,-240.79 354.498,-230.6213 350.482,-240.4255 357.4725,-240.79"/>
<text text-anchor="middle" x="389" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- diagnosis -->
<g id="node6" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M945,-633.5C945,-633.5 1310,-633.5 1310,-633.5 1316,-633.5 1322,-639.5 1322,-645.5 1322,-645.5 1322,-966.5 1322,-966.5 1322,-972.5 1316,-978.5 1310,-978.5 1310,-978.5 945,-978.5 945,-978.5 939,-978.5 933,-972.5 933,-966.5 933,-966.5 933,-645.5 933,-645.5 933,-639.5 939,-633.5 945,-633.5"/>
<text text-anchor="middle" x="975" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1017,-633.5 1017,-978.5 "/>
<text text-anchor="middle" x="1027.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1038,-633.5 1038,-978.5 "/>
<text text-anchor="middle" x="1169.5" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1038,-955.5 1301,-955.5 "/>
<text text-anchor="middle" x="1169.5" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1038,-932.5 1301,-932.5 "/>
<text text-anchor="middle" x="1169.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="1038,-909.5 1301,-909.5 "/>
<text text-anchor="middle" x="1169.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification</text>
<polyline fill="none" stroke="#000000" points="1038,-886.5 1301,-886.5 "/>
<text text-anchor="middle" x="1169.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="1038,-863.5 1301,-863.5 "/>
<text text-anchor="middle" x="1169.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="1038,-840.5 1301,-840.5 "/>
<text text-anchor="middle" x="1169.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1038,-817.5 1301,-817.5 "/>
<text text-anchor="middle" x="1169.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_verification_status</text>
<polyline fill="none" stroke="#000000" points="1038,-794.5 1301,-794.5 "/>
<text text-anchor="middle" x="1169.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="1038,-771.5 1301,-771.5 "/>
<text text-anchor="middle" x="1169.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="1038,-748.5 1301,-748.5 "/>
<text text-anchor="middle" x="1169.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1038,-725.5 1301,-725.5 "/>
<text text-anchor="middle" x="1169.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1038,-702.5 1301,-702.5 "/>
<text text-anchor="middle" x="1169.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1038,-679.5 1301,-679.5 "/>
<text text-anchor="middle" x="1169.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1038,-656.5 1301,-656.5 "/>
<text text-anchor="middle" x="1169.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1301,-633.5 1301,-978.5 "/>
<text text-anchor="middle" x="1311.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M975.152,-633.3054C958.5868,-617.0919 941.5423,-601.3704 924.5,-587 873.9992,-544.4169 812.7802,-503.6526 761.1228,-471.9049"/>
<polygon fill="#000000" stroke="#000000" points="762.9455,-468.917 752.5879,-466.6878 759.2947,-474.8896 762.9455,-468.917"/>
<text text-anchor="middle" x="941" y="-557.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
</g>
</svg>
</div>
