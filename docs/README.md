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
 viewBox="0.00 0.00 2437.92 1528.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1524)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1524 2433.925,-1524 2433.925,4 -4,4"/>
<!-- study -->
<g id="node1" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1990.925,-.5C1990.925,-.5 2209.925,-.5 2209.925,-.5 2215.925,-.5 2221.925,-6.5 2221.925,-12.5 2221.925,-12.5 2221.925,-149.5 2221.925,-149.5 2221.925,-155.5 2215.925,-161.5 2209.925,-161.5 2209.925,-161.5 1990.925,-161.5 1990.925,-161.5 1984.925,-161.5 1978.925,-155.5 1978.925,-149.5 1978.925,-149.5 1978.925,-12.5 1978.925,-12.5 1978.925,-6.5 1984.925,-.5 1990.925,-.5"/>
<text text-anchor="middle" x="2006.925" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="2034.925,-.5 2034.925,-161.5 "/>
<text text-anchor="middle" x="2045.425" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2055.925,-.5 2055.925,-161.5 "/>
<text text-anchor="middle" x="2128.425" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession</text>
<polyline fill="none" stroke="#000000" points="2055.925,-138.5 2200.925,-138.5 "/>
<text text-anchor="middle" x="2128.425" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="2055.925,-115.5 2200.925,-115.5 "/>
<text text-anchor="middle" x="2128.425" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2055.925,-92.5 2200.925,-92.5 "/>
<text text-anchor="middle" x="2128.425" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="2055.925,-69.5 2200.925,-69.5 "/>
<text text-anchor="middle" x="2128.425" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="2055.925,-46.5 2200.925,-46.5 "/>
<text text-anchor="middle" x="2128.425" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="2055.925,-23.5 2200.925,-23.5 "/>
<text text-anchor="middle" x="2128.425" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
<polyline fill="none" stroke="#000000" points="2200.925,-.5 2200.925,-161.5 "/>
<text text-anchor="middle" x="2211.425" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment -->
<g id="node2" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M915.425,-639.5C915.425,-639.5 1207.425,-639.5 1207.425,-639.5 1213.425,-639.5 1219.425,-645.5 1219.425,-651.5 1219.425,-651.5 1219.425,-857.5 1219.425,-857.5 1219.425,-863.5 1213.425,-869.5 1207.425,-869.5 1207.425,-869.5 915.425,-869.5 915.425,-869.5 909.425,-869.5 903.425,-863.5 903.425,-857.5 903.425,-857.5 903.425,-651.5 903.425,-651.5 903.425,-645.5 909.425,-639.5 915.425,-639.5"/>
<text text-anchor="middle" x="947.925" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="992.425,-639.5 992.425,-869.5 "/>
<text text-anchor="middle" x="1002.925" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1013.425,-639.5 1013.425,-869.5 "/>
<text text-anchor="middle" x="1105.925" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="1013.425,-846.5 1198.425,-846.5 "/>
<text text-anchor="middle" x="1105.925" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1013.425,-823.5 1198.425,-823.5 "/>
<text text-anchor="middle" x="1105.925" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose</text>
<polyline fill="none" stroke="#000000" points="1013.425,-800.5 1198.425,-800.5 "/>
<text text-anchor="middle" x="1105.925" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_frequency</text>
<polyline fill="none" stroke="#000000" points="1013.425,-777.5 1198.425,-777.5 "/>
<text text-anchor="middle" x="1105.925" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_route</text>
<polyline fill="none" stroke="#000000" points="1013.425,-754.5 1198.425,-754.5 "/>
<text text-anchor="middle" x="1105.925" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_unit</text>
<polyline fill="none" stroke="#000000" points="1013.425,-731.5 1198.425,-731.5 "/>
<text text-anchor="middle" x="1105.925" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1013.425,-708.5 1198.425,-708.5 "/>
<text text-anchor="middle" x="1105.925" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="1013.425,-685.5 1198.425,-685.5 "/>
<text text-anchor="middle" x="1105.925" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1013.425,-662.5 1198.425,-662.5 "/>
<text text-anchor="middle" x="1105.925" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1198.425,-639.5 1198.425,-869.5 "/>
<text text-anchor="middle" x="1208.925" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node6" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1314.925,-495.5C1314.925,-495.5 1545.925,-495.5 1545.925,-495.5 1551.925,-495.5 1557.925,-501.5 1557.925,-507.5 1557.925,-507.5 1557.925,-575.5 1557.925,-575.5 1557.925,-581.5 1551.925,-587.5 1545.925,-587.5 1545.925,-587.5 1314.925,-587.5 1314.925,-587.5 1308.925,-587.5 1302.925,-581.5 1302.925,-575.5 1302.925,-575.5 1302.925,-507.5 1302.925,-507.5 1302.925,-501.5 1308.925,-495.5 1314.925,-495.5"/>
<text text-anchor="middle" x="1350.925" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1398.925,-495.5 1398.925,-587.5 "/>
<text text-anchor="middle" x="1409.425" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1419.925,-495.5 1419.925,-587.5 "/>
<text text-anchor="middle" x="1478.425" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1419.925,-564.5 1536.925,-564.5 "/>
<text text-anchor="middle" x="1478.425" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1419.925,-541.5 1536.925,-541.5 "/>
<text text-anchor="middle" x="1478.425" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1419.925,-518.5 1536.925,-518.5 "/>
<text text-anchor="middle" x="1478.425" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="1536.925,-495.5 1536.925,-587.5 "/>
<text text-anchor="middle" x="1547.425" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1219.7028,-644.1533C1222.622,-642.4048 1225.5311,-640.6854 1228.425,-639 1256.7855,-622.4826 1288.3665,-606.2732 1317.9736,-591.9593"/>
<polygon fill="#000000" stroke="#000000" points="1319.5938,-595.0639 1327.0928,-587.5796 1316.5633,-588.7539 1319.5938,-595.0639"/>
<text text-anchor="middle" x="1335.425" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- sample -->
<g id="node3" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M559.425,-651C559.425,-651 873.425,-651 873.425,-651 879.425,-651 885.425,-657 885.425,-663 885.425,-663 885.425,-846 885.425,-846 885.425,-852 879.425,-858 873.425,-858 873.425,-858 559.425,-858 559.425,-858 553.425,-858 547.425,-852 547.425,-846 547.425,-846 547.425,-663 547.425,-663 547.425,-657 553.425,-651 559.425,-651"/>
<text text-anchor="middle" x="581.425" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="615.425,-651 615.425,-858 "/>
<text text-anchor="middle" x="625.925" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="636.425,-651 636.425,-858 "/>
<text text-anchor="middle" x="750.425" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="636.425,-835 864.425,-835 "/>
<text text-anchor="middle" x="750.425" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="636.425,-812 864.425,-812 "/>
<text text-anchor="middle" x="750.425" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="636.425,-789 864.425,-789 "/>
<text text-anchor="middle" x="750.425" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_necrosis</text>
<polyline fill="none" stroke="#000000" points="636.425,-766 864.425,-766 "/>
<text text-anchor="middle" x="750.425" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_tumor</text>
<polyline fill="none" stroke="#000000" points="636.425,-743 864.425,-743 "/>
<text text-anchor="middle" x="750.425" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="636.425,-720 864.425,-720 "/>
<text text-anchor="middle" x="750.425" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="636.425,-697 864.425,-697 "/>
<text text-anchor="middle" x="750.425" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="636.425,-674 864.425,-674 "/>
<text text-anchor="middle" x="750.425" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="864.425,-651 864.425,-858 "/>
<text text-anchor="middle" x="874.925" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M867.7313,-650.8869C876.5919,-646.5393 885.5223,-642.5327 894.425,-639 1023.902,-587.6212 1181.8033,-563.0892 1292.5706,-551.519"/>
<polygon fill="#000000" stroke="#000000" points="1293.2122,-554.9717 1302.8044,-550.4729 1292.5003,-548.008 1293.2122,-554.9717"/>
<text text-anchor="middle" x="1029.925" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- genetic_analysis -->
<g id="node4" class="node">
<title>genetic_analysis</title>
<path fill="none" stroke="#000000" d="M1557.425,-921.5C1557.425,-921.5 1941.425,-921.5 1941.425,-921.5 1947.425,-921.5 1953.425,-927.5 1953.425,-933.5 1953.425,-933.5 1953.425,-1507.5 1953.425,-1507.5 1953.425,-1513.5 1947.425,-1519.5 1941.425,-1519.5 1941.425,-1519.5 1557.425,-1519.5 1557.425,-1519.5 1551.425,-1519.5 1545.425,-1513.5 1545.425,-1507.5 1545.425,-1507.5 1545.425,-933.5 1545.425,-933.5 1545.425,-927.5 1551.425,-921.5 1557.425,-921.5"/>
<text text-anchor="middle" x="1612.925" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="1680.425,-921.5 1680.425,-1519.5 "/>
<text text-anchor="middle" x="1690.925" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1701.425,-921.5 1701.425,-1519.5 "/>
<text text-anchor="middle" x="1816.925" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="1701.425,-1496.5 1932.425,-1496.5 "/>
<text text-anchor="middle" x="1816.925" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">allelic_ratio</text>
<polyline fill="none" stroke="#000000" points="1701.425,-1473.5 1932.425,-1473.5 "/>
<text text-anchor="middle" x="1816.925" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration</text>
<polyline fill="none" stroke="#000000" points="1701.425,-1450.5 1932.425,-1450.5 "/>
<text text-anchor="middle" x="1816.925" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="1701.425,-1427.5 1932.425,-1427.5 "/>
<text text-anchor="middle" x="1816.925" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome_location</text>
<polyline fill="none" stroke="#000000" points="1701.425,-1404.5 1932.425,-1404.5 "/>
<text text-anchor="middle" x="1816.925" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="1701.425,-1381.5 1932.425,-1381.5 "/>
<text text-anchor="middle" x="1816.925" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">dna_index_numeric</text>
<polyline fill="none" stroke="#000000" points="1701.425,-1358.5 1932.425,-1358.5 "/>
<text text-anchor="middle" x="1816.925" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="1701.425,-1335.5 1932.425,-1335.5 "/>
<text text-anchor="middle" x="1816.925" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_exon</text>
<polyline fill="none" stroke="#000000" points="1701.425,-1312.5 1932.425,-1312.5 "/>
<text text-anchor="middle" x="1816.925" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_gene</text>
<polyline fill="none" stroke="#000000" points="1701.425,-1289.5 1932.425,-1289.5 "/>
<text text-anchor="middle" x="1816.925" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_transcript</text>
<polyline fill="none" stroke="#000000" points="1701.425,-1266.5 1932.425,-1266.5 "/>
<text text-anchor="middle" x="1816.925" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="1701.425,-1243.5 1932.425,-1243.5 "/>
<text text-anchor="middle" x="1816.925" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis_id</text>
<polyline fill="none" stroke="#000000" points="1701.425,-1220.5 1932.425,-1220.5 "/>
<text text-anchor="middle" x="1816.925" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_source_category</text>
<polyline fill="none" stroke="#000000" points="1701.425,-1197.5 1932.425,-1197.5 "/>
<text text-anchor="middle" x="1816.925" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_coding</text>
<polyline fill="none" stroke="#000000" points="1701.425,-1174.5 1932.425,-1174.5 "/>
<text text-anchor="middle" x="1816.925" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_genome</text>
<polyline fill="none" stroke="#000000" points="1701.425,-1151.5 1932.425,-1151.5 "/>
<text text-anchor="middle" x="1816.925" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_protein</text>
<polyline fill="none" stroke="#000000" points="1701.425,-1128.5 1932.425,-1128.5 "/>
<text text-anchor="middle" x="1816.925" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1701.425,-1105.5 1932.425,-1105.5 "/>
<text text-anchor="middle" x="1816.925" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">karyotype</text>
<polyline fill="none" stroke="#000000" points="1701.425,-1082.5 1932.425,-1082.5 "/>
<text text-anchor="middle" x="1816.925" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome</text>
<polyline fill="none" stroke="#000000" points="1701.425,-1059.5 1932.425,-1059.5 "/>
<text text-anchor="middle" x="1816.925" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance</text>
<polyline fill="none" stroke="#000000" points="1701.425,-1036.5 1932.425,-1036.5 "/>
<text text-anchor="middle" x="1816.925" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance_system</text>
<polyline fill="none" stroke="#000000" points="1701.425,-1013.5 1932.425,-1013.5 "/>
<text text-anchor="middle" x="1816.925" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">result</text>
<polyline fill="none" stroke="#000000" points="1701.425,-990.5 1932.425,-990.5 "/>
<text text-anchor="middle" x="1816.925" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="1701.425,-967.5 1932.425,-967.5 "/>
<text text-anchor="middle" x="1816.925" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">test</text>
<polyline fill="none" stroke="#000000" points="1701.425,-944.5 1932.425,-944.5 "/>
<text text-anchor="middle" x="1816.925" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 2 properties</text>
<polyline fill="none" stroke="#000000" points="1932.425,-921.5 1932.425,-1519.5 "/>
<text text-anchor="middle" x="1942.925" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1545.0967,-1098.6214C1434.529,-1037.3501 1293.6462,-966.6201 1160.425,-921 1046.5416,-882.0019 1006.1011,-914.9299 894.425,-870 888.5936,-867.6539 882.7489,-865.1075 876.9185,-862.3979"/>
<polygon fill="#000000" stroke="#000000" points="878.3023,-859.1799 867.7721,-858.0108 875.275,-865.4914 878.3023,-859.1799"/>
<text text-anchor="middle" x="1154.425" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1808.3684,-921.4347C1824.4528,-803.0923 1829.1511,-684.4652 1794.425,-639 1766.4552,-602.3805 1659.0517,-576.5398 1568.1023,-560.7035"/>
<polygon fill="#000000" stroke="#000000" points="1568.678,-557.2512 1558.2306,-559.0122 1567.4959,-564.1507 1568.678,-557.2512"/>
<text text-anchor="middle" x="1891.425" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- diagnosis -->
<g id="node5" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M267.925,-1013.5C267.925,-1013.5 632.925,-1013.5 632.925,-1013.5 638.925,-1013.5 644.925,-1019.5 644.925,-1025.5 644.925,-1025.5 644.925,-1415.5 644.925,-1415.5 644.925,-1421.5 638.925,-1427.5 632.925,-1427.5 632.925,-1427.5 267.925,-1427.5 267.925,-1427.5 261.925,-1427.5 255.925,-1421.5 255.925,-1415.5 255.925,-1415.5 255.925,-1025.5 255.925,-1025.5 255.925,-1019.5 261.925,-1013.5 267.925,-1013.5"/>
<text text-anchor="middle" x="297.925" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="339.925,-1013.5 339.925,-1427.5 "/>
<text text-anchor="middle" x="350.425" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="360.925,-1013.5 360.925,-1427.5 "/>
<text text-anchor="middle" x="492.425" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="360.925,-1404.5 623.925,-1404.5 "/>
<text text-anchor="middle" x="492.425" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="360.925,-1381.5 623.925,-1381.5 "/>
<text text-anchor="middle" x="492.425" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="360.925,-1358.5 623.925,-1358.5 "/>
<text text-anchor="middle" x="492.425" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="360.925,-1335.5 623.925,-1335.5 "/>
<text text-anchor="middle" x="492.425" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_category</text>
<polyline fill="none" stroke="#000000" points="360.925,-1312.5 623.925,-1312.5 "/>
<text text-anchor="middle" x="492.425" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="360.925,-1289.5 623.925,-1289.5 "/>
<text text-anchor="middle" x="492.425" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="360.925,-1266.5 623.925,-1266.5 "/>
<text text-anchor="middle" x="492.425" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="360.925,-1243.5 623.925,-1243.5 "/>
<text text-anchor="middle" x="492.425" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="360.925,-1220.5 623.925,-1220.5 "/>
<text text-anchor="middle" x="492.425" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="360.925,-1197.5 623.925,-1197.5 "/>
<text text-anchor="middle" x="492.425" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">laterality</text>
<polyline fill="none" stroke="#000000" points="360.925,-1174.5 623.925,-1174.5 "/>
<text text-anchor="middle" x="492.425" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="360.925,-1151.5 623.925,-1151.5 "/>
<text text-anchor="middle" x="492.425" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="360.925,-1128.5 623.925,-1128.5 "/>
<text text-anchor="middle" x="492.425" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="360.925,-1105.5 623.925,-1105.5 "/>
<text text-anchor="middle" x="492.425" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="360.925,-1082.5 623.925,-1082.5 "/>
<text text-anchor="middle" x="492.425" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="360.925,-1059.5 623.925,-1059.5 "/>
<text text-anchor="middle" x="492.425" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="360.925,-1036.5 623.925,-1036.5 "/>
<text text-anchor="middle" x="492.425" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="623.925,-1013.5 623.925,-1427.5 "/>
<text text-anchor="middle" x="634.425" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M568.6455,-1013.3918C597.3936,-963.0286 627.0743,-911.0316 652.2253,-866.9701"/>
<polygon fill="#000000" stroke="#000000" points="655.2757,-868.6862 657.1935,-858.2664 649.1964,-865.216 655.2757,-868.6862"/>
<text text-anchor="middle" x="682.925" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M255.7121,-1089.6717C95.3124,-966.3978 -86.0623,-780.069 45.425,-639 87.5508,-593.8044 950.7728,-558.4571 1292.6955,-546.1779"/>
<polygon fill="#000000" stroke="#000000" points="1293.0373,-549.668 1302.9057,-545.8125 1292.7869,-542.6724 1293.0373,-549.668"/>
<text text-anchor="middle" x="89.925" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- consent_group -->
<g id="node8" class="node">
<title>consent_group</title>
<path fill="none" stroke="#000000" d="M1582.925,-271C1582.925,-271 1907.925,-271 1907.925,-271 1913.925,-271 1919.925,-277 1919.925,-283 1919.925,-283 1919.925,-374 1919.925,-374 1919.925,-380 1913.925,-386 1907.925,-386 1907.925,-386 1582.925,-386 1582.925,-386 1576.925,-386 1570.925,-380 1570.925,-374 1570.925,-374 1570.925,-283 1570.925,-283 1570.925,-277 1576.925,-271 1582.925,-271"/>
<text text-anchor="middle" x="1631.925" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
<polyline fill="none" stroke="#000000" points="1692.925,-271 1692.925,-386 "/>
<text text-anchor="middle" x="1703.425" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1713.925,-271 1713.925,-386 "/>
<text text-anchor="middle" x="1806.425" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_id</text>
<polyline fill="none" stroke="#000000" points="1713.925,-363 1898.925,-363 "/>
<text text-anchor="middle" x="1806.425" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_name</text>
<polyline fill="none" stroke="#000000" points="1713.925,-340 1898.925,-340 "/>
<text text-anchor="middle" x="1806.425" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_number</text>
<polyline fill="none" stroke="#000000" points="1713.925,-317 1898.925,-317 "/>
<text text-anchor="middle" x="1806.425" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_suffix</text>
<polyline fill="none" stroke="#000000" points="1713.925,-294 1898.925,-294 "/>
<text text-anchor="middle" x="1806.425" y="-278.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1898.925,-271 1898.925,-386 "/>
<text text-anchor="middle" x="1909.425" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge10" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1498.7753,-495.2822C1543.5903,-464.9786 1602.764,-424.966 1651.918,-391.7285"/>
<polygon fill="#000000" stroke="#000000" points="1654.0202,-394.5321 1660.3436,-386.0312 1650.0991,-388.7334 1654.0202,-394.5321"/>
<text text-anchor="middle" x="1591.925" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- treatment_response -->
<g id="node7" class="node">
<title>treatment_response</title>
<path fill="none" stroke="#000000" d="M155.925,-685.5C155.925,-685.5 516.925,-685.5 516.925,-685.5 522.925,-685.5 528.925,-691.5 528.925,-697.5 528.925,-697.5 528.925,-811.5 528.925,-811.5 528.925,-817.5 522.925,-823.5 516.925,-823.5 516.925,-823.5 155.925,-823.5 155.925,-823.5 149.925,-823.5 143.925,-817.5 143.925,-811.5 143.925,-811.5 143.925,-697.5 143.925,-697.5 143.925,-691.5 149.925,-685.5 155.925,-685.5"/>
<text text-anchor="middle" x="224.425" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
<polyline fill="none" stroke="#000000" points="304.925,-685.5 304.925,-823.5 "/>
<text text-anchor="middle" x="315.425" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="325.925,-685.5 325.925,-823.5 "/>
<text text-anchor="middle" x="416.925" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_response</text>
<polyline fill="none" stroke="#000000" points="325.925,-800.5 507.925,-800.5 "/>
<text text-anchor="middle" x="416.925" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="325.925,-777.5 507.925,-777.5 "/>
<text text-anchor="middle" x="416.925" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="325.925,-754.5 507.925,-754.5 "/>
<text text-anchor="middle" x="416.925" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_category</text>
<polyline fill="none" stroke="#000000" points="325.925,-731.5 507.925,-731.5 "/>
<text text-anchor="middle" x="416.925" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_system</text>
<polyline fill="none" stroke="#000000" points="325.925,-708.5 507.925,-708.5 "/>
<text text-anchor="middle" x="416.925" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response_id</text>
<polyline fill="none" stroke="#000000" points="507.925,-685.5 507.925,-823.5 "/>
<text text-anchor="middle" x="518.425" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M439.4773,-685.4849C470.1809,-667.7537 504.6687,-650.467 538.425,-639 674.5502,-592.7582 1078.0585,-562.5136 1292.6362,-549.2359"/>
<polygon fill="#000000" stroke="#000000" points="1292.9433,-552.7237 1302.7096,-548.6165 1292.5136,-545.7369 1292.9433,-552.7237"/>
<text text-anchor="middle" x="766.425" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge15" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1828.2086,-270.7846C1872.2703,-240.0656 1927.3443,-201.6689 1976.4055,-167.4643"/>
<polygon fill="#000000" stroke="#000000" points="1978.6551,-170.1625 1984.8566,-161.5723 1974.6517,-164.4203 1978.6551,-170.1625"/>
<text text-anchor="middle" x="2018.925" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- laboratory_test -->
<g id="node9" class="node">
<title>laboratory_test</title>
<path fill="none" stroke="#000000" d="M822.925,-1140C822.925,-1140 1139.925,-1140 1139.925,-1140 1145.925,-1140 1151.925,-1146 1151.925,-1152 1151.925,-1152 1151.925,-1289 1151.925,-1289 1151.925,-1295 1145.925,-1301 1139.925,-1301 1139.925,-1301 822.925,-1301 822.925,-1301 816.925,-1301 810.925,-1295 810.925,-1289 810.925,-1289 810.925,-1152 810.925,-1152 810.925,-1146 816.925,-1140 822.925,-1140"/>
<text text-anchor="middle" x="873.925" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="936.925,-1140 936.925,-1301 "/>
<text text-anchor="middle" x="947.425" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="957.925,-1140 957.925,-1301 "/>
<text text-anchor="middle" x="1044.425" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_method</text>
<polyline fill="none" stroke="#000000" points="957.925,-1278 1130.925,-1278 "/>
<text text-anchor="middle" x="1044.425" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="957.925,-1255 1130.925,-1255 "/>
<text text-anchor="middle" x="1044.425" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_id</text>
<polyline fill="none" stroke="#000000" points="957.925,-1232 1130.925,-1232 "/>
<text text-anchor="middle" x="1044.425" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_name</text>
<polyline fill="none" stroke="#000000" points="957.925,-1209 1130.925,-1209 "/>
<text text-anchor="middle" x="1044.425" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_numeric</text>
<polyline fill="none" stroke="#000000" points="957.925,-1186 1130.925,-1186 "/>
<text text-anchor="middle" x="1044.425" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_text</text>
<polyline fill="none" stroke="#000000" points="957.925,-1163 1130.925,-1163 "/>
<text text-anchor="middle" x="1044.425" y="-1147.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_unit</text>
<polyline fill="none" stroke="#000000" points="1130.925,-1140 1130.925,-1301 "/>
<text text-anchor="middle" x="1141.425" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M935.568,-1139.861C892.7173,-1064.5084 828.3372,-951.2967 780.432,-867.0559"/>
<polygon fill="#000000" stroke="#000000" points="783.3954,-865.1866 775.4096,-858.224 777.3105,-868.6469 783.3954,-865.1866"/>
<text text-anchor="middle" x="860.925" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1130.6633,-1139.8519C1242.3626,-1079.5172 1398.9195,-995.011 1536.425,-921 1578.6226,-898.2876 1606.8255,-911.1261 1631.425,-870 1657.7757,-825.946 1658.6742,-682.5039 1631.425,-639 1616.0931,-614.5225 1592.6723,-596.0353 1567.1662,-582.1246"/>
<polygon fill="#000000" stroke="#000000" points="1568.5541,-578.9014 1558.0672,-577.3927 1565.3244,-585.1118 1568.5541,-578.9014"/>
<text text-anchor="middle" x="1717.925" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- synonym -->
<g id="node10" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M1996.925,-674C1996.925,-674 2297.925,-674 2297.925,-674 2303.925,-674 2309.925,-680 2309.925,-686 2309.925,-686 2309.925,-823 2309.925,-823 2309.925,-829 2303.925,-835 2297.925,-835 2297.925,-835 1996.925,-835 1996.925,-835 1990.925,-835 1984.925,-829 1984.925,-823 1984.925,-823 1984.925,-686 1984.925,-686 1984.925,-680 1990.925,-674 1996.925,-674"/>
<text text-anchor="middle" x="2024.925" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="2064.925,-674 2064.925,-835 "/>
<text text-anchor="middle" x="2075.425" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2085.925,-674 2085.925,-835 "/>
<text text-anchor="middle" x="2187.425" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_id</text>
<polyline fill="none" stroke="#000000" points="2085.925,-812 2288.925,-812 "/>
<text text-anchor="middle" x="2187.425" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">data_location</text>
<polyline fill="none" stroke="#000000" points="2085.925,-789 2288.925,-789 "/>
<text text-anchor="middle" x="2187.425" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">domain_category</text>
<polyline fill="none" stroke="#000000" points="2085.925,-766 2288.925,-766 "/>
<text text-anchor="middle" x="2187.425" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">domain_description</text>
<polyline fill="none" stroke="#000000" points="2085.925,-743 2288.925,-743 "/>
<text text-anchor="middle" x="2187.425" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2085.925,-720 2288.925,-720 "/>
<text text-anchor="middle" x="2187.425" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="2085.925,-697 2288.925,-697 "/>
<text text-anchor="middle" x="2187.425" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="2288.925,-674 2288.925,-835 "/>
<text text-anchor="middle" x="2299.425" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge2" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2139.7028,-673.8131C2133.8789,-611.1736 2125.9726,-522.127 2120.425,-444 2113.8496,-351.4003 2108.2279,-245.3803 2104.6346,-171.9277"/>
<polygon fill="#000000" stroke="#000000" points="2108.123,-171.6023 2104.1411,-161.7842 2101.1313,-171.9425 2108.123,-171.6023"/>
<text text-anchor="middle" x="2164.925" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2035.8199,-673.8525C2014.7683,-660.9297 1992.4344,-648.6545 1970.425,-639 1899.9951,-608.1057 1703.6023,-577.3976 1568.1524,-558.9301"/>
<polygon fill="#000000" stroke="#000000" points="1568.4806,-555.4427 1558.1009,-557.5668 1567.5398,-562.3792 1568.4806,-555.4427"/>
<text text-anchor="middle" x="1949.925" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- survival -->
<g id="node11" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M1249.925,-662.5C1249.925,-662.5 1610.925,-662.5 1610.925,-662.5 1616.925,-662.5 1622.925,-668.5 1622.925,-674.5 1622.925,-674.5 1622.925,-834.5 1622.925,-834.5 1622.925,-840.5 1616.925,-846.5 1610.925,-846.5 1610.925,-846.5 1249.925,-846.5 1249.925,-846.5 1243.925,-846.5 1237.925,-840.5 1237.925,-834.5 1237.925,-834.5 1237.925,-674.5 1237.925,-674.5 1237.925,-668.5 1243.925,-662.5 1249.925,-662.5"/>
<text text-anchor="middle" x="1274.925" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="1311.925,-662.5 1311.925,-846.5 "/>
<text text-anchor="middle" x="1322.425" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1332.925,-662.5 1332.925,-846.5 "/>
<text text-anchor="middle" x="1467.425" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="1332.925,-823.5 1601.925,-823.5 "/>
<text text-anchor="middle" x="1467.425" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="1332.925,-800.5 1601.925,-800.5 "/>
<text text-anchor="middle" x="1467.425" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="1332.925,-777.5 1601.925,-777.5 "/>
<text text-anchor="middle" x="1467.425" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="1332.925,-754.5 1601.925,-754.5 "/>
<text text-anchor="middle" x="1467.425" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="1332.925,-731.5 1601.925,-731.5 "/>
<text text-anchor="middle" x="1467.425" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1332.925,-708.5 1601.925,-708.5 "/>
<text text-anchor="middle" x="1467.425" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="1332.925,-685.5 1601.925,-685.5 "/>
<text text-anchor="middle" x="1467.425" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="1601.925,-662.5 1601.925,-846.5 "/>
<text text-anchor="middle" x="1612.425" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1430.425,-662.3139C1430.425,-640.2929 1430.425,-617.4402 1430.425,-597.6147"/>
<polygon fill="#000000" stroke="#000000" points="1433.9251,-597.5436 1430.425,-587.5436 1426.9251,-597.5437 1433.9251,-597.5436"/>
<text text-anchor="middle" x="1469.925" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- reference_file -->
<g id="node12" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M2140.925,-213.5C2140.925,-213.5 2417.925,-213.5 2417.925,-213.5 2423.925,-213.5 2429.925,-219.5 2429.925,-225.5 2429.925,-225.5 2429.925,-431.5 2429.925,-431.5 2429.925,-437.5 2423.925,-443.5 2417.925,-443.5 2417.925,-443.5 2140.925,-443.5 2140.925,-443.5 2134.925,-443.5 2128.925,-437.5 2128.925,-431.5 2128.925,-431.5 2128.925,-225.5 2128.925,-225.5 2128.925,-219.5 2134.925,-213.5 2140.925,-213.5"/>
<text text-anchor="middle" x="2186.925" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="2244.925,-213.5 2244.925,-443.5 "/>
<text text-anchor="middle" x="2255.425" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2265.925,-213.5 2265.925,-443.5 "/>
<text text-anchor="middle" x="2337.425" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="2265.925,-420.5 2408.925,-420.5 "/>
<text text-anchor="middle" x="2337.425" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="2265.925,-397.5 2408.925,-397.5 "/>
<text text-anchor="middle" x="2337.425" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2265.925,-374.5 2408.925,-374.5 "/>
<text text-anchor="middle" x="2337.425" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2265.925,-351.5 2408.925,-351.5 "/>
<text text-anchor="middle" x="2337.425" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2265.925,-328.5 2408.925,-328.5 "/>
<text text-anchor="middle" x="2337.425" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2265.925,-305.5 2408.925,-305.5 "/>
<text text-anchor="middle" x="2337.425" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2265.925,-282.5 2408.925,-282.5 "/>
<text text-anchor="middle" x="2337.425" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2265.925,-259.5 2408.925,-259.5 "/>
<text text-anchor="middle" x="2337.425" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="2265.925,-236.5 2408.925,-236.5 "/>
<text text-anchor="middle" x="2337.425" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="2408.925,-213.5 2408.925,-443.5 "/>
<text text-anchor="middle" x="2419.425" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge5" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2196.2133,-213.4448C2185.6049,-198.7767 2174.878,-183.9449 2164.6329,-169.7792"/>
<polygon fill="#000000" stroke="#000000" points="2167.3573,-167.5736 2158.6609,-161.5218 2161.6852,-171.6759 2167.3573,-167.5736"/>
<text text-anchor="middle" x="2238.925" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
</g>
</svg>
</div>
