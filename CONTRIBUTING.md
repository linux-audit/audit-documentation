How to Contribute to the Linux Audit Documentation Project
===============================================================================
https://github.com/linux-audit/audit-documentation

This document is intended to act as a guide to help you contribute to the
Linux Audit Documentation project.  It is not perfect, and there will always be
exceptions to the rules described here, but by following the instructions below
you should have a much easier time getting your work merged with the upstream
project.

## Explain Your Work

At the top of every patch you should include a one line summary of the change
that follows the "\<topic\>: \<brief summary\>" format.  After that you should
include a slightly longer description of the changes you are making in this
patch and why you are making these changes.  When in doubt you can always look
at the `git log` for examples.

## Sign Your Work

The sign-off is a simple line at the end of the patch description, which
certifies that you wrote it or otherwise have the right to pass it on as an
open-source patch.  The "Developer's Certificate of Origin" pledge is taken
from the Linux Kernel and the rules are pretty simple:

	Developer's Certificate of Origin 1.1

	By making a contribution to this project, I certify that:

	(a) The contribution was created in whole or in part by me and I
	    have the right to submit it under the open source license
	    indicated in the file; or

	(b) The contribution is based upon previous work that, to the best
	    of my knowledge, is covered under an appropriate open source
	    license and I have the right under that license to submit that
	    work with modifications, whether created in whole or in part
	    by me, under the same open source license (unless I am
	    permitted to submit under a different license), as indicated
	    in the file; or

	(c) The contribution was provided directly to me by some other
	    person who certified (a), (b) or (c) and I have not modified
	    it.

	(d) I understand and agree that this project and the contribution
	    are public and that a record of the contribution (including all
	    personal information I submit with it, including my sign-off) is
	    maintained indefinitely and may be redistributed consistent with
	    this project or the open source license(s) involved.

... then you just add a line to the bottom of your patch description, with
your real name, saying:

	Signed-off-by: Random J Developer <random@developer.example.org>

You can add this to your commit description in `git` with `git commit -s`

## Post Your Patches Upstream using GitHub Pull Requests

See [this guide](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) if you've never done this before.
