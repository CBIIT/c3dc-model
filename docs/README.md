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
<svg width="1019pt" height="1010pt"
 viewBox="0.00 0.00 1019.00 1010.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1006)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1006 1015,-1006 1015,4 -4,4"/>
<!-- study -->
<g id="node1" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M305,-.5C305,-.5 524,-.5 524,-.5 530,-.5 536,-6.5 536,-12.5 536,-12.5 536,-218.5 536,-218.5 536,-224.5 530,-230.5 524,-230.5 524,-230.5 305,-230.5 305,-230.5 299,-230.5 293,-224.5 293,-218.5 293,-218.5 293,-12.5 293,-12.5 293,-6.5 299,-.5 305,-.5"/>
<text text-anchor="middle" x="321" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="349,-.5 349,-230.5 "/>
<text text-anchor="middle" x="359.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="370,-.5 370,-230.5 "/>
<text text-anchor="middle" x="442.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="370,-207.5 515,-207.5 "/>
<text text-anchor="middle" x="442.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="370,-184.5 515,-184.5 "/>
<text text-anchor="middle" x="442.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="370,-161.5 515,-161.5 "/>
<text text-anchor="middle" x="442.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="370,-138.5 515,-138.5 "/>
<text text-anchor="middle" x="442.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="370,-115.5 515,-115.5 "/>
<text text-anchor="middle" x="442.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="370,-92.5 515,-92.5 "/>
<text text-anchor="middle" x="442.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="370,-69.5 515,-69.5 "/>
<text text-anchor="middle" x="442.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="370,-46.5 515,-46.5 "/>
<text text-anchor="middle" x="442.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="370,-23.5 515,-23.5 "/>
<text text-anchor="middle" x="442.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="515,-.5 515,-230.5 "/>
<text text-anchor="middle" x="525.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis -->
<g id="node2" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M632,-633.5C632,-633.5 999,-633.5 999,-633.5 1005,-633.5 1011,-639.5 1011,-645.5 1011,-645.5 1011,-966.5 1011,-966.5 1011,-972.5 1005,-978.5 999,-978.5 999,-978.5 632,-978.5 632,-978.5 626,-978.5 620,-972.5 620,-966.5 620,-966.5 620,-645.5 620,-645.5 620,-639.5 626,-633.5 632,-633.5"/>
<text text-anchor="middle" x="662" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="704,-633.5 704,-978.5 "/>
<text text-anchor="middle" x="714.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="725,-633.5 725,-978.5 "/>
<text text-anchor="middle" x="857.5" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="725,-955.5 990,-955.5 "/>
<text text-anchor="middle" x="857.5" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="725,-932.5 990,-932.5 "/>
<text text-anchor="middle" x="857.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_recurrence</text>
<polyline fill="none" stroke="#000000" points="725,-909.5 990,-909.5 "/>
<text text-anchor="middle" x="857.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="725,-886.5 990,-886.5 "/>
<text text-anchor="middle" x="857.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="725,-863.5 990,-863.5 "/>
<text text-anchor="middle" x="857.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="725,-840.5 990,-840.5 "/>
<text text-anchor="middle" x="857.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="725,-817.5 990,-817.5 "/>
<text text-anchor="middle" x="857.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="725,-794.5 990,-794.5 "/>
<text text-anchor="middle" x="857.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="725,-771.5 990,-771.5 "/>
<text text-anchor="middle" x="857.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="725,-748.5 990,-748.5 "/>
<text text-anchor="middle" x="857.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="725,-725.5 990,-725.5 "/>
<text text-anchor="middle" x="857.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="725,-702.5 990,-702.5 "/>
<text text-anchor="middle" x="857.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="725,-679.5 990,-679.5 "/>
<text text-anchor="middle" x="857.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="725,-656.5 990,-656.5 "/>
<text text-anchor="middle" x="857.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="990,-633.5 990,-978.5 "/>
<text text-anchor="middle" x="1000.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node5" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M517.5,-363C517.5,-363 821.5,-363 821.5,-363 827.5,-363 833.5,-369 833.5,-375 833.5,-375 833.5,-466 833.5,-466 833.5,-472 827.5,-478 821.5,-478 821.5,-478 517.5,-478 517.5,-478 511.5,-478 505.5,-472 505.5,-466 505.5,-466 505.5,-375 505.5,-375 505.5,-369 511.5,-363 517.5,-363"/>
<text text-anchor="middle" x="553.5" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="601.5,-363 601.5,-478 "/>
<text text-anchor="middle" x="612" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="622.5,-363 622.5,-478 "/>
<text text-anchor="middle" x="717.5" y="-462.8" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="622.5,-455 812.5,-455 "/>
<text text-anchor="middle" x="717.5" y="-439.8" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="622.5,-432 812.5,-432 "/>
<text text-anchor="middle" x="717.5" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="622.5,-409 812.5,-409 "/>
<text text-anchor="middle" x="717.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="622.5,-386 812.5,-386 "/>
<text text-anchor="middle" x="717.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="812.5,-363 812.5,-478 "/>
<text text-anchor="middle" x="823" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M750.0801,-633.2646C730.5548,-581.7099 710.2983,-528.2244 694.9793,-487.7759"/>
<polygon fill="#000000" stroke="#000000" points="698.2081,-486.419 691.3931,-478.3069 691.6619,-488.8983 698.2081,-486.419"/>
<text text-anchor="middle" x="778" y="-580.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- reference_file -->
<g id="node3" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M12,-282.5C12,-282.5 367,-282.5 367,-282.5 373,-282.5 379,-288.5 379,-294.5 379,-294.5 379,-546.5 379,-546.5 379,-552.5 373,-558.5 367,-558.5 367,-558.5 12,-558.5 12,-558.5 6,-558.5 0,-552.5 0,-546.5 0,-546.5 0,-294.5 0,-294.5 0,-288.5 6,-282.5 12,-282.5"/>
<text text-anchor="middle" x="58" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="116,-282.5 116,-558.5 "/>
<text text-anchor="middle" x="126.5" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="137,-282.5 137,-558.5 "/>
<text text-anchor="middle" x="247.5" y="-543.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="137,-535.5 358,-535.5 "/>
<text text-anchor="middle" x="247.5" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="137,-512.5 358,-512.5 "/>
<text text-anchor="middle" x="247.5" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="137,-489.5 358,-489.5 "/>
<text text-anchor="middle" x="247.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="137,-466.5 358,-466.5 "/>
<text text-anchor="middle" x="247.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="137,-443.5 358,-443.5 "/>
<text text-anchor="middle" x="247.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="137,-420.5 358,-420.5 "/>
<text text-anchor="middle" x="247.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="137,-397.5 358,-397.5 "/>
<text text-anchor="middle" x="247.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">mapping_documentation_url</text>
<polyline fill="none" stroke="#000000" points="137,-374.5 358,-374.5 "/>
<text text-anchor="middle" x="247.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="137,-351.5 358,-351.5 "/>
<text text-anchor="middle" x="247.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="137,-328.5 358,-328.5 "/>
<text text-anchor="middle" x="247.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">source_code_url</text>
<polyline fill="none" stroke="#000000" points="137,-305.5 358,-305.5 "/>
<text text-anchor="middle" x="247.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">source_file_url</text>
<polyline fill="none" stroke="#000000" points="358,-282.5 358,-558.5 "/>
<text text-anchor="middle" x="368.5" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge3" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M257.0539,-282.4498C264.1856,-270.8505 271.6987,-259.541 279.5,-249 282.0369,-245.5722 284.6622,-242.1499 287.3604,-238.7413"/>
<polygon fill="#000000" stroke="#000000" points="290.2053,-240.7897 293.7814,-230.8166 284.7666,-236.3829 290.2053,-240.7897"/>
<text text-anchor="middle" x="340" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- sample -->
<g id="node4" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M239,-610.5C239,-610.5 590,-610.5 590,-610.5 596,-610.5 602,-616.5 602,-622.5 602,-622.5 602,-989.5 602,-989.5 602,-995.5 596,-1001.5 590,-1001.5 590,-1001.5 239,-1001.5 239,-1001.5 233,-1001.5 227,-995.5 227,-989.5 227,-989.5 227,-622.5 227,-622.5 227,-616.5 233,-610.5 239,-610.5"/>
<text text-anchor="middle" x="261" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="295,-610.5 295,-1001.5 "/>
<text text-anchor="middle" x="305.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="316,-610.5 316,-1001.5 "/>
<text text-anchor="middle" x="448.5" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="316,-978.5 581,-978.5 "/>
<text text-anchor="middle" x="448.5" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="316,-955.5 581,-955.5 "/>
<text text-anchor="middle" x="448.5" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="316,-932.5 581,-932.5 "/>
<text text-anchor="middle" x="448.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="316,-909.5 581,-909.5 "/>
<text text-anchor="middle" x="448.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="316,-886.5 581,-886.5 "/>
<text text-anchor="middle" x="448.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="316,-863.5 581,-863.5 "/>
<text text-anchor="middle" x="448.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="316,-840.5 581,-840.5 "/>
<text text-anchor="middle" x="448.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="316,-817.5 581,-817.5 "/>
<text text-anchor="middle" x="448.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="316,-794.5 581,-794.5 "/>
<text text-anchor="middle" x="448.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="316,-771.5 581,-771.5 "/>
<text text-anchor="middle" x="448.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="316,-748.5 581,-748.5 "/>
<text text-anchor="middle" x="448.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="316,-725.5 581,-725.5 "/>
<text text-anchor="middle" x="448.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="316,-702.5 581,-702.5 "/>
<text text-anchor="middle" x="448.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="316,-679.5 581,-679.5 "/>
<text text-anchor="middle" x="448.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="316,-656.5 581,-656.5 "/>
<text text-anchor="middle" x="448.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="316,-633.5 581,-633.5 "/>
<text text-anchor="middle" x="448.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="581,-610.5 581,-1001.5 "/>
<text text-anchor="middle" x="591.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge1" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M414.5,-610.4384C414.5,-491.771 414.5,-343.8451 414.5,-240.762"/>
<polygon fill="#000000" stroke="#000000" points="418.0001,-240.616 414.5,-230.616 411.0001,-240.616 418.0001,-240.616"/>
<text text-anchor="middle" x="451" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M543.8676,-610.4266C573.4173,-565.7545 602.8331,-521.2846 625.7645,-486.6178"/>
<polygon fill="#000000" stroke="#000000" points="628.853,-488.2926 631.4509,-478.0212 623.0147,-484.4307 628.853,-488.2926"/>
<text text-anchor="middle" x="601" y="-580.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge5" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M621.2367,-362.7733C591.8833,-327.6643 553.2467,-281.452 517.3267,-238.4888"/>
<polygon fill="#000000" stroke="#000000" points="519.988,-236.2152 510.8886,-230.7883 514.6177,-240.7052 519.988,-236.2152"/>
<text text-anchor="middle" x="584" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
</g>
</svg>
</div>
