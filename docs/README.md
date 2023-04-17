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
<svg width="3973pt" height="1729pt"
 viewBox="0.00 0.00 3972.54 1729.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1725)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1725 3968.5416,-1725 3968.5416,4 -4,4"/>
<!-- study_admin -->
<g id="node1" class="node">
<title>study_admin</title>
<path fill="none" stroke="#000000" d="M12,-351.5C12,-351.5 338,-351.5 338,-351.5 344,-351.5 350,-357.5 350,-363.5 350,-363.5 350,-500.5 350,-500.5 350,-506.5 344,-512.5 338,-512.5 338,-512.5 12,-512.5 12,-512.5 6,-512.5 0,-506.5 0,-500.5 0,-500.5 0,-363.5 0,-363.5 0,-357.5 6,-351.5 12,-351.5"/>
<text text-anchor="middle" x="54" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin</text>
<polyline fill="none" stroke="#000000" points="108,-351.5 108,-512.5 "/>
<text text-anchor="middle" x="118.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="129,-351.5 129,-512.5 "/>
<text text-anchor="middle" x="229" y="-497.3" font-family="Times,serif" font-size="14.00" fill="#000000">adult_or_childhood_study</text>
<polyline fill="none" stroke="#000000" points="129,-489.5 329,-489.5 "/>
<text text-anchor="middle" x="229" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">data_types</text>
<polyline fill="none" stroke="#000000" points="129,-466.5 329,-466.5 "/>
<text text-anchor="middle" x="229" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_types_and_format</text>
<polyline fill="none" stroke="#000000" points="129,-443.5 329,-443.5 "/>
<text text-anchor="middle" x="229" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_participants</text>
<polyline fill="none" stroke="#000000" points="129,-420.5 329,-420.5 "/>
<text text-anchor="middle" x="229" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_samples</text>
<polyline fill="none" stroke="#000000" points="129,-397.5 329,-397.5 "/>
<text text-anchor="middle" x="229" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">organism_species</text>
<polyline fill="none" stroke="#000000" points="129,-374.5 329,-374.5 "/>
<text text-anchor="middle" x="229" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_admin_id</text>
<polyline fill="none" stroke="#000000" points="329,-351.5 329,-512.5 "/>
<text text-anchor="middle" x="339.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node12" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M498,-.5C498,-.5 888,-.5 888,-.5 894,-.5 900,-6.5 900,-12.5 900,-12.5 900,-287.5 900,-287.5 900,-293.5 894,-299.5 888,-299.5 888,-299.5 498,-299.5 498,-299.5 492,-299.5 486,-293.5 486,-287.5 486,-287.5 486,-12.5 486,-12.5 486,-6.5 492,-.5 498,-.5"/>
<text text-anchor="middle" x="514" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="542,-.5 542,-299.5 "/>
<text text-anchor="middle" x="552.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="563,-.5 563,-299.5 "/>
<text text-anchor="middle" x="721" y="-284.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="563,-276.5 879,-276.5 "/>
<text text-anchor="middle" x="721" y="-261.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="563,-253.5 879,-253.5 "/>
<text text-anchor="middle" x="721" y="-238.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="563,-230.5 879,-230.5 "/>
<text text-anchor="middle" x="721" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">experimental_strategy_and_data_subtype</text>
<polyline fill="none" stroke="#000000" points="563,-207.5 879,-207.5 "/>
<text text-anchor="middle" x="721" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="563,-184.5 879,-184.5 "/>
<text text-anchor="middle" x="721" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="563,-161.5 879,-161.5 "/>
<text text-anchor="middle" x="721" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">size_of_data_being_uploaded</text>
<polyline fill="none" stroke="#000000" points="563,-138.5 879,-138.5 "/>
<text text-anchor="middle" x="721" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="563,-115.5 879,-115.5 "/>
<text text-anchor="middle" x="721" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_data_types</text>
<polyline fill="none" stroke="#000000" points="563,-92.5 879,-92.5 "/>
<text text-anchor="middle" x="721" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="563,-69.5 879,-69.5 "/>
<text text-anchor="middle" x="721" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="563,-46.5 879,-46.5 "/>
<text text-anchor="middle" x="721" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="563,-23.5 879,-23.5 "/>
<text text-anchor="middle" x="721" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="879,-.5 879,-299.5 "/>
<text text-anchor="middle" x="889.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_admin&#45;&gt;study -->
<g id="edge2" class="edge">
<title>study_admin&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M225.2592,-351.3501C235.3579,-339.0844 246.6942,-327.4046 259,-318 322.7404,-269.2871 402.325,-233.0887 475.8742,-207.0251"/>
<polygon fill="#000000" stroke="#000000" points="477.4575,-210.1794 485.7424,-203.5755 475.1476,-203.5715 477.4575,-210.1794"/>
<text text-anchor="middle" x="315.5" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_admin</text>
</g>
<!-- family_relationship -->
<g id="node2" class="node">
<title>family_relationship</title>
<path fill="none" stroke="#000000" d="M2094.5,-932.5C2094.5,-932.5 2463.5,-932.5 2463.5,-932.5 2469.5,-932.5 2475.5,-938.5 2475.5,-944.5 2475.5,-944.5 2475.5,-1012.5 2475.5,-1012.5 2475.5,-1018.5 2469.5,-1024.5 2463.5,-1024.5 2463.5,-1024.5 2094.5,-1024.5 2094.5,-1024.5 2088.5,-1024.5 2082.5,-1018.5 2082.5,-1012.5 2082.5,-1012.5 2082.5,-944.5 2082.5,-944.5 2082.5,-938.5 2088.5,-932.5 2094.5,-932.5"/>
<text text-anchor="middle" x="2159.5" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship</text>
<polyline fill="none" stroke="#000000" points="2236.5,-932.5 2236.5,-1024.5 "/>
<text text-anchor="middle" x="2247" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2257.5,-932.5 2257.5,-1024.5 "/>
<text text-anchor="middle" x="2356" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_id</text>
<polyline fill="none" stroke="#000000" points="2257.5,-1001.5 2454.5,-1001.5 "/>
<text text-anchor="middle" x="2356" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">family_relationship_id</text>
<polyline fill="none" stroke="#000000" points="2257.5,-978.5 2454.5,-978.5 "/>
<text text-anchor="middle" x="2356" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">related_to_participant_id</text>
<polyline fill="none" stroke="#000000" points="2257.5,-955.5 2454.5,-955.5 "/>
<text text-anchor="middle" x="2356" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">relationship</text>
<polyline fill="none" stroke="#000000" points="2454.5,-932.5 2454.5,-1024.5 "/>
<text text-anchor="middle" x="2465" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node15" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1706,-374.5C1706,-374.5 2010,-374.5 2010,-374.5 2016,-374.5 2022,-380.5 2022,-386.5 2022,-386.5 2022,-477.5 2022,-477.5 2022,-483.5 2016,-489.5 2010,-489.5 2010,-489.5 1706,-489.5 1706,-489.5 1700,-489.5 1694,-483.5 1694,-477.5 1694,-477.5 1694,-386.5 1694,-386.5 1694,-380.5 1700,-374.5 1706,-374.5"/>
<text text-anchor="middle" x="1742" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1790,-374.5 1790,-489.5 "/>
<text text-anchor="middle" x="1800.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1811,-374.5 1811,-489.5 "/>
<text text-anchor="middle" x="1906" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_participant_id</text>
<polyline fill="none" stroke="#000000" points="1811,-466.5 2001,-466.5 "/>
<text text-anchor="middle" x="1906" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1811,-443.5 2001,-443.5 "/>
<text text-anchor="middle" x="1906" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="1811,-420.5 2001,-420.5 "/>
<text text-anchor="middle" x="1906" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1811,-397.5 2001,-397.5 "/>
<text text-anchor="middle" x="1906" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="2001,-374.5 2001,-489.5 "/>
<text text-anchor="middle" x="2011.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- family_relationship&#45;&gt;participant -->
<g id="edge9" class="edge">
<title>family_relationship&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2265.4254,-932.1974C2239.4316,-849.9667 2175.8956,-676.5298 2073,-564 2048.6175,-537.3346 2017.6235,-514.1477 1986.8109,-494.9665"/>
<polygon fill="#000000" stroke="#000000" points="1988.4888,-491.8901 1978.1307,-489.663 1984.8392,-497.8634 1988.4888,-491.8901"/>
<text text-anchor="middle" x="2133.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_family_relationship</text>
</g>
<!-- pdx -->
<g id="node3" class="node">
<title>pdx</title>
<path fill="none" stroke="#000000" d="M248.5,-1467.5C248.5,-1467.5 577.5,-1467.5 577.5,-1467.5 583.5,-1467.5 589.5,-1473.5 589.5,-1479.5 589.5,-1479.5 589.5,-1685.5 589.5,-1685.5 589.5,-1691.5 583.5,-1697.5 577.5,-1697.5 577.5,-1697.5 248.5,-1697.5 248.5,-1697.5 242.5,-1697.5 236.5,-1691.5 236.5,-1685.5 236.5,-1685.5 236.5,-1479.5 236.5,-1479.5 236.5,-1473.5 242.5,-1467.5 248.5,-1467.5"/>
<text text-anchor="middle" x="258" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000">pdx</text>
<polyline fill="none" stroke="#000000" points="279.5,-1467.5 279.5,-1697.5 "/>
<text text-anchor="middle" x="290" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="300.5,-1467.5 300.5,-1697.5 "/>
<text text-anchor="middle" x="434.5" y="-1682.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_site</text>
<polyline fill="none" stroke="#000000" points="300.5,-1674.5 568.5,-1674.5 "/>
<text text-anchor="middle" x="434.5" y="-1659.3" font-family="Times,serif" font-size="14.00" fill="#000000">implantation_type</text>
<polyline fill="none" stroke="#000000" points="300.5,-1651.5 568.5,-1651.5 "/>
<text text-anchor="middle" x="434.5" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">model_id</text>
<polyline fill="none" stroke="#000000" points="300.5,-1628.5 568.5,-1628.5 "/>
<text text-anchor="middle" x="434.5" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">mouse_strain</text>
<polyline fill="none" stroke="#000000" points="300.5,-1605.5 568.5,-1605.5 "/>
<text text-anchor="middle" x="434.5" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">pdx_id</text>
<polyline fill="none" stroke="#000000" points="300.5,-1582.5 568.5,-1582.5 "/>
<text text-anchor="middle" x="434.5" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">strain_immune_system_humanized</text>
<polyline fill="none" stroke="#000000" points="300.5,-1559.5 568.5,-1559.5 "/>
<text text-anchor="middle" x="434.5" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_characterization_method</text>
<polyline fill="none" stroke="#000000" points="300.5,-1536.5 568.5,-1536.5 "/>
<text text-anchor="middle" x="434.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_not_mus_or_ebv_origin</text>
<polyline fill="none" stroke="#000000" points="300.5,-1513.5 568.5,-1513.5 "/>
<text text-anchor="middle" x="434.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_preparation</text>
<polyline fill="none" stroke="#000000" points="300.5,-1490.5 568.5,-1490.5 "/>
<text text-anchor="middle" x="434.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_humanization</text>
<polyline fill="none" stroke="#000000" points="568.5,-1467.5 568.5,-1697.5 "/>
<text text-anchor="middle" x="579" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node11" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M468,-898C468,-898 782,-898 782,-898 788,-898 794,-904 794,-910 794,-910 794,-1047 794,-1047 794,-1053 788,-1059 782,-1059 782,-1059 468,-1059 468,-1059 462,-1059 456,-1053 456,-1047 456,-1047 456,-910 456,-910 456,-904 462,-898 468,-898"/>
<text text-anchor="middle" x="490" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="524,-898 524,-1059 "/>
<text text-anchor="middle" x="534.5" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="545,-898 545,-1059 "/>
<text text-anchor="middle" x="659" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">alternate_sample_id</text>
<polyline fill="none" stroke="#000000" points="545,-1036 773,-1036 "/>
<text text-anchor="middle" x="659" y="-1020.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="545,-1013 773,-1013 "/>
<text text-anchor="middle" x="659" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="545,-990 773,-990 "/>
<text text-anchor="middle" x="659" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="545,-967 773,-967 "/>
<text text-anchor="middle" x="659" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="545,-944 773,-944 "/>
<text text-anchor="middle" x="659" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="545,-921 773,-921 "/>
<text text-anchor="middle" x="659" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="773,-898 773,-1059 "/>
<text text-anchor="middle" x="783.5" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- pdx&#45;&gt;sample -->
<g id="edge3" class="edge">
<title>pdx&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M453.3746,-1467.4705C494.0329,-1351.6326 555.9284,-1175.2889 593.2206,-1069.0414"/>
<polygon fill="#000000" stroke="#000000" points="596.6304,-1069.8945 596.6399,-1059.2996 590.0255,-1067.5761 596.6304,-1069.8945"/>
<text text-anchor="middle" x="494" y="-1414.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_pdx</text>
</g>
<!-- clinical_measure_file -->
<g id="node4" class="node">
<title>clinical_measure_file</title>
<path fill="none" stroke="#000000" d="M53.5,-840.5C53.5,-840.5 426.5,-840.5 426.5,-840.5 432.5,-840.5 438.5,-846.5 438.5,-852.5 438.5,-852.5 438.5,-1104.5 438.5,-1104.5 438.5,-1110.5 432.5,-1116.5 426.5,-1116.5 426.5,-1116.5 53.5,-1116.5 53.5,-1116.5 47.5,-1116.5 41.5,-1110.5 41.5,-1104.5 41.5,-1104.5 41.5,-852.5 41.5,-852.5 41.5,-846.5 47.5,-840.5 53.5,-840.5"/>
<text text-anchor="middle" x="125" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file</text>
<polyline fill="none" stroke="#000000" points="208.5,-840.5 208.5,-1116.5 "/>
<text text-anchor="middle" x="219" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="229.5,-840.5 229.5,-1116.5 "/>
<text text-anchor="middle" x="323.5" y="-1101.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_algorithm</text>
<polyline fill="none" stroke="#000000" points="229.5,-1093.5 417.5,-1093.5 "/>
<text text-anchor="middle" x="323.5" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">checksum_value</text>
<polyline fill="none" stroke="#000000" points="229.5,-1070.5 417.5,-1070.5 "/>
<text text-anchor="middle" x="323.5" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_measure_file_id</text>
<polyline fill="none" stroke="#000000" points="229.5,-1047.5 417.5,-1047.5 "/>
<text text-anchor="middle" x="323.5" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="229.5,-1024.5 417.5,-1024.5 "/>
<text text-anchor="middle" x="323.5" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="229.5,-1001.5 417.5,-1001.5 "/>
<text text-anchor="middle" x="323.5" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_mapping_level</text>
<polyline fill="none" stroke="#000000" points="229.5,-978.5 417.5,-978.5 "/>
<text text-anchor="middle" x="323.5" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="229.5,-955.5 417.5,-955.5 "/>
<text text-anchor="middle" x="323.5" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="229.5,-932.5 417.5,-932.5 "/>
<text text-anchor="middle" x="323.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="229.5,-909.5 417.5,-909.5 "/>
<text text-anchor="middle" x="323.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_url_in_cds</text>
<polyline fill="none" stroke="#000000" points="229.5,-886.5 417.5,-886.5 "/>
<text text-anchor="middle" x="323.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="229.5,-863.5 417.5,-863.5 "/>
<text text-anchor="middle" x="323.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_list</text>
<polyline fill="none" stroke="#000000" points="417.5,-840.5 417.5,-1116.5 "/>
<text text-anchor="middle" x="428" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_measure_file&#45;&gt;study -->
<g id="edge5" class="edge">
<title>clinical_measure_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M282.9191,-840.4332C327.4298,-708.5362 404.7091,-507.2553 506,-351 515.5157,-336.3208 526.1466,-321.7191 537.3775,-307.4744"/>
<polygon fill="#000000" stroke="#000000" points="540.1632,-309.595 543.6753,-299.5993 534.6963,-305.2231 540.1632,-309.595"/>
<text text-anchor="middle" x="592" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file</text>
</g>
<!-- clinical_measure_file&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>clinical_measure_file&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M275.3867,-840.1378C305.9345,-748.4242 359.3314,-632.7397 447,-564 499.3518,-522.9517 527.2232,-540.9544 593,-531 697.9405,-515.1187 1361.7878,-467.0428 1683.5663,-444.2456"/>
<polygon fill="#000000" stroke="#000000" points="1684.1988,-447.7097 1693.9266,-443.512 1683.7043,-440.7272 1684.1988,-447.7097"/>
<text text-anchor="middle" x="722.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_clinical_measure_file_participant</text>
</g>
<!-- diagnosis -->
<g id="node5" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M3484,-783C3484,-783 3858,-783 3858,-783 3864,-783 3870,-789 3870,-795 3870,-795 3870,-1162 3870,-1162 3870,-1168 3864,-1174 3858,-1174 3858,-1174 3484,-1174 3484,-1174 3478,-1174 3472,-1168 3472,-1162 3472,-1162 3472,-795 3472,-795 3472,-789 3478,-783 3484,-783"/>
<text text-anchor="middle" x="3514" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="3556,-783 3556,-1174 "/>
<text text-anchor="middle" x="3566.5" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3577,-783 3577,-1174 "/>
<text text-anchor="middle" x="3713" y="-1158.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="3577,-1151 3849,-1151 "/>
<text text-anchor="middle" x="3713" y="-1135.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="3577,-1128 3849,-1128 "/>
<text text-anchor="middle" x="3713" y="-1112.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="3577,-1105 3849,-1105 "/>
<text text-anchor="middle" x="3713" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="3577,-1082 3849,-1082 "/>
<text text-anchor="middle" x="3713" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_recurrence</text>
<polyline fill="none" stroke="#000000" points="3577,-1059 3849,-1059 "/>
<text text-anchor="middle" x="3713" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="3577,-1036 3849,-1036 "/>
<text text-anchor="middle" x="3713" y="-1020.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="3577,-1013 3849,-1013 "/>
<text text-anchor="middle" x="3713" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="3577,-990 3849,-990 "/>
<text text-anchor="middle" x="3713" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="3577,-967 3849,-967 "/>
<text text-anchor="middle" x="3713" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="3577,-944 3849,-944 "/>
<text text-anchor="middle" x="3713" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="3577,-921 3849,-921 "/>
<text text-anchor="middle" x="3713" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="3577,-898 3849,-898 "/>
<text text-anchor="middle" x="3713" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="3577,-875 3849,-875 "/>
<text text-anchor="middle" x="3713" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="3577,-852 3849,-852 "/>
<text text-anchor="middle" x="3713" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="3577,-829 3849,-829 "/>
<text text-anchor="middle" x="3713" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="3577,-806 3849,-806 "/>
<text text-anchor="middle" x="3713" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="3849,-783 3849,-1174 "/>
<text text-anchor="middle" x="3859.5" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3603.4123,-782.8677C3569.3565,-706.8391 3521.5439,-623.8307 3458,-564 3431.486,-539.0354 3418.3764,-539.6447 3383,-531 3131.3751,-469.512 2376.3933,-444.2272 2032.3061,-435.6904"/>
<polygon fill="#000000" stroke="#000000" points="2032.3299,-432.19 2022.2468,-435.4427 2032.1575,-439.1879 2032.3299,-432.19"/>
<text text-anchor="middle" x="3476.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- therapeutic_procedure -->
<g id="node6" class="node">
<title>therapeutic_procedure</title>
<path fill="none" stroke="#000000" d="M824.5,-909.5C824.5,-909.5 1225.5,-909.5 1225.5,-909.5 1231.5,-909.5 1237.5,-915.5 1237.5,-921.5 1237.5,-921.5 1237.5,-1035.5 1237.5,-1035.5 1237.5,-1041.5 1231.5,-1047.5 1225.5,-1047.5 1225.5,-1047.5 824.5,-1047.5 824.5,-1047.5 818.5,-1047.5 812.5,-1041.5 812.5,-1035.5 812.5,-1035.5 812.5,-921.5 812.5,-921.5 812.5,-915.5 818.5,-909.5 824.5,-909.5"/>
<text text-anchor="middle" x="903" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure</text>
<polyline fill="none" stroke="#000000" points="993.5,-909.5 993.5,-1047.5 "/>
<text text-anchor="middle" x="1004" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1014.5,-909.5 1014.5,-1047.5 "/>
<text text-anchor="middle" x="1115.5" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_end</text>
<polyline fill="none" stroke="#000000" points="1014.5,-1024.5 1216.5,-1024.5 "/>
<text text-anchor="middle" x="1115.5" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1014.5,-1001.5 1216.5,-1001.5 "/>
<text text-anchor="middle" x="1115.5" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_agents</text>
<polyline fill="none" stroke="#000000" points="1014.5,-978.5 1216.5,-978.5 "/>
<text text-anchor="middle" x="1115.5" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_procedure_id</text>
<polyline fill="none" stroke="#000000" points="1014.5,-955.5 1216.5,-955.5 "/>
<text text-anchor="middle" x="1115.5" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_outcome</text>
<polyline fill="none" stroke="#000000" points="1014.5,-932.5 1216.5,-932.5 "/>
<text text-anchor="middle" x="1115.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1216.5,-909.5 1216.5,-1047.5 "/>
<text text-anchor="middle" x="1227" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- therapeutic_procedure&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>therapeutic_procedure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1042.4118,-909.2914C1069.6624,-815.8283 1131.6183,-650.9747 1247,-564 1314.839,-512.863 1528.2277,-474.9032 1683.7646,-453.1293"/>
<polygon fill="#000000" stroke="#000000" points="1684.5002,-456.5608 1693.9237,-451.7185 1683.5373,-449.6274 1684.5002,-456.5608"/>
<text text-anchor="middle" x="1396" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_therapeutic_procedure</text>
</g>
<!-- medical_history -->
<g id="node7" class="node">
<title>medical_history</title>
<path fill="none" stroke="#000000" d="M1268,-944C1268,-944 1622,-944 1622,-944 1628,-944 1634,-950 1634,-956 1634,-956 1634,-1001 1634,-1001 1634,-1007 1628,-1013 1622,-1013 1622,-1013 1268,-1013 1268,-1013 1262,-1013 1256,-1007 1256,-1001 1256,-1001 1256,-956 1256,-956 1256,-950 1262,-944 1268,-944"/>
<text text-anchor="middle" x="1321.5" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history</text>
<polyline fill="none" stroke="#000000" points="1387,-944 1387,-1013 "/>
<text text-anchor="middle" x="1397.5" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1408,-944 1408,-1013 "/>
<text text-anchor="middle" x="1510.5" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_category</text>
<polyline fill="none" stroke="#000000" points="1408,-990 1613,-990 "/>
<text text-anchor="middle" x="1510.5" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_condition</text>
<polyline fill="none" stroke="#000000" points="1408,-967 1613,-967 "/>
<text text-anchor="middle" x="1510.5" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">medical_history_id</text>
<polyline fill="none" stroke="#000000" points="1613,-944 1613,-1013 "/>
<text text-anchor="middle" x="1623.5" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- medical_history&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>medical_history&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1454.2033,-943.8342C1475.9209,-867.4583 1536.6886,-682.1017 1643,-564 1667.1068,-537.2197 1697.9223,-514.02 1728.6455,-494.8651"/>
<polygon fill="#000000" stroke="#000000" points="1730.5981,-497.7736 1737.3029,-489.5701 1726.9458,-491.802 1730.5981,-497.7736"/>
<text text-anchor="middle" x="1746" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_medical_history</text>
</g>
<!-- sample_diagnosis -->
<g id="node8" class="node">
<title>sample_diagnosis</title>
<path fill="none" stroke="#000000" d="M619.5,-1444.5C619.5,-1444.5 1052.5,-1444.5 1052.5,-1444.5 1058.5,-1444.5 1064.5,-1450.5 1064.5,-1456.5 1064.5,-1456.5 1064.5,-1708.5 1064.5,-1708.5 1064.5,-1714.5 1058.5,-1720.5 1052.5,-1720.5 1052.5,-1720.5 619.5,-1720.5 619.5,-1720.5 613.5,-1720.5 607.5,-1714.5 607.5,-1708.5 607.5,-1708.5 607.5,-1456.5 607.5,-1456.5 607.5,-1450.5 613.5,-1444.5 619.5,-1444.5"/>
<text text-anchor="middle" x="679" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis</text>
<polyline fill="none" stroke="#000000" points="750.5,-1444.5 750.5,-1720.5 "/>
<text text-anchor="middle" x="761" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="771.5,-1444.5 771.5,-1720.5 "/>
<text text-anchor="middle" x="907.5" y="-1705.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_followup</text>
<polyline fill="none" stroke="#000000" points="771.5,-1697.5 1043.5,-1697.5 "/>
<text text-anchor="middle" x="907.5" y="-1682.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="771.5,-1674.5 1043.5,-1674.5 "/>
<text text-anchor="middle" x="907.5" y="-1659.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_finer_resolution</text>
<polyline fill="none" stroke="#000000" points="771.5,-1651.5 1043.5,-1651.5 "/>
<text text-anchor="middle" x="907.5" y="-1636.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_cm</text>
<polyline fill="none" stroke="#000000" points="771.5,-1628.5 1043.5,-1628.5 "/>
<text text-anchor="middle" x="907.5" y="-1613.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_icd_o</text>
<polyline fill="none" stroke="#000000" points="771.5,-1605.5 1043.5,-1605.5 "/>
<text text-anchor="middle" x="907.5" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_disease_status</text>
<polyline fill="none" stroke="#000000" points="771.5,-1582.5 1043.5,-1582.5 "/>
<text text-anchor="middle" x="907.5" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="771.5,-1559.5 1043.5,-1559.5 "/>
<text text-anchor="middle" x="907.5" y="-1544.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="771.5,-1536.5 1043.5,-1536.5 "/>
<text text-anchor="middle" x="907.5" y="-1521.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="771.5,-1513.5 1043.5,-1513.5 "/>
<text text-anchor="middle" x="907.5" y="-1498.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="771.5,-1490.5 1043.5,-1490.5 "/>
<text text-anchor="middle" x="907.5" y="-1475.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="771.5,-1467.5 1043.5,-1467.5 "/>
<text text-anchor="middle" x="907.5" y="-1452.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1043.5,-1444.5 1043.5,-1720.5 "/>
<text text-anchor="middle" x="1054" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample_diagnosis&#45;&gt;sample -->
<g id="edge17" class="edge">
<title>sample_diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M787.7246,-1444.3089C747.4612,-1329.0525 691.2531,-1168.1535 656.5406,-1068.7868"/>
<polygon fill="#000000" stroke="#000000" points="659.7479,-1067.355 653.1457,-1059.0688 653.1395,-1069.6636 659.7479,-1067.355"/>
<text text-anchor="middle" x="854" y="-1414.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample_diagnosis</text>
</g>
<!-- molecular_test -->
<g id="node9" class="node">
<title>molecular_test</title>
<path fill="none" stroke="#000000" d="M1664,-564.5C1664,-564.5 2052,-564.5 2052,-564.5 2058,-564.5 2064,-570.5 2064,-576.5 2064,-576.5 2064,-1380.5 2064,-1380.5 2064,-1386.5 2058,-1392.5 2052,-1392.5 2052,-1392.5 1664,-1392.5 1664,-1392.5 1658,-1392.5 1652,-1386.5 1652,-1380.5 1652,-1380.5 1652,-576.5 1652,-576.5 1652,-570.5 1658,-564.5 1664,-564.5"/>
<text text-anchor="middle" x="1713.5" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test</text>
<polyline fill="none" stroke="#000000" points="1775,-564.5 1775,-1392.5 "/>
<text text-anchor="middle" x="1785.5" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1796,-564.5 1796,-1392.5 "/>
<text text-anchor="middle" x="1919.5" y="-1377.3" font-family="Times,serif" font-size="14.00" fill="#000000">aa_change</text>
<polyline fill="none" stroke="#000000" points="1796,-1369.5 2043,-1369.5 "/>
<text text-anchor="middle" x="1919.5" y="-1354.3" font-family="Times,serif" font-size="14.00" fill="#000000">antigen</text>
<polyline fill="none" stroke="#000000" points="1796,-1346.5 2043,-1346.5 "/>
<text text-anchor="middle" x="1919.5" y="-1331.3" font-family="Times,serif" font-size="14.00" fill="#000000">biospecimen_type</text>
<polyline fill="none" stroke="#000000" points="1796,-1323.5 2043,-1323.5 "/>
<text text-anchor="middle" x="1919.5" y="-1308.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_lower</text>
<polyline fill="none" stroke="#000000" points="1796,-1300.5 2043,-1300.5 "/>
<text text-anchor="middle" x="1919.5" y="-1285.3" font-family="Times,serif" font-size="14.00" fill="#000000">blood_test_normal_range_upper</text>
<polyline fill="none" stroke="#000000" points="1796,-1277.5 2043,-1277.5 "/>
<text text-anchor="middle" x="1919.5" y="-1262.3" font-family="Times,serif" font-size="14.00" fill="#000000">cell_count</text>
<polyline fill="none" stroke="#000000" points="1796,-1254.5 2043,-1254.5 "/>
<text text-anchor="middle" x="1919.5" y="-1239.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="1796,-1231.5 2043,-1231.5 "/>
<text text-anchor="middle" x="1919.5" y="-1216.3" font-family="Times,serif" font-size="14.00" fill="#000000">copy_number</text>
<polyline fill="none" stroke="#000000" points="1796,-1208.5 2043,-1208.5 "/>
<text text-anchor="middle" x="1919.5" y="-1193.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="1796,-1185.5 2043,-1185.5 "/>
<text text-anchor="middle" x="1919.5" y="-1170.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="1796,-1162.5 2043,-1162.5 "/>
<text text-anchor="middle" x="1919.5" y="-1147.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="1796,-1139.5 2043,-1139.5 "/>
<text text-anchor="middle" x="1919.5" y="-1124.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_family</text>
<polyline fill="none" stroke="#000000" points="1796,-1116.5 2043,-1116.5 "/>
<text text-anchor="middle" x="1919.5" y="-1101.3" font-family="Times,serif" font-size="14.00" fill="#000000">histone_variant</text>
<polyline fill="none" stroke="#000000" points="1796,-1093.5 2043,-1093.5 "/>
<text text-anchor="middle" x="1919.5" y="-1078.3" font-family="Times,serif" font-size="14.00" fill="#000000">intron</text>
<polyline fill="none" stroke="#000000" points="1796,-1070.5 2043,-1070.5 "/>
<text text-anchor="middle" x="1919.5" y="-1055.3" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="1796,-1047.5 2043,-1047.5 "/>
<text text-anchor="middle" x="1919.5" y="-1032.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_abnormal_count</text>
<polyline fill="none" stroke="#000000" points="1796,-1024.5 2043,-1024.5 "/>
<text text-anchor="middle" x="1919.5" y="-1009.3" font-family="Times,serif" font-size="14.00" fill="#000000">loci_count</text>
<polyline fill="none" stroke="#000000" points="1796,-1001.5 2043,-1001.5 "/>
<text text-anchor="middle" x="1919.5" y="-986.3" font-family="Times,serif" font-size="14.00" fill="#000000">locus</text>
<polyline fill="none" stroke="#000000" points="1796,-978.5 2043,-978.5 "/>
<text text-anchor="middle" x="1919.5" y="-963.3" font-family="Times,serif" font-size="14.00" fill="#000000">mismatch_repair_mutation</text>
<polyline fill="none" stroke="#000000" points="1796,-955.5 2043,-955.5 "/>
<text text-anchor="middle" x="1919.5" y="-940.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_analysis_method</text>
<polyline fill="none" stroke="#000000" points="1796,-932.5 2043,-932.5 "/>
<text text-anchor="middle" x="1919.5" y="-917.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_consequence</text>
<polyline fill="none" stroke="#000000" points="1796,-909.5 2043,-909.5 "/>
<text text-anchor="middle" x="1919.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_test_id</text>
<polyline fill="none" stroke="#000000" points="1796,-886.5 2043,-886.5 "/>
<text text-anchor="middle" x="1919.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathogenicity</text>
<polyline fill="none" stroke="#000000" points="1796,-863.5 2043,-863.5 "/>
<text text-anchor="middle" x="1919.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">ploidy</text>
<polyline fill="none" stroke="#000000" points="1796,-840.5 2043,-840.5 "/>
<text text-anchor="middle" x="1919.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">second_exon</text>
<polyline fill="none" stroke="#000000" points="1796,-817.5 2043,-817.5 "/>
<text text-anchor="middle" x="1919.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">second_gene_symbol</text>
<polyline fill="none" stroke="#000000" points="1796,-794.5 2043,-794.5 "/>
<text text-anchor="middle" x="1919.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">specialized_molecular_test</text>
<polyline fill="none" stroke="#000000" points="1796,-771.5 2043,-771.5 "/>
<text text-anchor="middle" x="1919.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">start_days_from_index</text>
<polyline fill="none" stroke="#000000" points="1796,-748.5 2043,-748.5 "/>
<text text-anchor="middle" x="1919.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">test_analyte_type</text>
<polyline fill="none" stroke="#000000" points="1796,-725.5 2043,-725.5 "/>
<text text-anchor="middle" x="1919.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">test_result</text>
<polyline fill="none" stroke="#000000" points="1796,-702.5 2043,-702.5 "/>
<text text-anchor="middle" x="1919.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">test_units</text>
<polyline fill="none" stroke="#000000" points="1796,-679.5 2043,-679.5 "/>
<text text-anchor="middle" x="1919.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">test_value</text>
<polyline fill="none" stroke="#000000" points="1796,-656.5 2043,-656.5 "/>
<text text-anchor="middle" x="1919.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">transcript</text>
<polyline fill="none" stroke="#000000" points="1796,-633.5 2043,-633.5 "/>
<text text-anchor="middle" x="1919.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">variant_origin</text>
<polyline fill="none" stroke="#000000" points="1796,-610.5 2043,-610.5 "/>
<text text-anchor="middle" x="1919.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">variant_type</text>
<polyline fill="none" stroke="#000000" points="1796,-587.5 2043,-587.5 "/>
<text text-anchor="middle" x="1919.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">zygosity</text>
<polyline fill="none" stroke="#000000" points="2043,-564.5 2043,-1392.5 "/>
<text text-anchor="middle" x="2053.5" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- molecular_test&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>molecular_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1858,-564.2924C1858,-540.4267 1858,-518.5365 1858,-499.7244"/>
<polygon fill="#000000" stroke="#000000" points="1861.5001,-499.5969 1858,-489.597 1854.5001,-499.597 1861.5001,-499.5969"/>
<text text-anchor="middle" x="1922" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_molecular_test</text>
</g>
<!-- synonym -->
<g id="node10" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M3218.5,-1559.5C3218.5,-1559.5 3519.5,-1559.5 3519.5,-1559.5 3525.5,-1559.5 3531.5,-1565.5 3531.5,-1571.5 3531.5,-1571.5 3531.5,-1593.5 3531.5,-1593.5 3531.5,-1599.5 3525.5,-1605.5 3519.5,-1605.5 3519.5,-1605.5 3218.5,-1605.5 3218.5,-1605.5 3212.5,-1605.5 3206.5,-1599.5 3206.5,-1593.5 3206.5,-1593.5 3206.5,-1571.5 3206.5,-1571.5 3206.5,-1565.5 3212.5,-1559.5 3218.5,-1559.5"/>
<text text-anchor="middle" x="3246.5" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="3286.5,-1559.5 3286.5,-1605.5 "/>
<text text-anchor="middle" x="3297" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3307.5,-1559.5 3307.5,-1605.5 "/>
<text text-anchor="middle" x="3409" y="-1590.3" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="3307.5,-1582.5 3510.5,-1582.5 "/>
<text text-anchor="middle" x="3409" y="-1567.3" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="3510.5,-1559.5 3510.5,-1605.5 "/>
<text text-anchor="middle" x="3521" y="-1578.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>synonym&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M3206.3392,-1571.6109C2645.832,-1533.9477 827.6067,-1410.5464 803,-1393 697.5342,-1317.7951 654.0464,-1166.7463 636.4746,-1069.2482"/>
<polygon fill="#000000" stroke="#000000" points="639.8715,-1068.3536 634.7049,-1059.104 632.9757,-1069.5568 639.8715,-1068.3536"/>
<text text-anchor="middle" x="1175.5" y="-1414.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge6" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M3469.6713,-1559.4583C3604.1523,-1526.4046 3831.1135,-1461.8785 3879,-1393 3984.1599,-1241.7412 4000.5825,-702.4035 3879,-564 3682.4456,-340.2521 1596.2985,-201.6862 910.2855,-161.9057"/>
<polygon fill="#000000" stroke="#000000" points="910.4742,-158.4109 900.2886,-161.3273 910.0697,-165.3992 910.4742,-158.4109"/>
<text text-anchor="middle" x="3900.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3369.2724,-1559.2755C3370.9052,-1410.9732 3378.1841,-601.4786 3343,-564 3254.8126,-470.0615 2405.3782,-442.397 2032.2799,-434.7411"/>
<polygon fill="#000000" stroke="#000000" points="2032.2655,-431.2402 2022.1966,-434.5367 2032.1236,-438.2388 2032.2655,-431.2402"/>
<text text-anchor="middle" x="3413.5" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge16" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M637.252,-897.8126C649.9073,-811.1054 669.1557,-669.1381 679,-546 685.2046,-468.39 688.6594,-382.0042 690.5831,-309.771"/>
<polygon fill="#000000" stroke="#000000" points="694.0844,-309.7622 690.8445,-299.6749 687.0867,-309.581 694.0844,-309.7622"/>
<text text-anchor="middle" x="726.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M635.5157,-897.9569C652.6318,-801.9344 696.1258,-644.3768 803,-564 871.8995,-512.1828 1402.0666,-465.698 1683.5884,-444.3576"/>
<polygon fill="#000000" stroke="#000000" points="1684.2022,-447.8213 1693.9102,-443.578 1683.675,-440.8412 1684.2022,-447.8213"/>
<text text-anchor="middle" x="925.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- follow_up -->
<g id="node13" class="node">
<title>follow_up</title>
<path fill="none" stroke="#000000" d="M2505.5,-875C2505.5,-875 2868.5,-875 2868.5,-875 2874.5,-875 2880.5,-881 2880.5,-887 2880.5,-887 2880.5,-1070 2880.5,-1070 2880.5,-1076 2874.5,-1082 2868.5,-1082 2868.5,-1082 2505.5,-1082 2505.5,-1082 2499.5,-1082 2493.5,-1076 2493.5,-1070 2493.5,-1070 2493.5,-887 2493.5,-887 2493.5,-881 2499.5,-875 2505.5,-875"/>
<text text-anchor="middle" x="2536" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
<polyline fill="none" stroke="#000000" points="2578.5,-875 2578.5,-1082 "/>
<text text-anchor="middle" x="2589" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2599.5,-875 2599.5,-1082 "/>
<text text-anchor="middle" x="2729.5" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event</text>
<polyline fill="none" stroke="#000000" points="2599.5,-1059 2859.5,-1059 "/>
<text text-anchor="middle" x="2729.5" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity</text>
<polyline fill="none" stroke="#000000" points="2599.5,-1036 2859.5,-1036 "/>
<text text-anchor="middle" x="2729.5" y="-1020.8" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity_method_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2599.5,-1013 2859.5,-1013 "/>
<text text-anchor="middle" x="2729.5" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">days_to_follow_up</text>
<polyline fill="none" stroke="#000000" points="2599.5,-990 2859.5,-990 "/>
<text text-anchor="middle" x="2729.5" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_response</text>
<polyline fill="none" stroke="#000000" points="2599.5,-967 2859.5,-967 "/>
<text text-anchor="middle" x="2729.5" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_category</text>
<polyline fill="none" stroke="#000000" points="2599.5,-944 2859.5,-944 "/>
<text text-anchor="middle" x="2729.5" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_id</text>
<polyline fill="none" stroke="#000000" points="2599.5,-921 2859.5,-921 "/>
<text text-anchor="middle" x="2729.5" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_other</text>
<polyline fill="none" stroke="#000000" points="2599.5,-898 2859.5,-898 "/>
<text text-anchor="middle" x="2729.5" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">risk_factor</text>
<polyline fill="none" stroke="#000000" points="2859.5,-875 2859.5,-1082 "/>
<text text-anchor="middle" x="2870" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- follow_up&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>follow_up&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2664.0721,-874.7008C2637.4533,-779.2433 2583.9437,-641.1742 2485,-564 2415.6235,-509.8876 2192.5797,-472.2485 2032.2673,-451.3858"/>
<polygon fill="#000000" stroke="#000000" points="2032.648,-447.906 2022.2823,-450.0974 2031.7521,-454.8484 2032.648,-447.906"/>
<text text-anchor="middle" x="2495" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_follow_up</text>
</g>
<!-- exposure -->
<g id="node14" class="node">
<title>exposure</title>
<path fill="none" stroke="#000000" d="M2910.5,-737C2910.5,-737 3321.5,-737 3321.5,-737 3327.5,-737 3333.5,-743 3333.5,-749 3333.5,-749 3333.5,-1208 3333.5,-1208 3333.5,-1214 3327.5,-1220 3321.5,-1220 3321.5,-1220 2910.5,-1220 2910.5,-1220 2904.5,-1220 2898.5,-1214 2898.5,-1208 2898.5,-1208 2898.5,-749 2898.5,-749 2898.5,-743 2904.5,-737 2910.5,-737"/>
<text text-anchor="middle" x="2939.5" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure</text>
<polyline fill="none" stroke="#000000" points="2980.5,-737 2980.5,-1220 "/>
<text text-anchor="middle" x="2991" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3001.5,-737 3001.5,-1220 "/>
<text text-anchor="middle" x="3157" y="-1204.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_days_per_week</text>
<polyline fill="none" stroke="#000000" points="3001.5,-1197 3312.5,-1197 "/>
<text text-anchor="middle" x="3157" y="-1181.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_drinks_per_day</text>
<polyline fill="none" stroke="#000000" points="3001.5,-1174 3312.5,-1174 "/>
<text text-anchor="middle" x="3157" y="-1158.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_history</text>
<polyline fill="none" stroke="#000000" points="3001.5,-1151 3312.5,-1151 "/>
<text text-anchor="middle" x="3157" y="-1135.8" font-family="Times,serif" font-size="14.00" fill="#000000">alcohol_intensity</text>
<polyline fill="none" stroke="#000000" points="3001.5,-1128 3312.5,-1128 "/>
<text text-anchor="middle" x="3157" y="-1112.8" font-family="Times,serif" font-size="14.00" fill="#000000">asbestos_exposure</text>
<polyline fill="none" stroke="#000000" points="3001.5,-1105 3312.5,-1105 "/>
<text text-anchor="middle" x="3157" y="-1089.8" font-family="Times,serif" font-size="14.00" fill="#000000">cigarettes_per_day</text>
<polyline fill="none" stroke="#000000" points="3001.5,-1082 3312.5,-1082 "/>
<text text-anchor="middle" x="3157" y="-1066.8" font-family="Times,serif" font-size="14.00" fill="#000000">coal_dust_exposure</text>
<polyline fill="none" stroke="#000000" points="3001.5,-1059 3312.5,-1059 "/>
<text text-anchor="middle" x="3157" y="-1043.8" font-family="Times,serif" font-size="14.00" fill="#000000">environmental_tobacco_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="3001.5,-1036 3312.5,-1036 "/>
<text text-anchor="middle" x="3157" y="-1020.8" font-family="Times,serif" font-size="14.00" fill="#000000">exposure_id</text>
<polyline fill="none" stroke="#000000" points="3001.5,-1013 3312.5,-1013 "/>
<text text-anchor="middle" x="3157" y="-997.8" font-family="Times,serif" font-size="14.00" fill="#000000">pack_years_smoked</text>
<polyline fill="none" stroke="#000000" points="3001.5,-990 3312.5,-990 "/>
<text text-anchor="middle" x="3157" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000">radon_exposure</text>
<polyline fill="none" stroke="#000000" points="3001.5,-967 3312.5,-967 "/>
<text text-anchor="middle" x="3157" y="-951.8" font-family="Times,serif" font-size="14.00" fill="#000000">respirable_crystalline_silica_exposure</text>
<polyline fill="none" stroke="#000000" points="3001.5,-944 3312.5,-944 "/>
<text text-anchor="middle" x="3157" y="-928.8" font-family="Times,serif" font-size="14.00" fill="#000000">smoking_frequency</text>
<polyline fill="none" stroke="#000000" points="3001.5,-921 3312.5,-921 "/>
<text text-anchor="middle" x="3157" y="-905.8" font-family="Times,serif" font-size="14.00" fill="#000000">start_days_from_index</text>
<polyline fill="none" stroke="#000000" points="3001.5,-898 3312.5,-898 "/>
<text text-anchor="middle" x="3157" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">time_between_waking_and_first_smoke</text>
<polyline fill="none" stroke="#000000" points="3001.5,-875 3312.5,-875 "/>
<text text-anchor="middle" x="3157" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_onset_year</text>
<polyline fill="none" stroke="#000000" points="3001.5,-852 3312.5,-852 "/>
<text text-anchor="middle" x="3157" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_quit_year</text>
<polyline fill="none" stroke="#000000" points="3001.5,-829 3312.5,-829 "/>
<text text-anchor="middle" x="3157" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">tobacco_smoking_status</text>
<polyline fill="none" stroke="#000000" points="3001.5,-806 3312.5,-806 "/>
<text text-anchor="middle" x="3157" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_smoke_exposure</text>
<polyline fill="none" stroke="#000000" points="3001.5,-783 3312.5,-783 "/>
<text text-anchor="middle" x="3157" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_tobacco_used</text>
<polyline fill="none" stroke="#000000" points="3001.5,-760 3312.5,-760 "/>
<text text-anchor="middle" x="3157" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">years_smoked</text>
<polyline fill="none" stroke="#000000" points="3312.5,-737 3312.5,-1220 "/>
<text text-anchor="middle" x="3323" y="-974.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- exposure&#45;&gt;participant -->
<g id="edge18" class="edge">
<title>exposure&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M3032.3991,-736.8735C2998.1965,-670.9725 2951.7526,-606.1945 2890,-564 2754.1892,-471.2029 2289.2742,-443.6335 2032.2732,-435.4496"/>
<polygon fill="#000000" stroke="#000000" points="2032.1897,-431.9454 2022.0854,-435.1319 2031.9714,-438.942 2032.1897,-431.9454"/>
<text text-anchor="middle" x="2891.5" y="-534.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_exposure</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge11" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1693.8627,-392.2689C1488.8365,-342.6402 1137.4226,-257.577 910.2536,-202.5884"/>
<polygon fill="#000000" stroke="#000000" points="910.7482,-199.1071 900.2055,-200.1562 909.1013,-205.9107 910.7482,-199.1071"/>
<text text-anchor="middle" x="1498.5" y="-321.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
</g>
</svg>
</div>
