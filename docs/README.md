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
<svg width="2333pt" height="1528pt"
 viewBox="0.00 0.00 2332.50 1528.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1524)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1524 2328.5,-1524 2328.5,4 -4,4"/>
<!-- consent_group -->
<g id="node1" class="node">
<title>consent_group</title>
<path fill="none" stroke="#000000" d="M781,-271C781,-271 1106,-271 1106,-271 1112,-271 1118,-277 1118,-283 1118,-283 1118,-374 1118,-374 1118,-380 1112,-386 1106,-386 1106,-386 781,-386 781,-386 775,-386 769,-380 769,-374 769,-374 769,-283 769,-283 769,-277 775,-271 781,-271"/>
<text text-anchor="middle" x="830" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
<polyline fill="none" stroke="#000000" points="891,-271 891,-386 "/>
<text text-anchor="middle" x="901.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="912,-271 912,-386 "/>
<text text-anchor="middle" x="1004.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_id</text>
<polyline fill="none" stroke="#000000" points="912,-363 1097,-363 "/>
<text text-anchor="middle" x="1004.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_name</text>
<polyline fill="none" stroke="#000000" points="912,-340 1097,-340 "/>
<text text-anchor="middle" x="1004.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_number</text>
<polyline fill="none" stroke="#000000" points="912,-317 1097,-317 "/>
<text text-anchor="middle" x="1004.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_suffix</text>
<polyline fill="none" stroke="#000000" points="912,-294 1097,-294 "/>
<text text-anchor="middle" x="1004.5" y="-278.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1097,-271 1097,-386 "/>
<text text-anchor="middle" x="1107.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node9" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M383,-.5C383,-.5 602,-.5 602,-.5 608,-.5 614,-6.5 614,-12.5 614,-12.5 614,-149.5 614,-149.5 614,-155.5 608,-161.5 602,-161.5 602,-161.5 383,-161.5 383,-161.5 377,-161.5 371,-155.5 371,-149.5 371,-149.5 371,-12.5 371,-12.5 371,-6.5 377,-.5 383,-.5"/>
<text text-anchor="middle" x="399" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="427,-.5 427,-161.5 "/>
<text text-anchor="middle" x="437.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="448,-.5 448,-161.5 "/>
<text text-anchor="middle" x="520.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession</text>
<polyline fill="none" stroke="#000000" points="448,-138.5 593,-138.5 "/>
<text text-anchor="middle" x="520.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="448,-115.5 593,-115.5 "/>
<text text-anchor="middle" x="520.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="448,-92.5 593,-92.5 "/>
<text text-anchor="middle" x="520.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="448,-69.5 593,-69.5 "/>
<text text-anchor="middle" x="520.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="448,-46.5 593,-46.5 "/>
<text text-anchor="middle" x="520.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="448,-23.5 593,-23.5 "/>
<text text-anchor="middle" x="520.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
<polyline fill="none" stroke="#000000" points="593,-.5 593,-161.5 "/>
<text text-anchor="middle" x="603.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge6" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M838.614,-270.9406C774.4788,-235.7445 691.899,-190.4263 623.4881,-152.8837"/>
<polygon fill="#000000" stroke="#000000" points="624.8128,-149.6183 614.3622,-147.8756 621.445,-155.755 624.8128,-149.6183"/>
<text text-anchor="middle" x="755" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- reference_file -->
<g id="node2" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M354,-213.5C354,-213.5 631,-213.5 631,-213.5 637,-213.5 643,-219.5 643,-225.5 643,-225.5 643,-431.5 643,-431.5 643,-437.5 637,-443.5 631,-443.5 631,-443.5 354,-443.5 354,-443.5 348,-443.5 342,-437.5 342,-431.5 342,-431.5 342,-225.5 342,-225.5 342,-219.5 348,-213.5 354,-213.5"/>
<text text-anchor="middle" x="400" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="458,-213.5 458,-443.5 "/>
<text text-anchor="middle" x="468.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="479,-213.5 479,-443.5 "/>
<text text-anchor="middle" x="550.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="479,-420.5 622,-420.5 "/>
<text text-anchor="middle" x="550.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="479,-397.5 622,-397.5 "/>
<text text-anchor="middle" x="550.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="479,-374.5 622,-374.5 "/>
<text text-anchor="middle" x="550.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="479,-351.5 622,-351.5 "/>
<text text-anchor="middle" x="550.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="479,-328.5 622,-328.5 "/>
<text text-anchor="middle" x="550.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="479,-305.5 622,-305.5 "/>
<text text-anchor="middle" x="550.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="479,-282.5 622,-282.5 "/>
<text text-anchor="middle" x="550.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="479,-259.5 622,-259.5 "/>
<text text-anchor="middle" x="550.5" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="479,-236.5 622,-236.5 "/>
<text text-anchor="middle" x="550.5" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="622,-213.5 622,-443.5 "/>
<text text-anchor="middle" x="632.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge2" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M492.5,-213.4448C492.5,-199.4621 492.5,-185.3307 492.5,-171.7693"/>
<polygon fill="#000000" stroke="#000000" points="496.0001,-171.5218 492.5,-161.5218 489.0001,-171.5219 496.0001,-171.5218"/>
<text text-anchor="middle" x="553" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- synonym -->
<g id="node3" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M12,-674C12,-674 313,-674 313,-674 319,-674 325,-680 325,-686 325,-686 325,-823 325,-823 325,-829 319,-835 313,-835 313,-835 12,-835 12,-835 6,-835 0,-829 0,-823 0,-823 0,-686 0,-686 0,-680 6,-674 12,-674"/>
<text text-anchor="middle" x="40" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="80,-674 80,-835 "/>
<text text-anchor="middle" x="90.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="101,-674 101,-835 "/>
<text text-anchor="middle" x="202.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_id</text>
<polyline fill="none" stroke="#000000" points="101,-812 304,-812 "/>
<text text-anchor="middle" x="202.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">data_location</text>
<polyline fill="none" stroke="#000000" points="101,-789 304,-789 "/>
<text text-anchor="middle" x="202.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">domain_category</text>
<polyline fill="none" stroke="#000000" points="101,-766 304,-766 "/>
<text text-anchor="middle" x="202.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">domain_description</text>
<polyline fill="none" stroke="#000000" points="101,-743 304,-743 "/>
<text text-anchor="middle" x="202.5" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="101,-720 304,-720 "/>
<text text-anchor="middle" x="202.5" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="101,-697 304,-697 "/>
<text text-anchor="middle" x="202.5" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="304,-674 304,-835 "/>
<text text-anchor="middle" x="314.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node6" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M983,-495.5C983,-495.5 1214,-495.5 1214,-495.5 1220,-495.5 1226,-501.5 1226,-507.5 1226,-507.5 1226,-575.5 1226,-575.5 1226,-581.5 1220,-587.5 1214,-587.5 1214,-587.5 983,-587.5 983,-587.5 977,-587.5 971,-581.5 971,-575.5 971,-575.5 971,-507.5 971,-507.5 971,-501.5 977,-495.5 983,-495.5"/>
<text text-anchor="middle" x="1019" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1067,-495.5 1067,-587.5 "/>
<text text-anchor="middle" x="1077.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1088,-495.5 1088,-587.5 "/>
<text text-anchor="middle" x="1146.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1088,-564.5 1205,-564.5 "/>
<text text-anchor="middle" x="1146.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1088,-541.5 1205,-541.5 "/>
<text text-anchor="middle" x="1146.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1088,-518.5 1205,-518.5 "/>
<text text-anchor="middle" x="1146.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="1205,-495.5 1205,-587.5 "/>
<text text-anchor="middle" x="1215.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M265.4368,-673.8967C286.9497,-660.3064 310.2013,-647.7806 333.5,-639 445.1975,-596.9045 772.4296,-566.1485 960.758,-551.3579"/>
<polygon fill="#000000" stroke="#000000" points="961.0344,-554.847 970.7316,-550.5793 960.4895,-547.8683 961.0344,-554.847"/>
<text text-anchor="middle" x="500" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M173.0961,-673.901C190.8653,-562.2977 234.8161,-358.0771 332.5,-213 343.1189,-197.2292 356.1631,-182.349 370.1808,-168.6628"/>
<polygon fill="#000000" stroke="#000000" points="372.7566,-171.0433 377.5921,-161.6162 367.9332,-165.9702 372.7566,-171.0433"/>
<text text-anchor="middle" x="263" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample -->
<g id="node4" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1217.5,-651C1217.5,-651 1531.5,-651 1531.5,-651 1537.5,-651 1543.5,-657 1543.5,-663 1543.5,-663 1543.5,-846 1543.5,-846 1543.5,-852 1537.5,-858 1531.5,-858 1531.5,-858 1217.5,-858 1217.5,-858 1211.5,-858 1205.5,-852 1205.5,-846 1205.5,-846 1205.5,-663 1205.5,-663 1205.5,-657 1211.5,-651 1217.5,-651"/>
<text text-anchor="middle" x="1239.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1273.5,-651 1273.5,-858 "/>
<text text-anchor="middle" x="1284" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1294.5,-651 1294.5,-858 "/>
<text text-anchor="middle" x="1408.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1294.5,-835 1522.5,-835 "/>
<text text-anchor="middle" x="1408.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1294.5,-812 1522.5,-812 "/>
<text text-anchor="middle" x="1408.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1294.5,-789 1522.5,-789 "/>
<text text-anchor="middle" x="1408.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_necrosis</text>
<polyline fill="none" stroke="#000000" points="1294.5,-766 1522.5,-766 "/>
<text text-anchor="middle" x="1408.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_tumor</text>
<polyline fill="none" stroke="#000000" points="1294.5,-743 1522.5,-743 "/>
<text text-anchor="middle" x="1408.5" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1294.5,-720 1522.5,-720 "/>
<text text-anchor="middle" x="1408.5" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1294.5,-697 1522.5,-697 "/>
<text text-anchor="middle" x="1408.5" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1294.5,-674 1522.5,-674 "/>
<text text-anchor="middle" x="1408.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1522.5,-651 1522.5,-858 "/>
<text text-anchor="middle" x="1533" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1240.1383,-650.8078C1214.4978,-631.02 1188.6897,-611.1029 1166.2579,-593.7914"/>
<polygon fill="#000000" stroke="#000000" points="1168.2079,-590.8752 1158.1529,-587.5365 1163.9312,-596.4169 1168.2079,-590.8752"/>
<text text-anchor="middle" x="1233" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- treatment -->
<g id="node5" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M354.5,-639.5C354.5,-639.5 646.5,-639.5 646.5,-639.5 652.5,-639.5 658.5,-645.5 658.5,-651.5 658.5,-651.5 658.5,-857.5 658.5,-857.5 658.5,-863.5 652.5,-869.5 646.5,-869.5 646.5,-869.5 354.5,-869.5 354.5,-869.5 348.5,-869.5 342.5,-863.5 342.5,-857.5 342.5,-857.5 342.5,-651.5 342.5,-651.5 342.5,-645.5 348.5,-639.5 354.5,-639.5"/>
<text text-anchor="middle" x="387" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="431.5,-639.5 431.5,-869.5 "/>
<text text-anchor="middle" x="442" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="452.5,-639.5 452.5,-869.5 "/>
<text text-anchor="middle" x="545" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="452.5,-846.5 637.5,-846.5 "/>
<text text-anchor="middle" x="545" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="452.5,-823.5 637.5,-823.5 "/>
<text text-anchor="middle" x="545" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose</text>
<polyline fill="none" stroke="#000000" points="452.5,-800.5 637.5,-800.5 "/>
<text text-anchor="middle" x="545" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_frequency</text>
<polyline fill="none" stroke="#000000" points="452.5,-777.5 637.5,-777.5 "/>
<text text-anchor="middle" x="545" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_route</text>
<polyline fill="none" stroke="#000000" points="452.5,-754.5 637.5,-754.5 "/>
<text text-anchor="middle" x="545" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_unit</text>
<polyline fill="none" stroke="#000000" points="452.5,-731.5 637.5,-731.5 "/>
<text text-anchor="middle" x="545" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="452.5,-708.5 637.5,-708.5 "/>
<text text-anchor="middle" x="545" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="452.5,-685.5 637.5,-685.5 "/>
<text text-anchor="middle" x="545" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="452.5,-662.5 637.5,-662.5 "/>
<text text-anchor="middle" x="545" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="637.5,-639.5 637.5,-869.5 "/>
<text text-anchor="middle" x="648" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M658.7825,-642.9808C661.688,-641.6043 664.5951,-640.2756 667.5,-639 761.1762,-597.8642 874.2169,-573.1276 961.025,-558.8676"/>
<polygon fill="#000000" stroke="#000000" points="961.6285,-562.3155 970.9421,-557.2652 960.5119,-555.4052 961.6285,-562.3155"/>
<text text-anchor="middle" x="793.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge3" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1064.8673,-495.2822C1043.3622,-465.73 1015.1377,-426.9441 991.3193,-394.213"/>
<polygon fill="#000000" stroke="#000000" points="994.0795,-392.0576 985.3654,-386.0312 988.4194,-396.1764 994.0795,-392.0576"/>
<text text-anchor="middle" x="1099" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- survival -->
<g id="node7" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M689,-662.5C689,-662.5 1050,-662.5 1050,-662.5 1056,-662.5 1062,-668.5 1062,-674.5 1062,-674.5 1062,-834.5 1062,-834.5 1062,-840.5 1056,-846.5 1050,-846.5 1050,-846.5 689,-846.5 689,-846.5 683,-846.5 677,-840.5 677,-834.5 677,-834.5 677,-674.5 677,-674.5 677,-668.5 683,-662.5 689,-662.5"/>
<text text-anchor="middle" x="714" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="751,-662.5 751,-846.5 "/>
<text text-anchor="middle" x="761.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="772,-662.5 772,-846.5 "/>
<text text-anchor="middle" x="906.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="772,-823.5 1041,-823.5 "/>
<text text-anchor="middle" x="906.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="772,-800.5 1041,-800.5 "/>
<text text-anchor="middle" x="906.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="772,-777.5 1041,-777.5 "/>
<text text-anchor="middle" x="906.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="772,-754.5 1041,-754.5 "/>
<text text-anchor="middle" x="906.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="772,-731.5 1041,-731.5 "/>
<text text-anchor="middle" x="906.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="772,-708.5 1041,-708.5 "/>
<text text-anchor="middle" x="906.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="772,-685.5 1041,-685.5 "/>
<text text-anchor="middle" x="906.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="1041,-662.5 1041,-846.5 "/>
<text text-anchor="middle" x="1051.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M948.0674,-662.2431C966.1651,-642.8681 985.8825,-623.1313 1005.5,-606 1010.162,-601.9288 1015.0848,-597.883 1020.1336,-593.9179"/>
<polygon fill="#000000" stroke="#000000" points="1022.3517,-596.6276 1028.1518,-587.7614 1018.0886,-591.0754 1022.3517,-596.6276"/>
<text text-anchor="middle" x="1045" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- laboratory_test -->
<g id="node8" class="node">
<title>laboratory_test</title>
<path fill="none" stroke="#000000" d="M1887.5,-1094C1887.5,-1094 2219.5,-1094 2219.5,-1094 2225.5,-1094 2231.5,-1100 2231.5,-1106 2231.5,-1106 2231.5,-1335 2231.5,-1335 2231.5,-1341 2225.5,-1347 2219.5,-1347 2219.5,-1347 1887.5,-1347 1887.5,-1347 1881.5,-1347 1875.5,-1341 1875.5,-1335 1875.5,-1335 1875.5,-1106 1875.5,-1106 1875.5,-1100 1881.5,-1094 1887.5,-1094"/>
<text text-anchor="middle" x="1938.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="2001.5,-1094 2001.5,-1347 "/>
<text text-anchor="middle" x="2012" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2022.5,-1094 2022.5,-1347 "/>
<text text-anchor="middle" x="2116.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_laboratory_test</text>
<polyline fill="none" stroke="#000000" points="2022.5,-1324 2210.5,-1324 "/>
<text text-anchor="middle" x="2116.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2022.5,-1301 2210.5,-1301 "/>
<text text-anchor="middle" x="2116.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_id</text>
<polyline fill="none" stroke="#000000" points="2022.5,-1278 2210.5,-1278 "/>
<text text-anchor="middle" x="2116.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_method</text>
<polyline fill="none" stroke="#000000" points="2022.5,-1255 2210.5,-1255 "/>
<text text-anchor="middle" x="2116.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_name</text>
<polyline fill="none" stroke="#000000" points="2022.5,-1232 2210.5,-1232 "/>
<text text-anchor="middle" x="2116.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">sensitivity</text>
<polyline fill="none" stroke="#000000" points="2022.5,-1209 2210.5,-1209 "/>
<text text-anchor="middle" x="2116.5" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">specimen</text>
<polyline fill="none" stroke="#000000" points="2022.5,-1186 2210.5,-1186 "/>
<text text-anchor="middle" x="2116.5" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_modifier</text>
<polyline fill="none" stroke="#000000" points="2022.5,-1163 2210.5,-1163 "/>
<text text-anchor="middle" x="2116.5" y="-1147.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_numeric</text>
<polyline fill="none" stroke="#000000" points="2022.5,-1140 2210.5,-1140 "/>
<text text-anchor="middle" x="2116.5" y="-1124.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_text</text>
<polyline fill="none" stroke="#000000" points="2022.5,-1117 2210.5,-1117 "/>
<text text-anchor="middle" x="2116.5" y="-1101.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_unit</text>
<polyline fill="none" stroke="#000000" points="2210.5,-1094 2210.5,-1347 "/>
<text text-anchor="middle" x="2221" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1957.6994,-1093.91C1905.5953,-1033.2773 1836.3542,-964.5575 1760.5,-921 1679.8283,-874.6762 1643.016,-906.6174 1557.5,-870 1552.0241,-867.6552 1546.5244,-865.1579 1541.0251,-862.5358"/>
<polygon fill="#000000" stroke="#000000" points="1542.2953,-859.2608 1531.7745,-858.0102 1539.2191,-865.5487 1542.2953,-859.2608"/>
<text text-anchor="middle" x="1786" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2121.5853,-1093.8374C2181.2896,-963.4447 2242.8687,-762.4035 2132.5,-639 2073.8663,-573.4415 1503.9532,-551.1784 1236.1874,-544.2969"/>
<polygon fill="#000000" stroke="#000000" points="1236.0952,-540.7935 1226.0097,-544.039 1235.9178,-547.7913 1236.0952,-540.7935"/>
<text text-anchor="middle" x="2259" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- diagnosis -->
<g id="node10" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M932,-1013.5C932,-1013.5 1297,-1013.5 1297,-1013.5 1303,-1013.5 1309,-1019.5 1309,-1025.5 1309,-1025.5 1309,-1415.5 1309,-1415.5 1309,-1421.5 1303,-1427.5 1297,-1427.5 1297,-1427.5 932,-1427.5 932,-1427.5 926,-1427.5 920,-1421.5 920,-1415.5 920,-1415.5 920,-1025.5 920,-1025.5 920,-1019.5 926,-1013.5 932,-1013.5"/>
<text text-anchor="middle" x="962" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1004,-1013.5 1004,-1427.5 "/>
<text text-anchor="middle" x="1014.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1025,-1013.5 1025,-1427.5 "/>
<text text-anchor="middle" x="1156.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1025,-1404.5 1288,-1404.5 "/>
<text text-anchor="middle" x="1156.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1025,-1381.5 1288,-1381.5 "/>
<text text-anchor="middle" x="1156.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1025,-1358.5 1288,-1358.5 "/>
<text text-anchor="middle" x="1156.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="1025,-1335.5 1288,-1335.5 "/>
<text text-anchor="middle" x="1156.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_category</text>
<polyline fill="none" stroke="#000000" points="1025,-1312.5 1288,-1312.5 "/>
<text text-anchor="middle" x="1156.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="1025,-1289.5 1288,-1289.5 "/>
<text text-anchor="middle" x="1156.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="1025,-1266.5 1288,-1266.5 "/>
<text text-anchor="middle" x="1156.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1025,-1243.5 1288,-1243.5 "/>
<text text-anchor="middle" x="1156.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="1025,-1220.5 1288,-1220.5 "/>
<text text-anchor="middle" x="1156.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1025,-1197.5 1288,-1197.5 "/>
<text text-anchor="middle" x="1156.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">laterality</text>
<polyline fill="none" stroke="#000000" points="1025,-1174.5 1288,-1174.5 "/>
<text text-anchor="middle" x="1156.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="1025,-1151.5 1288,-1151.5 "/>
<text text-anchor="middle" x="1156.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1025,-1128.5 1288,-1128.5 "/>
<text text-anchor="middle" x="1156.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1025,-1105.5 1288,-1105.5 "/>
<text text-anchor="middle" x="1156.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1025,-1082.5 1288,-1082.5 "/>
<text text-anchor="middle" x="1156.5" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1025,-1059.5 1288,-1059.5 "/>
<text text-anchor="middle" x="1156.5" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1025,-1036.5 1288,-1036.5 "/>
<text text-anchor="middle" x="1156.5" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1288,-1013.5 1288,-1427.5 "/>
<text text-anchor="middle" x="1298.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1230.0539,-1013.3918C1258.095,-963.1335 1287.0439,-911.2482 1311.5948,-867.2456"/>
<polygon fill="#000000" stroke="#000000" points="1314.7887,-868.7045 1316.6046,-858.2664 1308.6757,-865.2938 1314.7887,-868.7045"/>
<text text-anchor="middle" x="1343" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1109.6125,-1013.0881C1106.2234,-869.2601 1101.9512,-687.9606 1099.8264,-597.7901"/>
<polygon fill="#000000" stroke="#000000" points="1103.3252,-597.6929 1099.5905,-587.7781 1096.3271,-597.8579 1103.3252,-597.6929"/>
<text text-anchor="middle" x="1151" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- genetic_analysis -->
<g id="node11" class="node">
<title>genetic_analysis</title>
<path fill="none" stroke="#000000" d="M1355.5,-921.5C1355.5,-921.5 1739.5,-921.5 1739.5,-921.5 1745.5,-921.5 1751.5,-927.5 1751.5,-933.5 1751.5,-933.5 1751.5,-1507.5 1751.5,-1507.5 1751.5,-1513.5 1745.5,-1519.5 1739.5,-1519.5 1739.5,-1519.5 1355.5,-1519.5 1355.5,-1519.5 1349.5,-1519.5 1343.5,-1513.5 1343.5,-1507.5 1343.5,-1507.5 1343.5,-933.5 1343.5,-933.5 1343.5,-927.5 1349.5,-921.5 1355.5,-921.5"/>
<text text-anchor="middle" x="1411" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="1478.5,-921.5 1478.5,-1519.5 "/>
<text text-anchor="middle" x="1489" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1499.5,-921.5 1499.5,-1519.5 "/>
<text text-anchor="middle" x="1615" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="1499.5,-1496.5 1730.5,-1496.5 "/>
<text text-anchor="middle" x="1615" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">allelic_ratio</text>
<polyline fill="none" stroke="#000000" points="1499.5,-1473.5 1730.5,-1473.5 "/>
<text text-anchor="middle" x="1615" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration</text>
<polyline fill="none" stroke="#000000" points="1499.5,-1450.5 1730.5,-1450.5 "/>
<text text-anchor="middle" x="1615" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration_effect</text>
<polyline fill="none" stroke="#000000" points="1499.5,-1427.5 1730.5,-1427.5 "/>
<text text-anchor="middle" x="1615" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration_type</text>
<polyline fill="none" stroke="#000000" points="1499.5,-1404.5 1730.5,-1404.5 "/>
<text text-anchor="middle" x="1615" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="1499.5,-1381.5 1730.5,-1381.5 "/>
<text text-anchor="middle" x="1615" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="1499.5,-1358.5 1730.5,-1358.5 "/>
<text text-anchor="middle" x="1615" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">dna_index_numeric</text>
<polyline fill="none" stroke="#000000" points="1499.5,-1335.5 1730.5,-1335.5 "/>
<text text-anchor="middle" x="1615" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="1499.5,-1312.5 1730.5,-1312.5 "/>
<text text-anchor="middle" x="1615" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_exon</text>
<polyline fill="none" stroke="#000000" points="1499.5,-1289.5 1730.5,-1289.5 "/>
<text text-anchor="middle" x="1615" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_gene</text>
<polyline fill="none" stroke="#000000" points="1499.5,-1266.5 1730.5,-1266.5 "/>
<text text-anchor="middle" x="1615" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_transcript</text>
<polyline fill="none" stroke="#000000" points="1499.5,-1243.5 1730.5,-1243.5 "/>
<text text-anchor="middle" x="1615" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="1499.5,-1220.5 1730.5,-1220.5 "/>
<text text-anchor="middle" x="1615" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis_id</text>
<polyline fill="none" stroke="#000000" points="1499.5,-1197.5 1730.5,-1197.5 "/>
<text text-anchor="middle" x="1615" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_source_category</text>
<polyline fill="none" stroke="#000000" points="1499.5,-1174.5 1730.5,-1174.5 "/>
<text text-anchor="middle" x="1615" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_coding</text>
<polyline fill="none" stroke="#000000" points="1499.5,-1151.5 1730.5,-1151.5 "/>
<text text-anchor="middle" x="1615" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_genome</text>
<polyline fill="none" stroke="#000000" points="1499.5,-1128.5 1730.5,-1128.5 "/>
<text text-anchor="middle" x="1615" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_protein</text>
<polyline fill="none" stroke="#000000" points="1499.5,-1105.5 1730.5,-1105.5 "/>
<text text-anchor="middle" x="1615" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1499.5,-1082.5 1730.5,-1082.5 "/>
<text text-anchor="middle" x="1615" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">iscn</text>
<polyline fill="none" stroke="#000000" points="1499.5,-1059.5 1730.5,-1059.5 "/>
<text text-anchor="middle" x="1615" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">method</text>
<polyline fill="none" stroke="#000000" points="1499.5,-1036.5 1730.5,-1036.5 "/>
<text text-anchor="middle" x="1615" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome</text>
<polyline fill="none" stroke="#000000" points="1499.5,-1013.5 1730.5,-1013.5 "/>
<text text-anchor="middle" x="1615" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance</text>
<polyline fill="none" stroke="#000000" points="1499.5,-990.5 1730.5,-990.5 "/>
<text text-anchor="middle" x="1615" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance_system</text>
<polyline fill="none" stroke="#000000" points="1499.5,-967.5 1730.5,-967.5 "/>
<text text-anchor="middle" x="1615" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">result</text>
<polyline fill="none" stroke="#000000" points="1499.5,-944.5 1730.5,-944.5 "/>
<text text-anchor="middle" x="1615" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 6 properties</text>
<polyline fill="none" stroke="#000000" points="1730.5,-921.5 1730.5,-1519.5 "/>
<text text-anchor="middle" x="1741" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1432.2569,-921.4814C1429.9749,-915.2703 1427.7202,-909.1044 1425.5,-903 1421.3461,-891.5792 1417.0924,-879.6326 1412.8994,-867.6896"/>
<polygon fill="#000000" stroke="#000000" points="1416.1584,-866.406 1409.5529,-858.1225 1409.551,-868.7173 1416.1584,-866.406"/>
<text text-anchor="middle" x="1495.5" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1584.938,-921.4876C1592.893,-802.1164 1589.7002,-682.6576 1552.5,-639 1512.0466,-591.5245 1354.6225,-565.8195 1236.4145,-552.9123"/>
<polygon fill="#000000" stroke="#000000" points="1236.4985,-549.4014 1226.1826,-551.8161 1235.7528,-556.3615 1236.4985,-549.4014"/>
<text text-anchor="middle" x="1657.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- treatment_response -->
<g id="node12" class="node">
<title>treatment_response</title>
<path fill="none" stroke="#000000" d="M1750,-685.5C1750,-685.5 2111,-685.5 2111,-685.5 2117,-685.5 2123,-691.5 2123,-697.5 2123,-697.5 2123,-811.5 2123,-811.5 2123,-817.5 2117,-823.5 2111,-823.5 2111,-823.5 1750,-823.5 1750,-823.5 1744,-823.5 1738,-817.5 1738,-811.5 1738,-811.5 1738,-697.5 1738,-697.5 1738,-691.5 1744,-685.5 1750,-685.5"/>
<text text-anchor="middle" x="1818.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
<polyline fill="none" stroke="#000000" points="1899,-685.5 1899,-823.5 "/>
<text text-anchor="middle" x="1909.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1920,-685.5 1920,-823.5 "/>
<text text-anchor="middle" x="2011" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_response</text>
<polyline fill="none" stroke="#000000" points="1920,-800.5 2102,-800.5 "/>
<text text-anchor="middle" x="2011" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1920,-777.5 2102,-777.5 "/>
<text text-anchor="middle" x="2011" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="1920,-754.5 2102,-754.5 "/>
<text text-anchor="middle" x="2011" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_category</text>
<polyline fill="none" stroke="#000000" points="1920,-731.5 2102,-731.5 "/>
<text text-anchor="middle" x="2011" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_system</text>
<polyline fill="none" stroke="#000000" points="1920,-708.5 2102,-708.5 "/>
<text text-anchor="middle" x="2011" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response_id</text>
<polyline fill="none" stroke="#000000" points="2102,-685.5 2102,-823.5 "/>
<text text-anchor="middle" x="2112.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1819.2313,-685.4565C1788.9461,-668.6122 1755.6185,-651.7827 1723.5,-639 1668.1149,-616.9575 1652.0478,-617.2043 1593.5,-606 1473.6606,-583.0663 1335.9192,-565.8494 1236.2127,-554.9978"/>
<polygon fill="#000000" stroke="#000000" points="1236.395,-551.4972 1226.0768,-553.9023 1235.6428,-558.4566 1236.395,-551.4972"/>
<text text-anchor="middle" x="1750.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
</g>
</svg>
</div>
