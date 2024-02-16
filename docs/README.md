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
<svg width="1234pt" height="895pt"
 viewBox="0.00 0.00 1234.00 895.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 891)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-891 1230,-891 1230,4 -4,4"/>
<!-- diagnosis -->
<g id="node1" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M12,-530C12,-530 377,-530 377,-530 383,-530 389,-536 389,-542 389,-542 389,-863 389,-863 389,-869 383,-875 377,-875 377,-875 12,-875 12,-875 6,-875 0,-869 0,-863 0,-863 0,-542 0,-542 0,-536 6,-530 12,-530"/>
<text text-anchor="middle" x="42" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="84,-530 84,-875 "/>
<text text-anchor="middle" x="94.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="105,-530 105,-875 "/>
<text text-anchor="middle" x="236.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="105,-852 368,-852 "/>
<text text-anchor="middle" x="236.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="105,-829 368,-829 "/>
<text text-anchor="middle" x="236.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="105,-806 368,-806 "/>
<text text-anchor="middle" x="236.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="105,-783 368,-783 "/>
<text text-anchor="middle" x="236.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_certainty</text>
<polyline fill="none" stroke="#000000" points="105,-760 368,-760 "/>
<text text-anchor="middle" x="236.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="105,-737 368,-737 "/>
<text text-anchor="middle" x="236.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="105,-714 368,-714 "/>
<text text-anchor="middle" x="236.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="105,-691 368,-691 "/>
<text text-anchor="middle" x="236.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="105,-668 368,-668 "/>
<text text-anchor="middle" x="236.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="105,-645 368,-645 "/>
<text text-anchor="middle" x="236.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="105,-622 368,-622 "/>
<text text-anchor="middle" x="236.5" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="105,-599 368,-599 "/>
<text text-anchor="middle" x="236.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="105,-576 368,-576 "/>
<text text-anchor="middle" x="236.5" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="105,-553 368,-553 "/>
<text text-anchor="middle" x="236.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="368,-530 368,-875 "/>
<text text-anchor="middle" x="378.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node5" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M462,-317C462,-317 693,-317 693,-317 699,-317 705,-323 705,-329 705,-329 705,-397 705,-397 705,-403 699,-409 693,-409 693,-409 462,-409 462,-409 456,-409 450,-403 450,-397 450,-397 450,-329 450,-329 450,-323 456,-317 462,-317"/>
<text text-anchor="middle" x="498" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="546,-317 546,-409 "/>
<text text-anchor="middle" x="556.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="567,-317 567,-409 "/>
<text text-anchor="middle" x="625.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="567,-386 684,-386 "/>
<text text-anchor="middle" x="625.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="567,-363 684,-363 "/>
<text text-anchor="middle" x="625.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="567,-340 684,-340 "/>
<text text-anchor="middle" x="625.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="684,-317 684,-409 "/>
<text text-anchor="middle" x="694.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M383.9938,-529.9829C388.5342,-525.9438 393.0414,-521.9446 397.5,-518 436.409,-483.577 480.6111,-445.4995 515.4754,-415.6995"/>
<polygon fill="#000000" stroke="#000000" points="517.8884,-418.2414 523.2193,-409.0854 513.3422,-412.9187 517.8884,-418.2414"/>
<text text-anchor="middle" x="477" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- survival -->
<g id="node2" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M419,-633.5C419,-633.5 780,-633.5 780,-633.5 786,-633.5 792,-639.5 792,-645.5 792,-645.5 792,-759.5 792,-759.5 792,-765.5 786,-771.5 780,-771.5 780,-771.5 419,-771.5 419,-771.5 413,-771.5 407,-765.5 407,-759.5 407,-759.5 407,-645.5 407,-645.5 407,-639.5 413,-633.5 419,-633.5"/>
<text text-anchor="middle" x="444" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="481,-633.5 481,-771.5 "/>
<text text-anchor="middle" x="491.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="502,-633.5 502,-771.5 "/>
<text text-anchor="middle" x="636.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="502,-748.5 771,-748.5 "/>
<text text-anchor="middle" x="636.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="502,-725.5 771,-725.5 "/>
<text text-anchor="middle" x="636.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="502,-702.5 771,-702.5 "/>
<text text-anchor="middle" x="636.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="502,-679.5 771,-679.5 "/>
<text text-anchor="middle" x="636.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="502,-656.5 771,-656.5 "/>
<text text-anchor="middle" x="636.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="771,-633.5 771,-771.5 "/>
<text text-anchor="middle" x="781.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M595.0215,-633.3879C590.9326,-570.289 584.9622,-478.1547 581.1544,-419.3944"/>
<polygon fill="#000000" stroke="#000000" points="584.6322,-418.9374 580.4928,-409.1847 577.6469,-419.3902 584.6322,-418.9374"/>
<text text-anchor="middle" x="625" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- study -->
<g id="node3" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M764,-.5C764,-.5 983,-.5 983,-.5 989,-.5 995,-6.5 995,-12.5 995,-12.5 995,-195.5 995,-195.5 995,-201.5 989,-207.5 983,-207.5 983,-207.5 764,-207.5 764,-207.5 758,-207.5 752,-201.5 752,-195.5 752,-195.5 752,-12.5 752,-12.5 752,-6.5 758,-.5 764,-.5"/>
<text text-anchor="middle" x="780" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="808,-.5 808,-207.5 "/>
<text text-anchor="middle" x="818.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="829,-.5 829,-207.5 "/>
<text text-anchor="middle" x="901.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="829,-184.5 974,-184.5 "/>
<text text-anchor="middle" x="901.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="829,-161.5 974,-161.5 "/>
<text text-anchor="middle" x="901.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="829,-138.5 974,-138.5 "/>
<text text-anchor="middle" x="901.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="829,-115.5 974,-115.5 "/>
<text text-anchor="middle" x="901.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="829,-92.5 974,-92.5 "/>
<text text-anchor="middle" x="901.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="829,-69.5 974,-69.5 "/>
<text text-anchor="middle" x="901.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="829,-46.5 974,-46.5 "/>
<text text-anchor="middle" x="901.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="829,-23.5 974,-23.5 "/>
<text text-anchor="middle" x="901.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="974,-.5 974,-207.5 "/>
<text text-anchor="middle" x="984.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file -->
<g id="node4" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M735,-259.5C735,-259.5 1012,-259.5 1012,-259.5 1018,-259.5 1024,-265.5 1024,-271.5 1024,-271.5 1024,-454.5 1024,-454.5 1024,-460.5 1018,-466.5 1012,-466.5 1012,-466.5 735,-466.5 735,-466.5 729,-466.5 723,-460.5 723,-454.5 723,-454.5 723,-271.5 723,-271.5 723,-265.5 729,-259.5 735,-259.5"/>
<text text-anchor="middle" x="781" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="839,-259.5 839,-466.5 "/>
<text text-anchor="middle" x="849.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="860,-259.5 860,-466.5 "/>
<text text-anchor="middle" x="931.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="860,-443.5 1003,-443.5 "/>
<text text-anchor="middle" x="931.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="860,-420.5 1003,-420.5 "/>
<text text-anchor="middle" x="931.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="860,-397.5 1003,-397.5 "/>
<text text-anchor="middle" x="931.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="860,-374.5 1003,-374.5 "/>
<text text-anchor="middle" x="931.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="860,-351.5 1003,-351.5 "/>
<text text-anchor="middle" x="931.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="860,-328.5 1003,-328.5 "/>
<text text-anchor="middle" x="931.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="860,-305.5 1003,-305.5 "/>
<text text-anchor="middle" x="931.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="860,-282.5 1003,-282.5 "/>
<text text-anchor="middle" x="931.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="1003,-259.5 1003,-466.5 "/>
<text text-anchor="middle" x="1013.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge2" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M873.5,-259.1471C873.5,-245.6895 873.5,-231.8468 873.5,-218.2325"/>
<polygon fill="#000000" stroke="#000000" points="877.0001,-217.8761 873.5,-207.8762 870.0001,-217.8762 877.0001,-217.8761"/>
<text text-anchor="middle" x="934" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge1" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M630.0778,-316.9944C662.7645,-288.3935 706.2766,-250.3205 747.4669,-214.2789"/>
<polygon fill="#000000" stroke="#000000" points="749.9069,-216.7947 755.1279,-207.5756 745.2973,-211.5266 749.9069,-216.7947"/>
<text text-anchor="middle" x="776" y="-229.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- sample -->
<g id="node6" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M865,-518.5C865,-518.5 1214,-518.5 1214,-518.5 1220,-518.5 1226,-524.5 1226,-530.5 1226,-530.5 1226,-874.5 1226,-874.5 1226,-880.5 1220,-886.5 1214,-886.5 1214,-886.5 865,-886.5 865,-886.5 859,-886.5 853,-880.5 853,-874.5 853,-874.5 853,-530.5 853,-530.5 853,-524.5 859,-518.5 865,-518.5"/>
<text text-anchor="middle" x="887" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="921,-518.5 921,-886.5 "/>
<text text-anchor="middle" x="931.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="942,-518.5 942,-886.5 "/>
<text text-anchor="middle" x="1073.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="942,-863.5 1205,-863.5 "/>
<text text-anchor="middle" x="1073.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="942,-840.5 1205,-840.5 "/>
<text text-anchor="middle" x="1073.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="942,-817.5 1205,-817.5 "/>
<text text-anchor="middle" x="1073.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_certainty</text>
<polyline fill="none" stroke="#000000" points="942,-794.5 1205,-794.5 "/>
<text text-anchor="middle" x="1073.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="942,-771.5 1205,-771.5 "/>
<text text-anchor="middle" x="1073.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="942,-748.5 1205,-748.5 "/>
<text text-anchor="middle" x="1073.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="942,-725.5 1205,-725.5 "/>
<text text-anchor="middle" x="1073.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="942,-702.5 1205,-702.5 "/>
<text text-anchor="middle" x="1073.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="942,-679.5 1205,-679.5 "/>
<text text-anchor="middle" x="1073.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="942,-656.5 1205,-656.5 "/>
<text text-anchor="middle" x="1073.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="942,-633.5 1205,-633.5 "/>
<text text-anchor="middle" x="1073.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="942,-610.5 1205,-610.5 "/>
<text text-anchor="middle" x="1073.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="942,-587.5 1205,-587.5 "/>
<text text-anchor="middle" x="1073.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="942,-564.5 1205,-564.5 "/>
<text text-anchor="middle" x="1073.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="942,-541.5 1205,-541.5 "/>
<text text-anchor="middle" x="1073.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1205,-518.5 1205,-886.5 "/>
<text text-anchor="middle" x="1215.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1068.1486,-518.3669C1073.2541,-435.9381 1068.2057,-339.4226 1033.5,-259 1025.5987,-240.6905 1014.3893,-223.4685 1001.525,-207.6388"/>
<polygon fill="#000000" stroke="#000000" points="1004.1995,-205.381 995.0841,-199.981 998.8424,-209.8868 1004.1995,-205.381"/>
<text text-anchor="middle" x="1106" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M852.7902,-554.17C835.6533,-541.652 818.3876,-529.4256 801.5,-518 764.3776,-492.884 751.7491,-491.9277 714.5,-467 690.629,-451.0252 665.3553,-432.3727 643.1029,-415.3099"/>
<polygon fill="#000000" stroke="#000000" points="645.1068,-412.4355 635.0496,-409.1035 640.8338,-417.98 645.1068,-412.4355"/>
<text text-anchor="middle" x="808" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
</g>
</svg>
</div>
