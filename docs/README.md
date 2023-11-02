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
<svg width="1193pt" height="1033pt"
 viewBox="0.00 0.00 1193.00 1033.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1029)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1029 1189,-1029 1189,4 -4,4"/>
<!-- reference_file -->
<g id="node1" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M177,-282.5C177,-282.5 478,-282.5 478,-282.5 484,-282.5 490,-288.5 490,-294.5 490,-294.5 490,-523.5 490,-523.5 490,-529.5 484,-535.5 478,-535.5 478,-535.5 177,-535.5 177,-535.5 171,-535.5 165,-529.5 165,-523.5 165,-523.5 165,-294.5 165,-294.5 165,-288.5 171,-282.5 177,-282.5"/>
<text text-anchor="middle" x="223" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="281,-282.5 281,-535.5 "/>
<text text-anchor="middle" x="291.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="302,-282.5 302,-535.5 "/>
<text text-anchor="middle" x="385.5" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="302,-512.5 469,-512.5 "/>
<text text-anchor="middle" x="385.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="302,-489.5 469,-489.5 "/>
<text text-anchor="middle" x="385.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="302,-466.5 469,-466.5 "/>
<text text-anchor="middle" x="385.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="302,-443.5 469,-443.5 "/>
<text text-anchor="middle" x="385.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="302,-420.5 469,-420.5 "/>
<text text-anchor="middle" x="385.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="302,-397.5 469,-397.5 "/>
<text text-anchor="middle" x="385.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="302,-374.5 469,-374.5 "/>
<text text-anchor="middle" x="385.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="302,-351.5 469,-351.5 "/>
<text text-anchor="middle" x="385.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="302,-328.5 469,-328.5 "/>
<text text-anchor="middle" x="385.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="302,-305.5 469,-305.5 "/>
<text text-anchor="middle" x="385.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="469,-282.5 469,-535.5 "/>
<text text-anchor="middle" x="479.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node3" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M563,-.5C563,-.5 782,-.5 782,-.5 788,-.5 794,-6.5 794,-12.5 794,-12.5 794,-218.5 794,-218.5 794,-224.5 788,-230.5 782,-230.5 782,-230.5 563,-230.5 563,-230.5 557,-230.5 551,-224.5 551,-218.5 551,-218.5 551,-12.5 551,-12.5 551,-6.5 557,-.5 563,-.5"/>
<text text-anchor="middle" x="579" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="607,-.5 607,-230.5 "/>
<text text-anchor="middle" x="617.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="628,-.5 628,-230.5 "/>
<text text-anchor="middle" x="700.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="628,-207.5 773,-207.5 "/>
<text text-anchor="middle" x="700.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="628,-184.5 773,-184.5 "/>
<text text-anchor="middle" x="700.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="628,-161.5 773,-161.5 "/>
<text text-anchor="middle" x="700.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="628,-138.5 773,-138.5 "/>
<text text-anchor="middle" x="700.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="628,-115.5 773,-115.5 "/>
<text text-anchor="middle" x="700.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="628,-92.5 773,-92.5 "/>
<text text-anchor="middle" x="700.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="628,-69.5 773,-69.5 "/>
<text text-anchor="middle" x="700.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="628,-46.5 773,-46.5 "/>
<text text-anchor="middle" x="700.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="628,-23.5 773,-23.5 "/>
<text text-anchor="middle" x="700.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="773,-.5 773,-230.5 "/>
<text text-anchor="middle" x="783.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge6" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M476.3143,-282.4C498.5824,-263.456 521.3873,-244.0553 543.2065,-225.4932"/>
<polygon fill="#000000" stroke="#000000" points="545.5318,-228.1102 550.8806,-218.9646 540.996,-222.7785 545.5318,-228.1102"/>
<text text-anchor="middle" x="571" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- survival -->
<g id="node2" class="node">
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
<g id="node5" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M520.5,-351.5C520.5,-351.5 824.5,-351.5 824.5,-351.5 830.5,-351.5 836.5,-357.5 836.5,-363.5 836.5,-363.5 836.5,-454.5 836.5,-454.5 836.5,-460.5 830.5,-466.5 824.5,-466.5 824.5,-466.5 520.5,-466.5 520.5,-466.5 514.5,-466.5 508.5,-460.5 508.5,-454.5 508.5,-454.5 508.5,-363.5 508.5,-363.5 508.5,-357.5 514.5,-351.5 520.5,-351.5"/>
<text text-anchor="middle" x="556.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="604.5,-351.5 604.5,-466.5 "/>
<text text-anchor="middle" x="615" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="625.5,-351.5 625.5,-466.5 "/>
<text text-anchor="middle" x="720.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="625.5,-443.5 815.5,-443.5 "/>
<text text-anchor="middle" x="720.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="625.5,-420.5 815.5,-420.5 "/>
<text text-anchor="middle" x="720.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="625.5,-397.5 815.5,-397.5 "/>
<text text-anchor="middle" x="720.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="625.5,-374.5 815.5,-374.5 "/>
<text text-anchor="middle" x="720.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="815.5,-351.5 815.5,-466.5 "/>
<text text-anchor="middle" x="826" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M244.4338,-736.9273C282.0476,-690.2945 336.1776,-629.6961 393.5,-587 435.107,-556.0094 454.0374,-562.7326 498.5,-536 529.8601,-517.1451 562.6656,-494.1515 591.2307,-472.9369"/>
<polygon fill="#000000" stroke="#000000" points="593.6451,-475.5019 599.5604,-466.7122 589.4549,-469.8946 593.6451,-475.5019"/>
<text text-anchor="middle" x="500" y="-557.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- diagnosis -->
<g id="node4" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M415,-645C415,-645 780,-645 780,-645 786,-645 792,-651 792,-657 792,-657 792,-955 792,-955 792,-961 786,-967 780,-967 780,-967 415,-967 415,-967 409,-967 403,-961 403,-955 403,-955 403,-657 403,-657 403,-651 409,-645 415,-645"/>
<text text-anchor="middle" x="445" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="487,-645 487,-967 "/>
<text text-anchor="middle" x="497.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="508,-645 508,-967 "/>
<text text-anchor="middle" x="639.5" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="508,-944 771,-944 "/>
<text text-anchor="middle" x="639.5" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="508,-921 771,-921 "/>
<text text-anchor="middle" x="639.5" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="508,-898 771,-898 "/>
<text text-anchor="middle" x="639.5" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification</text>
<polyline fill="none" stroke="#000000" points="508,-875 771,-875 "/>
<text text-anchor="middle" x="639.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="508,-852 771,-852 "/>
<text text-anchor="middle" x="639.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="508,-829 771,-829 "/>
<text text-anchor="middle" x="639.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="508,-806 771,-806 "/>
<text text-anchor="middle" x="639.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_verification_status</text>
<polyline fill="none" stroke="#000000" points="508,-783 771,-783 "/>
<text text-anchor="middle" x="639.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="508,-760 771,-760 "/>
<text text-anchor="middle" x="639.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="508,-737 771,-737 "/>
<text text-anchor="middle" x="639.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="508,-714 771,-714 "/>
<text text-anchor="middle" x="639.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="508,-691 771,-691 "/>
<text text-anchor="middle" x="639.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="508,-668 771,-668 "/>
<text text-anchor="middle" x="639.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="771,-645 771,-967 "/>
<text text-anchor="middle" x="781.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M627.9513,-644.8111C639.0285,-586.1759 650.9569,-523.0349 659.6802,-476.8594"/>
<polygon fill="#000000" stroke="#000000" points="663.1298,-477.4534 661.5471,-466.9774 656.2515,-476.1539 663.1298,-477.4534"/>
<text text-anchor="middle" x="689" y="-557.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge5" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M672.5,-351.364C672.5,-319.7948 672.5,-279.3705 672.5,-240.9387"/>
<polygon fill="#000000" stroke="#000000" points="676.0001,-240.6911 672.5,-230.6911 669.0001,-240.6912 676.0001,-240.6911"/>
<text text-anchor="middle" x="723" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample -->
<g id="node6" class="node">
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
<!-- sample&#45;&gt;study -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M960.8464,-587.4676C937.8234,-489.1976 901.5196,-374.7311 845.5,-282 833.2409,-261.707 817.8899,-242.2128 801.4259,-224.1639"/>
<polygon fill="#000000" stroke="#000000" points="803.6837,-221.4526 794.3076,-216.5191 798.5606,-226.2228 803.6837,-221.4526"/>
<text text-anchor="middle" x="983" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M818.6003,-587.4671C784.9178,-546.3227 752.1848,-506.3381 726.2693,-474.6813"/>
<polygon fill="#000000" stroke="#000000" points="728.8739,-472.3376 719.8311,-466.8168 723.4574,-476.7717 728.8739,-472.3376"/>
<text text-anchor="middle" x="833" y="-557.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
</g>
</svg>
</div>
