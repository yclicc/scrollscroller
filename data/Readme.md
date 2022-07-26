# Dataset
This contains one record for each chapter of the Christian Bible, not including the deuterocanonical books.
### Fields:
1) title: The name of the chapter, e.g. "Genesis 4", "Psalm 1" (note not "Psalms 1"). Feeding this into Bible Gateway search should yield the text of the chapter.
2) testament: "Old Testament" for the first 39 books, "New Testament" for the rest.
3) book: The name of the book, e.g. "Genesis", "Psalms" (note not "Psalm").
4) chapter: The chapter number within the book, e.g. for Psalm 2 this will be 2
5) verses: How many verses are in this chapter in the 2011 NIV translation (Copyright © 1973, 1978, 1984, 2011 by Biblica, Inc.™). Note however that this is just based on the highest verse number that appears in the chapter, so verses which are relegated to a footnote ARE still counted. For example, Mark 7:16 is omitted from the NIV but Mark 7 still counts as having 37 verses.
6) book_index: The number of the book in the traditional Christian ordering, e.g. Genesis is 1, Psalms is 19, Matthew is 40.
7) chapter_index: The number of the chapter since the start of the Bible, e.g. Genesis 1 is 1, Psalm 1 is 479 and Psalm 117 is 595 (the median chapter in this ordering).
8) verse_index: The number of the FINAL verse in that chapter since the start of the Bible, e.g. Genesis 1 is 31 as Genesis 1 has 31 verses, Genesis 2 is 56 as there are another 25 verses in Genesis 2.
9) hebrew_book_index: The number of the book if the Old Testament/Hebrew Bible is ordered according to the traditional Jewish Tanakh ordering, e.g. Genesis is still 1, but Psalms is 27 instead of 19 and 2 Chronicles is 39 instead of Malachi.
10) hebrew_chapter_index: Same as chapter_index but for the Hebrew ordering. Interestingly the median chapter in the whole Bible is then Psalm 28, whilst in just the Hebrew Bible by itself it is Ezekiel 13.
11) hebrew_verse_index: The number of the FINAL verse in that chapter since the start of the Bible, but in the Tanakh ordering.
