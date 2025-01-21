# 前言

**Introduction**

=== "中文"

    ISO 32000 规定了一种称为便携式文档格式（Portable Document Format，通常简称为 PDF）的文档数字表示形式。PDF 是由 Adobe Systems Incorporated 开发并规范的，始于 1993 年，并一直持续到 2007 年，当时制定了这一 ISO 标准。Adobe Systems 版本的 PDF 1.7 是此 ISO 32000 版的基准。PDF 的规范是向后兼容的，意味着 PDF 1.7 包含了 Adobe PDF 规范中 1.0 至 1.6 版本之前所有文档化的功能。应当注意，Adobe 从他们的标准中移除了某些 PDF 特性，这些特性在此也不包含。

    PDF 的目标是使用户能够轻松可靠地交换和查看电子文档，而不受它们创建或查看打印的环境的影响。PDF 核心是一个高级成像模型，源自 PostScript® 页面描述语言。这个 PDF 成像模型能够以设备无关和分辨率无关的方式描述文本和图形。为了提高交互式查看的性能，PDF 定义了一个比大多数 PostScript 语言程序使用的格式更加结构化的格式。与 PostScript 不同，PostScript 是一种编程语言，PDF 基于一个为交互式查看优化的有结构的二进制文件格式。PDF 还包括一些对象，如注释和超链接，它们不是页面内容本身的一部分，但对于交互式查看和文档交换很有用。
    
    PDF 文件可以以 PDF 形式本地创建，从其他电子格式转换，或从纸张、缩微胶片或其他硬拷贝格式数字化。全球的企业、政府、图书馆、档案馆以及其他机构和个人使用 PDF 来表示大量重要信息。
    
    在过去的十四年中，得益于互联网的爆炸性增长，PDF 已成为电子文档交换的广泛使用格式。PDF 的几种特定应用已经发展起来，在这些应用中，限制 PDF 的某些特性的使用并要求使用其他特性，增强了 PDF 的有用性。ISO 32000 是完整功能 PDF 的 ISO 标准；以下标准是更专业用途的标准。PDF/X（ISO 15930）现在是传统印刷应用中电子预印系统中印刷材料中间表示形式的行业标准。PDF/A（ISO 19005）现在是数字文档归档的行业标准。PDF/E（ISO 24517）为表示工程文档和交换工程数据提供了一种机制。随着主要公司、政府机构和教育机构通过用电子信息交换取代基于纸张的工作流程来简化其运营，PDF 应用的影响和机会将以快速的步伐继续增长。
    
    PDF 以及用于以多种方式创建、查看、打印和处理 PDF 文件的软件，满足了包括以下在内的电子文档的一组要求：
    
    - 无论设备、平台和软件如何，都能保持文档保真度，
    - 将来自不同来源的内容—网站、文字处理和电子表格程序、扫描文档、照片和图形—合并到一个自包含的文档中，同时保持所有原始源文档的完整性，
    - 从多个位置或平台协作编辑文档，
    - 数字签名以证明真实性，
    - 安全和权限，允许创建者保留对文档及其相关权利的控制，
    - 为残疾人提供内容的可访问性，
    - 提取和重用内容，用于其他文件格式和应用程序，
    - 电子表格收集数据并将其与业务系统集成。
    
    国际标准化组织提请注意，声称遵守本文件可能涉及使用有关创建、修改、显示和处理 PDF 文件的专利，这些专利由以下各方拥有：
    
    - Adobe Systems Incorporated，345 Park Avenue, San Jose, California, 95110-2704, USA
    
    ISO 对这些专利权利的证据、有效性和范围不持立场。
    
    这些专利权利的持有者已向 ISO 保证，他们愿意在合理和非歧视性的条款和条件下与全世界的申请者谈判许可。在这方面，这些专利权利持有者的声明已在 ISO 注册。可以从上述列出的各方获取信息。
    
    请注意，本文件的一些要素可能是除了上述已识别的专利权利之外的其他专利权利的主题。ISO 不对识别任何或所有此类专利权利负责。
    
    AIIM（<http://www.aiim.org/pdfrefdocs>）已建立了一个参考文档库。并非所有参考文档都可以在那里找到，因为存在版权限制。
    

=== "英文"

    ISO 32000 specifies a digital form for representing documents called the Portable Document Format or usually referred to as PDF. PDF was developed and specified by Adobe Systems Incorporated beginning in 1993 and continuing until 2007 when this ISO standard was prepared. The Adobe Systems version PDF 1.7 is the basis for this ISO 32000 edition. The specifications for PDF are backward inclusive, meaning that PDF 1.7 includes all of the functionality previously documented in the Adobe PDF Specifications for versions 1.0 through 1.6. It should be noted that where Adobe removed certain features of PDF from their standard, they too are not contained herein.

    The goal of PDF is to enable users to exchange and view electronic documents easily and reliably, independent of the environment in which they were created or the environment in which they are viewed or printed. At the core of PDF is an advanced imaging model derived from the PostScript® page description language. This PDF Imaging Model enables the description of text and graphics in a device-independent and resolution-independent manner. To improve performance for interactive viewing, PDF defines a more structured format than that used by most PostScript language programs. Unlike Postscript, which is a programming language, PDF is based on a structured binary file format that is optimized for high performance in interactive viewing. PDF also includes objects, such as annotations and hypertext links, that are not part of the page content itself but are useful for interactive viewing and document interchange.
    
    PDF files may be created natively in PDF form, converted from other electronic formats or digitized from paper, microform, or other hard copy format. Businesses, governments, libraries, archives and other institutions and individuals around the world use PDF to represent considerable bodies of important information.
    
    Over the past fourteen years, aided by the explosive growth of the Internet, PDF has become widely used for the electronic exchange of documents. There are several specific applications of PDF that have evolved where limiting the use of some features of PDF and requiring the use of others, enhances the usefulness of PDF. ISO 32000 is an ISO standard for the full function PDF; the following standards are for more specialized uses. PDF/ X (ISO 15930) is now the industry standard for the intermediate representation of printed material in electronic prepress systems for conventional printing applications. PDF/A (ISO 19005) is now the industry standard for the archiving of digital documents. PDF/E (ISO 24517) provides a mechanism for representing engineering documents and exchange of engineering data. As major corporations, government agencies, and educational institutions streamline their operations by replacing paper-based workflow with electronic exchange of information, the impact and opportunity for the application of PDF will continue to grow at a rapid pace.
    
    PDF, together with software for creating, viewing, printing and processing PDF files in a variety of ways, fulfils a set of requirements for electronic documents including:
    
    - preservation of document fidelity independent of the device, platform, and software,
    - merging of content from diverse sources—Web sites, word processing and spreadsheet programs, scanned documents, photos, and graphics—into one self-contained document while maintaining the integrity of all original source documents,
    - collaborative editing of documents from multiple locations or platforms,
    - digital signatures to certify authenticity,
    - security and permissions to allow the creator to retain control of the document and associated rights,
    - accessibility of content to those with disabilities,
    - extraction and reuse of content for use with other file formats and applications, and
    - electronic forms to gather data and integrate it with business systems.
    
    The International Organization for Standardization draws attention to the fact that it is claimed that compliance with this document may involve the use of patents concerning the creation, modification, display and processing of PDF files which are owned by the following parties:
    
    - Adobe Systems Incorporated, 345 Park Avenue, San Jose, California,95110-2704, USA
    
    ISO takes no position concerning the evidence, validity and scope of these patent rights.
    
    The holders of these patent rights has assured the ISO that they are willing to negotiate licenses under reasonable and non-discriminatory terms and conditions with applicants throughout the world. In this respect, the statements of the holders of these patent rights are registered with ISO. Information may be obtained from those parties listed above.
    
    Attention is drawn to the possibility that some of the elements of this document may be the subject of patent rights other than those identified above. ISO shall not be held responsible for identifying any or all such patent rights.
    
    A repository of referenced documents has been established by AIIM (<http://www.aiim.org/pdfrefdocs>). Not all referenced documents can be found there because of copyright restrictions.