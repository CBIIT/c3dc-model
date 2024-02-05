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
<svg width="1233pt" height="918pt"
 viewBox="0.00 0.00 1233.00 918.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 914)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-914 1229,-914 1229,4 -4,4"/>
<!-- survival -->
<g id="node1" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M12,-656.5C12,-656.5 373,-656.5 373,-656.5 379,-656.5 385,-662.5 385,-668.5 385,-668.5 385,-782.5 385,-782.5 385,-788.5 379,-794.5 373,-794.5 373,-794.5 12,-794.5 12,-794.5 6,-794.5 0,-788.5 0,-782.5 0,-782.5 0,-668.5 0,-668.5 0,-662.5 6,-656.5 12,-656.5"/>
<text text-anchor="middle" x="37" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="74,-656.5 74,-794.5 "/>
<text text-anchor="middle" x="84.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="95,-656.5 95,-794.5 "/>
<text text-anchor="middle" x="229.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="95,-771.5 364,-771.5 "/>
<text text-anchor="middle" x="229.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="95,-748.5 364,-748.5 "/>
<text text-anchor="middle" x="229.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">event_free_survival_status</text>
<polyline fill="none" stroke="#000000" points="95,-725.5 364,-725.5 "/>
<text text-anchor="middle" x="229.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">first_event</text>
<polyline fill="none" stroke="#000000" points="95,-702.5 364,-702.5 "/>
<text text-anchor="middle" x="229.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">last_known_survival_status</text>
<polyline fill="none" stroke="#000000" points="95,-679.5 364,-679.5 "/>
<text text-anchor="middle" x="229.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_id</text>
<polyline fill="none" stroke="#000000" points="364,-656.5 364,-794.5 "/>
<text text-anchor="middle" x="374.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node5" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M461,-340C461,-340 692,-340 692,-340 698,-340 704,-346 704,-352 704,-352 704,-420 704,-420 704,-426 698,-432 692,-432 692,-432 461,-432 461,-432 455,-432 449,-426 449,-420 449,-420 449,-352 449,-352 449,-346 455,-340 461,-340"/>
<text text-anchor="middle" x="497" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="545,-340 545,-432 "/>
<text text-anchor="middle" x="555.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="566,-340 566,-432 "/>
<text text-anchor="middle" x="624.5" y="-416.8" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="566,-409 683,-409 "/>
<text text-anchor="middle" x="624.5" y="-393.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant_id</text>
<polyline fill="none" stroke="#000000" points="566,-386 683,-386 "/>
<text text-anchor="middle" x="624.5" y="-370.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="566,-363 683,-363 "/>
<text text-anchor="middle" x="624.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">sex_at_birth</text>
<polyline fill="none" stroke="#000000" points="683,-340 683,-432 "/>
<text text-anchor="middle" x="693.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;participant -->
<g id="edge2" class="edge">
<title>survival&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M266.3131,-656.4438C304.0374,-621.4842 350.867,-578.595 393.5,-541 432.6936,-506.4379 477.4425,-468.5093 512.8791,-438.8224"/>
<polygon fill="#000000" stroke="#000000" points="515.3302,-441.335 520.7531,-432.2331 510.8378,-435.9667 515.3302,-441.335"/>
<text text-anchor="middle" x="468" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_survival</text>
</g>
<!-- reference_file -->
<g id="node2" class="node">
<title>reference_file</title>
<path fill="none" stroke="#000000" d="M734,-282.5C734,-282.5 1011,-282.5 1011,-282.5 1017,-282.5 1023,-288.5 1023,-294.5 1023,-294.5 1023,-477.5 1023,-477.5 1023,-483.5 1017,-489.5 1011,-489.5 1011,-489.5 734,-489.5 734,-489.5 728,-489.5 722,-483.5 722,-477.5 722,-477.5 722,-294.5 722,-294.5 722,-288.5 728,-282.5 734,-282.5"/>
<text text-anchor="middle" x="780" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file</text>
<polyline fill="none" stroke="#000000" points="838,-282.5 838,-489.5 "/>
<text text-anchor="middle" x="848.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="859,-282.5 859,-489.5 "/>
<text text-anchor="middle" x="930.5" y="-474.3" font-family="Times,serif" font-size="14.00" fill="#000000">dcf_indexd_guid</text>
<polyline fill="none" stroke="#000000" points="859,-466.5 1002,-466.5 "/>
<text text-anchor="middle" x="930.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_category</text>
<polyline fill="none" stroke="#000000" points="859,-443.5 1002,-443.5 "/>
<text text-anchor="middle" x="930.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="859,-420.5 1002,-420.5 "/>
<text text-anchor="middle" x="930.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="859,-397.5 1002,-397.5 "/>
<text text-anchor="middle" x="930.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="859,-374.5 1002,-374.5 "/>
<text text-anchor="middle" x="930.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="859,-351.5 1002,-351.5 "/>
<text text-anchor="middle" x="930.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="859,-328.5 1002,-328.5 "/>
<text text-anchor="middle" x="930.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_id</text>
<polyline fill="none" stroke="#000000" points="859,-305.5 1002,-305.5 "/>
<text text-anchor="middle" x="930.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">reference_file_url</text>
<polyline fill="none" stroke="#000000" points="1002,-282.5 1002,-489.5 "/>
<text text-anchor="middle" x="1012.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node3" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M763,-.5C763,-.5 982,-.5 982,-.5 988,-.5 994,-6.5 994,-12.5 994,-12.5 994,-218.5 994,-218.5 994,-224.5 988,-230.5 982,-230.5 982,-230.5 763,-230.5 763,-230.5 757,-230.5 751,-224.5 751,-218.5 751,-218.5 751,-12.5 751,-12.5 751,-6.5 757,-.5 763,-.5"/>
<text text-anchor="middle" x="779" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="807,-.5 807,-230.5 "/>
<text text-anchor="middle" x="817.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="828,-.5 828,-230.5 "/>
<text text-anchor="middle" x="900.5" y="-215.3" font-family="Times,serif" font-size="14.00" fill="#000000">acl</text>
<polyline fill="none" stroke="#000000" points="828,-207.5 973,-207.5 "/>
<text text-anchor="middle" x="900.5" y="-192.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent</text>
<polyline fill="none" stroke="#000000" points="828,-184.5 973,-184.5 "/>
<text text-anchor="middle" x="900.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_number</text>
<polyline fill="none" stroke="#000000" points="828,-161.5 973,-161.5 "/>
<text text-anchor="middle" x="900.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">external_url</text>
<polyline fill="none" stroke="#000000" points="828,-138.5 973,-138.5 "/>
<text text-anchor="middle" x="900.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">phs_accession</text>
<polyline fill="none" stroke="#000000" points="828,-115.5 973,-115.5 "/>
<text text-anchor="middle" x="900.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_acronym</text>
<polyline fill="none" stroke="#000000" points="828,-92.5 973,-92.5 "/>
<text text-anchor="middle" x="900.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_description</text>
<polyline fill="none" stroke="#000000" points="828,-69.5 973,-69.5 "/>
<text text-anchor="middle" x="900.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_id</text>
<polyline fill="none" stroke="#000000" points="828,-46.5 973,-46.5 "/>
<text text-anchor="middle" x="900.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_name</text>
<polyline fill="none" stroke="#000000" points="828,-23.5 973,-23.5 "/>
<text text-anchor="middle" x="900.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_short_title</text>
<polyline fill="none" stroke="#000000" points="973,-.5 973,-230.5 "/>
<text text-anchor="middle" x="983.5" y="-111.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- reference_file&#45;&gt;study -->
<g id="edge1" class="edge">
<title>reference_file&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M872.5,-282.1912C872.5,-268.6437 872.5,-254.6506 872.5,-240.7975"/>
<polygon fill="#000000" stroke="#000000" points="876.0001,-240.7434 872.5,-230.7434 869.0001,-240.7435 876.0001,-240.7434"/>
<text text-anchor="middle" x="933" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_reference_file</text>
</g>
<!-- sample -->
<g id="node4" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M864,-541.5C864,-541.5 1213,-541.5 1213,-541.5 1219,-541.5 1225,-547.5 1225,-553.5 1225,-553.5 1225,-897.5 1225,-897.5 1225,-903.5 1219,-909.5 1213,-909.5 1213,-909.5 864,-909.5 864,-909.5 858,-909.5 852,-903.5 852,-897.5 852,-897.5 852,-553.5 852,-553.5 852,-547.5 858,-541.5 864,-541.5"/>
<text text-anchor="middle" x="886" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="920,-541.5 920,-909.5 "/>
<text text-anchor="middle" x="930.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="941,-541.5 941,-909.5 "/>
<text text-anchor="middle" x="1072.5" y="-894.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="941,-886.5 1204,-886.5 "/>
<text text-anchor="middle" x="1072.5" y="-871.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="941,-863.5 1204,-863.5 "/>
<text text-anchor="middle" x="1072.5" y="-848.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification</text>
<polyline fill="none" stroke="#000000" points="941,-840.5 1204,-840.5 "/>
<text text-anchor="middle" x="1072.5" y="-825.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="941,-817.5 1204,-817.5 "/>
<text text-anchor="middle" x="1072.5" y="-802.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="941,-794.5 1204,-794.5 "/>
<text text-anchor="middle" x="1072.5" y="-779.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_verification_status</text>
<polyline fill="none" stroke="#000000" points="941,-771.5 1204,-771.5 "/>
<text text-anchor="middle" x="1072.5" y="-756.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant_age_at_collection</text>
<polyline fill="none" stroke="#000000" points="941,-748.5 1204,-748.5 "/>
<text text-anchor="middle" x="1072.5" y="-733.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_description</text>
<polyline fill="none" stroke="#000000" points="941,-725.5 1204,-725.5 "/>
<text text-anchor="middle" x="1072.5" y="-710.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="941,-702.5 1204,-702.5 "/>
<text text-anchor="middle" x="1072.5" y="-687.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_tumor_status</text>
<polyline fill="none" stroke="#000000" points="941,-679.5 1204,-679.5 "/>
<text text-anchor="middle" x="1072.5" y="-664.3" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="941,-656.5 1204,-656.5 "/>
<text text-anchor="middle" x="1072.5" y="-641.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="941,-633.5 1204,-633.5 "/>
<text text-anchor="middle" x="1072.5" y="-618.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="941,-610.5 1204,-610.5 "/>
<text text-anchor="middle" x="1072.5" y="-595.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="941,-587.5 1204,-587.5 "/>
<text text-anchor="middle" x="1072.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="941,-564.5 1204,-564.5 "/>
<text text-anchor="middle" x="1072.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="1204,-541.5 1204,-909.5 "/>
<text text-anchor="middle" x="1214.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample&#45;&gt;study -->
<g id="edge5" class="edge">
<title>sample&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1065.8427,-541.3871C1070.6276,-459.1892 1065.6885,-362.8524 1032.5,-282 1024.6504,-262.8772 1013.4719,-244.703 1000.624,-227.8711"/>
<polygon fill="#000000" stroke="#000000" points="1003.1324,-225.3997 994.19,-219.7177 997.6372,-229.7361 1003.1324,-225.3997"/>
<text text-anchor="middle" x="1103" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- sample&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>sample&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M851.6823,-576.3317C834.921,-564.0909 818.0357,-552.1523 801.5,-541 764.0224,-515.7238 751.1306,-515.0478 713.5,-490 689.5894,-474.0846 664.3058,-455.4468 642.0566,-438.3794"/>
<polygon fill="#000000" stroke="#000000" points="644.0612,-435.5054 634.0049,-432.1704 639.7865,-441.0487 644.0612,-435.5054"/>
<text text-anchor="middle" x="807" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge3" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M627.0479,-339.8067C659.1359,-310.4831 702.2258,-271.1053 743.3434,-233.5299"/>
<polygon fill="#000000" stroke="#000000" points="745.7047,-236.1134 750.7256,-226.7837 740.9826,-230.946 745.7047,-236.1134"/>
<text text-anchor="middle" x="775" y="-252.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- diagnosis -->
<g id="node6" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M415,-553C415,-553 780,-553 780,-553 786,-553 792,-559 792,-565 792,-565 792,-886 792,-886 792,-892 786,-898 780,-898 780,-898 415,-898 415,-898 409,-898 403,-892 403,-886 403,-886 403,-565 403,-565 403,-559 409,-553 415,-553"/>
<text text-anchor="middle" x="445" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="487,-553 487,-898 "/>
<text text-anchor="middle" x="497.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="508,-553 508,-898 "/>
<text text-anchor="middle" x="639.5" y="-882.8" font-family="Times,serif" font-size="14.00" fill="#000000">age_at_diagnosis</text>
<polyline fill="none" stroke="#000000" points="508,-875 771,-875 "/>
<text text-anchor="middle" x="639.5" y="-859.8" font-family="Times,serif" font-size="14.00" fill="#000000">anatomic_site</text>
<polyline fill="none" stroke="#000000" points="508,-852 771,-852 "/>
<text text-anchor="middle" x="639.5" y="-836.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_basis</text>
<polyline fill="none" stroke="#000000" points="508,-829 771,-829 "/>
<text text-anchor="middle" x="639.5" y="-813.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification</text>
<polyline fill="none" stroke="#000000" points="508,-806 771,-806 "/>
<text text-anchor="middle" x="639.5" y="-790.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_classification_system</text>
<polyline fill="none" stroke="#000000" points="508,-783 771,-783 "/>
<text text-anchor="middle" x="639.5" y="-767.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_comment</text>
<polyline fill="none" stroke="#000000" points="508,-760 771,-760 "/>
<text text-anchor="middle" x="639.5" y="-744.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_id</text>
<polyline fill="none" stroke="#000000" points="508,-737 771,-737 "/>
<text text-anchor="middle" x="639.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_verification_status</text>
<polyline fill="none" stroke="#000000" points="508,-714 771,-714 "/>
<text text-anchor="middle" x="639.5" y="-698.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease_phase</text>
<polyline fill="none" stroke="#000000" points="508,-691 771,-691 "/>
<text text-anchor="middle" x="639.5" y="-675.8" font-family="Times,serif" font-size="14.00" fill="#000000">toronto_childhood_cancer_staging</text>
<polyline fill="none" stroke="#000000" points="508,-668 771,-668 "/>
<text text-anchor="middle" x="639.5" y="-652.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_classification</text>
<polyline fill="none" stroke="#000000" points="508,-645 771,-645 "/>
<text text-anchor="middle" x="639.5" y="-629.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_grade</text>
<polyline fill="none" stroke="#000000" points="508,-622 771,-622 "/>
<text text-anchor="middle" x="639.5" y="-606.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_m</text>
<polyline fill="none" stroke="#000000" points="508,-599 771,-599 "/>
<text text-anchor="middle" x="639.5" y="-583.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_n</text>
<polyline fill="none" stroke="#000000" points="508,-576 771,-576 "/>
<text text-anchor="middle" x="639.5" y="-560.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_stage_clinical_t</text>
<polyline fill="none" stroke="#000000" points="771,-553 771,-898 "/>
<text text-anchor="middle" x="781.5" y="-721.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M586.8154,-552.7662C584.3393,-512.7361 581.8769,-472.9272 579.9792,-442.2477"/>
<polygon fill="#000000" stroke="#000000" points="583.4689,-441.971 579.3581,-432.2062 576.4823,-442.4032 583.4689,-441.971"/>
<text text-anchor="middle" x="629" y="-511.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_diagnosis</text>
</g>
</g>
</svg>
</div>
