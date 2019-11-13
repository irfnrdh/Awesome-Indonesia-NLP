
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


# Sentences Dataset
1. [leipzig indonesian sentence collectoin](http://wortschatz.uni-leipzig.de/en/download) news articles, web articles, wikipedia data from 2008-2016
1. [wn-msa.sourceforge.net](https://sourceforge.net/p/wn-msa/tab/HEAD/tree/trunk/) Wordnet Bahasa
1. [Quran](http://tanzil.net/trans/id.indonesian) indonesian quran translation (id.muntakhab, id.jalalayn, id.indonesian)
1. [Kompas online collection](http://ilps.science.uva.nl/ilps/wp-content/uploads/sites/6/files/bahasaindonesia/kompas.zip).
   This corpus contains [Kompas online](http://www.kompas.com/) news articles from 2001-2002. See
   [here](http://ilps.science.uva.nl/resources/bahasa/) for more info and citations.
1. [Tempo online collection](http://ilps.science.uva.nl/ilps/wp-content/uploads/sites/6/files/bahasaindonesia/tempo.zip).
   This corpus contains [Tempo online](https://www.tempo.co/) news articles from 2000-2002. See
   [here](http://ilps.science.uva.nl/resources/bahasa/) for more info and citations.
1. [corpus-frog-storytelling](https://github.com/davidmoeljadi/corpus-frog-storytelling) spoken text story telling
1. [TED-Multilingual-Parallel-Corpus](https://raw.githubusercontent.com/ajinkyakulkarni14/TED-Multilingual-Parallel-Corpus/master/Monolingual_data/Indonesian.txt) Monolingual_data/Indonesian
1. [Opus](http://opus.nlpl.eu/) Opus NLPL
1. [Sealang](http://sealang.net/indonesia/) Sealang dataset

# Word reference (kemdikbud) [link](https://kbbi.kemdikbud.go.id/Beranda/Statistik)
1. Entri Dasar : 48.748 (44,64 %)
1. Kata Turunan : 26.312 (24,09 %)
1. Gabungan Kata : 30.625 (28,04 %)
1. Peribahasa : 2.040 (1,87 %)
1. Kiasan : 268 (0,25 %)
1. Ungkapan : 1.129 (1,03 %)
1. Varian : 91 (0,08 %)
1. Entri Total : 109.213 (100,00 %)
1. Makna Total : 127.775
1. Contoh Total : 29.495
1. Kategori Total : 255
1. Makna Per Entri : 1,170
1. Contoh Per Makna : 0,231

# Words dataset
1. [Word Sastrawi](https://github.com/sastrawi/sastrawi/tree/master/data)
1. [Word spaCy](https://github.com/explosion/spaCy/tree/master/spacy/lang/id) : id
1. [Word name](https://github.com/dominictarr/random-name) : random-name
1. [Word Indo name](https://github.com/seuriously/genderprediction/blob/master/namatraining.txt) : genderprediction
1. [Word Indo place](https://github.com/edwardsamuel/Wilayah-Administratif-Indonesia) : Wilayah-Administratif-Indonesia
1. [Word Indo place](https://github.com/pentagonal/Indonesia-Postal-Code) : Indonesia-Postal-Code
1. [Word Wiktionary](https://id.wiktionary.org/wiki) : word id
1. [Word sentiment](https://github.com/ramaprakoso/analisis-sentimen/tree/master/kamus) : analisis-sentimen
1. [Word sentiment](https://github.com/prasastoadi/ID-OpinionWords) : ID-OpinionWords
1. [Word sentiment](https://github.com/riochr17/Analisis-Sentimen-ID/tree/master/data) : Analisis-Sentimen-ID
1. [Word Acronims](https://github.com/ramaprakoso/analisis-sentimen/blob/master/kamus/acronym.txt)
1. [word](https://github.com/prasastoadi/serangkai/tree/master/serangkai/kamus/data) : serangkai

# Tagged dataset
1. [NER](https://github.com/yohanesgultom/nlp-experiments) : yohanesgultom/nlp-experiments 1700 sentences
1. [NER](https://github.com/yusufsyaifudin/indonesia-ner) : yusufsyaifudin/indonesia-ner 1835 sentences
1. [POS-TAG](https://github.com/famrashel/idn-tagged-corpus) : famrashel/idn-tagged-corpus
1. [POS-TAG](https://github.com/pebbie/pebahasa/blob/master/resource/Corpus.crp) : pebbie/pebahasa ~600 sentence
1. [POS-TAG Parser](https://github.com/UniversalDependencies/UD_Indonesian-GSD) : UniversalDependencies/UD_Indonesian-GSD ~4477 sentence 
1. [Sentimen](https://github.com/riochr17/Analisis-Sentimen-ID/blob/master/data/training_all_random.csv) 1506 sentences 
1. [panl10n](http://www.panl10n.net/english/OutputsIndonesia2.htm) Pan Localization

# Parallel corpus Eng-Ind
1. [parallel-corpora-en-id](https://github.com/prasastoadi/parallel-corpora-en-id/)
1. [Indonesian-English-Bilingual-Corpus](https://github.com/desmond86/Indonesian-English-Bilingual-Corpus)
1. [TALPCo](https://github.com/matbahasa/TALPCo)
1. [opus](http://opus.nlpl.eu/)
1. [Multi-Wiki](https://github.com/nguyenlab/Multi-Wiki)

# Morph
1. [MALINDO_Morph](https://github.com/matbahasa/MALINDO_Morph)
1. [morphind](http://septinalarasati.com/morphind/)
1. [INDRA](https://github.com/davidmoeljadi/INDRA)

# Crawler Data
1. [Crawler](https://github.com/harryandriyan/warta-scrap) Indonesian news portal


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
   This corpus has 39K sentences and 900K word tokens.
1. [IDN tagged corpus](https://github.com/famrashel/idn-tagged-corpus). This corpus contains
   10K sentences and 250K word tokens. The POS tags are annotated manually.

## Sentiment Analysis

1. [Aspect and Opinion Terms Extraction for Hotel Reviews](https://github.com/jordhy97/final_project).
    The corpus consists of 5000 hotel reviews from [Airy](https://www.airyrooms.com/) (78K tokens) with 5 labels. The paper is available on [arXiv](https://arxiv.org/abs/1908.04899).
1. [Aspect-Based Sentiment Analysis](https://github.com/annisanurulazhar/absa-playground).
    A text classification resource for multi-label aspect categorization.

## Syntactic parsing

1. [Indonesian Treebank](https://github.com/famrashel/idn-treebank). This corpus contains 1K parsed
   sentences. (constituency parsing)
1. [UD Indonesian](https://github.com/UniversalDependencies/UD_Indonesian-GSD). This corpus is
   provided by [Universal Dependencies](http://universaldependencies.org/). Training, development,
   and testing split are already provided. (dependency parsing)

## Machine translation

1. [PANL10N EN-ID news parallel corpus](http://www.panl10n.net/english/outputs/Indonesia/BPPT/0902/BPPTIndToEngCorpusHalfM.zip).
   This corpus has sentences from news articles from several categories: economy (6K sentences),
   international (6K sentences), science (6K sentences), and sport (4K sentences).
1. [PANL10N Indonesian translation of Penn treebank](http://www.panl10n.net/english/outputs/Indonesia/UI/0802/Parallel%20Corpus.zip).
   This corpus contains Indonesian translation of the Penn treebank. In total there are 24K
   sentences.

## Word Normalization

1. [Colloquial Indonesian Lexicon](https://github.com/nasalsabila/kamus-alay).
    This lexicon consists of 3592 unique colloquial tokens that are mapped onto 1742 unique lemmas. The full description of this lexicon can be seen in the [paper](https://ieeexplore.ieee.org/abstract/document/8629151).

## Text Summarization

1. [IndoSum](https://github.com/kata-ai/indosum).
    A collection of 20K online news article-summary pairs belonging to 6 categories and 10 sources.
    It has both abstractive summaries and extractive labels.

## Text Classification

1. [SMS Spam](http://nlp.yuliadi.pro/static/dataset_sms_spam_bhs_indonesia.zip).
   This corpus contains 1143 sentences that have been labeled with normal message, fraud, promotion. It is provided by http://nlp.yuliadi.pro/dataset
1. [Hate Speech Detection](https://github.com/ialfina/id-hatespeech-detection).
    This dataset consists of 713 tweets in the Indonesian language with 453 non hate speech and 260 hate speech tweets.
1. [Abusive Language Detection](https://github.com/okkyibrohim/id-abusive-language-detection).
    A collection of tweets for abusive language detection in Indonesian social media. It consists of two types of labelling, abusive/not abusive and not abusive/abusive but not offensive/offensive. It also has its own colloquial Indonesian lexicon.
   
## Speech recognition

1. [TITML-IDN speech corpus](http://research.nii.ac.jp/src/en/TITML-IDN.html).
   The corpus contains 20 speakers (11 male and 9 female), where each of the speaker speaks 343 utterances.
   The utterances are phonetically balanced.
   The corpus itself is free to use for academic/non-commercial usage, but interested party should make a formal request via email to the institution.
   The procedure is listed [here](http://research.nii.ac.jp/src/en/register.html).
1. [Indonesian Speech Recognition](https://github.com/frankydotid/Indonesian-Speech-Recognition).
   A small corpus of 50 utterances by a single male speaker. Disclaimer: This is a school project, do not use it for any important tasks. The author is not responsible for the undesired results of using the data provided here.
1. [CMU Wilderness Multilingual Speech Dataset](https://github.com/festvox/datasets-CMU_Wilderness).
   A dataset of over 700 different languages providing audio, aligned texts, and word pronunciations.
   One of the languages is Indonesian. The utterances are read from the bible, which is recorded by [bible.is](bible.is).
