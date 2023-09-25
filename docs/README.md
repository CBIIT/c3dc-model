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
<svg width="958pt" height="987pt"
 viewBox="0.00 0.00 958.00 987.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 983)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-983 954,-983 954,4 -4,4"/>
<!-- sample -->
<g id="node1" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M12,-587.5C12,-587.5 363,-587.5 363,-587.5 369,-587.5 375,-593.5 375,-599.5 375,-599.5 375,-966.5 375,-966.5 375,-972.5 369,-978.5 363,-978.5 363,-978.5 12,-978.5 12,-978.5 6,-978.5 0,-972.5 0,-966.5 0,-966.5 0,-599.5 0,-599.5 0,-593.5 6,-587.5 12,-587.5"/>
<text text-anchor="middle" x="34" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="68,-587.5 68,-978.5 "/>
<text text-anchor="middle" x="78.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="89,-587.5 89,-978.5 "/>
<text text-anchor="middle" x="221.5" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="89,-955.5 354,-955.5 "/>
<text text-anchor="middle" x="221.5" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="89,-932.5 354,-932.5 "/>
<text text-anchor="middle" x="221.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="89,-909.5 354,-909.5 "/>
<text text-anchor="middle" x="221.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="89,-886.5 354,-886.5 "/>
<text text-anchor="middle" x="221.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="89,-863.5 354,-863.5 "/>
<text text-anchor="middle" x="221.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="89,-840.5 354,-840.5 "/>
<text text-anchor="middle" x="221.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="89,-817.5 354,-817.5 "/>
<text text-anchor="middle" x="221.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="89,-794.5 354,-794.5 "/>
<text text-anchor="middle" x="221.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="89,-771.5 354,-771.5 "/>
<text text-anchor="middle" x="221.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="89,-748.5 354,-748.5 "/>
<text text-anchor="middle" x="221.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="89,-725.5 354,-725.5 "/>
<text text-anchor="middle" x="221.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="89,-702.5 354,-702.5 "/>
<text text-anchor="middle" x="221.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="89,-679.5 354,-679.5 "/>
<text text-anchor="middle" x="221.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="89,-656.5 354,-656.5 "/>
<text text-anchor="middle" x="221.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="89,-633.5 354,-633.5 "/>
<text text-anchor="middle" x="221.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="89,-610.5 354,-610.5 "/>
<text text-anchor="middle" x="221.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="354,-587.5 354,-978.5 "/>
<text text-anchor="middle" x="364.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node2" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M333,-.5C333,-.5 552,-.5 552,-.5 558,-.5 564,-6.5 564,-12.5 564,-12.5 564,-218.5 564,-218.5 564,-224.5 558,-230.5 552,-230.5 552,-230.5 333,-230.5 333,-230.5 327,-230.5 321,-224.5 321,-218.5 321,-218.5 321,-12.5 321,-12.5 321,-6.5 327,-.5 333,-.5"/>
<text text-anchor="middle" x="349" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="377,-.5 377,-230.5 "/>
<text text-anchor="middle" x="387.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="398,-.5 398,-230.5 "/>
<text text-anchor="middle" x="470.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="398,-207.5 543,-207.5 "/>
<text text-anchor="middle" x="470.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="398,-184.5 543,-184.5 "/>
<text text-anchor="middle" x="470.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="398,-161.5 543,-161.5 "/>
<text text-anchor="middle" x="470.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="398,-138.5 543,-138.5 "/>
<text text-anchor="middle" x="470.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="398,-115.5 543,-115.5 "/>
<text text-anchor="middle" x="470.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="398,-92.5 543,-92.5 "/>
<text text-anchor="middle" x="470.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="398,-69.5 543,-69.5 "/>
<text text-anchor="middle" x="470.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="398,-46.5 543,-46.5 "/>
<text text-anchor="middle" x="470.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="398,-23.5 543,-23.5 "/>
<text text-anchor="middle" x="470.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="543,-.5 543,-230.5 "/>
<text text-anchor="middle" x="553.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M150.3433,-587.3516C141.6296,-490.0695 146.6346,-373.9595 196.5,-282 221.9664,-235.0359 267.1053,-198.8164 311.8249,-172.336"/>
<polygon fill="#000000" stroke="#000000" points="313.8534,-175.206 320.7573,-167.1694 310.3486,-169.1466 313.8534,-175.206"/>
<text text-anchor="middle" x="233" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant -->
<g id="node4" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M290.5,-351.5C290.5,-351.5 594.5,-351.5 594.5,-351.5 600.5,-351.5 606.5,-357.5 606.5,-363.5 606.5,-363.5 606.5,-454.5 606.5,-454.5 606.5,-460.5 600.5,-466.5 594.5,-466.5 594.5,-466.5 290.5,-466.5 290.5,-466.5 284.5,-466.5 278.5,-460.5 278.5,-454.5 278.5,-454.5 278.5,-363.5 278.5,-363.5 278.5,-357.5 284.5,-351.5 290.5,-351.5"/>
<text text-anchor="middle" x="326.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="374.5,-351.5 374.5,-466.5 "/>
<text text-anchor="middle" x="385" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="395.5,-351.5 395.5,-466.5 "/>
<text text-anchor="middle" x="490.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="395.5,-443.5 585.5,-443.5 "/>
<text text-anchor="middle" x="490.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="395.5,-420.5 585.5,-420.5 "/>
<text text-anchor="middle" x="490.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="395.5,-397.5 585.5,-397.5 "/>
<text text-anchor="middle" x="490.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="395.5,-374.5 585.5,-374.5 "/>
<text text-anchor="middle" x="490.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="585.5,-351.5 585.5,-466.5 "/>
<text text-anchor="middle" x="596" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M320.9746,-587.2372C348.6291,-546.6773 375.908,-506.6683 397.5919,-474.8652"/>
<polygon fill="#000000" stroke="#000000" points="400.5257,-476.7752 403.2673,-466.5412 394.7421,-472.8318 400.5257,-476.7752"/>
<text text-anchor="middle" x="375" y="-557.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- diagnosis -->
<g id="node3" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M405,-610.5C405,-610.5 772,-610.5 772,-610.5 778,-610.5 784,-616.5 784,-622.5 784,-622.5 784,-943.5 784,-943.5 784,-949.5 778,-955.5 772,-955.5 772,-955.5 405,-955.5 405,-955.5 399,-955.5 393,-949.5 393,-943.5 393,-943.5 393,-622.5 393,-622.5 393,-616.5 399,-610.5 405,-610.5"/>
<text text-anchor="middle" x="435" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="477,-610.5 477,-955.5 "/>
<text text-anchor="middle" x="487.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="498,-610.5 498,-955.5 "/>
<text text-anchor="middle" x="630.5" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="498,-932.5 763,-932.5 "/>
<text text-anchor="middle" x="630.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="498,-909.5 763,-909.5 "/>
<text text-anchor="middle" x="630.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_recurrence</text>
<polyline fill="none" stroke="#000000" points="498,-886.5 763,-886.5 "/>
<text text-anchor="middle" x="630.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="498,-863.5 763,-863.5 "/>
<text text-anchor="middle" x="630.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="498,-840.5 763,-840.5 "/>
<text text-anchor="middle" x="630.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="498,-817.5 763,-817.5 "/>
<text text-anchor="middle" x="630.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="498,-794.5 763,-794.5 "/>
<text text-anchor="middle" x="630.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="498,-771.5 763,-771.5 "/>
<text text-anchor="middle" x="630.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="498,-748.5 763,-748.5 "/>
<text text-anchor="middle" x="630.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="498,-725.5 763,-725.5 "/>
<text text-anchor="middle" x="630.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="498,-702.5 763,-702.5 "/>
<text text-anchor="middle" x="630.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="498,-679.5 763,-679.5 "/>
<text text-anchor="middle" x="630.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="498,-656.5 763,-656.5 "/>
<text text-anchor="middle" x="630.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="498,-633.5 763,-633.5 "/>
<text text-anchor="middle" x="630.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="763,-610.5 763,-955.5 "/>
<text text-anchor="middle" x="773.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M521.0558,-610.2319C502.4585,-562.5923 483.3775,-513.7136 468.6784,-476.0597"/>
<polygon fill="#000000" stroke="#000000" points="471.9356,-474.7786 465.0387,-466.7361 465.4148,-477.3242 471.9356,-474.7786"/>
<text text-anchor="middle" x="547" y="-557.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge2" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M442.5,-351.364C442.5,-319.7948 442.5,-279.3705 442.5,-240.9387"/>
<polygon fill="#000000" stroke="#000000" points="446.0001,-240.6911 442.5,-230.6911 439.0001,-240.6912 446.0001,-240.6911"/>
<text text-anchor="middle" x="493" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- reference_file -->
<g id="node5" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M637,-282.5C637,-282.5 938,-282.5 938,-282.5 944,-282.5 950,-288.5 950,-294.5 950,-294.5 950,-523.5 950,-523.5 950,-529.5 944,-535.5 938,-535.5 938,-535.5 637,-535.5 637,-535.5 631,-535.5 625,-529.5 625,-523.5 625,-523.5 625,-294.5 625,-294.5 625,-288.5 631,-282.5 637,-282.5"/>
<text text-anchor="middle" x="683" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="741,-282.5 741,-535.5 "/>
<text text-anchor="middle" x="751.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="762,-282.5 762,-535.5 "/>
<text text-anchor="middle" x="845.5" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="762,-512.5 929,-512.5 "/>
<text text-anchor="middle" x="845.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="762,-489.5 929,-489.5 "/>
<text text-anchor="middle" x="845.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="762,-466.5 929,-466.5 "/>
<text text-anchor="middle" x="845.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="762,-443.5 929,-443.5 "/>
<text text-anchor="middle" x="845.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="762,-420.5 929,-420.5 "/>
<text text-anchor="middle" x="845.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="762,-397.5 929,-397.5 "/>
<text text-anchor="middle" x="845.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="762,-374.5 929,-374.5 "/>
<text text-anchor="middle" x="845.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="762,-351.5 929,-351.5 "/>
<text text-anchor="middle" x="845.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="762,-328.5 929,-328.5 "/>
<text text-anchor="middle" x="845.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="762,-305.5 929,-305.5 "/>
<text text-anchor="middle" x="845.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="929,-282.5 929,-535.5 "/>
<text text-anchor="middle" x="939.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge3" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M638.6857,-282.4C616.4176,-263.456 593.6127,-244.0553 571.7935,-225.4932"/>
<polygon fill="#000000" stroke="#000000" points="574.004,-222.7785 564.1194,-218.9646 569.4682,-228.1102 574.004,-222.7785"/>
<text text-anchor="middle" x="676" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
</g>
</svg>
</div>
