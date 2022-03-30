<!--
author:   Hermann Schranzhofer

email:    hermann.schranzhofer@tugraz.at

version:  0.0.1

language: en

comment:  This is a short course on the topic Research Data Management.
          It was created during the project FAIR Data Austria.

link:     https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.css

script:   https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js

translation: Deutsch  translations/German.md

-->

# Open Educational Resources for Research Data Management


{{1}}
Dieser Block erscheint als erster.

{{2-3}} Dieser Block als zweiter und
verschwindet bei drei.


```prolog blumenstrauss.pro
rot(rose).
gelb(tulpe).
weiss(nelke).
blau(vergissmeinnicht).
blau(veilchen)
```

__Description:__ The collection of open educational resources (OER) on the following pages was created by the Training Task Force in 2021 as part of the FAIR Data Austria project (BMBWF, 2020-2022). The collection consists of selected OER enhanced by further information and interactive elements to provide an introduction to the following nine topics. The pages or the individual elements can be reused to create informational and training materials on research data management. The collection is also available at https://fair-office.at/index.php/lernen-sie-mehr/.



__Authors:__ Christiane Stork, Elena Fürst, Heike Thöricht, Hermann Schranzhofer, Nikos Gänsdorfer, Tereza Kalová, Therese Macher.
The authors were supported by interns at the Vienna University Library in August 2021: Christine Stridde, Rebecca Ringbauer, Sonja Schillings, Tamara Köstenbach.

__License:__ [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) unless otherwise stated

__Cite the collection as:__ FAIR Data Austria (2021). Open Educational Resources Research Data Management. Link to website (https://fair-office.at/index.php/lernen-sie-mehr/?lang=en).

[Learn more about FAIR](https://fair-office.at/index.php/information-for-researchers/learn-more-about-fair/?lang=en)

## File Formats

The file format is created by saving a file and contains information about the structure of data contained in a file, its purpose and affiliation. Application software can use the information available in the file format to interpret the data and make the contents available. The format of a file is added to the actual name with an appropriate extension. This consists of a point and two to four letters.

With so-called proprietary formats, the files can only be opened, edited and saved with the associated application, auxiliary or system programs (e.g. .doc/.docx, .xls/.xlsx). Open formats (e.g. .html, .jpg, .mp3, .gif), on the other hand, make it possible to open and edit the file with software from different manufacturers.

File formats can be actively changed by conversion when saving, but data loss can occur. In the scientific field, particular attention should be paid to compatibility, suitability for long-term archiving and lossless conversion to alternative formats.

!?[youtube](https://www.youtube.com/watch?v=kxxlQnc8u1I)

__Duration:__  5:12 min

__Content:__ This short knowledge clip explains what file formats are, why they are important for research data management and what you should pay attention to.

__Licence:__ [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.en)

```block -Transcript
> What is the importance of file formats in research data management?

> A file format is a way of encoding information within a computer file. When a programme or an
> application wants to use a file, it needs to recognise the file format so that it can access the
> content within a file. One of the most common ways to recognise a file format is to look at the file
> name extension. Usually this is represented by three or four characters at the end of the file name
> after a full stop.

When you start planning your project, it is important to consider the file formats that you will use throughout your research. Sometimes the choice of a format is influenced by norms within your research discipline. For instance, by commonly used software programmes or file formats that you and your colleagues have used in the past. Or, the choice might also depend on the type of hardware or instrument you will use. In other situations, choosing a specific format might limit the possibility to collaborate with other scientist who don’t have access to the same software tools.

And last but not least, certain file formats are less future proofed than others. We often refer to this problem as file format obsolescence. And there are several reasons for this to happen. For example, sometimes older versions of a file format are no longer supported by newer versions of the software. Or, the software supporting the format is no longer available or cannot be used in newer operating systems. So, choosing the appropriate file format has implications doing your research project, but also for the long-term usability of your data.

All file formats are vulnerable to obsolescence to a certain degree. However, the sustainability of a file format can increase when you use what we call open and standard formats. Remember that a file format describes the way in which information is stored and organised within a computer file. If this description, known as file format specification, is available for anyone to see and free of charge, then we talk about open file formats. When a specification is not publicly available or there are limitations on how it can be reused, we talk about closed formats.

Let’s have a closer look. Closed formats, often called proprietary formats, are usually developed for commercial software applications. These files might only be readable with the same software used to create them for which licences is needed. Files produced with one version of the software might not be compatible with older or newer versions. Because the use of closed file formats depends on a specific software package or even a specific version of a software, they are more vulnerable to obsolescence. In other words, closed formats are less sustainable.

Open file formats can be both, proprietary and non-proprietary. Sometimes they are developed and maintained by a commercial company. But most often they are released by a standardisation body or a community without commercial interest. In any case, the file format specifications are open, which means that anyone can potentially develop software packages or applications that can use these formats, maximising the interoperability and reuse of information they contain. Besides, compatibility with older versions of the format is a priority. Making these types of formats less subject to obsolescence issues. So, in general open and non-proprietary formats are more sustainable when it comes to preserving data.

But sometimes we don’t have a choice but to use closed formats. In such cases it is good practice to also create a copy of your files in an open format to increase the chances of your data being accessible in the long term.

Actually, file format conversion might be needed at any moment of your research. For example, to use the data with a different software package or to share it with others. However, you should realise that converting files from one format to another might result in a loss of content, metadata or quality.

Before you migrate files to another format, it is important to be aware the risks and to test what can go wrong. It is also good practice to keep the original files, so you can always return to them and repair any errors or changes in your data if something goes wrong with your file conversion.

When choosing a file format, it might also be important to check what kind of compression is used. Compression is the process of encoding information using fewer bits than the original representation.

There are two types of compression. Lossless compression allows the original data to be perfectly reconstructed from the compressed data. When a file is compressed using this method, uncompressing it again results in a file that is identical to the original file.

But there are also lossy types of compression where some of the content is lost. Before performing a lossy compression, it is advisable to do some research to understand what compression parameters should be used. The objective should be to retain the critical information needed to make your files reusable.

As you can see, there are a few things to consider when it comes to file formats. To get started you can access a list of recommended formats via our website. Take a look!
```


__Quiz__<!-- style="color: black; font-size: 20px;" -->



What criteria should be considered when choosing a format?

    [[ ]] Formats are not of importance at all
    [[X]] Compatibility, suitability for long-term archiving and lossless conversion
    [[ ]] Proprietary data format and compressibility


Which file formats should be used?

    [[ ]] Files or formats should be encrypted, compressed, proprietary or patented
    [[X]] Open, documented standards should be preferred
    [[ ]] The file format does not matter, as software companies ensure compatibility anyway


What is the best way to ensure that digital data is accessible for a long time?

    [[ ]] The use and storage of proprietary data formats
    [[ ]] The use and storage of hardware-specific data formats
    [[X]] The use and storage of open data formats

__Further information__<!-- style="color: black; font-size: 20px;" -->

You can find further information including [descriptions of various file formats](https://www.loc.gov/preservation/digital/formats/fdd/descriptions.shtml) on the Library of Congress website.

You can download data management best practices evaluation checklist from the UCSB Library for some helpful tips on file formats and organization.


__Citation__<!-- style="color: black; font-size: 20px;" -->

FAIR Data Austria (2021). “File formats “. In: Research Data Management Open Educational Resources Collection. (https://fair-office.at/index.php/fileformates/?lang=en).

License: CC BY 4.0 unless otherwise stated.

## Data Management Plan (DMP)

## FAIR Data vs. Open data

## FAIR Principles

## Research Data Management (RDM)

## Metadata

## Open Science

## Persistent Identifier (PID)

## Publication of data
