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
<svg width="1331pt" height="918pt"
 viewBox="0.00 0.00 1331.00 918.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 914)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-914 1327,-914 1327,4 -4,4"/>
<!-- diagnosis -->
<g id="node1" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M12,-553C12,-553 377,-553 377,-553 383,-553 389,-559 389,-565 389,-565 389,-886 389,-886 389,-892 383,-898 377,-898 377,-898 12,-898 12,-898 6,-898 0,-892 0,-886 0,-886 0,-565 0,-565 0,-559 6,-553 12,-553"/>
<text text-anchor="middle" x="42" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="84,-553 84,-898 "/>
<text text-anchor="middle" x="94.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="105,-553 105,-898 "/>
<text text-anchor="middle" x="236.5" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="105,-875 368,-875 "/>
<text text-anchor="middle" x="236.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="105,-852 368,-852 "/>
<text text-anchor="middle" x="236.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="105,-829 368,-829 "/>
<text text-anchor="middle" x="236.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="105,-806 368,-806 "/>
<text text-anchor="middle" x="236.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="105,-783 368,-783 "/>
<text text-anchor="middle" x="236.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="105,-760 368,-760 "/>
<text text-anchor="middle" x="236.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="105,-737 368,-737 "/>
<text text-anchor="middle" x="236.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="105,-714 368,-714 "/>
<text text-anchor="middle" x="236.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="105,-691 368,-691 "/>
<text text-anchor="middle" x="236.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="105,-668 368,-668 "/>
<text text-anchor="middle" x="236.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="105,-645 368,-645 "/>
<text text-anchor="middle" x="236.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="105,-622 368,-622 "/>
<text text-anchor="middle" x="236.5" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="105,-599 368,-599 "/>
<text text-anchor="middle" x="236.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="105,-576 368,-576 "/>
<text text-anchor="middle" x="236.5" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="368,-553 368,-898 "/>
<text text-anchor="middle" x="378.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node3" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M568,-328.5C568,-328.5 799,-328.5 799,-328.5 805,-328.5 811,-334.5 811,-340.5 811,-340.5 811,-431.5 811,-431.5 811,-437.5 805,-443.5 799,-443.5 799,-443.5 568,-443.5 568,-443.5 562,-443.5 556,-437.5 556,-431.5 556,-431.5 556,-340.5 556,-340.5 556,-334.5 562,-328.5 568,-328.5"/>
<text text-anchor="middle" x="604" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="652,-328.5 652,-443.5 "/>
<text text-anchor="middle" x="662.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="673,-328.5 673,-443.5 "/>
<text text-anchor="middle" x="731.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="673,-420.5 790,-420.5 "/>
<text text-anchor="middle" x="731.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="673,-397.5 790,-397.5 "/>
<text text-anchor="middle" x="731.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="673,-374.5 790,-374.5 "/>
<text text-anchor="middle" x="731.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="673,-351.5 790,-351.5 "/>
<text text-anchor="middle" x="731.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="790,-328.5 790,-443.5 "/>
<text text-anchor="middle" x="800.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M381.1682,-552.9394C386.6128,-548.847 392.0626,-544.8586 397.5,-541 445.9451,-506.6212 502.8628,-474.3262 553.1121,-448.2065"/>
<polygon fill="#000000" stroke="#000000" points="554.8099,-451.2689 562.0879,-443.5693 551.597,-445.0498 554.8099,-451.2689"/>
<text text-anchor="middle" x="487" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- survival -->
<g id="node2" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M419,-645C419,-645 780,-645 780,-645 786,-645 792,-651 792,-657 792,-657 792,-794 792,-794 792,-800 786,-806 780,-806 780,-806 419,-806 419,-806 413,-806 407,-800 407,-794 407,-794 407,-657 407,-657 407,-651 413,-645 419,-645"/>
<text text-anchor="middle" x="444" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="481,-645 481,-806 "/>
<text text-anchor="middle" x="491.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="502,-645 502,-806 "/>
<text text-anchor="middle" x="636.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="502,-783 771,-783 "/>
<text text-anchor="middle" x="636.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="502,-760 771,-760 "/>
<text text-anchor="middle" x="636.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="502,-737 771,-737 "/>
<text text-anchor="middle" x="636.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="502,-714 771,-714 "/>
<text text-anchor="middle" x="636.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="502,-691 771,-691 "/>
<text text-anchor="middle" x="636.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="502,-668 771,-668 "/>
<text text-anchor="middle" x="636.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="771,-645 771,-806 "/>
<text text-anchor="middle" x="781.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M619.5134,-644.6126C633.9263,-586.3602 653.1501,-508.6641 666.7529,-453.6862"/>
<polygon fill="#000000" stroke="#000000" points="670.2207,-454.2427 669.225,-443.6948 663.4256,-452.5614 670.2207,-454.2427"/>
<text text-anchor="middle" x="690" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- study -->
<g id="node6" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M821,-.5C821,-.5 1040,-.5 1040,-.5 1046,-.5 1052,-6.5 1052,-12.5 1052,-12.5 1052,-218.5 1052,-218.5 1052,-224.5 1046,-230.5 1040,-230.5 1040,-230.5 821,-230.5 821,-230.5 815,-230.5 809,-224.5 809,-218.5 809,-218.5 809,-12.5 809,-12.5 809,-6.5 815,-.5 821,-.5"/>
<text text-anchor="middle" x="837" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="865,-.5 865,-230.5 "/>
<text text-anchor="middle" x="875.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="886,-.5 886,-230.5 "/>
<text text-anchor="middle" x="958.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="886,-207.5 1031,-207.5 "/>
<text text-anchor="middle" x="958.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="886,-184.5 1031,-184.5 "/>
<text text-anchor="middle" x="958.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="886,-161.5 1031,-161.5 "/>
<text text-anchor="middle" x="958.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="886,-138.5 1031,-138.5 "/>
<text text-anchor="middle" x="958.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="886,-115.5 1031,-115.5 "/>
<text text-anchor="middle" x="958.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="886,-92.5 1031,-92.5 "/>
<text text-anchor="middle" x="958.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="886,-69.5 1031,-69.5 "/>
<text text-anchor="middle" x="958.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="886,-46.5 1031,-46.5 "/>
<text text-anchor="middle" x="958.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="886,-23.5 1031,-23.5 "/>
<text text-anchor="middle" x="958.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1031,-.5 1031,-230.5 "/>
<text text-anchor="middle" x="1041.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge5" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M736.1847,-328.3027C760.2538,-301.9437 789.7429,-269.6489 818.4056,-238.2592"/>
<polygon fill="#000000" stroke="#000000" points="821.1216,-240.4755 825.28,-230.7308 815.9524,-235.7553 821.1216,-240.4755"/>
<text text-anchor="middle" x="857" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample -->
<g id="node4" class="node">
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
<g id="edge2" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M826.7178,-541.3433C796.8951,-508.9957 767.7204,-477.3509 743.5673,-451.1529"/>
<polygon fill="#000000" stroke="#000000" points="745.9173,-448.5383 736.5657,-443.5585 740.7708,-453.2831 745.9173,-448.5383"/>
<text text-anchor="middle" x="839" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M948.8928,-541.3727C945.5825,-524.0922 942.6941,-506.7723 940.5,-490 929.7031,-407.464 927.2022,-313.855 927.401,-240.872"/>
<polygon fill="#000000" stroke="#000000" points="930.9016,-240.7295 927.4464,-230.714 923.9016,-240.6982 930.9016,-240.7295"/>
<text text-anchor="middle" x="977" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- reference_file -->
<g id="node5" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M1034,-282.5C1034,-282.5 1311,-282.5 1311,-282.5 1317,-282.5 1323,-288.5 1323,-294.5 1323,-294.5 1323,-477.5 1323,-477.5 1323,-483.5 1317,-489.5 1311,-489.5 1311,-489.5 1034,-489.5 1034,-489.5 1028,-489.5 1022,-483.5 1022,-477.5 1022,-477.5 1022,-294.5 1022,-294.5 1022,-288.5 1028,-282.5 1034,-282.5"/>
<text text-anchor="middle" x="1080" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="1138,-282.5 1138,-489.5 "/>
<text text-anchor="middle" x="1148.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1159,-282.5 1159,-489.5 "/>
<text text-anchor="middle" x="1230.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1159,-466.5 1302,-466.5 "/>
<text text-anchor="middle" x="1230.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="1159,-443.5 1302,-443.5 "/>
<text text-anchor="middle" x="1230.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1159,-420.5 1302,-420.5 "/>
<text text-anchor="middle" x="1230.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1159,-397.5 1302,-397.5 "/>
<text text-anchor="middle" x="1230.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1159,-374.5 1302,-374.5 "/>
<text text-anchor="middle" x="1230.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1159,-351.5 1302,-351.5 "/>
<text text-anchor="middle" x="1230.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1159,-328.5 1302,-328.5 "/>
<text text-anchor="middle" x="1230.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="1159,-305.5 1302,-305.5 "/>
<text text-anchor="middle" x="1230.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="1302,-282.5 1302,-489.5 "/>
<text text-anchor="middle" x="1312.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge6" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1079.6286,-282.1912C1066.8024,-267.8545 1053.5298,-253.0188 1040.4317,-238.3781"/>
<polygon fill="#000000" stroke="#000000" points="1042.8774,-235.8626 1033.6013,-230.7434 1037.6604,-240.5299 1042.8774,-235.8626"/>
<text text-anchor="middle" x="1119" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
</g>
</svg>
</div>
