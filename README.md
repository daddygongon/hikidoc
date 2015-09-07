# HikiDoc

## Introduction

'HikiDoc' is a text-to-HTML conversion tool for web writers. HikiDoc
allows you to write using an easy-to-read, easy-to-write plain text
format, then convert it to structurally valid HTML (or XHTML).

## Requirements

HikiDoc requires Ruby 1.8.2 or later.

## Download

Get from the GitHub repository [https://github.com/hiki/hikidoc](https://github.com/hiki/hikidoc)

```
(eg.)
git clone https://github.com/hiki/hikidoc.git
```

## Installation

### Semi-manual installation

Run the 'setup.rb' script like so:

```
$ ruby setup.rb config
$ ruby setup.rb setup
# ruby setup.rb install
```

### Installation via RubyGems

Run the following command:

```
$ gem install hikidoc
```

## Syntax

See [TextFormattingRules](TextFormattingRules).

## Mailing list

To subscribe the HikiDoc ML, please send the following mail. English
posts are also welcome.

```
To: hikidoc@ml.fdiary.net
Cc: kazuhiko@fdiary.net
Subject: subscribe        <- any subject

Hello.                    <- any body
```

HikiDoc ML's archive is available at [http://www.fdiary.net/ml/hikidoc/](http://www.fdiary.net/ml/hikidoc/) .

## Related softwares

The following softwares use the HikiDoc library or the HikiDoc format.

<dl>
<dt><a href="http://www.tdiary.org/">tDiary</a></dt>
<dd>a Weblog/Web-diary software</dd>
<dt><a href="http://hikiwiki.org/">Hiki</a></dt>
<dd>a powerful and fast wiki clone</dd>
<dt><a href="http://lily.sourceforge.jp/">lily</a></dt>
<dd>a simple CMS</dd>
<dt><a href="http://search.cpan.org/perldoc?Text::HikiDoc">Text::HikiDoc</a></dt>
<dd>HikiDoc by Perl</dd>
<dt><a href="http://github.com/moro/piki_doc/">PikiDoc</a></dt>
<dd>a library that you can add plugin functions on HikiDoc</dd>
<dt><a href="http://sourceforge.jp/projects/mail2weblog/wiki/FrontPage">mail2weblog</a></dt>
<dd>a blog system via mobile phone email</dd>
</dl>

## License

HikiDoc's license is the 'Modified BSD License'.

```
Copyright (c) 2005, Kazuhiko <kazuhiko@fdiary.net>
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are
met:

    * Redistributions of source code must retain the above copyright
      notice, this list of conditions and the following disclaimer.
    * Redistributions in binary form must reproduce the above
      copyright notice, this list of conditions and the following
      disclaimer in the documentation and/or other materials provided
      with the distribution.
    * Neither the name of the HikiDoc nor the names of its
      contributors may be used to endorse or promote products derived
      from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
"AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT
OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT
LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```

