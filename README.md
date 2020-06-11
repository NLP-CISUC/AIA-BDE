# AIA-BDE corpus

The AIA-BDE corpus has FAQs, in Portuguese, and reformulations of their questions, to be used in the evaluation of Information Retrieval, QA, or task-oriented dialogue systems.

FAQs are related to the exercise of economic activity in Portugal and were obtained from the former Balcão do Empreendedor (BDE), the Portuguese Entrepreneur's Desk, now integrated in the e-Portugal website (https://eportugal.gov.pt/).

They are represented in a file where each line starts with one of the following tags:
  * P: Question
  * VG1: Reformulation of the previous question produced automatically with Google Translate, after translating the question to English and back to Portuguese
  * VG2: Reformulation of the previous question produced automatically with Google Translate, after translating the question to English, Portuguese, English and Portuguese
  * VUC: Reformulation of the previous question, produced manually by Portuguese speaking volunteers in the University of Coimbra
  * VIN: Reformulation of the previous question, produced manually by Portuguese speaking volunteers in the INESC-L2F, Lisbon
  * VMT: Reformulation of the previous question, produced manually by crowdsourcers, through the Mechanical Turk (since v2)
  * R: Original answer to the previous question

In addition to the previous tags, FAQs are grouped according to their sources, given by S (top-level, mandatory), SS (second level) and SSS (third-level) tags that apply to all the following FAQs. Four different top-level sources are covered:
* Espaço Empresa (Portal Empresa in v1, Business Spot): 625 FAQs
* Apoios Sociais (Social Support): 56 FAQs (since v2)
* RJACSR (Regime de Acesso a Atividades de Comércio, Serviços e Restauração, in English, Access Regime to Commerce, Services and Catering Activities): 118 FAQs
* Alojamento Local (Local Accommodation): 56 FAQs 

# Versions

* AIA-BDE_v2 (may 2020): second version of the corpus, comprising 855 FAQs from four sources and five types of reformulation.

* AIA-BDE_3vars_3classes (october 2019): first version of the corpus, comprising 380 FAQs from three sources (Portal Empresa, RJACSR, Alojamento Local) and at least three different types of reformulation for each (VG1, VG2, VUC), though some VIN are also present.

# How to cite

A <a href="https://www.aclweb.org/anthology/2020.lrec-1.669/">paper</a> on the creation of the first version of AIA-BDE and some experiments with this corpus was accepted for publication in the Proceedings of <a href="https://lrec2020.lrec-conf.org">12th International Conference on Language Resources and Evaluation (LREC)</a>. See bibtex:

<pre>
@inproceedings{goncalo-oliveira_etal:lrec2020,  
	Address = {Marseille, France},  
	Author = {Hugo {Gonçalo Oliveira} and João Ferreira and José Santos and Pedro Fialho and Ricardo Rodrigues and Luísa Coheur and Ana Alves},  
	Booktitle = {Proceedings of 12th International Conference on Language Resources and Evaluation},  
	Pages = {In press},  
	Publisher = {ELRA},  
	Series = {LREC 2020},  
	Title = {{AIA-BDE}: A Corpus of FAQs in Portuguese and their Variations},  
	Year = {2020}}
</pre>
