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
<svg width="1612pt" height="1085pt"
 viewBox="0.00 0.00 1612.00 1085.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1081)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1081 1608,-1081 1608,4 -4,4"/>
<!-- treatment -->
<g id="node1" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M1300,-518.5C1300,-518.5 1592,-518.5 1592,-518.5 1598,-518.5 1604,-524.5 1604,-530.5 1604,-530.5 1604,-644.5 1604,-644.5 1604,-650.5 1598,-656.5 1592,-656.5 1592,-656.5 1300,-656.5 1300,-656.5 1294,-656.5 1288,-650.5 1288,-644.5 1288,-644.5 1288,-530.5 1288,-530.5 1288,-524.5 1294,-518.5 1300,-518.5"/>
<text text-anchor="middle" x="1332.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1377,-518.5 1377,-656.5 "/>
<text text-anchor="middle" x="1387.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1398,-518.5 1398,-656.5 "/>
<text text-anchor="middle" x="1490.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="1398,-633.5 1583,-633.5 "/>
<text text-anchor="middle" x="1490.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1398,-610.5 1583,-610.5 "/>
<text text-anchor="middle" x="1490.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1398,-587.5 1583,-587.5 "/>
<text text-anchor="middle" x="1490.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="1398,-564.5 1583,-564.5 "/>
<text text-anchor="middle" x="1490.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1398,-541.5 1583,-541.5 "/>
<text text-anchor="middle" x="1490.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1583,-518.5 1583,-656.5 "/>
<text text-anchor="middle" x="1593.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node7" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M575.5,-294C575.5,-294 806.5,-294 806.5,-294 812.5,-294 818.5,-300 818.5,-306 818.5,-306 818.5,-374 818.5,-374 818.5,-380 812.5,-386 806.5,-386 806.5,-386 575.5,-386 575.5,-386 569.5,-386 563.5,-380 563.5,-374 563.5,-374 563.5,-306 563.5,-306 563.5,-300 569.5,-294 575.5,-294"/>
<text text-anchor="middle" x="611.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="659.5,-294 659.5,-386 "/>
<text text-anchor="middle" x="670" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="680.5,-294 680.5,-386 "/>
<text text-anchor="middle" x="739" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="680.5,-363 797.5,-363 "/>
<text text-anchor="middle" x="739" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="680.5,-340 797.5,-340 "/>
<text text-anchor="middle" x="739" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="680.5,-317 797.5,-317 "/>
<text text-anchor="middle" x="739" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="797.5,-294 797.5,-386 "/>
<text text-anchor="middle" x="808" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1329.6393,-518.3004C1312.9569,-509.7867 1295.7627,-501.7299 1279,-495 1129.7509,-435.079 949.9066,-391.5845 828.7341,-366.1858"/>
<polygon fill="#000000" stroke="#000000" points="829.1594,-362.6994 818.6558,-364.0867 827.732,-369.5523 829.1594,-362.6994"/>
<text text-anchor="middle" x="1264" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- treatment_response -->
<g id="node2" class="node">
<title>treatment_response</title>
<path fill="none" stroke="#000000" d="M493.5,-518.5C493.5,-518.5 854.5,-518.5 854.5,-518.5 860.5,-518.5 866.5,-524.5 866.5,-530.5 866.5,-530.5 866.5,-644.5 866.5,-644.5 866.5,-650.5 860.5,-656.5 854.5,-656.5 854.5,-656.5 493.5,-656.5 493.5,-656.5 487.5,-656.5 481.5,-650.5 481.5,-644.5 481.5,-644.5 481.5,-530.5 481.5,-530.5 481.5,-524.5 487.5,-518.5 493.5,-518.5"/>
<text text-anchor="middle" x="562" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
<polyline fill="none" stroke="#000000" points="642.5,-518.5 642.5,-656.5 "/>
<text text-anchor="middle" x="653" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="663.5,-518.5 663.5,-656.5 "/>
<text text-anchor="middle" x="754.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_response</text>
<polyline fill="none" stroke="#000000" points="663.5,-633.5 845.5,-633.5 "/>
<text text-anchor="middle" x="754.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="663.5,-610.5 845.5,-610.5 "/>
<text text-anchor="middle" x="754.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="663.5,-587.5 845.5,-587.5 "/>
<text text-anchor="middle" x="754.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_category</text>
<polyline fill="none" stroke="#000000" points="663.5,-564.5 845.5,-564.5 "/>
<text text-anchor="middle" x="754.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_system</text>
<polyline fill="none" stroke="#000000" points="663.5,-541.5 845.5,-541.5 "/>
<text text-anchor="middle" x="754.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response_id</text>
<polyline fill="none" stroke="#000000" points="845.5,-518.5 845.5,-656.5 "/>
<text text-anchor="middle" x="856" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M678.7581,-518.2283C681.3954,-479.8317 684.6332,-432.6928 687.1165,-396.5398"/>
<polygon fill="#000000" stroke="#000000" points="690.6349,-396.39 687.8285,-386.1736 683.6514,-395.9102 690.6349,-396.39"/>
<text text-anchor="middle" x="766" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- reference_file -->
<g id="node3" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M256.5,-236.5C256.5,-236.5 533.5,-236.5 533.5,-236.5 539.5,-236.5 545.5,-242.5 545.5,-248.5 545.5,-248.5 545.5,-431.5 545.5,-431.5 545.5,-437.5 539.5,-443.5 533.5,-443.5 533.5,-443.5 256.5,-443.5 256.5,-443.5 250.5,-443.5 244.5,-437.5 244.5,-431.5 244.5,-431.5 244.5,-248.5 244.5,-248.5 244.5,-242.5 250.5,-236.5 256.5,-236.5"/>
<text text-anchor="middle" x="302.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="360.5,-236.5 360.5,-443.5 "/>
<text text-anchor="middle" x="371" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="381.5,-236.5 381.5,-443.5 "/>
<text text-anchor="middle" x="453" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="381.5,-420.5 524.5,-420.5 "/>
<text text-anchor="middle" x="453" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="381.5,-397.5 524.5,-397.5 "/>
<text text-anchor="middle" x="453" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="381.5,-374.5 524.5,-374.5 "/>
<text text-anchor="middle" x="453" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="381.5,-351.5 524.5,-351.5 "/>
<text text-anchor="middle" x="453" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="381.5,-328.5 524.5,-328.5 "/>
<text text-anchor="middle" x="453" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="381.5,-305.5 524.5,-305.5 "/>
<text text-anchor="middle" x="453" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="381.5,-282.5 524.5,-282.5 "/>
<text text-anchor="middle" x="453" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="381.5,-259.5 524.5,-259.5 "/>
<text text-anchor="middle" x="453" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="524.5,-236.5 524.5,-443.5 "/>
<text text-anchor="middle" x="535" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node6" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M285.5,-.5C285.5,-.5 504.5,-.5 504.5,-.5 510.5,-.5 516.5,-6.5 516.5,-12.5 516.5,-12.5 516.5,-172.5 516.5,-172.5 516.5,-178.5 510.5,-184.5 504.5,-184.5 504.5,-184.5 285.5,-184.5 285.5,-184.5 279.5,-184.5 273.5,-178.5 273.5,-172.5 273.5,-172.5 273.5,-12.5 273.5,-12.5 273.5,-6.5 279.5,-.5 285.5,-.5"/>
<text text-anchor="middle" x="301.5" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="329.5,-.5 329.5,-184.5 "/>
<text text-anchor="middle" x="340" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="350.5,-.5 350.5,-184.5 "/>
<text text-anchor="middle" x="423" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="350.5,-161.5 495.5,-161.5 "/>
<text text-anchor="middle" x="423" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="350.5,-138.5 495.5,-138.5 "/>
<text text-anchor="middle" x="423" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession</text>
<polyline fill="none" stroke="#000000" points="350.5,-115.5 495.5,-115.5 "/>
<text text-anchor="middle" x="423" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="350.5,-92.5 495.5,-92.5 "/>
<text text-anchor="middle" x="423" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="350.5,-69.5 495.5,-69.5 "/>
<text text-anchor="middle" x="423" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="350.5,-46.5 495.5,-46.5 "/>
<text text-anchor="middle" x="423" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="350.5,-23.5 495.5,-23.5 "/>
<text text-anchor="middle" x="423" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="495.5,-.5 495.5,-184.5 "/>
<text text-anchor="middle" x="506" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge8" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M395,-236.4718C395,-222.7494 395,-208.686 395,-194.9814"/>
<polygon fill="#000000" stroke="#000000" points="398.5001,-194.5829 395,-184.5829 391.5001,-194.5829 398.5001,-194.5829"/>
<text text-anchor="middle" x="455.5" y="-206.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- sample -->
<g id="node4" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M12,-507C12,-507 326,-507 326,-507 332,-507 338,-513 338,-519 338,-519 338,-656 338,-656 338,-662 332,-668 326,-668 326,-668 12,-668 12,-668 6,-668 0,-662 0,-656 0,-656 0,-519 0,-519 0,-513 6,-507 12,-507"/>
<text text-anchor="middle" x="34" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="68,-507 68,-668 "/>
<text text-anchor="middle" x="78.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="89,-507 89,-668 "/>
<text text-anchor="middle" x="203" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="89,-645 317,-645 "/>
<text text-anchor="middle" x="203" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="89,-622 317,-622 "/>
<text text-anchor="middle" x="203" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="89,-599 317,-599 "/>
<text text-anchor="middle" x="203" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="89,-576 317,-576 "/>
<text text-anchor="middle" x="203" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="89,-553 317,-553 "/>
<text text-anchor="middle" x="203" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="89,-530 317,-530 "/>
<text text-anchor="middle" x="203" y="-514.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="317,-507 317,-668 "/>
<text text-anchor="middle" x="327.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge7" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M145.4572,-506.9119C128.3654,-431.8293 115.4935,-319.2614 162,-236 184.7703,-195.2338 224.402,-164.6179 264.5911,-142.3674"/>
<polygon fill="#000000" stroke="#000000" points="266.2939,-145.4257 273.4403,-137.6039 262.976,-139.262 266.2939,-145.4257"/>
<text text-anchor="middle" x="198.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M227.7105,-506.9106C244.7568,-489.1285 264.8307,-472.4843 287,-462 340.7593,-436.576 498.3088,-464.8552 554,-444 584.1499,-432.7095 613.2034,-412.4833 636.7366,-392.8502"/>
<polygon fill="#000000" stroke="#000000" points="639.1627,-395.3812 644.4994,-386.2286 634.6199,-390.0555 639.1627,-395.3812"/>
<text text-anchor="middle" x="323.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- survival -->
<g id="node5" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M896.5,-495.5C896.5,-495.5 1257.5,-495.5 1257.5,-495.5 1263.5,-495.5 1269.5,-501.5 1269.5,-507.5 1269.5,-507.5 1269.5,-667.5 1269.5,-667.5 1269.5,-673.5 1263.5,-679.5 1257.5,-679.5 1257.5,-679.5 896.5,-679.5 896.5,-679.5 890.5,-679.5 884.5,-673.5 884.5,-667.5 884.5,-667.5 884.5,-507.5 884.5,-507.5 884.5,-501.5 890.5,-495.5 896.5,-495.5"/>
<text text-anchor="middle" x="921.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="958.5,-495.5 958.5,-679.5 "/>
<text text-anchor="middle" x="969" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="979.5,-495.5 979.5,-679.5 "/>
<text text-anchor="middle" x="1114" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="979.5,-656.5 1248.5,-656.5 "/>
<text text-anchor="middle" x="1114" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="979.5,-633.5 1248.5,-633.5 "/>
<text text-anchor="middle" x="1114" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="979.5,-610.5 1248.5,-610.5 "/>
<text text-anchor="middle" x="1114" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="979.5,-587.5 1248.5,-587.5 "/>
<text text-anchor="middle" x="1114" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="979.5,-564.5 1248.5,-564.5 "/>
<text text-anchor="middle" x="1114" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="979.5,-541.5 1248.5,-541.5 "/>
<text text-anchor="middle" x="1114" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="979.5,-518.5 1248.5,-518.5 "/>
<text text-anchor="middle" x="1114" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="1248.5,-495.5 1248.5,-679.5 "/>
<text text-anchor="middle" x="1259" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M933.2678,-495.3401C878.5836,-460.2771 818.2441,-421.5878 771.4625,-391.5919"/>
<polygon fill="#000000" stroke="#000000" points="773.1969,-388.5463 762.8895,-386.095 769.4185,-394.439 773.1969,-388.5463"/>
<text text-anchor="middle" x="935.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge2" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M635.6719,-293.7375C601.1737,-264.8919 555.4348,-226.6473 513.1015,-191.2504"/>
<polygon fill="#000000" stroke="#000000" points="515.1567,-188.4066 505.24,-184.677 510.6665,-193.7767 515.1567,-188.4066"/>
<text text-anchor="middle" x="593.5" y="-206.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- diagnosis -->
<g id="node8" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M89.5,-731.5C89.5,-731.5 454.5,-731.5 454.5,-731.5 460.5,-731.5 466.5,-737.5 466.5,-743.5 466.5,-743.5 466.5,-1064.5 466.5,-1064.5 466.5,-1070.5 460.5,-1076.5 454.5,-1076.5 454.5,-1076.5 89.5,-1076.5 89.5,-1076.5 83.5,-1076.5 77.5,-1070.5 77.5,-1064.5 77.5,-1064.5 77.5,-743.5 77.5,-743.5 77.5,-737.5 83.5,-731.5 89.5,-731.5"/>
<text text-anchor="middle" x="119.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="161.5,-731.5 161.5,-1076.5 "/>
<text text-anchor="middle" x="172" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="182.5,-731.5 182.5,-1076.5 "/>
<text text-anchor="middle" x="314" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="182.5,-1053.5 445.5,-1053.5 "/>
<text text-anchor="middle" x="314" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="182.5,-1030.5 445.5,-1030.5 "/>
<text text-anchor="middle" x="314" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="182.5,-1007.5 445.5,-1007.5 "/>
<text text-anchor="middle" x="314" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="182.5,-984.5 445.5,-984.5 "/>
<text text-anchor="middle" x="314" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="182.5,-961.5 445.5,-961.5 "/>
<text text-anchor="middle" x="314" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="182.5,-938.5 445.5,-938.5 "/>
<text text-anchor="middle" x="314" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="182.5,-915.5 445.5,-915.5 "/>
<text text-anchor="middle" x="314" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="182.5,-892.5 445.5,-892.5 "/>
<text text-anchor="middle" x="314" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="182.5,-869.5 445.5,-869.5 "/>
<text text-anchor="middle" x="314" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="182.5,-846.5 445.5,-846.5 "/>
<text text-anchor="middle" x="314" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="182.5,-823.5 445.5,-823.5 "/>
<text text-anchor="middle" x="314" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="182.5,-800.5 445.5,-800.5 "/>
<text text-anchor="middle" x="314" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="182.5,-777.5 445.5,-777.5 "/>
<text text-anchor="middle" x="314" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="182.5,-754.5 445.5,-754.5 "/>
<text text-anchor="middle" x="314" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="445.5,-731.5 445.5,-1076.5 "/>
<text text-anchor="middle" x="456" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M215.8285,-731.3952C209.847,-713.0154 203.9504,-694.896 198.4647,-678.0397"/>
<polygon fill="#000000" stroke="#000000" points="201.7077,-676.6945 195.2849,-668.2685 195.0513,-678.8608 201.7077,-676.6945"/>
<text text-anchor="middle" x="253.5" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M332.312,-731.3331C337.5846,-714.0811 342.5851,-696.7552 347,-680 368.3432,-599.0002 326.731,-557.0508 383,-495 436.2754,-436.2504 483.2763,-479.8879 554,-444 581.2748,-430.1597 608.6549,-410.7465 631.69,-392.4352"/>
<polygon fill="#000000" stroke="#000000" points="634.0631,-395.0177 639.6493,-386.0152 629.6683,-389.5692 634.0631,-395.0177"/>
<text text-anchor="middle" x="427.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
</g>
</svg>
</div>
