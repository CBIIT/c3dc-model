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
<svg width="1335pt" height="918pt"
 viewBox="0.00 0.00 1335.00 918.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 914)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-914 1331,-914 1331,4 -4,4"/>
<!-- survival -->
<g id="node1" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M12,-645C12,-645 373,-645 373,-645 379,-645 385,-651 385,-657 385,-657 385,-794 385,-794 385,-800 379,-806 373,-806 373,-806 12,-806 12,-806 6,-806 0,-800 0,-794 0,-794 0,-657 0,-657 0,-651 6,-645 12,-645"/>
<text text-anchor="middle" x="37" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="74,-645 74,-806 "/>
<text text-anchor="middle" x="84.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="95,-645 95,-806 "/>
<text text-anchor="middle" x="229.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="95,-783 364,-783 "/>
<text text-anchor="middle" x="229.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="95,-760 364,-760 "/>
<text text-anchor="middle" x="229.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="95,-737 364,-737 "/>
<text text-anchor="middle" x="229.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="95,-714 364,-714 "/>
<text text-anchor="middle" x="229.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="95,-691 364,-691 "/>
<text text-anchor="middle" x="229.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="95,-668 364,-668 "/>
<text text-anchor="middle" x="229.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="364,-645 364,-806 "/>
<text text-anchor="middle" x="374.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node3" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M569,-328.5C569,-328.5 800,-328.5 800,-328.5 806,-328.5 812,-334.5 812,-340.5 812,-340.5 812,-431.5 812,-431.5 812,-437.5 806,-443.5 800,-443.5 800,-443.5 569,-443.5 569,-443.5 563,-443.5 557,-437.5 557,-431.5 557,-431.5 557,-340.5 557,-340.5 557,-334.5 563,-328.5 569,-328.5"/>
<text text-anchor="middle" x="605" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="653,-328.5 653,-443.5 "/>
<text text-anchor="middle" x="663.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="674,-328.5 674,-443.5 "/>
<text text-anchor="middle" x="732.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="674,-420.5 791,-420.5 "/>
<text text-anchor="middle" x="732.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="674,-397.5 791,-397.5 "/>
<text text-anchor="middle" x="732.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="674,-374.5 791,-374.5 "/>
<text text-anchor="middle" x="732.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="674,-351.5 791,-351.5 "/>
<text text-anchor="middle" x="732.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="791,-328.5 791,-443.5 "/>
<text text-anchor="middle" x="801.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M271.1225,-644.6795C306.7064,-610.4499 350.3931,-571.5163 393.5,-541 442.4206,-506.3681 500.0078,-474.1345 550.9869,-448.1315"/>
<polygon fill="#000000" stroke="#000000" points="552.7568,-451.1584 560.0946,-443.516 549.5925,-444.9144 552.7568,-451.1584"/>
<text text-anchor="middle" x="478" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- sample -->
<g id="node2" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M822,-541.5C822,-541.5 1171,-541.5 1171,-541.5 1177,-541.5 1183,-547.5 1183,-553.5 1183,-553.5 1183,-897.5 1183,-897.5 1183,-903.5 1177,-909.5 1171,-909.5 1171,-909.5 822,-909.5 822,-909.5 816,-909.5 810,-903.5 810,-897.5 810,-897.5 810,-553.5 810,-553.5 810,-547.5 816,-541.5 822,-541.5"/>
<text text-anchor="middle" x="844" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="878,-541.5 878,-909.5 "/>
<text text-anchor="middle" x="888.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="899,-541.5 899,-909.5 "/>
<text text-anchor="middle" x="1030.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="899,-886.5 1162,-886.5 "/>
<text text-anchor="middle" x="1030.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="899,-863.5 1162,-863.5 "/>
<text text-anchor="middle" x="1030.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="899,-840.5 1162,-840.5 "/>
<text text-anchor="middle" x="1030.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="899,-817.5 1162,-817.5 "/>
<text text-anchor="middle" x="1030.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="899,-794.5 1162,-794.5 "/>
<text text-anchor="middle" x="1030.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="899,-771.5 1162,-771.5 "/>
<text text-anchor="middle" x="1030.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="899,-748.5 1162,-748.5 "/>
<text text-anchor="middle" x="1030.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="899,-725.5 1162,-725.5 "/>
<text text-anchor="middle" x="1030.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="899,-702.5 1162,-702.5 "/>
<text text-anchor="middle" x="1030.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="899,-679.5 1162,-679.5 "/>
<text text-anchor="middle" x="1030.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="899,-656.5 1162,-656.5 "/>
<text text-anchor="middle" x="1030.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="899,-633.5 1162,-633.5 "/>
<text text-anchor="middle" x="1030.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="899,-610.5 1162,-610.5 "/>
<text text-anchor="middle" x="1030.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="899,-587.5 1162,-587.5 "/>
<text text-anchor="middle" x="1030.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="899,-564.5 1162,-564.5 "/>
<text text-anchor="middle" x="1030.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1162,-541.5 1162,-909.5 "/>
<text text-anchor="middle" x="1172.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M827.2603,-541.3433C797.5329,-508.9957 768.4513,-477.3509 744.3754,-451.1529"/>
<polygon fill="#000000" stroke="#000000" points="746.7398,-448.5532 737.3962,-443.5585 741.5857,-453.2898 746.7398,-448.5532"/>
<text text-anchor="middle" x="839" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study -->
<g id="node5" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M825,-.5C825,-.5 1044,-.5 1044,-.5 1050,-.5 1056,-6.5 1056,-12.5 1056,-12.5 1056,-218.5 1056,-218.5 1056,-224.5 1050,-230.5 1044,-230.5 1044,-230.5 825,-230.5 825,-230.5 819,-230.5 813,-224.5 813,-218.5 813,-218.5 813,-12.5 813,-12.5 813,-6.5 819,-.5 825,-.5"/>
<text text-anchor="middle" x="841" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="869,-.5 869,-230.5 "/>
<text text-anchor="middle" x="879.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="890,-.5 890,-230.5 "/>
<text text-anchor="middle" x="962.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="890,-207.5 1035,-207.5 "/>
<text text-anchor="middle" x="962.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="890,-184.5 1035,-184.5 "/>
<text text-anchor="middle" x="962.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="890,-161.5 1035,-161.5 "/>
<text text-anchor="middle" x="962.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="890,-138.5 1035,-138.5 "/>
<text text-anchor="middle" x="962.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="890,-115.5 1035,-115.5 "/>
<text text-anchor="middle" x="962.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="890,-92.5 1035,-92.5 "/>
<text text-anchor="middle" x="962.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="890,-69.5 1035,-69.5 "/>
<text text-anchor="middle" x="962.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="890,-46.5 1035,-46.5 "/>
<text text-anchor="middle" x="962.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="890,-23.5 1035,-23.5 "/>
<text text-anchor="middle" x="962.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1035,-.5 1035,-230.5 "/>
<text text-anchor="middle" x="1045.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M952.3226,-541.2772C949.2426,-524.0166 946.5511,-506.7275 944.5,-490 934.3693,-407.3796 931.8686,-313.7706 931.9008,-240.8086"/>
<polygon fill="#000000" stroke="#000000" points="935.401,-240.6609 931.9217,-230.6537 928.4011,-240.6465 935.401,-240.6609"/>
<text text-anchor="middle" x="981" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge5" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M737.8246,-328.3027C762.186,-301.9437 792.0333,-269.6489 821.0441,-238.2592"/>
<polygon fill="#000000" stroke="#000000" points="823.7851,-240.4503 828.002,-230.7308 818.6443,-235.6991 823.7851,-240.4503"/>
<text text-anchor="middle" x="860" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- reference_file -->
<g id="node4" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M1038,-282.5C1038,-282.5 1315,-282.5 1315,-282.5 1321,-282.5 1327,-288.5 1327,-294.5 1327,-294.5 1327,-477.5 1327,-477.5 1327,-483.5 1321,-489.5 1315,-489.5 1315,-489.5 1038,-489.5 1038,-489.5 1032,-489.5 1026,-483.5 1026,-477.5 1026,-477.5 1026,-294.5 1026,-294.5 1026,-288.5 1032,-282.5 1038,-282.5"/>
<text text-anchor="middle" x="1084" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="1142,-282.5 1142,-489.5 "/>
<text text-anchor="middle" x="1152.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1163,-282.5 1163,-489.5 "/>
<text text-anchor="middle" x="1234.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1163,-466.5 1306,-466.5 "/>
<text text-anchor="middle" x="1234.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="1163,-443.5 1306,-443.5 "/>
<text text-anchor="middle" x="1234.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1163,-420.5 1306,-420.5 "/>
<text text-anchor="middle" x="1234.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1163,-397.5 1306,-397.5 "/>
<text text-anchor="middle" x="1234.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1163,-374.5 1306,-374.5 "/>
<text text-anchor="middle" x="1234.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1163,-351.5 1306,-351.5 "/>
<text text-anchor="middle" x="1234.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1163,-328.5 1306,-328.5 "/>
<text text-anchor="middle" x="1234.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="1163,-305.5 1306,-305.5 "/>
<text text-anchor="middle" x="1234.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="1306,-282.5 1306,-489.5 "/>
<text text-anchor="middle" x="1316.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge6" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1083.6286,-282.1912C1070.8024,-267.8545 1057.5298,-253.0188 1044.4317,-238.3781"/>
<polygon fill="#000000" stroke="#000000" points="1046.8774,-235.8626 1037.6013,-230.7434 1041.6604,-240.5299 1046.8774,-235.8626"/>
<text text-anchor="middle" x="1123" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- diagnosis -->
<g id="node6" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M415,-553C415,-553 780,-553 780,-553 786,-553 792,-559 792,-565 792,-565 792,-886 792,-886 792,-892 786,-898 780,-898 780,-898 415,-898 415,-898 409,-898 403,-892 403,-886 403,-886 403,-565 403,-565 403,-559 409,-553 415,-553"/>
<text text-anchor="middle" x="445" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="487,-553 487,-898 "/>
<text text-anchor="middle" x="497.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="508,-553 508,-898 "/>
<text text-anchor="middle" x="639.5" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="508,-875 771,-875 "/>
<text text-anchor="middle" x="639.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="508,-852 771,-852 "/>
<text text-anchor="middle" x="639.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="508,-829 771,-829 "/>
<text text-anchor="middle" x="639.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="508,-806 771,-806 "/>
<text text-anchor="middle" x="639.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="508,-783 771,-783 "/>
<text text-anchor="middle" x="639.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="508,-760 771,-760 "/>
<text text-anchor="middle" x="639.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="508,-737 771,-737 "/>
<text text-anchor="middle" x="639.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="508,-714 771,-714 "/>
<text text-anchor="middle" x="639.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="508,-691 771,-691 "/>
<text text-anchor="middle" x="639.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="508,-668 771,-668 "/>
<text text-anchor="middle" x="639.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="508,-645 771,-645 "/>
<text text-anchor="middle" x="639.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="508,-622 771,-622 "/>
<text text-anchor="middle" x="639.5" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="508,-599 771,-599 "/>
<text text-anchor="middle" x="639.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="508,-576 771,-576 "/>
<text text-anchor="middle" x="639.5" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="771,-553 771,-898 "/>
<text text-anchor="middle" x="781.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M641.7646,-552.7662C650.8141,-517.4525 659.8194,-482.3111 667.2134,-453.4576"/>
<polygon fill="#000000" stroke="#000000" points="670.6669,-454.0798 669.7589,-443.524 663.886,-452.3421 670.6669,-454.0798"/>
<text text-anchor="middle" x="695" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
</g>
</svg>
</div>
