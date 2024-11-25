# PolGroGen: POLymer-GROmacs-input-file-GENerator
Use monomer structure to generate polymer chains of desired length while conserving atom indexing order. 
Make sure atom indexing start and end with terminal H of the repeating unit. Simply input the X, Y, Z spacing to create the polymer.
General chain architecture will be as follows

monomer -----> H-termer-n(nonmer)-initmer-H
(H-Z-{(repeating)*n}-A-H
termer = terminating fragment (H-Z)
nonmer = repeating fragment 
initmer = initializing fragment (A-H)
