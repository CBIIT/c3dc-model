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
<svg width="2350pt" height="1528pt"
 viewBox="0.00 0.00 2349.50 1528.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1524)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1524 2345.5,-1524 2345.5,4 -4,4"/>
<!-- genetic_analysis -->
<g id="node1" class="node">
<title>genetic_analysis</title>
<path fill="none" stroke="#000000" d="M1901.5,-921.5C1901.5,-921.5 2285.5,-921.5 2285.5,-921.5 2291.5,-921.5 2297.5,-927.5 2297.5,-933.5 2297.5,-933.5 2297.5,-1507.5 2297.5,-1507.5 2297.5,-1513.5 2291.5,-1519.5 2285.5,-1519.5 2285.5,-1519.5 1901.5,-1519.5 1901.5,-1519.5 1895.5,-1519.5 1889.5,-1513.5 1889.5,-1507.5 1889.5,-1507.5 1889.5,-933.5 1889.5,-933.5 1889.5,-927.5 1895.5,-921.5 1901.5,-921.5"/>
<text text-anchor="middle" x="1957" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="2024.5,-921.5 2024.5,-1519.5 "/>
<text text-anchor="middle" x="2035" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2045.5,-921.5 2045.5,-1519.5 "/>
<text text-anchor="middle" x="2161" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="2045.5,-1496.5 2276.5,-1496.5 "/>
<text text-anchor="middle" x="2161" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">allelic_ratio</text>
<polyline fill="none" stroke="#000000" points="2045.5,-1473.5 2276.5,-1473.5 "/>
<text text-anchor="middle" x="2161" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration</text>
<polyline fill="none" stroke="#000000" points="2045.5,-1450.5 2276.5,-1450.5 "/>
<text text-anchor="middle" x="2161" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration_effect</text>
<polyline fill="none" stroke="#000000" points="2045.5,-1427.5 2276.5,-1427.5 "/>
<text text-anchor="middle" x="2161" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration_type</text>
<polyline fill="none" stroke="#000000" points="2045.5,-1404.5 2276.5,-1404.5 "/>
<text text-anchor="middle" x="2161" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="2045.5,-1381.5 2276.5,-1381.5 "/>
<text text-anchor="middle" x="2161" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="2045.5,-1358.5 2276.5,-1358.5 "/>
<text text-anchor="middle" x="2161" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">dna_index_numeric</text>
<polyline fill="none" stroke="#000000" points="2045.5,-1335.5 2276.5,-1335.5 "/>
<text text-anchor="middle" x="2161" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="2045.5,-1312.5 2276.5,-1312.5 "/>
<text text-anchor="middle" x="2161" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_exon</text>
<polyline fill="none" stroke="#000000" points="2045.5,-1289.5 2276.5,-1289.5 "/>
<text text-anchor="middle" x="2161" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_gene</text>
<polyline fill="none" stroke="#000000" points="2045.5,-1266.5 2276.5,-1266.5 "/>
<text text-anchor="middle" x="2161" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_transcript</text>
<polyline fill="none" stroke="#000000" points="2045.5,-1243.5 2276.5,-1243.5 "/>
<text text-anchor="middle" x="2161" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="2045.5,-1220.5 2276.5,-1220.5 "/>
<text text-anchor="middle" x="2161" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis_id</text>
<polyline fill="none" stroke="#000000" points="2045.5,-1197.5 2276.5,-1197.5 "/>
<text text-anchor="middle" x="2161" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_source_category</text>
<polyline fill="none" stroke="#000000" points="2045.5,-1174.5 2276.5,-1174.5 "/>
<text text-anchor="middle" x="2161" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_coding</text>
<polyline fill="none" stroke="#000000" points="2045.5,-1151.5 2276.5,-1151.5 "/>
<text text-anchor="middle" x="2161" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_genome</text>
<polyline fill="none" stroke="#000000" points="2045.5,-1128.5 2276.5,-1128.5 "/>
<text text-anchor="middle" x="2161" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_protein</text>
<polyline fill="none" stroke="#000000" points="2045.5,-1105.5 2276.5,-1105.5 "/>
<text text-anchor="middle" x="2161" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2045.5,-1082.5 2276.5,-1082.5 "/>
<text text-anchor="middle" x="2161" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">iscn</text>
<polyline fill="none" stroke="#000000" points="2045.5,-1059.5 2276.5,-1059.5 "/>
<text text-anchor="middle" x="2161" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">method</text>
<polyline fill="none" stroke="#000000" points="2045.5,-1036.5 2276.5,-1036.5 "/>
<text text-anchor="middle" x="2161" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome</text>
<polyline fill="none" stroke="#000000" points="2045.5,-1013.5 2276.5,-1013.5 "/>
<text text-anchor="middle" x="2161" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance</text>
<polyline fill="none" stroke="#000000" points="2045.5,-990.5 2276.5,-990.5 "/>
<text text-anchor="middle" x="2161" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance_system</text>
<polyline fill="none" stroke="#000000" points="2045.5,-967.5 2276.5,-967.5 "/>
<text text-anchor="middle" x="2161" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">result</text>
<polyline fill="none" stroke="#000000" points="2045.5,-944.5 2276.5,-944.5 "/>
<text text-anchor="middle" x="2161" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 6 properties</text>
<polyline fill="none" stroke="#000000" points="2276.5,-921.5 2276.5,-1519.5 "/>
<text text-anchor="middle" x="2287" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node10" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M901,-495.5C901,-495.5 1132,-495.5 1132,-495.5 1138,-495.5 1144,-501.5 1144,-507.5 1144,-507.5 1144,-575.5 1144,-575.5 1144,-581.5 1138,-587.5 1132,-587.5 1132,-587.5 901,-587.5 901,-587.5 895,-587.5 889,-581.5 889,-575.5 889,-575.5 889,-507.5 889,-507.5 889,-501.5 895,-495.5 901,-495.5"/>
<text text-anchor="middle" x="937" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="985,-495.5 985,-587.5 "/>
<text text-anchor="middle" x="995.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1006,-495.5 1006,-587.5 "/>
<text text-anchor="middle" x="1064.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1006,-564.5 1123,-564.5 "/>
<text text-anchor="middle" x="1064.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1006,-541.5 1123,-541.5 "/>
<text text-anchor="middle" x="1064.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1006,-518.5 1123,-518.5 "/>
<text text-anchor="middle" x="1064.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="1123,-495.5 1123,-587.5 "/>
<text text-anchor="middle" x="1133.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2195.7522,-921.1316C2210.6882,-821.0081 2202.756,-715.536 2136.5,-639 2073.3671,-566.0716 1439.8958,-547.6353 1154.5569,-543.0202"/>
<polygon fill="#000000" stroke="#000000" points="1154.1937,-539.5141 1144.1396,-542.8553 1154.0829,-546.5132 1154.1937,-539.5141"/>
<text text-anchor="middle" x="2271.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- sample -->
<g id="node11" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M479.5,-651C479.5,-651 793.5,-651 793.5,-651 799.5,-651 805.5,-657 805.5,-663 805.5,-663 805.5,-846 805.5,-846 805.5,-852 799.5,-858 793.5,-858 793.5,-858 479.5,-858 479.5,-858 473.5,-858 467.5,-852 467.5,-846 467.5,-846 467.5,-663 467.5,-663 467.5,-657 473.5,-651 479.5,-651"/>
<text text-anchor="middle" x="501.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="535.5,-651 535.5,-858 "/>
<text text-anchor="middle" x="546" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="556.5,-651 556.5,-858 "/>
<text text-anchor="middle" x="670.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="556.5,-835 784.5,-835 "/>
<text text-anchor="middle" x="670.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="556.5,-812 784.5,-812 "/>
<text text-anchor="middle" x="670.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="556.5,-789 784.5,-789 "/>
<text text-anchor="middle" x="670.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_necrosis</text>
<polyline fill="none" stroke="#000000" points="556.5,-766 784.5,-766 "/>
<text text-anchor="middle" x="670.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_tumor</text>
<polyline fill="none" stroke="#000000" points="556.5,-743 784.5,-743 "/>
<text text-anchor="middle" x="670.5" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="556.5,-720 784.5,-720 "/>
<text text-anchor="middle" x="670.5" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="556.5,-697 784.5,-697 "/>
<text text-anchor="middle" x="670.5" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="556.5,-674 784.5,-674 "/>
<text text-anchor="middle" x="670.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="784.5,-651 784.5,-858 "/>
<text text-anchor="middle" x="795" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1889.3328,-1109.4793C1757.2608,-1043.0777 1579.4216,-963.5699 1412.5,-921 1347.8826,-904.5207 877.5803,-891.6299 814.5,-870 807.7321,-867.6793 800.9666,-865.046 794.2421,-862.1608"/>
<polygon fill="#000000" stroke="#000000" points="795.6592,-858.9605 785.1013,-858.076 792.8032,-865.3514 795.6592,-858.9605"/>
<text text-anchor="middle" x="1262.5" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- synonym -->
<g id="node2" class="node">
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
<g id="node5" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M406,-.5C406,-.5 625,-.5 625,-.5 631,-.5 637,-6.5 637,-12.5 637,-12.5 637,-149.5 637,-149.5 637,-155.5 631,-161.5 625,-161.5 625,-161.5 406,-161.5 406,-161.5 400,-161.5 394,-155.5 394,-149.5 394,-149.5 394,-12.5 394,-12.5 394,-6.5 400,-.5 406,-.5"/>
<text text-anchor="middle" x="422" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="450,-.5 450,-161.5 "/>
<text text-anchor="middle" x="460.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="471,-.5 471,-161.5 "/>
<text text-anchor="middle" x="543.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession</text>
<polyline fill="none" stroke="#000000" points="471,-138.5 616,-138.5 "/>
<text text-anchor="middle" x="543.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="471,-115.5 616,-115.5 "/>
<text text-anchor="middle" x="543.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="471,-92.5 616,-92.5 "/>
<text text-anchor="middle" x="543.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="471,-69.5 616,-69.5 "/>
<text text-anchor="middle" x="543.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="471,-46.5 616,-46.5 "/>
<text text-anchor="middle" x="543.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="471,-23.5 616,-23.5 "/>
<text text-anchor="middle" x="543.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
<polyline fill="none" stroke="#000000" points="616,-.5 616,-161.5 "/>
<text text-anchor="middle" x="626.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M177.1167,-673.8876C200.3274,-562.2686 253.7712,-358.0296 355.5,-213 366.506,-197.3093 379.8514,-182.4373 394.0877,-168.722"/>
<polygon fill="#000000" stroke="#000000" points="396.7154,-171.0556 401.6059,-161.657 391.9217,-165.9545 396.7154,-171.0556"/>
<text text-anchor="middle" x="276" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M198.271,-673.8445C213.8882,-647.8803 234.8288,-621.7711 261.5,-606 313.1771,-575.4426 675.0396,-555.6684 878.4504,-546.8363"/>
<polygon fill="#000000" stroke="#000000" points="878.7745,-550.3257 888.6146,-546.3984 878.4731,-543.3322 878.7745,-550.3257"/>
<text text-anchor="middle" x="304" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- laboratory_test -->
<g id="node3" class="node">
<title>laboratory_test</title>
<path fill="none" stroke="#000000" d="M1059.5,-1094C1059.5,-1094 1391.5,-1094 1391.5,-1094 1397.5,-1094 1403.5,-1100 1403.5,-1106 1403.5,-1106 1403.5,-1335 1403.5,-1335 1403.5,-1341 1397.5,-1347 1391.5,-1347 1391.5,-1347 1059.5,-1347 1059.5,-1347 1053.5,-1347 1047.5,-1341 1047.5,-1335 1047.5,-1335 1047.5,-1106 1047.5,-1106 1047.5,-1100 1053.5,-1094 1059.5,-1094"/>
<text text-anchor="middle" x="1110.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="1173.5,-1094 1173.5,-1347 "/>
<text text-anchor="middle" x="1184" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1194.5,-1094 1194.5,-1347 "/>
<text text-anchor="middle" x="1288.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_laboratory_test</text>
<polyline fill="none" stroke="#000000" points="1194.5,-1324 1382.5,-1324 "/>
<text text-anchor="middle" x="1288.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1194.5,-1301 1382.5,-1301 "/>
<text text-anchor="middle" x="1288.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_id</text>
<polyline fill="none" stroke="#000000" points="1194.5,-1278 1382.5,-1278 "/>
<text text-anchor="middle" x="1288.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_method</text>
<polyline fill="none" stroke="#000000" points="1194.5,-1255 1382.5,-1255 "/>
<text text-anchor="middle" x="1288.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_name</text>
<polyline fill="none" stroke="#000000" points="1194.5,-1232 1382.5,-1232 "/>
<text text-anchor="middle" x="1288.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">sensitivity</text>
<polyline fill="none" stroke="#000000" points="1194.5,-1209 1382.5,-1209 "/>
<text text-anchor="middle" x="1288.5" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">specimen</text>
<polyline fill="none" stroke="#000000" points="1194.5,-1186 1382.5,-1186 "/>
<text text-anchor="middle" x="1288.5" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_modifier</text>
<polyline fill="none" stroke="#000000" points="1194.5,-1163 1382.5,-1163 "/>
<text text-anchor="middle" x="1288.5" y="-1147.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_numeric</text>
<polyline fill="none" stroke="#000000" points="1194.5,-1140 1382.5,-1140 "/>
<text text-anchor="middle" x="1288.5" y="-1124.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_text</text>
<polyline fill="none" stroke="#000000" points="1194.5,-1117 1382.5,-1117 "/>
<text text-anchor="middle" x="1288.5" y="-1101.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_unit</text>
<polyline fill="none" stroke="#000000" points="1382.5,-1094 1382.5,-1347 "/>
<text text-anchor="middle" x="1393" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1403.5919,-1140.7329C1614.4606,-1045.4454 1939.3803,-895.6211 1955.5,-870 2010.1727,-783.1016 2023.9564,-715.5125 1955.5,-639 1903.1209,-580.4568 1402.5603,-554.9167 1154.4781,-545.7816"/>
<polygon fill="#000000" stroke="#000000" points="1154.43,-542.2776 1144.3092,-545.4112 1154.1751,-549.273 1154.43,-542.2776"/>
<text text-anchor="middle" x="2067" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1065.3312,-1093.779C974.6527,-1022.0367 862.3497,-933.1859 775.4178,-864.4078"/>
<polygon fill="#000000" stroke="#000000" points="777.3657,-861.486 767.3517,-858.0262 773.0225,-866.9757 777.3657,-861.486"/>
<text text-anchor="middle" x="877" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- diagnosis -->
<g id="node4" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M295,-1013.5C295,-1013.5 660,-1013.5 660,-1013.5 666,-1013.5 672,-1019.5 672,-1025.5 672,-1025.5 672,-1415.5 672,-1415.5 672,-1421.5 666,-1427.5 660,-1427.5 660,-1427.5 295,-1427.5 295,-1427.5 289,-1427.5 283,-1421.5 283,-1415.5 283,-1415.5 283,-1025.5 283,-1025.5 283,-1019.5 289,-1013.5 295,-1013.5"/>
<text text-anchor="middle" x="325" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="367,-1013.5 367,-1427.5 "/>
<text text-anchor="middle" x="377.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="388,-1013.5 388,-1427.5 "/>
<text text-anchor="middle" x="519.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="388,-1404.5 651,-1404.5 "/>
<text text-anchor="middle" x="519.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="388,-1381.5 651,-1381.5 "/>
<text text-anchor="middle" x="519.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="388,-1358.5 651,-1358.5 "/>
<text text-anchor="middle" x="519.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="388,-1335.5 651,-1335.5 "/>
<text text-anchor="middle" x="519.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_category</text>
<polyline fill="none" stroke="#000000" points="388,-1312.5 651,-1312.5 "/>
<text text-anchor="middle" x="519.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="388,-1289.5 651,-1289.5 "/>
<text text-anchor="middle" x="519.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="388,-1266.5 651,-1266.5 "/>
<text text-anchor="middle" x="519.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="388,-1243.5 651,-1243.5 "/>
<text text-anchor="middle" x="519.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="388,-1220.5 651,-1220.5 "/>
<text text-anchor="middle" x="519.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="388,-1197.5 651,-1197.5 "/>
<text text-anchor="middle" x="519.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">laterality</text>
<polyline fill="none" stroke="#000000" points="388,-1174.5 651,-1174.5 "/>
<text text-anchor="middle" x="519.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="388,-1151.5 651,-1151.5 "/>
<text text-anchor="middle" x="519.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="388,-1128.5 651,-1128.5 "/>
<text text-anchor="middle" x="519.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="388,-1105.5 651,-1105.5 "/>
<text text-anchor="middle" x="519.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="388,-1082.5 651,-1082.5 "/>
<text text-anchor="middle" x="519.5" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="388,-1059.5 651,-1059.5 "/>
<text text-anchor="middle" x="519.5" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="388,-1036.5 651,-1036.5 "/>
<text text-anchor="middle" x="519.5" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="651,-1013.5 651,-1427.5 "/>
<text text-anchor="middle" x="661.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M404.9562,-1013.1514C360.9211,-869.5699 321.6101,-694.6474 369.5,-639 402.2707,-600.9209 698.7133,-568.9105 878.7646,-552.7655"/>
<polygon fill="#000000" stroke="#000000" points="879.1992,-556.2407 888.8491,-551.8669 878.5778,-549.2683 879.1992,-556.2407"/>
<text text-anchor="middle" x="414" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M548.1657,-1013.3918C565.2423,-963.3434 582.8694,-911.6815 597.8428,-867.7971"/>
<polygon fill="#000000" stroke="#000000" points="601.1779,-868.8609 601.0947,-858.2664 594.5529,-866.6004 601.1779,-868.8609"/>
<text text-anchor="middle" x="635" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- treatment_response -->
<g id="node6" class="node">
<title>treatment_response</title>
<path fill="none" stroke="#000000" d="M836,-685.5C836,-685.5 1197,-685.5 1197,-685.5 1203,-685.5 1209,-691.5 1209,-697.5 1209,-697.5 1209,-811.5 1209,-811.5 1209,-817.5 1203,-823.5 1197,-823.5 1197,-823.5 836,-823.5 836,-823.5 830,-823.5 824,-817.5 824,-811.5 824,-811.5 824,-697.5 824,-697.5 824,-691.5 830,-685.5 836,-685.5"/>
<text text-anchor="middle" x="904.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
<polyline fill="none" stroke="#000000" points="985,-685.5 985,-823.5 "/>
<text text-anchor="middle" x="995.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1006,-685.5 1006,-823.5 "/>
<text text-anchor="middle" x="1097" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_response</text>
<polyline fill="none" stroke="#000000" points="1006,-800.5 1188,-800.5 "/>
<text text-anchor="middle" x="1097" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1006,-777.5 1188,-777.5 "/>
<text text-anchor="middle" x="1097" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="1006,-754.5 1188,-754.5 "/>
<text text-anchor="middle" x="1097" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_category</text>
<polyline fill="none" stroke="#000000" points="1006,-731.5 1188,-731.5 "/>
<text text-anchor="middle" x="1097" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_system</text>
<polyline fill="none" stroke="#000000" points="1006,-708.5 1188,-708.5 "/>
<text text-anchor="middle" x="1097" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response_id</text>
<polyline fill="none" stroke="#000000" points="1188,-685.5 1188,-823.5 "/>
<text text-anchor="middle" x="1198.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1016.5,-685.345C1016.5,-657.1412 1016.5,-624.9366 1016.5,-598.1595"/>
<polygon fill="#000000" stroke="#000000" points="1020.0001,-597.805 1016.5,-587.805 1013.0001,-597.805 1020.0001,-597.805"/>
<text text-anchor="middle" x="1099.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- reference_file -->
<g id="node7" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M377,-213.5C377,-213.5 654,-213.5 654,-213.5 660,-213.5 666,-219.5 666,-225.5 666,-225.5 666,-431.5 666,-431.5 666,-437.5 660,-443.5 654,-443.5 654,-443.5 377,-443.5 377,-443.5 371,-443.5 365,-437.5 365,-431.5 365,-431.5 365,-225.5 365,-225.5 365,-219.5 371,-213.5 377,-213.5"/>
<text text-anchor="middle" x="423" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="481,-213.5 481,-443.5 "/>
<text text-anchor="middle" x="491.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="502,-213.5 502,-443.5 "/>
<text text-anchor="middle" x="573.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="502,-420.5 645,-420.5 "/>
<text text-anchor="middle" x="573.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="502,-397.5 645,-397.5 "/>
<text text-anchor="middle" x="573.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="502,-374.5 645,-374.5 "/>
<text text-anchor="middle" x="573.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="502,-351.5 645,-351.5 "/>
<text text-anchor="middle" x="573.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="502,-328.5 645,-328.5 "/>
<text text-anchor="middle" x="573.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="502,-305.5 645,-305.5 "/>
<text text-anchor="middle" x="573.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="502,-282.5 645,-282.5 "/>
<text text-anchor="middle" x="573.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="502,-259.5 645,-259.5 "/>
<text text-anchor="middle" x="573.5" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="502,-236.5 645,-236.5 "/>
<text text-anchor="middle" x="573.5" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="645,-213.5 645,-443.5 "/>
<text text-anchor="middle" x="655.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge11" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M515.5,-213.4448C515.5,-199.4621 515.5,-185.3307 515.5,-171.7693"/>
<polygon fill="#000000" stroke="#000000" points="519.0001,-171.5218 515.5,-161.5218 512.0001,-171.5219 519.0001,-171.5218"/>
<text text-anchor="middle" x="576" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- survival -->
<g id="node8" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M1239,-662.5C1239,-662.5 1600,-662.5 1600,-662.5 1606,-662.5 1612,-668.5 1612,-674.5 1612,-674.5 1612,-834.5 1612,-834.5 1612,-840.5 1606,-846.5 1600,-846.5 1600,-846.5 1239,-846.5 1239,-846.5 1233,-846.5 1227,-840.5 1227,-834.5 1227,-834.5 1227,-674.5 1227,-674.5 1227,-668.5 1233,-662.5 1239,-662.5"/>
<text text-anchor="middle" x="1264" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="1301,-662.5 1301,-846.5 "/>
<text text-anchor="middle" x="1311.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1322,-662.5 1322,-846.5 "/>
<text text-anchor="middle" x="1456.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="1322,-823.5 1591,-823.5 "/>
<text text-anchor="middle" x="1456.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="1322,-800.5 1591,-800.5 "/>
<text text-anchor="middle" x="1456.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="1322,-777.5 1591,-777.5 "/>
<text text-anchor="middle" x="1456.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="1322,-754.5 1591,-754.5 "/>
<text text-anchor="middle" x="1456.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="1322,-731.5 1591,-731.5 "/>
<text text-anchor="middle" x="1456.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1322,-708.5 1591,-708.5 "/>
<text text-anchor="middle" x="1456.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="1322,-685.5 1591,-685.5 "/>
<text text-anchor="middle" x="1456.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="1591,-662.5 1591,-846.5 "/>
<text text-anchor="middle" x="1601.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1285.1701,-662.3227C1253.5245,-642.4681 1219.4064,-622.51 1186.5,-606 1176.0297,-600.7468 1165.0227,-595.6612 1153.8547,-590.8051"/>
<polygon fill="#000000" stroke="#000000" points="1155.0146,-587.4946 1144.4438,-586.7813 1152.2626,-593.9309 1155.0146,-587.4946"/>
<text text-anchor="middle" x="1253" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- treatment -->
<g id="node9" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M1642.5,-639.5C1642.5,-639.5 1934.5,-639.5 1934.5,-639.5 1940.5,-639.5 1946.5,-645.5 1946.5,-651.5 1946.5,-651.5 1946.5,-857.5 1946.5,-857.5 1946.5,-863.5 1940.5,-869.5 1934.5,-869.5 1934.5,-869.5 1642.5,-869.5 1642.5,-869.5 1636.5,-869.5 1630.5,-863.5 1630.5,-857.5 1630.5,-857.5 1630.5,-651.5 1630.5,-651.5 1630.5,-645.5 1636.5,-639.5 1642.5,-639.5"/>
<text text-anchor="middle" x="1675" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1719.5,-639.5 1719.5,-869.5 "/>
<text text-anchor="middle" x="1730" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1740.5,-639.5 1740.5,-869.5 "/>
<text text-anchor="middle" x="1833" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="1740.5,-846.5 1925.5,-846.5 "/>
<text text-anchor="middle" x="1833" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1740.5,-823.5 1925.5,-823.5 "/>
<text text-anchor="middle" x="1833" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose</text>
<polyline fill="none" stroke="#000000" points="1740.5,-800.5 1925.5,-800.5 "/>
<text text-anchor="middle" x="1833" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_frequency</text>
<polyline fill="none" stroke="#000000" points="1740.5,-777.5 1925.5,-777.5 "/>
<text text-anchor="middle" x="1833" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_route</text>
<polyline fill="none" stroke="#000000" points="1740.5,-754.5 1925.5,-754.5 "/>
<text text-anchor="middle" x="1833" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_unit</text>
<polyline fill="none" stroke="#000000" points="1740.5,-731.5 1925.5,-731.5 "/>
<text text-anchor="middle" x="1833" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1740.5,-708.5 1925.5,-708.5 "/>
<text text-anchor="middle" x="1833" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="1740.5,-685.5 1925.5,-685.5 "/>
<text text-anchor="middle" x="1833" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1740.5,-662.5 1925.5,-662.5 "/>
<text text-anchor="middle" x="1833" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1925.5,-639.5 1925.5,-869.5 "/>
<text text-anchor="middle" x="1936" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1630.3251,-642.7248C1627.3864,-641.4274 1624.4435,-640.184 1621.5,-639 1538.943,-605.7928 1305.9511,-574.3523 1154.3763,-556.5487"/>
<polygon fill="#000000" stroke="#000000" points="1154.3985,-553.0276 1144.0599,-555.3433 1153.586,-559.9803 1154.3985,-553.0276"/>
<text text-anchor="middle" x="1608.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- consent_group -->
<g id="node12" class="node">
<title>consent_group</title>
<path fill="none" stroke="#000000" d="M775,-271C775,-271 1100,-271 1100,-271 1106,-271 1112,-277 1112,-283 1112,-283 1112,-374 1112,-374 1112,-380 1106,-386 1100,-386 1100,-386 775,-386 775,-386 769,-386 763,-380 763,-374 763,-374 763,-283 763,-283 763,-277 769,-271 775,-271"/>
<text text-anchor="middle" x="824" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
<polyline fill="none" stroke="#000000" points="885,-271 885,-386 "/>
<text text-anchor="middle" x="895.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="906,-271 906,-386 "/>
<text text-anchor="middle" x="998.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_id</text>
<polyline fill="none" stroke="#000000" points="906,-363 1091,-363 "/>
<text text-anchor="middle" x="998.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_name</text>
<polyline fill="none" stroke="#000000" points="906,-340 1091,-340 "/>
<text text-anchor="middle" x="998.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_number</text>
<polyline fill="none" stroke="#000000" points="906,-317 1091,-317 "/>
<text text-anchor="middle" x="998.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_suffix</text>
<polyline fill="none" stroke="#000000" points="906,-294 1091,-294 "/>
<text text-anchor="middle" x="998.5" y="-278.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1091,-271 1091,-386 "/>
<text text-anchor="middle" x="1101.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge5" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M999.3582,-495.2822C988.5368,-466.1056 974.3773,-427.9287 962.3364,-395.4641"/>
<polygon fill="#000000" stroke="#000000" points="965.5969,-394.19 958.8379,-386.0312 959.0338,-396.6242 965.5969,-394.19"/>
<text text-anchor="middle" x="1042" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M794.0603,-650.7963C800.925,-646.7434 807.7584,-642.7944 814.5,-639 843.4854,-622.6862 875.6159,-606.4048 905.566,-591.9501"/>
<polygon fill="#000000" stroke="#000000" points="907.2844,-595.0076 914.785,-587.5248 904.2552,-588.697 907.2844,-595.0076"/>
<text text-anchor="middle" x="911" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge2" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M839.3583,-270.9406C781.7954,-237.1803 708.3532,-194.1071 645.9639,-157.5161"/>
<polygon fill="#000000" stroke="#000000" points="647.6332,-154.4377 637.2366,-152.3977 644.0919,-160.4758 647.6332,-154.4377"/>
<text text-anchor="middle" x="765" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
</g>
</svg>
</div>
