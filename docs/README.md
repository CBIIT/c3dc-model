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
<svg width="2448pt" height="1528pt"
 viewBox="0.00 0.00 2448.00 1528.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1524)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1524 2444,-1524 2444,4 -4,4"/>
<!-- sample -->
<g id="node1" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1534.5,-651C1534.5,-651 1848.5,-651 1848.5,-651 1854.5,-651 1860.5,-657 1860.5,-663 1860.5,-663 1860.5,-846 1860.5,-846 1860.5,-852 1854.5,-858 1848.5,-858 1848.5,-858 1534.5,-858 1534.5,-858 1528.5,-858 1522.5,-852 1522.5,-846 1522.5,-846 1522.5,-663 1522.5,-663 1522.5,-657 1528.5,-651 1534.5,-651"/>
<text text-anchor="middle" x="1556.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1590.5,-651 1590.5,-858 "/>
<text text-anchor="middle" x="1601" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1611.5,-651 1611.5,-858 "/>
<text text-anchor="middle" x="1725.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1611.5,-835 1839.5,-835 "/>
<text text-anchor="middle" x="1725.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1611.5,-812 1839.5,-812 "/>
<text text-anchor="middle" x="1725.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1611.5,-789 1839.5,-789 "/>
<text text-anchor="middle" x="1725.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_necrosis</text>
<polyline fill="none" stroke="#000000" points="1611.5,-766 1839.5,-766 "/>
<text text-anchor="middle" x="1725.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_tumor</text>
<polyline fill="none" stroke="#000000" points="1611.5,-743 1839.5,-743 "/>
<text text-anchor="middle" x="1725.5" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1611.5,-720 1839.5,-720 "/>
<text text-anchor="middle" x="1725.5" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1611.5,-697 1839.5,-697 "/>
<text text-anchor="middle" x="1725.5" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1611.5,-674 1839.5,-674 "/>
<text text-anchor="middle" x="1725.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1839.5,-651 1839.5,-858 "/>
<text text-anchor="middle" x="1850" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node6" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M966,-495.5C966,-495.5 1197,-495.5 1197,-495.5 1203,-495.5 1209,-501.5 1209,-507.5 1209,-507.5 1209,-575.5 1209,-575.5 1209,-581.5 1203,-587.5 1197,-587.5 1197,-587.5 966,-587.5 966,-587.5 960,-587.5 954,-581.5 954,-575.5 954,-575.5 954,-507.5 954,-507.5 954,-501.5 960,-495.5 966,-495.5"/>
<text text-anchor="middle" x="1002" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1050,-495.5 1050,-587.5 "/>
<text text-anchor="middle" x="1060.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1071,-495.5 1071,-587.5 "/>
<text text-anchor="middle" x="1129.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1071,-564.5 1188,-564.5 "/>
<text text-anchor="middle" x="1129.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1071,-541.5 1188,-541.5 "/>
<text text-anchor="middle" x="1129.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1071,-518.5 1188,-518.5 "/>
<text text-anchor="middle" x="1129.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="1188,-495.5 1188,-587.5 "/>
<text text-anchor="middle" x="1198.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1539.2463,-650.9526C1530.6844,-646.6347 1522.0718,-642.6118 1513.5,-639 1419.18,-599.2577 1306.1404,-574.4834 1219.3535,-559.8567"/>
<polygon fill="#000000" stroke="#000000" points="1219.8771,-556.3958 1209.4388,-558.2105 1218.7305,-563.3013 1219.8771,-556.3958"/>
<text text-anchor="middle" x="1493" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
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
<g id="node9" class="node">
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
<g id="edge6" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M176.2184,-213.4651C181.2736,-201.6374 187.3059,-190.2265 194.5,-180 197.1103,-176.2894 199.9042,-172.6633 202.8495,-169.1251"/>
<polygon fill="#000000" stroke="#000000" points="205.5584,-171.3446 209.527,-161.5211 200.2986,-166.7256 205.5584,-171.3446"/>
<text text-anchor="middle" x="255" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- treatment_response -->
<g id="node3" class="node">
<title>treatment_response</title>
<path fill="none" stroke="#000000" d="M2067,-685.5C2067,-685.5 2428,-685.5 2428,-685.5 2434,-685.5 2440,-691.5 2440,-697.5 2440,-697.5 2440,-811.5 2440,-811.5 2440,-817.5 2434,-823.5 2428,-823.5 2428,-823.5 2067,-823.5 2067,-823.5 2061,-823.5 2055,-817.5 2055,-811.5 2055,-811.5 2055,-697.5 2055,-697.5 2055,-691.5 2061,-685.5 2067,-685.5"/>
<text text-anchor="middle" x="2135.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
<polyline fill="none" stroke="#000000" points="2216,-685.5 2216,-823.5 "/>
<text text-anchor="middle" x="2226.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2237,-685.5 2237,-823.5 "/>
<text text-anchor="middle" x="2328" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_response</text>
<polyline fill="none" stroke="#000000" points="2237,-800.5 2419,-800.5 "/>
<text text-anchor="middle" x="2328" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2237,-777.5 2419,-777.5 "/>
<text text-anchor="middle" x="2328" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="2237,-754.5 2419,-754.5 "/>
<text text-anchor="middle" x="2328" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_category</text>
<polyline fill="none" stroke="#000000" points="2237,-731.5 2419,-731.5 "/>
<text text-anchor="middle" x="2328" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_system</text>
<polyline fill="none" stroke="#000000" points="2237,-708.5 2419,-708.5 "/>
<text text-anchor="middle" x="2328" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response_id</text>
<polyline fill="none" stroke="#000000" points="2419,-685.5 2419,-823.5 "/>
<text text-anchor="middle" x="2429.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2136.2313,-685.4565C2105.9461,-668.6122 2072.6185,-651.7827 2040.5,-639 1985.1149,-616.9575 1969.3189,-615.6807 1910.5,-606 1669.303,-566.3028 1384.4882,-550.9013 1219.2828,-545.0228"/>
<polygon fill="#000000" stroke="#000000" points="1219.1809,-541.5172 1209.0648,-544.666 1218.9365,-548.5129 1219.1809,-541.5172"/>
<text text-anchor="middle" x="2070.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- genetic_analysis -->
<g id="node4" class="node">
<title>genetic_analysis</title>
<path fill="none" stroke="#000000" d="M1602.5,-921.5C1602.5,-921.5 1986.5,-921.5 1986.5,-921.5 1992.5,-921.5 1998.5,-927.5 1998.5,-933.5 1998.5,-933.5 1998.5,-1507.5 1998.5,-1507.5 1998.5,-1513.5 1992.5,-1519.5 1986.5,-1519.5 1986.5,-1519.5 1602.5,-1519.5 1602.5,-1519.5 1596.5,-1519.5 1590.5,-1513.5 1590.5,-1507.5 1590.5,-1507.5 1590.5,-933.5 1590.5,-933.5 1590.5,-927.5 1596.5,-921.5 1602.5,-921.5"/>
<text text-anchor="middle" x="1658" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="1725.5,-921.5 1725.5,-1519.5 "/>
<text text-anchor="middle" x="1736" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1746.5,-921.5 1746.5,-1519.5 "/>
<text text-anchor="middle" x="1862" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="1746.5,-1496.5 1977.5,-1496.5 "/>
<text text-anchor="middle" x="1862" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">allelic_ratio</text>
<polyline fill="none" stroke="#000000" points="1746.5,-1473.5 1977.5,-1473.5 "/>
<text text-anchor="middle" x="1862" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration</text>
<polyline fill="none" stroke="#000000" points="1746.5,-1450.5 1977.5,-1450.5 "/>
<text text-anchor="middle" x="1862" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration_effect</text>
<polyline fill="none" stroke="#000000" points="1746.5,-1427.5 1977.5,-1427.5 "/>
<text text-anchor="middle" x="1862" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration_type</text>
<polyline fill="none" stroke="#000000" points="1746.5,-1404.5 1977.5,-1404.5 "/>
<text text-anchor="middle" x="1862" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="1746.5,-1381.5 1977.5,-1381.5 "/>
<text text-anchor="middle" x="1862" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="1746.5,-1358.5 1977.5,-1358.5 "/>
<text text-anchor="middle" x="1862" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">dna_index_numeric</text>
<polyline fill="none" stroke="#000000" points="1746.5,-1335.5 1977.5,-1335.5 "/>
<text text-anchor="middle" x="1862" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="1746.5,-1312.5 1977.5,-1312.5 "/>
<text text-anchor="middle" x="1862" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_exon</text>
<polyline fill="none" stroke="#000000" points="1746.5,-1289.5 1977.5,-1289.5 "/>
<text text-anchor="middle" x="1862" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_gene</text>
<polyline fill="none" stroke="#000000" points="1746.5,-1266.5 1977.5,-1266.5 "/>
<text text-anchor="middle" x="1862" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_transcript</text>
<polyline fill="none" stroke="#000000" points="1746.5,-1243.5 1977.5,-1243.5 "/>
<text text-anchor="middle" x="1862" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="1746.5,-1220.5 1977.5,-1220.5 "/>
<text text-anchor="middle" x="1862" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis_id</text>
<polyline fill="none" stroke="#000000" points="1746.5,-1197.5 1977.5,-1197.5 "/>
<text text-anchor="middle" x="1862" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_source_category</text>
<polyline fill="none" stroke="#000000" points="1746.5,-1174.5 1977.5,-1174.5 "/>
<text text-anchor="middle" x="1862" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_coding</text>
<polyline fill="none" stroke="#000000" points="1746.5,-1151.5 1977.5,-1151.5 "/>
<text text-anchor="middle" x="1862" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_genome</text>
<polyline fill="none" stroke="#000000" points="1746.5,-1128.5 1977.5,-1128.5 "/>
<text text-anchor="middle" x="1862" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_protein</text>
<polyline fill="none" stroke="#000000" points="1746.5,-1105.5 1977.5,-1105.5 "/>
<text text-anchor="middle" x="1862" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1746.5,-1082.5 1977.5,-1082.5 "/>
<text text-anchor="middle" x="1862" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">iscn</text>
<polyline fill="none" stroke="#000000" points="1746.5,-1059.5 1977.5,-1059.5 "/>
<text text-anchor="middle" x="1862" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">method</text>
<polyline fill="none" stroke="#000000" points="1746.5,-1036.5 1977.5,-1036.5 "/>
<text text-anchor="middle" x="1862" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome</text>
<polyline fill="none" stroke="#000000" points="1746.5,-1013.5 1977.5,-1013.5 "/>
<text text-anchor="middle" x="1862" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance</text>
<polyline fill="none" stroke="#000000" points="1746.5,-990.5 1977.5,-990.5 "/>
<text text-anchor="middle" x="1862" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance_system</text>
<polyline fill="none" stroke="#000000" points="1746.5,-967.5 1977.5,-967.5 "/>
<text text-anchor="middle" x="1862" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">result</text>
<polyline fill="none" stroke="#000000" points="1746.5,-944.5 1977.5,-944.5 "/>
<text text-anchor="middle" x="1862" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 6 properties</text>
<polyline fill="none" stroke="#000000" points="1977.5,-921.5 1977.5,-1519.5 "/>
<text text-anchor="middle" x="1988" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1728.3944,-921.4205C1724.339,-903.0727 1720.4154,-885.3209 1716.7359,-868.6741"/>
<polygon fill="#000000" stroke="#000000" points="1720.0533,-867.4654 1714.4775,-858.4565 1713.2183,-868.9762 1720.0533,-867.4654"/>
<text text-anchor="middle" x="1791.5" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1873.829,-921.1837C1897.3253,-801.7521 1907.7992,-682.33 1869.5,-639 1827.2345,-591.1827 1433.7724,-561.5258 1219.3283,-548.7774"/>
<polygon fill="#000000" stroke="#000000" points="1219.4429,-545.2782 1209.2541,-548.1831 1219.0306,-552.266 1219.4429,-545.2782"/>
<text text-anchor="middle" x="1964.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- consent_group -->
<g id="node5" class="node">
<title>consent_group</title>
<path fill="none" stroke="#000000" d="M644,-271C644,-271 969,-271 969,-271 975,-271 981,-277 981,-283 981,-283 981,-374 981,-374 981,-380 975,-386 969,-386 969,-386 644,-386 644,-386 638,-386 632,-380 632,-374 632,-374 632,-283 632,-283 632,-277 638,-271 644,-271"/>
<text text-anchor="middle" x="693" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
<polyline fill="none" stroke="#000000" points="754,-271 754,-386 "/>
<text text-anchor="middle" x="764.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="775,-271 775,-386 "/>
<text text-anchor="middle" x="867.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_id</text>
<polyline fill="none" stroke="#000000" points="775,-363 960,-363 "/>
<text text-anchor="middle" x="867.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_name</text>
<polyline fill="none" stroke="#000000" points="775,-340 960,-340 "/>
<text text-anchor="middle" x="867.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_number</text>
<polyline fill="none" stroke="#000000" points="775,-317 960,-317 "/>
<text text-anchor="middle" x="867.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_suffix</text>
<polyline fill="none" stroke="#000000" points="775,-294 960,-294 "/>
<text text-anchor="middle" x="867.5" y="-278.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="960,-271 960,-386 "/>
<text text-anchor="middle" x="970.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge10" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M695.5673,-270.9406C625.2096,-234.4342 533.8645,-187.0382 460.0232,-148.7243"/>
<polygon fill="#000000" stroke="#000000" points="461.5958,-145.5972 451.1075,-144.0982 458.3718,-151.8106 461.5958,-145.5972"/>
<text text-anchor="middle" x="603" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge7" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1021.8291,-495.2822C982.9473,-465.1665 931.6852,-425.4617 888.932,-392.3473"/>
<polygon fill="#000000" stroke="#000000" points="890.8265,-389.3877 880.7774,-386.0312 886.5401,-394.9218 890.8265,-389.3877"/>
<text text-anchor="middle" x="1044" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- synonym -->
<g id="node7" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M162,-674C162,-674 463,-674 463,-674 469,-674 475,-680 475,-686 475,-686 475,-823 475,-823 475,-829 469,-835 463,-835 463,-835 162,-835 162,-835 156,-835 150,-829 150,-823 150,-823 150,-686 150,-686 150,-680 156,-674 162,-674"/>
<text text-anchor="middle" x="190" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="230,-674 230,-835 "/>
<text text-anchor="middle" x="240.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="251,-674 251,-835 "/>
<text text-anchor="middle" x="352.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_id</text>
<polyline fill="none" stroke="#000000" points="251,-812 454,-812 "/>
<text text-anchor="middle" x="352.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">data_location</text>
<polyline fill="none" stroke="#000000" points="251,-789 454,-789 "/>
<text text-anchor="middle" x="352.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">domain_category</text>
<polyline fill="none" stroke="#000000" points="251,-766 454,-766 "/>
<text text-anchor="middle" x="352.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">domain_description</text>
<polyline fill="none" stroke="#000000" points="251,-743 454,-743 "/>
<text text-anchor="middle" x="352.5" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="251,-720 454,-720 "/>
<text text-anchor="middle" x="352.5" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="251,-697 454,-697 "/>
<text text-anchor="middle" x="352.5" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="454,-674 454,-835 "/>
<text text-anchor="middle" x="464.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M348.6006,-673.6147C364.2014,-647.7936 385.0468,-621.8346 411.5,-606 455.998,-579.3639 760.9525,-558.6537 943.7483,-548.4589"/>
<polygon fill="#000000" stroke="#000000" points="944.1911,-551.9399 953.9822,-547.892 943.8039,-544.9506 944.1911,-551.9399"/>
<text text-anchor="middle" x="454" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge1" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M314.5337,-673.9291C317.7204,-547.6808 323.8703,-304.0344 327.2089,-171.77"/>
<polygon fill="#000000" stroke="#000000" points="330.7104,-171.7487 327.464,-161.6635 323.7126,-171.572 330.7104,-171.7487"/>
<text text-anchor="middle" x="363" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- survival -->
<g id="node8" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M672,-662.5C672,-662.5 1033,-662.5 1033,-662.5 1039,-662.5 1045,-668.5 1045,-674.5 1045,-674.5 1045,-834.5 1045,-834.5 1045,-840.5 1039,-846.5 1033,-846.5 1033,-846.5 672,-846.5 672,-846.5 666,-846.5 660,-840.5 660,-834.5 660,-834.5 660,-674.5 660,-674.5 660,-668.5 666,-662.5 672,-662.5"/>
<text text-anchor="middle" x="697" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="734,-662.5 734,-846.5 "/>
<text text-anchor="middle" x="744.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="755,-662.5 755,-846.5 "/>
<text text-anchor="middle" x="889.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="755,-823.5 1024,-823.5 "/>
<text text-anchor="middle" x="889.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="755,-800.5 1024,-800.5 "/>
<text text-anchor="middle" x="889.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="755,-777.5 1024,-777.5 "/>
<text text-anchor="middle" x="889.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="755,-754.5 1024,-754.5 "/>
<text text-anchor="middle" x="889.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="755,-731.5 1024,-731.5 "/>
<text text-anchor="middle" x="889.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="755,-708.5 1024,-708.5 "/>
<text text-anchor="middle" x="889.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="755,-685.5 1024,-685.5 "/>
<text text-anchor="middle" x="889.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="1024,-662.5 1024,-846.5 "/>
<text text-anchor="middle" x="1034.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M931.0674,-662.2431C949.1651,-642.8681 968.8825,-623.1313 988.5,-606 993.162,-601.9288 998.0848,-597.883 1003.1336,-593.9179"/>
<polygon fill="#000000" stroke="#000000" points="1005.3517,-596.6276 1011.1518,-587.7614 1001.0886,-591.0754 1005.3517,-596.6276"/>
<text text-anchor="middle" x="1028" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- laboratory_test -->
<g id="node10" class="node">
<title>laboratory_test</title>
<path fill="none" stroke="#000000" d="M518.5,-1094C518.5,-1094 850.5,-1094 850.5,-1094 856.5,-1094 862.5,-1100 862.5,-1106 862.5,-1106 862.5,-1335 862.5,-1335 862.5,-1341 856.5,-1347 850.5,-1347 850.5,-1347 518.5,-1347 518.5,-1347 512.5,-1347 506.5,-1341 506.5,-1335 506.5,-1335 506.5,-1106 506.5,-1106 506.5,-1100 512.5,-1094 518.5,-1094"/>
<text text-anchor="middle" x="569.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="632.5,-1094 632.5,-1347 "/>
<text text-anchor="middle" x="643" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="653.5,-1094 653.5,-1347 "/>
<text text-anchor="middle" x="747.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_laboratory_test</text>
<polyline fill="none" stroke="#000000" points="653.5,-1324 841.5,-1324 "/>
<text text-anchor="middle" x="747.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="653.5,-1301 841.5,-1301 "/>
<text text-anchor="middle" x="747.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_id</text>
<polyline fill="none" stroke="#000000" points="653.5,-1278 841.5,-1278 "/>
<text text-anchor="middle" x="747.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_method</text>
<polyline fill="none" stroke="#000000" points="653.5,-1255 841.5,-1255 "/>
<text text-anchor="middle" x="747.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_name</text>
<polyline fill="none" stroke="#000000" points="653.5,-1232 841.5,-1232 "/>
<text text-anchor="middle" x="747.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">sensitivity</text>
<polyline fill="none" stroke="#000000" points="653.5,-1209 841.5,-1209 "/>
<text text-anchor="middle" x="747.5" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">specimen</text>
<polyline fill="none" stroke="#000000" points="653.5,-1186 841.5,-1186 "/>
<text text-anchor="middle" x="747.5" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_modifier</text>
<polyline fill="none" stroke="#000000" points="653.5,-1163 841.5,-1163 "/>
<text text-anchor="middle" x="747.5" y="-1147.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_numeric</text>
<polyline fill="none" stroke="#000000" points="653.5,-1140 841.5,-1140 "/>
<text text-anchor="middle" x="747.5" y="-1124.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_text</text>
<polyline fill="none" stroke="#000000" points="653.5,-1117 841.5,-1117 "/>
<text text-anchor="middle" x="747.5" y="-1101.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_unit</text>
<polyline fill="none" stroke="#000000" points="841.5,-1094 841.5,-1347 "/>
<text text-anchor="middle" x="852" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M767.2576,-1093.9551C815.8309,-1030.7597 883.0551,-959.6964 961.5,-921 1071.9784,-866.5017 1397.1127,-910.3678 1513.5,-870 1520.0476,-867.729 1526.5941,-865.1681 1533.1043,-862.3721"/>
<polygon fill="#000000" stroke="#000000" points="1534.9165,-865.3955 1542.6125,-858.1138 1532.0554,-859.007 1534.9165,-865.3955"/>
<text text-anchor="middle" x="1441" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M608.3188,-1093.9039C573.8464,-1029.3337 536.9652,-948.106 519.5,-870 497.0961,-769.8076 453.3989,-717.5562 519.5,-639 572.6716,-575.8096 795.1238,-553.5722 943.7015,-545.7473"/>
<polygon fill="#000000" stroke="#000000" points="944.0147,-549.236 953.8231,-545.2304 943.6576,-542.2451 944.0147,-549.236"/>
<text text-anchor="middle" x="585" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- treatment -->
<g id="node11" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M1200.5,-639.5C1200.5,-639.5 1492.5,-639.5 1492.5,-639.5 1498.5,-639.5 1504.5,-645.5 1504.5,-651.5 1504.5,-651.5 1504.5,-857.5 1504.5,-857.5 1504.5,-863.5 1498.5,-869.5 1492.5,-869.5 1492.5,-869.5 1200.5,-869.5 1200.5,-869.5 1194.5,-869.5 1188.5,-863.5 1188.5,-857.5 1188.5,-857.5 1188.5,-651.5 1188.5,-651.5 1188.5,-645.5 1194.5,-639.5 1200.5,-639.5"/>
<text text-anchor="middle" x="1233" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1277.5,-639.5 1277.5,-869.5 "/>
<text text-anchor="middle" x="1288" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1298.5,-639.5 1298.5,-869.5 "/>
<text text-anchor="middle" x="1391" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="1298.5,-846.5 1483.5,-846.5 "/>
<text text-anchor="middle" x="1391" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1298.5,-823.5 1483.5,-823.5 "/>
<text text-anchor="middle" x="1391" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose</text>
<polyline fill="none" stroke="#000000" points="1298.5,-800.5 1483.5,-800.5 "/>
<text text-anchor="middle" x="1391" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_frequency</text>
<polyline fill="none" stroke="#000000" points="1298.5,-777.5 1483.5,-777.5 "/>
<text text-anchor="middle" x="1391" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_route</text>
<polyline fill="none" stroke="#000000" points="1298.5,-754.5 1483.5,-754.5 "/>
<text text-anchor="middle" x="1391" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_unit</text>
<polyline fill="none" stroke="#000000" points="1298.5,-731.5 1483.5,-731.5 "/>
<text text-anchor="middle" x="1391" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1298.5,-708.5 1483.5,-708.5 "/>
<text text-anchor="middle" x="1391" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="1298.5,-685.5 1483.5,-685.5 "/>
<text text-anchor="middle" x="1391" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1298.5,-662.5 1483.5,-662.5 "/>
<text text-anchor="middle" x="1391" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1483.5,-639.5 1483.5,-869.5 "/>
<text text-anchor="middle" x="1494" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1203.1417,-639.2724C1183.3654,-623.3767 1163.9139,-607.7421 1146.5653,-593.7977"/>
<polygon fill="#000000" stroke="#000000" points="1148.7357,-591.0518 1138.7487,-587.515 1144.3503,-596.5079 1148.7357,-591.0518"/>
<text text-anchor="middle" x="1222.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- diagnosis -->
<g id="node12" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M983,-1013.5C983,-1013.5 1348,-1013.5 1348,-1013.5 1354,-1013.5 1360,-1019.5 1360,-1025.5 1360,-1025.5 1360,-1415.5 1360,-1415.5 1360,-1421.5 1354,-1427.5 1348,-1427.5 1348,-1427.5 983,-1427.5 983,-1427.5 977,-1427.5 971,-1421.5 971,-1415.5 971,-1415.5 971,-1025.5 971,-1025.5 971,-1019.5 977,-1013.5 983,-1013.5"/>
<text text-anchor="middle" x="1013" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1055,-1013.5 1055,-1427.5 "/>
<text text-anchor="middle" x="1065.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1076,-1013.5 1076,-1427.5 "/>
<text text-anchor="middle" x="1207.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1076,-1404.5 1339,-1404.5 "/>
<text text-anchor="middle" x="1207.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1076,-1381.5 1339,-1381.5 "/>
<text text-anchor="middle" x="1207.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1076,-1358.5 1339,-1358.5 "/>
<text text-anchor="middle" x="1207.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="1076,-1335.5 1339,-1335.5 "/>
<text text-anchor="middle" x="1207.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_category</text>
<polyline fill="none" stroke="#000000" points="1076,-1312.5 1339,-1312.5 "/>
<text text-anchor="middle" x="1207.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="1076,-1289.5 1339,-1289.5 "/>
<text text-anchor="middle" x="1207.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="1076,-1266.5 1339,-1266.5 "/>
<text text-anchor="middle" x="1207.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1076,-1243.5 1339,-1243.5 "/>
<text text-anchor="middle" x="1207.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="1076,-1220.5 1339,-1220.5 "/>
<text text-anchor="middle" x="1207.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1076,-1197.5 1339,-1197.5 "/>
<text text-anchor="middle" x="1207.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">laterality</text>
<polyline fill="none" stroke="#000000" points="1076,-1174.5 1339,-1174.5 "/>
<text text-anchor="middle" x="1207.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="1076,-1151.5 1339,-1151.5 "/>
<text text-anchor="middle" x="1207.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1076,-1128.5 1339,-1128.5 "/>
<text text-anchor="middle" x="1207.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1076,-1105.5 1339,-1105.5 "/>
<text text-anchor="middle" x="1207.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1076,-1082.5 1339,-1082.5 "/>
<text text-anchor="middle" x="1207.5" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1076,-1059.5 1339,-1059.5 "/>
<text text-anchor="middle" x="1207.5" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1076,-1036.5 1339,-1036.5 "/>
<text text-anchor="middle" x="1207.5" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1339,-1013.5 1339,-1427.5 "/>
<text text-anchor="middle" x="1349.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1360.242,-1047.972C1429.2485,-986.8368 1504.9905,-919.7346 1566.6109,-865.1432"/>
<polygon fill="#000000" stroke="#000000" points="1569.2741,-867.4598 1574.4382,-858.2087 1564.6322,-862.2202 1569.2741,-867.4598"/>
<text text-anchor="middle" x="1580" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1114.5477,-1013.0496C1104.8952,-966.2692 1096.0822,-916.6495 1090.5,-870 1079.1271,-774.9583 1078.7955,-663.3979 1079.9177,-597.7916"/>
<polygon fill="#000000" stroke="#000000" points="1083.4194,-597.7307 1080.1089,-587.6663 1076.4207,-597.5985 1083.4194,-597.7307"/>
<text text-anchor="middle" x="1135" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
</g>
</svg>
</div>
