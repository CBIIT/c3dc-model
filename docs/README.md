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
<!-- treatment_response -->
<g id="node1" class="node">
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
<!-- participant -->
<g id="node9" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M921,-495.5C921,-495.5 1152,-495.5 1152,-495.5 1158,-495.5 1164,-501.5 1164,-507.5 1164,-507.5 1164,-575.5 1164,-575.5 1164,-581.5 1158,-587.5 1152,-587.5 1152,-587.5 921,-587.5 921,-587.5 915,-587.5 909,-581.5 909,-575.5 909,-575.5 909,-507.5 909,-507.5 909,-501.5 915,-495.5 921,-495.5"/>
<text text-anchor="middle" x="957" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1005,-495.5 1005,-587.5 "/>
<text text-anchor="middle" x="1015.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1026,-495.5 1026,-587.5 "/>
<text text-anchor="middle" x="1084.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1026,-564.5 1143,-564.5 "/>
<text text-anchor="middle" x="1084.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1026,-541.5 1143,-541.5 "/>
<text text-anchor="middle" x="1084.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1026,-518.5 1143,-518.5 "/>
<text text-anchor="middle" x="1084.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="1143,-495.5 1143,-587.5 "/>
<text text-anchor="middle" x="1153.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1986.2313,-685.4565C1955.9461,-668.6122 1922.6185,-651.7827 1890.5,-639 1835.1149,-616.9575 1819.2638,-616.0101 1760.5,-606 1558.228,-571.5442 1320.8308,-554.8373 1174.5266,-547.2329"/>
<polygon fill="#000000" stroke="#000000" points="1174.318,-543.7177 1164.1519,-546.701 1173.9595,-550.7085 1174.318,-543.7177"/>
<text text-anchor="middle" x="1920.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
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
<path fill="none" stroke="#000000" d="M433,-.5C433,-.5 652,-.5 652,-.5 658,-.5 664,-6.5 664,-12.5 664,-12.5 664,-149.5 664,-149.5 664,-155.5 658,-161.5 652,-161.5 652,-161.5 433,-161.5 433,-161.5 427,-161.5 421,-155.5 421,-149.5 421,-149.5 421,-12.5 421,-12.5 421,-6.5 427,-.5 433,-.5"/>
<text text-anchor="middle" x="449" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="477,-.5 477,-161.5 "/>
<text text-anchor="middle" x="487.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="498,-.5 498,-161.5 "/>
<text text-anchor="middle" x="570.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession</text>
<polyline fill="none" stroke="#000000" points="498,-138.5 643,-138.5 "/>
<text text-anchor="middle" x="570.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="498,-115.5 643,-115.5 "/>
<text text-anchor="middle" x="570.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="498,-92.5 643,-92.5 "/>
<text text-anchor="middle" x="570.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="498,-69.5 643,-69.5 "/>
<text text-anchor="middle" x="570.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="498,-46.5 643,-46.5 "/>
<text text-anchor="middle" x="570.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="498,-23.5 643,-23.5 "/>
<text text-anchor="middle" x="570.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
<polyline fill="none" stroke="#000000" points="643,-.5 643,-161.5 "/>
<text text-anchor="middle" x="653.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge14" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M181.7977,-673.9273C211.3504,-562.3549 275.8847,-358.1704 382.5,-213 393.9356,-197.4289 407.605,-182.587 422.0697,-168.8526"/>
<polygon fill="#000000" stroke="#000000" points="424.7492,-171.141 429.6987,-161.7733 419.9877,-166.0098 424.7492,-171.141"/>
<text text-anchor="middle" x="292" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M268.922,-673.8506C289.5783,-660.7699 311.6266,-648.4404 333.5,-639 432.3378,-596.3425 723.7624,-566.494 898.8272,-551.8419"/>
<polygon fill="#000000" stroke="#000000" points="899.213,-555.322 908.8888,-551.0058 898.6333,-548.3461 899.213,-555.322"/>
<text text-anchor="middle" x="489" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- treatment -->
<g id="node3" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M354.5,-639.5C354.5,-639.5 646.5,-639.5 646.5,-639.5 652.5,-639.5 658.5,-645.5 658.5,-651.5 658.5,-651.5 658.5,-857.5 658.5,-857.5 658.5,-863.5 652.5,-869.5 646.5,-869.5 646.5,-869.5 354.5,-869.5 354.5,-869.5 348.5,-869.5 342.5,-863.5 342.5,-857.5 342.5,-857.5 342.5,-651.5 342.5,-651.5 342.5,-645.5 348.5,-639.5 354.5,-639.5"/>
<text text-anchor="middle" x="387" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="431.5,-639.5 431.5,-869.5 "/>
<text text-anchor="middle" x="442" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="452.5,-639.5 452.5,-869.5 "/>
<text text-anchor="middle" x="545" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="452.5,-846.5 637.5,-846.5 "/>
<text text-anchor="middle" x="545" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="452.5,-823.5 637.5,-823.5 "/>
<text text-anchor="middle" x="545" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose</text>
<polyline fill="none" stroke="#000000" points="452.5,-800.5 637.5,-800.5 "/>
<text text-anchor="middle" x="545" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_frequency</text>
<polyline fill="none" stroke="#000000" points="452.5,-777.5 637.5,-777.5 "/>
<text text-anchor="middle" x="545" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_route</text>
<polyline fill="none" stroke="#000000" points="452.5,-754.5 637.5,-754.5 "/>
<text text-anchor="middle" x="545" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_unit</text>
<polyline fill="none" stroke="#000000" points="452.5,-731.5 637.5,-731.5 "/>
<text text-anchor="middle" x="545" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="452.5,-708.5 637.5,-708.5 "/>
<text text-anchor="middle" x="545" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="452.5,-685.5 637.5,-685.5 "/>
<text text-anchor="middle" x="545" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="452.5,-662.5 637.5,-662.5 "/>
<text text-anchor="middle" x="545" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="637.5,-639.5 637.5,-869.5 "/>
<text text-anchor="middle" x="648" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M552.0094,-639.4943C561.8489,-626.601 573.2922,-614.9223 586.5,-606 636.2155,-572.4156 785.5982,-555.9725 898.73,-548.1561"/>
<polygon fill="#000000" stroke="#000000" points="899.1289,-551.6373 908.8705,-547.4717 898.6575,-544.6531 899.1289,-551.6373"/>
<text text-anchor="middle" x="633.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- laboratory_test -->
<g id="node4" class="node">
<title>laboratory_test</title>
<path fill="none" stroke="#000000" d="M650.5,-1094C650.5,-1094 982.5,-1094 982.5,-1094 988.5,-1094 994.5,-1100 994.5,-1106 994.5,-1106 994.5,-1335 994.5,-1335 994.5,-1341 988.5,-1347 982.5,-1347 982.5,-1347 650.5,-1347 650.5,-1347 644.5,-1347 638.5,-1341 638.5,-1335 638.5,-1335 638.5,-1106 638.5,-1106 638.5,-1100 644.5,-1094 650.5,-1094"/>
<text text-anchor="middle" x="701.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="764.5,-1094 764.5,-1347 "/>
<text text-anchor="middle" x="775" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="785.5,-1094 785.5,-1347 "/>
<text text-anchor="middle" x="879.5" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_laboratory_test</text>
<polyline fill="none" stroke="#000000" points="785.5,-1324 973.5,-1324 "/>
<text text-anchor="middle" x="879.5" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="785.5,-1301 973.5,-1301 "/>
<text text-anchor="middle" x="879.5" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_id</text>
<polyline fill="none" stroke="#000000" points="785.5,-1278 973.5,-1278 "/>
<text text-anchor="middle" x="879.5" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_method</text>
<polyline fill="none" stroke="#000000" points="785.5,-1255 973.5,-1255 "/>
<text text-anchor="middle" x="879.5" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_name</text>
<polyline fill="none" stroke="#000000" points="785.5,-1232 973.5,-1232 "/>
<text text-anchor="middle" x="879.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">sensitivity</text>
<polyline fill="none" stroke="#000000" points="785.5,-1209 973.5,-1209 "/>
<text text-anchor="middle" x="879.5" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">specimen</text>
<polyline fill="none" stroke="#000000" points="785.5,-1186 973.5,-1186 "/>
<text text-anchor="middle" x="879.5" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_modifier</text>
<polyline fill="none" stroke="#000000" points="785.5,-1163 973.5,-1163 "/>
<text text-anchor="middle" x="879.5" y="-1147.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_numeric</text>
<polyline fill="none" stroke="#000000" points="785.5,-1140 973.5,-1140 "/>
<text text-anchor="middle" x="879.5" y="-1124.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_text</text>
<polyline fill="none" stroke="#000000" points="785.5,-1117 973.5,-1117 "/>
<text text-anchor="middle" x="879.5" y="-1101.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_unit</text>
<polyline fill="none" stroke="#000000" points="973.5,-1094 973.5,-1347 "/>
<text text-anchor="middle" x="984" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node8" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1384.5,-651C1384.5,-651 1698.5,-651 1698.5,-651 1704.5,-651 1710.5,-657 1710.5,-663 1710.5,-663 1710.5,-846 1710.5,-846 1710.5,-852 1704.5,-858 1698.5,-858 1698.5,-858 1384.5,-858 1384.5,-858 1378.5,-858 1372.5,-852 1372.5,-846 1372.5,-846 1372.5,-663 1372.5,-663 1372.5,-657 1378.5,-651 1384.5,-651"/>
<text text-anchor="middle" x="1406.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1440.5,-651 1440.5,-858 "/>
<text text-anchor="middle" x="1451" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1461.5,-651 1461.5,-858 "/>
<text text-anchor="middle" x="1575.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1461.5,-835 1689.5,-835 "/>
<text text-anchor="middle" x="1575.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1461.5,-812 1689.5,-812 "/>
<text text-anchor="middle" x="1575.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1461.5,-789 1689.5,-789 "/>
<text text-anchor="middle" x="1575.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_necrosis</text>
<polyline fill="none" stroke="#000000" points="1461.5,-766 1689.5,-766 "/>
<text text-anchor="middle" x="1575.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_tumor</text>
<polyline fill="none" stroke="#000000" points="1461.5,-743 1689.5,-743 "/>
<text text-anchor="middle" x="1575.5" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1461.5,-720 1689.5,-720 "/>
<text text-anchor="middle" x="1575.5" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1461.5,-697 1689.5,-697 "/>
<text text-anchor="middle" x="1575.5" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1461.5,-674 1689.5,-674 "/>
<text text-anchor="middle" x="1575.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1689.5,-651 1689.5,-858 "/>
<text text-anchor="middle" x="1700" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge11" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M903.6682,-1093.9948C952.6868,-1032.4203 1019.1346,-962.8324 1094.5,-921 1198.986,-863.0038 1247.3861,-913.9839 1358.5,-870 1364.403,-867.6633 1370.3241,-865.1319 1376.2351,-862.4415"/>
<polygon fill="#000000" stroke="#000000" points="1377.9458,-865.505 1385.5116,-858.0882 1374.9719,-859.1681 1377.9458,-865.505"/>
<text text-anchor="middle" x="1353" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M765.0961,-1093.8299C741.2026,-1028.2235 715.4651,-946.1068 703.5,-870 687.5552,-768.5791 641.9426,-721.1653 703.5,-639 727.7461,-606.6369 818.1498,-581.4025 898.6503,-564.7208"/>
<polygon fill="#000000" stroke="#000000" points="899.8197,-568.0544 908.919,-562.6274 898.4214,-561.1955 899.8197,-568.0544"/>
<text text-anchor="middle" x="769" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- survival -->
<g id="node6" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M856,-662.5C856,-662.5 1217,-662.5 1217,-662.5 1223,-662.5 1229,-668.5 1229,-674.5 1229,-674.5 1229,-834.5 1229,-834.5 1229,-840.5 1223,-846.5 1217,-846.5 1217,-846.5 856,-846.5 856,-846.5 850,-846.5 844,-840.5 844,-834.5 844,-834.5 844,-674.5 844,-674.5 844,-668.5 850,-662.5 856,-662.5"/>
<text text-anchor="middle" x="881" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="918,-662.5 918,-846.5 "/>
<text text-anchor="middle" x="928.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="939,-662.5 939,-846.5 "/>
<text text-anchor="middle" x="1073.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="939,-823.5 1208,-823.5 "/>
<text text-anchor="middle" x="1073.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="939,-800.5 1208,-800.5 "/>
<text text-anchor="middle" x="1073.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="939,-777.5 1208,-777.5 "/>
<text text-anchor="middle" x="1073.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="939,-754.5 1208,-754.5 "/>
<text text-anchor="middle" x="1073.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="939,-731.5 1208,-731.5 "/>
<text text-anchor="middle" x="1073.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="939,-708.5 1208,-708.5 "/>
<text text-anchor="middle" x="1073.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="939,-685.5 1208,-685.5 "/>
<text text-anchor="middle" x="1073.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="1208,-662.5 1208,-846.5 "/>
<text text-anchor="middle" x="1218.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1036.5,-662.3139C1036.5,-640.2929 1036.5,-617.4402 1036.5,-597.6147"/>
<polygon fill="#000000" stroke="#000000" points="1040.0001,-597.5436 1036.5,-587.5436 1033.0001,-597.5437 1040.0001,-597.5436"/>
<text text-anchor="middle" x="1076" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- diagnosis -->
<g id="node7" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1115,-1013.5C1115,-1013.5 1480,-1013.5 1480,-1013.5 1486,-1013.5 1492,-1019.5 1492,-1025.5 1492,-1025.5 1492,-1415.5 1492,-1415.5 1492,-1421.5 1486,-1427.5 1480,-1427.5 1480,-1427.5 1115,-1427.5 1115,-1427.5 1109,-1427.5 1103,-1421.5 1103,-1415.5 1103,-1415.5 1103,-1025.5 1103,-1025.5 1103,-1019.5 1109,-1013.5 1115,-1013.5"/>
<text text-anchor="middle" x="1145" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1187,-1013.5 1187,-1427.5 "/>
<text text-anchor="middle" x="1197.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1208,-1013.5 1208,-1427.5 "/>
<text text-anchor="middle" x="1339.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1208,-1404.5 1471,-1404.5 "/>
<text text-anchor="middle" x="1339.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1208,-1381.5 1471,-1381.5 "/>
<text text-anchor="middle" x="1339.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1208,-1358.5 1471,-1358.5 "/>
<text text-anchor="middle" x="1339.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="1208,-1335.5 1471,-1335.5 "/>
<text text-anchor="middle" x="1339.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_category</text>
<polyline fill="none" stroke="#000000" points="1208,-1312.5 1471,-1312.5 "/>
<text text-anchor="middle" x="1339.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="1208,-1289.5 1471,-1289.5 "/>
<text text-anchor="middle" x="1339.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="1208,-1266.5 1471,-1266.5 "/>
<text text-anchor="middle" x="1339.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1208,-1243.5 1471,-1243.5 "/>
<text text-anchor="middle" x="1339.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="1208,-1220.5 1471,-1220.5 "/>
<text text-anchor="middle" x="1339.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1208,-1197.5 1471,-1197.5 "/>
<text text-anchor="middle" x="1339.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">laterality</text>
<polyline fill="none" stroke="#000000" points="1208,-1174.5 1471,-1174.5 "/>
<text text-anchor="middle" x="1339.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="1208,-1151.5 1471,-1151.5 "/>
<text text-anchor="middle" x="1339.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1208,-1128.5 1471,-1128.5 "/>
<text text-anchor="middle" x="1339.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1208,-1105.5 1471,-1105.5 "/>
<text text-anchor="middle" x="1339.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1208,-1082.5 1471,-1082.5 "/>
<text text-anchor="middle" x="1339.5" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1208,-1059.5 1471,-1059.5 "/>
<text text-anchor="middle" x="1339.5" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1208,-1036.5 1471,-1036.5 "/>
<text text-anchor="middle" x="1339.5" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1471,-1013.5 1471,-1427.5 "/>
<text text-anchor="middle" x="1481.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1405.9429,-1013.3918C1432.2584,-963.1335 1459.4258,-911.2482 1482.4658,-867.2456"/>
<polygon fill="#000000" stroke="#000000" points="1485.6293,-868.749 1487.1674,-858.2664 1479.428,-865.5019 1485.6293,-868.749"/>
<text text-anchor="middle" x="1513" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1281.2456,-1013.1883C1267.8885,-852.5325 1249.4441,-654.6216 1238.5,-639 1222.1108,-615.606 1198.5295,-597.6134 1173.2232,-583.8476"/>
<polygon fill="#000000" stroke="#000000" points="1174.695,-580.668 1164.2091,-579.1529 1171.4615,-586.8764 1174.695,-580.668"/>
<text text-anchor="middle" x="1312" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1380.7045,-650.9672C1373.2585,-646.8218 1365.8338,-642.812 1358.5,-639 1300.9381,-609.0803 1232.7131,-586.7698 1173.9124,-571.0977"/>
<polygon fill="#000000" stroke="#000000" points="1174.7443,-567.6975 1164.1832,-568.5418 1172.9657,-574.4678 1174.7443,-567.6975"/>
<text text-anchor="middle" x="1353" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- consent_group -->
<g id="node12" class="node">
<title>consent_group</title>
<path fill="none" stroke="#000000" d="M798,-271C798,-271 1123,-271 1123,-271 1129,-271 1135,-277 1135,-283 1135,-283 1135,-374 1135,-374 1135,-380 1129,-386 1123,-386 1123,-386 798,-386 798,-386 792,-386 786,-380 786,-374 786,-374 786,-283 786,-283 786,-277 792,-271 798,-271"/>
<text text-anchor="middle" x="847" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
<polyline fill="none" stroke="#000000" points="908,-271 908,-386 "/>
<text text-anchor="middle" x="918.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="929,-271 929,-386 "/>
<text text-anchor="middle" x="1021.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_id</text>
<polyline fill="none" stroke="#000000" points="929,-363 1114,-363 "/>
<text text-anchor="middle" x="1021.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_name</text>
<polyline fill="none" stroke="#000000" points="929,-340 1114,-340 "/>
<text text-anchor="middle" x="1021.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_number</text>
<polyline fill="none" stroke="#000000" points="929,-317 1114,-317 "/>
<text text-anchor="middle" x="1021.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_suffix</text>
<polyline fill="none" stroke="#000000" points="929,-294 1114,-294 "/>
<text text-anchor="middle" x="1021.5" y="-278.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1114,-271 1114,-386 "/>
<text text-anchor="middle" x="1124.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge13" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1020.0091,-495.2822C1009.5987,-466.1056 995.9769,-427.9287 984.3933,-395.4641"/>
<polygon fill="#000000" stroke="#000000" points="987.6846,-394.2734 981.0276,-386.0312 981.0918,-396.6259 987.6846,-394.2734"/>
<text text-anchor="middle" x="1062" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- genetic_analysis -->
<g id="node10" class="node">
<title>genetic_analysis</title>
<path fill="none" stroke="#000000" d="M1538.5,-921.5C1538.5,-921.5 1922.5,-921.5 1922.5,-921.5 1928.5,-921.5 1934.5,-927.5 1934.5,-933.5 1934.5,-933.5 1934.5,-1507.5 1934.5,-1507.5 1934.5,-1513.5 1928.5,-1519.5 1922.5,-1519.5 1922.5,-1519.5 1538.5,-1519.5 1538.5,-1519.5 1532.5,-1519.5 1526.5,-1513.5 1526.5,-1507.5 1526.5,-1507.5 1526.5,-933.5 1526.5,-933.5 1526.5,-927.5 1532.5,-921.5 1538.5,-921.5"/>
<text text-anchor="middle" x="1594" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="1661.5,-921.5 1661.5,-1519.5 "/>
<text text-anchor="middle" x="1672" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1682.5,-921.5 1682.5,-1519.5 "/>
<text text-anchor="middle" x="1798" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="1682.5,-1496.5 1913.5,-1496.5 "/>
<text text-anchor="middle" x="1798" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">allelic_ratio</text>
<polyline fill="none" stroke="#000000" points="1682.5,-1473.5 1913.5,-1473.5 "/>
<text text-anchor="middle" x="1798" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration</text>
<polyline fill="none" stroke="#000000" points="1682.5,-1450.5 1913.5,-1450.5 "/>
<text text-anchor="middle" x="1798" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration_effect</text>
<polyline fill="none" stroke="#000000" points="1682.5,-1427.5 1913.5,-1427.5 "/>
<text text-anchor="middle" x="1798" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration_type</text>
<polyline fill="none" stroke="#000000" points="1682.5,-1404.5 1913.5,-1404.5 "/>
<text text-anchor="middle" x="1798" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="1682.5,-1381.5 1913.5,-1381.5 "/>
<text text-anchor="middle" x="1798" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="1682.5,-1358.5 1913.5,-1358.5 "/>
<text text-anchor="middle" x="1798" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">dna_index_numeric</text>
<polyline fill="none" stroke="#000000" points="1682.5,-1335.5 1913.5,-1335.5 "/>
<text text-anchor="middle" x="1798" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="1682.5,-1312.5 1913.5,-1312.5 "/>
<text text-anchor="middle" x="1798" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_exon</text>
<polyline fill="none" stroke="#000000" points="1682.5,-1289.5 1913.5,-1289.5 "/>
<text text-anchor="middle" x="1798" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_gene</text>
<polyline fill="none" stroke="#000000" points="1682.5,-1266.5 1913.5,-1266.5 "/>
<text text-anchor="middle" x="1798" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_transcript</text>
<polyline fill="none" stroke="#000000" points="1682.5,-1243.5 1913.5,-1243.5 "/>
<text text-anchor="middle" x="1798" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="1682.5,-1220.5 1913.5,-1220.5 "/>
<text text-anchor="middle" x="1798" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis_id</text>
<polyline fill="none" stroke="#000000" points="1682.5,-1197.5 1913.5,-1197.5 "/>
<text text-anchor="middle" x="1798" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_source_category</text>
<polyline fill="none" stroke="#000000" points="1682.5,-1174.5 1913.5,-1174.5 "/>
<text text-anchor="middle" x="1798" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_coding</text>
<polyline fill="none" stroke="#000000" points="1682.5,-1151.5 1913.5,-1151.5 "/>
<text text-anchor="middle" x="1798" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_genome</text>
<polyline fill="none" stroke="#000000" points="1682.5,-1128.5 1913.5,-1128.5 "/>
<text text-anchor="middle" x="1798" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_protein</text>
<polyline fill="none" stroke="#000000" points="1682.5,-1105.5 1913.5,-1105.5 "/>
<text text-anchor="middle" x="1798" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1682.5,-1082.5 1913.5,-1082.5 "/>
<text text-anchor="middle" x="1798" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">iscn</text>
<polyline fill="none" stroke="#000000" points="1682.5,-1059.5 1913.5,-1059.5 "/>
<text text-anchor="middle" x="1798" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">method</text>
<polyline fill="none" stroke="#000000" points="1682.5,-1036.5 1913.5,-1036.5 "/>
<text text-anchor="middle" x="1798" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome</text>
<polyline fill="none" stroke="#000000" points="1682.5,-1013.5 1913.5,-1013.5 "/>
<text text-anchor="middle" x="1798" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance</text>
<polyline fill="none" stroke="#000000" points="1682.5,-990.5 1913.5,-990.5 "/>
<text text-anchor="middle" x="1798" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance_system</text>
<polyline fill="none" stroke="#000000" points="1682.5,-967.5 1913.5,-967.5 "/>
<text text-anchor="middle" x="1798" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">result</text>
<polyline fill="none" stroke="#000000" points="1682.5,-944.5 1913.5,-944.5 "/>
<text text-anchor="middle" x="1798" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 6 properties</text>
<polyline fill="none" stroke="#000000" points="1913.5,-921.5 1913.5,-1519.5 "/>
<text text-anchor="middle" x="1924" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1599.6494,-921.2156C1597.2247,-915.0998 1594.8389,-909.0229 1592.5,-903 1588.1007,-891.6715 1583.687,-879.785 1579.3972,-867.8784"/>
<polygon fill="#000000" stroke="#000000" points="1582.6479,-866.574 1575.9861,-858.3356 1576.0563,-868.9302 1582.6479,-866.574"/>
<text text-anchor="middle" x="1662.5" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1741.7899,-921.4575C1743.6328,-790.5261 1739.9385,-661.3577 1719.5,-639 1683.3004,-599.4011 1363.2166,-567.4725 1174.3498,-551.8745"/>
<polygon fill="#000000" stroke="#000000" points="1174.5931,-548.3828 1164.3403,-551.053 1174.0204,-555.3593 1174.5931,-548.3828"/>
<text text-anchor="middle" x="1811.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- reference_file -->
<g id="node11" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M404,-213.5C404,-213.5 681,-213.5 681,-213.5 687,-213.5 693,-219.5 693,-225.5 693,-225.5 693,-431.5 693,-431.5 693,-437.5 687,-443.5 681,-443.5 681,-443.5 404,-443.5 404,-443.5 398,-443.5 392,-437.5 392,-431.5 392,-431.5 392,-225.5 392,-225.5 392,-219.5 398,-213.5 404,-213.5"/>
<text text-anchor="middle" x="450" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="508,-213.5 508,-443.5 "/>
<text text-anchor="middle" x="518.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="529,-213.5 529,-443.5 "/>
<text text-anchor="middle" x="600.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="529,-420.5 672,-420.5 "/>
<text text-anchor="middle" x="600.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="529,-397.5 672,-397.5 "/>
<text text-anchor="middle" x="600.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="529,-374.5 672,-374.5 "/>
<text text-anchor="middle" x="600.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="529,-351.5 672,-351.5 "/>
<text text-anchor="middle" x="600.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="529,-328.5 672,-328.5 "/>
<text text-anchor="middle" x="600.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="529,-305.5 672,-305.5 "/>
<text text-anchor="middle" x="600.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="529,-282.5 672,-282.5 "/>
<text text-anchor="middle" x="600.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="529,-259.5 672,-259.5 "/>
<text text-anchor="middle" x="600.5" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="529,-236.5 672,-236.5 "/>
<text text-anchor="middle" x="600.5" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="672,-213.5 672,-443.5 "/>
<text text-anchor="middle" x="682.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge7" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M542.5,-213.4448C542.5,-199.4621 542.5,-185.3307 542.5,-171.7693"/>
<polygon fill="#000000" stroke="#000000" points="546.0001,-171.5218 542.5,-161.5218 539.0001,-171.5219 546.0001,-171.5218"/>
<text text-anchor="middle" x="603" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge1" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M863.2885,-270.9406C806.6168,-237.3849 734.4064,-194.6288 672.8521,-158.1821"/>
<polygon fill="#000000" stroke="#000000" points="674.6279,-155.1661 664.2399,-153.0828 671.0614,-161.1895 674.6279,-155.1661"/>
<text text-anchor="middle" x="790" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
</g>
</svg>
</div>
