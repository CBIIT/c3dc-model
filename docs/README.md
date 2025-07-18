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
<svg width="2426pt" height="1528pt"
 viewBox="0.00 0.00 2425.50 1528.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1524)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1524 2421.5,-1524 2421.5,4 -4,4"/>
<!-- reference_file -->
<g id="node1" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M1206.5,-213.5C1206.5,-213.5 1483.5,-213.5 1483.5,-213.5 1489.5,-213.5 1495.5,-219.5 1495.5,-225.5 1495.5,-225.5 1495.5,-431.5 1495.5,-431.5 1495.5,-437.5 1489.5,-443.5 1483.5,-443.5 1483.5,-443.5 1206.5,-443.5 1206.5,-443.5 1200.5,-443.5 1194.5,-437.5 1194.5,-431.5 1194.5,-431.5 1194.5,-225.5 1194.5,-225.5 1194.5,-219.5 1200.5,-213.5 1206.5,-213.5"/>
<text text-anchor="middle" x="1252.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="1310.5,-213.5 1310.5,-443.5 "/>
<text text-anchor="middle" x="1321" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1331.5,-213.5 1331.5,-443.5 "/>
<text text-anchor="middle" x="1403" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="1331.5,-420.5 1474.5,-420.5 "/>
<text text-anchor="middle" x="1403" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="1331.5,-397.5 1474.5,-397.5 "/>
<text text-anchor="middle" x="1403" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1331.5,-374.5 1474.5,-374.5 "/>
<text text-anchor="middle" x="1403" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1331.5,-351.5 1474.5,-351.5 "/>
<text text-anchor="middle" x="1403" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1331.5,-328.5 1474.5,-328.5 "/>
<text text-anchor="middle" x="1403" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1331.5,-305.5 1474.5,-305.5 "/>
<text text-anchor="middle" x="1403" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1331.5,-282.5 1474.5,-282.5 "/>
<text text-anchor="middle" x="1403" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1331.5,-259.5 1474.5,-259.5 "/>
<text text-anchor="middle" x="1403" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="1331.5,-236.5 1474.5,-236.5 "/>
<text text-anchor="middle" x="1403" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="1474.5,-213.5 1474.5,-443.5 "/>
<text text-anchor="middle" x="1485" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node9" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1578.5,-.5C1578.5,-.5 1797.5,-.5 1797.5,-.5 1803.5,-.5 1809.5,-6.5 1809.5,-12.5 1809.5,-12.5 1809.5,-149.5 1809.5,-149.5 1809.5,-155.5 1803.5,-161.5 1797.5,-161.5 1797.5,-161.5 1578.5,-161.5 1578.5,-161.5 1572.5,-161.5 1566.5,-155.5 1566.5,-149.5 1566.5,-149.5 1566.5,-12.5 1566.5,-12.5 1566.5,-6.5 1572.5,-.5 1578.5,-.5"/>
<text text-anchor="middle" x="1594.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1622.5,-.5 1622.5,-161.5 "/>
<text text-anchor="middle" x="1633" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1643.5,-.5 1643.5,-161.5 "/>
<text text-anchor="middle" x="1716" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">dbgap_accession</text>
<polyline fill="none" stroke="#000000" points="1643.5,-138.5 1788.5,-138.5 "/>
<text text-anchor="middle" x="1716" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="1643.5,-115.5 1788.5,-115.5 "/>
<text text-anchor="middle" x="1716" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1643.5,-92.5 1788.5,-92.5 "/>
<text text-anchor="middle" x="1716" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="1643.5,-69.5 1788.5,-69.5 "/>
<text text-anchor="middle" x="1716" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="1643.5,-46.5 1788.5,-46.5 "/>
<text text-anchor="middle" x="1716" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="1643.5,-23.5 1788.5,-23.5 "/>
<text text-anchor="middle" x="1716" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_status</text>
<polyline fill="none" stroke="#000000" points="1788.5,-.5 1788.5,-161.5 "/>
<text text-anchor="middle" x="1799" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge11" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1495.7422,-219.6806C1498.8553,-217.4341 1501.944,-215.2052 1505,-213 1525.3319,-198.3287 1546.9361,-182.7424 1567.9055,-167.6159"/>
<polygon fill="#000000" stroke="#000000" points="1570.1556,-170.3084 1576.2182,-161.6195 1566.0604,-164.6313 1570.1556,-170.3084"/>
<text text-anchor="middle" x="1610.5" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- survival -->
<g id="node2" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M787.5,-662.5C787.5,-662.5 1148.5,-662.5 1148.5,-662.5 1154.5,-662.5 1160.5,-668.5 1160.5,-674.5 1160.5,-674.5 1160.5,-834.5 1160.5,-834.5 1160.5,-840.5 1154.5,-846.5 1148.5,-846.5 1148.5,-846.5 787.5,-846.5 787.5,-846.5 781.5,-846.5 775.5,-840.5 775.5,-834.5 775.5,-834.5 775.5,-674.5 775.5,-674.5 775.5,-668.5 781.5,-662.5 787.5,-662.5"/>
<text text-anchor="middle" x="812.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="849.5,-662.5 849.5,-846.5 "/>
<text text-anchor="middle" x="860" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="870.5,-662.5 870.5,-846.5 "/>
<text text-anchor="middle" x="1005" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="870.5,-823.5 1139.5,-823.5 "/>
<text text-anchor="middle" x="1005" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="870.5,-800.5 1139.5,-800.5 "/>
<text text-anchor="middle" x="1005" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="870.5,-777.5 1139.5,-777.5 "/>
<text text-anchor="middle" x="1005" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="870.5,-754.5 1139.5,-754.5 "/>
<text text-anchor="middle" x="1005" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="870.5,-731.5 1139.5,-731.5 "/>
<text text-anchor="middle" x="1005" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="870.5,-708.5 1139.5,-708.5 "/>
<text text-anchor="middle" x="1005" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="870.5,-685.5 1139.5,-685.5 "/>
<text text-anchor="middle" x="1005" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="1139.5,-662.5 1139.5,-846.5 "/>
<text text-anchor="middle" x="1150" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node11" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M1255.5,-495.5C1255.5,-495.5 1486.5,-495.5 1486.5,-495.5 1492.5,-495.5 1498.5,-501.5 1498.5,-507.5 1498.5,-507.5 1498.5,-575.5 1498.5,-575.5 1498.5,-581.5 1492.5,-587.5 1486.5,-587.5 1486.5,-587.5 1255.5,-587.5 1255.5,-587.5 1249.5,-587.5 1243.5,-581.5 1243.5,-575.5 1243.5,-575.5 1243.5,-507.5 1243.5,-507.5 1243.5,-501.5 1249.5,-495.5 1255.5,-495.5"/>
<text text-anchor="middle" x="1291.5" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1339.5,-495.5 1339.5,-587.5 "/>
<text text-anchor="middle" x="1350" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1360.5,-495.5 1360.5,-587.5 "/>
<text text-anchor="middle" x="1419" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1360.5,-564.5 1477.5,-564.5 "/>
<text text-anchor="middle" x="1419" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="1360.5,-541.5 1477.5,-541.5 "/>
<text text-anchor="middle" x="1419" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1360.5,-518.5 1477.5,-518.5 "/>
<text text-anchor="middle" x="1419" y="-503.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="1477.5,-495.5 1477.5,-587.5 "/>
<text text-anchor="middle" x="1488" y="-537.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1126.7756,-662.3787C1141.3203,-654.3451 1155.8872,-646.4467 1170,-639 1199.9984,-623.1712 1232.9578,-606.7789 1263.3543,-592.0552"/>
<polygon fill="#000000" stroke="#000000" points="1265.2167,-595.0426 1272.6993,-587.5418 1262.1723,-588.7393 1265.2167,-595.0426"/>
<text text-anchor="middle" x="1269.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- consent_group -->
<g id="node3" class="node">
<title>consent_group</title>
<path fill="none" stroke="#000000" d="M1525.5,-271C1525.5,-271 1850.5,-271 1850.5,-271 1856.5,-271 1862.5,-277 1862.5,-283 1862.5,-283 1862.5,-374 1862.5,-374 1862.5,-380 1856.5,-386 1850.5,-386 1850.5,-386 1525.5,-386 1525.5,-386 1519.5,-386 1513.5,-380 1513.5,-374 1513.5,-374 1513.5,-283 1513.5,-283 1513.5,-277 1519.5,-271 1525.5,-271"/>
<text text-anchor="middle" x="1574.5" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group</text>
<polyline fill="none" stroke="#000000" points="1635.5,-271 1635.5,-386 "/>
<text text-anchor="middle" x="1646" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1656.5,-271 1656.5,-386 "/>
<text text-anchor="middle" x="1749" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_id</text>
<polyline fill="none" stroke="#000000" points="1656.5,-363 1841.5,-363 "/>
<text text-anchor="middle" x="1749" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_name</text>
<polyline fill="none" stroke="#000000" points="1656.5,-340 1841.5,-340 "/>
<text text-anchor="middle" x="1749" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_number</text>
<polyline fill="none" stroke="#000000" points="1656.5,-317 1841.5,-317 "/>
<text text-anchor="middle" x="1749" y="-301.8" font-family="Times,serif" font-size="14.00" fill="#000000">consent_group_suffix</text>
<polyline fill="none" stroke="#000000" points="1656.5,-294 1841.5,-294 "/>
<text text-anchor="middle" x="1749" y="-278.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1841.5,-271 1841.5,-386 "/>
<text text-anchor="middle" x="1852" y="-324.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- consent_group&#45;&gt;study -->
<g id="edge6" class="edge">
<title>consent_group&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1688,-270.7846C1688,-241.3997 1688,-204.9895 1688,-171.9435"/>
<polygon fill="#000000" stroke="#000000" points="1691.5001,-171.8072 1688,-161.8073 1684.5001,-171.8073 1691.5001,-171.8072"/>
<text text-anchor="middle" x="1751.5" y="-183.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_consent_group</text>
</g>
<!-- treatment -->
<g id="node4" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M1594,-639.5C1594,-639.5 1886,-639.5 1886,-639.5 1892,-639.5 1898,-645.5 1898,-651.5 1898,-651.5 1898,-857.5 1898,-857.5 1898,-863.5 1892,-869.5 1886,-869.5 1886,-869.5 1594,-869.5 1594,-869.5 1588,-869.5 1582,-863.5 1582,-857.5 1582,-857.5 1582,-651.5 1582,-651.5 1582,-645.5 1588,-639.5 1594,-639.5"/>
<text text-anchor="middle" x="1626.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1671,-639.5 1671,-869.5 "/>
<text text-anchor="middle" x="1681.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1692,-639.5 1692,-869.5 "/>
<text text-anchor="middle" x="1784.5" y="-854.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_end</text>
<polyline fill="none" stroke="#000000" points="1692,-846.5 1877,-846.5 "/>
<text text-anchor="middle" x="1784.5" y="-831.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_treatment_start</text>
<polyline fill="none" stroke="#000000" points="1692,-823.5 1877,-823.5 "/>
<text text-anchor="middle" x="1784.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose</text>
<polyline fill="none" stroke="#000000" points="1692,-800.5 1877,-800.5 "/>
<text text-anchor="middle" x="1784.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_frequency</text>
<polyline fill="none" stroke="#000000" points="1692,-777.5 1877,-777.5 "/>
<text text-anchor="middle" x="1784.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_route</text>
<polyline fill="none" stroke="#000000" points="1692,-754.5 1877,-754.5 "/>
<text text-anchor="middle" x="1784.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_unit</text>
<polyline fill="none" stroke="#000000" points="1692,-731.5 1877,-731.5 "/>
<text text-anchor="middle" x="1784.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1692,-708.5 1877,-708.5 "/>
<text text-anchor="middle" x="1784.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_agent</text>
<polyline fill="none" stroke="#000000" points="1692,-685.5 1877,-685.5 "/>
<text text-anchor="middle" x="1784.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_id</text>
<polyline fill="none" stroke="#000000" points="1692,-662.5 1877,-662.5 "/>
<text text-anchor="middle" x="1784.5" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_type</text>
<polyline fill="none" stroke="#000000" points="1877,-639.5 1877,-869.5 "/>
<text text-anchor="middle" x="1887.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>treatment&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1595.2909,-639.4177C1577.474,-627.3958 1559.1402,-615.9539 1541,-606 1530.4092,-600.1886 1519.1858,-594.6733 1507.7555,-589.4955"/>
<polygon fill="#000000" stroke="#000000" points="1509.113,-586.2688 1498.5525,-585.416 1506.2763,-592.6683 1509.113,-586.2688"/>
<text text-anchor="middle" x="1611" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment</text>
</g>
<!-- sample -->
<g id="node5" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M306,-651C306,-651 620,-651 620,-651 626,-651 632,-657 632,-663 632,-663 632,-846 632,-846 632,-852 626,-858 620,-858 620,-858 306,-858 306,-858 300,-858 294,-852 294,-846 294,-846 294,-663 294,-663 294,-657 300,-651 306,-651"/>
<text text-anchor="middle" x="328" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="362,-651 362,-858 "/>
<text text-anchor="middle" x="372.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="383,-651 383,-858 "/>
<text text-anchor="middle" x="497" y="-842.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="383,-835 611,-835 "/>
<text text-anchor="middle" x="497" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="383,-812 611,-812 "/>
<text text-anchor="middle" x="497" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="383,-789 611,-789 "/>
<text text-anchor="middle" x="497" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_necrosis</text>
<polyline fill="none" stroke="#000000" points="383,-766 611,-766 "/>
<text text-anchor="middle" x="497" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">percent_tumor</text>
<polyline fill="none" stroke="#000000" points="383,-743 611,-743 "/>
<text text-anchor="middle" x="497" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="383,-720 611,-720 "/>
<text text-anchor="middle" x="497" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="383,-697 611,-697 "/>
<text text-anchor="middle" x="497" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="383,-674 611,-674 "/>
<text text-anchor="middle" x="497" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="611,-651 611,-858 "/>
<text text-anchor="middle" x="621.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M526.8233,-650.8068C542.3721,-633.1081 560.5208,-616.9341 581,-606 636.9477,-576.1289 1022.0101,-555.8308 1233.1554,-546.809"/>
<polygon fill="#000000" stroke="#000000" points="1233.5446,-550.2958 1243.3872,-546.3749 1233.2478,-543.302 1233.5446,-550.2958"/>
<text text-anchor="middle" x="617.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- genetic_analysis -->
<g id="node6" class="node">
<title>genetic_analysis</title>
<path fill="none" stroke="#000000" d="M1395,-921.5C1395,-921.5 1779,-921.5 1779,-921.5 1785,-921.5 1791,-927.5 1791,-933.5 1791,-933.5 1791,-1507.5 1791,-1507.5 1791,-1513.5 1785,-1519.5 1779,-1519.5 1779,-1519.5 1395,-1519.5 1395,-1519.5 1389,-1519.5 1383,-1513.5 1383,-1507.5 1383,-1507.5 1383,-933.5 1383,-933.5 1383,-927.5 1389,-921.5 1395,-921.5"/>
<text text-anchor="middle" x="1450.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="1518,-921.5 1518,-1519.5 "/>
<text text-anchor="middle" x="1528.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1539,-921.5 1539,-1519.5 "/>
<text text-anchor="middle" x="1654.5" y="-1504.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_genetic_analysis</text>
<polyline fill="none" stroke="#000000" points="1539,-1496.5 1770,-1496.5 "/>
<text text-anchor="middle" x="1654.5" y="-1481.3" font-family="Times,serif" font-size="14.00" fill="#000000">allelic_ratio</text>
<polyline fill="none" stroke="#000000" points="1539,-1473.5 1770,-1473.5 "/>
<text text-anchor="middle" x="1654.5" y="-1458.3" font-family="Times,serif" font-size="14.00" fill="#000000">alteration</text>
<polyline fill="none" stroke="#000000" points="1539,-1450.5 1770,-1450.5 "/>
<text text-anchor="middle" x="1654.5" y="-1435.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="1539,-1427.5 1770,-1427.5 "/>
<text text-anchor="middle" x="1654.5" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome_location</text>
<polyline fill="none" stroke="#000000" points="1539,-1404.5 1770,-1404.5 "/>
<text text-anchor="middle" x="1654.5" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">cytoband</text>
<polyline fill="none" stroke="#000000" points="1539,-1381.5 1770,-1381.5 "/>
<text text-anchor="middle" x="1654.5" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">dna_index_numeric</text>
<polyline fill="none" stroke="#000000" points="1539,-1358.5 1770,-1358.5 "/>
<text text-anchor="middle" x="1654.5" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="1539,-1335.5 1770,-1335.5 "/>
<text text-anchor="middle" x="1654.5" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_exon</text>
<polyline fill="none" stroke="#000000" points="1539,-1312.5 1770,-1312.5 "/>
<text text-anchor="middle" x="1654.5" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_gene</text>
<polyline fill="none" stroke="#000000" points="1539,-1289.5 1770,-1289.5 "/>
<text text-anchor="middle" x="1654.5" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">fusion_partner_transcript</text>
<polyline fill="none" stroke="#000000" points="1539,-1266.5 1770,-1266.5 "/>
<text text-anchor="middle" x="1654.5" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_symbol</text>
<polyline fill="none" stroke="#000000" points="1539,-1243.5 1770,-1243.5 "/>
<text text-anchor="middle" x="1654.5" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">genetic_analysis_id</text>
<polyline fill="none" stroke="#000000" points="1539,-1220.5 1770,-1220.5 "/>
<text text-anchor="middle" x="1654.5" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_source_category</text>
<polyline fill="none" stroke="#000000" points="1539,-1197.5 1770,-1197.5 "/>
<text text-anchor="middle" x="1654.5" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_coding</text>
<polyline fill="none" stroke="#000000" points="1539,-1174.5 1770,-1174.5 "/>
<text text-anchor="middle" x="1654.5" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_genome</text>
<polyline fill="none" stroke="#000000" points="1539,-1151.5 1770,-1151.5 "/>
<text text-anchor="middle" x="1654.5" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs_protein</text>
<polyline fill="none" stroke="#000000" points="1539,-1128.5 1770,-1128.5 "/>
<text text-anchor="middle" x="1654.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1539,-1105.5 1770,-1105.5 "/>
<text text-anchor="middle" x="1654.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">karyotype</text>
<polyline fill="none" stroke="#000000" points="1539,-1082.5 1770,-1082.5 "/>
<text text-anchor="middle" x="1654.5" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_genome</text>
<polyline fill="none" stroke="#000000" points="1539,-1059.5 1770,-1059.5 "/>
<text text-anchor="middle" x="1654.5" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance</text>
<polyline fill="none" stroke="#000000" points="1539,-1036.5 1770,-1036.5 "/>
<text text-anchor="middle" x="1654.5" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">reported_significance_system</text>
<polyline fill="none" stroke="#000000" points="1539,-1013.5 1770,-1013.5 "/>
<text text-anchor="middle" x="1654.5" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">result</text>
<polyline fill="none" stroke="#000000" points="1539,-990.5 1770,-990.5 "/>
<text text-anchor="middle" x="1654.5" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="1539,-967.5 1770,-967.5 "/>
<text text-anchor="middle" x="1654.5" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">test</text>
<polyline fill="none" stroke="#000000" points="1539,-944.5 1770,-944.5 "/>
<text text-anchor="middle" x="1654.5" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">+ 2 properties</text>
<polyline fill="none" stroke="#000000" points="1770,-921.5 1770,-1519.5 "/>
<text text-anchor="middle" x="1780.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genetic_analysis&#45;&gt;sample -->
<g id="edge8" class="edge">
<title>genetic_analysis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1382.7466,-1138.7139C1225.627,-1076.6682 1002.6692,-990.4947 805,-921 734.9879,-896.3858 713.2483,-901.3883 646,-870 640.9998,-867.6662 635.971,-865.2199 630.9333,-862.6819"/>
<polygon fill="#000000" stroke="#000000" points="632.3542,-859.477 621.8602,-858.0187 629.1543,-865.7028 632.3542,-859.477"/>
<text text-anchor="middle" x="814" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- genetic_analysis&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>genetic_analysis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1791.1102,-1047.2102C1838.147,-995.519 1881.7499,-935.1063 1907,-870 1925.5615,-822.14 1939.8901,-678.4126 1907,-639 1857.2146,-579.3416 1650.5381,-556.0996 1508.8714,-547.1038"/>
<polygon fill="#000000" stroke="#000000" points="1508.9837,-543.6041 1498.7868,-546.4804 1508.5518,-550.5908 1508.9837,-543.6041"/>
<text text-anchor="middle" x="1996" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_genetic_analysis</text>
</g>
<!-- laboratory_test -->
<g id="node7" class="node">
<title>laboratory_test</title>
<path fill="none" stroke="#000000" d="M12,-1094C12,-1094 344,-1094 344,-1094 350,-1094 356,-1100 356,-1106 356,-1106 356,-1335 356,-1335 356,-1341 350,-1347 344,-1347 344,-1347 12,-1347 12,-1347 6,-1347 0,-1341 0,-1335 0,-1335 0,-1106 0,-1106 0,-1100 6,-1094 12,-1094"/>
<text text-anchor="middle" x="63" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test</text>
<polyline fill="none" stroke="#000000" points="126,-1094 126,-1347 "/>
<text text-anchor="middle" x="136.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="147,-1094 147,-1347 "/>
<text text-anchor="middle" x="241" y="-1331.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_laboratory_test</text>
<polyline fill="none" stroke="#000000" points="147,-1324 335,-1324 "/>
<text text-anchor="middle" x="241" y="-1308.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="147,-1301 335,-1301 "/>
<text text-anchor="middle" x="241" y="-1285.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_id</text>
<polyline fill="none" stroke="#000000" points="147,-1278 335,-1278 "/>
<text text-anchor="middle" x="241" y="-1262.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_method</text>
<polyline fill="none" stroke="#000000" points="147,-1255 335,-1255 "/>
<text text-anchor="middle" x="241" y="-1239.8" font-family="Times,serif" font-size="14.00" fill="#000000">laboratory_test_name</text>
<polyline fill="none" stroke="#000000" points="147,-1232 335,-1232 "/>
<text text-anchor="middle" x="241" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">sensitivity</text>
<polyline fill="none" stroke="#000000" points="147,-1209 335,-1209 "/>
<text text-anchor="middle" x="241" y="-1193.8" font-family="Times,serif" font-size="14.00" fill="#000000">specimen</text>
<polyline fill="none" stroke="#000000" points="147,-1186 335,-1186 "/>
<text text-anchor="middle" x="241" y="-1170.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_modifier</text>
<polyline fill="none" stroke="#000000" points="147,-1163 335,-1163 "/>
<text text-anchor="middle" x="241" y="-1147.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_numeric</text>
<polyline fill="none" stroke="#000000" points="147,-1140 335,-1140 "/>
<text text-anchor="middle" x="241" y="-1124.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_text</text>
<polyline fill="none" stroke="#000000" points="147,-1117 335,-1117 "/>
<text text-anchor="middle" x="241" y="-1101.8" font-family="Times,serif" font-size="14.00" fill="#000000">test_result_unit</text>
<polyline fill="none" stroke="#000000" points="335,-1094 335,-1347 "/>
<text text-anchor="middle" x="345.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- laboratory_test&#45;&gt;sample -->
<g id="edge4" class="edge">
<title>laboratory_test&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M247.7802,-1093.8714C283.1658,-1031.183 327.5469,-954.81 370,-888 374.4642,-880.9745 379.133,-873.7974 383.9001,-866.5968"/>
<polygon fill="#000000" stroke="#000000" points="386.9022,-868.4033 389.535,-858.1408 381.0771,-864.5215 386.9022,-868.4033"/>
<text text-anchor="middle" x="435.5" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- laboratory_test&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>laboratory_test&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M126.6176,-1093.9879C82.651,-962.7537 42.4076,-760.1283 154,-639 190.1335,-599.7787 921.7573,-561.9605 1232.8959,-547.5844"/>
<polygon fill="#000000" stroke="#000000" points="1233.5049,-551.0602 1243.3333,-547.1037 1233.1828,-544.0676 1233.5049,-551.0602"/>
<text text-anchor="middle" x="219.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_laboratory_test</text>
</g>
<!-- diagnosis -->
<g id="node8" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M419.5,-1013.5C419.5,-1013.5 784.5,-1013.5 784.5,-1013.5 790.5,-1013.5 796.5,-1019.5 796.5,-1025.5 796.5,-1025.5 796.5,-1415.5 796.5,-1415.5 796.5,-1421.5 790.5,-1427.5 784.5,-1427.5 784.5,-1427.5 419.5,-1427.5 419.5,-1427.5 413.5,-1427.5 407.5,-1421.5 407.5,-1415.5 407.5,-1415.5 407.5,-1025.5 407.5,-1025.5 407.5,-1019.5 413.5,-1013.5 419.5,-1013.5"/>
<text text-anchor="middle" x="449.5" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="491.5,-1013.5 491.5,-1427.5 "/>
<text text-anchor="middle" x="502" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="512.5,-1013.5 512.5,-1427.5 "/>
<text text-anchor="middle" x="644" y="-1412.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="512.5,-1404.5 775.5,-1404.5 "/>
<text text-anchor="middle" x="644" y="-1389.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="512.5,-1381.5 775.5,-1381.5 "/>
<text text-anchor="middle" x="644" y="-1366.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="512.5,-1358.5 775.5,-1358.5 "/>
<text text-anchor="middle" x="644" y="-1343.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="512.5,-1335.5 775.5,-1335.5 "/>
<text text-anchor="middle" x="644" y="-1320.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_category</text>
<polyline fill="none" stroke="#000000" points="512.5,-1312.5 775.5,-1312.5 "/>
<text text-anchor="middle" x="644" y="-1297.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="512.5,-1289.5 775.5,-1289.5 "/>
<text text-anchor="middle" x="644" y="-1274.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="512.5,-1266.5 775.5,-1266.5 "/>
<text text-anchor="middle" x="644" y="-1251.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="512.5,-1243.5 775.5,-1243.5 "/>
<text text-anchor="middle" x="644" y="-1228.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="512.5,-1220.5 775.5,-1220.5 "/>
<text text-anchor="middle" x="644" y="-1205.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="512.5,-1197.5 775.5,-1197.5 "/>
<text text-anchor="middle" x="644" y="-1182.3" font-family="Times,serif" font-size="14.00" fill="#000000">laterality</text>
<polyline fill="none" stroke="#000000" points="512.5,-1174.5 775.5,-1174.5 "/>
<text text-anchor="middle" x="644" y="-1159.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="512.5,-1151.5 775.5,-1151.5 "/>
<text text-anchor="middle" x="644" y="-1136.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="512.5,-1128.5 775.5,-1128.5 "/>
<text text-anchor="middle" x="644" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="512.5,-1105.5 775.5,-1105.5 "/>
<text text-anchor="middle" x="644" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="512.5,-1082.5 775.5,-1082.5 "/>
<text text-anchor="middle" x="644" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="512.5,-1059.5 775.5,-1059.5 "/>
<text text-anchor="middle" x="644" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="512.5,-1036.5 775.5,-1036.5 "/>
<text text-anchor="middle" x="644" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="775.5,-1013.5 775.5,-1427.5 "/>
<text text-anchor="middle" x="786" y="-1216.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;sample -->
<g id="edge12" class="edge">
<title>diagnosis&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M540.2231,-1013.3918C525.3258,-963.4483 509.9492,-911.8981 496.877,-868.0733"/>
<polygon fill="#000000" stroke="#000000" points="500.1642,-866.8487 493.9518,-858.2664 493.4563,-868.8496 500.1642,-866.8487"/>
<text text-anchor="middle" x="549.5" y="-891.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M625.8058,-1013.1584C645.1181,-848.919 670.2121,-645.8651 677,-639 715.4491,-600.1137 1042.1713,-567.7589 1233.3079,-551.9403"/>
<polygon fill="#000000" stroke="#000000" points="1233.7558,-555.4154 1243.4351,-551.1071 1233.1818,-548.4389 1233.7558,-555.4154"/>
<text text-anchor="middle" x="721.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
<!-- synonym -->
<g id="node10" class="node">
<title>synonym</title>
<path fill="none" stroke="#000000" d="M2104.5,-674C2104.5,-674 2405.5,-674 2405.5,-674 2411.5,-674 2417.5,-680 2417.5,-686 2417.5,-686 2417.5,-823 2417.5,-823 2417.5,-829 2411.5,-835 2405.5,-835 2405.5,-835 2104.5,-835 2104.5,-835 2098.5,-835 2092.5,-829 2092.5,-823 2092.5,-823 2092.5,-686 2092.5,-686 2092.5,-680 2098.5,-674 2104.5,-674"/>
<text text-anchor="middle" x="2132.5" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym</text>
<polyline fill="none" stroke="#000000" points="2172.5,-674 2172.5,-835 "/>
<text text-anchor="middle" x="2183" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2193.5,-674 2193.5,-835 "/>
<text text-anchor="middle" x="2295" y="-819.8" font-family="Times,serif" font-size="14.00" fill="#000000">associated_id</text>
<polyline fill="none" stroke="#000000" points="2193.5,-812 2396.5,-812 "/>
<text text-anchor="middle" x="2295" y="-796.8" font-family="Times,serif" font-size="14.00" fill="#000000">data_location</text>
<polyline fill="none" stroke="#000000" points="2193.5,-789 2396.5,-789 "/>
<text text-anchor="middle" x="2295" y="-773.8" font-family="Times,serif" font-size="14.00" fill="#000000">domain_category</text>
<polyline fill="none" stroke="#000000" points="2193.5,-766 2396.5,-766 "/>
<text text-anchor="middle" x="2295" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">domain_description</text>
<polyline fill="none" stroke="#000000" points="2193.5,-743 2396.5,-743 "/>
<text text-anchor="middle" x="2295" y="-727.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2193.5,-720 2396.5,-720 "/>
<text text-anchor="middle" x="2295" y="-704.8" font-family="Times,serif" font-size="14.00" fill="#000000">repository_of_synonym_id</text>
<polyline fill="none" stroke="#000000" points="2193.5,-697 2396.5,-697 "/>
<text text-anchor="middle" x="2295" y="-681.8" font-family="Times,serif" font-size="14.00" fill="#000000">synonym_id</text>
<polyline fill="none" stroke="#000000" points="2396.5,-674 2396.5,-835 "/>
<text text-anchor="middle" x="2407" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- synonym&#45;&gt;study -->
<g id="edge2" class="edge">
<title>synonym&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2209.679,-673.8816C2144.4634,-562.2555 2016.0403,-358.0083 1872,-213 1855.636,-196.526 1837.0288,-180.6274 1818.0844,-165.9156"/>
<polygon fill="#000000" stroke="#000000" points="1820.0173,-162.9874 1809.9503,-159.685 1815.7606,-168.5445 1820.0173,-162.9874"/>
<text text-anchor="middle" x="2123.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- synonym&#45;&gt;participant -->
<g id="edge1" class="edge">
<title>synonym&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M2143.3949,-673.8525C2122.3434,-660.9297 2100.0094,-648.6545 2078,-639 1978.7277,-595.4539 1684.8632,-565.8856 1508.7959,-551.5313"/>
<polygon fill="#000000" stroke="#000000" points="1508.9273,-548.0306 1498.6775,-550.7125 1508.3626,-555.0078 1508.9273,-548.0306"/>
<text text-anchor="middle" x="2064.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_synonym</text>
</g>
<!-- participant&#45;&gt;consent_group -->
<g id="edge9" class="edge">
<title>participant&#45;&gt;consent_group</title>
<path fill="none" stroke="#000000" d="M1439.7843,-495.2822C1484.8839,-464.9786 1544.4332,-424.966 1593.8994,-391.7285"/>
<polygon fill="#000000" stroke="#000000" points="1596.0301,-394.5136 1602.3784,-386.0312 1592.1261,-388.7033 1596.0301,-394.5136"/>
<text text-anchor="middle" x="1532.5" y="-465.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- treatment_response -->
<g id="node12" class="node">
<title>treatment_response</title>
<path fill="none" stroke="#000000" d="M1190.5,-685.5C1190.5,-685.5 1551.5,-685.5 1551.5,-685.5 1557.5,-685.5 1563.5,-691.5 1563.5,-697.5 1563.5,-697.5 1563.5,-811.5 1563.5,-811.5 1563.5,-817.5 1557.5,-823.5 1551.5,-823.5 1551.5,-823.5 1190.5,-823.5 1190.5,-823.5 1184.5,-823.5 1178.5,-817.5 1178.5,-811.5 1178.5,-811.5 1178.5,-697.5 1178.5,-697.5 1178.5,-691.5 1184.5,-685.5 1190.5,-685.5"/>
<text text-anchor="middle" x="1259" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response</text>
<polyline fill="none" stroke="#000000" points="1339.5,-685.5 1339.5,-823.5 "/>
<text text-anchor="middle" x="1350" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1360.5,-685.5 1360.5,-823.5 "/>
<text text-anchor="middle" x="1451.5" y="-808.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_response</text>
<polyline fill="none" stroke="#000000" points="1360.5,-800.5 1542.5,-800.5 "/>
<text text-anchor="middle" x="1451.5" y="-785.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1360.5,-777.5 1542.5,-777.5 "/>
<text text-anchor="middle" x="1451.5" y="-762.3" font-family="Times,serif" font-size="14.00" fill="#000000">response</text>
<polyline fill="none" stroke="#000000" points="1360.5,-754.5 1542.5,-754.5 "/>
<text text-anchor="middle" x="1451.5" y="-739.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_category</text>
<polyline fill="none" stroke="#000000" points="1360.5,-731.5 1542.5,-731.5 "/>
<text text-anchor="middle" x="1451.5" y="-716.3" font-family="Times,serif" font-size="14.00" fill="#000000">response_system</text>
<polyline fill="none" stroke="#000000" points="1360.5,-708.5 1542.5,-708.5 "/>
<text text-anchor="middle" x="1451.5" y="-693.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_response_id</text>
<polyline fill="none" stroke="#000000" points="1542.5,-685.5 1542.5,-823.5 "/>
<text text-anchor="middle" x="1553" y="-750.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment_response&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>treatment_response&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1371,-685.345C1371,-657.1412 1371,-624.9366 1371,-598.1595"/>
<polygon fill="#000000" stroke="#000000" points="1374.5001,-597.805 1371,-587.805 1367.5001,-597.805 1374.5001,-597.805"/>
<text text-anchor="middle" x="1454" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_treatment_response</text>
</g>
</g>
</svg>
</div>
