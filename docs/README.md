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
<!-- reference_file -->
<g id="node1" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M255,-259.5C255,-259.5 532,-259.5 532,-259.5 538,-259.5 544,-265.5 544,-271.5 544,-271.5 544,-454.5 544,-454.5 544,-460.5 538,-466.5 532,-466.5 532,-466.5 255,-466.5 255,-466.5 249,-466.5 243,-460.5 243,-454.5 243,-454.5 243,-271.5 243,-271.5 243,-265.5 249,-259.5 255,-259.5"/>
<text text-anchor="middle" x="301" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="359,-259.5 359,-466.5 "/>
<text text-anchor="middle" x="369.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="380,-259.5 380,-466.5 "/>
<text text-anchor="middle" x="451.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="380,-443.5 523,-443.5 "/>
<text text-anchor="middle" x="451.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="380,-420.5 523,-420.5 "/>
<text text-anchor="middle" x="451.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="380,-397.5 523,-397.5 "/>
<text text-anchor="middle" x="451.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="380,-374.5 523,-374.5 "/>
<text text-anchor="middle" x="451.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="380,-351.5 523,-351.5 "/>
<text text-anchor="middle" x="451.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="380,-328.5 523,-328.5 "/>
<text text-anchor="middle" x="451.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="380,-305.5 523,-305.5 "/>
<text text-anchor="middle" x="451.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="380,-282.5 523,-282.5 "/>
<text text-anchor="middle" x="451.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="523,-259.5 523,-466.5 "/>
<text text-anchor="middle" x="533.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node5" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M580,-.5C580,-.5 799,-.5 799,-.5 805,-.5 811,-6.5 811,-12.5 811,-12.5 811,-195.5 811,-195.5 811,-201.5 805,-207.5 799,-207.5 799,-207.5 580,-207.5 580,-207.5 574,-207.5 568,-201.5 568,-195.5 568,-195.5 568,-12.5 568,-12.5 568,-6.5 574,-.5 580,-.5"/>
<text text-anchor="middle" x="596" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="624,-.5 624,-207.5 "/>
<text text-anchor="middle" x="634.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="645,-.5 645,-207.5 "/>
<text text-anchor="middle" x="717.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="645,-184.5 790,-184.5 "/>
<text text-anchor="middle" x="717.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="645,-161.5 790,-161.5 "/>
<text text-anchor="middle" x="717.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="645,-138.5 790,-138.5 "/>
<text text-anchor="middle" x="717.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="645,-115.5 790,-115.5 "/>
<text text-anchor="middle" x="717.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="645,-92.5 790,-92.5 "/>
<text text-anchor="middle" x="717.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="645,-69.5 790,-69.5 "/>
<text text-anchor="middle" x="717.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="645,-46.5 790,-46.5 "/>
<text text-anchor="middle" x="717.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="645,-23.5 790,-23.5 "/>
<text text-anchor="middle" x="717.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="790,-.5 790,-207.5 "/>
<text text-anchor="middle" x="800.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge3" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M512.189,-259.1471C528.9263,-244.502 546.1846,-229.401 563.0607,-214.6344"/>
<polygon fill="#000000" stroke="#000000" points="565.5634,-217.0953 570.7844,-207.8762 560.9538,-211.8272 565.5634,-217.0953"/>
<text text-anchor="middle" x="602" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- diagnosis -->
<g id="node2" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M12,-530C12,-530 377,-530 377,-530 383,-530 389,-536 389,-542 389,-542 389,-840 389,-840 389,-846 383,-852 377,-852 377,-852 12,-852 12,-852 6,-852 0,-846 0,-840 0,-840 0,-542 0,-542 0,-536 6,-530 12,-530"/>
<text text-anchor="middle" x="42" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="84,-530 84,-852 "/>
<text text-anchor="middle" x="94.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="105,-530 105,-852 "/>
<text text-anchor="middle" x="236.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="105,-829 368,-829 "/>
<text text-anchor="middle" x="236.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="105,-806 368,-806 "/>
<text text-anchor="middle" x="236.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="105,-783 368,-783 "/>
<text text-anchor="middle" x="236.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification</text>
<polyline fill="none" stroke="#000000" points="105,-760 368,-760 "/>
<text text-anchor="middle" x="236.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="105,-737 368,-737 "/>
<text text-anchor="middle" x="236.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="105,-714 368,-714 "/>
<text text-anchor="middle" x="236.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="105,-691 368,-691 "/>
<text text-anchor="middle" x="236.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="105,-668 368,-668 "/>
<text text-anchor="middle" x="236.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="105,-645 368,-645 "/>
<text text-anchor="middle" x="236.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="105,-622 368,-622 "/>
<text text-anchor="middle" x="236.5" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="105,-599 368,-599 "/>
<text text-anchor="middle" x="236.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="105,-576 368,-576 "/>
<text text-anchor="middle" x="236.5" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="105,-553 368,-553 "/>
<text text-anchor="middle" x="236.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="368,-530 368,-852 "/>
<text text-anchor="middle" x="378.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node3" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M574,-317C574,-317 805,-317 805,-317 811,-317 817,-323 817,-329 817,-329 817,-397 817,-397 817,-403 811,-409 805,-409 805,-409 574,-409 574,-409 568,-409 562,-403 562,-397 562,-397 562,-329 562,-329 562,-323 568,-317 574,-317"/>
<text text-anchor="middle" x="610" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="658,-317 658,-409 "/>
<text text-anchor="middle" x="668.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="679,-317 679,-409 "/>
<text text-anchor="middle" x="737.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="679,-386 796,-386 "/>
<text text-anchor="middle" x="737.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="679,-363 796,-363 "/>
<text text-anchor="middle" x="737.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="679,-340 796,-340 "/>
<text text-anchor="middle" x="737.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="796,-317 796,-409 "/>
<text text-anchor="middle" x="806.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M377.5881,-529.889C384.1929,-525.7203 390.8388,-521.742 397.5,-518 460.7285,-482.4808 488.2941,-500.7202 552.5,-467 579.3417,-452.9031 606.4414,-433.6296 629.3726,-415.5028"/>
<polygon fill="#000000" stroke="#000000" points="631.6868,-418.1335 637.3025,-409.1494 627.3099,-412.6706 631.6868,-418.1335"/>
<text text-anchor="middle" x="551" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge2" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M689.5,-316.9944C689.5,-289.3429 689.5,-252.8377 689.5,-217.8744"/>
<polygon fill="#000000" stroke="#000000" points="693.0001,-217.5755 689.5,-207.5756 686.0001,-217.5756 693.0001,-217.5755"/>
<text text-anchor="middle" x="740" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- survival -->
<g id="node4" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M419,-622C419,-622 780,-622 780,-622 786,-622 792,-628 792,-634 792,-634 792,-748 792,-748 792,-754 786,-760 780,-760 780,-760 419,-760 419,-760 413,-760 407,-754 407,-748 407,-748 407,-634 407,-634 407,-628 413,-622 419,-622"/>
<text text-anchor="middle" x="444" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="481,-622 481,-760 "/>
<text text-anchor="middle" x="491.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="502,-622 502,-760 "/>
<text text-anchor="middle" x="636.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="502,-737 771,-737 "/>
<text text-anchor="middle" x="636.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="502,-714 771,-714 "/>
<text text-anchor="middle" x="636.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="502,-691 771,-691 "/>
<text text-anchor="middle" x="636.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="502,-668 771,-668 "/>
<text text-anchor="middle" x="636.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="502,-645 771,-645 "/>
<text text-anchor="middle" x="636.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="771,-622 771,-760 "/>
<text text-anchor="middle" x="781.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M618.4767,-621.8404C635.0181,-561.5563 658.7071,-475.223 674.097,-419.1354"/>
<polygon fill="#000000" stroke="#000000" points="677.5051,-419.9416 676.776,-409.3719 670.7546,-418.0893 677.5051,-419.9416"/>
<text text-anchor="middle" x="695" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- sample -->
<g id="node6" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M822,-518.5C822,-518.5 1171,-518.5 1171,-518.5 1177,-518.5 1183,-524.5 1183,-530.5 1183,-530.5 1183,-851.5 1183,-851.5 1183,-857.5 1177,-863.5 1171,-863.5 1171,-863.5 822,-863.5 822,-863.5 816,-863.5 810,-857.5 810,-851.5 810,-851.5 810,-530.5 810,-530.5 810,-524.5 816,-518.5 822,-518.5"/>
<text text-anchor="middle" x="844" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="878,-518.5 878,-863.5 "/>
<text text-anchor="middle" x="888.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="899,-518.5 899,-863.5 "/>
<text text-anchor="middle" x="1030.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="899,-840.5 1162,-840.5 "/>
<text text-anchor="middle" x="1030.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="899,-817.5 1162,-817.5 "/>
<text text-anchor="middle" x="1030.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification</text>
<polyline fill="none" stroke="#000000" points="899,-794.5 1162,-794.5 "/>
<text text-anchor="middle" x="1030.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="899,-771.5 1162,-771.5 "/>
<text text-anchor="middle" x="1030.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
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
<polyline fill="none" stroke="#000000" points="1162,-518.5 1162,-863.5 "/>
<text text-anchor="middle" x="1172.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M834.9086,-518.3551C800.1664,-481.2364 765.9784,-444.7099 739.4902,-416.4097"/>
<polygon fill="#000000" stroke="#000000" points="741.9674,-413.9346 732.5786,-409.0253 736.8568,-418.718 741.9674,-413.9346"/>
<text text-anchor="middle" x="853" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M943.5309,-518.4472C914.6591,-436.6833 874.7119,-339.5278 825.5,-259 816.605,-244.4448 806.3098,-229.9381 795.4437,-215.9661"/>
<polygon fill="#000000" stroke="#000000" points="797.936,-213.4753 788.9862,-207.8051 792.4466,-217.8189 797.936,-213.4753"/>
<text text-anchor="middle" x="960" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
</g>
</svg>
</div>
