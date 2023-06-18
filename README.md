# Design and Develop a PCB Board

### AIM
To design and develop a PCB board for any specific application.

### DESIGN STEPS
1)Design the schematic using Eagle.<br>
2)Create the PCB layout in Eagle, ensuring proper component placement and trace routing.<br>
3)Generate Gerber files in Eagle for manufacturing.<br>
4)Import the Gerber files into CopperCAM and generate GCODE.<br>
5)Set up the PCB prototyping machine and load the PCB blank.<br>
6)Load the GCODE into the machine's control software.<br>
7)Run the machine to mill traces, drill holes, and cut out the PCB.

### G-CODE

### Engraving Layer
```
%
( CopperCAM - 29/07/2019 / ISO-Mill Output )
( C:\CopperCAM2\Fawziya\eng.iso created 17/06/2023 at 10:32 )
( Workpiece dimensions: 60.884 x 73.098 x 1 mm )
G21 G40 G54
G80 G90 G94
( Tool #1 "Basic Engraver" / Diameter 3.17 mm )
T1 M06
M03 S12000
M07
G00 X16.834 Y49.98
G00 Z0
G01 F60 Z-0.2
G01 F600 X16.722 Y50.091
G01 X16.146
G01 X15.738 Y49.684
G01 Y49.526
G01 X12.624
G01 X12.598 Y49.523
G01 X12.574 Y49.516
G01 X12.552 Y49.504
G01 X12.532 Y49.488
G01 X9.547 Y46.502
G01 X9.52 Y46.59
G01 X9.45 Y46.722
G01 X9.355 Y46.838
G01 X9.239 Y46.933
G01 X9.106 Y47.004
G01 X8.963 Y47.047
G01 X8.814 Y47.062
G01 X8.665 Y47.047
G01 X8.521 Y47.004
G01 X8.389 Y46.933
G01 X8.273 Y46.838
G01 X8.178 Y46.722
G01 X8.107 Y46.59
G01 X8.064 Y46.446
G01 X8.049 Y46.297
G01 Y44.875
G01 X8.064 Y44.725
G01 X8.107 Y44.582
G01 X8.178 Y44.45
G01 X8.273 Y44.334
G01 X8.389 Y44.239
G01 X8.521 Y44.168
G01 X8.665 Y44.124
G01 X8.814 Y44.11
G01 X8.963 Y44.124
G01 X9.106 Y44.168
G01 X9.239 Y44.239
G01 X9.355 Y44.334
G01 X9.45 Y44.45
G01 X9.52 Y44.582
G01 X9.564 Y44.725
G01 X9.579 Y44.875
G01 Y46.167
G01 X12.678 Y49.266
G01 X15.738
G01 Y49.108
G01 X16.146 Y48.7
G01 X16.722
G01 X17.13 Y49.108
G01 Y49.684
G01 X17.018 Y49.796
G01 X32.413 Y65.192
G01 X33.604
G01 X33.743 Y65.206
G01 X33.877 Y65.246
G01 X34.001 Y65.312
G01 X34.109 Y65.401
G01 X34.198 Y65.509
G01 X34.264 Y65.633
G01 X34.304 Y65.767
G01 X34.318 Y65.906
G01 X34.304 Y66.045
G01 X34.264 Y66.179
G01 X34.198 Y66.302
G01 X34.109 Y66.411
G01 X34.001 Y66.499
G01 X33.877 Y66.565
G01 X33.743 Y66.606
G01 X33.604 Y66.62
G01 X32.283
G01 X32.144 Y66.606
G01 X32.01 Y66.565
G01 X31.887 Y66.499
G01 X31.779 Y66.411
G01 X31.69 Y66.302
G01 X31.624 Y66.179
G01 X31.583 Y66.045
G01 X31.569 Y65.906
G01 X31.583 Y65.767
G01 X31.624 Y65.633
G01 X31.69 Y65.509
G01 X31.779 Y65.401
G01 X31.887 Y65.312
G01 X32.01 Y65.246
G01 X32.08 Y65.225
G01 X16.834 Y49.98
G00 Z2
G00 X24.75 Y49.526
G00 Z0
G01 F60 Z-0.2
G01 F600 Y49.684
G01 X24.342 Y50.091
G01 X23.766
G01 X23.358 Y49.684
G01 Y49.108
G01 X23.766 Y48.7
G01 X24.342
G01 X24.75 Y49.108
G01 Y49.266
G01 X27.15
G01 Y48.735
G01 X27.164 Y48.596
G01 X27.204 Y48.462
G01 X27.27 Y48.339
G01 X27.359 Y48.231
G01 X27.467 Y48.142
G01 X27.591 Y48.076
G01 X27.725 Y48.035
G01 X27.864 Y48.021
G01 X28.003 Y48.035
G01 X28.137 Y48.076
G01 X28.26 Y48.142
G01 X28.369 Y48.231
G01 X28.457 Y48.339
G01 X28.523 Y48.462
G01 X28.564 Y48.596
G01 X28.578 Y48.735
G01 Y50.056
G01 X28.564 Y50.195
G01 X28.523 Y50.329
G01 X28.457 Y50.453
G01 X28.369 Y50.561
G01 X28.26 Y50.65
G01 X28.137 Y50.716
G01 X28.003 Y50.756
G01 X27.864 Y50.77
G01 X27.725 Y50.756
G01 X27.591 Y50.716
G01 X27.467 Y50.65
G01 X27.359 Y50.561
G01 X27.27 Y50.453
G01 X27.204 Y50.329
G01 X27.164 Y50.195
G01 X27.15 Y50.056
G01 Y49.526
G01 X24.75
G00 Z2
G00 X27.734 Y56.442
G00 Z0
G01 F60 Z-0.2
G01 F600 X27.576
G01 X27.168 Y56.034
G01 Y55.458
G01 X27.576 Y55.05
G01 X28.152
G01 X28.264 Y55.162
G01 X30.274 Y53.152
G01 Y50.757
G01 X30.265 Y50.756
G01 X30.131 Y50.716
G01 X30.007 Y50.65
G01 X29.899 Y50.561
G01 X29.81 Y50.453
G01 X29.744 Y50.329
G01 X29.704 Y50.195
G01 X29.69 Y50.056
G01 Y48.735
G01 X29.704 Y48.596
G01 X29.744 Y48.462
G01 X29.81 Y48.339
G01 X29.899 Y48.231
G01 X30.007 Y48.142
G01 X30.131 Y48.076
G01 X30.265 Y48.035
G01 X30.404 Y48.021
G01 X30.543 Y48.035
G01 X30.677 Y48.076
G01 X30.8 Y48.142
G01 X30.909 Y48.231
G01 X30.997 Y48.339
G01 X31.063 Y48.462
G01 X31.104 Y48.596
G01 X31.118 Y48.735
G01 Y50.056
G01 X31.104 Y50.195
G01 X31.063 Y50.329
G01 X30.997 Y50.453
G01 X30.909 Y50.561
G01 X30.8 Y50.65
G01 X30.677 Y50.716
G01 X30.543 Y50.756
G01 X30.534 Y50.757
G01 Y53.206
G01 X30.531 Y53.231
G01 X30.524 Y53.255
G01 X30.512 Y53.278
G01 X30.496 Y53.298
G01 X28.448 Y55.346
G01 X28.56 Y55.458
G01 Y56.034
G01 X28.152 Y56.442
G01 X27.994
G01 Y58.232
G01 X32.413 Y62.652
G01 X33.604
G01 X33.743 Y62.666
G01 X33.877 Y62.706
G01 X34.001 Y62.772
G01 X34.109 Y62.861
G01 X34.198 Y62.969
G01 X34.264 Y63.093
G01 X34.304 Y63.226
G01 X34.318 Y63.366
G01 X34.304 Y63.505
G01 X34.264 Y63.639
G01 X34.198 Y63.762
G01 X34.109 Y63.871
G01 X34.001 Y63.959
G01 X33.877 Y64.025
G01 X33.743 Y64.066
G01 X33.604 Y64.08
G01 X32.283
G01 X32.144 Y64.066
G01 X32.01 Y64.025
G01 X31.887 Y63.959
G01 X31.779 Y63.871
G01 X31.69 Y63.762
G01 X31.624 Y63.639
G01 X31.583 Y63.505
G01 X31.569 Y63.366
G01 X31.583 Y63.226
G01 X31.624 Y63.093
G01 X31.69 Y62.969
G01 X31.779 Y62.861
G01 X31.887 Y62.772
G01 X32.01 Y62.706
G01 X32.08 Y62.685
G01 X27.772 Y58.378
G01 X27.756 Y58.358
G01 X27.744 Y58.335
G01 X27.737 Y58.311
G01 X27.734 Y58.286
G01 Y56.442
G00 Z2
G00 X33.604 Y60.112
G00 Z0
G01 F60 Z-0.2
G01 F600 X33.743 Y60.126
G01 X33.877 Y60.166
G01 X34.001 Y60.232
G01 X34.109 Y60.321
G01 X34.198 Y60.429
G01 X34.264 Y60.553
G01 X34.304 Y60.687
G01 X34.318 Y60.826
G01 X34.304 Y60.965
G01 X34.264 Y61.099
G01 X34.198 Y61.222
G01 X34.109 Y61.331
G01 X34.001 Y61.419
G01 X33.877 Y61.485
G01 X33.743 Y61.526
G01 X33.604 Y61.54
G01 X32.283
G01 X32.144 Y61.526
G01 X32.01 Y61.485
G01 X31.887 Y61.419
G01 X31.779 Y61.331
G01 X31.69 Y61.222
G01 X31.624 Y61.099
G01 X31.583 Y60.965
G01 X31.569 Y60.826
G01 X31.583 Y60.687
G01 X31.624 Y60.553
G01 X31.69 Y60.429
G01 X31.779 Y60.321
G01 X31.887 Y60.232
G01 X32.01 Y60.166
G01 X32.144 Y60.126
G01 X32.283 Y60.112
G01 X33.604
G00 Z2
G00 X27.29 Y67.306
G00 Z0
G01 F60 Z-0.2
G01 F600 Y67.464
G01 X26.882 Y67.871
G01 X26.306
G01 X25.898 Y67.464
G01 Y66.888
G01 X26.306 Y66.48
G01 X26.882
G01 X27.29 Y66.888
G01 Y67.046
G01 X31.674
G01 X31.699 Y67.048
G01 X31.723 Y67.056
G01 X31.746 Y67.068
G01 X31.766 Y67.084
G01 X32.413 Y67.732
G01 X33.604
G01 X33.743 Y67.746
G01 X33.877 Y67.786
G01 X34.001 Y67.852
G01 X34.109 Y67.941
G01 X34.198 Y68.049
G01 X34.264 Y68.173
G01 X34.304 Y68.306
G01 X34.318 Y68.446
G01 X34.304 Y68.585
G01 X34.264 Y68.719
G01 X34.198 Y68.842
G01 X34.109 Y68.951
G01 X34.001 Y69.039
G01 X33.877 Y69.105
G01 X33.743 Y69.146
G01 X33.604 Y69.16
G01 X32.283
G01 X32.144 Y69.146
G01 X32.01 Y69.105
G01 X31.887 Y69.039
G01 X31.779 Y68.951
G01 X31.69 Y68.842
G01 X31.624 Y68.719
G01 X31.583 Y68.585
G01 X31.569 Y68.446
G01 X31.583 Y68.306
G01 X31.624 Y68.173
G01 X31.69 Y68.049
G01 X31.779 Y67.941
G01 X31.887 Y67.852
G01 X32.01 Y67.786
G01 X32.08 Y67.765
G01 X31.62 Y67.306
G01 X27.29
G00 Z2
G00 Y69.846
G00 Z0
G01 F60 Z-0.2
G01 F600 Y70.004
G01 X26.882 Y70.411
G01 X26.306
G01 X25.898 Y70.004
G01 Y69.428
G01 X26.306 Y69.02
G01 X26.882
G01 X27.29 Y69.428
G01 Y69.586
G01 X39.24
G01 X39.7 Y69.126
G01 X39.63 Y69.105
G01 X39.507 Y69.039
G01 X39.399 Y68.951
G01 X39.31 Y68.842
G01 X39.244 Y68.719
G01 X39.203 Y68.585
G01 X39.189 Y68.446
G01 X39.203 Y68.306
G01 X39.244 Y68.173
G01 X39.31 Y68.049
G01 X39.399 Y67.941
G01 X39.507 Y67.852
G01 X39.63 Y67.786
G01 X39.764 Y67.746
G01 X39.903 Y67.732
G01 X41.224
G01 X41.363 Y67.746
G01 X41.497 Y67.786
G01 X41.621 Y67.852
G01 X41.729 Y67.941
G01 X41.818 Y68.049
G01 X41.884 Y68.173
G01 X41.924 Y68.306
G01 X41.938 Y68.446
G01 X41.924 Y68.585
G01 X41.884 Y68.719
G01 X41.818 Y68.842
G01 X41.729 Y68.951
G01 X41.621 Y69.039
G01 X41.497 Y69.105
G01 X41.363 Y69.146
G01 X41.224 Y69.16
G01 X40.033
G01 X39.386 Y69.808
G01 X39.366 Y69.824
G01 X39.343 Y69.836
G01 X39.319 Y69.843
G01 X39.294 Y69.846
G01 X27.29
G00 Z2
G00 X37.328 Y49.266
G00 Z0
G01 F60 Z-0.2
G01 F600 Y49.108
G01 X37.736 Y48.7
G01 X38.312
G01 X38.72 Y49.108
G01 Y49.684
G01 X38.312 Y50.091
G01 X37.736
G01 X37.328 Y49.684
G01 Y49.526
G01 X33.658
G01 Y50.056
G01 X33.644 Y50.195
G01 X33.603 Y50.329
G01 X33.537 Y50.453
G01 X33.449 Y50.561
G01 X33.34 Y50.65
G01 X33.217 Y50.716
G01 X33.083 Y50.756
G01 X32.944 Y50.77
G01 X32.805 Y50.756
G01 X32.671 Y50.716
G01 X32.547 Y50.65
G01 X32.439 Y50.561
G01 X32.35 Y50.453
G01 X32.284 Y50.329
G01 X32.244 Y50.195
G01 X32.23 Y50.056
G01 Y48.735
G01 X32.244 Y48.596
G01 X32.284 Y48.462
G01 X32.35 Y48.339
G01 X32.439 Y48.231
G01 X32.547 Y48.142
G01 X32.671 Y48.076
G01 X32.805 Y48.035
G01 X32.944 Y48.021
G01 X33.083 Y48.035
G01 X33.217 Y48.076
G01 X33.34 Y48.142
G01 X33.449 Y48.231
G01 X33.537 Y48.339
G01 X33.603 Y48.462
G01 X33.644 Y48.596
G01 X33.658 Y48.735
G01 Y49.266
G01 X37.328
G00 Z2
G00 X47.364
G00 Z0
G01 F60 Z-0.2
G01 F600 Y49.056
G01 X47.844 Y48.576
G01 X48.524
G01 X49.004 Y49.056
G01 Y49.736
G01 X48.524 Y50.216
G01 X47.844
G01 X47.364 Y49.736
G01 Y49.526
G01 X41.26
G01 Y49.684
G01 X41.148 Y49.796
G01 X41.926 Y50.574
G01 X41.942 Y50.594
G01 X41.954 Y50.616
G01 X41.961 Y50.64
G01 X41.964 Y50.666
G01 Y53.78
G01 X42.122
G01 X42.53 Y54.188
G01 Y54.764
G01 X42.122 Y55.172
G01 X41.964
G01 Y59.556
G01 X41.961 Y59.581
G01 X41.954 Y59.605
G01 X41.942 Y59.628
G01 X41.926 Y59.648
G01 X41.428 Y60.145
G01 X41.497 Y60.166
G01 X41.621 Y60.232
G01 X41.729 Y60.321
G01 X41.818 Y60.429
G01 X41.884 Y60.553
G01 X41.924 Y60.687
G01 X41.938 Y60.826
G01 X41.924 Y60.965
G01 X41.884 Y61.099
G01 X41.818 Y61.222
G01 X41.729 Y61.331
G01 X41.621 Y61.419
G01 X41.497 Y61.485
G01 X41.363 Y61.526
G01 X41.224 Y61.54
G01 X39.903
G01 X39.764 Y61.526
G01 X39.63 Y61.485
G01 X39.507 Y61.419
G01 X39.399 Y61.331
G01 X39.31 Y61.222
G01 X39.244 Y61.099
G01 X39.203 Y60.965
G01 X39.189 Y60.826
G01 X39.203 Y60.687
G01 X39.244 Y60.553
G01 X39.31 Y60.429
G01 X39.399 Y60.321
G01 X39.507 Y60.232
G01 X39.63 Y60.166
G01 X39.764 Y60.126
G01 X39.903 Y60.112
G01 X41.094
G01 X41.704 Y59.502
G01 Y55.172
G01 X41.546
G01 X41.138 Y54.764
G01 Y54.188
G01 X41.546 Y53.78
G01 X41.704
G01 Y50.72
G01 X40.964 Y49.98
G01 X40.852 Y50.091
G01 X40.276
G01 X39.868 Y49.684
G01 Y49.108
G01 X40.276 Y48.7
G01 X40.852
G01 X41.26 Y49.108
G01 Y49.266
G01 X47.364
G00 Z2
G00 X51.552 Y49.526
G00 Z0
G01 F60 Z-0.2
G01 F600 X51.549 Y49.56
G01 X51.501 Y49.718
G01 X51.423 Y49.863
G01 X51.318 Y49.99
G01 X51.191 Y50.095
G01 X51.046 Y50.173
G01 X50.888 Y50.221
G01 X50.854 Y50.224
G01 Y53.206
G01 X50.851 Y53.231
G01 X50.844 Y53.255
G01 X50.832 Y53.278
G01 X50.816 Y53.298
G01 X50.038 Y54.076
G01 X50.15 Y54.188
G01 Y54.764
G01 X49.742 Y55.172
G01 X49.166
G01 X49.054 Y55.06
G01 X41.428 Y62.685
G01 X41.497 Y62.706
G01 X41.621 Y62.772
G01 X41.729 Y62.861
G01 X41.818 Y62.969
G01 X41.884 Y63.093
G01 X41.924 Y63.226
G01 X41.938 Y63.366
G01 X41.924 Y63.505
G01 X41.884 Y63.639
G01 X41.818 Y63.762
G01 X41.729 Y63.871
G01 X41.621 Y63.959
G01 X41.497 Y64.025
G01 X41.363 Y64.066
G01 X41.224 Y64.08
G01 X39.903
G01 X39.764 Y64.066
G01 X39.63 Y64.025
G01 X39.507 Y63.959
G01 X39.399 Y63.871
G01 X39.31 Y63.762
G01 X39.244 Y63.639
G01 X39.203 Y63.505
G01 X39.189 Y63.366
G01 X39.203 Y63.226
G01 X39.244 Y63.093
G01 X39.31 Y62.969
G01 X39.399 Y62.861
G01 X39.507 Y62.772
G01 X39.63 Y62.706
G01 X39.764 Y62.666
G01 X39.903 Y62.652
G01 X41.094
G01 X48.87 Y54.876
G01 X48.758 Y54.764
G01 Y54.188
G01 X49.166 Y53.78
G01 X49.742
G01 X49.854 Y53.892
G01 X50.594 Y53.152
G01 Y50.224
G01 X50.56 Y50.221
G01 X50.402 Y50.173
G01 X50.257 Y50.095
G01 X50.129 Y49.99
G01 X50.025 Y49.863
G01 X49.947 Y49.718
G01 X49.899 Y49.56
G01 X49.883 Y49.396
G01 X49.899 Y49.232
G01 X49.947 Y49.074
G01 X50.025 Y48.929
G01 X50.129 Y48.801
G01 X50.257 Y48.697
G01 X50.402 Y48.619
G01 X50.56 Y48.571
G01 X50.724 Y48.555
G01 X50.888 Y48.571
G01 X51.046 Y48.619
G01 X51.191 Y48.697
G01 X51.318 Y48.801
G01 X51.423 Y48.929
G01 X51.501 Y49.074
G01 X51.549 Y49.232
G01 X51.552 Y49.266
G01 X56.378
G01 Y49.108
G01 X56.786 Y48.7
G01 X57.362
G01 X57.77 Y49.108
G01 Y49.684
G01 X57.362 Y50.091
G01 X57.204
G01 Y52.51
G01 X57.362
G01 X57.77 Y52.918
G01 Y53.494
G01 X57.362 Y53.901
G01 X56.786
G01 X56.378 Y53.494
G01 Y52.918
G01 X56.786 Y52.51
G01 X56.944
G01 Y50.091
G01 X56.786
G01 X56.378 Y49.684
G01 Y49.526
G01 X51.552
G00 Z2
G00 X56.49 Y56.146
G00 Z0
G01 F60 Z-0.2
G01 F600 X56.378 Y56.034
G01 Y55.458
G01 X56.786 Y55.05
G01 X57.362
G01 X57.77 Y55.458
G01 Y56.034
G01 X57.362 Y56.442
G01 X56.786
G01 X56.674 Y56.33
G01 X47.006 Y65.998
G01 X46.986 Y66.014
G01 X46.963 Y66.026
G01 X46.939 Y66.033
G01 X46.914 Y66.036
G01 X41.925
G01 X41.924 Y66.045
G01 X41.884 Y66.179
G01 X41.818 Y66.302
G01 X41.729 Y66.411
G01 X41.621 Y66.499
G01 X41.497 Y66.565
G01 X41.363 Y66.606
G01 X41.224 Y66.62
G01 X39.903
G01 X39.764 Y66.606
G01 X39.63 Y66.565
G01 X39.507 Y66.499
G01 X39.399 Y66.411
G01 X39.31 Y66.302
G01 X39.244 Y66.179
G01 X39.203 Y66.045
G01 X39.189 Y65.906
G01 X39.203 Y65.767
G01 X39.244 Y65.633
G01 X39.31 Y65.509
G01 X39.399 Y65.401
G01 X39.507 Y65.312
G01 X39.63 Y65.246
G01 X39.7 Y65.225
G01 X35.392 Y60.918
G01 X35.376 Y60.898
G01 X35.364 Y60.875
G01 X35.357 Y60.851
G01 X35.354 Y60.826
G01 Y56.442
G01 X35.196
G01 X34.788 Y56.034
G01 Y55.458
G01 X35.196 Y55.05
G01 X35.772
G01 X36.18 Y55.458
G01 Y56.034
G01 X35.772 Y56.442
G01 X35.614
G01 Y60.772
G01 X40.033 Y65.192
G01 X41.224
G01 X41.363 Y65.206
G01 X41.497 Y65.246
G01 X41.621 Y65.312
G01 X41.729 Y65.401
G01 X41.818 Y65.509
G01 X41.884 Y65.633
G01 X41.924 Y65.767
G01 X41.925 Y65.776
G01 X46.86
G01 X56.49 Y56.146
G00 Z2
G00 X56.378 Y41.646
G00 Z0
G01 F60 Z-0.2
G01 F600 Y41.488
G01 X56.786 Y41.08
G01 X57.362
G01 X57.77 Y41.488
G01 Y42.064
G01 X57.362 Y42.472
G01 X56.786
G01 X56.378 Y42.064
G01 Y41.906
G01 X15.218
G01 X12.119 Y45.005
G01 Y46.297
G01 X12.104 Y46.446
G01 X12.06 Y46.59
G01 X11.99 Y46.722
G01 X11.895 Y46.838
G01 X11.779 Y46.933
G01 X11.646 Y47.004
G01 X11.503 Y47.047
G01 X11.354 Y47.062
G01 X11.205 Y47.047
G01 X11.061 Y47.004
G01 X10.929 Y46.933
G01 X10.813 Y46.838
G01 X10.718 Y46.722
G01 X10.647 Y46.59
G01 X10.604 Y46.446
G01 X10.589 Y46.297
G01 Y44.875
G01 X10.604 Y44.725
G01 X10.647 Y44.582
G01 X10.718 Y44.45
G01 X10.813 Y44.334
G01 X10.929 Y44.239
G01 X11.061 Y44.168
G01 X11.205 Y44.124
G01 X11.354 Y44.11
G01 X11.503 Y44.124
G01 X11.646 Y44.168
G01 X11.779 Y44.239
G01 X11.895 Y44.334
G01 X11.99 Y44.45
G01 X12.06 Y44.582
G01 X12.087 Y44.669
G01 X15.072 Y41.684
G01 X15.092 Y41.668
G01 X15.114 Y41.656
G01 X15.138 Y41.648
G01 X15.164 Y41.646
G01 X56.378
G00 Z2
G00 X00 Y00
M09
M05
M02
%
```
### Drill 0.8
```
%
( CopperCAM - 29/07/2019 / ISO-Mill Output )
( C:\CopperCAM2\Fawziya\drill.iso created 17/06/2023 at 10:32 )
( Workpiece dimensions: 60.884 x 73.098 x 1 mm )
G21 G40 G54
G80 G90 G94
( Tool #3 "Basic Drill" / Diameter 0.8 mm )
T3 M06
M03 S12000
M07
G00 X48.184 Y49.396
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X50.724
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X49.454 Y54.476
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X41.834
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X40.564 Y49.396
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X38.024
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X32.944
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X30.404
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X27.864
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X24.054
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X27.864 Y55.746
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X32.944 Y60.826
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y63.366
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y65.906
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y68.446
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X26.594 Y67.176
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y69.716
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X40.564 Y68.446
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y65.906
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y63.366
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y60.826
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X35.484 Y55.746
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X16.434 Y49.396
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X11.354 Y45.586
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X8.814
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X00 Y00
M09
M05
M02
%
```
### Cutting Layer
```
%
( CopperCAM - 29/07/2019 / ISO-Mill Output )
( C:\CopperCAM2\Fawziya\cut.iso created 17/06/2023 at 10:32 )
( Workpiece dimensions: 60.884 x 73.098 x 1 mm )
G21 G40 G54
G80 G90 G94
( Tool #3 "Basic Drill" / Diameter 0.8 mm )
T3 M06
M03 S12000
M07
G00 X59.877 Y37.792
G00 Z0
G01 F60 Z-2
G01 F300 X3.527
G01 Y74.142
G01 X59.877
G01 Y37.792
G00 Z2
M09
M05
M02
%
```

### SCHEMATIC LAYOUT
![IMG-20230618-WA0005](https://github.com/Fawziya20/PCB-MiniProject/assets/75235022/d8ac18c7-8ac9-4985-aa2f-052e0a41d9a1)

### PCB LAYOUT
![IMG-20230618-WA0010](https://github.com/Fawziya20/PCB-MiniProject/assets/75235022/1f12f9f4-aa7a-404d-b4f8-207e98370e25)

### COPPERCAM OUTPUT
![IMG-20230618-WA0009](https://github.com/Fawziya20/PCB-MiniProject/assets/75235022/17f5ebd4-ea78-4569-82ac-8c568a32c512)

### MANUFACTURED PCB
![WhatsApp Image 2023-06-18 at 21 39 21](https://github.com/Fawziya20/PCB-MiniProject/assets/75235022/d03f28d2-caa3-452e-bdb4-01d2a22770aa)

### RESULT:
Thus, a PCB board is designed and developed for a specific application.



