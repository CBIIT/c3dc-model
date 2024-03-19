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
<svg width="1191pt" height="872pt"
 viewBox="0.00 0.00 1191.00 872.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 868)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-868 1187,-868 1187,4 -4,4"/>
<!-- participant -->
<g id="node1" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M424,-317C424,-317 655,-317 655,-317 661,-317 667,-323 667,-329 667,-329 667,-397 667,-397 667,-403 661,-409 655,-409 655,-409 424,-409 424,-409 418,-409 412,-403 412,-397 412,-397 412,-329 412,-329 412,-323 418,-317 424,-317"/>
<text text-anchor="middle" x="460" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="508,-317 508,-409 "/>
<text text-anchor="middle" x="518.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="529,-317 529,-409 "/>
<text text-anchor="middle" x="587.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="529,-386 646,-386 "/>
<text text-anchor="middle" x="587.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="529,-363 646,-363 "/>
<text text-anchor="middle" x="587.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="529,-340 646,-340 "/>
<text text-anchor="middle" x="587.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="646,-317 646,-409 "/>
<text text-anchor="middle" x="656.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node6" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M430,-.5C430,-.5 649,-.5 649,-.5 655,-.5 661,-6.5 661,-12.5 661,-12.5 661,-195.5 661,-195.5 661,-201.5 655,-207.5 649,-207.5 649,-207.5 430,-207.5 430,-207.5 424,-207.5 418,-201.5 418,-195.5 418,-195.5 418,-12.5 418,-12.5 418,-6.5 424,-.5 430,-.5"/>
<text text-anchor="middle" x="446" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="474,-.5 474,-207.5 "/>
<text text-anchor="middle" x="484.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="495,-.5 495,-207.5 "/>
<text text-anchor="middle" x="567.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="495,-184.5 640,-184.5 "/>
<text text-anchor="middle" x="567.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="495,-161.5 640,-161.5 "/>
<text text-anchor="middle" x="567.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="495,-138.5 640,-138.5 "/>
<text text-anchor="middle" x="567.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="495,-115.5 640,-115.5 "/>
<text text-anchor="middle" x="567.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="495,-92.5 640,-92.5 "/>
<text text-anchor="middle" x="567.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="495,-69.5 640,-69.5 "/>
<text text-anchor="middle" x="567.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="495,-46.5 640,-46.5 "/>
<text text-anchor="middle" x="567.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="495,-23.5 640,-23.5 "/>
<text text-anchor="middle" x="567.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="640,-.5 640,-207.5 "/>
<text text-anchor="middle" x="650.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge1" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M539.5,-316.9944C539.5,-289.3429 539.5,-252.8377 539.5,-217.8744"/>
<polygon fill="#000000" stroke="#000000" points="543.0001,-217.5755 539.5,-207.5756 536.0001,-217.5756 543.0001,-217.5755"/>
<text text-anchor="middle" x="590" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample -->
<g id="node2" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M12,-518.5C12,-518.5 361,-518.5 361,-518.5 367,-518.5 373,-524.5 373,-530.5 373,-530.5 373,-851.5 373,-851.5 373,-857.5 367,-863.5 361,-863.5 361,-863.5 12,-863.5 12,-863.5 6,-863.5 0,-857.5 0,-851.5 0,-851.5 0,-530.5 0,-530.5 0,-524.5 6,-518.5 12,-518.5"/>
<text text-anchor="middle" x="34" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="68,-518.5 68,-863.5 "/>
<text text-anchor="middle" x="78.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="89,-518.5 89,-863.5 "/>
<text text-anchor="middle" x="220.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="89,-840.5 352,-840.5 "/>
<text text-anchor="middle" x="220.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="89,-817.5 352,-817.5 "/>
<text text-anchor="middle" x="220.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="89,-794.5 352,-794.5 "/>
<text text-anchor="middle" x="220.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="89,-771.5 352,-771.5 "/>
<text text-anchor="middle" x="220.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="89,-748.5 352,-748.5 "/>
<text text-anchor="middle" x="220.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="89,-725.5 352,-725.5 "/>
<text text-anchor="middle" x="220.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="89,-702.5 352,-702.5 "/>
<text text-anchor="middle" x="220.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="89,-679.5 352,-679.5 "/>
<text text-anchor="middle" x="220.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="89,-656.5 352,-656.5 "/>
<text text-anchor="middle" x="220.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="89,-633.5 352,-633.5 "/>
<text text-anchor="middle" x="220.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="89,-610.5 352,-610.5 "/>
<text text-anchor="middle" x="220.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="89,-587.5 352,-587.5 "/>
<text text-anchor="middle" x="220.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="89,-564.5 352,-564.5 "/>
<text text-anchor="middle" x="220.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="89,-541.5 352,-541.5 "/>
<text text-anchor="middle" x="220.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="352,-518.5 352,-863.5 "/>
<text text-anchor="middle" x="362.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M372.3038,-518.3551C412.4217,-481.0785 451.8968,-444.399 482.4078,-416.0488"/>
<polygon fill="#000000" stroke="#000000" points="485.0233,-418.3963 489.9666,-409.0253 480.2585,-413.2683 485.0233,-418.3963"/>
<text text-anchor="middle" x="442" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M217.9148,-518.4433C239.3189,-434.4338 274.1435,-335.3533 329.5,-259 351.077,-229.2388 380.0667,-202.7748 409.6044,-180.5069"/>
<polygon fill="#000000" stroke="#000000" points="411.986,-183.0988 417.9444,-174.3382 407.8233,-177.4709 411.986,-183.0988"/>
<text text-anchor="middle" x="366" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- reference_file -->
<g id="node3" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M697,-259.5C697,-259.5 974,-259.5 974,-259.5 980,-259.5 986,-265.5 986,-271.5 986,-271.5 986,-454.5 986,-454.5 986,-460.5 980,-466.5 974,-466.5 974,-466.5 697,-466.5 697,-466.5 691,-466.5 685,-460.5 685,-454.5 685,-454.5 685,-271.5 685,-271.5 685,-265.5 691,-259.5 697,-259.5"/>
<text text-anchor="middle" x="743" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="801,-259.5 801,-466.5 "/>
<text text-anchor="middle" x="811.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="822,-259.5 822,-466.5 "/>
<text text-anchor="middle" x="893.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="822,-443.5 965,-443.5 "/>
<text text-anchor="middle" x="893.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="822,-420.5 965,-420.5 "/>
<text text-anchor="middle" x="893.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="822,-397.5 965,-397.5 "/>
<text text-anchor="middle" x="893.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="822,-374.5 965,-374.5 "/>
<text text-anchor="middle" x="893.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="822,-351.5 965,-351.5 "/>
<text text-anchor="middle" x="893.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="822,-328.5 965,-328.5 "/>
<text text-anchor="middle" x="893.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="822,-305.5 965,-305.5 "/>
<text text-anchor="middle" x="893.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="822,-282.5 965,-282.5 "/>
<text text-anchor="middle" x="893.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="965,-259.5 965,-466.5 "/>
<text text-anchor="middle" x="975.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge3" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M716.811,-259.1471C700.0737,-244.502 682.8154,-229.401 665.9393,-214.6344"/>
<polygon fill="#000000" stroke="#000000" points="668.0462,-211.8272 658.2156,-207.8762 663.4366,-217.0953 668.0462,-211.8272"/>
<text text-anchor="middle" x="748" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- survival -->
<g id="node4" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M403,-622C403,-622 764,-622 764,-622 770,-622 776,-628 776,-634 776,-634 776,-748 776,-748 776,-754 770,-760 764,-760 764,-760 403,-760 403,-760 397,-760 391,-754 391,-748 391,-748 391,-634 391,-634 391,-628 397,-622 403,-622"/>
<text text-anchor="middle" x="428" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="465,-622 465,-760 "/>
<text text-anchor="middle" x="475.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="486,-622 486,-760 "/>
<text text-anchor="middle" x="620.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="486,-737 755,-737 "/>
<text text-anchor="middle" x="620.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="486,-714 755,-714 "/>
<text text-anchor="middle" x="620.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="486,-691 755,-691 "/>
<text text-anchor="middle" x="620.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="486,-668 755,-668 "/>
<text text-anchor="middle" x="620.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="486,-645 755,-645 "/>
<text text-anchor="middle" x="620.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="755,-622 755,-760 "/>
<text text-anchor="middle" x="765.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M574.2225,-621.8404C566.1523,-561.6811 554.6022,-475.5804 547.0771,-419.4841"/>
<polygon fill="#000000" stroke="#000000" points="550.5192,-418.8178 545.7206,-409.3719 543.5813,-419.7485 550.5192,-418.8178"/>
<text text-anchor="middle" x="598" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- diagnosis -->
<g id="node5" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M806,-530C806,-530 1171,-530 1171,-530 1177,-530 1183,-536 1183,-542 1183,-542 1183,-840 1183,-840 1183,-846 1177,-852 1171,-852 1171,-852 806,-852 806,-852 800,-852 794,-846 794,-840 794,-840 794,-542 794,-542 794,-536 800,-530 806,-530"/>
<text text-anchor="middle" x="836" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="878,-530 878,-852 "/>
<text text-anchor="middle" x="888.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="899,-530 899,-852 "/>
<text text-anchor="middle" x="1030.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="899,-829 1162,-829 "/>
<text text-anchor="middle" x="1030.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="899,-806 1162,-806 "/>
<text text-anchor="middle" x="1030.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="899,-783 1162,-783 "/>
<text text-anchor="middle" x="1030.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="899,-760 1162,-760 "/>
<text text-anchor="middle" x="1030.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="899,-737 1162,-737 "/>
<text text-anchor="middle" x="1030.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="899,-714 1162,-714 "/>
<text text-anchor="middle" x="1030.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="899,-691 1162,-691 "/>
<text text-anchor="middle" x="1030.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="899,-668 1162,-668 "/>
<text text-anchor="middle" x="1030.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="899,-645 1162,-645 "/>
<text text-anchor="middle" x="1030.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="899,-622 1162,-622 "/>
<text text-anchor="middle" x="1030.5" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="899,-599 1162,-599 "/>
<text text-anchor="middle" x="1030.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="899,-576 1162,-576 "/>
<text text-anchor="middle" x="1030.5" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="899,-553 1162,-553 "/>
<text text-anchor="middle" x="1030.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1162,-530 1162,-852 "/>
<text text-anchor="middle" x="1172.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M802.3993,-529.9157C796.4342,-525.8072 790.4602,-521.8244 784.5,-518 739.4852,-489.1156 721.2298,-494.7385 675.5,-467 650.4893,-451.8292 624.6094,-432.9528 602.2248,-415.462"/>
<polygon fill="#000000" stroke="#000000" points="604.1637,-412.5337 594.1441,-409.0901 599.8294,-418.0304 604.1637,-412.5337"/>
<text text-anchor="middle" x="795" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
</g>
</svg>
</div>
