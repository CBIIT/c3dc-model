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
<svg width="1265pt" height="1033pt"
 viewBox="0.00 0.00 1265.00 1033.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1029)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1029 1261,-1029 1261,4 -4,4"/>
<!-- diagnosis -->
<g id="node1" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M12,-633.5C12,-633.5 377,-633.5 377,-633.5 383,-633.5 389,-639.5 389,-645.5 389,-645.5 389,-966.5 389,-966.5 389,-972.5 383,-978.5 377,-978.5 377,-978.5 12,-978.5 12,-978.5 6,-978.5 0,-972.5 0,-966.5 0,-966.5 0,-645.5 0,-645.5 0,-639.5 6,-633.5 12,-633.5"/>
<text text-anchor="middle" x="42" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="84,-633.5 84,-978.5 "/>
<text text-anchor="middle" x="94.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="105,-633.5 105,-978.5 "/>
<text text-anchor="middle" x="236.5" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="105,-955.5 368,-955.5 "/>
<text text-anchor="middle" x="236.5" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="105,-932.5 368,-932.5 "/>
<text text-anchor="middle" x="236.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="105,-909.5 368,-909.5 "/>
<text text-anchor="middle" x="236.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification</text>
<polyline fill="none" stroke="#000000" points="105,-886.5 368,-886.5 "/>
<text text-anchor="middle" x="236.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="105,-863.5 368,-863.5 "/>
<text text-anchor="middle" x="236.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="105,-840.5 368,-840.5 "/>
<text text-anchor="middle" x="236.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="105,-817.5 368,-817.5 "/>
<text text-anchor="middle" x="236.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_verification_status</text>
<polyline fill="none" stroke="#000000" points="105,-794.5 368,-794.5 "/>
<text text-anchor="middle" x="236.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="105,-771.5 368,-771.5 "/>
<text text-anchor="middle" x="236.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="105,-748.5 368,-748.5 "/>
<text text-anchor="middle" x="236.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="105,-725.5 368,-725.5 "/>
<text text-anchor="middle" x="236.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="105,-702.5 368,-702.5 "/>
<text text-anchor="middle" x="236.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="105,-679.5 368,-679.5 "/>
<text text-anchor="middle" x="236.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="105,-656.5 368,-656.5 "/>
<text text-anchor="middle" x="236.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="368,-633.5 368,-978.5 "/>
<text text-anchor="middle" x="378.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node5" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M410.5,-351.5C410.5,-351.5 714.5,-351.5 714.5,-351.5 720.5,-351.5 726.5,-357.5 726.5,-363.5 726.5,-363.5 726.5,-454.5 726.5,-454.5 726.5,-460.5 720.5,-466.5 714.5,-466.5 714.5,-466.5 410.5,-466.5 410.5,-466.5 404.5,-466.5 398.5,-460.5 398.5,-454.5 398.5,-454.5 398.5,-363.5 398.5,-363.5 398.5,-357.5 404.5,-351.5 410.5,-351.5"/>
<text text-anchor="middle" x="446.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="494.5,-351.5 494.5,-466.5 "/>
<text text-anchor="middle" x="505" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="515.5,-351.5 515.5,-466.5 "/>
<text text-anchor="middle" x="610.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="515.5,-443.5 705.5,-443.5 "/>
<text text-anchor="middle" x="610.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="515.5,-420.5 705.5,-420.5 "/>
<text text-anchor="middle" x="610.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="515.5,-397.5 705.5,-397.5 "/>
<text text-anchor="middle" x="610.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="515.5,-374.5 705.5,-374.5 "/>
<text text-anchor="middle" x="610.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="705.5,-351.5 705.5,-466.5 "/>
<text text-anchor="middle" x="716" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M354.5721,-633.3135C406.9758,-576.7802 462.0134,-517.4054 502.2914,-473.9533"/>
<polygon fill="#000000" stroke="#000000" points="504.8989,-476.2888 509.1302,-466.5755 499.7652,-471.5301 504.8989,-476.2888"/>
<text text-anchor="middle" x="467" y="-557.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study -->
<g id="node2" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M798,-.5C798,-.5 1017,-.5 1017,-.5 1023,-.5 1029,-6.5 1029,-12.5 1029,-12.5 1029,-218.5 1029,-218.5 1029,-224.5 1023,-230.5 1017,-230.5 1017,-230.5 798,-230.5 798,-230.5 792,-230.5 786,-224.5 786,-218.5 786,-218.5 786,-12.5 786,-12.5 786,-6.5 792,-.5 798,-.5"/>
<text text-anchor="middle" x="814" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="842,-.5 842,-230.5 "/>
<text text-anchor="middle" x="852.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="863,-.5 863,-230.5 "/>
<text text-anchor="middle" x="935.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="863,-207.5 1008,-207.5 "/>
<text text-anchor="middle" x="935.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="863,-184.5 1008,-184.5 "/>
<text text-anchor="middle" x="935.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="863,-161.5 1008,-161.5 "/>
<text text-anchor="middle" x="935.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="863,-138.5 1008,-138.5 "/>
<text text-anchor="middle" x="935.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="863,-115.5 1008,-115.5 "/>
<text text-anchor="middle" x="935.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="863,-92.5 1008,-92.5 "/>
<text text-anchor="middle" x="935.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="863,-69.5 1008,-69.5 "/>
<text text-anchor="middle" x="935.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="863,-46.5 1008,-46.5 "/>
<text text-anchor="middle" x="935.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="863,-23.5 1008,-23.5 "/>
<text text-anchor="middle" x="935.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="1008,-.5 1008,-230.5 "/>
<text text-anchor="middle" x="1018.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file -->
<g id="node3" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M757,-282.5C757,-282.5 1058,-282.5 1058,-282.5 1064,-282.5 1070,-288.5 1070,-294.5 1070,-294.5 1070,-523.5 1070,-523.5 1070,-529.5 1064,-535.5 1058,-535.5 1058,-535.5 757,-535.5 757,-535.5 751,-535.5 745,-529.5 745,-523.5 745,-523.5 745,-294.5 745,-294.5 745,-288.5 751,-282.5 757,-282.5"/>
<text text-anchor="middle" x="803" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="861,-282.5 861,-535.5 "/>
<text text-anchor="middle" x="871.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="882,-282.5 882,-535.5 "/>
<text text-anchor="middle" x="965.5" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="882,-512.5 1049,-512.5 "/>
<text text-anchor="middle" x="965.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="882,-489.5 1049,-489.5 "/>
<text text-anchor="middle" x="965.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="882,-466.5 1049,-466.5 "/>
<text text-anchor="middle" x="965.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="882,-443.5 1049,-443.5 "/>
<text text-anchor="middle" x="965.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="882,-420.5 1049,-420.5 "/>
<text text-anchor="middle" x="965.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="882,-397.5 1049,-397.5 "/>
<text text-anchor="middle" x="965.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="882,-374.5 1049,-374.5 "/>
<text text-anchor="middle" x="965.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="882,-351.5 1049,-351.5 "/>
<text text-anchor="middle" x="965.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="882,-328.5 1049,-328.5 "/>
<text text-anchor="middle" x="965.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="882,-305.5 1049,-305.5 "/>
<text text-anchor="middle" x="965.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="1049,-282.5 1049,-535.5 "/>
<text text-anchor="middle" x="1059.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge6" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M907.5,-282.4C907.5,-268.5422 907.5,-254.44 907.5,-240.6005"/>
<polygon fill="#000000" stroke="#000000" points="911.0001,-240.5768 907.5,-230.5768 904.0001,-240.5769 911.0001,-240.5768"/>
<text text-anchor="middle" x="968" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- sample -->
<g id="node4" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M894,-587.5C894,-587.5 1245,-587.5 1245,-587.5 1251,-587.5 1257,-593.5 1257,-599.5 1257,-599.5 1257,-1012.5 1257,-1012.5 1257,-1018.5 1251,-1024.5 1245,-1024.5 1245,-1024.5 894,-1024.5 894,-1024.5 888,-1024.5 882,-1018.5 882,-1012.5 882,-1012.5 882,-599.5 882,-599.5 882,-593.5 888,-587.5 894,-587.5"/>
<text text-anchor="middle" x="916" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="950,-587.5 950,-1024.5 "/>
<text text-anchor="middle" x="960.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="971,-587.5 971,-1024.5 "/>
<text text-anchor="middle" x="1103.5" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="971,-1001.5 1236,-1001.5 "/>
<text text-anchor="middle" x="1103.5" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="971,-978.5 1236,-978.5 "/>
<text text-anchor="middle" x="1103.5" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="971,-955.5 1236,-955.5 "/>
<text text-anchor="middle" x="1103.5" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="971,-932.5 1236,-932.5 "/>
<text text-anchor="middle" x="1103.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification</text>
<polyline fill="none" stroke="#000000" points="971,-909.5 1236,-909.5 "/>
<text text-anchor="middle" x="1103.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="971,-886.5 1236,-886.5 "/>
<text text-anchor="middle" x="1103.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="971,-863.5 1236,-863.5 "/>
<text text-anchor="middle" x="1103.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_verification_status</text>
<polyline fill="none" stroke="#000000" points="971,-840.5 1236,-840.5 "/>
<text text-anchor="middle" x="1103.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="971,-817.5 1236,-817.5 "/>
<text text-anchor="middle" x="1103.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="971,-794.5 1236,-794.5 "/>
<text text-anchor="middle" x="1103.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="971,-771.5 1236,-771.5 "/>
<text text-anchor="middle" x="1103.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="971,-748.5 1236,-748.5 "/>
<text text-anchor="middle" x="1103.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="971,-725.5 1236,-725.5 "/>
<text text-anchor="middle" x="1103.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="971,-702.5 1236,-702.5 "/>
<text text-anchor="middle" x="1103.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="971,-679.5 1236,-679.5 "/>
<text text-anchor="middle" x="1103.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="971,-656.5 1236,-656.5 "/>
<text text-anchor="middle" x="1103.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="971,-633.5 1236,-633.5 "/>
<text text-anchor="middle" x="1103.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="971,-610.5 1236,-610.5 "/>
<text text-anchor="middle" x="1103.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1236,-587.5 1236,-1024.5 "/>
<text text-anchor="middle" x="1246.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1112.8646,-587.4161C1122.3816,-490.3588 1119.7056,-376.8775 1079.5,-282 1069.291,-257.9087 1053.7008,-235.5969 1035.9937,-215.6464"/>
<polygon fill="#000000" stroke="#000000" points="1038.441,-213.1361 1029.1104,-208.117 1033.2745,-217.8593 1038.441,-213.1361"/>
<text text-anchor="middle" x="1153" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M881.8441,-650.8759C855.0308,-629.2316 827.6724,-607.4232 801.5,-587 751.8641,-548.2675 695.4113,-506.1362 649.8389,-472.5899"/>
<polygon fill="#000000" stroke="#000000" points="651.8815,-469.7474 641.7517,-466.6428 647.7344,-475.3868 651.8815,-469.7474"/>
<text text-anchor="middle" x="812" y="-557.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge1" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M630.2493,-351.364C672.3399,-315.5565 727.8218,-268.3567 778.0883,-225.5937"/>
<polygon fill="#000000" stroke="#000000" points="780.437,-228.1908 785.7858,-219.0453 775.9012,-222.8591 780.437,-228.1908"/>
<text text-anchor="middle" x="795" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- survival -->
<g id="node6" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M419,-737C419,-737 780,-737 780,-737 786,-737 792,-743 792,-749 792,-749 792,-863 792,-863 792,-869 786,-875 780,-875 780,-875 419,-875 419,-875 413,-875 407,-869 407,-863 407,-863 407,-749 407,-749 407,-743 413,-737 419,-737"/>
<text text-anchor="middle" x="444" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="481,-737 481,-875 "/>
<text text-anchor="middle" x="491.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="502,-737 502,-875 "/>
<text text-anchor="middle" x="636.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="502,-852 771,-852 "/>
<text text-anchor="middle" x="636.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="502,-829 771,-829 "/>
<text text-anchor="middle" x="636.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="502,-806 771,-806 "/>
<text text-anchor="middle" x="636.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="502,-783 771,-783 "/>
<text text-anchor="middle" x="636.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="502,-760 771,-760 "/>
<text text-anchor="middle" x="636.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="771,-737 771,-875 "/>
<text text-anchor="middle" x="781.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M593.0551,-736.8479C586.2567,-663.9031 575.6114,-549.6815 568.8493,-477.1265"/>
<polygon fill="#000000" stroke="#000000" points="572.2937,-476.3659 567.8807,-466.7338 565.3239,-477.0155 572.2937,-476.3659"/>
<text text-anchor="middle" x="616" y="-557.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
</g>
</svg>
</div>
