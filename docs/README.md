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
<svg width="2702pt" height="1528pt"
 viewBox="0.00 0.00 2701.50 1528.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1524)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1524 2697.5,-1524 2697.5,4 -4,4"/>
<!-- sample -->
<g id="node1" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M623,-651C623,-651 937,-651 937,-651 943,-651 949,-657 949,-663 949,-663 949,-846 949,-846 949,-852 943,-858 937,-858 937,-858 623,-858 623,-858 617,-858 611,-852 611,-846 611,-846 611,-663 611,-663 611,-657 617,-651 623,-651"/>
<text text-anchor="middle" x="645" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="679,-651 679,-858 "/>
<text text-anchor="middle" x="689.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="700,-651 700,-858 "/>
<text text-anchor="middle" x="814" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="700,-835 928,-835 "/>
<text text-anchor="middle" x="814" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="700,-812 928,-812 "/>
<text text-anchor="middle" x="814" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="700,-789 928,-789 "/>
<text text-anchor="middle" x="814" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_necrosis</text>
<polyline fill="none" stroke="#000000" points="700,-766 928,-766 "/>
<text text-anchor="middle" x="814" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_tumor</text>
<polyline fill="none" stroke="#000000" points="700,-743 928,-743 "/>
<text text-anchor="middle" x="814" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="700,-720 928,-720 "/>
<text text-anchor="middle" x="814" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="700,-697 928,-697 "/>
<text text-anchor="middle" x="814" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="700,-674 928,-674 "/>
<text text-anchor="middle" x="814" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="928,-651 928,-858 "/>
<text text-anchor="middle" x="938.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node5" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1169.5,-495.5C1169.5,-495.5 1400.5,-495.5 1400.5,-495.5 1406.5,-495.5 1412.5,-501.5 1412.5,-507.5 1412.5,-507.5 1412.5,-575.5 1412.5,-575.5 1412.5,-581.5 1406.5,-587.5 1400.5,-587.5 1400.5,-587.5 1169.5,-587.5 1169.5,-587.5 1163.5,-587.5 1157.5,-581.5 1157.5,-575.5 1157.5,-575.5 1157.5,-507.5 1157.5,-507.5 1157.5,-501.5 1163.5,-495.5 1169.5,-495.5"/>
<text text-anchor="middle" x="1205.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1253.5,-495.5 1253.5,-587.5 "/>
<text text-anchor="middle" x="1264" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1274.5,-495.5 1274.5,-587.5 "/>
<text text-anchor="middle" x="1333" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1274.5,-564.5 1391.5,-564.5 "/>
<text text-anchor="middle" x="1333" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1274.5,-541.5 1391.5,-541.5 "/>
<text text-anchor="middle" x="1333" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1274.5,-518.5 1391.5,-518.5 "/>
<text text-anchor="middle" x="1333" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="1391.5,-495.5 1391.5,-587.5 "/>
<text text-anchor="middle" x="1402" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M845.8961,-650.6288C861.0801,-633.4003 878.5636,-617.4469 898,-606 939.5512,-581.5288 1053.5256,-564.3961 1147.0994,-553.9701"/>
<polygon fill="#000000" stroke="#000000" points="1147.6838,-557.427 1157.2424,-552.8571 1146.9202,-550.4688 1147.6838,-557.427"/>
<text text-anchor="middle" x="934.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- survival -->
<g id="node2" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M1507.5,-662.5C1507.5,-662.5 1868.5,-662.5 1868.5,-662.5 1874.5,-662.5 1880.5,-668.5 1880.5,-674.5 1880.5,-674.5 1880.5,-834.5 1880.5,-834.5 1880.5,-840.5 1874.5,-846.5 1868.5,-846.5 1868.5,-846.5 1507.5,-846.5 1507.5,-846.5 1501.5,-846.5 1495.5,-840.5 1495.5,-834.5 1495.5,-834.5 1495.5,-674.5 1495.5,-674.5 1495.5,-668.5 1501.5,-662.5 1507.5,-662.5"/>
<text text-anchor="middle" x="1532.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="1569.5,-662.5 1569.5,-846.5 "/>
<text text-anchor="middle" x="1580" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1590.5,-662.5 1590.5,-846.5 "/>
<text text-anchor="middle" x="1725" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="1590.5,-823.5 1859.5,-823.5 "/>
<text text-anchor="middle" x="1725" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="1590.5,-800.5 1859.5,-800.5 "/>
<text text-anchor="middle" x="1725" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="1590.5,-777.5 1859.5,-777.5 "/>
<text text-anchor="middle" x="1725" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="1590.5,-754.5 1859.5,-754.5 "/>
<text text-anchor="middle" x="1725" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="1590.5,-731.5 1859.5,-731.5 "/>
<text text-anchor="middle" x="1725" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1590.5,-708.5 1859.5,-708.5 "/>
<text text-anchor="middle" x="1725" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="1590.5,-685.5 1859.5,-685.5 "/>
<text text-anchor="middle" x="1725" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="1859.5,-662.5 1859.5,-846.5 "/>
<text text-anchor="middle" x="1870" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1553.6701,-662.3227C1522.0245,-642.4681 1487.9064,-622.51 1455,-606 1444.5297,-600.7468 1433.5227,-595.6612 1422.3547,-590.8051"/>
<polygon fill="#000000" stroke="#000000" points="1423.5146,-587.4946 1412.9438,-586.7813 1420.7626,-593.9309 1423.5146,-587.4946"/>
<text text-anchor="middle" x="1520.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- treatment -->
<g id="node3" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M1911,-639.5C1911,-639.5 2203,-639.5 2203,-639.5 2209,-639.5 2215,-645.5 2215,-651.5 2215,-651.5 2215,-857.5 2215,-857.5 2215,-863.5 2209,-869.5 2203,-869.5 2203,-869.5 1911,-869.5 1911,-869.5 1905,-869.5 1899,-863.5 1899,-857.5 1899,-857.5 1899,-651.5 1899,-651.5 1899,-645.5 1905,-639.5 1911,-639.5"/>
<text text-anchor="middle" x="1943.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1988,-639.5 1988,-869.5 "/>
<text text-anchor="middle" x="1998.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2009,-639.5 2009,-869.5 "/>
<text text-anchor="middle" x="2101.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="2009,-846.5 2194,-846.5 "/>
<text text-anchor="middle" x="2101.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="2009,-823.5 2194,-823.5 "/>
<text text-anchor="middle" x="2101.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose</text>
<polyline fill="none" stroke="#000000" points="2009,-800.5 2194,-800.5 "/>
<text text-anchor="middle" x="2101.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_frequency</text>
<polyline fill="none" stroke="#000000" points="2009,-777.5 2194,-777.5 "/>
<text text-anchor="middle" x="2101.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_route</text>
<polyline fill="none" stroke="#000000" points="2009,-754.5 2194,-754.5 "/>
<text text-anchor="middle" x="2101.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_unit</text>
<polyline fill="none" stroke="#000000" points="2009,-731.5 2194,-731.5 "/>
<text text-anchor="middle" x="2101.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2009,-708.5 2194,-708.5 "/>
<text text-anchor="middle" x="2101.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="2009,-685.5 2194,-685.5 "/>
<text text-anchor="middle" x="2101.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="2009,-662.5 2194,-662.5 "/>
<text text-anchor="middle" x="2101.5" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="2194,-639.5 2194,-869.5 "/>
<text text-anchor="middle" x="2204.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1898.8251,-642.7248C1895.8864,-641.4274 1892.9435,-640.184 1890,-639 1807.443,-605.7928 1574.4511,-574.3523 1422.8763,-556.5487"/>
<polygon fill="#000000" stroke="#000000" points="1422.8985,-553.0276 1412.5599,-555.3433 1422.086,-559.9803 1422.8985,-553.0276"/>
<text text-anchor="middle" x="1877" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- diagnosis -->
<g id="node4" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M812.5,-1013.5C812.5,-1013.5 1177.5,-1013.5 1177.5,-1013.5 1183.5,-1013.5 1189.5,-1019.5 1189.5,-1025.5 1189.5,-1025.5 1189.5,-1415.5 1189.5,-1415.5 1189.5,-1421.5 1183.5,-1427.5 1177.5,-1427.5 1177.5,-1427.5 812.5,-1427.5 812.5,-1427.5 806.5,-1427.5 800.5,-1421.5 800.5,-1415.5 800.5,-1415.5 800.5,-1025.5 800.5,-1025.5 800.5,-1019.5 806.5,-1013.5 812.5,-1013.5"/>
<text text-anchor="middle" x="842.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="884.5,-1013.5 884.5,-1427.5 "/>
<text text-anchor="middle" x="895" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="905.5,-1013.5 905.5,-1427.5 "/>
<text text-anchor="middle" x="1037" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="905.5,-1404.5 1168.5,-1404.5 "/>
<text text-anchor="middle" x="1037" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="905.5,-1381.5 1168.5,-1381.5 "/>
<text text-anchor="middle" x="1037" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="905.5,-1358.5 1168.5,-1358.5 "/>
<text text-anchor="middle" x="1037" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="905.5,-1335.5 1168.5,-1335.5 "/>
<text text-anchor="middle" x="1037" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_category</text>
<polyline fill="none" stroke="#000000" points="905.5,-1312.5 1168.5,-1312.5 "/>
<text text-anchor="middle" x="1037" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="905.5,-1289.5 1168.5,-1289.5 "/>
<text text-anchor="middle" x="1037" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="905.5,-1266.5 1168.5,-1266.5 "/>
<text text-anchor="middle" x="1037" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="905.5,-1243.5 1168.5,-1243.5 "/>
<text text-anchor="middle" x="1037" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="905.5,-1220.5 1168.5,-1220.5 "/>
<text text-anchor="middle" x="1037" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="905.5,-1197.5 1168.5,-1197.5 "/>
<text text-anchor="middle" x="1037" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">laterality</text>
<polyline fill="none" stroke="#000000" points="905.5,-1174.5 1168.5,-1174.5 "/>
<text text-anchor="middle" x="1037" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="905.5,-1151.5 1168.5,-1151.5 "/>
<text text-anchor="middle" x="1037" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="905.5,-1128.5 1168.5,-1128.5 "/>
<text text-anchor="middle" x="1037" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="905.5,-1105.5 1168.5,-1105.5 "/>
<text text-anchor="middle" x="1037" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="905.5,-1082.5 1168.5,-1082.5 "/>
<text text-anchor="middle" x="1037" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="905.5,-1059.5 1168.5,-1059.5 "/>
<text text-anchor="middle" x="1037" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="905.5,-1036.5 1168.5,-1036.5 "/>
<text text-anchor="middle" x="1037" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1168.5,-1013.5 1168.5,-1427.5 "/>
<text text-anchor="middle" x="1179" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M899.4458,-1013.3918C876.3064,-963.2385 852.4194,-911.4648 832.145,-867.5212"/>
<polygon fill="#000000" stroke="#000000" points="835.2425,-865.8803 827.8751,-858.2664 828.8864,-868.8129 835.2425,-865.8803"/>
<text text-anchor="middle" x="888.5" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M969.8092,-1013.3735C957.0558,-870.9486 951.9866,-697.3855 994,-639 1013.2037,-612.3129 1081.5226,-588.6969 1147.138,-571.3934"/>
<polygon fill="#000000" stroke="#000000" points="1148.4141,-574.6782 1157.2146,-568.7789 1146.6561,-567.9026 1148.4141,-574.6782"/>
<text text-anchor="middle" x="1038.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- consent_group -->
<g id="node8" class="node">
<title>consent_group</title>
<path fill="none" stroke="#000000" d="M1802.5,-271C1802.5,-271 2127.5,-271 2127.5,-271 2133.5,-271 2139.5,-277 2139.5,-283 2139.5,-283 2139.5,-374 2139.5,-374 2139.5,-380 2133.5,-386 2127.5,-386 2127.5,-386 1802.5,-386 1802.5,-386 1796.5,-386 1790.5,-380 1790.5,-374 1790.5,-374 1790.5,-283 1790.5,-283 1790.5,-277 1796.5,-271 1802.5,-271"/>
<text text-anchor="middle" x="1851.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
<polyline fill="none" stroke="#000000" points="1912.5,-271 1912.5,-386 "/>
<text text-anchor="middle" x="1923" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1933.5,-271 1933.5,-386 "/>
<text text-anchor="middle" x="2026" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_id</text>
<polyline fill="none" stroke="#000000" points="1933.5,-363 2118.5,-363 "/>
<text text-anchor="middle" x="2026" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_name</text>
<polyline fill="none" stroke="#000000" points="1933.5,-340 2118.5,-340 "/>
<text text-anchor="middle" x="2026" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_number</text>
<polyline fill="none" stroke="#000000" points="1933.5,-317 2118.5,-317 "/>
<text text-anchor="middle" x="2026" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_suffix</text>
<polyline fill="none" stroke="#000000" points="1933.5,-294 2118.5,-294 "/>
<text text-anchor="middle" x="2026" y="-278.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2118.5,-271 2118.5,-386 "/>
<text text-anchor="middle" x="2129" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge11" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1412.5037,-501.5613C1516.2096,-469.077 1663.9402,-422.8026 1780.5511,-386.2759"/>
<polygon fill="#000000" stroke="#000000" points="1781.8138,-389.5482 1790.3103,-383.219 1779.7213,-382.8682 1781.8138,-389.5482"/>
<text text-anchor="middle" x="1574.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study -->
<g id="node6" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M2254.5,-.5C2254.5,-.5 2473.5,-.5 2473.5,-.5 2479.5,-.5 2485.5,-6.5 2485.5,-12.5 2485.5,-12.5 2485.5,-149.5 2485.5,-149.5 2485.5,-155.5 2479.5,-161.5 2473.5,-161.5 2473.5,-161.5 2254.5,-161.5 2254.5,-161.5 2248.5,-161.5 2242.5,-155.5 2242.5,-149.5 2242.5,-149.5 2242.5,-12.5 2242.5,-12.5 2242.5,-6.5 2248.5,-.5 2254.5,-.5"/>
<text text-anchor="middle" x="2270.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="2298.5,-.5 2298.5,-161.5 "/>
<text text-anchor="middle" x="2309" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2319.5,-.5 2319.5,-161.5 "/>
<text text-anchor="middle" x="2392" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession</text>
<polyline fill="none" stroke="#000000" points="2319.5,-138.5 2464.5,-138.5 "/>
<text text-anchor="middle" x="2392" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="2319.5,-115.5 2464.5,-115.5 "/>
<text text-anchor="middle" x="2392" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2319.5,-92.5 2464.5,-92.5 "/>
<text text-anchor="middle" x="2392" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="2319.5,-69.5 2464.5,-69.5 "/>
<text text-anchor="middle" x="2392" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="2319.5,-46.5 2464.5,-46.5 "/>
<text text-anchor="middle" x="2392" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="2319.5,-23.5 2464.5,-23.5 "/>
<text text-anchor="middle" x="2392" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
<polyline fill="none" stroke="#000000" points="2464.5,-.5 2464.5,-161.5 "/>
<text text-anchor="middle" x="2475" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genetic_analysis -->
<g id="node7" class="node">
<title>genetic_analysis</title>
<path fill="none" stroke="#000000" d="M12,-921.5C12,-921.5 396,-921.5 396,-921.5 402,-921.5 408,-927.5 408,-933.5 408,-933.5 408,-1507.5 408,-1507.5 408,-1513.5 402,-1519.5 396,-1519.5 396,-1519.5 12,-1519.5 12,-1519.5 6,-1519.5 0,-1513.5 0,-1507.5 0,-1507.5 0,-933.5 0,-933.5 0,-927.5 6,-921.5 12,-921.5"/>
<text text-anchor="middle" x="67.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="135,-921.5 135,-1519.5 "/>
<text text-anchor="middle" x="145.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="156,-921.5 156,-1519.5 "/>
<text text-anchor="middle" x="271.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="156,-1496.5 387,-1496.5 "/>
<text text-anchor="middle" x="271.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">allelic_ratio</text>
<polyline fill="none" stroke="#000000" points="156,-1473.5 387,-1473.5 "/>
<text text-anchor="middle" x="271.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration</text>
<polyline fill="none" stroke="#000000" points="156,-1450.5 387,-1450.5 "/>
<text text-anchor="middle" x="271.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="156,-1427.5 387,-1427.5 "/>
<text text-anchor="middle" x="271.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome_location</text>
<polyline fill="none" stroke="#000000" points="156,-1404.5 387,-1404.5 "/>
<text text-anchor="middle" x="271.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="156,-1381.5 387,-1381.5 "/>
<text text-anchor="middle" x="271.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">dna_index_numeric</text>
<polyline fill="none" stroke="#000000" points="156,-1358.5 387,-1358.5 "/>
<text text-anchor="middle" x="271.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="156,-1335.5 387,-1335.5 "/>
<text text-anchor="middle" x="271.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_exon</text>
<polyline fill="none" stroke="#000000" points="156,-1312.5 387,-1312.5 "/>
<text text-anchor="middle" x="271.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_gene</text>
<polyline fill="none" stroke="#000000" points="156,-1289.5 387,-1289.5 "/>
<text text-anchor="middle" x="271.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_transcript</text>
<polyline fill="none" stroke="#000000" points="156,-1266.5 387,-1266.5 "/>
<text text-anchor="middle" x="271.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="156,-1243.5 387,-1243.5 "/>
<text text-anchor="middle" x="271.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis_id</text>
<polyline fill="none" stroke="#000000" points="156,-1220.5 387,-1220.5 "/>
<text text-anchor="middle" x="271.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_source_category</text>
<polyline fill="none" stroke="#000000" points="156,-1197.5 387,-1197.5 "/>
<text text-anchor="middle" x="271.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_coding</text>
<polyline fill="none" stroke="#000000" points="156,-1174.5 387,-1174.5 "/>
<text text-anchor="middle" x="271.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_genome</text>
<polyline fill="none" stroke="#000000" points="156,-1151.5 387,-1151.5 "/>
<text text-anchor="middle" x="271.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_protein</text>
<polyline fill="none" stroke="#000000" points="156,-1128.5 387,-1128.5 "/>
<text text-anchor="middle" x="271.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="156,-1105.5 387,-1105.5 "/>
<text text-anchor="middle" x="271.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">karyotype</text>
<polyline fill="none" stroke="#000000" points="156,-1082.5 387,-1082.5 "/>
<text text-anchor="middle" x="271.5" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome</text>
<polyline fill="none" stroke="#000000" points="156,-1059.5 387,-1059.5 "/>
<text text-anchor="middle" x="271.5" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance</text>
<polyline fill="none" stroke="#000000" points="156,-1036.5 387,-1036.5 "/>
<text text-anchor="middle" x="271.5" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance_system</text>
<polyline fill="none" stroke="#000000" points="156,-1013.5 387,-1013.5 "/>
<text text-anchor="middle" x="271.5" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">result</text>
<polyline fill="none" stroke="#000000" points="156,-990.5 387,-990.5 "/>
<text text-anchor="middle" x="271.5" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="156,-967.5 387,-967.5 "/>
<text text-anchor="middle" x="271.5" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">test</text>
<polyline fill="none" stroke="#000000" points="156,-944.5 387,-944.5 "/>
<text text-anchor="middle" x="271.5" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 2 properties</text>
<polyline fill="none" stroke="#000000" points="387,-921.5 387,-1519.5 "/>
<text text-anchor="middle" x="397.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M408.1053,-927.5334C411.0431,-925.3023 414.0081,-923.1233 417,-921 484.8089,-872.878 520.8965,-903.4967 597,-870 602.3419,-867.6488 607.7094,-865.1576 613.0797,-862.552"/>
<polygon fill="#000000" stroke="#000000" points="614.717,-865.6468 622.1162,-858.0637 611.6031,-859.3775 614.717,-865.6468"/>
<text text-anchor="middle" x="594" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M182.0977,-921.3219C190.5744,-819.2628 219.7029,-712.4841 293,-639 352.1313,-579.7179 888.838,-554.3452 1147.2166,-545.493"/>
<polygon fill="#000000" stroke="#000000" points="1147.5458,-548.984 1157.4214,-545.147 1147.3085,-541.988 1147.5458,-548.984"/>
<text text-anchor="middle" x="363" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge10" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2057.7928,-270.9406C2110.0248,-238.541 2176.0846,-197.5641 2233.4648,-161.9711"/>
<polygon fill="#000000" stroke="#000000" points="2235.577,-164.7796 2242.2299,-156.5341 2231.8871,-158.8311 2235.577,-164.7796"/>
<text text-anchor="middle" x="2263.5" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- laboratory_test -->
<g id="node9" class="node">
<title>laboratory_test</title>
<path fill="none" stroke="#000000" d="M438,-1094C438,-1094 770,-1094 770,-1094 776,-1094 782,-1100 782,-1106 782,-1106 782,-1335 782,-1335 782,-1341 776,-1347 770,-1347 770,-1347 438,-1347 438,-1347 432,-1347 426,-1341 426,-1335 426,-1335 426,-1106 426,-1106 426,-1100 432,-1094 438,-1094"/>
<text text-anchor="middle" x="489" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="552,-1094 552,-1347 "/>
<text text-anchor="middle" x="562.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="573,-1094 573,-1347 "/>
<text text-anchor="middle" x="667" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_laboratory_test</text>
<polyline fill="none" stroke="#000000" points="573,-1324 761,-1324 "/>
<text text-anchor="middle" x="667" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="573,-1301 761,-1301 "/>
<text text-anchor="middle" x="667" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_id</text>
<polyline fill="none" stroke="#000000" points="573,-1278 761,-1278 "/>
<text text-anchor="middle" x="667" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_method</text>
<polyline fill="none" stroke="#000000" points="573,-1255 761,-1255 "/>
<text text-anchor="middle" x="667" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_name</text>
<polyline fill="none" stroke="#000000" points="573,-1232 761,-1232 "/>
<text text-anchor="middle" x="667" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">sensitivity</text>
<polyline fill="none" stroke="#000000" points="573,-1209 761,-1209 "/>
<text text-anchor="middle" x="667" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">specimen</text>
<polyline fill="none" stroke="#000000" points="573,-1186 761,-1186 "/>
<text text-anchor="middle" x="667" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_modifier</text>
<polyline fill="none" stroke="#000000" points="573,-1163 761,-1163 "/>
<text text-anchor="middle" x="667" y="-1147.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_numeric</text>
<polyline fill="none" stroke="#000000" points="573,-1140 761,-1140 "/>
<text text-anchor="middle" x="667" y="-1124.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_text</text>
<polyline fill="none" stroke="#000000" points="573,-1117 761,-1117 "/>
<text text-anchor="middle" x="667" y="-1101.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_unit</text>
<polyline fill="none" stroke="#000000" points="761,-1094 761,-1347 "/>
<text text-anchor="middle" x="771.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M618.9704,-1093.9519C629.7661,-1030.058 647.924,-952.6035 678,-888 681.2892,-880.9348 685.0029,-873.8902 689.0166,-866.9388"/>
<polygon fill="#000000" stroke="#000000" points="692.1208,-868.5674 694.2518,-858.1891 686.114,-864.9733 692.1208,-868.5674"/>
<text text-anchor="middle" x="743.5" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M543.1993,-1093.8841C515.1891,-1028.636 485.0851,-946.8206 471,-870 452.4846,-769.0167 402.8572,-715.7919 471,-639 515.0478,-589.3613 926.9713,-560.2997 1147.3598,-548.1797"/>
<polygon fill="#000000" stroke="#000000" points="1147.5893,-551.6725 1157.3838,-547.6329 1147.2079,-544.6829 1147.5893,-551.6725"/>
<text text-anchor="middle" x="536.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- synonym -->
<g id="node10" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M2244.5,-674C2244.5,-674 2545.5,-674 2545.5,-674 2551.5,-674 2557.5,-680 2557.5,-686 2557.5,-686 2557.5,-823 2557.5,-823 2557.5,-829 2551.5,-835 2545.5,-835 2545.5,-835 2244.5,-835 2244.5,-835 2238.5,-835 2232.5,-829 2232.5,-823 2232.5,-823 2232.5,-686 2232.5,-686 2232.5,-680 2238.5,-674 2244.5,-674"/>
<text text-anchor="middle" x="2272.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="2312.5,-674 2312.5,-835 "/>
<text text-anchor="middle" x="2323" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2333.5,-674 2333.5,-835 "/>
<text text-anchor="middle" x="2435" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_id</text>
<polyline fill="none" stroke="#000000" points="2333.5,-812 2536.5,-812 "/>
<text text-anchor="middle" x="2435" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">data_location</text>
<polyline fill="none" stroke="#000000" points="2333.5,-789 2536.5,-789 "/>
<text text-anchor="middle" x="2435" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">domain_category</text>
<polyline fill="none" stroke="#000000" points="2333.5,-766 2536.5,-766 "/>
<text text-anchor="middle" x="2435" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">domain_description</text>
<polyline fill="none" stroke="#000000" points="2333.5,-743 2536.5,-743 "/>
<text text-anchor="middle" x="2435" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2333.5,-720 2536.5,-720 "/>
<text text-anchor="middle" x="2435" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="2333.5,-697 2536.5,-697 "/>
<text text-anchor="middle" x="2435" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="2536.5,-674 2536.5,-835 "/>
<text text-anchor="middle" x="2547" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2292.6363,-673.8973C2270.985,-660.2181 2247.5352,-647.6588 2224,-639 2080.4641,-586.1918 1647.1483,-558.5614 1422.856,-547.4648"/>
<polygon fill="#000000" stroke="#000000" points="1422.8238,-543.9591 1412.6643,-546.9648 1422.4807,-550.9507 1422.8238,-543.9591"/>
<text text-anchor="middle" x="2191.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge6" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2391.2915,-673.9291C2385.4805,-547.6808 2374.2659,-304.0344 2368.178,-171.77"/>
<polygon fill="#000000" stroke="#000000" points="2371.669,-171.492 2367.7128,-161.6635 2364.6764,-171.8139 2371.669,-171.492"/>
<text text-anchor="middle" x="2423.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- treatment_response -->
<g id="node11" class="node">
<title>treatment_response</title>
<path fill="none" stroke="#000000" d="M1104.5,-685.5C1104.5,-685.5 1465.5,-685.5 1465.5,-685.5 1471.5,-685.5 1477.5,-691.5 1477.5,-697.5 1477.5,-697.5 1477.5,-811.5 1477.5,-811.5 1477.5,-817.5 1471.5,-823.5 1465.5,-823.5 1465.5,-823.5 1104.5,-823.5 1104.5,-823.5 1098.5,-823.5 1092.5,-817.5 1092.5,-811.5 1092.5,-811.5 1092.5,-697.5 1092.5,-697.5 1092.5,-691.5 1098.5,-685.5 1104.5,-685.5"/>
<text text-anchor="middle" x="1173" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
<polyline fill="none" stroke="#000000" points="1253.5,-685.5 1253.5,-823.5 "/>
<text text-anchor="middle" x="1264" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1274.5,-685.5 1274.5,-823.5 "/>
<text text-anchor="middle" x="1365.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_response</text>
<polyline fill="none" stroke="#000000" points="1274.5,-800.5 1456.5,-800.5 "/>
<text text-anchor="middle" x="1365.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1274.5,-777.5 1456.5,-777.5 "/>
<text text-anchor="middle" x="1365.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="1274.5,-754.5 1456.5,-754.5 "/>
<text text-anchor="middle" x="1365.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_category</text>
<polyline fill="none" stroke="#000000" points="1274.5,-731.5 1456.5,-731.5 "/>
<text text-anchor="middle" x="1365.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_system</text>
<polyline fill="none" stroke="#000000" points="1274.5,-708.5 1456.5,-708.5 "/>
<text text-anchor="middle" x="1365.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response_id</text>
<polyline fill="none" stroke="#000000" points="1456.5,-685.5 1456.5,-823.5 "/>
<text text-anchor="middle" x="1467" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1285,-685.345C1285,-657.1412 1285,-624.9366 1285,-598.1595"/>
<polygon fill="#000000" stroke="#000000" points="1288.5001,-597.805 1285,-587.805 1281.5001,-597.805 1288.5001,-597.805"/>
<text text-anchor="middle" x="1368" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- reference_file -->
<g id="node12" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M2404.5,-213.5C2404.5,-213.5 2681.5,-213.5 2681.5,-213.5 2687.5,-213.5 2693.5,-219.5 2693.5,-225.5 2693.5,-225.5 2693.5,-431.5 2693.5,-431.5 2693.5,-437.5 2687.5,-443.5 2681.5,-443.5 2681.5,-443.5 2404.5,-443.5 2404.5,-443.5 2398.5,-443.5 2392.5,-437.5 2392.5,-431.5 2392.5,-431.5 2392.5,-225.5 2392.5,-225.5 2392.5,-219.5 2398.5,-213.5 2404.5,-213.5"/>
<text text-anchor="middle" x="2450.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="2508.5,-213.5 2508.5,-443.5 "/>
<text text-anchor="middle" x="2519" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2529.5,-213.5 2529.5,-443.5 "/>
<text text-anchor="middle" x="2601" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2529.5,-420.5 2672.5,-420.5 "/>
<text text-anchor="middle" x="2601" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="2529.5,-397.5 2672.5,-397.5 "/>
<text text-anchor="middle" x="2601" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2529.5,-374.5 2672.5,-374.5 "/>
<text text-anchor="middle" x="2601" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2529.5,-351.5 2672.5,-351.5 "/>
<text text-anchor="middle" x="2601" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2529.5,-328.5 2672.5,-328.5 "/>
<text text-anchor="middle" x="2601" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2529.5,-305.5 2672.5,-305.5 "/>
<text text-anchor="middle" x="2601" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2529.5,-282.5 2672.5,-282.5 "/>
<text text-anchor="middle" x="2601" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2529.5,-259.5 2672.5,-259.5 "/>
<text text-anchor="middle" x="2601" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="2529.5,-236.5 2672.5,-236.5 "/>
<text text-anchor="middle" x="2601" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="2672.5,-213.5 2672.5,-443.5 "/>
<text text-anchor="middle" x="2683" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge14" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2459.7884,-213.4448C2449.1799,-198.7767 2438.4531,-183.9449 2428.208,-169.7792"/>
<polygon fill="#000000" stroke="#000000" points="2430.9323,-167.5736 2422.236,-161.5218 2425.2603,-171.6759 2430.9323,-167.5736"/>
<text text-anchor="middle" x="2502.5" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
</g>
</svg>
</div>
