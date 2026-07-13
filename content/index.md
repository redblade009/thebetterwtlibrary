---
publish: true
created: 2026-07-12T21:38:00.391+12:00
modified: 2026-07-13T03:04:49.027+12:00
---

![[Vault Resources/The Better Watchtower Library Image.png|675]]

# Read Me

## The Point of this Vault

The point of this Vault is simple, make it as easy as possible to research and look up Watchtower publications in detail without risk of them being altered, removed, or hidden by the Watchtower. There is evidence of them doing this out in the wild if you want to research it, but a couple of prime examples can be seen in the Examples of Alteration below. It is clear from the examples below (and many others that have been altered or removed from the Watchtower Online Library) that the Watchtower can't be trusted to not change things, but I guess it is understandable when they make statements like the following

![[Vault Resources/2016 Jan Watchtower Personal.png]]
Can be seen at the following link: [Open Watchtower Jan 2016 Personal Pg 5](https://pdfs-noindex.themindscapeishere.workers.dev/wp_E_201601.pdf#page=5)

> [!important] Questions to ask
>
> 1. Who decides who is entitled to know the truth?
> 2. Are Jehovah's Witnesses entitled to know the truth?

### Example of Alteration 1

#### Single Magazine Version of the January 1 1989 Article Pg 12

![[Vault Resources/1989 The Watchtower_Single_Volume.png]]

#### Bound Volume Version of the January 1 1989 Article Pg 12

![[Vault Resources/1989 The Watchtower_Bound_Volume.png]]

### Example of Alteration 2

There are other cases of this kind of example, but I will show the main one

#### 1984 New World Translation Printed Book Colossians 1:16-17

The Print version keeps the square brackets implying that the word "other" is a word added and not in the original Greek

![[Vault Resources/NWT 1984 Print Ver Col 1.16-17.jpg]]

#### 1984 New World Translation PDF File Download Colossians 1:16-17

The square brackets surrounding the occurrences of the word "other" have been removed, implying that the word "other" has been  translated from the Greek when it is not in the Greek at all.

![[Vault Resources/Pages from 1984 New World Translation of the Holy Scriptures (bi12-E)-2-1.png]]

![[Vault Resources/Pages from 1984 New World Translation of the Holy Scriptures (bi12-E)-2-2.png]]

The second point to this vault is that the Watchtower Online Library only contains Watchtower/Awake Magazines as far back as 1950 and books as far back as 1970. This vault contains ALMOST EVERYTHING published in written form (only missing the odd thing here or there) and even contains other things such as various revisions of the Elder's Book and some internal documents (These came from leakers who I do not have any contact with, I simply downloaded them from some archives)

# Vault Information

## How this Vault Works

- Within this Vault, there are different sections and they are setup in such a way to make all this work
  - **Dummy PDFs:** These are to do with the PDF++ Plugin and are solely there so that Obsidian can link externally to the PDFs folder one step back in the file path. this is done so that the links in the text-based versions of the publications can open the PDFs without lagging obsidian to the point of crashing on startup (DO NOT RENAME OR DELETE THESE OTHERWISE THE LINKS WILL BREAK)
  - **Publications:** These are the Markdown text versions of the publications. They should all be paginated based on the PDFs in the PDFs folder separated by a line break to show where one page ends and the next begins. There are also page numbers in super script which show the PDF page number (e.g. <sup>**Page 2**</sup>). The print-based pagination will be there if the publication had print-based pagination and how that shows will depend on the publication. Lastly there will be links on each page which when clicked will open up the PDF in a tab to the left or right of the text and should open up to the page based on the link name
  - **Vault Resources:** This just contains stuff I used in the vault like the image on this page, just ignore it

- There are also some useful things you can do with Obsidian, but I would recommend researching how to use obsidian for that. There are also a bunch of plugins that can be used but if I gave this to you, then I probably explained about that. if you are just browsing then you shouldn't need to worry about them.

- The vault is also setup to do Semantic Searching with AI through QMD https://github.com/tobi/qmd (it uses a forked plugin to do it. it may not be setup unless I showed you how to set it up and use it)

- Lastly, as mentioned in the "Dummy PDFs" section, this vault uses a feature in PDF++ to allow the PDFs to be loaded while they are outside the vault, otherwise it would have to load 60GBs or so of PDFs every time the vault was opened which just wouldn't work. These PDFs are located in the same file as the vault folder itself (one step back in the folder path from here) and the links in the publications use "Relevant Paths" so that it can dynamically figure out the file path before that folder. This means you should be able to put the main "WT-Library" folder anywhere and the links should still work

- DO NOT CHANGE THE LOCATION OF THE ORIGINAL PDFS! This will break the links in the Publications files

## File Names

- While Some of the publications are named with the year it was published, then the full name. some of them are named by their short-form codes with the date of the article
  - For example "w\_E\_19640715" which can be interpreted as The Watchtower (w\_E\_) / YYYY / MM / DD so this is the watchtower magazine for **15th of July 1964**
  - Some may only have the Year and the month, for example "bsm\_E\_191401" which can be interpreted as "Bible Students Monthly" (bsm\_E\_) / YYYY / MM so this would be the Bible Students Monthly for January 1914.
  - Others may not immediately be obvious and require checking the file
- All the Publications will have some kind of tagging, this will allow you to be able to search by tags
  - E.g. "w\_E\_20040401" has the tags "tags: "watchtower", "magazine", "2000s"

## OCR Information

- Approximately 99.9% of these OCRs of these are from scans of the original physical publications (the approximately 0.01% are pretty much in the books section where I decided to just use them as they were good quality digital copies and they are older books)
- Mistral AI OCR model was used to OCR these scans, and while it is much better than traditional OCR that you might get on say Adobe Acrobat, it is not perfect and there may be errors scattered throughout. This is why each Markdown Text file has baked in links to the PDF, it is recommended to read from those as they will be accurate
- The main ones with errors will be ones that are designed like a Newspaper (e.g. Kingdom News, Bible Students Monthly, etc...) I would highly recommend reading the linked PDFs for those as there was no good way of OCRing them properly. Some sections in them are fine but others have glitched paragraphs, this is because the scans had many columns and the text was very small so the AI couldn't pick it up on most of it.
  - **E.g.** _"Thus the great finale is marked, similar, much of the most880s of progress and with the first of the world. The most successful ever ever is the world, and the most successful ever is the world, and the most successful ever is the world, and the most successful ever is the world, and the most successful ever is the world, and the most successful ever is the world, and the most successful ever is the world, and the most successful ever is the world, and the most successful ever is the world, and the most successful ever is the world, and the most successful ever is the world, and the most successful ever is"_ <sub>\[Kingdom News 3 (/News/Kingdom News/kn03\_E)]</sub>
