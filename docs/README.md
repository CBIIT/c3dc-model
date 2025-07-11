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
<!-- diagnosis -->
<g id="node1" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M809,-1013.5C809,-1013.5 1174,-1013.5 1174,-1013.5 1180,-1013.5 1186,-1019.5 1186,-1025.5 1186,-1025.5 1186,-1415.5 1186,-1415.5 1186,-1421.5 1180,-1427.5 1174,-1427.5 1174,-1427.5 809,-1427.5 809,-1427.5 803,-1427.5 797,-1421.5 797,-1415.5 797,-1415.5 797,-1025.5 797,-1025.5 797,-1019.5 803,-1013.5 809,-1013.5"/>
<text text-anchor="middle" x="839" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="881,-1013.5 881,-1427.5 "/>
<text text-anchor="middle" x="891.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="902,-1013.5 902,-1427.5 "/>
<text text-anchor="middle" x="1033.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="902,-1404.5 1165,-1404.5 "/>
<text text-anchor="middle" x="1033.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="902,-1381.5 1165,-1381.5 "/>
<text text-anchor="middle" x="1033.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="902,-1358.5 1165,-1358.5 "/>
<text text-anchor="middle" x="1033.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="902,-1335.5 1165,-1335.5 "/>
<text text-anchor="middle" x="1033.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_category</text>
<polyline fill="none" stroke="#000000" points="902,-1312.5 1165,-1312.5 "/>
<text text-anchor="middle" x="1033.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="902,-1289.5 1165,-1289.5 "/>
<text text-anchor="middle" x="1033.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="902,-1266.5 1165,-1266.5 "/>
<text text-anchor="middle" x="1033.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="902,-1243.5 1165,-1243.5 "/>
<text text-anchor="middle" x="1033.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="902,-1220.5 1165,-1220.5 "/>
<text text-anchor="middle" x="1033.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="902,-1197.5 1165,-1197.5 "/>
<text text-anchor="middle" x="1033.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">laterality</text>
<polyline fill="none" stroke="#000000" points="902,-1174.5 1165,-1174.5 "/>
<text text-anchor="middle" x="1033.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="902,-1151.5 1165,-1151.5 "/>
<text text-anchor="middle" x="1033.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="902,-1128.5 1165,-1128.5 "/>
<text text-anchor="middle" x="1033.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="902,-1105.5 1165,-1105.5 "/>
<text text-anchor="middle" x="1033.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="902,-1082.5 1165,-1082.5 "/>
<text text-anchor="middle" x="1033.5" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="902,-1059.5 1165,-1059.5 "/>
<text text-anchor="middle" x="1033.5" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="902,-1036.5 1165,-1036.5 "/>
<text text-anchor="middle" x="1033.5" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1165,-1013.5 1165,-1427.5 "/>
<text text-anchor="middle" x="1175.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node5" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M686,-495.5C686,-495.5 917,-495.5 917,-495.5 923,-495.5 929,-501.5 929,-507.5 929,-507.5 929,-575.5 929,-575.5 929,-581.5 923,-587.5 917,-587.5 917,-587.5 686,-587.5 686,-587.5 680,-587.5 674,-581.5 674,-575.5 674,-575.5 674,-507.5 674,-507.5 674,-501.5 680,-495.5 686,-495.5"/>
<text text-anchor="middle" x="722" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="770,-495.5 770,-587.5 "/>
<text text-anchor="middle" x="780.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="791,-495.5 791,-587.5 "/>
<text text-anchor="middle" x="849.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="791,-564.5 908,-564.5 "/>
<text text-anchor="middle" x="849.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="791,-541.5 908,-541.5 "/>
<text text-anchor="middle" x="849.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="791,-518.5 908,-518.5 "/>
<text text-anchor="middle" x="849.5" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="908,-495.5 908,-587.5 "/>
<text text-anchor="middle" x="918.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M796.8259,-1079.8799C683.4903,-995.9076 560.0411,-899.9216 545.5,-870 500.6251,-777.6599 487.2381,-723.534 545.5,-639 560.6175,-617.0656 611.5279,-595.6572 664.0097,-578.515"/>
<polygon fill="#000000" stroke="#000000" points="665.3684,-581.7548 673.8193,-575.3646 663.228,-575.09 665.3684,-581.7548"/>
<text text-anchor="middle" x="590" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample -->
<g id="node7" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M1393.5,-651C1393.5,-651 1707.5,-651 1707.5,-651 1713.5,-651 1719.5,-657 1719.5,-663 1719.5,-663 1719.5,-846 1719.5,-846 1719.5,-852 1713.5,-858 1707.5,-858 1707.5,-858 1393.5,-858 1393.5,-858 1387.5,-858 1381.5,-852 1381.5,-846 1381.5,-846 1381.5,-663 1381.5,-663 1381.5,-657 1387.5,-651 1393.5,-651"/>
<text text-anchor="middle" x="1415.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="1449.5,-651 1449.5,-858 "/>
<text text-anchor="middle" x="1460" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1470.5,-651 1470.5,-858 "/>
<text text-anchor="middle" x="1584.5" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="1470.5,-835 1698.5,-835 "/>
<text text-anchor="middle" x="1584.5" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1470.5,-812 1698.5,-812 "/>
<text text-anchor="middle" x="1584.5" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="1470.5,-789 1698.5,-789 "/>
<text text-anchor="middle" x="1584.5" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_necrosis</text>
<polyline fill="none" stroke="#000000" points="1470.5,-766 1698.5,-766 "/>
<text text-anchor="middle" x="1584.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_tumor</text>
<polyline fill="none" stroke="#000000" points="1470.5,-743 1698.5,-743 "/>
<text text-anchor="middle" x="1584.5" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="1470.5,-720 1698.5,-720 "/>
<text text-anchor="middle" x="1584.5" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="1470.5,-697 1698.5,-697 "/>
<text text-anchor="middle" x="1584.5" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="1470.5,-674 1698.5,-674 "/>
<text text-anchor="middle" x="1584.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="1698.5,-651 1698.5,-858 "/>
<text text-anchor="middle" x="1709" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1186.2263,-1058.17C1262.8345,-994.307 1348.8278,-922.6203 1418.0181,-864.9411"/>
<polygon fill="#000000" stroke="#000000" points="1420.5014,-867.4276 1425.9414,-858.336 1416.0192,-862.0508 1420.5014,-867.4276"/>
<text text-anchor="middle" x="1429" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- consent_group -->
<g id="node2" class="node">
<title>consent_group</title>
<path fill="none" stroke="#000000" d="M429,-271C429,-271 754,-271 754,-271 760,-271 766,-277 766,-283 766,-283 766,-374 766,-374 766,-380 760,-386 754,-386 754,-386 429,-386 429,-386 423,-386 417,-380 417,-374 417,-374 417,-283 417,-283 417,-277 423,-271 429,-271"/>
<text text-anchor="middle" x="478" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
<polyline fill="none" stroke="#000000" points="539,-271 539,-386 "/>
<text text-anchor="middle" x="549.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="560,-271 560,-386 "/>
<text text-anchor="middle" x="652.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_id</text>
<polyline fill="none" stroke="#000000" points="560,-363 745,-363 "/>
<text text-anchor="middle" x="652.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_name</text>
<polyline fill="none" stroke="#000000" points="560,-340 745,-340 "/>
<text text-anchor="middle" x="652.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_number</text>
<polyline fill="none" stroke="#000000" points="560,-317 745,-317 "/>
<text text-anchor="middle" x="652.5" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_suffix</text>
<polyline fill="none" stroke="#000000" points="560,-294 745,-294 "/>
<text text-anchor="middle" x="652.5" y="-278.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="745,-271 745,-386 "/>
<text text-anchor="middle" x="755.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node4" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M482,-.5C482,-.5 701,-.5 701,-.5 707,-.5 713,-6.5 713,-12.5 713,-12.5 713,-149.5 713,-149.5 713,-155.5 707,-161.5 701,-161.5 701,-161.5 482,-161.5 482,-161.5 476,-161.5 470,-155.5 470,-149.5 470,-149.5 470,-12.5 470,-12.5 470,-6.5 476,-.5 482,-.5"/>
<text text-anchor="middle" x="498" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="526,-.5 526,-161.5 "/>
<text text-anchor="middle" x="536.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="547,-.5 547,-161.5 "/>
<text text-anchor="middle" x="619.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession</text>
<polyline fill="none" stroke="#000000" points="547,-138.5 692,-138.5 "/>
<text text-anchor="middle" x="619.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="547,-115.5 692,-115.5 "/>
<text text-anchor="middle" x="619.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="547,-92.5 692,-92.5 "/>
<text text-anchor="middle" x="619.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="547,-69.5 692,-69.5 "/>
<text text-anchor="middle" x="619.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="547,-46.5 692,-46.5 "/>
<text text-anchor="middle" x="619.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="547,-23.5 692,-23.5 "/>
<text text-anchor="middle" x="619.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
<polyline fill="none" stroke="#000000" points="692,-.5 692,-161.5 "/>
<text text-anchor="middle" x="702.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge8" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M591.5,-270.7846C591.5,-241.3997 591.5,-204.9895 591.5,-171.9435"/>
<polygon fill="#000000" stroke="#000000" points="595.0001,-171.8072 591.5,-161.8073 588.0001,-171.8073 595.0001,-171.8072"/>
<text text-anchor="middle" x="655" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- treatment_response -->
<g id="node3" class="node">
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
<!-- treatment_response&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1985.2649,-685.3885C1955.1985,-668.6906 1922.2187,-651.9491 1890.5,-639 1838.893,-617.9315 1824.472,-615.2323 1769.5,-606 1613.9123,-579.8697 1167.6521,-557.4421 939.4671,-547.2914"/>
<polygon fill="#000000" stroke="#000000" points="939.5819,-543.7931 929.4367,-546.8468 939.2719,-550.7863 939.5819,-543.7931"/>
<text text-anchor="middle" x="1923.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge1" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M755.9331,-495.2822C726.5502,-465.4795 687.9088,-426.2861 655.4683,-393.3821"/>
<polygon fill="#000000" stroke="#000000" points="657.7341,-390.695 648.2209,-386.0312 652.7493,-395.6096 657.7341,-390.695"/>
<text text-anchor="middle" x="785" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- synonym -->
<g id="node6" class="node">
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
<!-- synonym&#45;&gt;study -->
<g id="edge11" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M184.4437,-673.8824C218.095,-561.3492 291.0571,-355.0405 407.5,-213 423.1226,-193.943 442.1255,-176.3049 461.9168,-160.5332"/>
<polygon fill="#000000" stroke="#000000" points="464.1055,-163.2648 469.834,-154.3521 459.7978,-157.7472 464.1055,-163.2648"/>
<text text-anchor="middle" x="304" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M198.8059,-673.9533C214.4252,-648.1628 235.2299,-622.1366 261.5,-606 326.7912,-565.8943 526.3691,-550.7164 663.7015,-544.9786"/>
<polygon fill="#000000" stroke="#000000" points="664.0418,-548.4678 673.8917,-544.5654 663.7581,-541.4736 664.0418,-548.4678"/>
<text text-anchor="middle" x="304" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1399.4955,-650.8949C1390.5392,-646.529 1381.5074,-642.5181 1372.5,-639 1230.9602,-583.7184 1057.5865,-559.7283 939.2635,-549.3499"/>
<polygon fill="#000000" stroke="#000000" points="939.3222,-545.8422 929.0601,-548.4767 938.7252,-552.8167 939.3222,-545.8422"/>
<text text-anchor="middle" x="1349" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- genetic_analysis -->
<g id="node8" class="node">
<title>genetic_analysis</title>
<path fill="none" stroke="#000000" d="M185.5,-921.5C185.5,-921.5 569.5,-921.5 569.5,-921.5 575.5,-921.5 581.5,-927.5 581.5,-933.5 581.5,-933.5 581.5,-1507.5 581.5,-1507.5 581.5,-1513.5 575.5,-1519.5 569.5,-1519.5 569.5,-1519.5 185.5,-1519.5 185.5,-1519.5 179.5,-1519.5 173.5,-1513.5 173.5,-1507.5 173.5,-1507.5 173.5,-933.5 173.5,-933.5 173.5,-927.5 179.5,-921.5 185.5,-921.5"/>
<text text-anchor="middle" x="241" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="308.5,-921.5 308.5,-1519.5 "/>
<text text-anchor="middle" x="319" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="329.5,-921.5 329.5,-1519.5 "/>
<text text-anchor="middle" x="445" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="329.5,-1496.5 560.5,-1496.5 "/>
<text text-anchor="middle" x="445" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">allelic_ratio</text>
<polyline fill="none" stroke="#000000" points="329.5,-1473.5 560.5,-1473.5 "/>
<text text-anchor="middle" x="445" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration</text>
<polyline fill="none" stroke="#000000" points="329.5,-1450.5 560.5,-1450.5 "/>
<text text-anchor="middle" x="445" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="329.5,-1427.5 560.5,-1427.5 "/>
<text text-anchor="middle" x="445" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome_location</text>
<polyline fill="none" stroke="#000000" points="329.5,-1404.5 560.5,-1404.5 "/>
<text text-anchor="middle" x="445" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="329.5,-1381.5 560.5,-1381.5 "/>
<text text-anchor="middle" x="445" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">dna_index_numeric</text>
<polyline fill="none" stroke="#000000" points="329.5,-1358.5 560.5,-1358.5 "/>
<text text-anchor="middle" x="445" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="329.5,-1335.5 560.5,-1335.5 "/>
<text text-anchor="middle" x="445" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_exon</text>
<polyline fill="none" stroke="#000000" points="329.5,-1312.5 560.5,-1312.5 "/>
<text text-anchor="middle" x="445" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_gene</text>
<polyline fill="none" stroke="#000000" points="329.5,-1289.5 560.5,-1289.5 "/>
<text text-anchor="middle" x="445" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_transcript</text>
<polyline fill="none" stroke="#000000" points="329.5,-1266.5 560.5,-1266.5 "/>
<text text-anchor="middle" x="445" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="329.5,-1243.5 560.5,-1243.5 "/>
<text text-anchor="middle" x="445" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis_id</text>
<polyline fill="none" stroke="#000000" points="329.5,-1220.5 560.5,-1220.5 "/>
<text text-anchor="middle" x="445" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_source_category</text>
<polyline fill="none" stroke="#000000" points="329.5,-1197.5 560.5,-1197.5 "/>
<text text-anchor="middle" x="445" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_coding</text>
<polyline fill="none" stroke="#000000" points="329.5,-1174.5 560.5,-1174.5 "/>
<text text-anchor="middle" x="445" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_genome</text>
<polyline fill="none" stroke="#000000" points="329.5,-1151.5 560.5,-1151.5 "/>
<text text-anchor="middle" x="445" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_protein</text>
<polyline fill="none" stroke="#000000" points="329.5,-1128.5 560.5,-1128.5 "/>
<text text-anchor="middle" x="445" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="329.5,-1105.5 560.5,-1105.5 "/>
<text text-anchor="middle" x="445" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">karyotype</text>
<polyline fill="none" stroke="#000000" points="329.5,-1082.5 560.5,-1082.5 "/>
<text text-anchor="middle" x="445" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome</text>
<polyline fill="none" stroke="#000000" points="329.5,-1059.5 560.5,-1059.5 "/>
<text text-anchor="middle" x="445" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance</text>
<polyline fill="none" stroke="#000000" points="329.5,-1036.5 560.5,-1036.5 "/>
<text text-anchor="middle" x="445" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance_system</text>
<polyline fill="none" stroke="#000000" points="329.5,-1013.5 560.5,-1013.5 "/>
<text text-anchor="middle" x="445" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">result</text>
<polyline fill="none" stroke="#000000" points="329.5,-990.5 560.5,-990.5 "/>
<text text-anchor="middle" x="445" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="329.5,-967.5 560.5,-967.5 "/>
<text text-anchor="middle" x="445" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">test</text>
<polyline fill="none" stroke="#000000" points="329.5,-944.5 560.5,-944.5 "/>
<text text-anchor="middle" x="445" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 2 properties</text>
<polyline fill="none" stroke="#000000" points="560.5,-921.5 560.5,-1519.5 "/>
<text text-anchor="middle" x="571" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M353.7293,-921.3141C346.4278,-791.0764 344.607,-662.5611 363.5,-639 400.7544,-592.5408 549.7284,-566.7991 663.6947,-553.5996"/>
<polygon fill="#000000" stroke="#000000" points="664.3729,-557.0451 673.9138,-552.4385 663.5826,-550.0899 664.3729,-557.0451"/>
<text text-anchor="middle" x="433.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge13" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M581.6307,-1038.0446C643.7283,-992.1539 714.8719,-948.2486 787.5,-921 848.5886,-898.0808 1310.801,-891.2212 1372.5,-870 1379.2657,-867.673 1386.0293,-865.0342 1392.7523,-862.1445"/>
<polygon fill="#000000" stroke="#000000" points="1394.1936,-865.334 1401.8911,-858.054 1391.3338,-858.9448 1394.1936,-865.334"/>
<text text-anchor="middle" x="1257.5" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- treatment -->
<g id="node9" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M655.5,-639.5C655.5,-639.5 947.5,-639.5 947.5,-639.5 953.5,-639.5 959.5,-645.5 959.5,-651.5 959.5,-651.5 959.5,-857.5 959.5,-857.5 959.5,-863.5 953.5,-869.5 947.5,-869.5 947.5,-869.5 655.5,-869.5 655.5,-869.5 649.5,-869.5 643.5,-863.5 643.5,-857.5 643.5,-857.5 643.5,-651.5 643.5,-651.5 643.5,-645.5 649.5,-639.5 655.5,-639.5"/>
<text text-anchor="middle" x="688" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="732.5,-639.5 732.5,-869.5 "/>
<text text-anchor="middle" x="743" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="753.5,-639.5 753.5,-869.5 "/>
<text text-anchor="middle" x="846" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="753.5,-846.5 938.5,-846.5 "/>
<text text-anchor="middle" x="846" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="753.5,-823.5 938.5,-823.5 "/>
<text text-anchor="middle" x="846" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose</text>
<polyline fill="none" stroke="#000000" points="753.5,-800.5 938.5,-800.5 "/>
<text text-anchor="middle" x="846" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_frequency</text>
<polyline fill="none" stroke="#000000" points="753.5,-777.5 938.5,-777.5 "/>
<text text-anchor="middle" x="846" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_route</text>
<polyline fill="none" stroke="#000000" points="753.5,-754.5 938.5,-754.5 "/>
<text text-anchor="middle" x="846" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_unit</text>
<polyline fill="none" stroke="#000000" points="753.5,-731.5 938.5,-731.5 "/>
<text text-anchor="middle" x="846" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="753.5,-708.5 938.5,-708.5 "/>
<text text-anchor="middle" x="846" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="753.5,-685.5 938.5,-685.5 "/>
<text text-anchor="middle" x="846" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="753.5,-662.5 938.5,-662.5 "/>
<text text-anchor="middle" x="846" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="938.5,-639.5 938.5,-869.5 "/>
<text text-anchor="middle" x="949" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M801.5,-639.2724C801.5,-624.8861 801.5,-610.7136 801.5,-597.8145"/>
<polygon fill="#000000" stroke="#000000" points="805.0001,-597.7629 801.5,-587.7629 798.0001,-597.763 805.0001,-597.7629"/>
<text text-anchor="middle" x="848.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- reference_file -->
<g id="node10" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M796,-213.5C796,-213.5 1073,-213.5 1073,-213.5 1079,-213.5 1085,-219.5 1085,-225.5 1085,-225.5 1085,-431.5 1085,-431.5 1085,-437.5 1079,-443.5 1073,-443.5 1073,-443.5 796,-443.5 796,-443.5 790,-443.5 784,-437.5 784,-431.5 784,-431.5 784,-225.5 784,-225.5 784,-219.5 790,-213.5 796,-213.5"/>
<text text-anchor="middle" x="842" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="900,-213.5 900,-443.5 "/>
<text text-anchor="middle" x="910.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="921,-213.5 921,-443.5 "/>
<text text-anchor="middle" x="992.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="921,-420.5 1064,-420.5 "/>
<text text-anchor="middle" x="992.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="921,-397.5 1064,-397.5 "/>
<text text-anchor="middle" x="992.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="921,-374.5 1064,-374.5 "/>
<text text-anchor="middle" x="992.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="921,-351.5 1064,-351.5 "/>
<text text-anchor="middle" x="992.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="921,-328.5 1064,-328.5 "/>
<text text-anchor="middle" x="992.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="921,-305.5 1064,-305.5 "/>
<text text-anchor="middle" x="992.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="921,-282.5 1064,-282.5 "/>
<text text-anchor="middle" x="992.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="921,-259.5 1064,-259.5 "/>
<text text-anchor="middle" x="992.5" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="921,-236.5 1064,-236.5 "/>
<text text-anchor="middle" x="992.5" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="1064,-213.5 1064,-443.5 "/>
<text text-anchor="middle" x="1074.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge14" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M783.7578,-219.6806C780.6447,-217.4341 777.556,-215.2052 774.5,-213 754.1681,-198.3287 732.5639,-182.7424 711.5945,-167.6159"/>
<polygon fill="#000000" stroke="#000000" points="713.4396,-164.6313 703.2818,-161.6195 709.3444,-170.3084 713.4396,-164.6313"/>
<text text-anchor="middle" x="806" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- survival -->
<g id="node11" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M990,-662.5C990,-662.5 1351,-662.5 1351,-662.5 1357,-662.5 1363,-668.5 1363,-674.5 1363,-674.5 1363,-834.5 1363,-834.5 1363,-840.5 1357,-846.5 1351,-846.5 1351,-846.5 990,-846.5 990,-846.5 984,-846.5 978,-840.5 978,-834.5 978,-834.5 978,-674.5 978,-674.5 978,-668.5 984,-662.5 990,-662.5"/>
<text text-anchor="middle" x="1015" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="1052,-662.5 1052,-846.5 "/>
<text text-anchor="middle" x="1062.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1073,-662.5 1073,-846.5 "/>
<text text-anchor="middle" x="1207.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="1073,-823.5 1342,-823.5 "/>
<text text-anchor="middle" x="1207.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="1073,-800.5 1342,-800.5 "/>
<text text-anchor="middle" x="1207.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="1073,-777.5 1342,-777.5 "/>
<text text-anchor="middle" x="1207.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="1073,-754.5 1342,-754.5 "/>
<text text-anchor="middle" x="1207.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="1073,-731.5 1342,-731.5 "/>
<text text-anchor="middle" x="1207.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1073,-708.5 1342,-708.5 "/>
<text text-anchor="middle" x="1207.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="1073,-685.5 1342,-685.5 "/>
<text text-anchor="middle" x="1207.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="1342,-662.5 1342,-846.5 "/>
<text text-anchor="middle" x="1352.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1011.0654,-662.4687C969.7366,-638.6122 926.6982,-613.7689 890.4539,-592.8474"/>
<polygon fill="#000000" stroke="#000000" points="891.8013,-589.5839 881.3908,-587.6158 888.3018,-595.6464 891.8013,-589.5839"/>
<text text-anchor="middle" x="971" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- laboratory_test -->
<g id="node12" class="node">
<title>laboratory_test</title>
<path fill="none" stroke="#000000" d="M1501.5,-1128.5C1501.5,-1128.5 1833.5,-1128.5 1833.5,-1128.5 1839.5,-1128.5 1845.5,-1134.5 1845.5,-1140.5 1845.5,-1140.5 1845.5,-1300.5 1845.5,-1300.5 1845.5,-1306.5 1839.5,-1312.5 1833.5,-1312.5 1833.5,-1312.5 1501.5,-1312.5 1501.5,-1312.5 1495.5,-1312.5 1489.5,-1306.5 1489.5,-1300.5 1489.5,-1300.5 1489.5,-1140.5 1489.5,-1140.5 1489.5,-1134.5 1495.5,-1128.5 1501.5,-1128.5"/>
<text text-anchor="middle" x="1552.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="1615.5,-1128.5 1615.5,-1312.5 "/>
<text text-anchor="middle" x="1626" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1636.5,-1128.5 1636.5,-1312.5 "/>
<text text-anchor="middle" x="1730.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_laboratory_test</text>
<polyline fill="none" stroke="#000000" points="1636.5,-1289.5 1824.5,-1289.5 "/>
<text text-anchor="middle" x="1730.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1636.5,-1266.5 1824.5,-1266.5 "/>
<text text-anchor="middle" x="1730.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_id</text>
<polyline fill="none" stroke="#000000" points="1636.5,-1243.5 1824.5,-1243.5 "/>
<text text-anchor="middle" x="1730.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_method</text>
<polyline fill="none" stroke="#000000" points="1636.5,-1220.5 1824.5,-1220.5 "/>
<text text-anchor="middle" x="1730.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_name</text>
<polyline fill="none" stroke="#000000" points="1636.5,-1197.5 1824.5,-1197.5 "/>
<text text-anchor="middle" x="1730.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_numeric</text>
<polyline fill="none" stroke="#000000" points="1636.5,-1174.5 1824.5,-1174.5 "/>
<text text-anchor="middle" x="1730.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_text</text>
<polyline fill="none" stroke="#000000" points="1636.5,-1151.5 1824.5,-1151.5 "/>
<text text-anchor="middle" x="1730.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">test_unit</text>
<polyline fill="none" stroke="#000000" points="1824.5,-1128.5 1824.5,-1312.5 "/>
<text text-anchor="middle" x="1835" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1693.1635,-1128.4064C1731.1683,-982.8592 1791.4957,-708.969 1728.5,-639 1676.7032,-581.4696 1184.4374,-555.4699 939.0993,-546.0069"/>
<polygon fill="#000000" stroke="#000000" points="939.1676,-542.507 929.0413,-545.6228 938.9005,-549.5019 939.1676,-542.507"/>
<text text-anchor="middle" x="1821" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1644.3846,-1128.4334C1625.6402,-1053.7764 1599.1323,-948.1979 1579.0612,-868.2564"/>
<polygon fill="#000000" stroke="#000000" points="1582.3521,-866.9909 1576.5223,-858.1443 1575.5629,-868.6956 1582.3521,-866.9909"/>
<text text-anchor="middle" x="1650" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
</g>
</svg>
</div>
