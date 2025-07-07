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
<svg width="2673pt" height="1269pt"
 viewBox="0.00 0.00 2673.00 1269.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1265)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1265 2669,-1265 2669,4 -4,4"/>
<!-- synonym -->
<g id="node1" class="node">
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
<!-- participant -->
<g id="node7" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M901,-328.5C901,-328.5 1132,-328.5 1132,-328.5 1138,-328.5 1144,-334.5 1144,-340.5 1144,-340.5 1144,-408.5 1144,-408.5 1144,-414.5 1138,-420.5 1132,-420.5 1132,-420.5 901,-420.5 901,-420.5 895,-420.5 889,-414.5 889,-408.5 889,-408.5 889,-340.5 889,-340.5 889,-334.5 895,-328.5 901,-328.5"/>
<text text-anchor="middle" x="937" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="985,-328.5 985,-420.5 "/>
<text text-anchor="middle" x="995.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1006,-328.5 1006,-420.5 "/>
<text text-anchor="middle" x="1064.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1006,-397.5 1123,-397.5 "/>
<text text-anchor="middle" x="1064.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1006,-374.5 1123,-374.5 "/>
<text text-anchor="middle" x="1064.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1006,-351.5 1123,-351.5 "/>
<text text-anchor="middle" x="1064.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="1123,-328.5 1123,-420.5 "/>
<text text-anchor="middle" x="1133.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M191.2993,-598.7276C207.0739,-565.6818 229.965,-530.0939 261.5,-508 359.0278,-439.6705 689.0369,-401.6414 878.9142,-384.9358"/>
<polygon fill="#000000" stroke="#000000" points="879.3113,-388.4145 888.9697,-384.0595 878.7036,-381.441 879.3113,-388.4145"/>
<text text-anchor="middle" x="304" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- study -->
<g id="node9" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M907,-.5C907,-.5 1126,-.5 1126,-.5 1132,-.5 1138,-6.5 1138,-12.5 1138,-12.5 1138,-195.5 1138,-195.5 1138,-201.5 1132,-207.5 1126,-207.5 1126,-207.5 907,-207.5 907,-207.5 901,-207.5 895,-201.5 895,-195.5 895,-195.5 895,-12.5 895,-12.5 895,-6.5 901,-.5 907,-.5"/>
<text text-anchor="middle" x="923" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="951,-.5 951,-207.5 "/>
<text text-anchor="middle" x="961.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="972,-.5 972,-207.5 "/>
<text text-anchor="middle" x="1044.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="972,-184.5 1117,-184.5 "/>
<text text-anchor="middle" x="1044.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="972,-161.5 1117,-161.5 "/>
<text text-anchor="middle" x="1044.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession</text>
<polyline fill="none" stroke="#000000" points="972,-138.5 1117,-138.5 "/>
<text text-anchor="middle" x="1044.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="972,-115.5 1117,-115.5 "/>
<text text-anchor="middle" x="1044.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="972,-92.5 1117,-92.5 "/>
<text text-anchor="middle" x="1044.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="972,-69.5 1117,-69.5 "/>
<text text-anchor="middle" x="1044.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="972,-46.5 1117,-46.5 "/>
<text text-anchor="middle" x="1044.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="972,-23.5 1117,-23.5 "/>
<text text-anchor="middle" x="1044.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
<polyline fill="none" stroke="#000000" points="1117,-.5 1117,-207.5 "/>
<text text-anchor="middle" x="1127.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge2" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M187.0505,-598.6514C199.5412,-567.5291 217.3108,-533.4011 241.5,-508 423.6955,-316.6765 716.5725,-198.7173 885.2839,-142.8327"/>
<polygon fill="#000000" stroke="#000000" points="886.5612,-146.0972 894.9673,-139.6482 884.3743,-139.4475 886.5612,-146.0972"/>
<text text-anchor="middle" x="639" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- diagnosis -->
<g id="node2" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M194,-869.5C194,-869.5 559,-869.5 559,-869.5 565,-869.5 571,-875.5 571,-881.5 571,-881.5 571,-1248.5 571,-1248.5 571,-1254.5 565,-1260.5 559,-1260.5 559,-1260.5 194,-1260.5 194,-1260.5 188,-1260.5 182,-1254.5 182,-1248.5 182,-1248.5 182,-881.5 182,-881.5 182,-875.5 188,-869.5 194,-869.5"/>
<text text-anchor="middle" x="224" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="266,-869.5 266,-1260.5 "/>
<text text-anchor="middle" x="276.5" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="287,-869.5 287,-1260.5 "/>
<text text-anchor="middle" x="418.5" y="-1245.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="287,-1237.5 550,-1237.5 "/>
<text text-anchor="middle" x="418.5" y="-1222.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="287,-1214.5 550,-1214.5 "/>
<text text-anchor="middle" x="418.5" y="-1199.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="287,-1191.5 550,-1191.5 "/>
<text text-anchor="middle" x="418.5" y="-1176.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="287,-1168.5 550,-1168.5 "/>
<text text-anchor="middle" x="418.5" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="287,-1145.5 550,-1145.5 "/>
<text text-anchor="middle" x="418.5" y="-1130.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="287,-1122.5 550,-1122.5 "/>
<text text-anchor="middle" x="418.5" y="-1107.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="287,-1099.5 550,-1099.5 "/>
<text text-anchor="middle" x="418.5" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="287,-1076.5 550,-1076.5 "/>
<text text-anchor="middle" x="418.5" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="287,-1053.5 550,-1053.5 "/>
<text text-anchor="middle" x="418.5" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">laterality</text>
<polyline fill="none" stroke="#000000" points="287,-1030.5 550,-1030.5 "/>
<text text-anchor="middle" x="418.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="287,-1007.5 550,-1007.5 "/>
<text text-anchor="middle" x="418.5" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="287,-984.5 550,-984.5 "/>
<text text-anchor="middle" x="418.5" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="287,-961.5 550,-961.5 "/>
<text text-anchor="middle" x="418.5" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="287,-938.5 550,-938.5 "/>
<text text-anchor="middle" x="418.5" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="287,-915.5 550,-915.5 "/>
<text text-anchor="middle" x="418.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="287,-892.5 550,-892.5 "/>
<text text-anchor="middle" x="418.5" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="550,-869.5 550,-1260.5 "/>
<text text-anchor="middle" x="560.5" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M349.3144,-869.373C336.1912,-742.2435 330.6194,-591.153 369.5,-541 431.2936,-461.2911 707.7206,-413.0409 878.6458,-390.293"/>
<polygon fill="#000000" stroke="#000000" points="879.2753,-393.7404 888.7323,-388.9639 878.3608,-386.8004 879.2753,-393.7404"/>
<text text-anchor="middle" x="414" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample -->
<g id="node11" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M479.5,-576C479.5,-576 793.5,-576 793.5,-576 799.5,-576 805.5,-582 805.5,-588 805.5,-588 805.5,-771 805.5,-771 805.5,-777 799.5,-783 793.5,-783 793.5,-783 479.5,-783 479.5,-783 473.5,-783 467.5,-777 467.5,-771 467.5,-771 467.5,-588 467.5,-588 467.5,-582 473.5,-576 479.5,-576"/>
<text text-anchor="middle" x="501.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="535.5,-576 535.5,-783 "/>
<text text-anchor="middle" x="546" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="556.5,-576 556.5,-783 "/>
<text text-anchor="middle" x="670.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="556.5,-760 784.5,-760 "/>
<text text-anchor="middle" x="670.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="556.5,-737 784.5,-737 "/>
<text text-anchor="middle" x="670.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="556.5,-714 784.5,-714 "/>
<text text-anchor="middle" x="670.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_necrosis</text>
<polyline fill="none" stroke="#000000" points="556.5,-691 784.5,-691 "/>
<text text-anchor="middle" x="670.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_tumor</text>
<polyline fill="none" stroke="#000000" points="556.5,-668 784.5,-668 "/>
<text text-anchor="middle" x="670.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="556.5,-645 784.5,-645 "/>
<text text-anchor="middle" x="670.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="556.5,-622 784.5,-622 "/>
<text text-anchor="middle" x="670.5" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="556.5,-599 784.5,-599 "/>
<text text-anchor="middle" x="670.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="784.5,-576 784.5,-783 "/>
<text text-anchor="middle" x="795" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M508.4042,-869.4266C526.3952,-842.7515 544.3376,-816.1485 560.8527,-791.6617"/>
<polygon fill="#000000" stroke="#000000" points="563.9425,-793.3398 566.6324,-783.0921 558.1391,-789.4256 563.9425,-793.3398"/>
<text text-anchor="middle" x="575" y="-839.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- treatment_response -->
<g id="node3" class="node">
<title>treatment_response</title>
<path fill="none" stroke="#000000" d="M836,-610.5C836,-610.5 1197,-610.5 1197,-610.5 1203,-610.5 1209,-616.5 1209,-622.5 1209,-622.5 1209,-736.5 1209,-736.5 1209,-742.5 1203,-748.5 1197,-748.5 1197,-748.5 836,-748.5 836,-748.5 830,-748.5 824,-742.5 824,-736.5 824,-736.5 824,-622.5 824,-622.5 824,-616.5 830,-610.5 836,-610.5"/>
<text text-anchor="middle" x="904.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
<polyline fill="none" stroke="#000000" points="985,-610.5 985,-748.5 "/>
<text text-anchor="middle" x="995.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1006,-610.5 1006,-748.5 "/>
<text text-anchor="middle" x="1097" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_response</text>
<polyline fill="none" stroke="#000000" points="1006,-725.5 1188,-725.5 "/>
<text text-anchor="middle" x="1097" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1006,-702.5 1188,-702.5 "/>
<text text-anchor="middle" x="1097" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="1006,-679.5 1188,-679.5 "/>
<text text-anchor="middle" x="1097" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_category</text>
<polyline fill="none" stroke="#000000" points="1006,-656.5 1188,-656.5 "/>
<text text-anchor="middle" x="1097" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_system</text>
<polyline fill="none" stroke="#000000" points="1006,-633.5 1188,-633.5 "/>
<text text-anchor="middle" x="1097" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response_id</text>
<polyline fill="none" stroke="#000000" points="1188,-610.5 1188,-748.5 "/>
<text text-anchor="middle" x="1198.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1016.5,-610.2908C1016.5,-556.0291 1016.5,-481.4733 1016.5,-430.8269"/>
<polygon fill="#000000" stroke="#000000" points="1020.0001,-430.7142 1016.5,-420.7142 1013.0001,-430.7142 1020.0001,-430.7142"/>
<text text-anchor="middle" x="1099.5" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- treatment -->
<g id="node4" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M1239.5,-564.5C1239.5,-564.5 1531.5,-564.5 1531.5,-564.5 1537.5,-564.5 1543.5,-570.5 1543.5,-576.5 1543.5,-576.5 1543.5,-782.5 1543.5,-782.5 1543.5,-788.5 1537.5,-794.5 1531.5,-794.5 1531.5,-794.5 1239.5,-794.5 1239.5,-794.5 1233.5,-794.5 1227.5,-788.5 1227.5,-782.5 1227.5,-782.5 1227.5,-576.5 1227.5,-576.5 1227.5,-570.5 1233.5,-564.5 1239.5,-564.5"/>
<text text-anchor="middle" x="1272" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1316.5,-564.5 1316.5,-794.5 "/>
<text text-anchor="middle" x="1327" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1337.5,-564.5 1337.5,-794.5 "/>
<text text-anchor="middle" x="1430" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="1337.5,-771.5 1522.5,-771.5 "/>
<text text-anchor="middle" x="1430" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1337.5,-748.5 1522.5,-748.5 "/>
<text text-anchor="middle" x="1430" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose</text>
<polyline fill="none" stroke="#000000" points="1337.5,-725.5 1522.5,-725.5 "/>
<text text-anchor="middle" x="1430" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_frequency</text>
<polyline fill="none" stroke="#000000" points="1337.5,-702.5 1522.5,-702.5 "/>
<text text-anchor="middle" x="1430" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_route</text>
<polyline fill="none" stroke="#000000" points="1337.5,-679.5 1522.5,-679.5 "/>
<text text-anchor="middle" x="1430" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_unit</text>
<polyline fill="none" stroke="#000000" points="1337.5,-656.5 1522.5,-656.5 "/>
<text text-anchor="middle" x="1430" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1337.5,-633.5 1522.5,-633.5 "/>
<text text-anchor="middle" x="1430" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="1337.5,-610.5 1522.5,-610.5 "/>
<text text-anchor="middle" x="1430" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1337.5,-587.5 1522.5,-587.5 "/>
<text text-anchor="middle" x="1430" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1522.5,-564.5 1522.5,-794.5 "/>
<text text-anchor="middle" x="1533" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1260.441,-564.3703C1236.6271,-544.5954 1211.359,-524.9743 1186.5,-508 1172.3797,-498.3583 1166.6551,-499.5905 1152.5,-490 1124.9626,-471.3427 1096.5987,-448.0162 1072.9466,-427.22"/>
<polygon fill="#000000" stroke="#000000" points="1075.245,-424.5801 1065.44,-420.566 1070.6017,-429.8185 1075.245,-424.5801"/>
<text text-anchor="middle" x="1251.5" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- genetic_analysis -->
<g id="node5" class="node">
<title>genetic_analysis</title>
<path fill="none" stroke="#000000" d="M1574,-553C1574,-553 1917,-553 1917,-553 1923,-553 1929,-559 1929,-565 1929,-565 1929,-794 1929,-794 1929,-800 1923,-806 1917,-806 1917,-806 1574,-806 1574,-806 1568,-806 1562,-800 1562,-794 1562,-794 1562,-565 1562,-565 1562,-559 1568,-553 1574,-553"/>
<text text-anchor="middle" x="1629.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="1697,-553 1697,-806 "/>
<text text-anchor="middle" x="1707.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1718,-553 1718,-806 "/>
<text text-anchor="middle" x="1813" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="1718,-783 1908,-783 "/>
<text text-anchor="middle" x="1813" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">allelic_ratio</text>
<polyline fill="none" stroke="#000000" points="1718,-760 1908,-760 "/>
<text text-anchor="middle" x="1813" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">alteration</text>
<polyline fill="none" stroke="#000000" points="1718,-737 1908,-737 "/>
<text text-anchor="middle" x="1813" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">dna_index_numeric</text>
<polyline fill="none" stroke="#000000" points="1718,-714 1908,-714 "/>
<text text-anchor="middle" x="1813" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis_id</text>
<polyline fill="none" stroke="#000000" points="1718,-691 1908,-691 "/>
<text text-anchor="middle" x="1813" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_coding</text>
<polyline fill="none" stroke="#000000" points="1718,-668 1908,-668 "/>
<text text-anchor="middle" x="1813" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_protein</text>
<polyline fill="none" stroke="#000000" points="1718,-645 1908,-645 "/>
<text text-anchor="middle" x="1813" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1718,-622 1908,-622 "/>
<text text-anchor="middle" x="1813" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">iscn</text>
<polyline fill="none" stroke="#000000" points="1718,-599 1908,-599 "/>
<text text-anchor="middle" x="1813" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="1718,-576 1908,-576 "/>
<text text-anchor="middle" x="1813" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">vaf_numeric</text>
<polyline fill="none" stroke="#000000" points="1908,-553 1908,-806 "/>
<text text-anchor="middle" x="1918.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1579.0964,-552.9699C1570.3042,-548.5586 1561.4159,-544.5286 1552.5,-541 1448.2894,-499.7575 1413.6958,-522.0102 1302.5,-508 1235.8817,-499.6064 1214.0332,-516.8722 1152.5,-490 1119.6986,-475.6753 1088.8012,-450.7518 1064.7715,-427.7154"/>
<polygon fill="#000000" stroke="#000000" points="1067.1357,-425.132 1057.5399,-420.6406 1062.2405,-430.1357 1067.1357,-425.132"/>
<text text-anchor="middle" x="1562.5" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- survival -->
<g id="node6" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M1959,-587.5C1959,-587.5 2320,-587.5 2320,-587.5 2326,-587.5 2332,-593.5 2332,-599.5 2332,-599.5 2332,-759.5 2332,-759.5 2332,-765.5 2326,-771.5 2320,-771.5 2320,-771.5 1959,-771.5 1959,-771.5 1953,-771.5 1947,-765.5 1947,-759.5 1947,-759.5 1947,-599.5 1947,-599.5 1947,-593.5 1953,-587.5 1959,-587.5"/>
<text text-anchor="middle" x="1984" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="2021,-587.5 2021,-771.5 "/>
<text text-anchor="middle" x="2031.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2042,-587.5 2042,-771.5 "/>
<text text-anchor="middle" x="2176.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="2042,-748.5 2311,-748.5 "/>
<text text-anchor="middle" x="2176.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="2042,-725.5 2311,-725.5 "/>
<text text-anchor="middle" x="2176.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="2042,-702.5 2311,-702.5 "/>
<text text-anchor="middle" x="2176.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="2042,-679.5 2311,-679.5 "/>
<text text-anchor="middle" x="2176.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="2042,-656.5 2311,-656.5 "/>
<text text-anchor="middle" x="2176.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2042,-633.5 2311,-633.5 "/>
<text text-anchor="middle" x="2176.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="2042,-610.5 2311,-610.5 "/>
<text text-anchor="middle" x="2176.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="2311,-587.5 2311,-771.5 "/>
<text text-anchor="middle" x="2321.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2026.4357,-587.3809C1999.0597,-569.2167 1968.8853,-552.3017 1938.5,-541 1811.9492,-493.9298 1771.1615,-517.8486 1636.5,-508 1582.8284,-504.0747 1202.6611,-509.4914 1152.5,-490 1118.614,-476.8327 1087.2149,-451.4643 1063.1442,-427.8489"/>
<polygon fill="#000000" stroke="#000000" points="1065.4518,-425.2061 1055.9146,-420.5917 1060.4926,-430.1465 1065.4518,-425.2061"/>
<text text-anchor="middle" x="1917" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge6" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1016.5,-328.3067C1016.5,-297.9024 1016.5,-256.6891 1016.5,-217.8833"/>
<polygon fill="#000000" stroke="#000000" points="1020.0001,-217.5472 1016.5,-207.5472 1013.0001,-217.5472 1020.0001,-217.5472"/>
<text text-anchor="middle" x="1067" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- laboratory_test -->
<g id="node8" class="node">
<title>laboratory_test</title>
<path fill="none" stroke="#000000" d="M2362,-541.5C2362,-541.5 2653,-541.5 2653,-541.5 2659,-541.5 2665,-547.5 2665,-553.5 2665,-553.5 2665,-805.5 2665,-805.5 2665,-811.5 2659,-817.5 2653,-817.5 2653,-817.5 2362,-817.5 2362,-817.5 2356,-817.5 2350,-811.5 2350,-805.5 2350,-805.5 2350,-553.5 2350,-553.5 2350,-547.5 2356,-541.5 2362,-541.5"/>
<text text-anchor="middle" x="2413" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="2476,-541.5 2476,-817.5 "/>
<text text-anchor="middle" x="2486.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2497,-541.5 2497,-817.5 "/>
<text text-anchor="middle" x="2570.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_lab</text>
<polyline fill="none" stroke="#000000" points="2497,-794.5 2644,-794.5 "/>
<text text-anchor="middle" x="2570.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2497,-771.5 2644,-771.5 "/>
<text text-anchor="middle" x="2570.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_id</text>
<polyline fill="none" stroke="#000000" points="2497,-748.5 2644,-748.5 "/>
<text text-anchor="middle" x="2570.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">method</text>
<polyline fill="none" stroke="#000000" points="2497,-725.5 2644,-725.5 "/>
<text text-anchor="middle" x="2570.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">result</text>
<polyline fill="none" stroke="#000000" points="2497,-702.5 2644,-702.5 "/>
<text text-anchor="middle" x="2570.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">result_modifier</text>
<polyline fill="none" stroke="#000000" points="2497,-679.5 2644,-679.5 "/>
<text text-anchor="middle" x="2570.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">result_numeric</text>
<polyline fill="none" stroke="#000000" points="2497,-656.5 2644,-656.5 "/>
<text text-anchor="middle" x="2570.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">result_text</text>
<polyline fill="none" stroke="#000000" points="2497,-633.5 2644,-633.5 "/>
<text text-anchor="middle" x="2570.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">result_unit</text>
<polyline fill="none" stroke="#000000" points="2497,-610.5 2644,-610.5 "/>
<text text-anchor="middle" x="2570.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">sensitivity</text>
<polyline fill="none" stroke="#000000" points="2497,-587.5 2644,-587.5 "/>
<text text-anchor="middle" x="2570.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">specimen</text>
<polyline fill="none" stroke="#000000" points="2497,-564.5 2644,-564.5 "/>
<text text-anchor="middle" x="2570.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">test</text>
<polyline fill="none" stroke="#000000" points="2644,-541.5 2644,-817.5 "/>
<text text-anchor="middle" x="2654.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2349.7923,-544.6181C2347.041,-543.3517 2344.2762,-542.144 2341.5,-541 2184.3516,-476.2445 2130.2165,-517.2308 1960.5,-508 1915.6662,-505.5615 1194.4714,-505.9503 1152.5,-490 1118.3857,-477.0356 1086.8672,-451.5422 1062.7805,-427.7973"/>
<polygon fill="#000000" stroke="#000000" points="1065.0742,-425.1396 1055.5492,-420.5001 1060.1021,-430.0669 1065.0742,-425.1396"/>
<text text-anchor="middle" x="2354" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- reference_file -->
<g id="node10" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M1174,-259.5C1174,-259.5 1451,-259.5 1451,-259.5 1457,-259.5 1463,-265.5 1463,-271.5 1463,-271.5 1463,-477.5 1463,-477.5 1463,-483.5 1457,-489.5 1451,-489.5 1451,-489.5 1174,-489.5 1174,-489.5 1168,-489.5 1162,-483.5 1162,-477.5 1162,-477.5 1162,-271.5 1162,-271.5 1162,-265.5 1168,-259.5 1174,-259.5"/>
<text text-anchor="middle" x="1220" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="1278,-259.5 1278,-489.5 "/>
<text text-anchor="middle" x="1288.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1299,-259.5 1299,-489.5 "/>
<text text-anchor="middle" x="1370.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1299,-466.5 1442,-466.5 "/>
<text text-anchor="middle" x="1370.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="1299,-443.5 1442,-443.5 "/>
<text text-anchor="middle" x="1370.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1299,-420.5 1442,-420.5 "/>
<text text-anchor="middle" x="1370.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1299,-397.5 1442,-397.5 "/>
<text text-anchor="middle" x="1370.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1299,-374.5 1442,-374.5 "/>
<text text-anchor="middle" x="1370.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1299,-351.5 1442,-351.5 "/>
<text text-anchor="middle" x="1370.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1299,-328.5 1442,-328.5 "/>
<text text-anchor="middle" x="1370.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1299,-305.5 1442,-305.5 "/>
<text text-anchor="middle" x="1370.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="1299,-282.5 1442,-282.5 "/>
<text text-anchor="middle" x="1370.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="1442,-259.5 1442,-489.5 "/>
<text text-anchor="middle" x="1452.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge12" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1186.5401,-259.3914C1170.3023,-244.5524 1153.7023,-229.3825 1137.5459,-214.6179"/>
<polygon fill="#000000" stroke="#000000" points="1139.8998,-212.0277 1130.1568,-207.8654 1135.1776,-217.195 1139.8998,-212.0277"/>
<text text-anchor="middle" x="1225" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M765.6809,-575.8153C828.0748,-525.7361 900.2506,-467.8054 951.1127,-426.9819"/>
<polygon fill="#000000" stroke="#000000" points="953.4802,-429.5697 959.088,-420.5807 949.0985,-424.1106 953.4802,-429.5697"/>
<text text-anchor="middle" x="886" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
</g>
</svg>
</div>
