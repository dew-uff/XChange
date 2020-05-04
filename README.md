# XChange: A Semantic Diff Approach for XML Documents

XML documents are increasingly being used to allow data interchange among sys-tems. A related problem is that XML documents evolve over time, so identifying and under-standing these changes becomes fundamental. However, existing approaches related to under-standing changes (diff) in XML documents are focused only on syntactic changes. This means that these approaches compare XML documents based on their structures, without considering the associated semantics. For large XML documents, which have undergone many changes from a version to the next, fewer semantic changes might encompass many syntactic changes. This feature has the potential to ease the understanding of changes in XML documents. Thus, this proposal presents the XChange approach to provide support for diff of XML documents considering the semantic of the changes. For such, the granular syntactic changes in attributes and elements are analyzed by means of inference rules. This analysis identifies sets of syntac-tic changes that can be combined into semantic changes. Thus, differently from existing ap-proaches, XChange proposes the use of syntactic changes in versions of an XML document as a means to infer the real reason for the change and support the process of semantic diff. In order to ensure the correct functioning of the semantic diff, it is important to evaluate the quality of the matching among elements. The experimental results show that XChange was able to provide equivalent precision results, with only a fraction of the time needed by a state-of-the-art approach, being a more efficient approach. Furthermore, the results show that XChange presents higher efficacy and efficiency in understanding changes between versions of XML documents, when compared to a state-of-the-art approach.

# Team


# Dataset

[Baltmore](http://link)


# Publications


# License Terms

Copyright (c) 2016 Universidade Federal Fluminense (UFF)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
