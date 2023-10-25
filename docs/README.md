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
<svg width="1193pt" height="987pt"
 viewBox="0.00 0.00 1193.00 987.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 983)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-983 1189,-983 1189,4 -4,4"/>
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
<!-- participant -->
<g id="node2" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M397.5,-351.5C397.5,-351.5 701.5,-351.5 701.5,-351.5 707.5,-351.5 713.5,-357.5 713.5,-363.5 713.5,-363.5 713.5,-454.5 713.5,-454.5 713.5,-460.5 707.5,-466.5 701.5,-466.5 701.5,-466.5 397.5,-466.5 397.5,-466.5 391.5,-466.5 385.5,-460.5 385.5,-454.5 385.5,-454.5 385.5,-363.5 385.5,-363.5 385.5,-357.5 391.5,-351.5 397.5,-351.5"/>
<text text-anchor="middle" x="433.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="481.5,-351.5 481.5,-466.5 "/>
<text text-anchor="middle" x="492" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="502.5,-351.5 502.5,-466.5 "/>
<text text-anchor="middle" x="597.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="502.5,-443.5 692.5,-443.5 "/>
<text text-anchor="middle" x="597.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="502.5,-420.5 692.5,-420.5 "/>
<text text-anchor="middle" x="597.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="502.5,-397.5 692.5,-397.5 "/>
<text text-anchor="middle" x="597.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="502.5,-374.5 692.5,-374.5 "/>
<text text-anchor="middle" x="597.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="692.5,-351.5 692.5,-466.5 "/>
<text text-anchor="middle" x="703" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M375.1271,-589.1532C415.3428,-547.6044 455.1217,-506.5068 486.5083,-474.0798"/>
<polygon fill="#000000" stroke="#000000" points="489.0422,-476.4944 493.4822,-466.8747 484.0124,-471.626 489.0422,-476.4944"/>
<text text-anchor="middle" x="438" y="-557.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study -->
<g id="node3" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M440,-.5C440,-.5 659,-.5 659,-.5 665,-.5 671,-6.5 671,-12.5 671,-12.5 671,-218.5 671,-218.5 671,-224.5 665,-230.5 659,-230.5 659,-230.5 440,-230.5 440,-230.5 434,-230.5 428,-224.5 428,-218.5 428,-218.5 428,-12.5 428,-12.5 428,-6.5 434,-.5 440,-.5"/>
<text text-anchor="middle" x="456" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="484,-.5 484,-230.5 "/>
<text text-anchor="middle" x="494.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="505,-.5 505,-230.5 "/>
<text text-anchor="middle" x="577.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="505,-207.5 650,-207.5 "/>
<text text-anchor="middle" x="577.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="505,-184.5 650,-184.5 "/>
<text text-anchor="middle" x="577.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="505,-161.5 650,-161.5 "/>
<text text-anchor="middle" x="577.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="505,-138.5 650,-138.5 "/>
<text text-anchor="middle" x="577.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="505,-115.5 650,-115.5 "/>
<text text-anchor="middle" x="577.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="505,-92.5 650,-92.5 "/>
<text text-anchor="middle" x="577.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="505,-69.5 650,-69.5 "/>
<text text-anchor="middle" x="577.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="505,-46.5 650,-46.5 "/>
<text text-anchor="middle" x="577.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="505,-23.5 650,-23.5 "/>
<text text-anchor="middle" x="577.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="650,-.5 650,-230.5 "/>
<text text-anchor="middle" x="660.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M199.0699,-587.4903C212.8543,-488.8204 242.1017,-371.4269 303.5,-282 332.6517,-239.5404 376.4972,-204.8694 419.1352,-178.3721"/>
<polygon fill="#000000" stroke="#000000" points="421.2096,-181.2066 427.9253,-173.0121 417.5652,-175.2301 421.2096,-181.2066"/>
<text text-anchor="middle" x="340" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge2" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M549.5,-351.364C549.5,-319.7948 549.5,-279.3705 549.5,-240.9387"/>
<polygon fill="#000000" stroke="#000000" points="553.0001,-240.6911 549.5,-230.6911 546.0001,-240.6912 553.0001,-240.6911"/>
<text text-anchor="middle" x="600" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- survival -->
<g id="node4" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M405,-714C405,-714 766,-714 766,-714 772,-714 778,-720 778,-726 778,-726 778,-840 778,-840 778,-846 772,-852 766,-852 766,-852 405,-852 405,-852 399,-852 393,-846 393,-840 393,-840 393,-726 393,-726 393,-720 399,-714 405,-714"/>
<text text-anchor="middle" x="430" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="467,-714 467,-852 "/>
<text text-anchor="middle" x="477.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="488,-714 488,-852 "/>
<text text-anchor="middle" x="622.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="488,-829 757,-829 "/>
<text text-anchor="middle" x="622.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="488,-806 757,-806 "/>
<text text-anchor="middle" x="622.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="488,-783 757,-783 "/>
<text text-anchor="middle" x="622.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="488,-760 757,-760 "/>
<text text-anchor="middle" x="622.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="488,-737 757,-737 "/>
<text text-anchor="middle" x="622.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="757,-714 757,-852 "/>
<text text-anchor="middle" x="767.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M578.8551,-713.9668C572.3428,-646.3111 562.4788,-543.8353 556.0124,-476.6567"/>
<polygon fill="#000000" stroke="#000000" points="559.4865,-476.2181 555.0443,-466.5995 552.5187,-476.8889 559.4865,-476.2181"/>
<text text-anchor="middle" x="604" y="-557.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- reference_file -->
<g id="node5" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M744,-282.5C744,-282.5 1045,-282.5 1045,-282.5 1051,-282.5 1057,-288.5 1057,-294.5 1057,-294.5 1057,-523.5 1057,-523.5 1057,-529.5 1051,-535.5 1045,-535.5 1045,-535.5 744,-535.5 744,-535.5 738,-535.5 732,-529.5 732,-523.5 732,-523.5 732,-294.5 732,-294.5 732,-288.5 738,-282.5 744,-282.5"/>
<text text-anchor="middle" x="790" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="848,-282.5 848,-535.5 "/>
<text text-anchor="middle" x="858.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="869,-282.5 869,-535.5 "/>
<text text-anchor="middle" x="952.5" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="869,-512.5 1036,-512.5 "/>
<text text-anchor="middle" x="952.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="869,-489.5 1036,-489.5 "/>
<text text-anchor="middle" x="952.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="869,-466.5 1036,-466.5 "/>
<text text-anchor="middle" x="952.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="869,-443.5 1036,-443.5 "/>
<text text-anchor="middle" x="952.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="869,-420.5 1036,-420.5 "/>
<text text-anchor="middle" x="952.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="869,-397.5 1036,-397.5 "/>
<text text-anchor="middle" x="952.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="869,-374.5 1036,-374.5 "/>
<text text-anchor="middle" x="952.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="869,-351.5 1036,-351.5 "/>
<text text-anchor="middle" x="952.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="869,-328.5 1036,-328.5 "/>
<text text-anchor="middle" x="952.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="869,-305.5 1036,-305.5 "/>
<text text-anchor="middle" x="952.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="1036,-282.5 1036,-535.5 "/>
<text text-anchor="middle" x="1046.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge1" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M745.6857,-282.4C723.4176,-263.456 700.6127,-244.0553 678.7935,-225.4932"/>
<polygon fill="#000000" stroke="#000000" points="681.004,-222.7785 671.1194,-218.9646 676.4682,-228.1102 681.004,-222.7785"/>
<text text-anchor="middle" x="783" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- diagnosis -->
<g id="node6" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M808,-645C808,-645 1173,-645 1173,-645 1179,-645 1185,-651 1185,-657 1185,-657 1185,-909 1185,-909 1185,-915 1179,-921 1173,-921 1173,-921 808,-921 808,-921 802,-921 796,-915 796,-909 796,-909 796,-657 796,-657 796,-651 802,-645 808,-645"/>
<text text-anchor="middle" x="838" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="880,-645 880,-921 "/>
<text text-anchor="middle" x="890.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="901,-645 901,-921 "/>
<text text-anchor="middle" x="1032.5" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="901,-898 1164,-898 "/>
<text text-anchor="middle" x="1032.5" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="901,-875 1164,-875 "/>
<text text-anchor="middle" x="1032.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="901,-852 1164,-852 "/>
<text text-anchor="middle" x="1032.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="901,-829 1164,-829 "/>
<text text-anchor="middle" x="1032.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="901,-806 1164,-806 "/>
<text text-anchor="middle" x="1032.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="901,-783 1164,-783 "/>
<text text-anchor="middle" x="1032.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="901,-760 1164,-760 "/>
<text text-anchor="middle" x="1032.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="901,-737 1164,-737 "/>
<text text-anchor="middle" x="1032.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="901,-714 1164,-714 "/>
<text text-anchor="middle" x="1032.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="901,-691 1164,-691 "/>
<text text-anchor="middle" x="1032.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="901,-668 1164,-668 "/>
<text text-anchor="middle" x="1032.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1164,-645 1164,-921 "/>
<text text-anchor="middle" x="1174.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M851.2744,-644.9631C829.9602,-625.0883 807.9189,-605.2169 786.5,-587 759.3666,-563.9229 692.2693,-513.7492 636.3671,-472.5348"/>
<polygon fill="#000000" stroke="#000000" points="638.3337,-469.6364 628.2065,-466.5233 634.182,-475.2723 638.3337,-469.6364"/>
<text text-anchor="middle" x="808" y="-557.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
</g>
</svg>
</div>
