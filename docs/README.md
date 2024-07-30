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
<svg width="1612pt" height="1131pt"
 viewBox="0.00 0.00 1612.00 1131.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1127)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1127 1608,-1127 1608,4 -4,4"/>
<!-- treatment -->
<g id="node1" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M1300,-564.5C1300,-564.5 1592,-564.5 1592,-564.5 1598,-564.5 1604,-570.5 1604,-576.5 1604,-576.5 1604,-690.5 1604,-690.5 1604,-696.5 1598,-702.5 1592,-702.5 1592,-702.5 1300,-702.5 1300,-702.5 1294,-702.5 1288,-696.5 1288,-690.5 1288,-690.5 1288,-576.5 1288,-576.5 1288,-570.5 1294,-564.5 1300,-564.5"/>
<text text-anchor="middle" x="1332.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1377,-564.5 1377,-702.5 "/>
<text text-anchor="middle" x="1387.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1398,-564.5 1398,-702.5 "/>
<text text-anchor="middle" x="1490.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="1398,-679.5 1583,-679.5 "/>
<text text-anchor="middle" x="1490.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1398,-656.5 1583,-656.5 "/>
<text text-anchor="middle" x="1490.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1398,-633.5 1583,-633.5 "/>
<text text-anchor="middle" x="1490.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="1398,-610.5 1583,-610.5 "/>
<text text-anchor="middle" x="1490.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1398,-587.5 1583,-587.5 "/>
<text text-anchor="middle" x="1490.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1583,-564.5 1583,-702.5 "/>
<text text-anchor="middle" x="1593.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node8" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M575.5,-328.5C575.5,-328.5 806.5,-328.5 806.5,-328.5 812.5,-328.5 818.5,-334.5 818.5,-340.5 818.5,-340.5 818.5,-431.5 818.5,-431.5 818.5,-437.5 812.5,-443.5 806.5,-443.5 806.5,-443.5 575.5,-443.5 575.5,-443.5 569.5,-443.5 563.5,-437.5 563.5,-431.5 563.5,-431.5 563.5,-340.5 563.5,-340.5 563.5,-334.5 569.5,-328.5 575.5,-328.5"/>
<text text-anchor="middle" x="611.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="659.5,-328.5 659.5,-443.5 "/>
<text text-anchor="middle" x="670" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="680.5,-328.5 680.5,-443.5 "/>
<text text-anchor="middle" x="739" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="680.5,-420.5 797.5,-420.5 "/>
<text text-anchor="middle" x="739" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="680.5,-397.5 797.5,-397.5 "/>
<text text-anchor="middle" x="739" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="680.5,-374.5 797.5,-374.5 "/>
<text text-anchor="middle" x="739" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="680.5,-351.5 797.5,-351.5 "/>
<text text-anchor="middle" x="739" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="797.5,-328.5 797.5,-443.5 "/>
<text text-anchor="middle" x="808" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1329.6393,-564.3004C1312.9569,-555.7867 1295.7627,-547.7299 1279,-541 1129.7509,-481.079 949.9066,-437.5845 828.7341,-412.1858"/>
<polygon fill="#000000" stroke="#000000" points="829.1594,-408.6994 818.6558,-410.0867 827.732,-415.5523 829.1594,-408.6994"/>
<text text-anchor="middle" x="1264" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- reference_file -->
<g id="node2" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M256.5,-282.5C256.5,-282.5 533.5,-282.5 533.5,-282.5 539.5,-282.5 545.5,-288.5 545.5,-294.5 545.5,-294.5 545.5,-477.5 545.5,-477.5 545.5,-483.5 539.5,-489.5 533.5,-489.5 533.5,-489.5 256.5,-489.5 256.5,-489.5 250.5,-489.5 244.5,-483.5 244.5,-477.5 244.5,-477.5 244.5,-294.5 244.5,-294.5 244.5,-288.5 250.5,-282.5 256.5,-282.5"/>
<text text-anchor="middle" x="302.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="360.5,-282.5 360.5,-489.5 "/>
<text text-anchor="middle" x="371" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="381.5,-282.5 381.5,-489.5 "/>
<text text-anchor="middle" x="453" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="381.5,-466.5 524.5,-466.5 "/>
<text text-anchor="middle" x="453" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="381.5,-443.5 524.5,-443.5 "/>
<text text-anchor="middle" x="453" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="381.5,-420.5 524.5,-420.5 "/>
<text text-anchor="middle" x="453" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="381.5,-397.5 524.5,-397.5 "/>
<text text-anchor="middle" x="453" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="381.5,-374.5 524.5,-374.5 "/>
<text text-anchor="middle" x="453" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="381.5,-351.5 524.5,-351.5 "/>
<text text-anchor="middle" x="453" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="381.5,-328.5 524.5,-328.5 "/>
<text text-anchor="middle" x="453" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="381.5,-305.5 524.5,-305.5 "/>
<text text-anchor="middle" x="453" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="524.5,-282.5 524.5,-489.5 "/>
<text text-anchor="middle" x="535" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node5" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M285.5,-.5C285.5,-.5 504.5,-.5 504.5,-.5 510.5,-.5 516.5,-6.5 516.5,-12.5 516.5,-12.5 516.5,-218.5 516.5,-218.5 516.5,-224.5 510.5,-230.5 504.5,-230.5 504.5,-230.5 285.5,-230.5 285.5,-230.5 279.5,-230.5 273.5,-224.5 273.5,-218.5 273.5,-218.5 273.5,-12.5 273.5,-12.5 273.5,-6.5 279.5,-.5 285.5,-.5"/>
<text text-anchor="middle" x="301.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="329.5,-.5 329.5,-230.5 "/>
<text text-anchor="middle" x="340" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="350.5,-.5 350.5,-230.5 "/>
<text text-anchor="middle" x="423" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="350.5,-207.5 495.5,-207.5 "/>
<text text-anchor="middle" x="423" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="350.5,-184.5 495.5,-184.5 "/>
<text text-anchor="middle" x="423" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="350.5,-161.5 495.5,-161.5 "/>
<text text-anchor="middle" x="423" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession</text>
<polyline fill="none" stroke="#000000" points="350.5,-138.5 495.5,-138.5 "/>
<text text-anchor="middle" x="423" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="350.5,-115.5 495.5,-115.5 "/>
<text text-anchor="middle" x="423" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="350.5,-92.5 495.5,-92.5 "/>
<text text-anchor="middle" x="423" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="350.5,-69.5 495.5,-69.5 "/>
<text text-anchor="middle" x="423" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="350.5,-46.5 495.5,-46.5 "/>
<text text-anchor="middle" x="423" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="350.5,-23.5 495.5,-23.5 "/>
<text text-anchor="middle" x="423" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="495.5,-.5 495.5,-230.5 "/>
<text text-anchor="middle" x="506" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge3" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M395,-282.1912C395,-268.6437 395,-254.6506 395,-240.7975"/>
<polygon fill="#000000" stroke="#000000" points="398.5001,-240.7434 395,-230.7434 391.5001,-240.7435 398.5001,-240.7434"/>
<text text-anchor="middle" x="455.5" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- sample -->
<g id="node3" class="node">
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
<!-- sample&#45;&gt;study -->
<g id="edge9" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M146.6121,-552.8973C130.5287,-478.3133 118.509,-366.5324 162,-282 184.4562,-238.3526 224.2456,-203.6073 264.6592,-177.3896"/>
<polygon fill="#000000" stroke="#000000" points="266.7118,-180.2325 273.2864,-171.9244 262.9658,-174.3192 266.7118,-180.2325"/>
<text text-anchor="middle" x="198.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M227.7105,-552.9106C244.7568,-535.1285 264.8307,-518.4843 287,-508 340.7593,-482.576 498.3088,-510.8552 554,-490 578.441,-480.8473 602.1616,-465.8225 622.805,-450.0018"/>
<polygon fill="#000000" stroke="#000000" points="625.1592,-452.6031 630.8576,-443.6713 620.8329,-447.1 625.1592,-452.6031"/>
<text text-anchor="middle" x="323.5" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- treatment_response -->
<g id="node4" class="node">
<title>treatment_response</title>
<path fill="none" stroke="#000000" d="M493.5,-564.5C493.5,-564.5 854.5,-564.5 854.5,-564.5 860.5,-564.5 866.5,-570.5 866.5,-576.5 866.5,-576.5 866.5,-690.5 866.5,-690.5 866.5,-696.5 860.5,-702.5 854.5,-702.5 854.5,-702.5 493.5,-702.5 493.5,-702.5 487.5,-702.5 481.5,-696.5 481.5,-690.5 481.5,-690.5 481.5,-576.5 481.5,-576.5 481.5,-570.5 487.5,-564.5 493.5,-564.5"/>
<text text-anchor="middle" x="562" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
<polyline fill="none" stroke="#000000" points="642.5,-564.5 642.5,-702.5 "/>
<text text-anchor="middle" x="653" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="663.5,-564.5 663.5,-702.5 "/>
<text text-anchor="middle" x="754.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_response</text>
<polyline fill="none" stroke="#000000" points="663.5,-679.5 845.5,-679.5 "/>
<text text-anchor="middle" x="754.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="663.5,-656.5 845.5,-656.5 "/>
<text text-anchor="middle" x="754.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="663.5,-633.5 845.5,-633.5 "/>
<text text-anchor="middle" x="754.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_category</text>
<polyline fill="none" stroke="#000000" points="663.5,-610.5 845.5,-610.5 "/>
<text text-anchor="middle" x="754.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_system</text>
<polyline fill="none" stroke="#000000" points="663.5,-587.5 845.5,-587.5 "/>
<text text-anchor="middle" x="754.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response_id</text>
<polyline fill="none" stroke="#000000" points="845.5,-564.5 845.5,-702.5 "/>
<text text-anchor="middle" x="856" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M678.7581,-564.2283C681.1259,-529.7549 683.9778,-488.2344 686.3331,-453.9446"/>
<polygon fill="#000000" stroke="#000000" points="689.8534,-453.7673 687.047,-443.5509 682.8699,-453.2875 689.8534,-453.7673"/>
<text text-anchor="middle" x="766" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- diagnosis -->
<g id="node6" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M89.5,-777.5C89.5,-777.5 454.5,-777.5 454.5,-777.5 460.5,-777.5 466.5,-783.5 466.5,-789.5 466.5,-789.5 466.5,-1110.5 466.5,-1110.5 466.5,-1116.5 460.5,-1122.5 454.5,-1122.5 454.5,-1122.5 89.5,-1122.5 89.5,-1122.5 83.5,-1122.5 77.5,-1116.5 77.5,-1110.5 77.5,-1110.5 77.5,-789.5 77.5,-789.5 77.5,-783.5 83.5,-777.5 89.5,-777.5"/>
<text text-anchor="middle" x="119.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="161.5,-777.5 161.5,-1122.5 "/>
<text text-anchor="middle" x="172" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="182.5,-777.5 182.5,-1122.5 "/>
<text text-anchor="middle" x="314" y="-1107.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="182.5,-1099.5 445.5,-1099.5 "/>
<text text-anchor="middle" x="314" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="182.5,-1076.5 445.5,-1076.5 "/>
<text text-anchor="middle" x="314" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="182.5,-1053.5 445.5,-1053.5 "/>
<text text-anchor="middle" x="314" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="182.5,-1030.5 445.5,-1030.5 "/>
<text text-anchor="middle" x="314" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="182.5,-1007.5 445.5,-1007.5 "/>
<text text-anchor="middle" x="314" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="182.5,-984.5 445.5,-984.5 "/>
<text text-anchor="middle" x="314" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="182.5,-961.5 445.5,-961.5 "/>
<text text-anchor="middle" x="314" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="182.5,-938.5 445.5,-938.5 "/>
<text text-anchor="middle" x="314" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="182.5,-915.5 445.5,-915.5 "/>
<text text-anchor="middle" x="314" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="182.5,-892.5 445.5,-892.5 "/>
<text text-anchor="middle" x="314" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="182.5,-869.5 445.5,-869.5 "/>
<text text-anchor="middle" x="314" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="182.5,-846.5 445.5,-846.5 "/>
<text text-anchor="middle" x="314" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="182.5,-823.5 445.5,-823.5 "/>
<text text-anchor="middle" x="314" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="182.5,-800.5 445.5,-800.5 "/>
<text text-anchor="middle" x="314" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="445.5,-777.5 445.5,-1122.5 "/>
<text text-anchor="middle" x="456" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M215.8285,-777.3952C209.847,-759.0154 203.9504,-740.896 198.4647,-724.0397"/>
<polygon fill="#000000" stroke="#000000" points="201.7077,-722.6945 195.2849,-714.2685 195.0513,-724.8608 201.7077,-722.6945"/>
<text text-anchor="middle" x="253.5" y="-747.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M332.312,-777.3331C337.5846,-760.0811 342.5851,-742.7552 347,-726 368.3432,-645.0002 326.731,-603.0508 383,-541 436.2754,-482.2504 483.2763,-525.8879 554,-490 575.7664,-478.9549 597.5998,-464.3606 617.2384,-449.6095"/>
<polygon fill="#000000" stroke="#000000" points="619.4003,-452.3625 625.2249,-443.5123 615.1525,-446.7986 619.4003,-452.3625"/>
<text text-anchor="middle" x="427.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- survival -->
<g id="node7" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M896.5,-541.5C896.5,-541.5 1257.5,-541.5 1257.5,-541.5 1263.5,-541.5 1269.5,-547.5 1269.5,-553.5 1269.5,-553.5 1269.5,-713.5 1269.5,-713.5 1269.5,-719.5 1263.5,-725.5 1257.5,-725.5 1257.5,-725.5 896.5,-725.5 896.5,-725.5 890.5,-725.5 884.5,-719.5 884.5,-713.5 884.5,-713.5 884.5,-553.5 884.5,-553.5 884.5,-547.5 890.5,-541.5 896.5,-541.5"/>
<text text-anchor="middle" x="921.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="958.5,-541.5 958.5,-725.5 "/>
<text text-anchor="middle" x="969" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="979.5,-541.5 979.5,-725.5 "/>
<text text-anchor="middle" x="1114" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="979.5,-702.5 1248.5,-702.5 "/>
<text text-anchor="middle" x="1114" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="979.5,-679.5 1248.5,-679.5 "/>
<text text-anchor="middle" x="1114" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="979.5,-656.5 1248.5,-656.5 "/>
<text text-anchor="middle" x="1114" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="979.5,-633.5 1248.5,-633.5 "/>
<text text-anchor="middle" x="1114" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="979.5,-610.5 1248.5,-610.5 "/>
<text text-anchor="middle" x="1114" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="979.5,-587.5 1248.5,-587.5 "/>
<text text-anchor="middle" x="1114" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="979.5,-564.5 1248.5,-564.5 "/>
<text text-anchor="middle" x="1114" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="1248.5,-541.5 1248.5,-725.5 "/>
<text text-anchor="middle" x="1259" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M933.2678,-541.3401C885.3414,-510.6101 833.071,-477.0947 789.3909,-449.0874"/>
<polygon fill="#000000" stroke="#000000" points="791.0806,-446.0132 780.7732,-443.5618 787.3022,-451.9059 791.0806,-446.0132"/>
<text text-anchor="middle" x="935.5" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge4" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M627.8636,-328.3027C597.5875,-300.6348 560.1549,-266.4271 524.2232,-233.5908"/>
<polygon fill="#000000" stroke="#000000" points="526.3246,-230.7698 516.5816,-226.6075 521.6024,-235.9371 526.3246,-230.7698"/>
<text text-anchor="middle" x="602.5" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
</g>
</svg>
</div>
