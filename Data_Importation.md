# Preprocessing Techniques: *Data Importation* 
## Mayte Alejandra Chi Poot 
### Data Engineering 3B
### Data table: 
Data tables display sets of data across rows and columns. They organize information in a way that’s easy to scan so that users can look for patterns and develop insights from data.  [Source](https://material.io/components/data-tables)
### Data types:

- Categorical: They are variables in the data set that unlike continuous variables take a finite set of values. For example, grades that students are given by a teacher for assignments (A, B, C, D, E, and F). In the dataset, categorical variables are often strings. [Source](https://towardsdatascience.com/what-are-categorical-variables-and-how-to-encode-them-6e77ddc263b3)
- Numerical: 
    - An integer is a numeric value without a decimal. Integers are whole numbers and can be positive or negative (1, -7).
    - A number with a decimal is referred to as a decimal, a float or a double (13.5, 20.03). 
- Boolean: Has two possible values (Usually true or false) that represent the two truth values of logic and Boolean algebra. [Source](https://techterms.com/definition/boolean)
- Dates: Holds IEEE 64-bit (8-byte) values that represent dates ranging from January 1 of the year 0001 through December 31 of the year 9999, and times from 12:00:00 AM (midnight) through 11:59:59.9999999 PM. [Source](https://docs.microsoft.com/en-us/dotnet/visual-basic/language-reference/data-types/date-data-type#example)
- Strings: Represents text rather than numbers and uses characters to do so. 

### Data formats

- csv:It has a header with the columns and main properties, and the following rows are the data.
- json: JavaScript Object Notation, Lightweight format for storing and transporting data. It is easy for machines to parse and generate. JSON is built on two structures:
    - A collection of name/value pairs. In various languages, this is realized as an object, record, struct, dictionary, hash table, keyed list, or associative array.
    - An ordered list of values. In most languages, this is realized as an array, vector, list, or sequence. [Source](https://www.json.org/json-en.html):
- xml: Self descriptive eXtensible Markup Language designed to store and transport data. It can be viewed and edited by basic text editors. [Source](https://fileinfo.com/extension/xml#:~:text=An%20XML%20file%20is%20an,open%20in%20Microsoft%20XML%20Notepad)
- xls: Microsoft Excel's workbook files containing all the information from the worksheets in a workbook, including formatting, charts, images, formulas, etc.

### Local and Remote repositories

- url: A remote URL is Git's fancy way of saying "the place where your code is stored." That URL could be your repository on GitHub, or another user's fork, or even on a completely different server. [Source](https://docs.github.com/en/free-pro-team@latest/github/using-git/about-remote-repositories)
- apis: To interact with any defined repository, use the default repository APIs that are included in Pega Platform. Other methods of interacting with files, such as using custom java, are not supported. [Source](https://community.pega.com/knowledgebase/articles/data-management-and-integration/84/repository-apis)

### Secure data transfer protocols
- File Transfer Protocol (FTP), Its objectives are:
    - to promote sharing of files (computer programs and/or data).
    - to encourage indirect or implicit (via programs) use of remote computers.
    - to shield a user from variations in file storage systems among hosts.
    - to transfer data reliably and efficiently.
[Source](https://www.sftpplus.com/articles/2018/sftpplus-best-protocols.html)
- Hypertext Transfer Protocol (HTTP): is an application-level protocol for distributed, collaborative, hypermedia information systems. It is a generic, stateless, protocol which can be used for many tasks. [Source](https://www.sftpplus.com/articles/2018/sftpplus-best-protocols.html)

### Procedures for data importing
There are many ways of importing data and they all depend on where you are working on, every method needs a file that contains the data which is then added onto the workspace so that it can be read and modified at will in order to perfect the visualization of information. The first step to import data in a environment is to be able to this data, we can use a file that are in our computer, and this file could has a -read- permission, but a lot of times the file that we need is on internet.
[Source](https://v8doc.sas.com/sashtml/accpc/z1227915.htm) 
