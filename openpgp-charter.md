OpenPGP is an Internet standard that covers object encryption, object
signing, and identity certification. These were defined by the first
incarnation of the OpenPGP working group.

The following is an excerpt from the charter of the original
incarnation of the openpgp working group

> The goal of the OpenPGP working group is to provide IETF standards
> for the algorithms and formats of PGP processed objects as well as
> providing the MIME framework for exchanging them via e-mail or other
> transport protocols.

The working group concluded this work and was closed in March of
2008. In the intervening period, there has been a rough consensus
reached that the RFC that defined the IETF openpgp standard, RFC4880,
is in need of revision.

This incarnation of the working group is chartered to primarily
produce a revision of RFC4880 to address issues that have been
identified by the community since the working group was originally
closed.

These revisions will include, but are not limited to:

* Potential inclusion of elliptic curves recommended by the CFRG (see
  note below)

* A symmetric encryption mechanism that offers modern message
  integrity protection (e.g. AEAD)

* Revision of mandatory-to-implement algorithm selection and
  deprecation of weak algorithms

* An updated public-key fingerprint mechanism

The Working Group will perform the following work:

* Revise RFC4880

* Other work related to OpenPGP may be entertained by the working
  group as long as it does not interfere with the completion of the
  RFC4880 revision. As the revision of RFC4880 is the primary goal of
  the working group, other work may be undertaken, so long as:

   1. The work will not unduly delay the closure of the working group
      after the revision is finished (unless the working group is
      rechartered).

   2. The work has widespread support in the working group.

Inclusion of CFRG Curves
------------------------

The Working Group will consider CFRG curves as possible Mandatory to
Implement (MTI) based on the output of the CFRG and/or Working Group
consensus in the matter.

Working Group Process
---------------------

The working group will endeavor to complete most if not all of its
work online on the working group's mailing list. We expect that the
requirement for face-to-face sessions at IETF meetings to be minimal.

Furthermore, the working group will accept no ID's as working group
items unless there is a review by at least two un-interested parties
of the ID as part of the acceptance process.


Milestones

Sep 2015 - Working Group (rough) consensus on the necessary updates to RFC4880.

Feb 2016 - First wg-id for RFC4880bis

Jul 2016 - RFC4880bis wg-id final call


