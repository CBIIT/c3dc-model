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
<svg width="2376pt" height="1528pt"
 viewBox="0.00 0.00 2376.00 1528.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1524)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1524 2372,-1524 2372,4 -4,4"/>
<!-- sample -->
<g id="node1" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1328.5,-651C1328.5,-651 1642.5,-651 1642.5,-651 1648.5,-651 1654.5,-657 1654.5,-663 1654.5,-663 1654.5,-846 1654.5,-846 1654.5,-852 1648.5,-858 1642.5,-858 1642.5,-858 1328.5,-858 1328.5,-858 1322.5,-858 1316.5,-852 1316.5,-846 1316.5,-846 1316.5,-663 1316.5,-663 1316.5,-657 1322.5,-651 1328.5,-651"/>
<text text-anchor="middle" x="1350.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1384.5,-651 1384.5,-858 "/>
<text text-anchor="middle" x="1395" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1405.5,-651 1405.5,-858 "/>
<text text-anchor="middle" x="1519.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1405.5,-835 1633.5,-835 "/>
<text text-anchor="middle" x="1519.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1405.5,-812 1633.5,-812 "/>
<text text-anchor="middle" x="1519.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1405.5,-789 1633.5,-789 "/>
<text text-anchor="middle" x="1519.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_necrosis</text>
<polyline fill="none" stroke="#000000" points="1405.5,-766 1633.5,-766 "/>
<text text-anchor="middle" x="1519.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_tumor</text>
<polyline fill="none" stroke="#000000" points="1405.5,-743 1633.5,-743 "/>
<text text-anchor="middle" x="1519.5" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1405.5,-720 1633.5,-720 "/>
<text text-anchor="middle" x="1519.5" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1405.5,-697 1633.5,-697 "/>
<text text-anchor="middle" x="1519.5" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1405.5,-674 1633.5,-674 "/>
<text text-anchor="middle" x="1519.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1633.5,-651 1633.5,-858 "/>
<text text-anchor="middle" x="1644" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node6" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1052,-495.5C1052,-495.5 1283,-495.5 1283,-495.5 1289,-495.5 1295,-501.5 1295,-507.5 1295,-507.5 1295,-575.5 1295,-575.5 1295,-581.5 1289,-587.5 1283,-587.5 1283,-587.5 1052,-587.5 1052,-587.5 1046,-587.5 1040,-581.5 1040,-575.5 1040,-575.5 1040,-507.5 1040,-507.5 1040,-501.5 1046,-495.5 1052,-495.5"/>
<text text-anchor="middle" x="1088" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1136,-495.5 1136,-587.5 "/>
<text text-anchor="middle" x="1146.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1157,-495.5 1157,-587.5 "/>
<text text-anchor="middle" x="1215.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1157,-564.5 1274,-564.5 "/>
<text text-anchor="middle" x="1215.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1157,-541.5 1274,-541.5 "/>
<text text-anchor="middle" x="1215.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1157,-518.5 1274,-518.5 "/>
<text text-anchor="middle" x="1215.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="1274,-495.5 1274,-587.5 "/>
<text text-anchor="middle" x="1284.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1330.692,-650.8078C1300.7609,-630.7597 1270.6316,-610.5787 1244.5507,-593.1094"/>
<polygon fill="#000000" stroke="#000000" points="1246.4867,-590.1936 1236.2305,-587.5365 1242.5911,-596.0095 1246.4867,-590.1936"/>
<text text-anchor="middle" x="1316" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- survival -->
<g id="node2" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M355,-662.5C355,-662.5 716,-662.5 716,-662.5 722,-662.5 728,-668.5 728,-674.5 728,-674.5 728,-834.5 728,-834.5 728,-840.5 722,-846.5 716,-846.5 716,-846.5 355,-846.5 355,-846.5 349,-846.5 343,-840.5 343,-834.5 343,-834.5 343,-674.5 343,-674.5 343,-668.5 349,-662.5 355,-662.5"/>
<text text-anchor="middle" x="380" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="417,-662.5 417,-846.5 "/>
<text text-anchor="middle" x="427.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="438,-662.5 438,-846.5 "/>
<text text-anchor="middle" x="572.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="438,-823.5 707,-823.5 "/>
<text text-anchor="middle" x="572.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="438,-800.5 707,-800.5 "/>
<text text-anchor="middle" x="572.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="438,-777.5 707,-777.5 "/>
<text text-anchor="middle" x="572.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="438,-754.5 707,-754.5 "/>
<text text-anchor="middle" x="572.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="438,-731.5 707,-731.5 "/>
<text text-anchor="middle" x="572.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="438,-708.5 707,-708.5 "/>
<text text-anchor="middle" x="572.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="438,-685.5 707,-685.5 "/>
<text text-anchor="middle" x="572.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="707,-662.5 707,-846.5 "/>
<text text-anchor="middle" x="717.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M684.5454,-662.4326C701.7141,-653.7698 719.2528,-645.7295 736.5,-639 831.1996,-602.0499 943.3334,-577.2296 1029.4835,-561.8814"/>
<polygon fill="#000000" stroke="#000000" points="1030.3495,-565.2829 1039.5916,-560.1027 1029.1364,-558.3888 1030.3495,-565.2829"/>
<text text-anchor="middle" x="868" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- treatment_response -->
<g id="node3" class="node">
<title>treatment_response</title>
<path fill="none" stroke="#000000" d="M758,-685.5C758,-685.5 1119,-685.5 1119,-685.5 1125,-685.5 1131,-691.5 1131,-697.5 1131,-697.5 1131,-811.5 1131,-811.5 1131,-817.5 1125,-823.5 1119,-823.5 1119,-823.5 758,-823.5 758,-823.5 752,-823.5 746,-817.5 746,-811.5 746,-811.5 746,-697.5 746,-697.5 746,-691.5 752,-685.5 758,-685.5"/>
<text text-anchor="middle" x="826.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
<polyline fill="none" stroke="#000000" points="907,-685.5 907,-823.5 "/>
<text text-anchor="middle" x="917.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="928,-685.5 928,-823.5 "/>
<text text-anchor="middle" x="1019" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_response</text>
<polyline fill="none" stroke="#000000" points="928,-800.5 1110,-800.5 "/>
<text text-anchor="middle" x="1019" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="928,-777.5 1110,-777.5 "/>
<text text-anchor="middle" x="1019" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="928,-754.5 1110,-754.5 "/>
<text text-anchor="middle" x="1019" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_category</text>
<polyline fill="none" stroke="#000000" points="928,-731.5 1110,-731.5 "/>
<text text-anchor="middle" x="1019" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_system</text>
<polyline fill="none" stroke="#000000" points="928,-708.5 1110,-708.5 "/>
<text text-anchor="middle" x="1019" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response_id</text>
<polyline fill="none" stroke="#000000" points="1110,-685.5 1110,-823.5 "/>
<text text-anchor="middle" x="1120.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M947.8861,-685.1771C954.7834,-657.5309 966.7477,-627.2855 987.5,-606 999.704,-593.4824 1014.5045,-583.3854 1030.3167,-575.2428"/>
<polygon fill="#000000" stroke="#000000" points="1032.2651,-578.1876 1039.7316,-570.6708 1029.2072,-571.8907 1032.2651,-578.1876"/>
<text text-anchor="middle" x="1070.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- diagnosis -->
<g id="node4" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1991,-1013.5C1991,-1013.5 2356,-1013.5 2356,-1013.5 2362,-1013.5 2368,-1019.5 2368,-1025.5 2368,-1025.5 2368,-1415.5 2368,-1415.5 2368,-1421.5 2362,-1427.5 2356,-1427.5 2356,-1427.5 1991,-1427.5 1991,-1427.5 1985,-1427.5 1979,-1421.5 1979,-1415.5 1979,-1415.5 1979,-1025.5 1979,-1025.5 1979,-1019.5 1985,-1013.5 1991,-1013.5"/>
<text text-anchor="middle" x="2021" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="2063,-1013.5 2063,-1427.5 "/>
<text text-anchor="middle" x="2073.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2084,-1013.5 2084,-1427.5 "/>
<text text-anchor="middle" x="2215.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2084,-1404.5 2347,-1404.5 "/>
<text text-anchor="middle" x="2215.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="2084,-1381.5 2347,-1381.5 "/>
<text text-anchor="middle" x="2215.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="2084,-1358.5 2347,-1358.5 "/>
<text text-anchor="middle" x="2215.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="2084,-1335.5 2347,-1335.5 "/>
<text text-anchor="middle" x="2215.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_category</text>
<polyline fill="none" stroke="#000000" points="2084,-1312.5 2347,-1312.5 "/>
<text text-anchor="middle" x="2215.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="2084,-1289.5 2347,-1289.5 "/>
<text text-anchor="middle" x="2215.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="2084,-1266.5 2347,-1266.5 "/>
<text text-anchor="middle" x="2215.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2084,-1243.5 2347,-1243.5 "/>
<text text-anchor="middle" x="2215.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="2084,-1220.5 2347,-1220.5 "/>
<text text-anchor="middle" x="2215.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2084,-1197.5 2347,-1197.5 "/>
<text text-anchor="middle" x="2215.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">laterality</text>
<polyline fill="none" stroke="#000000" points="2084,-1174.5 2347,-1174.5 "/>
<text text-anchor="middle" x="2215.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="2084,-1151.5 2347,-1151.5 "/>
<text text-anchor="middle" x="2215.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="2084,-1128.5 2347,-1128.5 "/>
<text text-anchor="middle" x="2215.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2084,-1105.5 2347,-1105.5 "/>
<text text-anchor="middle" x="2215.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2084,-1082.5 2347,-1082.5 "/>
<text text-anchor="middle" x="2215.5" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2084,-1059.5 2347,-1059.5 "/>
<text text-anchor="middle" x="2215.5" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2084,-1036.5 2347,-1036.5 "/>
<text text-anchor="middle" x="2215.5" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2347,-1013.5 2347,-1427.5 "/>
<text text-anchor="middle" x="2357.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2018.0567,-1013.2153C1983.4333,-978.0509 1944.4224,-945.1578 1902.5,-921 1808.393,-866.7707 1763.8372,-911.5859 1663.5,-870 1657.9407,-867.6959 1652.366,-865.2155 1646.8007,-862.5907"/>
<polygon fill="#000000" stroke="#000000" points="1647.9714,-859.2682 1637.4477,-858.0428 1644.9103,-865.5634 1647.9714,-859.2682"/>
<text text-anchor="middle" x="1905" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2237.4828,-1013.2428C2261.6902,-890.3503 2265.4752,-739.4699 2178.5,-639 2122.4166,-574.2149 1568.6519,-551.6005 1305.297,-544.4671"/>
<polygon fill="#000000" stroke="#000000" points="1305.3735,-540.968 1295.2836,-544.1995 1305.1865,-547.9655 1305.3735,-540.968"/>
<text text-anchor="middle" x="2296" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- laboratory_test -->
<g id="node5" class="node">
<title>laboratory_test</title>
<path fill="none" stroke="#000000" d="M1096.5,-1094C1096.5,-1094 1428.5,-1094 1428.5,-1094 1434.5,-1094 1440.5,-1100 1440.5,-1106 1440.5,-1106 1440.5,-1335 1440.5,-1335 1440.5,-1341 1434.5,-1347 1428.5,-1347 1428.5,-1347 1096.5,-1347 1096.5,-1347 1090.5,-1347 1084.5,-1341 1084.5,-1335 1084.5,-1335 1084.5,-1106 1084.5,-1106 1084.5,-1100 1090.5,-1094 1096.5,-1094"/>
<text text-anchor="middle" x="1147.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="1210.5,-1094 1210.5,-1347 "/>
<text text-anchor="middle" x="1221" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1231.5,-1094 1231.5,-1347 "/>
<text text-anchor="middle" x="1325.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_laboratory_test</text>
<polyline fill="none" stroke="#000000" points="1231.5,-1324 1419.5,-1324 "/>
<text text-anchor="middle" x="1325.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1231.5,-1301 1419.5,-1301 "/>
<text text-anchor="middle" x="1325.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_id</text>
<polyline fill="none" stroke="#000000" points="1231.5,-1278 1419.5,-1278 "/>
<text text-anchor="middle" x="1325.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_method</text>
<polyline fill="none" stroke="#000000" points="1231.5,-1255 1419.5,-1255 "/>
<text text-anchor="middle" x="1325.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_name</text>
<polyline fill="none" stroke="#000000" points="1231.5,-1232 1419.5,-1232 "/>
<text text-anchor="middle" x="1325.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">sensitivity</text>
<polyline fill="none" stroke="#000000" points="1231.5,-1209 1419.5,-1209 "/>
<text text-anchor="middle" x="1325.5" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">specimen</text>
<polyline fill="none" stroke="#000000" points="1231.5,-1186 1419.5,-1186 "/>
<text text-anchor="middle" x="1325.5" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_modifier</text>
<polyline fill="none" stroke="#000000" points="1231.5,-1163 1419.5,-1163 "/>
<text text-anchor="middle" x="1325.5" y="-1147.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_numeric</text>
<polyline fill="none" stroke="#000000" points="1231.5,-1140 1419.5,-1140 "/>
<text text-anchor="middle" x="1325.5" y="-1124.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_text</text>
<polyline fill="none" stroke="#000000" points="1231.5,-1117 1419.5,-1117 "/>
<text text-anchor="middle" x="1325.5" y="-1101.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_unit</text>
<polyline fill="none" stroke="#000000" points="1419.5,-1094 1419.5,-1347 "/>
<text text-anchor="middle" x="1430" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1316.2621,-1093.7989C1343.5583,-1031.2631 1377.9726,-955.0432 1411.5,-888 1414.9169,-881.1674 1418.5026,-874.1807 1422.1758,-867.1613"/>
<polygon fill="#000000" stroke="#000000" points="1425.3003,-868.7398 1426.8692,-858.2617 1419.1085,-865.4744 1425.3003,-868.7398"/>
<text text-anchor="middle" x="1477" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1224.538,-1093.9795C1206.477,-1027.8862 1186.6496,-945.2889 1176.5,-870 1163.7119,-775.1383 1163.82,-663.522 1165.4135,-597.8558"/>
<polygon fill="#000000" stroke="#000000" points="1168.9158,-597.8095 1165.6802,-587.7209 1161.9182,-597.6253 1168.9158,-597.8095"/>
<text text-anchor="middle" x="1242" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- consent_group -->
<g id="node12" class="node">
<title>consent_group</title>
<path fill="none" stroke="#000000" d="M898,-271C898,-271 1223,-271 1223,-271 1229,-271 1235,-277 1235,-283 1235,-283 1235,-374 1235,-374 1235,-380 1229,-386 1223,-386 1223,-386 898,-386 898,-386 892,-386 886,-380 886,-374 886,-374 886,-283 886,-283 886,-277 892,-271 898,-271"/>
<text text-anchor="middle" x="947" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
<polyline fill="none" stroke="#000000" points="1008,-271 1008,-386 "/>
<text text-anchor="middle" x="1018.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1029,-271 1029,-386 "/>
<text text-anchor="middle" x="1121.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_id</text>
<polyline fill="none" stroke="#000000" points="1029,-363 1214,-363 "/>
<text text-anchor="middle" x="1121.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_name</text>
<polyline fill="none" stroke="#000000" points="1029,-340 1214,-340 "/>
<text text-anchor="middle" x="1121.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_number</text>
<polyline fill="none" stroke="#000000" points="1029,-317 1214,-317 "/>
<text text-anchor="middle" x="1121.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_suffix</text>
<polyline fill="none" stroke="#000000" points="1029,-294 1214,-294 "/>
<text text-anchor="middle" x="1121.5" y="-278.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1214,-271 1214,-386 "/>
<text text-anchor="middle" x="1224.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge13" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1144.2826,-495.2822C1129.5629,-465.9804 1110.2831,-427.6009 1093.9294,-395.0464"/>
<polygon fill="#000000" stroke="#000000" points="1097.0172,-393.396 1089.4007,-386.0312 1090.7621,-396.5382 1097.0172,-393.396"/>
<text text-anchor="middle" x="1184" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- treatment -->
<g id="node7" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M1684.5,-639.5C1684.5,-639.5 1976.5,-639.5 1976.5,-639.5 1982.5,-639.5 1988.5,-645.5 1988.5,-651.5 1988.5,-651.5 1988.5,-857.5 1988.5,-857.5 1988.5,-863.5 1982.5,-869.5 1976.5,-869.5 1976.5,-869.5 1684.5,-869.5 1684.5,-869.5 1678.5,-869.5 1672.5,-863.5 1672.5,-857.5 1672.5,-857.5 1672.5,-651.5 1672.5,-651.5 1672.5,-645.5 1678.5,-639.5 1684.5,-639.5"/>
<text text-anchor="middle" x="1717" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1761.5,-639.5 1761.5,-869.5 "/>
<text text-anchor="middle" x="1772" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1782.5,-639.5 1782.5,-869.5 "/>
<text text-anchor="middle" x="1875" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="1782.5,-846.5 1967.5,-846.5 "/>
<text text-anchor="middle" x="1875" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1782.5,-823.5 1967.5,-823.5 "/>
<text text-anchor="middle" x="1875" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose</text>
<polyline fill="none" stroke="#000000" points="1782.5,-800.5 1967.5,-800.5 "/>
<text text-anchor="middle" x="1875" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_frequency</text>
<polyline fill="none" stroke="#000000" points="1782.5,-777.5 1967.5,-777.5 "/>
<text text-anchor="middle" x="1875" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_route</text>
<polyline fill="none" stroke="#000000" points="1782.5,-754.5 1967.5,-754.5 "/>
<text text-anchor="middle" x="1875" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_unit</text>
<polyline fill="none" stroke="#000000" points="1782.5,-731.5 1967.5,-731.5 "/>
<text text-anchor="middle" x="1875" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1782.5,-708.5 1967.5,-708.5 "/>
<text text-anchor="middle" x="1875" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="1782.5,-685.5 1967.5,-685.5 "/>
<text text-anchor="middle" x="1875" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1782.5,-662.5 1967.5,-662.5 "/>
<text text-anchor="middle" x="1875" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1967.5,-639.5 1967.5,-869.5 "/>
<text text-anchor="middle" x="1978" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1672.2672,-642.8653C1669.3463,-641.5245 1666.4227,-640.2343 1663.5,-639 1548.0958,-590.264 1407.1739,-565.5638 1305.0736,-553.2477"/>
<polygon fill="#000000" stroke="#000000" points="1305.347,-549.7557 1295.0054,-552.0581 1304.5256,-556.7074 1305.347,-549.7557"/>
<text text-anchor="middle" x="1659.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- study -->
<g id="node8" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M502,-.5C502,-.5 721,-.5 721,-.5 727,-.5 733,-6.5 733,-12.5 733,-12.5 733,-149.5 733,-149.5 733,-155.5 727,-161.5 721,-161.5 721,-161.5 502,-161.5 502,-161.5 496,-161.5 490,-155.5 490,-149.5 490,-149.5 490,-12.5 490,-12.5 490,-6.5 496,-.5 502,-.5"/>
<text text-anchor="middle" x="518" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="546,-.5 546,-161.5 "/>
<text text-anchor="middle" x="556.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="567,-.5 567,-161.5 "/>
<text text-anchor="middle" x="639.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession</text>
<polyline fill="none" stroke="#000000" points="567,-138.5 712,-138.5 "/>
<text text-anchor="middle" x="639.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="567,-115.5 712,-115.5 "/>
<text text-anchor="middle" x="639.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="567,-92.5 712,-92.5 "/>
<text text-anchor="middle" x="639.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="567,-69.5 712,-69.5 "/>
<text text-anchor="middle" x="639.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="567,-46.5 712,-46.5 "/>
<text text-anchor="middle" x="639.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="567,-23.5 712,-23.5 "/>
<text text-anchor="middle" x="639.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
<polyline fill="none" stroke="#000000" points="712,-.5 712,-161.5 "/>
<text text-anchor="middle" x="722.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym -->
<g id="node9" class="node">
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
<!-- synonym&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M264.9005,-673.9969C286.5488,-660.3095 309.988,-647.7218 333.5,-639 457.8275,-592.8808 826.6463,-563.0706 1029.6666,-549.681"/>
<polygon fill="#000000" stroke="#000000" points="1030.0551,-553.1632 1039.805,-549.0169 1029.5975,-546.1781 1030.0551,-553.1632"/>
<text text-anchor="middle" x="511" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge11" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M193.7677,-673.8051C239.3792,-562.538 331.9098,-359.1983 451.5,-213 464.2361,-197.4301 479.0321,-182.3703 494.3825,-168.3391"/>
<polygon fill="#000000" stroke="#000000" points="496.8556,-170.8223 501.9561,-161.536 492.1778,-165.6148 496.8556,-170.8223"/>
<text text-anchor="middle" x="335" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- reference_file -->
<g id="node10" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M473,-213.5C473,-213.5 750,-213.5 750,-213.5 756,-213.5 762,-219.5 762,-225.5 762,-225.5 762,-431.5 762,-431.5 762,-437.5 756,-443.5 750,-443.5 750,-443.5 473,-443.5 473,-443.5 467,-443.5 461,-437.5 461,-431.5 461,-431.5 461,-225.5 461,-225.5 461,-219.5 467,-213.5 473,-213.5"/>
<text text-anchor="middle" x="519" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="577,-213.5 577,-443.5 "/>
<text text-anchor="middle" x="587.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="598,-213.5 598,-443.5 "/>
<text text-anchor="middle" x="669.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="598,-420.5 741,-420.5 "/>
<text text-anchor="middle" x="669.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="598,-397.5 741,-397.5 "/>
<text text-anchor="middle" x="669.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="598,-374.5 741,-374.5 "/>
<text text-anchor="middle" x="669.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="598,-351.5 741,-351.5 "/>
<text text-anchor="middle" x="669.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="598,-328.5 741,-328.5 "/>
<text text-anchor="middle" x="669.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="598,-305.5 741,-305.5 "/>
<text text-anchor="middle" x="669.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="598,-282.5 741,-282.5 "/>
<text text-anchor="middle" x="669.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="598,-259.5 741,-259.5 "/>
<text text-anchor="middle" x="669.5" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="598,-236.5 741,-236.5 "/>
<text text-anchor="middle" x="669.5" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="741,-213.5 741,-443.5 "/>
<text text-anchor="middle" x="751.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge14" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M611.5,-213.4448C611.5,-199.4621 611.5,-185.3307 611.5,-171.7693"/>
<polygon fill="#000000" stroke="#000000" points="615.0001,-171.5218 611.5,-161.5218 608.0001,-171.5219 615.0001,-171.5218"/>
<text text-anchor="middle" x="672" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- genetic_analysis -->
<g id="node11" class="node">
<title>genetic_analysis</title>
<path fill="none" stroke="#000000" d="M1497.5,-921.5C1497.5,-921.5 1881.5,-921.5 1881.5,-921.5 1887.5,-921.5 1893.5,-927.5 1893.5,-933.5 1893.5,-933.5 1893.5,-1507.5 1893.5,-1507.5 1893.5,-1513.5 1887.5,-1519.5 1881.5,-1519.5 1881.5,-1519.5 1497.5,-1519.5 1497.5,-1519.5 1491.5,-1519.5 1485.5,-1513.5 1485.5,-1507.5 1485.5,-1507.5 1485.5,-933.5 1485.5,-933.5 1485.5,-927.5 1491.5,-921.5 1497.5,-921.5"/>
<text text-anchor="middle" x="1553" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="1620.5,-921.5 1620.5,-1519.5 "/>
<text text-anchor="middle" x="1631" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1641.5,-921.5 1641.5,-1519.5 "/>
<text text-anchor="middle" x="1757" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="1641.5,-1496.5 1872.5,-1496.5 "/>
<text text-anchor="middle" x="1757" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">allelic_ratio</text>
<polyline fill="none" stroke="#000000" points="1641.5,-1473.5 1872.5,-1473.5 "/>
<text text-anchor="middle" x="1757" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration</text>
<polyline fill="none" stroke="#000000" points="1641.5,-1450.5 1872.5,-1450.5 "/>
<text text-anchor="middle" x="1757" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration_effect</text>
<polyline fill="none" stroke="#000000" points="1641.5,-1427.5 1872.5,-1427.5 "/>
<text text-anchor="middle" x="1757" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration_type</text>
<polyline fill="none" stroke="#000000" points="1641.5,-1404.5 1872.5,-1404.5 "/>
<text text-anchor="middle" x="1757" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="1641.5,-1381.5 1872.5,-1381.5 "/>
<text text-anchor="middle" x="1757" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="1641.5,-1358.5 1872.5,-1358.5 "/>
<text text-anchor="middle" x="1757" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">dna_index_numeric</text>
<polyline fill="none" stroke="#000000" points="1641.5,-1335.5 1872.5,-1335.5 "/>
<text text-anchor="middle" x="1757" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="1641.5,-1312.5 1872.5,-1312.5 "/>
<text text-anchor="middle" x="1757" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_exon</text>
<polyline fill="none" stroke="#000000" points="1641.5,-1289.5 1872.5,-1289.5 "/>
<text text-anchor="middle" x="1757" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_gene</text>
<polyline fill="none" stroke="#000000" points="1641.5,-1266.5 1872.5,-1266.5 "/>
<text text-anchor="middle" x="1757" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_transcript</text>
<polyline fill="none" stroke="#000000" points="1641.5,-1243.5 1872.5,-1243.5 "/>
<text text-anchor="middle" x="1757" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="1641.5,-1220.5 1872.5,-1220.5 "/>
<text text-anchor="middle" x="1757" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis_id</text>
<polyline fill="none" stroke="#000000" points="1641.5,-1197.5 1872.5,-1197.5 "/>
<text text-anchor="middle" x="1757" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_source_category</text>
<polyline fill="none" stroke="#000000" points="1641.5,-1174.5 1872.5,-1174.5 "/>
<text text-anchor="middle" x="1757" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_coding</text>
<polyline fill="none" stroke="#000000" points="1641.5,-1151.5 1872.5,-1151.5 "/>
<text text-anchor="middle" x="1757" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_genome</text>
<polyline fill="none" stroke="#000000" points="1641.5,-1128.5 1872.5,-1128.5 "/>
<text text-anchor="middle" x="1757" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_protein</text>
<polyline fill="none" stroke="#000000" points="1641.5,-1105.5 1872.5,-1105.5 "/>
<text text-anchor="middle" x="1757" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1641.5,-1082.5 1872.5,-1082.5 "/>
<text text-anchor="middle" x="1757" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">iscn</text>
<polyline fill="none" stroke="#000000" points="1641.5,-1059.5 1872.5,-1059.5 "/>
<text text-anchor="middle" x="1757" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">method</text>
<polyline fill="none" stroke="#000000" points="1641.5,-1036.5 1872.5,-1036.5 "/>
<text text-anchor="middle" x="1757" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome</text>
<polyline fill="none" stroke="#000000" points="1641.5,-1013.5 1872.5,-1013.5 "/>
<text text-anchor="middle" x="1757" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance</text>
<polyline fill="none" stroke="#000000" points="1641.5,-990.5 1872.5,-990.5 "/>
<text text-anchor="middle" x="1757" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance_system</text>
<polyline fill="none" stroke="#000000" points="1641.5,-967.5 1872.5,-967.5 "/>
<text text-anchor="middle" x="1757" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">result</text>
<polyline fill="none" stroke="#000000" points="1641.5,-944.5 1872.5,-944.5 "/>
<text text-anchor="middle" x="1757" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 6 properties</text>
<polyline fill="none" stroke="#000000" points="1872.5,-921.5 1872.5,-1519.5 "/>
<text text-anchor="middle" x="1883" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1558.5725,-921.4205C1550.3889,-902.7265 1542.4761,-884.6513 1535.0698,-867.733"/>
<polygon fill="#000000" stroke="#000000" points="1538.2254,-866.2135 1531.0088,-858.4565 1531.8129,-869.0208 1538.2254,-866.2135"/>
<text text-anchor="middle" x="1616.5" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1893.8447,-1012.5287C1942.7577,-957.5571 1984.6424,-904.1102 1997.5,-870 2033.7123,-773.9317 2065.7302,-715.7143 1997.5,-639 1952.3926,-588.2836 1529.7651,-559.6163 1305.6172,-547.8618"/>
<polygon fill="#000000" stroke="#000000" points="1305.5932,-544.3559 1295.4249,-547.3318 1305.2296,-551.3465 1305.5932,-544.3559"/>
<text text-anchor="middle" x="2107.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge7" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M956.0791,-270.9406C892.3523,-235.8128 810.3339,-190.6022 742.3041,-153.1025"/>
<polygon fill="#000000" stroke="#000000" points="743.6757,-149.8621 733.2285,-148.0998 740.2965,-155.9924 743.6757,-149.8621"/>
<text text-anchor="middle" x="873" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
</g>
</svg>
</div>
