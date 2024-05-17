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
<svg width="1612pt" height="1108pt"
 viewBox="0.00 0.00 1612.00 1108.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1104)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1104 1608,-1104 1608,4 -4,4"/>
<!-- reference_file -->
<g id="node1" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M419.5,-282.5C419.5,-282.5 696.5,-282.5 696.5,-282.5 702.5,-282.5 708.5,-288.5 708.5,-294.5 708.5,-294.5 708.5,-477.5 708.5,-477.5 708.5,-483.5 702.5,-489.5 696.5,-489.5 696.5,-489.5 419.5,-489.5 419.5,-489.5 413.5,-489.5 407.5,-483.5 407.5,-477.5 407.5,-477.5 407.5,-294.5 407.5,-294.5 407.5,-288.5 413.5,-282.5 419.5,-282.5"/>
<text text-anchor="middle" x="465.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="523.5,-282.5 523.5,-489.5 "/>
<text text-anchor="middle" x="534" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="544.5,-282.5 544.5,-489.5 "/>
<text text-anchor="middle" x="616" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="544.5,-466.5 687.5,-466.5 "/>
<text text-anchor="middle" x="616" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="544.5,-443.5 687.5,-443.5 "/>
<text text-anchor="middle" x="616" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="544.5,-420.5 687.5,-420.5 "/>
<text text-anchor="middle" x="616" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="544.5,-397.5 687.5,-397.5 "/>
<text text-anchor="middle" x="616" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="544.5,-374.5 687.5,-374.5 "/>
<text text-anchor="middle" x="616" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="544.5,-351.5 687.5,-351.5 "/>
<text text-anchor="middle" x="616" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="544.5,-328.5 687.5,-328.5 "/>
<text text-anchor="middle" x="616" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="544.5,-305.5 687.5,-305.5 "/>
<text text-anchor="middle" x="616" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="687.5,-282.5 687.5,-489.5 "/>
<text text-anchor="middle" x="698" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node7" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M744.5,-.5C744.5,-.5 963.5,-.5 963.5,-.5 969.5,-.5 975.5,-6.5 975.5,-12.5 975.5,-12.5 975.5,-218.5 975.5,-218.5 975.5,-224.5 969.5,-230.5 963.5,-230.5 963.5,-230.5 744.5,-230.5 744.5,-230.5 738.5,-230.5 732.5,-224.5 732.5,-218.5 732.5,-218.5 732.5,-12.5 732.5,-12.5 732.5,-6.5 738.5,-.5 744.5,-.5"/>
<text text-anchor="middle" x="760.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="788.5,-.5 788.5,-230.5 "/>
<text text-anchor="middle" x="799" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="809.5,-.5 809.5,-230.5 "/>
<text text-anchor="middle" x="882" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="809.5,-207.5 954.5,-207.5 "/>
<text text-anchor="middle" x="882" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="809.5,-184.5 954.5,-184.5 "/>
<text text-anchor="middle" x="882" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="809.5,-161.5 954.5,-161.5 "/>
<text text-anchor="middle" x="882" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession</text>
<polyline fill="none" stroke="#000000" points="809.5,-138.5 954.5,-138.5 "/>
<text text-anchor="middle" x="882" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="809.5,-115.5 954.5,-115.5 "/>
<text text-anchor="middle" x="882" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="809.5,-92.5 954.5,-92.5 "/>
<text text-anchor="middle" x="882" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="809.5,-69.5 954.5,-69.5 "/>
<text text-anchor="middle" x="882" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="809.5,-46.5 954.5,-46.5 "/>
<text text-anchor="middle" x="882" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="809.5,-23.5 954.5,-23.5 "/>
<text text-anchor="middle" x="882" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="954.5,-.5 954.5,-230.5 "/>
<text text-anchor="middle" x="965" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge9" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M671.5948,-282.1912C688.9987,-266.2867 707.0746,-249.768 724.7857,-233.5827"/>
<polygon fill="#000000" stroke="#000000" points="727.33,-235.9989 732.3508,-226.6693 722.6078,-230.8316 727.33,-235.9989"/>
<text text-anchor="middle" x="766.5" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- survival -->
<g id="node2" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M471.5,-541.5C471.5,-541.5 832.5,-541.5 832.5,-541.5 838.5,-541.5 844.5,-547.5 844.5,-553.5 844.5,-553.5 844.5,-690.5 844.5,-690.5 844.5,-696.5 838.5,-702.5 832.5,-702.5 832.5,-702.5 471.5,-702.5 471.5,-702.5 465.5,-702.5 459.5,-696.5 459.5,-690.5 459.5,-690.5 459.5,-553.5 459.5,-553.5 459.5,-547.5 465.5,-541.5 471.5,-541.5"/>
<text text-anchor="middle" x="496.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="533.5,-541.5 533.5,-702.5 "/>
<text text-anchor="middle" x="544" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="554.5,-541.5 554.5,-702.5 "/>
<text text-anchor="middle" x="689" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="554.5,-679.5 823.5,-679.5 "/>
<text text-anchor="middle" x="689" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="554.5,-656.5 823.5,-656.5 "/>
<text text-anchor="middle" x="689" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="554.5,-633.5 823.5,-633.5 "/>
<text text-anchor="middle" x="689" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="554.5,-610.5 823.5,-610.5 "/>
<text text-anchor="middle" x="689" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="554.5,-587.5 823.5,-587.5 "/>
<text text-anchor="middle" x="689" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="554.5,-564.5 823.5,-564.5 "/>
<text text-anchor="middle" x="689" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="823.5,-541.5 823.5,-702.5 "/>
<text text-anchor="middle" x="834" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node6" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M738.5,-328.5C738.5,-328.5 969.5,-328.5 969.5,-328.5 975.5,-328.5 981.5,-334.5 981.5,-340.5 981.5,-340.5 981.5,-431.5 981.5,-431.5 981.5,-437.5 975.5,-443.5 969.5,-443.5 969.5,-443.5 738.5,-443.5 738.5,-443.5 732.5,-443.5 726.5,-437.5 726.5,-431.5 726.5,-431.5 726.5,-340.5 726.5,-340.5 726.5,-334.5 732.5,-328.5 738.5,-328.5"/>
<text text-anchor="middle" x="774.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="822.5,-328.5 822.5,-443.5 "/>
<text text-anchor="middle" x="833" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="843.5,-328.5 843.5,-443.5 "/>
<text text-anchor="middle" x="902" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="843.5,-420.5 960.5,-420.5 "/>
<text text-anchor="middle" x="902" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="843.5,-397.5 960.5,-397.5 "/>
<text text-anchor="middle" x="902" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="843.5,-374.5 960.5,-374.5 "/>
<text text-anchor="middle" x="902" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="843.5,-351.5 960.5,-351.5 "/>
<text text-anchor="middle" x="902" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="960.5,-328.5 960.5,-443.5 "/>
<text text-anchor="middle" x="971" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M720.952,-541.4423C746.0249,-512.1491 774.0375,-479.4216 797.8676,-451.5804"/>
<polygon fill="#000000" stroke="#000000" points="800.6285,-453.7373 804.4721,-443.8643 795.3105,-449.1855 800.6285,-453.7373"/>
<text text-anchor="middle" x="786.5" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- treatment -->
<g id="node3" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M12,-553C12,-553 304,-553 304,-553 310,-553 316,-559 316,-565 316,-565 316,-679 316,-679 316,-685 310,-691 304,-691 304,-691 12,-691 12,-691 6,-691 0,-685 0,-679 0,-679 0,-565 0,-565 0,-559 6,-553 12,-553"/>
<text text-anchor="middle" x="44.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="89,-553 89,-691 "/>
<text text-anchor="middle" x="99.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="110,-553 110,-691 "/>
<text text-anchor="middle" x="202.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="110,-668 295,-668 "/>
<text text-anchor="middle" x="202.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="110,-645 295,-645 "/>
<text text-anchor="middle" x="202.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="110,-622 295,-622 "/>
<text text-anchor="middle" x="202.5" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="110,-599 295,-599 "/>
<text text-anchor="middle" x="202.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="110,-576 295,-576 "/>
<text text-anchor="middle" x="202.5" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="295,-553 295,-691 "/>
<text text-anchor="middle" x="305.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M195.0749,-552.7948C208.0881,-535.1044 224.4417,-518.2138 244,-508 290.6195,-483.6544 667.4819,-507.7214 717,-490 741.8206,-481.1172 765.8146,-465.9932 786.6005,-449.9887"/>
<polygon fill="#000000" stroke="#000000" points="789.0301,-452.5295 794.7029,-443.5813 784.6881,-447.0389 789.0301,-452.5295"/>
<text text-anchor="middle" x="291" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- diagnosis -->
<g id="node4" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M185.5,-754.5C185.5,-754.5 550.5,-754.5 550.5,-754.5 556.5,-754.5 562.5,-760.5 562.5,-766.5 562.5,-766.5 562.5,-1087.5 562.5,-1087.5 562.5,-1093.5 556.5,-1099.5 550.5,-1099.5 550.5,-1099.5 185.5,-1099.5 185.5,-1099.5 179.5,-1099.5 173.5,-1093.5 173.5,-1087.5 173.5,-1087.5 173.5,-766.5 173.5,-766.5 173.5,-760.5 179.5,-754.5 185.5,-754.5"/>
<text text-anchor="middle" x="215.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="257.5,-754.5 257.5,-1099.5 "/>
<text text-anchor="middle" x="268" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="278.5,-754.5 278.5,-1099.5 "/>
<text text-anchor="middle" x="410" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="278.5,-1076.5 541.5,-1076.5 "/>
<text text-anchor="middle" x="410" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="278.5,-1053.5 541.5,-1053.5 "/>
<text text-anchor="middle" x="410" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="278.5,-1030.5 541.5,-1030.5 "/>
<text text-anchor="middle" x="410" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="278.5,-1007.5 541.5,-1007.5 "/>
<text text-anchor="middle" x="410" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="278.5,-984.5 541.5,-984.5 "/>
<text text-anchor="middle" x="410" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="278.5,-961.5 541.5,-961.5 "/>
<text text-anchor="middle" x="410" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="278.5,-938.5 541.5,-938.5 "/>
<text text-anchor="middle" x="410" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="278.5,-915.5 541.5,-915.5 "/>
<text text-anchor="middle" x="410" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="278.5,-892.5 541.5,-892.5 "/>
<text text-anchor="middle" x="410" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="278.5,-869.5 541.5,-869.5 "/>
<text text-anchor="middle" x="410" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="278.5,-846.5 541.5,-846.5 "/>
<text text-anchor="middle" x="410" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="278.5,-823.5 541.5,-823.5 "/>
<text text-anchor="middle" x="410" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="278.5,-800.5 541.5,-800.5 "/>
<text text-anchor="middle" x="410" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="278.5,-777.5 541.5,-777.5 "/>
<text text-anchor="middle" x="410" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="541.5,-754.5 541.5,-1099.5 "/>
<text text-anchor="middle" x="552" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M343.0446,-754.4189C334.606,-667.098 333.3125,-572.9367 361,-541 413.3511,-480.6147 643.2599,-520.8126 717,-490 740.5944,-480.141 763.7332,-465.2409 784.0812,-449.7754"/>
<polygon fill="#000000" stroke="#000000" points="786.283,-452.497 792.0314,-443.5972 781.9877,-446.9698 786.283,-452.497"/>
<text text-anchor="middle" x="405.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample -->
<g id="node8" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1278,-541.5C1278,-541.5 1592,-541.5 1592,-541.5 1598,-541.5 1604,-547.5 1604,-553.5 1604,-553.5 1604,-690.5 1604,-690.5 1604,-696.5 1598,-702.5 1592,-702.5 1592,-702.5 1278,-702.5 1278,-702.5 1272,-702.5 1266,-696.5 1266,-690.5 1266,-690.5 1266,-553.5 1266,-553.5 1266,-547.5 1272,-541.5 1278,-541.5"/>
<text text-anchor="middle" x="1300" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1334,-541.5 1334,-702.5 "/>
<text text-anchor="middle" x="1344.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1355,-541.5 1355,-702.5 "/>
<text text-anchor="middle" x="1469" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1355,-679.5 1583,-679.5 "/>
<text text-anchor="middle" x="1469" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1355,-656.5 1583,-656.5 "/>
<text text-anchor="middle" x="1469" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1355,-633.5 1583,-633.5 "/>
<text text-anchor="middle" x="1469" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1355,-610.5 1583,-610.5 "/>
<text text-anchor="middle" x="1469" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1355,-587.5 1583,-587.5 "/>
<text text-anchor="middle" x="1469" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1355,-564.5 1583,-564.5 "/>
<text text-anchor="middle" x="1469" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1583,-541.5 1583,-702.5 "/>
<text text-anchor="middle" x="1593.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M562.5812,-888.5553C742.2993,-850.6081 1015.7185,-786.6686 1256.0829,-703.2396"/>
<polygon fill="#000000" stroke="#000000" points="1257.4092,-706.4838 1265.6985,-699.8854 1255.1037,-699.8744 1257.4092,-706.4838"/>
<text text-anchor="middle" x="1230.5" y="-724.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- treatment_response -->
<g id="node5" class="node">
<title>treatment_response</title>
<path fill="none" stroke="#000000" d="M874.5,-553C874.5,-553 1235.5,-553 1235.5,-553 1241.5,-553 1247.5,-559 1247.5,-565 1247.5,-565 1247.5,-679 1247.5,-679 1247.5,-685 1241.5,-691 1235.5,-691 1235.5,-691 874.5,-691 874.5,-691 868.5,-691 862.5,-685 862.5,-679 862.5,-679 862.5,-565 862.5,-565 862.5,-559 868.5,-553 874.5,-553"/>
<text text-anchor="middle" x="943" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
<polyline fill="none" stroke="#000000" points="1023.5,-553 1023.5,-691 "/>
<text text-anchor="middle" x="1034" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1044.5,-553 1044.5,-691 "/>
<text text-anchor="middle" x="1135.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_response</text>
<polyline fill="none" stroke="#000000" points="1044.5,-668 1226.5,-668 "/>
<text text-anchor="middle" x="1135.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1044.5,-645 1226.5,-645 "/>
<text text-anchor="middle" x="1135.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="1044.5,-622 1226.5,-622 "/>
<text text-anchor="middle" x="1135.5" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">response_category</text>
<polyline fill="none" stroke="#000000" points="1044.5,-599 1226.5,-599 "/>
<text text-anchor="middle" x="1135.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">response_system</text>
<polyline fill="none" stroke="#000000" points="1044.5,-576 1226.5,-576 "/>
<text text-anchor="middle" x="1135.5" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response_id</text>
<polyline fill="none" stroke="#000000" points="1226.5,-553 1226.5,-691 "/>
<text text-anchor="middle" x="1237" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M996.0515,-552.7868C968.8204,-520.814 936.6495,-483.0412 909.8154,-451.5345"/>
<polygon fill="#000000" stroke="#000000" points="912.2629,-449.0103 903.1144,-443.6666 906.9338,-453.5491 912.2629,-449.0103"/>
<text text-anchor="middle" x="1050" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge8" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M854,-328.3027C854,-302.7223 854,-271.5515 854,-241.0428"/>
<polygon fill="#000000" stroke="#000000" points="857.5001,-240.7308 854,-230.7308 850.5001,-240.7308 857.5001,-240.7308"/>
<text text-anchor="middle" x="904.5" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1265.9905,-544.7961C1262.9732,-543.5139 1259.9744,-542.2475 1257,-541 1169.3149,-504.2255 1069.5848,-465.8402 991.2729,-436.4686"/>
<polygon fill="#000000" stroke="#000000" points="992.4235,-433.1622 981.8311,-432.9321 989.9681,-439.7174 992.4235,-433.1622"/>
<text text-anchor="middle" x="1238.5" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge7" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1342.6178,-541.4637C1245.6117,-456.8964 1092.3121,-323.254 983.3119,-228.2306"/>
<polygon fill="#000000" stroke="#000000" points="985.3796,-225.3899 975.5418,-221.4568 980.7797,-230.6664 985.3796,-225.3899"/>
<text text-anchor="middle" x="1311.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
</g>
</svg>
</div>
