# 4 术语和定义

**Terms and definitions**

=== "中文"

    为了本文档的目的，这些术语和定义适用。
    
    **4.1**
    
    **… (ellipsis)**
    
    在 PDF 示例中使用省略号来表示省略的细节。成对的省略号也用来括住关于这些省略细节的评论，以斜体显示。
    
    **4.2**
    
    **8位值(8-bit value)**
    
    (见 byte)
    
    **4.3**
    
    **数组对象(array object)**
    
    一个一维的对象集合，这些对象按顺序排列，并从 0 开始隐式编号
    
    **4.4**
    
    **ASCII**
    
    美国信息交换标准代码，一种广泛使用的传统，用于将一组特定的 128 个字符编码为在 ANSI X3.4-1986 中定义的二进制数字
    
    **4.5**
    
    **二进制数据(binary data)**
    
    字节的有序序列
    
    **4.6**
    
    **布尔对象(boolean objects)**
    
    关键字 **true** 或关键字 **false** 中的一个
    
    **4.7**
    
    **字节(byte)**
    
    一组 8 位二进制数字，它们共同可以配置来表示 256 个不同的值，并且 8 位二进制数字的各种实现在当今的电子设备中被广泛使用
    
    **4.8**
    
    **目录(catalog)**
    
    主要的字典对象，包含对文档中所有其他对象的直接或间接引用，但可能有例外，即在 **尾段** 中可能有一些对象没有被 **目录** 引用
    
    **4.9**
    
    **字符(character)**
    
    根据某些定义的字符编码规则表示抽象符号的数字代码
    
    !!! info "NOTE 1"
    
        在 PDF 中，根据上下文，字符有三种表现形式：
        
        - PDF 文件表示为 8 位字节序列，其中一些被解释为 ASCII 字符集中的字符代码，而另一些则根据上下文被视为任意二进制数据。
        - 在某些情况下，字符串或流对象的内容（数据）被解释为 PDFDocEncoding 或 UTF-16 字符集中的字符代码。
        - 在 PDF 内容流中的字符串的内容，在某些情况下被解释为字符代码，根据与文本字体相关联的字符编码选择要绘制在页面上的字形。
    
    **4.10**
    
    **字符集(character set)**
    
    每个符号都被赋予一个唯一字符值的已定义集合
    
    **4.11**
    
    **合规阅读器(conforming reader)**
    
    能够读取和处理符合本规范制作的 PDF 文件的软件应用程序，并且本身符合此处指定的合规阅读器的要求 [ISO 32000-1]
    
    **4.12**
    
    **合规产品(conforming product)**
    
    既是合规阅读器又是合规写入器的软件应用程序
    
    **4.13**
    
    **合规写入器(conforming writer)**
    
    能够写入符合本规范 [ISO 32000-1] 的 PDF 文件的软件应用程序
    
    **4.14**
    
    **内容流(content stream)**
    
    数据由一系列指令组成，描述要在页面上绘制的图形元素的流对象
    
    **4.15**
    
    **交叉引用表(cross reference table)**
    
    包含文件中每个间接对象的字节偏移起始的数据结构
    
    **4.16**
    
    **开发者(developer)**
    
    任何实体，包括个人、公司、非营利组织、标准机构、开源组织等，他们正在开发使用和扩展 ISO 32000-1 的标准或软件。
    
    **4.17**
    
    **字典对象(dictionary object)**
    
    包含对象对的关联表，第一个对象是作为键的名称对象，第二个对象是作为值，可以是任何类型的对象，包括另一个字典
    
    **4.18**
    
    **直接对象(direct object)**
    
    尚未制成间接对象的任何对象
    
    **4.19**
    
    **电子文档(electronic document)**
    
    以页面为单位的文本、图像和图形数据以及元数据的电子表示，这些数据有助于识别、理解和呈现这些信息，并且可以在纸张上复制或显示，而不会显著丢失其信息内容。
    
    **4.20**
    
    **行结束标记 (EOL 标记)(end-of-line marker (EOL marker))**
    
    标记文本行结束的单个或两个字符序列，由回车符 (0Dh) 或换行符 (0Ah) 或回车符后紧跟换行符组成。
    
    **4.21**
    
    **FDF 文件(FDF file)**
    
    符合表单数据格式的文件，包含可导入 PDF 文件的表单数据或注释（见 [12.7.7 节](./c12/s7.md#1277-表单数据格式)，“表单数据格式”）。
    
    **4.22**
    
    **过滤器(filter)**
    
    流对象规范中的一个可选部分，指明在使用流中的数据之前应如何对其进行解码。
    
    **4.23**
    
    **字体(font)**
    
    可识别的图形集合，可能是字形或其他图形元素 [ISO 15930-4]。
    
    **4.24**
    
    **函数(function)**
    
    一种特殊类型的对象，代表参数化的类，包括数学公式和具有任意分辨率的采样表示。
    
    **4.25**
    
    **字形(glyph)**
    
    可识别的抽象图形符号，独立于任何特定的设计 [ISO/IEC 9541-1]。
    
    **4.26**
    
    **图形状态(graphic state)**
    
    图形控制参数的堆叠栈顶，定义了图形操作符执行的当前全局框架。
    
    **4.27**
    
    **ICC 配置文件(ICC profile)**
    
    符合 ICC 规范的颜色配置文件 [ISO 15076-1:2005]。
    
    **4.28**
    
    **间接对象(indirect object)**
    
    一个对象，其标签为正整数对象编号，后跟非负整数代数编号，然后是 **obj**，并在之后有 **endobj**。

    **4.29**
    
    **整数对象(integer object)**
    
    以 0 为中心的、实现指定区间内的数学整数，并可写作一个或多个十进制数字，前面可有可无符号。
    
    **4.30**
    
    **名称对象(name object)**
    
    由一个实心斜杠 (SOLIDUS) (/), (2Fh) 引入的字符序列唯一定义的原子符号，但实心斜杠不被视为名称的一部分。
    
    **4.31**
    
    **名称树(name tree)**
    
    类似于字典，关联键和值，但名称树中的键是字符串，并且是有序的。
    
    **4.32**
    
    **空对象(null object)**
    
    表示空类型的单个对象，用关键字 **null** 表示，其类型和值与其他任何对象都不相等。
    
    **4.33**
    
    **数字树(number tree)**
    
    类似于字典，关联键和值，但数字树中的键是整数，并且是有序的。
    
    **4.34**
    
    **数值对象(numeric object)**
    
    整数对象或实数对象。
    
    **4.35**
    
    **对象(object)**
    
    构建 PDF 文件的基本数据结构，包括以下类型：数组、布尔值、字典、整数、名称、空值、实数、流和字符串。
    
    **4.36**
    
    **对象引用(object reference)**
    
    用于允许一个对象引用另一个对象的对象值；形式为 “<n> <m> R”，其中 <n> 是间接对象编号，<m> 是其版本号，R 是大写字母 R。
    
    **4.37**
    
    **对象流(object stream)**
    
    包含一系列 PDF 对象的流。
    
    **4.38**
    
    **PDF**
    
    由本规范 [ISO 32000-1] 定义的便携式文档格式文件格式。
    
    **4.39**
    
    **实数对象(real object)**
    
    近似的数学实数，但范围和精度有限，并可写作一个或多个十进制数字，前面可有可无符号，以及前导、尾随或嵌入式的句点 (2Eh)（小数点）。
    
    **4.40**
    
    **矩形(rectangle)**
    
    用于描述页面上的位置和各种对象的边界框的特定数组对象，并写成一个包含四个数字的数组，给出对角相对的两个角的坐标，通常形式为 [llx lly urx ury]，按顺序指定矩形的左下 x、左下 y、右上 x 和右上 y 坐标。
    
    **4.41**
    
    **资源字典(resource dictionary)**
    
    将内容流中使用的资源名称与资源对象本身关联起来，并按不同类别（例如，字体、颜色空间、图案）组织。
    
    **4.42**
    
    **空格字符(space character)**
    
    用于在文本字符串中表示正字法空白的文本字符串字符
    
    !!! info "NOTE 2"
    
        空格字符包括水平制表符 (U+0009)、换行符 (U+000A)、垂直制表符 (U+000B)、表单进纸符 (U+000C)、回车符 (U+000D)、空格 (U+0020)、不间断空格 (U+00A0)、EN 空格 (U+2002)、EM 空格 (U+2003)、数字空格 (U+2007)、标点符号空格 (U+2008)、瘦空格 (U+2009)、发丝空格 (U+200A)、零宽度空格 (U+200B) 和表意文字空格 (U+3000)
    
    **4.43**
    
    **流对象(stream object)**
    
    由一个字典组成，后面跟着零个或多个字节，这些字节被流和结束流这两个关键字括起来。
    
    **4.44**
    
    **字符串对象(string object)**
    
    由一系列字节组成（无符号整数值在 0 到 255 的范围内），这些字节不是整数对象，而是以更紧凑的形式存储。
    
    **4.45**
    
    **网页捕获(web capture)**
    
    指的是通过导入并可能转换基于互联网或本地的文件来创建 PDF 内容的过程。被导入的文件可能是任何任意格式，如 HTML、GIF、JPEG、文本和 PDF。
    
    **4.46**
    
    **空白字符(white-space character)**
    
    分隔 PDF 语法结构（如名称和数字）的字符；空白字符包括水平制表符 (09h)、换行符 (0Ah)、表单进纸符 (0Ch)、回车符 (0Dh)、空格 (20h)；（见 [7.2.2 节](./c7/s2.md#722-字符集)，“字符集”中的表 1）
    
    **4.47**
    
    **XFDF 文件(XFDF file)**
    
    符合 XML 表单数据格式 2.0 规范的文件，这是表单数据格式 (FDF) 的 XML 转录。
    
    **4.48**
    
    **XMP 数据包(XMP packet)**
    
    用于结构化包装序列化 XML 元数据的容器，可以嵌入到各种文件格式中。

=== "英文"

    For the purposes of this document, these terms and definitions apply.
    
    **4.1**
    
    **… (ellipsis)**
    
    An ellipsis is used within PDF examples to indicate omitted detail. Pairs of ellipses are also used to bracket comments, in italic, about such omitted detail.
    
    **4.2**
    
    **8-bit value**
    
    (see byte)
    
    **4.3**
    
    **array object**
    
    a one-dimensional collection of objects arranged sequentially and implicitly numbered starting at 0
    
    **4.4**
    
    **ASCII**
    
    the American Standard Code for Information Interchange, a widely used convention for encoding a specific set of 128 characters as binary numbers defined in ANSI X3.4-1986
    
    **4.5**
    
    **binary data**
    
    an ordered sequence of bytes
    
    **4.6**
    
    **boolean objects**
    
    either the keyword **true** or the keyword **false**
    
    **4.7**
    
    **byte**
    
    a group of 8 binary digits which collectively can be configured to represent one of 256 different values and various realizations of the 8 binary digits are widely used in today's electronic equipment
    
    **4.8**
    
    **catalog**
    
    the primary dictionary object containing references directly or indirectly to all other objects in the document with the exception that there may be objects in the **trailer** that are not referred to by the **catalog**
    
    **4.9**
    
    **character**
    
    numeric code representing an abstract symbol according to some defined character encoding rule
    
    !!! info "NOTE 1"
    
        There are three manifestations of characters in PDF, depending on context:
    
        - A PDF file is represented as a sequence of 8-bit bytes, some of which are interpreted as character codes in the ASCII character set and some of which are treated as arbitrary binary data depending upon the context.
        - The contents (data) of a string or stream object in some contexts are interpreted as character codes in the PDFDocEncoding or UTF-16 character set.
        - The contents of a string within a PDF content stream in some situations are interpreted as character codes that select glyphs to be drawn on the page according to a character encoding that is associated with the text font.
    
    **4.10**
    
    **character set**
    
    a defined set of symbols each assigned a unique character value
    
    **4.11**
    
    **conforming reader**
    
    software application that is able to read and process PDF files that have been made in conformance with this specification and that itself conforms to requirements of conforming readers specified here [ISO 32000-1]
    
    **4.12**
    
    **conforming product**
    
    software application that is both a conforming reader and a conforming writer
    
    **4.13**
    
    **conforming writer**
    
    software application that is able to write PDF files that conform to this specification [ISO 32000-1]
    
    **4.14**
    
    **content stream**
    
    stream object whose data consists of a sequence of instructions describing the graphical elements to be painted on a page
    
    **4.15**
    
    **cross reference table**
    
    data structure that contains the byte offset start for each of the indirect objects within the file
    
    **4.16**
    
    **developer**
    
    Any entity, including individuals, companies, non-profits, standards bodies, open source groups, etc., who are developing standards or software to use and extend ISO 32000-1.
    
    **4.17**
    
    **dictionary object**
    
    an associative table containing pairs of objects, the first object being a name object serving as the key and the second object serving as the value and may be any kind of object including another dictionary
    
    **4.18**
    
    **direct object**
    
    any object that has not been made into an indirect object
    
    **4.19**
    
    **electronic document**
    
    electronic representation of a page-oriented aggregation of text, image and graphic data, and metadata useful to identify, understand and render that data, that can be reproduced on paper or displayed without significant loss of its information content
    
    **4.20**
    
    **end-of-line marker (EOL marker)**
    
    one or two character sequence marking the end of a line of text, consisting of a CARRIAGE RETURN character (0Dh) or a LINE FEED character (0Ah) or a CARRIAGE RETURN followed immediately by a LINE FEED
    
    **4.21**
    
    **FDF file**
    
    File conforming to the Forms Data Format containing form data or annotations that may be imported into a PDF file (see 12.7.7, “Forms Data Format”)
    
    **4.22**
    
    **filter**
    
    an optional part of the specification of a stream object, indicating how the data in the stream should be decoded before it is used
    
    **4.23**
    
    **font**
    
    identified collection of graphics that may be glyphs or other graphic elements [ISO 15930-4]
    
    **4.24**
    
    **function**
    
    a special type of object that represents parameterized classes, including mathematical formulas and sampled representations with arbitrary resolution
    
    **4.25**
    
    **glyph**
    
    recognizable abstract graphic symbol that is independent of any specific design [ISO/IEC 9541-1]
    
    **4.26**
    
    **graphic state**
    
    the top of a push down stack of the graphics control parameters that define the current global framework within which the graphics operators execute
    
    **4.27**
    
    **ICC profile**
    
    colour profile conforming to the ICC specification [ISO 15076-1:2005]
    
    **4.28**
    
    **indirect object**
    
    an object that is labeled with a positive integer object number followed by a non-negative integer generation number followed by **obj** and having **endobj** after it
    
    **4.29**
    
    **integer object**
    
    mathematical integers with an implementation specified interval centered at 0 and written as one or more decimal digits optionally preceded by a sign
    
    **4.30**
    
    **name object**
    
    an atomic symbol uniquely defined by a sequence of characters introduced by a SOLIDUS (/), (2Fh) but the SOLIDUS is not considered to be part of the name
    
    **4.31**
    
    **name tree**
    
    similar to a dictionary that associates keys and values but the keys in a name tree are strings and are ordered
    
    **4.32**
    
    **null object**
    
    a single object of type null, denoted by the keyword **null**, and having a type and value that are unequal to those of any other object
    
    **4.33**
    
    **number tree**
    
    similar to a dictionary that associates keys and values but the keys in a number tree are integers and are ordered
    
    
    **4.34**
    
    **numeric object**
    
    either an integer object or a real object
    
    **4.35**
    
    **object**
    
    a basic data structure from which PDF files are constructed and includes these types: array, Boolean, dictionary, integer, name, null, real, stream and string
    
    **4.36**
    
    **object reference**
    
    an object value used to allow one object to refer to another; that has the form “`<n> <m> R`” where `<n>` is an indirect object number, `<m>` is its version number and R is the uppercase letter R
    
    **4.37**
    
    **object stream**
    
    a stream that contains a sequence of PDF objects
    
    **4.38**
    
    **PDF**
    
    Portable Document Format file format defined by this specification [ISO 32000-1]
    
    **4.39**
    
    **real object**
    
    approximate mathematical real numbers, but with limited range and precision and written as one or more decimal digits with an optional sign and a leading, trailing, or embedded PERIOD (2Eh) (decimal point)
    
    **4.40**
    
    **rectangle**
    
    a specific array object used to describe locations on a page and bounding boxes for a variety of objects and written as an array of four numbers giving the coordinates of a pair of diagonally opposite corners, typically in the form [ llx lly urx ury ] specifying the lower-left x, lower-left y, upper-right x, and upper-right y coordinates of the rectangle, in that order
    
    **4.41**
    
    **resource dictionary**
    
    associates resource names, used in content streams, with the resource objects themselves and organized into various categories (e.g., Font, ColorSpace, Pattern)
    
    **4.42**
    
    **space character**
    
    text string character used to represent orthographic white space in text strings
    
    !!! info "NOTE 2"
    
        space characters include HORIZONTAL TAB (U+0009), LINE FEED (U+000A), VERTICAL TAB (U+000B), FORM FEED (U+000C), CARRIAGE RETURN (U+000D), SPACE (U+0020), NOBREAK SPACE (U+00A0), EN SPACE (U+2002), EM SPACE (U+2003), FIGURE SPACE (U+2007), PUNCTUATION SPACE (U+2008), THIN SPACE (U+2009), HAIR SPACE (U+200A), ZERO WIDTH SPACE (U+200B), and IDEOGRAPHIC SPACE (U+3000)
    
    **4.43**
    
    **stream object**
    
    consists of a dictionary followed by zero or more bytes bracketed between the keywords stream and endstream
    
    **4.44**
    
    **string object**
    
    consists of a series of bytes (unsigned integer values in the range 0 to 255) and the bytes are not integer objects, but are stored in a more compact form
    
    **4.45**
    
    **web capture**
    
    refers to the process of creating PDF content by importing and possibly converting internet-based or locally-resident files. The files being imported may be any arbitrary format, such as HTML, GIF, JPEG, text, and PDF
    
    **4.46**
    
    **white-space character**
    
    characters that separate PDF syntactic constructs such as names and numbers from each other; white space characters are HORIZONTAL TAB (09h), LINE FEED (0Ah), FORM FEED (0Ch), CARRIAGE RETURN (0Dh), SPACE (20h); (see Table 1 in 7.2.2, “Character Set”)
    
    **4.47**
    
    **XFDF file**
    
    file conforming to the XML Forms Data Format 2.0 specification, which is an XML transliteration of Forms Data Format (FDF)
    
    **4.48**
    
    **XMP packet**
    
    structured wrapper for serialized XML metadata that can be embedded in a wide variety of file formats