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
<svg width="2673pt" height="1292pt"
 viewBox="0.00 0.00 2673.00 1292.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1288)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1288 2669,-1288 2669,4 -4,4"/>
<!-- treatment_response -->
<g id="node1" class="node">
<title>treatment_response</title>
<path fill="none" stroke="#000000" d="M2292,-610.5C2292,-610.5 2653,-610.5 2653,-610.5 2659,-610.5 2665,-616.5 2665,-622.5 2665,-622.5 2665,-736.5 2665,-736.5 2665,-742.5 2659,-748.5 2653,-748.5 2653,-748.5 2292,-748.5 2292,-748.5 2286,-748.5 2280,-742.5 2280,-736.5 2280,-736.5 2280,-622.5 2280,-622.5 2280,-616.5 2286,-610.5 2292,-610.5"/>
<text text-anchor="middle" x="2360.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
<polyline fill="none" stroke="#000000" points="2441,-610.5 2441,-748.5 "/>
<text text-anchor="middle" x="2451.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2462,-610.5 2462,-748.5 "/>
<text text-anchor="middle" x="2553" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_response</text>
<polyline fill="none" stroke="#000000" points="2462,-725.5 2644,-725.5 "/>
<text text-anchor="middle" x="2553" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2462,-702.5 2644,-702.5 "/>
<text text-anchor="middle" x="2553" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="2462,-679.5 2644,-679.5 "/>
<text text-anchor="middle" x="2553" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_category</text>
<polyline fill="none" stroke="#000000" points="2462,-656.5 2644,-656.5 "/>
<text text-anchor="middle" x="2553" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_system</text>
<polyline fill="none" stroke="#000000" points="2462,-633.5 2644,-633.5 "/>
<text text-anchor="middle" x="2553" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response_id</text>
<polyline fill="none" stroke="#000000" points="2644,-610.5 2644,-748.5 "/>
<text text-anchor="middle" x="2654.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node10" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1122,-328.5C1122,-328.5 1353,-328.5 1353,-328.5 1359,-328.5 1365,-334.5 1365,-340.5 1365,-340.5 1365,-408.5 1365,-408.5 1365,-414.5 1359,-420.5 1353,-420.5 1353,-420.5 1122,-420.5 1122,-420.5 1116,-420.5 1110,-414.5 1110,-408.5 1110,-408.5 1110,-340.5 1110,-340.5 1110,-334.5 1116,-328.5 1122,-328.5"/>
<text text-anchor="middle" x="1158" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1206,-328.5 1206,-420.5 "/>
<text text-anchor="middle" x="1216.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1227,-328.5 1227,-420.5 "/>
<text text-anchor="middle" x="1285.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1227,-397.5 1344,-397.5 "/>
<text text-anchor="middle" x="1285.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1227,-374.5 1344,-374.5 "/>
<text text-anchor="middle" x="1285.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1227,-351.5 1344,-351.5 "/>
<text text-anchor="middle" x="1285.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="1344,-328.5 1344,-420.5 "/>
<text text-anchor="middle" x="1354.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2391.5876,-610.3143C2356.8024,-584.2881 2314.3356,-557.1194 2271.5,-541 2153.3968,-496.5568 2115.3539,-517.185 1989.5,-508 1921.208,-503.016 1437.4227,-514.5465 1373.5,-490 1339.5619,-476.9677 1308.1585,-451.6105 1284.0983,-427.9677"/>
<polygon fill="#000000" stroke="#000000" points="1286.4054,-425.324 1276.8724,-420.7008 1281.4416,-430.2598 1286.4054,-425.324"/>
<text text-anchor="middle" x="2297.5" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- laboratory_test -->
<g id="node2" class="node">
<title>laboratory_test</title>
<path fill="none" stroke="#000000" d="M355,-541.5C355,-541.5 646,-541.5 646,-541.5 652,-541.5 658,-547.5 658,-553.5 658,-553.5 658,-805.5 658,-805.5 658,-811.5 652,-817.5 646,-817.5 646,-817.5 355,-817.5 355,-817.5 349,-817.5 343,-811.5 343,-805.5 343,-805.5 343,-553.5 343,-553.5 343,-547.5 349,-541.5 355,-541.5"/>
<text text-anchor="middle" x="406" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="469,-541.5 469,-817.5 "/>
<text text-anchor="middle" x="479.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="490,-541.5 490,-817.5 "/>
<text text-anchor="middle" x="563.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_lab</text>
<polyline fill="none" stroke="#000000" points="490,-794.5 637,-794.5 "/>
<text text-anchor="middle" x="563.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="490,-771.5 637,-771.5 "/>
<text text-anchor="middle" x="563.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_id</text>
<polyline fill="none" stroke="#000000" points="490,-748.5 637,-748.5 "/>
<text text-anchor="middle" x="563.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">method</text>
<polyline fill="none" stroke="#000000" points="490,-725.5 637,-725.5 "/>
<text text-anchor="middle" x="563.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">result</text>
<polyline fill="none" stroke="#000000" points="490,-702.5 637,-702.5 "/>
<text text-anchor="middle" x="563.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">result_modifier</text>
<polyline fill="none" stroke="#000000" points="490,-679.5 637,-679.5 "/>
<text text-anchor="middle" x="563.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">result_numeric</text>
<polyline fill="none" stroke="#000000" points="490,-656.5 637,-656.5 "/>
<text text-anchor="middle" x="563.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">result_text</text>
<polyline fill="none" stroke="#000000" points="490,-633.5 637,-633.5 "/>
<text text-anchor="middle" x="563.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">result_unit</text>
<polyline fill="none" stroke="#000000" points="490,-610.5 637,-610.5 "/>
<text text-anchor="middle" x="563.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">sensitivity</text>
<polyline fill="none" stroke="#000000" points="490,-587.5 637,-587.5 "/>
<text text-anchor="middle" x="563.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">specimen</text>
<polyline fill="none" stroke="#000000" points="490,-564.5 637,-564.5 "/>
<text text-anchor="middle" x="563.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">test</text>
<polyline fill="none" stroke="#000000" points="637,-541.5 637,-817.5 "/>
<text text-anchor="middle" x="647.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M658.0679,-545.6544C660.8727,-544.0533 663.6844,-542.5001 666.5,-541 805.0016,-467.2087 980.2972,-422.3512 1099.8875,-398.0803"/>
<polygon fill="#000000" stroke="#000000" points="1100.7241,-401.4823 1109.8393,-396.082 1099.346,-394.6193 1100.7241,-401.4823"/>
<text text-anchor="middle" x="790" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- survival -->
<g id="node3" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M688,-587.5C688,-587.5 1049,-587.5 1049,-587.5 1055,-587.5 1061,-593.5 1061,-599.5 1061,-599.5 1061,-759.5 1061,-759.5 1061,-765.5 1055,-771.5 1049,-771.5 1049,-771.5 688,-771.5 688,-771.5 682,-771.5 676,-765.5 676,-759.5 676,-759.5 676,-599.5 676,-599.5 676,-593.5 682,-587.5 688,-587.5"/>
<text text-anchor="middle" x="713" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="750,-587.5 750,-771.5 "/>
<text text-anchor="middle" x="760.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="771,-587.5 771,-771.5 "/>
<text text-anchor="middle" x="905.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="771,-748.5 1040,-748.5 "/>
<text text-anchor="middle" x="905.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="771,-725.5 1040,-725.5 "/>
<text text-anchor="middle" x="905.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="771,-702.5 1040,-702.5 "/>
<text text-anchor="middle" x="905.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="771,-679.5 1040,-679.5 "/>
<text text-anchor="middle" x="905.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="771,-656.5 1040,-656.5 "/>
<text text-anchor="middle" x="905.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="771,-633.5 1040,-633.5 "/>
<text text-anchor="middle" x="905.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="771,-610.5 1040,-610.5 "/>
<text text-anchor="middle" x="905.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="1040,-587.5 1040,-771.5 "/>
<text text-anchor="middle" x="1050.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M979.963,-587.3693C1043.3296,-534.9932 1120.403,-471.2875 1173.6295,-427.2927"/>
<polygon fill="#000000" stroke="#000000" points="1176.155,-429.7461 1181.633,-420.6773 1171.6953,-424.3506 1176.155,-429.7461"/>
<text text-anchor="middle" x="1115" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- treatment -->
<g id="node4" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M1091.5,-564.5C1091.5,-564.5 1383.5,-564.5 1383.5,-564.5 1389.5,-564.5 1395.5,-570.5 1395.5,-576.5 1395.5,-576.5 1395.5,-782.5 1395.5,-782.5 1395.5,-788.5 1389.5,-794.5 1383.5,-794.5 1383.5,-794.5 1091.5,-794.5 1091.5,-794.5 1085.5,-794.5 1079.5,-788.5 1079.5,-782.5 1079.5,-782.5 1079.5,-576.5 1079.5,-576.5 1079.5,-570.5 1085.5,-564.5 1091.5,-564.5"/>
<text text-anchor="middle" x="1124" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1168.5,-564.5 1168.5,-794.5 "/>
<text text-anchor="middle" x="1179" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1189.5,-564.5 1189.5,-794.5 "/>
<text text-anchor="middle" x="1282" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="1189.5,-771.5 1374.5,-771.5 "/>
<text text-anchor="middle" x="1282" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1189.5,-748.5 1374.5,-748.5 "/>
<text text-anchor="middle" x="1282" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose</text>
<polyline fill="none" stroke="#000000" points="1189.5,-725.5 1374.5,-725.5 "/>
<text text-anchor="middle" x="1282" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_frequency</text>
<polyline fill="none" stroke="#000000" points="1189.5,-702.5 1374.5,-702.5 "/>
<text text-anchor="middle" x="1282" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_route</text>
<polyline fill="none" stroke="#000000" points="1189.5,-679.5 1374.5,-679.5 "/>
<text text-anchor="middle" x="1282" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_unit</text>
<polyline fill="none" stroke="#000000" points="1189.5,-656.5 1374.5,-656.5 "/>
<text text-anchor="middle" x="1282" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1189.5,-633.5 1374.5,-633.5 "/>
<text text-anchor="middle" x="1282" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="1189.5,-610.5 1374.5,-610.5 "/>
<text text-anchor="middle" x="1282" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1189.5,-587.5 1374.5,-587.5 "/>
<text text-anchor="middle" x="1282" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1374.5,-564.5 1374.5,-794.5 "/>
<text text-anchor="middle" x="1385" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1237.5,-564.1926C1237.5,-518.5507 1237.5,-468.1751 1237.5,-430.8143"/>
<polygon fill="#000000" stroke="#000000" points="1241.0001,-430.6365 1237.5,-420.6366 1234.0001,-430.6366 1241.0001,-430.6365"/>
<text text-anchor="middle" x="1284.5" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- sample -->
<g id="node5" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1425.5,-576C1425.5,-576 1739.5,-576 1739.5,-576 1745.5,-576 1751.5,-582 1751.5,-588 1751.5,-588 1751.5,-771 1751.5,-771 1751.5,-777 1745.5,-783 1739.5,-783 1739.5,-783 1425.5,-783 1425.5,-783 1419.5,-783 1413.5,-777 1413.5,-771 1413.5,-771 1413.5,-588 1413.5,-588 1413.5,-582 1419.5,-576 1425.5,-576"/>
<text text-anchor="middle" x="1447.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1481.5,-576 1481.5,-783 "/>
<text text-anchor="middle" x="1492" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1502.5,-576 1502.5,-783 "/>
<text text-anchor="middle" x="1616.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1502.5,-760 1730.5,-760 "/>
<text text-anchor="middle" x="1616.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1502.5,-737 1730.5,-737 "/>
<text text-anchor="middle" x="1616.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1502.5,-714 1730.5,-714 "/>
<text text-anchor="middle" x="1616.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_necrosis</text>
<polyline fill="none" stroke="#000000" points="1502.5,-691 1730.5,-691 "/>
<text text-anchor="middle" x="1616.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_tumor</text>
<polyline fill="none" stroke="#000000" points="1502.5,-668 1730.5,-668 "/>
<text text-anchor="middle" x="1616.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1502.5,-645 1730.5,-645 "/>
<text text-anchor="middle" x="1616.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1502.5,-622 1730.5,-622 "/>
<text text-anchor="middle" x="1616.5" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1502.5,-599 1730.5,-599 "/>
<text text-anchor="middle" x="1616.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1730.5,-576 1730.5,-783 "/>
<text text-anchor="middle" x="1741" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1465.2173,-575.8153C1408.7794,-525.9209 1343.5258,-468.233 1297.3768,-427.4346"/>
<polygon fill="#000000" stroke="#000000" points="1299.6622,-424.7834 1289.8519,-420.7821 1295.0258,-430.0278 1299.6622,-424.7834"/>
<text text-anchor="middle" x="1437" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- synonym -->
<g id="node6" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M12,-599C12,-599 313,-599 313,-599 319,-599 325,-605 325,-611 325,-611 325,-748 325,-748 325,-754 319,-760 313,-760 313,-760 12,-760 12,-760 6,-760 0,-754 0,-748 0,-748 0,-611 0,-611 0,-605 6,-599 12,-599"/>
<text text-anchor="middle" x="40" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="80,-599 80,-760 "/>
<text text-anchor="middle" x="90.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="101,-599 101,-760 "/>
<text text-anchor="middle" x="202.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_id</text>
<polyline fill="none" stroke="#000000" points="101,-737 304,-737 "/>
<text text-anchor="middle" x="202.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">data_location</text>
<polyline fill="none" stroke="#000000" points="101,-714 304,-714 "/>
<text text-anchor="middle" x="202.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">domain_category</text>
<polyline fill="none" stroke="#000000" points="101,-691 304,-691 "/>
<text text-anchor="middle" x="202.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">domain_description</text>
<polyline fill="none" stroke="#000000" points="101,-668 304,-668 "/>
<text text-anchor="middle" x="202.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="101,-645 304,-645 "/>
<text text-anchor="middle" x="202.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="101,-622 304,-622 "/>
<text text-anchor="middle" x="202.5" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="304,-599 304,-760 "/>
<text text-anchor="middle" x="314.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M245.1209,-598.8173C271.5228,-577.0035 302.0942,-555.4588 333.5,-541 467.8112,-479.1651 881.351,-419.608 1099.4978,-391.4312"/>
<polygon fill="#000000" stroke="#000000" points="1100.2649,-394.8614 1109.7362,-390.1132 1099.3712,-387.9187 1100.2649,-394.8614"/>
<text text-anchor="middle" x="464" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study -->
<g id="node11" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1128,-.5C1128,-.5 1347,-.5 1347,-.5 1353,-.5 1359,-6.5 1359,-12.5 1359,-12.5 1359,-195.5 1359,-195.5 1359,-201.5 1353,-207.5 1347,-207.5 1347,-207.5 1128,-207.5 1128,-207.5 1122,-207.5 1116,-201.5 1116,-195.5 1116,-195.5 1116,-12.5 1116,-12.5 1116,-6.5 1122,-.5 1128,-.5"/>
<text text-anchor="middle" x="1144" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1172,-.5 1172,-207.5 "/>
<text text-anchor="middle" x="1182.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1193,-.5 1193,-207.5 "/>
<text text-anchor="middle" x="1265.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="1193,-184.5 1338,-184.5 "/>
<text text-anchor="middle" x="1265.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="1193,-161.5 1338,-161.5 "/>
<text text-anchor="middle" x="1265.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession</text>
<polyline fill="none" stroke="#000000" points="1193,-138.5 1338,-138.5 "/>
<text text-anchor="middle" x="1265.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1193,-115.5 1338,-115.5 "/>
<text text-anchor="middle" x="1265.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1193,-92.5 1338,-92.5 "/>
<text text-anchor="middle" x="1265.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1193,-69.5 1338,-69.5 "/>
<text text-anchor="middle" x="1265.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="1193,-46.5 1338,-46.5 "/>
<text text-anchor="middle" x="1265.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1193,-23.5 1338,-23.5 "/>
<text text-anchor="middle" x="1265.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
<polyline fill="none" stroke="#000000" points="1338,-.5 1338,-207.5 "/>
<text text-anchor="middle" x="1348.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge3" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M254.0376,-598.8311C292.5089,-567.6446 338.8703,-533.4225 384.5,-508 633.1097,-369.4877 937.0025,-232.9677 1106.7376,-159.4904"/>
<polygon fill="#000000" stroke="#000000" points="1108.1791,-162.6804 1115.9689,-155.4992 1105.4011,-156.2552 1108.1791,-162.6804"/>
<text text-anchor="middle" x="922" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- diagnosis -->
<g id="node7" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1503,-869.5C1503,-869.5 1868,-869.5 1868,-869.5 1874,-869.5 1880,-875.5 1880,-881.5 1880,-881.5 1880,-1271.5 1880,-1271.5 1880,-1277.5 1874,-1283.5 1868,-1283.5 1868,-1283.5 1503,-1283.5 1503,-1283.5 1497,-1283.5 1491,-1277.5 1491,-1271.5 1491,-1271.5 1491,-881.5 1491,-881.5 1491,-875.5 1497,-869.5 1503,-869.5"/>
<text text-anchor="middle" x="1533" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1575,-869.5 1575,-1283.5 "/>
<text text-anchor="middle" x="1585.5" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1596,-869.5 1596,-1283.5 "/>
<text text-anchor="middle" x="1727.5" y="-1268.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1596,-1260.5 1859,-1260.5 "/>
<text text-anchor="middle" x="1727.5" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1596,-1237.5 1859,-1237.5 "/>
<text text-anchor="middle" x="1727.5" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1596,-1214.5 1859,-1214.5 "/>
<text text-anchor="middle" x="1727.5" y="-1199.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="1596,-1191.5 1859,-1191.5 "/>
<text text-anchor="middle" x="1727.5" y="-1176.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_category</text>
<polyline fill="none" stroke="#000000" points="1596,-1168.5 1859,-1168.5 "/>
<text text-anchor="middle" x="1727.5" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="1596,-1145.5 1859,-1145.5 "/>
<text text-anchor="middle" x="1727.5" y="-1130.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="1596,-1122.5 1859,-1122.5 "/>
<text text-anchor="middle" x="1727.5" y="-1107.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1596,-1099.5 1859,-1099.5 "/>
<text text-anchor="middle" x="1727.5" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="1596,-1076.5 1859,-1076.5 "/>
<text text-anchor="middle" x="1727.5" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1596,-1053.5 1859,-1053.5 "/>
<text text-anchor="middle" x="1727.5" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">laterality</text>
<polyline fill="none" stroke="#000000" points="1596,-1030.5 1859,-1030.5 "/>
<text text-anchor="middle" x="1727.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="1596,-1007.5 1859,-1007.5 "/>
<text text-anchor="middle" x="1727.5" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1596,-984.5 1859,-984.5 "/>
<text text-anchor="middle" x="1727.5" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1596,-961.5 1859,-961.5 "/>
<text text-anchor="middle" x="1727.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1596,-938.5 1859,-938.5 "/>
<text text-anchor="middle" x="1727.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1596,-915.5 1859,-915.5 "/>
<text text-anchor="middle" x="1727.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1596,-892.5 1859,-892.5 "/>
<text text-anchor="middle" x="1727.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1859,-869.5 1859,-1283.5 "/>
<text text-anchor="middle" x="1869.5" y="-1072.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1631.7375,-869.2794C1624.921,-843.0061 1618.1575,-816.937 1611.9258,-792.9178"/>
<polygon fill="#000000" stroke="#000000" points="1615.2808,-791.912 1609.3816,-783.1114 1608.5051,-793.67 1615.2808,-791.912"/>
<text text-anchor="middle" x="1670" y="-839.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1751.145,-869.1542C1754.9038,-851.9752 1758.1163,-834.7708 1760.5,-818 1769.1623,-757.057 1801.0834,-587.2825 1760.5,-541 1703.3102,-475.7791 1452.7911,-525.1762 1373.5,-490 1340.9105,-475.5422 1310.1353,-450.7388 1286.1302,-427.8145"/>
<polygon fill="#000000" stroke="#000000" points="1288.5084,-425.2451 1278.9032,-420.774 1283.6238,-430.2591 1288.5084,-425.2451"/>
<text text-anchor="middle" x="1825" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- genetic_analysis -->
<g id="node8" class="node">
<title>genetic_analysis</title>
<path fill="none" stroke="#000000" d="M1907,-553C1907,-553 2250,-553 2250,-553 2256,-553 2262,-559 2262,-565 2262,-565 2262,-794 2262,-794 2262,-800 2256,-806 2250,-806 2250,-806 1907,-806 1907,-806 1901,-806 1895,-800 1895,-794 1895,-794 1895,-565 1895,-565 1895,-559 1901,-553 1907,-553"/>
<text text-anchor="middle" x="1962.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="2030,-553 2030,-806 "/>
<text text-anchor="middle" x="2040.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2051,-553 2051,-806 "/>
<text text-anchor="middle" x="2146" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="2051,-783 2241,-783 "/>
<text text-anchor="middle" x="2146" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">allelic_ratio</text>
<polyline fill="none" stroke="#000000" points="2051,-760 2241,-760 "/>
<text text-anchor="middle" x="2146" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">alteration</text>
<polyline fill="none" stroke="#000000" points="2051,-737 2241,-737 "/>
<text text-anchor="middle" x="2146" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">dna_index_numeric</text>
<polyline fill="none" stroke="#000000" points="2051,-714 2241,-714 "/>
<text text-anchor="middle" x="2146" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis_id</text>
<polyline fill="none" stroke="#000000" points="2051,-691 2241,-691 "/>
<text text-anchor="middle" x="2146" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_coding</text>
<polyline fill="none" stroke="#000000" points="2051,-668 2241,-668 "/>
<text text-anchor="middle" x="2146" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_protein</text>
<polyline fill="none" stroke="#000000" points="2051,-645 2241,-645 "/>
<text text-anchor="middle" x="2146" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2051,-622 2241,-622 "/>
<text text-anchor="middle" x="2146" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">iscn</text>
<polyline fill="none" stroke="#000000" points="2051,-599 2241,-599 "/>
<text text-anchor="middle" x="2146" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="2051,-576 2241,-576 "/>
<text text-anchor="middle" x="2146" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">vaf_numeric</text>
<polyline fill="none" stroke="#000000" points="2241,-553 2241,-806 "/>
<text text-anchor="middle" x="2251.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1901.2872,-552.8906C1894.3352,-548.7714 1887.3913,-544.7919 1880.5,-541 1847.1624,-522.6559 1838.6436,-516.2616 1801.5,-508 1708.5756,-487.3315 1462.1477,-524.6945 1373.5,-490 1339.6461,-476.7504 1308.2497,-451.3752 1284.1724,-427.7765"/>
<polygon fill="#000000" stroke="#000000" points="1286.4803,-425.1342 1276.9405,-420.5252 1281.5239,-430.0774 1286.4803,-425.1342"/>
<text text-anchor="middle" x="1915.5" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- reference_file -->
<g id="node9" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M1395,-259.5C1395,-259.5 1672,-259.5 1672,-259.5 1678,-259.5 1684,-265.5 1684,-271.5 1684,-271.5 1684,-477.5 1684,-477.5 1684,-483.5 1678,-489.5 1672,-489.5 1672,-489.5 1395,-489.5 1395,-489.5 1389,-489.5 1383,-483.5 1383,-477.5 1383,-477.5 1383,-271.5 1383,-271.5 1383,-265.5 1389,-259.5 1395,-259.5"/>
<text text-anchor="middle" x="1441" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="1499,-259.5 1499,-489.5 "/>
<text text-anchor="middle" x="1509.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1520,-259.5 1520,-489.5 "/>
<text text-anchor="middle" x="1591.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1520,-466.5 1663,-466.5 "/>
<text text-anchor="middle" x="1591.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="1520,-443.5 1663,-443.5 "/>
<text text-anchor="middle" x="1591.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1520,-420.5 1663,-420.5 "/>
<text text-anchor="middle" x="1591.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1520,-397.5 1663,-397.5 "/>
<text text-anchor="middle" x="1591.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1520,-374.5 1663,-374.5 "/>
<text text-anchor="middle" x="1591.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1520,-351.5 1663,-351.5 "/>
<text text-anchor="middle" x="1591.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1520,-328.5 1663,-328.5 "/>
<text text-anchor="middle" x="1591.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1520,-305.5 1663,-305.5 "/>
<text text-anchor="middle" x="1591.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="1520,-282.5 1663,-282.5 "/>
<text text-anchor="middle" x="1591.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="1663,-259.5 1663,-489.5 "/>
<text text-anchor="middle" x="1673.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge6" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1407.5401,-259.3914C1391.3023,-244.5524 1374.7023,-229.3825 1358.5459,-214.6179"/>
<polygon fill="#000000" stroke="#000000" points="1360.8998,-212.0277 1351.1568,-207.8654 1356.1776,-217.195 1360.8998,-212.0277"/>
<text text-anchor="middle" x="1446" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge12" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1237.5,-328.3067C1237.5,-297.9024 1237.5,-256.6891 1237.5,-217.8833"/>
<polygon fill="#000000" stroke="#000000" points="1241.0001,-217.5472 1237.5,-207.5472 1234.0001,-217.5472 1241.0001,-217.5472"/>
<text text-anchor="middle" x="1288" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
</g>
</svg>
</div>
