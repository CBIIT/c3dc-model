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
<svg width="1331pt" height="895pt"
 viewBox="0.00 0.00 1331.00 895.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 891)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-891 1327,-891 1327,4 -4,4"/>
<!-- study -->
<g id="node1" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M821,-.5C821,-.5 1040,-.5 1040,-.5 1046,-.5 1052,-6.5 1052,-12.5 1052,-12.5 1052,-195.5 1052,-195.5 1052,-201.5 1046,-207.5 1040,-207.5 1040,-207.5 821,-207.5 821,-207.5 815,-207.5 809,-201.5 809,-195.5 809,-195.5 809,-12.5 809,-12.5 809,-6.5 815,-.5 821,-.5"/>
<text text-anchor="middle" x="837" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="865,-.5 865,-207.5 "/>
<text text-anchor="middle" x="875.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="886,-.5 886,-207.5 "/>
<text text-anchor="middle" x="958.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="886,-184.5 1031,-184.5 "/>
<text text-anchor="middle" x="958.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="886,-161.5 1031,-161.5 "/>
<text text-anchor="middle" x="958.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="886,-138.5 1031,-138.5 "/>
<text text-anchor="middle" x="958.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
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
<polyline fill="none" stroke="#000000" points="1031,-.5 1031,-207.5 "/>
<text text-anchor="middle" x="1041.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis -->
<g id="node2" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M12,-530C12,-530 377,-530 377,-530 383,-530 389,-536 389,-542 389,-542 389,-863 389,-863 389,-869 383,-875 377,-875 377,-875 12,-875 12,-875 6,-875 0,-869 0,-863 0,-863 0,-542 0,-542 0,-536 6,-530 12,-530"/>
<text text-anchor="middle" x="42" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="84,-530 84,-875 "/>
<text text-anchor="middle" x="94.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="105,-530 105,-875 "/>
<text text-anchor="middle" x="236.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="105,-852 368,-852 "/>
<text text-anchor="middle" x="236.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="105,-829 368,-829 "/>
<text text-anchor="middle" x="236.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="105,-806 368,-806 "/>
<text text-anchor="middle" x="236.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification</text>
<polyline fill="none" stroke="#000000" points="105,-783 368,-783 "/>
<text text-anchor="middle" x="236.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="105,-760 368,-760 "/>
<text text-anchor="middle" x="236.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="105,-737 368,-737 "/>
<text text-anchor="middle" x="236.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="105,-714 368,-714 "/>
<text text-anchor="middle" x="236.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_verification_status</text>
<polyline fill="none" stroke="#000000" points="105,-691 368,-691 "/>
<text text-anchor="middle" x="236.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="105,-668 368,-668 "/>
<text text-anchor="middle" x="236.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="105,-645 368,-645 "/>
<text text-anchor="middle" x="236.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="105,-622 368,-622 "/>
<text text-anchor="middle" x="236.5" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="105,-599 368,-599 "/>
<text text-anchor="middle" x="236.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="105,-576 368,-576 "/>
<text text-anchor="middle" x="236.5" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="105,-553 368,-553 "/>
<text text-anchor="middle" x="236.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="368,-530 368,-875 "/>
<text text-anchor="middle" x="378.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node3" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M568,-317C568,-317 799,-317 799,-317 805,-317 811,-323 811,-329 811,-329 811,-397 811,-397 811,-403 805,-409 799,-409 799,-409 568,-409 568,-409 562,-409 556,-403 556,-397 556,-397 556,-329 556,-329 556,-323 562,-317 568,-317"/>
<text text-anchor="middle" x="604" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="652,-317 652,-409 "/>
<text text-anchor="middle" x="662.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="673,-317 673,-409 "/>
<text text-anchor="middle" x="731.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="673,-386 790,-386 "/>
<text text-anchor="middle" x="731.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="673,-363 790,-363 "/>
<text text-anchor="middle" x="731.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="673,-340 790,-340 "/>
<text text-anchor="middle" x="731.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="790,-317 790,-409 "/>
<text text-anchor="middle" x="800.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M381.1682,-529.9394C386.6128,-525.847 392.0626,-521.8586 397.5,-518 453.3444,-478.3703 520.4471,-441.5096 575.6161,-413.685"/>
<polygon fill="#000000" stroke="#000000" points="577.3443,-416.7338 584.7149,-409.1231 574.2069,-410.4763 577.3443,-416.7338"/>
<text text-anchor="middle" x="487" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge3" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M727.374,-316.9944C754.4234,-288.6309 790.3568,-250.9518 824.4744,-215.1767"/>
<polygon fill="#000000" stroke="#000000" points="827.3547,-217.2278 831.7233,-207.5756 822.289,-212.3968 827.3547,-217.2278"/>
<text text-anchor="middle" x="858" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample -->
<g id="node4" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M822,-518.5C822,-518.5 1171,-518.5 1171,-518.5 1177,-518.5 1183,-524.5 1183,-530.5 1183,-530.5 1183,-874.5 1183,-874.5 1183,-880.5 1177,-886.5 1171,-886.5 1171,-886.5 822,-886.5 822,-886.5 816,-886.5 810,-880.5 810,-874.5 810,-874.5 810,-530.5 810,-530.5 810,-524.5 816,-518.5 822,-518.5"/>
<text text-anchor="middle" x="844" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="878,-518.5 878,-886.5 "/>
<text text-anchor="middle" x="888.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="899,-518.5 899,-886.5 "/>
<text text-anchor="middle" x="1030.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="899,-863.5 1162,-863.5 "/>
<text text-anchor="middle" x="1030.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="899,-840.5 1162,-840.5 "/>
<text text-anchor="middle" x="1030.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification</text>
<polyline fill="none" stroke="#000000" points="899,-817.5 1162,-817.5 "/>
<text text-anchor="middle" x="1030.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="899,-794.5 1162,-794.5 "/>
<text text-anchor="middle" x="1030.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="899,-771.5 1162,-771.5 "/>
<text text-anchor="middle" x="1030.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_verification_status</text>
<polyline fill="none" stroke="#000000" points="899,-748.5 1162,-748.5 "/>
<text text-anchor="middle" x="1030.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="899,-725.5 1162,-725.5 "/>
<text text-anchor="middle" x="1030.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="899,-702.5 1162,-702.5 "/>
<text text-anchor="middle" x="1030.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="899,-679.5 1162,-679.5 "/>
<text text-anchor="middle" x="1030.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="899,-656.5 1162,-656.5 "/>
<text text-anchor="middle" x="1030.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="899,-633.5 1162,-633.5 "/>
<text text-anchor="middle" x="1030.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="899,-610.5 1162,-610.5 "/>
<text text-anchor="middle" x="1030.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="899,-587.5 1162,-587.5 "/>
<text text-anchor="middle" x="1030.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="899,-564.5 1162,-564.5 "/>
<text text-anchor="middle" x="1030.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="899,-541.5 1162,-541.5 "/>
<text text-anchor="middle" x="1030.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1162,-518.5 1162,-886.5 "/>
<text text-anchor="middle" x="1172.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M948.0014,-518.4022C944.6406,-501.1155 941.7139,-483.7862 939.5,-467 928.5796,-384.1986 926.5518,-289.8794 927.1371,-218.1399"/>
<polygon fill="#000000" stroke="#000000" points="930.6411,-217.7579 927.2417,-207.7233 923.6414,-217.6876 930.6411,-217.7579"/>
<text text-anchor="middle" x="976" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M826.7178,-518.3433C792.4322,-481.1549 759.0029,-444.8953 733.0759,-416.7732"/>
<polygon fill="#000000" stroke="#000000" points="735.3192,-414.0429 725.9676,-409.0631 730.1727,-418.7877 735.3192,-414.0429"/>
<text text-anchor="middle" x="840" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- survival -->
<g id="node5" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M419,-633.5C419,-633.5 780,-633.5 780,-633.5 786,-633.5 792,-639.5 792,-645.5 792,-645.5 792,-759.5 792,-759.5 792,-765.5 786,-771.5 780,-771.5 780,-771.5 419,-771.5 419,-771.5 413,-771.5 407,-765.5 407,-759.5 407,-759.5 407,-645.5 407,-645.5 407,-639.5 413,-633.5 419,-633.5"/>
<text text-anchor="middle" x="444" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="481,-633.5 481,-771.5 "/>
<text text-anchor="middle" x="491.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="502,-633.5 502,-771.5 "/>
<text text-anchor="middle" x="636.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="502,-748.5 771,-748.5 "/>
<text text-anchor="middle" x="636.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="502,-725.5 771,-725.5 "/>
<text text-anchor="middle" x="636.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="502,-702.5 771,-702.5 "/>
<text text-anchor="middle" x="636.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="502,-679.5 771,-679.5 "/>
<text text-anchor="middle" x="636.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="502,-656.5 771,-656.5 "/>
<text text-anchor="middle" x="636.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="771,-633.5 771,-771.5 "/>
<text text-anchor="middle" x="781.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M616.5999,-633.3879C632.2443,-570.1584 655.1026,-477.773 669.6369,-419.0299"/>
<polygon fill="#000000" stroke="#000000" points="673.0685,-419.7327 672.0728,-409.1847 666.2734,-418.0514 673.0685,-419.7327"/>
<text text-anchor="middle" x="691" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- reference_file -->
<g id="node6" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M1034,-259.5C1034,-259.5 1311,-259.5 1311,-259.5 1317,-259.5 1323,-265.5 1323,-271.5 1323,-271.5 1323,-454.5 1323,-454.5 1323,-460.5 1317,-466.5 1311,-466.5 1311,-466.5 1034,-466.5 1034,-466.5 1028,-466.5 1022,-460.5 1022,-454.5 1022,-454.5 1022,-271.5 1022,-271.5 1022,-265.5 1028,-259.5 1034,-259.5"/>
<text text-anchor="middle" x="1080" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="1138,-259.5 1138,-466.5 "/>
<text text-anchor="middle" x="1148.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1159,-259.5 1159,-466.5 "/>
<text text-anchor="middle" x="1230.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1159,-443.5 1302,-443.5 "/>
<text text-anchor="middle" x="1230.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="1159,-420.5 1302,-420.5 "/>
<text text-anchor="middle" x="1230.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1159,-397.5 1302,-397.5 "/>
<text text-anchor="middle" x="1230.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1159,-374.5 1302,-374.5 "/>
<text text-anchor="middle" x="1230.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1159,-351.5 1302,-351.5 "/>
<text text-anchor="middle" x="1230.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1159,-328.5 1302,-328.5 "/>
<text text-anchor="middle" x="1230.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1159,-305.5 1302,-305.5 "/>
<text text-anchor="middle" x="1230.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="1159,-282.5 1302,-282.5 "/>
<text text-anchor="middle" x="1230.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="1302,-259.5 1302,-466.5 "/>
<text text-anchor="middle" x="1312.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge2" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1075.4637,-259.1471C1062.0264,-244.7659 1048.1784,-229.945 1034.6188,-215.4329"/>
<polygon fill="#000000" stroke="#000000" points="1036.9427,-212.7934 1027.558,-207.8762 1031.8279,-217.5725 1036.9427,-212.7934"/>
<text text-anchor="middle" x="1112" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
</g>
</svg>
</div>
