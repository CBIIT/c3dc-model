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
<svg width="1191pt" height="918pt"
 viewBox="0.00 0.00 1191.00 918.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 914)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-914 1187,-914 1187,4 -4,4"/>
<!-- study -->
<g id="node1" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M430,-.5C430,-.5 649,-.5 649,-.5 655,-.5 661,-6.5 661,-12.5 661,-12.5 661,-218.5 661,-218.5 661,-224.5 655,-230.5 649,-230.5 649,-230.5 430,-230.5 430,-230.5 424,-230.5 418,-224.5 418,-218.5 418,-218.5 418,-12.5 418,-12.5 418,-6.5 424,-.5 430,-.5"/>
<text text-anchor="middle" x="446" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="474,-.5 474,-230.5 "/>
<text text-anchor="middle" x="484.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="495,-.5 495,-230.5 "/>
<text text-anchor="middle" x="567.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="495,-207.5 640,-207.5 "/>
<text text-anchor="middle" x="567.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="495,-184.5 640,-184.5 "/>
<text text-anchor="middle" x="567.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="495,-161.5 640,-161.5 "/>
<text text-anchor="middle" x="567.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="495,-138.5 640,-138.5 "/>
<text text-anchor="middle" x="567.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="495,-115.5 640,-115.5 "/>
<text text-anchor="middle" x="567.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="495,-92.5 640,-92.5 "/>
<text text-anchor="middle" x="567.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="495,-69.5 640,-69.5 "/>
<text text-anchor="middle" x="567.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="495,-46.5 640,-46.5 "/>
<text text-anchor="middle" x="567.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="495,-23.5 640,-23.5 "/>
<text text-anchor="middle" x="567.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="640,-.5 640,-230.5 "/>
<text text-anchor="middle" x="650.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival -->
<g id="node2" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M403,-656.5C403,-656.5 764,-656.5 764,-656.5 770,-656.5 776,-662.5 776,-668.5 776,-668.5 776,-782.5 776,-782.5 776,-788.5 770,-794.5 764,-794.5 764,-794.5 403,-794.5 403,-794.5 397,-794.5 391,-788.5 391,-782.5 391,-782.5 391,-668.5 391,-668.5 391,-662.5 397,-656.5 403,-656.5"/>
<text text-anchor="middle" x="428" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="465,-656.5 465,-794.5 "/>
<text text-anchor="middle" x="475.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="486,-656.5 486,-794.5 "/>
<text text-anchor="middle" x="620.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="486,-771.5 755,-771.5 "/>
<text text-anchor="middle" x="620.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="486,-748.5 755,-748.5 "/>
<text text-anchor="middle" x="620.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="486,-725.5 755,-725.5 "/>
<text text-anchor="middle" x="620.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="486,-702.5 755,-702.5 "/>
<text text-anchor="middle" x="620.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="486,-679.5 755,-679.5 "/>
<text text-anchor="middle" x="620.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="755,-656.5 755,-794.5 "/>
<text text-anchor="middle" x="765.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node4" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M424,-340C424,-340 655,-340 655,-340 661,-340 667,-346 667,-352 667,-352 667,-420 667,-420 667,-426 661,-432 655,-432 655,-432 424,-432 424,-432 418,-432 412,-426 412,-420 412,-420 412,-352 412,-352 412,-346 418,-340 424,-340"/>
<text text-anchor="middle" x="460" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="508,-340 508,-432 "/>
<text text-anchor="middle" x="518.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="529,-340 529,-432 "/>
<text text-anchor="middle" x="587.5" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="529,-409 646,-409 "/>
<text text-anchor="middle" x="587.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="529,-386 646,-386 "/>
<text text-anchor="middle" x="587.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="529,-363 646,-363 "/>
<text text-anchor="middle" x="587.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="646,-340 646,-432 "/>
<text text-anchor="middle" x="656.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M574.5429,-656.3879C566.3651,-593.289 554.4243,-501.1547 546.8089,-442.3944"/>
<polygon fill="#000000" stroke="#000000" points="550.242,-441.6519 545.4857,-432.1847 543.3,-442.5517 550.242,-441.6519"/>
<text text-anchor="middle" x="596" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- sample -->
<g id="node3" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M12,-541.5C12,-541.5 361,-541.5 361,-541.5 367,-541.5 373,-547.5 373,-553.5 373,-553.5 373,-897.5 373,-897.5 373,-903.5 367,-909.5 361,-909.5 361,-909.5 12,-909.5 12,-909.5 6,-909.5 0,-903.5 0,-897.5 0,-897.5 0,-553.5 0,-553.5 0,-547.5 6,-541.5 12,-541.5"/>
<text text-anchor="middle" x="34" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="68,-541.5 68,-909.5 "/>
<text text-anchor="middle" x="78.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="89,-541.5 89,-909.5 "/>
<text text-anchor="middle" x="220.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="89,-886.5 352,-886.5 "/>
<text text-anchor="middle" x="220.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="89,-863.5 352,-863.5 "/>
<text text-anchor="middle" x="220.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification</text>
<polyline fill="none" stroke="#000000" points="89,-840.5 352,-840.5 "/>
<text text-anchor="middle" x="220.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="89,-817.5 352,-817.5 "/>
<text text-anchor="middle" x="220.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="89,-794.5 352,-794.5 "/>
<text text-anchor="middle" x="220.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_verification_status</text>
<polyline fill="none" stroke="#000000" points="89,-771.5 352,-771.5 "/>
<text text-anchor="middle" x="220.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="89,-748.5 352,-748.5 "/>
<text text-anchor="middle" x="220.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="89,-725.5 352,-725.5 "/>
<text text-anchor="middle" x="220.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="89,-702.5 352,-702.5 "/>
<text text-anchor="middle" x="220.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="89,-679.5 352,-679.5 "/>
<text text-anchor="middle" x="220.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="89,-656.5 352,-656.5 "/>
<text text-anchor="middle" x="220.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="89,-633.5 352,-633.5 "/>
<text text-anchor="middle" x="220.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="89,-610.5 352,-610.5 "/>
<text text-anchor="middle" x="220.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="89,-587.5 352,-587.5 "/>
<text text-anchor="middle" x="220.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="89,-564.5 352,-564.5 "/>
<text text-anchor="middle" x="220.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="352,-541.5 352,-909.5 "/>
<text text-anchor="middle" x="362.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M220.1954,-541.309C241.8098,-456.9918 276.1502,-358.9583 329.5,-282 351.0957,-250.8478 380.2143,-222.6607 409.8806,-198.7065"/>
<polygon fill="#000000" stroke="#000000" points="412.1854,-201.3457 417.8418,-192.3871 407.8334,-195.863 412.1854,-201.3457"/>
<text text-anchor="middle" x="366" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M373.0784,-546.0571C413.6763,-507.0117 453.5609,-468.6524 484.1029,-439.2786"/>
<polygon fill="#000000" stroke="#000000" points="486.8798,-441.4638 491.6612,-432.0093 482.0275,-436.4185 486.8798,-441.4638"/>
<text text-anchor="middle" x="442" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge5" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M539.5,-339.8067C539.5,-312.4079 539.5,-276.2314 539.5,-240.9491"/>
<polygon fill="#000000" stroke="#000000" points="543.0001,-240.5361 539.5,-230.5362 536.0001,-240.5362 543.0001,-240.5361"/>
<text text-anchor="middle" x="590" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- reference_file -->
<g id="node5" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M697,-282.5C697,-282.5 974,-282.5 974,-282.5 980,-282.5 986,-288.5 986,-294.5 986,-294.5 986,-477.5 986,-477.5 986,-483.5 980,-489.5 974,-489.5 974,-489.5 697,-489.5 697,-489.5 691,-489.5 685,-483.5 685,-477.5 685,-477.5 685,-294.5 685,-294.5 685,-288.5 691,-282.5 697,-282.5"/>
<text text-anchor="middle" x="743" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="801,-282.5 801,-489.5 "/>
<text text-anchor="middle" x="811.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="822,-282.5 822,-489.5 "/>
<text text-anchor="middle" x="893.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="822,-466.5 965,-466.5 "/>
<text text-anchor="middle" x="893.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="822,-443.5 965,-443.5 "/>
<text text-anchor="middle" x="893.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="822,-420.5 965,-420.5 "/>
<text text-anchor="middle" x="893.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="822,-397.5 965,-397.5 "/>
<text text-anchor="middle" x="893.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="822,-374.5 965,-374.5 "/>
<text text-anchor="middle" x="893.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="822,-351.5 965,-351.5 "/>
<text text-anchor="middle" x="893.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="822,-328.5 965,-328.5 "/>
<text text-anchor="middle" x="893.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="822,-305.5 965,-305.5 "/>
<text text-anchor="middle" x="893.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="965,-282.5 965,-489.5 "/>
<text text-anchor="middle" x="975.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge6" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M721.9052,-282.1912C704.5013,-266.2867 686.4254,-249.768 668.7143,-233.5827"/>
<polygon fill="#000000" stroke="#000000" points="670.8922,-230.8316 661.1492,-226.6693 666.17,-235.9989 670.8922,-230.8316"/>
<text text-anchor="middle" x="756" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- diagnosis -->
<g id="node6" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M806,-553C806,-553 1171,-553 1171,-553 1177,-553 1183,-559 1183,-565 1183,-565 1183,-886 1183,-886 1183,-892 1177,-898 1171,-898 1171,-898 806,-898 806,-898 800,-898 794,-892 794,-886 794,-886 794,-565 794,-565 794,-559 800,-553 806,-553"/>
<text text-anchor="middle" x="836" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="878,-553 878,-898 "/>
<text text-anchor="middle" x="888.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="899,-553 899,-898 "/>
<text text-anchor="middle" x="1030.5" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="899,-875 1162,-875 "/>
<text text-anchor="middle" x="1030.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="899,-852 1162,-852 "/>
<text text-anchor="middle" x="1030.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="899,-829 1162,-829 "/>
<text text-anchor="middle" x="1030.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification</text>
<polyline fill="none" stroke="#000000" points="899,-806 1162,-806 "/>
<text text-anchor="middle" x="1030.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="899,-783 1162,-783 "/>
<text text-anchor="middle" x="1030.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="899,-760 1162,-760 "/>
<text text-anchor="middle" x="1030.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="899,-737 1162,-737 "/>
<text text-anchor="middle" x="1030.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_verification_status</text>
<polyline fill="none" stroke="#000000" points="899,-714 1162,-714 "/>
<text text-anchor="middle" x="1030.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="899,-691 1162,-691 "/>
<text text-anchor="middle" x="1030.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="899,-668 1162,-668 "/>
<text text-anchor="middle" x="1030.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="899,-645 1162,-645 "/>
<text text-anchor="middle" x="1030.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="899,-622 1162,-622 "/>
<text text-anchor="middle" x="1030.5" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="899,-599 1162,-599 "/>
<text text-anchor="middle" x="1030.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="899,-576 1162,-576 "/>
<text text-anchor="middle" x="1030.5" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1162,-553 1162,-898 "/>
<text text-anchor="middle" x="1172.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M802.7412,-552.9032C797.0069,-548.7963 791.2537,-544.8185 785.5,-541 740.6003,-511.2021 721.6231,-517.8669 675.5,-490 650.4629,-474.8729 624.5768,-456.0067 602.1947,-438.5117"/>
<polygon fill="#000000" stroke="#000000" points="604.1341,-435.5837 594.1153,-432.1377 599.7984,-441.0793 604.1341,-435.5837"/>
<text text-anchor="middle" x="797" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
</g>
</svg>
</div>
