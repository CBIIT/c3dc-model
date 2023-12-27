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
<svg width="1371pt" height="1033pt"
 viewBox="0.00 0.00 1371.00 1033.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1029)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1029 1367,-1029 1367,4 -4,4"/>
<!-- survival -->
<g id="node1" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M12,-737C12,-737 373,-737 373,-737 379,-737 385,-743 385,-749 385,-749 385,-863 385,-863 385,-869 379,-875 373,-875 373,-875 12,-875 12,-875 6,-875 0,-869 0,-863 0,-863 0,-749 0,-749 0,-743 6,-737 12,-737"/>
<text text-anchor="middle" x="37" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="74,-737 74,-875 "/>
<text text-anchor="middle" x="84.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="95,-737 95,-875 "/>
<text text-anchor="middle" x="229.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="95,-852 364,-852 "/>
<text text-anchor="middle" x="229.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="95,-829 364,-829 "/>
<text text-anchor="middle" x="229.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="95,-806 364,-806 "/>
<text text-anchor="middle" x="229.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="95,-783 364,-783 "/>
<text text-anchor="middle" x="229.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="95,-760 364,-760 "/>
<text text-anchor="middle" x="229.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="364,-737 364,-875 "/>
<text text-anchor="middle" x="374.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node3" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M545.5,-351.5C545.5,-351.5 849.5,-351.5 849.5,-351.5 855.5,-351.5 861.5,-357.5 861.5,-363.5 861.5,-363.5 861.5,-454.5 861.5,-454.5 861.5,-460.5 855.5,-466.5 849.5,-466.5 849.5,-466.5 545.5,-466.5 545.5,-466.5 539.5,-466.5 533.5,-460.5 533.5,-454.5 533.5,-454.5 533.5,-363.5 533.5,-363.5 533.5,-357.5 539.5,-351.5 545.5,-351.5"/>
<text text-anchor="middle" x="581.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="629.5,-351.5 629.5,-466.5 "/>
<text text-anchor="middle" x="640" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="650.5,-351.5 650.5,-466.5 "/>
<text text-anchor="middle" x="745.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="650.5,-443.5 840.5,-443.5 "/>
<text text-anchor="middle" x="745.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="650.5,-420.5 840.5,-420.5 "/>
<text text-anchor="middle" x="745.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="650.5,-397.5 840.5,-397.5 "/>
<text text-anchor="middle" x="745.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="650.5,-374.5 840.5,-374.5 "/>
<text text-anchor="middle" x="745.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="840.5,-351.5 840.5,-466.5 "/>
<text text-anchor="middle" x="851" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M246.7507,-736.8117C284.7822,-690.9981 338.4784,-631.4001 393.5,-587 448.1661,-542.8868 514.9721,-502.527 572.0211,-471.4323"/>
<polygon fill="#000000" stroke="#000000" points="573.9626,-474.3612 581.09,-466.5221 570.6298,-468.2055 573.9626,-474.3612"/>
<text text-anchor="middle" x="472" y="-557.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- diagnosis -->
<g id="node2" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M415,-633.5C415,-633.5 780,-633.5 780,-633.5 786,-633.5 792,-639.5 792,-645.5 792,-645.5 792,-966.5 792,-966.5 792,-972.5 786,-978.5 780,-978.5 780,-978.5 415,-978.5 415,-978.5 409,-978.5 403,-972.5 403,-966.5 403,-966.5 403,-645.5 403,-645.5 403,-639.5 409,-633.5 415,-633.5"/>
<text text-anchor="middle" x="445" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="487,-633.5 487,-978.5 "/>
<text text-anchor="middle" x="497.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="508,-633.5 508,-978.5 "/>
<text text-anchor="middle" x="639.5" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="508,-955.5 771,-955.5 "/>
<text text-anchor="middle" x="639.5" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="508,-932.5 771,-932.5 "/>
<text text-anchor="middle" x="639.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="508,-909.5 771,-909.5 "/>
<text text-anchor="middle" x="639.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification</text>
<polyline fill="none" stroke="#000000" points="508,-886.5 771,-886.5 "/>
<text text-anchor="middle" x="639.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="508,-863.5 771,-863.5 "/>
<text text-anchor="middle" x="639.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="508,-840.5 771,-840.5 "/>
<text text-anchor="middle" x="639.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="508,-817.5 771,-817.5 "/>
<text text-anchor="middle" x="639.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_verification_status</text>
<polyline fill="none" stroke="#000000" points="508,-794.5 771,-794.5 "/>
<text text-anchor="middle" x="639.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="508,-771.5 771,-771.5 "/>
<text text-anchor="middle" x="639.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="508,-748.5 771,-748.5 "/>
<text text-anchor="middle" x="639.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="508,-725.5 771,-725.5 "/>
<text text-anchor="middle" x="639.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="508,-702.5 771,-702.5 "/>
<text text-anchor="middle" x="639.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="508,-679.5 771,-679.5 "/>
<text text-anchor="middle" x="639.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="508,-656.5 771,-656.5 "/>
<text text-anchor="middle" x="639.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="771,-633.5 771,-978.5 "/>
<text text-anchor="middle" x="781.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M640.9979,-633.3135C654.9732,-577.8315 669.6379,-519.6126 680.5243,-476.3937"/>
<polygon fill="#000000" stroke="#000000" points="683.9487,-477.1276 682.9973,-466.5755 677.1607,-475.4177 683.9487,-477.1276"/>
<text text-anchor="middle" x="703" y="-557.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study -->
<g id="node6" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M838,-.5C838,-.5 1057,-.5 1057,-.5 1063,-.5 1069,-6.5 1069,-12.5 1069,-12.5 1069,-218.5 1069,-218.5 1069,-224.5 1063,-230.5 1057,-230.5 1057,-230.5 838,-230.5 838,-230.5 832,-230.5 826,-224.5 826,-218.5 826,-218.5 826,-12.5 826,-12.5 826,-6.5 832,-.5 838,-.5"/>
<text text-anchor="middle" x="854" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="882,-.5 882,-230.5 "/>
<text text-anchor="middle" x="892.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="903,-.5 903,-230.5 "/>
<text text-anchor="middle" x="975.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="903,-207.5 1048,-207.5 "/>
<text text-anchor="middle" x="975.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="903,-184.5 1048,-184.5 "/>
<text text-anchor="middle" x="975.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="903,-161.5 1048,-161.5 "/>
<text text-anchor="middle" x="975.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="903,-138.5 1048,-138.5 "/>
<text text-anchor="middle" x="975.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="903,-115.5 1048,-115.5 "/>
<text text-anchor="middle" x="975.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="903,-92.5 1048,-92.5 "/>
<text text-anchor="middle" x="975.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="903,-69.5 1048,-69.5 "/>
<text text-anchor="middle" x="975.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="903,-46.5 1048,-46.5 "/>
<text text-anchor="middle" x="975.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="903,-23.5 1048,-23.5 "/>
<text text-anchor="middle" x="975.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1048,-.5 1048,-230.5 "/>
<text text-anchor="middle" x="1058.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge4" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M745.7827,-351.4879C771.4623,-320.9726 803.6153,-282.8804 832.5,-249 835.4258,-245.5682 838.396,-242.0889 841.3957,-238.579"/>
<polygon fill="#000000" stroke="#000000" points="844.164,-240.7272 848.0043,-230.8528 838.8445,-236.1771 844.164,-240.7272"/>
<text text-anchor="middle" x="883" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample -->
<g id="node4" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M822,-587.5C822,-587.5 1173,-587.5 1173,-587.5 1179,-587.5 1185,-593.5 1185,-599.5 1185,-599.5 1185,-1012.5 1185,-1012.5 1185,-1018.5 1179,-1024.5 1173,-1024.5 1173,-1024.5 822,-1024.5 822,-1024.5 816,-1024.5 810,-1018.5 810,-1012.5 810,-1012.5 810,-599.5 810,-599.5 810,-593.5 816,-587.5 822,-587.5"/>
<text text-anchor="middle" x="844" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="878,-587.5 878,-1024.5 "/>
<text text-anchor="middle" x="888.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="899,-587.5 899,-1024.5 "/>
<text text-anchor="middle" x="1031.5" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="899,-1001.5 1164,-1001.5 "/>
<text text-anchor="middle" x="1031.5" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="899,-978.5 1164,-978.5 "/>
<text text-anchor="middle" x="1031.5" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="899,-955.5 1164,-955.5 "/>
<text text-anchor="middle" x="1031.5" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="899,-932.5 1164,-932.5 "/>
<text text-anchor="middle" x="1031.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification</text>
<polyline fill="none" stroke="#000000" points="899,-909.5 1164,-909.5 "/>
<text text-anchor="middle" x="1031.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="899,-886.5 1164,-886.5 "/>
<text text-anchor="middle" x="1031.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="899,-863.5 1164,-863.5 "/>
<text text-anchor="middle" x="1031.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_verification_status</text>
<polyline fill="none" stroke="#000000" points="899,-840.5 1164,-840.5 "/>
<text text-anchor="middle" x="1031.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="899,-817.5 1164,-817.5 "/>
<text text-anchor="middle" x="1031.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="899,-794.5 1164,-794.5 "/>
<text text-anchor="middle" x="1031.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="899,-771.5 1164,-771.5 "/>
<text text-anchor="middle" x="1031.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="899,-748.5 1164,-748.5 "/>
<text text-anchor="middle" x="1031.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="899,-725.5 1164,-725.5 "/>
<text text-anchor="middle" x="1031.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="899,-702.5 1164,-702.5 "/>
<text text-anchor="middle" x="1031.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="899,-679.5 1164,-679.5 "/>
<text text-anchor="middle" x="1031.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="899,-656.5 1164,-656.5 "/>
<text text-anchor="middle" x="1031.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="899,-633.5 1164,-633.5 "/>
<text text-anchor="middle" x="1031.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="899,-610.5 1164,-610.5 "/>
<text text-anchor="middle" x="1031.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1164,-587.5 1164,-1024.5 "/>
<text text-anchor="middle" x="1174.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M832.3618,-587.4671C801.402,-546.497 771.3113,-506.6769 747.4377,-475.0842"/>
<polygon fill="#000000" stroke="#000000" points="750.0116,-472.6849 741.1903,-466.8168 744.4268,-476.9052 750.0116,-472.6849"/>
<text text-anchor="middle" x="848" y="-557.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge1" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M961.8662,-587.4585C959.7803,-570.0795 957.9466,-552.7691 956.5,-536 947.9668,-437.0799 945.9593,-324.6127 945.9527,-240.896"/>
<polygon fill="#000000" stroke="#000000" points="949.4526,-240.8351 945.9615,-230.832 942.4526,-240.8289 949.4526,-240.8351"/>
<text text-anchor="middle" x="993" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- reference_file -->
<g id="node5" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M1050,-282.5C1050,-282.5 1351,-282.5 1351,-282.5 1357,-282.5 1363,-288.5 1363,-294.5 1363,-294.5 1363,-523.5 1363,-523.5 1363,-529.5 1357,-535.5 1351,-535.5 1351,-535.5 1050,-535.5 1050,-535.5 1044,-535.5 1038,-529.5 1038,-523.5 1038,-523.5 1038,-294.5 1038,-294.5 1038,-288.5 1044,-282.5 1050,-282.5"/>
<text text-anchor="middle" x="1096" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="1154,-282.5 1154,-535.5 "/>
<text text-anchor="middle" x="1164.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1175,-282.5 1175,-535.5 "/>
<text text-anchor="middle" x="1258.5" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1175,-512.5 1342,-512.5 "/>
<text text-anchor="middle" x="1258.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1175,-489.5 1342,-489.5 "/>
<text text-anchor="middle" x="1258.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1175,-466.5 1342,-466.5 "/>
<text text-anchor="middle" x="1258.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="1175,-443.5 1342,-443.5 "/>
<text text-anchor="middle" x="1258.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1175,-420.5 1342,-420.5 "/>
<text text-anchor="middle" x="1258.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1175,-397.5 1342,-397.5 "/>
<text text-anchor="middle" x="1258.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1175,-374.5 1342,-374.5 "/>
<text text-anchor="middle" x="1258.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1175,-351.5 1342,-351.5 "/>
<text text-anchor="middle" x="1258.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1175,-328.5 1342,-328.5 "/>
<text text-anchor="middle" x="1258.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="1175,-305.5 1342,-305.5 "/>
<text text-anchor="middle" x="1258.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="1342,-282.5 1342,-535.5 "/>
<text text-anchor="middle" x="1352.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge6" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1091.3695,-282.4C1078.7281,-267.735 1065.8507,-252.7962 1053.2555,-238.1847"/>
<polygon fill="#000000" stroke="#000000" points="1055.8776,-235.866 1046.6974,-230.5768 1050.5756,-240.4364 1055.8776,-235.866"/>
<text text-anchor="middle" x="1134" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
</g>
</svg>
</div>
