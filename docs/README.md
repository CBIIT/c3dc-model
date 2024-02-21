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
<svg width="1335pt" height="895pt"
 viewBox="0.00 0.00 1335.00 895.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 891)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-891 1331,-891 1331,4 -4,4"/>
<!-- survival -->
<g id="node1" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M12,-633.5C12,-633.5 373,-633.5 373,-633.5 379,-633.5 385,-639.5 385,-645.5 385,-645.5 385,-759.5 385,-759.5 385,-765.5 379,-771.5 373,-771.5 373,-771.5 12,-771.5 12,-771.5 6,-771.5 0,-765.5 0,-759.5 0,-759.5 0,-645.5 0,-645.5 0,-639.5 6,-633.5 12,-633.5"/>
<text text-anchor="middle" x="37" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="74,-633.5 74,-771.5 "/>
<text text-anchor="middle" x="84.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="95,-633.5 95,-771.5 "/>
<text text-anchor="middle" x="229.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="95,-748.5 364,-748.5 "/>
<text text-anchor="middle" x="229.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="95,-725.5 364,-725.5 "/>
<text text-anchor="middle" x="229.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="95,-702.5 364,-702.5 "/>
<text text-anchor="middle" x="229.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="95,-679.5 364,-679.5 "/>
<text text-anchor="middle" x="229.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="95,-656.5 364,-656.5 "/>
<text text-anchor="middle" x="229.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="364,-633.5 364,-771.5 "/>
<text text-anchor="middle" x="374.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node3" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M569,-317C569,-317 800,-317 800,-317 806,-317 812,-323 812,-329 812,-329 812,-397 812,-397 812,-403 806,-409 800,-409 800,-409 569,-409 569,-409 563,-409 557,-403 557,-397 557,-397 557,-329 557,-329 557,-323 563,-317 569,-317"/>
<text text-anchor="middle" x="605" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="653,-317 653,-409 "/>
<text text-anchor="middle" x="663.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="674,-317 674,-409 "/>
<text text-anchor="middle" x="732.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="674,-386 791,-386 "/>
<text text-anchor="middle" x="732.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="674,-363 791,-363 "/>
<text text-anchor="middle" x="732.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="674,-340 791,-340 "/>
<text text-anchor="middle" x="732.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="791,-317 791,-409 "/>
<text text-anchor="middle" x="801.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M259.0202,-633.4396C296.5115,-596.643 345.3672,-552.0742 393.5,-518 449.9253,-478.0553 517.8801,-441.3013 573.9265,-413.6183"/>
<polygon fill="#000000" stroke="#000000" points="575.7373,-416.6284 583.172,-409.0802 572.6529,-410.3445 575.7373,-416.6284"/>
<text text-anchor="middle" x="478" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- diagnosis -->
<g id="node2" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M415,-530C415,-530 780,-530 780,-530 786,-530 792,-536 792,-542 792,-542 792,-863 792,-863 792,-869 786,-875 780,-875 780,-875 415,-875 415,-875 409,-875 403,-869 403,-863 403,-863 403,-542 403,-542 403,-536 409,-530 415,-530"/>
<text text-anchor="middle" x="445" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="487,-530 487,-875 "/>
<text text-anchor="middle" x="497.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="508,-530 508,-875 "/>
<text text-anchor="middle" x="639.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="508,-852 771,-852 "/>
<text text-anchor="middle" x="639.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="508,-829 771,-829 "/>
<text text-anchor="middle" x="639.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="508,-806 771,-806 "/>
<text text-anchor="middle" x="639.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification</text>
<polyline fill="none" stroke="#000000" points="508,-783 771,-783 "/>
<text text-anchor="middle" x="639.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="508,-760 771,-760 "/>
<text text-anchor="middle" x="639.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="508,-737 771,-737 "/>
<text text-anchor="middle" x="639.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="508,-714 771,-714 "/>
<text text-anchor="middle" x="639.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_verification_status</text>
<polyline fill="none" stroke="#000000" points="508,-691 771,-691 "/>
<text text-anchor="middle" x="639.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="508,-668 771,-668 "/>
<text text-anchor="middle" x="639.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="508,-645 771,-645 "/>
<text text-anchor="middle" x="639.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="508,-622 771,-622 "/>
<text text-anchor="middle" x="639.5" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="508,-599 771,-599 "/>
<text text-anchor="middle" x="639.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="508,-576 771,-576 "/>
<text text-anchor="middle" x="639.5" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="508,-553 771,-553 "/>
<text text-anchor="middle" x="639.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="771,-530 771,-875 "/>
<text text-anchor="middle" x="781.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M641.7646,-529.7662C652.0227,-489.7361 662.2241,-449.9272 670.086,-419.2477"/>
<polygon fill="#000000" stroke="#000000" points="673.5672,-419.762 672.6592,-409.2062 666.7863,-418.0243 673.5672,-419.762"/>
<text text-anchor="middle" x="695" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study -->
<g id="node5" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M825,-.5C825,-.5 1044,-.5 1044,-.5 1050,-.5 1056,-6.5 1056,-12.5 1056,-12.5 1056,-195.5 1056,-195.5 1056,-201.5 1050,-207.5 1044,-207.5 1044,-207.5 825,-207.5 825,-207.5 819,-207.5 813,-201.5 813,-195.5 813,-195.5 813,-12.5 813,-12.5 813,-6.5 819,-.5 825,-.5"/>
<text text-anchor="middle" x="841" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="869,-.5 869,-207.5 "/>
<text text-anchor="middle" x="879.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="890,-.5 890,-207.5 "/>
<text text-anchor="middle" x="962.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="890,-184.5 1035,-184.5 "/>
<text text-anchor="middle" x="962.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="890,-161.5 1035,-161.5 "/>
<text text-anchor="middle" x="962.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="890,-138.5 1035,-138.5 "/>
<text text-anchor="middle" x="962.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
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
<polyline fill="none" stroke="#000000" points="1035,-.5 1035,-207.5 "/>
<text text-anchor="middle" x="1045.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge4" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M728.9069,-316.9944C756.2849,-288.6309 792.6547,-250.9518 827.1866,-215.1767"/>
<polygon fill="#000000" stroke="#000000" points="830.0968,-217.2013 834.5236,-207.5756 825.0603,-212.3398 830.0968,-217.2013"/>
<text text-anchor="middle" x="860" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
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
<text text-anchor="middle" x="1030.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_certainty</text>
<polyline fill="none" stroke="#000000" points="899,-817.5 1162,-817.5 "/>
<text text-anchor="middle" x="1030.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification</text>
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
<!-- sample&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M827.2603,-518.3433C793.0842,-481.1549 759.7617,-444.8953 733.9175,-416.7732"/>
<polygon fill="#000000" stroke="#000000" points="736.1756,-414.0578 726.8319,-409.0631 731.0215,-418.7944 736.1756,-414.0578"/>
<text text-anchor="middle" x="839" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M952.3376,-518.2753C949.2545,-501.0151 946.5581,-483.7266 944.5,-467 934.2996,-384.1008 931.9787,-289.785 932.1137,-218.0716"/>
<polygon fill="#000000" stroke="#000000" points="935.6151,-217.6714 932.1508,-207.659 928.6151,-217.6464 935.6151,-217.6714"/>
<text text-anchor="middle" x="981" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- reference_file -->
<g id="node6" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M1038,-259.5C1038,-259.5 1315,-259.5 1315,-259.5 1321,-259.5 1327,-265.5 1327,-271.5 1327,-271.5 1327,-454.5 1327,-454.5 1327,-460.5 1321,-466.5 1315,-466.5 1315,-466.5 1038,-466.5 1038,-466.5 1032,-466.5 1026,-460.5 1026,-454.5 1026,-454.5 1026,-271.5 1026,-271.5 1026,-265.5 1032,-259.5 1038,-259.5"/>
<text text-anchor="middle" x="1084" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="1142,-259.5 1142,-466.5 "/>
<text text-anchor="middle" x="1152.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1163,-259.5 1163,-466.5 "/>
<text text-anchor="middle" x="1234.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1163,-443.5 1306,-443.5 "/>
<text text-anchor="middle" x="1234.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="1163,-420.5 1306,-420.5 "/>
<text text-anchor="middle" x="1234.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1163,-397.5 1306,-397.5 "/>
<text text-anchor="middle" x="1234.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1163,-374.5 1306,-374.5 "/>
<text text-anchor="middle" x="1234.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1163,-351.5 1306,-351.5 "/>
<text text-anchor="middle" x="1234.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1163,-328.5 1306,-328.5 "/>
<text text-anchor="middle" x="1234.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1163,-305.5 1306,-305.5 "/>
<text text-anchor="middle" x="1234.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="1163,-282.5 1306,-282.5 "/>
<text text-anchor="middle" x="1234.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="1306,-259.5 1306,-466.5 "/>
<text text-anchor="middle" x="1316.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge1" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1079.4637,-259.1471C1066.0264,-244.7659 1052.1784,-229.945 1038.6188,-215.4329"/>
<polygon fill="#000000" stroke="#000000" points="1040.9427,-212.7934 1031.558,-207.8762 1035.8279,-217.5725 1040.9427,-212.7934"/>
<text text-anchor="middle" x="1116" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
</g>
</svg>
</div>
