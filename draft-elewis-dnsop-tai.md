---
title: "Trust Anchor Indicator"
abbrev: "TAI"
category: info

docname: draft-elewis-dnsop-tai-latest
submissiontype: IETF  # also: "independent", "editorial", "IAB", or "IRTF"
number:
date:
consensus: true
v: 3
area: "Operations and Management"
workgroup: "Domain Name System Operations"
keyword:
 - next generation
 - unicorn
 - sparkling distributed ledger
venue:
  group: "Domain Name System Operations"
  type: "Working Group"
  mail: "dnsop@ietf.org"
  arch: "https://mailarchive.ietf.org/arch/browse/dnsop/"
  github: "edwardlewisicann/tai"
  latest: "https://edwardlewisicann.github.io/tai/draft-elewis-dnsop-tai.html"

author:
 -
    fullname: Edward Lewis
    organization: ICANN
    email: edward.lewis@icann.org.

normative:

informative:


--- abstract

This is an addition to the DNS and DNSSEC protocol to convey trust anchor information from the zone administration to DNSSEC validating resolvers.

This is intended to replace the use of Automated Updates of DNSSEC Trust Anchors, STD 74.  This document will describe Trust Anchor Indicators and why this replacement is needed.


--- middle

# Introduction

Trust Anchor Indicator is a replacement for Automated Updates of DNSSEC Trust Anchors, motivated by some deficiencies in the existing standardized approach.  This document will first describe what trust anchor indication is and what is required, second describe the protocol extension, and finally cover the reasons why this is proposed to replace the existing mechanism.


# Conventions and Definitions

{::boilerplate bcp14-tagged}


# Security Considerations

TODO Security


# IANA Considerations

This document has no IANA actions.


--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
