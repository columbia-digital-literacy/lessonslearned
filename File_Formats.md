

<html>
<body>

<h1>File Formats</h1>

<b>What are they?</b>
<p>File formats are standardized methods by which information is encoded for storage in computer files. They specify how bits are encoding information in digital storage media. The formats can be proprietary or free, and open or unpublished. There are dozens of different file formats across many different environments, but this document will list several formats that are basic, as listed below:</p>
<ol>
<li>Fixed field length</li>
<li>Delimited list (CSV)</li>
<li>Extensible Markup Language (XML)</li>
<li>JavaScript Object Notation (JSON)</li>
<li>Yet Another Markup Language (YAML)</li>
</ol>
<b>Fixed Field Length</b>
<p>Fixed field length file format is a special case of data storage where the format is specified by column widths, pad character and left/right alignment.  Column widths are in units of characters. So if you have data in a text file where the first column always has exactly 10 characters, and the second column has exactly 5, the third has exactly 12 (and so on), then you have a fixed width text file format.</p>
<p>Each row (paragraph) contains one record of information; each record can contain multiple pieces of data (fields), each data field (column) has a precise number of characters. The data is padded with spaces (or any character you specify) if it does not completely use all the characters allotted to it. Further, each piece of data can be left or right justified, meaning the padding of characters can occur on either side.</p>
<p>Fixed field length is not a self-documenting file format.</p>

<b>Delimited List</b>
<p>Delimited list file formats use delimiter-separated-values (DSV) to store two-dimensional arrays of data by separating the values in each row with specific delimiter characters, such as comma, tab and colon. This format has the advantage of the ability to store data of any size potentially, compared to fixed field length.</p>
<p>Delimited list is not a self-documenting file format.</p>

<b>Extensible Markup Language (XML)</b>
<p>Extensible Markup Language is a markup language file format that defines a set of rules for encoding documents in a format which is both human-readable and machine-readable. It is defined by the W3C's XML 1.0 Specification and by several other related specifications, all of which are free open standards. This file format is very similar to HTML, only without hypertexts. This file format is self-documenting.</p>
 <p>The design goals of XML emphasize simplicity, generality and usability across the Internet. It is a textual data format with strong support via Unicode for different human languages. Although the design of XML focuses on documents, it is widely used for the representation of arbitrary data structures such as those used in web services.</p>

<b>JavaScript Object Notation (JSON)</b>
<p>JSON (JavaScript Object Notation) is a lightweight data-interchange format that is easy for both humans to read and write, as well as for machines to parse and generate. It is based on a subset of the JavaScript Programming Language, Standard ECMA-262 3rd Edition - December 1999. JSON is a text format that is completely language independent but uses conventions that are familiar to programmers of the C-family of languages, including C, C++, C#, Java, JavaScript, Perl, Python, and many others. These properties make JSON an ideal data-interchange language.</p>

<b>YAML</b>
<p>YAML (rhymes with camel) is a human-readable data serialization language that takes concepts from programming languages such as C, Perl, and Python, and ideas from XML and the data format of electronic mail. YAML is available for several programming languages.</p>
<p>YAML is a recursive acronym for "YAML Ain't Markup Language". Early in its development, YAML was said to mean "Yet Another Markup Language",but it was then reinterpreted to distinguish its purpose as data-oriented, rather than document markup.</p>

<b>Sources</b>
<ol>
<li>http://www.softinterface.com/Convert-XLS/Features/Fixed-Width-Text-File-Definition.htm</li>
 <li>www.json.org</li>
 <li>[Wikipedia.org](www.wikipedia.org)</li>
</ol>
</body>
</html>

![FileTypes](http://jhigh.co.uk/Images/DataFileTypes/FileTypes.png)
