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
<svg width="2298pt" height="1528pt"
 viewBox="0.00 0.00 2298.00 1528.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1524)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1524 2294,-1524 2294,4 -4,4"/>
<!-- synonym -->
<g id="node1" class="node">
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
<g id="node2" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M622,-.5C622,-.5 841,-.5 841,-.5 847,-.5 853,-6.5 853,-12.5 853,-12.5 853,-149.5 853,-149.5 853,-155.5 847,-161.5 841,-161.5 841,-161.5 622,-161.5 622,-161.5 616,-161.5 610,-155.5 610,-149.5 610,-149.5 610,-12.5 610,-12.5 610,-6.5 616,-.5 622,-.5"/>
<text text-anchor="middle" x="638" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="666,-.5 666,-161.5 "/>
<text text-anchor="middle" x="676.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="687,-.5 687,-161.5 "/>
<text text-anchor="middle" x="759.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession</text>
<polyline fill="none" stroke="#000000" points="687,-138.5 832,-138.5 "/>
<text text-anchor="middle" x="759.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="687,-115.5 832,-115.5 "/>
<text text-anchor="middle" x="759.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="687,-92.5 832,-92.5 "/>
<text text-anchor="middle" x="759.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="687,-69.5 832,-69.5 "/>
<text text-anchor="middle" x="759.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="687,-46.5 832,-46.5 "/>
<text text-anchor="middle" x="759.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="687,-23.5 832,-23.5 "/>
<text text-anchor="middle" x="759.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
<polyline fill="none" stroke="#000000" points="832,-.5 832,-161.5 "/>
<text text-anchor="middle" x="842.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M200.1692,-673.9209C211.6288,-651.4398 224.8321,-627.3394 238.5,-606 358.3394,-418.8974 386.9687,-366.6183 547.5,-213 564.152,-197.065 582.8268,-181.506 601.7245,-166.9863"/>
<polygon fill="#000000" stroke="#000000" points="603.985,-169.6645 609.832,-160.8292 599.7514,-164.0899 603.985,-169.6645"/>
<text text-anchor="middle" x="373" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant -->
<g id="node6" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M965,-495.5C965,-495.5 1196,-495.5 1196,-495.5 1202,-495.5 1208,-501.5 1208,-507.5 1208,-507.5 1208,-575.5 1208,-575.5 1208,-581.5 1202,-587.5 1196,-587.5 1196,-587.5 965,-587.5 965,-587.5 959,-587.5 953,-581.5 953,-575.5 953,-575.5 953,-507.5 953,-507.5 953,-501.5 959,-495.5 965,-495.5"/>
<text text-anchor="middle" x="1001" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1049,-495.5 1049,-587.5 "/>
<text text-anchor="middle" x="1059.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1070,-495.5 1070,-587.5 "/>
<text text-anchor="middle" x="1128.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1070,-564.5 1187,-564.5 "/>
<text text-anchor="middle" x="1128.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1070,-541.5 1187,-541.5 "/>
<text text-anchor="middle" x="1128.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1070,-518.5 1187,-518.5 "/>
<text text-anchor="middle" x="1128.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="1187,-495.5 1187,-587.5 "/>
<text text-anchor="middle" x="1197.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M198.2129,-673.7459C213.8247,-647.7724 234.7766,-621.6826 261.5,-606 318.6385,-572.4684 724.2553,-553.634 942.4118,-545.826"/>
<polygon fill="#000000" stroke="#000000" points="942.7868,-549.315 952.6564,-545.4625 942.5386,-542.3194 942.7868,-549.315"/>
<text text-anchor="middle" x="304" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- treatment_response -->
<g id="node3" class="node">
<title>treatment_response</title>
<path fill="none" stroke="#000000" d="M1917,-685.5C1917,-685.5 2278,-685.5 2278,-685.5 2284,-685.5 2290,-691.5 2290,-697.5 2290,-697.5 2290,-811.5 2290,-811.5 2290,-817.5 2284,-823.5 2278,-823.5 2278,-823.5 1917,-823.5 1917,-823.5 1911,-823.5 1905,-817.5 1905,-811.5 1905,-811.5 1905,-697.5 1905,-697.5 1905,-691.5 1911,-685.5 1917,-685.5"/>
<text text-anchor="middle" x="1985.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
<polyline fill="none" stroke="#000000" points="2066,-685.5 2066,-823.5 "/>
<text text-anchor="middle" x="2076.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2087,-685.5 2087,-823.5 "/>
<text text-anchor="middle" x="2178" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_response</text>
<polyline fill="none" stroke="#000000" points="2087,-800.5 2269,-800.5 "/>
<text text-anchor="middle" x="2178" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2087,-777.5 2269,-777.5 "/>
<text text-anchor="middle" x="2178" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="2087,-754.5 2269,-754.5 "/>
<text text-anchor="middle" x="2178" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_category</text>
<polyline fill="none" stroke="#000000" points="2087,-731.5 2269,-731.5 "/>
<text text-anchor="middle" x="2178" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_system</text>
<polyline fill="none" stroke="#000000" points="2087,-708.5 2269,-708.5 "/>
<text text-anchor="middle" x="2178" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response_id</text>
<polyline fill="none" stroke="#000000" points="2269,-685.5 2269,-823.5 "/>
<text text-anchor="middle" x="2279.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1993.6531,-685.35C1941.3682,-654.5971 1875.5962,-621.811 1811.5,-606 1702.6954,-579.1604 1398.2189,-558.7493 1218.3861,-548.6063"/>
<polygon fill="#000000" stroke="#000000" points="1218.5027,-545.1074 1208.3225,-548.0421 1218.1108,-552.0965 1218.5027,-545.1074"/>
<text text-anchor="middle" x="1935.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- genetic_analysis -->
<g id="node4" class="node">
<title>genetic_analysis</title>
<path fill="none" stroke="#000000" d="M458.5,-921.5C458.5,-921.5 842.5,-921.5 842.5,-921.5 848.5,-921.5 854.5,-927.5 854.5,-933.5 854.5,-933.5 854.5,-1507.5 854.5,-1507.5 854.5,-1513.5 848.5,-1519.5 842.5,-1519.5 842.5,-1519.5 458.5,-1519.5 458.5,-1519.5 452.5,-1519.5 446.5,-1513.5 446.5,-1507.5 446.5,-1507.5 446.5,-933.5 446.5,-933.5 446.5,-927.5 452.5,-921.5 458.5,-921.5"/>
<text text-anchor="middle" x="514" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="581.5,-921.5 581.5,-1519.5 "/>
<text text-anchor="middle" x="592" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="602.5,-921.5 602.5,-1519.5 "/>
<text text-anchor="middle" x="718" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="602.5,-1496.5 833.5,-1496.5 "/>
<text text-anchor="middle" x="718" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">allelic_ratio</text>
<polyline fill="none" stroke="#000000" points="602.5,-1473.5 833.5,-1473.5 "/>
<text text-anchor="middle" x="718" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration</text>
<polyline fill="none" stroke="#000000" points="602.5,-1450.5 833.5,-1450.5 "/>
<text text-anchor="middle" x="718" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration_effect</text>
<polyline fill="none" stroke="#000000" points="602.5,-1427.5 833.5,-1427.5 "/>
<text text-anchor="middle" x="718" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration_type</text>
<polyline fill="none" stroke="#000000" points="602.5,-1404.5 833.5,-1404.5 "/>
<text text-anchor="middle" x="718" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="602.5,-1381.5 833.5,-1381.5 "/>
<text text-anchor="middle" x="718" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="602.5,-1358.5 833.5,-1358.5 "/>
<text text-anchor="middle" x="718" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">dna_index_numeric</text>
<polyline fill="none" stroke="#000000" points="602.5,-1335.5 833.5,-1335.5 "/>
<text text-anchor="middle" x="718" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="602.5,-1312.5 833.5,-1312.5 "/>
<text text-anchor="middle" x="718" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_exon</text>
<polyline fill="none" stroke="#000000" points="602.5,-1289.5 833.5,-1289.5 "/>
<text text-anchor="middle" x="718" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_gene</text>
<polyline fill="none" stroke="#000000" points="602.5,-1266.5 833.5,-1266.5 "/>
<text text-anchor="middle" x="718" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_transcript</text>
<polyline fill="none" stroke="#000000" points="602.5,-1243.5 833.5,-1243.5 "/>
<text text-anchor="middle" x="718" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="602.5,-1220.5 833.5,-1220.5 "/>
<text text-anchor="middle" x="718" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis_id</text>
<polyline fill="none" stroke="#000000" points="602.5,-1197.5 833.5,-1197.5 "/>
<text text-anchor="middle" x="718" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_source_category</text>
<polyline fill="none" stroke="#000000" points="602.5,-1174.5 833.5,-1174.5 "/>
<text text-anchor="middle" x="718" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_coding</text>
<polyline fill="none" stroke="#000000" points="602.5,-1151.5 833.5,-1151.5 "/>
<text text-anchor="middle" x="718" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_genome</text>
<polyline fill="none" stroke="#000000" points="602.5,-1128.5 833.5,-1128.5 "/>
<text text-anchor="middle" x="718" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_protein</text>
<polyline fill="none" stroke="#000000" points="602.5,-1105.5 833.5,-1105.5 "/>
<text text-anchor="middle" x="718" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="602.5,-1082.5 833.5,-1082.5 "/>
<text text-anchor="middle" x="718" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">iscn</text>
<polyline fill="none" stroke="#000000" points="602.5,-1059.5 833.5,-1059.5 "/>
<text text-anchor="middle" x="718" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">method</text>
<polyline fill="none" stroke="#000000" points="602.5,-1036.5 833.5,-1036.5 "/>
<text text-anchor="middle" x="718" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome</text>
<polyline fill="none" stroke="#000000" points="602.5,-1013.5 833.5,-1013.5 "/>
<text text-anchor="middle" x="718" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance</text>
<polyline fill="none" stroke="#000000" points="602.5,-990.5 833.5,-990.5 "/>
<text text-anchor="middle" x="718" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance_system</text>
<polyline fill="none" stroke="#000000" points="602.5,-967.5 833.5,-967.5 "/>
<text text-anchor="middle" x="718" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">result</text>
<polyline fill="none" stroke="#000000" points="602.5,-944.5 833.5,-944.5 "/>
<text text-anchor="middle" x="718" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 6 properties</text>
<polyline fill="none" stroke="#000000" points="833.5,-921.5 833.5,-1519.5 "/>
<text text-anchor="middle" x="844" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M446.1914,-1011.0397C414.7362,-967.5114 386.9516,-919.6679 369.5,-870 352.4831,-821.5693 335.7575,-677.6854 369.5,-639 406.5541,-596.5178 746.5566,-565.373 942.6522,-550.7672"/>
<polygon fill="#000000" stroke="#000000" points="943.0334,-554.2486 952.7479,-550.0204 942.5169,-547.2677 943.0334,-554.2486"/>
<text text-anchor="middle" x="439.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- sample -->
<g id="node12" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1435.5,-651C1435.5,-651 1749.5,-651 1749.5,-651 1755.5,-651 1761.5,-657 1761.5,-663 1761.5,-663 1761.5,-846 1761.5,-846 1761.5,-852 1755.5,-858 1749.5,-858 1749.5,-858 1435.5,-858 1435.5,-858 1429.5,-858 1423.5,-852 1423.5,-846 1423.5,-846 1423.5,-663 1423.5,-663 1423.5,-657 1429.5,-651 1435.5,-651"/>
<text text-anchor="middle" x="1457.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1491.5,-651 1491.5,-858 "/>
<text text-anchor="middle" x="1502" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1512.5,-651 1512.5,-858 "/>
<text text-anchor="middle" x="1626.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1512.5,-835 1740.5,-835 "/>
<text text-anchor="middle" x="1626.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1512.5,-812 1740.5,-812 "/>
<text text-anchor="middle" x="1626.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1512.5,-789 1740.5,-789 "/>
<text text-anchor="middle" x="1626.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_necrosis</text>
<polyline fill="none" stroke="#000000" points="1512.5,-766 1740.5,-766 "/>
<text text-anchor="middle" x="1626.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_tumor</text>
<polyline fill="none" stroke="#000000" points="1512.5,-743 1740.5,-743 "/>
<text text-anchor="middle" x="1626.5" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1512.5,-720 1740.5,-720 "/>
<text text-anchor="middle" x="1626.5" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1512.5,-697 1740.5,-697 "/>
<text text-anchor="middle" x="1626.5" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1512.5,-674 1740.5,-674 "/>
<text text-anchor="middle" x="1626.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1740.5,-651 1740.5,-858 "/>
<text text-anchor="middle" x="1751" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M854.5247,-1065.7646C933.8551,-1012.4028 1027.8473,-957.0443 1120.5,-921 1181.2775,-897.356 1348.6714,-893.512 1409.5,-870 1415.5367,-867.6666 1421.5896,-865.1243 1427.6292,-862.4117"/>
<polygon fill="#000000" stroke="#000000" points="1429.5072,-865.3988 1437.1048,-858.0145 1426.5606,-859.0492 1429.5072,-865.3988"/>
<text text-anchor="middle" x="1388.5" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- survival -->
<g id="node5" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M531,-662.5C531,-662.5 892,-662.5 892,-662.5 898,-662.5 904,-668.5 904,-674.5 904,-674.5 904,-834.5 904,-834.5 904,-840.5 898,-846.5 892,-846.5 892,-846.5 531,-846.5 531,-846.5 525,-846.5 519,-840.5 519,-834.5 519,-834.5 519,-674.5 519,-674.5 519,-668.5 525,-662.5 531,-662.5"/>
<text text-anchor="middle" x="556" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="593,-662.5 593,-846.5 "/>
<text text-anchor="middle" x="603.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="614,-662.5 614,-846.5 "/>
<text text-anchor="middle" x="748.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="614,-823.5 883,-823.5 "/>
<text text-anchor="middle" x="748.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="614,-800.5 883,-800.5 "/>
<text text-anchor="middle" x="748.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="614,-777.5 883,-777.5 "/>
<text text-anchor="middle" x="748.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="614,-754.5 883,-754.5 "/>
<text text-anchor="middle" x="748.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="614,-731.5 883,-731.5 "/>
<text text-anchor="middle" x="748.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="614,-708.5 883,-708.5 "/>
<text text-anchor="middle" x="748.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="614,-685.5 883,-685.5 "/>
<text text-anchor="middle" x="748.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="883,-662.5 883,-846.5 "/>
<text text-anchor="middle" x="893.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M870.9346,-662.4687C912.2634,-638.6122 955.3018,-613.7689 991.5461,-592.8474"/>
<polygon fill="#000000" stroke="#000000" points="993.6982,-595.6464 1000.6092,-587.6158 990.1987,-589.5839 993.6982,-595.6464"/>
<text text-anchor="middle" x="1000" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- consent_group -->
<g id="node10" class="node">
<title>consent_group</title>
<path fill="none" stroke="#000000" d="M569,-271C569,-271 894,-271 894,-271 900,-271 906,-277 906,-283 906,-283 906,-374 906,-374 906,-380 900,-386 894,-386 894,-386 569,-386 569,-386 563,-386 557,-380 557,-374 557,-374 557,-283 557,-283 557,-277 563,-271 569,-271"/>
<text text-anchor="middle" x="618" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
<polyline fill="none" stroke="#000000" points="679,-271 679,-386 "/>
<text text-anchor="middle" x="689.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="700,-271 700,-386 "/>
<text text-anchor="middle" x="792.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_id</text>
<polyline fill="none" stroke="#000000" points="700,-363 885,-363 "/>
<text text-anchor="middle" x="792.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_name</text>
<polyline fill="none" stroke="#000000" points="700,-340 885,-340 "/>
<text text-anchor="middle" x="792.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_number</text>
<polyline fill="none" stroke="#000000" points="700,-317 885,-317 "/>
<text text-anchor="middle" x="792.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_suffix</text>
<polyline fill="none" stroke="#000000" points="700,-294 885,-294 "/>
<text text-anchor="middle" x="792.5" y="-278.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="885,-271 885,-386 "/>
<text text-anchor="middle" x="895.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge3" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1001.3505,-495.3107C974.0546,-479.2279 943.3478,-460.9638 915.5,-444 888.0335,-427.2684 858.4499,-408.8684 831.207,-391.7678"/>
<polygon fill="#000000" stroke="#000000" points="832.7791,-388.6221 822.4498,-386.2651 829.0548,-394.5491 832.7791,-388.6221"/>
<text text-anchor="middle" x="1020" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- treatment -->
<g id="node7" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M934.5,-639.5C934.5,-639.5 1226.5,-639.5 1226.5,-639.5 1232.5,-639.5 1238.5,-645.5 1238.5,-651.5 1238.5,-651.5 1238.5,-857.5 1238.5,-857.5 1238.5,-863.5 1232.5,-869.5 1226.5,-869.5 1226.5,-869.5 934.5,-869.5 934.5,-869.5 928.5,-869.5 922.5,-863.5 922.5,-857.5 922.5,-857.5 922.5,-651.5 922.5,-651.5 922.5,-645.5 928.5,-639.5 934.5,-639.5"/>
<text text-anchor="middle" x="967" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1011.5,-639.5 1011.5,-869.5 "/>
<text text-anchor="middle" x="1022" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1032.5,-639.5 1032.5,-869.5 "/>
<text text-anchor="middle" x="1125" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="1032.5,-846.5 1217.5,-846.5 "/>
<text text-anchor="middle" x="1125" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1032.5,-823.5 1217.5,-823.5 "/>
<text text-anchor="middle" x="1125" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose</text>
<polyline fill="none" stroke="#000000" points="1032.5,-800.5 1217.5,-800.5 "/>
<text text-anchor="middle" x="1125" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_frequency</text>
<polyline fill="none" stroke="#000000" points="1032.5,-777.5 1217.5,-777.5 "/>
<text text-anchor="middle" x="1125" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_route</text>
<polyline fill="none" stroke="#000000" points="1032.5,-754.5 1217.5,-754.5 "/>
<text text-anchor="middle" x="1125" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_unit</text>
<polyline fill="none" stroke="#000000" points="1032.5,-731.5 1217.5,-731.5 "/>
<text text-anchor="middle" x="1125" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1032.5,-708.5 1217.5,-708.5 "/>
<text text-anchor="middle" x="1125" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="1032.5,-685.5 1217.5,-685.5 "/>
<text text-anchor="middle" x="1125" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1032.5,-662.5 1217.5,-662.5 "/>
<text text-anchor="middle" x="1125" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1217.5,-639.5 1217.5,-869.5 "/>
<text text-anchor="middle" x="1228" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1080.5,-639.2724C1080.5,-624.8861 1080.5,-610.7136 1080.5,-597.8145"/>
<polygon fill="#000000" stroke="#000000" points="1084.0001,-597.7629 1080.5,-587.7629 1077.0001,-597.763 1084.0001,-597.7629"/>
<text text-anchor="middle" x="1127.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- diagnosis -->
<g id="node8" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1549,-1013.5C1549,-1013.5 1914,-1013.5 1914,-1013.5 1920,-1013.5 1926,-1019.5 1926,-1025.5 1926,-1025.5 1926,-1415.5 1926,-1415.5 1926,-1421.5 1920,-1427.5 1914,-1427.5 1914,-1427.5 1549,-1427.5 1549,-1427.5 1543,-1427.5 1537,-1421.5 1537,-1415.5 1537,-1415.5 1537,-1025.5 1537,-1025.5 1537,-1019.5 1543,-1013.5 1549,-1013.5"/>
<text text-anchor="middle" x="1579" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1621,-1013.5 1621,-1427.5 "/>
<text text-anchor="middle" x="1631.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1642,-1013.5 1642,-1427.5 "/>
<text text-anchor="middle" x="1773.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1642,-1404.5 1905,-1404.5 "/>
<text text-anchor="middle" x="1773.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1642,-1381.5 1905,-1381.5 "/>
<text text-anchor="middle" x="1773.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1642,-1358.5 1905,-1358.5 "/>
<text text-anchor="middle" x="1773.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="1642,-1335.5 1905,-1335.5 "/>
<text text-anchor="middle" x="1773.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_category</text>
<polyline fill="none" stroke="#000000" points="1642,-1312.5 1905,-1312.5 "/>
<text text-anchor="middle" x="1773.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="1642,-1289.5 1905,-1289.5 "/>
<text text-anchor="middle" x="1773.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="1642,-1266.5 1905,-1266.5 "/>
<text text-anchor="middle" x="1773.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1642,-1243.5 1905,-1243.5 "/>
<text text-anchor="middle" x="1773.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="1642,-1220.5 1905,-1220.5 "/>
<text text-anchor="middle" x="1773.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1642,-1197.5 1905,-1197.5 "/>
<text text-anchor="middle" x="1773.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">laterality</text>
<polyline fill="none" stroke="#000000" points="1642,-1174.5 1905,-1174.5 "/>
<text text-anchor="middle" x="1773.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="1642,-1151.5 1905,-1151.5 "/>
<text text-anchor="middle" x="1773.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1642,-1128.5 1905,-1128.5 "/>
<text text-anchor="middle" x="1773.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1642,-1105.5 1905,-1105.5 "/>
<text text-anchor="middle" x="1773.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1642,-1082.5 1905,-1082.5 "/>
<text text-anchor="middle" x="1773.5" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1642,-1059.5 1905,-1059.5 "/>
<text text-anchor="middle" x="1773.5" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1642,-1036.5 1905,-1036.5 "/>
<text text-anchor="middle" x="1773.5" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1905,-1013.5 1905,-1427.5 "/>
<text text-anchor="middle" x="1915.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1775.1881,-1013.3035C1800.1512,-869.2728 1818.025,-693.7126 1770.5,-639 1734.8657,-597.9765 1409.4081,-566.5126 1218.4729,-551.3955"/>
<polygon fill="#000000" stroke="#000000" points="1218.5992,-547.8947 1208.3555,-550.5998 1218.0503,-554.8732 1218.5992,-547.8947"/>
<text text-anchor="middle" x="1844" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1669.7231,-1013.3918C1654.8258,-963.4483 1639.4492,-911.8981 1626.377,-868.0733"/>
<polygon fill="#000000" stroke="#000000" points="1629.6642,-866.8487 1623.4518,-858.2664 1622.9563,-868.8496 1629.6642,-866.8487"/>
<text text-anchor="middle" x="1678" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- laboratory_test -->
<g id="node9" class="node">
<title>laboratory_test</title>
<path fill="none" stroke="#000000" d="M1141.5,-1094C1141.5,-1094 1473.5,-1094 1473.5,-1094 1479.5,-1094 1485.5,-1100 1485.5,-1106 1485.5,-1106 1485.5,-1335 1485.5,-1335 1485.5,-1341 1479.5,-1347 1473.5,-1347 1473.5,-1347 1141.5,-1347 1141.5,-1347 1135.5,-1347 1129.5,-1341 1129.5,-1335 1129.5,-1335 1129.5,-1106 1129.5,-1106 1129.5,-1100 1135.5,-1094 1141.5,-1094"/>
<text text-anchor="middle" x="1192.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="1255.5,-1094 1255.5,-1347 "/>
<text text-anchor="middle" x="1266" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1276.5,-1094 1276.5,-1347 "/>
<text text-anchor="middle" x="1370.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_laboratory_test</text>
<polyline fill="none" stroke="#000000" points="1276.5,-1324 1464.5,-1324 "/>
<text text-anchor="middle" x="1370.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1276.5,-1301 1464.5,-1301 "/>
<text text-anchor="middle" x="1370.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_id</text>
<polyline fill="none" stroke="#000000" points="1276.5,-1278 1464.5,-1278 "/>
<text text-anchor="middle" x="1370.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_method</text>
<polyline fill="none" stroke="#000000" points="1276.5,-1255 1464.5,-1255 "/>
<text text-anchor="middle" x="1370.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_name</text>
<polyline fill="none" stroke="#000000" points="1276.5,-1232 1464.5,-1232 "/>
<text text-anchor="middle" x="1370.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">sensitivity</text>
<polyline fill="none" stroke="#000000" points="1276.5,-1209 1464.5,-1209 "/>
<text text-anchor="middle" x="1370.5" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">specimen</text>
<polyline fill="none" stroke="#000000" points="1276.5,-1186 1464.5,-1186 "/>
<text text-anchor="middle" x="1370.5" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_modifier</text>
<polyline fill="none" stroke="#000000" points="1276.5,-1163 1464.5,-1163 "/>
<text text-anchor="middle" x="1370.5" y="-1147.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_numeric</text>
<polyline fill="none" stroke="#000000" points="1276.5,-1140 1464.5,-1140 "/>
<text text-anchor="middle" x="1370.5" y="-1124.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_text</text>
<polyline fill="none" stroke="#000000" points="1276.5,-1117 1464.5,-1117 "/>
<text text-anchor="middle" x="1370.5" y="-1101.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_unit</text>
<polyline fill="none" stroke="#000000" points="1464.5,-1094 1464.5,-1347 "/>
<text text-anchor="middle" x="1475" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1297.3608,-1093.9406C1283.6914,-928.6302 1259.6662,-657.8734 1247.5,-639 1235.8272,-620.892 1219.5129,-605.7358 1201.6175,-593.1894"/>
<polygon fill="#000000" stroke="#000000" points="1203.5495,-590.2709 1193.295,-587.6072 1199.6502,-596.0843 1203.5495,-590.2709"/>
<text text-anchor="middle" x="1342" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1376.6941,-1093.7459C1411.8412,-1031.0269 1456.0098,-954.6644 1498.5,-888 1502.9897,-880.9559 1507.6914,-873.7646 1512.4967,-866.5532"/>
<polygon fill="#000000" stroke="#000000" points="1515.5126,-868.34 1518.1788,-858.0861 1509.7001,-864.4393 1515.5126,-868.34"/>
<text text-anchor="middle" x="1564" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge7" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M731.5,-270.7846C731.5,-241.3997 731.5,-204.9895 731.5,-171.9435"/>
<polygon fill="#000000" stroke="#000000" points="735.0001,-171.8072 731.5,-161.8073 728.0001,-171.8073 735.0001,-171.8072"/>
<text text-anchor="middle" x="795" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- reference_file -->
<g id="node11" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M936,-213.5C936,-213.5 1213,-213.5 1213,-213.5 1219,-213.5 1225,-219.5 1225,-225.5 1225,-225.5 1225,-431.5 1225,-431.5 1225,-437.5 1219,-443.5 1213,-443.5 1213,-443.5 936,-443.5 936,-443.5 930,-443.5 924,-437.5 924,-431.5 924,-431.5 924,-225.5 924,-225.5 924,-219.5 930,-213.5 936,-213.5"/>
<text text-anchor="middle" x="982" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="1040,-213.5 1040,-443.5 "/>
<text text-anchor="middle" x="1050.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1061,-213.5 1061,-443.5 "/>
<text text-anchor="middle" x="1132.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1061,-420.5 1204,-420.5 "/>
<text text-anchor="middle" x="1132.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="1061,-397.5 1204,-397.5 "/>
<text text-anchor="middle" x="1132.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1061,-374.5 1204,-374.5 "/>
<text text-anchor="middle" x="1132.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1061,-351.5 1204,-351.5 "/>
<text text-anchor="middle" x="1132.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1061,-328.5 1204,-328.5 "/>
<text text-anchor="middle" x="1132.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1061,-305.5 1204,-305.5 "/>
<text text-anchor="middle" x="1132.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1061,-282.5 1204,-282.5 "/>
<text text-anchor="middle" x="1132.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1061,-259.5 1204,-259.5 "/>
<text text-anchor="middle" x="1132.5" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="1061,-236.5 1204,-236.5 "/>
<text text-anchor="middle" x="1132.5" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="1204,-213.5 1204,-443.5 "/>
<text text-anchor="middle" x="1214.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge5" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M923.8722,-219.0471C921.0592,-217.0142 918.2664,-214.997 915.5,-213 895.0979,-198.2719 873.3961,-182.6572 852.3197,-167.52"/>
<polygon fill="#000000" stroke="#000000" points="854.1283,-164.5099 843.964,-161.5203 850.0455,-170.1959 854.1283,-164.5099"/>
<text text-anchor="middle" x="951" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1433.9998,-650.8933C1425.821,-646.6778 1417.6269,-642.6836 1409.5,-639 1348.7211,-611.4516 1278.1419,-589.3443 1217.9751,-573.1908"/>
<polygon fill="#000000" stroke="#000000" points="1218.5903,-569.7329 1208.0269,-570.5484 1216.7933,-576.4983 1218.5903,-569.7329"/>
<text text-anchor="middle" x="1403" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
</g>
</svg>
</div>
