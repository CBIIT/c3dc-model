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
<svg width="1774pt" height="1200pt"
 viewBox="0.00 0.00 1773.50 1200.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1196)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1196 1769.5,-1196 1769.5,4 -4,4"/>
<!-- survival -->
<g id="node1" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M299,-495.5C299,-495.5 660,-495.5 660,-495.5 666,-495.5 672,-501.5 672,-507.5 672,-507.5 672,-667.5 672,-667.5 672,-673.5 666,-679.5 660,-679.5 660,-679.5 299,-679.5 299,-679.5 293,-679.5 287,-673.5 287,-667.5 287,-667.5 287,-507.5 287,-507.5 287,-501.5 293,-495.5 299,-495.5"/>
<text text-anchor="middle" x="324" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="361,-495.5 361,-679.5 "/>
<text text-anchor="middle" x="371.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="382,-495.5 382,-679.5 "/>
<text text-anchor="middle" x="516.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="382,-656.5 651,-656.5 "/>
<text text-anchor="middle" x="516.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="382,-633.5 651,-633.5 "/>
<text text-anchor="middle" x="516.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="382,-610.5 651,-610.5 "/>
<text text-anchor="middle" x="516.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="382,-587.5 651,-587.5 "/>
<text text-anchor="middle" x="516.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="382,-564.5 651,-564.5 "/>
<text text-anchor="middle" x="516.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="382,-541.5 651,-541.5 "/>
<text text-anchor="middle" x="516.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="382,-518.5 651,-518.5 "/>
<text text-anchor="middle" x="516.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="651,-495.5 651,-679.5 "/>
<text text-anchor="middle" x="661.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node6" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M816,-282.5C816,-282.5 1047,-282.5 1047,-282.5 1053,-282.5 1059,-288.5 1059,-294.5 1059,-294.5 1059,-385.5 1059,-385.5 1059,-391.5 1053,-397.5 1047,-397.5 1047,-397.5 816,-397.5 816,-397.5 810,-397.5 804,-391.5 804,-385.5 804,-385.5 804,-294.5 804,-294.5 804,-288.5 810,-282.5 816,-282.5"/>
<text text-anchor="middle" x="852" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="900,-282.5 900,-397.5 "/>
<text text-anchor="middle" x="910.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="921,-282.5 921,-397.5 "/>
<text text-anchor="middle" x="979.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="921,-374.5 1038,-374.5 "/>
<text text-anchor="middle" x="979.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="921,-351.5 1038,-351.5 "/>
<text text-anchor="middle" x="979.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="921,-328.5 1038,-328.5 "/>
<text text-anchor="middle" x="979.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="921,-305.5 1038,-305.5 "/>
<text text-anchor="middle" x="979.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="1038,-282.5 1038,-397.5 "/>
<text text-anchor="middle" x="1048.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M647.8081,-495.3401C704.397,-464.354 766.1576,-430.5359 817.5624,-402.3884"/>
<polygon fill="#000000" stroke="#000000" points="819.2868,-405.4346 826.3769,-397.5618 815.9248,-399.2948 819.2868,-405.4346"/>
<text text-anchor="middle" x="745" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- treatment_response -->
<g id="node2" class="node">
<title>treatment_response</title>
<path fill="none" stroke="#000000" d="M702,-518.5C702,-518.5 1063,-518.5 1063,-518.5 1069,-518.5 1075,-524.5 1075,-530.5 1075,-530.5 1075,-644.5 1075,-644.5 1075,-650.5 1069,-656.5 1063,-656.5 1063,-656.5 702,-656.5 702,-656.5 696,-656.5 690,-650.5 690,-644.5 690,-644.5 690,-530.5 690,-530.5 690,-524.5 696,-518.5 702,-518.5"/>
<text text-anchor="middle" x="770.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
<polyline fill="none" stroke="#000000" points="851,-518.5 851,-656.5 "/>
<text text-anchor="middle" x="861.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="872,-518.5 872,-656.5 "/>
<text text-anchor="middle" x="963" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_response</text>
<polyline fill="none" stroke="#000000" points="872,-633.5 1054,-633.5 "/>
<text text-anchor="middle" x="963" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="872,-610.5 1054,-610.5 "/>
<text text-anchor="middle" x="963" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="872,-587.5 1054,-587.5 "/>
<text text-anchor="middle" x="963" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_category</text>
<polyline fill="none" stroke="#000000" points="872,-564.5 1054,-564.5 "/>
<text text-anchor="middle" x="963" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_system</text>
<polyline fill="none" stroke="#000000" points="872,-541.5 1054,-541.5 "/>
<text text-anchor="middle" x="963" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response_id</text>
<polyline fill="none" stroke="#000000" points="1054,-518.5 1054,-656.5 "/>
<text text-anchor="middle" x="1064.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M896.2144,-518.2283C903.0689,-483.6063 911.3306,-441.8763 918.136,-407.5016"/>
<polygon fill="#000000" stroke="#000000" points="921.5973,-408.0403 920.1061,-397.5509 914.7305,-406.6807 921.5973,-408.0403"/>
<text text-anchor="middle" x="990.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- treatment -->
<g id="node3" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M1105.5,-518.5C1105.5,-518.5 1397.5,-518.5 1397.5,-518.5 1403.5,-518.5 1409.5,-524.5 1409.5,-530.5 1409.5,-530.5 1409.5,-644.5 1409.5,-644.5 1409.5,-650.5 1403.5,-656.5 1397.5,-656.5 1397.5,-656.5 1105.5,-656.5 1105.5,-656.5 1099.5,-656.5 1093.5,-650.5 1093.5,-644.5 1093.5,-644.5 1093.5,-530.5 1093.5,-530.5 1093.5,-524.5 1099.5,-518.5 1105.5,-518.5"/>
<text text-anchor="middle" x="1138" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1182.5,-518.5 1182.5,-656.5 "/>
<text text-anchor="middle" x="1193" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1203.5,-518.5 1203.5,-656.5 "/>
<text text-anchor="middle" x="1296" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="1203.5,-633.5 1388.5,-633.5 "/>
<text text-anchor="middle" x="1296" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1203.5,-610.5 1388.5,-610.5 "/>
<text text-anchor="middle" x="1296" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1203.5,-587.5 1388.5,-587.5 "/>
<text text-anchor="middle" x="1296" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="1203.5,-564.5 1388.5,-564.5 "/>
<text text-anchor="middle" x="1296" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1203.5,-541.5 1388.5,-541.5 "/>
<text text-anchor="middle" x="1296" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1388.5,-518.5 1388.5,-656.5 "/>
<text text-anchor="middle" x="1399" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1161.9366,-518.2283C1115.5398,-482.3433 1059.2701,-438.8222 1013.9496,-403.7696"/>
<polygon fill="#000000" stroke="#000000" points="1015.9607,-400.9004 1005.9092,-397.5509 1011.6781,-406.4375 1015.9607,-400.9004"/>
<text text-anchor="middle" x="1147.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- reference_file -->
<g id="node4" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M1187,-236.5C1187,-236.5 1464,-236.5 1464,-236.5 1470,-236.5 1476,-242.5 1476,-248.5 1476,-248.5 1476,-431.5 1476,-431.5 1476,-437.5 1470,-443.5 1464,-443.5 1464,-443.5 1187,-443.5 1187,-443.5 1181,-443.5 1175,-437.5 1175,-431.5 1175,-431.5 1175,-248.5 1175,-248.5 1175,-242.5 1181,-236.5 1187,-236.5"/>
<text text-anchor="middle" x="1233" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="1291,-236.5 1291,-443.5 "/>
<text text-anchor="middle" x="1301.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1312,-236.5 1312,-443.5 "/>
<text text-anchor="middle" x="1383.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1312,-420.5 1455,-420.5 "/>
<text text-anchor="middle" x="1383.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="1312,-397.5 1455,-397.5 "/>
<text text-anchor="middle" x="1383.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1312,-374.5 1455,-374.5 "/>
<text text-anchor="middle" x="1383.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1312,-351.5 1455,-351.5 "/>
<text text-anchor="middle" x="1383.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1312,-328.5 1455,-328.5 "/>
<text text-anchor="middle" x="1383.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1312,-305.5 1455,-305.5 "/>
<text text-anchor="middle" x="1383.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1312,-282.5 1455,-282.5 "/>
<text text-anchor="middle" x="1383.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="1312,-259.5 1455,-259.5 "/>
<text text-anchor="middle" x="1383.5" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="1455,-236.5 1455,-443.5 "/>
<text text-anchor="middle" x="1465.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node8" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1216,-.5C1216,-.5 1435,-.5 1435,-.5 1441,-.5 1447,-6.5 1447,-12.5 1447,-12.5 1447,-172.5 1447,-172.5 1447,-178.5 1441,-184.5 1435,-184.5 1435,-184.5 1216,-184.5 1216,-184.5 1210,-184.5 1204,-178.5 1204,-172.5 1204,-172.5 1204,-12.5 1204,-12.5 1204,-6.5 1210,-.5 1216,-.5"/>
<text text-anchor="middle" x="1232" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1260,-.5 1260,-184.5 "/>
<text text-anchor="middle" x="1270.5" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1281,-.5 1281,-184.5 "/>
<text text-anchor="middle" x="1353.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="1281,-161.5 1426,-161.5 "/>
<text text-anchor="middle" x="1353.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="1281,-138.5 1426,-138.5 "/>
<text text-anchor="middle" x="1353.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession</text>
<polyline fill="none" stroke="#000000" points="1281,-115.5 1426,-115.5 "/>
<text text-anchor="middle" x="1353.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1281,-92.5 1426,-92.5 "/>
<text text-anchor="middle" x="1353.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1281,-69.5 1426,-69.5 "/>
<text text-anchor="middle" x="1353.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1281,-46.5 1426,-46.5 "/>
<text text-anchor="middle" x="1353.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="1281,-23.5 1426,-23.5 "/>
<text text-anchor="middle" x="1353.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1426,-.5 1426,-184.5 "/>
<text text-anchor="middle" x="1436.5" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge4" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1325.5,-236.4718C1325.5,-222.7494 1325.5,-208.686 1325.5,-194.9814"/>
<polygon fill="#000000" stroke="#000000" points="1329.0001,-194.5829 1325.5,-184.5829 1322.0001,-194.5829 1329.0001,-194.5829"/>
<text text-anchor="middle" x="1386" y="-206.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- diagnosis -->
<g id="node5" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M12,-731.5C12,-731.5 379,-731.5 379,-731.5 385,-731.5 391,-737.5 391,-743.5 391,-743.5 391,-1179.5 391,-1179.5 391,-1185.5 385,-1191.5 379,-1191.5 379,-1191.5 12,-1191.5 12,-1191.5 6,-1191.5 0,-1185.5 0,-1179.5 0,-1179.5 0,-743.5 0,-743.5 0,-737.5 6,-731.5 12,-731.5"/>
<text text-anchor="middle" x="42" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="84,-731.5 84,-1191.5 "/>
<text text-anchor="middle" x="94.5" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="105,-731.5 105,-1191.5 "/>
<text text-anchor="middle" x="237.5" y="-1176.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="105,-1168.5 370,-1168.5 "/>
<text text-anchor="middle" x="237.5" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="105,-1145.5 370,-1145.5 "/>
<text text-anchor="middle" x="237.5" y="-1130.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_recurrence</text>
<polyline fill="none" stroke="#000000" points="105,-1122.5 370,-1122.5 "/>
<text text-anchor="middle" x="237.5" y="-1107.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="105,-1099.5 370,-1099.5 "/>
<text text-anchor="middle" x="237.5" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="105,-1076.5 370,-1076.5 "/>
<text text-anchor="middle" x="237.5" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="105,-1053.5 370,-1053.5 "/>
<text text-anchor="middle" x="237.5" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="105,-1030.5 370,-1030.5 "/>
<text text-anchor="middle" x="237.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="105,-1007.5 370,-1007.5 "/>
<text text-anchor="middle" x="237.5" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="105,-984.5 370,-984.5 "/>
<text text-anchor="middle" x="237.5" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="105,-961.5 370,-961.5 "/>
<text text-anchor="middle" x="237.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="105,-938.5 370,-938.5 "/>
<text text-anchor="middle" x="237.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="105,-915.5 370,-915.5 "/>
<text text-anchor="middle" x="237.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="105,-892.5 370,-892.5 "/>
<text text-anchor="middle" x="237.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="105,-869.5 370,-869.5 "/>
<text text-anchor="middle" x="237.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="105,-846.5 370,-846.5 "/>
<text text-anchor="middle" x="237.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade_source</text>
<polyline fill="none" stroke="#000000" points="105,-823.5 370,-823.5 "/>
<text text-anchor="middle" x="237.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="105,-800.5 370,-800.5 "/>
<text text-anchor="middle" x="237.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="105,-777.5 370,-777.5 "/>
<text text-anchor="middle" x="237.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="105,-754.5 370,-754.5 "/>
<text text-anchor="middle" x="237.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_source</text>
<polyline fill="none" stroke="#000000" points="370,-731.5 370,-1191.5 "/>
<text text-anchor="middle" x="380.5" y="-957.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M134.7109,-731.3523C126.6413,-648.7547 135.6189,-560.0513 188.5,-495 263.2678,-403.025 599.8926,-363.7727 793.4049,-348.564"/>
<polygon fill="#000000" stroke="#000000" points="793.9525,-352.0322 803.6524,-347.7706 793.4121,-345.0531 793.9525,-352.0322"/>
<text text-anchor="middle" x="233" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample -->
<g id="node7" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1439.5,-507C1439.5,-507 1753.5,-507 1753.5,-507 1759.5,-507 1765.5,-513 1765.5,-519 1765.5,-519 1765.5,-656 1765.5,-656 1765.5,-662 1759.5,-668 1753.5,-668 1753.5,-668 1439.5,-668 1439.5,-668 1433.5,-668 1427.5,-662 1427.5,-656 1427.5,-656 1427.5,-519 1427.5,-519 1427.5,-513 1433.5,-507 1439.5,-507"/>
<text text-anchor="middle" x="1461.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1495.5,-507 1495.5,-668 "/>
<text text-anchor="middle" x="1506" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1516.5,-507 1516.5,-668 "/>
<text text-anchor="middle" x="1630.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1516.5,-645 1744.5,-645 "/>
<text text-anchor="middle" x="1630.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1516.5,-622 1744.5,-622 "/>
<text text-anchor="middle" x="1630.5" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1516.5,-599 1744.5,-599 "/>
<text text-anchor="middle" x="1630.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1516.5,-576 1744.5,-576 "/>
<text text-anchor="middle" x="1630.5" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1516.5,-553 1744.5,-553 "/>
<text text-anchor="middle" x="1630.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1516.5,-530 1744.5,-530 "/>
<text text-anchor="middle" x="1630.5" y="-514.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1744.5,-507 1744.5,-668 "/>
<text text-anchor="middle" x="1755" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M391.0583,-932.1952C636.2571,-891.9157 1067.0789,-809.3721 1418.5,-680 1425.2407,-677.5185 1432.0506,-674.8364 1438.8748,-672.0022"/>
<polygon fill="#000000" stroke="#000000" points="1440.3488,-675.1789 1448.1844,-668.0476 1437.6119,-668.7361 1440.3488,-675.1789"/>
<text text-anchor="middle" x="1399" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge8" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1023.3782,-282.2846C1074.5302,-250.1524 1139.0546,-209.6199 1195.3266,-174.2714"/>
<polygon fill="#000000" stroke="#000000" points="1197.3184,-177.1535 1203.9245,-168.8704 1193.5949,-171.2259 1197.3184,-177.1535"/>
<text text-anchor="middle" x="1190" y="-206.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1448.7921,-506.8593C1438.6717,-502.5442 1428.5159,-498.537 1418.5,-495 1310.7506,-456.9494 1275.3876,-478.6594 1166.5,-444 1130.3032,-432.4784 1092.1895,-417.1169 1057.4377,-401.7442"/>
<polygon fill="#000000" stroke="#000000" points="1058.764,-398.5034 1048.2056,-397.6254 1055.912,-404.8961 1058.764,-398.5034"/>
<text text-anchor="middle" x="1387" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1583.1361,-506.8499C1568.0751,-432.2327 1538.473,-320.4295 1485.5,-236 1475.8789,-220.6657 1464.1579,-205.9896 1451.4786,-192.273"/>
<polygon fill="#000000" stroke="#000000" points="1453.7654,-189.5981 1444.3432,-184.7533 1448.6876,-194.4165 1453.7654,-189.5981"/>
<text text-anchor="middle" x="1604" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
</g>
</svg>
</div>
