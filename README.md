# Corpus Voynichianum

*The open library of the Voynich manuscript.* Compiled by Alexander S. Gambarian (Gamba, [x.com/gambarian](https://x.com/gambarian)).

## Overview

### What it is
Corpus Voynichianum is a comprehensive, annotated database of what has been written, said and filmed about the Voynich manuscript. The manuscript is held at Yale University (Beinecke Rare Book and Manuscript Library, MS 408). It has 102 parchment leaves written in an unknown script, and its parchment has been radiocarbon-dated to 1404-1438.

The collection runs from Georg Baresch's 1639 letter to Athanasius Kircher to forum posts of November 2026. It also keeps older books the manuscript is often compared with, such as printed herbals and Trithemius's Polygraphia.

### Why it exists
Writing on the manuscript is scattered across journals, newspapers, mailing lists, forums, blogs and videos, in many languages. Most of it is hard to find, and new readings of the manuscript often repeat ideas published decades earlier. The collection puts these sources in one place, in a form that a person or a program can search, so that anyone can check what has already been said before proposing something new.

### Who made it
Alexander S. Gambarian compiled the collection in October and November 2026, working with several AI models (Claude, GPT, Gemini, and Qwen run locally). The models searched, read, extracted and classified sources and checked each other's work. The compiler decided what to include. This description was drafted by an AI model (Claude) and reviewed by the compiler. The project is non-commercial and will stay so.

### What is inside
The release counts two units. A record is one catalogued item: an article, a book, a video, a forum thread, a blog post. There are 70,709 records, and one real work can have more than one record. A text is a piece of text attached to a record: the body of an article, one forum reply, one mailing-list message, a video transcript, an abstract. There are 120,463 texts with a body, about 1.09 GB of UTF-8, and 64,773 records have at least one. A blog post on Cipher Mysteries with its comments is one record and 909 texts.

Every record is annotated with its kind, date, language and author where known, and with the address of its source.

The contents, listed by their likely value for research rather than by size:

- 2,114 scholarly works: journal articles, theses, preprints and conference papers, with full text where it is openly available. The collection holds 40 of the 44 works on the manuscript listed in Mary E. D'Imperio's 1978 bibliography.
- 700 archival items, such as letters, catalogues and papers on the manuscript's history, and 2,251 newspaper and magazine items.
- 32,873 messages of the Voynich mailing list, December 1991 to February 2013, the main meeting place of researchers in those years.
- A folio index that links each leaf of the manuscript to the texts that discuss it.
- 9,872 links between records: other copies or probable copies of the same work, parts of larger works, editions and reprints, links from an experiment to its code or data, and 77 reviews of a work. Replies and rebuttals between works are not linked yet; that is planned for the next version.
- 417 claimed results and experiments, catalogued so that a new proposal can be checked against earlier ones.
- 1,062 code and data items: transcriptions of the script, statistical tools, datasets.
- 14,749 short English summaries written by machine, 6,355 of them for works in 62 other languages, so that an English reader can find work published in Russian, Polish, Chinese or Japanese.
- 38,913 records from forums and discussion sites (Voynich Ninja, Reddit and others), with 28,220 forum replies.
- 759 books, often as a catalogue description without text when the book is still sold.
- 9,178 blog posts and web pages, and 18,648 comments on the Cipher Mysteries blog.
- 7,688 videos and podcasts, with 8,863 machine transcripts.
- 5,876 social media posts, 490 works of art, music and fiction, and 1,261 other items.

Languages, duplicate groups and links between records were assigned by machine and are provisional.

### Where it comes from and how it was collected
Everything was collected from openly accessible sources: the open sections of the Voynich Ninja forum, the mailing-list archives kept at voynich.net, voynich.nu and Jorge Stolfi's mirror at Unicamp, blogs and their comments, Reddit, YouTube and podcast pages, scholarly repositories and catalogues, free newspaper archives such as Chronicling America, and the Internet Archive. Searches were run in several dozen languages. Each record keeps the address of its source where one exists; 1,026 records have none.

The records come from about 3,400 websites, or about 4,300 if each blog on a shared platform such as WordPress or Blogspot is counted separately. Five sources give two thirds of the records: the mailing-list archives at voynich.net and voynich.nu, YouTube, Bluesky and the Voynich Ninja forum. About 2,300 sites gave a single record each.

#### Platform by platform

Counted by the host of each record's source address in `works` (70,709 records in v1.0); a record counts once, and records without an address are under "Other websites".

| Platform | Records | Share |
|---|---:|---:|
| Mailing-list archives (voynich.net, voynich.nu, Unicamp mirror) | 33,722 | 47.7 % |
| YouTube | 5,788 | 8.2 % |
| Bluesky | 5,317 | 7.5 % |
| Voynich Ninja forum | 3,053 | 4.3 % |
| Reddit | 2,582 | 3.7 % |
| WordPress blogs | 1,270 | 1.8 % |
| GitHub | 750 | 1.1 % |
| Bilibili | 648 | 0.9 % |
| Apple Podcasts | 616 | 0.9 % |
| Internet Archive | 532 | 0.8 % |
| X / Twitter | 335 | 0.5 % |
| Blogspot blogs | 326 | 0.5 % |
| Wikipedia | 224 | 0.3 % |
| Hacker News | 219 | 0.3 % |
| Spotify | 63 | 0.1 % |
| Substack | 63 | 0.1 % |
| Mastodon | 62 | 0.1 % |
| Medium | 45 | 0.1 % |
| Academia.edu | 42 | 0.1 % |
| ResearchGate | 41 | 0.1 % |
| arXiv | 37 | 0.1 % |
| Telegram | 34 | <0.1 % |
| Habr | 24 | <0.1 % |
| Stack Exchange | 17 | <0.1 % |
| Zhihu | 15 | <0.1 % |
| Facebook | 12 | <0.1 % |
| Vimeo | 5 | <0.1 % |
| Dailymotion | 4 | <0.1 % |
| VKontakte | 2 | <0.1 % |
| Weibo | 1 | <0.1 % |
| Instagram | 1 | <0.1 % |
| TikTok | 0 | 0 % |
| Other websites (3,916 addresses, led by doi.org, ciphermysteries.com, voynichrevisionist.com, mysteriesdept.com, zenodo.org and note.com) | 14,843 | 21.0 % |

Of the 7,688 video and podcast records, 5,766 are on YouTube, 634 on Bilibili, 615 on Apple Podcasts, 59 on Spotify, 34 on the Internet Archive and 580 elsewhere.

Some platforms are thin or empty here: TikTok, Instagram, Facebook, VKontakte and Weibo. Collection used open pages only, with no logins. If you know where the manuscript is discussed and that place is missing or thin in this table, open an issue on GitHub or write to gambarian@gmail.com.

Speech in videos and podcasts was transcribed by machine. Scanned newspapers and books were read by optical character recognition. Duplicates were grouped by AI models, and the groupings are marked as provisional.

The sections below give the details: how to read a record, the files, the rights rule, what was left out and why, and how to cite.




A catalogue and text collection about the Voynich manuscript: research papers, theses, books primarily as records, press, blogs, machine transcripts, social posts, code and data, experiments, public forum material and the mailing list **1991–2013**.

Data: https://huggingface.co/datasets/Gambarian/corpus-voynichianum. Archive with DOI: DOI: 10.5281/zenodo.24031111. Code: `tools/` inside the release.

This repository holds only the introduction; the data, `tools/` (with its MIT licence), `LICENSE.md` and `DATA_DICTIONARY.md` are in the Hugging Face dataset (https://huggingface.co/datasets/Gambarian/corpus-voynichianum) and in the Zenodo archive (DOI: 10.5281/zenodo.24031111).

Release v1.0, 2026-11-07. Built on 2026-11-07. Schema version 2.0. Left out or changed in this build: 1,107 listed text ids excluded; 1,230 masking rules, which changed 2,788 texts; 312 texts exported as metadata only (all hold categories).

**Everything here was collected from openly accessible sources; an author or rights holder who shows their authorship or rights can have their work removed on request.** To ask, see Opt-out and removal.

This is a non-commercial project and will stay non-commercial; its aim is to save future researchers from repeating the search. 69,683 of 70,709 records link back to a source address, 12,579 of them built from the saved reference; see **Source addresses** below.

New here? Start with the folio index, `folio_index.csv` (or `.parquet`): choose a leaf of the manuscript and follow its records to the sources. For the whole catalogue open `works.csv` (one row per record) and `texts_index.csv` (one row per text, without the body). `STATE_OF_RESEARCH.md` is an optional AI-written overview with its sources linked to library records: read the sources before relying on it.


The library also retains 20 catalogue records whose titles name Ethel Voynich's novel The Gadfly (including its Russian title), as context on the Voynich family.

Short-text and exact-repeat counts exclude the forum attribution header; texts_index.chars and released hashes include it.

Languages are machine-detected from text openings and remain provisional; later-import detections use up to 3,000 characters.

## Opt-out and removal

This is a non-commercial database for the advancement of science. It is built on openly served material; no text that sits behind a payment is published here.

To have something removed, write to gambarian@gmail.com with the subject "Opt-out request" (also accepted: "Delete request", "Request for deletion"). Name the work, post or link, state that you are its author or rights holder, and show your authorship or rights. We check that showing by correspondence before removing anything. We do not act on anonymous requests or requests that do not show authorship or rights; we politely ask for that showing and remove nothing meanwhile. A rights holder may request removal of the whole work; a forum participant may request removal of their own posts, leaving the thread and other people's posts. We act promptly on verified requests.

What we control: our copies on Zenodo, GitHub and Hugging Face, and all future versions. We cannot recall copies others have already downloaded, and Zenodo keeps earlier versions unless its operator removes them.

## What is in this build?

This copy holds **70,709 records**. These records add letters and monographs together: a mailing-list message and a book each count as one record. **64,773 records** carry at least one text beyond a catalogue abstract. There are **120,463 texts with body** (1.09 GB of UTF-8) in **3 shard(s)**, and **312 texts exported as metadata only** (body withheld for rights, privacy, scope, duplication or data-quality reasons). Under the grouping rule described in this document the records fall into **68,890 distinct-work groups (provisional)**: 3,061 records sit in 1,242 multi-record groups, the rest stand alone. Records whose address is on voynich.ninja (any kind): 3,053, with 3,291 texts. The library holds 9,872 relations between records and 1,671 described experiments (369 with at least one linked code or data address, 101 with a replication check made by the library).

These are records, text units and provisional groups, not interchangeable counts of publications. The counts here were written by the export tool from `manifest.json`; marked curator notes are the exception.

**24,910 of the 120,463 texts (21%) are shorter than 200 characters and 24,430 (20%) do not mention the manuscript**, most of them replies in long threads. Nothing was filtered out for that reason; 8,802 texts are also exact repeats. Where they come from:

| Source | Records | Texts with body | Very short | No mention |
|---|---|---|---|---|
| forum:mailing lists | 32,916 | 32,890 | 491 | 2,556 |
| web_blog | 9,178 | 30,134 | 5,189 | 6,651 |
| forum:reddit | 2,560 | 27,326 | 14,430 | 11,911 |
| video_podcast | 7,688 | 9,390 | 55 | 517 |
| social | 5,876 | 5,679 | 3,223 | 624 |
| forum:voynich.ninja | 2,995 | 3,128 | 33 | 36 |
| scholarly | 2,114 | 2,484 | 53 | 113 |
| forum:hacker news | 217 | 2,242 | 1,124 | 1,287 |
| press | 2,251 | 1,951 | 13 | 230 |
| other | 1,261 | 1,682 | 54 | 68 |
| code_data | 1,062 | 1,061 | 71 | 20 |
| archive_collection | 700 | 897 | 141 | 305 |
| experiment_claim | 417 | 772 | 18 | 76 |
| book | 759 | 402 | 10 | 17 |
| culture | 490 | 260 | 0 | 11 |
| forum:other | 225 | 165 | 5 | 8 |

**150 short texts were written by the library's own language models**, from bibliographies, bookseller pages and catalogue records. They carry `MACHINE_SUMMARY` in `quality_flag`; they are not the publisher's abstract, and a first person in them is the model speaking, not the author of the work. A `catalog_abstract` on a blog is the opening of the post.

## How to read a card

One row of `works.csv` is one unit of the catalogue, and the units differ. **The 70,709 records add letters and monographs together**: a one-line message to the mailing list in 1994 and D'Imperio's monograph of 1978 each count as one record. `unit` in `works_card.csv` says which it is. It is a first version, worked out by a program from the role, the class and the kinds of text of a record.

| Unit | Records | What it is |
|---|---|---|
| message | 32,894 | one message of the mailing list |
| work | 23,762 | an article, book, thesis, video, blog post or page |
| thread | 5,332 | a saved forum discussion thread |
| post | 6,514 | one post or reply |
| collection | 2,140 | an item of an archive inventory or a catalogue |
| issue | 67 | a whole newspaper issue or journal volume |

- **Title, author, year** stand as catalogued. An author's name is as written, so one person can appear under several spellings. `year` holds the year where one can be read, and `year_raw` keeps what was saved: a date, a range or a relative date copied from a page. `date_precision` in `works_card.csv` says how exact it is.
- **Address and DOI.** Addresses are retained where known; records without one include archival collections and web pages. Mailing-list links can name an individual page or an archive file; `source_ref` keeps the saved reference.
- **Class and access.** `class`, `kind`, `access_status` and `access_class` say what the item is and what is known about reaching it, not whether it may be reused. `vocabulary.csv` gives every raw value in plain English.
- **Short text.** `abstract_by` says who wrote it: `author_or_publisher`, `page_opening` (the opening of a blog post), `saved_page`, `machine` (the `MACHINE_SUMMARY` flag) or `none`. In a `machine` row, "I found no independent review" is the model speaking, not the author.

How full the card is, counted by a program on this release. An empty field means nothing is recorded; it does not mean nothing exists.

| Field | Records | Share |
|---|---|---|
| title | 70,709 | 100% |
| author | 63,030 | 89% |
| year usable for sorting | 62,132 | 88% |
| web address | 69,683 | 99% |
| DOI | 1,506 | 2% |
| subject | 6,966 | 10% |
| language measured | 61,370 | 87% |
| any short text | 3,893 | 6% |
| text beyond a short text | 64,773 | 92% |


## Loading

Download the data release and run from its unpacked export directory with `pandas` and `pyarrow` installed (tested with Python 3.13.13, pandas 3.1.0, pyarrow 26.0.1). The metadata tables can be read without loading text bodies:

```python
import pandas as pd
works = pd.read_parquet("works.parquet")
index = pd.read_parquet("texts_index.parquet")
shard = pd.read_parquet("texts-00000-of-00003.parquet")
print(shard[["text_id", "kind", "chars"]].head())
```

Stop before loading `shard` for metadata-only work. `work_id` joins texts to `works.id`. Use `text_id` for individual texts; do not cite changeable duplicate-group ids. The text index locates rows and shards, and `manifest.json` lists files and checksums.

`EXAMPLES.md` holds three worked queries with their output on this export: a literal name search, the individually saved posts of one forum member, and experiments with their code links and replication checks. The search is not exhaustive, whole-thread extracts are reported apart from one person's posts, and replication statuses include unsuccessful or inconclusive checks.

## Known errors in 1.0

Found on 7 November 2026, after publication; all will be fixed in the next version. Corrections from readers are welcome.

- **Annotation authorship.** In `machine_annotations_en`, 13,140 of the 13,612 rows marked `gpt-6.1-sol` were written by Claude Haiku. The other 472 are being traced.
- **Annotations that fail our own check.** 2,656 annotations do not pass the program check used for the rest (2-3 sentences of 40-70 words; every name and number present in the source). They will be rewritten or removed.
- **Links between records.** An earlier wording said the links include replies and rebuttals. They do not yet: the 9,872 links are copies, parts, editions, experiment-to-code links and 77 reviews.
- **Author, title and year.** 1,411 records carried a wrong author, title or year. Corrected on 9 November 2026 in `works`, `works_card` and `texts_index` (see Corrections); the text files keep the old author in 112 rows until v1.1.

## Licence and reuse

**Licence:** CC BY 4.0 for our compilation and markup; third-party texts stay with their authors. That covers the selection and arrangement of the library and the catalogue records, relations, tables and documents we made. It gives you no rights in the texts themselves: they belong to their authors, so check the original source before reusing one. The same holds for our machine translations of them (`translation_en`, `translation_gemini`): a translation follows the rights of its original. An `open` access label says a text could be reached, not that it may be reused. The code in `tools/` is under the MIT licence: see `tools/LICENSE`.

Open the [code licence](https://huggingface.co/datasets/Gambarian/corpus-voynichianum/blob/main/tools/LICENSE), [licence note](https://huggingface.co/datasets/Gambarian/corpus-voynichianum/blob/main/LICENSE.md) and [data dictionary](https://huggingface.co/datasets/Gambarian/corpus-voynichianum/blob/main/DATA_DICTIONARY.md) in the dataset.

## What was published, and what was not

The curator, a lawyer, decided what to publish by the harm our copy could do: to an author or publisher, a lost sale; to a private person, exposure. Newspapers and magazines are published in full; copies others already placed on the open web are published unless the file itself forbids copying. **Books still on sale** (new copies from the publisher or its distributors; second-hand offers do not count) keep only the record and the link. Articles still on sale keep the record and, where held, the abstract. **A work with a free legitimate copy elsewhere, or that nobody sells new now,** may be published. This is the curator's decision for this release; it gives you no licence to any third-party text.

41 texts were published after a case-by-case harm test, 5 under the press rule, and 767 because "metadata only" is a catalogue label, not a rights limit; `rights_decisions.csv` lists each with its basis. In all, 312 text rows have empty bodies across all hold categories, including 210 for rights and 24 for privacy. Other single messages of the mailing list stay, redacted. Separately, 6 own-post copies inside threads were withheld by the library for privacy, not removed at a rights holder's request. 10,080 further texts are omitted (table below). What is forbidden or for sale was checked by reading the files and by judgement: mistakes are possible.

Excluded with a stated reason: 861 texts for privacy, 205 wrong texts, 41 internal notes, and 1,823 whole records not about the manuscript with their 19,699 texts. Withdrawn at the request of an author or rights holder so far: 0.

| Why excluded | Records | Texts |
|---|---|---|
| Hacker News job-seeker thread: off topic, and the posts carry personal contact details (privacy) | – | 861 |
| wrong text on the record: the text belongs to another work | – | 93 |
| wrong text on the record: a placeholder page, not the work | – | 66 |
| an internal note of the library's cataloguers, not an abstract | – | 41 |
| wrong text on the record: broken encoding | – | 19 |
| wrong text on the record: one text shared by records it does not belong to | – | 8 |
| wrong text on the record: other files of the same Zenodo deposit, not the file asked for | – | 8 |
| wrong text on the record: machine transcript of music, no speech | – | 6 |
| wrong text on the record: a whole volume; the record keeps its own shorter text | – | 4 |
| wrong text on the record: an advert | – | 1 |
| whole record: the library's audit found it is not about the manuscript | 1,723 | 19,601 |
| whole record: a reader flagged it as not about the manuscript | 97 | 94 |
| whole record: about the novelist Ethel Voynich, not the manuscript | 2 | 4 |
| whole record: shares only the surname Voynich | 1 | 0 |

## Replication

The library reran the published code of 15 recent claims: preprints and blog posts from 2026, 6 of them by one author. They are not the standard works of the field. Outcome: 7 reproduced, 2 partly, 6 not runnable, 0 different. "Reproduced" means the published number comes out of the published code and data; it does not validate the interpretation. `replication_recent15.csv` holds the notes, and `experiments.csv` records all 101 checks, not all of them successful.

Replication statuses are historical library checks; their run materials are not published here, so `CONFIRMED` and `DIFFERENT` cannot be verified from this release alone.

## Provenance and coverage

Sources include bibliographies, repositories, public pages and archives, assisted by AI cataloguing and duplicate review. Import dates are not crawl dates. The ledger records what entered this catalogue, not independent completeness against each source.

<details>
<summary>Collection method and full coverage ledger</summary>

The catalogue was assembled from literature lists, library and repository searches, independent searches by several research models, targeted language searches, crawls of public pages and public archives. The named search languages are English, German, French, Spanish, Portuguese, Italian, Polish, Czech, Slovak and Hungarian.

Saved texts retain their public source address where one exists. Later batches were checked against the catalogue using DOI, URL, ISBN, title, author and year to identify possible duplicates; this does not guarantee that all duplicates were detected. AI models assisted with cataloguing and duplicate judgments. Speech in videos and podcasts was transcribed by machine. Automatic transcripts are marked as such, and some have a suspect `quality_flag`.

The ledger has one row per source group. "Records in catalogue (expected)" counts the records held for that group before selection; the remaining columns describe the export. These expected units are catalogue counts, not an independent count of all material available from each source.

"Imported into the library" is the date a text entered the database, not the crawl date. Crawl dates are not stored per text. Withheld-by-policy texts include restricted full texts, quarantined versions, empty bodies and similar exclusions. Most of the 1,107 excluded ids are text ids, so the records that held them stay: see "Texts excluded", not "Records withdrawn".

| Source group | Imported into the library (first–last) | Records in catalogue (expected) | Records exported | Texts with body | Texts metadata-only | Texts withheld by policy | Texts excluded | Records withdrawn | Curator note |
|---|---|---|---|---|---|---|---|---|---|
| forum:mailing lists | 2026-10-11 – 2026-11-07 | 32,972 | 32,916 | 32,890 | 10 | 27 | 1 | 56 | Voynich mailing list archive, messages 1991–2013 (curator statement). Messages can link to their own msgNNNNN.html page or to an archive file on voynich.nu, voynich.net or unicamp. For archive-file links, search for the subject; source_ref retains the saved reference. Counts are computed at export in manifest.json. |
| web_blog | 2026-10-11 – 2026-11-07 | 9,234 | 9,178 | 30,134 | 107 | 646 | 26 | 56 | – |
| video_podcast | 2026-10-11 – 2026-11-07 | 8,443 | 7,688 | 9,390 | 6 | 335 | 16 | 755 | Transcripts are machine-made (automatic speech recognition); some are flagged SUSPECT in quality_flag. |
| social | 2026-10-27 – 2026-11-07 | 6,190 | 5,876 | 5,679 | 0 | 3 | 0 | 314 | – |
| forum:voynich.ninja | 2026-10-11 – 2026-11-07 | 3,000 | 2,995 | 3,128 | 0 | 3,496 | 0 | 5 | Crawled without a login on 4 October 2026, as the forum served it, with single posts added on 26 and 31 October (curator statement; crawl dates are not stored per text). Roughly 1,476 threads in login-only sections were never collected and are not counted as expected units (curator estimate, not computed from the database). |
| forum:reddit | 2026-10-27 – 2026-11-07 | 2,582 | 2,560 | 27,326 | 11 | 4,489 | 1 | 22 | – |
| scholarly | 2026-10-11 – 2026-11-07 | 2,300 | 2,114 | 2,484 | 30 | 183 | 30 | 186 | – |
| press | 2026-10-11 – 2026-11-07 | 2,276 | 2,251 | 1,951 | 13 | 106 | 8 | 25 | – |
| other | 2026-10-11 – 2026-11-07 | 1,378 | 1,261 | 1,682 | 16 | 76 | 0 | 117 | – |
| code_data | 2026-10-11 – 2026-11-07 | 1,124 | 1,062 | 1,061 | 23 | 7 | 7 | 62 | – |
| book | 2026-10-11 – 2026-11-07 | 775 | 759 | 402 | 6 | 376 | 14 | 16 | Default rule: records only, except open editions first published in 1930 or earlier; see the rights rule. |
| archive_collection | 2026-10-11 – 2026-11-07 | 762 | 700 | 897 | 78 | 167 | 101 | 62 | – |
| culture | 2026-10-26 – 2026-11-07 | 498 | 490 | 260 | 5 | 67 | 33 | 8 | – |
| experiment_claim | 2026-10-11 – 2026-11-07 | 417 | 417 | 772 | 6 | 81 | 8 | 0 | – |
| forum:hacker news | 2026-10-11 – 2026-11-07 | 341 | 217 | 2,242 | 0 | 14 | 862 | 124 | – |
| forum:other | 2026-10-27 – 2026-11-07 | 240 | 225 | 165 | 1 | 7 | 0 | 15 | – |

Where no snapshot statement is given, the library has no recorded crawl date for that source group. The forum source groups and the host-wide voynich.ninja totals have different scopes.

</details>

## Limitations

In a stratified random sample of 300 records (seed 20261107; scholarly works, books and press over-represented), assessed by a language model (Claude Opus) against saved text where available (read in full or at its opening, middle and end), otherwise from catalogue metadata, a second-model cross-check confirmed 4 wrong titles, 3 wrong authors, 1 wrong year, 22 wrong source kinds, and 17 texts that were not the work alone (8 whole magazine issues or volumes filed under one article without a flag, and 9 stubs, page frames, unreadable extractions, listing pages, another work or appended unrelated articles); 2 further title verdicts and 4 further source-kind verdicts remain unconfirmed, the counts describe the sample before the whole-issue flag corrections, forum and mailing-list records, 57% of the library, showed no error detected by Opus in 40 read, and no person checked these verdicts.

The second model family (OpenAI) agreed with 50 of Opus's 59 wrong-value verdicts, disagreed with 2 (one title and one source kind), and could not confirm 7 (the 2 titles and 4 source kinds noted above, plus one access verdict); it did not recheck the 28 proposed fills of empty fields or the sample's other verdicts.

This is an incomplete, growing collection. Catalogue identities, AI-assisted duplicate links and automatic transcripts can be wrong. Extraction can omit images, tables, formulae or formatting; a blank `quality_flag` is not an approval. Whole-thread extracts can contain several contributors' words. Verify important passages against their original sources.

A link is not necessarily verified code, and a replication-check status does not necessarily mean a successful rerun. Reproducing a number does not validate its interpretation or a decipherment. Group counts are provisional: many records with the same title and author are still not joined, so do not read them as the number of real works. `year` holds a four-digit year or is empty: 8,577 records have none. `year_raw` keeps the value as saved; at least 1,241 of these hold a relative date such as `2mo ago`. **Author names.** Names stand as saved and are not merged in this release: René Zandbergen also appears as Rene Zandbergen, R. Zandbergen, Zandbergen, René and, on the forum, ReneZ. Joining such forms is left for version 1.1. **Language.** `language` in `works_card.csv` comes from a program that read the longest text of a record. It is measured for 61,370 records (87%). 4,536 records were not measured, 3,929 rest on a short text, and 874 look like transliterations of the manuscript that the program mistook for a language. `language_basis` says which case applies. The human audit of catalogue identity, duplicate decisions and transcripts has not yet been published. Access labels do not establish reuse rights.

## Corrections

### Correction of 9 November 2026

In the first build of v1.0, 1,411 records carried a wrong author, title or year. A catalogue update meant to change only access and language fields also copied stale values from the raw catalogue, so pages by Jorge Stolfi were credited to Rene Zandbergen, papers from the CEUR-WS proceedings to "CEUR-WS Vol. 3313 authors", and Nick Pelling's blog posts to the login nickpelling. The catalogue was repaired on 9 November 2026, and `works`, `works_card` and `texts_index` were rebuilt here with the original values; 5 more records take a correction the cataloguers had approved, 1,416 records in all, and no record was added or removed. The text files (`texts-*`) still show the old author in 112 rows, where a text has no author of its own and takes its record's; they will be corrected in v1.1. The other counts in this card are those of the first build (after the correction 8,449 records have no year, 63,106 have an author and 62,260 a year usable for sorting); `manifest.json` lists them under `amendments` with the new file hashes, and the archive on Zenodo (DOI: 10.5281/zenodo.24031111) keeps the first build of v1.0 until v1.1.

To remove something, see Opt-out and removal. To report an error, an attribution concern or personal data that should be masked, email gambarian@gmail.com with a record ID, text ID or source URL and the requested change. Send sensitive details privately. We will explain the action taken, and accepted corrections will be listed in the README of the next version without private information.

<details>
<summary>Export controls for removals and corrections</summary>

Removals go through a removal list that every later build reads (`--removals`); it holds records, texts and the hashes of their stored bodies. The tool also supports `--exclude-host`, `--exclude-ids`, `--exclude-author`, `--author-strict` (also texts quoting the name), `--mask-file` and `--withhold-texts`. Rebuilding is only the export step; already hosted releases and older versions must also be addressed.

</details>

## How to cite

Dataset (version-specific):

> Gambarian, A. S. (2026). *Corpus Voynichianum: the open library of the Voynich manuscript* (v1.0). Dataset. DOI: 10.5281/zenodo.24031111. Available at https://huggingface.co/datasets/Gambarian/corpus-voynichianum. Tools: `tools/` inside the release.

Cite the original author as well as the dataset. Record ids are stable inside a release; include the release version and a text id where relevant.

<details>
<summary>Example citation for an individual record and text</summary>

A single record or text (record ids are stable inside a release; cite the original author as well):

> Parisel, Christophe (2026). Evidence of Layered Positional and Directional Constraints in the Voynich Manuscript: Implications for Cipher-Like Structure. In: *Corpus Voynichianum* (v1.0), record `EXT:ARXIV_2604.19762`, text `ET_3758fa7330fb03959a4b8f17`. Original source: https://arxiv.org/abs/2604.19762. Dataset DOI: 10.5281/zenodo.24031111.

Each text keeps its source address (`source_url`) where one exists and, for the forum, the poster's name. Please cite the original authors together with the library.

</details>

## Build reference

<details>
<summary>Units, file inventory, record counts and export policy</summary>

### Units

A **record** is one catalogued item: one row of `works.csv`. Several records can describe the same real-world work.

A **text** is one row of the text shards: a forum post, mailing-list message, article extract, transcript, abstract or other saved text unit. A text is not necessarily a complete publication or an individual forum post.

A **distinct-work group (provisional)** is a connected group of records joined by `same_work` relations, followed transitively. These relations were judged with models. The groups are a working aid, not a verified count of real-world works.

### Files

Every file and directory listed here is in the dataset (https://huggingface.co/datasets/Gambarian/corpus-voynichianum); this GitHub repository holds only the introduction. Texts are distributed as shards rather than individual files.

Full machine translations (`translation_en`, `translation_gemini`) carry `MACHINE_TRANSLATION` and a visible header: made by the library, not verified or approved by the original author. Read the original source.

- `texts-00000-of-NNNNN.parquet` and `.jsonl`: the same rows in alternative formats. Each text row has `work_id, text_id, kind, quality_flag, author, title, chars, sha256, source_url, source_ref, header, body, body_status, masked`. Each file is at most **500 MB**. Choose one format; do not count both copies as separate texts.
- `machine_annotations_en.csv` and `.parquet`: 14,749 English annotations. **They are written by a machine, not by the author or the publisher. An annotation describes the work and is no substitute for it.** Of the annotations tied to published texts, 7,258 use English source texts, 6,355 use other recorded languages, and 0 have no recorded source language. 1,136 annotations have no text_id; 376 of those records nevertheless carry 752 published texts, which can be short descriptions or other copies. Models: Claude Haiku, Claude Opus, Qwen 3.8, gpt-6.1-sol. **Correction (7 November 2026):** in the `model` column, 13,140 of the 13,612 rows marked `gpt-6.1-sol` were written by Claude Haiku; the other 472 are being traced. See "Known errors in 1.0". `basis` records whether the model received a text extract or catalogue metadata. Opening extracts were up to 2,500 characters in L packs and up to 6,000 in M packs; `chars_source` gives the saved input length, or 0 if unavailable. The minimum annotation length is 80 characters. Join by `work_id`; read the source before relying on an annotation.
- `works_card.csv` and `.parquet`: a supplement to the card, one row per record: year in four digits and how precise it is, language, subject, unit, who wrote the short text. Built by a program, not checked by a person.
- `vocabulary.csv` and `.parquet`: every raw value of `class`, text `kind`, `access_status`, `record_role` and `subject`, with a normalized value, an English label and a count.
- `folio_index.csv` and `.parquet`: which published texts name which leaf of the manuscript, by the standard notation f1r to f116v. Built by a program from the pattern. **A mention does not mean the text is about that leaf.** Forms such as "folio 67 recto" or "fol. 67r" are not caught, and a number may name a leaf that is lost. `text_type=transliteration` marks detected interlinear/IVTFF files and manuscript transcriptions; other rows are `text`. Detection is provisional.
- `works.parquet`, `works.jsonl`, `works.csv`: one row per catalogue record.
- `relations.parquet`, `relations.csv`: links between records and related addresses. `experiment_code_data:*` rows carry an `experiment_id` connecting the experiment's record with a code or data address.
- `experiments.parquet`, `experiments.csv`: recorded questions, methods, results, the registry's judgement of reproducibility, code and data addresses, code-link status and library replication-check status where present.
- `attachments.parquet`, `attachments.csv`: attachment metadata; the attached files themselves are not republished.
- `texts_index.parquet`, `texts_index.csv`: text metadata without bodies, including shard number, 0-based row position and each text's SHA-256. Start here for metadata-only work.
- `rights_decisions.csv`, `replication_recent15.csv`: rights evidence per text; the 15 recent claims the library reran.
- `manifest.json`: counts; shard sizes and SHA-256; a root hash over per-text hashes; the file list with SHA-256; the coverage ledger; and the export command with private arguments redacted.
- `LICENSE.md`: the licence note. `DATA_DICTIONARY.md`: schema documentation. `tools/`: export, checking, example and overview programs.

### Records by kind

| Kind | Records |
|---|---|
| forum | 38,913 |
| web_blog | 9,178 |
| video_podcast | 7,688 |
| social | 5,876 |
| press | 2,251 |
| scholarly | 2,114 |
| other | 1,261 |
| code_data | 1,062 |
| book | 759 |
| archive_collection | 700 |
| culture | 490 |
| experiment_claim | 417 |

### Records by access class

The class describes availability, not permission to reuse; see `DATA_DICTIONARY.md`. `unknown` means the catalogue recorded no licence or access test; it does not mean a rights problem was found.

| Access class | Records |
|---|---|
| open | 34,684 |
| unknown | 30,426 |
| metadata_only | 4,797 |
| restricted | 802 |

### Selection and exceptions

Two more kinds of metadata-only row keep the release to what it is about. `withheld_whole_volume` (17 texts) is a whole reference volume that only mentions the manuscript: the record and the link stay. `withheld_same_text` (60 texts) is a further copy of a text of 100,000 characters or more: the text is published once, and `relations.csv` links different records with `same_text` where applicable; another copy can also belong to the same record. `withheld_binary` (1 texts) retains metadata and any known source link for binary data incorrectly decoded as text; it has no published body and does not count as readable text. This is a data-quality hold, not a rights judgement.

**Forum threads.** Voynich Ninja sections that needed a login when the forum was crawled on 4 October 2026 were not collected, and pages that only asked a guest to log in are excluded. The other threads were crawled that day without a login, as the forum served them. The forum now hides most replies outside its News section from guests, so much of this text can no longer be read there without an account.

**Attachments.** Attached files are not republished; `attachments.csv` contains their metadata only. The snapshot statement in the coverage ledger is a curator statement, not a per-text crawl log.

**Paywalled or restricted works.** The default rule retains the catalogue record, link and at most the abstract. Texts with conflicting access fields, such as both open and paywalled, were withheld. The exceptions above mean this is not an unqualified "never full text" claim.

**Books.** The default rule is records only. Text is normally included only for an open edition first published in 1930 or earlier. That year is a working cut-off, not a worldwide clearance rule.

**Metadata-only material.** A catalogue-only source may have no associated text. This differs from an existing text exported with its body withheld. The record-level access class and the text-level `body_status` should not be treated as interchangeable.

### Withheld at export

| Reason | Texts |
|---|---|
| quarantined_version:QUARANTINED_METADATA_STUB | 7,733 |
| quarantined_version:TEXT_HIDDEN_FROM_GUESTS | 578 |
| retracted_binding | 504 |
| paywalled_or_restricted_full_text | 409 |
| book_record_only_full_text | 277 |
| quarantined_version:QUARANTINED_WRONG_ATTACHMENT | 269 |
| superseded_by_corrected_text | 188 |
| quarantined_version:QUARANTINED_DUPLICATE_REVIEW | 66 |
| quarantined_version:QUARANTINED_EXPLICIT_WORK_ACCESS_STATUS | 19 |
| quarantined_version:NOT_CURRENT_LOWER_CLEAN_SHARE | 18 |
| quarantined_version:WRONG_AUDIO_TRACK | 16 |
| quarantined_version:SUPERSEDED_BY_RETRANSCRIPTION | 2 |
| empty_body | 1 |

### Forum texts and attribution

Every text from voynich.ninja has a `header` beginning:

```text
Author: <author>. Written on the Voynich Ninja forum: <thread URL>
```

The `body` contains the saved extracted text, unchanged after saving except for masking indicated in `masked`. This is not a guarantee of a lossless copy of the original page. The `author` field is retained as saved. For whole-thread extracts, it ends with "; forum contributors" because the text contains a discussion by multiple people. Do not attribute the entire extract to the first named contributor.

Of all texts, **967** have no address of their own; their `source_ref` holds the internal source name.

**Source addresses.** 69,683 of 70,709 records carry an address in `url`. For 12,579 of them the address was built from the saved reference, not read from the source, and `url_basis` says so: 12,518 mailing-list messages point to the public archive file of their month or year on voynich.nu, 30 records with forum references point to a thread, and 31 Reddit records to an address built from the post id. Mailing-list source addresses by host: www.ic.unicamp.br: 1,051, www.voynich.net: 19,309, www.voynich.nu: 12,513; 12,928 messages have an individual msgNNNNN.html page. For archive-file addresses, open the file and search for its subject; `source_ref` also gives the saved reference. The other 1,026 records have no address: 656 of them have a link to another copy or to a same-work record in `relations.csv`, and 370 have neither.

### Duplicate handling

Duplicate handling links retained records rather than collapsing them. Where several records describe the same work, such as a preprint and its landing page, a copy and its original, or a title variant, `same_work` joins them and `works.csv` assigns a `duplicate_group_id`. This does not mean that nothing was withheld or removed from the export.

Group ids are assigned at export time and may change between builds. Cite records by `id`, not by group id. `duplicate_group_size` counts the group's records inside this export. Other relation types include `edition_of`, `part_of`, `review_of`, `unsure_same` and links to code, data and alternate copies. `unsure_same` records disagreement between readers and does not join the records into a `same_work` group.

</details>

Respect, Gamba
