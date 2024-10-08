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
<svg width="1613pt" height="1085pt"
 viewBox="0.00 0.00 1612.50 1085.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1081)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1081 1608.5,-1081 1608.5,4 -4,4"/>
<!-- reference_file -->
<g id="node1" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M471,-236.5C471,-236.5 748,-236.5 748,-236.5 754,-236.5 760,-242.5 760,-248.5 760,-248.5 760,-431.5 760,-431.5 760,-437.5 754,-443.5 748,-443.5 748,-443.5 471,-443.5 471,-443.5 465,-443.5 459,-437.5 459,-431.5 459,-431.5 459,-248.5 459,-248.5 459,-242.5 465,-236.5 471,-236.5"/>
<text text-anchor="middle" x="517" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="575,-236.5 575,-443.5 "/>
<text text-anchor="middle" x="585.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="596,-236.5 596,-443.5 "/>
<text text-anchor="middle" x="667.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="596,-420.5 739,-420.5 "/>
<text text-anchor="middle" x="667.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="596,-397.5 739,-397.5 "/>
<text text-anchor="middle" x="667.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="596,-374.5 739,-374.5 "/>
<text text-anchor="middle" x="667.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="596,-351.5 739,-351.5 "/>
<text text-anchor="middle" x="667.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="596,-328.5 739,-328.5 "/>
<text text-anchor="middle" x="667.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="596,-305.5 739,-305.5 "/>
<text text-anchor="middle" x="667.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="596,-282.5 739,-282.5 "/>
<text text-anchor="middle" x="667.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="596,-259.5 739,-259.5 "/>
<text text-anchor="middle" x="667.5" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="739,-236.5 739,-443.5 "/>
<text text-anchor="middle" x="749.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node2" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M796,-.5C796,-.5 1015,-.5 1015,-.5 1021,-.5 1027,-6.5 1027,-12.5 1027,-12.5 1027,-172.5 1027,-172.5 1027,-178.5 1021,-184.5 1015,-184.5 1015,-184.5 796,-184.5 796,-184.5 790,-184.5 784,-178.5 784,-172.5 784,-172.5 784,-12.5 784,-12.5 784,-6.5 790,-.5 796,-.5"/>
<text text-anchor="middle" x="812" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="840,-.5 840,-184.5 "/>
<text text-anchor="middle" x="850.5" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="861,-.5 861,-184.5 "/>
<text text-anchor="middle" x="933.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="861,-161.5 1006,-161.5 "/>
<text text-anchor="middle" x="933.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="861,-138.5 1006,-138.5 "/>
<text text-anchor="middle" x="933.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession</text>
<polyline fill="none" stroke="#000000" points="861,-115.5 1006,-115.5 "/>
<text text-anchor="middle" x="933.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="861,-92.5 1006,-92.5 "/>
<text text-anchor="middle" x="933.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="861,-69.5 1006,-69.5 "/>
<text text-anchor="middle" x="933.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="861,-46.5 1006,-46.5 "/>
<text text-anchor="middle" x="933.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="861,-23.5 1006,-23.5 "/>
<text text-anchor="middle" x="933.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1006,-.5 1006,-184.5 "/>
<text text-anchor="middle" x="1016.5" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge7" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M733.3156,-236.4718C751.1751,-221.5386 769.5175,-206.2016 787.2644,-191.3625"/>
<polygon fill="#000000" stroke="#000000" points="789.9461,-193.6826 795.3726,-184.5829 785.4558,-188.3125 789.9461,-193.6826"/>
<text text-anchor="middle" x="827" y="-206.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- survival -->
<g id="node3" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M541,-495.5C541,-495.5 902,-495.5 902,-495.5 908,-495.5 914,-501.5 914,-507.5 914,-507.5 914,-667.5 914,-667.5 914,-673.5 908,-679.5 902,-679.5 902,-679.5 541,-679.5 541,-679.5 535,-679.5 529,-673.5 529,-667.5 529,-667.5 529,-507.5 529,-507.5 529,-501.5 535,-495.5 541,-495.5"/>
<text text-anchor="middle" x="566" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="603,-495.5 603,-679.5 "/>
<text text-anchor="middle" x="613.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="624,-495.5 624,-679.5 "/>
<text text-anchor="middle" x="758.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="624,-656.5 893,-656.5 "/>
<text text-anchor="middle" x="758.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="624,-633.5 893,-633.5 "/>
<text text-anchor="middle" x="758.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="624,-610.5 893,-610.5 "/>
<text text-anchor="middle" x="758.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="624,-587.5 893,-587.5 "/>
<text text-anchor="middle" x="758.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="624,-564.5 893,-564.5 "/>
<text text-anchor="middle" x="758.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="624,-541.5 893,-541.5 "/>
<text text-anchor="middle" x="758.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="624,-518.5 893,-518.5 "/>
<text text-anchor="middle" x="758.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="893,-495.5 893,-679.5 "/>
<text text-anchor="middle" x="903.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node4" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M790,-294C790,-294 1021,-294 1021,-294 1027,-294 1033,-300 1033,-306 1033,-306 1033,-374 1033,-374 1033,-380 1027,-386 1021,-386 1021,-386 790,-386 790,-386 784,-386 778,-380 778,-374 778,-374 778,-306 778,-306 778,-300 784,-294 790,-294"/>
<text text-anchor="middle" x="826" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="874,-294 874,-386 "/>
<text text-anchor="middle" x="884.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="895,-294 895,-386 "/>
<text text-anchor="middle" x="953.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="895,-363 1012,-363 "/>
<text text-anchor="middle" x="953.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="895,-340 1012,-340 "/>
<text text-anchor="middle" x="953.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="895,-317 1012,-317 "/>
<text text-anchor="middle" x="953.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="1012,-294 1012,-386 "/>
<text text-anchor="middle" x="1022.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M790.0148,-495.3401C815.3248,-461.2955 843.1762,-423.8323 865.1855,-394.2273"/>
<polygon fill="#000000" stroke="#000000" points="868.074,-396.2084 871.2314,-386.095 862.4563,-392.032 868.074,-396.2084"/>
<text text-anchor="middle" x="853" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge3" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M905.5,-293.7375C905.5,-265.8494 905.5,-229.176 905.5,-194.7844"/>
<polygon fill="#000000" stroke="#000000" points="909.0001,-194.677 905.5,-184.677 902.0001,-194.6771 909.0001,-194.677"/>
<text text-anchor="middle" x="956" y="-206.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- treatment_response -->
<g id="node5" class="node">
<title>treatment_response</title>
<path fill="none" stroke="#000000" d="M12,-518.5C12,-518.5 373,-518.5 373,-518.5 379,-518.5 385,-524.5 385,-530.5 385,-530.5 385,-644.5 385,-644.5 385,-650.5 379,-656.5 373,-656.5 373,-656.5 12,-656.5 12,-656.5 6,-656.5 0,-650.5 0,-644.5 0,-644.5 0,-530.5 0,-530.5 0,-524.5 6,-518.5 12,-518.5"/>
<text text-anchor="middle" x="80.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
<polyline fill="none" stroke="#000000" points="161,-518.5 161,-656.5 "/>
<text text-anchor="middle" x="171.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="182,-518.5 182,-656.5 "/>
<text text-anchor="middle" x="273" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_response</text>
<polyline fill="none" stroke="#000000" points="182,-633.5 364,-633.5 "/>
<text text-anchor="middle" x="273" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="182,-610.5 364,-610.5 "/>
<text text-anchor="middle" x="273" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="182,-587.5 364,-587.5 "/>
<text text-anchor="middle" x="273" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_category</text>
<polyline fill="none" stroke="#000000" points="182,-564.5 364,-564.5 "/>
<text text-anchor="middle" x="273" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_system</text>
<polyline fill="none" stroke="#000000" points="182,-541.5 364,-541.5 "/>
<text text-anchor="middle" x="273" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response_id</text>
<polyline fill="none" stroke="#000000" points="364,-518.5 364,-656.5 "/>
<text text-anchor="middle" x="374.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M204.0809,-518.2355C211.2311,-496.7475 222.7956,-475.2505 241.5,-462 289.3088,-428.1315 713.2981,-463.6344 768.5,-444 799.0857,-433.1212 828.4,-412.7275 852.0072,-392.8618"/>
<polygon fill="#000000" stroke="#000000" points="854.4955,-395.3378 859.7879,-386.1595 849.927,-390.0342 854.4955,-395.3378"/>
<text text-anchor="middle" x="324.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- sample -->
<g id="node6" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1278.5,-507C1278.5,-507 1592.5,-507 1592.5,-507 1598.5,-507 1604.5,-513 1604.5,-519 1604.5,-519 1604.5,-656 1604.5,-656 1604.5,-662 1598.5,-668 1592.5,-668 1592.5,-668 1278.5,-668 1278.5,-668 1272.5,-668 1266.5,-662 1266.5,-656 1266.5,-656 1266.5,-519 1266.5,-519 1266.5,-513 1272.5,-507 1278.5,-507"/>
<text text-anchor="middle" x="1300.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1334.5,-507 1334.5,-668 "/>
<text text-anchor="middle" x="1345" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1355.5,-507 1355.5,-668 "/>
<text text-anchor="middle" x="1469.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1355.5,-645 1583.5,-645 "/>
<text text-anchor="middle" x="1469.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1355.5,-622 1583.5,-622 "/>
<text text-anchor="middle" x="1469.5" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1355.5,-599 1583.5,-599 "/>
<text text-anchor="middle" x="1469.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1355.5,-576 1583.5,-576 "/>
<text text-anchor="middle" x="1469.5" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1355.5,-553 1583.5,-553 "/>
<text text-anchor="middle" x="1469.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1355.5,-530 1583.5,-530 "/>
<text text-anchor="middle" x="1469.5" y="-514.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1583.5,-507 1583.5,-668 "/>
<text text-anchor="middle" x="1594" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge6" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1349.1668,-506.868C1257.0224,-420.8087 1110.9321,-284.3659 1011.7806,-191.7621"/>
<polygon fill="#000000" stroke="#000000" points="1014.1238,-189.1614 1004.4265,-184.8937 1009.3458,-194.2772 1014.1238,-189.1614"/>
<text text-anchor="middle" x="1310" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1281.923,-506.9074C1273.6869,-502.831 1265.5081,-498.839 1257.5,-495 1180.7277,-458.1962 1093.1117,-419.6037 1024.4979,-390.1338"/>
<polygon fill="#000000" stroke="#000000" points="1025.5154,-386.7619 1014.9454,-386.0371 1022.7564,-393.1953 1025.5154,-386.7619"/>
<text text-anchor="middle" x="1246" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- treatment -->
<g id="node7" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M944.5,-518.5C944.5,-518.5 1236.5,-518.5 1236.5,-518.5 1242.5,-518.5 1248.5,-524.5 1248.5,-530.5 1248.5,-530.5 1248.5,-644.5 1248.5,-644.5 1248.5,-650.5 1242.5,-656.5 1236.5,-656.5 1236.5,-656.5 944.5,-656.5 944.5,-656.5 938.5,-656.5 932.5,-650.5 932.5,-644.5 932.5,-644.5 932.5,-530.5 932.5,-530.5 932.5,-524.5 938.5,-518.5 944.5,-518.5"/>
<text text-anchor="middle" x="977" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1021.5,-518.5 1021.5,-656.5 "/>
<text text-anchor="middle" x="1032" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1042.5,-518.5 1042.5,-656.5 "/>
<text text-anchor="middle" x="1135" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="1042.5,-633.5 1227.5,-633.5 "/>
<text text-anchor="middle" x="1135" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1042.5,-610.5 1227.5,-610.5 "/>
<text text-anchor="middle" x="1135" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1042.5,-587.5 1227.5,-587.5 "/>
<text text-anchor="middle" x="1135" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="1042.5,-564.5 1227.5,-564.5 "/>
<text text-anchor="middle" x="1135" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1042.5,-541.5 1227.5,-541.5 "/>
<text text-anchor="middle" x="1135" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1227.5,-518.5 1227.5,-656.5 "/>
<text text-anchor="middle" x="1238" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1038.7212,-518.2283C1009.4048,-479.0077 973.2703,-430.6656 946.0338,-394.2277"/>
<polygon fill="#000000" stroke="#000000" points="948.8041,-392.0879 940.0136,-386.1736 943.1973,-396.2788 948.8041,-392.0879"/>
<text text-anchor="middle" x="1050.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- diagnosis -->
<g id="node8" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M255,-731.5C255,-731.5 620,-731.5 620,-731.5 626,-731.5 632,-737.5 632,-743.5 632,-743.5 632,-1064.5 632,-1064.5 632,-1070.5 626,-1076.5 620,-1076.5 620,-1076.5 255,-1076.5 255,-1076.5 249,-1076.5 243,-1070.5 243,-1064.5 243,-1064.5 243,-743.5 243,-743.5 243,-737.5 249,-731.5 255,-731.5"/>
<text text-anchor="middle" x="285" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="327,-731.5 327,-1076.5 "/>
<text text-anchor="middle" x="337.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="348,-731.5 348,-1076.5 "/>
<text text-anchor="middle" x="479.5" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="348,-1053.5 611,-1053.5 "/>
<text text-anchor="middle" x="479.5" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="348,-1030.5 611,-1030.5 "/>
<text text-anchor="middle" x="479.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="348,-1007.5 611,-1007.5 "/>
<text text-anchor="middle" x="479.5" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="348,-984.5 611,-984.5 "/>
<text text-anchor="middle" x="479.5" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="348,-961.5 611,-961.5 "/>
<text text-anchor="middle" x="479.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="348,-938.5 611,-938.5 "/>
<text text-anchor="middle" x="479.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="348,-915.5 611,-915.5 "/>
<text text-anchor="middle" x="479.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="348,-892.5 611,-892.5 "/>
<text text-anchor="middle" x="479.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="348,-869.5 611,-869.5 "/>
<text text-anchor="middle" x="479.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="348,-846.5 611,-846.5 "/>
<text text-anchor="middle" x="479.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="348,-823.5 611,-823.5 "/>
<text text-anchor="middle" x="479.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="348,-800.5 611,-800.5 "/>
<text text-anchor="middle" x="479.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="348,-777.5 611,-777.5 "/>
<text text-anchor="middle" x="479.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="348,-754.5 611,-754.5 "/>
<text text-anchor="middle" x="479.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="611,-731.5 611,-1076.5 "/>
<text text-anchor="middle" x="621.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M412.3671,-731.3622C402.6952,-636.1278 400.2187,-530.1932 430.5,-495 480.0441,-437.4195 698.5213,-473.5483 768.5,-444 797.6646,-431.6853 826.169,-411.7344 849.5583,-392.5839"/>
<polygon fill="#000000" stroke="#000000" points="851.8534,-395.2272 857.2878,-386.1323 847.3679,-389.8532 851.8534,-395.2272"/>
<text text-anchor="middle" x="475" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M632.1943,-863.1266C800.7443,-824.8549 1049.4627,-761.3991 1257.5,-680 1263.8192,-677.5275 1270.2076,-674.8955 1276.6181,-672.1426"/>
<polygon fill="#000000" stroke="#000000" points="1278.2629,-675.2434 1286.0205,-668.0274 1275.4561,-668.8307 1278.2629,-675.2434"/>
<text text-anchor="middle" x="1237" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
</g>
</svg>
</div>
