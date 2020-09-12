# ECS-Z370H4-EM-OpenCore
Files to install MacOS Catalina on ECS Z370H4-EM with OpenCore Bootloader
Introduction
As per Medion AG, these following Machines shipped with this Motherboard:
10022077 MEDION AKOYA P67001 (MD 34049) / C605
10022092 MEDION AKOYA P67002 (MD 34051) / C606
10022093 MEDION AKOYA P67003 (MD 34052) / C607
10022132 MEDION AKOYA P56002 (MD 34040) / 2520
10022163 MEDION AKOYA P40000 (MD 34045) / 2521
10022173 MEDION AKOYA P42000 (MD 34060) / 2523
10022194 MEDION AKOYA P42000 (MD 34060) / 2525
10022195 MEDION AKOYA P42000 (MD 34060) / 2526
10022247 MEDION AKOYA P42000 (MD 34060) / 2528 SOUTH
10022259 MEDION AKOYA P66013 (MD 34149) / C695
10022273 MEDION AKOYA P42000 (MD 34060) / 2529
10022280 MEDION AKOYA P42000 (MD 34060) / 2530
10022281 MEDION AKOYA P42000 (MD 34060) / 2531
10022282 MEDION AKOYA P42000 (MD 34060) / 2532
10022285 MEDION AKOYA P62000 (MD 34065) / 2533
10022286 MEDION AKOYA P62010 (MD 34070) / 2534
10022317 MEDION AKOYA P40002 (MD 34147) / C693
10022318 MEDION AKOYA P62001 (MD 34148) / C694
10022385 MEDION AKOYA P65001 (MD 34166) / C712
10022391 MEDION AKOYA P6600 DR / F653 ML
10022415 MEDION AKOYA P62003 (MD 34178) / C723
10022419 MEDION AKOYA P40006 (MD 34183) / C726
10022422 MEDION AKOYA P62002 (MD 34174) / C720
10022424 MEDION AKOYA P40004 (MD 34177) / C722
10022430 MEDION AKOYA P42008 (MD 34184) / C727
10022431 MEDION AKOYA P60001 (MD 34186) / C728
10022433 MEDION AKOYA P66023 (MD 34188) / C730
10022434 MEDION AKOYA P60002 (MD 34189) / C731
10022435 MEDION AKOYA P62006 (MD 34191) / C732
10022436 MEDION AKOYA P66024 (MD 34192) / C733
10022450 MEDION AKOYA P4240 DR / F683 ML
10022451 MEDION AKOYA P6200 DR / F684 ML
10022462 MEDION AKOYA P5601 DR / F695 ML
10022470 MEDION AKOYA P62001 (MD 34148) / C694.03
10022490 MEDION AKOYA P6700 DR / F703 ML
10022492 MEDION AKOYA P4019 DR / F705 ML
10022515 MEDION AKOYA P6604 DR / F717 ML
10022539 MEDION AKOYA P6201 DR / F729 ML
10022540 MEDION AKOYA P62001 (MD 34148) / C694.04
10022570 MEDION AKOYA P6202 DR / F730 ML
10022598 MEDION AKOYA P6701 DR / F743 ML
10022657 MEDION AKOYA P4020 DR / F750 ML
10022780 MEDION AKOYA P6607 DR / F775 ML
10022991 MEDION AKOYA P6702 DR / F803 ML
10022094 MEDION ERAZER X67001 (MD 34053) / C608
10022095 MEDION ERAZER X67002 (MD 34054) / C609
10022096 MEDION ERAZER X67003 (MD 34056) / C610
10022098 MEDION ERAZER P66001 (MD 34058) / C612
10022099 MEDION ERAZER X66001 (MD 34059) / C613
10022102 MEDION ERAZER P66005 (MD 34068) / C620
10022103 MEDION ERAZER P66006 (MD 34069) / C621
10022104 MEDION ERAZER P66007 (MD 34071) / C622
10022105 MEDION ERAZER P66008 (MD 34072) / C623
10022106 MEDION ERAZER X67006 (MD 34073) / C624
10022107 MEDION ERAZER X67007 (MD 34074) / C625
10022110 MEDION ERAZER X67004 (MD 34061) / C614
10022111 MEDION ERAZER X67005 (MD 34062) / C615
10022112 MEDION ERAZER P66002 (MD 34063) / C616
10022113 MEDION ERAZER P66003 (MD 34064) / C617
10022114 MEDION ERAZER P67004 (MD 34066) / C618
10022115 MEDION ERAZER P66004 (MD 34067) / C619
10022121 MEDION ERAZER P67007 (MD 34082) / C633
10022127 MEDION ERAZER X67012 (MD 34091) / C642
10022129 MEDION ERAZER X67013 (MD 34093) / C644
10022131 MEDION ERAZER X67009 (MD 34081) / C632
10022135 MEDION ERAZER X67011 (MD 34084) / C637
10022140 MEDION ERAZER X67008 (MD 34075) / C630
10022141 MEDION ERAZER P67006 (MD 34035) / C631
10022170 MEDION ERAZER X67014 (MD 34094) / C645
10022171 MEDION ERAZER X67015 (MD 34050) / 2522 SOUTH
10022193 MEDION ERAZER X67015 (MD 34050) / 2524
10022196 MEDION ERAZER P66009 (MD 34106) / C657
10022197 MEDION ERAZER X67016 (MD 34107) / C658
10022198 MEDION ERAZER X67017 (MD 34108) / C659
10022199 MEDION ERAZER X67018 (MD 34109) / C660
10022208 MEDION ERAZER X67015 (MD 34050) / 2527
10022212 MEDION ERAZER X67019 (MD 34115) / C667
10022213 MEDION ERAZER X67021 (MD 34116) / C668
10022214 MEDION ERAZER X67022 (MD 34117) / C669
10022243 MEDION ERAZER X67023 (MD 34118) / C670
10022244 MEDION ERAZER X67024 (MD 34119) / C671
10022249 MEDION ERAZER X67026 (MD 34123) / C674
10022289 MEDION ERAZER X67032 (MD 34134) C682
10022320 MEDION ERAZER X67033 (MD 34136) C683
10022328 MEDION ERAZER X67034 (MD 34145) / C691
10022348 MEDION ERAZER X6700 DR / F633
10022363 MEDION ERAZER X67020 (MD 34080) / 2537 SOUTH
10022364 MEDION ERAZER P66014 (MD 34151) / C697
10022366 MEDION ERAZER X67009 (MD 34081) / C699
10022367 MEDION ERAZER X67033 (MD 34136) / C700
10022371 MEDION ERAZER X67015 (MD 34050) / 2538
10022372 MEDION ERAZER X67015 (MD 34050) / 2539
10022374 MEDION ERAZER X67038 (MD 34161) / C708
10022375 MEDION ERAZER X67039 (MD 34162) / C709
10022376 MEDION ERAZER X67041 (MD 34163) / C710
10022377 MEDION ERAZER X67042 (MD 34164) / C711
10022379 MEDION ERAZER X67043 (MD 34171) / C717
10022382 MEDION ERAZER P66017 (MD 34156) / C704
10022383 MEDION ERAZER P67009 (MD 34157) / C705
10022384 MEDION ERAZER X67037 (MD 34158) / C706
10022389 MEDION ERAZER X6700 DR / F651 ML
10022397 MEDION ERAZER X6701 DR / F659 ML
10022402 MEDION ERAZER P66018 (MD 34168) / C715
10022409 MEDION ERAZER P66019 (MD 34169) / C716
10022413 MEDION ERAZER P6601 DR / F669 ML
10022414 MEDION ERAZER P6602 DR / F670 ML
10022416 MEDION ERAZER X67044 (MD 34179) / C724
10022420 MEDION ERAZER P66021 (MD 34172) / C718
10022421 MEDION ERAZER P66022 (MD 34173) / C719
10022483 MEDION ERAZER P66026 (MD 34193) / C734
10022484 MEDION ERAZER X67015 (MD 34050) / 2538.02
10022487 MEDION ERAZER X67048 (MD 34197) / C737
10022512 MEDION ERAZER X6600 DR / F714 ML
10022513 MEDION ERAZER P6603 DR / F715 ML
10022514 MEDION ERAZER X6702 DR / F716 ML
10022524 MEDION ERAZER P6605 DR / F722 ML
10022525 MEDION ERAZER X6703 DR / F723 ML
10022527 MEDION ERAZER X6704 DR / F725 ML
10022528 MEDION ERAZER X6705 DR / F726 ML
10022599 MEDION ERAZER X6706 DR / F744 ML
10022630 MEDION ERAZER X6707 DR / F745 ML
10022631 MEDION ERAZER X6708 DR / F746 ML
10022632 MEDION ERAZER X6709 DR / F747 ML
10022633 MEDION ERAZER X6710 DR / F748 ML
10022634 MEDION ERAZER X6711 DR / F749 ML
10022642 MEDION ERAZER P67044 (MD 34262) / C798
10022676 MEDION ERAZER P6606 DR / F759 ML
10022769 MEDION ERAZER X6713 DR / F774 ML
10022781 MEDION ERAZER X6714 DR / F776 ML
10022782 MEDION ERAZER X6715 DR / F777 ML
10022866 MEDION ERAZER X6718 DR / F786 ML
10023044 MEDION ERAZER X6725 DR / F815 ML
10023069 MEDION ERAZER X6727 DR / F828 ML
10022133 MICROSTAR PROFESSIONAL P67008 / C636
10022220 MICROSTAR PROFESSIONAL P66011 (MD 34122) / C663
10022248 MICROSTAR PROFESSIONAL P66012 (MD 34121) / C672
10022287 MICROSTAR PROFESSIONAL P66011 (MD 34122) / C663.03
10022368 MICROSTAR PROFESSIONAL P66016 (MD 34153) / C701
10022516 MICROSTAR PROFESSIONAL P66016 (MD 34153) / C701.03

This efi config was done on my 
ALDI PC February 2018 MEDION® AKOYA® P40000 MD 34045
with
Intel® Core™ i3-8100 processor
