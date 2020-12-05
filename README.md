# Summary

The [LoResMT](https://github.com/panlingua/loresmt-2020/) 2020 Shared Task is a part of the [3rd Workshop on Technologies for MT of Low Resource Languages](https://sites.google.com/view/loresmt/).

# Introduction
In addition to pivot machine translation (MT), the zero-shot approach is one notable development in neural MT (NMT) to build MT systems for language pairs where parallel corpora are small or even non-existent. However, the performance of zero-shot NMT is low compared to pivot MT in general. In this shared task, we solicit participants to submit novel zero-shot NMT systems for the following language pairs:

	Hindi-Bhojpuri
	Hindi-Magahi
	Russian-Hindi

## Structure of the `LoResMT-2020 Shared Task data`:
```
loresmt2020/
├─ monolingual/
│  ├─ mono.loresmt-2020.bho
│  ├─ mono.hi/
│  │  └─ mono.loresmt-2020.hi
│     └─ mono.pmindia.v1.hi( borrowed from http://data.statmt.org/pmindia/v1/monolingual/pmindia.v1.hi.tgz)	
│  ├─ mono.loresmt-2020.mag
│  ├─ mono.loresmt-2020.ru
│  
└─ Dev/
   ├─ dev.bho
   ├─ dev.hi
   ├─ dev.mag   
   ├─ dev.ru
├─ bho2hi.test.bho
├─ bho2hi.test.hi
├─ hi2bho.test.bho
├─ hi2bho.test.hi
├─ hi2mag.test.hi
├─ hi2mag.test.mag
├─ hi2ru.test.hi
├─ hi2ru.test.ru
├─ mag2hi.test.hi
├─ mag2hi.test.mag
├─ ru2hi.test.hi
├─ rui2hi.test.ru
├─ license.md
├─ license.txt
├─ README.md
   
```
**The data Statistics are presented below (the Dev data are multilingual):
-----------------------------------------------------
Language_Name	Total_Sentences		Total_Words

Bhojpuri (bho)	91131	1562465

Hindi (hi)	473605	7092870

Magahi (mag)	148606	2178424

Russian (ru)	154589	1007029

Hindi-Bhojpuri (dev)	500

Hindi-Magahi (dev)	500

Hindi-Russian (dev)	500

Hindi-Bhojpuri (test)	500

Hindi-Magahi (test)	500

Hindi-Russian (test)	500

# Acknowledgments

We would like to thanks [Alok,Deepak; Lahiri, Bornini and Kumar, Ritesh](http://lrec-conf.org/workshops/lrec2018/W11/pdf/26_W11.pdf) for sharing  Magahi monolingual data to [Panlingua Language Processing LLP](http://panlingua.co.in/). 

## References
If you use this data, please cite:
<pre>
@inproceedings{ojha-etal-2020-findings,
    title = "Findings of the {L}o{R}es{MT} 2020 Shared Task on Zero-Shot for Low-Resource languages",
    author = "Ojha, Atul Kr.  and
      Malykh, Valentin  and
      Karakanta, Alina  and
      Liu, Chao-Hong",
    booktitle = "Proceedings of the 3rd Workshop on Technologies for MT of Low Resource Languages",
    month = dec,
    year = "2020",
    address = "Suzhou, China",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.loresmt-1.4",
    pages = "33--37",
}
</pre>
other papers/references about the LoResMT shared task are:
<pre>
@proceedings{ws-2019-technologies,
    title = "Proceedings of the 2nd Workshop on Technologies for MT of Low Resource Languages",
    editor = "Karakanta, Alina  and
      Ojha, Atul Kr.  and
      Liu, Chao-Hong  and
      Washington, Jonathan  and
      Oco, Nathaniel  and
      Lakew, Surafel Melaku  and
      Malykh, Valentin  and
      Zhao, Xiaobing",
    month = aug,
    year = "2019",
    address = "Dublin, Ireland",
    publisher = "European Association for Machine Translation",
    url = "https://www.aclweb.org/anthology/W19-6800",
}
</pre>

<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: LoResMT Shared Task-2020
License: CC BY-NC-SA 4.0
=======
Includes text: yes
Genre: nonfiction news/subtitle/news
Shared Task Organiser: Ojha, Atul Kr.; Malykh, Valentin; Karakanta, Alina; Liu, Chao-Hong
Contact: shashwatup9k@gmail.com, valentin.malykh@phystech.edu
Contributor/&copy;holder: Panlingua Language Porcessing LLP, N. Delhi, India
===============================================================================
</pre>
