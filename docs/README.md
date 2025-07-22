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
<svg width="2435pt" height="1528pt"
 viewBox="0.00 0.00 2434.50 1528.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1524)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1524 2430.5,-1524 2430.5,4 -4,4"/>
<!-- laboratory_test -->
<g id="node1" class="node">
<title>laboratory_test</title>
<path fill="none" stroke="#000000" d="M1929.5,-1094C1929.5,-1094 2261.5,-1094 2261.5,-1094 2267.5,-1094 2273.5,-1100 2273.5,-1106 2273.5,-1106 2273.5,-1335 2273.5,-1335 2273.5,-1341 2267.5,-1347 2261.5,-1347 2261.5,-1347 1929.5,-1347 1929.5,-1347 1923.5,-1347 1917.5,-1341 1917.5,-1335 1917.5,-1335 1917.5,-1106 1917.5,-1106 1917.5,-1100 1923.5,-1094 1929.5,-1094"/>
<text text-anchor="middle" x="1980.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="2043.5,-1094 2043.5,-1347 "/>
<text text-anchor="middle" x="2054" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2064.5,-1094 2064.5,-1347 "/>
<text text-anchor="middle" x="2158.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_laboratory_test</text>
<polyline fill="none" stroke="#000000" points="2064.5,-1324 2252.5,-1324 "/>
<text text-anchor="middle" x="2158.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2064.5,-1301 2252.5,-1301 "/>
<text text-anchor="middle" x="2158.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_id</text>
<polyline fill="none" stroke="#000000" points="2064.5,-1278 2252.5,-1278 "/>
<text text-anchor="middle" x="2158.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_method</text>
<polyline fill="none" stroke="#000000" points="2064.5,-1255 2252.5,-1255 "/>
<text text-anchor="middle" x="2158.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_name</text>
<polyline fill="none" stroke="#000000" points="2064.5,-1232 2252.5,-1232 "/>
<text text-anchor="middle" x="2158.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">sensitivity</text>
<polyline fill="none" stroke="#000000" points="2064.5,-1209 2252.5,-1209 "/>
<text text-anchor="middle" x="2158.5" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">specimen</text>
<polyline fill="none" stroke="#000000" points="2064.5,-1186 2252.5,-1186 "/>
<text text-anchor="middle" x="2158.5" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_modifier</text>
<polyline fill="none" stroke="#000000" points="2064.5,-1163 2252.5,-1163 "/>
<text text-anchor="middle" x="2158.5" y="-1147.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_numeric</text>
<polyline fill="none" stroke="#000000" points="2064.5,-1140 2252.5,-1140 "/>
<text text-anchor="middle" x="2158.5" y="-1124.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_text</text>
<polyline fill="none" stroke="#000000" points="2064.5,-1117 2252.5,-1117 "/>
<text text-anchor="middle" x="2158.5" y="-1101.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_unit</text>
<polyline fill="none" stroke="#000000" points="2252.5,-1094 2252.5,-1347 "/>
<text text-anchor="middle" x="2263" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node5" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1023,-495.5C1023,-495.5 1254,-495.5 1254,-495.5 1260,-495.5 1266,-501.5 1266,-507.5 1266,-507.5 1266,-575.5 1266,-575.5 1266,-581.5 1260,-587.5 1254,-587.5 1254,-587.5 1023,-587.5 1023,-587.5 1017,-587.5 1011,-581.5 1011,-575.5 1011,-575.5 1011,-507.5 1011,-507.5 1011,-501.5 1017,-495.5 1023,-495.5"/>
<text text-anchor="middle" x="1059" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1107,-495.5 1107,-587.5 "/>
<text text-anchor="middle" x="1117.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1128,-495.5 1128,-587.5 "/>
<text text-anchor="middle" x="1186.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1128,-564.5 1245,-564.5 "/>
<text text-anchor="middle" x="1186.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1128,-541.5 1245,-541.5 "/>
<text text-anchor="middle" x="1186.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1128,-518.5 1245,-518.5 "/>
<text text-anchor="middle" x="1186.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="1245,-495.5 1245,-587.5 "/>
<text text-anchor="middle" x="1255.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2185.7813,-1093.7788C2266.3787,-963.8161 2355.5398,-763.5651 2241.5,-639 2177.5268,-569.1224 1558.0641,-549.0483 1276.5259,-543.5109"/>
<polygon fill="#000000" stroke="#000000" points="1276.3106,-540.0062 1266.2448,-543.3122 1276.1752,-547.0049 1276.3106,-540.0062"/>
<text text-anchor="middle" x="2361" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- sample -->
<g id="node11" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1326.5,-651C1326.5,-651 1640.5,-651 1640.5,-651 1646.5,-651 1652.5,-657 1652.5,-663 1652.5,-663 1652.5,-846 1652.5,-846 1652.5,-852 1646.5,-858 1640.5,-858 1640.5,-858 1326.5,-858 1326.5,-858 1320.5,-858 1314.5,-852 1314.5,-846 1314.5,-846 1314.5,-663 1314.5,-663 1314.5,-657 1320.5,-651 1326.5,-651"/>
<text text-anchor="middle" x="1348.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1382.5,-651 1382.5,-858 "/>
<text text-anchor="middle" x="1393" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1403.5,-651 1403.5,-858 "/>
<text text-anchor="middle" x="1517.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1403.5,-835 1631.5,-835 "/>
<text text-anchor="middle" x="1517.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1403.5,-812 1631.5,-812 "/>
<text text-anchor="middle" x="1517.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1403.5,-789 1631.5,-789 "/>
<text text-anchor="middle" x="1517.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_necrosis</text>
<polyline fill="none" stroke="#000000" points="1403.5,-766 1631.5,-766 "/>
<text text-anchor="middle" x="1517.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_tumor</text>
<polyline fill="none" stroke="#000000" points="1403.5,-743 1631.5,-743 "/>
<text text-anchor="middle" x="1517.5" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1403.5,-720 1631.5,-720 "/>
<text text-anchor="middle" x="1517.5" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1403.5,-697 1631.5,-697 "/>
<text text-anchor="middle" x="1517.5" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1403.5,-674 1631.5,-674 "/>
<text text-anchor="middle" x="1517.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1631.5,-651 1631.5,-858 "/>
<text text-anchor="middle" x="1642" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2004.2802,-1093.7218C1955.818,-1034.1588 1891.7817,-966.4314 1821.5,-921 1760.5948,-881.6297 1732.1009,-900.919 1666.5,-870 1661.5617,-867.6725 1656.5944,-865.237 1651.6173,-862.7135"/>
<polygon fill="#000000" stroke="#000000" points="1653.1427,-859.5621 1642.652,-858.0801 1649.9288,-865.7807 1653.1427,-859.5621"/>
<text text-anchor="middle" x="1850" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- study -->
<g id="node2" class="node">
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
<!-- treatment_response -->
<g id="node3" class="node">
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
<g id="edge13" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M651.3717,-685.3324C657.8047,-656.6844 670.101,-625.6292 693.5,-606 739.0003,-567.8301 887.6186,-552.248 1000.7012,-545.8872"/>
<polygon fill="#000000" stroke="#000000" points="1001.0439,-549.3738 1010.8391,-545.3361 1000.6639,-542.3841 1001.0439,-549.3738"/>
<text text-anchor="middle" x="776.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- genetic_analysis -->
<g id="node4" class="node">
<title>genetic_analysis</title>
<path fill="none" stroke="#000000" d="M1416.5,-921.5C1416.5,-921.5 1800.5,-921.5 1800.5,-921.5 1806.5,-921.5 1812.5,-927.5 1812.5,-933.5 1812.5,-933.5 1812.5,-1507.5 1812.5,-1507.5 1812.5,-1513.5 1806.5,-1519.5 1800.5,-1519.5 1800.5,-1519.5 1416.5,-1519.5 1416.5,-1519.5 1410.5,-1519.5 1404.5,-1513.5 1404.5,-1507.5 1404.5,-1507.5 1404.5,-933.5 1404.5,-933.5 1404.5,-927.5 1410.5,-921.5 1416.5,-921.5"/>
<text text-anchor="middle" x="1472" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="1539.5,-921.5 1539.5,-1519.5 "/>
<text text-anchor="middle" x="1550" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1560.5,-921.5 1560.5,-1519.5 "/>
<text text-anchor="middle" x="1676" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="1560.5,-1496.5 1791.5,-1496.5 "/>
<text text-anchor="middle" x="1676" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">allelic_ratio</text>
<polyline fill="none" stroke="#000000" points="1560.5,-1473.5 1791.5,-1473.5 "/>
<text text-anchor="middle" x="1676" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration</text>
<polyline fill="none" stroke="#000000" points="1560.5,-1450.5 1791.5,-1450.5 "/>
<text text-anchor="middle" x="1676" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="1560.5,-1427.5 1791.5,-1427.5 "/>
<text text-anchor="middle" x="1676" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome_location</text>
<polyline fill="none" stroke="#000000" points="1560.5,-1404.5 1791.5,-1404.5 "/>
<text text-anchor="middle" x="1676" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="1560.5,-1381.5 1791.5,-1381.5 "/>
<text text-anchor="middle" x="1676" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">dna_index_numeric</text>
<polyline fill="none" stroke="#000000" points="1560.5,-1358.5 1791.5,-1358.5 "/>
<text text-anchor="middle" x="1676" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="1560.5,-1335.5 1791.5,-1335.5 "/>
<text text-anchor="middle" x="1676" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_exon</text>
<polyline fill="none" stroke="#000000" points="1560.5,-1312.5 1791.5,-1312.5 "/>
<text text-anchor="middle" x="1676" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_gene</text>
<polyline fill="none" stroke="#000000" points="1560.5,-1289.5 1791.5,-1289.5 "/>
<text text-anchor="middle" x="1676" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_transcript</text>
<polyline fill="none" stroke="#000000" points="1560.5,-1266.5 1791.5,-1266.5 "/>
<text text-anchor="middle" x="1676" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="1560.5,-1243.5 1791.5,-1243.5 "/>
<text text-anchor="middle" x="1676" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis_id</text>
<polyline fill="none" stroke="#000000" points="1560.5,-1220.5 1791.5,-1220.5 "/>
<text text-anchor="middle" x="1676" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_source_category</text>
<polyline fill="none" stroke="#000000" points="1560.5,-1197.5 1791.5,-1197.5 "/>
<text text-anchor="middle" x="1676" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_coding</text>
<polyline fill="none" stroke="#000000" points="1560.5,-1174.5 1791.5,-1174.5 "/>
<text text-anchor="middle" x="1676" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_genome</text>
<polyline fill="none" stroke="#000000" points="1560.5,-1151.5 1791.5,-1151.5 "/>
<text text-anchor="middle" x="1676" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_protein</text>
<polyline fill="none" stroke="#000000" points="1560.5,-1128.5 1791.5,-1128.5 "/>
<text text-anchor="middle" x="1676" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1560.5,-1105.5 1791.5,-1105.5 "/>
<text text-anchor="middle" x="1676" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">karyotype</text>
<polyline fill="none" stroke="#000000" points="1560.5,-1082.5 1791.5,-1082.5 "/>
<text text-anchor="middle" x="1676" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome</text>
<polyline fill="none" stroke="#000000" points="1560.5,-1059.5 1791.5,-1059.5 "/>
<text text-anchor="middle" x="1676" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance</text>
<polyline fill="none" stroke="#000000" points="1560.5,-1036.5 1791.5,-1036.5 "/>
<text text-anchor="middle" x="1676" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance_system</text>
<polyline fill="none" stroke="#000000" points="1560.5,-1013.5 1791.5,-1013.5 "/>
<text text-anchor="middle" x="1676" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">result</text>
<polyline fill="none" stroke="#000000" points="1560.5,-990.5 1791.5,-990.5 "/>
<text text-anchor="middle" x="1676" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="1560.5,-967.5 1791.5,-967.5 "/>
<text text-anchor="middle" x="1676" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">test</text>
<polyline fill="none" stroke="#000000" points="1560.5,-944.5 1791.5,-944.5 "/>
<text text-anchor="middle" x="1676" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 2 properties</text>
<polyline fill="none" stroke="#000000" points="1791.5,-921.5 1791.5,-1519.5 "/>
<text text-anchor="middle" x="1802" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1673.904,-921.4826C1692.3058,-802.3196 1698.5292,-683.028 1661.5,-639 1613.0711,-581.4177 1414.455,-557.638 1276.4302,-547.9582"/>
<polygon fill="#000000" stroke="#000000" points="1276.4007,-544.4481 1266.1852,-547.2576 1275.9231,-551.4318 1276.4007,-544.4481"/>
<text text-anchor="middle" x="1758.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge10" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1528.2748,-921.4205C1523.3068,-902.8996 1518.5016,-884.9861 1513.9998,-868.2033"/>
<polygon fill="#000000" stroke="#000000" points="1517.3567,-867.2082 1511.3853,-858.4565 1510.5957,-869.0218 1517.3567,-867.2082"/>
<text text-anchor="middle" x="1590.5" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- consent_group -->
<g id="node10" class="node">
<title>consent_group</title>
<path fill="none" stroke="#000000" d="M673,-271C673,-271 998,-271 998,-271 1004,-271 1010,-277 1010,-283 1010,-283 1010,-374 1010,-374 1010,-380 1004,-386 998,-386 998,-386 673,-386 673,-386 667,-386 661,-380 661,-374 661,-374 661,-283 661,-283 661,-277 667,-271 673,-271"/>
<text text-anchor="middle" x="722" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
<polyline fill="none" stroke="#000000" points="783,-271 783,-386 "/>
<text text-anchor="middle" x="793.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="804,-271 804,-386 "/>
<text text-anchor="middle" x="896.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_id</text>
<polyline fill="none" stroke="#000000" points="804,-363 989,-363 "/>
<text text-anchor="middle" x="896.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_name</text>
<polyline fill="none" stroke="#000000" points="804,-340 989,-340 "/>
<text text-anchor="middle" x="896.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_number</text>
<polyline fill="none" stroke="#000000" points="804,-317 989,-317 "/>
<text text-anchor="middle" x="896.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_suffix</text>
<polyline fill="none" stroke="#000000" points="804,-294 989,-294 "/>
<text text-anchor="middle" x="896.5" y="-278.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="989,-271 989,-386 "/>
<text text-anchor="middle" x="999.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge2" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1072.7535,-495.2822C1029.7347,-465.0413 972.9614,-425.1313 925.738,-391.9346"/>
<polygon fill="#000000" stroke="#000000" points="927.5339,-388.9189 917.3402,-386.0312 923.5083,-394.6455 927.5339,-388.9189"/>
<text text-anchor="middle" x="1091" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
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
<!-- reference_file&#45;&gt;study -->
<g id="edge15" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M176.2184,-213.4651C181.2736,-201.6374 187.3059,-190.2265 194.5,-180 197.1103,-176.2894 199.9042,-172.6633 202.8495,-169.1251"/>
<polygon fill="#000000" stroke="#000000" points="205.5584,-171.3446 209.527,-161.5211 200.2986,-166.7256 205.5584,-171.3446"/>
<text text-anchor="middle" x="255" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- treatment -->
<g id="node7" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M992.5,-639.5C992.5,-639.5 1284.5,-639.5 1284.5,-639.5 1290.5,-639.5 1296.5,-645.5 1296.5,-651.5 1296.5,-651.5 1296.5,-857.5 1296.5,-857.5 1296.5,-863.5 1290.5,-869.5 1284.5,-869.5 1284.5,-869.5 992.5,-869.5 992.5,-869.5 986.5,-869.5 980.5,-863.5 980.5,-857.5 980.5,-857.5 980.5,-651.5 980.5,-651.5 980.5,-645.5 986.5,-639.5 992.5,-639.5"/>
<text text-anchor="middle" x="1025" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1069.5,-639.5 1069.5,-869.5 "/>
<text text-anchor="middle" x="1080" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1090.5,-639.5 1090.5,-869.5 "/>
<text text-anchor="middle" x="1183" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="1090.5,-846.5 1275.5,-846.5 "/>
<text text-anchor="middle" x="1183" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1090.5,-823.5 1275.5,-823.5 "/>
<text text-anchor="middle" x="1183" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose</text>
<polyline fill="none" stroke="#000000" points="1090.5,-800.5 1275.5,-800.5 "/>
<text text-anchor="middle" x="1183" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_frequency</text>
<polyline fill="none" stroke="#000000" points="1090.5,-777.5 1275.5,-777.5 "/>
<text text-anchor="middle" x="1183" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_route</text>
<polyline fill="none" stroke="#000000" points="1090.5,-754.5 1275.5,-754.5 "/>
<text text-anchor="middle" x="1183" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_unit</text>
<polyline fill="none" stroke="#000000" points="1090.5,-731.5 1275.5,-731.5 "/>
<text text-anchor="middle" x="1183" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1090.5,-708.5 1275.5,-708.5 "/>
<text text-anchor="middle" x="1183" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="1090.5,-685.5 1275.5,-685.5 "/>
<text text-anchor="middle" x="1183" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1090.5,-662.5 1275.5,-662.5 "/>
<text text-anchor="middle" x="1183" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1275.5,-639.5 1275.5,-869.5 "/>
<text text-anchor="middle" x="1286" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1138.5,-639.2724C1138.5,-624.8861 1138.5,-610.7136 1138.5,-597.8145"/>
<polygon fill="#000000" stroke="#000000" points="1142.0001,-597.7629 1138.5,-587.7629 1135.0001,-597.763 1142.0001,-597.7629"/>
<text text-anchor="middle" x="1185.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- synonym -->
<g id="node8" class="node">
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
<g id="edge6" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M282.8594,-673.9136C291.3183,-611.3278 302.5591,-522.3045 309.5,-444 317.6966,-351.5297 323.0766,-245.4904 326.1708,-171.998"/>
<polygon fill="#000000" stroke="#000000" points="329.6742,-171.9854 326.5923,-161.8487 322.6803,-171.6948 329.6742,-171.9854"/>
<text text-anchor="middle" x="351" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M377.8782,-673.7486C398.5389,-660.6781 420.5999,-648.3783 442.5,-639 540.2166,-597.1546 827.346,-567.1038 1000.7779,-552.1775"/>
<polygon fill="#000000" stroke="#000000" points="1001.0819,-555.6644 1010.7474,-551.3254 1000.4857,-548.6898 1001.0819,-555.6644"/>
<text text-anchor="middle" x="597" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- diagnosis -->
<g id="node9" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M913,-1013.5C913,-1013.5 1278,-1013.5 1278,-1013.5 1284,-1013.5 1290,-1019.5 1290,-1025.5 1290,-1025.5 1290,-1415.5 1290,-1415.5 1290,-1421.5 1284,-1427.5 1278,-1427.5 1278,-1427.5 913,-1427.5 913,-1427.5 907,-1427.5 901,-1421.5 901,-1415.5 901,-1415.5 901,-1025.5 901,-1025.5 901,-1019.5 907,-1013.5 913,-1013.5"/>
<text text-anchor="middle" x="943" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="985,-1013.5 985,-1427.5 "/>
<text text-anchor="middle" x="995.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1006,-1013.5 1006,-1427.5 "/>
<text text-anchor="middle" x="1137.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1006,-1404.5 1269,-1404.5 "/>
<text text-anchor="middle" x="1137.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1006,-1381.5 1269,-1381.5 "/>
<text text-anchor="middle" x="1137.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1006,-1358.5 1269,-1358.5 "/>
<text text-anchor="middle" x="1137.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="1006,-1335.5 1269,-1335.5 "/>
<text text-anchor="middle" x="1137.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_category</text>
<polyline fill="none" stroke="#000000" points="1006,-1312.5 1269,-1312.5 "/>
<text text-anchor="middle" x="1137.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="1006,-1289.5 1269,-1289.5 "/>
<text text-anchor="middle" x="1137.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="1006,-1266.5 1269,-1266.5 "/>
<text text-anchor="middle" x="1137.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1006,-1243.5 1269,-1243.5 "/>
<text text-anchor="middle" x="1137.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="1006,-1220.5 1269,-1220.5 "/>
<text text-anchor="middle" x="1137.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1006,-1197.5 1269,-1197.5 "/>
<text text-anchor="middle" x="1137.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">laterality</text>
<polyline fill="none" stroke="#000000" points="1006,-1174.5 1269,-1174.5 "/>
<text text-anchor="middle" x="1137.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="1006,-1151.5 1269,-1151.5 "/>
<text text-anchor="middle" x="1137.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1006,-1128.5 1269,-1128.5 "/>
<text text-anchor="middle" x="1137.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1006,-1105.5 1269,-1105.5 "/>
<text text-anchor="middle" x="1137.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1006,-1082.5 1269,-1082.5 "/>
<text text-anchor="middle" x="1137.5" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1006,-1059.5 1269,-1059.5 "/>
<text text-anchor="middle" x="1137.5" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1006,-1036.5 1269,-1036.5 "/>
<text text-anchor="middle" x="1137.5" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1269,-1013.5 1269,-1427.5 "/>
<text text-anchor="middle" x="1279.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M944.4575,-1013.146C918.9039,-968.0081 896.2286,-919.0262 882.5,-870 854.8157,-771.1363 824.2381,-723.534 882.5,-639 897.6175,-617.0656 948.5279,-595.6572 1001.0097,-578.515"/>
<polygon fill="#000000" stroke="#000000" points="1002.3684,-581.7548 1010.8193,-575.3646 1000.228,-575.09 1002.3684,-581.7548"/>
<text text-anchor="middle" x="927" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1267.942,-1013.3918C1310.1374,-962.7139 1353.7102,-910.3815 1390.5425,-866.1448"/>
<polygon fill="#000000" stroke="#000000" points="1393.3933,-868.1909 1397.1022,-858.2664 1388.0139,-863.7118 1393.3933,-868.1909"/>
<text text-anchor="middle" x="1414" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge5" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M717.823,-270.9406C640.7868,-233.2599 540.0319,-183.9776 460.4581,-145.0556"/>
<polygon fill="#000000" stroke="#000000" points="461.8757,-141.8528 451.3549,-140.6029 458.8,-148.1409 461.8757,-141.8528"/>
<text text-anchor="middle" x="616" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1324.5838,-650.8553C1318.1529,-646.8286 1311.7734,-642.8636 1305.5,-639 1280.5681,-623.6449 1253.2407,-607.4357 1228.0438,-592.7365"/>
<polygon fill="#000000" stroke="#000000" points="1229.6307,-589.6105 1219.2276,-587.6041 1226.1089,-595.6601 1229.6307,-589.6105"/>
<text text-anchor="middle" x="1311" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- survival -->
<g id="node12" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M1859,-662.5C1859,-662.5 2220,-662.5 2220,-662.5 2226,-662.5 2232,-668.5 2232,-674.5 2232,-674.5 2232,-834.5 2232,-834.5 2232,-840.5 2226,-846.5 2220,-846.5 2220,-846.5 1859,-846.5 1859,-846.5 1853,-846.5 1847,-840.5 1847,-834.5 1847,-834.5 1847,-674.5 1847,-674.5 1847,-668.5 1853,-662.5 1859,-662.5"/>
<text text-anchor="middle" x="1884" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="1921,-662.5 1921,-846.5 "/>
<text text-anchor="middle" x="1931.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1942,-662.5 1942,-846.5 "/>
<text text-anchor="middle" x="2076.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="1942,-823.5 2211,-823.5 "/>
<text text-anchor="middle" x="2076.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="1942,-800.5 2211,-800.5 "/>
<text text-anchor="middle" x="2076.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="1942,-777.5 2211,-777.5 "/>
<text text-anchor="middle" x="2076.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="1942,-754.5 2211,-754.5 "/>
<text text-anchor="middle" x="2076.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="1942,-731.5 2211,-731.5 "/>
<text text-anchor="middle" x="2076.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1942,-708.5 2211,-708.5 "/>
<text text-anchor="middle" x="2076.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="1942,-685.5 2211,-685.5 "/>
<text text-anchor="middle" x="2076.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="2211,-662.5 2211,-846.5 "/>
<text text-anchor="middle" x="2221.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1884.5064,-662.4079C1867.2597,-653.8571 1849.7063,-645.8479 1832.5,-639 1777.1149,-616.9575 1761.134,-616.7442 1702.5,-606 1558.173,-579.5533 1390.9608,-562.0524 1276.2967,-552.037"/>
<polygon fill="#000000" stroke="#000000" points="1276.325,-548.5264 1266.0603,-551.1506 1275.721,-555.5003 1276.325,-548.5264"/>
<text text-anchor="middle" x="1819" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
</g>
</svg>
</div>
