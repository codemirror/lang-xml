<!-- NOTE: README.md is generated from src/README.md -->

# @codemirror/lang-xml [![NPM version](https://img.shields.io/npm/v/@codemirror/lang-xml.svg)](https://www.npmjs.org/package/@codemirror/lang-xml)

[ [**WEBSITE**](https://codemirror.net/6/) | [**ISSUES**](https://github.com/codemirror/codemirror.next/issues) | [**FORUM**](https://discuss.codemirror.net/c/next/) | [**CHANGELOG**](https://github.com/codemirror/lang-xml/blob/main/CHANGELOG.md) ]

This package implements XML language support for the
[CodeMirror](https://codemirror.net/6/) code editor.

The [project page](https://codemirror.net/6/) has more information, a
number of [examples](https://codemirror.net/6/examples/) and the
[documentation](https://codemirror.net/6/docs/).

This code is released under an
[MIT license](https://github.com/codemirror/lang-xml/tree/main/LICENSE).

We aim to be an inclusive, welcoming community. To make that explicit,
we have a [code of
conduct](http://contributor-covenant.org/version/1/1/0/) that applies
to communication around the project.

## API Reference
<dl>
<dt id="user-content-xml">
  <code><strong><a href="#user-content-xml">xml</a></strong>(<a id="user-content-xml^conf" href="#user-content-xml^conf">conf</a>&#8288;?: <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object">Object</a> = {}) → <a href="https://codemirror.net/6/docs/ref#language.LanguageSupport">LanguageSupport</a></code></dt>

<dd><p>XML language support. Includes schema-based autocompletion when
configured.</p>
<dl><dt id="user-content-xml^conf">
  <code><strong><a href="#user-content-xml^conf">conf</a></strong></code></dt>

<dd><dl><dt id="user-content-xml^conf.elements">
  <code><strong><a href="#user-content-xml^conf.elements">elements</a></strong>&#8288;?: readonly Object[]</code></dt>

<dd><p>Provide a schema to create completions from.</p>
</dd><dt id="user-content-xml^conf.attributes">
  <code><strong><a href="#user-content-xml^conf.attributes">attributes</a></strong>&#8288;?: readonly Object[]</code></dt>

<dd><p>Supporting attribute descriptions for the schema specified in
<a href="#user-content-xml%5econf.elements"><code>elements</code></a>.</p>
</dd></dl></dd></dl></dd>
<dt id="user-content-xmllanguage">
  <code><strong><a href="#user-content-xmllanguage">xmlLanguage</a></strong>: <a href="https://codemirror.net/6/docs/ref#language.LezerLanguage">LezerLanguage</a></code></dt>

<dd><p>A language provider based on the <a href="https://github.com/lezer-parser/xml">Lezer XML
parser</a>, extended with
highlighting and indentation information.</p>
</dd>
</dl>

