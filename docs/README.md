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
<svg width="3748pt" height="1735pt"
 viewBox="0.00 0.00 3748.00 1735.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1731)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1731 3744,-1731 3744,4 -4,4"/>
<!-- clinical_measure_file -->
<g id="node1" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M1004.5,-754.5C1004.5,-754.5 1356.5,-754.5 1356.5,-754.5 1362.5,-754.5 1368.5,-760.5 1368.5,-766.5 1368.5,-766.5 1368.5,-995.5 1368.5,-995.5 1368.5,-1001.5 1362.5,-1007.5 1356.5,-1007.5 1356.5,-1007.5 1004.5,-1007.5 1004.5,-1007.5 998.5,-1007.5 992.5,-1001.5 992.5,-995.5 992.5,-995.5 992.5,-766.5 992.5,-766.5 992.5,-760.5 998.5,-754.5 1004.5,-754.5"/>
<text text-anchor="middle" x="1076" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="1159.5,-754.5 1159.5,-1007.5 "/>
<text text-anchor="middle" x="1170" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1180.5,-754.5 1180.5,-1007.5 "/>
<text text-anchor="middle" x="1264" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1180.5,-984.5 1347.5,-984.5 "/>
<text text-anchor="middle" x="1264" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1180.5,-961.5 1347.5,-961.5 "/>
<text text-anchor="middle" x="1264" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1180.5,-938.5 1347.5,-938.5 "/>
<text text-anchor="middle" x="1264" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1180.5,-915.5 1347.5,-915.5 "/>
<text text-anchor="middle" x="1264" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1180.5,-892.5 1347.5,-892.5 "/>
<text text-anchor="middle" x="1264" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1180.5,-869.5 1347.5,-869.5 "/>
<text text-anchor="middle" x="1264" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1180.5,-846.5 1347.5,-846.5 "/>
<text text-anchor="middle" x="1264" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1180.5,-823.5 1347.5,-823.5 "/>
<text text-anchor="middle" x="1264" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1180.5,-800.5 1347.5,-800.5 "/>
<text text-anchor="middle" x="1264" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1180.5,-777.5 1347.5,-777.5 "/>
<text text-anchor="middle" x="1264" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="1347.5,-754.5 1347.5,-1007.5 "/>
<text text-anchor="middle" x="1358" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node7" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M2299.5,-.5C2299.5,-.5 2689.5,-.5 2689.5,-.5 2695.5,-.5 2701.5,-6.5 2701.5,-12.5 2701.5,-12.5 2701.5,-195.5 2701.5,-195.5 2701.5,-201.5 2695.5,-207.5 2689.5,-207.5 2689.5,-207.5 2299.5,-207.5 2299.5,-207.5 2293.5,-207.5 2287.5,-201.5 2287.5,-195.5 2287.5,-195.5 2287.5,-12.5 2287.5,-12.5 2287.5,-6.5 2293.5,-.5 2299.5,-.5"/>
<text text-anchor="middle" x="2315.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="2343.5,-.5 2343.5,-207.5 "/>
<text text-anchor="middle" x="2354" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2364.5,-.5 2364.5,-207.5 "/>
<text text-anchor="middle" x="2522.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="2364.5,-184.5 2680.5,-184.5 "/>
<text text-anchor="middle" x="2522.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="2364.5,-161.5 2680.5,-161.5 "/>
<text text-anchor="middle" x="2522.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="2364.5,-138.5 2680.5,-138.5 "/>
<text text-anchor="middle" x="2522.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="2364.5,-115.5 2680.5,-115.5 "/>
<text text-anchor="middle" x="2522.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="2364.5,-92.5 2680.5,-92.5 "/>
<text text-anchor="middle" x="2522.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="2364.5,-69.5 2680.5,-69.5 "/>
<text text-anchor="middle" x="2522.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="2364.5,-46.5 2680.5,-46.5 "/>
<text text-anchor="middle" x="2522.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="2364.5,-23.5 2680.5,-23.5 "/>
<text text-anchor="middle" x="2522.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="2680.5,-.5 2680.5,-207.5 "/>
<text text-anchor="middle" x="2691" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge11" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1254.5766,-754.4316C1346.0625,-610.1925 1515.6215,-378.9617 1725.5,-259 1817.8944,-206.1895 2084.0739,-160.0922 2277.42,-132.1933"/>
<polygon fill="#000000" stroke="#000000" points="2278.0369,-135.6407 2287.4378,-130.7547 2277.0417,-128.7118 2278.0369,-135.6407"/>
<text text-anchor="middle" x="1559.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- participant -->
<g id="node10" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1789.5,-495.5C1789.5,-495.5 2093.5,-495.5 2093.5,-495.5 2099.5,-495.5 2105.5,-501.5 2105.5,-507.5 2105.5,-507.5 2105.5,-598.5 2105.5,-598.5 2105.5,-604.5 2099.5,-610.5 2093.5,-610.5 2093.5,-610.5 1789.5,-610.5 1789.5,-610.5 1783.5,-610.5 1777.5,-604.5 1777.5,-598.5 1777.5,-598.5 1777.5,-507.5 1777.5,-507.5 1777.5,-501.5 1783.5,-495.5 1789.5,-495.5"/>
<text text-anchor="middle" x="1825.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1873.5,-495.5 1873.5,-610.5 "/>
<text text-anchor="middle" x="1884" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1894.5,-495.5 1894.5,-610.5 "/>
<text text-anchor="middle" x="1989.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="1894.5,-587.5 2084.5,-587.5 "/>
<text text-anchor="middle" x="1989.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1894.5,-564.5 2084.5,-564.5 "/>
<text text-anchor="middle" x="1989.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1894.5,-541.5 2084.5,-541.5 "/>
<text text-anchor="middle" x="1989.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1894.5,-518.5 2084.5,-518.5 "/>
<text text-anchor="middle" x="1989.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="2084.5,-495.5 2084.5,-610.5 "/>
<text text-anchor="middle" x="2095" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1272.4637,-754.4478C1302.601,-720.2989 1338.4759,-686.1614 1377.5,-662 1441.5703,-622.3316 1626.5404,-591.513 1767.3427,-572.9195"/>
<polygon fill="#000000" stroke="#000000" points="1767.9412,-576.3711 1777.4019,-571.6019 1767.032,-569.4304 1767.9412,-576.3711"/>
<text text-anchor="middle" x="1583" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- therapeutic_procedure -->
<g id="node2" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M2292,-823.5C2292,-823.5 2649,-823.5 2649,-823.5 2655,-823.5 2661,-829.5 2661,-835.5 2661,-835.5 2661,-926.5 2661,-926.5 2661,-932.5 2655,-938.5 2649,-938.5 2649,-938.5 2292,-938.5 2292,-938.5 2286,-938.5 2280,-932.5 2280,-926.5 2280,-926.5 2280,-835.5 2280,-835.5 2280,-829.5 2286,-823.5 2292,-823.5"/>
<text text-anchor="middle" x="2370.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="2461,-823.5 2461,-938.5 "/>
<text text-anchor="middle" x="2471.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2482,-823.5 2482,-938.5 "/>
<text text-anchor="middle" x="2561" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment</text>
<polyline fill="none" stroke="#000000" points="2482,-915.5 2640,-915.5 "/>
<text text-anchor="middle" x="2561" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="2482,-892.5 2640,-892.5 "/>
<text text-anchor="middle" x="2561" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="2482,-869.5 2640,-869.5 "/>
<text text-anchor="middle" x="2561" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="2482,-846.5 2640,-846.5 "/>
<text text-anchor="middle" x="2561" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="2640,-823.5 2640,-938.5 "/>
<text text-anchor="middle" x="2650.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge17" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2427.3318,-823.1627C2389.0618,-775.0391 2329.4522,-707.3148 2265.5,-662 2220.9392,-630.4255 2166.5491,-607.4664 2115.1542,-591.0088"/>
<polygon fill="#000000" stroke="#000000" points="2116.1846,-587.6639 2105.5955,-588.0108 2114.0898,-594.3431 2116.1846,-587.6639"/>
<text text-anchor="middle" x="2327.5" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- pdx -->
<g id="node3" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M1784,-1335.5C1784,-1335.5 2113,-1335.5 2113,-1335.5 2119,-1335.5 2125,-1341.5 2125,-1347.5 2125,-1347.5 2125,-1530.5 2125,-1530.5 2125,-1536.5 2119,-1542.5 2113,-1542.5 2113,-1542.5 1784,-1542.5 1784,-1542.5 1778,-1542.5 1772,-1536.5 1772,-1530.5 1772,-1530.5 1772,-1347.5 1772,-1347.5 1772,-1341.5 1778,-1335.5 1784,-1335.5"/>
<text text-anchor="middle" x="1793.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="1815,-1335.5 1815,-1542.5 "/>
<text text-anchor="middle" x="1825.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1836,-1335.5 1836,-1542.5 "/>
<text text-anchor="middle" x="1970" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">injection_type_and_site</text>
<polyline fill="none" stroke="#000000" points="1836,-1519.5 2104,-1519.5 "/>
<text text-anchor="middle" x="1970" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="1836,-1496.5 2104,-1496.5 "/>
<text text-anchor="middle" x="1970" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_type</text>
<polyline fill="none" stroke="#000000" points="1836,-1473.5 2104,-1473.5 "/>
<text text-anchor="middle" x="1970" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="1836,-1450.5 2104,-1450.5 "/>
<text text-anchor="middle" x="1970" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="1836,-1427.5 2104,-1427.5 "/>
<text text-anchor="middle" x="1970" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="1836,-1404.5 2104,-1404.5 "/>
<text text-anchor="middle" x="1970" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="1836,-1381.5 2104,-1381.5 "/>
<text text-anchor="middle" x="1970" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="1836,-1358.5 2104,-1358.5 "/>
<text text-anchor="middle" x="1970" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="2104,-1335.5 2104,-1542.5 "/>
<text text-anchor="middle" x="2114.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node6" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1398.5,-800.5C1398.5,-800.5 1712.5,-800.5 1712.5,-800.5 1718.5,-800.5 1724.5,-806.5 1724.5,-812.5 1724.5,-812.5 1724.5,-949.5 1724.5,-949.5 1724.5,-955.5 1718.5,-961.5 1712.5,-961.5 1712.5,-961.5 1398.5,-961.5 1398.5,-961.5 1392.5,-961.5 1386.5,-955.5 1386.5,-949.5 1386.5,-949.5 1386.5,-812.5 1386.5,-812.5 1386.5,-806.5 1392.5,-800.5 1398.5,-800.5"/>
<text text-anchor="middle" x="1420.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1454.5,-800.5 1454.5,-961.5 "/>
<text text-anchor="middle" x="1465" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1475.5,-800.5 1475.5,-961.5 "/>
<text text-anchor="middle" x="1589.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="1475.5,-938.5 1703.5,-938.5 "/>
<text text-anchor="middle" x="1589.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1475.5,-915.5 1703.5,-915.5 "/>
<text text-anchor="middle" x="1589.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1475.5,-892.5 1703.5,-892.5 "/>
<text text-anchor="middle" x="1589.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1475.5,-869.5 1703.5,-869.5 "/>
<text text-anchor="middle" x="1589.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1475.5,-846.5 1703.5,-846.5 "/>
<text text-anchor="middle" x="1589.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1475.5,-823.5 1703.5,-823.5 "/>
<text text-anchor="middle" x="1589.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="1703.5,-800.5 1703.5,-961.5 "/>
<text text-anchor="middle" x="1714" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1884.4096,-1335.3661C1849.432,-1279.9515 1804.7512,-1210.9706 1762.5,-1151 1718.898,-1089.1122 1667.0682,-1021.5148 1626.1788,-969.4381"/>
<polygon fill="#000000" stroke="#000000" points="1628.9035,-967.2408 1619.9708,-961.5436 1623.4011,-971.5678 1628.9035,-967.2408"/>
<text text-anchor="middle" x="1771.5" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- sample_diagnosis -->
<g id="node4" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M12,-1220.5C12,-1220.5 445,-1220.5 445,-1220.5 451,-1220.5 457,-1226.5 457,-1232.5 457,-1232.5 457,-1645.5 457,-1645.5 457,-1651.5 451,-1657.5 445,-1657.5 445,-1657.5 12,-1657.5 12,-1657.5 6,-1657.5 0,-1651.5 0,-1645.5 0,-1645.5 0,-1232.5 0,-1232.5 0,-1226.5 6,-1220.5 12,-1220.5"/>
<text text-anchor="middle" x="71.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="143,-1220.5 143,-1657.5 "/>
<text text-anchor="middle" x="153.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="164,-1220.5 164,-1657.5 "/>
<text text-anchor="middle" x="300" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="164,-1634.5 436,-1634.5 "/>
<text text-anchor="middle" x="300" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="164,-1611.5 436,-1611.5 "/>
<text text-anchor="middle" x="300" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="164,-1588.5 436,-1588.5 "/>
<text text-anchor="middle" x="300" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="164,-1565.5 436,-1565.5 "/>
<text text-anchor="middle" x="300" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="164,-1542.5 436,-1542.5 "/>
<text text-anchor="middle" x="300" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="164,-1519.5 436,-1519.5 "/>
<text text-anchor="middle" x="300" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="164,-1496.5 436,-1496.5 "/>
<text text-anchor="middle" x="300" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="164,-1473.5 436,-1473.5 "/>
<text text-anchor="middle" x="300" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="164,-1450.5 436,-1450.5 "/>
<text text-anchor="middle" x="300" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="164,-1427.5 436,-1427.5 "/>
<text text-anchor="middle" x="300" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="164,-1404.5 436,-1404.5 "/>
<text text-anchor="middle" x="300" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="164,-1381.5 436,-1381.5 "/>
<text text-anchor="middle" x="300" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="164,-1358.5 436,-1358.5 "/>
<text text-anchor="middle" x="300" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="164,-1335.5 436,-1335.5 "/>
<text text-anchor="middle" x="300" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="164,-1312.5 436,-1312.5 "/>
<text text-anchor="middle" x="300" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="164,-1289.5 436,-1289.5 "/>
<text text-anchor="middle" x="300" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="164,-1266.5 436,-1266.5 "/>
<text text-anchor="middle" x="300" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="164,-1243.5 436,-1243.5 "/>
<text text-anchor="middle" x="300" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="436,-1220.5 436,-1657.5 "/>
<text text-anchor="middle" x="446.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M374.4382,-1220.2323C401.5898,-1192.9114 432.0745,-1168.4769 465.5,-1151 625.5404,-1067.321 690.2113,-1128.5399 870.5,-1118 926.7727,-1114.7102 1327.0382,-1125.1207 1377.5,-1100 1433.3588,-1072.1926 1477.6926,-1017.8539 1508.1441,-970.2628"/>
<polygon fill="#000000" stroke="#000000" points="1511.123,-972.1004 1513.4785,-961.7707 1505.1955,-968.3769 1511.123,-972.1004"/>
<text text-anchor="middle" x="944.5" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- sequencing_file -->
<g id="node5" class="node">
<title>sequencing_file</title>
<path fill="none" stroke="#000000" d="M487,-1151.5C487,-1151.5 956,-1151.5 956,-1151.5 962,-1151.5 968,-1157.5 968,-1163.5 968,-1163.5 968,-1714.5 968,-1714.5 968,-1720.5 962,-1726.5 956,-1726.5 956,-1726.5 487,-1726.5 487,-1726.5 481,-1726.5 475,-1720.5 475,-1714.5 475,-1714.5 475,-1163.5 475,-1163.5 475,-1157.5 481,-1151.5 487,-1151.5"/>
<text text-anchor="middle" x="539" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequencing_file</text>
<polyline fill="none" stroke="#000000" points="603,-1151.5 603,-1726.5 "/>
<text text-anchor="middle" x="613.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="624,-1151.5 624,-1726.5 "/>
<text text-anchor="middle" x="785.5" y="-1711.3" font-family="Times,serif" font-size="14.00" fill="#000000">avg_read_length</text>
<polyline fill="none" stroke="#000000" points="624,-1703.5 947,-1703.5 "/>
<text text-anchor="middle" x="785.5" y="-1688.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="624,-1680.5 947,-1680.5 "/>
<text text-anchor="middle" x="785.5" y="-1665.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="624,-1657.5 947,-1657.5 "/>
<text text-anchor="middle" x="785.5" y="-1642.3" font-family="Times,serif" font-size="14.00" fill="#000000">coverage</text>
<polyline fill="none" stroke="#000000" points="624,-1634.5 947,-1634.5 "/>
<text text-anchor="middle" x="785.5" y="-1619.3" font-family="Times,serif" font-size="14.00" fill="#000000">custom_assembly_fasta_file_for_alignment</text>
<polyline fill="none" stroke="#000000" points="624,-1611.5 947,-1611.5 "/>
<text text-anchor="middle" x="785.5" y="-1596.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="624,-1588.5 947,-1588.5 "/>
<text text-anchor="middle" x="785.5" y="-1573.3" font-family="Times,serif" font-size="14.00" fill="#000000">design_description</text>
<polyline fill="none" stroke="#000000" points="624,-1565.5 947,-1565.5 "/>
<text text-anchor="middle" x="785.5" y="-1550.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="624,-1542.5 947,-1542.5 "/>
<text text-anchor="middle" x="785.5" y="-1527.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="624,-1519.5 947,-1519.5 "/>
<text text-anchor="middle" x="785.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="624,-1496.5 947,-1496.5 "/>
<text text-anchor="middle" x="785.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="624,-1473.5 947,-1473.5 "/>
<text text-anchor="middle" x="785.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="624,-1450.5 947,-1450.5 "/>
<text text-anchor="middle" x="785.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="624,-1427.5 947,-1427.5 "/>
<text text-anchor="middle" x="785.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">instrument_model</text>
<polyline fill="none" stroke="#000000" points="624,-1404.5 947,-1404.5 "/>
<text text-anchor="middle" x="785.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_id</text>
<polyline fill="none" stroke="#000000" points="624,-1381.5 947,-1381.5 "/>
<text text-anchor="middle" x="785.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_layout</text>
<polyline fill="none" stroke="#000000" points="624,-1358.5 947,-1358.5 "/>
<text text-anchor="middle" x="785.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_selection</text>
<polyline fill="none" stroke="#000000" points="624,-1335.5 947,-1335.5 "/>
<text text-anchor="middle" x="785.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_source</text>
<polyline fill="none" stroke="#000000" points="624,-1312.5 947,-1312.5 "/>
<text text-anchor="middle" x="785.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">library_strategy</text>
<polyline fill="none" stroke="#000000" points="624,-1289.5 947,-1289.5 "/>
<text text-anchor="middle" x="785.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="624,-1266.5 947,-1266.5 "/>
<text text-anchor="middle" x="785.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_bp</text>
<polyline fill="none" stroke="#000000" points="624,-1243.5 947,-1243.5 "/>
<text text-anchor="middle" x="785.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_reads</text>
<polyline fill="none" stroke="#000000" points="624,-1220.5 947,-1220.5 "/>
<text text-anchor="middle" x="785.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">platform</text>
<polyline fill="none" stroke="#000000" points="624,-1197.5 947,-1197.5 "/>
<text text-anchor="middle" x="785.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome_assembly</text>
<polyline fill="none" stroke="#000000" points="624,-1174.5 947,-1174.5 "/>
<text text-anchor="middle" x="785.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">sequence_alignment_software</text>
<polyline fill="none" stroke="#000000" points="947,-1151.5 947,-1726.5 "/>
<text text-anchor="middle" x="957.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sequencing_file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>sequencing_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M968.1364,-1155.5788C970.9078,-1154.0098 973.6958,-1152.4829 976.5,-1151 1079.0826,-1096.7553 1120.3842,-1132.6297 1235.5,-1118 1298.6085,-1109.9797 1321.8926,-1130.9003 1377.5,-1100 1431.3246,-1070.0904 1475.2011,-1016.7664 1505.9247,-970.2261"/>
<polygon fill="#000000" stroke="#000000" points="1509.0004,-971.916 1511.5079,-961.6221 1503.1284,-968.1056 1509.0004,-971.916"/>
<text text-anchor="middle" x="1302" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sequencing_file</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge20" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1578.6945,-800.2785C1618.1219,-673.8077 1708.0709,-426.1603 1850.5,-259 1905.7008,-194.2142 2112.3826,-152.5266 2276.909,-128.886"/>
<polygon fill="#000000" stroke="#000000" points="2277.7782,-132.2977 2287.1859,-127.4248 2276.7928,-125.3674 2277.7782,-132.2977"/>
<text text-anchor="middle" x="1753" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge21" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1608.6597,-800.4875C1640.9743,-755.8109 1685.2372,-701.4693 1733.5,-662 1754.5104,-644.8177 1778.6599,-629.2005 1802.8949,-615.4965"/>
<polygon fill="#000000" stroke="#000000" points="1804.7815,-618.4523 1811.8218,-610.5348 1801.3808,-612.3338 1804.7815,-618.4523"/>
<text text-anchor="middle" x="1812" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- methylation_array_file -->
<g id="node8" class="node">
<title>methylation_array_file</title>
<path fill="none" stroke="#000000" d="M998,-1324C998,-1324 1365,-1324 1365,-1324 1371,-1324 1377,-1330 1377,-1336 1377,-1336 1377,-1542 1377,-1542 1377,-1548 1371,-1554 1365,-1554 1365,-1554 998,-1554 998,-1554 992,-1554 986,-1548 986,-1542 986,-1542 986,-1336 986,-1336 986,-1330 992,-1324 998,-1324"/>
<text text-anchor="middle" x="1075" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_array_file</text>
<polyline fill="none" stroke="#000000" points="1164,-1324 1164,-1554 "/>
<text text-anchor="middle" x="1174.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1185,-1324 1185,-1554 "/>
<text text-anchor="middle" x="1270.5" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1185,-1531 1356,-1531 "/>
<text text-anchor="middle" x="1270.5" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1185,-1508 1356,-1508 "/>
<text text-anchor="middle" x="1270.5" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1185,-1485 1356,-1485 "/>
<text text-anchor="middle" x="1270.5" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1185,-1462 1356,-1462 "/>
<text text-anchor="middle" x="1270.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1185,-1439 1356,-1439 "/>
<text text-anchor="middle" x="1270.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1185,-1416 1356,-1416 "/>
<text text-anchor="middle" x="1270.5" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1185,-1393 1356,-1393 "/>
<text text-anchor="middle" x="1270.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1185,-1370 1356,-1370 "/>
<text text-anchor="middle" x="1270.5" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">methylation_platform</text>
<polyline fill="none" stroke="#000000" points="1185,-1347 1356,-1347 "/>
<text text-anchor="middle" x="1270.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">reporter_label</text>
<polyline fill="none" stroke="#000000" points="1356,-1324 1356,-1554 "/>
<text text-anchor="middle" x="1366.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- methylation_array_file&#45;&gt;sample -->
<g id="edge19" class="edge">
<title>methylation_array_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1248.2773,-1323.6677C1285.0145,-1261.7823 1332.2216,-1184.7298 1377.5,-1118 1411.5679,-1067.7919 1452.0146,-1013.5566 1485.7369,-969.6551"/>
<polygon fill="#000000" stroke="#000000" points="1488.6256,-971.6403 1491.9522,-961.5813 1483.0788,-967.3703 1488.6256,-971.6403"/>
<text text-anchor="middle" x="1469" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_methylation_array_file</text>
</g>
<!-- imaging_file -->
<g id="node9" class="node">
<title>imaging_file</title>
<path fill="none" stroke="#000000" d="M1407.5,-1278C1407.5,-1278 1741.5,-1278 1741.5,-1278 1747.5,-1278 1753.5,-1284 1753.5,-1290 1753.5,-1290 1753.5,-1588 1753.5,-1588 1753.5,-1594 1747.5,-1600 1741.5,-1600 1741.5,-1600 1407.5,-1600 1407.5,-1600 1401.5,-1600 1395.5,-1594 1395.5,-1588 1395.5,-1588 1395.5,-1290 1395.5,-1290 1395.5,-1284 1401.5,-1278 1407.5,-1278"/>
<text text-anchor="middle" x="1447.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_file</text>
<polyline fill="none" stroke="#000000" points="1499.5,-1278 1499.5,-1600 "/>
<text text-anchor="middle" x="1510" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1520.5,-1278 1520.5,-1600 "/>
<text text-anchor="middle" x="1626.5" y="-1584.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="1520.5,-1577 1732.5,-1577 "/>
<text text-anchor="middle" x="1626.5" y="-1561.8" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="1520.5,-1554 1732.5,-1554 "/>
<text text-anchor="middle" x="1626.5" y="-1538.8" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1520.5,-1531 1732.5,-1531 "/>
<text text-anchor="middle" x="1626.5" y="-1515.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1520.5,-1508 1732.5,-1508 "/>
<text text-anchor="middle" x="1626.5" y="-1492.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="1520.5,-1485 1732.5,-1485 "/>
<text text-anchor="middle" x="1626.5" y="-1469.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1520.5,-1462 1732.5,-1462 "/>
<text text-anchor="middle" x="1626.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1520.5,-1439 1732.5,-1439 "/>
<text text-anchor="middle" x="1626.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1520.5,-1416 1732.5,-1416 "/>
<text text-anchor="middle" x="1626.5" y="-1400.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="1520.5,-1393 1732.5,-1393 "/>
<text text-anchor="middle" x="1626.5" y="-1377.8" font-family="Times,serif" font-size="14.00" fill="#000000">image_modality</text>
<polyline fill="none" stroke="#000000" points="1520.5,-1370 1732.5,-1370 "/>
<text text-anchor="middle" x="1626.5" y="-1354.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_instrument_model</text>
<polyline fill="none" stroke="#000000" points="1520.5,-1347 1732.5,-1347 "/>
<text text-anchor="middle" x="1626.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">imaging_platform</text>
<polyline fill="none" stroke="#000000" points="1520.5,-1324 1732.5,-1324 "/>
<text text-anchor="middle" x="1626.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1520.5,-1301 1732.5,-1301 "/>
<text text-anchor="middle" x="1626.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">software_package</text>
<polyline fill="none" stroke="#000000" points="1732.5,-1278 1732.5,-1600 "/>
<text text-anchor="middle" x="1743" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- imaging_file&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>imaging_file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1569.0172,-1277.9777C1565.6289,-1178.4707 1561.405,-1054.4213 1558.5894,-971.732"/>
<polygon fill="#000000" stroke="#000000" points="1562.083,-971.4811 1558.2446,-961.606 1555.0871,-971.7193 1562.083,-971.4811"/>
<text text-anchor="middle" x="1619" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_imaging_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge13" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1904.4892,-495.4433C1868.3985,-431.2675 1826.1147,-327.5095 1879.5,-259 1928.714,-195.8434 2120.4907,-154.4214 2276.9694,-130.4219"/>
<polygon fill="#000000" stroke="#000000" points="2277.8616,-133.8266 2287.2234,-128.8662 2276.8116,-126.9058 2277.8616,-133.8266"/>
<text text-anchor="middle" x="1930" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study_arm -->
<g id="node13" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M2002,-317C2002,-317 2299,-317 2299,-317 2305,-317 2311,-323 2311,-329 2311,-329 2311,-374 2311,-374 2311,-380 2305,-386 2299,-386 2299,-386 2002,-386 2002,-386 1996,-386 1990,-380 1990,-374 1990,-374 1990,-329 1990,-329 1990,-323 1996,-317 2002,-317"/>
<text text-anchor="middle" x="2036" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="2082,-317 2082,-386 "/>
<text text-anchor="middle" x="2092.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2103,-317 2103,-386 "/>
<text text-anchor="middle" x="2196.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_arm</text>
<polyline fill="none" stroke="#000000" points="2103,-363 2290,-363 "/>
<text text-anchor="middle" x="2196.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_identifier</text>
<polyline fill="none" stroke="#000000" points="2103,-340 2290,-340 "/>
<text text-anchor="middle" x="2196.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_trial_repository</text>
<polyline fill="none" stroke="#000000" points="2290,-317 2290,-386 "/>
<text text-anchor="middle" x="2300.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study_arm -->
<g id="edge14" class="edge">
<title>participant&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M2001.391,-495.2582C2035.0845,-462.7738 2076.3947,-422.946 2106.9825,-393.4559"/>
<polygon fill="#000000" stroke="#000000" points="2109.747,-395.6524 2114.5168,-386.1919 2104.8885,-390.613 2109.747,-395.6524"/>
<text text-anchor="middle" x="2084" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- synonym -->
<g id="node11" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M2155,-1416C2155,-1416 2456,-1416 2456,-1416 2462,-1416 2468,-1422 2468,-1428 2468,-1428 2468,-1450 2468,-1450 2468,-1456 2462,-1462 2456,-1462 2456,-1462 2155,-1462 2155,-1462 2149,-1462 2143,-1456 2143,-1450 2143,-1450 2143,-1428 2143,-1428 2143,-1422 2149,-1416 2155,-1416"/>
<text text-anchor="middle" x="2183" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="2223,-1416 2223,-1462 "/>
<text text-anchor="middle" x="2233.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2244,-1416 2244,-1462 "/>
<text text-anchor="middle" x="2345.5" y="-1446.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="2244,-1439 2447,-1439 "/>
<text text-anchor="middle" x="2345.5" y="-1423.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="2447,-1416 2447,-1462 "/>
<text text-anchor="middle" x="2457.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2299.2764,-1415.8206C2282.8572,-1359.6111 2232.6579,-1215.9111 2133.5,-1151 2096.0136,-1126.4605 1772.6559,-1121.777 1733.5,-1100 1679.6863,-1070.0709 1635.81,-1016.7465 1605.0837,-970.2109"/>
<polygon fill="#000000" stroke="#000000" points="1607.8801,-968.0905 1599.5001,-961.6078 1602.0084,-971.9015 1607.8801,-968.0905"/>
<text text-anchor="middle" x="2071" y="-1121.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2345.6817,-1415.8445C2424.0095,-1368.2204 2595.8766,-1250.9667 2669.5,-1100 2712.3247,-1012.1869 2688.5,-978.699 2688.5,-881 2688.5,-881 2688.5,-881 2688.5,-351.5 2688.5,-309.4389 2688.0552,-296.2388 2668.5,-259 2660.4812,-243.7299 2650.3076,-229.2471 2638.9192,-215.7129"/>
<polygon fill="#000000" stroke="#000000" points="2641.2857,-213.1006 2632.0807,-207.8549 2636.0053,-217.6961 2641.2857,-213.1006"/>
<text text-anchor="middle" x="2731" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2294.9045,-1415.7722C2270.7756,-1361.7077 2211.7961,-1222.7036 2185.5,-1100 2165.0352,-1004.5067 2203.4332,-743.4186 2149.5,-662 2137.7942,-644.3287 2122.2637,-629.3393 2104.9449,-616.6714"/>
<polygon fill="#000000" stroke="#000000" points="2106.5103,-613.4955 2096.3082,-610.6375 2102.5013,-619.2338 2106.5103,-613.4955"/>
<text text-anchor="middle" x="2228" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study_personnel -->
<g id="node12" class="node">
<title>study_personnel</title>
<path fill="none" stroke="#000000" d="M2341,-294C2341,-294 2648,-294 2648,-294 2654,-294 2660,-300 2660,-306 2660,-306 2660,-397 2660,-397 2660,-403 2654,-409 2648,-409 2648,-409 2341,-409 2341,-409 2335,-409 2329,-403 2329,-397 2329,-397 2329,-306 2329,-306 2329,-300 2335,-294 2341,-294"/>
<text text-anchor="middle" x="2396" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel</text>
<polyline fill="none" stroke="#000000" points="2463,-294 2463,-409 "/>
<text text-anchor="middle" x="2473.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2484,-294 2484,-409 "/>
<text text-anchor="middle" x="2561.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">email_address</text>
<polyline fill="none" stroke="#000000" points="2484,-386 2639,-386 "/>
<text text-anchor="middle" x="2561.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">institution</text>
<polyline fill="none" stroke="#000000" points="2484,-363 2639,-363 "/>
<text text-anchor="middle" x="2561.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_name</text>
<polyline fill="none" stroke="#000000" points="2484,-340 2639,-340 "/>
<text text-anchor="middle" x="2561.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">personnel_type</text>
<polyline fill="none" stroke="#000000" points="2484,-317 2639,-317 "/>
<text text-anchor="middle" x="2561.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_personnel_id</text>
<polyline fill="none" stroke="#000000" points="2639,-294 2639,-409 "/>
<text text-anchor="middle" x="2649.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_personnel&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_personnel&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2494.5,-293.7846C2494.5,-271.1126 2494.5,-244.2586 2494.5,-217.9942"/>
<polygon fill="#000000" stroke="#000000" points="2498.0001,-217.967 2494.5,-207.967 2491.0001,-217.967 2498.0001,-217.967"/>
<text text-anchor="middle" x="2564" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_personnel</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2198.6939,-316.8256C2236.1674,-289.8643 2290.3198,-250.9029 2342.0765,-213.6651"/>
<polygon fill="#000000" stroke="#000000" points="2344.2864,-216.387 2350.3597,-207.7056 2340.1982,-210.7048 2344.2864,-216.387"/>
<text text-anchor="middle" x="2371" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- publication -->
<g id="node14" class="node">
<title>publication</title>
<path fill="none" stroke="#000000" d="M2728.5,-333.5C2728.5,-333.5 2938.5,-333.5 2938.5,-333.5 2944.5,-333.5 2950.5,-339.5 2950.5,-345.5 2950.5,-345.5 2950.5,-357.5 2950.5,-357.5 2950.5,-363.5 2944.5,-369.5 2938.5,-369.5 2938.5,-369.5 2728.5,-369.5 2728.5,-369.5 2722.5,-369.5 2716.5,-363.5 2716.5,-357.5 2716.5,-357.5 2716.5,-345.5 2716.5,-345.5 2716.5,-339.5 2722.5,-333.5 2728.5,-333.5"/>
<text text-anchor="middle" x="2765" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">publication</text>
<polyline fill="none" stroke="#000000" points="2813.5,-333.5 2813.5,-369.5 "/>
<text text-anchor="middle" x="2824" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2834.5,-333.5 2834.5,-369.5 "/>
<text text-anchor="middle" x="2882" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">pubmed_id</text>
<polyline fill="none" stroke="#000000" points="2929.5,-333.5 2929.5,-369.5 "/>
<text text-anchor="middle" x="2940" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- publication&#45;&gt;study -->
<g id="edge1" class="edge">
<title>publication&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2817.2818,-333.4944C2793.6026,-307.8069 2747.4759,-259.9933 2702.5,-226 2696.9463,-221.8024 2691.2364,-217.6354 2685.4141,-213.5127"/>
<polygon fill="#000000" stroke="#000000" points="2687.0117,-210.3595 2676.8085,-207.5057 2683.0051,-216.0995 2687.0117,-210.3595"/>
<text text-anchor="middle" x="2769.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_publication</text>
</g>
<!-- study_admin -->
<g id="node15" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M2980.5,-259.5C2980.5,-259.5 3306.5,-259.5 3306.5,-259.5 3312.5,-259.5 3318.5,-265.5 3318.5,-271.5 3318.5,-271.5 3318.5,-431.5 3318.5,-431.5 3318.5,-437.5 3312.5,-443.5 3306.5,-443.5 3306.5,-443.5 2980.5,-443.5 2980.5,-443.5 2974.5,-443.5 2968.5,-437.5 2968.5,-431.5 2968.5,-431.5 2968.5,-271.5 2968.5,-271.5 2968.5,-265.5 2974.5,-259.5 2980.5,-259.5"/>
<text text-anchor="middle" x="3022.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="3076.5,-259.5 3076.5,-443.5 "/>
<text text-anchor="middle" x="3087" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3097.5,-259.5 3097.5,-443.5 "/>
<text text-anchor="middle" x="3197.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="3097.5,-420.5 3297.5,-420.5 "/>
<text text-anchor="middle" x="3197.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="3097.5,-397.5 3297.5,-397.5 "/>
<text text-anchor="middle" x="3197.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="3097.5,-374.5 3297.5,-374.5 "/>
<text text-anchor="middle" x="3197.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="3097.5,-351.5 3297.5,-351.5 "/>
<text text-anchor="middle" x="3197.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="3097.5,-328.5 3297.5,-328.5 "/>
<text text-anchor="middle" x="3197.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="3097.5,-305.5 3297.5,-305.5 "/>
<text text-anchor="middle" x="3197.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="3097.5,-282.5 3297.5,-282.5 "/>
<text text-anchor="middle" x="3197.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="3297.5,-259.5 3297.5,-443.5 "/>
<text text-anchor="middle" x="3308" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge4" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2968.4652,-262.783C2965.4616,-261.4968 2962.4716,-260.2346 2959.5,-259 2879.8334,-225.8996 2790.3409,-194.7076 2711.2986,-169.1035"/>
<polygon fill="#000000" stroke="#000000" points="2712.3041,-165.7503 2701.7124,-166.009 2710.1537,-172.4118 2712.3041,-165.7503"/>
<text text-anchor="middle" x="2966" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- study_funding -->
<g id="node16" class="node">
<title>study_funding</title>
<path fill="none" stroke="#000000" d="M3349,-317C3349,-317 3728,-317 3728,-317 3734,-317 3740,-323 3740,-329 3740,-329 3740,-374 3740,-374 3740,-380 3734,-386 3728,-386 3728,-386 3349,-386 3349,-386 3343,-386 3337,-380 3337,-374 3337,-374 3337,-329 3337,-329 3337,-323 3343,-317 3349,-317"/>
<text text-anchor="middle" x="3396.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_funding</text>
<polyline fill="none" stroke="#000000" points="3456,-317 3456,-386 "/>
<text text-anchor="middle" x="3466.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3477,-317 3477,-386 "/>
<text text-anchor="middle" x="3598" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_agency</text>
<polyline fill="none" stroke="#000000" points="3477,-363 3719,-363 "/>
<text text-anchor="middle" x="3598" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">funding_source_program_name</text>
<polyline fill="none" stroke="#000000" points="3477,-340 3719,-340 "/>
<text text-anchor="middle" x="3598" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">grant_id</text>
<polyline fill="none" stroke="#000000" points="3719,-317 3719,-386 "/>
<text text-anchor="middle" x="3729.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_funding&#45;&gt;study -->
<g id="edge10" class="edge">
<title>study_funding&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3470.6462,-316.9976C3430.0062,-297.5462 3376.814,-274.177 3327.5,-259 3122.97,-196.0533 2881.8953,-154.5938 2711.8594,-130.5278"/>
<polygon fill="#000000" stroke="#000000" points="2712.1734,-127.0376 2701.7833,-129.1103 2711.1982,-133.9693 2712.1734,-127.0376"/>
<text text-anchor="middle" x="3323.5" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_funding</text>
</g>
<!-- diagnosis -->
<g id="node17" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1754.5,-662.5C1754.5,-662.5 2128.5,-662.5 2128.5,-662.5 2134.5,-662.5 2140.5,-668.5 2140.5,-674.5 2140.5,-674.5 2140.5,-1087.5 2140.5,-1087.5 2140.5,-1093.5 2134.5,-1099.5 2128.5,-1099.5 2128.5,-1099.5 1754.5,-1099.5 1754.5,-1099.5 1748.5,-1099.5 1742.5,-1093.5 1742.5,-1087.5 1742.5,-1087.5 1742.5,-674.5 1742.5,-674.5 1742.5,-668.5 1748.5,-662.5 1754.5,-662.5"/>
<text text-anchor="middle" x="1784.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1826.5,-662.5 1826.5,-1099.5 "/>
<text text-anchor="middle" x="1837" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1847.5,-662.5 1847.5,-1099.5 "/>
<text text-anchor="middle" x="1983.5" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1847.5,-1076.5 2119.5,-1076.5 "/>
<text text-anchor="middle" x="1983.5" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="1847.5,-1053.5 2119.5,-1053.5 "/>
<text text-anchor="middle" x="1983.5" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1847.5,-1030.5 2119.5,-1030.5 "/>
<text text-anchor="middle" x="1983.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="1847.5,-1007.5 2119.5,-1007.5 "/>
<text text-anchor="middle" x="1983.5" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="1847.5,-984.5 2119.5,-984.5 "/>
<text text-anchor="middle" x="1983.5" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="1847.5,-961.5 2119.5,-961.5 "/>
<text text-anchor="middle" x="1983.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="1847.5,-938.5 2119.5,-938.5 "/>
<text text-anchor="middle" x="1983.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1847.5,-915.5 2119.5,-915.5 "/>
<text text-anchor="middle" x="1983.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="1847.5,-892.5 2119.5,-892.5 "/>
<text text-anchor="middle" x="1983.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_site</text>
<polyline fill="none" stroke="#000000" points="1847.5,-869.5 2119.5,-869.5 "/>
<text text-anchor="middle" x="1983.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">progression_or_recurrence</text>
<polyline fill="none" stroke="#000000" points="1847.5,-846.5 2119.5,-846.5 "/>
<text text-anchor="middle" x="1983.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">site_of_resection_or_biopsy</text>
<polyline fill="none" stroke="#000000" points="1847.5,-823.5 2119.5,-823.5 "/>
<text text-anchor="middle" x="1983.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tissue_or_organ_of_origin</text>
<polyline fill="none" stroke="#000000" points="1847.5,-800.5 2119.5,-800.5 "/>
<text text-anchor="middle" x="1983.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1847.5,-777.5 2119.5,-777.5 "/>
<text text-anchor="middle" x="1983.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_incidence_type</text>
<polyline fill="none" stroke="#000000" points="1847.5,-754.5 2119.5,-754.5 "/>
<text text-anchor="middle" x="1983.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_morphology</text>
<polyline fill="none" stroke="#000000" points="1847.5,-731.5 2119.5,-731.5 "/>
<text text-anchor="middle" x="1983.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1847.5,-708.5 2119.5,-708.5 "/>
<text text-anchor="middle" x="1983.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1847.5,-685.5 2119.5,-685.5 "/>
<text text-anchor="middle" x="1983.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="2119.5,-662.5 2119.5,-1099.5 "/>
<text text-anchor="middle" x="2130" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1941.5,-662.2193C1941.5,-647.476 1941.5,-633.4001 1941.5,-620.5497"/>
<polygon fill="#000000" stroke="#000000" points="1945.0001,-620.5173 1941.5,-610.5174 1938.0001,-620.5174 1945.0001,-620.5173"/>
<text text-anchor="middle" x="1986" y="-632.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
</g>
</svg>
</div>
