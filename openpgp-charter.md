An Open Specification for Pretty Good Privacy (openpgp)
=======================================================

Charter
-------

Chairs:
     Christopher Liljenstolpe <ietf@cdl.asgaard.org>
     Daniel Kahn Gillmor <dkg@fifthhorseman.net>

Security Area Directors:
     Stephen Farrell <stephen.farrell@cs.tcd.ie>
     Kathleen Moriarty <Kathleen.Moriarty.ietf@gmail.com>

Security Area Advisor:
     Stephen Farrell <stephen.farrell@cs.tcd.ie>

 Mailing Lists:
     To Subscribe:       https://www.ietf.org/mailman/listinfo/openpgp
     Archive:            http://www.ietf.org/mail-archive/web/openpgp/

Description of Working Group
----------------------------

OpenPGP is an Internet standard that covers object encryption, object
signing, and identity certification.  These were defined by the first
incarnation of the OpenPGP working group.

The following is an excerpt from the charter of the original
incarnation of the openpgp working group

> The goal of the OpenPGP working group is to provide IETF standards
> for the algorithms and formats of PGP processed objects as well as
> providing the MIME framework for exchanging them via e-mail or other
> transport protocols.

The working group concluded this work and was closed in March
of 2008.  In the intervening period, there has been a rough consensus
reached that the RFC that defined the IETF openpgp standard, RFC4880,
is in need of revision.

This incarnation of the working group is chartered to primarily
produce a revision of RFC4880 to address issues that have been
identified by the community since the working group was originally
closed.

Some of the revisions might include, but are not limited to:

* inclusion of the CFRG elliptic curves

* proper AEAD symmetric crypto

* updated mandatory-to-implement algorithms

* updated fingerprints

The Working Group will perform the following work
-------------------------------------------------

Revise RFC4880

Other work may be entertained by the working group as long as it does
not interfere with the completion of the RFC4880 revision.  As the
revision of RFC4880 is the primary goal of the working group, other
work may be undertaken, so long as:

1. Will not unduly delay the closure of the working group
   after the revision is finished (unless the working group is
   rechartered).

2. Has widespread support in the working group.

Working Group Process
---------------------

The working group will endeavor to complete most if not all of its
work online on the working group's mailing list.  We expect that the
requirement for face-to-face sessions at IETF meetings to be minimal.

Furthermore, the working group will accept no ID's as working group
items unless there is a review by at least two un-interested parties
of the ID as part of the acceptance process.


Goals and Milestones
--------------------

1. September 2016: Working Group (rough) consensus on the necessary
   updates to RFC4880.

2. February 2016: First wg-id for RFC4880bis.

3. July 2016: RFC4880bis wg-id final call.
