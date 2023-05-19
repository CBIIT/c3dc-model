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
<svg width="622pt" height="895pt"
 viewBox="0.00 0.00 622.00 895.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 891)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-891 618,-891 618,4 -4,4"/>
<!-- sample -->
<g id="node1" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M12,-610.5C12,-610.5 278,-610.5 278,-610.5 284,-610.5 290,-616.5 290,-622.5 290,-622.5 290,-874.5 290,-874.5 290,-880.5 284,-886.5 278,-886.5 278,-886.5 12,-886.5 12,-886.5 6,-886.5 0,-880.5 0,-874.5 0,-874.5 0,-622.5 0,-622.5 0,-616.5 6,-610.5 12,-610.5"/>
<text text-anchor="middle" x="34" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="68,-610.5 68,-886.5 "/>
<text text-anchor="middle" x="78.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="89,-610.5 89,-886.5 "/>
<text text-anchor="middle" x="179" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">harmonized_cde</text>
<polyline fill="none" stroke="#000000" points="89,-863.5 269,-863.5 "/>
<text text-anchor="middle" x="179" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">harmonized_term</text>
<polyline fill="none" stroke="#000000" points="89,-840.5 269,-840.5 "/>
<text text-anchor="middle" x="179" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">harmonized_value</text>
<polyline fill="none" stroke="#000000" points="89,-817.5 269,-817.5 "/>
<text text-anchor="middle" x="179" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">harmonized_value_id</text>
<polyline fill="none" stroke="#000000" points="89,-794.5 269,-794.5 "/>
<text text-anchor="middle" x="179" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="89,-771.5 269,-771.5 "/>
<text text-anchor="middle" x="179" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">source_data_file_guid</text>
<polyline fill="none" stroke="#000000" points="89,-748.5 269,-748.5 "/>
<text text-anchor="middle" x="179" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">source_data_file_name</text>
<polyline fill="none" stroke="#000000" points="89,-725.5 269,-725.5 "/>
<text text-anchor="middle" x="179" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">source_dataset</text>
<polyline fill="none" stroke="#000000" points="89,-702.5 269,-702.5 "/>
<text text-anchor="middle" x="179" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">source_field_name</text>
<polyline fill="none" stroke="#000000" points="89,-679.5 269,-679.5 "/>
<text text-anchor="middle" x="179" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">source_value</text>
<polyline fill="none" stroke="#000000" points="89,-656.5 269,-656.5 "/>
<text text-anchor="middle" x="179" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">transformation_logic</text>
<polyline fill="none" stroke="#000000" points="89,-633.5 269,-633.5 "/>
<text text-anchor="middle" x="179" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">version</text>
<polyline fill="none" stroke="#000000" points="269,-610.5 269,-886.5 "/>
<text text-anchor="middle" x="279.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node2" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M248,-282.5C248,-282.5 542,-282.5 542,-282.5 548,-282.5 554,-288.5 554,-294.5 554,-294.5 554,-546.5 554,-546.5 554,-552.5 548,-558.5 542,-558.5 542,-558.5 248,-558.5 248,-558.5 242,-558.5 236,-552.5 236,-546.5 236,-546.5 236,-294.5 236,-294.5 236,-288.5 242,-282.5 248,-282.5"/>
<text text-anchor="middle" x="284" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="332,-282.5 332,-558.5 "/>
<text text-anchor="middle" x="342.5" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="353,-282.5 353,-558.5 "/>
<text text-anchor="middle" x="443" y="-543.3" font-family="Times,serif" font-size="14.00" fill="#000000">harmonized_cde</text>
<polyline fill="none" stroke="#000000" points="353,-535.5 533,-535.5 "/>
<text text-anchor="middle" x="443" y="-520.3" font-family="Times,serif" font-size="14.00" fill="#000000">harmonized_term</text>
<polyline fill="none" stroke="#000000" points="353,-512.5 533,-512.5 "/>
<text text-anchor="middle" x="443" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">harmonized_value</text>
<polyline fill="none" stroke="#000000" points="353,-489.5 533,-489.5 "/>
<text text-anchor="middle" x="443" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">harmonized_value_id</text>
<polyline fill="none" stroke="#000000" points="353,-466.5 533,-466.5 "/>
<text text-anchor="middle" x="443" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="353,-443.5 533,-443.5 "/>
<text text-anchor="middle" x="443" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">source_data_file_guid</text>
<polyline fill="none" stroke="#000000" points="353,-420.5 533,-420.5 "/>
<text text-anchor="middle" x="443" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">source_data_file_name</text>
<polyline fill="none" stroke="#000000" points="353,-397.5 533,-397.5 "/>
<text text-anchor="middle" x="443" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">source_dataset</text>
<polyline fill="none" stroke="#000000" points="353,-374.5 533,-374.5 "/>
<text text-anchor="middle" x="443" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">source_field_name</text>
<polyline fill="none" stroke="#000000" points="353,-351.5 533,-351.5 "/>
<text text-anchor="middle" x="443" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">source_value</text>
<polyline fill="none" stroke="#000000" points="353,-328.5 533,-328.5 "/>
<text text-anchor="middle" x="443" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">transformation_logic</text>
<polyline fill="none" stroke="#000000" points="353,-305.5 533,-305.5 "/>
<text text-anchor="middle" x="443" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">version</text>
<polyline fill="none" stroke="#000000" points="533,-282.5 533,-558.5 "/>
<text text-anchor="middle" x="543.5" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M250.2979,-610.3491C261.2758,-595.9462 272.4616,-581.2704 283.5051,-566.7813"/>
<polygon fill="#000000" stroke="#000000" points="286.3452,-568.8288 289.6236,-558.7539 280.778,-564.5854 286.3452,-568.8288"/>
<text text-anchor="middle" x="306.5" y="-580.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- study -->
<g id="node3" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M51.5,-.5C51.5,-.5 270.5,-.5 270.5,-.5 276.5,-.5 282.5,-6.5 282.5,-12.5 282.5,-12.5 282.5,-218.5 282.5,-218.5 282.5,-224.5 276.5,-230.5 270.5,-230.5 270.5,-230.5 51.5,-230.5 51.5,-230.5 45.5,-230.5 39.5,-224.5 39.5,-218.5 39.5,-218.5 39.5,-12.5 39.5,-12.5 39.5,-6.5 45.5,-.5 51.5,-.5"/>
<text text-anchor="middle" x="67.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="95.5,-.5 95.5,-230.5 "/>
<text text-anchor="middle" x="106" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="116.5,-.5 116.5,-230.5 "/>
<text text-anchor="middle" x="189" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="116.5,-207.5 261.5,-207.5 "/>
<text text-anchor="middle" x="189" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="116.5,-184.5 261.5,-184.5 "/>
<text text-anchor="middle" x="189" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="116.5,-161.5 261.5,-161.5 "/>
<text text-anchor="middle" x="189" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="116.5,-138.5 261.5,-138.5 "/>
<text text-anchor="middle" x="189" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="116.5,-115.5 261.5,-115.5 "/>
<text text-anchor="middle" x="189" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="116.5,-92.5 261.5,-92.5 "/>
<text text-anchor="middle" x="189" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="116.5,-69.5 261.5,-69.5 "/>
<text text-anchor="middle" x="189" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="116.5,-46.5 261.5,-46.5 "/>
<text text-anchor="middle" x="189" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="116.5,-23.5 261.5,-23.5 "/>
<text text-anchor="middle" x="189" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="261.5,-.5 261.5,-230.5 "/>
<text text-anchor="middle" x="272" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge3" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M146.8411,-610.4408C148.2817,-517.5793 150.6142,-392.4182 154,-282 154.4103,-268.6197 154.9009,-254.637 155.4295,-240.7069"/>
<polygon fill="#000000" stroke="#000000" points="158.9319,-240.7098 155.8204,-230.5822 151.9371,-240.4396 158.9319,-240.7098"/>
<text text-anchor="middle" x="190.5" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge1" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M288.9545,-282.2783C277.9361,-267.9168 266.7871,-253.3849 255.9028,-239.1981"/>
<polygon fill="#000000" stroke="#000000" points="258.3919,-236.6925 249.5279,-230.8889 252.8381,-240.9534 258.3919,-236.6925"/>
<text text-anchor="middle" x="321.5" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- diagnosis -->
<g id="node4" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M320,-610.5C320,-610.5 602,-610.5 602,-610.5 608,-610.5 614,-616.5 614,-622.5 614,-622.5 614,-874.5 614,-874.5 614,-880.5 608,-886.5 602,-886.5 602,-886.5 320,-886.5 320,-886.5 314,-886.5 308,-880.5 308,-874.5 308,-874.5 308,-622.5 308,-622.5 308,-616.5 314,-610.5 320,-610.5"/>
<text text-anchor="middle" x="350" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="392,-610.5 392,-886.5 "/>
<text text-anchor="middle" x="402.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="413,-610.5 413,-886.5 "/>
<text text-anchor="middle" x="503" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="413,-863.5 593,-863.5 "/>
<text text-anchor="middle" x="503" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">harmonized_cde</text>
<polyline fill="none" stroke="#000000" points="413,-840.5 593,-840.5 "/>
<text text-anchor="middle" x="503" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">harmonized_term</text>
<polyline fill="none" stroke="#000000" points="413,-817.5 593,-817.5 "/>
<text text-anchor="middle" x="503" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">harmonized_value</text>
<polyline fill="none" stroke="#000000" points="413,-794.5 593,-794.5 "/>
<text text-anchor="middle" x="503" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">harmonized_value_id</text>
<polyline fill="none" stroke="#000000" points="413,-771.5 593,-771.5 "/>
<text text-anchor="middle" x="503" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">source_data_file_guid</text>
<polyline fill="none" stroke="#000000" points="413,-748.5 593,-748.5 "/>
<text text-anchor="middle" x="503" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">source_data_file_name</text>
<polyline fill="none" stroke="#000000" points="413,-725.5 593,-725.5 "/>
<text text-anchor="middle" x="503" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">source_dataset</text>
<polyline fill="none" stroke="#000000" points="413,-702.5 593,-702.5 "/>
<text text-anchor="middle" x="503" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">source_field_name</text>
<polyline fill="none" stroke="#000000" points="413,-679.5 593,-679.5 "/>
<text text-anchor="middle" x="503" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">source_value</text>
<polyline fill="none" stroke="#000000" points="413,-656.5 593,-656.5 "/>
<text text-anchor="middle" x="503" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">transformation_logic</text>
<polyline fill="none" stroke="#000000" points="413,-633.5 593,-633.5 "/>
<text text-anchor="middle" x="503" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">version</text>
<polyline fill="none" stroke="#000000" points="593,-610.5 593,-886.5 "/>
<text text-anchor="middle" x="603.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M433.2013,-610.3491C430.4374,-596.613 427.6235,-582.6287 424.8398,-568.7948"/>
<polygon fill="#000000" stroke="#000000" points="428.2233,-567.8669 422.8194,-558.7539 421.3609,-569.2479 428.2233,-567.8669"/>
<text text-anchor="middle" x="472.5" y="-580.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
</g>
</svg>
</div>
