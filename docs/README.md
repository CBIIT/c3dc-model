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
<svg width="2320pt" height="1528pt"
 viewBox="0.00 0.00 2319.50 1528.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1524)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1524 2315.5,-1524 2315.5,4 -4,4"/>
<!-- genetic_analysis -->
<g id="node1" class="node">
<title>genetic_analysis</title>
<path fill="none" stroke="#000000" d="M1712.5,-921.5C1712.5,-921.5 2096.5,-921.5 2096.5,-921.5 2102.5,-921.5 2108.5,-927.5 2108.5,-933.5 2108.5,-933.5 2108.5,-1507.5 2108.5,-1507.5 2108.5,-1513.5 2102.5,-1519.5 2096.5,-1519.5 2096.5,-1519.5 1712.5,-1519.5 1712.5,-1519.5 1706.5,-1519.5 1700.5,-1513.5 1700.5,-1507.5 1700.5,-1507.5 1700.5,-933.5 1700.5,-933.5 1700.5,-927.5 1706.5,-921.5 1712.5,-921.5"/>
<text text-anchor="middle" x="1768" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="1835.5,-921.5 1835.5,-1519.5 "/>
<text text-anchor="middle" x="1846" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1856.5,-921.5 1856.5,-1519.5 "/>
<text text-anchor="middle" x="1972" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="1856.5,-1496.5 2087.5,-1496.5 "/>
<text text-anchor="middle" x="1972" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">allelic_ratio</text>
<polyline fill="none" stroke="#000000" points="1856.5,-1473.5 2087.5,-1473.5 "/>
<text text-anchor="middle" x="1972" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration</text>
<polyline fill="none" stroke="#000000" points="1856.5,-1450.5 2087.5,-1450.5 "/>
<text text-anchor="middle" x="1972" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration_effect</text>
<polyline fill="none" stroke="#000000" points="1856.5,-1427.5 2087.5,-1427.5 "/>
<text text-anchor="middle" x="1972" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration_type</text>
<polyline fill="none" stroke="#000000" points="1856.5,-1404.5 2087.5,-1404.5 "/>
<text text-anchor="middle" x="1972" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="1856.5,-1381.5 2087.5,-1381.5 "/>
<text text-anchor="middle" x="1972" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="1856.5,-1358.5 2087.5,-1358.5 "/>
<text text-anchor="middle" x="1972" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">dna_index_numeric</text>
<polyline fill="none" stroke="#000000" points="1856.5,-1335.5 2087.5,-1335.5 "/>
<text text-anchor="middle" x="1972" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="1856.5,-1312.5 2087.5,-1312.5 "/>
<text text-anchor="middle" x="1972" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_exon</text>
<polyline fill="none" stroke="#000000" points="1856.5,-1289.5 2087.5,-1289.5 "/>
<text text-anchor="middle" x="1972" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_gene</text>
<polyline fill="none" stroke="#000000" points="1856.5,-1266.5 2087.5,-1266.5 "/>
<text text-anchor="middle" x="1972" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_transcript</text>
<polyline fill="none" stroke="#000000" points="1856.5,-1243.5 2087.5,-1243.5 "/>
<text text-anchor="middle" x="1972" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="1856.5,-1220.5 2087.5,-1220.5 "/>
<text text-anchor="middle" x="1972" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis_id</text>
<polyline fill="none" stroke="#000000" points="1856.5,-1197.5 2087.5,-1197.5 "/>
<text text-anchor="middle" x="1972" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_source_category</text>
<polyline fill="none" stroke="#000000" points="1856.5,-1174.5 2087.5,-1174.5 "/>
<text text-anchor="middle" x="1972" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_coding</text>
<polyline fill="none" stroke="#000000" points="1856.5,-1151.5 2087.5,-1151.5 "/>
<text text-anchor="middle" x="1972" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_genome</text>
<polyline fill="none" stroke="#000000" points="1856.5,-1128.5 2087.5,-1128.5 "/>
<text text-anchor="middle" x="1972" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_protein</text>
<polyline fill="none" stroke="#000000" points="1856.5,-1105.5 2087.5,-1105.5 "/>
<text text-anchor="middle" x="1972" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1856.5,-1082.5 2087.5,-1082.5 "/>
<text text-anchor="middle" x="1972" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">iscn</text>
<polyline fill="none" stroke="#000000" points="1856.5,-1059.5 2087.5,-1059.5 "/>
<text text-anchor="middle" x="1972" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">method</text>
<polyline fill="none" stroke="#000000" points="1856.5,-1036.5 2087.5,-1036.5 "/>
<text text-anchor="middle" x="1972" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome</text>
<polyline fill="none" stroke="#000000" points="1856.5,-1013.5 2087.5,-1013.5 "/>
<text text-anchor="middle" x="1972" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance</text>
<polyline fill="none" stroke="#000000" points="1856.5,-990.5 2087.5,-990.5 "/>
<text text-anchor="middle" x="1972" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance_system</text>
<polyline fill="none" stroke="#000000" points="1856.5,-967.5 2087.5,-967.5 "/>
<text text-anchor="middle" x="1972" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">result</text>
<polyline fill="none" stroke="#000000" points="1856.5,-944.5 2087.5,-944.5 "/>
<text text-anchor="middle" x="1972" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 6 properties</text>
<polyline fill="none" stroke="#000000" points="2087.5,-921.5 2087.5,-1519.5 "/>
<text text-anchor="middle" x="2098" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
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
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1700.2588,-1072.6449C1620.4516,-1019.6045 1526.3932,-962.673 1435.5,-921 1363.7949,-888.1245 1337.2921,-902.6852 1265.5,-870 1260.4245,-867.6893 1255.3224,-865.2582 1250.2137,-862.7285"/>
<polygon fill="#000000" stroke="#000000" points="1251.5183,-859.466 1241.0154,-858.0732 1248.3573,-865.7117 1251.5183,-859.466"/>
<text text-anchor="middle" x="1454.5" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- participant -->
<g id="node12" class="node">
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
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2108.5353,-965.8C2172.0099,-854.9076 2206.2153,-729.8244 2123.5,-639 2063.8242,-573.4738 1489.3295,-551.181 1220.2536,-544.2933"/>
<polygon fill="#000000" stroke="#000000" points="1220.1123,-540.7887 1210.0271,-544.0352 1219.9356,-547.7865 1220.1123,-540.7887"/>
<text text-anchor="middle" x="2241.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
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
<g id="edge13" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M200.1475,-673.9069C211.6067,-651.4257 224.8154,-627.3286 238.5,-606 358.6348,-418.7601 387.6493,-366.6822 548.5,-213 565.1645,-197.0781 583.8461,-181.5261 602.7469,-167.0096"/>
<polygon fill="#000000" stroke="#000000" points="605.0071,-169.6881 610.8554,-160.8536 600.7743,-164.1128 605.0071,-169.6881"/>
<text text-anchor="middle" x="373" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M198.2112,-673.7431C213.8228,-647.7693 234.7751,-621.68 261.5,-606 318.8183,-572.3702 725.9254,-553.5675 944.5094,-545.7934"/>
<polygon fill="#000000" stroke="#000000" points="944.9031,-549.2818 954.7735,-545.4316 944.6564,-542.2862 944.9031,-549.2818"/>
<text text-anchor="middle" x="304" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- diagnosis -->
<g id="node3" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1050,-1013.5C1050,-1013.5 1415,-1013.5 1415,-1013.5 1421,-1013.5 1427,-1019.5 1427,-1025.5 1427,-1025.5 1427,-1415.5 1427,-1415.5 1427,-1421.5 1421,-1427.5 1415,-1427.5 1415,-1427.5 1050,-1427.5 1050,-1427.5 1044,-1427.5 1038,-1421.5 1038,-1415.5 1038,-1415.5 1038,-1025.5 1038,-1025.5 1038,-1019.5 1044,-1013.5 1050,-1013.5"/>
<text text-anchor="middle" x="1080" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1122,-1013.5 1122,-1427.5 "/>
<text text-anchor="middle" x="1132.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1143,-1013.5 1143,-1427.5 "/>
<text text-anchor="middle" x="1274.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1143,-1404.5 1406,-1404.5 "/>
<text text-anchor="middle" x="1274.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1143,-1381.5 1406,-1381.5 "/>
<text text-anchor="middle" x="1274.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1143,-1358.5 1406,-1358.5 "/>
<text text-anchor="middle" x="1274.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="1143,-1335.5 1406,-1335.5 "/>
<text text-anchor="middle" x="1274.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_category</text>
<polyline fill="none" stroke="#000000" points="1143,-1312.5 1406,-1312.5 "/>
<text text-anchor="middle" x="1274.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="1143,-1289.5 1406,-1289.5 "/>
<text text-anchor="middle" x="1274.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="1143,-1266.5 1406,-1266.5 "/>
<text text-anchor="middle" x="1274.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1143,-1243.5 1406,-1243.5 "/>
<text text-anchor="middle" x="1274.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="1143,-1220.5 1406,-1220.5 "/>
<text text-anchor="middle" x="1274.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1143,-1197.5 1406,-1197.5 "/>
<text text-anchor="middle" x="1274.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">laterality</text>
<polyline fill="none" stroke="#000000" points="1143,-1174.5 1406,-1174.5 "/>
<text text-anchor="middle" x="1274.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="1143,-1151.5 1406,-1151.5 "/>
<text text-anchor="middle" x="1274.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1143,-1128.5 1406,-1128.5 "/>
<text text-anchor="middle" x="1274.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1143,-1105.5 1406,-1105.5 "/>
<text text-anchor="middle" x="1274.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1143,-1082.5 1406,-1082.5 "/>
<text text-anchor="middle" x="1274.5" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1143,-1059.5 1406,-1059.5 "/>
<text text-anchor="middle" x="1274.5" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1143,-1036.5 1406,-1036.5 "/>
<text text-anchor="middle" x="1274.5" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1406,-1013.5 1406,-1427.5 "/>
<text text-anchor="middle" x="1416.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1165.8343,-1013.3918C1149.7243,-963.3434 1133.0949,-911.6815 1118.969,-867.7971"/>
<polygon fill="#000000" stroke="#000000" points="1122.297,-866.713 1115.9012,-858.2664 1115.6337,-868.8579 1122.297,-866.713"/>
<text text-anchor="middle" x="1172" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1266.0698,-1013.245C1284.5055,-872.2958 1297.0124,-700.6309 1260.5,-639 1249.6963,-620.764 1234.1412,-605.7145 1216.6643,-593.3611"/>
<polygon fill="#000000" stroke="#000000" points="1218.1972,-590.1749 1207.9427,-587.5111 1214.2978,-595.9883 1218.1972,-590.1749"/>
<text text-anchor="middle" x="1329" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- treatment_response -->
<g id="node4" class="node">
<title>treatment_response</title>
<path fill="none" stroke="#000000" d="M522,-685.5C522,-685.5 883,-685.5 883,-685.5 889,-685.5 895,-691.5 895,-697.5 895,-697.5 895,-811.5 895,-811.5 895,-817.5 889,-823.5 883,-823.5 883,-823.5 522,-823.5 522,-823.5 516,-823.5 510,-817.5 510,-811.5 510,-811.5 510,-697.5 510,-697.5 510,-691.5 516,-685.5 522,-685.5"/>
<text text-anchor="middle" x="590.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
<polyline fill="none" stroke="#000000" points="671,-685.5 671,-823.5 "/>
<text text-anchor="middle" x="681.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="692,-685.5 692,-823.5 "/>
<text text-anchor="middle" x="783" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_response</text>
<polyline fill="none" stroke="#000000" points="692,-800.5 874,-800.5 "/>
<text text-anchor="middle" x="783" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="692,-777.5 874,-777.5 "/>
<text text-anchor="middle" x="783" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="692,-754.5 874,-754.5 "/>
<text text-anchor="middle" x="783" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_category</text>
<polyline fill="none" stroke="#000000" points="692,-731.5 874,-731.5 "/>
<text text-anchor="middle" x="783" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_system</text>
<polyline fill="none" stroke="#000000" points="692,-708.5 874,-708.5 "/>
<text text-anchor="middle" x="783" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response_id</text>
<polyline fill="none" stroke="#000000" points="874,-685.5 874,-823.5 "/>
<text text-anchor="middle" x="884.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M789.7329,-685.3302C826.3085,-658.3489 870.1253,-628.5515 912.5,-606 922.9498,-600.4387 933.986,-595.1226 945.2125,-590.0993"/>
<polygon fill="#000000" stroke="#000000" points="946.9254,-593.1701 954.6788,-585.9497 944.115,-586.759 946.9254,-593.1701"/>
<text text-anchor="middle" x="995.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- laboratory_test -->
<g id="node5" class="node">
<title>laboratory_test</title>
<path fill="none" stroke="#000000" d="M510.5,-1094C510.5,-1094 842.5,-1094 842.5,-1094 848.5,-1094 854.5,-1100 854.5,-1106 854.5,-1106 854.5,-1335 854.5,-1335 854.5,-1341 848.5,-1347 842.5,-1347 842.5,-1347 510.5,-1347 510.5,-1347 504.5,-1347 498.5,-1341 498.5,-1335 498.5,-1335 498.5,-1106 498.5,-1106 498.5,-1100 504.5,-1094 510.5,-1094"/>
<text text-anchor="middle" x="561.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="624.5,-1094 624.5,-1347 "/>
<text text-anchor="middle" x="635" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="645.5,-1094 645.5,-1347 "/>
<text text-anchor="middle" x="739.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_laboratory_test</text>
<polyline fill="none" stroke="#000000" points="645.5,-1324 833.5,-1324 "/>
<text text-anchor="middle" x="739.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="645.5,-1301 833.5,-1301 "/>
<text text-anchor="middle" x="739.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_id</text>
<polyline fill="none" stroke="#000000" points="645.5,-1278 833.5,-1278 "/>
<text text-anchor="middle" x="739.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_method</text>
<polyline fill="none" stroke="#000000" points="645.5,-1255 833.5,-1255 "/>
<text text-anchor="middle" x="739.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_name</text>
<polyline fill="none" stroke="#000000" points="645.5,-1232 833.5,-1232 "/>
<text text-anchor="middle" x="739.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">sensitivity</text>
<polyline fill="none" stroke="#000000" points="645.5,-1209 833.5,-1209 "/>
<text text-anchor="middle" x="739.5" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">specimen</text>
<polyline fill="none" stroke="#000000" points="645.5,-1186 833.5,-1186 "/>
<text text-anchor="middle" x="739.5" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_modifier</text>
<polyline fill="none" stroke="#000000" points="645.5,-1163 833.5,-1163 "/>
<text text-anchor="middle" x="739.5" y="-1147.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_numeric</text>
<polyline fill="none" stroke="#000000" points="645.5,-1140 833.5,-1140 "/>
<text text-anchor="middle" x="739.5" y="-1124.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_text</text>
<polyline fill="none" stroke="#000000" points="645.5,-1117 833.5,-1117 "/>
<text text-anchor="middle" x="739.5" y="-1101.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_unit</text>
<polyline fill="none" stroke="#000000" points="833.5,-1094 833.5,-1347 "/>
<text text-anchor="middle" x="844" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M786.905,-1093.779C848.9694,-1022.5425 925.7303,-934.4377 985.4736,-865.8653"/>
<polygon fill="#000000" stroke="#000000" points="988.3733,-867.8651 992.3034,-858.0262 983.0954,-863.2668 988.3733,-867.8651"/>
<text text-anchor="middle" x="1029" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M525.4471,-1093.8677C464.6961,-1033.1838 401.5299,-955.1808 369.5,-870 351.4326,-821.9513 335.7502,-677.679 369.5,-639 406.6897,-596.3787 748.0839,-565.2661 944.6663,-550.7091"/>
<polygon fill="#000000" stroke="#000000" points="945.0702,-554.189 954.7865,-549.9649 944.5567,-547.2078 945.0702,-554.189"/>
<text text-anchor="middle" x="435" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- consent_group -->
<g id="node6" class="node">
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
<g id="edge4" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M732.5,-270.7846C732.5,-241.3997 732.5,-204.9895 732.5,-171.9435"/>
<polygon fill="#000000" stroke="#000000" points="736.0001,-171.8072 732.5,-161.8073 729.0001,-171.8073 736.0001,-171.8072"/>
<text text-anchor="middle" x="796" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1082.5,-650.8078C1082.5,-632.5822 1082.5,-614.2469 1082.5,-597.9389"/>
<polygon fill="#000000" stroke="#000000" points="1086.0001,-597.5364 1082.5,-587.5365 1079.0001,-597.5365 1086.0001,-597.5364"/>
<text text-anchor="middle" x="1119" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- treatment -->
<g id="node9" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M1406.5,-639.5C1406.5,-639.5 1698.5,-639.5 1698.5,-639.5 1704.5,-639.5 1710.5,-645.5 1710.5,-651.5 1710.5,-651.5 1710.5,-857.5 1710.5,-857.5 1710.5,-863.5 1704.5,-869.5 1698.5,-869.5 1698.5,-869.5 1406.5,-869.5 1406.5,-869.5 1400.5,-869.5 1394.5,-863.5 1394.5,-857.5 1394.5,-857.5 1394.5,-651.5 1394.5,-651.5 1394.5,-645.5 1400.5,-639.5 1406.5,-639.5"/>
<text text-anchor="middle" x="1439" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1483.5,-639.5 1483.5,-869.5 "/>
<text text-anchor="middle" x="1494" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1504.5,-639.5 1504.5,-869.5 "/>
<text text-anchor="middle" x="1597" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="1504.5,-846.5 1689.5,-846.5 "/>
<text text-anchor="middle" x="1597" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1504.5,-823.5 1689.5,-823.5 "/>
<text text-anchor="middle" x="1597" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose</text>
<polyline fill="none" stroke="#000000" points="1504.5,-800.5 1689.5,-800.5 "/>
<text text-anchor="middle" x="1597" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_frequency</text>
<polyline fill="none" stroke="#000000" points="1504.5,-777.5 1689.5,-777.5 "/>
<text text-anchor="middle" x="1597" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_route</text>
<polyline fill="none" stroke="#000000" points="1504.5,-754.5 1689.5,-754.5 "/>
<text text-anchor="middle" x="1597" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_unit</text>
<polyline fill="none" stroke="#000000" points="1504.5,-731.5 1689.5,-731.5 "/>
<text text-anchor="middle" x="1597" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1504.5,-708.5 1689.5,-708.5 "/>
<text text-anchor="middle" x="1597" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="1504.5,-685.5 1689.5,-685.5 "/>
<text text-anchor="middle" x="1597" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1504.5,-662.5 1689.5,-662.5 "/>
<text text-anchor="middle" x="1597" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1689.5,-639.5 1689.5,-869.5 "/>
<text text-anchor="middle" x="1700" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1394.3556,-646.666C1389.7178,-644.0321 1385.0931,-641.4707 1380.5,-639 1330.5183,-612.1139 1271.8199,-590.9555 1219.7954,-575.3188"/>
<polygon fill="#000000" stroke="#000000" points="1220.7449,-571.9498 1210.1625,-572.4632 1218.7553,-578.6611 1220.7449,-571.9498"/>
<text text-anchor="middle" x="1389.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
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
<g id="edge5" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M924.7578,-219.6806C921.6447,-217.4341 918.556,-215.2052 915.5,-213 895.1681,-198.3287 873.5639,-182.7424 852.5945,-167.6159"/>
<polygon fill="#000000" stroke="#000000" points="854.4396,-164.6313 844.2818,-161.6195 850.3444,-170.3084 854.4396,-164.6313"/>
<text text-anchor="middle" x="947" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- survival -->
<g id="node11" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M1741,-662.5C1741,-662.5 2102,-662.5 2102,-662.5 2108,-662.5 2114,-668.5 2114,-674.5 2114,-674.5 2114,-834.5 2114,-834.5 2114,-840.5 2108,-846.5 2102,-846.5 2102,-846.5 1741,-846.5 1741,-846.5 1735,-846.5 1729,-840.5 1729,-834.5 1729,-834.5 1729,-674.5 1729,-674.5 1729,-668.5 1735,-662.5 1741,-662.5"/>
<text text-anchor="middle" x="1766" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="1803,-662.5 1803,-846.5 "/>
<text text-anchor="middle" x="1813.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1824,-662.5 1824,-846.5 "/>
<text text-anchor="middle" x="1958.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="1824,-823.5 2093,-823.5 "/>
<text text-anchor="middle" x="1958.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="1824,-800.5 2093,-800.5 "/>
<text text-anchor="middle" x="1958.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="1824,-777.5 2093,-777.5 "/>
<text text-anchor="middle" x="1958.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="1824,-754.5 2093,-754.5 "/>
<text text-anchor="middle" x="1958.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="1824,-731.5 2093,-731.5 "/>
<text text-anchor="middle" x="1958.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1824,-708.5 2093,-708.5 "/>
<text text-anchor="middle" x="1958.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="1824,-685.5 2093,-685.5 "/>
<text text-anchor="middle" x="1958.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="2093,-662.5 2093,-846.5 "/>
<text text-anchor="middle" x="2103.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1774.6834,-662.4467C1756.5464,-653.5233 1737.9041,-645.4202 1719.5,-639 1553.7457,-581.1771 1351.8692,-557.6078 1220.4246,-548.0251"/>
<polygon fill="#000000" stroke="#000000" points="1220.5199,-544.5232 1210.2967,-547.3043 1220.0229,-551.5055 1220.5199,-544.5232"/>
<text text-anchor="middle" x="1692" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge8" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1002.3191,-495.4401C974.6866,-479.3676 943.6223,-461.077 915.5,-444 887.9722,-427.284 858.3608,-408.8121 831.1476,-391.6347"/>
<polygon fill="#000000" stroke="#000000" points="832.7252,-388.4913 822.4022,-386.1069 828.9852,-394.4084 832.7252,-388.4913"/>
<text text-anchor="middle" x="1021" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
</g>
</svg>
</div>
