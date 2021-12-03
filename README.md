# HUST-PhD-Thesis-Latex


HUSTThesis.cls 2021/12/3 version V4.0

This is the unofficial LaTeX class for Master Thesis Template of Huazhong University of Science and Technology


Contributors: Dake Li (2021 V4.0),Xinze Zhang (2020 V3.0), Huikan Liu (2006 V2.0), and Feng Jiang (2005 V1.0). 

Copyright (C) 2021-2022 by Dake Li <ldk689@vip.qq.com>

Copyright (C) 2020-2021 by Xinze Zhang <xinze@hust.edu.cn>

Copyright (C) 2006-2007 by Huikan Liu <hkliu@mail.edu.cn>

This code is distributed under the Perl Artistic License
( http://language.perl.com/misc/Artistic.html )
and may be freely used, distributed and modified.
Retain the contribution notices and credits.

Current maintainer: 
xinze@hust.edu.cn


**********************************************************************

Available class options
(e.g., \documentclass[draftformat,dvips]{HUSTThesis}

            *** choose only one from each category ***

draftformat, finalformat

    提交草稿打开 draftformat 选项，提交最终版打开 finalformat 选项。
    草稿正文页包括页眉（“华中科技大学博士学位论文”），页眉修饰线（双线）。
    页脚（页码），页脚修饰线（单线）。
    最终版正文页不包括页眉、页眉修饰线和页脚修饰线，仅包含页脚。


dvips, dvipdfm

    打开 dvips 支持，否则编译方式为 dvipdfm(x)，如果运行 pdflatex，
    则需要把这两个选项同时关闭。

arial
    打开选项启用 arial 字体，若无字体宏包，则默认采用 helvet 字体。


*******
12/2021 V4.0 changes:
1. recoding the setting of page header and page footer:

    1.1 according to the Word template of PhD thesis in CEEE(电气与电子工程学院)

    1.2 The first page of each chapter does not display a header

    1.3 The header of the odd-numbered pages shows the name of each chapter (need to enter manually by yourself)

    1.4 The header of the even-numbered pages shows "华中科技大学博士学位论文"

2. change the draftformat of documentclass in main.tex to finalformat will red mark the header and footer

 by Dake Li (ldk689@vip.qq.com)

*******
11/2020 V3.0 changes:
1. modify class file (HUSTthesis.cls):

    1.1 update the location of 学号(xuehao) of covering page

    1.2 update the table length of the emajor

    1.3 update the font specification with using the font locally, enabling this project be compiled on overleaf

    1.4 remove the font command of lishu and youyuan

2. change the folder name of ./data/* to ./body/* and update the information of xinze zhang

 by Zhang Xinze (xinze@hust.edu.cn)
 
 *******

 06/2006 V2.0 changes:

 1. wrote class file (HUSTthesis.cls) based on ThuThesis.cls written by
    Xue Ruini, the class file is designed for Doctoral Thesis of HUST.

 2. define new Itemize, Enumerate and Description environments with compact spacing

 by Liu Huikan (hkliu@mail.edu.cn)

*******

 04/2004 V1.0 released (Feng Jiang)


 by Feng Jiang (fjiang@people.com.cn)
