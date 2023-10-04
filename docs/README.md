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
<svg width="1145pt" height="987pt"
 viewBox="0.00 0.00 1145.00 987.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 983)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-983 1141,-983 1141,4 -4,4"/>
<!-- diagnosis -->
<g id="node1" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M12,-645C12,-645 377,-645 377,-645 383,-645 389,-651 389,-657 389,-657 389,-909 389,-909 389,-915 383,-921 377,-921 377,-921 12,-921 12,-921 6,-921 0,-915 0,-909 0,-909 0,-657 0,-657 0,-651 6,-645 12,-645"/>
<text text-anchor="middle" x="42" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="84,-645 84,-921 "/>
<text text-anchor="middle" x="94.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="105,-645 105,-921 "/>
<text text-anchor="middle" x="236.5" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="105,-898 368,-898 "/>
<text text-anchor="middle" x="236.5" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="105,-875 368,-875 "/>
<text text-anchor="middle" x="236.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="105,-852 368,-852 "/>
<text text-anchor="middle" x="236.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="105,-829 368,-829 "/>
<text text-anchor="middle" x="236.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="105,-806 368,-806 "/>
<text text-anchor="middle" x="236.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="105,-783 368,-783 "/>
<text text-anchor="middle" x="236.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="105,-760 368,-760 "/>
<text text-anchor="middle" x="236.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="105,-737 368,-737 "/>
<text text-anchor="middle" x="236.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="105,-714 368,-714 "/>
<text text-anchor="middle" x="236.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="105,-691 368,-691 "/>
<text text-anchor="middle" x="236.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="105,-668 368,-668 "/>
<text text-anchor="middle" x="236.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="368,-645 368,-921 "/>
<text text-anchor="middle" x="378.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node6" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M310.5,-351.5C310.5,-351.5 614.5,-351.5 614.5,-351.5 620.5,-351.5 626.5,-357.5 626.5,-363.5 626.5,-363.5 626.5,-454.5 626.5,-454.5 626.5,-460.5 620.5,-466.5 614.5,-466.5 614.5,-466.5 310.5,-466.5 310.5,-466.5 304.5,-466.5 298.5,-460.5 298.5,-454.5 298.5,-454.5 298.5,-363.5 298.5,-363.5 298.5,-357.5 304.5,-351.5 310.5,-351.5"/>
<text text-anchor="middle" x="346.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="394.5,-351.5 394.5,-466.5 "/>
<text text-anchor="middle" x="405" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="415.5,-351.5 415.5,-466.5 "/>
<text text-anchor="middle" x="510.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="415.5,-443.5 605.5,-443.5 "/>
<text text-anchor="middle" x="510.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="415.5,-420.5 605.5,-420.5 "/>
<text text-anchor="middle" x="510.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="415.5,-397.5 605.5,-397.5 "/>
<text text-anchor="middle" x="510.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="415.5,-374.5 605.5,-374.5 "/>
<text text-anchor="middle" x="510.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="605.5,-351.5 605.5,-466.5 "/>
<text text-anchor="middle" x="616" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M293.5319,-644.7988C335.1679,-586.6948 381.6467,-521.8325 415.3019,-474.866"/>
<polygon fill="#000000" stroke="#000000" points="418.2417,-476.7723 421.2215,-466.6051 412.5517,-472.695 418.2417,-476.7723"/>
<text text-anchor="middle" x="398" y="-557.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- study -->
<g id="node2" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M698,-.5C698,-.5 917,-.5 917,-.5 923,-.5 929,-6.5 929,-12.5 929,-12.5 929,-218.5 929,-218.5 929,-224.5 923,-230.5 917,-230.5 917,-230.5 698,-230.5 698,-230.5 692,-230.5 686,-224.5 686,-218.5 686,-218.5 686,-12.5 686,-12.5 686,-6.5 692,-.5 698,-.5"/>
<text text-anchor="middle" x="714" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="742,-.5 742,-230.5 "/>
<text text-anchor="middle" x="752.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="763,-.5 763,-230.5 "/>
<text text-anchor="middle" x="835.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="763,-207.5 908,-207.5 "/>
<text text-anchor="middle" x="835.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="763,-184.5 908,-184.5 "/>
<text text-anchor="middle" x="835.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="763,-161.5 908,-161.5 "/>
<text text-anchor="middle" x="835.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="763,-138.5 908,-138.5 "/>
<text text-anchor="middle" x="835.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="763,-115.5 908,-115.5 "/>
<text text-anchor="middle" x="835.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="763,-92.5 908,-92.5 "/>
<text text-anchor="middle" x="835.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="763,-69.5 908,-69.5 "/>
<text text-anchor="middle" x="835.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="763,-46.5 908,-46.5 "/>
<text text-anchor="middle" x="835.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="763,-23.5 908,-23.5 "/>
<text text-anchor="middle" x="835.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="908,-.5 908,-230.5 "/>
<text text-anchor="middle" x="918.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file -->
<g id="node3" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M657,-282.5C657,-282.5 958,-282.5 958,-282.5 964,-282.5 970,-288.5 970,-294.5 970,-294.5 970,-523.5 970,-523.5 970,-529.5 964,-535.5 958,-535.5 958,-535.5 657,-535.5 657,-535.5 651,-535.5 645,-529.5 645,-523.5 645,-523.5 645,-294.5 645,-294.5 645,-288.5 651,-282.5 657,-282.5"/>
<text text-anchor="middle" x="703" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="761,-282.5 761,-535.5 "/>
<text text-anchor="middle" x="771.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="782,-282.5 782,-535.5 "/>
<text text-anchor="middle" x="865.5" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="782,-512.5 949,-512.5 "/>
<text text-anchor="middle" x="865.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="782,-489.5 949,-489.5 "/>
<text text-anchor="middle" x="865.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="782,-466.5 949,-466.5 "/>
<text text-anchor="middle" x="865.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="782,-443.5 949,-443.5 "/>
<text text-anchor="middle" x="865.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="782,-420.5 949,-420.5 "/>
<text text-anchor="middle" x="865.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="782,-397.5 949,-397.5 "/>
<text text-anchor="middle" x="865.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="782,-374.5 949,-374.5 "/>
<text text-anchor="middle" x="865.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="782,-351.5 949,-351.5 "/>
<text text-anchor="middle" x="865.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="782,-328.5 949,-328.5 "/>
<text text-anchor="middle" x="865.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="782,-305.5 949,-305.5 "/>
<text text-anchor="middle" x="865.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="949,-282.5 949,-535.5 "/>
<text text-anchor="middle" x="959.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge2" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M807.5,-282.4C807.5,-268.5422 807.5,-254.44 807.5,-240.6005"/>
<polygon fill="#000000" stroke="#000000" points="811.0001,-240.5768 807.5,-230.5768 804.0001,-240.5769 811.0001,-240.5768"/>
<text text-anchor="middle" x="868" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- event -->
<g id="node4" class="node">
<title>event</title>
<path fill="none" stroke="#000000" d="M419,-737C419,-737 620,-737 620,-737 626,-737 632,-743 632,-749 632,-749 632,-817 632,-817 632,-823 626,-829 620,-829 620,-829 419,-829 419,-829 413,-829 407,-823 407,-817 407,-817 407,-749 407,-749 407,-743 413,-737 419,-737"/>
<text text-anchor="middle" x="435" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">event</text>
<polyline fill="none" stroke="#000000" points="463,-737 463,-829 "/>
<text text-anchor="middle" x="473.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="484,-737 484,-829 "/>
<text text-anchor="middle" x="547.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event</text>
<polyline fill="none" stroke="#000000" points="484,-806 611,-806 "/>
<text text-anchor="middle" x="547.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">event_category</text>
<polyline fill="none" stroke="#000000" points="484,-783 611,-783 "/>
<text text-anchor="middle" x="547.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">event_detail</text>
<polyline fill="none" stroke="#000000" points="484,-760 611,-760 "/>
<text text-anchor="middle" x="547.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">event_id</text>
<polyline fill="none" stroke="#000000" points="611,-737 611,-829 "/>
<text text-anchor="middle" x="621.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- event&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>event&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M512.4535,-736.7651C502.5252,-671.6215 484.3523,-552.3817 472.8775,-477.0908"/>
<polygon fill="#000000" stroke="#000000" points="476.2711,-476.1273 471.3043,-466.7688 469.351,-477.182 476.2711,-476.1273"/>
<text text-anchor="middle" x="516" y="-557.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_event</text>
</g>
<!-- sample -->
<g id="node5" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M774,-587.5C774,-587.5 1125,-587.5 1125,-587.5 1131,-587.5 1137,-593.5 1137,-599.5 1137,-599.5 1137,-966.5 1137,-966.5 1137,-972.5 1131,-978.5 1125,-978.5 1125,-978.5 774,-978.5 774,-978.5 768,-978.5 762,-972.5 762,-966.5 762,-966.5 762,-599.5 762,-599.5 762,-593.5 768,-587.5 774,-587.5"/>
<text text-anchor="middle" x="796" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="830,-587.5 830,-978.5 "/>
<text text-anchor="middle" x="840.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="851,-587.5 851,-978.5 "/>
<text text-anchor="middle" x="983.5" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="851,-955.5 1116,-955.5 "/>
<text text-anchor="middle" x="983.5" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="851,-932.5 1116,-932.5 "/>
<text text-anchor="middle" x="983.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="851,-909.5 1116,-909.5 "/>
<text text-anchor="middle" x="983.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="851,-886.5 1116,-886.5 "/>
<text text-anchor="middle" x="983.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="851,-863.5 1116,-863.5 "/>
<text text-anchor="middle" x="983.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="851,-840.5 1116,-840.5 "/>
<text text-anchor="middle" x="983.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="851,-817.5 1116,-817.5 "/>
<text text-anchor="middle" x="983.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="851,-794.5 1116,-794.5 "/>
<text text-anchor="middle" x="983.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="851,-771.5 1116,-771.5 "/>
<text text-anchor="middle" x="983.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="851,-748.5 1116,-748.5 "/>
<text text-anchor="middle" x="983.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="851,-725.5 1116,-725.5 "/>
<text text-anchor="middle" x="983.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="851,-702.5 1116,-702.5 "/>
<text text-anchor="middle" x="983.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="851,-679.5 1116,-679.5 "/>
<text text-anchor="middle" x="983.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="851,-656.5 1116,-656.5 "/>
<text text-anchor="middle" x="983.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="851,-633.5 1116,-633.5 "/>
<text text-anchor="middle" x="983.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="851,-610.5 1116,-610.5 "/>
<text text-anchor="middle" x="983.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1116,-587.5 1116,-978.5 "/>
<text text-anchor="middle" x="1126.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1000.9856,-587.2456C1016.3423,-491.7166 1019.8301,-377.1713 979.5,-282 969.291,-257.9087 953.7008,-235.5969 935.9937,-215.6464"/>
<polygon fill="#000000" stroke="#000000" points="938.441,-213.1361 929.1104,-208.117 933.2745,-217.8593 938.441,-213.1361"/>
<text text-anchor="middle" x="1048" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M761.9097,-638.9368C687.1834,-581.5494 605.0308,-518.459 545.7127,-472.9046"/>
<polygon fill="#000000" stroke="#000000" points="547.5603,-469.9105 537.4974,-466.5955 543.2967,-475.4622 547.5603,-469.9105"/>
<text text-anchor="middle" x="698" y="-557.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge4" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M530.2493,-351.364C572.3399,-315.5565 627.8218,-268.3567 678.0883,-225.5937"/>
<polygon fill="#000000" stroke="#000000" points="680.437,-228.1908 685.7858,-219.0453 675.9012,-222.8591 680.437,-228.1908"/>
<text text-anchor="middle" x="695" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
</g>
</svg>
</div>
