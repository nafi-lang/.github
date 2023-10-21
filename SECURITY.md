## Security

We believe it's important to take security seriously, even for small/hobby projects. We can't offer any sort of bug bounty, but we _greatly_ appreciate responsible disclosure of potential security issues and will do our best to address them in a reasonable timeframe.

### Reporting issues

The best way to report a security issue is [directly via GitHub](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability) so it can be handled directly by the [@nafi-lang/security](https://github.com/orgs/nafi-lang/teams/security) team. If you prefer email, we also accept security reports at nafi+security@cad97.com. Unsolicited communication (i.e. not potentially security related) at this address will be summarily ignored.

If there's any possibility that an issue could even potentially be exploited, we advise you to use private disclosure. We can't un-publicize a security risk once it's been made public. If public disclosure is nonproblematic, we can always create a public tracking issue after determining such.

Issues requiring deliberate misuse or misconfiguration of a library or application are generally considered safe for public disclosure without extenuating circumstances. An example exception to this is if a privledged context did not make sufficiently clear the potential risk of processing unsanitized user input.

### Helpful information

Please provide as much information in the report as possible to assist with understanding and resolving the issue, such as:

- The type of issue (e.g. undefined behavior, privilege escalation, etc.)
- Exactly where the issue manifests
- Versions/revisions of affected software
- Reproduction and/or proof of concept
- Any non-default configuration required for reproduction
- Estimated impact of issue

None of these details are required, but all are appreciated when applicable.
