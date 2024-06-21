This is the schema repository for Digital Forensics XML, version 2.0.0-beta.0.

If you intend to use the dfxml.xsd file as a DFXML document validator, note that you will also need to download two accompanying .xsd files under the "ref" directory.  The easiest way to do this is by downloading the repository as a Git clone, or by downloading the [zip archive](https://github.com/dfxml-working-group/dfxml_schema/archive/master.zip) from the Github page.

To report issues, questions, or feature requests, please either:
* File a Github issue, seeing first if it is already filed, [here](https://github.com/dfxml-working-group/dfxml_schema).
* Email the dfxml@nist.gov mailing list.  If you wish to join the mailing list, send an email to [dfxml-subscribe@nist.gov](mailto:dfxml-subsribe@nist.gov) (no subject or message body is necessary), and a moderator will grant access.


## Development conventions

Following version 1.2.0, this project adopted the following development conventions:

* [Semantic Versioning 2.0.0](https://semver.org/).
* A branching model as described [here](https://nvie.com/posts/a-successful-git-branching-model/), with the additional convention that a "release" branch will initially present `-beta.n` releases for a period of at least two weeks for comment.
  - When a feature branch is merged into `develop`, any associated Github Issues may be considered resolved.
