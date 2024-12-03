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
<path fill="none" stroke="#000000" d="M1258.5,-564.5C1258.5,-564.5 1550.5,-564.5 1550.5,-564.5 1556.5,-564.5 1562.5,-570.5 1562.5,-576.5 1562.5,-576.5 1562.5,-690.5 1562.5,-690.5 1562.5,-696.5 1556.5,-702.5 1550.5,-702.5 1550.5,-702.5 1258.5,-702.5 1258.5,-702.5 1252.5,-702.5 1246.5,-696.5 1246.5,-690.5 1246.5,-690.5 1246.5,-576.5 1246.5,-576.5 1246.5,-570.5 1252.5,-564.5 1258.5,-564.5"/>
<text text-anchor="middle" x="1291" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1335.5,-564.5 1335.5,-702.5 "/>
<text text-anchor="middle" x="1346" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1356.5,-564.5 1356.5,-702.5 "/>
<text text-anchor="middle" x="1449" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="1356.5,-679.5 1541.5,-679.5 "/>
<text text-anchor="middle" x="1449" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1356.5,-656.5 1541.5,-656.5 "/>
<text text-anchor="middle" x="1449" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1356.5,-633.5 1541.5,-633.5 "/>
<text text-anchor="middle" x="1449" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="1356.5,-610.5 1541.5,-610.5 "/>
<text text-anchor="middle" x="1449" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1356.5,-587.5 1541.5,-587.5 "/>
<text text-anchor="middle" x="1449" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1541.5,-564.5 1541.5,-702.5 "/>
<text text-anchor="middle" x="1552" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node7" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1157,-294C1157,-294 1388,-294 1388,-294 1394,-294 1400,-300 1400,-306 1400,-306 1400,-374 1400,-374 1400,-380 1394,-386 1388,-386 1388,-386 1157,-386 1157,-386 1151,-386 1145,-380 1145,-374 1145,-374 1145,-306 1145,-306 1145,-300 1151,-294 1157,-294"/>
<text text-anchor="middle" x="1193" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1241,-294 1241,-386 "/>
<text text-anchor="middle" x="1251.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1262,-294 1262,-386 "/>
<text text-anchor="middle" x="1320.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1262,-363 1379,-363 "/>
<text text-anchor="middle" x="1320.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1262,-340 1379,-340 "/>
<text text-anchor="middle" x="1320.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1262,-317 1379,-317 "/>
<text text-anchor="middle" x="1320.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="1379,-294 1379,-386 "/>
<text text-anchor="middle" x="1389.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1373.385,-564.3163C1350.233,-512.8381 1319.0439,-443.4897 1297.5026,-395.5928"/>
<polygon fill="#000000" stroke="#000000" points="1300.622,-393.9956 1293.3282,-386.3111 1294.2379,-396.8668 1300.622,-393.9956"/>
<text text-anchor="middle" x="1378.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- survival -->
<g id="node2" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M12,-541.5C12,-541.5 373,-541.5 373,-541.5 379,-541.5 385,-547.5 385,-553.5 385,-553.5 385,-713.5 385,-713.5 385,-719.5 379,-725.5 373,-725.5 373,-725.5 12,-725.5 12,-725.5 6,-725.5 0,-719.5 0,-713.5 0,-713.5 0,-553.5 0,-553.5 0,-547.5 6,-541.5 12,-541.5"/>
<text text-anchor="middle" x="37" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="74,-541.5 74,-725.5 "/>
<text text-anchor="middle" x="84.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="95,-541.5 95,-725.5 "/>
<text text-anchor="middle" x="229.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="95,-702.5 364,-702.5 "/>
<text text-anchor="middle" x="229.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="95,-679.5 364,-679.5 "/>
<text text-anchor="middle" x="229.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="95,-656.5 364,-656.5 "/>
<text text-anchor="middle" x="229.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="95,-633.5 364,-633.5 "/>
<text text-anchor="middle" x="229.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="95,-610.5 364,-610.5 "/>
<text text-anchor="middle" x="229.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="95,-587.5 364,-587.5 "/>
<text text-anchor="middle" x="229.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="95,-564.5 364,-564.5 "/>
<text text-anchor="middle" x="229.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="364,-541.5 364,-725.5 "/>
<text text-anchor="middle" x="374.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M305.6016,-541.481C332.9758,-523.3118 363.14,-506.3695 393.5,-495 514.9816,-449.5063 554.1592,-471.9209 683.5,-462 733.6148,-458.156 1088.1921,-460.9776 1135.5,-444 1166.0548,-433.0347 1195.3644,-412.628 1218.9765,-392.7759"/>
<polygon fill="#000000" stroke="#000000" points="1221.4619,-395.2546 1226.7592,-386.0791 1216.8962,-389.9486 1221.4619,-395.2546"/>
<text text-anchor="middle" x="723" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- laboratory_test -->
<g id="node3" class="node">
<title>laboratory_test</title>
<path fill="none" stroke="#000000" d="M415,-495.5C415,-495.5 706,-495.5 706,-495.5 712,-495.5 718,-501.5 718,-507.5 718,-507.5 718,-759.5 718,-759.5 718,-765.5 712,-771.5 706,-771.5 706,-771.5 415,-771.5 415,-771.5 409,-771.5 403,-765.5 403,-759.5 403,-759.5 403,-507.5 403,-507.5 403,-501.5 409,-495.5 415,-495.5"/>
<text text-anchor="middle" x="466" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="529,-495.5 529,-771.5 "/>
<text text-anchor="middle" x="539.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="550,-495.5 550,-771.5 "/>
<text text-anchor="middle" x="623.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_lab</text>
<polyline fill="none" stroke="#000000" points="550,-748.5 697,-748.5 "/>
<text text-anchor="middle" x="623.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="550,-725.5 697,-725.5 "/>
<text text-anchor="middle" x="623.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_id</text>
<polyline fill="none" stroke="#000000" points="550,-702.5 697,-702.5 "/>
<text text-anchor="middle" x="623.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">method</text>
<polyline fill="none" stroke="#000000" points="550,-679.5 697,-679.5 "/>
<text text-anchor="middle" x="623.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">result</text>
<polyline fill="none" stroke="#000000" points="550,-656.5 697,-656.5 "/>
<text text-anchor="middle" x="623.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">result_modifier</text>
<polyline fill="none" stroke="#000000" points="550,-633.5 697,-633.5 "/>
<text text-anchor="middle" x="623.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">result_numeric</text>
<polyline fill="none" stroke="#000000" points="550,-610.5 697,-610.5 "/>
<text text-anchor="middle" x="623.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">result_text</text>
<polyline fill="none" stroke="#000000" points="550,-587.5 697,-587.5 "/>
<text text-anchor="middle" x="623.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">result_unit</text>
<polyline fill="none" stroke="#000000" points="550,-564.5 697,-564.5 "/>
<text text-anchor="middle" x="623.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">sensitivity</text>
<polyline fill="none" stroke="#000000" points="550,-541.5 697,-541.5 "/>
<text text-anchor="middle" x="623.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">specimen</text>
<polyline fill="none" stroke="#000000" points="550,-518.5 697,-518.5 "/>
<text text-anchor="middle" x="623.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">test</text>
<polyline fill="none" stroke="#000000" points="697,-495.5 697,-771.5 "/>
<text text-anchor="middle" x="707.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M718.0842,-499.6849C720.884,-498.0743 723.6902,-496.511 726.5,-495 771.4538,-470.8259 786.2451,-470.9266 836.5,-462 902.0389,-450.3586 1073.0794,-467.1199 1135.5,-444 1165.816,-432.7713 1194.9923,-412.4402 1218.571,-392.7136"/>
<polygon fill="#000000" stroke="#000000" points="1221.0234,-395.2216 1226.3463,-386.0609 1216.4725,-389.9028 1221.0234,-395.2216"/>
<text text-anchor="middle" x="902" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- genetic_analysis -->
<g id="node4" class="node">
<title>genetic_analysis</title>
<path fill="none" stroke="#000000" d="M748,-507C748,-507 1091,-507 1091,-507 1097,-507 1103,-513 1103,-519 1103,-519 1103,-748 1103,-748 1103,-754 1097,-760 1091,-760 1091,-760 748,-760 748,-760 742,-760 736,-754 736,-748 736,-748 736,-519 736,-519 736,-513 742,-507 748,-507"/>
<text text-anchor="middle" x="803.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="871,-507 871,-760 "/>
<text text-anchor="middle" x="881.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="892,-507 892,-760 "/>
<text text-anchor="middle" x="987" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="892,-737 1082,-737 "/>
<text text-anchor="middle" x="987" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">allelic_ratio</text>
<polyline fill="none" stroke="#000000" points="892,-714 1082,-714 "/>
<text text-anchor="middle" x="987" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">alteration</text>
<polyline fill="none" stroke="#000000" points="892,-691 1082,-691 "/>
<text text-anchor="middle" x="987" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">dna_index_numeric</text>
<polyline fill="none" stroke="#000000" points="892,-668 1082,-668 "/>
<text text-anchor="middle" x="987" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis_id</text>
<polyline fill="none" stroke="#000000" points="892,-645 1082,-645 "/>
<text text-anchor="middle" x="987" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_coding</text>
<polyline fill="none" stroke="#000000" points="892,-622 1082,-622 "/>
<text text-anchor="middle" x="987" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_protein</text>
<polyline fill="none" stroke="#000000" points="892,-599 1082,-599 "/>
<text text-anchor="middle" x="987" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="892,-576 1082,-576 "/>
<text text-anchor="middle" x="987" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">iscn</text>
<polyline fill="none" stroke="#000000" points="892,-553 1082,-553 "/>
<text text-anchor="middle" x="987" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="892,-530 1082,-530 "/>
<text text-anchor="middle" x="987" y="-514.8" font-family="Times,serif" font-size="14.00" fill="#000000">vaf_numeric</text>
<polyline fill="none" stroke="#000000" points="1082,-507 1082,-760 "/>
<text text-anchor="middle" x="1092.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M949.5359,-506.9506C958.5509,-489.6862 970.269,-473.8557 985.5,-462 1038.4851,-420.7566 1073.2543,-469.1778 1135.5,-444 1165.0967,-432.0284 1193.8675,-411.9168 1217.34,-392.5524"/>
<polygon fill="#000000" stroke="#000000" points="1219.6951,-395.1449 1225.0907,-386.0269 1215.1867,-389.7901 1219.6951,-395.1449"/>
<text text-anchor="middle" x="1055.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- study -->
<g id="node5" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1163,-.5C1163,-.5 1382,-.5 1382,-.5 1388,-.5 1394,-6.5 1394,-12.5 1394,-12.5 1394,-172.5 1394,-172.5 1394,-178.5 1388,-184.5 1382,-184.5 1382,-184.5 1163,-184.5 1163,-184.5 1157,-184.5 1151,-178.5 1151,-172.5 1151,-172.5 1151,-12.5 1151,-12.5 1151,-6.5 1157,-.5 1163,-.5"/>
<text text-anchor="middle" x="1179" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1207,-.5 1207,-184.5 "/>
<text text-anchor="middle" x="1217.5" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1228,-.5 1228,-184.5 "/>
<text text-anchor="middle" x="1300.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="1228,-161.5 1373,-161.5 "/>
<text text-anchor="middle" x="1300.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="1228,-138.5 1373,-138.5 "/>
<text text-anchor="middle" x="1300.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession</text>
<polyline fill="none" stroke="#000000" points="1228,-115.5 1373,-115.5 "/>
<text text-anchor="middle" x="1300.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1228,-92.5 1373,-92.5 "/>
<text text-anchor="middle" x="1300.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1228,-69.5 1373,-69.5 "/>
<text text-anchor="middle" x="1300.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1228,-46.5 1373,-46.5 "/>
<text text-anchor="middle" x="1300.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="1228,-23.5 1373,-23.5 "/>
<text text-anchor="middle" x="1300.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1373,-.5 1373,-184.5 "/>
<text text-anchor="middle" x="1383.5" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file -->
<g id="node6" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M838,-236.5C838,-236.5 1115,-236.5 1115,-236.5 1121,-236.5 1127,-242.5 1127,-248.5 1127,-248.5 1127,-431.5 1127,-431.5 1127,-437.5 1121,-443.5 1115,-443.5 1115,-443.5 838,-443.5 838,-443.5 832,-443.5 826,-437.5 826,-431.5 826,-431.5 826,-248.5 826,-248.5 826,-242.5 832,-236.5 838,-236.5"/>
<text text-anchor="middle" x="884" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="942,-236.5 942,-443.5 "/>
<text text-anchor="middle" x="952.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="963,-236.5 963,-443.5 "/>
<text text-anchor="middle" x="1034.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="963,-420.5 1106,-420.5 "/>
<text text-anchor="middle" x="1034.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="963,-397.5 1106,-397.5 "/>
<text text-anchor="middle" x="1034.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="963,-374.5 1106,-374.5 "/>
<text text-anchor="middle" x="1034.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="963,-351.5 1106,-351.5 "/>
<text text-anchor="middle" x="1034.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="963,-328.5 1106,-328.5 "/>
<text text-anchor="middle" x="1034.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="963,-305.5 1106,-305.5 "/>
<text text-anchor="middle" x="1034.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="963,-282.5 1106,-282.5 "/>
<text text-anchor="middle" x="1034.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="963,-259.5 1106,-259.5 "/>
<text text-anchor="middle" x="1034.5" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="1106,-236.5 1106,-443.5 "/>
<text text-anchor="middle" x="1116.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge1" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1100.3156,-236.4718C1118.1751,-221.5386 1136.5175,-206.2016 1154.2644,-191.3625"/>
<polygon fill="#000000" stroke="#000000" points="1156.9461,-193.6826 1162.3726,-184.5829 1152.4558,-188.3125 1156.9461,-193.6826"/>
<text text-anchor="middle" x="1194" y="-206.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge9" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1272.5,-293.7375C1272.5,-265.8494 1272.5,-229.176 1272.5,-194.7844"/>
<polygon fill="#000000" stroke="#000000" points="1276.0001,-194.677 1272.5,-184.677 1269.0001,-194.6771 1276.0001,-194.677"/>
<text text-anchor="middle" x="1323" y="-206.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- diagnosis -->
<g id="node8" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M973,-823.5C973,-823.5 1338,-823.5 1338,-823.5 1344,-823.5 1350,-829.5 1350,-835.5 1350,-835.5 1350,-1202.5 1350,-1202.5 1350,-1208.5 1344,-1214.5 1338,-1214.5 1338,-1214.5 973,-1214.5 973,-1214.5 967,-1214.5 961,-1208.5 961,-1202.5 961,-1202.5 961,-835.5 961,-835.5 961,-829.5 967,-823.5 973,-823.5"/>
<text text-anchor="middle" x="1003" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1045,-823.5 1045,-1214.5 "/>
<text text-anchor="middle" x="1055.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1066,-823.5 1066,-1214.5 "/>
<text text-anchor="middle" x="1197.5" y="-1199.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1066,-1191.5 1329,-1191.5 "/>
<text text-anchor="middle" x="1197.5" y="-1176.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1066,-1168.5 1329,-1168.5 "/>
<text text-anchor="middle" x="1197.5" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1066,-1145.5 1329,-1145.5 "/>
<text text-anchor="middle" x="1197.5" y="-1130.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="1066,-1122.5 1329,-1122.5 "/>
<text text-anchor="middle" x="1197.5" y="-1107.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="1066,-1099.5 1329,-1099.5 "/>
<text text-anchor="middle" x="1197.5" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="1066,-1076.5 1329,-1076.5 "/>
<text text-anchor="middle" x="1197.5" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="1066,-1053.5 1329,-1053.5 "/>
<text text-anchor="middle" x="1197.5" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="1066,-1030.5 1329,-1030.5 "/>
<text text-anchor="middle" x="1197.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1066,-1007.5 1329,-1007.5 "/>
<text text-anchor="middle" x="1197.5" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">laterality</text>
<polyline fill="none" stroke="#000000" points="1066,-984.5 1329,-984.5 "/>
<text text-anchor="middle" x="1197.5" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="1066,-961.5 1329,-961.5 "/>
<text text-anchor="middle" x="1197.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1066,-938.5 1329,-938.5 "/>
<text text-anchor="middle" x="1197.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="1066,-915.5 1329,-915.5 "/>
<text text-anchor="middle" x="1197.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="1066,-892.5 1329,-892.5 "/>
<text text-anchor="middle" x="1197.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="1066,-869.5 1329,-869.5 "/>
<text text-anchor="middle" x="1197.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1066,-846.5 1329,-846.5 "/>
<text text-anchor="middle" x="1197.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1329,-823.5 1329,-1214.5 "/>
<text text-anchor="middle" x="1339.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1121.4333,-823.4396C1111.6288,-722.6398 1111.9101,-599.3097 1148.5,-495 1161.8461,-456.9532 1188.8938,-421.3075 1214.3314,-393.8153"/>
<polygon fill="#000000" stroke="#000000" points="1217.1258,-395.9541 1221.4506,-386.2821 1212.0383,-391.1461 1217.1258,-395.9541"/>
<text text-anchor="middle" x="1193" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample -->
<g id="node9" class="node">
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
<!-- diagnosis&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1350.0239,-981.6549C1521.2187,-943.9198 1773.8983,-876.1646 1975.5,-772 2002.9657,-757.8089 2030.4212,-739.197 2055.2603,-720.2411"/>
<polygon fill="#000000" stroke="#000000" points="2057.4591,-722.9652 2063.2297,-714.0797 2053.1776,-717.4273 2057.4591,-722.9652"/>
<text text-anchor="middle" x="1978" y="-793.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge11" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2091.381,-552.9287C2064.9657,-522.0251 2032.4392,-487.98 1998.5,-462 1809.7151,-317.4881 1555.8114,-203.437 1403.7158,-142.156"/>
<polygon fill="#000000" stroke="#000000" points="1404.882,-138.8527 1394.2979,-138.3764 1402.2748,-145.3491 1404.882,-138.8527"/>
<text text-anchor="middle" x="2005" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2065.8092,-552.8556C2038.5162,-531.3086 2007.2193,-509.8989 1975.5,-495 1791.1514,-408.4093 1556.6297,-369.2512 1410.5169,-352.2259"/>
<polygon fill="#000000" stroke="#000000" points="1410.485,-348.6994 1400.1515,-351.0379 1409.6879,-355.6539 1410.485,-348.6994"/>
<text text-anchor="middle" x="1958" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- treatment_response -->
<g id="node10" class="node">
<title>treatment_response</title>
<path fill="none" stroke="#000000" d="M1593,-564.5C1593,-564.5 1954,-564.5 1954,-564.5 1960,-564.5 1966,-570.5 1966,-576.5 1966,-576.5 1966,-690.5 1966,-690.5 1966,-696.5 1960,-702.5 1954,-702.5 1954,-702.5 1593,-702.5 1593,-702.5 1587,-702.5 1581,-696.5 1581,-690.5 1581,-690.5 1581,-576.5 1581,-576.5 1581,-570.5 1587,-564.5 1593,-564.5"/>
<text text-anchor="middle" x="1661.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
<polyline fill="none" stroke="#000000" points="1742,-564.5 1742,-702.5 "/>
<text text-anchor="middle" x="1752.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1763,-564.5 1763,-702.5 "/>
<text text-anchor="middle" x="1854" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_response</text>
<polyline fill="none" stroke="#000000" points="1763,-679.5 1945,-679.5 "/>
<text text-anchor="middle" x="1854" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1763,-656.5 1945,-656.5 "/>
<text text-anchor="middle" x="1854" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="1763,-633.5 1945,-633.5 "/>
<text text-anchor="middle" x="1854" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_category</text>
<polyline fill="none" stroke="#000000" points="1763,-610.5 1945,-610.5 "/>
<text text-anchor="middle" x="1854" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_system</text>
<polyline fill="none" stroke="#000000" points="1763,-587.5 1945,-587.5 "/>
<text text-anchor="middle" x="1854" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response_id</text>
<polyline fill="none" stroke="#000000" points="1945,-564.5 1945,-702.5 "/>
<text text-anchor="middle" x="1955.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1677.9853,-564.4647C1644.8422,-541.4681 1607.0665,-516.3022 1571.5,-495 1508.7687,-457.4277 1435.9725,-419.5745 1377.9157,-390.6813"/>
<polygon fill="#000000" stroke="#000000" points="1379.2419,-387.4321 1368.7283,-386.1224 1376.1304,-393.7026 1379.2419,-387.4321"/>
<text text-anchor="middle" x="1623.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
</g>
</svg>
</div>
