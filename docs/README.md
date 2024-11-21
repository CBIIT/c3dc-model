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
<!-- genetic_analysis -->
<g id="node1" class="node">
<title>genetic_analysis</title>
<path fill="none" stroke="#000000" d="M1967.5,-507C1967.5,-507 2310.5,-507 2310.5,-507 2316.5,-507 2322.5,-513 2322.5,-519 2322.5,-519 2322.5,-748 2322.5,-748 2322.5,-754 2316.5,-760 2310.5,-760 2310.5,-760 1967.5,-760 1967.5,-760 1961.5,-760 1955.5,-754 1955.5,-748 1955.5,-748 1955.5,-519 1955.5,-519 1955.5,-513 1961.5,-507 1967.5,-507"/>
<text text-anchor="middle" x="2023" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="2090.5,-507 2090.5,-760 "/>
<text text-anchor="middle" x="2101" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2111.5,-507 2111.5,-760 "/>
<text text-anchor="middle" x="2206.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="2111.5,-737 2301.5,-737 "/>
<text text-anchor="middle" x="2206.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">allelic_ratio</text>
<polyline fill="none" stroke="#000000" points="2111.5,-714 2301.5,-714 "/>
<text text-anchor="middle" x="2206.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">alteration</text>
<polyline fill="none" stroke="#000000" points="2111.5,-691 2301.5,-691 "/>
<text text-anchor="middle" x="2206.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">dna_index_numeric</text>
<polyline fill="none" stroke="#000000" points="2111.5,-668 2301.5,-668 "/>
<text text-anchor="middle" x="2206.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis_id</text>
<polyline fill="none" stroke="#000000" points="2111.5,-645 2301.5,-645 "/>
<text text-anchor="middle" x="2206.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_coding</text>
<polyline fill="none" stroke="#000000" points="2111.5,-622 2301.5,-622 "/>
<text text-anchor="middle" x="2206.5" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_protein</text>
<polyline fill="none" stroke="#000000" points="2111.5,-599 2301.5,-599 "/>
<text text-anchor="middle" x="2206.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2111.5,-576 2301.5,-576 "/>
<text text-anchor="middle" x="2206.5" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">iscn</text>
<polyline fill="none" stroke="#000000" points="2111.5,-553 2301.5,-553 "/>
<text text-anchor="middle" x="2206.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="2111.5,-530 2301.5,-530 "/>
<text text-anchor="middle" x="2206.5" y="-514.8" font-family="Times,serif" font-size="14.00" fill="#000000">vaf_numeric</text>
<polyline fill="none" stroke="#000000" points="2301.5,-507 2301.5,-760 "/>
<text text-anchor="middle" x="2312" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node10" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M800.5,-294C800.5,-294 1031.5,-294 1031.5,-294 1037.5,-294 1043.5,-300 1043.5,-306 1043.5,-306 1043.5,-374 1043.5,-374 1043.5,-380 1037.5,-386 1031.5,-386 1031.5,-386 800.5,-386 800.5,-386 794.5,-386 788.5,-380 788.5,-374 788.5,-374 788.5,-306 788.5,-306 788.5,-300 794.5,-294 800.5,-294"/>
<text text-anchor="middle" x="836.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="884.5,-294 884.5,-386 "/>
<text text-anchor="middle" x="895" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="905.5,-294 905.5,-386 "/>
<text text-anchor="middle" x="964" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="905.5,-363 1022.5,-363 "/>
<text text-anchor="middle" x="964" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="905.5,-340 1022.5,-340 "/>
<text text-anchor="middle" x="964" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="905.5,-317 1022.5,-317 "/>
<text text-anchor="middle" x="964" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="1022.5,-294 1022.5,-386 "/>
<text text-anchor="middle" x="1033" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1972.8438,-506.8773C1964.2947,-502.5256 1955.6587,-498.5296 1947,-495 1787.6463,-430.0424 1296.2336,-376.0693 1053.9469,-352.5989"/>
<polygon fill="#000000" stroke="#000000" points="1053.9525,-349.0833 1043.6626,-351.6065 1053.2801,-356.0509 1053.9525,-349.0833"/>
<text text-anchor="middle" x="1954" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- study -->
<g id="node2" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M416.5,-.5C416.5,-.5 635.5,-.5 635.5,-.5 641.5,-.5 647.5,-6.5 647.5,-12.5 647.5,-12.5 647.5,-172.5 647.5,-172.5 647.5,-178.5 641.5,-184.5 635.5,-184.5 635.5,-184.5 416.5,-184.5 416.5,-184.5 410.5,-184.5 404.5,-178.5 404.5,-172.5 404.5,-172.5 404.5,-12.5 404.5,-12.5 404.5,-6.5 410.5,-.5 416.5,-.5"/>
<text text-anchor="middle" x="432.5" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="460.5,-.5 460.5,-184.5 "/>
<text text-anchor="middle" x="471" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="481.5,-.5 481.5,-184.5 "/>
<text text-anchor="middle" x="554" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="481.5,-161.5 626.5,-161.5 "/>
<text text-anchor="middle" x="554" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="481.5,-138.5 626.5,-138.5 "/>
<text text-anchor="middle" x="554" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession</text>
<polyline fill="none" stroke="#000000" points="481.5,-115.5 626.5,-115.5 "/>
<text text-anchor="middle" x="554" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="481.5,-92.5 626.5,-92.5 "/>
<text text-anchor="middle" x="554" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="481.5,-69.5 626.5,-69.5 "/>
<text text-anchor="middle" x="554" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="481.5,-46.5 626.5,-46.5 "/>
<text text-anchor="middle" x="554" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="481.5,-23.5 626.5,-23.5 "/>
<text text-anchor="middle" x="554" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="626.5,-.5 626.5,-184.5 "/>
<text text-anchor="middle" x="637" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- laboratory_test -->
<g id="node3" class="node">
<title>laboratory_test</title>
<path fill="none" stroke="#000000" d="M493.5,-495.5C493.5,-495.5 784.5,-495.5 784.5,-495.5 790.5,-495.5 796.5,-501.5 796.5,-507.5 796.5,-507.5 796.5,-759.5 796.5,-759.5 796.5,-765.5 790.5,-771.5 784.5,-771.5 784.5,-771.5 493.5,-771.5 493.5,-771.5 487.5,-771.5 481.5,-765.5 481.5,-759.5 481.5,-759.5 481.5,-507.5 481.5,-507.5 481.5,-501.5 487.5,-495.5 493.5,-495.5"/>
<text text-anchor="middle" x="544.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="607.5,-495.5 607.5,-771.5 "/>
<text text-anchor="middle" x="618" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="628.5,-495.5 628.5,-771.5 "/>
<text text-anchor="middle" x="702" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_lab</text>
<polyline fill="none" stroke="#000000" points="628.5,-748.5 775.5,-748.5 "/>
<text text-anchor="middle" x="702" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="628.5,-725.5 775.5,-725.5 "/>
<text text-anchor="middle" x="702" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_id</text>
<polyline fill="none" stroke="#000000" points="628.5,-702.5 775.5,-702.5 "/>
<text text-anchor="middle" x="702" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">method</text>
<polyline fill="none" stroke="#000000" points="628.5,-679.5 775.5,-679.5 "/>
<text text-anchor="middle" x="702" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">result</text>
<polyline fill="none" stroke="#000000" points="628.5,-656.5 775.5,-656.5 "/>
<text text-anchor="middle" x="702" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">result_modifier</text>
<polyline fill="none" stroke="#000000" points="628.5,-633.5 775.5,-633.5 "/>
<text text-anchor="middle" x="702" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">result_numeric</text>
<polyline fill="none" stroke="#000000" points="628.5,-610.5 775.5,-610.5 "/>
<text text-anchor="middle" x="702" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">result_text</text>
<polyline fill="none" stroke="#000000" points="628.5,-587.5 775.5,-587.5 "/>
<text text-anchor="middle" x="702" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">result_unit</text>
<polyline fill="none" stroke="#000000" points="628.5,-564.5 775.5,-564.5 "/>
<text text-anchor="middle" x="702" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">sensitivity</text>
<polyline fill="none" stroke="#000000" points="628.5,-541.5 775.5,-541.5 "/>
<text text-anchor="middle" x="702" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">specimen</text>
<polyline fill="none" stroke="#000000" points="628.5,-518.5 775.5,-518.5 "/>
<text text-anchor="middle" x="702" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">test</text>
<polyline fill="none" stroke="#000000" points="775.5,-495.5 775.5,-771.5 "/>
<text text-anchor="middle" x="786" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M769.3889,-495.3443C803.5241,-459.1758 838.3185,-422.3087 865.4401,-393.5716"/>
<polygon fill="#000000" stroke="#000000" points="868.2029,-395.7435 872.5213,-386.0686 863.1121,-390.9389 868.2029,-395.7435"/>
<text text-anchor="middle" x="860.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- treatment -->
<g id="node4" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M827,-564.5C827,-564.5 1119,-564.5 1119,-564.5 1125,-564.5 1131,-570.5 1131,-576.5 1131,-576.5 1131,-690.5 1131,-690.5 1131,-696.5 1125,-702.5 1119,-702.5 1119,-702.5 827,-702.5 827,-702.5 821,-702.5 815,-696.5 815,-690.5 815,-690.5 815,-576.5 815,-576.5 815,-570.5 821,-564.5 827,-564.5"/>
<text text-anchor="middle" x="859.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="904,-564.5 904,-702.5 "/>
<text text-anchor="middle" x="914.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="925,-564.5 925,-702.5 "/>
<text text-anchor="middle" x="1017.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="925,-679.5 1110,-679.5 "/>
<text text-anchor="middle" x="1017.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="925,-656.5 1110,-656.5 "/>
<text text-anchor="middle" x="1017.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="925,-633.5 1110,-633.5 "/>
<text text-anchor="middle" x="1017.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="925,-610.5 1110,-610.5 "/>
<text text-anchor="middle" x="1017.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="925,-587.5 1110,-587.5 "/>
<text text-anchor="middle" x="1017.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1110,-564.5 1110,-702.5 "/>
<text text-anchor="middle" x="1120.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M959.564,-564.3163C949.6082,-513.0526 936.2107,-444.0673 926.9131,-396.1927"/>
<polygon fill="#000000" stroke="#000000" points="930.3363,-395.4604 924.994,-386.3111 923.4647,-396.795 930.3363,-395.4604"/>
<text text-anchor="middle" x="989" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- reference_file -->
<g id="node5" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M387.5,-236.5C387.5,-236.5 664.5,-236.5 664.5,-236.5 670.5,-236.5 676.5,-242.5 676.5,-248.5 676.5,-248.5 676.5,-431.5 676.5,-431.5 676.5,-437.5 670.5,-443.5 664.5,-443.5 664.5,-443.5 387.5,-443.5 387.5,-443.5 381.5,-443.5 375.5,-437.5 375.5,-431.5 375.5,-431.5 375.5,-248.5 375.5,-248.5 375.5,-242.5 381.5,-236.5 387.5,-236.5"/>
<text text-anchor="middle" x="433.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="491.5,-236.5 491.5,-443.5 "/>
<text text-anchor="middle" x="502" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="512.5,-236.5 512.5,-443.5 "/>
<text text-anchor="middle" x="584" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="512.5,-420.5 655.5,-420.5 "/>
<text text-anchor="middle" x="584" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="512.5,-397.5 655.5,-397.5 "/>
<text text-anchor="middle" x="584" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="512.5,-374.5 655.5,-374.5 "/>
<text text-anchor="middle" x="584" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="512.5,-351.5 655.5,-351.5 "/>
<text text-anchor="middle" x="584" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="512.5,-328.5 655.5,-328.5 "/>
<text text-anchor="middle" x="584" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="512.5,-305.5 655.5,-305.5 "/>
<text text-anchor="middle" x="584" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="512.5,-282.5 655.5,-282.5 "/>
<text text-anchor="middle" x="584" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="512.5,-259.5 655.5,-259.5 "/>
<text text-anchor="middle" x="584" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="655.5,-236.5 655.5,-443.5 "/>
<text text-anchor="middle" x="666" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge6" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M526,-236.4718C526,-222.7494 526,-208.686 526,-194.9814"/>
<polygon fill="#000000" stroke="#000000" points="529.5001,-194.5829 526,-184.5829 522.5001,-194.5829 529.5001,-194.5829"/>
<text text-anchor="middle" x="586.5" y="-206.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- diagnosis -->
<g id="node6" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M89.5,-823.5C89.5,-823.5 454.5,-823.5 454.5,-823.5 460.5,-823.5 466.5,-829.5 466.5,-835.5 466.5,-835.5 466.5,-1202.5 466.5,-1202.5 466.5,-1208.5 460.5,-1214.5 454.5,-1214.5 454.5,-1214.5 89.5,-1214.5 89.5,-1214.5 83.5,-1214.5 77.5,-1208.5 77.5,-1202.5 77.5,-1202.5 77.5,-835.5 77.5,-835.5 77.5,-829.5 83.5,-823.5 89.5,-823.5"/>
<text text-anchor="middle" x="119.5" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="161.5,-823.5 161.5,-1214.5 "/>
<text text-anchor="middle" x="172" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="182.5,-823.5 182.5,-1214.5 "/>
<text text-anchor="middle" x="314" y="-1199.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="182.5,-1191.5 445.5,-1191.5 "/>
<text text-anchor="middle" x="314" y="-1176.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="182.5,-1168.5 445.5,-1168.5 "/>
<text text-anchor="middle" x="314" y="-1153.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="182.5,-1145.5 445.5,-1145.5 "/>
<text text-anchor="middle" x="314" y="-1130.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="182.5,-1122.5 445.5,-1122.5 "/>
<text text-anchor="middle" x="314" y="-1107.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="182.5,-1099.5 445.5,-1099.5 "/>
<text text-anchor="middle" x="314" y="-1084.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="182.5,-1076.5 445.5,-1076.5 "/>
<text text-anchor="middle" x="314" y="-1061.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="182.5,-1053.5 445.5,-1053.5 "/>
<text text-anchor="middle" x="314" y="-1038.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="182.5,-1030.5 445.5,-1030.5 "/>
<text text-anchor="middle" x="314" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="182.5,-1007.5 445.5,-1007.5 "/>
<text text-anchor="middle" x="314" y="-992.3" font-family="Times,serif" font-size="14.00" fill="#000000">laterality</text>
<polyline fill="none" stroke="#000000" points="182.5,-984.5 445.5,-984.5 "/>
<text text-anchor="middle" x="314" y="-969.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="182.5,-961.5 445.5,-961.5 "/>
<text text-anchor="middle" x="314" y="-946.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="182.5,-938.5 445.5,-938.5 "/>
<text text-anchor="middle" x="314" y="-923.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="182.5,-915.5 445.5,-915.5 "/>
<text text-anchor="middle" x="314" y="-900.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="182.5,-892.5 445.5,-892.5 "/>
<text text-anchor="middle" x="314" y="-877.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="182.5,-869.5 445.5,-869.5 "/>
<text text-anchor="middle" x="314" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="182.5,-846.5 445.5,-846.5 "/>
<text text-anchor="middle" x="314" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="445.5,-823.5 445.5,-1214.5 "/>
<text text-anchor="middle" x="456" y="-1015.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node9" class="node">
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
<!-- diagnosis&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M219.7456,-823.4266C210.4845,-788.765 201.256,-754.2251 193.2582,-724.2917"/>
<polygon fill="#000000" stroke="#000000" points="196.5576,-723.0811 190.5949,-714.3235 189.7949,-724.8881 196.5576,-723.0811"/>
<text text-anchor="middle" x="259.5" y="-793.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M334.6479,-823.2677C339.1892,-806.0224 343.3928,-788.758 347,-772 360.0623,-711.3167 339.9507,-539.7196 383,-495 477.4044,-396.9327 554.7641,-483.5978 685,-444 730.282,-430.2322 778.3125,-409.6624 818.7794,-390.4419"/>
<polygon fill="#000000" stroke="#000000" points="820.3204,-393.5846 827.8267,-386.1076 817.296,-387.2716 820.3204,-393.5846"/>
<text text-anchor="middle" x="427.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- survival -->
<g id="node7" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M1161.5,-541.5C1161.5,-541.5 1522.5,-541.5 1522.5,-541.5 1528.5,-541.5 1534.5,-547.5 1534.5,-553.5 1534.5,-553.5 1534.5,-713.5 1534.5,-713.5 1534.5,-719.5 1528.5,-725.5 1522.5,-725.5 1522.5,-725.5 1161.5,-725.5 1161.5,-725.5 1155.5,-725.5 1149.5,-719.5 1149.5,-713.5 1149.5,-713.5 1149.5,-553.5 1149.5,-553.5 1149.5,-547.5 1155.5,-541.5 1161.5,-541.5"/>
<text text-anchor="middle" x="1186.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="1223.5,-541.5 1223.5,-725.5 "/>
<text text-anchor="middle" x="1234" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1244.5,-541.5 1244.5,-725.5 "/>
<text text-anchor="middle" x="1379" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="1244.5,-702.5 1513.5,-702.5 "/>
<text text-anchor="middle" x="1379" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="1244.5,-679.5 1513.5,-679.5 "/>
<text text-anchor="middle" x="1379" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="1244.5,-656.5 1513.5,-656.5 "/>
<text text-anchor="middle" x="1379" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="1244.5,-633.5 1513.5,-633.5 "/>
<text text-anchor="middle" x="1379" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="1244.5,-610.5 1513.5,-610.5 "/>
<text text-anchor="middle" x="1379" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1244.5,-587.5 1513.5,-587.5 "/>
<text text-anchor="middle" x="1379" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="1244.5,-564.5 1513.5,-564.5 "/>
<text text-anchor="middle" x="1379" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="1513.5,-541.5 1513.5,-725.5 "/>
<text text-anchor="middle" x="1524" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1208.3798,-541.44C1136.8346,-492.1478 1051.346,-433.2489 991.3477,-391.9121"/>
<polygon fill="#000000" stroke="#000000" points="993.2755,-388.99 983.055,-386.1987 989.304,-394.7544 993.2755,-388.99"/>
<text text-anchor="middle" x="1143.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- treatment_response -->
<g id="node8" class="node">
<title>treatment_response</title>
<path fill="none" stroke="#000000" d="M1564.5,-564.5C1564.5,-564.5 1925.5,-564.5 1925.5,-564.5 1931.5,-564.5 1937.5,-570.5 1937.5,-576.5 1937.5,-576.5 1937.5,-690.5 1937.5,-690.5 1937.5,-696.5 1931.5,-702.5 1925.5,-702.5 1925.5,-702.5 1564.5,-702.5 1564.5,-702.5 1558.5,-702.5 1552.5,-696.5 1552.5,-690.5 1552.5,-690.5 1552.5,-576.5 1552.5,-576.5 1552.5,-570.5 1558.5,-564.5 1564.5,-564.5"/>
<text text-anchor="middle" x="1633" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
<polyline fill="none" stroke="#000000" points="1713.5,-564.5 1713.5,-702.5 "/>
<text text-anchor="middle" x="1724" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1734.5,-564.5 1734.5,-702.5 "/>
<text text-anchor="middle" x="1825.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_response</text>
<polyline fill="none" stroke="#000000" points="1734.5,-679.5 1916.5,-679.5 "/>
<text text-anchor="middle" x="1825.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1734.5,-656.5 1916.5,-656.5 "/>
<text text-anchor="middle" x="1825.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="1734.5,-633.5 1916.5,-633.5 "/>
<text text-anchor="middle" x="1825.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_category</text>
<polyline fill="none" stroke="#000000" points="1734.5,-610.5 1916.5,-610.5 "/>
<text text-anchor="middle" x="1825.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_system</text>
<polyline fill="none" stroke="#000000" points="1734.5,-587.5 1916.5,-587.5 "/>
<text text-anchor="middle" x="1825.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response_id</text>
<polyline fill="none" stroke="#000000" points="1916.5,-564.5 1916.5,-702.5 "/>
<text text-anchor="middle" x="1927" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1658.5993,-564.1446C1624.2511,-539.3517 1583.348,-513.1 1543,-495 1382.7152,-423.0965 1183.7861,-381.1492 1053.5432,-359.4223"/>
<polygon fill="#000000" stroke="#000000" points="1053.9423,-355.9409 1043.5057,-357.7652 1052.802,-362.8474 1053.9423,-355.9409"/>
<text text-anchor="middle" x="1578" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge10" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M177.3489,-552.6584C189.8261,-466.4206 220.2567,-329.616 293,-236 319.9862,-201.2705 357.9256,-172.8929 395.3669,-150.8151"/>
<polygon fill="#000000" stroke="#000000" points="397.445,-153.6569 404.3563,-145.6266 393.9457,-147.5942 397.445,-153.6569"/>
<text text-anchor="middle" x="329.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M204.1362,-552.6397C223.3955,-518.507 250.8172,-482.0811 287,-462 325.706,-440.5186 641.9402,-454.2692 685,-444 733.1272,-432.5222 783.5638,-411.0492 824.9865,-390.5818"/>
<polygon fill="#000000" stroke="#000000" points="826.5762,-393.7001 833.9547,-386.0969 823.4452,-387.4393 826.5762,-393.7001"/>
<text text-anchor="middle" x="323.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge1" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M843.1015,-293.7375C790.6708,-260.4641 718.5338,-214.6849 656.3086,-175.1958"/>
<polygon fill="#000000" stroke="#000000" points="657.9159,-172.0706 647.5972,-169.6674 654.1651,-177.9809 657.9159,-172.0706"/>
<text text-anchor="middle" x="771.5" y="-206.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
</g>
</svg>
</div>
