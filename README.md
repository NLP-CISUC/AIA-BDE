# AIA-BDE
AIA-BDE corpus of FAQs and variations

The AIA-BDE corpus has FAQs, in Portuguese, and reformulations of their questions, to be used in the evaluation of Information Retrieval, QA, or task-oriented dialogue systems.

FAQs are related to the exercise of economic activity in Portugal and were obtained from the former Balcão do Empreendedor (BDE), the Portuguese Entrepreneur's Desk, now integrated in the e-Portugal website (https://eportugal.gov.pt/).

They are represented in a file where each line starts with one of the following tags:
  * P: Question
  * VG1: Reformulation of the previous question produced automatically with Google Translate, after translating the question to English and back to Portuguese
  * VG2: Reformulation of the previous question produced automatically with Google Translate, after translating the question to English, Portuguese, English and Portuguese
  * VUC: Reformulation of the previous question, produced manually by Portuguese speaking volunteers in the University of Coimbra
  * VIN: Reformulation of the previous question, produced manually by Portuguese speaking volunteers in the INESC-L2F, Lisbon
  * R: Original answer to the previous question
