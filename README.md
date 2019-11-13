
NLP Bahasa Indonesia
====================

Kumpulan thesis, paper, dan artikel tentang NLP (_Natural Language Processing_) Bahasa Indonesia.

### Daftar Isi

- [NLP Bahasa Indonesia](#nlp-bahasa-indonesia)
    - [Memulai](#memulai)
    - [Automatic Summarization](#automatic-summarizatio)
    - [Parsing](#parsing)
    - [Part-of-speech Tagging](#part-of-speech-tagging)
    - [Stemming](#stemming)
    - [Word Sense Disambiguation](#word-sense-disambiguation)
    - [Lain-lain](#lain-lain)
    - [Software, Library, Kamus](#software-library-kamus)
    - [Berkontribusi](#berkontribusi)


# Dataset-Berita-Indonesia

- Indonesian News Corpus (https://data.mendeley.com/datasets/2zpbjs22k3/1)
- INDONESIAN HOAX NEWS DETECTION DATASET (https://data.mendeley.com/datasets/p3hfgr5j3m/1)
- Warta Berita Online Kompas dan Tempo (https://ilps.science.uva.nl/resources/bahasa/)
- Raw dataset of Indonesian news articles (https://github.com/feryandi/Dataset-Artikel)

# Books
- Hoax dan Hate Speech di Dunia Maya (https://zenodo.org/record/3364834) 

# Jurnal
- Indonesian News Classification using Support Vector Machine (https://zenodo.org/record/1074439)


# Indonesian NLP resources

## Language modeling

1. [Kompas online collection](http://ilps.science.uva.nl/ilps/wp-content/uploads/sites/6/files/bahasaindonesia/kompas.zip).
   This corpus contains [Kompas online](http://www.kompas.com/) news articles from 2001-2002. See
   [here](http://ilps.science.uva.nl/resources/bahasa/) for more info and citations.
1. [Tempo online collection](http://ilps.science.uva.nl/ilps/wp-content/uploads/sites/6/files/bahasaindonesia/tempo.zip).
   This corpus contains [Tempo online](https://www.tempo.co/) news articles from 2000-2002. See
   [here](http://ilps.science.uva.nl/resources/bahasa/) for more info and citations.

## POS tagging

1. [PANL10N POS tagging](http://www.panl10n.net/english/outputs/Indonesia/UI/0802/UI-1M-tagged.zip).
   This corpus has ~39K sentences and ~900K word tokens.
1. [IDN tagged corpus](https://github.com/famrashel/idn-tagged-corpus). This corpus contains
   ~10K sentences and ~250K word tokens. The POS tags are annotated manually.

## Syntactic parsing

1. [Indonesian Treebank](https://github.com/famrashel/idn-treebank). This corpus contains ~1K parsed
   sentences. (constituency parsing)
1. [UD Indonesian](https://github.com/UniversalDependencies/UD_Indonesian-GSD). This corpus is
   provided by [Universal Dependencies](http://universaldependencies.org/). Training, development,
   and testing split is already provided. (dependency parsing)

## Machine translation

1. [PANL10N EN-ID news parallel corpus](http://www.panl10n.net/english/outputs/Indonesia/BPPT/0902/BPPTIndToEngCorpusHalfM.zip).
   This corpus has sentences from news articles from several categories: economy (6K sentences),
   international (6K sentences), science (6K sentences), and sport (4K sentences).
1. [PANL10N Indonesian translation of Penn treebank](http://www.panl10n.net/english/outputs/Indonesia/UI/0802/Parallel%20Corpus.zip).
   This corpus contains Indonesian translation of the Penn treebank. In total there are ~24K
   sentences.

## Speech recognition

1. [TITML-IDN speech corpus](http://research.nii.ac.jp/src/en/TITML-IDN.html).
   The corpus contains 20 speakers (11 male and 9 female), where each of the speaker speaks 343 utterances.
   The utterances are phonetically balanced.
   
   The corpus itself is free to use for academic/non-commercial usage, but interested party should make a formal request via email to the institution.
   The procedure is listed [here](http://research.nii.ac.jp/src/en/register.html)

1. [frankydotid/Indonesian-Speech-Recognition](https://github.com/frankydotid/Indonesian-Speech-Recognition).
   A small corpus of 50 utterances by a single male speaker.


Memulai
=======

### Artikel-Artikel Tentang NLP

- [Karena Data Gak Mungkin Bohong](https://medium.com/karena-x/karena-data-gak-mungkin-bohong-a17ff90cef87) - Jim Geovedi. 2014.

### Materi Pengantar NLP

- [Pengantar NLP](http://lecturer.eepis-its.edu/~kangedi/materi%20kuliah/Kecerdasan%20Buatan/Bab%205%20Natural%20Language%20Processing.pdf) - Kang Edi, PENS.


Automatic Summarization
=======================

- [Frequent Term based Text Summarization for Bahasa Indonesia](http://eprints.unsri.ac.id/3296/1/Frequent_Term_Based_Text_Summarization_For_Bahasa_Indonesia_-_E1213550.pdf)

  M.Fachrurrozi, Novi Yusliani, and Rizky Utami Yoanita. International Conference on Innovations in Engineering and Technology (ICIET'2013) Dec. 25-26, 2013 Bangkok (Thailand).


Parsing
=======

- [Analisa Struktur Kalimat Bahasa Indonesia dengan Menggunakan Pengurai Kalimat Berbasis Linguistic String Analysis](http://staf.cs.ui.ac.id/WebKuliah/IKI40921/Shelly.doc)

  Shavitri, Shelly. Undergraduate Theses for computer science, University of Indonesia, 1999.

- [INAGP : Pengurai Kalimat Bahasa Indonesia Sebagai Alat Bantu Untuk Pengembangan Aplikasi PBA](http://mail.informatika.org/~ayu/2009parser.pdf)

  Rosalina Paramita N., Dwi H. Widyantoro, Ayu Purwarianti. Undergraduate Theses from JBPTITBPP, Institute Technology Bandung, 2007.

- [Penguraian Bahasa Indonesia dengan Menggunakan Pengurai Collins](http://digilib.itb.ac.id/gdl.php?mod=browse&op=read&id=jbptitbpp-gdl-rosaariani-25714)

  Sukamto, Rosa Ariani. Tesis untuk Magister, Institut Technology Bandung, 2009.


Part-of-speech Tagging
======================

- [HMM Based Part-of-Speech Tagger for Bahasa Indonesia](http://mail.informatika.org/~ayu/2010postagger.pdf)

  Wicaksono, A. Farizki dan Purwanti, Ayu. Proceeding of 4th International Malindo (Malay and Indonesian Language) Workshop (2010).

- [Penggunaan Hidden Markov Model untuk Kompresi Kalimat](http://digilib.itb.ac.id/files/disk1/627/jbptitbpp-gdl-yudiwibiso-31314-1-2008ts-r.pdf)

  Yudi Wibisono. Graduate Thesis. Institute of Technology Bandung. 2008.
  
- [Probabilistic Part Of Speech Tagging for Bahasa Indonesia](http://www.panl10n.net/english/outputs/Indonesia/UI/0901/UI-POSTAG.pdf)

  Femphy Pisceldo, Mirna Adriani, Ruli Manurung. Third International MALINDO Workshop, colocated event ACL-IJCNLP 2009, Singapore, August 1, 2009. 


Stemming
========

- [Effective Techniques for Indonesian Text Retrieval](http://researchbank.rmit.edu.au/eserv/rmit:6312/Asian.pdf)

  Asian J. (2007). PhD thesis School of Computer Science and Information Technology RMIT University Australia.

- [Enhanced Confix Stripping Stemmer and Ants Algorithm for Classifying News Document in Indonesian Language](http://personal.its.ac.id/files/pub/2623-agusza-baru%2021%20d%20VIP%20enhanced-confix-stripping-stem.pdf)

  Arifin, A.Z., I.P.A.K. Mahendra dan H.T. Ciptaningtyas. 2009. Proceeding of International Conference on Information & Communication Technology and Systems (ICTS).

- [Implementasi Modifikasi Enhanced Confix Stripping Stemmer Untuk Bahasa Indonesia dengan Metode Corpus Based Stemming](http://digilib.its.ac.id/public/ITS-Undergraduate-14255-paperpdf.pdf)

  A. D. Tahitoe, D. Purwitasari. Institut Teknologi Sepuluh Nopember (ITS) – Surabaya.


Word Sense Disambiguation
=========================

- [Building an Indonesian WordNet](http://bahasa.cs.ui.ac.id/pub/malindo08wordnet.pdf)

  Desmond Darma Putra, Abdul Arfan and Ruli Manurung. In Proceedings of the 2nd International MALINDO Workshop. 2008.

- [English-to-Indonesian Lexical Mapping using Latent Semantic Analysis](http://bahasa.cs.ui.ac.id/pub/malindo08lsa.pdf)

  Eliza Margaretha, Franky, and Ruli Manurung. In Proceedings of the 2nd International MALINDO Workshop. 2008.


Lain-lain
=========

- [A survey of bahasa Indonesia NLP research conducted at the University of Indonesia](http://staf.cs.ui.ac.id/~maruli/pub/malindo08nlp.pdf)

  Mirna Adriani and Ruli Manurung. Faculty of Computer Science, University of Indonesia.

- [Indonesian Morphology Tool (MorphInd): Towards an Indonesian Corpus](http://ufal.mff.cuni.cz/~larasati/papers/paper6.pdf)

  Septina Dian Larasati, Vladislav Kuboˇn, and Daniel Zeman. Charles University in Prague.

- [Research Report on Local Language Computing: Development of Indonesian Language Resources and Translation System](http://www.panl10n.net/english/outputs/Indonesia/FinalReportID.pdf)

  Adriani, Mirna. Riza, Hammam. 2008.

- [Towards a Semantic Analysis of Bahasa Indonesia for Question Answering](http://bahasa.cs.ui.ac.id/pub/pacling07.pdf)

  Septina Dian Larasati and Ruli Manurung. Faculty of Computer Science. University of Indonesia. 2007.


Software, Library, Kamus
========================

- [Kateglo](http://kateglo.com/) - Kamus, Tesaurus, dan Glosarium Bahasa Indonesia.
- [Sastrawi](https://github.com/sastrawi/sastrawi) - Stemmer PHP untuk Bahasa Indonesia.

