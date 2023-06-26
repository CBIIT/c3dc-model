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
<svg width="903pt" height="964pt"
 viewBox="0.00 0.00 903.00 964.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 960)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-960 899,-960 899,4 -4,4"/>
<!-- study -->
<g id="node1" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M398,-.5C398,-.5 617,-.5 617,-.5 623,-.5 629,-6.5 629,-12.5 629,-12.5 629,-218.5 629,-218.5 629,-224.5 623,-230.5 617,-230.5 617,-230.5 398,-230.5 398,-230.5 392,-230.5 386,-224.5 386,-218.5 386,-218.5 386,-12.5 386,-12.5 386,-6.5 392,-.5 398,-.5"/>
<text text-anchor="middle" x="414" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="442,-.5 442,-230.5 "/>
<text text-anchor="middle" x="452.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="463,-.5 463,-230.5 "/>
<text text-anchor="middle" x="535.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="463,-207.5 608,-207.5 "/>
<text text-anchor="middle" x="535.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="463,-184.5 608,-184.5 "/>
<text text-anchor="middle" x="535.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="463,-161.5 608,-161.5 "/>
<text text-anchor="middle" x="535.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="463,-138.5 608,-138.5 "/>
<text text-anchor="middle" x="535.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="463,-115.5 608,-115.5 "/>
<text text-anchor="middle" x="535.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="463,-92.5 608,-92.5 "/>
<text text-anchor="middle" x="535.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="463,-69.5 608,-69.5 "/>
<text text-anchor="middle" x="535.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="463,-46.5 608,-46.5 "/>
<text text-anchor="middle" x="535.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="463,-23.5 608,-23.5 "/>
<text text-anchor="middle" x="535.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="608,-.5 608,-230.5 "/>
<text text-anchor="middle" x="618.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file -->
<g id="node2" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M12,-282.5C12,-282.5 313,-282.5 313,-282.5 319,-282.5 325,-288.5 325,-294.5 325,-294.5 325,-500.5 325,-500.5 325,-506.5 319,-512.5 313,-512.5 313,-512.5 12,-512.5 12,-512.5 6,-512.5 0,-506.5 0,-500.5 0,-500.5 0,-294.5 0,-294.5 0,-288.5 6,-282.5 12,-282.5"/>
<text text-anchor="middle" x="58" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="116,-282.5 116,-512.5 "/>
<text text-anchor="middle" x="126.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="137,-282.5 137,-512.5 "/>
<text text-anchor="middle" x="220.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="137,-489.5 304,-489.5 "/>
<text text-anchor="middle" x="220.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="137,-466.5 304,-466.5 "/>
<text text-anchor="middle" x="220.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="137,-443.5 304,-443.5 "/>
<text text-anchor="middle" x="220.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="137,-420.5 304,-420.5 "/>
<text text-anchor="middle" x="220.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="137,-397.5 304,-397.5 "/>
<text text-anchor="middle" x="220.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="137,-374.5 304,-374.5 "/>
<text text-anchor="middle" x="220.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="137,-351.5 304,-351.5 "/>
<text text-anchor="middle" x="220.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="137,-328.5 304,-328.5 "/>
<text text-anchor="middle" x="220.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="137,-305.5 304,-305.5 "/>
<text text-anchor="middle" x="220.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="304,-282.5 304,-512.5 "/>
<text text-anchor="middle" x="314.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge4" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M303.3223,-282.3931C328.0367,-262.1917 353.6496,-241.256 378.0365,-221.3223"/>
<polygon fill="#000000" stroke="#000000" points="380.381,-223.9264 385.9086,-214.8878 375.9509,-218.5066 380.381,-223.9264"/>
<text text-anchor="middle" x="396" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- participant -->
<g id="node3" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M355.5,-340C355.5,-340 659.5,-340 659.5,-340 665.5,-340 671.5,-346 671.5,-352 671.5,-352 671.5,-443 671.5,-443 671.5,-449 665.5,-455 659.5,-455 659.5,-455 355.5,-455 355.5,-455 349.5,-455 343.5,-449 343.5,-443 343.5,-443 343.5,-352 343.5,-352 343.5,-346 349.5,-340 355.5,-340"/>
<text text-anchor="middle" x="391.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="439.5,-340 439.5,-455 "/>
<text text-anchor="middle" x="450" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="460.5,-340 460.5,-455 "/>
<text text-anchor="middle" x="555.5" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="460.5,-432 650.5,-432 "/>
<text text-anchor="middle" x="555.5" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="460.5,-409 650.5,-409 "/>
<text text-anchor="middle" x="555.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="460.5,-386 650.5,-386 "/>
<text text-anchor="middle" x="555.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="460.5,-363 650.5,-363 "/>
<text text-anchor="middle" x="555.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="650.5,-340 650.5,-455 "/>
<text text-anchor="middle" x="661" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge3" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M507.5,-339.7526C507.5,-311.0804 507.5,-275.2524 507.5,-240.7054"/>
<polygon fill="#000000" stroke="#000000" points="511.0001,-240.5203 507.5,-230.5203 504.0001,-240.5204 511.0001,-240.5203"/>
<text text-anchor="middle" x="558" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- diagnosis -->
<g id="node4" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M123,-587.5C123,-587.5 490,-587.5 490,-587.5 496,-587.5 502,-593.5 502,-599.5 502,-599.5 502,-920.5 502,-920.5 502,-926.5 496,-932.5 490,-932.5 490,-932.5 123,-932.5 123,-932.5 117,-932.5 111,-926.5 111,-920.5 111,-920.5 111,-599.5 111,-599.5 111,-593.5 117,-587.5 123,-587.5"/>
<text text-anchor="middle" x="153" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="195,-587.5 195,-932.5 "/>
<text text-anchor="middle" x="205.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="216,-587.5 216,-932.5 "/>
<text text-anchor="middle" x="348.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="216,-909.5 481,-909.5 "/>
<text text-anchor="middle" x="348.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="216,-886.5 481,-886.5 "/>
<text text-anchor="middle" x="348.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_recurrence</text>
<polyline fill="none" stroke="#000000" points="216,-863.5 481,-863.5 "/>
<text text-anchor="middle" x="348.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="216,-840.5 481,-840.5 "/>
<text text-anchor="middle" x="348.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="216,-817.5 481,-817.5 "/>
<text text-anchor="middle" x="348.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="216,-794.5 481,-794.5 "/>
<text text-anchor="middle" x="348.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="216,-771.5 481,-771.5 "/>
<text text-anchor="middle" x="348.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="216,-748.5 481,-748.5 "/>
<text text-anchor="middle" x="348.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="216,-725.5 481,-725.5 "/>
<text text-anchor="middle" x="348.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="216,-702.5 481,-702.5 "/>
<text text-anchor="middle" x="348.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="216,-679.5 481,-679.5 "/>
<text text-anchor="middle" x="348.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="216,-656.5 481,-656.5 "/>
<text text-anchor="middle" x="348.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="216,-633.5 481,-633.5 "/>
<text text-anchor="middle" x="348.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="216,-610.5 481,-610.5 "/>
<text text-anchor="middle" x="348.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="481,-587.5 481,-932.5 "/>
<text text-anchor="middle" x="491.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M402.2906,-587.2433C426.5162,-543.5529 451.1074,-499.203 470.4173,-464.378"/>
<polygon fill="#000000" stroke="#000000" points="473.6751,-465.7202 475.4635,-455.2773 467.5532,-462.3256 473.6751,-465.7202"/>
<text text-anchor="middle" x="476" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample -->
<g id="node5" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M532,-564.5C532,-564.5 883,-564.5 883,-564.5 889,-564.5 895,-570.5 895,-576.5 895,-576.5 895,-943.5 895,-943.5 895,-949.5 889,-955.5 883,-955.5 883,-955.5 532,-955.5 532,-955.5 526,-955.5 520,-949.5 520,-943.5 520,-943.5 520,-576.5 520,-576.5 520,-570.5 526,-564.5 532,-564.5"/>
<text text-anchor="middle" x="554" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="588,-564.5 588,-955.5 "/>
<text text-anchor="middle" x="598.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="609,-564.5 609,-955.5 "/>
<text text-anchor="middle" x="741.5" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="609,-932.5 874,-932.5 "/>
<text text-anchor="middle" x="741.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="609,-909.5 874,-909.5 "/>
<text text-anchor="middle" x="741.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="609,-886.5 874,-886.5 "/>
<text text-anchor="middle" x="741.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="609,-863.5 874,-863.5 "/>
<text text-anchor="middle" x="741.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="609,-840.5 874,-840.5 "/>
<text text-anchor="middle" x="741.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="609,-817.5 874,-817.5 "/>
<text text-anchor="middle" x="741.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="609,-794.5 874,-794.5 "/>
<text text-anchor="middle" x="741.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="609,-771.5 874,-771.5 "/>
<text text-anchor="middle" x="741.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="609,-748.5 874,-748.5 "/>
<text text-anchor="middle" x="741.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="609,-725.5 874,-725.5 "/>
<text text-anchor="middle" x="741.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="609,-702.5 874,-702.5 "/>
<text text-anchor="middle" x="741.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="609,-679.5 874,-679.5 "/>
<text text-anchor="middle" x="741.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="609,-656.5 874,-656.5 "/>
<text text-anchor="middle" x="741.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="609,-633.5 874,-633.5 "/>
<text text-anchor="middle" x="741.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="609,-610.5 874,-610.5 "/>
<text text-anchor="middle" x="741.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="609,-587.5 874,-587.5 "/>
<text text-anchor="middle" x="741.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="874,-564.5 874,-955.5 "/>
<text text-anchor="middle" x="884.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M728.2419,-564.3536C729.93,-474.6045 720.4758,-369.0541 680.5,-282 669.6253,-258.3186 653.7456,-236.2743 635.9537,-216.4799"/>
<polygon fill="#000000" stroke="#000000" points="638.4044,-213.9748 629.0476,-209.0049 633.2629,-218.7251 638.4044,-213.9748"/>
<text text-anchor="middle" x="765" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M599.5972,-564.4261C579.7027,-528.3674 560.228,-493.0695 544.3491,-464.289"/>
<polygon fill="#000000" stroke="#000000" points="547.2193,-462.246 539.324,-455.181 541.0903,-465.6276 547.2193,-462.246"/>
<text text-anchor="middle" x="621" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
</g>
</svg>
</div>
