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
<path fill="none" stroke="#000000" d="M431,-.5C431,-.5 650,-.5 650,-.5 656,-.5 662,-6.5 662,-12.5 662,-12.5 662,-218.5 662,-218.5 662,-224.5 656,-230.5 650,-230.5 650,-230.5 431,-230.5 431,-230.5 425,-230.5 419,-224.5 419,-218.5 419,-218.5 419,-12.5 419,-12.5 419,-6.5 425,-.5 431,-.5"/>
<text text-anchor="middle" x="447" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="475,-.5 475,-230.5 "/>
<text text-anchor="middle" x="485.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="496,-.5 496,-230.5 "/>
<text text-anchor="middle" x="568.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="496,-207.5 641,-207.5 "/>
<text text-anchor="middle" x="568.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="496,-184.5 641,-184.5 "/>
<text text-anchor="middle" x="568.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="496,-161.5 641,-161.5 "/>
<text text-anchor="middle" x="568.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="496,-138.5 641,-138.5 "/>
<text text-anchor="middle" x="568.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="496,-115.5 641,-115.5 "/>
<text text-anchor="middle" x="568.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="496,-92.5 641,-92.5 "/>
<text text-anchor="middle" x="568.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="496,-69.5 641,-69.5 "/>
<text text-anchor="middle" x="568.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="496,-46.5 641,-46.5 "/>
<text text-anchor="middle" x="568.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="496,-23.5 641,-23.5 "/>
<text text-anchor="middle" x="568.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="641,-.5 641,-230.5 "/>
<text text-anchor="middle" x="651.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node2" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M425,-340C425,-340 656,-340 656,-340 662,-340 668,-346 668,-352 668,-352 668,-420 668,-420 668,-426 662,-432 656,-432 656,-432 425,-432 425,-432 419,-432 413,-426 413,-420 413,-420 413,-352 413,-352 413,-346 419,-340 425,-340"/>
<text text-anchor="middle" x="461" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="509,-340 509,-432 "/>
<text text-anchor="middle" x="519.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="530,-340 530,-432 "/>
<text text-anchor="middle" x="588.5" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="530,-409 647,-409 "/>
<text text-anchor="middle" x="588.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="530,-386 647,-386 "/>
<text text-anchor="middle" x="588.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="530,-363 647,-363 "/>
<text text-anchor="middle" x="588.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="647,-340 647,-432 "/>
<text text-anchor="middle" x="657.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge4" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M540.5,-339.8067C540.5,-312.4079 540.5,-276.2314 540.5,-240.9491"/>
<polygon fill="#000000" stroke="#000000" points="544.0001,-240.5361 540.5,-230.5362 537.0001,-240.5362 544.0001,-240.5361"/>
<text text-anchor="middle" x="591" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
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
<g id="edge6" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M220.6644,-541.3057C242.4806,-456.9878 277.0364,-358.9546 330.5,-282 352.1274,-250.8698 381.2577,-222.6908 410.9249,-198.7373"/>
<polygon fill="#000000" stroke="#000000" points="413.2297,-201.3764 418.8861,-192.4178 408.8777,-195.8937 413.2297,-201.3764"/>
<text text-anchor="middle" x="367" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M373.0891,-546.5537C413.8907,-507.4234 454.0107,-468.9466 484.7428,-439.4733"/>
<polygon fill="#000000" stroke="#000000" points="487.5537,-441.627 492.3485,-432.1792 482.7085,-436.5749 487.5537,-441.627"/>
<text text-anchor="middle" x="443" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- reference_file -->
<g id="node4" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M698,-282.5C698,-282.5 975,-282.5 975,-282.5 981,-282.5 987,-288.5 987,-294.5 987,-294.5 987,-477.5 987,-477.5 987,-483.5 981,-489.5 975,-489.5 975,-489.5 698,-489.5 698,-489.5 692,-489.5 686,-483.5 686,-477.5 686,-477.5 686,-294.5 686,-294.5 686,-288.5 692,-282.5 698,-282.5"/>
<text text-anchor="middle" x="744" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="802,-282.5 802,-489.5 "/>
<text text-anchor="middle" x="812.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="823,-282.5 823,-489.5 "/>
<text text-anchor="middle" x="894.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="823,-466.5 966,-466.5 "/>
<text text-anchor="middle" x="894.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="823,-443.5 966,-443.5 "/>
<text text-anchor="middle" x="894.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="823,-420.5 966,-420.5 "/>
<text text-anchor="middle" x="894.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="823,-397.5 966,-397.5 "/>
<text text-anchor="middle" x="894.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="823,-374.5 966,-374.5 "/>
<text text-anchor="middle" x="894.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="823,-351.5 966,-351.5 "/>
<text text-anchor="middle" x="894.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="823,-328.5 966,-328.5 "/>
<text text-anchor="middle" x="894.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="823,-305.5 966,-305.5 "/>
<text text-anchor="middle" x="894.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="966,-282.5 966,-489.5 "/>
<text text-anchor="middle" x="976.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge1" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M722.9052,-282.1912C705.5013,-266.2867 687.4254,-249.768 669.7143,-233.5827"/>
<polygon fill="#000000" stroke="#000000" points="671.8922,-230.8316 662.1492,-226.6693 667.17,-235.9989 671.8922,-230.8316"/>
<text text-anchor="middle" x="757" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- diagnosis -->
<g id="node5" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M403,-553C403,-553 768,-553 768,-553 774,-553 780,-559 780,-565 780,-565 780,-886 780,-886 780,-892 774,-898 768,-898 768,-898 403,-898 403,-898 397,-898 391,-892 391,-886 391,-886 391,-565 391,-565 391,-559 397,-553 403,-553"/>
<text text-anchor="middle" x="433" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="475,-553 475,-898 "/>
<text text-anchor="middle" x="485.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="496,-553 496,-898 "/>
<text text-anchor="middle" x="627.5" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="496,-875 759,-875 "/>
<text text-anchor="middle" x="627.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="496,-852 759,-852 "/>
<text text-anchor="middle" x="627.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="496,-829 759,-829 "/>
<text text-anchor="middle" x="627.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="496,-806 759,-806 "/>
<text text-anchor="middle" x="627.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_certainty</text>
<polyline fill="none" stroke="#000000" points="496,-783 759,-783 "/>
<text text-anchor="middle" x="627.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="496,-760 759,-760 "/>
<text text-anchor="middle" x="627.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="496,-737 759,-737 "/>
<text text-anchor="middle" x="627.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="496,-714 759,-714 "/>
<text text-anchor="middle" x="627.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="496,-691 759,-691 "/>
<text text-anchor="middle" x="627.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="496,-668 759,-668 "/>
<text text-anchor="middle" x="627.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="496,-645 759,-645 "/>
<text text-anchor="middle" x="627.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="496,-622 759,-622 "/>
<text text-anchor="middle" x="627.5" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="496,-599 759,-599 "/>
<text text-anchor="middle" x="627.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="496,-576 759,-576 "/>
<text text-anchor="middle" x="627.5" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="759,-553 759,-898 "/>
<text text-anchor="middle" x="769.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M562.6045,-552.7662C557.2986,-512.7361 552.022,-472.9272 547.9555,-442.2477"/>
<polygon fill="#000000" stroke="#000000" points="551.4083,-441.6595 546.6245,-432.2062 544.4689,-442.5794 551.4083,-441.6595"/>
<text text-anchor="middle" x="603" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- survival -->
<g id="node6" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M810,-656.5C810,-656.5 1171,-656.5 1171,-656.5 1177,-656.5 1183,-662.5 1183,-668.5 1183,-668.5 1183,-782.5 1183,-782.5 1183,-788.5 1177,-794.5 1171,-794.5 1171,-794.5 810,-794.5 810,-794.5 804,-794.5 798,-788.5 798,-782.5 798,-782.5 798,-668.5 798,-668.5 798,-662.5 804,-656.5 810,-656.5"/>
<text text-anchor="middle" x="835" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="872,-656.5 872,-794.5 "/>
<text text-anchor="middle" x="882.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="893,-656.5 893,-794.5 "/>
<text text-anchor="middle" x="1027.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="893,-771.5 1162,-771.5 "/>
<text text-anchor="middle" x="1027.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="893,-748.5 1162,-748.5 "/>
<text text-anchor="middle" x="1027.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="893,-725.5 1162,-725.5 "/>
<text text-anchor="middle" x="1027.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="893,-702.5 1162,-702.5 "/>
<text text-anchor="middle" x="1027.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="893,-679.5 1162,-679.5 "/>
<text text-anchor="middle" x="1027.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="1162,-656.5 1162,-794.5 "/>
<text text-anchor="middle" x="1172.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M925.737,-656.0725C888.3929,-618.722 839.1175,-573.7417 789.5,-541 743.5102,-510.6522 723.8053,-518.2535 676.5,-490 651.2726,-474.9327 625.248,-455.9932 602.8041,-438.4192"/>
<polygon fill="#000000" stroke="#000000" points="604.7205,-435.4726 594.7054,-432.0161 600.379,-440.9637 604.7205,-435.4726"/>
<text text-anchor="middle" x="795" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
</g>
</svg>
</div>
