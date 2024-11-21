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
<svg width="2331pt" height="1223pt"
 viewBox="0.00 0.00 2330.50 1223.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1219)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1219 2326.5,-1219 2326.5,4 -4,4"/>
<!-- treatment -->
<g id="node1" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M1133.5,-564.5C1133.5,-564.5 1425.5,-564.5 1425.5,-564.5 1431.5,-564.5 1437.5,-570.5 1437.5,-576.5 1437.5,-576.5 1437.5,-690.5 1437.5,-690.5 1437.5,-696.5 1431.5,-702.5 1425.5,-702.5 1425.5,-702.5 1133.5,-702.5 1133.5,-702.5 1127.5,-702.5 1121.5,-696.5 1121.5,-690.5 1121.5,-690.5 1121.5,-576.5 1121.5,-576.5 1121.5,-570.5 1127.5,-564.5 1133.5,-564.5"/>
<text text-anchor="middle" x="1166" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1210.5,-564.5 1210.5,-702.5 "/>
<text text-anchor="middle" x="1221" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1231.5,-564.5 1231.5,-702.5 "/>
<text text-anchor="middle" x="1324" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="1231.5,-679.5 1416.5,-679.5 "/>
<text text-anchor="middle" x="1324" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1231.5,-656.5 1416.5,-656.5 "/>
<text text-anchor="middle" x="1324" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1231.5,-633.5 1416.5,-633.5 "/>
<text text-anchor="middle" x="1324" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="1231.5,-610.5 1416.5,-610.5 "/>
<text text-anchor="middle" x="1324" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1231.5,-587.5 1416.5,-587.5 "/>
<text text-anchor="middle" x="1324" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1416.5,-564.5 1416.5,-702.5 "/>
<text text-anchor="middle" x="1427" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node6" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1261,-294C1261,-294 1492,-294 1492,-294 1498,-294 1504,-300 1504,-306 1504,-306 1504,-374 1504,-374 1504,-380 1498,-386 1492,-386 1492,-386 1261,-386 1261,-386 1255,-386 1249,-380 1249,-374 1249,-374 1249,-306 1249,-306 1249,-300 1255,-294 1261,-294"/>
<text text-anchor="middle" x="1297" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1345,-294 1345,-386 "/>
<text text-anchor="middle" x="1355.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1366,-294 1366,-386 "/>
<text text-anchor="middle" x="1424.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1366,-363 1483,-363 "/>
<text text-anchor="middle" x="1424.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1366,-340 1483,-340 "/>
<text text-anchor="middle" x="1424.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1366,-317 1483,-317 "/>
<text text-anchor="middle" x="1424.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="1483,-294 1483,-386 "/>
<text text-anchor="middle" x="1493.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1302.3648,-564.3163C1319.3426,-512.9453 1342.2018,-443.7786 1358.0279,-395.8925"/>
<polygon fill="#000000" stroke="#000000" points="1361.3796,-396.9043 1361.1945,-386.3111 1354.7332,-394.7077 1361.3796,-396.9043"/>
<text text-anchor="middle" x="1380.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- study -->
<g id="node2" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1686,-.5C1686,-.5 1905,-.5 1905,-.5 1911,-.5 1917,-6.5 1917,-12.5 1917,-12.5 1917,-172.5 1917,-172.5 1917,-178.5 1911,-184.5 1905,-184.5 1905,-184.5 1686,-184.5 1686,-184.5 1680,-184.5 1674,-178.5 1674,-172.5 1674,-172.5 1674,-12.5 1674,-12.5 1674,-6.5 1680,-.5 1686,-.5"/>
<text text-anchor="middle" x="1702" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1730,-.5 1730,-184.5 "/>
<text text-anchor="middle" x="1740.5" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1751,-.5 1751,-184.5 "/>
<text text-anchor="middle" x="1823.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="1751,-161.5 1896,-161.5 "/>
<text text-anchor="middle" x="1823.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="1751,-138.5 1896,-138.5 "/>
<text text-anchor="middle" x="1823.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession</text>
<polyline fill="none" stroke="#000000" points="1751,-115.5 1896,-115.5 "/>
<text text-anchor="middle" x="1823.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1751,-92.5 1896,-92.5 "/>
<text text-anchor="middle" x="1823.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1751,-69.5 1896,-69.5 "/>
<text text-anchor="middle" x="1823.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1751,-46.5 1896,-46.5 "/>
<text text-anchor="middle" x="1823.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="1751,-23.5 1896,-23.5 "/>
<text text-anchor="middle" x="1823.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1896,-.5 1896,-184.5 "/>
<text text-anchor="middle" x="1906.5" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- laboratory_test -->
<g id="node3" class="node">
<title>laboratory_test</title>
<path fill="none" stroke="#000000" d="M12,-495.5C12,-495.5 303,-495.5 303,-495.5 309,-495.5 315,-501.5 315,-507.5 315,-507.5 315,-759.5 315,-759.5 315,-765.5 309,-771.5 303,-771.5 303,-771.5 12,-771.5 12,-771.5 6,-771.5 0,-765.5 0,-759.5 0,-759.5 0,-507.5 0,-507.5 0,-501.5 6,-495.5 12,-495.5"/>
<text text-anchor="middle" x="63" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="126,-495.5 126,-771.5 "/>
<text text-anchor="middle" x="136.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="147,-495.5 147,-771.5 "/>
<text text-anchor="middle" x="220.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_lab</text>
<polyline fill="none" stroke="#000000" points="147,-748.5 294,-748.5 "/>
<text text-anchor="middle" x="220.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="147,-725.5 294,-725.5 "/>
<text text-anchor="middle" x="220.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_id</text>
<polyline fill="none" stroke="#000000" points="147,-702.5 294,-702.5 "/>
<text text-anchor="middle" x="220.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">method</text>
<polyline fill="none" stroke="#000000" points="147,-679.5 294,-679.5 "/>
<text text-anchor="middle" x="220.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">result</text>
<polyline fill="none" stroke="#000000" points="147,-656.5 294,-656.5 "/>
<text text-anchor="middle" x="220.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">result_modifier</text>
<polyline fill="none" stroke="#000000" points="147,-633.5 294,-633.5 "/>
<text text-anchor="middle" x="220.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">result_numeric</text>
<polyline fill="none" stroke="#000000" points="147,-610.5 294,-610.5 "/>
<text text-anchor="middle" x="220.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">result_text</text>
<polyline fill="none" stroke="#000000" points="147,-587.5 294,-587.5 "/>
<text text-anchor="middle" x="220.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">result_unit</text>
<polyline fill="none" stroke="#000000" points="147,-564.5 294,-564.5 "/>
<text text-anchor="middle" x="220.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">sensitivity</text>
<polyline fill="none" stroke="#000000" points="147,-541.5 294,-541.5 "/>
<text text-anchor="middle" x="220.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">specimen</text>
<polyline fill="none" stroke="#000000" points="147,-518.5 294,-518.5 "/>
<text text-anchor="middle" x="220.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">test</text>
<polyline fill="none" stroke="#000000" points="294,-495.5 294,-771.5 "/>
<text text-anchor="middle" x="304.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M315.0524,-498.9758C317.8569,-497.5917 320.6736,-496.2647 323.5,-495 484.6622,-422.8863 991.9921,-372.0637 1238.8624,-350.9301"/>
<polygon fill="#000000" stroke="#000000" points="1239.3098,-354.4048 1248.9765,-350.0684 1238.7155,-347.43 1239.3098,-354.4048"/>
<text text-anchor="middle" x="471" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- genetic_analysis -->
<g id="node4" class="node">
<title>genetic_analysis</title>
<path fill="none" stroke="#000000" d="M345,-507C345,-507 688,-507 688,-507 694,-507 700,-513 700,-519 700,-519 700,-748 700,-748 700,-754 694,-760 688,-760 688,-760 345,-760 345,-760 339,-760 333,-754 333,-748 333,-748 333,-519 333,-519 333,-513 339,-507 345,-507"/>
<text text-anchor="middle" x="400.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="468,-507 468,-760 "/>
<text text-anchor="middle" x="478.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="489,-507 489,-760 "/>
<text text-anchor="middle" x="584" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="489,-737 679,-737 "/>
<text text-anchor="middle" x="584" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">allelic_ratio</text>
<polyline fill="none" stroke="#000000" points="489,-714 679,-714 "/>
<text text-anchor="middle" x="584" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">alteration</text>
<polyline fill="none" stroke="#000000" points="489,-691 679,-691 "/>
<text text-anchor="middle" x="584" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">dna_index_numeric</text>
<polyline fill="none" stroke="#000000" points="489,-668 679,-668 "/>
<text text-anchor="middle" x="584" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis_id</text>
<polyline fill="none" stroke="#000000" points="489,-645 679,-645 "/>
<text text-anchor="middle" x="584" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_coding</text>
<polyline fill="none" stroke="#000000" points="489,-622 679,-622 "/>
<text text-anchor="middle" x="584" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_protein</text>
<polyline fill="none" stroke="#000000" points="489,-599 679,-599 "/>
<text text-anchor="middle" x="584" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="489,-576 679,-576 "/>
<text text-anchor="middle" x="584" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">iscn</text>
<polyline fill="none" stroke="#000000" points="489,-553 679,-553 "/>
<text text-anchor="middle" x="584" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="489,-530 679,-530 "/>
<text text-anchor="middle" x="584" y="-514.8" font-family="Times,serif" font-size="14.00" fill="#000000">vaf_numeric</text>
<polyline fill="none" stroke="#000000" points="679,-507 679,-760 "/>
<text text-anchor="middle" x="689.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M684.4128,-506.9679C692.4066,-502.6735 700.4548,-498.6553 708.5,-495 882.0527,-416.1479 1099.8272,-375.2974 1238.6113,-355.7585"/>
<polygon fill="#000000" stroke="#000000" points="1239.4572,-359.1747 1248.8802,-354.3314 1238.4936,-352.2413 1239.4572,-359.1747"/>
<text text-anchor="middle" x="847.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- treatment_response -->
<g id="node5" class="node">
<title>treatment_response</title>
<path fill="none" stroke="#000000" d="M730,-564.5C730,-564.5 1091,-564.5 1091,-564.5 1097,-564.5 1103,-570.5 1103,-576.5 1103,-576.5 1103,-690.5 1103,-690.5 1103,-696.5 1097,-702.5 1091,-702.5 1091,-702.5 730,-702.5 730,-702.5 724,-702.5 718,-696.5 718,-690.5 718,-690.5 718,-576.5 718,-576.5 718,-570.5 724,-564.5 730,-564.5"/>
<text text-anchor="middle" x="798.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
<polyline fill="none" stroke="#000000" points="879,-564.5 879,-702.5 "/>
<text text-anchor="middle" x="889.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="900,-564.5 900,-702.5 "/>
<text text-anchor="middle" x="991" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_response</text>
<polyline fill="none" stroke="#000000" points="900,-679.5 1082,-679.5 "/>
<text text-anchor="middle" x="991" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="900,-656.5 1082,-656.5 "/>
<text text-anchor="middle" x="991" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="900,-633.5 1082,-633.5 "/>
<text text-anchor="middle" x="991" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_category</text>
<polyline fill="none" stroke="#000000" points="900,-610.5 1082,-610.5 "/>
<text text-anchor="middle" x="991" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_system</text>
<polyline fill="none" stroke="#000000" points="900,-587.5 1082,-587.5 "/>
<text text-anchor="middle" x="991" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response_id</text>
<polyline fill="none" stroke="#000000" points="1082,-564.5 1082,-702.5 "/>
<text text-anchor="middle" x="1092.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1007.5744,-564.463C1054.06,-532.2436 1110.9346,-494.0282 1163.5,-462 1202.8345,-438.0334 1246.9235,-412.557 1284.7406,-391.1179"/>
<polygon fill="#000000" stroke="#000000" points="1286.73,-394.0137 1293.7092,-386.0424 1283.2823,-387.9216 1286.73,-394.0137"/>
<text text-anchor="middle" x="1246.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge9" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1454.8192,-293.7375C1513.8776,-258.8521 1596.2087,-210.2198 1665.1397,-169.5028"/>
<polygon fill="#000000" stroke="#000000" points="1667.0778,-172.4231 1673.9078,-164.3236 1663.5176,-166.396 1667.0778,-172.4231"/>
<text text-anchor="middle" x="1649" y="-206.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- reference_file -->
<g id="node7" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M1657,-236.5C1657,-236.5 1934,-236.5 1934,-236.5 1940,-236.5 1946,-242.5 1946,-248.5 1946,-248.5 1946,-431.5 1946,-431.5 1946,-437.5 1940,-443.5 1934,-443.5 1934,-443.5 1657,-443.5 1657,-443.5 1651,-443.5 1645,-437.5 1645,-431.5 1645,-431.5 1645,-248.5 1645,-248.5 1645,-242.5 1651,-236.5 1657,-236.5"/>
<text text-anchor="middle" x="1703" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="1761,-236.5 1761,-443.5 "/>
<text text-anchor="middle" x="1771.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1782,-236.5 1782,-443.5 "/>
<text text-anchor="middle" x="1853.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1782,-420.5 1925,-420.5 "/>
<text text-anchor="middle" x="1853.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="1782,-397.5 1925,-397.5 "/>
<text text-anchor="middle" x="1853.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1782,-374.5 1925,-374.5 "/>
<text text-anchor="middle" x="1853.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1782,-351.5 1925,-351.5 "/>
<text text-anchor="middle" x="1853.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1782,-328.5 1925,-328.5 "/>
<text text-anchor="middle" x="1853.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1782,-305.5 1925,-305.5 "/>
<text text-anchor="middle" x="1853.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1782,-282.5 1925,-282.5 "/>
<text text-anchor="middle" x="1853.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="1782,-259.5 1925,-259.5 "/>
<text text-anchor="middle" x="1853.5" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="1925,-236.5 1925,-443.5 "/>
<text text-anchor="middle" x="1935.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge6" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1795.5,-236.4718C1795.5,-222.7494 1795.5,-208.686 1795.5,-194.9814"/>
<polygon fill="#000000" stroke="#000000" points="1799.0001,-194.5829 1795.5,-184.5829 1792.0001,-194.5829 1799.0001,-194.5829"/>
<text text-anchor="middle" x="1856" y="-206.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- sample -->
<g id="node8" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1996.5,-553C1996.5,-553 2310.5,-553 2310.5,-553 2316.5,-553 2322.5,-559 2322.5,-565 2322.5,-565 2322.5,-702 2322.5,-702 2322.5,-708 2316.5,-714 2310.5,-714 2310.5,-714 1996.5,-714 1996.5,-714 1990.5,-714 1984.5,-708 1984.5,-702 1984.5,-702 1984.5,-565 1984.5,-565 1984.5,-559 1990.5,-553 1996.5,-553"/>
<text text-anchor="middle" x="2018.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="2052.5,-553 2052.5,-714 "/>
<text text-anchor="middle" x="2063" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2073.5,-553 2073.5,-714 "/>
<text text-anchor="middle" x="2187.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="2073.5,-691 2301.5,-691 "/>
<text text-anchor="middle" x="2187.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2073.5,-668 2301.5,-668 "/>
<text text-anchor="middle" x="2187.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="2073.5,-645 2301.5,-645 "/>
<text text-anchor="middle" x="2187.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="2073.5,-622 2301.5,-622 "/>
<text text-anchor="middle" x="2187.5" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="2073.5,-599 2301.5,-599 "/>
<text text-anchor="middle" x="2187.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="2073.5,-576 2301.5,-576 "/>
<text text-anchor="middle" x="2187.5" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="2301.5,-553 2301.5,-714 "/>
<text text-anchor="middle" x="2312" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2123.1252,-552.6442C2089.4529,-468.8334 2029.9354,-336.2946 1955.5,-236 1942.7585,-218.832 1936.2889,-217.4152 1920.5,-203 1916.2519,-199.1215 1911.9107,-195.1798 1907.5163,-191.208"/>
<polygon fill="#000000" stroke="#000000" points="1909.8485,-188.5981 1900.0778,-184.5012 1905.161,-193.797 1909.8485,-188.5981"/>
<text text-anchor="middle" x="2109" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2068.2483,-552.9302C2040.5533,-530.8473 2008.425,-509.1258 1975.5,-495 1835.4804,-434.9272 1783.547,-483.8925 1636.5,-444 1585.5807,-430.1861 1531.1087,-409.3945 1485.2468,-390.0237"/>
<polygon fill="#000000" stroke="#000000" points="1486.4666,-386.7391 1475.8946,-386.0431 1483.7251,-393.1799 1486.4666,-386.7391"/>
<text text-anchor="middle" x="1957" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- diagnosis -->
<g id="node9" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1307,-823.5C1307,-823.5 1672,-823.5 1672,-823.5 1678,-823.5 1684,-829.5 1684,-835.5 1684,-835.5 1684,-1202.5 1684,-1202.5 1684,-1208.5 1678,-1214.5 1672,-1214.5 1672,-1214.5 1307,-1214.5 1307,-1214.5 1301,-1214.5 1295,-1208.5 1295,-1202.5 1295,-1202.5 1295,-835.5 1295,-835.5 1295,-829.5 1301,-823.5 1307,-823.5"/>
<text text-anchor="middle" x="1337" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1379,-823.5 1379,-1214.5 "/>
<text text-anchor="middle" x="1389.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1400,-823.5 1400,-1214.5 "/>
<text text-anchor="middle" x="1531.5" y="-1199.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1400,-1191.5 1663,-1191.5 "/>
<text text-anchor="middle" x="1531.5" y="-1176.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1400,-1168.5 1663,-1168.5 "/>
<text text-anchor="middle" x="1531.5" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1400,-1145.5 1663,-1145.5 "/>
<text text-anchor="middle" x="1531.5" y="-1130.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="1400,-1122.5 1663,-1122.5 "/>
<text text-anchor="middle" x="1531.5" y="-1107.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="1400,-1099.5 1663,-1099.5 "/>
<text text-anchor="middle" x="1531.5" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="1400,-1076.5 1663,-1076.5 "/>
<text text-anchor="middle" x="1531.5" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1400,-1053.5 1663,-1053.5 "/>
<text text-anchor="middle" x="1531.5" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="1400,-1030.5 1663,-1030.5 "/>
<text text-anchor="middle" x="1531.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1400,-1007.5 1663,-1007.5 "/>
<text text-anchor="middle" x="1531.5" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">laterality</text>
<polyline fill="none" stroke="#000000" points="1400,-984.5 1663,-984.5 "/>
<text text-anchor="middle" x="1531.5" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="1400,-961.5 1663,-961.5 "/>
<text text-anchor="middle" x="1531.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1400,-938.5 1663,-938.5 "/>
<text text-anchor="middle" x="1531.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1400,-915.5 1663,-915.5 "/>
<text text-anchor="middle" x="1531.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1400,-892.5 1663,-892.5 "/>
<text text-anchor="middle" x="1531.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1400,-869.5 1663,-869.5 "/>
<text text-anchor="middle" x="1531.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1400,-846.5 1663,-846.5 "/>
<text text-anchor="middle" x="1531.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1663,-823.5 1663,-1214.5 "/>
<text text-anchor="middle" x="1673.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1480.3914,-823.4927C1473.3467,-701.0816 1462.1386,-555.4792 1446.5,-495 1437.5956,-460.564 1421.5715,-424.2154 1407.0999,-395.3792"/>
<polygon fill="#000000" stroke="#000000" points="1410.1274,-393.6116 1402.4668,-386.2927 1403.8912,-396.7913 1410.1274,-393.6116"/>
<text text-anchor="middle" x="1521" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1684.0014,-930.7013C1774.8067,-886.84 1883.0148,-830.7237 1975.5,-772 1999.8943,-756.5108 2025.0163,-738.4421 2048.4194,-720.5684"/>
<polygon fill="#000000" stroke="#000000" points="2050.8294,-723.1303 2056.6216,-714.2589 2046.5613,-717.5819 2050.8294,-723.1303"/>
<text text-anchor="middle" x="1982" y="-793.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- survival -->
<g id="node10" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M1593,-541.5C1593,-541.5 1954,-541.5 1954,-541.5 1960,-541.5 1966,-547.5 1966,-553.5 1966,-553.5 1966,-713.5 1966,-713.5 1966,-719.5 1960,-725.5 1954,-725.5 1954,-725.5 1593,-725.5 1593,-725.5 1587,-725.5 1581,-719.5 1581,-713.5 1581,-713.5 1581,-553.5 1581,-553.5 1581,-547.5 1587,-541.5 1593,-541.5"/>
<text text-anchor="middle" x="1618" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="1655,-541.5 1655,-725.5 "/>
<text text-anchor="middle" x="1665.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1676,-541.5 1676,-725.5 "/>
<text text-anchor="middle" x="1810.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="1676,-702.5 1945,-702.5 "/>
<text text-anchor="middle" x="1810.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="1676,-679.5 1945,-679.5 "/>
<text text-anchor="middle" x="1810.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="1676,-656.5 1945,-656.5 "/>
<text text-anchor="middle" x="1810.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="1676,-633.5 1945,-633.5 "/>
<text text-anchor="middle" x="1810.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="1676,-610.5 1945,-610.5 "/>
<text text-anchor="middle" x="1810.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1676,-587.5 1945,-587.5 "/>
<text text-anchor="middle" x="1810.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="1676,-564.5 1945,-564.5 "/>
<text text-anchor="middle" x="1810.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="1945,-541.5 1945,-725.5 "/>
<text text-anchor="middle" x="1955.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1648.976,-541.44C1582.4376,-492.2486 1502.9581,-433.4898 1447.0617,-392.1659"/>
<polygon fill="#000000" stroke="#000000" points="1449.112,-389.3291 1438.9902,-386.1987 1444.9506,-394.9579 1449.112,-389.3291"/>
<text text-anchor="middle" x="1590" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
</g>
</svg>
</div>
