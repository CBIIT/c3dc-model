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
<svg width="2438pt" height="1528pt"
 viewBox="0.00 0.00 2437.50 1528.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1524)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1524 2433.5,-1524 2433.5,4 -4,4"/>
<!-- laboratory_test -->
<g id="node1" class="node">
<title>laboratory_test</title>
<path fill="none" stroke="#000000" d="M2032.5,-1128.5C2032.5,-1128.5 2364.5,-1128.5 2364.5,-1128.5 2370.5,-1128.5 2376.5,-1134.5 2376.5,-1140.5 2376.5,-1140.5 2376.5,-1300.5 2376.5,-1300.5 2376.5,-1306.5 2370.5,-1312.5 2364.5,-1312.5 2364.5,-1312.5 2032.5,-1312.5 2032.5,-1312.5 2026.5,-1312.5 2020.5,-1306.5 2020.5,-1300.5 2020.5,-1300.5 2020.5,-1140.5 2020.5,-1140.5 2020.5,-1134.5 2026.5,-1128.5 2032.5,-1128.5"/>
<text text-anchor="middle" x="2083.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="2146.5,-1128.5 2146.5,-1312.5 "/>
<text text-anchor="middle" x="2157" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2167.5,-1128.5 2167.5,-1312.5 "/>
<text text-anchor="middle" x="2261.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_laboratory_test</text>
<polyline fill="none" stroke="#000000" points="2167.5,-1289.5 2355.5,-1289.5 "/>
<text text-anchor="middle" x="2261.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2167.5,-1266.5 2355.5,-1266.5 "/>
<text text-anchor="middle" x="2261.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_id</text>
<polyline fill="none" stroke="#000000" points="2167.5,-1243.5 2355.5,-1243.5 "/>
<text text-anchor="middle" x="2261.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_method</text>
<polyline fill="none" stroke="#000000" points="2167.5,-1220.5 2355.5,-1220.5 "/>
<text text-anchor="middle" x="2261.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_name</text>
<polyline fill="none" stroke="#000000" points="2167.5,-1197.5 2355.5,-1197.5 "/>
<text text-anchor="middle" x="2261.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_numeric</text>
<polyline fill="none" stroke="#000000" points="2167.5,-1174.5 2355.5,-1174.5 "/>
<text text-anchor="middle" x="2261.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_text</text>
<polyline fill="none" stroke="#000000" points="2167.5,-1151.5 2355.5,-1151.5 "/>
<text text-anchor="middle" x="2261.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">test_unit</text>
<polyline fill="none" stroke="#000000" points="2355.5,-1128.5 2355.5,-1312.5 "/>
<text text-anchor="middle" x="2366" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node4" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M992.5,-651C992.5,-651 1306.5,-651 1306.5,-651 1312.5,-651 1318.5,-657 1318.5,-663 1318.5,-663 1318.5,-846 1318.5,-846 1318.5,-852 1312.5,-858 1306.5,-858 1306.5,-858 992.5,-858 992.5,-858 986.5,-858 980.5,-852 980.5,-846 980.5,-846 980.5,-663 980.5,-663 980.5,-657 986.5,-651 992.5,-651"/>
<text text-anchor="middle" x="1014.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1048.5,-651 1048.5,-858 "/>
<text text-anchor="middle" x="1059" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1069.5,-651 1069.5,-858 "/>
<text text-anchor="middle" x="1183.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1069.5,-835 1297.5,-835 "/>
<text text-anchor="middle" x="1183.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1069.5,-812 1297.5,-812 "/>
<text text-anchor="middle" x="1183.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1069.5,-789 1297.5,-789 "/>
<text text-anchor="middle" x="1183.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_necrosis</text>
<polyline fill="none" stroke="#000000" points="1069.5,-766 1297.5,-766 "/>
<text text-anchor="middle" x="1183.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_tumor</text>
<polyline fill="none" stroke="#000000" points="1069.5,-743 1297.5,-743 "/>
<text text-anchor="middle" x="1183.5" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1069.5,-720 1297.5,-720 "/>
<text text-anchor="middle" x="1183.5" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1069.5,-697 1297.5,-697 "/>
<text text-anchor="middle" x="1183.5" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1069.5,-674 1297.5,-674 "/>
<text text-anchor="middle" x="1183.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1297.5,-651 1297.5,-858 "/>
<text text-anchor="middle" x="1308" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2095.7029,-1128.2425C2012.1756,-1058.9287 1888.0143,-968.1441 1762.5,-921 1671.3864,-886.7771 1419.0559,-903.0213 1327.5,-870 1321.0972,-867.6907 1314.6915,-865.1131 1308.3165,-862.318"/>
<polygon fill="#000000" stroke="#000000" points="1309.5535,-859.0354 1299.0024,-858.0731 1306.6504,-865.4051 1309.5535,-859.0354"/>
<text text-anchor="middle" x="1729" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- participant -->
<g id="node12" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1034,-495.5C1034,-495.5 1265,-495.5 1265,-495.5 1271,-495.5 1277,-501.5 1277,-507.5 1277,-507.5 1277,-575.5 1277,-575.5 1277,-581.5 1271,-587.5 1265,-587.5 1265,-587.5 1034,-587.5 1034,-587.5 1028,-587.5 1022,-581.5 1022,-575.5 1022,-575.5 1022,-507.5 1022,-507.5 1022,-501.5 1028,-495.5 1034,-495.5"/>
<text text-anchor="middle" x="1070" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1118,-495.5 1118,-587.5 "/>
<text text-anchor="middle" x="1128.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1139,-495.5 1139,-587.5 "/>
<text text-anchor="middle" x="1197.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1139,-564.5 1256,-564.5 "/>
<text text-anchor="middle" x="1197.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1139,-541.5 1256,-541.5 "/>
<text text-anchor="middle" x="1197.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1139,-518.5 1256,-518.5 "/>
<text text-anchor="middle" x="1197.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="1256,-495.5 1256,-587.5 "/>
<text text-anchor="middle" x="1266.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2238.8244,-1128.4672C2287.2036,-1002.1859 2348.1972,-775.3671 2231.5,-639 2171.2173,-568.5563 1565.1915,-548.8054 1287.3537,-543.4332"/>
<polygon fill="#000000" stroke="#000000" points="1287.2699,-539.9311 1277.2052,-543.2406 1287.137,-546.9299 1287.2699,-539.9311"/>
<text text-anchor="middle" x="2364" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- treatment_response -->
<g id="node2" class="node">
<title>treatment_response</title>
<path fill="none" stroke="#000000" d="M464,-685.5C464,-685.5 825,-685.5 825,-685.5 831,-685.5 837,-691.5 837,-697.5 837,-697.5 837,-811.5 837,-811.5 837,-817.5 831,-823.5 825,-823.5 825,-823.5 464,-823.5 464,-823.5 458,-823.5 452,-817.5 452,-811.5 452,-811.5 452,-697.5 452,-697.5 452,-691.5 458,-685.5 464,-685.5"/>
<text text-anchor="middle" x="532.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
<polyline fill="none" stroke="#000000" points="613,-685.5 613,-823.5 "/>
<text text-anchor="middle" x="623.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="634,-685.5 634,-823.5 "/>
<text text-anchor="middle" x="725" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_response</text>
<polyline fill="none" stroke="#000000" points="634,-800.5 816,-800.5 "/>
<text text-anchor="middle" x="725" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="634,-777.5 816,-777.5 "/>
<text text-anchor="middle" x="725" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="634,-754.5 816,-754.5 "/>
<text text-anchor="middle" x="725" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_category</text>
<polyline fill="none" stroke="#000000" points="634,-731.5 816,-731.5 "/>
<text text-anchor="middle" x="725" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_system</text>
<polyline fill="none" stroke="#000000" points="634,-708.5 816,-708.5 "/>
<text text-anchor="middle" x="725" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response_id</text>
<polyline fill="none" stroke="#000000" points="816,-685.5 816,-823.5 "/>
<text text-anchor="middle" x="826.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M651.34,-685.2945C657.7671,-656.6394 670.0674,-625.5891 693.5,-606 717.7822,-585.7006 886.4687,-565.8374 1011.6411,-553.6363"/>
<polygon fill="#000000" stroke="#000000" points="1012.0946,-557.1089 1021.7111,-552.6621 1011.4205,-550.1414 1012.0946,-557.1089"/>
<text text-anchor="middle" x="776.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- diagnosis -->
<g id="node3" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M808,-1013.5C808,-1013.5 1173,-1013.5 1173,-1013.5 1179,-1013.5 1185,-1019.5 1185,-1025.5 1185,-1025.5 1185,-1415.5 1185,-1415.5 1185,-1421.5 1179,-1427.5 1173,-1427.5 1173,-1427.5 808,-1427.5 808,-1427.5 802,-1427.5 796,-1421.5 796,-1415.5 796,-1415.5 796,-1025.5 796,-1025.5 796,-1019.5 802,-1013.5 808,-1013.5"/>
<text text-anchor="middle" x="838" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="880,-1013.5 880,-1427.5 "/>
<text text-anchor="middle" x="890.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="901,-1013.5 901,-1427.5 "/>
<text text-anchor="middle" x="1032.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="901,-1404.5 1164,-1404.5 "/>
<text text-anchor="middle" x="1032.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="901,-1381.5 1164,-1381.5 "/>
<text text-anchor="middle" x="1032.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="901,-1358.5 1164,-1358.5 "/>
<text text-anchor="middle" x="1032.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="901,-1335.5 1164,-1335.5 "/>
<text text-anchor="middle" x="1032.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_category</text>
<polyline fill="none" stroke="#000000" points="901,-1312.5 1164,-1312.5 "/>
<text text-anchor="middle" x="1032.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="901,-1289.5 1164,-1289.5 "/>
<text text-anchor="middle" x="1032.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="901,-1266.5 1164,-1266.5 "/>
<text text-anchor="middle" x="1032.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="901,-1243.5 1164,-1243.5 "/>
<text text-anchor="middle" x="1032.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="901,-1220.5 1164,-1220.5 "/>
<text text-anchor="middle" x="1032.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="901,-1197.5 1164,-1197.5 "/>
<text text-anchor="middle" x="1032.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">laterality</text>
<polyline fill="none" stroke="#000000" points="901,-1174.5 1164,-1174.5 "/>
<text text-anchor="middle" x="1032.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="901,-1151.5 1164,-1151.5 "/>
<text text-anchor="middle" x="1032.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="901,-1128.5 1164,-1128.5 "/>
<text text-anchor="middle" x="1032.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="901,-1105.5 1164,-1105.5 "/>
<text text-anchor="middle" x="1032.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="901,-1082.5 1164,-1082.5 "/>
<text text-anchor="middle" x="1032.5" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="901,-1059.5 1164,-1059.5 "/>
<text text-anchor="middle" x="1032.5" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="901,-1036.5 1164,-1036.5 "/>
<text text-anchor="middle" x="1032.5" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1164,-1013.5 1164,-1427.5 "/>
<text text-anchor="middle" x="1174.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1061.1657,-1013.3918C1078.2423,-963.3434 1095.8694,-911.6815 1110.8428,-867.7971"/>
<polygon fill="#000000" stroke="#000000" points="1114.1779,-868.8609 1114.0947,-858.2664 1107.5529,-866.6004 1114.1779,-868.8609"/>
<text text-anchor="middle" x="1148" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M915.5412,-1013.4434C901.8244,-966.8601 889.6105,-917.2231 882.5,-870 867.2135,-768.4777 823.6573,-723.1307 882.5,-639 898.9097,-615.5381 955.2995,-593.3137 1012.0544,-576.0251"/>
<polygon fill="#000000" stroke="#000000" points="1013.3258,-579.298 1021.9004,-573.0749 1011.3165,-572.5925 1013.3258,-579.298"/>
<text text-anchor="middle" x="927" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1149.5,-650.8078C1149.5,-632.5822 1149.5,-614.2469 1149.5,-597.9389"/>
<polygon fill="#000000" stroke="#000000" points="1153.0001,-597.5364 1149.5,-587.5365 1146.0001,-597.5365 1153.0001,-597.5364"/>
<text text-anchor="middle" x="1186" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- treatment -->
<g id="node5" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M1348.5,-639.5C1348.5,-639.5 1640.5,-639.5 1640.5,-639.5 1646.5,-639.5 1652.5,-645.5 1652.5,-651.5 1652.5,-651.5 1652.5,-857.5 1652.5,-857.5 1652.5,-863.5 1646.5,-869.5 1640.5,-869.5 1640.5,-869.5 1348.5,-869.5 1348.5,-869.5 1342.5,-869.5 1336.5,-863.5 1336.5,-857.5 1336.5,-857.5 1336.5,-651.5 1336.5,-651.5 1336.5,-645.5 1342.5,-639.5 1348.5,-639.5"/>
<text text-anchor="middle" x="1381" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1425.5,-639.5 1425.5,-869.5 "/>
<text text-anchor="middle" x="1436" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1446.5,-639.5 1446.5,-869.5 "/>
<text text-anchor="middle" x="1539" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="1446.5,-846.5 1631.5,-846.5 "/>
<text text-anchor="middle" x="1539" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1446.5,-823.5 1631.5,-823.5 "/>
<text text-anchor="middle" x="1539" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose</text>
<polyline fill="none" stroke="#000000" points="1446.5,-800.5 1631.5,-800.5 "/>
<text text-anchor="middle" x="1539" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_frequency</text>
<polyline fill="none" stroke="#000000" points="1446.5,-777.5 1631.5,-777.5 "/>
<text text-anchor="middle" x="1539" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_route</text>
<polyline fill="none" stroke="#000000" points="1446.5,-754.5 1631.5,-754.5 "/>
<text text-anchor="middle" x="1539" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_unit</text>
<polyline fill="none" stroke="#000000" points="1446.5,-731.5 1631.5,-731.5 "/>
<text text-anchor="middle" x="1539" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1446.5,-708.5 1631.5,-708.5 "/>
<text text-anchor="middle" x="1539" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="1446.5,-685.5 1631.5,-685.5 "/>
<text text-anchor="middle" x="1539" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1446.5,-662.5 1631.5,-662.5 "/>
<text text-anchor="middle" x="1539" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1631.5,-639.5 1631.5,-869.5 "/>
<text text-anchor="middle" x="1642" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1336.0989,-644.3587C1333.2177,-642.547 1330.3496,-640.7593 1327.5,-639 1301.7756,-623.1184 1273.2997,-606.9302 1246.8063,-592.4249"/>
<polygon fill="#000000" stroke="#000000" points="1248.36,-589.2856 1237.9045,-587.5731 1245.01,-595.432 1248.36,-589.2856"/>
<text text-anchor="middle" x="1341.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- reference_file -->
<g id="node6" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M12,-213.5C12,-213.5 289,-213.5 289,-213.5 295,-213.5 301,-219.5 301,-225.5 301,-225.5 301,-431.5 301,-431.5 301,-437.5 295,-443.5 289,-443.5 289,-443.5 12,-443.5 12,-443.5 6,-443.5 0,-437.5 0,-431.5 0,-431.5 0,-225.5 0,-225.5 0,-219.5 6,-213.5 12,-213.5"/>
<text text-anchor="middle" x="58" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="116,-213.5 116,-443.5 "/>
<text text-anchor="middle" x="126.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="137,-213.5 137,-443.5 "/>
<text text-anchor="middle" x="208.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="137,-420.5 280,-420.5 "/>
<text text-anchor="middle" x="208.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="137,-397.5 280,-397.5 "/>
<text text-anchor="middle" x="208.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="137,-374.5 280,-374.5 "/>
<text text-anchor="middle" x="208.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="137,-351.5 280,-351.5 "/>
<text text-anchor="middle" x="208.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="137,-328.5 280,-328.5 "/>
<text text-anchor="middle" x="208.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="137,-305.5 280,-305.5 "/>
<text text-anchor="middle" x="208.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="137,-282.5 280,-282.5 "/>
<text text-anchor="middle" x="208.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="137,-259.5 280,-259.5 "/>
<text text-anchor="middle" x="208.5" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="137,-236.5 280,-236.5 "/>
<text text-anchor="middle" x="208.5" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="280,-213.5 280,-443.5 "/>
<text text-anchor="middle" x="290.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node10" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M220,-.5C220,-.5 439,-.5 439,-.5 445,-.5 451,-6.5 451,-12.5 451,-12.5 451,-149.5 451,-149.5 451,-155.5 445,-161.5 439,-161.5 439,-161.5 220,-161.5 220,-161.5 214,-161.5 208,-155.5 208,-149.5 208,-149.5 208,-12.5 208,-12.5 208,-6.5 214,-.5 220,-.5"/>
<text text-anchor="middle" x="236" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="264,-.5 264,-161.5 "/>
<text text-anchor="middle" x="274.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="285,-.5 285,-161.5 "/>
<text text-anchor="middle" x="357.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession</text>
<polyline fill="none" stroke="#000000" points="285,-138.5 430,-138.5 "/>
<text text-anchor="middle" x="357.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="285,-115.5 430,-115.5 "/>
<text text-anchor="middle" x="357.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="285,-92.5 430,-92.5 "/>
<text text-anchor="middle" x="357.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="285,-69.5 430,-69.5 "/>
<text text-anchor="middle" x="357.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="285,-46.5 430,-46.5 "/>
<text text-anchor="middle" x="357.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="285,-23.5 430,-23.5 "/>
<text text-anchor="middle" x="357.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
<polyline fill="none" stroke="#000000" points="430,-.5 430,-161.5 "/>
<text text-anchor="middle" x="440.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge15" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M176.2184,-213.4651C181.2736,-201.6374 187.3059,-190.2265 194.5,-180 197.1103,-176.2894 199.9042,-172.6633 202.8495,-169.1251"/>
<polygon fill="#000000" stroke="#000000" points="205.5584,-171.3446 209.527,-161.5211 200.2986,-166.7256 205.5584,-171.3446"/>
<text text-anchor="middle" x="255" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- synonym -->
<g id="node7" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M121,-674C121,-674 422,-674 422,-674 428,-674 434,-680 434,-686 434,-686 434,-823 434,-823 434,-829 428,-835 422,-835 422,-835 121,-835 121,-835 115,-835 109,-829 109,-823 109,-823 109,-686 109,-686 109,-680 115,-674 121,-674"/>
<text text-anchor="middle" x="149" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="189,-674 189,-835 "/>
<text text-anchor="middle" x="199.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="210,-674 210,-835 "/>
<text text-anchor="middle" x="311.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_id</text>
<polyline fill="none" stroke="#000000" points="210,-812 413,-812 "/>
<text text-anchor="middle" x="311.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">data_location</text>
<polyline fill="none" stroke="#000000" points="210,-789 413,-789 "/>
<text text-anchor="middle" x="311.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">domain_category</text>
<polyline fill="none" stroke="#000000" points="210,-766 413,-766 "/>
<text text-anchor="middle" x="311.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">domain_description</text>
<polyline fill="none" stroke="#000000" points="210,-743 413,-743 "/>
<text text-anchor="middle" x="311.5" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="210,-720 413,-720 "/>
<text text-anchor="middle" x="311.5" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="210,-697 413,-697 "/>
<text text-anchor="middle" x="311.5" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="413,-674 413,-835 "/>
<text text-anchor="middle" x="423.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge13" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M282.8594,-673.9136C291.3183,-611.3278 302.5591,-522.3045 309.5,-444 317.6966,-351.5297 323.0766,-245.4904 326.1708,-171.998"/>
<polygon fill="#000000" stroke="#000000" points="329.6742,-171.9854 326.5923,-161.8487 322.6803,-171.6948 329.6742,-171.9854"/>
<text text-anchor="middle" x="351" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M377.9108,-673.8246C398.5682,-660.7465 420.6198,-648.4246 442.5,-639 542.0601,-596.1161 835.8189,-566.3048 1011.7906,-551.7303"/>
<polygon fill="#000000" stroke="#000000" points="1012.2239,-555.2065 1021.9034,-550.8987 1011.6502,-548.2301 1012.2239,-555.2065"/>
<text text-anchor="middle" x="599" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- consent_group -->
<g id="node8" class="node">
<title>consent_group</title>
<path fill="none" stroke="#000000" d="M678,-271C678,-271 1003,-271 1003,-271 1009,-271 1015,-277 1015,-283 1015,-283 1015,-374 1015,-374 1015,-380 1009,-386 1003,-386 1003,-386 678,-386 678,-386 672,-386 666,-380 666,-374 666,-374 666,-283 666,-283 666,-277 672,-271 678,-271"/>
<text text-anchor="middle" x="727" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
<polyline fill="none" stroke="#000000" points="788,-271 788,-386 "/>
<text text-anchor="middle" x="798.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="809,-271 809,-386 "/>
<text text-anchor="middle" x="901.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_id</text>
<polyline fill="none" stroke="#000000" points="809,-363 994,-363 "/>
<text text-anchor="middle" x="901.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_name</text>
<polyline fill="none" stroke="#000000" points="809,-340 994,-340 "/>
<text text-anchor="middle" x="901.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_number</text>
<polyline fill="none" stroke="#000000" points="809,-317 994,-317 "/>
<text text-anchor="middle" x="901.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_suffix</text>
<polyline fill="none" stroke="#000000" points="809,-294 994,-294 "/>
<text text-anchor="middle" x="901.5" y="-278.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="994,-271 994,-386 "/>
<text text-anchor="middle" x="1004.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge5" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M721.6602,-270.9406C643.4369,-233.0536 540.9975,-183.4376 460.4343,-144.4173"/>
<polygon fill="#000000" stroke="#000000" points="461.7454,-141.1635 451.2198,-139.9543 458.6941,-147.4634 461.7454,-141.1635"/>
<text text-anchor="middle" x="618" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- survival -->
<g id="node9" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M1683,-662.5C1683,-662.5 2044,-662.5 2044,-662.5 2050,-662.5 2056,-668.5 2056,-674.5 2056,-674.5 2056,-834.5 2056,-834.5 2056,-840.5 2050,-846.5 2044,-846.5 2044,-846.5 1683,-846.5 1683,-846.5 1677,-846.5 1671,-840.5 1671,-834.5 1671,-834.5 1671,-674.5 1671,-674.5 1671,-668.5 1677,-662.5 1683,-662.5"/>
<text text-anchor="middle" x="1708" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="1745,-662.5 1745,-846.5 "/>
<text text-anchor="middle" x="1755.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1766,-662.5 1766,-846.5 "/>
<text text-anchor="middle" x="1900.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="1766,-823.5 2035,-823.5 "/>
<text text-anchor="middle" x="1900.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="1766,-800.5 2035,-800.5 "/>
<text text-anchor="middle" x="1900.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="1766,-777.5 2035,-777.5 "/>
<text text-anchor="middle" x="1900.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="1766,-754.5 2035,-754.5 "/>
<text text-anchor="middle" x="1900.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="1766,-731.5 2035,-731.5 "/>
<text text-anchor="middle" x="1900.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1766,-708.5 2035,-708.5 "/>
<text text-anchor="middle" x="1900.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="1766,-685.5 2035,-685.5 "/>
<text text-anchor="middle" x="1900.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="2035,-662.5 2035,-846.5 "/>
<text text-anchor="middle" x="2045.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1715.0399,-662.4033C1697.3905,-653.634 1679.3108,-645.5782 1661.5,-639 1539.081,-593.7864 1392.0949,-568.5717 1287.0765,-555.1724"/>
<polygon fill="#000000" stroke="#000000" points="1287.405,-551.6863 1277.0467,-553.9123 1286.5324,-558.6317 1287.405,-551.6863"/>
<text text-anchor="middle" x="1647" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- genetic_analysis -->
<g id="node11" class="node">
<title>genetic_analysis</title>
<path fill="none" stroke="#000000" d="M1357.5,-921.5C1357.5,-921.5 1741.5,-921.5 1741.5,-921.5 1747.5,-921.5 1753.5,-927.5 1753.5,-933.5 1753.5,-933.5 1753.5,-1507.5 1753.5,-1507.5 1753.5,-1513.5 1747.5,-1519.5 1741.5,-1519.5 1741.5,-1519.5 1357.5,-1519.5 1357.5,-1519.5 1351.5,-1519.5 1345.5,-1513.5 1345.5,-1507.5 1345.5,-1507.5 1345.5,-933.5 1345.5,-933.5 1345.5,-927.5 1351.5,-921.5 1357.5,-921.5"/>
<text text-anchor="middle" x="1413" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="1480.5,-921.5 1480.5,-1519.5 "/>
<text text-anchor="middle" x="1491" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1501.5,-921.5 1501.5,-1519.5 "/>
<text text-anchor="middle" x="1617" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="1501.5,-1496.5 1732.5,-1496.5 "/>
<text text-anchor="middle" x="1617" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">allelic_ratio</text>
<polyline fill="none" stroke="#000000" points="1501.5,-1473.5 1732.5,-1473.5 "/>
<text text-anchor="middle" x="1617" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration</text>
<polyline fill="none" stroke="#000000" points="1501.5,-1450.5 1732.5,-1450.5 "/>
<text text-anchor="middle" x="1617" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="1501.5,-1427.5 1732.5,-1427.5 "/>
<text text-anchor="middle" x="1617" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome_location</text>
<polyline fill="none" stroke="#000000" points="1501.5,-1404.5 1732.5,-1404.5 "/>
<text text-anchor="middle" x="1617" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="1501.5,-1381.5 1732.5,-1381.5 "/>
<text text-anchor="middle" x="1617" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">dna_index_numeric</text>
<polyline fill="none" stroke="#000000" points="1501.5,-1358.5 1732.5,-1358.5 "/>
<text text-anchor="middle" x="1617" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="1501.5,-1335.5 1732.5,-1335.5 "/>
<text text-anchor="middle" x="1617" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_exon</text>
<polyline fill="none" stroke="#000000" points="1501.5,-1312.5 1732.5,-1312.5 "/>
<text text-anchor="middle" x="1617" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_gene</text>
<polyline fill="none" stroke="#000000" points="1501.5,-1289.5 1732.5,-1289.5 "/>
<text text-anchor="middle" x="1617" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_transcript</text>
<polyline fill="none" stroke="#000000" points="1501.5,-1266.5 1732.5,-1266.5 "/>
<text text-anchor="middle" x="1617" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="1501.5,-1243.5 1732.5,-1243.5 "/>
<text text-anchor="middle" x="1617" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis_id</text>
<polyline fill="none" stroke="#000000" points="1501.5,-1220.5 1732.5,-1220.5 "/>
<text text-anchor="middle" x="1617" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_source_category</text>
<polyline fill="none" stroke="#000000" points="1501.5,-1197.5 1732.5,-1197.5 "/>
<text text-anchor="middle" x="1617" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_coding</text>
<polyline fill="none" stroke="#000000" points="1501.5,-1174.5 1732.5,-1174.5 "/>
<text text-anchor="middle" x="1617" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_genome</text>
<polyline fill="none" stroke="#000000" points="1501.5,-1151.5 1732.5,-1151.5 "/>
<text text-anchor="middle" x="1617" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_protein</text>
<polyline fill="none" stroke="#000000" points="1501.5,-1128.5 1732.5,-1128.5 "/>
<text text-anchor="middle" x="1617" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1501.5,-1105.5 1732.5,-1105.5 "/>
<text text-anchor="middle" x="1617" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">karyotype</text>
<polyline fill="none" stroke="#000000" points="1501.5,-1082.5 1732.5,-1082.5 "/>
<text text-anchor="middle" x="1617" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome</text>
<polyline fill="none" stroke="#000000" points="1501.5,-1059.5 1732.5,-1059.5 "/>
<text text-anchor="middle" x="1617" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance</text>
<polyline fill="none" stroke="#000000" points="1501.5,-1036.5 1732.5,-1036.5 "/>
<text text-anchor="middle" x="1617" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance_system</text>
<polyline fill="none" stroke="#000000" points="1501.5,-1013.5 1732.5,-1013.5 "/>
<text text-anchor="middle" x="1617" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">result</text>
<polyline fill="none" stroke="#000000" points="1501.5,-990.5 1732.5,-990.5 "/>
<text text-anchor="middle" x="1617" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="1501.5,-967.5 1732.5,-967.5 "/>
<text text-anchor="middle" x="1617" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">test</text>
<polyline fill="none" stroke="#000000" points="1501.5,-944.5 1732.5,-944.5 "/>
<text text-anchor="middle" x="1617" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 2 properties</text>
<polyline fill="none" stroke="#000000" points="1732.5,-921.5 1732.5,-1519.5 "/>
<text text-anchor="middle" x="1743" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1345.3987,-982.722C1310.3918,-941.9389 1275.5524,-901.3511 1245.1732,-865.9593"/>
<polygon fill="#000000" stroke="#000000" points="1247.5279,-863.3288 1238.3588,-858.0205 1242.2163,-867.8882 1247.5279,-863.3288"/>
<text text-anchor="middle" x="1338.5" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1753.5585,-1094.7799C1889.8835,-1008.65 2047.459,-904.064 2065.5,-870 2089.5256,-824.6361 2099.8235,-677.1708 2065.5,-639 2014.5037,-582.2875 1530.8916,-555.9567 1287.7126,-546.2195"/>
<polygon fill="#000000" stroke="#000000" points="1287.5154,-542.709 1277.3846,-545.8101 1287.2381,-549.7035 1287.5154,-542.709"/>
<text text-anchor="middle" x="2157.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge4" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1082.4516,-495.2822C1038.4901,-464.9786 980.4436,-424.966 932.2258,-391.7285"/>
<polygon fill="#000000" stroke="#000000" points="934.1806,-388.825 923.9608,-386.0312 930.2078,-394.5884 934.1806,-388.825"/>
<text text-anchor="middle" x="1101" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
</g>
</svg>
</div>
