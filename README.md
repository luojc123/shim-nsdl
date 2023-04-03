This repo i s for review of requests for signing shim.  To create a request for review:

- clone this repo
- edit the template below
- add the shim.efi to be signed
- add build logs
- add any additional binaries/certificates/SHA256 hashes that may be needed
- commit all of that
- tag it with a tag of the form "myorg-shim-arch-YYYYMMDD"
- push that to github
- file an issue at https://github.com/rhboot/shim-review/issues with a link to your branch
- approval is ready when you have accepted tag

Note that we really only have experience with using GRUB2 on Linux, so asking
us to endorse anything else for signing is going to require some convincing on
your part.

Here's the template:

-------------------------------------------------------------------------------
What organization or people are asking to have this signed:
-------------------------------------------------------------------------------
[Guangdong Zhongxing Newstart Technology Co. ,Ltd]

-------------------------------------------------------------------------------
What product or service is this for:
-------------------------------------------------------------------------------
[Newstart Desktop Linux V4.3.6]

-------------------------------------------------------------------------------
What's the justification that this really does need to be signed for the whole world to be able to boot it:
-------------------------------------------------------------------------------
[We're OS vendor]

-------------------------------------------------------------------------------
Who is the primary contact for security updates, etc.
-------------------------------------------------------------------------------
- Name:lvkaiyi
- Position:Engineer
- Email address:lv.kaiyi@gd-linux.com
- PGP key, signed by the other security contacts, and preferably also with signatures that are reasonably well known in the linux community:
	-----BEGIN PGP PUBLIC KEY BLOCK-----

mQENBF4mxmMBCADLulGam1qXMGdFv8ACIpa+UgxnPLtbGiivIbQyvHd3rDoruKbH
9gqRmJTZ53uoFLWuGdlshTFUDMNwDvffpxt8lMRJE6S9YZ8m/XkQL3Esu1m7nk7n
DGswPrG1waMOF3T+XRwucs990zBmC8nGF6W6AhLWVDmbl4LWRVvF1sXlkdRt/3V+
v59x/7pi7G5dX2EoiGz9qMvcFtPuz9b3Qa9GnVTLtfvI/cRidYFzt5JrVw+2yWtU
bXBLdrMAWEJJKyefGL2Lmw2jfexcf8NxbBi8ARhb/ilU4P205SSX9XM64l7yhgqE
5+Y438po4Bs3COywY2T3tczD/EfHl7jq27qVABEBAAG0KGx2a2FpeWkgKFBHUEtl
eSkgPGx2LmthaXlpQGdkLWxpbnV4LmNvbT6JATgEEwECACIFAl4mxmMCGwMGCwkI
BwMCBhUIAgkKCwQWAgMBAh4BAheAAAoJEB0Cp12ZeUEWK54H/RiTC/utxNL2nRah
NPMs9SQ9flrts9m7IM/RhtKJgMqnKhdQyPomD9Q0XKpfsQjB50n/4RS2Aey7bYj8
fqNis0uC4VwlOjvkiGm75v4In2BwrVPySz0MCmCaDHZFgCS4/pcGVQOQgz9D7RyL
E7VM6jNMqwgei+2uRkxJMkbyd9CJLNeNwwo4o9bincsa79s/pLkTm359pi9izVkI
+8FHMfWZvjd7qIiSmvnjPsM0kU8Fcu/h4R1n4yCzvbq6WR/BVuDruUSVX4yC88xe
E5vdkuY1teimEsr1+DuLbShO3BPjcrphrJhujgL6s7ac3V1JnYSOWBU9segvW0/a
pBP4vQy5AQ0EXibGYwEIAO9jBvJ8LKB96ArmirtzforfTdRmTzsJkH+BUidKQur3
ETjmt2ekQfsRrp5nlFZ9qT+J0/myfcgF9fbSjgNJyQSHcv3H1VxBbk6dGyRIxMqp
yFxDvBH0DihiOVl4aXGZJ9ztLnx3R0ywhC/9fa/UFW5D2Ynma/wmOdKsanZHrf3y
3HBA9/B4JtOi5D7Q1xl7xWw2MadrQ8g60zmaXUi/OxI79c92CxICkpKxnaxoGABs
AtqelcNNMH3lP5Fg2AvhAgrDnMVAread+N7LXJEjROnZdnUgks7bDKYQlcV5NI2t
z5pgF8brQR70A2iW6+6leZMhS8djisNGClHh9DTUqcsAEQEAAYkBHwQYAQIACQUC
XibGYwIbDAAKCRAdAqddmXlBFuj4B/0a04N+S/hrZ8SA20+Try8FMhJ6JYoL57tg
JM3uQej815ZunEU6ExwddVDz5d4mh+NDSh5f5S2E/nJ/8+V1YQPqSTeIONsPZQ/W
qaDIocj7xldt2/HDtLnJpVXGJouwqm34SMPRPYmPlisgCUml0OCWNA1VuLp3ehsp
fnXpYI5baZijaNwOeRNfHG4pJJd4ndKL5NEQ5gSiaQwK9Ts0vghJpgVxt+IPQ17Q
l01PszOtG8AsZ3zCMLcevGHBK7kbA8x+s7f2XIbmZVqQdZufBGLakLG/Ekw5vFPW
aK+Ynw60ipcIkGoYpDTTPLrVdk7QkAEbHWC1gzSrMmo89X1WUQOI
=4LA3
-----END PGP PUBLIC KEY BLOCK-----

-------------------------------------------------------------------------------
Who is the secondary contact for security updates, etc.
-------------------------------------------------------------------------------
- Name:maizhuodong
- Position:Engineer
- Email address:mai.zhuodong@gd-linux.com
- PGP key, signed by the other security contacts, and preferably also with signatures that are reasonably well known in the linux community:
-----BEGIN PGP PUBLIC KEY BLOCK-----

mQENBF4myXoBCACoBBQTzQnkTPrBS0AfQStcHO7ymmvXo3Rvs0wBf9QEMe01aYi9
Ax6Sgn1FkodswD1Us06TWBTagrvEG+3+M0hURXI36k5t8EL9Eg76zd4+sZOXpDFY
uaTLympEJL25PxmvFOi6hbsQlgGMOsF+kS5PcaZPOJvX8RBIc2KG485g+KcQz962
xunRB10C/81LCZntFA9LDpGLedr5x5nkgpBqZL1Arkl2WcXUtuq8BF6q/ET7UPZy
91WBXYHrO7rfz/98xxGTcXVw8TYuR3KDg7+tqMiGRC6g28d7ZmNBQP0iJM4AgWHs
hL06/17/WxPKFmgm+L7RQ3zV2vH3k0JPugovABEBAAG0MG1haXpodW9kb25nIChQ
R1BLZXkpIDxtYWkuemh1b2RvbmdAZ2QtbGludXguY29tPokBOAQTAQIAIgUCXibJ
egIbAwYLCQgHAwIGFQgCCQoLBBYCAwECHgECF4AACgkQfxKPgCr0TOYwnAf+Nm1q
DTiANj3SlkK0bDO3vlfUqY8MCErQ3Zxx4AziEBgkKbdiuDkCTgdZWRPjUCr6NpgA
geQqkuNd/C9JxAzJRYG+XbHdYkU4jLTO9BqLiURJ5vmNWddfEeT6jmemuIFBDhRg
pHjPzknL8l70VGIk1xscdO6uCdJr4NKk1Gc1VT8kVtnFpgbXdgO2ePupPWG9Ft0U
7tZo7vVZ0fNY3pRo0MRZ+0G9YIPHYmB1Oi4qMIiiaJm6cI1cn1/tE4no0HaOon5b
5smqlPeF8hYbEra3SJxALDx9cvjyg/mVF1p91ef6NZQPXnmJf3C5j+CcNthtvPkK
v5va+1PmgGVMSdBPK7kBDQReJsl6AQgApFjZOPzbjrj5tsdUfxYFrfFvgD+RRJSg
VOJ7PrdzBiTyS0eO3sBs2FGlpaOo49mTcYMg4mVp0QM677OyPg6D0W9ZZ8Keatte
mj4Y79L0EAk7dXkv2N5LAFxq2MSKcl7kMntwObkph6B+TbpJ4bQYxqGgNG0zX/3h
NljUrJNPWeO+ZwwHbduvks04Oj2+xU/I72HHfd74rRi1VCk9qkQFjeOPbzQhZ4gf
FAMKFLoWGvcUWlwR9cQC0WBQdxXgtsf8QlLvsg08zxVcMBxzT7L6J80W7QOKFNhN
XuRVm2Q77jX9q1fkoUHpbVtQF6JtKDFNZ084uAwZk0FK16l/L7SEAwARAQABiQEf
BBgBAgAJBQJeJsl6AhsMAAoJEH8Sj4Aq9EzmGDUH/1dVCwJR/atkKx4tzVIw6ER4
SeSiPwY/sBiWYTThWg+1aiohGCAxWOmTXcaLm0a8eYu6233cAe2N3Bq1XzZgTymv
EXBbvTZceQzNGS+brj5yOhrl+UnV6BV3bAN3QBRyM6Dv9wnF3lUa8SXEBCdjF/AD
161KuxzdHGkQGDYfrDUiAmYO2AjtrUg7aZP87snedsm/aTwI+d/UvGwPtBQE0cNj
9bPatUWv2yeihh1hPf+V+zxpMMtjDt9cCqFI1kk7+dpV4qzN9SSKWzdWp7BlDbSr
F7Fd9wnopEid1PoXvyDU4TOPRyTXGrrwGsSsTpX2U8Ix6vTmMozkDIpxCsgBfQQ=
=evGb
-----END PGP PUBLIC KEY BLOCK-----

-------------------------------------------------------------------------------
Please create your shim binaries starting with the 15.4 shim release tar file:
https://github.com/rhboot/shim/releases/download/15.4/shim-15.4.tar.bz2

This matches https://github.com/rhboot/shim/releases/tag/15.4 and contains
the appropriate gnu-efi source.
-------------------------------------------------------------------------------
Yes, we are using shim 15.4 release tarball

-------------------------------------------------------------------------------
URL for a repo that contains the exact code which was built to get this binary:
-------------------------------------------------------------------------------
https://github.com/circle-linux/shim-review/blob/master/shim-unsigned-x64-15.4-4.el8.1.src.rpm

-------------------------------------------------------------------------------
What patches are being applied and why:
-------------------------------------------------------------------------------
none

-------------------------------------------------------------------------------
If bootloader, shim loading is, GRUB2: is CVE-2020-14372, CVE-2020-25632,
 CVE-2020-25647, CVE-2020-27749, CVE-2020-27779, CVE-2021-20225, CVE-2021-20233,
 CVE-2020-10713, CVE-2020-14308, CVE-2020-14309, CVE-2020-14310, CVE-2020-14311,
 CVE-2020-15705, and if you are shipping the shim_lock module CVE-2021-3418
-------------------------------------------------------------------------------
grub2-2.02-78


-------------------------------------------------------------------------------
What exact implementation of Secureboot in GRUB2 ( if this is your bootloader ) you have ?
* Upstream GRUB2 shim_lock verifier or * Downstream RHEL/Fedora/Debian/Canonical like implementation ?
-------------------------------------------------------------------------------
RHEL like implementation

-------------------------------------------------------------------------------
If bootloader, shim loading is, GRUB2, and previous shims were trusting affected
by CVE-2020-14372, CVE-2020-25632, CVE-2020-25647, CVE-2020-27749,
  CVE-2020-27779, CVE-2021-20225, CVE-2021-20233, CVE-2020-10713,
  CVE-2020-14308, CVE-2020-14309, CVE-2020-14310, CVE-2020-14311, CVE-2020-15705,
  and if you were shipping the shim_lock module CVE-2021-3418
  ( July 2020 grub2 CVE list + March 2021 grub2 CVE list )
  grub2:
* were old shims hashes provided to Microsoft for verification
  and to be added to future DBX update ?
* Does your new chain of trust disallow booting old, affected by CVE-2020-14372,
  CVE-2020-25632, CVE-2020-25647, CVE-2020-27749,
  CVE-2020-27779, CVE-2021-20225, CVE-2021-20233, CVE-2020-10713,
  CVE-2020-14308, CVE-2020-14309, CVE-2020-14310, CVE-2020-14311, CVE-2020-15705,
  and if you were shipping the shim_lock module CVE-2021-3418
  ( July 2020 grub2 CVE list + March 2021 grub2 CVE list )
  grub2 builds ?
-------------------------------------------------------------------------------
This is our first shim submission

-------------------------------------------------------------------------------
If your boot chain of trust includes linux kernel, is
"efi: Restrict efivar_ssdt_load when the kernel is locked down"
upstream commit 1957a85b0032a81e6482ca4aab883643b8dae06e applied ?
Is "ACPI: configfs: Disallow loading ACPI tables when locked down"
upstream commit 75b0cea7bf307f362057cc778efe89af4c615354 applied ?
-------------------------------------------------------------------------------
no

-------------------------------------------------------------------------------
If you use vendor_db functionality of providing multiple certificates and/or
hashes please briefly describe your certificate setup. If there are allow-listed hashes
please provide exact binaries for which hashes are created via file sharing service,
available in public with anonymous access for verification
-------------------------------------------------------------------------------
We don't use vendor_db functionality in this build

-------------------------------------------------------------------------------
If you are re-using a previously used (CA) certificate, you will need
to add the hashes of the previous GRUB2 binaries to vendor_dbx in shim
in order to prevent GRUB2 from being able to chainload those older GRUB2
binaries. If you are changing to a new (CA) certificate, this does not
apply. Please describe your strategy.
-------------------------------------------------------------------------------
We are not reusing any previously used CA, this is our first submission

-------------------------------------------------------------------------------
What OS and toolchain must we use to reproduce this build?  Include where to find it, etc.  We're going to try to reproduce your build as close as possible to verify that it's really a build of the source tree you tell us it is, so these need to be fairly thorough. At the very least include the specific versions of gcc, binutils, and gnu-efi which were used, and where to find those binaries.
If the shim binaries can't be reproduced using the provided Dockerfile, please explain why that's the case and what the differences would be.
-------------------------------------------------------------------------------
Dockerfile is provided to reproduce this build

-------------------------------------------------------------------------------
Which files in this repo are the logs for your build?   This should include logs for creating the buildroots, applying patches, doing the build, creating the archives, etc.
-------------------------------------------------------------------------------
build.log

-------------------------------------------------------------------------------
Add any additional information you think we may need to validate this shim
-------------------------------------------------------------------------------
New vendor - First submission
