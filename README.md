# OCR Correction Project

This project is dedicated to correcting text extracted from the Mvskoke translation of the book of Genesis. The goal is to produce a clean, readable copy by identifying and fixing errors introduced by Optical Character Recognition (OCR) software.

Skip to [Progress](#progress) to see the current status of the project.

## Guidelines for Editing

## Common OCR Errors & Corrections

Here are some common OCR mistakes to look out for:

- `"cn"` versus `"en"` (e.g., `"cn nvrkvpv"` should be `"en nvrkvpv"`)
- `"fnswv"` versus `"fuswv"`
- `"inake"` versus `"hake"`
- `,` versus `.`
- `S` versus `8` (page number, chapter number, verse numbers, e.g.)

## Why Accuracy Matters

The Mvskoke translation of the book of Genesis is a valuable resource for the Mvskoke people and others interested in the language. By correcting OCR errors, we can ensure that the text is accessible and accurate for future generations.

I was taught that those who worked on translating these biblical texts were extremely careful with their work. We should strive to act with the same care and respect for their efforts.

### ✅ DO
- Correct clear misreadings.
- Fix obvious word splits, but only if you’re sure of the correction.
- Keep the original formatting (paragraphs, spacing, apostrophe style, etc.) intact.

### ❌ DON'T
- Relocate or reposition words.
- Remove blank lines.
- Remove blank spaces at end of lines.
- Modify words unless you're sure they are OCR errors.

---

## Process

For the first pass through, the process is to amend one chapter at a time:

1. With the scanned image pulled up along side the original OCR text, read
   verse by verse, comparing the two and correcting any discrepancies in the
   text.
2. Once the chapter is complete, stage the changes using `git add --patch` and
   be sure to review the changes you've made to each verse. Essentially this
   be just like step 1.
      a. Best to use `s` (split) to split large chunks of differences into
         smaller, more manageable pieces.
      b. For each chunk, look closely at the unchanged lines to be sure you
         haven't missed anything.
      c. Also look closely at the lines you've changed (in green) to be sure
         you've made the correct changes and haven't missed anything.
      d. Use `e` (edit) to make changes to the chunk if any of your changed lines
         need additional work.
      e. Do not use `e` to change the unchanged lines, even if you see you've
         missed something. Instead, make note of the Chapter and verse number
         and make the changes after you finish staging your made-so-far changes.
3. Once you're satisfied with the changes you've made, commit, push, and send
   a pull request.
4. As chapters become complete, they can be confirmed and reconfirmed by anyone.

## Progress

Ceneses has 50 chapters. The status of each chapter is as follows:

- ✅ Chapter 1
- ✅ Chapter 2
- ✅ Chapter 3
- ✅ Chapter 4
- ✅ Chapter 5
- ✅ Chapter 6
- ✅ Chapter 7
- ✅ Chapter 8
- ✅ Chapter 9
- ✅ Chapter 10
- ✅ Chapter 11
- ✅ Chapter 12
- ✅ Chapter 13
- ✅ Chapter 14
- ✅ Chapter 15
- ✅ Chapter 16
- ✅ Chapter 17
- ✅ Chapter 18
- ✅ Chapter 19
- ✅ Chapter 20
- ✅ Chapter 21
- ✅ Chapter 22
- ✅ Chapter 23
- ✅ Chapter 24
- ✅ Chapter 25
- [ ] Chapter 26
- [ ] Chapter 27
- [ ] Chapter 28
- [ ] Chapter 29
- [ ] Chapter 30
- [ ] Chapter 31
- [ ] Chapter 32
- [ ] Chapter 33
- [ ] Chapter 34
- [ ] Chapter 35
- [ ] Chapter 36
- [ ] Chapter 37
- [ ] Chapter 38
- [ ] Chapter 39
- [ ] Chapter 40
- [ ] Chapter 41
- [ ] Chapter 42
- [ ] Chapter 43
- [ ] Chapter 44
- [ ] Chapter 45
- [ ] Chapter 46
- [ ] Chapter 47
- [ ] Chapter 48
- [ ] Chapter 49
- [✅] Chapter 50
