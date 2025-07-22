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
<svg width="2536pt" height="1528pt"
 viewBox="0.00 0.00 2536.00 1528.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1524)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1524 2532,-1524 2532,4 -4,4"/>
<!-- sample -->
<g id="node1" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1772.5,-651C1772.5,-651 2086.5,-651 2086.5,-651 2092.5,-651 2098.5,-657 2098.5,-663 2098.5,-663 2098.5,-846 2098.5,-846 2098.5,-852 2092.5,-858 2086.5,-858 2086.5,-858 1772.5,-858 1772.5,-858 1766.5,-858 1760.5,-852 1760.5,-846 1760.5,-846 1760.5,-663 1760.5,-663 1760.5,-657 1766.5,-651 1772.5,-651"/>
<text text-anchor="middle" x="1794.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1828.5,-651 1828.5,-858 "/>
<text text-anchor="middle" x="1839" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1849.5,-651 1849.5,-858 "/>
<text text-anchor="middle" x="1963.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1849.5,-835 2077.5,-835 "/>
<text text-anchor="middle" x="1963.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1849.5,-812 2077.5,-812 "/>
<text text-anchor="middle" x="1963.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1849.5,-789 2077.5,-789 "/>
<text text-anchor="middle" x="1963.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_necrosis</text>
<polyline fill="none" stroke="#000000" points="1849.5,-766 2077.5,-766 "/>
<text text-anchor="middle" x="1963.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_tumor</text>
<polyline fill="none" stroke="#000000" points="1849.5,-743 2077.5,-743 "/>
<text text-anchor="middle" x="1963.5" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1849.5,-720 2077.5,-720 "/>
<text text-anchor="middle" x="1963.5" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1849.5,-697 2077.5,-697 "/>
<text text-anchor="middle" x="1963.5" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1849.5,-674 2077.5,-674 "/>
<text text-anchor="middle" x="1963.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="2077.5,-651 2077.5,-858 "/>
<text text-anchor="middle" x="2088" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node8" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1065,-495.5C1065,-495.5 1296,-495.5 1296,-495.5 1302,-495.5 1308,-501.5 1308,-507.5 1308,-507.5 1308,-575.5 1308,-575.5 1308,-581.5 1302,-587.5 1296,-587.5 1296,-587.5 1065,-587.5 1065,-587.5 1059,-587.5 1053,-581.5 1053,-575.5 1053,-575.5 1053,-507.5 1053,-507.5 1053,-501.5 1059,-495.5 1065,-495.5"/>
<text text-anchor="middle" x="1101" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1149,-495.5 1149,-587.5 "/>
<text text-anchor="middle" x="1159.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1170,-495.5 1170,-587.5 "/>
<text text-anchor="middle" x="1228.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1170,-564.5 1287,-564.5 "/>
<text text-anchor="middle" x="1228.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1170,-541.5 1287,-541.5 "/>
<text text-anchor="middle" x="1228.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1170,-518.5 1287,-518.5 "/>
<text text-anchor="middle" x="1228.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="1287,-495.5 1287,-587.5 "/>
<text text-anchor="middle" x="1297.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1778.4955,-650.8949C1769.5392,-646.529 1760.5074,-642.5181 1751.5,-639 1609.9602,-583.7184 1436.5865,-559.7283 1318.2635,-549.3499"/>
<polygon fill="#000000" stroke="#000000" points="1318.3222,-545.8422 1308.0601,-548.4767 1317.7252,-552.8167 1318.3222,-545.8422"/>
<text text-anchor="middle" x="1728" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- reference_file -->
<g id="node2" class="node">
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
<g id="node12" class="node">
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
<g id="edge14" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M176.2184,-213.4651C181.2736,-201.6374 187.3059,-190.2265 194.5,-180 197.1103,-176.2894 199.9042,-172.6633 202.8495,-169.1251"/>
<polygon fill="#000000" stroke="#000000" points="205.5584,-171.3446 209.527,-161.5211 200.2986,-166.7256 205.5584,-171.3446"/>
<text text-anchor="middle" x="255" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- genetic_analysis -->
<g id="node3" class="node">
<title>genetic_analysis</title>
<path fill="none" stroke="#000000" d="M1724.5,-921.5C1724.5,-921.5 2108.5,-921.5 2108.5,-921.5 2114.5,-921.5 2120.5,-927.5 2120.5,-933.5 2120.5,-933.5 2120.5,-1507.5 2120.5,-1507.5 2120.5,-1513.5 2114.5,-1519.5 2108.5,-1519.5 2108.5,-1519.5 1724.5,-1519.5 1724.5,-1519.5 1718.5,-1519.5 1712.5,-1513.5 1712.5,-1507.5 1712.5,-1507.5 1712.5,-933.5 1712.5,-933.5 1712.5,-927.5 1718.5,-921.5 1724.5,-921.5"/>
<text text-anchor="middle" x="1780" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="1847.5,-921.5 1847.5,-1519.5 "/>
<text text-anchor="middle" x="1858" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1868.5,-921.5 1868.5,-1519.5 "/>
<text text-anchor="middle" x="1984" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="1868.5,-1496.5 2099.5,-1496.5 "/>
<text text-anchor="middle" x="1984" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">allelic_ratio</text>
<polyline fill="none" stroke="#000000" points="1868.5,-1473.5 2099.5,-1473.5 "/>
<text text-anchor="middle" x="1984" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration</text>
<polyline fill="none" stroke="#000000" points="1868.5,-1450.5 2099.5,-1450.5 "/>
<text text-anchor="middle" x="1984" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="1868.5,-1427.5 2099.5,-1427.5 "/>
<text text-anchor="middle" x="1984" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome_location</text>
<polyline fill="none" stroke="#000000" points="1868.5,-1404.5 2099.5,-1404.5 "/>
<text text-anchor="middle" x="1984" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="1868.5,-1381.5 2099.5,-1381.5 "/>
<text text-anchor="middle" x="1984" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">dna_index_numeric</text>
<polyline fill="none" stroke="#000000" points="1868.5,-1358.5 2099.5,-1358.5 "/>
<text text-anchor="middle" x="1984" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="1868.5,-1335.5 2099.5,-1335.5 "/>
<text text-anchor="middle" x="1984" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_exon</text>
<polyline fill="none" stroke="#000000" points="1868.5,-1312.5 2099.5,-1312.5 "/>
<text text-anchor="middle" x="1984" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_gene</text>
<polyline fill="none" stroke="#000000" points="1868.5,-1289.5 2099.5,-1289.5 "/>
<text text-anchor="middle" x="1984" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_transcript</text>
<polyline fill="none" stroke="#000000" points="1868.5,-1266.5 2099.5,-1266.5 "/>
<text text-anchor="middle" x="1984" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="1868.5,-1243.5 2099.5,-1243.5 "/>
<text text-anchor="middle" x="1984" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis_id</text>
<polyline fill="none" stroke="#000000" points="1868.5,-1220.5 2099.5,-1220.5 "/>
<text text-anchor="middle" x="1984" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_source_category</text>
<polyline fill="none" stroke="#000000" points="1868.5,-1197.5 2099.5,-1197.5 "/>
<text text-anchor="middle" x="1984" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_coding</text>
<polyline fill="none" stroke="#000000" points="1868.5,-1174.5 2099.5,-1174.5 "/>
<text text-anchor="middle" x="1984" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_genome</text>
<polyline fill="none" stroke="#000000" points="1868.5,-1151.5 2099.5,-1151.5 "/>
<text text-anchor="middle" x="1984" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_protein</text>
<polyline fill="none" stroke="#000000" points="1868.5,-1128.5 2099.5,-1128.5 "/>
<text text-anchor="middle" x="1984" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1868.5,-1105.5 2099.5,-1105.5 "/>
<text text-anchor="middle" x="1984" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">karyotype</text>
<polyline fill="none" stroke="#000000" points="1868.5,-1082.5 2099.5,-1082.5 "/>
<text text-anchor="middle" x="1984" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome</text>
<polyline fill="none" stroke="#000000" points="1868.5,-1059.5 2099.5,-1059.5 "/>
<text text-anchor="middle" x="1984" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance</text>
<polyline fill="none" stroke="#000000" points="1868.5,-1036.5 2099.5,-1036.5 "/>
<text text-anchor="middle" x="1984" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance_system</text>
<polyline fill="none" stroke="#000000" points="1868.5,-1013.5 2099.5,-1013.5 "/>
<text text-anchor="middle" x="1984" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">result</text>
<polyline fill="none" stroke="#000000" points="1868.5,-990.5 2099.5,-990.5 "/>
<text text-anchor="middle" x="1984" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="1868.5,-967.5 2099.5,-967.5 "/>
<text text-anchor="middle" x="1984" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">test</text>
<polyline fill="none" stroke="#000000" points="1868.5,-944.5 2099.5,-944.5 "/>
<text text-anchor="middle" x="1984" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 2 properties</text>
<polyline fill="none" stroke="#000000" points="2099.5,-921.5 2099.5,-1519.5 "/>
<text text-anchor="middle" x="2110" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1924.8434,-921.4205C1925.3553,-903.0727 1925.8505,-885.3209 1926.3149,-868.6741"/>
<polygon fill="#000000" stroke="#000000" points="1929.8196,-868.5502 1926.5999,-858.4565 1922.8223,-868.355 1929.8196,-868.5502"/>
<text text-anchor="middle" x="1995.5" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2120.581,-927.2113C2164.692,-826.3632 2179.3996,-718.8585 2107.5,-639 2055.7032,-581.4696 1563.4374,-555.4699 1318.0993,-546.0069"/>
<polygon fill="#000000" stroke="#000000" points="1318.1676,-542.507 1308.0413,-545.6228 1317.9005,-549.5019 1318.1676,-542.507"/>
<text text-anchor="middle" x="2227.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- treatment_response -->
<g id="node4" class="node">
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
<g id="edge1" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M651.2586,-685.1968C657.6703,-656.5231 669.9811,-625.4854 693.5,-606 720.1298,-583.9372 908.497,-563.9405 1042.972,-552.2478"/>
<polygon fill="#000000" stroke="#000000" points="1043.301,-555.7325 1052.9631,-551.3857 1042.6992,-548.7584 1043.301,-555.7325"/>
<text text-anchor="middle" x="776.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- consent_group -->
<g id="node5" class="node">
<title>consent_group</title>
<path fill="none" stroke="#000000" d="M694,-271C694,-271 1019,-271 1019,-271 1025,-271 1031,-277 1031,-283 1031,-283 1031,-374 1031,-374 1031,-380 1025,-386 1019,-386 1019,-386 694,-386 694,-386 688,-386 682,-380 682,-374 682,-374 682,-283 682,-283 682,-277 688,-271 694,-271"/>
<text text-anchor="middle" x="743" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
<polyline fill="none" stroke="#000000" points="804,-271 804,-386 "/>
<text text-anchor="middle" x="814.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="825,-271 825,-386 "/>
<text text-anchor="middle" x="917.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_id</text>
<polyline fill="none" stroke="#000000" points="825,-363 1010,-363 "/>
<text text-anchor="middle" x="917.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_name</text>
<polyline fill="none" stroke="#000000" points="825,-340 1010,-340 "/>
<text text-anchor="middle" x="917.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_number</text>
<polyline fill="none" stroke="#000000" points="825,-317 1010,-317 "/>
<text text-anchor="middle" x="917.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_suffix</text>
<polyline fill="none" stroke="#000000" points="825,-294 1010,-294 "/>
<text text-anchor="middle" x="917.5" y="-278.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1010,-271 1010,-386 "/>
<text text-anchor="middle" x="1020.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge13" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M733.9391,-270.9406C652.0123,-232.4645 544.3285,-181.8919 460.6751,-142.605"/>
<polygon fill="#000000" stroke="#000000" points="461.9106,-139.3185 451.3712,-138.2355 458.9349,-145.6546 461.9106,-139.3185"/>
<text text-anchor="middle" x="625" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- synonym -->
<g id="node6" class="node">
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
<!-- synonym&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M377.9108,-673.8246C398.5682,-660.7465 420.6198,-648.4246 442.5,-639 547.4895,-593.7774 859.7946,-564.4964 1042.7539,-550.7198"/>
<polygon fill="#000000" stroke="#000000" points="1043.2783,-554.1904 1052.9897,-549.955 1042.7567,-547.2099 1043.2783,-554.1904"/>
<text text-anchor="middle" x="604" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M282.8594,-673.9136C291.3183,-611.3278 302.5591,-522.3045 309.5,-444 317.6966,-351.5297 323.0766,-245.4904 326.1708,-171.998"/>
<polygon fill="#000000" stroke="#000000" points="329.6742,-171.9854 326.5923,-161.8487 322.6803,-171.6948 329.6742,-171.9854"/>
<text text-anchor="middle" x="351" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- diagnosis -->
<g id="node7" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M2151,-1013.5C2151,-1013.5 2516,-1013.5 2516,-1013.5 2522,-1013.5 2528,-1019.5 2528,-1025.5 2528,-1025.5 2528,-1415.5 2528,-1415.5 2528,-1421.5 2522,-1427.5 2516,-1427.5 2516,-1427.5 2151,-1427.5 2151,-1427.5 2145,-1427.5 2139,-1421.5 2139,-1415.5 2139,-1415.5 2139,-1025.5 2139,-1025.5 2139,-1019.5 2145,-1013.5 2151,-1013.5"/>
<text text-anchor="middle" x="2181" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="2223,-1013.5 2223,-1427.5 "/>
<text text-anchor="middle" x="2233.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2244,-1013.5 2244,-1427.5 "/>
<text text-anchor="middle" x="2375.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2244,-1404.5 2507,-1404.5 "/>
<text text-anchor="middle" x="2375.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="2244,-1381.5 2507,-1381.5 "/>
<text text-anchor="middle" x="2375.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="2244,-1358.5 2507,-1358.5 "/>
<text text-anchor="middle" x="2375.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="2244,-1335.5 2507,-1335.5 "/>
<text text-anchor="middle" x="2375.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_category</text>
<polyline fill="none" stroke="#000000" points="2244,-1312.5 2507,-1312.5 "/>
<text text-anchor="middle" x="2375.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="2244,-1289.5 2507,-1289.5 "/>
<text text-anchor="middle" x="2375.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="2244,-1266.5 2507,-1266.5 "/>
<text text-anchor="middle" x="2375.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="2244,-1243.5 2507,-1243.5 "/>
<text text-anchor="middle" x="2375.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="2244,-1220.5 2507,-1220.5 "/>
<text text-anchor="middle" x="2375.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2244,-1197.5 2507,-1197.5 "/>
<text text-anchor="middle" x="2375.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">laterality</text>
<polyline fill="none" stroke="#000000" points="2244,-1174.5 2507,-1174.5 "/>
<text text-anchor="middle" x="2375.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="2244,-1151.5 2507,-1151.5 "/>
<text text-anchor="middle" x="2375.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="2244,-1128.5 2507,-1128.5 "/>
<text text-anchor="middle" x="2375.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="2244,-1105.5 2507,-1105.5 "/>
<text text-anchor="middle" x="2375.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="2244,-1082.5 2507,-1082.5 "/>
<text text-anchor="middle" x="2375.5" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="2244,-1059.5 2507,-1059.5 "/>
<text text-anchor="middle" x="2375.5" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2244,-1036.5 2507,-1036.5 "/>
<text text-anchor="middle" x="2375.5" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2507,-1013.5 2507,-1427.5 "/>
<text text-anchor="middle" x="2517.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2203.635,-1013.3644C2180.3857,-981.2873 2155.2989,-949.4109 2129.5,-921 2112.0617,-901.7962 2092.3854,-882.8313 2072.3521,-864.9642"/>
<polygon fill="#000000" stroke="#000000" points="2074.473,-862.1677 2064.6605,-858.1719 2069.8395,-867.4147 2074.473,-862.1677"/>
<text text-anchor="middle" x="2154" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2381.8176,-1013.1581C2397.6435,-889.2558 2392.112,-737.3317 2301.5,-639 2236.097,-568.025 1603.6511,-548.5274 1318.5994,-543.3257"/>
<polygon fill="#000000" stroke="#000000" points="1318.2535,-539.819 1308.1924,-543.1393 1318.1281,-546.8179 1318.2535,-539.819"/>
<text text-anchor="middle" x="2431" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge9" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1110.1968,-495.2822C1064.1013,-464.9786 1003.237,-424.966 952.6786,-391.7285"/>
<polygon fill="#000000" stroke="#000000" points="954.291,-388.6 944.0123,-386.0312 950.4457,-394.4492 954.291,-388.6"/>
<text text-anchor="middle" x="1127" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- treatment -->
<g id="node9" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M1034.5,-639.5C1034.5,-639.5 1326.5,-639.5 1326.5,-639.5 1332.5,-639.5 1338.5,-645.5 1338.5,-651.5 1338.5,-651.5 1338.5,-857.5 1338.5,-857.5 1338.5,-863.5 1332.5,-869.5 1326.5,-869.5 1326.5,-869.5 1034.5,-869.5 1034.5,-869.5 1028.5,-869.5 1022.5,-863.5 1022.5,-857.5 1022.5,-857.5 1022.5,-651.5 1022.5,-651.5 1022.5,-645.5 1028.5,-639.5 1034.5,-639.5"/>
<text text-anchor="middle" x="1067" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1111.5,-639.5 1111.5,-869.5 "/>
<text text-anchor="middle" x="1122" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1132.5,-639.5 1132.5,-869.5 "/>
<text text-anchor="middle" x="1225" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="1132.5,-846.5 1317.5,-846.5 "/>
<text text-anchor="middle" x="1225" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1132.5,-823.5 1317.5,-823.5 "/>
<text text-anchor="middle" x="1225" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose</text>
<polyline fill="none" stroke="#000000" points="1132.5,-800.5 1317.5,-800.5 "/>
<text text-anchor="middle" x="1225" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_frequency</text>
<polyline fill="none" stroke="#000000" points="1132.5,-777.5 1317.5,-777.5 "/>
<text text-anchor="middle" x="1225" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_route</text>
<polyline fill="none" stroke="#000000" points="1132.5,-754.5 1317.5,-754.5 "/>
<text text-anchor="middle" x="1225" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_unit</text>
<polyline fill="none" stroke="#000000" points="1132.5,-731.5 1317.5,-731.5 "/>
<text text-anchor="middle" x="1225" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1132.5,-708.5 1317.5,-708.5 "/>
<text text-anchor="middle" x="1225" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="1132.5,-685.5 1317.5,-685.5 "/>
<text text-anchor="middle" x="1225" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1132.5,-662.5 1317.5,-662.5 "/>
<text text-anchor="middle" x="1225" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1317.5,-639.5 1317.5,-869.5 "/>
<text text-anchor="middle" x="1328" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1180.5,-639.2724C1180.5,-624.8861 1180.5,-610.7136 1180.5,-597.8145"/>
<polygon fill="#000000" stroke="#000000" points="1184.0001,-597.7629 1180.5,-587.7629 1177.0001,-597.763 1184.0001,-597.7629"/>
<text text-anchor="middle" x="1227.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- survival -->
<g id="node10" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M1369,-662.5C1369,-662.5 1730,-662.5 1730,-662.5 1736,-662.5 1742,-668.5 1742,-674.5 1742,-674.5 1742,-834.5 1742,-834.5 1742,-840.5 1736,-846.5 1730,-846.5 1730,-846.5 1369,-846.5 1369,-846.5 1363,-846.5 1357,-840.5 1357,-834.5 1357,-834.5 1357,-674.5 1357,-674.5 1357,-668.5 1363,-662.5 1369,-662.5"/>
<text text-anchor="middle" x="1394" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="1431,-662.5 1431,-846.5 "/>
<text text-anchor="middle" x="1441.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1452,-662.5 1452,-846.5 "/>
<text text-anchor="middle" x="1586.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="1452,-823.5 1721,-823.5 "/>
<text text-anchor="middle" x="1586.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="1452,-800.5 1721,-800.5 "/>
<text text-anchor="middle" x="1586.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="1452,-777.5 1721,-777.5 "/>
<text text-anchor="middle" x="1586.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="1452,-754.5 1721,-754.5 "/>
<text text-anchor="middle" x="1586.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="1452,-731.5 1721,-731.5 "/>
<text text-anchor="middle" x="1586.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1452,-708.5 1721,-708.5 "/>
<text text-anchor="middle" x="1586.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="1452,-685.5 1721,-685.5 "/>
<text text-anchor="middle" x="1586.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="1721,-662.5 1721,-846.5 "/>
<text text-anchor="middle" x="1731.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1390.0654,-662.4687C1348.7366,-638.6122 1305.6982,-613.7689 1269.4539,-592.8474"/>
<polygon fill="#000000" stroke="#000000" points="1270.8013,-589.5839 1260.3908,-587.6158 1267.3018,-595.6464 1270.8013,-589.5839"/>
<text text-anchor="middle" x="1350" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- laboratory_test -->
<g id="node11" class="node">
<title>laboratory_test</title>
<path fill="none" stroke="#000000" d="M1022.5,-1094C1022.5,-1094 1354.5,-1094 1354.5,-1094 1360.5,-1094 1366.5,-1100 1366.5,-1106 1366.5,-1106 1366.5,-1335 1366.5,-1335 1366.5,-1341 1360.5,-1347 1354.5,-1347 1354.5,-1347 1022.5,-1347 1022.5,-1347 1016.5,-1347 1010.5,-1341 1010.5,-1335 1010.5,-1335 1010.5,-1106 1010.5,-1106 1010.5,-1100 1016.5,-1094 1022.5,-1094"/>
<text text-anchor="middle" x="1073.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="1136.5,-1094 1136.5,-1347 "/>
<text text-anchor="middle" x="1147" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1157.5,-1094 1157.5,-1347 "/>
<text text-anchor="middle" x="1251.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_laboratory_test</text>
<polyline fill="none" stroke="#000000" points="1157.5,-1324 1345.5,-1324 "/>
<text text-anchor="middle" x="1251.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1157.5,-1301 1345.5,-1301 "/>
<text text-anchor="middle" x="1251.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_id</text>
<polyline fill="none" stroke="#000000" points="1157.5,-1278 1345.5,-1278 "/>
<text text-anchor="middle" x="1251.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_method</text>
<polyline fill="none" stroke="#000000" points="1157.5,-1255 1345.5,-1255 "/>
<text text-anchor="middle" x="1251.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_name</text>
<polyline fill="none" stroke="#000000" points="1157.5,-1232 1345.5,-1232 "/>
<text text-anchor="middle" x="1251.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">sensitivity</text>
<polyline fill="none" stroke="#000000" points="1157.5,-1209 1345.5,-1209 "/>
<text text-anchor="middle" x="1251.5" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">specimen</text>
<polyline fill="none" stroke="#000000" points="1157.5,-1186 1345.5,-1186 "/>
<text text-anchor="middle" x="1251.5" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_modifier</text>
<polyline fill="none" stroke="#000000" points="1157.5,-1163 1345.5,-1163 "/>
<text text-anchor="middle" x="1251.5" y="-1147.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_numeric</text>
<polyline fill="none" stroke="#000000" points="1157.5,-1140 1345.5,-1140 "/>
<text text-anchor="middle" x="1251.5" y="-1124.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_text</text>
<polyline fill="none" stroke="#000000" points="1157.5,-1117 1345.5,-1117 "/>
<text text-anchor="middle" x="1251.5" y="-1101.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_unit</text>
<polyline fill="none" stroke="#000000" points="1345.5,-1094 1345.5,-1347 "/>
<text text-anchor="middle" x="1356" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1366.5305,-1110.8466C1477.5615,-1042.1679 1623.2376,-951.5285 1751.5,-870 1754.8154,-867.8926 1758.1634,-865.7604 1761.5357,-863.609"/>
<polygon fill="#000000" stroke="#000000" points="1763.4202,-866.5584 1769.9631,-858.2252 1759.6517,-860.6594 1763.4202,-866.5584"/>
<text text-anchor="middle" x="1786" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1037.93,-1093.7786C977.3752,-1033.0779 914.4159,-955.0862 882.5,-870 846.4428,-773.8734 822.239,-722.1207 882.5,-639 902.5611,-611.3288 974.6443,-587.3446 1042.8864,-570.0882"/>
<polygon fill="#000000" stroke="#000000" points="1044.0615,-573.4026 1052.9204,-567.5914 1042.3711,-566.6098 1044.0615,-573.4026"/>
<text text-anchor="middle" x="948" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
</g>
</svg>
</div>
