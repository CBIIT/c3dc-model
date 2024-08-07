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
<svg width="1622pt" height="1085pt"
 viewBox="0.00 0.00 1622.00 1085.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1081)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1081 1618,-1081 1618,4 -4,4"/>
<!-- participant -->
<g id="node1" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M646.5,-294C646.5,-294 877.5,-294 877.5,-294 883.5,-294 889.5,-300 889.5,-306 889.5,-306 889.5,-374 889.5,-374 889.5,-380 883.5,-386 877.5,-386 877.5,-386 646.5,-386 646.5,-386 640.5,-386 634.5,-380 634.5,-374 634.5,-374 634.5,-306 634.5,-306 634.5,-300 640.5,-294 646.5,-294"/>
<text text-anchor="middle" x="682.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="730.5,-294 730.5,-386 "/>
<text text-anchor="middle" x="741" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="751.5,-294 751.5,-386 "/>
<text text-anchor="middle" x="810" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="751.5,-363 868.5,-363 "/>
<text text-anchor="middle" x="810" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="751.5,-340 868.5,-340 "/>
<text text-anchor="middle" x="810" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="751.5,-317 868.5,-317 "/>
<text text-anchor="middle" x="810" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="868.5,-294 868.5,-386 "/>
<text text-anchor="middle" x="879" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node5" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M243.5,-.5C243.5,-.5 462.5,-.5 462.5,-.5 468.5,-.5 474.5,-6.5 474.5,-12.5 474.5,-12.5 474.5,-172.5 474.5,-172.5 474.5,-178.5 468.5,-184.5 462.5,-184.5 462.5,-184.5 243.5,-184.5 243.5,-184.5 237.5,-184.5 231.5,-178.5 231.5,-172.5 231.5,-172.5 231.5,-12.5 231.5,-12.5 231.5,-6.5 237.5,-.5 243.5,-.5"/>
<text text-anchor="middle" x="259.5" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="287.5,-.5 287.5,-184.5 "/>
<text text-anchor="middle" x="298" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="308.5,-.5 308.5,-184.5 "/>
<text text-anchor="middle" x="381" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="308.5,-161.5 453.5,-161.5 "/>
<text text-anchor="middle" x="381" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="308.5,-138.5 453.5,-138.5 "/>
<text text-anchor="middle" x="381" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession</text>
<polyline fill="none" stroke="#000000" points="308.5,-115.5 453.5,-115.5 "/>
<text text-anchor="middle" x="381" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="308.5,-92.5 453.5,-92.5 "/>
<text text-anchor="middle" x="381" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="308.5,-69.5 453.5,-69.5 "/>
<text text-anchor="middle" x="381" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="308.5,-46.5 453.5,-46.5 "/>
<text text-anchor="middle" x="381" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="308.5,-23.5 453.5,-23.5 "/>
<text text-anchor="middle" x="381" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="453.5,-.5 453.5,-184.5 "/>
<text text-anchor="middle" x="464" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge1" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M685.55,-293.7375C628.9036,-259.4588 550.3232,-211.9071 483.7711,-171.6341"/>
<polygon fill="#000000" stroke="#000000" points="485.2503,-168.4383 474.8827,-166.2554 481.6262,-174.4271 485.2503,-168.4383"/>
<text text-anchor="middle" x="608.5" y="-206.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- treatment_response -->
<g id="node2" class="node">
<title>treatment_response</title>
<path fill="none" stroke="#000000" d="M368.5,-518.5C368.5,-518.5 729.5,-518.5 729.5,-518.5 735.5,-518.5 741.5,-524.5 741.5,-530.5 741.5,-530.5 741.5,-644.5 741.5,-644.5 741.5,-650.5 735.5,-656.5 729.5,-656.5 729.5,-656.5 368.5,-656.5 368.5,-656.5 362.5,-656.5 356.5,-650.5 356.5,-644.5 356.5,-644.5 356.5,-530.5 356.5,-530.5 356.5,-524.5 362.5,-518.5 368.5,-518.5"/>
<text text-anchor="middle" x="437" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
<polyline fill="none" stroke="#000000" points="517.5,-518.5 517.5,-656.5 "/>
<text text-anchor="middle" x="528" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="538.5,-518.5 538.5,-656.5 "/>
<text text-anchor="middle" x="629.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_response</text>
<polyline fill="none" stroke="#000000" points="538.5,-633.5 720.5,-633.5 "/>
<text text-anchor="middle" x="629.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="538.5,-610.5 720.5,-610.5 "/>
<text text-anchor="middle" x="629.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="538.5,-587.5 720.5,-587.5 "/>
<text text-anchor="middle" x="629.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_category</text>
<polyline fill="none" stroke="#000000" points="538.5,-564.5 720.5,-564.5 "/>
<text text-anchor="middle" x="629.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_system</text>
<polyline fill="none" stroke="#000000" points="538.5,-541.5 720.5,-541.5 "/>
<text text-anchor="middle" x="629.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response_id</text>
<polyline fill="none" stroke="#000000" points="720.5,-518.5 720.5,-656.5 "/>
<text text-anchor="middle" x="731" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M608.6156,-518.2283C642.5109,-478.8429 684.3224,-430.2592 715.7261,-393.769"/>
<polygon fill="#000000" stroke="#000000" points="718.3925,-396.0363 722.2627,-386.1736 713.0868,-391.4701 718.3925,-396.0363"/>
<text text-anchor="middle" x="739" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- survival -->
<g id="node3" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M771.5,-495.5C771.5,-495.5 1132.5,-495.5 1132.5,-495.5 1138.5,-495.5 1144.5,-501.5 1144.5,-507.5 1144.5,-507.5 1144.5,-667.5 1144.5,-667.5 1144.5,-673.5 1138.5,-679.5 1132.5,-679.5 1132.5,-679.5 771.5,-679.5 771.5,-679.5 765.5,-679.5 759.5,-673.5 759.5,-667.5 759.5,-667.5 759.5,-507.5 759.5,-507.5 759.5,-501.5 765.5,-495.5 771.5,-495.5"/>
<text text-anchor="middle" x="796.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="833.5,-495.5 833.5,-679.5 "/>
<text text-anchor="middle" x="844" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="854.5,-495.5 854.5,-679.5 "/>
<text text-anchor="middle" x="989" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="854.5,-656.5 1123.5,-656.5 "/>
<text text-anchor="middle" x="989" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="854.5,-633.5 1123.5,-633.5 "/>
<text text-anchor="middle" x="989" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="854.5,-610.5 1123.5,-610.5 "/>
<text text-anchor="middle" x="989" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="854.5,-587.5 1123.5,-587.5 "/>
<text text-anchor="middle" x="989" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="854.5,-564.5 1123.5,-564.5 "/>
<text text-anchor="middle" x="989" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="854.5,-541.5 1123.5,-541.5 "/>
<text text-anchor="middle" x="989" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="854.5,-518.5 1123.5,-518.5 "/>
<text text-anchor="middle" x="989" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="1123.5,-495.5 1123.5,-679.5 "/>
<text text-anchor="middle" x="1134" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M881.251,-495.3401C855.1157,-461.2955 826.3561,-423.8323 803.6291,-394.2273"/>
<polygon fill="#000000" stroke="#000000" points="806.2517,-391.8959 797.386,-386.095 800.6992,-396.1585 806.2517,-391.8959"/>
<text text-anchor="middle" x="902.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- diagnosis -->
<g id="node4" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M659.5,-731.5C659.5,-731.5 1024.5,-731.5 1024.5,-731.5 1030.5,-731.5 1036.5,-737.5 1036.5,-743.5 1036.5,-743.5 1036.5,-1064.5 1036.5,-1064.5 1036.5,-1070.5 1030.5,-1076.5 1024.5,-1076.5 1024.5,-1076.5 659.5,-1076.5 659.5,-1076.5 653.5,-1076.5 647.5,-1070.5 647.5,-1064.5 647.5,-1064.5 647.5,-743.5 647.5,-743.5 647.5,-737.5 653.5,-731.5 659.5,-731.5"/>
<text text-anchor="middle" x="689.5" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="731.5,-731.5 731.5,-1076.5 "/>
<text text-anchor="middle" x="742" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="752.5,-731.5 752.5,-1076.5 "/>
<text text-anchor="middle" x="884" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="752.5,-1053.5 1015.5,-1053.5 "/>
<text text-anchor="middle" x="884" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="752.5,-1030.5 1015.5,-1030.5 "/>
<text text-anchor="middle" x="884" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="752.5,-1007.5 1015.5,-1007.5 "/>
<text text-anchor="middle" x="884" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="752.5,-984.5 1015.5,-984.5 "/>
<text text-anchor="middle" x="884" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="752.5,-961.5 1015.5,-961.5 "/>
<text text-anchor="middle" x="884" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="752.5,-938.5 1015.5,-938.5 "/>
<text text-anchor="middle" x="884" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="752.5,-915.5 1015.5,-915.5 "/>
<text text-anchor="middle" x="884" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="752.5,-892.5 1015.5,-892.5 "/>
<text text-anchor="middle" x="884" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="752.5,-869.5 1015.5,-869.5 "/>
<text text-anchor="middle" x="884" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="752.5,-846.5 1015.5,-846.5 "/>
<text text-anchor="middle" x="884" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="752.5,-823.5 1015.5,-823.5 "/>
<text text-anchor="middle" x="884" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="752.5,-800.5 1015.5,-800.5 "/>
<text text-anchor="middle" x="884" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="752.5,-777.5 1015.5,-777.5 "/>
<text text-anchor="middle" x="884" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="752.5,-754.5 1015.5,-754.5 "/>
<text text-anchor="middle" x="884" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1015.5,-731.5 1015.5,-1076.5 "/>
<text text-anchor="middle" x="1026" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1036.5399,-862.5982C1206.5397,-822.0074 1434.3579,-755.3758 1488,-680 1535.6743,-613.01 1539.7153,-558.922 1488,-495 1415.4297,-405.3006 1089.2404,-365.2529 899.6928,-349.2814"/>
<polygon fill="#000000" stroke="#000000" points="899.9072,-345.7873 889.6517,-348.4471 899.3275,-352.7632 899.9072,-345.7873"/>
<text text-anchor="middle" x="1569.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- sample -->
<g id="node8" class="node">
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
<!-- diagnosis&#45;&gt;sample -->
<g id="edge7" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M647.2157,-818.7867C555.5714,-777.948 445.1079,-727.6462 347,-680 342.1051,-677.6228 337.1446,-675.1912 332.1448,-672.7206"/>
<polygon fill="#000000" stroke="#000000" points="333.6217,-669.5463 323.1083,-668.235 330.5093,-675.8163 333.6217,-669.5463"/>
<text text-anchor="middle" x="458.5" y="-701.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- reference_file -->
<g id="node6" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M27.5,-236.5C27.5,-236.5 304.5,-236.5 304.5,-236.5 310.5,-236.5 316.5,-242.5 316.5,-248.5 316.5,-248.5 316.5,-431.5 316.5,-431.5 316.5,-437.5 310.5,-443.5 304.5,-443.5 304.5,-443.5 27.5,-443.5 27.5,-443.5 21.5,-443.5 15.5,-437.5 15.5,-431.5 15.5,-431.5 15.5,-248.5 15.5,-248.5 15.5,-242.5 21.5,-236.5 27.5,-236.5"/>
<text text-anchor="middle" x="73.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="131.5,-236.5 131.5,-443.5 "/>
<text text-anchor="middle" x="142" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="152.5,-236.5 152.5,-443.5 "/>
<text text-anchor="middle" x="224" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="152.5,-420.5 295.5,-420.5 "/>
<text text-anchor="middle" x="224" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="152.5,-397.5 295.5,-397.5 "/>
<text text-anchor="middle" x="224" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="152.5,-374.5 295.5,-374.5 "/>
<text text-anchor="middle" x="224" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="152.5,-351.5 295.5,-351.5 "/>
<text text-anchor="middle" x="224" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="152.5,-328.5 295.5,-328.5 "/>
<text text-anchor="middle" x="224" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="152.5,-305.5 295.5,-305.5 "/>
<text text-anchor="middle" x="224" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="152.5,-282.5 295.5,-282.5 "/>
<text text-anchor="middle" x="224" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="152.5,-259.5 295.5,-259.5 "/>
<text text-anchor="middle" x="224" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="295.5,-236.5 295.5,-443.5 "/>
<text text-anchor="middle" x="306" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge2" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M198.5603,-236.3374C204.1885,-224.6118 210.644,-213.2212 218,-203 220.5377,-199.4739 223.2149,-195.9959 226.0079,-192.5719"/>
<polygon fill="#000000" stroke="#000000" points="228.9066,-194.5663 232.724,-184.6831 223.5765,-190.0286 228.9066,-194.5663"/>
<text text-anchor="middle" x="278.5" y="-206.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- treatment -->
<g id="node7" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M1175,-518.5C1175,-518.5 1467,-518.5 1467,-518.5 1473,-518.5 1479,-524.5 1479,-530.5 1479,-530.5 1479,-644.5 1479,-644.5 1479,-650.5 1473,-656.5 1467,-656.5 1467,-656.5 1175,-656.5 1175,-656.5 1169,-656.5 1163,-650.5 1163,-644.5 1163,-644.5 1163,-530.5 1163,-530.5 1163,-524.5 1169,-518.5 1175,-518.5"/>
<text text-anchor="middle" x="1207.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1252,-518.5 1252,-656.5 "/>
<text text-anchor="middle" x="1262.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1273,-518.5 1273,-656.5 "/>
<text text-anchor="middle" x="1365.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="1273,-633.5 1458,-633.5 "/>
<text text-anchor="middle" x="1365.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1273,-610.5 1458,-610.5 "/>
<text text-anchor="middle" x="1365.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1273,-587.5 1458,-587.5 "/>
<text text-anchor="middle" x="1365.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="1273,-564.5 1458,-564.5 "/>
<text text-anchor="middle" x="1365.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1273,-541.5 1458,-541.5 "/>
<text text-anchor="middle" x="1365.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1458,-518.5 1458,-656.5 "/>
<text text-anchor="middle" x="1468.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1200.6468,-518.436C1185.1072,-510.231 1169.2846,-502.2178 1154,-495 1071.0249,-455.8168 975.2912,-417.8328 899.2026,-389.2733"/>
<polygon fill="#000000" stroke="#000000" points="900.1424,-385.888 889.55,-385.6612 897.689,-392.444 900.1424,-385.888"/>
<text text-anchor="middle" x="1160" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M321.3402,-506.8081C329.9724,-502.7136 338.5669,-498.7493 347,-495 437.8305,-454.617 542.7261,-415.502 624.3329,-386.6679"/>
<polygon fill="#000000" stroke="#000000" points="625.8984,-389.8273 634.167,-383.2031 623.5722,-383.2251 625.8984,-389.8273"/>
<text text-anchor="middle" x="450.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M278.5218,-506.9947C296.9436,-488.3805 313.7191,-467.1578 325,-444 362.7674,-366.4699 367.4477,-267.8272 364.0192,-194.7854"/>
<polygon fill="#000000" stroke="#000000" points="367.5068,-194.4552 363.4842,-184.6537 360.5165,-194.8244 367.5068,-194.4552"/>
<text text-anchor="middle" x="401.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
</g>
</svg>
</div>
