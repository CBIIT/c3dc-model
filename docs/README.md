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
<svg width="2326pt" height="1528pt"
 viewBox="0.00 0.00 2325.50 1528.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1524)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1524 2321.5,-1524 2321.5,4 -4,4"/>
<!-- diagnosis -->
<g id="node1" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1857,-1013.5C1857,-1013.5 2222,-1013.5 2222,-1013.5 2228,-1013.5 2234,-1019.5 2234,-1025.5 2234,-1025.5 2234,-1415.5 2234,-1415.5 2234,-1421.5 2228,-1427.5 2222,-1427.5 2222,-1427.5 1857,-1427.5 1857,-1427.5 1851,-1427.5 1845,-1421.5 1845,-1415.5 1845,-1415.5 1845,-1025.5 1845,-1025.5 1845,-1019.5 1851,-1013.5 1857,-1013.5"/>
<text text-anchor="middle" x="1887" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1929,-1013.5 1929,-1427.5 "/>
<text text-anchor="middle" x="1939.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1950,-1013.5 1950,-1427.5 "/>
<text text-anchor="middle" x="2081.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1950,-1404.5 2213,-1404.5 "/>
<text text-anchor="middle" x="2081.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1950,-1381.5 2213,-1381.5 "/>
<text text-anchor="middle" x="2081.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1950,-1358.5 2213,-1358.5 "/>
<text text-anchor="middle" x="2081.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="1950,-1335.5 2213,-1335.5 "/>
<text text-anchor="middle" x="2081.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_category</text>
<polyline fill="none" stroke="#000000" points="1950,-1312.5 2213,-1312.5 "/>
<text text-anchor="middle" x="2081.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="1950,-1289.5 2213,-1289.5 "/>
<text text-anchor="middle" x="2081.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="1950,-1266.5 2213,-1266.5 "/>
<text text-anchor="middle" x="2081.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1950,-1243.5 2213,-1243.5 "/>
<text text-anchor="middle" x="2081.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="1950,-1220.5 2213,-1220.5 "/>
<text text-anchor="middle" x="2081.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1950,-1197.5 2213,-1197.5 "/>
<text text-anchor="middle" x="2081.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">laterality</text>
<polyline fill="none" stroke="#000000" points="1950,-1174.5 2213,-1174.5 "/>
<text text-anchor="middle" x="2081.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="1950,-1151.5 2213,-1151.5 "/>
<text text-anchor="middle" x="2081.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1950,-1128.5 2213,-1128.5 "/>
<text text-anchor="middle" x="2081.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1950,-1105.5 2213,-1105.5 "/>
<text text-anchor="middle" x="2081.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1950,-1082.5 2213,-1082.5 "/>
<text text-anchor="middle" x="2081.5" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1950,-1059.5 2213,-1059.5 "/>
<text text-anchor="middle" x="2081.5" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1950,-1036.5 2213,-1036.5 "/>
<text text-anchor="middle" x="2081.5" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2213,-1013.5 2213,-1427.5 "/>
<text text-anchor="middle" x="2223.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node8" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M925.5,-651C925.5,-651 1239.5,-651 1239.5,-651 1245.5,-651 1251.5,-657 1251.5,-663 1251.5,-663 1251.5,-846 1251.5,-846 1251.5,-852 1245.5,-858 1239.5,-858 1239.5,-858 925.5,-858 925.5,-858 919.5,-858 913.5,-852 913.5,-846 913.5,-846 913.5,-663 913.5,-663 913.5,-657 919.5,-651 925.5,-651"/>
<text text-anchor="middle" x="947.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="981.5,-651 981.5,-858 "/>
<text text-anchor="middle" x="992" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1002.5,-651 1002.5,-858 "/>
<text text-anchor="middle" x="1116.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1002.5,-835 1230.5,-835 "/>
<text text-anchor="middle" x="1116.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1002.5,-812 1230.5,-812 "/>
<text text-anchor="middle" x="1116.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1002.5,-789 1230.5,-789 "/>
<text text-anchor="middle" x="1116.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_necrosis</text>
<polyline fill="none" stroke="#000000" points="1002.5,-766 1230.5,-766 "/>
<text text-anchor="middle" x="1116.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_tumor</text>
<polyline fill="none" stroke="#000000" points="1002.5,-743 1230.5,-743 "/>
<text text-anchor="middle" x="1116.5" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1002.5,-720 1230.5,-720 "/>
<text text-anchor="middle" x="1116.5" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1002.5,-697 1230.5,-697 "/>
<text text-anchor="middle" x="1116.5" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1002.5,-674 1230.5,-674 "/>
<text text-anchor="middle" x="1116.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1230.5,-651 1230.5,-858 "/>
<text text-anchor="middle" x="1241" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1844.8594,-1069.2897C1765.3228,-1014.5239 1669.9221,-957.2811 1575.5,-921 1443.1136,-870.1314 1392.8253,-921.0273 1260.5,-870 1254.5226,-867.695 1248.5359,-865.1702 1242.5687,-862.466"/>
<polygon fill="#000000" stroke="#000000" points="1243.7516,-859.1549 1233.2119,-858.0748 1240.7776,-865.4917 1243.7516,-859.1549"/>
<text text-anchor="middle" x="1556" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- participant -->
<g id="node11" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M967,-495.5C967,-495.5 1198,-495.5 1198,-495.5 1204,-495.5 1210,-501.5 1210,-507.5 1210,-507.5 1210,-575.5 1210,-575.5 1210,-581.5 1204,-587.5 1198,-587.5 1198,-587.5 967,-587.5 967,-587.5 961,-587.5 955,-581.5 955,-575.5 955,-575.5 955,-507.5 955,-507.5 955,-501.5 961,-495.5 967,-495.5"/>
<text text-anchor="middle" x="1003" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1051,-495.5 1051,-587.5 "/>
<text text-anchor="middle" x="1061.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1072,-495.5 1072,-587.5 "/>
<text text-anchor="middle" x="1130.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1072,-564.5 1189,-564.5 "/>
<text text-anchor="middle" x="1130.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1072,-541.5 1189,-541.5 "/>
<text text-anchor="middle" x="1130.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1072,-518.5 1189,-518.5 "/>
<text text-anchor="middle" x="1130.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="1189,-495.5 1189,-587.5 "/>
<text text-anchor="middle" x="1199.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2168.8234,-1013.4383C2227.2655,-891.0045 2265.2105,-740.5395 2174.5,-639 2112.0858,-569.1349 1499.8044,-549.064 1220.3332,-543.5198"/>
<polygon fill="#000000" stroke="#000000" points="1220.1927,-540.0165 1210.1263,-543.3208 1220.0562,-547.0152 1220.1927,-540.0165"/>
<text text-anchor="middle" x="2273" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- genetic_analysis -->
<g id="node2" class="node">
<title>genetic_analysis</title>
<path fill="none" stroke="#000000" d="M1170.5,-921.5C1170.5,-921.5 1554.5,-921.5 1554.5,-921.5 1560.5,-921.5 1566.5,-927.5 1566.5,-933.5 1566.5,-933.5 1566.5,-1507.5 1566.5,-1507.5 1566.5,-1513.5 1560.5,-1519.5 1554.5,-1519.5 1554.5,-1519.5 1170.5,-1519.5 1170.5,-1519.5 1164.5,-1519.5 1158.5,-1513.5 1158.5,-1507.5 1158.5,-1507.5 1158.5,-933.5 1158.5,-933.5 1158.5,-927.5 1164.5,-921.5 1170.5,-921.5"/>
<text text-anchor="middle" x="1226" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="1293.5,-921.5 1293.5,-1519.5 "/>
<text text-anchor="middle" x="1304" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1314.5,-921.5 1314.5,-1519.5 "/>
<text text-anchor="middle" x="1430" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="1314.5,-1496.5 1545.5,-1496.5 "/>
<text text-anchor="middle" x="1430" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">allelic_ratio</text>
<polyline fill="none" stroke="#000000" points="1314.5,-1473.5 1545.5,-1473.5 "/>
<text text-anchor="middle" x="1430" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration</text>
<polyline fill="none" stroke="#000000" points="1314.5,-1450.5 1545.5,-1450.5 "/>
<text text-anchor="middle" x="1430" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="1314.5,-1427.5 1545.5,-1427.5 "/>
<text text-anchor="middle" x="1430" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome_location</text>
<polyline fill="none" stroke="#000000" points="1314.5,-1404.5 1545.5,-1404.5 "/>
<text text-anchor="middle" x="1430" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="1314.5,-1381.5 1545.5,-1381.5 "/>
<text text-anchor="middle" x="1430" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">dna_index_numeric</text>
<polyline fill="none" stroke="#000000" points="1314.5,-1358.5 1545.5,-1358.5 "/>
<text text-anchor="middle" x="1430" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="1314.5,-1335.5 1545.5,-1335.5 "/>
<text text-anchor="middle" x="1430" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_exon</text>
<polyline fill="none" stroke="#000000" points="1314.5,-1312.5 1545.5,-1312.5 "/>
<text text-anchor="middle" x="1430" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_gene</text>
<polyline fill="none" stroke="#000000" points="1314.5,-1289.5 1545.5,-1289.5 "/>
<text text-anchor="middle" x="1430" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_transcript</text>
<polyline fill="none" stroke="#000000" points="1314.5,-1266.5 1545.5,-1266.5 "/>
<text text-anchor="middle" x="1430" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="1314.5,-1243.5 1545.5,-1243.5 "/>
<text text-anchor="middle" x="1430" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis_id</text>
<polyline fill="none" stroke="#000000" points="1314.5,-1220.5 1545.5,-1220.5 "/>
<text text-anchor="middle" x="1430" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_source_category</text>
<polyline fill="none" stroke="#000000" points="1314.5,-1197.5 1545.5,-1197.5 "/>
<text text-anchor="middle" x="1430" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_coding</text>
<polyline fill="none" stroke="#000000" points="1314.5,-1174.5 1545.5,-1174.5 "/>
<text text-anchor="middle" x="1430" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_genome</text>
<polyline fill="none" stroke="#000000" points="1314.5,-1151.5 1545.5,-1151.5 "/>
<text text-anchor="middle" x="1430" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_protein</text>
<polyline fill="none" stroke="#000000" points="1314.5,-1128.5 1545.5,-1128.5 "/>
<text text-anchor="middle" x="1430" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1314.5,-1105.5 1545.5,-1105.5 "/>
<text text-anchor="middle" x="1430" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">karyotype</text>
<polyline fill="none" stroke="#000000" points="1314.5,-1082.5 1545.5,-1082.5 "/>
<text text-anchor="middle" x="1430" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome</text>
<polyline fill="none" stroke="#000000" points="1314.5,-1059.5 1545.5,-1059.5 "/>
<text text-anchor="middle" x="1430" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance</text>
<polyline fill="none" stroke="#000000" points="1314.5,-1036.5 1545.5,-1036.5 "/>
<text text-anchor="middle" x="1430" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance_system</text>
<polyline fill="none" stroke="#000000" points="1314.5,-1013.5 1545.5,-1013.5 "/>
<text text-anchor="middle" x="1430" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">result</text>
<polyline fill="none" stroke="#000000" points="1314.5,-990.5 1545.5,-990.5 "/>
<text text-anchor="middle" x="1430" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="1314.5,-967.5 1545.5,-967.5 "/>
<text text-anchor="middle" x="1430" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">test</text>
<polyline fill="none" stroke="#000000" points="1314.5,-944.5 1545.5,-944.5 "/>
<text text-anchor="middle" x="1430" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 2 properties</text>
<polyline fill="none" stroke="#000000" points="1545.5,-921.5 1545.5,-1519.5 "/>
<text text-anchor="middle" x="1556" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1182.7956,-921.4205C1171.4592,-902.5535 1160.5014,-884.3166 1150.2548,-867.2634"/>
<polygon fill="#000000" stroke="#000000" points="1153.1136,-865.2255 1144.9631,-858.4565 1147.1134,-868.8308 1153.1136,-865.2255"/>
<text text-anchor="middle" x="1235.5" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1566.5794,-941.7791C1577.6616,-918.2568 1587.2179,-894.1949 1594.5,-870 1624.089,-771.6896 1659.9548,-718.0956 1594.5,-639 1547.7869,-582.5519 1355.2781,-558.5041 1220.1303,-548.4533"/>
<polygon fill="#000000" stroke="#000000" points="1220.3222,-544.9581 1210.095,-547.7247 1219.8153,-551.9397 1220.3222,-544.9581"/>
<text text-anchor="middle" x="1700.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
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
<!-- study -->
<g id="node7" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M623,-.5C623,-.5 842,-.5 842,-.5 848,-.5 854,-6.5 854,-12.5 854,-12.5 854,-149.5 854,-149.5 854,-155.5 848,-161.5 842,-161.5 842,-161.5 623,-161.5 623,-161.5 617,-161.5 611,-155.5 611,-149.5 611,-149.5 611,-12.5 611,-12.5 611,-6.5 617,-.5 623,-.5"/>
<text text-anchor="middle" x="639" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="667,-.5 667,-161.5 "/>
<text text-anchor="middle" x="677.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="688,-.5 688,-161.5 "/>
<text text-anchor="middle" x="760.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession</text>
<polyline fill="none" stroke="#000000" points="688,-138.5 833,-138.5 "/>
<text text-anchor="middle" x="760.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="688,-115.5 833,-115.5 "/>
<text text-anchor="middle" x="760.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="688,-92.5 833,-92.5 "/>
<text text-anchor="middle" x="760.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="688,-69.5 833,-69.5 "/>
<text text-anchor="middle" x="760.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="688,-46.5 833,-46.5 "/>
<text text-anchor="middle" x="760.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="688,-23.5 833,-23.5 "/>
<text text-anchor="middle" x="760.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
<polyline fill="none" stroke="#000000" points="833,-.5 833,-161.5 "/>
<text text-anchor="middle" x="843.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge4" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M200.1475,-673.9069C211.6067,-651.4257 224.8154,-627.3286 238.5,-606 358.6348,-418.7601 387.6493,-366.6822 548.5,-213 565.1645,-197.0781 583.8461,-181.5261 602.7469,-167.0096"/>
<polygon fill="#000000" stroke="#000000" points="605.0071,-169.6881 610.8554,-160.8536 600.7743,-164.1128 605.0071,-169.6881"/>
<text text-anchor="middle" x="373" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M198.2112,-673.7431C213.8228,-647.7693 234.7751,-621.68 261.5,-606 318.8183,-572.3702 725.9254,-553.5675 944.5094,-545.7934"/>
<polygon fill="#000000" stroke="#000000" points="944.9031,-549.2818 954.7735,-545.4316 944.6564,-542.2862 944.9031,-549.2818"/>
<text text-anchor="middle" x="304" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- survival -->
<g id="node4" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M522,-662.5C522,-662.5 883,-662.5 883,-662.5 889,-662.5 895,-668.5 895,-674.5 895,-674.5 895,-834.5 895,-834.5 895,-840.5 889,-846.5 883,-846.5 883,-846.5 522,-846.5 522,-846.5 516,-846.5 510,-840.5 510,-834.5 510,-834.5 510,-674.5 510,-674.5 510,-668.5 516,-662.5 522,-662.5"/>
<text text-anchor="middle" x="547" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="584,-662.5 584,-846.5 "/>
<text text-anchor="middle" x="594.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="605,-662.5 605,-846.5 "/>
<text text-anchor="middle" x="739.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="605,-823.5 874,-823.5 "/>
<text text-anchor="middle" x="739.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="605,-800.5 874,-800.5 "/>
<text text-anchor="middle" x="739.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="605,-777.5 874,-777.5 "/>
<text text-anchor="middle" x="739.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="605,-754.5 874,-754.5 "/>
<text text-anchor="middle" x="739.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="605,-731.5 874,-731.5 "/>
<text text-anchor="middle" x="739.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="605,-708.5 874,-708.5 "/>
<text text-anchor="middle" x="739.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="605,-685.5 874,-685.5 "/>
<text text-anchor="middle" x="739.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="874,-662.5 874,-846.5 "/>
<text text-anchor="middle" x="884.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M863.0527,-662.3454C877.0524,-654.417 891.0163,-646.5469 904.5,-639 931.7096,-623.7706 961.3781,-607.4192 988.554,-592.5414"/>
<polygon fill="#000000" stroke="#000000" points="990.574,-595.426 997.6675,-587.5562 987.2146,-589.2847 990.574,-595.426"/>
<text text-anchor="middle" x="1003" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- laboratory_test -->
<g id="node5" class="node">
<title>laboratory_test</title>
<path fill="none" stroke="#000000" d="M635.5,-1094C635.5,-1094 967.5,-1094 967.5,-1094 973.5,-1094 979.5,-1100 979.5,-1106 979.5,-1106 979.5,-1335 979.5,-1335 979.5,-1341 973.5,-1347 967.5,-1347 967.5,-1347 635.5,-1347 635.5,-1347 629.5,-1347 623.5,-1341 623.5,-1335 623.5,-1335 623.5,-1106 623.5,-1106 623.5,-1100 629.5,-1094 635.5,-1094"/>
<text text-anchor="middle" x="686.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="749.5,-1094 749.5,-1347 "/>
<text text-anchor="middle" x="760" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="770.5,-1094 770.5,-1347 "/>
<text text-anchor="middle" x="864.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_laboratory_test</text>
<polyline fill="none" stroke="#000000" points="770.5,-1324 958.5,-1324 "/>
<text text-anchor="middle" x="864.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="770.5,-1301 958.5,-1301 "/>
<text text-anchor="middle" x="864.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_id</text>
<polyline fill="none" stroke="#000000" points="770.5,-1278 958.5,-1278 "/>
<text text-anchor="middle" x="864.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_method</text>
<polyline fill="none" stroke="#000000" points="770.5,-1255 958.5,-1255 "/>
<text text-anchor="middle" x="864.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_name</text>
<polyline fill="none" stroke="#000000" points="770.5,-1232 958.5,-1232 "/>
<text text-anchor="middle" x="864.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">sensitivity</text>
<polyline fill="none" stroke="#000000" points="770.5,-1209 958.5,-1209 "/>
<text text-anchor="middle" x="864.5" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">specimen</text>
<polyline fill="none" stroke="#000000" points="770.5,-1186 958.5,-1186 "/>
<text text-anchor="middle" x="864.5" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_modifier</text>
<polyline fill="none" stroke="#000000" points="770.5,-1163 958.5,-1163 "/>
<text text-anchor="middle" x="864.5" y="-1147.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_numeric</text>
<polyline fill="none" stroke="#000000" points="770.5,-1140 958.5,-1140 "/>
<text text-anchor="middle" x="864.5" y="-1124.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_text</text>
<polyline fill="none" stroke="#000000" points="770.5,-1117 958.5,-1117 "/>
<text text-anchor="middle" x="864.5" y="-1101.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_unit</text>
<polyline fill="none" stroke="#000000" points="958.5,-1094 958.5,-1347 "/>
<text text-anchor="middle" x="969" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M877.9133,-1093.779C920.695,-1022.8315 973.5659,-935.1523 1014.8424,-866.7008"/>
<polygon fill="#000000" stroke="#000000" points="1017.9066,-868.3971 1020.0733,-858.0262 1011.9121,-864.7824 1017.9066,-868.3971"/>
<text text-anchor="middle" x="1065" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M623.4324,-1127.7254C529.1946,-1068.0313 422.3052,-980.8425 369.5,-870 347.4222,-823.6569 335.7502,-677.679 369.5,-639 406.6897,-596.3787 748.0839,-565.2661 944.6663,-550.7091"/>
<polygon fill="#000000" stroke="#000000" points="945.0702,-554.189 954.7865,-549.9649 944.5567,-547.2078 945.0702,-554.189"/>
<text text-anchor="middle" x="435" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- treatment -->
<g id="node6" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M1281.5,-639.5C1281.5,-639.5 1573.5,-639.5 1573.5,-639.5 1579.5,-639.5 1585.5,-645.5 1585.5,-651.5 1585.5,-651.5 1585.5,-857.5 1585.5,-857.5 1585.5,-863.5 1579.5,-869.5 1573.5,-869.5 1573.5,-869.5 1281.5,-869.5 1281.5,-869.5 1275.5,-869.5 1269.5,-863.5 1269.5,-857.5 1269.5,-857.5 1269.5,-651.5 1269.5,-651.5 1269.5,-645.5 1275.5,-639.5 1281.5,-639.5"/>
<text text-anchor="middle" x="1314" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1358.5,-639.5 1358.5,-869.5 "/>
<text text-anchor="middle" x="1369" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1379.5,-639.5 1379.5,-869.5 "/>
<text text-anchor="middle" x="1472" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="1379.5,-846.5 1564.5,-846.5 "/>
<text text-anchor="middle" x="1472" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1379.5,-823.5 1564.5,-823.5 "/>
<text text-anchor="middle" x="1472" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose</text>
<polyline fill="none" stroke="#000000" points="1379.5,-800.5 1564.5,-800.5 "/>
<text text-anchor="middle" x="1472" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_frequency</text>
<polyline fill="none" stroke="#000000" points="1379.5,-777.5 1564.5,-777.5 "/>
<text text-anchor="middle" x="1472" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_route</text>
<polyline fill="none" stroke="#000000" points="1379.5,-754.5 1564.5,-754.5 "/>
<text text-anchor="middle" x="1472" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_unit</text>
<polyline fill="none" stroke="#000000" points="1379.5,-731.5 1564.5,-731.5 "/>
<text text-anchor="middle" x="1472" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1379.5,-708.5 1564.5,-708.5 "/>
<text text-anchor="middle" x="1472" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="1379.5,-685.5 1564.5,-685.5 "/>
<text text-anchor="middle" x="1472" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1379.5,-662.5 1564.5,-662.5 "/>
<text text-anchor="middle" x="1472" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1564.5,-639.5 1564.5,-869.5 "/>
<text text-anchor="middle" x="1575" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1269.0989,-644.3587C1266.2177,-642.547 1263.3496,-640.7593 1260.5,-639 1234.7756,-623.1184 1206.2997,-606.9302 1179.8063,-592.4249"/>
<polygon fill="#000000" stroke="#000000" points="1181.36,-589.2856 1170.9045,-587.5731 1178.01,-595.432 1181.36,-589.2856"/>
<text text-anchor="middle" x="1274.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1082.5,-650.8078C1082.5,-632.5822 1082.5,-614.2469 1082.5,-597.9389"/>
<polygon fill="#000000" stroke="#000000" points="1086.0001,-597.5364 1082.5,-587.5365 1079.0001,-597.5365 1086.0001,-597.5364"/>
<text text-anchor="middle" x="1119" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- consent_group -->
<g id="node9" class="node">
<title>consent_group</title>
<path fill="none" stroke="#000000" d="M570,-271C570,-271 895,-271 895,-271 901,-271 907,-277 907,-283 907,-283 907,-374 907,-374 907,-380 901,-386 895,-386 895,-386 570,-386 570,-386 564,-386 558,-380 558,-374 558,-374 558,-283 558,-283 558,-277 564,-271 570,-271"/>
<text text-anchor="middle" x="619" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
<polyline fill="none" stroke="#000000" points="680,-271 680,-386 "/>
<text text-anchor="middle" x="690.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="701,-271 701,-386 "/>
<text text-anchor="middle" x="793.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_id</text>
<polyline fill="none" stroke="#000000" points="701,-363 886,-363 "/>
<text text-anchor="middle" x="793.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_name</text>
<polyline fill="none" stroke="#000000" points="701,-340 886,-340 "/>
<text text-anchor="middle" x="793.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_number</text>
<polyline fill="none" stroke="#000000" points="701,-317 886,-317 "/>
<text text-anchor="middle" x="793.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_suffix</text>
<polyline fill="none" stroke="#000000" points="701,-294 886,-294 "/>
<text text-anchor="middle" x="793.5" y="-278.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="886,-271 886,-386 "/>
<text text-anchor="middle" x="896.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge2" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M732.5,-270.7846C732.5,-241.3997 732.5,-204.9895 732.5,-171.9435"/>
<polygon fill="#000000" stroke="#000000" points="736.0001,-171.8072 732.5,-161.8073 729.0001,-171.8073 736.0001,-171.8072"/>
<text text-anchor="middle" x="796" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- reference_file -->
<g id="node10" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M937,-213.5C937,-213.5 1214,-213.5 1214,-213.5 1220,-213.5 1226,-219.5 1226,-225.5 1226,-225.5 1226,-431.5 1226,-431.5 1226,-437.5 1220,-443.5 1214,-443.5 1214,-443.5 937,-443.5 937,-443.5 931,-443.5 925,-437.5 925,-431.5 925,-431.5 925,-225.5 925,-225.5 925,-219.5 931,-213.5 937,-213.5"/>
<text text-anchor="middle" x="983" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="1041,-213.5 1041,-443.5 "/>
<text text-anchor="middle" x="1051.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1062,-213.5 1062,-443.5 "/>
<text text-anchor="middle" x="1133.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1062,-420.5 1205,-420.5 "/>
<text text-anchor="middle" x="1133.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="1062,-397.5 1205,-397.5 "/>
<text text-anchor="middle" x="1133.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1062,-374.5 1205,-374.5 "/>
<text text-anchor="middle" x="1133.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1062,-351.5 1205,-351.5 "/>
<text text-anchor="middle" x="1133.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1062,-328.5 1205,-328.5 "/>
<text text-anchor="middle" x="1133.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1062,-305.5 1205,-305.5 "/>
<text text-anchor="middle" x="1133.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1062,-282.5 1205,-282.5 "/>
<text text-anchor="middle" x="1133.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1062,-259.5 1205,-259.5 "/>
<text text-anchor="middle" x="1133.5" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="1062,-236.5 1205,-236.5 "/>
<text text-anchor="middle" x="1133.5" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="1205,-213.5 1205,-443.5 "/>
<text text-anchor="middle" x="1215.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge3" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M924.7578,-219.6806C921.6447,-217.4341 918.556,-215.2052 915.5,-213 895.1681,-198.3287 873.5639,-182.7424 852.5945,-167.6159"/>
<polygon fill="#000000" stroke="#000000" points="854.4396,-164.6313 844.2818,-161.6195 850.3444,-170.3084 854.4396,-164.6313"/>
<text text-anchor="middle" x="947" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge15" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1002.3191,-495.4401C974.6866,-479.3676 943.6223,-461.077 915.5,-444 887.9722,-427.284 858.3608,-408.8121 831.1476,-391.6347"/>
<polygon fill="#000000" stroke="#000000" points="832.7252,-388.4913 822.4022,-386.1069 828.9852,-394.4084 832.7252,-388.4913"/>
<text text-anchor="middle" x="1021" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- treatment_response -->
<g id="node12" class="node">
<title>treatment_response</title>
<path fill="none" stroke="#000000" d="M1792,-685.5C1792,-685.5 2153,-685.5 2153,-685.5 2159,-685.5 2165,-691.5 2165,-697.5 2165,-697.5 2165,-811.5 2165,-811.5 2165,-817.5 2159,-823.5 2153,-823.5 2153,-823.5 1792,-823.5 1792,-823.5 1786,-823.5 1780,-817.5 1780,-811.5 1780,-811.5 1780,-697.5 1780,-697.5 1780,-691.5 1786,-685.5 1792,-685.5"/>
<text text-anchor="middle" x="1860.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
<polyline fill="none" stroke="#000000" points="1941,-685.5 1941,-823.5 "/>
<text text-anchor="middle" x="1951.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1962,-685.5 1962,-823.5 "/>
<text text-anchor="middle" x="2053" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_response</text>
<polyline fill="none" stroke="#000000" points="1962,-800.5 2144,-800.5 "/>
<text text-anchor="middle" x="2053" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1962,-777.5 2144,-777.5 "/>
<text text-anchor="middle" x="2053" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="1962,-754.5 2144,-754.5 "/>
<text text-anchor="middle" x="2053" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_category</text>
<polyline fill="none" stroke="#000000" points="1962,-731.5 2144,-731.5 "/>
<text text-anchor="middle" x="2053" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_system</text>
<polyline fill="none" stroke="#000000" points="1962,-708.5 2144,-708.5 "/>
<text text-anchor="middle" x="2053" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response_id</text>
<polyline fill="none" stroke="#000000" points="2144,-685.5 2144,-823.5 "/>
<text text-anchor="middle" x="2154.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1861.2313,-685.4565C1830.9461,-668.6122 1797.6185,-651.7827 1765.5,-639 1710.1149,-616.9575 1694.1219,-616.81 1635.5,-606 1495.0184,-580.0949 1332.4346,-562.6035 1220.0874,-552.4449"/>
<polygon fill="#000000" stroke="#000000" points="1220.3271,-548.9525 1210.0544,-551.5451 1219.7018,-555.9245 1220.3271,-548.9525"/>
<text text-anchor="middle" x="1795.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
</g>
</svg>
</div>
