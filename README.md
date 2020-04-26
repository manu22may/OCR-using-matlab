# OCR-using-matlab
Using matlab and a few speech tools present to create an OCR that uses the english language to convert the picture with text into text which is reaad out aloud by the system

Optical Character Recognition(OCR) is the mechanical or electrical conversion of images of typewritten or printed text into machine-encoded text. It is widely used as a form of data entry from printed paper data records, whether passport documents, invoices, bank statements, computerized receipts, business cards, mail, printouts of static-data, or any suitable documentation. It is a common method of digitizing printed texts so that it can be electronically edited, searched, stored more compactly, displayed on-line, and used in machine processes such as machine translation, text-to-speech, key data and text mining. OCR is a field of research in pattern recognition, artificial intelligence and computer vision.

## Character Recognition and how it works
The project is an offline recognition system developed to identify either printed characters or discrete run on handwritten characters .It is a part of pattern recognition that  usually deals with the realization of the written texts in digital form is that ,It requires less space for storage and can be maintained for further references without referring to the actual script again and again.

## How it works?
  The process of converting an image to an editable document is divided into several steps. Every step is a set of related algorithms that do a piece of the OCR job. The general steps in the OCR process are as follows:
  Loading an image as bitmap from a given source. The source can be a file or a pointer to a memory block. Moreover, a good OCR system must understand a lot of image formats: BMP, TIFF (both one-page and multi-page images), JPEG, PNG, and so on. It must also support PDF files, because many documents are stored as images in the PDF format, and the only way to extract text from such files is to perform OCR.
   Detecting the most important image features, such as resolution and inversion. Many OCR algorithms expect a predefined range of font sizes and foreground/background colours, so the image must be rescaled and inverted before processing if necessary.
  Many OCR algorithms can handle bi-tonal images only, so colour or grayscale images must be converted to bi-tonal. The process is called "binarization." This step is very important, because incorrect binarization will cause a lot of problems.
  Lines detection and removal. This step is required to improve page layout analysis, to achieve better recognition quality for underlined text, to detect tables, etc.
  Page layout analysis (also called "zoning"). The OCR system must detect the positions and types of all important areas in the image.
  Detection of text lines and words. Sometimes it is not an easy task because of different font sizes and small spaces between words.
  Combined-broken characters analysis. Oftentimes, some characters are broken into several parts, or some characters touch each other. It is necessary to detect such cases and find the correct position of every character.
  Recognition of characters. This is the main algorithm of OCR. An image of every character must be converted to the appropriate character code. Sometimes this algorithm produces several character codes for uncertain images. For example, recognition of the image of the "I" character can produce the codes for "I", "|", "1", "l"; the final character code will be selected later.
  Dictionary support. This step can improve the recognition quality. Some characters like "1" and "I", "C" and "G" can look very similar, and the dictionary can help to make the decision.
  Saving results to the selected output format, for example, searchable PDF, DOC, RTF, or TXT. It is important to save the original page layout: columns, fonts, colours, pictures, background, and so on.

## Contribution of the authors
1.Research on OCR and matlab functions
2.Downloaded dataset for English text
3.Integrated into code
4.Make necessary optimisations
5.Adding Image enhancements
6.Adding voice inputs
7.Text enhancement added with progression
8.Adding picture to voice 

## Objectives and goals
1)To properly pre-process the image to get best outcomes
2)To Split  the image into lines and characters
3)To correlate the image characters with the dataset characters
4)To try removing any spelling errors due to converting image to text
5)To integrate system audio to read out the text
6)Improve the post processing to get better outputs
