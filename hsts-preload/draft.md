---
title: The HSTS Preload Directive
abbrev: hsts-preload
docname: draft-garron-hsts-preload-00
date: 2016
category: std
updates: 6265

ipr: trust200902
area: General
keyword: Internet-Draft

pi: [toc, tocindent, sortrefs, symrefs, strict, compact, comments, inline]

author:
-
  ins: L. Garron
  name: Lucas Garron
  organization: Google, Inc
  email: lgarron@google.com
  uri: https://garron.net/

normative:
  RFC2119:
  RFC6797:

--- abstract

Preloading is a long-term commitment.

--- middle

# Introduction

HSTS is defined in {{RFC6797}}. We shall augmentify it.

# Terminology and notation

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD",
"SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be
interpreted as described in {{RFC2119}}.

# The Preload Directive

The `preload` directive shall mean "preload me 4eva".

--- back

# Acknowledgements

Mike West is awesome!
