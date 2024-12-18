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
<!-- treatment_response -->
<g id="node1" class="node">
<title>treatment_response</title>
<path fill="none" stroke="#000000" d="M1949.5,-564.5C1949.5,-564.5 2310.5,-564.5 2310.5,-564.5 2316.5,-564.5 2322.5,-570.5 2322.5,-576.5 2322.5,-576.5 2322.5,-690.5 2322.5,-690.5 2322.5,-696.5 2316.5,-702.5 2310.5,-702.5 2310.5,-702.5 1949.5,-702.5 1949.5,-702.5 1943.5,-702.5 1937.5,-696.5 1937.5,-690.5 1937.5,-690.5 1937.5,-576.5 1937.5,-576.5 1937.5,-570.5 1943.5,-564.5 1949.5,-564.5"/>
<text text-anchor="middle" x="2018" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
<polyline fill="none" stroke="#000000" points="2098.5,-564.5 2098.5,-702.5 "/>
<text text-anchor="middle" x="2109" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2119.5,-564.5 2119.5,-702.5 "/>
<text text-anchor="middle" x="2210.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_response</text>
<polyline fill="none" stroke="#000000" points="2119.5,-679.5 2301.5,-679.5 "/>
<text text-anchor="middle" x="2210.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2119.5,-656.5 2301.5,-656.5 "/>
<text text-anchor="middle" x="2210.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="2119.5,-633.5 2301.5,-633.5 "/>
<text text-anchor="middle" x="2210.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_category</text>
<polyline fill="none" stroke="#000000" points="2119.5,-610.5 2301.5,-610.5 "/>
<text text-anchor="middle" x="2210.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_system</text>
<polyline fill="none" stroke="#000000" points="2119.5,-587.5 2301.5,-587.5 "/>
<text text-anchor="middle" x="2210.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response_id</text>
<polyline fill="none" stroke="#000000" points="2301.5,-564.5 2301.5,-702.5 "/>
<text text-anchor="middle" x="2312" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node3" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M963.5,-294C963.5,-294 1194.5,-294 1194.5,-294 1200.5,-294 1206.5,-300 1206.5,-306 1206.5,-306 1206.5,-374 1206.5,-374 1206.5,-380 1200.5,-386 1194.5,-386 1194.5,-386 963.5,-386 963.5,-386 957.5,-386 951.5,-380 951.5,-374 951.5,-374 951.5,-306 951.5,-306 951.5,-300 957.5,-294 963.5,-294"/>
<text text-anchor="middle" x="999.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1047.5,-294 1047.5,-386 "/>
<text text-anchor="middle" x="1058" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1068.5,-294 1068.5,-386 "/>
<text text-anchor="middle" x="1127" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1068.5,-363 1185.5,-363 "/>
<text text-anchor="middle" x="1127" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1068.5,-340 1185.5,-340 "/>
<text text-anchor="middle" x="1127" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1068.5,-317 1185.5,-317 "/>
<text text-anchor="middle" x="1127" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="1185.5,-294 1185.5,-386 "/>
<text text-anchor="middle" x="1196" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2048.6079,-564.3915C2013.6377,-538.3771 1970.9717,-511.1964 1928,-495 1813.2241,-451.7399 1776.2614,-471.8535 1654,-462 1605.339,-458.0782 1260.9105,-460.5982 1215,-444 1184.6123,-433.0138 1155.5082,-412.604 1132.0773,-392.7552"/>
<polygon fill="#000000" stroke="#000000" points="1134.2034,-389.9662 1124.355,-386.0598 1129.6178,-395.2551 1134.2034,-389.9662"/>
<text text-anchor="middle" x="1950" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- laboratory_test -->
<g id="node2" class="node">
<title>laboratory_test</title>
<path fill="none" stroke="#000000" d="M368.5,-495.5C368.5,-495.5 659.5,-495.5 659.5,-495.5 665.5,-495.5 671.5,-501.5 671.5,-507.5 671.5,-507.5 671.5,-759.5 671.5,-759.5 671.5,-765.5 665.5,-771.5 659.5,-771.5 659.5,-771.5 368.5,-771.5 368.5,-771.5 362.5,-771.5 356.5,-765.5 356.5,-759.5 356.5,-759.5 356.5,-507.5 356.5,-507.5 356.5,-501.5 362.5,-495.5 368.5,-495.5"/>
<text text-anchor="middle" x="419.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="482.5,-495.5 482.5,-771.5 "/>
<text text-anchor="middle" x="493" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="503.5,-495.5 503.5,-771.5 "/>
<text text-anchor="middle" x="577" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_lab</text>
<polyline fill="none" stroke="#000000" points="503.5,-748.5 650.5,-748.5 "/>
<text text-anchor="middle" x="577" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="503.5,-725.5 650.5,-725.5 "/>
<text text-anchor="middle" x="577" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_id</text>
<polyline fill="none" stroke="#000000" points="503.5,-702.5 650.5,-702.5 "/>
<text text-anchor="middle" x="577" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">method</text>
<polyline fill="none" stroke="#000000" points="503.5,-679.5 650.5,-679.5 "/>
<text text-anchor="middle" x="577" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">result</text>
<polyline fill="none" stroke="#000000" points="503.5,-656.5 650.5,-656.5 "/>
<text text-anchor="middle" x="577" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">result_modifier</text>
<polyline fill="none" stroke="#000000" points="503.5,-633.5 650.5,-633.5 "/>
<text text-anchor="middle" x="577" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">result_numeric</text>
<polyline fill="none" stroke="#000000" points="503.5,-610.5 650.5,-610.5 "/>
<text text-anchor="middle" x="577" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">result_text</text>
<polyline fill="none" stroke="#000000" points="503.5,-587.5 650.5,-587.5 "/>
<text text-anchor="middle" x="577" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">result_unit</text>
<polyline fill="none" stroke="#000000" points="503.5,-564.5 650.5,-564.5 "/>
<text text-anchor="middle" x="577" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">sensitivity</text>
<polyline fill="none" stroke="#000000" points="503.5,-541.5 650.5,-541.5 "/>
<text text-anchor="middle" x="577" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">specimen</text>
<polyline fill="none" stroke="#000000" points="503.5,-518.5 650.5,-518.5 "/>
<text text-anchor="middle" x="577" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">test</text>
<polyline fill="none" stroke="#000000" points="650.5,-495.5 650.5,-771.5 "/>
<text text-anchor="middle" x="661" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M671.7578,-499.993C674.5037,-498.2868 677.2521,-496.6209 680,-495 762.1132,-446.5648 862.1253,-407.7498 941.4775,-381.0763"/>
<polygon fill="#000000" stroke="#000000" points="942.6707,-384.3679 951.0496,-377.8838 940.4559,-377.7275 942.6707,-384.3679"/>
<text text-anchor="middle" x="796.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- study -->
<g id="node9" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M969.5,-.5C969.5,-.5 1188.5,-.5 1188.5,-.5 1194.5,-.5 1200.5,-6.5 1200.5,-12.5 1200.5,-12.5 1200.5,-172.5 1200.5,-172.5 1200.5,-178.5 1194.5,-184.5 1188.5,-184.5 1188.5,-184.5 969.5,-184.5 969.5,-184.5 963.5,-184.5 957.5,-178.5 957.5,-172.5 957.5,-172.5 957.5,-12.5 957.5,-12.5 957.5,-6.5 963.5,-.5 969.5,-.5"/>
<text text-anchor="middle" x="985.5" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1013.5,-.5 1013.5,-184.5 "/>
<text text-anchor="middle" x="1024" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1034.5,-.5 1034.5,-184.5 "/>
<text text-anchor="middle" x="1107" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="1034.5,-161.5 1179.5,-161.5 "/>
<text text-anchor="middle" x="1107" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="1034.5,-138.5 1179.5,-138.5 "/>
<text text-anchor="middle" x="1107" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession</text>
<polyline fill="none" stroke="#000000" points="1034.5,-115.5 1179.5,-115.5 "/>
<text text-anchor="middle" x="1107" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1034.5,-92.5 1179.5,-92.5 "/>
<text text-anchor="middle" x="1107" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1034.5,-69.5 1179.5,-69.5 "/>
<text text-anchor="middle" x="1107" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1034.5,-46.5 1179.5,-46.5 "/>
<text text-anchor="middle" x="1107" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="1034.5,-23.5 1179.5,-23.5 "/>
<text text-anchor="middle" x="1107" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1179.5,-.5 1179.5,-184.5 "/>
<text text-anchor="middle" x="1190" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge4" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1079,-293.7375C1079,-265.8494 1079,-229.176 1079,-194.7844"/>
<polygon fill="#000000" stroke="#000000" points="1082.5001,-194.677 1079,-184.677 1075.5001,-194.6771 1082.5001,-194.677"/>
<text text-anchor="middle" x="1129.5" y="-206.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample -->
<g id="node4" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M12,-553C12,-553 326,-553 326,-553 332,-553 338,-559 338,-565 338,-565 338,-702 338,-702 338,-708 332,-714 326,-714 326,-714 12,-714 12,-714 6,-714 0,-708 0,-702 0,-702 0,-565 0,-565 0,-559 6,-553 12,-553"/>
<text text-anchor="middle" x="34" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="68,-553 68,-714 "/>
<text text-anchor="middle" x="78.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="89,-553 89,-714 "/>
<text text-anchor="middle" x="203" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="89,-691 317,-691 "/>
<text text-anchor="middle" x="203" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="89,-668 317,-668 "/>
<text text-anchor="middle" x="203" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="89,-645 317,-645 "/>
<text text-anchor="middle" x="203" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="89,-622 317,-622 "/>
<text text-anchor="middle" x="203" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="89,-599 317,-599 "/>
<text text-anchor="middle" x="203" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="89,-576 317,-576 "/>
<text text-anchor="middle" x="203" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="317,-553 317,-714 "/>
<text text-anchor="middle" x="327.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M256.6123,-552.6875C283.9033,-531.1363 315.2188,-509.7664 347,-495 541.4765,-404.6407 789.526,-366.3639 941.1855,-350.573"/>
<polygon fill="#000000" stroke="#000000" points="941.8931,-354.019 951.4851,-349.5198 941.1809,-347.0553 941.8931,-354.019"/>
<text text-anchor="middle" x="458.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M269.3953,-552.6901C294.3972,-533.3179 321.3855,-513.0309 347,-495 545.4886,-355.2773 797.3256,-226.2076 947.9108,-153.5848"/>
<polygon fill="#000000" stroke="#000000" points="949.7415,-156.5881 957.2347,-149.0979 946.7061,-150.2804 949.7415,-156.5881"/>
<text text-anchor="middle" x="814.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- survival -->
<g id="node5" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M701.5,-541.5C701.5,-541.5 1062.5,-541.5 1062.5,-541.5 1068.5,-541.5 1074.5,-547.5 1074.5,-553.5 1074.5,-553.5 1074.5,-713.5 1074.5,-713.5 1074.5,-719.5 1068.5,-725.5 1062.5,-725.5 1062.5,-725.5 701.5,-725.5 701.5,-725.5 695.5,-725.5 689.5,-719.5 689.5,-713.5 689.5,-713.5 689.5,-553.5 689.5,-553.5 689.5,-547.5 695.5,-541.5 701.5,-541.5"/>
<text text-anchor="middle" x="726.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="763.5,-541.5 763.5,-725.5 "/>
<text text-anchor="middle" x="774" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="784.5,-541.5 784.5,-725.5 "/>
<text text-anchor="middle" x="919" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="784.5,-702.5 1053.5,-702.5 "/>
<text text-anchor="middle" x="919" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="784.5,-679.5 1053.5,-679.5 "/>
<text text-anchor="middle" x="919" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="784.5,-656.5 1053.5,-656.5 "/>
<text text-anchor="middle" x="919" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="784.5,-633.5 1053.5,-633.5 "/>
<text text-anchor="middle" x="919" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="784.5,-610.5 1053.5,-610.5 "/>
<text text-anchor="middle" x="919" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="784.5,-587.5 1053.5,-587.5 "/>
<text text-anchor="middle" x="919" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="784.5,-564.5 1053.5,-564.5 "/>
<text text-anchor="middle" x="919" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="1053.5,-541.5 1053.5,-725.5 "/>
<text text-anchor="middle" x="1064" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M943.7915,-541.44C976.1327,-493.2566 1014.6351,-435.8939 1042.266,-394.728"/>
<polygon fill="#000000" stroke="#000000" points="1045.324,-396.4523 1047.991,-386.1987 1039.5118,-392.5511 1045.324,-396.4523"/>
<text text-anchor="middle" x="1032.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- reference_file -->
<g id="node6" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M1236.5,-236.5C1236.5,-236.5 1513.5,-236.5 1513.5,-236.5 1519.5,-236.5 1525.5,-242.5 1525.5,-248.5 1525.5,-248.5 1525.5,-431.5 1525.5,-431.5 1525.5,-437.5 1519.5,-443.5 1513.5,-443.5 1513.5,-443.5 1236.5,-443.5 1236.5,-443.5 1230.5,-443.5 1224.5,-437.5 1224.5,-431.5 1224.5,-431.5 1224.5,-248.5 1224.5,-248.5 1224.5,-242.5 1230.5,-236.5 1236.5,-236.5"/>
<text text-anchor="middle" x="1282.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="1340.5,-236.5 1340.5,-443.5 "/>
<text text-anchor="middle" x="1351" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1361.5,-236.5 1361.5,-443.5 "/>
<text text-anchor="middle" x="1433" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1361.5,-420.5 1504.5,-420.5 "/>
<text text-anchor="middle" x="1433" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="1361.5,-397.5 1504.5,-397.5 "/>
<text text-anchor="middle" x="1433" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1361.5,-374.5 1504.5,-374.5 "/>
<text text-anchor="middle" x="1433" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1361.5,-351.5 1504.5,-351.5 "/>
<text text-anchor="middle" x="1433" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1361.5,-328.5 1504.5,-328.5 "/>
<text text-anchor="middle" x="1433" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1361.5,-305.5 1504.5,-305.5 "/>
<text text-anchor="middle" x="1433" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1361.5,-282.5 1504.5,-282.5 "/>
<text text-anchor="middle" x="1433" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="1361.5,-259.5 1504.5,-259.5 "/>
<text text-anchor="middle" x="1433" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="1504.5,-236.5 1504.5,-443.5 "/>
<text text-anchor="middle" x="1515" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge3" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1251.1844,-236.4718C1233.3249,-221.5386 1214.9825,-206.2016 1197.2356,-191.3625"/>
<polygon fill="#000000" stroke="#000000" points="1199.0442,-188.3125 1189.1274,-184.5829 1194.5539,-193.6826 1199.0442,-188.3125"/>
<text text-anchor="middle" x="1287.5" y="-206.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- genetic_analysis -->
<g id="node7" class="node">
<title>genetic_analysis</title>
<path fill="none" stroke="#000000" d="M1104.5,-507C1104.5,-507 1447.5,-507 1447.5,-507 1453.5,-507 1459.5,-513 1459.5,-519 1459.5,-519 1459.5,-748 1459.5,-748 1459.5,-754 1453.5,-760 1447.5,-760 1447.5,-760 1104.5,-760 1104.5,-760 1098.5,-760 1092.5,-754 1092.5,-748 1092.5,-748 1092.5,-519 1092.5,-519 1092.5,-513 1098.5,-507 1104.5,-507"/>
<text text-anchor="middle" x="1160" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="1227.5,-507 1227.5,-760 "/>
<text text-anchor="middle" x="1238" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1248.5,-507 1248.5,-760 "/>
<text text-anchor="middle" x="1343.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="1248.5,-737 1438.5,-737 "/>
<text text-anchor="middle" x="1343.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">allelic_ratio</text>
<polyline fill="none" stroke="#000000" points="1248.5,-714 1438.5,-714 "/>
<text text-anchor="middle" x="1343.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">alteration</text>
<polyline fill="none" stroke="#000000" points="1248.5,-691 1438.5,-691 "/>
<text text-anchor="middle" x="1343.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">dna_index_numeric</text>
<polyline fill="none" stroke="#000000" points="1248.5,-668 1438.5,-668 "/>
<text text-anchor="middle" x="1343.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis_id</text>
<polyline fill="none" stroke="#000000" points="1248.5,-645 1438.5,-645 "/>
<text text-anchor="middle" x="1343.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_coding</text>
<polyline fill="none" stroke="#000000" points="1248.5,-622 1438.5,-622 "/>
<text text-anchor="middle" x="1343.5" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_protein</text>
<polyline fill="none" stroke="#000000" points="1248.5,-599 1438.5,-599 "/>
<text text-anchor="middle" x="1343.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1248.5,-576 1438.5,-576 "/>
<text text-anchor="middle" x="1343.5" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">iscn</text>
<polyline fill="none" stroke="#000000" points="1248.5,-553 1438.5,-553 "/>
<text text-anchor="middle" x="1343.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="1248.5,-530 1438.5,-530 "/>
<text text-anchor="middle" x="1343.5" y="-514.8" font-family="Times,serif" font-size="14.00" fill="#000000">vaf_numeric</text>
<polyline fill="none" stroke="#000000" points="1438.5,-507 1438.5,-760 "/>
<text text-anchor="middle" x="1449" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1191.0249,-506.9C1164.658,-467.6174 1136.9732,-426.3713 1115.7221,-394.7103"/>
<polygon fill="#000000" stroke="#000000" points="1118.3844,-392.3965 1109.9052,-386.044 1112.5723,-396.2977 1118.3844,-392.3965"/>
<text text-anchor="middle" x="1236" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- diagnosis -->
<g id="node8" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M650.5,-823.5C650.5,-823.5 1015.5,-823.5 1015.5,-823.5 1021.5,-823.5 1027.5,-829.5 1027.5,-835.5 1027.5,-835.5 1027.5,-1202.5 1027.5,-1202.5 1027.5,-1208.5 1021.5,-1214.5 1015.5,-1214.5 1015.5,-1214.5 650.5,-1214.5 650.5,-1214.5 644.5,-1214.5 638.5,-1208.5 638.5,-1202.5 638.5,-1202.5 638.5,-835.5 638.5,-835.5 638.5,-829.5 644.5,-823.5 650.5,-823.5"/>
<text text-anchor="middle" x="680.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="722.5,-823.5 722.5,-1214.5 "/>
<text text-anchor="middle" x="733" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="743.5,-823.5 743.5,-1214.5 "/>
<text text-anchor="middle" x="875" y="-1199.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="743.5,-1191.5 1006.5,-1191.5 "/>
<text text-anchor="middle" x="875" y="-1176.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="743.5,-1168.5 1006.5,-1168.5 "/>
<text text-anchor="middle" x="875" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="743.5,-1145.5 1006.5,-1145.5 "/>
<text text-anchor="middle" x="875" y="-1130.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="743.5,-1122.5 1006.5,-1122.5 "/>
<text text-anchor="middle" x="875" y="-1107.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="743.5,-1099.5 1006.5,-1099.5 "/>
<text text-anchor="middle" x="875" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="743.5,-1076.5 1006.5,-1076.5 "/>
<text text-anchor="middle" x="875" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="743.5,-1053.5 1006.5,-1053.5 "/>
<text text-anchor="middle" x="875" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="743.5,-1030.5 1006.5,-1030.5 "/>
<text text-anchor="middle" x="875" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="743.5,-1007.5 1006.5,-1007.5 "/>
<text text-anchor="middle" x="875" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">laterality</text>
<polyline fill="none" stroke="#000000" points="743.5,-984.5 1006.5,-984.5 "/>
<text text-anchor="middle" x="875" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="743.5,-961.5 1006.5,-961.5 "/>
<text text-anchor="middle" x="875" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="743.5,-938.5 1006.5,-938.5 "/>
<text text-anchor="middle" x="875" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="743.5,-915.5 1006.5,-915.5 "/>
<text text-anchor="middle" x="875" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="743.5,-892.5 1006.5,-892.5 "/>
<text text-anchor="middle" x="875" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="743.5,-869.5 1006.5,-869.5 "/>
<text text-anchor="middle" x="875" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="743.5,-846.5 1006.5,-846.5 "/>
<text text-anchor="middle" x="875" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1006.5,-823.5 1006.5,-1214.5 "/>
<text text-anchor="middle" x="1017" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1027.6641,-969.3721C1194.9362,-922.3247 1417.1523,-847.7562 1469,-772 1503.766,-721.2023 1507.8528,-542.7446 1469,-495 1396.3243,-405.6919 1320.1325,-490.9556 1215,-444 1186.5956,-431.3137 1158.6852,-411.6178 1135.6122,-392.7641"/>
<polygon fill="#000000" stroke="#000000" points="1137.5845,-389.8519 1127.66,-386.1433 1133.1057,-395.2315 1137.5845,-389.8519"/>
<text text-anchor="middle" x="1540.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge9" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M638.4986,-930.7013C547.6933,-886.84 439.4852,-830.7237 347,-772 322.6057,-756.5108 297.4837,-738.4421 274.0806,-720.5684"/>
<polygon fill="#000000" stroke="#000000" points="275.9387,-717.5819 265.8784,-714.2589 271.6706,-723.1303 275.9387,-717.5819"/>
<text text-anchor="middle" x="442.5" y="-793.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- treatment -->
<g id="node10" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M1615,-564.5C1615,-564.5 1907,-564.5 1907,-564.5 1913,-564.5 1919,-570.5 1919,-576.5 1919,-576.5 1919,-690.5 1919,-690.5 1919,-696.5 1913,-702.5 1907,-702.5 1907,-702.5 1615,-702.5 1615,-702.5 1609,-702.5 1603,-696.5 1603,-690.5 1603,-690.5 1603,-576.5 1603,-576.5 1603,-570.5 1609,-564.5 1615,-564.5"/>
<text text-anchor="middle" x="1647.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1692,-564.5 1692,-702.5 "/>
<text text-anchor="middle" x="1702.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1713,-564.5 1713,-702.5 "/>
<text text-anchor="middle" x="1805.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="1713,-679.5 1898,-679.5 "/>
<text text-anchor="middle" x="1805.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1713,-656.5 1898,-656.5 "/>
<text text-anchor="middle" x="1805.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1713,-633.5 1898,-633.5 "/>
<text text-anchor="middle" x="1805.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="1713,-610.5 1898,-610.5 "/>
<text text-anchor="middle" x="1805.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1713,-587.5 1898,-587.5 "/>
<text text-anchor="middle" x="1805.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1898,-564.5 1898,-702.5 "/>
<text text-anchor="middle" x="1908.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1684.7885,-564.4419C1656.0674,-540.5375 1622.2757,-514.8022 1589,-495 1556.3008,-475.5408 1547.0638,-470.6124 1510,-462 1446.0269,-447.1348 1276.5389,-466.9455 1215,-444 1184.8485,-432.7577 1155.8765,-412.4245 1132.4787,-392.7"/>
<polygon fill="#000000" stroke="#000000" points="1134.6229,-389.9275 1124.7638,-386.0482 1130.0519,-395.229 1134.6229,-389.9275"/>
<text text-anchor="middle" x="1603" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
</g>
</svg>
</div>
