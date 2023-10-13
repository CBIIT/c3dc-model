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
<svg width="1067pt" height="987pt"
 viewBox="0.00 0.00 1067.00 987.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 983)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-983 1063,-983 1063,4 -4,4"/>
<!-- study -->
<g id="node1" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M442,-.5C442,-.5 661,-.5 661,-.5 667,-.5 673,-6.5 673,-12.5 673,-12.5 673,-218.5 673,-218.5 673,-224.5 667,-230.5 661,-230.5 661,-230.5 442,-230.5 442,-230.5 436,-230.5 430,-224.5 430,-218.5 430,-218.5 430,-12.5 430,-12.5 430,-6.5 436,-.5 442,-.5"/>
<text text-anchor="middle" x="458" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="486,-.5 486,-230.5 "/>
<text text-anchor="middle" x="496.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="507,-.5 507,-230.5 "/>
<text text-anchor="middle" x="579.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="507,-207.5 652,-207.5 "/>
<text text-anchor="middle" x="579.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="507,-184.5 652,-184.5 "/>
<text text-anchor="middle" x="579.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="507,-161.5 652,-161.5 "/>
<text text-anchor="middle" x="579.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="507,-138.5 652,-138.5 "/>
<text text-anchor="middle" x="579.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="507,-115.5 652,-115.5 "/>
<text text-anchor="middle" x="579.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="507,-92.5 652,-92.5 "/>
<text text-anchor="middle" x="579.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="507,-69.5 652,-69.5 "/>
<text text-anchor="middle" x="579.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="507,-46.5 652,-46.5 "/>
<text text-anchor="middle" x="579.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="507,-23.5 652,-23.5 "/>
<text text-anchor="middle" x="579.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="652,-.5 652,-230.5 "/>
<text text-anchor="middle" x="662.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node2" class="node">
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
<!-- sample&#45;&gt;study -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M199.9608,-587.4593C214.1689,-488.7811 243.8781,-371.3895 305.5,-282 334.6636,-239.6949 378.3898,-205.0992 420.9253,-178.6201"/>
<polygon fill="#000000" stroke="#000000" points="422.9854,-181.463 429.6945,-173.2631 419.3362,-175.4895 422.9854,-181.463"/>
<text text-anchor="middle" x="342" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant -->
<g id="node4" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M399.5,-351.5C399.5,-351.5 703.5,-351.5 703.5,-351.5 709.5,-351.5 715.5,-357.5 715.5,-363.5 715.5,-363.5 715.5,-454.5 715.5,-454.5 715.5,-460.5 709.5,-466.5 703.5,-466.5 703.5,-466.5 399.5,-466.5 399.5,-466.5 393.5,-466.5 387.5,-460.5 387.5,-454.5 387.5,-454.5 387.5,-363.5 387.5,-363.5 387.5,-357.5 393.5,-351.5 399.5,-351.5"/>
<text text-anchor="middle" x="435.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="483.5,-351.5 483.5,-466.5 "/>
<text text-anchor="middle" x="494" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="504.5,-351.5 504.5,-466.5 "/>
<text text-anchor="middle" x="599.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="504.5,-443.5 694.5,-443.5 "/>
<text text-anchor="middle" x="599.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="504.5,-420.5 694.5,-420.5 "/>
<text text-anchor="middle" x="599.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="504.5,-397.5 694.5,-397.5 "/>
<text text-anchor="middle" x="599.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="504.5,-374.5 694.5,-374.5 "/>
<text text-anchor="middle" x="599.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="694.5,-351.5 694.5,-466.5 "/>
<text text-anchor="middle" x="705" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M375.0978,-590.2484C415.8666,-548.3596 456.2604,-506.856 488.0863,-474.1558"/>
<polygon fill="#000000" stroke="#000000" points="490.6903,-476.4985 495.1568,-466.8911 485.6739,-471.6163 490.6903,-476.4985"/>
<text text-anchor="middle" x="439" y="-557.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- diagnosis -->
<g id="node3" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M405,-645C405,-645 770,-645 770,-645 776,-645 782,-651 782,-657 782,-657 782,-909 782,-909 782,-915 776,-921 770,-921 770,-921 405,-921 405,-921 399,-921 393,-915 393,-909 393,-909 393,-657 393,-657 393,-651 399,-645 405,-645"/>
<text text-anchor="middle" x="435" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="477,-645 477,-921 "/>
<text text-anchor="middle" x="487.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="498,-645 498,-921 "/>
<text text-anchor="middle" x="629.5" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="498,-898 761,-898 "/>
<text text-anchor="middle" x="629.5" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="498,-875 761,-875 "/>
<text text-anchor="middle" x="629.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="498,-852 761,-852 "/>
<text text-anchor="middle" x="629.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="498,-829 761,-829 "/>
<text text-anchor="middle" x="629.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="498,-806 761,-806 "/>
<text text-anchor="middle" x="629.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="498,-783 761,-783 "/>
<text text-anchor="middle" x="629.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="498,-760 761,-760 "/>
<text text-anchor="middle" x="629.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="498,-737 761,-737 "/>
<text text-anchor="middle" x="629.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="498,-714 761,-714 "/>
<text text-anchor="middle" x="629.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="498,-691 761,-691 "/>
<text text-anchor="middle" x="629.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="498,-668 761,-668 "/>
<text text-anchor="middle" x="629.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="761,-645 761,-921 "/>
<text text-anchor="middle" x="771.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M574.1972,-644.7988C568.6738,-587.4166 562.5159,-523.443 558.0093,-476.6246"/>
<polygon fill="#000000" stroke="#000000" points="561.487,-476.2237 557.0449,-466.6051 554.5192,-476.8945 561.487,-476.2237"/>
<text text-anchor="middle" x="611" y="-557.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge2" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M551.5,-351.364C551.5,-319.7948 551.5,-279.3705 551.5,-240.9387"/>
<polygon fill="#000000" stroke="#000000" points="555.0001,-240.6911 551.5,-230.6911 548.0001,-240.6912 555.0001,-240.6911"/>
<text text-anchor="middle" x="602" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- reference_file -->
<g id="node5" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M746,-282.5C746,-282.5 1047,-282.5 1047,-282.5 1053,-282.5 1059,-288.5 1059,-294.5 1059,-294.5 1059,-523.5 1059,-523.5 1059,-529.5 1053,-535.5 1047,-535.5 1047,-535.5 746,-535.5 746,-535.5 740,-535.5 734,-529.5 734,-523.5 734,-523.5 734,-294.5 734,-294.5 734,-288.5 740,-282.5 746,-282.5"/>
<text text-anchor="middle" x="792" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="850,-282.5 850,-535.5 "/>
<text text-anchor="middle" x="860.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="871,-282.5 871,-535.5 "/>
<text text-anchor="middle" x="954.5" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="871,-512.5 1038,-512.5 "/>
<text text-anchor="middle" x="954.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="871,-489.5 1038,-489.5 "/>
<text text-anchor="middle" x="954.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="871,-466.5 1038,-466.5 "/>
<text text-anchor="middle" x="954.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="871,-443.5 1038,-443.5 "/>
<text text-anchor="middle" x="954.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="871,-420.5 1038,-420.5 "/>
<text text-anchor="middle" x="954.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="871,-397.5 1038,-397.5 "/>
<text text-anchor="middle" x="954.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="871,-374.5 1038,-374.5 "/>
<text text-anchor="middle" x="954.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="871,-351.5 1038,-351.5 "/>
<text text-anchor="middle" x="954.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="871,-328.5 1038,-328.5 "/>
<text text-anchor="middle" x="954.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="871,-305.5 1038,-305.5 "/>
<text text-anchor="middle" x="954.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="1038,-282.5 1038,-535.5 "/>
<text text-anchor="middle" x="1048.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge1" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M747.6857,-282.4C725.4176,-263.456 702.6127,-244.0553 680.7935,-225.4932"/>
<polygon fill="#000000" stroke="#000000" points="683.004,-222.7785 673.1194,-218.9646 678.4682,-228.1102 683.004,-222.7785"/>
<text text-anchor="middle" x="785" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- event -->
<g id="node6" class="node">
<title>event</title>
<path fill="none" stroke="#000000" d="M812,-737C812,-737 1013,-737 1013,-737 1019,-737 1025,-743 1025,-749 1025,-749 1025,-817 1025,-817 1025,-823 1019,-829 1013,-829 1013,-829 812,-829 812,-829 806,-829 800,-823 800,-817 800,-817 800,-749 800,-749 800,-743 806,-737 812,-737"/>
<text text-anchor="middle" x="828" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">event</text>
<polyline fill="none" stroke="#000000" points="856,-737 856,-829 "/>
<text text-anchor="middle" x="866.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="877,-737 877,-829 "/>
<text text-anchor="middle" x="940.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event</text>
<polyline fill="none" stroke="#000000" points="877,-806 1004,-806 "/>
<text text-anchor="middle" x="940.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">event_category</text>
<polyline fill="none" stroke="#000000" points="877,-783 1004,-783 "/>
<text text-anchor="middle" x="940.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">event_detail</text>
<polyline fill="none" stroke="#000000" points="877,-760 1004,-760 "/>
<text text-anchor="middle" x="940.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">event_id</text>
<polyline fill="none" stroke="#000000" points="1004,-737 1004,-829 "/>
<text text-anchor="middle" x="1014.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- event&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>event&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M890.4367,-736.8665C868.94,-694.8756 833.4261,-632.6535 791.5,-587 784.9699,-579.8893 704.8611,-520.8452 638.9648,-472.6788"/>
<polygon fill="#000000" stroke="#000000" points="640.7338,-469.6366 630.5946,-466.5631 636.6042,-475.2887 640.7338,-469.6366"/>
<text text-anchor="middle" x="797" y="-557.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_event</text>
</g>
</g>
</svg>
</div>
