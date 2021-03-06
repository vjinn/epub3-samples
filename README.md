# EPUB 3 Samples

This repository contains the source for a variety of EPUB 3.0 sample documents. The collection is intended to showcase features of the EPUB 3 standard, and to provide testing materials for Reading System developers.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Samples List](#samples-list)
- [Feature Matrix](#feature-matrix)
 - [Package](#package)
 - [Content Documents](#content-documents)
   - [XHTML](#xhtml)
   - [SVG](#svg)
   - [Scripted Content Documents](#scripted-content-documents)
 - [Navigation Document](#navigation-document)
 - [Global Language Support](#global-language-support)
   - [Languages/Scripts/Unicode](#languagesscriptsunicode)
   - [Content Documents](#content-documents-1)
   - [CSS](#css)
 - [Styling and Layout](#styling-and-layout)
   - [Alternate Stylesheets](#alternate-stylesheets)
   - [Fonts](#fonts)
   - [Media Queries](#media-queries)
   - [CSS Multi-column layout](#css-multi-column-layout)
   - [CSS Namespaces](#css-namespaces)
 - [Media Overlays](#media-overlays)
 - [TTS](#tts)
 - [Linking](#linking)
 - [Extensions](#extensions)
   - [Fixed Layout](#fixed-layout)
   - [Dictionaries and Glossaries](#dictionaries-and-glossaries)
 - [Indexes](#indexes)
   - [OCF Multiple Renditions](#ocf-multiple-renditions)
- [Want to contribute?](#want-to-contribute)
 - [Reporting Issues](#reporting-issues)
 - [Contributing new samples](#contributing-new-samples)
 - [Contributing variations / improvements to existing samples](#contributing-variations--improvements-to-existing-samples)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Samples List

<p>The EPUB 3 samples are also available for individual download from <a
href="https://drive.google.com/open?id=0B9g8D2Y-6aPLflIyZE50Um50cG5BNkZSQ2NqcVhtUlZJSGRoVWhla3ktZ2JQdDJjdFNyZlk"
>Google Drive</a>.</p>
<p>
<i>Unless otherwise specified, all samples listed here are licensed under <a
href="http://creativecommons.org/licenses/by-sa/3.0/">CC-BY-SA 3.0</a></i>
</p>
<table>
<tr>
<th class="s1">Publication</th>
<th class="s2">Description</th>
<th class="s3">Updated</th>
<th class="s4">Download</th>
<th class="s5">Source</th>
</tr>
<tr>
<th id="accessible-epub3">Accessible EPUB 3</th>
<td>Strategies for creating EPUB 3 content that can be read by people with different
preferred reading modalities.</td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLRmFKRTNIam93RTQ"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/accessible_epub_3/EPUB"
>Browse</a>
</td>
</tr>
<tr>
<th id="childrens-literature">Children's Literature</th>
<td> This sample section from Children's Literature includes span-element headings in the
navigation document toc and also includes the table of contents in the spine with
styling and hidden page list. </td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLaHlLWlF0b3VaSEk"
>EPUB 3.0</a>
</td>
<td>
<a
href="https://github.com/IDPF/epub3-samples/tree/master/30/childrens-literature/EPUB"
>Browse</a>
</td>
</tr>
<tr>
<th id="cc-shared-culture">Creative Commons Shared Culture</th>
<td>The video, audio and text from <a
href="http://creativecommons.org/videos/a-shared-culture">Creative Commons A
Shared Culture</a> in EPUB form; each spine item containing a variation of
<code>&lt;video&gt;</code>/<code>&lt;audio&gt;</code> embedding. See <a
href="http://epub-samples.googlecode.com/svn/trunk/30/cc-shared-culture/EPUB/xhtml/toc.xhtml"
>the Navigation Document (toc.xhtml)</a> for details. <p>Licensing: <a
href="http://creativecommons.org/licenses/by-nc-sa/3.0/us/"
>CC-BY-NC-SA</a></p>
</td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLU2tfalh5NUFLS0E"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/cc-shared-culture/EPUB"
>Browse</a>
</td>
</tr>
<tr>
<th id="epub30-spec">EPUB 3.0 Specification</th>
<td> The <a href="http://idpf.org/epub/30">EPUB 3.0 specifications</a> in EPUB 3.0 format. </td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLR2VjY1JtOVVtaUU"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/epub30-spec/EPUB"
>Browse</a>
</td>
</tr>
<tr>
<th id="figure-gallery">Figure Gallery</th>
<td> A <a href="http://idpf.org/epub/30/spec/epub30-publications.html#sec-bindings-elem"
>bindings</a>-based "object rotator". This particular sample represents an image gallery 
with caption fields. (The data model is based on
the <a href="http://www.w3.org/TR/html5/grouping-content.html#the-figure-element"
>HTML5 figure element</a>, and is thus intended to be used with any type of
content that can be represented using <code>&lt;figure&gt;</code>.) <p>Implementations
that do not support <a
href="http://idpf.org/epub/30/spec/epub30-publications.html#sec-bindings-elem"
>bindings</a> will fallback to display all figures simultaneously.</p>
</td>
<td>2015-03-08</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLUXFTcXpNMTF2b2s"
>EPUB 3.0</a>
</td>
<td>
<a
href="https://github.com/IDPF/epub3-samples/tree/master/30/figure-gallery-bindings/EPUB"
>Browse</a>
</td>
</tr>
<tr>
<th id="georgia">Georgia</th>
<td> This sample entry from the Encyclopedia Britannica includes a PLS lexicon file and
embedded SSML pronunciations showing how the two technologies can be used together to
improve TTS rendering. <p>This sample also includes a page-list nav.</p>
</td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLXy03X0JITThBMjQ"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/georgia-pls-ssml/EPUB"
>Browse</a>
</td>
</tr>
<tr>
<th id="georgia-cfi"><span class="invisible">Georgia with EPUB Canonical Fragment
Identifiers</span></th>
<td> Like <a href="#georgia">the base version</a>, but uses <a
href="http://idpf.org/epub/linking/cfi/epub-cfi.html">EPUB Canonical Fragment
Identifiers (CFI)</a> in the Navigation Document page-list. <p>This sample
demonstrates how CFI can be used to identify positions in a target document
without having to modify the target document structure. Note that the identified
page boundary positions in this document are otherwise identical to those in <a
href="#georgia">the base version</a>.</p>
</td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLTWZwNmlXRDd4TTA"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/georgia-cfi/EPUB"
>Browse</a>
</td>
</tr>
<tr>
<th id="haruko">Haruko</th>
<td> Japanese manga. Each page is represented by an HTML document having a single image
and nothing else. </td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLdmU4S2VJVUxpcjg"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/haruko-html-jpeg/OPS"
>Browse</a>
</td>
</tr>
<tr>
<th id="haruko-jpeg"><span class="invisible">Haruko with JPEGs in spine</span></th>
<td> Japanese manga. Each page is represented by a single image, which has a fallback
HTML. </td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLM1hLd29CQmxZYU0"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/haruko-jpeg/OPS"
>Browse</a>
</td>
</tr>
<tr>
<th id="hefty-water">Hefty Water</th>
<td> This sample contains one instance of the epub:switch element, along with inline
instructions for how to determine whether a Reading System supports epub:switch. There
is also a little bit of ruby markup available, used to render captions under/over
chemical formula segments. </td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLM3oyLTB3eDZzWWc"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/hefty-water/EPUB"
>Browse</a>
</td>
</tr>
<tr>
<th id="internallinks">Internal Links</th>
<td>Test document for internal linking.</td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLVXE5dE9mcFZoTTQ"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/internallinks/OEBPS"
>Browse</a>
</td>
</tr>
<tr>
<th id="israelsailing">Israel Sailing</th>
<td>BIDI, page-progression-direction, rtl, and Hebrew text. </td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLYi00Ym0yd3Z6c3M"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/israelsailing"
>Browse</a>
</td>
</tr>
<tr>
<th id="kusamakura">Kusamakura</th>
<td>A Japanese Novel <a href="http://en.wikipedia.org/wiki/Kusamakura_(novel)"
>Kusamakura</a>
<a href="http://ja.wikipedia.org/wiki/%E8%8D%89%E6%9E%95">草枕</a> by <a
href="http://en.wikipedia.org/wiki/Natsume_S%C5%8Dseki">Natsume Sōseki</a> 夏目漱石.
This EPUB publication has features as below: <ul>
<li>Vertical Writing</li>
<li>Ruby</li>
<li>Media overlay</li>
<li>Non-ASCII file names and Internationalized Resource Identifiers</li>
<li>Emphasis Dots</li>
<li>Embedded OpenType<a href="/p/epub-samples/w/edit/OpenType">?</a> font for
U+2014</li>
<li>EPUB3 metadata including phonetics</li>
<li>XMP metadata</li>
</ul>
</td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLbDhfMUVKYk8yVWc"
>EPUB 3.0</a>
</td>
<td>
<a
href="https://github.com/IDPF/epub3-samples/tree/master/30/kusamakura-japanese-vertical-writing/OPS"
>Browse</a>
</td>
</tr>
<tr>
<th id="linear-algebra">Linear Algebra</th>
<td>A First Course in Linear Algebra, available in its canonical version at <a
href="http://linear.ups.edu">http://linear.ups.edu</a>. This sample contains
substantive amounts of <a href="http://www.w3.org/TR/MathML3/MathML">MathML</a>.
<p>Licensing: <a href="http://www.gnu.org/copyleft/fdl.html">GNU FDL 1.2</a></p>
</td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLbDhfMUVKYk8yVWc"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/linear-algebra/EPUB"
>Browse</a>
</td>
</tr>
<tr>
<th id="mahabharata">Mahabharata</th>
<td> The <a href="http://en.wikipedia.org/wiki/Mahabharata">Mahabharata</a> in Devanāgarī
(देवनागरी). Note that this sample does not include embedded fonts, and can thus be
used to test Reading System native support for Devanāgarī font/glyph rendering. </td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLR24ta3ZuNEZfMFE"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/mahabharata/EPUB"
>Browse</a>
</td>
</tr>
<tr>
<th id="moby-dick">Moby Dick</th>
<td> Herman Melville's <i>Moby-Dick </i> with, as opposed to <a href="#wasteland"
>wasteland</a>, one spine item per chapter. Includes embedded fonts (OpenType).
Uses the <a
href="http://idpf.org/epub/30/spec/epub30-contentdocs.html#sec-xhtml-content-type-attribute"
>epub:type</a> attribute. </td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLbjVrbHJqMEhZM0k"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/moby-dick/EPUB"
>Browse</a>
</td>
</tr>
<tr>
<th id="moby-dick-mo"><span class="invisible">Moby Dick with Media Overlays</span></th>
<td> Like <a href="#moby-dick">the base version</a>, but includes <a
href="http://idpf.org/epub/30/spec/epub30-mediaoverlays.html">Media Overlays</a>
for the first two chapters. </td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLWXZsaXBsd2hoRnM"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/moby-dick-mo/OPS"
>Browse</a>
</td>
</tr>
<tr>
<th id="page-blanche">Page Blanche</th>
<td>An extract of a <a href="http://www.idpf.org/epub/fxl/">fixed layout document</a>,
using XHTML spine items that embed bitmaps. This sample has both the
<code>rendition:orientation</code> and the <code>rendition:spread</code>
properties set to 'auto'. </td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLMmpCYktzbkJlQ1E"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/page-blanche/EPUB"
>Browse</a>
</td>
</tr>
<tr>
<th id="page-blanche-jpeg"><span class="invisible">Page Blanche with JPEGs in
spine</span></th>
<td> Much like the <a href="#page-blanche">base version</a>, but instead of JPEG embedded
in XHTML spine items, this variant uses JPEG spine items. </td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLeTZfNlNlRDFHSTQ"
>EPUB 3.0</a>
</td>
<td>
<a
href="https://github.com/IDPF/epub3-samples/tree/master/30/page-blanche-bitmaps-in-spine/EPUB"
>Browse</a>
</td>
</tr>
<tr>
<th id="quiz">Quiz</th>
<td> A <a href="http://idpf.org/epub/30/spec/epub30-publications.html#sec-bindings-elem"
>bindings</a>-based "quiz". This particular sample represents a multiple-choice quiz 
with a self-checking feature. Allows for
three types of quizzes: all questions at once, one question at a time, and one
question at a time with immediate feedback ("flashcard" mode). Implementations that do
not support <a
href="http://idpf.org/epub/30/spec/epub30-publications.html#sec-bindings-elem"
>bindings</a> will fallback to display all questions and possible answers as a
static list. </td>
<td>2015-03-09</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLYXlBSGR6bV9fX00"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/quiz-bindings/EPUB"
>Browse</a>
</td>
</tr>
<tr>
<th id="regime-anticancer-arabic">Regime Anti-Cancer Arabic</th>
<td> Arabic content. Note that this sample does not include embedded fonts, and can thus
be used to test Reading System native support for arabic font/glyph rendering. </td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLUUkxa2VYbURqVjA"
>EPUB 3.0</a>
</td>
<td>
<a
href="https://github.com/IDPF/epub3-samples/tree/master/30/regime-anticancer-arabic/EPUB"
>Browse</a>
</td>
</tr>
<tr>
<th id="jlreq">Requirements for Japanese Text Layout</th>
<td> EPUB version of <a href="http://www.w3.org/TR/2012/NOTE-jlreq-20120403/ja/"
>Requirements for Japanese Text Layout (W3C Note) in Japanese</a>
</td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLVTM1ajNGZjRsZFk"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/jlreq-in-japanese"
>Browse</a>
</td>
</tr>
<tr>
<th id="jlreq-in-english"><span class="invisible">Requirements for Japanese Text Layout
(English)</span></th>
<td> EPUB version of <a href="http://www.w3.org/TR/2012/NOTE-jlreq-20120403/">Requirements
for Japanese Text Layout (W3C Note) in English</a>
</td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLR2hXWGxtWHliRjg"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/jlreq-in-english"
>Browse</a>
</td>
</tr>
<tr>
<th id="sous-le-vent">Sous le vent</th>
<td> An extract of a <a href="http://www.idpf.org/epub/fxl/">fixed layout document</a>,
using SVG embedded in XHTML spine items. This sample has the
<code>rendition:orientation</code> property set to 'portrait', and the
<code>rendition:spread</code> property set to 'none'. </td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLZUh2VFRhZ21NU1k"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/sous-le-vent/EPUB"
>Browse</a>
</td>
</tr>
<tr>
<th id="sous-le-vent-svg"><span class="invisible">Sous le Vent with SVG in
spine</span></th>
<td> Much like the <a href="#sous-le-vent">base version</a>, but instead of SVG embedded
in XHTML spine items, this variant uses SVG spine items. </td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLdGsyZEtxaHlNSEE"
>EPUB 3.0</a>
</td>
<td>
<a
href="https://github.com/IDPF/epub3-samples/tree/master/30/sous-le-vent_svg-in-spine/EPUB"
>Browse</a>
</td>
</tr>
<tr>
<th id="svg-in-spine">SVG-in-spine</th>
<td> An extract of a <a href="http://www.idpf.org/epub/fxl/">fixed layout document</a>,
using SVG spine items. This sample uses spine itemref <code>page-spread-*</code>
properties in a way that impacts default spread population behavior for the first two
pages. </td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLSF9rTjlUWjNYQkU"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/svg-in-spine/OPS"
>Browse</a>
</td>
</tr>
<tr>
<th id="the-swans">The Swans</th>
<td> This sample contains CSS Media Queries with adaptions for device screen size and
orientation. <p>By virtue of the included Package Document metadata, this sample can
also be used to test how Reading Systems handles multiple DC elements of the same
kind, and whether it recognizes MARC relator codes (the sample includes multiple
dc:creator elements, annotated with MARC illustrator and author roles).</p>
</td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLWWtqeDNxU3h2N2M"
>EPUB 3.0</a>
</td>
<td>
<a
href="https://github.com/IDPF/epub3-samples/tree/master/30/childrens-media-query/EPUB"
>Browse</a>
</td>
</tr>
<tr>
<th id="the-voyage-of-life">The Voyage of Life</th>
<td> A mixed reflowable and <a href="http://www.idpf.org/epub/fxl/">fixed layout</a>
document. This sample can be used to test Reading System support for item-level
changes to fixed layout meta properties. </td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLWXp5SEgxY0pDeEE"
>EPUB 3.0</a>
</td>
<td>
<a
href="https://github.com/IDPF/epub3-samples/tree/master/30/cole-voyage-of-life/EPUB"
>Browse</a>
</td>
</tr>
<tr>
<th id="the-voyage-of-life-tol"><span class="invisible">The Voyage of Life with textual
overlays</span></th>
<td> Much like the <a href="#the-voyage-of-life">base version</a>, but instead of
interspersed reflowable/fixed pages, this variant contains an experimental "textual
overlay" for each painting (click or tap on the painting surface to toggle the
visibility of the text). <p>While the implementation of the toggling in this sample is
not very slick, the main purpose is to show how rich text can be supplied with
otherwise image-centric content without negative impact on the visual
experience.</p>
</td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLNHM1R1RMcTIwMDQ"
>EPUB 3.0</a>
</td>
<td>
<a
href="https://github.com/IDPF/epub3-samples/tree/master/30/cole-voyage-of-life-tol/EPUB"
>Browse</a>
</td>
</tr>
<tr>
<th id="wasteland">The Waste Land</th>
<td> A basic recast of T.S. Eliot's <i>The Waste Land</i> in a single XHTML document,
using <code>&lt;</code>section<code>&gt;</code> elements and the <a
href="http://idpf.org/epub/30/spec/epub30-contentdocs.html#sec-xhtml-content-type-attribute"
>epub:type</a> attribute to mark a live linked note apparatus and other structural
components. Contains day and night <a href="http://idpf.org/epub/altss-tags/"
>alternate style sheets</a>. <p>For EPUB 2.0 Reading System compatibility
purposes, a 2.01 NCX and the <a
href="http://blog.threepress.org/2009/11/20/best-practices-in-epub-cover-images/"
>EPUB 2 cover meta element</a> is included.</p>
</td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLemZ6a3B1b1pvZE0"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/wasteland/EPUB"
>Browse</a>
</td>
</tr>
<tr>
<th id="wasteland-otf"><span class="invisible">The Waste Land with OTF fonts</span></th>
<td> Like <a href="#wasteland">the base version</a>, but uses serif OTF embedded fonts.
The fallback is a sans-serif system font. </td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLQjlaZ2JMRl9HaWM"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/wasteland-otf/EPUB"
>Browse</a>
</td>
</tr>
<tr>
<th id="wasteland-otf-obf"><span class="invisible">The Waste Land with encrypted OTF
fonts</span></th>
<td> Like <a href="#wasteland">the base version</a>, but uses serif OTF embedded fonts
encrypted using the <a
href="http://idpf.org/epub/30/spec/epub30-ocf.html#font-obfuscation">OCF 3.0 font
obfuscation algorithm</a>. The fallback is a sans-serif system font. </td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLZV9xdlVLWURqd2s"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/wasteland-otf-obf/EPUB"
>Browse</a>
</td>
</tr>
<tr>
<th id="wasteland-woff"><span class="invisible">The Waste Land with WOFF fonts</span></th>
<td> Like <a href="#wasteland">the base version</a>, but uses serif WOFF embedded fonts.
The fallback is a sans-serif system font. </td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLZ0s0cjFaZHJOYms"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/wasteland-woff/EPUB"
>Browse</a>
</td>
</tr>
<tr>
<th id="wasteland-woff-obf"><span class="invisible">The Waste Land with WOFF encrypted
fonts</span></th>
<td> Like <a href="#wasteland">the base version</a>, but uses serif WOFF embedded fonts
encrypted using the <a
href="http://idpf.org/epub/30/spec/epub30-ocf.html#font-obfuscation">OCF 3.0 font
obfuscation algorithm</a>. The fallback is a sans-serif system font. </td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLZ0s0cjFaZHJOYms"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/wasteland-woff-obf/EPUB"
>Browse</a>
</td>
</tr>
<tr>
<th id="trees">Trees</th>
<td> This sample contains the HTML5 canvas element used to draw decorational trees on page
load. If your reading system does not support canvas, the text "Your Reading System
does not support canvas" will be shown instead. <p>Following the title (first) page,
this sample also contains two spine items that are styled using CSS multi-column
layout. If your reading system supports multi-column layout, then the pages will
be rendered in two columns.</p>
</td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLS0R6dl84eTBLSEU"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/trees/EPUB">B\rowse</a>
</td>
</tr>
<tr>
<th id="mymedia-lite">Vertical Writing</th>
<td>Vertical writing, page-progression-direction rtl, and alternate stylesheets for
vertical/horizontal writing. </td>
<td>2015-02-16</td>
<td>
<a
href="https://drive.google.com/uc?export=download&amp;id=0B9g8D2Y-6aPLSG5FamctMXpqX28"
>EPUB 3.0</a>
</td>
<td>
<a href="https://github.com/IDPF/epub3-samples/tree/master/30/mymedia_lite">Browse</a>
</td>
</tr>
</table>

Packaged versions of the samples are also available for direct download from Google Drive[https://drive.google.com/open?id=0B9g8D2Y-6aPLflIyZE50Um50cG5BNkZSQ2NqcVhtUlZJSGRoVWhla3ktZ2JQdDJjdFNyZlk].

<h2>Feature Matrix</h2>
<h3 id="Package">Package</h3>
<table>
<tbody>
<tr>
<th class="m1"> Feature </th>
<th class="m2"> Details </th>
<th class="m3"> Samples </th>
</tr>
<tr>
<th> Cover Image </th>
<td>Using bitmap format</td>
<td><a href="#wasteland">The Waste Land</a>, <a href="#epub30-spec">EPUB 3.0
Specification</a>, <a href="#kusamakura">Kusamakura</a></td>
</tr>
<tr>
<th>&#160;</th>
<td>Using SVG format</td>
<td>
<a href="#svg-in-spine">SVG-in-spine</a>
</td>
</tr>
<tr>
<th> Bindings </th>
<td>&#160;</td>
<td><a href="#figure-gallery">Figure Gallery</a>, <a href="#quiz">Quiz</a></td>
</tr>
<tr>
<th> DCMES </th>
<td>Multiple <code>dc:creator</code> elements</td>
<td><a href="#the-swans">The Swans</a>, <a href="#regime-anticancer-arabic">Regime
Anti-cancer Arabic</a></td>
</tr>
<tr>
<th> alternate-script property </th>
<td>&#160;</td>
<td><a href="#regime-anticancer-arabic">Regime Anti-cancer Arabic</a>, <a
href="#kusamakura">Kusamakura</a></td>
</tr>
<tr>
<th> display-seq property </th>
<td>&#160;</td>
<td>
<a href="#regime-anticancer-arabic">Regime Anti-cancer Arabic</a>
</td>
</tr>
<tr>
<th> role property </th>
<td>MARC <code>aut</code> and <code>ill</code> roles</td>
<td><a href="#the-swans">The Swans</a>, <a href="#kusamakura">Kusamakura</a></td>
</tr>
<tr>
<th> page-progression-direction attribute </th>
<td>rtl (right to left)</td>
<td><a href="#regime-anticancer-arabic">Regime Anti-cancer Arabic</a>, <a
href="#kusamakura">Kusamakura</a>,<a href="#haruko">Haruko</a>,<a
href="#haruko-jpeg">Haruko (with JPEGs in spine)</a>, <a href="#mymedia-lite"
>Vertical Writing</a></td>
</tr>
</tbody>
</table>
<h3 id="Content_Documents">Content Documents</h3>
<h4 id="XHTML">XHTML</h4>
<table>
<tbody>
<tr>
<th class="m1"> Feature </th>
<th class="m2"> Details </th>
<th class="m3"> Samples </th>
</tr>
<tr>
<th> epub:type attribute </th>
<td>&#160;</td>
<td><a href="#wasteland">The Waste Land</a>, <a href="#kusamakura">Kusamakura</a></td>
</tr>
<tr>
<th> epub:switch element </th>
<td>&#160;</td>
<td>
<a href="#hefty-water">Hefty Water</a>
</td>
</tr>
<tr>
<th> epub:trigger element </th>
<td>&#160;</td>
<td>
<a href="#cc-shared-culture">Shared Culture</a>
</td>
</tr>
<tr>
<th> html5 video element </th>
<td>Using h.264 codec</td>
<td>
<a href="#cc-shared-culture">Shared Culture</a>
</td>
</tr>
<tr>
<th>&#160;</th>
<td>Using WebM codec</td>
<td>
<a href="#cc-shared-culture">Shared Culture</a>
</td>
</tr>
<tr>
<th> html5 audio element </th>
<td>Using mp3 codec</td>
<td>
<a href="#cc-shared-culture">Shared Culture</a>
</td>
</tr>
<tr>
<th> html5 ruby element </th>
<td>&#160;</td>
<td><a href="#kusamakura">Kusamakura</a>, <a href="#hefty-water">Hefty Water</a></td>
</tr>
<tr>
<th> html5 canvas element </th>
<td>&#160;</td>
<td>
<a href="#trees">Trees</a>
</td>
</tr>
<tr>
<th> MathML </th>
<td>&#160;</td>
<td>
<a href="#linear-algebra">Linear Algebra</a>
</td>
</tr>
<tr>
<th> html5 non-ascii-identifiers </th>
<td>&#160;</td>
<td>
<a href="#internallinks">Internal Links</a>
</td>
</tr>
</tbody>
</table>
<h4 id="SVG">SVG</h4>
<table>
<tbody>
<tr>
<th class="m1"> Feature </th>
<th class="m2"> Details </th>
<th class="m3"> Samples </th>
</tr>
<tr>
<th> embedded in XHTML </th>
<td>&#160;</td>
<td>
<a href="#sous-le-vent">Sous le Vent</a>
</td>
</tr>
<tr>
<th> spine-level </th>
<td>&#160;</td>
<td><a href="#svg-in-spine">SVG-in-spine</a>, <a href="#sous-le-vent-svg">Sous le Vent
(with SVG in spine)</a></td>
</tr>
</tbody>
</table>
<h4 id="Scripted_Content_Documents">Scripted Content Documents</h4>
<table>
<tbody>
<tr>
<th class="m1"> Feature </th>
<th class="m2"> Details </th>
<th class="m3"> Samples </th>
</tr>
<tr>
<th> Container-constrained </th>
<td>&#160;</td>
<td><a href="#figure-gallery">Figure Gallery</a>, <a href="#quiz">Quiz</a></td>
</tr>
<tr>
<th> Spine-level </th>
<td>&#160;</td>
<td><a href="#cc-shared-culture">Shared Culture</a>, <a href="#the-voyage-of-life-tol"
>The Voyage of Life (with text overlays)</a></td>
</tr>
<tr>
<th> Using aria attributes </th>
<td>&#160;</td>
<td><a href="#cc-shared-culture">Shared Culture</a>, <a href="#the-voyage-of-life-tol"
>The Voyage of Life (with text overlays)</a></td>
</tr>
<tr>
<th> epubReadingSystem queries </th>
<td>&#160;</td>
<td><a href="#cc-shared-culture">Shared Culture</a>, <a href="#the-voyage-of-life-tol"
>The Voyage of Life (with text overlays)</a></td>
</tr>
</tbody>
</table>
<h3 id="Navigation_Document">Navigation Document</h3>
<table>
<tbody>
<tr>
<th class="m1"> Feature </th>
<th class="m2"> Details </th>
<th class="m3"> Samples </th>
</tr>
<tr>
<th> In-spine </th>
<td>&#160;</td>
<td><a href="#cc-shared-culture">Shared Culture</a>, <a href="#kusamakura"
>Kusamakura</a>, <a href="#haruko">Haruko</a>, <a href="#haruko-jpeg">Haruko
(with JPEGs in spine)</a>, <a href="#jlreq">Japanese Language
Requirements</a>, <a href="#jlreq-in-english">Japanese Language Requirements
(English)</a>, <a href="#childrens-literature">Children's Literature</a></td>
</tr>
<tr>
<th> Out-of-spine </th>
<td>&#160;</td>
<td>
<a href="#wasteland">The Waste Land</a>
</td>
</tr>
<tr>
<th> page-list </th>
<td>&#160;</td>
<td><a href="#georgia">Georgia</a>, <a href="#childrens-literature">Children's
Literature</a></td>
</tr>
<tr>
<th> landmarks </th>
<td>&#160;</td>
<td>
<a href="#wasteland">The Waste Land</a>
</td>
</tr>
<tr>
<th> NCX fallback </th>
<td>&#160;</td>
<td><a href="#wasteland">The Waste Land</a>, <a href="#the-swans"
>childrens-media-query</a>, <a href="#kusamakura">Kusamakura</a>, <a
href="#jlreq">Japanese Language Requirements</a>, <a href="#jlreq-in-english"
>Japanese Language Requirements (English)</a></td>
</tr>
<tr>
<th> @hidden </th>
<td>&#160;</td>
<td><a href="#epub30-spec">epub30-spec</a>, <a href="#mahabharata">Mahabharata</a>, <a
href="#childrens-literature">Children's Literature</a></td>
</tr>
<tr>
<th> span headings </th>
<td>&#160;</td>
<td>
<a href="#childrens-literature">Children's Literature</a>
</td>
</tr>
</tbody>
</table>
<h3 id="Global_Language_Support">Global Language Support</h3>
<h4 id="Languages_Scripts_Unicode">Languages/Scripts/Unicode</h4>
<table>
<tbody>
<tr>
<th class="m1"> Feature </th>
<th class="m2"> Details </th>
<th class="m3"> Samples </th>
</tr>
<tr>
<th> Devanāgarī (देवनागरी) </th>
<td>&#160;</td>
<td>
<a href="#mahabharata">Mahabharata</a>
</td>
</tr>
<tr>
<th> arabic (العربية) </th>
<td>writing from right to left</td>
<td>
<a href="#regime-anticancer-arabic">Regime Anti-cancer Arabic</a>
</td>
</tr>
<tr>
<th> Japanese(日本語) </th>
<td>Vertical writing, right-to-left page progression direction</td>
<td><a href="#kusamakura">Kusamakura</a>, <a href="#mymedia-lite">Vertical
Writing</a></td>
</tr>
</tbody>
</table>
<h4 id="Content_Docs">Content Documents</h4>
<table>
<tbody>
<tr>
<th class="m1"> Feature </th>
<th class="m2"> Details </th>
<th class="m3"> Samples </th>
</tr>
<tr>
<th> HTML5 ruby </th>
<td>&#160;</td>
<td>
<a href="#kusamakura">Kusamakura</a>
</td>
</tr>
<tr>
<th> HTML5 dir/bdo </th>
<td>&#160;</td>
<td>
<a href="#regime-anticancer-arabic">Regime Anti-cancer Arabic</a>
</td>
</tr>
</tbody>
</table>
<h4 id="CSS">CSS</h4>
<table>
<tbody>
<tr>
<th class="m1"> Feature </th>
<th class="m2"> Details </th>
<th class="m3"> Samples </th>
</tr>
<tr>
<th> CSS3 Text </th>
<td>&#160;</td>
<td>
<a href="#kusamakura">Kusamakura</a>
</td>
</tr>
<tr>
<th> CSS3 Writing Modes </th>
<td>&#160;</td>
<td>
<a href="#kusamakura">Kusamakura</a>
</td>
</tr>
<tr>
<th> CSS3 Ruby Positioning </th>
<td>&#160;</td>
<td>
<a href="#hefty-water">Hefty Water</a>
</td>
</tr>
<!--                    <tr>
<th> oeb-page-head and oeb-page-foot </th>
<td>&#160;</td>
<td>
<a href="#GhV-oeb-page.epub">GhV-oeb-page</a>
</td>
</tr> -->
</tbody>
</table>
<h3 id="Styling_and_Layout">Styling and Layout</h3>
<h4 id="Alternate_Stylesheets">Alternate Stylesheets</h4>
<table>
<tbody>
<tr>
<th class="m1"> Feature </th>
<th class="m2"> Details </th>
<th class="m3"> Samples </th>
</tr>
<tr>
<th> Day/Night </th>
<td>&#160;</td>
<td>
<a href="#wasteland">The Waste Land</a>
</td>
</tr>
<tr>
<th> Vertical/Horizontal </th>
<td>&#160;</td>
<td><a href="#kusamakura">Kusamakura</a>, <a href="#mymedia-lite">Vertical
Writing</a></td>
</tr>
</tbody>
</table>
<h4 id="Fonts">Fonts</h4>
<table>
<tbody>
<tr>
<th class="m1"> Feature </th>
<th class="m2"> Details </th>
<th class="m3"> Samples </th>
</tr>
<tr>
<th> Embedded Fonts </th>
<td>Using WOFF</td>
<td>
<a href="#wasteland-woff">The Waste Land (WOFF fonts)</a>
</td>
</tr>
<tr>
<th>&#160;</th>
<td>Using OTF</td>
<td><a href="#wasteland-otf">The Waste Land (OTF fonts)</a>, <a href="#kusamakura"
>Kusamakura</a></td>
</tr>
<tr>
<th> Font Obfuscation </th>
<td>Using WOFF</td>
<td>
<a href="#wasteland-woff-obf">The Waste Land (obf. WOFF fonts)</a>
</td>
</tr>
<tr>
<th>&#160;</th>
<td>Using OTF</td>
<td>
<a href="#wasteland-otf-obf">The Waste Land (obf. OTF fonts)</a>
</td>
</tr>
</tbody>
</table>
<h4 id="Media_Queries">Media Queries</h4>
<table>
<tbody>
<tr>
<th class="m1"> Feature </th>
<th class="m2"> Details </th>
<th class="m3"> Samples </th>
</tr>
<tr>
<th>screen size and orientation</th>
<td>&#160;</td>
<td>
<a href="#the-swans">The Swans</a>
</td>
</tr>
</tbody>
</table>
<h4 id="CSS_Multi-column_layout">CSS Multi-column layout</h4>
<table>
<tbody>
<tr>
<th class="m1"> Feature </th>
<th class="m2"> Details </th>
<th class="m3"> Samples </th>
</tr>
<tr>
<th>basic multicol styling</th>
<td>&#160;</td>
<td>
<a href="#trees">Trees</a>
</td>
</tr>
</tbody>
</table>
<h4 id="CSS_Namespaces">CSS Namespaces</h4>
<table>
<tbody>
<tr>
<th class="m1"> Feature </th>
<th class="m2"> Details </th>
<th class="m3"> Samples </th>
</tr>
<tr>
<th>Namespaced attribute selectors</th>
<td>&#160;</td>
<td><a href="#the-swans">The Swans</a>, <a href="#cc-shared-culture">Shared
Culture</a></td>
</tr>
</tbody>
</table>
<h3 id="Media_Overlays">Media Overlays</h3>
<table>
<tbody>
<tr>
<th class="m1"> Feature </th>
<th class="m2"> Details </th>
<th class="m3"> Samples </th>
</tr>
<tr>
<th>&#160;</th>
<td>&#160;</td>
<td><a href="#moby-dick-mo">Moby Dick (with media overlays)</a>, <a href="#kusamakura"
>Kusamakura</a></td>
</tr>
</tbody>
</table>
<h3 id="TTS">TTS</h3>
<table>
<tbody>
<tr>
<th class="m1"> Feature </th>
<th class="m2"> Details </th>
<th class="m3"> Samples </th>
</tr>
<tr>
<th> SSML attributes </th>
<td>&#160;</td>
<td>
<a href="#georgia">Georgia</a>
</td>
</tr>
<tr>
<th> PLS dictionaries </th>
<td>&#160;</td>
<td>
<a href="#georgia">Georgia</a>
</td>
</tr>
<tr>
<th> CSS3 Speech </th>
<td>&#160;</td>
<td>
<a href="#accessible-epub3">Accessible EPUB 3</a>
</td>
</tr>
</tbody>
</table>
<h3 id="Linking">Linking</h3>
<table>
<tbody>
<tr>
<th class="m1"> Feature </th>
<th class="m2"> Details </th>
<th class="m3"> Samples </th>
</tr>
<tr>
<th> CFI </th>
<td>Intra-publication CFIs</td>
<td>
<a href="#georgia-cfi">Georgia (with EPUBCFIs)</a>
</td>
</tr>
</tbody>
</table>
<h3 id="Extensions">Extensions</h3>
<h4 id="Fixed_Layout">Fixed Layout</h4>
<table>
<tbody>
<tr>
<th class="m1"> Feature </th>
<th class="m2"> Details </th>
<th class="m3"> Samples </th>
</tr>
<tr>
<th> XHTML-based </th>
<td>&#160;</td>
<td><a href="#page-blanche">Page Blanche</a>, <a href="#haruko">Haruko</a></td>
</tr>
<tr>
<th> SVG-based </th>
<td>SVG embedded in XHTML spine items</td>
<td>
<a href="#sous-le-vent">Sous le Vent</a>
</td>
</tr>
<tr>
<th>&#160;</th>
<td>SVG directly in spine</td>
<td><a href="#svg-in-spine">SVG-in-spine</a>, <a href="#sous-le-vent-svg">Sous le Vent
(with SVG in spine)</a></td>
</tr>
<tr>
<th> JPEG-based </th>
<td>JPEG directly in spine</td>
<td><a href="#page-blanche-jpeg">Page Blanche (with JPEGs in spine)</a>, <a
href="#haruko-jpeg">Haruko (with JPEGs in spine)</a></td>
</tr>
<tr>
<th> Mixed reflowable/fixed </th>
<td>&#160;</td>
<td><a href="#the-voyage-of-life">The Voyage of Life</a>, <a
href="#the-voyage-of-life-tol">The Voyage of Life (with text
overlays)</a></td>
</tr>
</tbody>
</table>
<h4 id="Dictionaries_and_Glossaries">Dictionaries and Glossaries</h4>
<p>
<i>TBD</i>
</p>
<table>
<tbody>
<tr>
<th class="m1"> Feature </th>
<th class="m2"> Details </th>
<th class="m3"> Samples </th>
</tr>
</tbody>
</table>
<h3 id="Indexes">Indexes</h3>
<p>
<i>TBD</i>
</p>
<table>
<tbody>
<tr>
<th class="m1"> Feature </th>
<th class="m2"> Details </th>
<th class="m3"> Samples </th>
</tr>
</tbody>
</table>
<h4 id="OCF_Multiple_Renditions">OCF Multiple Renditions</h4>
<p>
<i>TBD</i>
</p>
<table style="width:100%;">
<tbody>
<tr>
<th style="width:25%;"> Feature </th>
<th style="width:40%;"> Details </th>
<th style="width:35%;"> Samples </th>
</tr>
</tbody>
</table>


## Want to contribute?

If you want to contribute to this project, here are your options:

### Reporting Issues

We want to make sure all samples provided here are conformant, pristine, and employ best practices consistently. If you spot an issue while reviewing and/or testing the content, report it to the issue tracker.

### Contributing new samples

If you want to contribute sample(s), please contact the project owners. After an initial discussion, they will either give you write access to the repository, or arrange some other means of getting the content into the repository. Note that all submitted content is by default subject to CC-BY-SA 3.0 licensing. As a contributor, you are able to specify attribution metadata only in the sample's package file. Note also that the project owners may suggest or even require modifications to your submissions to be done in order to meet the desired quality level.

### Contributing variations / improvements to existing samples

If you want to contribute to an existing sample by adding to or varying some aspect of it, use the issue tracker and submit your patch as an attachment. Note that your submission must adhere to the same open source license as the containing sample.
