# ssGSEA
The code for computing the single sample gene set enrichment analysis from the bulk transcriptomic dataset
Last login: Sat Feb 15 12:58:42 on ttys000
--------------------------------------------------------------------------------
                                  ***WARNING***
--------------------------------------------------------------------------------
- This warning banner provides privacy and security notices consistent
  with applicable federal laws, directives, and other federal guidance for
  accessing this Government system, which includes (1) this computer
  network, (2) all computers connected to this network, and (3) all devices
  and storage media attached to this network or to a computer on this
  network.
  
- This system is provided for Government-authorized use only.
 
- Unauthorized or improper use of this system is prohibited and may result
  in disciplinary action and/or civil and criminal penalties.
  
- Personal use of social media and networking sites on this system is
  limited as to not interfere with official work duties and is subject to
  monitoring.
  
- By using this system, you understand and consent to the following:
    
    - The Government may monitor, record, and audit your system usage,
      including usage of personal devices and email systems for official
      duties or to conduct HHS business. Therefore, you have no reasonable
      expectation of privacy regarding any communication or data transiting
      or stored on this system. At any time, and for any lawful Government
      purpose, the government may monitor, intercept, and search and seize
      any communication or data transiting or stored on this system.
  
  -   Any communication or data transiting or stored on this system may be
      disclosed or used for any lawful Government purpose.
--------------------------------------------------------------------------------


The default interactive shell is now zsh.
To update your account to use zsh, please run `chsh -s /bin/zsh`.
For more details, please visit https://support.apple.com/kb/HT208050.
[kumarr9@NCI-02296922-ML ~]$ cd ~/Downloads
[kumarr9@NCI-02296922-ML Downloads]$ scp kumarr9@helix.nih.gov:/data/kumarr9/Brett_HPD/analysis/ARACNE_HPD_vs_NonHPD.png .
                           ***WARNING***

You are accessing a U.S. Government information system, which includes
(1) this computer, (2) this computer network, (3) all computers 
connected to this network, and (4) all devices and storage media 
attached to this network or to a computer on this network. This 
information system is provided for U.S.  Government-authorized use only.

Unauthorized or improper use of this system may result in disciplinary
action, as well as civil and criminal penalties.

By using this information system, you understand and consent to the
following:

* You have no reasonable expectation of privacy regarding any 
communications or data transiting or stored on this information system. 
At any time, and for any lawful Government purpose, the government may 
monitor, intercept, record, and search and seize any communication or 
data transiting or stored on this information system.

* Any communication or data transiting or stored on this information 
system may be disclosed or used for any lawful Government purpose.

--
Notice to users:  This system is rebooted for patches and maintenance on
the first Sunday of every month at 8:00 pm unless Monday is a holiday, in
which case it is rebooted the following Sunday evening at 8:00 pm.  Running 
cluster jobs are not affected by the monthly reboot. 

kumarr9@helix.nih.gov's password: 
ARACNE_HPD_vs_NonHPD.png                                                                                                          100%  134KB 845.0KB/s   00:00    
[kumarr9@NCI-02296922-ML Downloads]$ ssGSEA.git
-bash: ssGSEA.git: command not found
[kumarr9@NCI-02296922-ML Downloads]$ vi ssGSEA.git
[kumarr9@NCI-02296922-ML Downloads]$ vi ssGSEA.git 
[kumarr9@NCI-02296922-ML Downloads]$ git remote add origin git@github.com:imrjesh/ssGSEA.git
fatal: not a git repository (or any of the parent directories): .git
[kumarr9@NCI-02296922-ML Downloads]$ git status
fatal: not a git repository (or any of the parent directories): .git
[kumarr9@NCI-02296922-ML Downloads]$ git ini
git: 'ini' is not a git command. See 'git --help'.

The most similar commands are
	init
	init-db
[kumarr9@NCI-02296922-ML Downloads]$ git remote add origin git@github.com:imrjesh/ssGSEA.git
fatal: not a git repository (or any of the parent directories): .git
[kumarr9@NCI-02296922-ML Downloads]$ ls -lrt
total 81875384
drwxrwxr-x@ 10 kumarr9  NIH\Domain Users          320 Jan 18  2016 Hope4Genes-master
-rw-r--r--@  1 kumarr9  NIH\Domain Users         2728 Mar  2  2019 quartile_norm.pl
-rw-r--r--@  1 kumarr9  NIH\Domain Users      5876481 Sep 21  2021 s41591-021-01448-w.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        15912 Sep 23  2021 List of Apartment.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users      3400731 Oct  1  2021 G__Online_Inspire_ReadWriteData_Temp_20211001215822310136386.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users      3400570 Oct  1  2021 G__Online_Inspire_ReadWriteData_Temp_2021100122002742805404.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       524863 Oct 11  2021 PPT_Merck.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users     23963087 Oct 20  2021 metadata.csv
-rw-------@  1 kumarr9  NIH\Domain Users       456565 Nov  8  2021 changeofaddressform.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        25022 Nov 10  2021 DBT_early_career_full_proposal (1).docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        27939 Nov 10  2021 DBT_early_career_full_proposal.docx
-rw-------@  1 kumarr9  NIH\Domain Users      2091214 Nov 23  2021 Return-to-Work-Guidance (1).pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       120914 Nov 24  2021 Certificate.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users      3718120 Dec 15  2021 TCS_Interview_PPT.pdf
drwxrwxr-x@  3 kumarr9  NIH\Domain Users           96 Dec 15  2021 IGV_2.11.7.app
-rw-r--r--@  1 kumarr9  NIH\Domain Users      3384263 Dec 16  2021 PXL_20211213_230047769.PORTRAIT.jpg
-rw-r--r--@  1 kumarr9  NIH\Domain Users     30764972 Dec 17  2021 anjali_epitope_pipeline.rar
-rw-r--r--@  1 kumarr9  NIH\Domain Users      5501255 Dec 19  2021 rajesh.jpg
-rw-r--r--@  1 kumarr9  NIH\Domain Users      4012901 Dec 19  2021 rajesh_11.jpeg
-rw-r--r--@  1 kumarr9  NIH\Domain Users        12520 Dec 19  2021 ridhi.jpeg
-rw-r--r--@  1 kumarr9  NIH\Domain Users        11217 Jan 23  2022 george_data_ids_genomes.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       396722 Feb  2  2022 all_fusion_numbers.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       388074 Feb  7  2022 circos.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users     87756404 Feb  9  2022 jre-8u321-macosx-x64.dmg
-rw-r-----@  1 kumarr9  NIH\Domain Users      6654682 Feb 10  2022 fusions.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        90483 Feb 14  2022 IL-2_Manuscript_Revised_latest_all_modified.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        90721 Feb 14  2022 IL-2_Manuscript_Revised_latest_highlighted.docx
-rw-------@  1 kumarr9  NIH\Domain Users        47089 Feb 15  2022 DTB EMAIL-02152022.pdf
-rw-------@  1 kumarr9  NIH\Domain Users       126173 Feb 15  2022 2-15-2022-DTB Lab Roster .pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1340287 Feb 17  2022 PLX038 ATM  0215 final final.docx
-rw-------@  1 kumarr9  NIH\Domain Users      1350234 Feb 18  2022 PLX038 ATM  0215 final final_NT20220218.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users           47 Feb 22  2022 donut.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       194610 Feb 22  2022 PoW- Fraction of total (student grades).tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users       108203 Feb 23  2022 cancerGeneList.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         7279 Feb 23  2022 oncokb.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users         5588 Feb 23  2022 all_gene.txt
-rw-r--r--   1 kumarr9  NIH\Domain Users          226 Feb 23  2022 for_grep.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users          265 Feb 23  2022 SCLC_fusion_mapped_oncoKb_list.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users         4760 Feb 23  2022 SCLC_fusion_mapped_oncoKB.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users       127951 Feb 23  2022 untitled.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users         9009 Feb 23  2022 oncofuse.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        53919 Feb 27  2022 NIHMS958978-supplement-3.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         9869 Mar  4  2022 Book11.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        59881 Mar  4  2022 Rajesh.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        10477 Mar  6  2022 book_chapter.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       417819 Mar  9  2022 rajesh_biodata_cum_cover_letter_postdoc.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        44964 Mar  9  2022 Draft_chapter.docx
-rw-------@  1 kumarr9  NIH\Domain Users        53980 Mar 10  2022 Clinical-characteritics-AT-March9-review.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users         9662 Mar 10  2022 Book2.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        16037 Mar 10  2022 sclc_bam_to_sorted_bam.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users       186960 Mar 11  2022 Starbucks eGift Cards from CashStar.pdf
-rw-------@  1 kumarr9  NIH\Domain Users        89600 Mar 11  2022 Sample sheet CS028104 CS029023 and CS029575parth.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users     22456253 Mar 12  2022 featurecount.xlsx
-rw-r--r--   1 kumarr9  NIH\Domain Users     14000428 Mar 13  2022 RsubReadcounts-TheRawCounts.csv
-rw-r--r--   1 kumarr9  NIH\Domain Users         1874 Mar 13  2022 phenodata.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       790054 Mar 13  2022 annotation_file.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users     14000428 Mar 13  2022 test.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        14376 Mar 16  2022 MicrosoftTeams-image.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        21039 Mar 19  2022 Annexure A_final.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        67607 Mar 20  2022 proof_documents_state_id.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       434495 Mar 20  2022 Online Services - myMVA.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users     10042996 Mar 20  2022 CCLE_fusions.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users    217178263 Mar 21  2022 RStudio-2022.02.0-443.dmg
-rw-r--r--@  1 kumarr9  NIH\Domain Users        14289 Mar 23  2022 Current and Emerging Approaches in Vaccine Design.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        13617 Mar 23  2022 Anjali Ver - Current and Emerging Approaches in Vaccine Design and Delivery.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        56220 Mar 23  2022 MC Proposal 2021.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        15920 Mar 24  2022 PR.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        19091 Mar 29  2022 DTB_files_fathi.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        33193 Mar 29  2022 george_all_fusion.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        11206 Mar 29  2022 sclc_jiang.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         6970 Mar 29  2022 all_common.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        53050 Mar 29  2022 all_common.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users      5929117 Mar 31  2022 RASGRF1 Fusions Activate Oncogenic RAS Signaling and Confer Sensitivity to MEK Inhibition .pdf
-rw-------@  1 kumarr9  NIH\Domain Users      5499665 Apr  1  2022 Proof_NT20220330.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        19244 Apr  1  2022 Responses_to_reviewer_DDT.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users      4653134 Apr  1  2022 stem_cell_book.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users      2604275 Apr  3  2022 RK_Biography.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        73416 Apr  3  2022 SCL.fasta
-rw-r--r--@  1 kumarr9  NIH\Domain Users        16293 Apr  3  2022 Authors list by RK-PR.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1058845 Apr  5  2022 Discover-Statement-20220318-2036.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       447414 Apr  5  2022 Maryland ID.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       193743 Apr  5  2022 bank_statement.pdf
-rw-------@  1 kumarr9  NIH\Domain Users     30445738 Apr  5  2022 41586_2015_BFnature14664_MOESM72_ESM.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       292929 Apr  6  2022 Rajesh_tax_form.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       136391 Apr  7  2022 f1040nr.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         9309 Apr  9  2022 POLD3_plot.svg
-rw-r--r--@  1 kumarr9  NIH\Domain Users        55930 Apr  9  2022 Enrichr_results_bar.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users       667547 Apr  9  2022 POLD3_drugs.jpeg
-rw-r--r--@  1 kumarr9  NIH\Domain Users        73929 Apr 11  2022 Inspire_faculty_Results_2020.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       128752 Apr 14  2022 fusion_Nobu.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users     14305253 Apr 18  2022 BoxToolsInstaller.dmg
-rw-r--r--@  1 kumarr9  NIH\Domain Users        11598 Apr 18  2022 POLD3_RNF169.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         3293 Apr 20  2022 cell lines in SCLC.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        60709 Apr 20  2022 Presentation1.pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       131902 Apr 20  2022 kisspng-bhavra-allahabad-chandra-shekhar-azad-july-23-hind-wife-5ac0bc7e137339.6590616415225806060797.jpg
-rw-r--r--@  1 kumarr9  NIH\Domain Users       437819 Apr 20  2022 120-1201942_chandrashekhar-azad-hd-png-download.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users      2826085 Apr 21  2022 41467_2019_9940_MOESM5_ESM.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users      2392639 Apr 25  2022 ecDNA manuscript 04262022.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       454730 Apr 25  2022 41467_2019_9940_MOESM11_ESM.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users        14092 Apr 26  2022 POLD3_RNF169.docx
-rw-------@  1 kumarr9  NIH\Domain Users       489853 Apr 26  2022 image002.png
-rw-------@  1 kumarr9  NIH\Domain Users      4657166 Apr 27  2022 FISH for chromosome instability human tissues.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users      2524180 Apr 28  2022 ecDNA manuscript 04262022.CWSMIA.docx
-rw-r--r--   1 kumarr9  NIH\Domain Users         3585 Apr 28  2022 POLD3-RNF169.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users        18936 Apr 28  2022 Annexure_III_Authors list.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       149062 Apr 29  2022 ijerph-09-02444.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1709421 Apr 29  2022 pnas.201204406si.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       596901 Apr 29  2022 pnas.201204406.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       150115 May  3  2022 Discover Card_ Make a Payment Confirmation Printable.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users     21586693 May  5  2022 homo_sapiens.v104.hg38.gff3
-rw-r--r--@  1 kumarr9  NIH\Domain Users          137 May  9  2022 charlie.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users         5659 May  9  2022 id.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users        18010 May 13  2022 Whyte_et_al_2013_SEs_genes.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      2242358 May 13  2022 Rplot.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1402302 May 13  2022 Rplot02.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1682326 May 13  2022 Rplot03.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users      4802518 May 13  2022 Rplot04.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users        55525 May 13  2022 Rplot05.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        50535 May 13  2022 Rplot06.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1297 May 13  2022 countss.tsv
-rw-------@  1 kumarr9  NIH\Domain Users      5973738 May 14  2022 Fig.pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        12682 May 15  2022 Rplot07.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        14249 May 15  2022 Rplot08.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        14260 May 15  2022 Rplot09.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users          280 May 15  2022 sample.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users          750 May 15  2022 sample1.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       595438 May 15  2022 Rplot10.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users         5385 May 15  2022 Rplot11.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         3520 May 15  2022 cont.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         3337 May 15  2022 countsss.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1402 May 15  2022 test.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         5425 May 15  2022 Rplot12.pdf
-rw-r--r--   1 kumarr9  NIH\Domain Users         1297 May 15  2022 test1.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         2327 May 15  2022 test2.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         8166 May 15  2022 Rplot13.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users          647 May 15  2022 loli.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        14185 May 15  2022 Rplot14.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        14210 May 15  2022 Rplot15.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        14030 May 15  2022 Rplot16.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        14244 May 15  2022 Rplot17.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        14281 May 15  2022 Rplot18.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        14064 May 15  2022 Rplot19.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        14403 May 15  2022 Rplot20.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users     38503223 May 16  2022 sample_1.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users         7793 May 17  2022 EP_SCLC.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         7652 May 17  2022 NE_NonNE.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         7855 May 17  2022 Rplot21.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        14315 May 17  2022 Rplot22.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        14400 May 17  2022 Rplot23.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        14414 May 17  2022 Rplot24.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        14453 May 17  2022 Rplot25.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        14296 May 17  2022 Rplot26.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        14171 May 17  2022 Rplot27.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        14212 May 17  2022 Rplot28.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        14382 May 17  2022 Rplot29.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        15694 May 17  2022 Rplot30.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users          111 May 17  2022 bar.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         5725 May 17  2022 Rplot31.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         5723 May 17  2022 Rplot32.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         5811 May 17  2022 Rplot33.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         5833 May 17  2022 Rplot34.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users           74 May 17  2022 bar1.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users         2485 May 17  2022 contt.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1220 May 17  2022 bar2.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         2723 May 17  2022 All_chr_num_DS_splice.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users          121 May 17  2022 bar3.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1487906 May 17  2022 PIIS2589750021002740.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1562 May 17  2022 file_ftd.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         5997 May 17  2022 Rplot35.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         5902 May 17  2022 Rplot36.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         8093 May 17  2022 Rplot37.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         8094 May 17  2022 Rplot38.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         8069 May 17  2022 Rplot39.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         8083 May 17  2022 Rplot40.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         7964 May 17  2022 Rplot41.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         8027 May 17  2022 Rplot42.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        34411 May 17  2022 NE_nonNE.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         7306 May 18  2022 Rplot43.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         7282 May 18  2022 Rplot44.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         5048 May 18  2022 Rplot45.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         4977 May 18  2022 Rplot46.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users          675 May 18  2022 sample2.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         2485 May 18  2022 conttt.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1094 May 18  2022 context.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        10890 May 18  2022 Rplot47.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        10881 May 18  2022 Rplot48.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       715168 May 18  2022 sankeymatic_20220518_142911_5400x3600.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users       695690 May 18  2022 sankeymatic_20220518_145546_5400x3600.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users       306391 May 18  2022 SCLC_sample_distribution.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users       388461 May 18  2022 SCLC_Fusion_distribution.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users       407583 May 18  2022 sankey_latest.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users         7309 May 18  2022 Rplot49.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       151132 May 19  2022 Discover Card_ Make a Payment Confirmation Printable_May.pdf
-rw-------@  1 kumarr9  NIH\Domain Users          695 May 19  2022 Pritee Smith.vcf
-rw-r--r--   1 kumarr9  NIH\Domain Users         1275 May 19  2022 sample2_bkp.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users         1157 May 19  2022 counts.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1539 May 19  2022 final_circular.R
-rw-r--r--@  1 kumarr9  NIH\Domain Users        21751 May 19  2022 George_all.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         2725 May 19  2022 counts.csv
-rw-r--r--   1 kumarr9  NIH\Domain Users         1157 May 19  2022 count.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users         2622 May 19  2022 counts_salman.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1094 May 19  2022 counttt.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         9847 May 19  2022 circular_salman.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users     31302009 May 19  2022 Rplot50.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        20966 May 20  2022 computational vaccinology.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users       558599 May 22  2022 NCI_huizi_autopsy_SCLC_liver_others_GSEA_Tachmatzidi_liver_tf_20220522.pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       384384 May 22  2022 I-129 worksheet.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       107490 May 23  2022 Vaccine appointment confirmation - CVS Pharmacy.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1462 May 24  2022 data10.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        17810 May 24  2022 project_review_report.docx
-rw-r--r--   1 kumarr9  NIH\Domain Users         1135 May 24  2022 venn.png.2022-05-24_14-39-36.log
-rw-r--r--   1 kumarr9  NIH\Domain Users         1135 May 24  2022 venn.png.2022-05-24_14-40-27.log
-rw-r--r--@  1 kumarr9  NIH\Domain Users       484718 May 24  2022 venn.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        16988 May 25  2022 Review paper  Comments.docx
-rw-------@  1 kumarr9  NIH\Domain Users      1385287 May 25  2022 SCLC_RxbeyondIO_seminars.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         3284 May 25  2022 venn_intersection.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       205951 May 26  2022 r-cheat-sheet.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1844 May 26  2022 venn_intersection1.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        20431 May 27  2022 all_RNA_seq_data.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        38907 May 28  2022 Reviewer Questionnaire_Raghav, et al.docx
-rw-------@  1 kumarr9  NIH\Domain Users       517874 May 31  2022 HLA_project_proposal_final_short.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       174270 Jun  1  2022 Piyush_Passport_renewal.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       331570 Jun  1  2022 Piyush_APPLICATION FORM FOR INDIAN PASSPORT_ARN_22-2002021430.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       418609 Jun  3  2022 BillImage.pdf
-rw-r--r--   1 kumarr9  NIH\Domain Users         2029 Jun  3  2022 TPM_Merged_File.R
-rw-------@  1 kumarr9  NIH\Domain Users        31532 Jun  5  2022 IMG_3387.jpg
-rw-r--r--@  1 kumarr9  NIH\Domain Users     87987880 Jun  6  2022 ATAC-seq workshop-20220606T180539Z-001.zip
-rw-r--r--@  1 kumarr9  NIH\Domain Users        65004 Jun  7  2022 m_4840fig1.jpeg
-rw-r--r--@  1 kumarr9  NIH\Domain Users       299895 Jun 10  2022 ATAC.png
-rw-------@  1 kumarr9  NIH\Domain Users        12126 Jun 10  2022 Rapid Autopsy CHiPSeq-ATACseq batch1 Manifest.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        29768 Jun 11  2022 ReviewCompliedDocument_Raghav, et al.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        22783 Jun 13  2022 Stem Cell_Suggested_Reviewers.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users    159266814 Jun 14  2022 all_sample.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users    128872456 Jun 14  2022 all_sclc_rna_samples_TPM_57622_genes.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users          425 Jun 14  2022 gsets.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users        31991 Jun 14  2022 NE_Non_NE.tsv
-rw-------@  1 kumarr9  NIH\Domain Users        27655 Jun 16  2022 NCI_signatures.tsv
-rw-------@  1 kumarr9  NIH\Domain Users        12988 Jun 16  2022 Cells to Juanma.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       972485 Jun 18  2022 Modified_Vaishali_Review1.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       417605 Jun 18  2022 Vaishali_review_outline.docx
-rw-------@  1 kumarr9  NIH\Domain Users           71 Jun 18  2022 RLF_MYCL_hg19.bed
-rw-------@  1 kumarr9  NIH\Domain Users       192356 Jun 18  2022 image003.png
-rw-------@  1 kumarr9  NIH\Domain Users      6148524 Jun 23  2022 SCLC-cfChIP_nature_medicine_submission.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users     10644544 Jun 24  2022 CANCER_TYPE_EDA.html
-rw-------@  1 kumarr9  NIH\Domain Users        46061 Jun 29  2022 NCI_Kumar_POLD3_RNF169_TE-94461624_4X_RNA.zip
-rw-------@  1 kumarr9  NIH\Domain Users        79708 Jun 29  2022 NCI_Kumar_POLD3_RNF169_TE-93150521_LongRead_hg19.zip
-rw-------@  1 kumarr9  NIH\Domain Users      3945395 Jun 30  2022 Califano_VIPER.pptx
-rw-------@  1 kumarr9  NIH\Domain Users       156804 Jun 30  2022 nci_sclc_viper_ne_diffexp160.pdf
-rw-------@  1 kumarr9  NIH\Domain Users       144429 Jun 30  2022 nci_sclc_viper_ne_diffact160.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users      4149820 Jun 30  2022 Anjali_paper.pdf
-rw-------@  1 kumarr9  NIH\Domain Users        33528 Jul  7  2022 Q-185302_POLD3_LongRead Panel .pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         9828 Jul  7  2022 SCLC_bam_files.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users      2106848 Jul 11  2022 Fusion_DTB_comments_ajit.pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users     10918706 Jul 14  2022 Rapid genome editing by CRISPR-Cas9-POLD3 fusion.pdf
-rw-r--r--   1 kumarr9  NIH\Domain Users        34914 Jul 14  2022 hg19-blacklist.v2.bed
-rw-------@  1 kumarr9  NIH\Domain Users      5704758 Jul 15  2022 ISCIENCE-D-22-02793_reviewer.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1647183 Jul 15  2022 mmc2.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users    258051137 Jul 15  2022 CCLE_mutations.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      7897203 Jul 15  2022 f1.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users     11873824 Jul 15  2022 f17.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users     19771027 Jul 15  2022 CCLE_file.txt
-rw-r--r--   1 kumarr9  NIH\Domain Users         7119 Jul 15  2022 Gene_file.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users        12693 Jul 15  2022 common_ccle_SE_gene.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users          608 Jul 15  2022 common_ccle_SE_gene_top_50.tsv
-rw-------@  1 kumarr9  NIH\Domain Users      6253362 Jul 18  2022 Fusion_Functional_Approaches.pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        14097 Jul 20  2022 POLD3-RNF169_cDNA.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users          318 Jul 20  2022 epitope_predicted.tsv
-rw-------@  1 kumarr9  NIH\Domain Users       509245 Jul 21  2022 Signed_Raghav, et al_Book Head Contract Inc Ltd BV 972970.docx.pdf
-rw-------@  1 kumarr9  NIH\Domain Users        34458 Jul 22  2022 sample sheet.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users      6431448 Jul 28  2022 FTD.hg38.genotype_selectedVars_het_chr3.raw
-rw-r--r--@  1 kumarr9  NIH\Domain Users        89185 Jul 29  2022 NEUROD1_batch1.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users       142053 Jul 29  2022 ASCL1_batch1.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users       137487 Jul 29  2022 POU2F2_batch1.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users       110188 Jul 29  2022 YAP1_batch1.png
-rw-r--r--   1 kumarr9  NIH\Domain Users        77555 Jul 29  2022 MYC_batch1.png
-rw-r--r--   1 kumarr9  NIH\Domain Users        98552 Jul 29  2022 MYCL_batch1.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users       703906 Jul 30  2022 REVIEW.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       441171 Jul 31  2022 rsfs20150105.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users      2407157 Jul 31  2022 47.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users      7913129 Jul 31  2022 Computational Tools for Stem Cell Biology _ Enhanced Reader.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       615749 Aug  1  2022 certificate_2022.jpeg
-rw-------@  1 kumarr9  NIH\Domain Users       454840 Aug  1  2022 20220801_135514_resized.jpeg
-rw-------@  1 kumarr9  NIH\Domain Users       477441 Aug  1  2022 20220801_135505_resized.jpeg
-rw-r--r--@  1 kumarr9  NIH\Domain Users       182732 Aug  1  2022 Division of International Services Case Status and Reports_.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        45750 Aug  2  2022 PROX1_longitudinal_0059.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        46655 Aug  2  2022 FOXA1_longitudinal_0059.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        51637 Aug  2  2022 ONCECUT1_longitudinal_0059.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        69532 Aug  2  2022 FOXA1_high_liver_met_vs_low_TF_no_liver_sum_score.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        83023 Aug  2  2022 NR5A2_high_liver_met_vs_low_TF_no_live_sum_score.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        80404 Aug  2  2022 ONECUT1_high_liver_met_vs_low_TF_no_liver_sum_score.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        77498 Aug  2  2022 GATA6_high_liver_met_vs_low_TF_no_liver_sum_score.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        80884 Aug  2  2022 PROX1_high_liver_met_vs_low_TF_no_liver_sum_score.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users      6431448 Aug  3  2022 FTD.hg38.neotype_selectvar.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        89351 Aug  3  2022 DocumentChecklists2.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       193323 Aug  3  2022 USA996219993.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         9676 Aug  3  2022 USA996219993_CourierLabel.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users     18822324 Aug  3  2022 DRISTHI_PAPER.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users      2178460 Aug  5  2022 Rapid identification of genomic structural variations with nanopore sequencing           enables blood-based cancer monitoring .pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users    184255161 Aug  5  2022 Handbook of Chemoinformatics - 2003 - Gasteiger.pdf
-rw-------@  1 kumarr9  NIH\Domain Users        45499 Aug  5  2022 qPCR.pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users      2739356 Aug  8  2022 JCB_201109100.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users      5055459 Aug  8  2022 vcf_subset.zip
drwxr-xr-x@  3 kumarr9  NIH\Domain Users           96 Aug  8  2022 vcf_subset
-rw-------@  1 kumarr9  NIH\Domain Users        16984 Aug  9  2022 CSID_NCI thomas large dataset.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        14456 Aug  9  2022 Accepted and waiting list.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users        27160 Aug  9  2022 Master sheet_NCI THOMAS_352.txt
-rw-------@  1 kumarr9  NIH\Domain Users        64971 Aug  9  2022 Combined Bulk_4_2022_Rajesh_list_all_RNA_seq_data.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        48143 Aug 11  2022 istockphoto-1297657670-612x612.jpeg
-rw-r--r--@  1 kumarr9  NIH\Domain Users       617253 Aug 11  2022 6314734.jpeg
-rw-r--r--@  1 kumarr9  NIH\Domain Users        15997 Aug 11  2022 Accepted and waiting list (1).xlsx
-rw-------@  1 kumarr9  NIH\Domain Users        36780 Aug 12  2022 Copy of sample sheet (002).xlsx
drwxr-xr-x   3 kumarr9  NIH\Domain Users           96 Aug 16  2022 PDX_atac_narrow
-rw-r--r--@  1 kumarr9  NIH\Domain Users        12101 Aug 16  2022 ATAC_feature_distribution.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       259872 Aug 17  2022 ATAC_feature_npg_color.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users       261595 Aug 17  2022 ATAC_feature_igv.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users       280358 Aug 17  2022 Covplot.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        25752 Aug 17  2022 ATAC_peak_TSS.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        30947 Aug 17  2022 Heatmap_ATAC_TSS.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        93028 Aug 17  2022 ATAC_venn_upset.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        76412 Aug 17  2022 ATAC_enrichment.png
-rw-------@  1 kumarr9  NIH\Domain Users      1630201 Aug 22  2022 DSP_tumor_stroma_correlation_violin_plot_20211228.pzfx
-rw-r-----@  1 kumarr9  NIH\Domain Users       132569 Aug 23  2022 PCA_plot_loading.png
-rw-r-----   1 kumarr9  NIH\Domain Users        83594 Aug 23  2022 PCA_pairplot.png
-rw-r-----   1 kumarr9  NIH\Domain Users        85361 Aug 23  2022 PCA_bi.png
-rw-r-----@  1 kumarr9  NIH\Domain Users        81064 Aug 23  2022 PCA.png
-rw-r--r--   1 kumarr9  NIH\Domain Users         8240 Aug 23  2022 Chip_only.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        99368 Aug 23  2022 ATAC_only.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        62865 Aug 23  2022 Chip_only.png
-rw-r-----   1 kumarr9  NIH\Domain Users        49427 Aug 23  2022 ATAC_screenshot.png
-rw-r-----   1 kumarr9  NIH\Domain Users       147457 Aug 23  2022 ATAC_cluster.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users         8426 Aug 23  2022 ATAC.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        43520 Aug 24  2022 SampleLetterTravel.doc
-rw-r-----   1 kumarr9  NIH\Domain Users    155029544 Aug 25  2022 ATAC_all_sample_peaks_sorted.narrowPeak
-rw-r--r--   1 kumarr9  NIH\Domain Users         8231 Aug 29  2022 TMSCLC.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        21706 Aug 29  2022 ATAC_feature_distribution_copy.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       101285 Aug 29  2022 TMSCLC.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        85850 Aug 30  2022 PCA_ATAC.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        91067 Aug 30  2022 ATAC_PCAA.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users       142997 Aug 31  2022 Rplot51.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users     60755704 Aug 31  2022 ATAC_count.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       396025 Aug 31  2022 ATAC_PCA_top_one.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users       290854 Aug 31  2022 venn_plot_parth.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users       370830 Aug 31  2022 ATAC_PCA_all_samples.png
-rw-r--r--   1 kumarr9  NIH\Domain Users         1892 Aug 31  2022 VennDiagram.2022-08-31_14-11-25.log
-rw-r--r--@  1 kumarr9  NIH\Domain Users       259813 Aug 31  2022 venn_plot_parthh.sb-654ff044-hbMMSC
-rw-r--r--@  1 kumarr9  NIH\Domain Users       259813 Aug 31  2022 venn_plot_parthh.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users       391264 Aug 31  2022 venn_plot_parthhh.png
-rw-r--r--   1 kumarr9  NIH\Domain Users         1892 Aug 31  2022 VennDiagram.2022-08-31_14-16-13.log
-rw-r--r--@  1 kumarr9  NIH\Domain Users       232164 Aug 31  2022 plot_zoom_png.sb-654ff044-v8ySQR
-rw-r--r--@  1 kumarr9  NIH\Domain Users       232164 Aug 31  2022 plot_zoom_png.png
-rw-------@  1 kumarr9  NIH\Domain Users       743122 Sep  7  2022 NucleoSIF-AH-Davis-NCI-18 samples (6 human-12 mouse)-CHIP-WOBI-NVUS2021050508_V2.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users     16033001 Sep  7  2022 chromatin landscape based enhancer patterns and IO response.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users          976 Sep  7  2022 metadata1.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       918281 Sep  7  2022 QC analysis report.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users     60755701 Sep  8  2022 ATAC_count1.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        13021 Sep  8  2022 UMAP.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       151825 Sep  9  2022 UMAP_plot_example2.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users      6327757 Sep 12  2022 s41467-022-29517-9.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         2601 Sep 13  2022 metadata2.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      9205493 Sep 13  2022 ATAC_RNA.csv
-rw-------@  1 kumarr9  NIH\Domain Users         8223 Sep 13  2022 ssGSEA_NE_SignatureEtc.Rmd
-rw-r--r--@  1 kumarr9  NIH\Domain Users       152379 Sep 13  2022 EthicsCert.jpeg
-rw-r--r--@  1 kumarr9  NIH\Domain Users     14600192 Sep 14  2022 ATAC_RNA.xls
-rw-r--r--@  1 kumarr9  NIH\Domain Users      4108568 Sep 14  2022 RNA.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         5944 Sep 15  2022 cricker_run.csv
-rw-------@  1 kumarr9  NIH\Domain Users       153081 Sep 16  2022 Supplier Payee Onboarding Form (Rajesh Kumar).xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       264639 Sep 16  2022 MicrosoftTeams-image (1).png
-rw-r--r--@  1 kumarr9  NIH\Domain Users       186128 Sep 16  2022 UMAP_plot_example1.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users       158335 Sep 18  2022 UMAP_plot_example11.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users       614804 Sep 18  2022 UMAP_top1.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       616690 Sep 18  2022 consensus_top1.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       614201 Sep 18  2022 consensus_top1_copy.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users         2697 Sep 18  2022 atest.tsv
drwxr-xr-x@  3 kumarr9  NIH\Domain Users           96 Sep 19  2022 FileZilla.app
-rw-r--r--@  1 kumarr9  NIH\Domain Users       152140 Sep 19  2022 corr.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users      4380255 Sep 20  2022 ftd_umap_data.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         2293 Sep 20  2022 chat_martin.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users     58271689 Sep 20  2022 ATAC_TPM_standard_deviation.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       624447 Sep 20  2022 top1_tpm.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       622536 Sep 20  2022 top1_tpm_umap.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1249719 Sep 20  2022 top2_tpm.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1245323 Sep 20  2022 top2_tpm_umap.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       937374 Sep 20  2022 top1.5_tpm.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       934220 Sep 20  2022 top1.5_tpm_umap.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1560207 Sep 20  2022 top2.5_tpm.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1554569 Sep 20  2022 top2.5_tsv_umap.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1870902 Sep 20  2022 top3_tpm.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1864021 Sep 20  2022 top3_tpm_umap.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      3105026 Sep 20  2022 top5_tpm.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      3093175 Sep 20  2022 top5_tpm_umap.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       502192 Sep 20  2022 top2000_tpm.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       754302 Sep 20  2022 top3000_tpm.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       500766 Sep 20  2022 top2000_tpm_umap.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       751876 Sep 20  2022 top3000_tpm_umap.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       375077 Sep 20  2022 top1500_tpm_umap.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       376003 Sep 20  2022 top1500_tpm.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       249750 Sep 20  2022 top1000_tpm_umap.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       250176 Sep 20  2022 top1000_tpm.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       125169 Sep 20  2022 top500_tpm.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       125243 Sep 20  2022 top500_tpm_umap.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        26538 Sep 20  2022 top100_tpm_umap.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        26064 Sep 20  2022 top100_tpm.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1421908 Sep 20  2022 science.aay0256-2.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        68653 Sep 22  2022 Rplot52_copy.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users       565390 Sep 22  2022 top1_tpm_consensus.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        21316 Oct  1  2022 ATAC_data_distribution_with_biopsy_site_NT20220721.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        11554 Oct  1  2022 second_batch_atac.xlsx
drwxrwxr-x@  3 kumarr9  NIH\Domain Users           96 Oct  3  2022 GSEA_4.3.2.app
-rw-r--r--@  1 kumarr9  NIH\Domain Users        59155 Oct  4  2022 WhatsApp Image 2022-10-04 at 12.59.19 PM.jpeg
-rw-r--r--@  1 kumarr9  NIH\Domain Users       138058 Oct 10  2022 Jitesh_Fee_Receipt_3rd_quarter.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        91622 Oct 10  2022 PayOnline -OSM _Online School Management_Details.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        20935 Oct 29  2022 gProfiler_hsapiens_10-29-2022_2-22-48 AM.csv
-rw-------@  1 kumarr9  NIH\Domain Users        11856 Oct 29  2022 216_upregulated_SCLC-Inflamed_genes.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users        13677 Oct 29  2022 gene_iD_ensmbl.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        55381 Oct 31  2022 antiharasment.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       840853 Nov  1  2022 Jeetu Journey Confirmation.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        63370 Nov  2  2022 fatdestroyer_0.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users          798 Nov  3  2022 try.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users     12114839 Nov  4  2022 Inferring gene expression from cell-free DNA fragmentation profiles.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         8108 Nov  6  2022 Rplot02.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       109830 Nov  6  2022 Rplot53.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        98285 Nov  6  2022 Rplot52.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1142 Nov  7  2022 counts_1.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       147225 Nov  7  2022 Rplot54.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        15465 Nov  7  2022 inter_intra_fusion.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         8947 Nov  9  2022 NVUS2022081004.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       694097 Nov  9  2022 October_2022.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       168834 Nov  9  2022 September_2022.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       168887 Nov  9  2022 August_2022.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        34377 Nov  9  2022 ICMJE COI Disclosure Form.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        15827 Nov 11  2022 comments_respinse_covid-19.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        51125 Nov 11  2022 Stem cell_10-10-2022.docx
-rw-------@  1 kumarr9  NIH\Domain Users      6493484 Nov 14  2022 SCLC gene fusions 11042022.pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       718191 Nov 14  2022 UMAP_plot_example12.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users       998781 Nov 14  2022 PXL_20221115_014406606.jpeg
-rw-------@  1 kumarr9  NIH\Domain Users      1532097 Nov 15  2022 Tumor_Proteomics.csv
-rw-------@  1 kumarr9  NIH\Domain Users      1208461 Nov 15  2022 TME_Liverspecific.csv
-rw-------@  1 kumarr9  NIH\Domain Users       102695 Nov 15  2022 GSEA_multiple 4000SD genes_summary.txt
-rw-------@  1 kumarr9  NIH\Domain Users       399946 Nov 15  2022 GSEA_GOBP_4000SD.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users       102183 Nov 16  2022 GSEA_multiple_4000_genes.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        27443 Nov 16  2022 gsea_m_4000.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users          858 Nov 16  2022 gsea.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users         2146 Nov 16  2022 new_gsea.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users         2122 Nov 16  2022 go_gsea.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         2523 Nov 16  2022 q_gsea_multiple.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users         2657 Nov 16  2022 q_gsea_go.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       376551 Nov 16  2022 GSEA_GOBP_4000.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       188447 Nov 16  2022 GSEA_GOBP_4000.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        86662 Nov 17  2022 ajit_phone.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        27366 Nov 18  2022 POLD3-RNF169 Fusion Patient Info and Neoantigenicity.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users    224491875 Nov 18  2022 RStudio-2022.07.2-576.dmg
-rw-r--r--   1 kumarr9  NIH\Domain Users           82 Nov 18  2022 cafgenelist.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users        25411 Nov 18  2022 mellisa_new_score.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        25411 Nov 18  2022 mellisa.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        27114 Nov 18  2022 mellisa_ne_score.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      2399627 Nov 19  2022 TME_tumor.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       417819 Nov 22  2022 rajesh_biodata_cum_cover_letter_postdoc (1).pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        91384 Nov 23  2022 delphine_data.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       353924 Nov 27  2022 Rajesh_Kumar_Consulting_Agreement_signed.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1791225 Nov 28  2022 SRR8652085.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       650589 Nov 28  2022 SRR8670710.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      2215348 Nov 28  2022 SRR8639221.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      3211776 Nov 28  2022 SRR8652085.xls
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1559040 Nov 28  2022 SRR8670710.xls
-rw-r--r--@  1 kumarr9  NIH\Domain Users        39835 Nov 30  2022 TMB.pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users      7859712 Dec  5  2022 SRR8639221.xls
-rw-------@  1 kumarr9  NIH\Domain Users       336813 Dec  6  2022 Rajesh Kumar Receipt.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1510673 Dec  7  2022 NIH_map.jpeg
-rw-r--r--@  1 kumarr9  NIH\Domain Users        11788 Dec  8  2022 ATAC.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        12186 Dec 11  2022 Book10.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        43456 Dec 14  2022 ppt.pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       798711 Dec 14  2022 Immunotherapy of Neuroendocrine Neoplasms- Any Role for the Chimeric Antigen Receptor T Cells?.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users      7772711 Dec 14  2022 nosine Monophosphate Dehydrogenase Dependence in a Subset of Small Cell Lung Cancers.pdf
-rw-r--r--   1 kumarr9  NIH\Domain Users        31560 Dec 16  2022 dotplot.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users         1164 Dec 16  2022 dotplot2.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        29608 Dec 18  2022 Book16.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        26905 Dec 28  2022 consensus.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1829826 Dec 29  2022 Biowulf data.pptx
-rw-r-----@  1 kumarr9  NIH\Domain Users    137681188 Dec 29  2022 TPM_normalized_coverages.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users          282 Jan  1  2023 bubble.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users          236 Jan  2  2023 bubble_top1.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users          242 Jan  2  2023 bubble_top5000.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1311592 Jan  2  2023 liver_mets_pdx.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        11586 Jan  5  2023 for_parth.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         5781 Jan  5  2023 rlf.csv
-rw-r--r--   1 kumarr9  NIH\Domain Users       188873 Jan  5  2023 dotplot3.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       400282 Jan  5  2023 GSEA_fusion_positive_GO_terms
-rw-r--r--@  1 kumarr9  NIH\Domain Users         9095 Jan  6  2023 RA22.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users      7374742 Jan  8  2023 new_file.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      3965671 Jan 13  2023 vierstra.sm.pdf
-rw-r--r--   1 kumarr9  NIH\Domain Users        11938 Jan 17  2023 ATAC_only.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         3345 Jan 19  2023 RA22_gene.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      6591149 Jan 23  2023 1-s2.0-S107476132200084X-main.pdf
-rw-------@  1 kumarr9  NIH\Domain Users          676 Jan 24  2023 Consensusmatrix.Rmd
drwxrwxr-x@  3 kumarr9  NIH\Domain Users           96 Jan 25  2023 IGV_2.16.0.app
-rw-r--r--@  1 kumarr9  NIH\Domain Users      2070444 Feb  6  2023 top5000_all_PDX_RA_natched_comparison_K5.pdf
-rw-------@  1 kumarr9  NIH\Domain Users      2456776 Feb 16  2023 atac.seq.2.16.23.pptx
-rw-------@  1 kumarr9  NIH\Domain Users     45791133 Feb 16  2023 1161_BatchCode.zip
-rw-r--r--@  1 kumarr9  NIH\Domain Users        76079 Feb 18  2023 CIRI_Full_v2.1.1.jar
-rw-r--r--@  1 kumarr9  NIH\Domain Users      4261665 Feb 18  2023 CIRI_v2.0.5.zip
-rw-r--r--   1 kumarr9  NIH\Domain Users         1877 Feb 18  2023 circminer.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users      5400599 Feb 22  2023 ATAC_RNA_raw_count.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        11234 Feb 22  2023 cell_line_fusion.xlsx
-rw-r--r--   1 kumarr9  NIH\Domain Users       205153 Feb 23  2023 RNA_liver_other_sig.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       132486 Feb 23  2023 hallmark.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users         2070 Feb 27  2023 clustinfo.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users          859 Mar  2  2023 NAPY.tsv
-rw-------@  1 kumarr9  NIH\Domain Users        65804 Mar  6  2023 image_parth.png
-rw-------@  1 kumarr9  NIH\Domain Users        65804 Mar  6  2023 image001.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        16604 Mar  6  2023 parth.xlsx
-rw-r--r--   1 kumarr9  NIH\Domain Users          671 Mar  7  2023 st_bar.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users         1667 Mar  8  2023 test_heatmap_annotation.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       217488 Mar  8  2023 Rplot 11.29.08 AM.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1328 Mar  8  2023 test_heatmap.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      3338240 Mar  9  2023 GSE214342_RAW.tar
-rw-------@  1 kumarr9  NIH\Domain Users       447357 Mar 24  2023 Authorship_Change_Form.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       172981 Mar 26  2023 Cyrus Driving School.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       155802 Mar 26  2023 Cyrus Driving School 2.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users      4742688 Mar 27  2023 TMM.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users      4264586 Mar 27  2023 FPKM.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users        85950 Mar 30  2023 IMG-20230329-WA0002.jpg
-rw-r--r--@  1 kumarr9  NIH\Domain Users        96226 Mar 30  2023 IMG-20230329-WA0003.jpg
-rw-r--r--@  1 kumarr9  NIH\Domain Users      7621991 Apr  5  2023 pbmc3k_filtered_gene_bc_matrices.tar.gz
-rw-r--r--@  1 kumarr9  NIH\Domain Users      2481704 Apr  6  2023 SCAF2447_Donor_1_filtered_feature_bc_matrix.h5
-rw-r--r--   1 kumarr9  NIH\Domain Users         3348 Apr  6  2023 single_cell.R
-rw-r--r--@  1 kumarr9  NIH\Domain Users        18212 Apr 13  2023 Thomas_RNAseq_all_data.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users     28562574 Apr 21  2023 PBMC_seu.RData
-rw-r--r--@  1 kumarr9  NIH\Domain Users        48651 Apr 22  2023 h.all.v2022.1.Hs.symbols.gmt
-rw-r-----@  1 kumarr9  NIH\Domain Users       443507 Apr 27  2023 infercnv.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users     49583484 May  2  2023 CytoTRACE_0.3.3.tar.gz
-rw-r--r--@  1 kumarr9  NIH\Domain Users       175514 May  8  2023 paul-maurizio-cv.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users      2193949 May  8  2023 Harvard-CV-Templates-Word-Download.zip
-rw-r--r--@  1 kumarr9  NIH\Domain Users      3357864 May  8  2023 Research-CV-Templates-Download-Word.zip
-rw-r--r--@  1 kumarr9  NIH\Domain Users        14044 May  9  2023 tongwu_data_transfer.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users       148992 May 10  2023 Copy of cfChiPseq_list_Pt_IDs_NT20230327_PD_editsant.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        18218 May 10  2023 all_CS_number_sample_ID.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        82886 May 11  2023 ctDNA plasma samples sent to Israel.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users        20005 May 12  2023 Batch0_DNA_Nobu era.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        81720 May 12  2023 ctDNA plasma samples sent to Israel new.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        10509 May 19  2023 data_to_be_transferred.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users          114 May 25  2023 2year.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         6279 May 25  2023 Population.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users          191 May 25  2023 2year.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users          159 May 25  2023 comparison.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users        86958 May 25  2023 phd_vs_postdoc.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1865341 May 26  2023 CLCVsharma.pdf
-rw-r--r--   1 kumarr9  NIH\Domain Users      2433879 May 30  2023 TP53_RB1_NE.csv
-rw-r-----   1 kumarr9  NIH\Domain Users     11582391 May 30  2023 brett_df_protein_coding.csv
-rw-r-----@  1 kumarr9  NIH\Domain Users     11582391 May 30  2023 brett_df_protein_coding.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         6805 May 30  2023 ne_score_brett.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users      2433879 May 30  2023 TP53_RB1_NE.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1000 May 30  2023 ne_score_brett_TP53_RB1_NE.tsv
-rw-r-----@  1 kumarr9  NIH\Domain Users       442978 May 30  2023 RU1138_all.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        20598 May 30  2023 RU1138_top20.csv
-rw-r-----   1 kumarr9  NIH\Domain Users       462290 May 30  2023 positive_marker_gene.csv
-rw-r-----@  1 kumarr9  NIH\Domain Users       462290 May 30  2023 RU426B.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        17008 May 30  2023 RU426B_top20.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        81235 Jun  1  2023 ctDNA plasma samples sent to Israel (1).xlsx
-rw-------@  1 kumarr9  NIH\Domain Users        24201 Jun  1  2023 HPD Annotation File for Max and Howard_5_30_2023.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users          833 Jun  5  2023 smallGenesFile.csv
-rw-r--r--   1 kumarr9  NIH\Domain Users      5477706 Jun  6  2023 israel_dataset.csv
-rw-r--r--   1 kumarr9  NIH\Domain Users      5477706 Jun  6  2023 israel_dataset.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users      5477706 Jun  6  2023 israel_dataset_log2_tpm_plus1.csv
-rwx------@  1 kumarr9  NIH\Domain Users      4128258 Jun 13  2023 Manan_tpm_normalized_protein_coding_only.tsv
-rwx------@  1 kumarr9  NIH\Domain Users         5545 Jun 14  2023 cluster_heatmap_df.csv
-rw-------@  1 kumarr9  NIH\Domain Users       456773 Jun 15  2023 DLL3_newest.png
-rwx------@  1 kumarr9  NIH\Domain Users      4128258 Jun 16  2023 Manan_data_all.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        32962 Jun 16  2023 liver_data.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         9270 Jun 16  2023 DLL_brain_liver_P1.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       220845 Jun 20  2023 PEPCO Bill.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1365261 Jun 20  2023 Discover-Statement-20230611-6726.pdf
-rw-r-----@  1 kumarr9  NIH\Domain Users       254683 Jun 20  2023 annotation.txt
-rw-------@  1 kumarr9  NIH\Domain Users         7790 Jun 26  2023 consensus_parth_sep11.Rmd
-rw-r--r--@  1 kumarr9  NIH\Domain Users        11103 Jun 26  2023 Copy of autopsy_samples_info.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1419439 Jun 27  2023 brett_df_raw.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users         1125 Jun 28  2023 DESeq2.R
-rw-r--r--@  1 kumarr9  NIH\Domain Users        52675 Jun 28  2023 NLGL3.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1833099 Jun 29  2023 drosphila_example_de.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        60131 Jun 29  2023 KO_Parenal_Hallmark.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        39260 Jun 29  2023 POLR2A.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1041 Jul  5  2023 liver_like_gene_sets.txt
-rw-r--r--   1 kumarr9  NIH\Domain Users         4575 Jul  5  2023 nucleo.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users         2083 Jul  5  2023 GOBP_NUCLEAR_TRANSPORT.v2023.1.Hs.gmt
-rw-------@  1 kumarr9  NIH\Domain Users        41409 Jul  6  2023 HPD Annotation File_7_6_2023_deidentified.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         4095 Jul  6  2023 GSEA.Rmd
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1466438 Jul  6  2023 atri_study_exp_tbl.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       347536 Jul  6  2023 gsea_gene_sets.rds
-rw-------@  1 kumarr9  NIH\Domain Users        10105 Jul  7  2023 Nat_Commun_RNAseq_sample_list_for_Rajesh_20230612.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1071907 Jul  7  2023 ASCO-Caris-2022-Molecular-correlates-of-Delta-like-ligand-3-DLL3-expression-in-neuroendocrine-neoplasms-NENs.pdf
-rw-r-----   1 kumarr9  NIH\Domain Users     76229964 Jul  7  2023 raw_coverages.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users          378 Jul  7  2023 ajit_gene.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       495328 Jul  7  2023 ajit_figure.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users       362467 Jul 10  2023 Mastersheet_NCI THOMAS_352_PD_892022_START.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users        11534 Jul 10  2023 NCI SCLC patients without MRN.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        15165 Jul 11  2023 data1.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users        84130 Jul 11  2023 susovan.jpg
-rw-r--r--@  1 kumarr9  NIH\Domain Users      3940547 Jul 12  2023 Delfin plasma samples hyperprogression autopsy brain mets EGFR prostate .xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users     16239418 Jul 12  2023 Rplot01.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users     16239418 Jul 12  2023 sankey.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users        35810 Jul 13  2023 Author_response_cancer cell_June 2023_AT_PDant.docx
-rw-r-----@  1 kumarr9  NIH\Domain Users    147899007 Jul 13  2023 raw_tmm_fpkm_batch_corrected.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1020469 Jul 13  2023 consensus_plot_mad_new.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1347645 Jul 13  2023 consensus_plot_mad_try.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1173735 Jul 13  2023 consensus_plot_mad_patient_info.png
-rw-r--r--   1 kumarr9  NIH\Domain Users          385 Jul 14  2023 chris_test.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users         1337 Jul 14  2023 deseq_george.R
-rw-r--r--@  1 kumarr9  NIH\Domain Users        10859 Jul 15  2023 scRNA_cell_cluster_count.xlsx
-rwx------@  1 kumarr9  NIH\Domain Users       989703 Jul 17  2023 consensus_plot_DESeq_patient_info_biopsy_new2.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users       364717 Jul 18  2023 PCA_color_new_atac_july18.jpg
-rw-r--r--@  1 kumarr9  NIH\Domain Users      9822673 Jul 19  2023 golub.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       567544 Jul 19  2023 PCA_color_raw_data_july_19.jpg
-rw-r-----@  1 kumarr9  NIH\Domain Users         3232 Jul 20  2023 tmm_fpkm_batch_corrected_annotation.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        23994 Jul 25  2023 Book3.xlsx
-rw-r--r--   1 kumarr9  NIH\Domain Users         2658 Jul 26  2023 all_atac_graph.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users         7387 Jul 26  2023 NCI_thomas_439_df2.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users         8358 Jul 26  2023 NCI_thomas_439.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         9240 Jul 26  2023 NCI_thomas_439_matched.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      2104034 Jul 27  2023 LaTeXTemplates_freeman-cv_v3.0.zip
-rw-r--r--@  1 kumarr9  NIH\Domain Users        98588 Jul 27  2023 NMF.png
-rw-r-----   1 kumarr9  NIH\Domain Users     66207363 Jul 27  2023 NCI_Thomas_439_protein_coding_only_TPM_normalized.tsv
-rw-r-----@  1 kumarr9  NIH\Domain Users         3605 Jul 27  2023 NCI_Thomas_439_batch_info.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       190026 Jul 31  2023 DESeq2_july_31.png
drwx--x--x@  3 kumarr9  NIH\Domain Users           96 Aug  3  2023 Open To Start Support Session.app
drwx--x--x@  3 kumarr9  NIH\Domain Users           96 Aug  3  2023 Open To Start Support Session 2.app
-rw-r--r--   1 kumarr9  NIH\Domain Users      1589742 Aug  4  2023 rsem_gene.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users      1589742 Aug  4  2023 rsem_gene_bkp.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users       516477 Aug  4  2023 rsem_gene_output.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      2173029 Aug  5  2023 Ajit_adheretn_vs_suspension.pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         6032 Aug  8  2023 ATAC_RNA_data.tsv
-rw-r-----   1 kumarr9  NIH\Domain Users     11286210 Aug  8  2023 RNA_subsetted_vinod.tsv
-rw-r-----@  1 kumarr9  NIH\Domain Users      2153207 Aug  8  2023 parental_LMD_Gen1_Gen2.csv
-rw-r-----@  1 kumarr9  NIH\Domain Users          258 Aug  8  2023 parental_LMD_gen1_gen2_metadata.tsv
-rw-r-----@  1 kumarr9  NIH\Domain Users      1122751 Aug  8  2023 raw_count_parental_LMD_Gen1_Gen2.csv
-rw-r-----@  1 kumarr9  NIH\Domain Users          272 Aug  9  2023 parental_LMD_gen1_gen2_metadata_copy.tsv
-rw-r-----@  1 kumarr9  NIH\Domain Users      5501025 Aug 12  2023 RNA_subsetted_TPM.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         6063 Aug 12  2023 RNA_subsetted_ne_score.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1016 Aug 12  2023 second.txt
-rw-r-----@  1 kumarr9  NIH\Domain Users      2606000 Aug 13  2023 RNA.rawcount.subsetted.protein.coding.txt
-rw-r--r--   1 kumarr9  NIH\Domain Users           95 Aug 13  2023 cluster1_2_metadata.cls
-rw-------@  1 kumarr9  NIH\Domain Users        13064 Aug 17  2023 SCCL_gene_list.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         3145 Aug 19  2023 RNA_subsetted_ne_score_august_12.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         3145 Aug 19  2023 RNA_subsetted_ne_score_august_19.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users     92457997 Aug 21  2023 parth_scRNA.zip
-rw-r--r--@  1 kumarr9  NIH\Domain Users        57616 Aug 22  2023 certificate_2023.jpg
-rw-r--r--@  1 kumarr9  NIH\Domain Users     69091031 Aug 23  2023 NCI-SCLC-326-ARACNE-GeneRegNet_new.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users        16118 Aug 25  2023 Clinical_annot_August24_NCI_SCLC.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         9189 Aug 28  2023 Chris_LMNA.xlsx
-rw-r-----   1 kumarr9  NIH\Domain Users      1751612 Aug 28  2023 TPM.count.protein.coding.log2.norm.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        26112 Aug 28  2023 ajit_dataset.xls
-rw-r--r--   1 kumarr9  NIH\Domain Users       529068 Aug 29  2023 chris_LMNA_figure_august_29.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users       741576 Aug 31  2023 ATAC_flow.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        19461 Sep  1  2023 rna.matched.atac.homer.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users      9261388 Sep  1  2023 Knockdown of IGF2BP3 inhibits the tumorigenesis of gallbladder cancer and modifies tumor microenvironment.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        18912 Sep  5  2023 Rajaa_sheet_ATAC.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users      3314234 Sep  5  2023 RA-022_cell_lines_RawCountFile_rsemgenes_log2_TMM_FPKM.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1027551 Sep  5  2023 RA22.protein.coding.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users          533 Sep  5  2023 RA22.ajit_dataset.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       561519 Sep  6  2023 motiffAnalysis-seurat-report.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users      3054544 Sep 12  2023 ATAC_discussion_sep07.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        12759 Sep 13  2023 SCLC_gene_signature_sept13.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users        14632 Sep 13  2023 scRNA_ITH_ATAC_RAJESH project_12092023.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        47929 Sep 13  2023 86918-Free SeeSaw PowerPoint Template.pptx
-rw-------@  1 kumarr9  NIH\Domain Users     21160979 Sep 14  2023 scRNA analysis_PD_September 2023_For ATAC and ITH projects.pptx
-rw-------@  1 kumarr9  NIH\Domain Users     21654968 Sep 14  2023 scRNA analysis_PD_September 2023_For ATAC and ITH projects_Rajeshcorrected_9132023.pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        98948 Sep 15  2023 Tumor_Methylation_Collaborators.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users     66207363 Sep 15  2023 NCI_Thomas_439_protein_coding_only_TPM_normalized (1).tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      8289526 Sep 18  2023 scRNA_sep15.pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        10291 Sep 21  2023 homer_analysis.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       189717 Sep 25  2023 3p-Neutrophils-UMAP-Projection.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        96967 Sep 25  2023 3p-Neutrophils-clusters.csv
-rw-------@  1 kumarr9  NIH\Domain Users       911673 Oct  6  2023 CENPA_genes.pptx
-rw-------@  1 kumarr9  NIH\Domain Users      1048174 Oct  6  2023 CENPA_genes (002).pptx
-rw-r-----@  1 kumarr9  NIH\Domain Users       216165 Oct 11  2023 parental.lmd.bmd.heatmap.others.jpg
-rw-------@  1 kumarr9  NIH\Domain Users       299008 Oct 11  2023 RU1065C_for_heatmap.csv
-rw-r-----@  1 kumarr9  NIH\Domain Users        80545 Oct 12  2023 without_doublets_malignant_only.jpg
-rw-r-----@  1 kumarr9  NIH\Domain Users       516688 Oct 12  2023 feature.heatmap2.jpg
-rw-r-----@  1 kumarr9  NIH\Domain Users       476665 Oct 12  2023 feature.heatmap.jpg
-rw-r-----@  1 kumarr9  NIH\Domain Users       432503 Oct 12  2023 feature.heatmap3.jpg
-rw-r-----@  1 kumarr9  NIH\Domain Users       472750 Oct 12  2023 feature.heatmap4.jpg
-rw-r-----@  1 kumarr9  NIH\Domain Users       486100 Oct 12  2023 feature.heatmap5.jpg
-rw-r-----@  1 kumarr9  NIH\Domain Users       527955 Oct 12  2023 feature.heatmap6.jpg
-rw-r-----@  1 kumarr9  NIH\Domain Users       484673 Oct 12  2023 feature.heatmap7.jpg
-rw-r-----@  1 kumarr9  NIH\Domain Users       526366 Oct 12  2023 feature.heatmap8.jpg
-rw-r-----@  1 kumarr9  NIH\Domain Users       481836 Oct 12  2023 feature.heatmap9.jpg
-rw-r-----   1 kumarr9  NIH\Domain Users       524301 Oct 12  2023 feature.heatmap10.jpg
-rw-r-----@  1 kumarr9  NIH\Domain Users       384581 Oct 12  2023 tumor.cluster.dotplot.jpg
-rw-r-----@  1 kumarr9  NIH\Domain Users       353480 Oct 12  2023 tumor.cluster.dotplot2.jpg
-rw-r-----@  1 kumarr9  NIH\Domain Users       341612 Oct 12  2023 tumor.cluster.dotplot3.jpg
-rw-r-----@  1 kumarr9  NIH\Domain Users        62430 Oct 12  2023 without_doublets_malignant_only.ver.2.jpg
-rw-r-----@  1 kumarr9  NIH\Domain Users       370468 Oct 12  2023 without_doublets.jpg
-rw-r-----@  1 kumarr9  NIH\Domain Users        73469 Oct 12  2023 without_doublets_malignant_only.ver.3.jpg
-rw-r-----   1 kumarr9  NIH\Domain Users      7250396 Oct 12  2023 before_treatment.log2.tpm.1.tsv
-rw-r-----@  1 kumarr9  NIH\Domain Users     16717420 Oct 12  2023 after_treatment.log2.tpm.1.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         2211 Oct 12  2023 before_treatment.log2.tpm.1.NE.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         5174 Oct 12  2023 after_treatment.log2.tpm.1.NE.tsv
-rw-r-----@  1 kumarr9  NIH\Domain Users         1442 Oct 12  2023 before.treatment.NAPY.df.transposed.tsv
-rw-r-----@  1 kumarr9  NIH\Domain Users         3428 Oct 12  2023 after.treatment.NAPY.df.transposed.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        25526 Oct 12  2023 Delfi plasma with RNAseq samples for Rajesh_NE classifications.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       171095 Oct 19  2023 3rdquarter.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        17924 Nov 19  2023 For_parth_new.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users        16212 Nov 20  2023 SCLC_Thomas_RNA_samples.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users       324549 Nov 21  2023 SCLC Mapping Tumor and TME Mastersheet_2062023.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users       156623 Nov 22  2023 SCAF2497_positive_marker_gene_significant.csv
-rw-------@  1 kumarr9  NIH\Domain Users       419165 Nov 22  2023 Addition of Author Request in Schultz et Al. EMBO Molecular Medecine 2023 15-e17313.pdf-RE_DA_ZWO signed (002).pdf
-rw-r--r--   1 kumarr9  NIH\Domain Users         6807 Nov 22  2023 NAPY_targets.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users     14551282 Nov 24  2023 SCLC_ATAC_Sep_27.pptx
-rw-------@  1 kumarr9  NIH\Domain Users     12033342 Nov 28  2023 SCAF2229_cell_cycle_regress_difference_out.rds
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1035601 Nov 28  2023 MISC-Sep-21-2020.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       105890 Nov 28  2023 Form_Pdf_66.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users      2393284 Nov 29  2023 HIM-D-23-01091.pdf
-rw-r-----@  1 kumarr9  NIH\Domain Users        32236 Nov 29  2023 filtered3.tsv
-rw-------@  1 kumarr9  NIH\Domain Users       102146 Nov 29  2023 Master RNA Submission File.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users       486013 Nov 29  2023 Master CHIP Submission File.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users       925147 Nov 29  2023 Master ATAC Submission File.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1333728 Dec  1  2023 Molecular classification of small cell lung cancer subtypes- characteristics, prognostic factors, and clinical translation.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       139301 Dec  4  2023 Open To Start Support Session (1).zip
-rw-------@  1 kumarr9  NIH\Domain Users        10794 Dec  6  2023 data_shared_sheet.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users          589 Dec  7  2023 report-due-date.ics
-rw-r--r--   1 kumarr9  NIH\Domain Users         1288 Dec  8  2023 neuron_genes.txt
-rw-r-----   1 kumarr9  NIH\Domain Users         8335 Dec  8  2023 sclc_genesets_new.gmt
-rw-r-----   1 kumarr9  NIH\Domain Users         8335 Dec  8  2023 sclc_genesets_new.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users     37712257 Dec 11  2023 ScienceDirect_files_11Dec2023_18-18-36.410.zip
-rw-r--r--@  1 kumarr9  NIH\Domain Users        86339 Dec 20  2023 Copy of Copy of cfChiPseq_list_Pt_IDs_NT20230327_PD_editsant (002) Rajesh anon.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        23281 Dec 21  2023 nature_geentics_validation_cohort.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users       158169 Dec 21  2023 ARCHIBUS Web Central.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users      3266889 Dec 22  2023 1-s2.0-S0167779923000884-main.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users     18640047 Dec 27  2023 science.abe1505_tables_s1_to_s17.zip
-rw-------@  1 kumarr9  NIH\Domain Users        13404 Jan  3  2024 1_3_23_RNA_Seq_datasets.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         3093 Jan  4  2024 chris_gsea.tsv
-rw-------@  1 kumarr9  NIH\Domain Users        23466 Jan  4  2024 nature_geentics_validation_cohort_MA unclear samples.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       956838 Jan  4  2024 NKcell.pptx
-rw-r--r--   1 kumarr9  NIH\Domain Users         1646 Jan  4  2024 cross_cor.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users          449 Jan  5  2024 gene_df.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users          442 Jan  5  2024 motif_df.tsv
-rw-r-----   1 kumarr9  NIH\Domain Users      1125719 Jan  5  2024 scRNA_integrated_markers.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       241059 Jan  5  2024 integrated_scRNA.pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        73617 Jan  8  2024 df2.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1786355 Jan  8  2024 df3.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        57177 Jan  8  2024 df1.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users        45583 Jan  8  2024 cluster1_unique.bed
-rw-r--r--   1 kumarr9  NIH\Domain Users        62023 Jan  8  2024 cluster2_unique.bed
-rw-r-----   1 kumarr9  NIH\Domain Users        49341 Jan  8  2024 pdx.rank3.cluster1.motif.txt
-rw-r-----   1 kumarr9  NIH\Domain Users        49055 Jan  8  2024 pdx.rank3.cluster3.motif.txt
-rw-r-----   1 kumarr9  NIH\Domain Users        49575 Jan  8  2024 pdx.rank3.cluster2.motif.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users        11054 Jan 10  2024 motif_calculation.xlsx
-rw-r-----@  1 kumarr9  NIH\Domain Users      2339903 Jan 11  2024 data_integrated_features.jpg
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1030 Jan 11  2024 POU5F1.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       176640 Jan 11  2024 Correlation_justin.xls
-rw-r--r--   1 kumarr9  NIH\Domain Users         2807 Jan 13  2024 survival_3_vs_2.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users         1281 Jan 13  2024 survival_1_vs_2.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        37724 Jan 13  2024 survival.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         3059 Jan 13  2024 survival.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users         3771 Jan 13  2024 survival_multivariate.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         5485 Jan 13  2024 Rajesh_4ob.R
-rw-r--r--@  1 kumarr9  NIH\Domain Users        12964 Jan 13  2024 SPlice_Best.R
-rw-r--r--@  1 kumarr9  NIH\Domain Users        26260 Jan 13  2024 Splice_ML.R
-rw-r--r--@  1 kumarr9  NIH\Domain Users        19390 Jan 13  2024 Splice_Study.R
-rw-r--r--@  1 kumarr9  NIH\Domain Users      8431060 Jan 15  2024 all_paper_combined.pdf
-rw-------@  1 kumarr9  NIH\Domain Users       221696 Jan 16  2024 10_16_23_SCLC_Cell_lines.xlsx
-rw-r--r--   1 kumarr9  NIH\Domain Users         7775 Jan 17  2024 survival_new.tsv
-rw-------@  1 kumarr9  NIH\Domain Users       544123 Jan 17  2024 RSW_Project_V1.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users     15881626 Jan 17  2024 ScienceDirect_files_18Jan2024_00-43-23.252.zip
-rw-r--r--@  1 kumarr9  NIH\Domain Users        25184 Jan 18  2024 survival_new.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users        11749 Jan 18  2024 qpcr.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users    790389064 Jan 18  2024 rat.ss.LV.RNA.cluster.rds
-rw-r--r--@  1 kumarr9  NIH\Domain Users    420349214 Jan 18  2024 mouse.LV.RNA.cluster.rds
-rw-r--r--@  1 kumarr9  NIH\Domain Users        94385 Jan 22  2024 Dilli-chalo.jpg
-rw-------@  1 kumarr9  NIH\Domain Users       450969 Jan 22  2024 SCAF2326_cell.png
-rw-------@  1 kumarr9  NIH\Domain Users        13279 Jan 23  2024 AU_21_162_INFO.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users       107105 Jan 24  2024 metadata_SCLC_new.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users     13751913 Jan 24  2024 RNAseq from ClinOmics.xlsx
-rw-r--r--   1 kumarr9  NIH\Domain Users     31955364 Jan 25  2024 raw_counts.featureCounts.txt
-rw-------@  1 kumarr9  NIH\Domain Users      4870852 Jan 26  2024 ThomasProject_expression.count.zip
-rw-rw-r--@  1 kumarr9  NIH\Domain Users     13981049 Jan 27  2024 ThomasProject_expression.count.tsv
-rw-------@  1 kumarr9  NIH\Domain Users       128117 Jan 27  2024 metadata_SCLC.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         7974 Jan 28  2024 metadata_piyush.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users     25409797 Jan 28  2024 New_BRCA_matrix.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       489583 Jan 28  2024 SCAF2326.pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1943 Jan 29  2024 surv.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users          464 Jan 30  2024 latency.tsv
-rw-r-----@  1 kumarr9  NIH\Domain Users         4993 Jan 30  2024 cluster1_signature.tsv
-rw-r-----@  1 kumarr9  NIH\Domain Users        12836 Jan 30  2024 cluster2_signature.tsv
-rw-r-----@  1 kumarr9  NIH\Domain Users         8325 Jan 30  2024 cluster3_signature.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users         1370 Jan 30  2024 survival_new_jan_30.tsv
-rw-r-----   1 kumarr9  NIH\Domain Users     21063568 Jan 30  2024 SCAF2326_cell_cycle_regress_difference_out_resolution_1.rds
-rw-r--r--@  1 kumarr9  NIH\Domain Users        32489 Jan 30  2024 survival_new_jan_30.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users        11011 Jan 30  2024 Gene_signature_new.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        11011 Jan 30  2024 Gene_signature.xlsx
-rw-r--r--   1 kumarr9  NIH\Domain Users          134 Jan 30  2024 gene_list.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users          227 Jan 31  2024 cluster2_top_motif.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users          209 Jan 31  2024 cluster3_top_motif.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         2526 Jan 31  2024 integrated_cell.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users         1692 Jan 31  2024 integrated_cell_2.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         4652 Jan 31  2024 cell_types.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users         1871 Jan 31  2024 cell_type_graph.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users          898 Jan 31  2024 cell_type_graph_2.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users          646 Jan 31  2024 integrated_cell_3.tsv
-rw-r-----   1 kumarr9  NIH\Domain Users        12313 Jan 31  2024 cluster2_target_genes.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users          233 Jan 31  2024 anno.tsv
-rw-r-----   1 kumarr9  NIH\Domain Users        11688 Jan 31  2024 cluster3_target_genes.tsv
-rw-r-----   1 kumarr9  NIH\Domain Users        12108 Jan 31  2024 cluster1_target_genes.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        81306 Jan 31  2024 ARACNe_TF_motifs.xlsx
-rw-r--r--   1 kumarr9  NIH\Domain Users        10305 Feb  1  2024 cluster2_all.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users         3522 Feb  1  2024 cluster3_all.tsv
-rw-------@  1 kumarr9  NIH\Domain Users       525577 Feb  1  2024 Integrated_scRNA_FOR ATAC Project_Rajesh_PD.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users      1506858 Feb  1  2024 Integrated object_scRNA_for ATAC project_Rajesh_PD.pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users     32852585 Feb  2  2024 Keka-1.3.7.dmg
-rw-r--r--@  1 kumarr9  NIH\Domain Users    382658676 Feb  2  2024 RStudio-2023.12.1-402.dmg
-rw-r--r--@  1 kumarr9  NIH\Domain Users    230331666 Feb  2  2024 Cytoscape_3_10_1_macos_aarch64.dmg
-rw-r--r--@  1 kumarr9  NIH\Domain Users    284459866 Feb  2  2024 mendeley-reference-manager-2.109.0-x64.dmg
-rw-r--r--@  1 kumarr9  NIH\Domain Users        10560 Feb  3  2024 ATOH1.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        13885 Feb  3  2024 validation_cohort_uniform.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1534213 Feb  4  2024 signature.png
drwxrwxrwx@  3 kumarr9  NIH\Domain Users           96 Feb  5  2024 GSEA_4.3.3 3.app
drwxrwxrwx@  3 kumarr9  NIH\Domain Users           96 Feb  5  2024 GSEA_4.3.3 2.app
-rw-r--r--@  1 kumarr9  NIH\Domain Users     16792661 Feb  5  2024 Thomas_RNASeq_log2_TMM_FPKM_for_cfCHiPseq_20210616.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        99482 Feb  5  2024 AsynonymousTSS_clinical_characteristics_updated_20210803.xlsx
-rw-r--r--   1 kumarr9  NIH\Domain Users          345 Feb  6  2024 stem_cell_no.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users          606 Feb  6  2024 percentage_file.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        42297 Feb  7  2024 UMD_cover_letter.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        41643 Feb  8  2024 survival_analysis.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1236 Feb  9  2024 TGFB_UP.V1_UP.v2023.2.Hs.gmt
-rw-r--r--@  1 kumarr9  NIH\Domain Users          620 Feb  9  2024 KEGG_TGF_BETA_SIGNALING_PATHWAY.v2023.2.Hs.gmt
-rw-r--r--@  1 kumarr9  NIH\Domain Users     20420077 Feb  9  2024 NIHMS1002246-supplement-4.pdf
-rw-r--r--   1 kumarr9  NIH\Domain Users          159 Feb  9  2024 cluster15.txt
-rw-r--r--   1 kumarr9  NIH\Domain Users          460 Feb  9  2024 cluster15_all.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users       443075 Feb 11  2024 sciB_vrdl_nm007056_MSc1.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1411 Feb 12  2024 test_data.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users          808 Feb 12  2024 test_data_2.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       190047 Feb 12  2024 1-s2.0-S0092867423013351-mmc6.xlsx
-rw-r-----@  1 kumarr9  NIH\Domain Users      5481519 Feb 14  2024 Cellchat_R_4.3.ipynb
-rw-------@  1 kumarr9  NIH\Domain Users       130627 Feb 15  2024 metadata_SCLC _with diagnosis_MLA.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users     15950872 Feb 15  2024 mmc3.xlsx
-rw-r-----@  1 kumarr9  NIH\Domain Users         3560 Feb 17  2024 ATAC_cluster_sig_ssGSEA.tsv
-rw-r-----@  1 kumarr9  NIH\Domain Users         3560 Feb 17  2024 ATAC_cluster_sig_ssGSEA.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users          352 Feb 18  2024 cluster2.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1042 Feb 18  2024 cluster3.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1530 Feb 18  2024 boxplot.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users           87 Feb 18  2024 mean_exp.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users           87 Feb 18  2024 mean_exp_cp.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1337647 Feb 21  2024 Discover-Statement-20240218-2036.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        16654 Feb 22  2024 all_tar_files.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       917799 Feb 23  2024 Rajesh_Slide.pptx
-rw-r--r--   1 kumarr9  NIH\Domain Users          266 Feb 23  2024 ensemble.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users          137 Feb 23  2024 ensemble_cp.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       586835 Feb 23  2024 preprints202401.1989.v1.pdf
-rw-------@  1 kumarr9  NIH\Domain Users      7009082 Feb 25  2024 SCLC.html
-rw-------@  1 kumarr9  NIH\Domain Users      7911407 Feb 25  2024 SCLC_240221.html
-rw-------@  1 kumarr9  NIH\Domain Users        56665 Feb 25  2024 Cluster_1_2_3_relaxed.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        32624 Feb 26  2024 1708955629381SR4BdZw05tqgahM0.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users     28999338 Feb 27  2024 ScienceDirect_files_27Feb2024_14-59-38.952.zip
-rw-r--r--@  1 kumarr9  NIH\Domain Users     26582196 Feb 28  2024 GSM2550011_RKO_c0011_w0053.CEL.gz
-rw-r--r--@  1 kumarr9  NIH\Domain Users       469619 Feb 28  2024 GSM2550011_RKO_c0011_w0053.sst-rma-gene-full.chp.gz
-rw-r--r--@  1 kumarr9  NIH\Domain Users      2804810 Feb 28  2024 GSM2550011_RKO_c0011_w0053.sst-rma-gene-full.chp
-rw-r--r--@  1 kumarr9  NIH\Domain Users     69354683 Feb 28  2024 GSM2550011_RKO_c0011_w0053.CEL
-rw-r--r--@  1 kumarr9  NIH\Domain Users       555180 Feb 28  2024 HAP1 RNAseq Normalized reads.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        10866 Feb 28  2024 IHC_Rajaa.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users          460 Mar  1  2024 REACTOME_REGULATED_NECROSIS.v2023.2.Hs.gmt
-rw-r--r--@  1 kumarr9  NIH\Domain Users   2235239687 Mar  4  2024 Unconfirmed 852599.crdownload
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1676 Mar  5  2024 rank3.pdx.cluster3_GO.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         3356 Mar  5  2024 rank3.pdx.cluster1_GO.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1808 Mar  5  2024 rank3.pdx.cluster1_GO_top_10.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         3264 Mar  5  2024 rank3.pdx.cluster2_GO.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         2444 Mar  5  2024 rank3.pdx.cluster2_GO_sig.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users     11301101 Mar  5  2024 RKO_293T_HAP1 RNAseq raw counts.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users    154791479 Mar  6  2024 ScienceDirect_files_06Mar2024_16-16-33.280.zip
-rw-r--r--@  1 kumarr9  NIH\Domain Users     12140756 Mar  7  2024 Functional_characterization_ATOH_Indicate_metastastic_role_SCLC.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users         9926 Mar  7  2024 Samples for spatial transcriptomics.xlsx
-rw-r-----@  1 kumarr9  NIH\Domain Users        26236 Mar  8  2024 boundless_bio_data_transferred.txt
-rw-r-----@  1 kumarr9  NIH\Domain Users       103905 Mar  8  2024 boundless_bio_data_transferred_RNA.txt
-rw-------@  1 kumarr9  NIH\Domain Users        73431 Mar  8  2024 Biowulf_Collaborators_MNAnnotated.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users     12836351 Mar 16  2024 drive-download-20240317T020552Z-001.zip
-rw-r--r--@  1 kumarr9  NIH\Domain Users       421359 Mar 16  2024 alrification.pdf
drwxr-xr-x@  3 kumarr9  NIH\Domain Users           96 Apr 15  2024 FileZilla 2.app
-rw-r--r--@  1 kumarr9  NIH\Domain Users        65777 Apr 19  2024 signature_table.tsv
-rw-r-----@  1 kumarr9  NIH\Domain Users         3251 Apr 22  2024 ATAC_cluster_sig_ssGSEA_2.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         5580 Apr 22  2024 ATAC_cluster_sig_ssGSEA_anno.tsv
-rw-------@  1 kumarr9  NIH\Domain Users        14998 Apr 23  2024 Copy of Metadata_For_Parth.xlsx
-rw-r--r--   1 kumarr9  NIH\Domain Users        12070 Apr 24  2024 cluster2_chromvar_TF.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users        13279 Apr 24  2024 cluster1_chromvar_TF.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users        13319 Apr 24  2024 cluster3_chromvar_TF.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        51849 Apr 24  2024 cluster_1_2_3_cell_line_chromvar_TF.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        10823 Apr 24  2024 nonNE_vs_SCLC.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        18589 Apr 24  2024 nonNE_vs_others.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users        10801 Apr 24  2024 nonNE_vs_SCLC_transposed.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users        18555 Apr 24  2024 nonNE_vs_others_transposed.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      2955370 Apr 24  2024 cell_line_TF.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        13335 Apr 25  2024 Nabet_parth.tsv
-rw-------@  1 kumarr9  NIH\Domain Users         2912 Apr 25  2024 Nabet_parth_cell_line_anno.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users    101603542 Apr 26  2024 Mendeley-Desktop-1.19.3-OSX-Universal.dmg
-rw-r--r--@  1 kumarr9  NIH\Domain Users        12534 Apr 26  2024 metadata_for_kelley.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users      8695335 Apr 29  2024 bomgar-scc-w05c30wfx5w8xeix7xexx5jgz1jhyg5zfxeegdc40jc90.dmg
-rw-r--r--@  1 kumarr9  NIH\Domain Users          693 Apr 30  2024 appointment.ics
-rw-r--r--@  1 kumarr9  NIH\Domain Users          689 Apr 30  2024 appointment_tomorrow.ics
-rw-------@  1 kumarr9  NIH\Domain Users       123435 Apr 30  2024 NIH_file_prefixes_2024-03-20_V1_Collaborators.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        11448 Apr 30  2024 Nabet_parth_updated.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users         3212 Apr 30  2024 updated
-rw-r--r--@  1 kumarr9  NIH\Domain Users     20656844 May  2  2024 Spatial_cell_reports_medicine.zip
-rw-r--r--@  1 kumarr9  NIH\Domain Users        18755 May  2  2024 cell_line_pdx_new.pdf
-rw-------@  1 kumarr9  NIH\Domain Users      4504938 May  2  2024 george_final.txt
-rw-------@  1 kumarr9  NIH\Domain Users      4504938 May  2  2024 george_final_may02_2024.txt
-rw-------@  1 kumarr9  NIH\Domain Users         5708 May  6  2024 pdx_rank3_metadata.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users     14008641 May  8  2024 FileZilla_3.67.0_macos-arm64.app.tar.bz2
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1126673 May  8  2024 home.docx
-rw-------@  1 kumarr9  NIH\Domain Users       668806 May  9  2024 lates_figure.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users       723230 May  9  2024 chiori_KIF18A.pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users     26119169 May  9  2024 HP_Color_LaserJet_Pro_MFP_M282_M285_Series-20231206.dmg
-rw-r--r--@  1 kumarr9  NIH\Domain Users    527151410 May  9  2024 ATAC_Fig_Draft_May_09_2024.pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        29950 May 10  2024 cluster3_motif_name.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        29537 May 10  2024 cluster2_motif_name.tsv
-rw-------@  1 kumarr9  NIH\Domain Users       132552 May 13  2024 GEO submission_RNAseq_Proteomic.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users   2824099636 May 13  2024 A406a_ATAC_S0_L001_R1_001.fastq.gz
-rw-r--r--@  1 kumarr9  NIH\Domain Users  13839870745 May 13  2024 A406a_ATAC_S0_L001_R1_001.fastq
-rw-------@  1 kumarr9  NIH\Domain Users      8761773 May 14  2024 Cancer research_Notch mutant GEMM.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users         3212 May 14  2024 Nabet_parth_cell_line_anno_updated.csv
-rw-r--r--   1 kumarr9  NIH\Domain Users     28804134 May 14  2024 ccle_cell_line_custom_color.tiff
-rw-------@  1 kumarr9  NIH\Domain Users       409743 May 14  2024 OF306.pdf
-rw-------@  1 kumarr9  NIH\Domain Users         5091 May 14  2024 ATAC_PDXmatch_Rajesh_PD_Signatures_2.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users     24494437 May 15  2024 example_input.zip
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1319 May 15  2024 normalization_script.zip
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1317 May 15  2024 download.ics
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1317 May 15  2024 download (1).ics
-rw-------@  1 kumarr9  NIH\Domain Users       201475 May 16  2024 aws_cli_install_and_upload_instructions.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       272939 May 16  2024 WGS_boundless_bio_data_transferred_WGS_alone.txt
-rw-r--r--   1 kumarr9  NIH\Domain Users         1048 May 17  2024 test_script.sh
-rw-------@  1 kumarr9  NIH\Domain Users        20083 May 17  2024 all_bam.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users        15672 May 17  2024 leave.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        65503 May 17  2024 OIG4..jpeg
-rw-r--r--@  1 kumarr9  NIH\Domain Users        81439 May 18  2024 just_breathe.jpeg
-rw-r--r--@  1 kumarr9  NIH\Domain Users        63063 May 18  2024 counseling.jpeg
-rw-r--r--@  1 kumarr9  NIH\Domain Users        16086 May 18  2024 teaching.jpeg
-rw-r--r--@  1 kumarr9  NIH\Domain Users        24355 May 18  2024 guidance.jpeg
-rw-r-----   1 kumarr9  NIH\Domain Users     69643989 May 20  2024 NCI_Thomas_429_raw_count.csv
-rw-------@  1 kumarr9  NIH\Domain Users      1018708 May 23  2024 RNAseq_variable_genes_heatmap.pdf _ Powered by Box.html
-rw-------@  1 kumarr9  NIH\Domain Users      1520686 May 23  2024 promoter_top1.tiff
-rw-------@  1 kumarr9  NIH\Domain Users      1571324 May 23  2024 promoter_top2.tiff
-rw-------@  1 kumarr9  NIH\Domain Users      1570862 May 23  2024 promoter_top_1000.tiff
-rw-------@  1 kumarr9  NIH\Domain Users      1650150 May 23  2024 promoter_top_2000.tiff
-rw-------@  1 kumarr9  NIH\Domain Users      1575570 May 23  2024 distal_science_top1.tiff
-rw-------@  1 kumarr9  NIH\Domain Users      1562122 May 23  2024 distal_science_top2.tiff
-rw-------@  1 kumarr9  NIH\Domain Users      1592788 May 23  2024 distal_science_top_150.tiff
-rw-------@  1 kumarr9  NIH\Domain Users      1643208 May 23  2024 distal_science_top_300.tiff
-rw-------@  1 kumarr9  NIH\Domain Users      1644916 May 23  2024 distal_chipseeker_top1.tiff
-rw-------@  1 kumarr9  NIH\Domain Users      1637318 May 23  2024 distal_chipseeker_top2.tiff
-rw-------@  1 kumarr9  NIH\Domain Users      1580982 May 23  2024 distal_chipseeker_top_4000.tiff
-rw-------@  1 kumarr9  NIH\Domain Users      1580982 May 23  2024 distal_chipseeker_top_5000.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users         6633 May 23  2024 consensusmatrix.tsv
-rw-------@  1 kumarr9  NIH\Domain Users         9741 May 24  2024 Fig4C_tumor_SOI_data2.txt
-rw-------@  1 kumarr9  NIH\Domain Users         2153 May 24  2024 Fig4C_heatmap.Rmd
-rw-------@  1 kumarr9  NIH\Domain Users         3434 May 24  2024 AllDataWTA.meta.new.tumor_only.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users     37506406 May 29  2024 ijms-23-03369.pdf
-rw-------@  1 kumarr9  NIH\Domain Users         2139 May 29  2024 tf_target.rds
-rw-------@  1 kumarr9  NIH\Domain Users        28351 May 29  2024 hallmark.rds
-rw-------@  1 kumarr9  NIH\Domain Users         1038 May 29  2024 Stemcell_genesets.csv
-rw-------@  1 kumarr9  NIH\Domain Users        15387 May 29  2024 NOTCH_genesets.csv
-rw-------@  1 kumarr9  NIH\Domain Users        41604 May 29  2024 IMPOWER_gene sets.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users        65359 May 29  2024 Archetype_signatures_ssGSEA.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      9561572 May 31  2024 cell_paper.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users      4034983 May 31  2024 May31_NEC_subtype.pptx
-rw-r--r--   1 kumarr9  NIH\Domain Users         1059 Jun  3  2024 peak1.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users         1050 Jun  3  2024 peak2.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users         1069 Jun  3  2024 peak3.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1104254 Jun  3  2024 clusters_sig_df.tsv
-rw-r-----@  1 kumarr9  NIH\Domain Users       276583 Jun  3  2024 WGS_boundless_bio_data_transferred.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users         7711 Jun  4  2024 rna_cluster_sig_diff_terms.csv
-rw-r--r--   1 kumarr9  NIH\Domain Users       292812 Jun  5  2024 clstr1.immune.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users       292043 Jun  5  2024 clstr2.immune.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users       294164 Jun  5  2024 clstr3.immune.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1740 Jun  5  2024 clstr2.immune.deenriched.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         6377 Jun  5  2024 cluster1_2_3_NES_immune_C7_Msigdb.tsv
-rw-------@  1 kumarr9  NIH\Domain Users         2139 Jun  6  2024 tf_target[35].rds
-rw-------@  1 kumarr9  NIH\Domain Users       125330 Jun  6  2024 signature_hypoxia_geneset.numbers
-rw-------@  1 kumarr9  NIH\Domain Users         3109 Jun  6  2024 segal_adult_fetal_hepatobiliary.rds
-rw-------@  1 kumarr9  NIH\Domain Users         1204 Jun  6  2024 human_protein_liver.rds
-rw-------@  1 kumarr9  NIH\Domain Users        28351 Jun  6  2024 hallmark[35].rds
-rw-------@  1 kumarr9  NIH\Domain Users          606 Jun  6  2024 dhimolea_diapause_100_up.rds
-rw-------@  1 kumarr9  NIH\Domain Users          216 Jun  6  2024 cell_cycle_score_genes.txt
-rw-------@  1 kumarr9  NIH\Domain Users         1038 Jun  6  2024 Stemcell_genesets[56].csv
-rw-------@  1 kumarr9  NIH\Domain Users        15387 Jun  6  2024 NOTCH_genesets[66].csv
-rw-------@  1 kumarr9  NIH\Domain Users        41604 Jun  6  2024 IMPOWER_gene sets[26].xlsx
-rw-------@  1 kumarr9  NIH\Domain Users          964 Jun  6  2024 HALLMARK_MYC_TARGETS_V1.rds
-rw-------@  1 kumarr9  NIH\Domain Users         8911 Jun  6  2024 Gavish_malignant_cell_MP.rds
-rw-------@  1 kumarr9  NIH\Domain Users          251 Jun  6  2024 CCP_Cuzick.rds
-rw-------@  1 kumarr9  NIH\Domain Users        65359 Jun  6  2024 Archetype_signatures_ssGSEA[56].csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1700 Jun  7  2024 rna_cluster_sig_diff_terms_new_2.csv
-rw-r-----   1 kumarr9  NIH\Domain Users        10812 Jun 10  2024 transferred_2.txt
-rw-r--r--   1 kumarr9  NIH\Domain Users         4745 Jun 10  2024 ATAC_PDXmatch_Rajesh_PD_Signatures_2_new.txt
-rwx------@  1 kumarr9  NIH\Domain Users     16435505 Jun 10  2024 TPMcalc_zscored.tsv
-rw-r-x---@  1 kumarr9  NIH\Domain Users      5728575 Jun 10  2024 TPMcalc_rawCounts.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      3611827 Jun 10  2024 ccle_cell_line_protein_coding_genes.tsv
-rw-------@  1 kumarr9  NIH\Domain Users         3272 Jun 10  2024 ccle_cell_line_metadata.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       100560 Jun 10  2024 CCLE_DGE_result.csv
-rw-r-----@  1 kumarr9  NIH\Domain Users        48690 Jun 10  2024 h.all.v2023.2.Hs.symbols.gmt
-rw-r-----@  1 kumarr9  NIH\Domain Users         1039 Jun 11  2024 dataframe_enriched_term.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        14603 Jun 13  2024 41586_2020_2922_MOESM3_ESM.xlsx
-rw-r-----   1 kumarr9  NIH\Domain Users       655518 Jun 14  2024 TPM.count.protein.coding.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         2979 Jun 14  2024 rna_cluster_sig_diff_terms_new.csv
-rw-------@  1 kumarr9  NIH\Domain Users         3409 Jun 17  2024 Nabet_parth_cell_line_anno_updated_new.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users     95048086 Jun 18  2024 ATAC_signature_cell_line.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users      6327404 Jun 18  2024 NIHMS1641013-supplement-1.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users     95048086 Jun 18  2024 ATAC_signature_cell_line_try.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users       679908 Jun 18  2024 transcriptomics_and_sequencing_analysis_of_gene.6.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users     95048086 Jun 19  2024 ATAC_signature_cell_line_second_list.tiff
-rw-------@  1 kumarr9  NIH\Domain Users         3212 Jun 19  2024 Nabet_parth_cell_line_anno_updated.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users     28804134 Jun 19  2024 ccle_cell_line_custom_color_new_today_2.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users        12286 Jun 19  2024 CCLE_gsea.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users     22683614 Jun 20  2024 CCLE_test.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users        10784 Jun 20  2024 rajesh_paper_citations.csv
-rw-r--r--   1 kumarr9  NIH\Domain Users        15604 Jun 20  2024 publication.bib
-rw-r--r--@  1 kumarr9  NIH\Domain Users          540 Jun 20  2024 publication.csv
-rw-------@  1 kumarr9  NIH\Domain Users    166942534 Jun 24  2024 Ajit_parental_vs_animal.pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         3302 Jun 25  2024 CCLE_gsea_new.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users     12603014 Jun 25  2024 CCLE_test_new.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1617 Jun 26  2024 AXL.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1518 Jun 26  2024 AXL_cp.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users     15419033 Jun 26  2024 FileZilla_3.67.0_macos-x86.app.tar.bz2
-rw-r--r--   1 kumarr9  NIH\Domain Users         1126 Jun 26  2024 AXL_cp_new.tsv
-rw-------@  1 kumarr9  NIH\Domain Users      6326441 Jul  1  2024 PILOT_RNA_Seq_Tumor_Data.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users         2368 Jul  2  2024 PILOT_RNA_Seq_Tumor_Data_ssGSEA.tsv
-rw-------@  1 kumarr9  NIH\Domain Users        12669 Jul  2  2024 SubtypeData Bretts trial.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        15878 Jul  2  2024 mmerged_TGFBR1.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        15883 Jul  2  2024 mmerged_BAX.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       734251 Jul  5  2024 TGFBR_expression.pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1985 Jul  5  2024 Msigdb_STEM_CELLS_BUSSLINGER.v2023.2.Hs .gmt
-rw-r--r--   1 kumarr9  NIH\Domain Users          525 Jul  5  2024 stem_cell_related.gmt
-rw-r--r--@  1 kumarr9  NIH\Domain Users        68746 Jul  8  2024 parth_NES.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1389 Jul  8  2024 Parth_NES_signature.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        79724 Jul  8  2024 parth_NES_new.png
-rw-r--r--   1 kumarr9  NIH\Domain Users         1419 Jul  8  2024 TWIST1.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       138842 Jul  8  2024 webR-shiny-blog.png
-rw-r--r--   1 kumarr9  NIH\Domain Users         3911 Jul  9  2024 NFKB_all.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       170244 Jul  9  2024 NFKB_all.png
-rw-r--r--   1 kumarr9  NIH\Domain Users        96676 Jul  9  2024 FDA_aproved_drug_signature.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users    288021414 Jul  9  2024 FDA_approved_common.tiff
-rw-r--r--   1 kumarr9  NIH\Domain Users      1268807 Jul  9  2024 TTD_database.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users    144011814 Jul 10  2024 TTD.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users    288021414 Jul 10  2024 DepMap.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users         9636 Jul 10  2024 depmaplong_data.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users     59408666 Jul 11  2024 DepMap_subset.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users      9002790 Jul 11  2024 DepMap_subset_Figure_6.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users        54182 Jul 11  2024 DepMap_ssGSEA_KEGG_WNT_Priya.tsv
-rw-r-----@  1 kumarr9  NIH\Domain Users         8206 Jul 11  2024 DepMap_ssGSEA_KEGG_WNT_Priya_NE_only.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users     28804062 Jul 12  2024 ccle_cell_line_custom_color_new_today.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users        31348 Jul 15  2024 Agenda this week.docx
-rw-r--r--   1 kumarr9  NIH\Domain Users        25946 Jul 15  2024 TPMcalc_zscorednorm_parth_gene_transposed.tsv
-rw-r-----@  1 kumarr9  NIH\Domain Users        26148 Jul 15  2024 TPMcalc_zscorednorm_parth_gene.tsv
-rw-------@  1 kumarr9  NIH\Domain Users      1173900 Jul 16  2024 GSM3165679_H1048_POU2F3_CHIP_peaks_filtered.score.gt.500.log.q.gt.20.narrowPeak
-rw-------@  1 kumarr9  NIH\Domain Users      3930758 Jul 16  2024 ASCL1.n.NEUROD1.chipSeq.TFBS.Borromeo.2016.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users      1580439 Jul 16  2024 YAP1.chipSeqPks.3.cell.lines.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users         9824 Jul 17  2024 cell_line_NFKB.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       192695 Jul 18  2024 ChEA_2022_table.txt
-rw-------@  1 kumarr9  NIH\Domain Users        21688 Jul 20  2024 CSEMLabGuidelines2021WELCOME LETTER.docx
-rw-------@  1 kumarr9  NIH\Domain Users        11216 Jul 26  2024 LabWorks.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users         8915 Jul 27  2024 md5value_duplicate_check_august_07.csv
-rw-------@  1 kumarr9  NIH\Domain Users         8915 Jul 27  2024 md5value_duplicate_check.csv
-rw-------@  1 kumarr9  NIH\Domain Users       149504 Jul 30  2024 immunecells Validation cohort.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users        31090 Jul 30  2024 Finallexapansion.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         3309 Jul 31  2024 gProfiler_hsapiens_7-31-2024_12-34-06 PM.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         5545 Jul 31  2024 gProfiler_hsapiens_7-31-2024_12-35-34 PM.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         8562 Jul 31  2024 gProfiler_hsapiens_7-31-2024_12-36-13 PM.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         4578 Jul 31  2024 gProfiler_hsapiens_7-31-2024_12-51-39 PM.csv
-rw-------@  1 kumarr9  NIH\Domain Users        12211 Aug  3  2024 TFBSPILOT.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      3910846 Aug  4  2024 sdbbootcampletters of recommend.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       130489 Aug  4  2024 Sample-Letters-of-Recommendation.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users      5474530 Aug  4  2024 sdbbootcampletters of recommend.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       211481 Aug  5  2024 NIH Information Security and Management Awareness Refresher.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        11664 Aug  5  2024 TFBSPILOT.tsv
-rw-------@  1 kumarr9  NIH\Domain Users       109026 Aug  5  2024 phs003628_NT20240712_RK.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users       110592 Aug  6  2024 15-C-0145 Dates added- 7-31-24.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users        62976 Aug  6  2024 Example for Rajesh.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        35071 Aug  6  2024 15_c_0145.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      4535097 Aug  6  2024 science.abe1505.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        16885 Aug  7  2024 tongwu_data_file.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users    443664125 Aug  7  2024 Copy of ATAC_Fig_Draft_May_09_2024_PD3_june9_2024.pptx
-rw-------@  1 kumarr9  NIH\Domain Users       724105 Aug  8  2024 DepMap-Clusters_vs_Dependencies.pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users    260382345 Aug  8  2024 ENCFF231FNI.bigWig
-rw-r--r--@  1 kumarr9  NIH\Domain Users    508672748 Aug  8  2024 ENCFF012XAP.bigWig
-rw-r--r--@  1 kumarr9  NIH\Domain Users        10942 Aug  8  2024 diffbind.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       285218 Aug  9  2024 mountains-190055_1280.jpg
-rw-r--r--@  1 kumarr9  NIH\Domain Users         6613 Aug 13  2024 FATSQ_missing_paired_Information.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users          631 Aug 13  2024 tong.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       176232 Aug 13  2024 Supplementary_Data.pdf
-rw-r--r--   1 kumarr9  NIH\Domain Users           52 Aug 13  2024 FRA21.bed
-rw-r--r--   1 kumarr9  NIH\Domain Users         5386 Aug 14  2024 tong_flowcell.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users          562 Aug 14  2024 tong_other_flowcell.tsv
-rw-------@  1 kumarr9  NIH\Domain Users         6537 Aug 14  2024 FASTQ_missing_paired_information.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users    169934351 Aug 14  2024 macs_peak_homer_annot.zip
-rw-r--r--   1 kumarr9  NIH\Domain Users         8510 Aug 14  2024 Flowcell_H3M7HDSX2.tsv
-rw-------@  1 kumarr9  NIH\Domain Users         3624 Aug 15  2024 tumor_normal_paired_check.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        10869 Aug 23 15:24 DMS273.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users        34055 Aug 28 13:51 sclc_ucologne_2015_clinical_data (5).tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       164178 Aug 28 15:30 WhatsApp Image 2024-08-28 at 3.28.48 PM.jpeg
-rw-------@  1 kumarr9  NIH\Domain Users        16802 Aug 29 12:15 khanproc_fastq.swarm
-rw-------@  1 kumarr9  NIH\Domain Users     26139039 Aug 29 12:33 Supplementary figures- Chromothripsis.pdf
-rwx------@  1 kumarr9  NIH\Domain Users     52635465 Aug 30 16:44 DMS273_137_met_18Ac.seacr.consensus.peak_counts.bed
-rw-r--r--@  1 kumarr9  NIH\Domain Users     72403584 Sep  3 15:24 IGV_MacApp_2.18.2_WithJava.zip
-rw-r--r--@  1 kumarr9  NIH\Domain Users      2926753 Sep  5 09:03 Chipseq.pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        45398 Sep  5 15:39 aug_Advertisment_for_the_post_of_Deputy_Scientific_Officer.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users     28806810 Sep 10 10:25 ccle_cell_line_custom_color_new.tiff
-rw-r-----   1 kumarr9  NIH\Domain Users     52450848 Sep 10 11:34 content.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1097156 Sep 10 11:34 content.txt.zip
-rw-r--r--   1 kumarr9  NIH\Domain Users        14914 Sep 10 11:56 samplesheet.csv
-rw-r-----@  1 kumarr9  NIH\Domain Users        15368 Sep 10 13:43 combined_fastq_info.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users     48041381 Sep 12 20:19 reiboot-mac_11726185967413801301.dmg
-rw-r--r--@  1 kumarr9  NIH\Domain Users    291523996 Sep 12 20:50 iTunes12.8.3.dmg
-rw-r--r--@  1 kumarr9  NIH\Domain Users        48379 Sep 13 17:32 HNF1A.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        52312 Sep 13 17:33 HNF4A.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        45303 Sep 13 17:34 DLL3_new.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        48261 Sep 13 17:34 HES1.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        59069 Sep 13 17:37 ASCL1.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users      4103254 Sep 14 14:58 Advertisement Details (1).pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users      8021423 Sep 14 14:59 Advertisement Details.pdf
-rw-r--r--   1 kumarr9  NIH\Domain Users        17372 Sep 19 12:49 NFKB1.png
-rw-r--r--   1 kumarr9  NIH\Domain Users        17514 Sep 19 12:49 RELA.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        45115 Sep 19 13:50 all_consensus_peaks.png
-rwx------   1 kumarr9  NIH\Domain Users     95079091 Sep 19 15:37 DMS273_137_met_27Ac.seacr.consensus.peak_counts.bed
-rw-r--r--   1 kumarr9  NIH\Domain Users     18098153 Sep 19 15:39 DMS273_137_met_27Ac.bed
-rw-r--r--   1 kumarr9  NIH\Domain Users     10065915 Sep 19 15:39 DMS273_137_met_18Ac.bed
-rw-r--r--@  1 kumarr9  NIH\Domain Users       115700 Sep 19 16:04 mqc_21_fragment_lengths.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        87904 Sep 19 16:58 fragment length.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        59165 Sep 19 16:58 no of peak per sample.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        81472 Sep 20 11:17 DLL3.png
-rw-r--r--   1 kumarr9  NIH\Domain Users        81718 Sep 20 11:23 ALDOB.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users     35309263 Sep 20 13:17 figeno-1.4.0.tar.gz
-rw-r--r--@  1 kumarr9  NIH\Domain Users     79342410 Sep 20 15:01 DLL3.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users     79342410 Sep 20 15:11 HNF1A.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users     79342410 Sep 20 15:18 FOXA1.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users     79342410 Sep 20 15:23 FOXA3.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users     79342410 Sep 20 15:25 ALDOB.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users     79342410 Sep 20 15:29 ALB.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users     79342410 Sep 20 15:33 HES1.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users     79350650 Sep 20 15:40 HNF4A.tiff
-rw-------@  1 kumarr9  NIH\Domain Users        43412 Sep 24 14:10 NAPY_annotation.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         9977 Sep 24 14:56 NE_Dr_Thomas.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       906630 Sep 27 09:41 genes_refseq.hg19.bed
-rw-r--r--@  1 kumarr9  NIH\Domain Users       242383 Oct  2 11:26 chirayoo_NE_NonNE.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users     74554604 Oct  2 12:29 NCI_Thomas_495_protein_coding_only_TPM_normalized.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users            0 Oct  2 12:30 NCI_Thomas_495_protein_coding_only_TPM_normalized (1).csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        80507 Oct  3 15:24 Highligh_RajeshTXT.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users       825957 Oct  4 15:00 file_manifest.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       193134 Oct  6 16:04 yugam.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users      2258258 Oct  8 11:39 BPM_distant_promoter_27Ac.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users      2011400 Oct  8 11:39 BPM_distant_promoter_27Ac 1.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1467910 Oct  8 16:58 boxplot.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users        81259 Oct  9 10:22 gene.tiff
-rw-r--r--   1 kumarr9  NIH\Domain Users     32404374 Oct  9 12:15 ccle_cell_line_custom_color_new_october_9.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users     32404214 Oct  9 12:16 ccle_cell_line_custom_color_new_october_9_new.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users      4948507 Oct  9 15:12 atNIH_2024_10_8_12_37_2_AA_Results.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users      2466632 Oct  9 15:14 Anish-NCI BBI Collaboration Meeting_09OCT2024.pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        25707 Oct 11 15:24 cell_line_updated.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users     32404214 Oct 11 18:33 ccle_cell_line_cluster_split_bold.tiff
-rw-r--r--   1 kumarr9  NIH\Domain Users     32404374 Oct 11 19:39 ccle_cell_line_cluster_split_ordered.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users     32404214 Oct 11 19:39 ccle_cell_line_cluster_split_ordered_bold.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users     32404374 Oct 12 16:51 ccle_cell_line_cluster_split_ordered_log2.tiff
-rw-r--r--   1 kumarr9  NIH\Domain Users     95048086 Oct 13 18:44 modified_ccle_cell_line_cluster_split.tiff
-rw-r--r--   1 kumarr9  NIH\Domain Users     32404374 Oct 13 19:04 ccle_cell_line_cluster_split.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users        10687 Oct 15 10:52 NFE2L2.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users        18315 Oct 15 16:13 ThomasLab_RNA_PDXOnly.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users      3249604 Oct 16 09:51 Boundless_bio_RNA_data.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users          184 Oct 16 10:23 cluster1_depth.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1140 Oct 16 10:29 cluster2_depth.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users          420 Oct 16 10:33 cluster2_depth_new.tsv
-rw-------@  1 kumarr9  NIH\Domain Users      2898652 Oct 16 10:39 TPMCountFile_rsemgenes_1.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users      3876298 Oct 16 10:45 log2_tpm_1_cell_line_bkp.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      3876298 Oct 16 10:47 log2_tpm_1_cell_line.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      2802679 Oct 16 10:58 log2_tpm_1_cell_line.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users     51845414 Oct 17 11:35 ccle_cell_line_cluster_split_bold_updated_new.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users     51845414 Oct 17 12:24 ccle_cell_line_cluster_split_bold_updated_log2_TPM.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users        10241 Oct 18 09:48 batch_1_2_DELFI.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users     31684350 Oct 18 10:32 ccle_cell_line_NEv2_features.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users     36004614 Oct 18 14:23 PDX_figure_cell_line_genes.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users      4325803 Oct 21 15:28 CTM2-12-e1060-s002.docx
-rw-r--r--   1 kumarr9  NIH\Domain Users     36004614 Oct 21 16:41 PDX_figure_cell_line_genes_log2_norm.tiff
-rw-r--r--   1 kumarr9  NIH\Domain Users         4011 Oct 22 11:54 SC.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      9615816 Oct 22 12:47 pnas.1818210116.sapp.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users        44740 Oct 22 12:49 pnas.1818210116.sd01.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1108 Oct 22 12:58 first_bkp.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users     86407550 Oct 23 10:19 PDX_figure_curated_gene_PNAS_Zscore.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users     86407550 Oct 23 11:35 ccle_figure_curated_gene_PNAS_Zscore.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users     86407550 Oct 23 11:40 ccle_figure_curated_gene_PNAS_Zscore_2.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users      2103268 Oct 24 10:46 SpotifyInstaller.zip
-rw-r--r--@  1 kumarr9  NIH\Domain Users     51845414 Oct 24 14:30 ccle_cell_line_cluster_split_bold_updated.tiff
-rw-r--r--   1 kumarr9  NIH\Domain Users     36004614 Oct 24 15:12 PDX_figure_cell_line_genes_updated.tiff
-rw-r--r--   1 kumarr9  NIH\Domain Users     86407550 Oct 25 11:18 PDX_figure_curated_gene_PNAS_logTPM.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users       257671 Oct 25 13:57 pngtree-phoenix-fire-red-bird-3d-ai-image_15695749.jpg
-rw-r--r--@  1 kumarr9  NIH\Domain Users         2450 Oct 30 13:13 rna_cluster_sig_diff_terms_new_updated.csv
-rw-r--r--   1 kumarr9  NIH\Domain Users      7562694 Oct 30 13:14 Figure2C_NES.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users          732 Oct 30 14:56 proteomics-sdrf.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users       197294 Oct 30 19:27 kmeans_new.pdf
-rw-r--r--   1 kumarr9  NIH\Domain Users    259218214 Nov  1 08:23 FDA_approved_all.tiff
-rw-------@  1 kumarr9  NIH\Domain Users          388 Nov  1 11:56 REACTOME_INTERLEUKIN_2_FAMILY_SIGNALING.v2024.1.Hs.gmt
-rw-r--r--@  1 kumarr9  NIH\Domain Users        84480 Nov  1 13:15 ncomms12619-s2.xls
-rw-------@  1 kumarr9  NIH\Domain Users      1785816 Nov  2 18:08 Rajesh_cluster_2_CTRP_drug_activity_NT20241102.pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       690015 Nov  3 14:21 UMAP_disease_region.png.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       200342 Nov  7 10:07 NIH_Intramural_Request_Form_Permission_Access_GDS_Data.pdf
-rw-------@  1 kumarr9  NIH\Domain Users       142848 Nov  7 11:22 merged_PILOTRNA_tumor_zscores.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1717 Nov  8 13:39 invite.ics
-rw-r--r--@  1 kumarr9  NIH\Domain Users       834602 Nov 10 12:00 MDD.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users       567809 Nov 10 12:01 MDD.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users       373471 Nov 10 12:20 tried_figure.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users      2178505 Nov 10 17:51 schizo.png
-rw-r-----   1 kumarr9  NIH\Domain Users       127107 Nov 14 09:38 final_directory_structure.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users         9927 Nov 14 15:49 Parth_gene_list_Nov_14.xlsx
-rw-r-----   1 kumarr9  NIH\Domain Users      6075204 Nov 18 12:11 H_Score.tiff
-rw-r-----   1 kumarr9  NIH\Domain Users      3456204 Nov 18 16:57 STEMNESS.tiff
-rw-r-----   1 kumarr9  NIH\Domain Users        11429 Nov 19 11:26 list_remain.txt
-rw-r-----@  1 kumarr9  NIH\Domain Users      9720212 Nov 20 14:16 Cell_line_correlation_new.tiff
-rw-r--r--   1 kumarr9  NIH\Domain Users         3992 Nov 20 18:56 heatma.R
-rw-r--r--@  1 kumarr9  NIH\Domain Users    432038214 Nov 20 20:02 Cell_line_heatmap_new_try.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users    720062214 Nov 20 20:19 Cell_line_heatmap_new_try_2.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users     92168614 Nov 20 20:31 Cell_line_heatmap_new_try (1).tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users    144011814 Nov 20 20:39 Cell_line_heatmap_new_try (2).tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users     64006214 Nov 20 20:47 Cell_line_heatmap_new_try_celline.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users      9652704 Nov 21 06:21 cluster1_vs_2_hallmark.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users         4000 Nov 21 09:48 heatmap.R
-rw-r--r--@  1 kumarr9  NIH\Domain Users    121299848 Nov 21 17:07 Vinod_Figure_3.pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users      8608036 Nov 21 18:52 NTE.pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       419074 Nov 21 21:18 Rajesh_Bioinformatics_Boss_Presentation.pptx
-rw-------@  1 kumarr9  NIH\Domain Users          155 Nov 26 13:45 prj_39354.ngc
-rw-r--r--@  1 kumarr9  NIH\Domain Users        10147 Nov 26 15:19 chris_chipseq_metadata.xlsx
-rw-r-----@  1 kumarr9  NIH\Domain Users     45360212 Nov 26 20:04 heatmap_correlation_complex.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users        29504 Nov 27 09:49 cluster1_motif_name.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users     10800204 Nov 27 11:24 combined_cluster_plots.tiff
-rw-r-----   1 kumarr9  NIH\Domain Users      3938564 Nov 27 14:21 output_3.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users     93600212 Nov 27 15:32 Cell_line_heatmap_new_try_celline_Nov27.tiff
-rw-------@  1 kumarr9  NIH\Domain Users         3813 Dec  1 12:15 Nabet_parth_cell_line_anno_updated_new.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         2432 Dec  1 12:16 cell_line_stemness.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      4747710 Dec  1 12:53 ScienceDirect_files_01Dec2024_17-53-54.598.zip
-rw-r-----@  1 kumarr9  NIH\Domain Users         1951 Dec  1 17:45 YAP_TAZ_signature_ssGSEA.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users         2585 Dec  2 13:36 Cell_line_stemness_TPMcalc_zscored.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users         2584 Dec  2 13:41 Cell_line_stemness_TPM_zscore.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         2559 Dec  2 13:45 Cell_line_stemness_Z_score_logTPM.tsv
-rw-r-----@  1 kumarr9  NIH\Domain Users     93600212 Dec  2 13:54 Cell_line_heatmap_new_try_celline_reordered.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users         2644 Dec  2 14:39 YAP_TAZ_signature_ssGSEA_cell_line.tsv
-rw-r-----   1 kumarr9  NIH\Domain Users        10217 Dec  4 12:53 senescence_pathways_ssGSEA_PDX.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1741775 Dec  4 12:58 PDX_sensescence.png
-rw-r-----@  1 kumarr9  NIH\Domain Users        13924 Dec  4 13:13 senescence_pathways_ssGSEA_cell_line.tsv
-rw-r--r--   1 kumarr9  NIH\Domain Users      1881537 Dec  4 13:15 Cell_line_sensescence.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users          802 Dec  4 13:43 R_studio_biowulf.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users         1024 Dec  4 13:57 first.txt
-rw-------@  1 kumarr9  NIH\Domain Users          566 Dec  5 09:20 saul_senescent_cells.rds
-rw-------@  1 kumarr9  NIH\Domain Users          511 Dec  5 09:20 casella_cellular_senescence.rds
-rw-r--r--@  1 kumarr9  NIH\Domain Users        18448 Dec  5 09:37 41467_2022_32552_MOESM4_ESM.xlsx
-rw-r-----@  1 kumarr9  NIH\Domain Users    162000204 Dec  5 15:41 WNT_ssGSEA_PDX.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users    162000204 Dec  5 15:50 WNT_ssGSEA_cell_line.tiff
-rw-r-----   1 kumarr9  NIH\Domain Users     51840204 Dec  5 16:03 WNT_ssGSEA_PDX_sig.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users    155520204 Dec  5 16:31 WNT_ssGSEA_cellline_sig.tiff
-rw-------@  1 kumarr9  NIH\Domain Users      1410107 Dec  5 18:30 Caffeine treatments [Comparision].xlsx
-rw-r-----@  1 kumarr9  NIH\Domain Users     51840204 Dec  6 11:59 Stemness_berzin_pdx.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users      9720204 Dec  6 12:04 YAP_TAZ_berzin_pdx.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users    155520204 Dec  6 12:08 WNT_berzin_pdx.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users    155520204 Dec  6 12:21 WNT_berzin_pdx_sig.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users    129600204 Dec  6 12:39 senescence_berzin_pdx_sig.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users      4905795 Dec  6 15:23 Matrix_data_Dr_teiff.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users        24823 Dec  9 12:47 sticky.txt
-rw-r-----@  1 kumarr9  NIH\Domain Users     19440204 Dec  9 13:25 motif_dotplot_with_table.tiff
-rw-r-----   1 kumarr9  NIH\Domain Users      8640204 Dec  9 13:39 cluster2_motif.tiff
-rw-r-----   1 kumarr9  NIH\Domain Users      8640204 Dec  9 13:43 cluster1_motif.tiff
-rw-r-----   1 kumarr9  NIH\Domain Users      8640204 Dec  9 13:45 cluster3_motif.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users     28687704 Dec  9 15:08 3_top_100_reactome_modified.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users     28687704 Dec  9 15:10 1_top_100_reactome_modified.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users     32062704 Dec  9 15:10 2_top_100_reactome_modified.tiff
drwxr-xr-x  32 kumarr9  NIH\Domain Users         1024 Dec  9 20:03 NES
drwxr-xr-x@ 26 kumarr9  NIH\Domain Users          832 Dec  9 20:03 png
drwxr-xr-x@  6 kumarr9  NIH\Domain Users          192 Dec  9 20:03 test
drwxr-xr-x@  4 kumarr9  NIH\Domain Users          128 Dec  9 20:03 Rajaa
drwxr-xr-x  23 kumarr9  NIH\Domain Users          736 Dec  9 20:04 CCRSF
drwxr-xr-x@  8 kumarr9  NIH\Domain Users          256 Dec  9 20:26 finspect
drwxr-xr-x@  7 kumarr9  NIH\Domain Users          224 Dec  9 20:30 test_rmd
drwxr-xr-x   6 kumarr9  NIH\Domain Users          192 Dec  9 21:21 vinod_doc
drwxr-xr-x  16 kumarr9  NIH\Domain Users          512 Dec  9 21:29 Manan_data
drwxr-xr-x@ 18 kumarr9  NIH\Domain Users          576 Dec  9 21:32 R_learning
drwxr-xr-x  23 kumarr9  NIH\Domain Users          736 Dec  9 21:34 chris_LMNA
drwxr-xr-x  22 kumarr9  NIH\Domain Users          704 Dec  9 21:36 piyush_dos
drwxr-xr-x@  6 kumarr9  NIH\Domain Users          192 Dec  9 21:36 CIRI_v2.0.5
drwxr-xr-x  13 kumarr9  NIH\Domain Users          416 Dec  9 21:37 parth_scRNA
drwxr-xr-x  14 kumarr9  NIH\Domain Users          448 Dec  9 21:39 figeno-1.4.0
drwxr-xr-x   5 kumarr9  NIH\Domain Users          160 Dec  9 21:43 example_input
drwxr-xr-x   3 kumarr9  NIH\Domain Users           96 Dec  9 21:43 GSEA_4.3.3.app
drwx------@ 45 kumarr9  NIH\Domain Users         1440 Dec  9 21:43 GSE214342_RAW
drwxr-xr-x   3 kumarr9  NIH\Domain Users           96 Dec  9 21:46 IGV_2.18.2.app
drwxr-xr-x  56 kumarr9  NIH\Domain Users         1792 Dec  9 21:50 parth_Tumor_TME
drwxr-xr-x  32 kumarr9  NIH\Domain Users         1024 Dec  9 21:57 cutandrun_bigwig
drwxrwxr-x@  9 kumarr9  NIH\Domain Users          288 Dec  9 21:58 oncofuse-1.1.1 2
drwxr-xr-x@  7 kumarr9  NIH\Domain Users          224 Dec  9 21:59 ATAC_seq_workshop
drwxr-xr-x  11 kumarr9  NIH\Domain Users          352 Dec  9 21:59 all_fusion_common
drwxr-xr-x   3 kumarr9  NIH\Domain Users           96 Dec  9 22:05 Install Spotify.app
drwx------@  5 kumarr9  NIH\Domain Users          160 Dec  9 22:06 pharos data download
drwxr-xr-x   4 kumarr9  NIH\Domain Users          128 Dec  9 22:28 macs_peak_homer_annot
drwxr-xr-x@ 15 kumarr9  NIH\Domain Users          480 Dec  9 22:31 lollipops-v1.5.2-mac64
drwxr-xr-x@ 17 kumarr9  NIH\Domain Users          544 Dec  9 22:31 israel_nature_genetics
drwxr-xr-x  27 kumarr9  NIH\Domain Users          864 Dec  9 22:32 tf_rank_within_clusters
drwxr-x---   6 kumarr9  NIH\Domain Users          192 Dec  9 22:45 pdx.rank3.TF.targets.aracne
drwx------@ 20 kumarr9  NIH\Domain Users          640 Dec  9 22:49 science.abe1505_tables_s1_to_s17
drwxr-xr-x@ 10 kumarr9  NIH\Domain Users          320 Dec  9 22:49 Harvard-CV-Templates-Word-Download
drwx------@ 20 kumarr9  NIH\Domain Users          640 Dec  9 22:50 science.abe1505_tables_s1_to_s17 2
drwx------@  6 kumarr9  NIH\Domain Users          192 Dec  9 22:50 drive-download-20240317T020552Z-001
drwxr-xr-x  31 kumarr9  NIH\Domain Users          992 Dec  9 22:51 sclc_fusion_comparison_other_databases
drwx------@  7 kumarr9  NIH\Domain Users          224 Dec  9 22:52 NCI_Kumar_POLD3_RNF169_TE-94461624_4X_RNA
drwxr-xr-x   4 kumarr9  NIH\Domain Users          128 Dec  9 22:53 ScienceDirect_files_01Dec2024_17-53-54.598
drwx------@  7 kumarr9  NIH\Domain Users          224 Dec  9 22:54 ScienceDirect_files_11Dec2023_18-18-36.410
drwx------@  7 kumarr9  NIH\Domain Users          224 Dec  9 22:54 ScienceDirect_files_18Jan2024_00-43-23.252
drwx------@  9 kumarr9  NIH\Domain Users          288 Dec  9 22:54 ScienceDirect_files_06Mar2024_16-16-33.280
drwx------@  5 kumarr9  NIH\Domain Users          160 Dec  9 22:54 ScienceDirect_files_27Feb2024_14-59-38.952
drwx------@  7 kumarr9  NIH\Domain Users          224 Dec  9 22:54 ScienceDirect_files_30Jun2022_16-17-24.275
drwx------@  6 kumarr9  NIH\Domain Users          192 Dec  9 22:56 NCI_Kumar_POLD3_RNF169_TE-93150521_LongRead_hg19
-rw-r--r--@  1 kumarr9  NIH\Domain Users      2880514 Dec 10 13:41 1-s2.0-S2590262824000856-main.pdf
-rw-r-----   1 kumarr9  NIH\Domain Users      4320204 Dec 10 16:28 H_Score_new_boxplot.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users      4646526 Dec 10 16:59 output_4_z_scored.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users     96000212 Dec 11 10:06 Cell_line_heatmap_new_try_celline_Dec11.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users     96000212 Dec 11 10:10 Cell_line_heatmap_new_try_celline_Dec11_bold.tiff
drwxr-xr-x@ 15 kumarr9  NIH\Domain Users          480 Dec 11 10:13 circRNA
drwxr-xr-x@ 14 kumarr9  NIH\Domain Users          448 Dec 11 10:13 Clinker
drwxr-xr-x  37 kumarr9  NIH\Domain Users         1184 Dec 11 10:13 consensusCluster_matrix
drwxr-xr-x@ 30 kumarr9  NIH\Domain Users          960 Dec 11 10:13 IL2_paper
drwxrwxr-x@ 16 kumarr9  NIH\Domain Users          512 Dec 11 10:13 lollipops-1.5.2
drwxr-xr-x@ 12 kumarr9  NIH\Domain Users          384 Dec 11 10:13 oncofuse-1.1.1
drwx------@ 12 kumarr9  NIH\Domain Users          384 Dec 11 10:13 Research-CV-Templates-Download-Word
drwxr-xr-x@ 20 kumarr9  NIH\Domain Users          640 Dec 11 10:13 NGS_data_analysis_workshop
drwxr-xr-x  20 kumarr9  NIH\Domain Users          640 Dec 11 10:13 ViralFusionSeq
drwx------@  5 kumarr9  NIH\Domain Users          160 Dec 11 10:13 matplotlib-1.5.0-np110py35_0
drwxrwxr-x@ 23 kumarr9  NIH\Domain Users          736 Dec 11 10:13 solar-correlation-map-R-master
drwxr-xr-x  37 kumarr9  NIH\Domain Users         1184 Dec 11 10:13 science_slides
drwxr-xr-x@ 95 kumarr9  NIH\Domain Users         3040 Dec 11 10:13 ATAC_data
drwxr-xr-x@  5 kumarr9  NIH\Domain Users          160 Dec 11 10:13 test_bam
drwxr-xr-x@  9 kumarr9  NIH\Domain Users          288 Dec 11 10:13 Spatial_cell_reports_medicine
drwxr-xr-x@ 22 kumarr9  NIH\Domain Users          704 Dec 11 10:13 ATACgraph
drwxr-xr-x@  6 kumarr9  NIH\Domain Users          192 Dec 11 10:13 TF_peaks
drwxr-xr-x  38 kumarr9  NIH\Domain Users         1216 Dec 11 10:38 GSEA_berzin
-rw-r--r--@  1 kumarr9  NIH\Domain Users    154791479 Dec 11 16:56 ScienceDirect_files_11Dec2024_21-55-46.183.zip
-rw-------@  1 kumarr9  NIH\Domain Users          428 Dec 11 17:05 cart_DAR139766_202412111704.krt
-rw-r--r--@  1 kumarr9  NIH\Domain Users    794346082 Dec 11 17:15 ATAC_Final_ppt.pptx
drwx------@ 11 kumarr9  NIH\Domain Users          352 Dec 12 13:12 ScienceDirect_files_11Dec2024_21-55-46.183
-rw-r--r--@  1 kumarr9  NIH\Domain Users       222758 Dec 13 15:24 Priyanka_updated_CV.pdf
-rw-------@  1 kumarr9  NIH\Domain Users         1558 Dec 14 09:02 chr_arms.bed
-rw-r-----@  1 kumarr9  NIH\Domain Users     32400212 Dec 16 12:56 filtered_motif_dotplot.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users       102124 Dec 16 14:00 tf_rank_within_clusters.csv
-rw-r-----@  1 kumarr9  NIH\Domain Users     51840204 Dec 17 13:22 Stemness_liu_pdx.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users      8601284 Dec 17 13:50 Liu_heatmap.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users    181440204 Dec 17 14:42 senescence_Liu_pdx.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users     38880204 Dec 19 13:48 IL2_liu_nmf.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users     38880204 Dec 19 13:48 NE_liu_nmf.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users     38880204 Dec 19 13:48 Neuronal_IFN_gamma_liu_nmf.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users    145800204 Dec 19 13:48 Sesenscene_liu_nmf.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users     69120204 Dec 19 13:48 Stemness_liu_nmf.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users      9720204 Dec 19 15:57 motif_plot_cluster1.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users      9720204 Dec 19 16:06 motif_plot_cluster2.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users      9720204 Dec 19 16:08 motif_plot_cluster3.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users      9720212 Dec 19 16:19 filtered_motif_dotplot_within_cluster.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users   1124284085 Dec 19 16:48 ATAC_12_10_2024_Main.pptx
-rw-------@  1 kumarr9  NIH\Domain Users      8182940 Dec 20 08:49 TPMCountFile_rsemgenes_log2(1+TPM)_NT20240611.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users        47616 Dec 21 11:14 PL_IP_clinical_anon.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users      7949349 Dec 23 08:59 NIHMS1624031-supplement-1624031_Supp_Tab4.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        15995 Dec 23 09:27 41586_2020_2922_MOESM4_ESM.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         9870 Dec 23 09:28 41586_2020_2922_MOESM5_ESM.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users      7949349 Dec 23 09:30 41586_2020_2922_MOESM6_ESM.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users      2766848 Dec 23 10:19 pone.0018378.s001.doc
-rw-r--r--@  1 kumarr9  NIH\Domain Users      5763389 Dec 24 11:00 41586_2018_393_MOESM3_ESM.zip
-rw-r--r--@  1 kumarr9  NIH\Domain Users       403068 Dec 24 11:04 41586_2018_393_MOESM4_ESM.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       174130 Dec 24 13:08 SraRunTable_phs.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users     26191777 Dec 26 08:31 2024.11.13.623500v1.full_copy.pdf
-rw-r-----@  1 kumarr9  NIH\Domain Users       204189 Dec 26 10:29 NIH SCLC Batch 2 Lab Data 15AUG2023 (1).xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        45671 Dec 26 17:02 Rajesh_bio.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        70946 Dec 26 17:06 Hope4Genes-master.zip
-rwxr-x---@  1 kumarr9  NIH\Domain Users    115389952 Dec 27 07:51 PL_IP_TPM_anon.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        39452 Dec 27 10:10 berzin_metadata.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users     26145572 Dec 27 12:46 2024.11.13.623500v1.full.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users     11469654 Dec 27 12:57 SCLC_tuft_like.pptx
drwx------@ 15 kumarr9  NIH\Domain Users          480 Dec 27 14:45 41586_2018_393_MOESM3_ESM
-rw-------@  1 kumarr9  NIH\Domain Users        39643 Dec 27 16:23 Ananda_GiftCard20241227133615.pdf
-rw-------@  1 kumarr9  NIH\Domain Users       253388 Dec 27 16:34 CS035635_Thomas_Schultz_FinalReport.docx
-rw-------@  1 kumarr9  NIH\Domain Users        42797 Dec 30 06:52 CLuster_2_Anylasis .pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users      6239501 Dec 30 15:57 DL-002.pdf
-rw-r-----@  1 kumarr9  NIH\Domain Users      4562214 Jan  4 09:16 output_5_z_scored.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users         5656 Jan  4 09:45 pdx_rank3_metadata_bonta_removed.tsv
-rw-r-----@  1 kumarr9  NIH\Domain Users         2495 Jan  4 09:46 PDX_bonta_remove_figure2_berzin_df.tsv
-rw-r-----   1 kumarr9  NIH\Domain Users     12960204 Jan  4 11:38 enrichment_plot_Cluster2_Proliferating_basal_cell.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users     21600204 Jan  4 12:04 berzin_NE_nonNE.tiff
-rw-r-----   1 kumarr9  NIH\Domain Users      8640204 Jan  6 08:54 cluster3_tf_heatmap_kelly.tiff
-rw-r-----   1 kumarr9  NIH\Domain Users     12960204 Jan  6 09:03 enrichment_plot_Cluster2_TCA_CYCLE_SENESCENCE.tiff
-rw-r-----   1 kumarr9  NIH\Domain Users         7167 Jan  6 09:54 Liu_sankey.svg
-rw-r--r--@  1 kumarr9  NIH\Domain Users       618056 Jan  6 10:04 Liu_sankey.pptx
-rw-r-----@  1 kumarr9  NIH\Domain Users     32400204 Jan  6 10:26 Survival_by_Cluster_KM.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users     12150212 Jan  6 10:35 Survival_by_Cluster_KM_with_risk_table.tiff
-rw-r-----   1 kumarr9  NIH\Domain Users     12150212 Jan  6 10:44 Survival_by_Liu_Cluster_KM_with_risk_table.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users     12150212 Jan  6 11:41 Survival_Cluster1_vs_Others_KM_with_risk_table.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users     12150212 Jan  6 12:05 OS_survival_plot_updated.tiff
-rw-r-----   1 kumarr9  NIH\Domain Users     12150212 Jan  6 12:06 PFS_survival_plot.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users     12150212 Jan  6 12:13 PFS_survival_plot_updated.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users     12150212 Jan  6 12:29 OS_Survival_by_Cluster_KM_with_risk_table.tiff
-rw-r-----   1 kumarr9  NIH\Domain Users     12150212 Jan  6 12:30 PFS_Survival_by_Cluster_KM_with_risk_table.tiff
-rw-------@  1 kumarr9  NIH\Domain Users       260051 Jan  8 09:28 go30081_EGA_clinical_biomarkerdata_anonymized_pass.numbers
-rw-r--r--@  1 kumarr9  NIH\Domain Users        68608 Jan  8 09:56 go30081_EGA_clinical_biomarkerdata_anonymized_pass.xlsx
-rw-r-----@  1 kumarr9  NIH\Domain Users        17467 Jan  8 13:26 Barzin_sankey_most_updated.svg
-rw-r-----@  1 kumarr9  NIH\Domain Users       164723 Jan  8 14:06 PCA_plot_top1percent.png
-rw-r-----@  1 kumarr9  NIH\Domain Users       164249 Jan  8 14:06 PCA_plot_top1percent_MAD.png
-rw-r-----   1 kumarr9  NIH\Domain Users       100628 Jan  8 14:06 PCA_scree_plot_top1percent.png
-rw-r-----   1 kumarr9  NIH\Domain Users        90000 Jan  8 14:06 PCA_scree_plot_top1percent_MAD.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users   1024433817 Jan  9 11:07 Yang_RNA_seq.pptx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       450070 Jan  9 17:33 rank3.pdx.cluster3.alone.logFC_1.pval_0.05.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      6054755 Jan  9 17:33 rank3.pdx.cluster2.alone.logFC_1.pval_0.05.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      4717025 Jan  9 17:33 rank3.pdx.cluster1.alone.logFC_1.pval_0.05.csv
-rw-------@  1 kumarr9  NIH\Domain Users     38115624 Jan 10 13:39 Figure_7_Cluster_2.pptx
-rw-r-----@  1 kumarr9  NIH\Domain Users         4014 Jan 10 14:15 hallmark_enrichment_results_new.csv
-rw-r-----   1 kumarr9  NIH\Domain Users         4902 Jan 10 14:15 hallmark_enrichment_plot_new.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users    925579326 Jan 10 15:05 ATAC 01042025_RK_new.pptx
-rw-r-----@  1 kumarr9  NIH\Domain Users       168234 Jan 10 15:22 forest-plot.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users        12899 Jan 10 15:58 unibbb.xlsx
-rw-r-----@  1 kumarr9  NIH\Domain Users       163460 Jan 10 16:00 forest-plot_new.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users        66710 Jan 11 18:45 Surface_targets.xlsx
-rw-r-----@  1 kumarr9  NIH\Domain Users      9450204 Jan 11 19:02 Surface_targets_PDX.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users      9450204 Jan 11 19:22 Surface_targets_cell_line.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users      9450204 Jan 11 19:22 Surface_targets_Liu.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users      9450204 Jan 11 19:22 Surface_targets_Barzin.tiff
-rw-------@  1 kumarr9  NIH\Domain Users      2866477 Jan 12 15:57 Gene dependency in Rajesh ATACseq cluster 2_NT20250112.pptx
-rw-r-----@  1 kumarr9  NIH\Domain Users     45360204 Jan 12 17:30 DGE_cluster2_vs_cluster1_hallmark_plot.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users     45360204 Jan 12 17:30 DGE_cluster2_vs_cluster3_hallmark_plot.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users     45360204 Jan 12 17:31 DGE_cluster2_vs_cluster1_3_hallmark_plot.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users        10365 Jan 12 17:35 DGE_cluster2_vs_cluster1_3.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users     98891131 Jan 13 07:05 go30081_anonymized_tpm_pass.numbers
-rw-r--r--@  1 kumarr9  NIH\Domain Users        68608 Jan 13 10:06 go30081_EGA_clinical_biomarkerdata_anonymized_pass (1).xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users    100320256 Jan 13 11:39 go30081_anonymized_tpm_pass.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        41984 Jan 13 11:45 EGA_go30081_20210122_IMp133-subtype_anon_pass.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         5638 Jan 13 12:53 multivariate_analysis_results_gayeetal_CHEMOIOCHORT_only.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         5638 Jan 13 12:53 multivariate_analysis_results_gayeetal-CHEMOIOCHORT only (1).xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         9951 Jan 13 13:51 Genelist_cluster2.xlsx
-rw-r-----@  1 kumarr9  NIH\Domain Users     19440218 Jan 13 13:54 forest-plot_ATAC.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users     19440218 Jan 13 14:08 forest-plot_ATAC_2.tiff
-rw-r-----   1 kumarr9  NIH\Domain Users     16200218 Jan 13 14:15 forest-plot_ATAC_3.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users        10181 Jan 13 15:05 univariate_analysis_results_Rx_1B.xlsx
-rw-r-----@  1 kumarr9  NIH\Domain Users       160060 Jan 13 15:25 forest-plot_Rx_1B.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users     19440218 Jan 13 15:53 forest-plot_Barzin_Rx_1B.tiff
-rw-r-----   1 kumarr9  NIH\Domain Users     19440218 Jan 13 16:15 forest-plot_Gay_Rx_1B.tiff
-rw-r-----   1 kumarr9  NIH\Domain Users     19440218 Jan 13 16:30 forest-plot_PDX_Rx_1B.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users     19440218 Jan 13 16:33 forest-plot_Gay.tiff
-rw-r-----   1 kumarr9  NIH\Domain Users     19440218 Jan 13 16:34 forest-plot_Barzin.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users        10365 Jan 14 09:54 DGE_cluster2_vs_cluster1_3 1.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        83293 Jan 14 10:30 fedex 0113.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users          365 Jan 14 14:21 icons8-star-24.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        33260 Jan 14 15:10 Data_Clinical.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        20116 Jan 14 15:30 AACR_abstract_RK_PD_1142025.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        15983 Jan 14 16:47 Affiliations_aacr_abstract.docx
-rw-r-----@  1 kumarr9  NIH\Domain Users     69120204 Jan 15 10:18 basal_new_Cell_Line.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users     69120204 Jan 15 10:18 basal_new_PDX.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users     69120204 Jan 15 10:18 basal_new_barzin.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users        15983 Jan 15 11:08 Affiliations_aacr_abstract (1).docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        15730 Jan 15 11:10 AACR_abstract_CM.docx
-rw-r-----@  1 kumarr9  NIH\Domain Users     19289524 Jan 15 12:30 barzin_cell_surface_targets.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users        16083 Jan 15 14:33 ATAC_manuscript_author_list.docx
-rw-r-----@  1 kumarr9  NIH\Domain Users         5324 Jan 15 16:39 classifying_berzin_new.R
-rw-r-----@  1 kumarr9  NIH\Domain Users     12960212 Jan 15 22:47 forest_plot.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users     12960212 Jan 15 23:04 forest_plot_colored.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users        11990 Jan 16 10:41 unibbb (1).xlsx
-rw-------@  1 kumarr9  NIH\Domain Users     12960204 Jan 16 15:30 peak_counts_boxplot.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users     19610328 Jan 17 14:16 sankeymatic_20241220_132332.tif
-rw-r--r--@  1 kumarr9  NIH\Domain Users     52069536 Jan 17 14:18 Barzin_sankey_most_updated.tif
-rw-r--r--@  1 kumarr9  NIH\Domain Users     22669564 Jan 17 15:35 sankeymatic_20241220_132332 1.tif
-rw-------@  1 kumarr9  NIH\Domain Users        18073 Jan 17 16:24 legends.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        18396 Jan 17 16:39 legends_RK.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        19734 Jan 17 16:59 legends_CM_RK.docx
-rw-------@  1 kumarr9  NIH\Domain Users        51176 Jan 18 09:09 Resource Table_May2024_R2.docx
-rw-------@  1 kumarr9  NIH\Domain Users       473646 Jan 18 09:09 SCLC_TME_Manuscript_Methods_May 2024_PanadaR2.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       127167 Jan 18 09:23 Timberland Returns.pdf
-rw-r-----   1 kumarr9  NIH\Domain Users      7560212 Jan 20 15:17 Cell_Line_NES.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users      3456204 Jan 21 09:42 cell_line_STEMNESS.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users        18236 Jan 21 17:14 barzin_sankey.svg
-rw-------@  1 kumarr9  NIH\Domain Users       101165 Jan 22 13:15 oncoplot_Daryl.svg
-rw-------@  1 kumarr9  NIH\Domain Users        95383 Jan 22 13:22 Darryl_figure
-rw-------@  1 kumarr9  NIH\Domain Users        95383 Jan 22 13:22 Darryl.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users         6796 Jan 22 13:39 Liu_sankey_V4.svg
-rw-r--r--@  1 kumarr9  NIH\Domain Users         6665 Jan 22 14:01 Liu_sankey_V5.svg
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1172252 Jan 23 06:13 d4nr04417g.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users     12994691 Jan 23 15:02 multivariate_figure.pptx
-rw-r-----   1 kumarr9  NIH\Domain Users       167418 Jan 24 08:59 azam_data.txt
-rw-------@  1 kumarr9  NIH\Domain Users        27194 Jan 27 14:32 1_StudyConfig_RK.docx
-rw-------@  1 kumarr9  NIH\Domain Users       512280 Jan 27 14:41 Basic_Study_Information_Sheet_RK.pdf
-rw-r--r--@  1 kumarr9  NIH\Domain Users      3681324 Jan 27 14:54 crc-22-0168-s01.docx
-rw-r-----   1 kumarr9  NIH\Domain Users          861 Jan 27 15:00 repstress_score_DMS_273.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        48690 Jan 28 14:23 h.all.v2024.1.Hs.symbols.gmt
-rw-r--r--@  1 kumarr9  NIH\Domain Users       163849 Jan 28 14:31 PR_vs_HPD_PD_absLog2FC0.5_padj0.05_DEGs.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        28012 Jan 28 15:41 geneInfo.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1831852 Jan 29 12:17 br_22_3_1931_PDF.pdf
-rw-------@  1 kumarr9  NIH\Domain Users       102375 Jan 29 13:19 PHS_EIR_Ver_150623_ PD_rajesh signed.docx
-rw-r--r--@  1 kumarr9  NIH\Domain Users     78438975 Jan 29 16:25 Svg10.svg
-rw-r--r--@  1 kumarr9  NIH\Domain Users      9806230 Jan 30 10:41 With Great Power Comes Great Responsibility  High-Dimensional Spectral Flow Cytometry to Support Clinical Trials.pdf
-rw-r-----@  1 kumarr9  NIH\Domain Users       341203 Jan 30 13:49 Liu_hypoxia_selected_pathways.png
-rw-r-----   1 kumarr9  NIH\Domain Users      2675834 Jan 30 13:49 PDX_hypoxia.png
-rw-r-----@  1 kumarr9  NIH\Domain Users       235511 Jan 30 13:49 PDX_hypoxia_selected_pathways.png
-rw-r-----   1 kumarr9  NIH\Domain Users      6363178 Jan 30 13:49 barzin_hypoxia.png
-rw-r-----@  1 kumarr9  NIH\Domain Users       502296 Jan 30 13:49 barzin_hypoxia_selected_pathways.png
-rw-r-----   1 kumarr9  NIH\Domain Users      3027710 Jan 30 13:49 cell_line_hypoxia.png
-rw-r-----@  1 kumarr9  NIH\Domain Users       270829 Jan 30 13:49 cell_line_hypoxia_selected_pathways.png
-rw-r-----@  1 kumarr9  NIH\Domain Users      2675834 Jan 30 13:49 Liu_hypoxia.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        22014 Jan 30 13:54 Copy_of_Sample_HPD_Chirau_CB.xlsx
-rw-r-----@  1 kumarr9  NIH\Domain Users      1338102 Jan 30 15:08 Cell_line_sensesnce.png
-rw-r-----@  1 kumarr9  NIH\Domain Users        20001 Jan 30 15:12 Cell_Line_senescence_updated.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        21398 Jan 30 15:49 Copy_of_Sample_HPD_Chirau_CB (1).xlsx
-rw-r-----@  1 kumarr9  NIH\Domain Users         4827 Jan 30 16:23 Clinical_benefit_Yes_No_absLog2FC0.5_padj0.05_DEGs_hallmark.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        22381 Jan 31 09:45 Copy_of_Sample_HPD_Chirau_CB_1.31.2.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         6665 Jan 31 11:17 Liu_sankey_V5 (1).svg
-rw-r--r--@  1 kumarr9  NIH\Domain Users         6665 Jan 31 11:17 Liu_sankey_V5 (2).svg
-rw-r-----@  1 kumarr9  NIH\Domain Users    155520204 Jan 31 14:38 clinical_benefits_vs_No_signature.tiff
-rw-r-----@  1 kumarr9  NIH\Domain Users    155520204 Jan 31 14:38 clinical_benefits_vs_HPD_signature.tiff
-rw-------@  1 kumarr9  NIH\Domain Users        10442 Jan 31 16:13 TMSCLC_P0_P1_P3_RNAID.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users        10630 Jan 31 16:33 Copy of TMSCLC_P0_P1_P3_RNAID.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users          165 Jan 31 17:15 ~$all_atac_file.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        12058 Jan 31 17:20 all_atac_file.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users         8955 Feb  1 09:12 Liu_sankey_Jan31.svg
-rw-r--r--@  1 kumarr9  NIH\Domain Users         8300 Feb  1 09:13 barzin_sankey_Jan31.svg
-rw-r--r--@  1 kumarr9  NIH\Domain Users     72572516 Feb  3 09:54 IGV_MacApp_2.16.0_WithJava.zip
drwxr-xr-x@  3 kumarr9  NIH\Domain Users           96 Feb  3 11:19 GitHub Desktop.app
-rw-r-----@  1 kumarr9  NIH\Domain Users       196685 Feb  3 14:20 Cell_line.png
-rw-r-----@  1 kumarr9  NIH\Domain Users       292101 Feb  3 14:20 Liu.png
-rw-r-----@  1 kumarr9  NIH\Domain Users       167668 Feb  3 14:20 PDX.png
-rw-r-----@  1 kumarr9  NIH\Domain Users       944345 Feb  3 14:36 Cell_Line_with_name.png
-rw-r-----@  1 kumarr9  NIH\Domain Users       434265 Feb  3 16:35 Barzin_log_norm.png
-rw-r-----@  1 kumarr9  NIH\Domain Users       196764 Feb  3 16:35 Cell_line_log_norm.png
-rw-r-----@  1 kumarr9  NIH\Domain Users       297184 Feb  3 16:35 Liu_log_norm.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users     36602348 Feb  4 11:18 EMS195999-supplement-Data_S1.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users     15252461 Feb  4 11:19 EMS195999-supplement-Data_S2.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        29369 Feb  4 11:19 EMS195999-supplement-Table_S1.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users        18665 Feb  4 11:19 EMS195999-supplement-Table_S2.xlsx
-rw-r--r--@  1 kumarr9  NIH\Domain Users       226755 Feb  4 11:19 EMS195999-supplement-Table_S3.xlsx
-rw-------@  1 kumarr9  NIH\Domain Users     25242157 Feb  5 10:17 data_NCI-DTP SCLC_exp.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users     11713017 Feb  5 10:17 data_NCI-DTP SCLC_exp.zip
-rw-r--r--@  1 kumarr9  NIH\Domain Users        22402 Feb  5 11:28 Copy_of_Sample_HPD_Chirau_CB_2.5.25 1.xlsx
drwxr-xr-x  32 kumarr9  NIH\Domain Users         1024 Feb  5 12:07 Room_rent
-rw-r-----@  1 kumarr9  NIH\Domain Users     96000212 Feb  5 14:35 Cell_line_heatmap_new_try_celline_Dec11_bold_updated.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users          644 Feb  6 10:48 footnotes_NCI-DTP SCLC_exp.csv
-rw-r--r--@  1 kumarr9  NIH\Domain Users         9552 Feb  6 10:48 Cell_line_annotation_nciSclc.txt
-rw-r--r--@  1 kumarr9  NIH\Domain Users        10619 Feb 10 08:23 Copy of TMSCLC_P0_P1_P3_RNAID(37).xlsx
-rw-r-----@  1 kumarr9  NIH\Domain Users       439879 Feb 10 13:52 EMT_barzin.png
-rw-r-----   1 kumarr9  NIH\Domain Users       214870 Feb 10 13:53 EMT_PDX.png
-rw-r-----@  1 kumarr9  NIH\Domain Users       290561 Feb 10 13:54 EMT_Liu.png
-rw-r-----@  1 kumarr9  NIH\Domain Users       446437 Feb 10 18:13 Liver_mets_vs_parental_absLog2FC1_hallamrk_hallmark.png
-rw-r-----@  1 kumarr9  NIH\Domain Users       449022 Feb 10 18:14 Liver_mets_vs_parental_absLog2FC1_hallamrk_hallmark_logFold_rank.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        21541 Feb 11 10:02 Copy_of_Sample_HPD_Chirau_CB_2.5.25 1 (1).xlsx
-rw-r-----@  1 kumarr9  NIH\Domain Users       204056 Feb 11 11:42 HPD_vs_Pre_Post_absLog2FC0.5_padj0.05_DEGs.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users      8750266 Feb 11 14:00 ScienceDirect_files_11Feb2025_19-00-07.608.zip
drwx------@  8 kumarr9  NIH\Domain Users          256 Feb 11 14:02 ScienceDirect_files_11Feb2025_19-00-07.608
-rw-------@  1 kumarr9  NIH\Domain Users      3757761 Feb 11 14:38 SCLC _ATAC_classification_manuscript_02102025.docx
-rw-------@  1 kumarr9  NIH\Domain Users        13239 Feb 11 14:48 metadata_for_Rajaa.xlsx
-rw-r-----@  1 kumarr9  NIH\Domain Users         5949 Feb 12 09:57 brett_df_NE_NonNE_with_subtype2.tsv
-rw-r--r--@  1 kumarr9  NIH\Domain Users        21847 Feb 12 10:26 Copy_of_Sample_HPD_Chirau_CB_2.5.25 1 (2).xlsx
-rw-r-----@  1 kumarr9  NIH\Domain Users       147768 Feb 12 10:39 Liver_mets_vs_parental_absLog2FC1_padj0.05_DEGs.tsv
-rw-r-----@  1 kumarr9  NIH\Domain Users       249948 Feb 12 10:46 Liver_mets_vs_parental_absLog2FC1_immune_neg.png
-rw-r-----@  1 kumarr9  NIH\Domain Users       241506 Feb 12 10:46 Liver_mets_vs_parental_absLog2FC1_immune_pos.png
-rw-r-----@  1 kumarr9  NIH\Domain Users       269927 Feb 12 11:15 HPD_vs_Pre_Post_fewer_sample_absLog2FC0.5_padj0.05_DEGs.tsv
-rw-r-----@  1 kumarr9  NIH\Domain Users     32400212 Feb 12 12:11 NMF_K3_new_legend_updated.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users     56594930 Feb 12 13:15 GSEA_MacApp_4.3.3.app.zip
-rw-r-----@  1 kumarr9  NIH\Domain Users       260960 Feb 12 13:40 Liver_mets_vs_parental_absLog2FC1_immune.png
-rw-r-----@  1 kumarr9  NIH\Domain Users       467678 Feb 12 14:23 HPD_vs_Pre_Post_fewer_sample_absLog2FC0.5_hallmark_stat.png
-rw-r-----@  1 kumarr9  NIH\Domain Users       466847 Feb 12 14:23 HPD_vs_Pre_Post_fewer_sample_absLog2FC0.5_hallmark_log2fold.png
-rw-r-----@  1 kumarr9  NIH\Domain Users       694816 Feb 12 14:39 HPD_vs_Pre_Post_fewer_sample_absLog2FC0.5_padj0.05_DEGs_reactome.csv
-rw-r-----@  1 kumarr9  NIH\Domain Users     43942704 Feb 12 14:53 HPD_vs_Pre_Post_fewer_sample_absLog2FC0.5_padj0.05_DEGs_reactome_plot.png
-rw-r-----@  1 kumarr9  NIH\Domain Users       145739 Feb 12 16:55 HPD_vs_Pre_Post_fewer_sample_absLog2FC0.5_stemness_log2fold.png
-rw-r--r--@  1 kumarr9  NIH\Domain Users        44740 Feb 13 10:53 pnas.1818210116.sd01 (1).xlsx
-rw-r-----@  1 kumarr9  NIH\Domain Users        86481 Feb 13 11:13 HPD_vs_non_HPD_Cell_line_signature_signature.png
-rw-r-----   1 kumarr9  NIH\Domain Users          184 Feb 13 11:17 REACTOME_INTERLEUKIN_2_SIGNALING.v2024.1.Hs.gmt
-rw-r-----   1 kumarr9  NIH\Domain Users         1290 Feb 13 11:17 neuron_gene.gmt
-rw-r--r--@  1 kumarr9  NIH\Domain Users      1506803 Feb 13 12:06 January_2025.pdf
-rw-r-----@  1 kumarr9  NIH\Domain Users       551641 Feb 13 12:28 TGF_beta_HPD_vs_Non_HPD.png
-rw-r-----@  1 kumarr9  NIH\Domain Users       324136 Feb 13 13:07 TGF_beta_HPD_vs_Non_HPD_cell_line.png
-rw-r-----@  1 kumarr9  NIH\Domain Users       117725 Feb 13 13:58 HPD_vs_non_HPD_stemness_stat.png
-rw-r-----@  1 kumarr9  NIH\Domain Users       117256 Feb 13 13:59 HPD_vs_non_HPD_stemness_log2FC.png
-rw-r-----@  1 kumarr9  NIH\Domain Users       379245 Feb 13 14:37 Stemness_HPD_vs_NonHPD.png
-rw-r-----   1 kumarr9  NIH\Domain Users       340200 Feb 13 15:14 Stemness_HPD_vs_NonHPD_cell_line.png
drwxr-xr-x  29 kumarr9  NIH\Domain Users          928 Feb 13 16:48 TGF_beta_HOD_vs_Non_HPD
-rw-r-----@  1 kumarr9  NIH\Domain Users      7087712 Feb 14 12:09 Cell_Line_DTB_NES.tiff
-rw-r--r--@  1 kumarr9  NIH\Domain Users      9730396 Feb 14 12:36 Amira_Liiver_mets_parental.pptx
-rw-r-----@  1 kumarr9  NIH\Domain Users       306102 Feb 14 14:31 HPD_Pre_vs_Post.png
-rw-r-----@  1 kumarr9  NIH\Domain Users       260308 Feb 14 14:31 HPD_vs_NonHPD.png
-rw-r-----   1 kumarr9  NIH\Domain Users       137129 Feb 15 13:18 ARACNE_HPD_vs_NonHPD.png
-rw-r--r--   1 kumarr9  NIH\Domain Users         1595 Feb 15 13:35 ssGSEA.git
-rw-r--r--@  1 kumarr9  NIH\Domain Users    175045926 Feb 15 13:37 GitHubDesktop-x64.zip
[kumarr9@NCI-02296922-ML Downloads]$ git remote add origin git@github.com:imrjesh/ssGSEA.git
[kumarr9@NCI-02296922-ML Downloads]$ git init
Initialized empty Git repository in /Users/kumarr9/Downloads/.git/
[kumarr9@NCI-02296922-ML Downloads]$ git remote add origin git@github.com:imrjesh/ssGSEA.git
[kumarr9@NCI-02296922-ML Downloads]$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	.ATAC_code.R.swp
	.DS_Store
	.RData
	.Rapp.history
	.Rhistory
	.com.google.Chrome.3sSuNe
	.com.google.Chrome.3zqFtU
	.com.google.Chrome.6s2WG9
	.com.google.Chrome.7A80hE
	.com.google.Chrome.DklR0S
	.com.google.Chrome.STyJYg
	.com.google.Chrome.UVAxWx
	.com.google.Chrome.X3xxSY
	.com.google.Chrome.aoONB3
	.com.google.Chrome.kLYS5n
	.com.google.Chrome.rpbTZG
	.com.google.Chrome.srUxex
	.com.google.Chrome.x284mB
	.localized
	.parth_gene.txt.swp
	.png.ps
	.rank3.pdx.cluster1.motif.txt.swp
	.surv.tsv.swp
	.test.txt.swp
	.v.txt.swp
	1-s2.0-S0092867423013351-mmc6.xlsx
	1-s2.0-S0167779923000884-main.pdf
	1-s2.0-S107476132200084X-main.pdf
	1-s2.0-S2590262824000856-main.pdf
	10_16_23_SCLC_Cell_lines.xlsx
	1161_BatchCode.zip
	120-1201942_chandrashekhar-azad-hd-png-download.png
	15-C-0145 Dates added- 7-31-24.xlsx
	15_c_0145.tsv
	1708955629381SR4BdZw05tqgahM0.pdf
	1_3_23_RNA_Seq_datasets.xlsx
	1_StudyConfig_RK.docx
	1_top_100_reactome_modified.tiff
	2-15-2022-DTB Lab Roster .pdf
	20220801_135505_resized.jpeg
	20220801_135514_resized.jpeg
	2024.11.13.623500v1.full.pdf
	2024.11.13.623500v1.full_copy.pdf
	216_upregulated_SCLC-Inflamed_genes.txt
	2_top_100_reactome_modified.tiff
	2year.csv
	2year.tsv
	3_top_100_reactome_modified.tiff
	3p-Neutrophils-UMAP-Projection.csv
	3p-Neutrophils-clusters.csv
	3rdquarter.pdf
	41467_2019_9940_MOESM11_ESM.xlsx
	41467_2019_9940_MOESM5_ESM.xlsx
	41467_2022_32552_MOESM4_ESM.xlsx
	41586_2015_BFnature14664_MOESM72_ESM.xlsx
	41586_2018_393_MOESM3_ESM.zip
	41586_2018_393_MOESM3_ESM/
	41586_2018_393_MOESM4_ESM.xlsx
	41586_2020_2922_MOESM3_ESM.xlsx
	41586_2020_2922_MOESM4_ESM.xlsx
	41586_2020_2922_MOESM5_ESM.xlsx
	41586_2020_2922_MOESM6_ESM.xlsx
	47.pdf
	6314734.jpeg
	86918-Free SeeSaw PowerPoint Template.pptx
	A406a_ATAC_S0_L001_R1_001.fastq
	A406a_ATAC_S0_L001_R1_001.fastq.gz
	AACR_abstract_CM.docx
	AACR_abstract_RK_PD_1142025.docx
	ALB.tiff
	ALDOB.png
	ALDOB.tiff
	ARACNE_HPD_vs_NonHPD.png
	ARACNe_TF_motifs.xlsx
	ARCHIBUS Web Central.pdf
	ASCL1.n.NEUROD1.chipSeq.TFBS.Borromeo.2016.xlsx
	ASCL1.png
	ASCL1_batch1.png
	ASCO-Caris-2022-Molecular-correlates-of-Delta-like-ligand-3-DLL3-expression-in-neuroendocrine-neoplasms-NENs.pdf
	ATAC 01042025_RK_new.pptx
	ATAC-seq workshop-20220606T180539Z-001.zip
	ATAC.png
	ATAC.tsv
	ATAC.xlsx
	ATAC_12_10_2024_Main.pptx
	ATAC_Fig_Draft_May_09_2024.pptx
	ATAC_Final_ppt.pptx
	ATAC_PCAA.png
	ATAC_PCA_all_samples.png
	ATAC_PCA_top_one.png
	ATAC_PDXmatch_Rajesh_PD_Signatures_2.txt
	ATAC_PDXmatch_Rajesh_PD_Signatures_2_new.txt
	ATAC_RNA.csv
	ATAC_RNA.xls
	ATAC_RNA_data.tsv
	ATAC_RNA_raw_count.csv
	ATAC_TPM_standard_deviation.csv
	ATAC_all_sample_peaks_sorted.narrowPeak
	ATAC_cluster.png
	ATAC_cluster_sig_ssGSEA.csv
	ATAC_cluster_sig_ssGSEA.tsv
	ATAC_cluster_sig_ssGSEA_2.csv
	ATAC_cluster_sig_ssGSEA_anno.tsv
	ATAC_count.csv
	ATAC_count1.csv
	ATAC_data/
	ATAC_data_distribution_with_biopsy_site_NT20220721.xlsx
	ATAC_discussion_sep07.docx
	ATAC_enrichment.png
	ATAC_feature_distribution.xlsx
	ATAC_feature_distribution_copy.xlsx
	ATAC_feature_igv.png
	ATAC_feature_npg_color.png
	ATAC_flow.png
	ATAC_manuscript_author_list.docx
	ATAC_only.png
	ATAC_only.tsv
	ATAC_peak_TSS.png
	ATAC_screenshot.png
	ATAC_seq_workshop/
	ATAC_signature_cell_line.tiff
	ATAC_signature_cell_line_second_list.tiff
	ATAC_signature_cell_line_try.tiff
	ATAC_venn_upset.png
	ATACgraph/
	ATOH1.xlsx
	AU_21_162_INFO.xlsx
	AXL.tsv
	AXL_cp.tsv
	AXL_cp_new.tsv
	Accepted and waiting list (1).xlsx
	Accepted and waiting list.xlsx
	Addition of Author Request in Schultz et Al. EMBO Molecular Medecine 2023 15-e17313.pdf-RE_DA_ZWO signed (002).pdf
	Advertisement Details (1).pdf
	Advertisement Details.pdf
	Affiliations_aacr_abstract (1).docx
	Affiliations_aacr_abstract.docx
	Agenda this week.docx
	Ajit_adheretn_vs_suspension.pptx
	Ajit_parental_vs_animal.pptx
	AllDataWTA.meta.new.tumor_only.csv
	All_chr_num_DS_splice.txt
	Amira_Liiver_mets_parental.pptx
	Ananda_GiftCard20241227133615.pdf
	Anish-NCI BBI Collaboration Meeting_09OCT2024.pptx
	Anjali Ver - Current and Emerging Approaches in Vaccine Design and Delivery.docx
	Anjali_paper.pdf
	Annexure A_final.docx
	Annexure_III_Authors list.xlsx
	Archetype_signatures_ssGSEA.csv
	Archetype_signatures_ssGSEA[56].csv
	AsynonymousTSS_clinical_characteristics_updated_20210803.xlsx
	August_2022.pdf
	Author_response_cancer cell_June 2023_AT_PDant.docx
	Authors list by RK-PR.xlsx
	Authorship_Change_Form.pdf
	BPM_distant_promoter_27Ac 1.tiff
	BPM_distant_promoter_27Ac.tiff
	Barzin_log_norm.png
	Barzin_sankey_most_updated.svg
	Barzin_sankey_most_updated.tif
	Basic_Study_Information_Sheet_RK.pdf
	Batch0_DNA_Nobu era.xlsx
	BillImage.pdf
	Biowulf data.pptx
	Biowulf_Collaborators_MNAnnotated.xlsx
	Book10.xlsx
	Book11.xlsx
	Book16.xlsx
	Book2.xlsx
	Book3.xlsx
	Boundless_bio_RNA_data.tsv
	BoxToolsInstaller.dmg
	CANCER_TYPE_EDA.html
	CCLE_DGE_result.csv
	CCLE_file.txt
	CCLE_fusions.csv
	CCLE_gsea.tsv
	CCLE_gsea_new.tsv
	CCLE_mutations.csv
	CCLE_test.tiff
	CCLE_test_new.tiff
	CCP_Cuzick.rds
	CCRSF/
	CENPA_genes (002).pptx
	CENPA_genes.pptx
	CIRI_Full_v2.1.1.jar
	CIRI_v2.0.5.zip
	CIRI_v2.0.5/
	CLCVsharma.pdf
	CLuster_2_Anylasis .pptx
	CS035635_Thomas_Schultz_FinalReport.docx
	CSEMLabGuidelines2021WELCOME LETTER.docx
	CSID_NCI thomas large dataset.xlsx
	CTM2-12-e1060-s002.docx
	Caffeine treatments [Comparision].xlsx
	Califano_VIPER.pptx
	Cancer research_Notch mutant GEMM.xlsx
	Cell_Line_DTB_NES.tiff
	Cell_Line_NES.tiff
	Cell_Line_senescence_updated.tsv
	Cell_Line_with_name.png
	Cell_line.png
	Cell_line_annotation_nciSclc.txt
	Cell_line_correlation_new.tiff
	Cell_line_heatmap_new_try (1).tiff
	Cell_line_heatmap_new_try (2).tiff
	Cell_line_heatmap_new_try.tiff
	Cell_line_heatmap_new_try_2.tiff
	Cell_line_heatmap_new_try_celline.tiff
	Cell_line_heatmap_new_try_celline_Dec11.tiff
	Cell_line_heatmap_new_try_celline_Dec11_bold.tiff
	Cell_line_heatmap_new_try_celline_Dec11_bold_updated.tiff
	Cell_line_heatmap_new_try_celline_Nov27.tiff
	Cell_line_heatmap_new_try_celline_reordered.tiff
	Cell_line_log_norm.png
	Cell_line_sensescence.png
	Cell_line_sensesnce.png
	Cell_line_stemness_TPM_zscore.tsv
	Cell_line_stemness_TPMcalc_zscored.tsv
	Cell_line_stemness_Z_score_logTPM.tsv
	Cellchat_R_4.3.ipynb
	Cells to Juanma.docx
	Certificate.pdf
	ChEA_2022_table.txt
	Chip_only.png
	Chip_only.tsv
	Chipseq.pptx
	Chris_LMNA.xlsx
	Clinical-characteritics-AT-March9-review.xlsx
	Clinical_annot_August24_NCI_SCLC.xlsx
	Clinical_benefit_Yes_No_absLog2FC0.5_padj0.05_DEGs_hallmark.csv
	Clinker/
	Cluster_1_2_3_relaxed.xlsx
	Combined Bulk_4_2022_Rajesh_list_all_RNA_seq_data.xlsx
	Computational Tools for Stem Cell Biology _ Enhanced Reader.pdf
	Consensusmatrix.Rmd
	Copy of ATAC_Fig_Draft_May_09_2024_PD3_june9_2024.pptx
	Copy of Copy of cfChiPseq_list_Pt_IDs_NT20230327_PD_editsant (002) Rajesh anon.xlsx
	Copy of Metadata_For_Parth.xlsx
	Copy of TMSCLC_P0_P1_P3_RNAID(37).xlsx
	Copy of TMSCLC_P0_P1_P3_RNAID.xlsx
	Copy of autopsy_samples_info.xlsx
	Copy of cfChiPseq_list_Pt_IDs_NT20230327_PD_editsant.xlsx
	Copy of sample sheet (002).xlsx
	Copy_of_Sample_HPD_Chirau_CB (1).xlsx
	Copy_of_Sample_HPD_Chirau_CB.xlsx
	Copy_of_Sample_HPD_Chirau_CB_1.31.2.xlsx
	Copy_of_Sample_HPD_Chirau_CB_2.5.25 1 (1).xlsx
	Copy_of_Sample_HPD_Chirau_CB_2.5.25 1 (2).xlsx
	Copy_of_Sample_HPD_Chirau_CB_2.5.25 1.xlsx
	Correlation_justin.xls
	Covplot.png
	Current and Emerging Approaches in Vaccine Design.docx
	Cyrus Driving School 2.pdf
	Cyrus Driving School.pdf
	CytoTRACE_0.3.3.tar.gz
	Cytoscape_3_10_1_macos_aarch64.dmg
	DBT_early_career_full_proposal (1).docx
	DBT_early_career_full_proposal.docx
	DESeq2.R
	DESeq2_july_31.png
	DGE_cluster2_vs_cluster1_3 1.tsv
	DGE_cluster2_vs_cluster1_3.tsv
	DGE_cluster2_vs_cluster1_3_hallmark_plot.tiff
	DGE_cluster2_vs_cluster1_hallmark_plot.tiff
	DGE_cluster2_vs_cluster3_hallmark_plot.tiff
	DL-002.pdf
	DLL3.png
	DLL3.tiff
	DLL3_new.png
	DLL3_newest.png
	DLL_brain_liver_P1.xlsx
	DMS273.xlsx
	DMS273_137_met_18Ac.bed
	DMS273_137_met_18Ac.seacr.consensus.peak_counts.bed
	DMS273_137_met_27Ac.bed
	DMS273_137_met_27Ac.seacr.consensus.peak_counts.bed
	DRISTHI_PAPER.pdf
	DSP_tumor_stroma_correlation_violin_plot_20211228.pzfx
	DTB EMAIL-02152022.pdf
	DTB_files_fathi.xlsx
	Darryl.png
	Darryl_figure
	Data_Clinical.xlsx
	Delfi plasma with RNAseq samples for Rajesh_NE classifications.xlsx
	Delfin plasma samples hyperprogression autopsy brain mets EGFR prostate .xlsx
	DepMap-Clusters_vs_Dependencies.pptx
	DepMap.tiff
	DepMap_ssGSEA_KEGG_WNT_Priya.tsv
	DepMap_ssGSEA_KEGG_WNT_Priya_NE_only.tsv
	DepMap_subset.tiff
	DepMap_subset_Figure_6.tiff
	Dilli-chalo.jpg
	Discover Card_ Make a Payment Confirmation Printable.pdf
	Discover Card_ Make a Payment Confirmation Printable_May.pdf
	Discover-Statement-20220318-2036.pdf
	Discover-Statement-20230611-6726.pdf
	Discover-Statement-20240218-2036.pdf
	Division of International Services Case Status and Reports_.pdf
	DocumentChecklists2.pdf
	Draft_chapter.docx
	EGA_go30081_20210122_IMp133-subtype_anon_pass.xlsx
	EMS195999-supplement-Data_S1.csv
	EMS195999-supplement-Data_S2.csv
	EMS195999-supplement-Table_S1.xlsx
	EMS195999-supplement-Table_S2.xlsx
	EMS195999-supplement-Table_S3.xlsx
	EMT_Liu.png
	EMT_PDX.png
	EMT_barzin.png
	ENCFF012XAP.bigWig
	ENCFF231FNI.bigWig
	EP_SCLC.pdf
	Enrichr_results_bar.png
	EthicsCert.jpeg
	Example for Rajesh.xlsx
	FASTQ_missing_paired_information.csv
	FATSQ_missing_paired_Information.tsv
	FDA_approved_all.tiff
	FDA_approved_common.tiff
	FDA_aproved_drug_signature.tsv
	FISH for chromosome instability human tissues.pdf
	FOXA1.tiff
	FOXA1_high_liver_met_vs_low_TF_no_liver_sum_score.png
	FOXA1_longitudinal_0059.png
	FOXA3.tiff
	FPKM.txt
	FRA21.bed
	FTD.hg38.genotype_selectedVars_het_chr3.raw
	FTD.hg38.neotype_selectvar.tsv
	Fig.pptx
	Fig4C_heatmap.Rmd
	Fig4C_tumor_SOI_data2.txt
	Figure2C_NES.tiff
	Figure_7_Cluster_2.pptx
	FileZilla 2.app/
	FileZilla.app/
	FileZilla_3.67.0_macos-arm64.app.tar.bz2
	FileZilla_3.67.0_macos-x86.app.tar.bz2
	Finallexapansion.csv
	Flowcell_H3M7HDSX2.tsv
	For_parth_new.xlsx
	Form_Pdf_66.pdf
	Functional_characterization_ATOH_Indicate_metastastic_role_SCLC.xlsx
	Fusion_DTB_comments_ajit.pptx
	Fusion_Functional_Approaches.pptx
	GATA6_high_liver_met_vs_low_TF_no_liver_sum_score.png
	GEO submission_RNAseq_Proteomic.xlsx
	GOBP_NUCLEAR_TRANSPORT.v2023.1.Hs.gmt
	GSE214342_RAW.tar
	GSE214342_RAW/
	GSEA.Rmd
	GSEA_4.3.2.app/
	GSEA_4.3.3 2.app/
	GSEA_4.3.3 3.app/
	GSEA_4.3.3.app/
	GSEA_GOBP_4000.csv
	GSEA_GOBP_4000.xlsx
	GSEA_GOBP_4000SD.txt
	GSEA_MacApp_4.3.3.app.zip
	GSEA_berzin/
	GSEA_fusion_positive_GO_terms
	GSEA_multiple 4000SD genes_summary.txt
	GSEA_multiple_4000_genes.csv
	GSM2550011_RKO_c0011_w0053.CEL
	GSM2550011_RKO_c0011_w0053.CEL.gz
	GSM2550011_RKO_c0011_w0053.sst-rma-gene-full.chp
	GSM2550011_RKO_c0011_w0053.sst-rma-gene-full.chp.gz
	GSM3165679_H1048_POU2F3_CHIP_peaks_filtered.score.gt.500.log.q.gt.20.narrowPeak
	G__Online_Inspire_ReadWriteData_Temp_20211001215822310136386.pdf
	G__Online_Inspire_ReadWriteData_Temp_2021100122002742805404.pdf
	Gavish_malignant_cell_MP.rds
	Gene dependency in Rajesh ATACseq cluster 2_NT20250112.pptx
	Gene_file.txt
	Gene_signature.xlsx
	Gene_signature_new.xlsx
	Genelist_cluster2.xlsx
	George_all.xlsx
	GitHub Desktop.app/
	GitHubDesktop-x64.zip
	HALLMARK_MYC_TARGETS_V1.rds
	HAP1 RNAseq Normalized reads.xlsx
	HES1.png
	HES1.tiff
	HIM-D-23-01091.pdf
	HLA_project_proposal_final_short.pdf
	HNF1A.png
	HNF1A.tiff
	HNF4A.png
	HNF4A.tiff
	HPD Annotation File for Max and Howard_5_30_2023.xlsx
	HPD Annotation File_7_6_2023_deidentified.xlsx
	HPD_Pre_vs_Post.png
	HPD_vs_NonHPD.png
	HPD_vs_Pre_Post_absLog2FC0.5_padj0.05_DEGs.tsv
	HPD_vs_Pre_Post_fewer_sample_absLog2FC0.5_hallmark_log2fold.png
	HPD_vs_Pre_Post_fewer_sample_absLog2FC0.5_hallmark_stat.png
	HPD_vs_Pre_Post_fewer_sample_absLog2FC0.5_padj0.05_DEGs.tsv
	HPD_vs_Pre_Post_fewer_sample_absLog2FC0.5_padj0.05_DEGs_reactome.csv
	HPD_vs_Pre_Post_fewer_sample_absLog2FC0.5_padj0.05_DEGs_reactome_plot.png
	HPD_vs_Pre_Post_fewer_sample_absLog2FC0.5_stemness_log2fold.png
	HPD_vs_non_HPD_Cell_line_signature_signature.png
	HPD_vs_non_HPD_stemness_log2FC.png
	HPD_vs_non_HPD_stemness_stat.png
	HP_Color_LaserJet_Pro_MFP_M282_M285_Series-20231206.dmg
	H_Score.tiff
	H_Score_new_boxplot.tiff
	Handbook of Chemoinformatics - 2003 - Gasteiger.pdf
	Harvard-CV-Templates-Word-Download.zip
	Harvard-CV-Templates-Word-Download/
	Heatmap_ATAC_TSS.png
	Highligh_RajeshTXT.xlsx
	Hope4Genes-master.zip
	Hope4Genes-master/
	I-129 worksheet.pdf
	ICMJE COI Disclosure Form.docx
	IGV_2.11.7.app/
	IGV_2.16.0.app/
	IGV_2.18.2.app/
	IGV_MacApp_2.16.0_WithJava.zip
	IGV_MacApp_2.18.2_WithJava.zip
	IHC_Rajaa.xlsx
	IL-2_Manuscript_Revised_latest_all_modified.docx
	IL-2_Manuscript_Revised_latest_highlighted.docx
	IL2_liu_nmf.tiff
	IL2_paper/
	IMG-20230329-WA0002.jpg
	IMG-20230329-WA0003.jpg
	IMG_3387.jpg
	IMPOWER_gene sets.xlsx
	IMPOWER_gene sets[26].xlsx
	ISCIENCE-D-22-02793_reviewer.pdf
	Immunotherapy of Neuroendocrine Neoplasms- Any Role for the Chimeric Antigen Receptor T Cells?.pdf
	Inferring gene expression from cell-free DNA fragmentation profiles.pdf
	Inspire_faculty_Results_2020.pdf
	Install Spotify.app/
	Integrated object_scRNA_for ATAC project_Rajesh_PD.pptx
	Integrated_scRNA_FOR ATAC Project_Rajesh_PD.xlsx
	JCB_201109100.pdf
	January_2025.pdf
	Jeetu Journey Confirmation.pdf
	Jitesh_Fee_Receipt_3rd_quarter.pdf
	KEGG_TGF_BETA_SIGNALING_PATHWAY.v2023.2.Hs.gmt
	KO_Parenal_Hallmark.png
	Keka-1.3.7.dmg
	Knockdown of IGF2BP3 inhibits the tumorigenesis of gallbladder cancer and modifies tumor microenvironment.pdf
	LaTeXTemplates_freeman-cv_v3.0.zip
	LabWorks.xlsx
	List of Apartment.docx
	Liu.png
	Liu_heatmap.tiff
	Liu_hypoxia.png
	Liu_hypoxia_selected_pathways.png
	Liu_log_norm.png
	Liu_sankey.pptx
	Liu_sankey.svg
	Liu_sankey_Jan31.svg
	Liu_sankey_V4.svg
	Liu_sankey_V5 (1).svg
	Liu_sankey_V5 (2).svg
	Liu_sankey_V5.svg
	Liver_mets_vs_parental_absLog2FC1_hallamrk_hallmark.png
	Liver_mets_vs_parental_absLog2FC1_hallamrk_hallmark_logFold_rank.png
	Liver_mets_vs_parental_absLog2FC1_immune.png
	Liver_mets_vs_parental_absLog2FC1_immune_neg.png
	Liver_mets_vs_parental_absLog2FC1_immune_pos.png
	Liver_mets_vs_parental_absLog2FC1_padj0.05_DEGs.tsv
	MC Proposal 2021.docx
	MDD.pdf
	MDD.png
	MISC-Sep-21-2020.pdf
	MYCL_batch1.png
	MYC_batch1.png
	Manan_data/
	Manan_data_all.csv
	Manan_tpm_normalized_protein_coding_only.tsv
	Maryland ID.pdf
	Master ATAC Submission File.xlsx
	Master CHIP Submission File.xlsx
	Master RNA Submission File.xlsx
	Master sheet_NCI THOMAS_352.txt
	Mastersheet_NCI THOMAS_352_PD_892022_START.xlsx
	Matrix_data_Dr_teiff.xlsx
	May31_NEC_subtype.pptx
	Mendeley-Desktop-1.19.3-OSX-Universal.dmg
	MicrosoftTeams-image (1).png
	MicrosoftTeams-image.png
	Modified_Vaishali_Review1.docx
	Molecular classification of small cell lung cancer subtypes- characteristics, prognostic factors, and clinical translation.pdf
	Msigdb_STEM_CELLS_BUSSLINGER.v2023.2.Hs .gmt
	NAPY.tsv
	NAPY_annotation.xlsx
	NAPY_targets.txt
	NCI SCLC patients without MRN.xlsx
	NCI-SCLC-326-ARACNE-GeneRegNet_new.xlsx
	NCI_Kumar_POLD3_RNF169_TE-93150521_LongRead_hg19.zip
	NCI_Kumar_POLD3_RNF169_TE-93150521_LongRead_hg19/
	NCI_Kumar_POLD3_RNF169_TE-94461624_4X_RNA.zip
	NCI_Kumar_POLD3_RNF169_TE-94461624_4X_RNA/
	NCI_Thomas_429_raw_count.csv
	NCI_Thomas_439_batch_info.tsv
	NCI_Thomas_439_protein_coding_only_TPM_normalized (1).tsv
	NCI_Thomas_439_protein_coding_only_TPM_normalized.tsv
	NCI_Thomas_495_protein_coding_only_TPM_normalized (1).csv
	NCI_Thomas_495_protein_coding_only_TPM_normalized.csv
	NCI_huizi_autopsy_SCLC_liver_others_GSEA_Tachmatzidi_liver_tf_20220522.pptx
	NCI_signatures.tsv
	NCI_thomas_439.tsv
	NCI_thomas_439_df2.tsv
	NCI_thomas_439_matched.tsv
	NES/
	NEUROD1_batch1.png
	NE_Dr_Thomas.xlsx
	NE_NonNE.pdf
	NE_Non_NE.tsv
	NE_liu_nmf.tiff
	NE_nonNE.xlsx
	NFE2L2.xlsx
	NFKB1.png
	NFKB_all.png
	NFKB_all.tsv
	NGS_data_analysis_workshop/
	NIH Information Security and Management Awareness Refresher.pdf
	NIH SCLC Batch 2 Lab Data 15AUG2023 (1).xlsx
	NIHMS1002246-supplement-4.pdf
	NIHMS1624031-supplement-1624031_Supp_Tab4.xlsx
	NIHMS1641013-supplement-1.pdf
	NIHMS958978-supplement-3.xlsx
	NIH_Intramural_Request_Form_Permission_Access_GDS_Data.pdf
	NIH_file_prefixes_2024-03-20_V1_Collaborators.xlsx
	NIH_map.jpeg
	NKcell.pptx
	NLGL3.png
	NMF.png
	NMF_K3_new_legend_updated.tiff
	NOTCH_genesets.csv
	NOTCH_genesets[66].csv
	NR5A2_high_liver_met_vs_low_TF_no_live_sum_score.png
	NTE.pptx
	NVUS2022081004.xlsx
	Nabet_parth.tsv
	Nabet_parth_cell_line_anno.csv
	Nabet_parth_cell_line_anno_updated.csv
	Nabet_parth_cell_line_anno_updated.tsv
	Nabet_parth_cell_line_anno_updated_new.csv
	Nabet_parth_cell_line_anno_updated_new.tsv
	Nabet_parth_updated.tsv
	Nat_Commun_RNAseq_sample_list_for_Rajesh_20230612.xlsx
	Neuronal_IFN_gamma_liu_nmf.tiff
	New_BRCA_matrix.csv
	NucleoSIF-AH-Davis-NCI-18 samples (6 human-12 mouse)-CHIP-WOBI-NVUS2021050508_V2.xlsx
	OF306.pdf
	OIG4..jpeg
	ONCECUT1_longitudinal_0059.png
	ONECUT1_high_liver_met_vs_low_TF_no_liver_sum_score.png
	OS_Survival_by_Cluster_KM_with_risk_table.tiff
	OS_survival_plot_updated.tiff
	October_2022.pdf
	Online Services - myMVA.pdf
	Open To Start Support Session (1).zip
	Open To Start Support Session 2.app/
	Open To Start Support Session.app/
	PBMC_seu.RData
	PCA.png
	PCA_ATAC.png
	PCA_bi.png
	PCA_color_new_atac_july18.jpg
	PCA_color_raw_data_july_19.jpg
	PCA_pairplot.png
	PCA_plot_loading.png
	PCA_plot_top1percent.png
	PCA_plot_top1percent_MAD.png
	PCA_scree_plot_top1percent.png
	PCA_scree_plot_top1percent_MAD.png
	PDX.png
	PDX_atac_narrow/
	PDX_bonta_remove_figure2_berzin_df.tsv
	PDX_figure_cell_line_genes.tiff
	PDX_figure_cell_line_genes_log2_norm.tiff
	PDX_figure_cell_line_genes_updated.tiff
	PDX_figure_curated_gene_PNAS_Zscore.tiff
	PDX_figure_curated_gene_PNAS_logTPM.tiff
	PDX_hypoxia.png
	PDX_hypoxia_selected_pathways.png
	PDX_sensescence.png
	PEPCO Bill.pdf
	PFS_Survival_by_Cluster_KM_with_risk_table.tiff
	PFS_survival_plot.tiff
	PFS_survival_plot_updated.tiff
	PHS_EIR_Ver_150623_ PD_rajesh signed.docx
	PIIS2589750021002740.pdf
	PILOT_RNA_Seq_Tumor_Data.xlsx
	PILOT_RNA_Seq_Tumor_Data_ssGSEA.tsv
	PLX038 ATM  0215 final final.docx
	PLX038 ATM  0215 final final_NT20220218.docx
	PL_IP_TPM_anon.xlsx
	PL_IP_clinical_anon.xlsx
	POLD3-RNF169 Fusion Patient Info and Neoantigenicity.xlsx
	POLD3-RNF169.txt
	POLD3-RNF169_cDNA.docx
	POLD3_RNF169.docx
	POLD3_RNF169.xlsx
	POLD3_drugs.jpeg
	POLD3_plot.svg
	POLR2A.png
	POU2F2_batch1.png
	POU5F1.tsv
	PPT_Merck.pdf
	PR.docx
	PROX1_high_liver_met_vs_low_TF_no_liver_sum_score.png
	PROX1_longitudinal_0059.png
	PR_vs_HPD_PD_absLog2FC0.5_padj0.05_DEGs.tsv
	PXL_20211213_230047769.PORTRAIT.jpg
	PXL_20221115_014406606.jpeg
	Parth_NES_signature.tsv
	Parth_gene_list_Nov_14.xlsx
	PayOnline -OSM _Online School Management_Details.pdf
	Piyush_APPLICATION FORM FOR INDIAN PASSPORT_ARN_22-2002021430.pdf
	Piyush_Passport_renewal.pdf
	PoW- Fraction of total (student grades).tiff
	Population.csv
	Presentation1.pptx
	Pritee Smith.vcf
	Priyanka_updated_CV.pdf
	Proof_NT20220330.pdf
	Q-185302_POLD3_LongRead Panel .pdf
	QC analysis report.pdf
	RA-022_cell_lines_RawCountFile_rsemgenes_log2_TMM_FPKM.xlsx
	RA22.ajit_dataset.tsv
	RA22.protein.coding.tsv
	RA22.xlsx
	RA22_gene.csv
	RASGRF1 Fusions Activate Oncogenic RAS Signaling and Confer Sensitivity to MEK Inhibition .pdf
	REACTOME_INTERLEUKIN_2_FAMILY_SIGNALING.v2024.1.Hs.gmt
	REACTOME_INTERLEUKIN_2_SIGNALING.v2024.1.Hs.gmt
	REACTOME_REGULATED_NECROSIS.v2023.2.Hs.gmt
	RELA.png
	REVIEW.docx
	RKO_293T_HAP1 RNAseq raw counts.xlsx
	RK_Biography.docx
	RLF_MYCL_hg19.bed
	RNA.csv
	RNA.rawcount.subsetted.protein.coding.txt
	RNA_liver_other_sig.csv
	RNA_subsetted_TPM.tsv
	RNA_subsetted_ne_score.tsv
	RNA_subsetted_ne_score_august_12.tsv
	RNA_subsetted_ne_score_august_19.tsv
	RNA_subsetted_vinod.tsv
	RNAseq from ClinOmics.xlsx
	RNAseq_variable_genes_heatmap.pdf _ Powered by Box.html
	RSW_Project_V1.docx
	RStudio-2022.02.0-443.dmg
	RStudio-2022.07.2-576.dmg
	RStudio-2023.12.1-402.dmg
	RU1065C_for_heatmap.csv
	RU1138_all.tsv
	RU1138_top20.csv
	RU426B.tsv
	RU426B_top20.csv
	R_learning/
	R_studio_biowulf.txt
	Rajaa/
	Rajaa_sheet_ATAC.xlsx
	Rajesh Kumar Receipt.pdf
	Rajesh.png
	Rajesh_4ob.R
	Rajesh_Bioinformatics_Boss_Presentation.pptx
	Rajesh_Kumar_Consulting_Agreement_signed.pdf
	Rajesh_Slide.pptx
	Rajesh_bio.docx
	Rajesh_cluster_2_CTRP_drug_activity_NT20241102.pptx
	Rajesh_tax_form.pdf
	Rapid Autopsy CHiPSeq-ATACseq batch1 Manifest.xlsx
	Rapid genome editing by CRISPR-Cas9-POLD3 fusion.pdf
	Rapid identification of genomic structural variations with nanopore sequencing           enables blood-based cancer monitoring .pdf
	Research-CV-Templates-Download-Word.zip
	Research-CV-Templates-Download-Word/
	Resource Table_May2024_R2.docx
	Responses_to_reviewer_DDT.docx
	Return-to-Work-Guidance (1).pdf
	Review paper  Comments.docx
	ReviewCompliedDocument_Raghav, et al.docx
	Reviewer Questionnaire_Raghav, et al.docx
	Room_rent/
	Rplot 11.29.08 AM.png
	Rplot.tiff
	Rplot01.tiff
	Rplot02.pdf
	Rplot02.tiff
	Rplot03.tiff
	Rplot04.tiff
	Rplot05.pdf
	Rplot06.pdf
	Rplot07.pdf
	Rplot08.pdf
	Rplot09.pdf
	Rplot10.tiff
	Rplot11.pdf
	Rplot12.pdf
	Rplot13.pdf
	Rplot14.pdf
	Rplot15.pdf
	Rplot16.pdf
	Rplot17.pdf
	Rplot18.pdf
	Rplot19.pdf
	Rplot20.pdf
	Rplot21.pdf
	Rplot22.pdf
	Rplot23.pdf
	Rplot24.pdf
	Rplot25.pdf
	Rplot26.pdf
	Rplot27.pdf
	Rplot28.pdf
	Rplot29.pdf
	Rplot30.pdf
	Rplot31.pdf
	Rplot32.pdf
	Rplot33.pdf
	Rplot34.pdf
	Rplot35.pdf
	Rplot36.pdf
	Rplot37.pdf
	Rplot38.pdf
	Rplot39.pdf
	Rplot40.pdf
	Rplot41.pdf
	Rplot42.pdf
	Rplot43.pdf
	Rplot44.pdf
	Rplot45.pdf
	Rplot46.pdf
	Rplot47.pdf
	Rplot48.pdf
	Rplot49.pdf
	Rplot50.pdf
	Rplot51.png
	Rplot52.png
	Rplot52_copy.png
	Rplot53.png
	Rplot54.png
	RsubReadcounts-TheRawCounts.csv
	SC.tsv
	SCAF2229_cell_cycle_regress_difference_out.rds
	SCAF2326.pptx
	SCAF2326_cell.png
	SCAF2326_cell_cycle_regress_difference_out_resolution_1.rds
	SCAF2447_Donor_1_filtered_feature_bc_matrix.h5
	SCAF2497_positive_marker_gene_significant.csv
	SCCL_gene_list.xlsx
	SCL.fasta
	SCLC Mapping Tumor and TME Mastersheet_2062023.xlsx
	SCLC _ATAC_classification_manuscript_02102025.docx
	SCLC gene fusions 11042022.pptx
	SCLC-cfChIP_nature_medicine_submission.docx
	SCLC.html
	SCLC_240221.html
	SCLC_ATAC_Sep_27.pptx
	SCLC_Fusion_distribution.png
	SCLC_RxbeyondIO_seminars.pdf
	SCLC_TME_Manuscript_Methods_May 2024_PanadaR2.docx
	SCLC_Thomas_RNA_samples.xlsx
	SCLC_bam_files.xlsx
	SCLC_fusion_mapped_oncoKB.txt
	SCLC_fusion_mapped_oncoKb_list.txt
	SCLC_gene_signature_sept13.xlsx
	SCLC_sample_distribution.png
	SCLC_tuft_like.pptx
	SPlice_Best.R
	SRR8639221.csv
	SRR8639221.xls
	SRR8652085.csv
	SRR8652085.xls
	SRR8670710.csv
	SRR8670710.xls
	STEMNESS.tiff
	Sample sheet CS028104 CS029023 and CS029575parth.xlsx
	Sample-Letters-of-Recommendation.pdf
	SampleLetterTravel.doc
	Samples for spatial transcriptomics.xlsx
	ScienceDirect_files_01Dec2024_17-53-54.598.zip
	ScienceDirect_files_01Dec2024_17-53-54.598/
	ScienceDirect_files_06Mar2024_16-16-33.280.zip
	ScienceDirect_files_06Mar2024_16-16-33.280/
	ScienceDirect_files_11Dec2023_18-18-36.410.zip
	ScienceDirect_files_11Dec2023_18-18-36.410/
	ScienceDirect_files_11Dec2024_21-55-46.183.zip
	ScienceDirect_files_11Dec2024_21-55-46.183/
	ScienceDirect_files_11Feb2025_19-00-07.608.zip
	ScienceDirect_files_11Feb2025_19-00-07.608/
	ScienceDirect_files_18Jan2024_00-43-23.252.zip
	ScienceDirect_files_18Jan2024_00-43-23.252/
	ScienceDirect_files_27Feb2024_14-59-38.952.zip
	ScienceDirect_files_27Feb2024_14-59-38.952/
	ScienceDirect_files_30Jun2022_16-17-24.275/
	September_2022.pdf
	Sesenscene_liu_nmf.tiff
	Signed_Raghav, et al_Book Head Contract Inc Ltd BV 972970.docx.pdf
	Spatial_cell_reports_medicine.zip
	Spatial_cell_reports_medicine/
	Splice_ML.R
	Splice_Study.R
	SpotifyInstaller.zip
	SraRunTable_phs.csv
	Starbucks eGift Cards from CashStar.pdf
	Stem Cell_Suggested_Reviewers.docx
	Stem cell_10-10-2022.docx
	Stemcell_genesets.csv
	Stemcell_genesets[56].csv
	Stemness_HPD_vs_NonHPD.png
	Stemness_HPD_vs_NonHPD_cell_line.png
	Stemness_berzin_pdx.tiff
	Stemness_liu_nmf.tiff
	Stemness_liu_pdx.tiff
	SubtypeData Bretts trial.xlsx
	Supplementary figures- Chromothripsis.pdf
	Supplementary_Data.pdf
	Supplier Payee Onboarding Form (Rajesh Kumar).xlsx
	Surface_targets.xlsx
	Surface_targets_Barzin.tiff
	Surface_targets_Liu.tiff
	Surface_targets_PDX.tiff
	Surface_targets_cell_line.tiff
	Survival_Cluster1_vs_Others_KM_with_risk_table.tiff
	Survival_by_Cluster_KM.tiff
	Survival_by_Cluster_KM_with_risk_table.tiff
	Survival_by_Liu_Cluster_KM_with_risk_table.tiff
	Svg10.svg
	TCS_Interview_PPT.pdf
	TFBSPILOT.csv
	TFBSPILOT.tsv
	TF_peaks/
	TGFBR_expression.pptx
	TGFB_UP.V1_UP.v2023.2.Hs.gmt
	TGF_beta_HOD_vs_Non_HPD/
	TGF_beta_HPD_vs_Non_HPD.png
	TGF_beta_HPD_vs_Non_HPD_cell_line.png
	TMB.pptx
	TME_Liverspecific.csv
	TME_tumor.csv
	TMM.txt
	TMSCLC.png
	TMSCLC.tsv
	TMSCLC_P0_P1_P3_RNAID.xlsx
	TP53_RB1_NE.csv
	TP53_RB1_NE.tsv
	TPM.count.protein.coding.log2.norm.tsv
	TPM.count.protein.coding.tsv
	TPMCountFile_rsemgenes_1.txt
	TPMCountFile_rsemgenes_log2(1+TPM)_NT20240611.xlsx
	TPM_Merged_File.R
	TPM_normalized_coverages.tsv
	TPMcalc_rawCounts.tsv
	TPMcalc_zscored.tsv
	TPMcalc_zscorednorm_parth_gene.tsv
	TPMcalc_zscorednorm_parth_gene_transposed.tsv
	TTD.tiff
	TTD_database.tsv
	TWIST1.tsv
	ThomasLab_RNA_PDXOnly.xlsx
	ThomasProject_expression.count.tsv
	ThomasProject_expression.count.zip
	Thomas_RNASeq_log2_TMM_FPKM_for_cfCHiPseq_20210616.xlsx
	Thomas_RNAseq_all_data.xlsx
	Timberland Returns.pdf
	Tumor_Methylation_Collaborators.xlsx
	Tumor_Proteomics.csv
	UMAP.csv
	UMAP_disease_region.png.pdf
	UMAP_plot_example1.png
	UMAP_plot_example11.png
	UMAP_plot_example12.png
	UMAP_plot_example2.png
	UMAP_top1.csv
	UMD_cover_letter.pdf
	USA996219993.pdf
	USA996219993_CourierLabel.pdf
	Unconfirmed 852599.crdownload
	Vaccine appointment confirmation - CVS Pharmacy.pdf
	Vaishali_review_outline.docx
	VennDiagram.2022-08-31_14-11-25.log
	VennDiagram.2022-08-31_14-16-13.log
	Vinod_Figure_3.pptx
	ViralFusionSeq/
	WGS_boundless_bio_data_transferred.txt
	WGS_boundless_bio_data_transferred_WGS_alone.txt
	WNT_berzin_pdx.tiff
	WNT_berzin_pdx_sig.tiff
	WNT_ssGSEA_PDX.tiff
	WNT_ssGSEA_PDX_sig.tiff
	WNT_ssGSEA_cell_line.tiff
	WNT_ssGSEA_cellline_sig.tiff
	WhatsApp Image 2022-10-04 at 12.59.19 PM.jpeg
	WhatsApp Image 2024-08-28 at 3.28.48 PM.jpeg
	Whyte_et_al_2013_SEs_genes.csv
	With Great Power Comes Great Responsibility  High-Dimensional Spectral Flow Cytometry to Support Clinical Trials.pdf
	YAP1.chipSeqPks.3.cell.lines.xlsx
	YAP1_batch1.png
	YAP_TAZ_berzin_pdx.tiff
	YAP_TAZ_signature_ssGSEA.tsv
	YAP_TAZ_signature_ssGSEA_cell_line.tsv
	Yang_RNA_seq.pptx
	after.treatment.NAPY.df.transposed.tsv
	after_treatment.log2.tpm.1.NE.tsv
	after_treatment.log2.tpm.1.tsv
	ajit_dataset.xls
	ajit_figure.png
	ajit_gene.tsv
	ajit_phone.pdf
	all_CS_number_sample_ID.xlsx
	all_RNA_seq_data.xlsx
	all_atac_file.xlsx
	all_atac_graph.tsv
	all_bam.txt
	all_common.pdf
	all_common.png
	all_consensus_peaks.png
	all_fusion_common/
	all_fusion_numbers.xlsx
	all_gene.txt
	all_paper_combined.pdf
	all_sample.xlsx
	all_sclc_rna_samples_TPM_57622_genes.tsv
	all_tar_files.xlsx
	alrification.pdf
	anjali_epitope_pipeline.rar
	anno.tsv
	annotation.txt
	annotation_file.csv
	antiharasment.pdf
	appointment.ics
	appointment_tomorrow.ics
	atNIH_2024_10_8_12_37_2_AA_Results.xlsx
	atac.seq.2.16.23.pptx
	atest.tsv
	atri_study_exp_tbl.xlsx
	aug_Advertisment_for_the_post_of_Deputy_Scientific_Officer.docx
	aws_cli_install_and_upload_instructions.pdf
	azam_data.txt
	bank_statement.pdf
	bar.tsv
	bar1.tsv
	bar2.tsv
	bar3.tsv
	barzin_cell_surface_targets.tiff
	barzin_hypoxia.png
	barzin_hypoxia_selected_pathways.png
	barzin_sankey.svg
	barzin_sankey_Jan31.svg
	basal_new_Cell_Line.tiff
	basal_new_PDX.tiff
	basal_new_barzin.tiff
	batch_1_2_DELFI.xlsx
	before.treatment.NAPY.df.transposed.tsv
	before_treatment.log2.tpm.1.NE.tsv
	before_treatment.log2.tpm.1.tsv
	berzin_NE_nonNE.tiff
	berzin_metadata.xlsx
	bomgar-scc-w05c30wfx5w8xeix7xexx5jgz1jhyg5zfxeegdc40jc90.dmg
	book_chapter.xlsx
	boundless_bio_data_transferred.txt
	boundless_bio_data_transferred_RNA.txt
	boxplot.tiff
	boxplot.tsv
	br_22_3_1931_PDF.pdf
	brett_df_NE_NonNE_with_subtype2.tsv
	brett_df_protein_coding.csv
	brett_df_protein_coding.tsv
	brett_df_raw.xlsx
	bubble.tsv
	bubble_top1.tsv
	bubble_top5000.tsv
	cafgenelist.txt
	cancerGeneList.tsv
	cart_DAR139766_202412111704.krt
	casella_cellular_senescence.rds
	ccle_cell_line_NEv2_features.tiff
	ccle_cell_line_cluster_split.tiff
	ccle_cell_line_cluster_split_bold.tiff
	ccle_cell_line_cluster_split_bold_updated.tiff
	ccle_cell_line_cluster_split_bold_updated_log2_TPM.tiff
	ccle_cell_line_cluster_split_bold_updated_new.tiff
	ccle_cell_line_cluster_split_ordered.tiff
	ccle_cell_line_cluster_split_ordered_bold.tiff
	ccle_cell_line_cluster_split_ordered_log2.tiff
	ccle_cell_line_custom_color.tiff
	ccle_cell_line_custom_color_new.tiff
	ccle_cell_line_custom_color_new_october_9.tiff
	ccle_cell_line_custom_color_new_october_9_new.tiff
	ccle_cell_line_custom_color_new_today.tiff
	ccle_cell_line_custom_color_new_today_2.tiff
	ccle_cell_line_metadata.tsv
	ccle_cell_line_protein_coding_genes.tsv
	ccle_figure_curated_gene_PNAS_Zscore.tiff
	ccle_figure_curated_gene_PNAS_Zscore_2.tiff
	cell lines in SCLC.csv
	cell_cycle_score_genes.txt
	cell_line_NFKB.xlsx
	cell_line_STEMNESS.tiff
	cell_line_TF.docx
	cell_line_fusion.xlsx
	cell_line_hypoxia.png
	cell_line_hypoxia_selected_pathways.png
	cell_line_pdx_new.pdf
	cell_line_stemness.tsv
	cell_line_updated.pdf
	cell_paper.pdf
	cell_type_graph.tsv
	cell_type_graph_2.tsv
	cell_types.tsv
	certificate_2022.jpeg
	certificate_2023.jpg
	changeofaddressform.pdf
	charlie.txt
	chat_martin.txt
	chiori_KIF18A.pptx
	chirayoo_NE_NonNE.xlsx
	chr_arms.bed
	chris_LMNA/
	chris_LMNA_figure_august_29.png
	chris_chipseq_metadata.xlsx
	chris_gsea.tsv
	chris_test.tsv
	chromatin landscape based enhancer patterns and IO response.pdf
	circRNA/
	circminer.txt
	circos.png
	circular_salman.pdf
	classifying_berzin_new.R
	clinical_benefits_vs_HPD_signature.tiff
	clinical_benefits_vs_No_signature.tiff
	clstr1.immune.tsv
	clstr2.immune.deenriched.tsv
	clstr2.immune.tsv
	clstr3.immune.tsv
	cluster15.txt
	cluster15_all.txt
	cluster1_2_3_NES_immune_C7_Msigdb.tsv
	cluster1_2_metadata.cls
	cluster1_chromvar_TF.tsv
	cluster1_depth.tsv
	cluster1_motif.tiff
	cluster1_motif_name.tsv
	cluster1_signature.tsv
	cluster1_target_genes.tsv
	cluster1_unique.bed
	cluster1_vs_2_hallmark.tiff
	cluster2.tsv
	cluster2_all.tsv
	cluster2_chromvar_TF.tsv
	cluster2_depth.tsv
	cluster2_depth_new.tsv
	cluster2_motif.tiff
	cluster2_motif_name.tsv
	cluster2_signature.tsv
	cluster2_target_genes.tsv
	cluster2_top_motif.tsv
	cluster2_unique.bed
	cluster3.tsv
	cluster3_all.tsv
	cluster3_chromvar_TF.tsv
	cluster3_motif.tiff
	cluster3_motif_name.tsv
	cluster3_signature.tsv
	cluster3_target_genes.tsv
	cluster3_tf_heatmap_kelly.tiff
	cluster3_top_motif.tsv
	cluster_1_2_3_cell_line_chromvar_TF.xlsx
	cluster_heatmap_df.csv
	clusters_sig_df.tsv
	clustinfo.tsv
	combined_cluster_plots.tiff
	combined_fastq_info.csv
	comments_respinse_covid-19.docx
	common_ccle_SE_gene.tsv
	common_ccle_SE_gene_top_50.tsv
	comparison.tsv
	computational vaccinology.xlsx
	consensus.pdf
	consensusCluster_matrix/
	consensus_parth_sep11.Rmd
	consensus_plot_DESeq_patient_info_biopsy_new2.png
	consensus_plot_mad_new.png
	consensus_plot_mad_patient_info.png
	consensus_plot_mad_try.png
	consensus_top1.csv
	consensus_top1_copy.tsv
	consensusmatrix.tsv
	cont.tsv
	content.txt
	content.txt.zip
	context.tsv
	contt.tsv
	conttt.tsv
	corr.png
	counseling.jpeg
	count.tsv
	counts.csv
	counts.tsv
	counts_1.tsv
	counts_salman.tsv
	countss.tsv
	countsss.tsv
	counttt.tsv
	crc-22-0168-s01.docx
	cricker_run.csv
	cross_cor.tsv
	ctDNA plasma samples sent to Israel (1).xlsx
	ctDNA plasma samples sent to Israel new.xlsx
	ctDNA plasma samples sent to Israel.xlsx
	cutandrun_bigwig/
	d4nr04417g.pdf
	data1.txt
	data10.tsv
	data_NCI-DTP SCLC_exp.txt
	data_NCI-DTP SCLC_exp.zip
	data_integrated_features.jpg
	data_shared_sheet.xlsx
	data_to_be_transferred.xlsx
	dataframe_enriched_term.tsv
	delphine_data.csv
	depmaplong_data.tsv
	deseq_george.R
	df1.tsv
	df2.tsv
	df3.tsv
	dhimolea_diapause_100_up.rds
	diffbind.xlsx
	distal_chipseeker_top1.tiff
	distal_chipseeker_top2.tiff
	distal_chipseeker_top_4000.tiff
	distal_chipseeker_top_5000.tiff
	distal_science_top1.tiff
	distal_science_top2.tiff
	distal_science_top_150.tiff
	distal_science_top_300.tiff
	donut.tsv
	dotplot.tsv
	dotplot2.tsv
	dotplot3.tsv
	download (1).ics
	download.ics
	drive-download-20240317T020552Z-001.zip
	drive-download-20240317T020552Z-001/
	drosphila_example_de.csv
	ecDNA manuscript 04262022.CWSMIA.docx
	ecDNA manuscript 04262022.docx
	enrichment_plot_Cluster2_Proliferating_basal_cell.tiff
	enrichment_plot_Cluster2_TCA_CYCLE_SENESCENCE.tiff
	ensemble.tsv
	ensemble_cp.tsv
	epitope_predicted.tsv
	example_input.zip
	example_input/
	f1.txt
	f1040nr.pdf
	f17.txt
	fatdestroyer_0.pdf
	feature.heatmap.jpg
	feature.heatmap10.jpg
	feature.heatmap2.jpg
	feature.heatmap3.jpg
	feature.heatmap4.jpg
	feature.heatmap5.jpg
	feature.heatmap6.jpg
	feature.heatmap7.jpg
	feature.heatmap8.jpg
	feature.heatmap9.jpg
	featurecount.xlsx
	fedex 0113.pdf
	figeno-1.4.0.tar.gz
	figeno-1.4.0/
	file_ftd.csv
	file_manifest.csv
	filtered3.tsv
	filtered_motif_dotplot.tiff
	filtered_motif_dotplot_within_cluster.tiff
	final_circular.R
	final_directory_structure.txt
	finspect/
	first.txt
	first_bkp.txt
	footnotes_NCI-DTP SCLC_exp.csv
	for_grep.txt
	for_parth.xlsx
	forest-plot.tiff
	forest-plot_ATAC.tiff
	forest-plot_ATAC_2.tiff
	forest-plot_ATAC_3.tiff
	forest-plot_Barzin.tiff
	forest-plot_Barzin_Rx_1B.tiff
	forest-plot_Gay.tiff
	forest-plot_Gay_Rx_1B.tiff
	forest-plot_PDX_Rx_1B.tiff
	forest-plot_Rx_1B.tiff
	forest-plot_new.tiff
	forest_plot.tiff
	forest_plot_colored.tiff
	fragment length.png
	ftd_umap_data.csv
	fusion_Nobu.xlsx
	fusions.pdf
	gProfiler_hsapiens_10-29-2022_2-22-48 AM.csv
	gProfiler_hsapiens_7-31-2024_12-34-06 PM.csv
	gProfiler_hsapiens_7-31-2024_12-35-34 PM.csv
	gProfiler_hsapiens_7-31-2024_12-36-13 PM.csv
	gProfiler_hsapiens_7-31-2024_12-51-39 PM.csv
	gene.tiff
	geneInfo.csv
	gene_df.tsv
	gene_iD_ensmbl.xlsx
	gene_list.txt
	genes_refseq.hg19.bed
	george_all_fusion.xlsx
	george_data_ids_genomes.xlsx
	george_final.txt
	george_final_may02_2024.txt
	go30081_EGA_clinical_biomarkerdata_anonymized_pass (1).xlsx
	go30081_EGA_clinical_biomarkerdata_anonymized_pass.numbers
	go30081_EGA_clinical_biomarkerdata_anonymized_pass.xlsx
	go30081_anonymized_tpm_pass.numbers
	go30081_anonymized_tpm_pass.xlsx
	go_gsea.tsv
	golub.csv
	gsea.tsv
	gsea_gene_sets.rds
	gsea_m_4000.csv
	gsets.txt
	guidance.jpeg
	h.all.v2022.1.Hs.symbols.gmt
	h.all.v2023.2.Hs.symbols.gmt
	h.all.v2024.1.Hs.symbols.gmt
	hallmark.png
	hallmark.rds
	hallmark[35].rds
	hallmark_enrichment_plot_new.pdf
	hallmark_enrichment_results_new.csv
	heatma.R
	heatmap.R
	heatmap_correlation_complex.tiff
	hg19-blacklist.v2.bed
	home.docx
	homer_analysis.xlsx
	homo_sapiens.v104.hg38.gff3
	human_protein_liver.rds
	iTunes12.8.3.dmg
	icons8-star-24.png
	id.txt
	ijerph-09-02444.pdf
	ijms-23-03369.pdf
	image001.png
	image002.png
	image003.png
	image_parth.png
	immunecells Validation cohort.xlsx
	infercnv.png
	integrated_cell.tsv
	integrated_cell_2.tsv
	integrated_cell_3.tsv
	integrated_scRNA.pptx
	inter_intra_fusion.xlsx
	invite.ics
	israel_dataset.csv
	israel_dataset.tsv
	israel_dataset_log2_tpm_plus1.csv
	israel_nature_genetics/
	istockphoto-1297657670-612x612.jpeg
	jre-8u321-macosx-x64.dmg
	just_breathe.jpeg
	khanproc_fastq.swarm
	kisspng-bhavra-allahabad-chandra-shekhar-azad-july-23-hind-wife-5ac0bc7e137339.6590616415225806060797.jpg
	kmeans_new.pdf
	latency.tsv
	lates_figure.png
	leave.docx
	legends.docx
	legends_CM_RK.docx
	legends_RK.docx
	list_remain.txt
	liver_data.xlsx
	liver_like_gene_sets.txt
	liver_mets_pdx.png
	log2_tpm_1_cell_line.csv
	log2_tpm_1_cell_line.tsv
	log2_tpm_1_cell_line_bkp.csv
	loli.tsv
	lollipops-1.5.2/
	lollipops-v1.5.2-mac64/
	m_4840fig1.jpeg
	macs_peak_homer_annot.zip
	macs_peak_homer_annot/
	matplotlib-1.5.0-np110py35_0/
	md5value_duplicate_check.csv
	md5value_duplicate_check_august_07.csv
	mean_exp.tsv
	mean_exp_cp.tsv
	mellisa.csv
	mellisa_ne_score.csv
	mellisa_new_score.csv
	mendeley-reference-manager-2.109.0-x64.dmg
	merged_PILOTRNA_tumor_zscores.xlsx
	metadata.csv
	metadata1.csv
	metadata2.csv
	metadata_SCLC _with diagnosis_MLA.xlsx
	metadata_SCLC.xlsx
	metadata_SCLC_new.xlsx
	metadata_for_Rajaa.xlsx
	metadata_for_kelley.xlsx
	metadata_piyush.csv
	mmc2.xlsx
	mmc3.xlsx
	mmerged_BAX.tsv
	mmerged_TGFBR1.tsv
	modified_ccle_cell_line_cluster_split.tiff
	motif_calculation.xlsx
	motif_df.tsv
	motif_dotplot_with_table.tiff
	motif_plot_cluster1.tiff
	motif_plot_cluster2.tiff
	motif_plot_cluster3.tiff
	motiffAnalysis-seurat-report.pdf
	mountains-190055_1280.jpg
	mouse.LV.RNA.cluster.rds
	mqc_21_fragment_lengths.png
	multivariate_analysis_results_gayeetal-CHEMOIOCHORT only (1).xlsx
	multivariate_analysis_results_gayeetal_CHEMOIOCHORT_only.xlsx
	multivariate_figure.pptx
	nature_geentics_validation_cohort.xlsx
	nature_geentics_validation_cohort_MA unclear samples.xlsx
	nci_sclc_viper_ne_diffact160.pdf
	nci_sclc_viper_ne_diffexp160.pdf
	ncomms12619-s2.xls
	ne_score_brett.tsv
	ne_score_brett_TP53_RB1_NE.tsv
	neuron_gene.gmt
	neuron_genes.txt
	new_file.csv
	new_gsea.tsv
	no of peak per sample.png
	nonNE_vs_SCLC.tsv
	nonNE_vs_SCLC_transposed.tsv
	nonNE_vs_others.tsv
	nonNE_vs_others_transposed.tsv
	normalization_script.zip
	nosine Monophosphate Dehydrogenase Dependence in a Subset of Small Cell Lung Cancers.pdf
	nucleo.txt
	oncofuse-1.1.1 2/
	oncofuse-1.1.1/
	oncofuse.xlsx
	oncokb.txt
	oncoplot_Daryl.svg
	output_3.tiff
	output_4_z_scored.tiff
	output_5_z_scored.tiff
	parental.lmd.bmd.heatmap.others.jpg
	parental_LMD_Gen1_Gen2.csv
	parental_LMD_gen1_gen2_metadata.tsv
	parental_LMD_gen1_gen2_metadata_copy.tsv
	parth.xlsx
	parth_NES.png
	parth_NES_new.png
	parth_Tumor_TME/
	parth_scRNA.zip
	parth_scRNA/
	paul-maurizio-cv.pdf
	pbmc3k_filtered_gene_bc_matrices.tar.gz
	pdx.rank3.TF.targets.aracne/
	pdx.rank3.cluster1.motif.txt
	pdx.rank3.cluster2.motif.txt
	pdx.rank3.cluster3.motif.txt
	pdx_rank3_metadata.tsv
	pdx_rank3_metadata_bonta_removed.tsv
	peak1.tsv
	peak2.tsv
	peak3.tsv
	peak_counts_boxplot.tiff
	percentage_file.tsv
	pharos data download/
	phd_vs_postdoc.png
	phenodata.csv
	phs003628_NT20240712_RK.xlsx
	piyush_dos/
	plot_zoom_png.png
	plot_zoom_png.sb-654ff044-v8ySQR
	pnas.1818210116.sapp.pdf
	pnas.1818210116.sd01 (1).xlsx
	pnas.1818210116.sd01.xlsx
	pnas.201204406.pdf
	pnas.201204406si.pdf
	png/
	pngtree-phoenix-fire-red-bird-3d-ai-image_15695749.jpg
	pone.0018378.s001.doc
	positive_marker_gene.csv
	ppt.pptx
	preprints202401.1989.v1.pdf
	prj_39354.ngc
	project_review_report.docx
	promoter_top1.tiff
	promoter_top2.tiff
	promoter_top_1000.tiff
	promoter_top_2000.tiff
	proof_documents_state_id.pdf
	proteomics-sdrf.tsv
	publication.bib
	publication.csv
	qPCR.pptx
	q_gsea_go.tsv
	q_gsea_multiple.tsv
	qpcr.xlsx
	quartile_norm.pl
	r-cheat-sheet.pdf
	rajesh.jpg
	rajesh_11.jpeg
	rajesh_biodata_cum_cover_letter_postdoc (1).pdf
	rajesh_biodata_cum_cover_letter_postdoc.pdf
	rajesh_paper_citations.csv
	rank3.pdx.cluster1.alone.logFC_1.pval_0.05.csv
	rank3.pdx.cluster1_GO.tsv
	rank3.pdx.cluster1_GO_top_10.tsv
	rank3.pdx.cluster2.alone.logFC_1.pval_0.05.csv
	rank3.pdx.cluster2_GO.tsv
	rank3.pdx.cluster2_GO_sig.tsv
	rank3.pdx.cluster3.alone.logFC_1.pval_0.05.csv
	rank3.pdx.cluster3_GO.tsv
	rat.ss.LV.RNA.cluster.rds
	raw_count_parental_LMD_Gen1_Gen2.csv
	raw_counts.featureCounts.txt
	raw_coverages.tsv
	raw_tmm_fpkm_batch_corrected.csv
	reiboot-mac_11726185967413801301.dmg
	report-due-date.ics
	repstress_score_DMS_273.tsv
	ridhi.jpeg
	rlf.csv
	rna.matched.atac.homer.xlsx
	rna_cluster_sig_diff_terms.csv
	rna_cluster_sig_diff_terms_new.csv
	rna_cluster_sig_diff_terms_new_2.csv
	rna_cluster_sig_diff_terms_new_updated.csv
	rsem_gene.tsv
	rsem_gene_bkp.tsv
	rsem_gene_output.tsv
	rsfs20150105.pdf
	s41467-022-29517-9.pdf
	s41591-021-01448-w.pdf
	sample sheet.xlsx
	sample.tsv
	sample1.tsv
	sample2.tsv
	sample2_bkp.tsv
	sample_1.txt
	samplesheet.csv
	sankey.tiff
	sankey_latest.png
	sankeymatic_20220518_142911_5400x3600.png
	sankeymatic_20220518_145546_5400x3600.png
	sankeymatic_20241220_132332 1.tif
	sankeymatic_20241220_132332.tif
	saul_senescent_cells.rds
	scRNA analysis_PD_September 2023_For ATAC and ITH projects.pptx
	scRNA analysis_PD_September 2023_For ATAC and ITH projects_Rajeshcorrected_9132023.pptx
	scRNA_ITH_ATAC_RAJESH project_12092023.xlsx
	scRNA_cell_cluster_count.xlsx
	scRNA_integrated_markers.csv
	scRNA_sep15.pptx
	schizo.png
	sciB_vrdl_nm007056_MSc1.pdf
	science.aay0256-2.pdf
	science.abe1505.pdf
	science.abe1505_tables_s1_to_s17 2/
	science.abe1505_tables_s1_to_s17.zip
	science.abe1505_tables_s1_to_s17/
	science_slides/
	sclc_bam_to_sorted_bam.txt
	sclc_fusion_comparison_other_databases/
	sclc_genesets_new.gmt
	sclc_genesets_new.txt
	sclc_jiang.xlsx
	sclc_ucologne_2015_clinical_data (5).tsv
	sdbbootcampletters of recommend.docx
	sdbbootcampletters of recommend.pdf
	second.txt
	second_batch_atac.xlsx
	segal_adult_fetal_hepatobiliary.rds
	senescence_Liu_pdx.tiff
	senescence_berzin_pdx_sig.tiff
	senescence_pathways_ssGSEA_PDX.tsv
	senescence_pathways_ssGSEA_cell_line.tsv
	signature.png
	signature_hypoxia_geneset.numbers
	signature_table.tsv
	single_cell.R
	smallGenesFile.csv
	solar-correlation-map-R-master/
	ssGSEA.git
	ssGSEA_NE_SignatureEtc.Rmd
	st_bar.tsv
	stem_cell_book.xlsx
	stem_cell_no.tsv
	stem_cell_related.gmt
	sticky.txt
	surv.tsv
	survival.tsv
	survival.xlsx
	survival_1_vs_2.tsv
	survival_3_vs_2.tsv
	survival_analysis.xlsx
	survival_multivariate.tsv
	survival_new.tsv
	survival_new.xlsx
	survival_new_jan_30.tsv
	survival_new_jan_30.xlsx
	susovan.jpg
	teaching.jpeg
	test.csv
	test.tsv
	test/
	test1.tsv
	test2.tsv
	test_bam/
	test_data.tsv
	test_data_2.tsv
	test_heatmap.tsv
	test_heatmap_annotation.tsv
	test_rmd/
	test_script.sh
	tf_rank_within_clusters.csv
	tf_rank_within_clusters/
	tf_target.rds
	tf_target[35].rds
	tmm_fpkm_batch_corrected_annotation.tsv
	tong.tsv
	tong_flowcell.tsv
	tong_other_flowcell.tsv
	tongwu_data_file.xlsx
	tongwu_data_transfer.xlsx
	top1.5_tpm.tsv
	top1.5_tpm_umap.csv
	top1000_tpm.tsv
	top1000_tpm_umap.csv
	top100_tpm.tsv
	top100_tpm_umap.csv
	top1500_tpm.tsv
	top1500_tpm_umap.csv
	top1_tpm.tsv
	top1_tpm_consensus.csv
	top1_tpm_umap.csv
	top2.5_tpm.tsv
	top2.5_tsv_umap.csv
	top2000_tpm.tsv
	top2000_tpm_umap.csv
	top2_tpm.tsv
	top2_tpm_umap.csv
	top3000_tpm.tsv
	top3000_tpm_umap.csv
	top3_tpm.tsv
	top3_tpm_umap.csv
	top5000_all_PDX_RA_natched_comparison_K5.pdf
	top500_tpm.tsv
	top500_tpm_umap.csv
	top5_tpm.tsv
	top5_tpm_umap.csv
	transcriptomics_and_sequencing_analysis_of_gene.6.pdf
	transferred_2.txt
	tried_figure.png
	try.txt
	tumor.cluster.dotplot.jpg
	tumor.cluster.dotplot2.jpg
	tumor.cluster.dotplot3.jpg
	tumor_normal_paired_check.csv
	unibbb (1).xlsx
	unibbb.xlsx
	univariate_analysis_results_Rx_1B.xlsx
	untitled.png
	updated
	validation_cohort_uniform.xlsx
	vcf_subset.zip
	vcf_subset/
	venn.png
	venn.png.2022-05-24_14-39-36.log
	venn.png.2022-05-24_14-40-27.log
	venn_intersection.tsv
	venn_intersection1.tsv
	venn_plot_parth.png
	venn_plot_parthh.png
	venn_plot_parthh.sb-654ff044-hbMMSC
	venn_plot_parthhh.png
	vierstra.sm.pdf
	vinod_doc/
	webR-shiny-blog.png
	without_doublets.jpg
	without_doublets_malignant_only.jpg
	without_doublets_malignant_only.ver.2.jpg
	without_doublets_malignant_only.ver.3.jpg
	yugam.pdf
	~$all_atac_file.xlsx

nothing added to commit but untracked files present (use "git add" to track)
[kumarr9@NCI-02296922-ML Downloads]$ git add .
^C
[kumarr9@NCI-02296922-ML Downloads]$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	.ATAC_code.R.swp
	.DS_Store
	.RData
	.Rapp.history
	.Rhistory
	.com.google.Chrome.3sSuNe
	.com.google.Chrome.3zqFtU
	.com.google.Chrome.6s2WG9
	.com.google.Chrome.7A80hE
	.com.google.Chrome.DklR0S
	.com.google.Chrome.STyJYg
	.com.google.Chrome.UVAxWx
	.com.google.Chrome.X3xxSY
	.com.google.Chrome.aoONB3
	.com.google.Chrome.kLYS5n
	.com.google.Chrome.rpbTZG
	.com.google.Chrome.srUxex
	.com.google.Chrome.x284mB
	.localized
	.parth_gene.txt.swp
	.png.ps
	.rank3.pdx.cluster1.motif.txt.swp
	.surv.tsv.swp
	.test.txt.swp
	.v.txt.swp
	1-s2.0-S0092867423013351-mmc6.xlsx
	1-s2.0-S0167779923000884-main.pdf
	1-s2.0-S107476132200084X-main.pdf
	1-s2.0-S2590262824000856-main.pdf
	10_16_23_SCLC_Cell_lines.xlsx
	1161_BatchCode.zip
	120-1201942_chandrashekhar-azad-hd-png-download.png
	15-C-0145 Dates added- 7-31-24.xlsx
	15_c_0145.tsv
	1708955629381SR4BdZw05tqgahM0.pdf
	1_3_23_RNA_Seq_datasets.xlsx
	1_StudyConfig_RK.docx
	1_top_100_reactome_modified.tiff
	2-15-2022-DTB Lab Roster .pdf
	20220801_135505_resized.jpeg
	20220801_135514_resized.jpeg
	2024.11.13.623500v1.full.pdf
	2024.11.13.623500v1.full_copy.pdf
	216_upregulated_SCLC-Inflamed_genes.txt
	2_top_100_reactome_modified.tiff
	2year.csv
	2year.tsv
	3_top_100_reactome_modified.tiff
	3p-Neutrophils-UMAP-Projection.csv
	3p-Neutrophils-clusters.csv
	3rdquarter.pdf
	41467_2019_9940_MOESM11_ESM.xlsx
	41467_2019_9940_MOESM5_ESM.xlsx
	41467_2022_32552_MOESM4_ESM.xlsx
	41586_2015_BFnature14664_MOESM72_ESM.xlsx
	41586_2018_393_MOESM3_ESM.zip
	41586_2018_393_MOESM3_ESM/
	41586_2018_393_MOESM4_ESM.xlsx
	41586_2020_2922_MOESM3_ESM.xlsx
	41586_2020_2922_MOESM4_ESM.xlsx
	41586_2020_2922_MOESM5_ESM.xlsx
	41586_2020_2922_MOESM6_ESM.xlsx
	47.pdf
	6314734.jpeg
	86918-Free SeeSaw PowerPoint Template.pptx
	A406a_ATAC_S0_L001_R1_001.fastq
	A406a_ATAC_S0_L001_R1_001.fastq.gz
	AACR_abstract_CM.docx
	AACR_abstract_RK_PD_1142025.docx
	ALB.tiff
	ALDOB.png
	ALDOB.tiff
	ARACNE_HPD_vs_NonHPD.png
	ARACNe_TF_motifs.xlsx
	ARCHIBUS Web Central.pdf
	ASCL1.n.NEUROD1.chipSeq.TFBS.Borromeo.2016.xlsx
	ASCL1.png
	ASCL1_batch1.png
	ASCO-Caris-2022-Molecular-correlates-of-Delta-like-ligand-3-DLL3-expression-in-neuroendocrine-neoplasms-NENs.pdf
	ATAC 01042025_RK_new.pptx
	ATAC-seq workshop-20220606T180539Z-001.zip
	ATAC.png
	ATAC.tsv
	ATAC.xlsx
	ATAC_12_10_2024_Main.pptx
	ATAC_Fig_Draft_May_09_2024.pptx
	ATAC_Final_ppt.pptx
	ATAC_PCAA.png
	ATAC_PCA_all_samples.png
	ATAC_PCA_top_one.png
	ATAC_PDXmatch_Rajesh_PD_Signatures_2.txt
	ATAC_PDXmatch_Rajesh_PD_Signatures_2_new.txt
	ATAC_RNA.csv
	ATAC_RNA.xls
	ATAC_RNA_data.tsv
	ATAC_RNA_raw_count.csv
	ATAC_TPM_standard_deviation.csv
	ATAC_all_sample_peaks_sorted.narrowPeak
	ATAC_cluster.png
	ATAC_cluster_sig_ssGSEA.csv
	ATAC_cluster_sig_ssGSEA.tsv
	ATAC_cluster_sig_ssGSEA_2.csv
	ATAC_cluster_sig_ssGSEA_anno.tsv
	ATAC_count.csv
	ATAC_count1.csv
	ATAC_data/
	ATAC_data_distribution_with_biopsy_site_NT20220721.xlsx
	ATAC_discussion_sep07.docx
	ATAC_enrichment.png
	ATAC_feature_distribution.xlsx
	ATAC_feature_distribution_copy.xlsx
	ATAC_feature_igv.png
	ATAC_feature_npg_color.png
	ATAC_flow.png
	ATAC_manuscript_author_list.docx
	ATAC_only.png
	ATAC_only.tsv
	ATAC_peak_TSS.png
	ATAC_screenshot.png
	ATAC_seq_workshop/
	ATAC_signature_cell_line.tiff
	ATAC_signature_cell_line_second_list.tiff
	ATAC_signature_cell_line_try.tiff
	ATAC_venn_upset.png
	ATACgraph/
	ATOH1.xlsx
	AU_21_162_INFO.xlsx
	AXL.tsv
	AXL_cp.tsv
	AXL_cp_new.tsv
	Accepted and waiting list (1).xlsx
	Accepted and waiting list.xlsx
	Addition of Author Request in Schultz et Al. EMBO Molecular Medecine 2023 15-e17313.pdf-RE_DA_ZWO signed (002).pdf
	Advertisement Details (1).pdf
	Advertisement Details.pdf
	Affiliations_aacr_abstract (1).docx
	Affiliations_aacr_abstract.docx
	Agenda this week.docx
	Ajit_adheretn_vs_suspension.pptx
	Ajit_parental_vs_animal.pptx
	AllDataWTA.meta.new.tumor_only.csv
	All_chr_num_DS_splice.txt
	Amira_Liiver_mets_parental.pptx
	Ananda_GiftCard20241227133615.pdf
	Anish-NCI BBI Collaboration Meeting_09OCT2024.pptx
	Anjali Ver - Current and Emerging Approaches in Vaccine Design and Delivery.docx
	Anjali_paper.pdf
	Annexure A_final.docx
	Annexure_III_Authors list.xlsx
	Archetype_signatures_ssGSEA.csv
	Archetype_signatures_ssGSEA[56].csv
	AsynonymousTSS_clinical_characteristics_updated_20210803.xlsx
	August_2022.pdf
	Author_response_cancer cell_June 2023_AT_PDant.docx
	Authors list by RK-PR.xlsx
	Authorship_Change_Form.pdf
	BPM_distant_promoter_27Ac 1.tiff
	BPM_distant_promoter_27Ac.tiff
	Barzin_log_norm.png
	Barzin_sankey_most_updated.svg
	Barzin_sankey_most_updated.tif
	Basic_Study_Information_Sheet_RK.pdf
	Batch0_DNA_Nobu era.xlsx
	BillImage.pdf
	Biowulf data.pptx
	Biowulf_Collaborators_MNAnnotated.xlsx
	Book10.xlsx
	Book11.xlsx
	Book16.xlsx
	Book2.xlsx
	Book3.xlsx
	Boundless_bio_RNA_data.tsv
	BoxToolsInstaller.dmg
	CANCER_TYPE_EDA.html
	CCLE_DGE_result.csv
	CCLE_file.txt
	CCLE_fusions.csv
	CCLE_gsea.tsv
	CCLE_gsea_new.tsv
	CCLE_mutations.csv
	CCLE_test.tiff
	CCLE_test_new.tiff
	CCP_Cuzick.rds
	CCRSF/
	CENPA_genes (002).pptx
	CENPA_genes.pptx
	CIRI_Full_v2.1.1.jar
	CIRI_v2.0.5.zip
	CIRI_v2.0.5/
	CLCVsharma.pdf
	CLuster_2_Anylasis .pptx
	CS035635_Thomas_Schultz_FinalReport.docx
	CSEMLabGuidelines2021WELCOME LETTER.docx
	CSID_NCI thomas large dataset.xlsx
	CTM2-12-e1060-s002.docx
	Caffeine treatments [Comparision].xlsx
	Califano_VIPER.pptx
	Cancer research_Notch mutant GEMM.xlsx
	Cell_Line_DTB_NES.tiff
	Cell_Line_NES.tiff
	Cell_Line_senescence_updated.tsv
	Cell_Line_with_name.png
	Cell_line.png
	Cell_line_annotation_nciSclc.txt
	Cell_line_correlation_new.tiff
	Cell_line_heatmap_new_try (1).tiff
	Cell_line_heatmap_new_try (2).tiff
	Cell_line_heatmap_new_try.tiff
	Cell_line_heatmap_new_try_2.tiff
	Cell_line_heatmap_new_try_celline.tiff
	Cell_line_heatmap_new_try_celline_Dec11.tiff
	Cell_line_heatmap_new_try_celline_Dec11_bold.tiff
	Cell_line_heatmap_new_try_celline_Dec11_bold_updated.tiff
	Cell_line_heatmap_new_try_celline_Nov27.tiff
	Cell_line_heatmap_new_try_celline_reordered.tiff
	Cell_line_log_norm.png
	Cell_line_sensescence.png
	Cell_line_sensesnce.png
	Cell_line_stemness_TPM_zscore.tsv
	Cell_line_stemness_TPMcalc_zscored.tsv
	Cell_line_stemness_Z_score_logTPM.tsv
	Cellchat_R_4.3.ipynb
	Cells to Juanma.docx
	Certificate.pdf
	ChEA_2022_table.txt
	Chip_only.png
	Chip_only.tsv
	Chipseq.pptx
	Chris_LMNA.xlsx
	Clinical-characteritics-AT-March9-review.xlsx
	Clinical_annot_August24_NCI_SCLC.xlsx
	Clinical_benefit_Yes_No_absLog2FC0.5_padj0.05_DEGs_hallmark.csv
	Clinker/
	Cluster_1_2_3_relaxed.xlsx
	Combined Bulk_4_2022_Rajesh_list_all_RNA_seq_data.xlsx
	Computational Tools for Stem Cell Biology _ Enhanced Reader.pdf
	Consensusmatrix.Rmd
	Copy of ATAC_Fig_Draft_May_09_2024_PD3_june9_2024.pptx
	Copy of Copy of cfChiPseq_list_Pt_IDs_NT20230327_PD_editsant (002) Rajesh anon.xlsx
	Copy of Metadata_For_Parth.xlsx
	Copy of TMSCLC_P0_P1_P3_RNAID(37).xlsx
	Copy of TMSCLC_P0_P1_P3_RNAID.xlsx
	Copy of autopsy_samples_info.xlsx
	Copy of cfChiPseq_list_Pt_IDs_NT20230327_PD_editsant.xlsx
	Copy of sample sheet (002).xlsx
	Copy_of_Sample_HPD_Chirau_CB (1).xlsx
	Copy_of_Sample_HPD_Chirau_CB.xlsx
	Copy_of_Sample_HPD_Chirau_CB_1.31.2.xlsx
	Copy_of_Sample_HPD_Chirau_CB_2.5.25 1 (1).xlsx
	Copy_of_Sample_HPD_Chirau_CB_2.5.25 1 (2).xlsx
	Copy_of_Sample_HPD_Chirau_CB_2.5.25 1.xlsx
	Correlation_justin.xls
	Covplot.png
	Current and Emerging Approaches in Vaccine Design.docx
	Cyrus Driving School 2.pdf
	Cyrus Driving School.pdf
	CytoTRACE_0.3.3.tar.gz
	Cytoscape_3_10_1_macos_aarch64.dmg
	DBT_early_career_full_proposal (1).docx
	DBT_early_career_full_proposal.docx
	DESeq2.R
	DESeq2_july_31.png
	DGE_cluster2_vs_cluster1_3 1.tsv
	DGE_cluster2_vs_cluster1_3.tsv
	DGE_cluster2_vs_cluster1_3_hallmark_plot.tiff
	DGE_cluster2_vs_cluster1_hallmark_plot.tiff
	DGE_cluster2_vs_cluster3_hallmark_plot.tiff
	DL-002.pdf
	DLL3.png
	DLL3.tiff
	DLL3_new.png
	DLL3_newest.png
	DLL_brain_liver_P1.xlsx
	DMS273.xlsx
	DMS273_137_met_18Ac.bed
	DMS273_137_met_18Ac.seacr.consensus.peak_counts.bed
	DMS273_137_met_27Ac.bed
	DMS273_137_met_27Ac.seacr.consensus.peak_counts.bed
	DRISTHI_PAPER.pdf
	DSP_tumor_stroma_correlation_violin_plot_20211228.pzfx
	DTB EMAIL-02152022.pdf
	DTB_files_fathi.xlsx
	Darryl.png
	Darryl_figure
	Data_Clinical.xlsx
	Delfi plasma with RNAseq samples for Rajesh_NE classifications.xlsx
	Delfin plasma samples hyperprogression autopsy brain mets EGFR prostate .xlsx
	DepMap-Clusters_vs_Dependencies.pptx
	DepMap.tiff
	DepMap_ssGSEA_KEGG_WNT_Priya.tsv
	DepMap_ssGSEA_KEGG_WNT_Priya_NE_only.tsv
	DepMap_subset.tiff
	DepMap_subset_Figure_6.tiff
	Dilli-chalo.jpg
	Discover Card_ Make a Payment Confirmation Printable.pdf
	Discover Card_ Make a Payment Confirmation Printable_May.pdf
	Discover-Statement-20220318-2036.pdf
	Discover-Statement-20230611-6726.pdf
	Discover-Statement-20240218-2036.pdf
	Division of International Services Case Status and Reports_.pdf
	DocumentChecklists2.pdf
	Draft_chapter.docx
	EGA_go30081_20210122_IMp133-subtype_anon_pass.xlsx
	EMS195999-supplement-Data_S1.csv
	EMS195999-supplement-Data_S2.csv
	EMS195999-supplement-Table_S1.xlsx
	EMS195999-supplement-Table_S2.xlsx
	EMS195999-supplement-Table_S3.xlsx
	EMT_Liu.png
	EMT_PDX.png
	EMT_barzin.png
	ENCFF012XAP.bigWig
	ENCFF231FNI.bigWig
	EP_SCLC.pdf
	Enrichr_results_bar.png
	EthicsCert.jpeg
	Example for Rajesh.xlsx
	FASTQ_missing_paired_information.csv
	FATSQ_missing_paired_Information.tsv
	FDA_approved_all.tiff
	FDA_approved_common.tiff
	FDA_aproved_drug_signature.tsv
	FISH for chromosome instability human tissues.pdf
	FOXA1.tiff
	FOXA1_high_liver_met_vs_low_TF_no_liver_sum_score.png
	FOXA1_longitudinal_0059.png
	FOXA3.tiff
	FPKM.txt
	FRA21.bed
	FTD.hg38.genotype_selectedVars_het_chr3.raw
	FTD.hg38.neotype_selectvar.tsv
	Fig.pptx
	Fig4C_heatmap.Rmd
	Fig4C_tumor_SOI_data2.txt
	Figure2C_NES.tiff
	Figure_7_Cluster_2.pptx
	FileZilla 2.app/
	FileZilla.app/
	FileZilla_3.67.0_macos-arm64.app.tar.bz2
	FileZilla_3.67.0_macos-x86.app.tar.bz2
	Finallexapansion.csv
	Flowcell_H3M7HDSX2.tsv
	For_parth_new.xlsx
	Form_Pdf_66.pdf
	Functional_characterization_ATOH_Indicate_metastastic_role_SCLC.xlsx
	Fusion_DTB_comments_ajit.pptx
	Fusion_Functional_Approaches.pptx
	GATA6_high_liver_met_vs_low_TF_no_liver_sum_score.png
	GEO submission_RNAseq_Proteomic.xlsx
	GOBP_NUCLEAR_TRANSPORT.v2023.1.Hs.gmt
	GSE214342_RAW.tar
	GSE214342_RAW/
	GSEA.Rmd
	GSEA_4.3.2.app/
	GSEA_4.3.3 2.app/
	GSEA_4.3.3 3.app/
	GSEA_4.3.3.app/
	GSEA_GOBP_4000.csv
	GSEA_GOBP_4000.xlsx
	GSEA_GOBP_4000SD.txt
	GSEA_MacApp_4.3.3.app.zip
	GSEA_berzin/
	GSEA_fusion_positive_GO_terms
	GSEA_multiple 4000SD genes_summary.txt
	GSEA_multiple_4000_genes.csv
	GSM2550011_RKO_c0011_w0053.CEL
	GSM2550011_RKO_c0011_w0053.CEL.gz
	GSM2550011_RKO_c0011_w0053.sst-rma-gene-full.chp
	GSM2550011_RKO_c0011_w0053.sst-rma-gene-full.chp.gz
	GSM3165679_H1048_POU2F3_CHIP_peaks_filtered.score.gt.500.log.q.gt.20.narrowPeak
	G__Online_Inspire_ReadWriteData_Temp_20211001215822310136386.pdf
	G__Online_Inspire_ReadWriteData_Temp_2021100122002742805404.pdf
	Gavish_malignant_cell_MP.rds
	Gene dependency in Rajesh ATACseq cluster 2_NT20250112.pptx
	Gene_file.txt
	Gene_signature.xlsx
	Gene_signature_new.xlsx
	Genelist_cluster2.xlsx
	George_all.xlsx
	GitHub Desktop.app/
	GitHubDesktop-x64.zip
	HALLMARK_MYC_TARGETS_V1.rds
	HAP1 RNAseq Normalized reads.xlsx
	HES1.png
	HES1.tiff
	HIM-D-23-01091.pdf
	HLA_project_proposal_final_short.pdf
	HNF1A.png
	HNF1A.tiff
	HNF4A.png
	HNF4A.tiff
	HPD Annotation File for Max and Howard_5_30_2023.xlsx
	HPD Annotation File_7_6_2023_deidentified.xlsx
	HPD_Pre_vs_Post.png
	HPD_vs_NonHPD.png
	HPD_vs_Pre_Post_absLog2FC0.5_padj0.05_DEGs.tsv
	HPD_vs_Pre_Post_fewer_sample_absLog2FC0.5_hallmark_log2fold.png
	HPD_vs_Pre_Post_fewer_sample_absLog2FC0.5_hallmark_stat.png
	HPD_vs_Pre_Post_fewer_sample_absLog2FC0.5_padj0.05_DEGs.tsv
	HPD_vs_Pre_Post_fewer_sample_absLog2FC0.5_padj0.05_DEGs_reactome.csv
	HPD_vs_Pre_Post_fewer_sample_absLog2FC0.5_padj0.05_DEGs_reactome_plot.png
	HPD_vs_Pre_Post_fewer_sample_absLog2FC0.5_stemness_log2fold.png
	HPD_vs_non_HPD_Cell_line_signature_signature.png
	HPD_vs_non_HPD_stemness_log2FC.png
	HPD_vs_non_HPD_stemness_stat.png
	HP_Color_LaserJet_Pro_MFP_M282_M285_Series-20231206.dmg
	H_Score.tiff
	H_Score_new_boxplot.tiff
	Handbook of Chemoinformatics - 2003 - Gasteiger.pdf
	Harvard-CV-Templates-Word-Download.zip
	Harvard-CV-Templates-Word-Download/
	Heatmap_ATAC_TSS.png
	Highligh_RajeshTXT.xlsx
	Hope4Genes-master.zip
	Hope4Genes-master/
	I-129 worksheet.pdf
	ICMJE COI Disclosure Form.docx
	IGV_2.11.7.app/
	IGV_2.16.0.app/
	IGV_2.18.2.app/
	IGV_MacApp_2.16.0_WithJava.zip
	IGV_MacApp_2.18.2_WithJava.zip
	IHC_Rajaa.xlsx
	IL-2_Manuscript_Revised_latest_all_modified.docx
	IL-2_Manuscript_Revised_latest_highlighted.docx
	IL2_liu_nmf.tiff
	IL2_paper/
	IMG-20230329-WA0002.jpg
	IMG-20230329-WA0003.jpg
	IMG_3387.jpg
	IMPOWER_gene sets.xlsx
	IMPOWER_gene sets[26].xlsx
	ISCIENCE-D-22-02793_reviewer.pdf
	Immunotherapy of Neuroendocrine Neoplasms- Any Role for the Chimeric Antigen Receptor T Cells?.pdf
	Inferring gene expression from cell-free DNA fragmentation profiles.pdf
	Inspire_faculty_Results_2020.pdf
	Install Spotify.app/
	Integrated object_scRNA_for ATAC project_Rajesh_PD.pptx
	Integrated_scRNA_FOR ATAC Project_Rajesh_PD.xlsx
	JCB_201109100.pdf
	January_2025.pdf
	Jeetu Journey Confirmation.pdf
	Jitesh_Fee_Receipt_3rd_quarter.pdf
	KEGG_TGF_BETA_SIGNALING_PATHWAY.v2023.2.Hs.gmt
	KO_Parenal_Hallmark.png
	Keka-1.3.7.dmg
	Knockdown of IGF2BP3 inhibits the tumorigenesis of gallbladder cancer and modifies tumor microenvironment.pdf
	LaTeXTemplates_freeman-cv_v3.0.zip
	LabWorks.xlsx
	List of Apartment.docx
	Liu.png
	Liu_heatmap.tiff
	Liu_hypoxia.png
	Liu_hypoxia_selected_pathways.png
	Liu_log_norm.png
	Liu_sankey.pptx
	Liu_sankey.svg
	Liu_sankey_Jan31.svg
	Liu_sankey_V4.svg
	Liu_sankey_V5 (1).svg
	Liu_sankey_V5 (2).svg
	Liu_sankey_V5.svg
	Liver_mets_vs_parental_absLog2FC1_hallamrk_hallmark.png
	Liver_mets_vs_parental_absLog2FC1_hallamrk_hallmark_logFold_rank.png
	Liver_mets_vs_parental_absLog2FC1_immune.png
	Liver_mets_vs_parental_absLog2FC1_immune_neg.png
	Liver_mets_vs_parental_absLog2FC1_immune_pos.png
	Liver_mets_vs_parental_absLog2FC1_padj0.05_DEGs.tsv
	MC Proposal 2021.docx
	MDD.pdf
	MDD.png
	MISC-Sep-21-2020.pdf
	MYCL_batch1.png
	MYC_batch1.png
	Manan_data/
	Manan_data_all.csv
	Manan_tpm_normalized_protein_coding_only.tsv
	Maryland ID.pdf
	Master ATAC Submission File.xlsx
	Master CHIP Submission File.xlsx
	Master RNA Submission File.xlsx
	Master sheet_NCI THOMAS_352.txt
	Mastersheet_NCI THOMAS_352_PD_892022_START.xlsx
	Matrix_data_Dr_teiff.xlsx
	May31_NEC_subtype.pptx
	Mendeley-Desktop-1.19.3-OSX-Universal.dmg
	MicrosoftTeams-image (1).png
	MicrosoftTeams-image.png
	Modified_Vaishali_Review1.docx
	Molecular classification of small cell lung cancer subtypes- characteristics, prognostic factors, and clinical translation.pdf
	Msigdb_STEM_CELLS_BUSSLINGER.v2023.2.Hs .gmt
	NAPY.tsv
	NAPY_annotation.xlsx
	NAPY_targets.txt
	NCI SCLC patients without MRN.xlsx
	NCI-SCLC-326-ARACNE-GeneRegNet_new.xlsx
	NCI_Kumar_POLD3_RNF169_TE-93150521_LongRead_hg19.zip
	NCI_Kumar_POLD3_RNF169_TE-93150521_LongRead_hg19/
	NCI_Kumar_POLD3_RNF169_TE-94461624_4X_RNA.zip
	NCI_Kumar_POLD3_RNF169_TE-94461624_4X_RNA/
	NCI_Thomas_429_raw_count.csv
	NCI_Thomas_439_batch_info.tsv
	NCI_Thomas_439_protein_coding_only_TPM_normalized (1).tsv
	NCI_Thomas_439_protein_coding_only_TPM_normalized.tsv
	NCI_Thomas_495_protein_coding_only_TPM_normalized (1).csv
	NCI_Thomas_495_protein_coding_only_TPM_normalized.csv
	NCI_huizi_autopsy_SCLC_liver_others_GSEA_Tachmatzidi_liver_tf_20220522.pptx
	NCI_signatures.tsv
	NCI_thomas_439.tsv
	NCI_thomas_439_df2.tsv
	NCI_thomas_439_matched.tsv
	NES/
	NEUROD1_batch1.png
	NE_Dr_Thomas.xlsx
	NE_NonNE.pdf
	NE_Non_NE.tsv
	NE_liu_nmf.tiff
	NE_nonNE.xlsx
	NFE2L2.xlsx
	NFKB1.png
	NFKB_all.png
	NFKB_all.tsv
	NGS_data_analysis_workshop/
	NIH Information Security and Management Awareness Refresher.pdf
	NIH SCLC Batch 2 Lab Data 15AUG2023 (1).xlsx
	NIHMS1002246-supplement-4.pdf
	NIHMS1624031-supplement-1624031_Supp_Tab4.xlsx
	NIHMS1641013-supplement-1.pdf
	NIHMS958978-supplement-3.xlsx
	NIH_Intramural_Request_Form_Permission_Access_GDS_Data.pdf
	NIH_file_prefixes_2024-03-20_V1_Collaborators.xlsx
	NIH_map.jpeg
	NKcell.pptx
	NLGL3.png
	NMF.png
	NMF_K3_new_legend_updated.tiff
	NOTCH_genesets.csv
	NOTCH_genesets[66].csv
	NR5A2_high_liver_met_vs_low_TF_no_live_sum_score.png
	NTE.pptx
	NVUS2022081004.xlsx
	Nabet_parth.tsv
	Nabet_parth_cell_line_anno.csv
	Nabet_parth_cell_line_anno_updated.csv
	Nabet_parth_cell_line_anno_updated.tsv
	Nabet_parth_cell_line_anno_updated_new.csv
	Nabet_parth_cell_line_anno_updated_new.tsv
	Nabet_parth_updated.tsv
	Nat_Commun_RNAseq_sample_list_for_Rajesh_20230612.xlsx
	Neuronal_IFN_gamma_liu_nmf.tiff
	New_BRCA_matrix.csv
	NucleoSIF-AH-Davis-NCI-18 samples (6 human-12 mouse)-CHIP-WOBI-NVUS2021050508_V2.xlsx
	OF306.pdf
	OIG4..jpeg
	ONCECUT1_longitudinal_0059.png
	ONECUT1_high_liver_met_vs_low_TF_no_liver_sum_score.png
	OS_Survival_by_Cluster_KM_with_risk_table.tiff
	OS_survival_plot_updated.tiff
	October_2022.pdf
	Online Services - myMVA.pdf
	Open To Start Support Session (1).zip
	Open To Start Support Session 2.app/
	Open To Start Support Session.app/
	PBMC_seu.RData
	PCA.png
	PCA_ATAC.png
	PCA_bi.png
	PCA_color_new_atac_july18.jpg
	PCA_color_raw_data_july_19.jpg
	PCA_pairplot.png
	PCA_plot_loading.png
	PCA_plot_top1percent.png
	PCA_plot_top1percent_MAD.png
	PCA_scree_plot_top1percent.png
	PCA_scree_plot_top1percent_MAD.png
	PDX.png
	PDX_atac_narrow/
	PDX_bonta_remove_figure2_berzin_df.tsv
	PDX_figure_cell_line_genes.tiff
	PDX_figure_cell_line_genes_log2_norm.tiff
	PDX_figure_cell_line_genes_updated.tiff
	PDX_figure_curated_gene_PNAS_Zscore.tiff
	PDX_figure_curated_gene_PNAS_logTPM.tiff
	PDX_hypoxia.png
	PDX_hypoxia_selected_pathways.png
	PDX_sensescence.png
	PEPCO Bill.pdf
	PFS_Survival_by_Cluster_KM_with_risk_table.tiff
	PFS_survival_plot.tiff
	PFS_survival_plot_updated.tiff
	PHS_EIR_Ver_150623_ PD_rajesh signed.docx
	PIIS2589750021002740.pdf
	PILOT_RNA_Seq_Tumor_Data.xlsx
	PILOT_RNA_Seq_Tumor_Data_ssGSEA.tsv
	PLX038 ATM  0215 final final.docx
	PLX038 ATM  0215 final final_NT20220218.docx
	PL_IP_TPM_anon.xlsx
	PL_IP_clinical_anon.xlsx
	POLD3-RNF169 Fusion Patient Info and Neoantigenicity.xlsx
	POLD3-RNF169.txt
	POLD3-RNF169_cDNA.docx
	POLD3_RNF169.docx
	POLD3_RNF169.xlsx
	POLD3_drugs.jpeg
	POLD3_plot.svg
	POLR2A.png
	POU2F2_batch1.png
	POU5F1.tsv
	PPT_Merck.pdf
	PR.docx
	PROX1_high_liver_met_vs_low_TF_no_liver_sum_score.png
	PROX1_longitudinal_0059.png
	PR_vs_HPD_PD_absLog2FC0.5_padj0.05_DEGs.tsv
	PXL_20211213_230047769.PORTRAIT.jpg
	PXL_20221115_014406606.jpeg
	Parth_NES_signature.tsv
	Parth_gene_list_Nov_14.xlsx
	PayOnline -OSM _Online School Management_Details.pdf
	Piyush_APPLICATION FORM FOR INDIAN PASSPORT_ARN_22-2002021430.pdf
	Piyush_Passport_renewal.pdf
	PoW- Fraction of total (student grades).tiff
	Population.csv
	Presentation1.pptx
	Pritee Smith.vcf
	Priyanka_updated_CV.pdf
	Proof_NT20220330.pdf
	Q-185302_POLD3_LongRead Panel .pdf
	QC analysis report.pdf
	RA-022_cell_lines_RawCountFile_rsemgenes_log2_TMM_FPKM.xlsx
	RA22.ajit_dataset.tsv
	RA22.protein.coding.tsv
	RA22.xlsx
	RA22_gene.csv
	RASGRF1 Fusions Activate Oncogenic RAS Signaling and Confer Sensitivity to MEK Inhibition .pdf
	REACTOME_INTERLEUKIN_2_FAMILY_SIGNALING.v2024.1.Hs.gmt
	REACTOME_INTERLEUKIN_2_SIGNALING.v2024.1.Hs.gmt
	REACTOME_REGULATED_NECROSIS.v2023.2.Hs.gmt
	RELA.png
	REVIEW.docx
	RKO_293T_HAP1 RNAseq raw counts.xlsx
	RK_Biography.docx
	RLF_MYCL_hg19.bed
	RNA.csv
	RNA.rawcount.subsetted.protein.coding.txt
	RNA_liver_other_sig.csv
	RNA_subsetted_TPM.tsv
	RNA_subsetted_ne_score.tsv
	RNA_subsetted_ne_score_august_12.tsv
	RNA_subsetted_ne_score_august_19.tsv
	RNA_subsetted_vinod.tsv
	RNAseq from ClinOmics.xlsx
	RNAseq_variable_genes_heatmap.pdf _ Powered by Box.html
	RSW_Project_V1.docx
	RStudio-2022.02.0-443.dmg
	RStudio-2022.07.2-576.dmg
	RStudio-2023.12.1-402.dmg
	RU1065C_for_heatmap.csv
	RU1138_all.tsv
	RU1138_top20.csv
	RU426B.tsv
	RU426B_top20.csv
	R_learning/
	R_studio_biowulf.txt
	Rajaa/
	Rajaa_sheet_ATAC.xlsx
	Rajesh Kumar Receipt.pdf
	Rajesh.png
	Rajesh_4ob.R
	Rajesh_Bioinformatics_Boss_Presentation.pptx
	Rajesh_Kumar_Consulting_Agreement_signed.pdf
	Rajesh_Slide.pptx
	Rajesh_bio.docx
	Rajesh_cluster_2_CTRP_drug_activity_NT20241102.pptx
	Rajesh_tax_form.pdf
	Rapid Autopsy CHiPSeq-ATACseq batch1 Manifest.xlsx
	Rapid genome editing by CRISPR-Cas9-POLD3 fusion.pdf
	Rapid identification of genomic structural variations with nanopore sequencing           enables blood-based cancer monitoring .pdf
	Research-CV-Templates-Download-Word.zip
	Research-CV-Templates-Download-Word/
	Resource Table_May2024_R2.docx
	Responses_to_reviewer_DDT.docx
	Return-to-Work-Guidance (1).pdf
	Review paper  Comments.docx
	ReviewCompliedDocument_Raghav, et al.docx
	Reviewer Questionnaire_Raghav, et al.docx
	Room_rent/
	Rplot 11.29.08 AM.png
	Rplot.tiff
	Rplot01.tiff
	Rplot02.pdf
	Rplot02.tiff
	Rplot03.tiff
	Rplot04.tiff
	Rplot05.pdf
	Rplot06.pdf
	Rplot07.pdf
	Rplot08.pdf
	Rplot09.pdf
	Rplot10.tiff
	Rplot11.pdf
	Rplot12.pdf
	Rplot13.pdf
	Rplot14.pdf
	Rplot15.pdf
	Rplot16.pdf
	Rplot17.pdf
	Rplot18.pdf
	Rplot19.pdf
	Rplot20.pdf
	Rplot21.pdf
	Rplot22.pdf
	Rplot23.pdf
	Rplot24.pdf
	Rplot25.pdf
	Rplot26.pdf
	Rplot27.pdf
	Rplot28.pdf
	Rplot29.pdf
	Rplot30.pdf
	Rplot31.pdf
	Rplot32.pdf
	Rplot33.pdf
	Rplot34.pdf
	Rplot35.pdf
	Rplot36.pdf
	Rplot37.pdf
	Rplot38.pdf
	Rplot39.pdf
	Rplot40.pdf
	Rplot41.pdf
	Rplot42.pdf
	Rplot43.pdf
	Rplot44.pdf
	Rplot45.pdf
	Rplot46.pdf
	Rplot47.pdf
	Rplot48.pdf
	Rplot49.pdf
	Rplot50.pdf
	Rplot51.png
	Rplot52.png
	Rplot52_copy.png
	Rplot53.png
	Rplot54.png
	RsubReadcounts-TheRawCounts.csv
	SC.tsv
	SCAF2229_cell_cycle_regress_difference_out.rds
	SCAF2326.pptx
	SCAF2326_cell.png
	SCAF2326_cell_cycle_regress_difference_out_resolution_1.rds
	SCAF2447_Donor_1_filtered_feature_bc_matrix.h5
	SCAF2497_positive_marker_gene_significant.csv
	SCCL_gene_list.xlsx
	SCL.fasta
	SCLC Mapping Tumor and TME Mastersheet_2062023.xlsx
	SCLC _ATAC_classification_manuscript_02102025.docx
	SCLC gene fusions 11042022.pptx
	SCLC-cfChIP_nature_medicine_submission.docx
	SCLC.html
	SCLC_240221.html
	SCLC_ATAC_Sep_27.pptx
	SCLC_Fusion_distribution.png
	SCLC_RxbeyondIO_seminars.pdf
	SCLC_TME_Manuscript_Methods_May 2024_PanadaR2.docx
	SCLC_Thomas_RNA_samples.xlsx
	SCLC_bam_files.xlsx
	SCLC_fusion_mapped_oncoKB.txt
	SCLC_fusion_mapped_oncoKb_list.txt
	SCLC_gene_signature_sept13.xlsx
	SCLC_sample_distribution.png
	SCLC_tuft_like.pptx
	SPlice_Best.R
	SRR8639221.csv
	SRR8639221.xls
	SRR8652085.csv
	SRR8652085.xls
	SRR8670710.csv
	SRR8670710.xls
	STEMNESS.tiff
	Sample sheet CS028104 CS029023 and CS029575parth.xlsx
	Sample-Letters-of-Recommendation.pdf
	SampleLetterTravel.doc
	Samples for spatial transcriptomics.xlsx
	ScienceDirect_files_01Dec2024_17-53-54.598.zip
	ScienceDirect_files_01Dec2024_17-53-54.598/
	ScienceDirect_files_06Mar2024_16-16-33.280.zip
	ScienceDirect_files_06Mar2024_16-16-33.280/
	ScienceDirect_files_11Dec2023_18-18-36.410.zip
	ScienceDirect_files_11Dec2023_18-18-36.410/
	ScienceDirect_files_11Dec2024_21-55-46.183.zip
	ScienceDirect_files_11Dec2024_21-55-46.183/
	ScienceDirect_files_11Feb2025_19-00-07.608.zip
	ScienceDirect_files_11Feb2025_19-00-07.608/
	ScienceDirect_files_18Jan2024_00-43-23.252.zip
	ScienceDirect_files_18Jan2024_00-43-23.252/
	ScienceDirect_files_27Feb2024_14-59-38.952.zip
	ScienceDirect_files_27Feb2024_14-59-38.952/
	ScienceDirect_files_30Jun2022_16-17-24.275/
	September_2022.pdf
	Sesenscene_liu_nmf.tiff
	Signed_Raghav, et al_Book Head Contract Inc Ltd BV 972970.docx.pdf
	Spatial_cell_reports_medicine.zip
	Spatial_cell_reports_medicine/
	Splice_ML.R
	Splice_Study.R
	SpotifyInstaller.zip
	SraRunTable_phs.csv
	Starbucks eGift Cards from CashStar.pdf
	Stem Cell_Suggested_Reviewers.docx
	Stem cell_10-10-2022.docx
	Stemcell_genesets.csv
	Stemcell_genesets[56].csv
	Stemness_HPD_vs_NonHPD.png
	Stemness_HPD_vs_NonHPD_cell_line.png
	Stemness_berzin_pdx.tiff
	Stemness_liu_nmf.tiff
	Stemness_liu_pdx.tiff
	SubtypeData Bretts trial.xlsx
	Supplementary figures- Chromothripsis.pdf
	Supplementary_Data.pdf
	Supplier Payee Onboarding Form (Rajesh Kumar).xlsx
	Surface_targets.xlsx
	Surface_targets_Barzin.tiff
	Surface_targets_Liu.tiff
	Surface_targets_PDX.tiff
	Surface_targets_cell_line.tiff
	Survival_Cluster1_vs_Others_KM_with_risk_table.tiff
	Survival_by_Cluster_KM.tiff
	Survival_by_Cluster_KM_with_risk_table.tiff
	Survival_by_Liu_Cluster_KM_with_risk_table.tiff
	Svg10.svg
	TCS_Interview_PPT.pdf
	TFBSPILOT.csv
	TFBSPILOT.tsv
	TF_peaks/
	TGFBR_expression.pptx
	TGFB_UP.V1_UP.v2023.2.Hs.gmt
	TGF_beta_HOD_vs_Non_HPD/
	TGF_beta_HPD_vs_Non_HPD.png
	TGF_beta_HPD_vs_Non_HPD_cell_line.png
	TMB.pptx
	TME_Liverspecific.csv
	TME_tumor.csv
	TMM.txt
	TMSCLC.png
	TMSCLC.tsv
	TMSCLC_P0_P1_P3_RNAID.xlsx
	TP53_RB1_NE.csv
	TP53_RB1_NE.tsv
	TPM.count.protein.coding.log2.norm.tsv
	TPM.count.protein.coding.tsv
	TPMCountFile_rsemgenes_1.txt
	TPMCountFile_rsemgenes_log2(1+TPM)_NT20240611.xlsx
	TPM_Merged_File.R
	TPM_normalized_coverages.tsv
	TPMcalc_rawCounts.tsv
	TPMcalc_zscored.tsv
	TPMcalc_zscorednorm_parth_gene.tsv
	TPMcalc_zscorednorm_parth_gene_transposed.tsv
	TTD.tiff
	TTD_database.tsv
	TWIST1.tsv
	ThomasLab_RNA_PDXOnly.xlsx
	ThomasProject_expression.count.tsv
	ThomasProject_expression.count.zip
	Thomas_RNASeq_log2_TMM_FPKM_for_cfCHiPseq_20210616.xlsx
	Thomas_RNAseq_all_data.xlsx
	Timberland Returns.pdf
	Tumor_Methylation_Collaborators.xlsx
	Tumor_Proteomics.csv
	UMAP.csv
	UMAP_disease_region.png.pdf
	UMAP_plot_example1.png
	UMAP_plot_example11.png
	UMAP_plot_example12.png
	UMAP_plot_example2.png
	UMAP_top1.csv
	UMD_cover_letter.pdf
	USA996219993.pdf
	USA996219993_CourierLabel.pdf
	Unconfirmed 852599.crdownload
	Vaccine appointment confirmation - CVS Pharmacy.pdf
	Vaishali_review_outline.docx
	VennDiagram.2022-08-31_14-11-25.log
	VennDiagram.2022-08-31_14-16-13.log
	Vinod_Figure_3.pptx
	ViralFusionSeq/
	WGS_boundless_bio_data_transferred.txt
	WGS_boundless_bio_data_transferred_WGS_alone.txt
	WNT_berzin_pdx.tiff
	WNT_berzin_pdx_sig.tiff
	WNT_ssGSEA_PDX.tiff
	WNT_ssGSEA_PDX_sig.tiff
	WNT_ssGSEA_cell_line.tiff
	WNT_ssGSEA_cellline_sig.tiff
	WhatsApp Image 2022-10-04 at 12.59.19 PM.jpeg
	WhatsApp Image 2024-08-28 at 3.28.48 PM.jpeg
	Whyte_et_al_2013_SEs_genes.csv
	With Great Power Comes Great Responsibility  High-Dimensional Spectral Flow Cytometry to Support Clinical Trials.pdf
	YAP1.chipSeqPks.3.cell.lines.xlsx
	YAP1_batch1.png
	YAP_TAZ_berzin_pdx.tiff
	YAP_TAZ_signature_ssGSEA.tsv
	YAP_TAZ_signature_ssGSEA_cell_line.tsv
	Yang_RNA_seq.pptx
	after.treatment.NAPY.df.transposed.tsv
	after_treatment.log2.tpm.1.NE.tsv
	after_treatment.log2.tpm.1.tsv
	ajit_dataset.xls
	ajit_figure.png
	ajit_gene.tsv
	ajit_phone.pdf
	all_CS_number_sample_ID.xlsx
	all_RNA_seq_data.xlsx
	all_atac_file.xlsx
	all_atac_graph.tsv
	all_bam.txt
	all_common.pdf
	all_common.png
	all_consensus_peaks.png
	all_fusion_common/
	all_fusion_numbers.xlsx
	all_gene.txt
	all_paper_combined.pdf
	all_sample.xlsx
	all_sclc_rna_samples_TPM_57622_genes.tsv
	all_tar_files.xlsx
	alrification.pdf
	anjali_epitope_pipeline.rar
	anno.tsv
	annotation.txt
	annotation_file.csv
	antiharasment.pdf
	appointment.ics
	appointment_tomorrow.ics
	atNIH_2024_10_8_12_37_2_AA_Results.xlsx
	atac.seq.2.16.23.pptx
	atest.tsv
	atri_study_exp_tbl.xlsx
	aug_Advertisment_for_the_post_of_Deputy_Scientific_Officer.docx
	aws_cli_install_and_upload_instructions.pdf
	azam_data.txt
	bank_statement.pdf
	bar.tsv
	bar1.tsv
	bar2.tsv
	bar3.tsv
	barzin_cell_surface_targets.tiff
	barzin_hypoxia.png
	barzin_hypoxia_selected_pathways.png
	barzin_sankey.svg
	barzin_sankey_Jan31.svg
	basal_new_Cell_Line.tiff
	basal_new_PDX.tiff
	basal_new_barzin.tiff
	batch_1_2_DELFI.xlsx
	before.treatment.NAPY.df.transposed.tsv
	before_treatment.log2.tpm.1.NE.tsv
	before_treatment.log2.tpm.1.tsv
	berzin_NE_nonNE.tiff
	berzin_metadata.xlsx
	bomgar-scc-w05c30wfx5w8xeix7xexx5jgz1jhyg5zfxeegdc40jc90.dmg
	book_chapter.xlsx
	boundless_bio_data_transferred.txt
	boundless_bio_data_transferred_RNA.txt
	boxplot.tiff
	boxplot.tsv
	br_22_3_1931_PDF.pdf
	brett_df_NE_NonNE_with_subtype2.tsv
	brett_df_protein_coding.csv
	brett_df_protein_coding.tsv
	brett_df_raw.xlsx
	bubble.tsv
	bubble_top1.tsv
	bubble_top5000.tsv
	cafgenelist.txt
	cancerGeneList.tsv
	cart_DAR139766_202412111704.krt
	casella_cellular_senescence.rds
	ccle_cell_line_NEv2_features.tiff
	ccle_cell_line_cluster_split.tiff
	ccle_cell_line_cluster_split_bold.tiff
	ccle_cell_line_cluster_split_bold_updated.tiff
	ccle_cell_line_cluster_split_bold_updated_log2_TPM.tiff
	ccle_cell_line_cluster_split_bold_updated_new.tiff
	ccle_cell_line_cluster_split_ordered.tiff
	ccle_cell_line_cluster_split_ordered_bold.tiff
	ccle_cell_line_cluster_split_ordered_log2.tiff
	ccle_cell_line_custom_color.tiff
	ccle_cell_line_custom_color_new.tiff
	ccle_cell_line_custom_color_new_october_9.tiff
	ccle_cell_line_custom_color_new_october_9_new.tiff
	ccle_cell_line_custom_color_new_today.tiff
	ccle_cell_line_custom_color_new_today_2.tiff
	ccle_cell_line_metadata.tsv
	ccle_cell_line_protein_coding_genes.tsv
	ccle_figure_curated_gene_PNAS_Zscore.tiff
	ccle_figure_curated_gene_PNAS_Zscore_2.tiff
	cell lines in SCLC.csv
	cell_cycle_score_genes.txt
	cell_line_NFKB.xlsx
	cell_line_STEMNESS.tiff
	cell_line_TF.docx
	cell_line_fusion.xlsx
	cell_line_hypoxia.png
	cell_line_hypoxia_selected_pathways.png
	cell_line_pdx_new.pdf
	cell_line_stemness.tsv
	cell_line_updated.pdf
	cell_paper.pdf
	cell_type_graph.tsv
	cell_type_graph_2.tsv
	cell_types.tsv
	certificate_2022.jpeg
	certificate_2023.jpg
	changeofaddressform.pdf
	charlie.txt
	chat_martin.txt
	chiori_KIF18A.pptx
	chirayoo_NE_NonNE.xlsx
	chr_arms.bed
	chris_LMNA/
	chris_LMNA_figure_august_29.png
	chris_chipseq_metadata.xlsx
	chris_gsea.tsv
	chris_test.tsv
	chromatin landscape based enhancer patterns and IO response.pdf
	circRNA/
	circminer.txt
	circos.png
	circular_salman.pdf
	classifying_berzin_new.R
	clinical_benefits_vs_HPD_signature.tiff
	clinical_benefits_vs_No_signature.tiff
	clstr1.immune.tsv
	clstr2.immune.deenriched.tsv
	clstr2.immune.tsv
	clstr3.immune.tsv
	cluster15.txt
	cluster15_all.txt
	cluster1_2_3_NES_immune_C7_Msigdb.tsv
	cluster1_2_metadata.cls
	cluster1_chromvar_TF.tsv
	cluster1_depth.tsv
	cluster1_motif.tiff
	cluster1_motif_name.tsv
	cluster1_signature.tsv
	cluster1_target_genes.tsv
	cluster1_unique.bed
	cluster1_vs_2_hallmark.tiff
	cluster2.tsv
	cluster2_all.tsv
	cluster2_chromvar_TF.tsv
	cluster2_depth.tsv
	cluster2_depth_new.tsv
	cluster2_motif.tiff
	cluster2_motif_name.tsv
	cluster2_signature.tsv
	cluster2_target_genes.tsv
	cluster2_top_motif.tsv
	cluster2_unique.bed
	cluster3.tsv
	cluster3_all.tsv
	cluster3_chromvar_TF.tsv
	cluster3_motif.tiff
	cluster3_motif_name.tsv
	cluster3_signature.tsv
	cluster3_target_genes.tsv
	cluster3_tf_heatmap_kelly.tiff
	cluster3_top_motif.tsv
	cluster_1_2_3_cell_line_chromvar_TF.xlsx
	cluster_heatmap_df.csv
	clusters_sig_df.tsv
	clustinfo.tsv
	combined_cluster_plots.tiff
	combined_fastq_info.csv
	comments_respinse_covid-19.docx
	common_ccle_SE_gene.tsv
	common_ccle_SE_gene_top_50.tsv
	comparison.tsv
	computational vaccinology.xlsx
	consensus.pdf
	consensusCluster_matrix/
	consensus_parth_sep11.Rmd
	consensus_plot_DESeq_patient_info_biopsy_new2.png
	consensus_plot_mad_new.png
	consensus_plot_mad_patient_info.png
	consensus_plot_mad_try.png
	consensus_top1.csv
	consensus_top1_copy.tsv
	consensusmatrix.tsv
	cont.tsv
	content.txt
	content.txt.zip
	context.tsv
	contt.tsv
	conttt.tsv
	corr.png
	counseling.jpeg
	count.tsv
	counts.csv
	counts.tsv
	counts_1.tsv
	counts_salman.tsv
	countss.tsv
	countsss.tsv
	counttt.tsv
	crc-22-0168-s01.docx
	cricker_run.csv
	cross_cor.tsv
	ctDNA plasma samples sent to Israel (1).xlsx
	ctDNA plasma samples sent to Israel new.xlsx
	ctDNA plasma samples sent to Israel.xlsx
	cutandrun_bigwig/
	d4nr04417g.pdf
	data1.txt
	data10.tsv
	data_NCI-DTP SCLC_exp.txt
	data_NCI-DTP SCLC_exp.zip
	data_integrated_features.jpg
	data_shared_sheet.xlsx
	data_to_be_transferred.xlsx
	dataframe_enriched_term.tsv
	delphine_data.csv
	depmaplong_data.tsv
	deseq_george.R
	df1.tsv
	df2.tsv
	df3.tsv
	dhimolea_diapause_100_up.rds
	diffbind.xlsx
	distal_chipseeker_top1.tiff
	distal_chipseeker_top2.tiff
	distal_chipseeker_top_4000.tiff
	distal_chipseeker_top_5000.tiff
	distal_science_top1.tiff
	distal_science_top2.tiff
	distal_science_top_150.tiff
	distal_science_top_300.tiff
	donut.tsv
	dotplot.tsv
	dotplot2.tsv
	dotplot3.tsv
	download (1).ics
	download.ics
	drive-download-20240317T020552Z-001.zip
	drive-download-20240317T020552Z-001/
	drosphila_example_de.csv
	ecDNA manuscript 04262022.CWSMIA.docx
	ecDNA manuscript 04262022.docx
	enrichment_plot_Cluster2_Proliferating_basal_cell.tiff
	enrichment_plot_Cluster2_TCA_CYCLE_SENESCENCE.tiff
	ensemble.tsv
	ensemble_cp.tsv
	epitope_predicted.tsv
	example_input.zip
	example_input/
	f1.txt
	f1040nr.pdf
	f17.txt
	fatdestroyer_0.pdf
	feature.heatmap.jpg
	feature.heatmap10.jpg
	feature.heatmap2.jpg
	feature.heatmap3.jpg
	feature.heatmap4.jpg
	feature.heatmap5.jpg
	feature.heatmap6.jpg
	feature.heatmap7.jpg
	feature.heatmap8.jpg
	feature.heatmap9.jpg
	featurecount.xlsx
	fedex 0113.pdf
	figeno-1.4.0.tar.gz
	figeno-1.4.0/
	file_ftd.csv
	file_manifest.csv
	filtered3.tsv
	filtered_motif_dotplot.tiff
	filtered_motif_dotplot_within_cluster.tiff
	final_circular.R
	final_directory_structure.txt
	finspect/
	first.txt
	first_bkp.txt
	footnotes_NCI-DTP SCLC_exp.csv
	for_grep.txt
	for_parth.xlsx
	forest-plot.tiff
	forest-plot_ATAC.tiff
	forest-plot_ATAC_2.tiff
	forest-plot_ATAC_3.tiff
	forest-plot_Barzin.tiff
	forest-plot_Barzin_Rx_1B.tiff
	forest-plot_Gay.tiff
	forest-plot_Gay_Rx_1B.tiff
	forest-plot_PDX_Rx_1B.tiff
	forest-plot_Rx_1B.tiff
	forest-plot_new.tiff
	forest_plot.tiff
	forest_plot_colored.tiff
	fragment length.png
	ftd_umap_data.csv
	fusion_Nobu.xlsx
	fusions.pdf
	gProfiler_hsapiens_10-29-2022_2-22-48 AM.csv
	gProfiler_hsapiens_7-31-2024_12-34-06 PM.csv
	gProfiler_hsapiens_7-31-2024_12-35-34 PM.csv
	gProfiler_hsapiens_7-31-2024_12-36-13 PM.csv
	gProfiler_hsapiens_7-31-2024_12-51-39 PM.csv
	gene.tiff
	geneInfo.csv
	gene_df.tsv
	gene_iD_ensmbl.xlsx
	gene_list.txt
	genes_refseq.hg19.bed
	george_all_fusion.xlsx
	george_data_ids_genomes.xlsx
	george_final.txt
	george_final_may02_2024.txt
	go30081_EGA_clinical_biomarkerdata_anonymized_pass (1).xlsx
	go30081_EGA_clinical_biomarkerdata_anonymized_pass.numbers
	go30081_EGA_clinical_biomarkerdata_anonymized_pass.xlsx
	go30081_anonymized_tpm_pass.numbers
	go30081_anonymized_tpm_pass.xlsx
	go_gsea.tsv
	golub.csv
	gsea.tsv
	gsea_gene_sets.rds
	gsea_m_4000.csv
	gsets.txt
	guidance.jpeg
	h.all.v2022.1.Hs.symbols.gmt
	h.all.v2023.2.Hs.symbols.gmt
	h.all.v2024.1.Hs.symbols.gmt
	hallmark.png
	hallmark.rds
	hallmark[35].rds
	hallmark_enrichment_plot_new.pdf
	hallmark_enrichment_results_new.csv
	heatma.R
	heatmap.R
	heatmap_correlation_complex.tiff
	hg19-blacklist.v2.bed
	home.docx
	homer_analysis.xlsx
	homo_sapiens.v104.hg38.gff3
	human_protein_liver.rds
	iTunes12.8.3.dmg
	icons8-star-24.png
	id.txt
	ijerph-09-02444.pdf
	ijms-23-03369.pdf
	image001.png
	image002.png
	image003.png
	image_parth.png
	immunecells Validation cohort.xlsx
	infercnv.png
	integrated_cell.tsv
	integrated_cell_2.tsv
	integrated_cell_3.tsv
	integrated_scRNA.pptx
	inter_intra_fusion.xlsx
	invite.ics
	israel_dataset.csv
	israel_dataset.tsv
	israel_dataset_log2_tpm_plus1.csv
	israel_nature_genetics/
	istockphoto-1297657670-612x612.jpeg
	jre-8u321-macosx-x64.dmg
	just_breathe.jpeg
	khanproc_fastq.swarm
	kisspng-bhavra-allahabad-chandra-shekhar-azad-july-23-hind-wife-5ac0bc7e137339.6590616415225806060797.jpg
	kmeans_new.pdf
	latency.tsv
	lates_figure.png
	leave.docx
	legends.docx
	legends_CM_RK.docx
	legends_RK.docx
	list_remain.txt
	liver_data.xlsx
	liver_like_gene_sets.txt
	liver_mets_pdx.png
	log2_tpm_1_cell_line.csv
	log2_tpm_1_cell_line.tsv
	log2_tpm_1_cell_line_bkp.csv
	loli.tsv
	lollipops-1.5.2/
	lollipops-v1.5.2-mac64/
	m_4840fig1.jpeg
	macs_peak_homer_annot.zip
	macs_peak_homer_annot/
	matplotlib-1.5.0-np110py35_0/
	md5value_duplicate_check.csv
	md5value_duplicate_check_august_07.csv
	mean_exp.tsv
	mean_exp_cp.tsv
	mellisa.csv
	mellisa_ne_score.csv
	mellisa_new_score.csv
	mendeley-reference-manager-2.109.0-x64.dmg
	merged_PILOTRNA_tumor_zscores.xlsx
	metadata.csv
	metadata1.csv
	metadata2.csv
	metadata_SCLC _with diagnosis_MLA.xlsx
	metadata_SCLC.xlsx
	metadata_SCLC_new.xlsx
	metadata_for_Rajaa.xlsx
	metadata_for_kelley.xlsx
	metadata_piyush.csv
	mmc2.xlsx
	mmc3.xlsx
	mmerged_BAX.tsv
	mmerged_TGFBR1.tsv
	modified_ccle_cell_line_cluster_split.tiff
	motif_calculation.xlsx
	motif_df.tsv
	motif_dotplot_with_table.tiff
	motif_plot_cluster1.tiff
	motif_plot_cluster2.tiff
	motif_plot_cluster3.tiff
	motiffAnalysis-seurat-report.pdf
	mountains-190055_1280.jpg
	mouse.LV.RNA.cluster.rds
	mqc_21_fragment_lengths.png
	multivariate_analysis_results_gayeetal-CHEMOIOCHORT only (1).xlsx
	multivariate_analysis_results_gayeetal_CHEMOIOCHORT_only.xlsx
	multivariate_figure.pptx
	nature_geentics_validation_cohort.xlsx
	nature_geentics_validation_cohort_MA unclear samples.xlsx
	nci_sclc_viper_ne_diffact160.pdf
	nci_sclc_viper_ne_diffexp160.pdf
	ncomms12619-s2.xls
	ne_score_brett.tsv
	ne_score_brett_TP53_RB1_NE.tsv
	neuron_gene.gmt
	neuron_genes.txt
	new_file.csv
	new_gsea.tsv
	no of peak per sample.png
	nonNE_vs_SCLC.tsv
	nonNE_vs_SCLC_transposed.tsv
	nonNE_vs_others.tsv
	nonNE_vs_others_transposed.tsv
	normalization_script.zip
	nosine Monophosphate Dehydrogenase Dependence in a Subset of Small Cell Lung Cancers.pdf
	nucleo.txt
	oncofuse-1.1.1 2/
	oncofuse-1.1.1/
	oncofuse.xlsx
	oncokb.txt
	oncoplot_Daryl.svg
	output_3.tiff
	output_4_z_scored.tiff
	output_5_z_scored.tiff
	parental.lmd.bmd.heatmap.others.jpg
	parental_LMD_Gen1_Gen2.csv
	parental_LMD_gen1_gen2_metadata.tsv
	parental_LMD_gen1_gen2_metadata_copy.tsv
	parth.xlsx
	parth_NES.png
	parth_NES_new.png
	parth_Tumor_TME/
	parth_scRNA.zip
	parth_scRNA/
	paul-maurizio-cv.pdf
	pbmc3k_filtered_gene_bc_matrices.tar.gz
	pdx.rank3.TF.targets.aracne/
	pdx.rank3.cluster1.motif.txt
	pdx.rank3.cluster2.motif.txt
	pdx.rank3.cluster3.motif.txt
	pdx_rank3_metadata.tsv
	pdx_rank3_metadata_bonta_removed.tsv
	peak1.tsv
	peak2.tsv
	peak3.tsv
	peak_counts_boxplot.tiff
	percentage_file.tsv
	pharos data download/
	phd_vs_postdoc.png
	phenodata.csv
	phs003628_NT20240712_RK.xlsx
	piyush_dos/
	plot_zoom_png.png
	plot_zoom_png.sb-654ff044-v8ySQR
	pnas.1818210116.sapp.pdf
	pnas.1818210116.sd01 (1).xlsx
	pnas.1818210116.sd01.xlsx
	pnas.201204406.pdf
	pnas.201204406si.pdf
	png/
	pngtree-phoenix-fire-red-bird-3d-ai-image_15695749.jpg
	pone.0018378.s001.doc
	positive_marker_gene.csv
	ppt.pptx
	preprints202401.1989.v1.pdf
	prj_39354.ngc
	project_review_report.docx
	promoter_top1.tiff
	promoter_top2.tiff
	promoter_top_1000.tiff
	promoter_top_2000.tiff
	proof_documents_state_id.pdf
	proteomics-sdrf.tsv
	publication.bib
	publication.csv
	qPCR.pptx
	q_gsea_go.tsv
	q_gsea_multiple.tsv
	qpcr.xlsx
	quartile_norm.pl
	r-cheat-sheet.pdf
	rajesh.jpg
	rajesh_11.jpeg
	rajesh_biodata_cum_cover_letter_postdoc (1).pdf
	rajesh_biodata_cum_cover_letter_postdoc.pdf
	rajesh_paper_citations.csv
	rank3.pdx.cluster1.alone.logFC_1.pval_0.05.csv
	rank3.pdx.cluster1_GO.tsv
	rank3.pdx.cluster1_GO_top_10.tsv
	rank3.pdx.cluster2.alone.logFC_1.pval_0.05.csv
	rank3.pdx.cluster2_GO.tsv
	rank3.pdx.cluster2_GO_sig.tsv
	rank3.pdx.cluster3.alone.logFC_1.pval_0.05.csv
	rank3.pdx.cluster3_GO.tsv
	rat.ss.LV.RNA.cluster.rds
	raw_count_parental_LMD_Gen1_Gen2.csv
	raw_counts.featureCounts.txt
	raw_coverages.tsv
	raw_tmm_fpkm_batch_corrected.csv
	reiboot-mac_11726185967413801301.dmg
	report-due-date.ics
	repstress_score_DMS_273.tsv
	ridhi.jpeg
	rlf.csv
	rna.matched.atac.homer.xlsx
	rna_cluster_sig_diff_terms.csv
	rna_cluster_sig_diff_terms_new.csv
	rna_cluster_sig_diff_terms_new_2.csv
	rna_cluster_sig_diff_terms_new_updated.csv
	rsem_gene.tsv
	rsem_gene_bkp.tsv
	rsem_gene_output.tsv
	rsfs20150105.pdf
	s41467-022-29517-9.pdf
	s41591-021-01448-w.pdf
	sample sheet.xlsx
	sample.tsv
	sample1.tsv
	sample2.tsv
	sample2_bkp.tsv
	sample_1.txt
	samplesheet.csv
	sankey.tiff
	sankey_latest.png
	sankeymatic_20220518_142911_5400x3600.png
	sankeymatic_20220518_145546_5400x3600.png
	sankeymatic_20241220_132332 1.tif
	sankeymatic_20241220_132332.tif
	saul_senescent_cells.rds
	scRNA analysis_PD_September 2023_For ATAC and ITH projects.pptx
	scRNA analysis_PD_September 2023_For ATAC and ITH projects_Rajeshcorrected_9132023.pptx
	scRNA_ITH_ATAC_RAJESH project_12092023.xlsx
	scRNA_cell_cluster_count.xlsx
	scRNA_integrated_markers.csv
	scRNA_sep15.pptx
	schizo.png
	sciB_vrdl_nm007056_MSc1.pdf
	science.aay0256-2.pdf
	science.abe1505.pdf
	science.abe1505_tables_s1_to_s17 2/
	science.abe1505_tables_s1_to_s17.zip
	science.abe1505_tables_s1_to_s17/
	science_slides/
	sclc_bam_to_sorted_bam.txt
	sclc_fusion_comparison_other_databases/
	sclc_genesets_new.gmt
	sclc_genesets_new.txt
	sclc_jiang.xlsx
	sclc_ucologne_2015_clinical_data (5).tsv
	sdbbootcampletters of recommend.docx
	sdbbootcampletters of recommend.pdf
	second.txt
	second_batch_atac.xlsx
	segal_adult_fetal_hepatobiliary.rds
	senescence_Liu_pdx.tiff
	senescence_berzin_pdx_sig.tiff
	senescence_pathways_ssGSEA_PDX.tsv
	senescence_pathways_ssGSEA_cell_line.tsv
	signature.png
	signature_hypoxia_geneset.numbers
	signature_table.tsv
	single_cell.R
	smallGenesFile.csv
	solar-correlation-map-R-master/
	ssGSEA.git
	ssGSEA_NE_SignatureEtc.Rmd
	st_bar.tsv
	stem_cell_book.xlsx
	stem_cell_no.tsv
	stem_cell_related.gmt
	sticky.txt
	surv.tsv
	survival.tsv
	survival.xlsx
	survival_1_vs_2.tsv
	survival_3_vs_2.tsv
	survival_analysis.xlsx
	survival_multivariate.tsv
	survival_new.tsv
	survival_new.xlsx
	survival_new_jan_30.tsv
	survival_new_jan_30.xlsx
	susovan.jpg
	teaching.jpeg
	test.csv
	test.tsv
	test/
	test1.tsv
	test2.tsv
	test_bam/
	test_data.tsv
	test_data_2.tsv
	test_heatmap.tsv
	test_heatmap_annotation.tsv
	test_rmd/
	test_script.sh
	tf_rank_within_clusters.csv
	tf_rank_within_clusters/
	tf_target.rds
	tf_target[35].rds
	tmm_fpkm_batch_corrected_annotation.tsv
	tong.tsv
	tong_flowcell.tsv
	tong_other_flowcell.tsv
	tongwu_data_file.xlsx
	tongwu_data_transfer.xlsx
	top1.5_tpm.tsv
	top1.5_tpm_umap.csv
	top1000_tpm.tsv
	top1000_tpm_umap.csv
	top100_tpm.tsv
	top100_tpm_umap.csv
	top1500_tpm.tsv
	top1500_tpm_umap.csv
	top1_tpm.tsv
	top1_tpm_consensus.csv
	top1_tpm_umap.csv
	top2.5_tpm.tsv
	top2.5_tsv_umap.csv
	top2000_tpm.tsv
	top2000_tpm_umap.csv
	top2_tpm.tsv
	top2_tpm_umap.csv
	top3000_tpm.tsv
	top3000_tpm_umap.csv
	top3_tpm.tsv
	top3_tpm_umap.csv
	top5000_all_PDX_RA_natched_comparison_K5.pdf
	top500_tpm.tsv
	top500_tpm_umap.csv
	top5_tpm.tsv
	top5_tpm_umap.csv
	transcriptomics_and_sequencing_analysis_of_gene.6.pdf
	transferred_2.txt
	tried_figure.png
	try.txt
	tumor.cluster.dotplot.jpg
	tumor.cluster.dotplot2.jpg
	tumor.cluster.dotplot3.jpg
	tumor_normal_paired_check.csv
	unibbb (1).xlsx
	unibbb.xlsx
	univariate_analysis_results_Rx_1B.xlsx
	untitled.png
	updated
	validation_cohort_uniform.xlsx
	vcf_subset.zip
	vcf_subset/
	venn.png
	venn.png.2022-05-24_14-39-36.log
	venn.png.2022-05-24_14-40-27.log
	venn_intersection.tsv
	venn_intersection1.tsv
	venn_plot_parth.png
	venn_plot_parthh.png
	venn_plot_parthh.sb-654ff044-hbMMSC
	venn_plot_parthhh.png
	vierstra.sm.pdf
	vinod_doc/
	webR-shiny-blog.png
	without_doublets.jpg
	without_doublets_malignant_only.jpg
	without_doublets_malignant_only.ver.2.jpg
	without_doublets_malignant_only.ver.3.jpg
	yugam.pdf
	~$all_atac_file.xlsx

nothing added to commit but untracked files present (use "git add" to track)
[kumarr9@NCI-02296922-ML Downloads]$ vi ssGSEA.git 

### Load required libraries
library(tidyverse)
library(GSEABase)
library(readr)
library(tidyverse)
library(dplyr)
### Load the Dataset #####
## The Gene Expression Dataset ######
#### The Clinical Benefits vs No Dataset ####
exp_tbl <- read.table("path of dataset/gene_expression.tsv", header=T)

# gene_sets: A named list object with character vectors indicating
#            gene sets for which ssGSEA scores are to be computed.

get_ssgsea_table <- function(X, gene_sets) {
  if (is.data.frame(X)) {
    X <- X %>%
      tibble::column_to_rownames(colnames(.)[[1]]) %>%
      as.data.frame() %>%
      as.matrix()
  }
  stopifnot(!any(duplicated(rownames(X))), is.numeric(X))

  # Remove genes w/constant expression
  #gene_sdev <- apply(X, MARGIN = 1, FUN = stats::sd)
  #X <- X[gene_sdev != 0, , drop = FALSE]

  set.seed(1)
  ssgsea_tab <- GSVA::gsva(expr = X, gset.idx.list = gene_sets,
                           method = 'ssgsea', kcdf = "Gaussian",
                           verbose=FALSE) %>%
    t() %>%
    as.data.frame() %>%
    tibble::rownames_to_column(var = "sample_id") %>%
    tibble::as_tibble()

  return(ssgsea_tab)
}

## Stemness signature from PNAS paper

