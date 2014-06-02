# Making 18F Open Source by Default

**Note:** This is currently a **draft**, **pre-decisional** document. It is **not finalized** for 18F.

[18F](https://18f.gsa.gov), a digital services delivery team within the [General Services Administration](http://gsa.gov), develops in-house digital solutions to help agencies meet the needs of the citizens and businesses it serves. This requires flexibility in how we code, with a focus on lowering costs for the American people, while improving their interactions with the U.S. government.

The default position of 18F when working on new projects is to:

1. Use Free and Open Source Software (FOSS) <1><a href="#fn1" id="ref1">1</a></sup> in our projects and to contribute back to the open source community;
2. Create an environment where any project can be developed in the open; and
3. Publish all source code created or modified by 18F publicly.

## Benefits

Using FOSS allows for product customization, advances interoperability between tools, and improves the overall quality to the final product. Other benefits include:

1. **Flexible usage.** The benefits to using FOSS compel 18F to meet citizen and business needs by modifying existing or creating new FOSS. FOSS is particularly suitable for rapid prototyping and experimentation. The testing process generates minimal costs, and the process encourages the identification and elimination of defects not recognized by the original development team.

1. **Community involvement.** Publicly available source code enables continuous and broad peer review. Whether it is simply publishing the completed code or opening the development process, expanding the review and testing process to a wider audience, beyond the development team, ensures increased software reliability and security. Developing in the open also allows for other opinions to help adjust the direction of a product to maximize its usefulness to the community it serves.

1. **Cost-savings.**  able to modify FOSS enables 18F to respond rapidly to changing missions and markets. Support and maintenance of open source code, as opposed to more burdensome usages of proprietary software, provides a real cost advantage where multiple copies of software are required, or when the user base grows. The total cost of ownership is shared with a community, rather than solely 18F.

1. **Reusability.** The code we create belongs to the American people as a part of the public domain. The code we work on was paid for by the American people, but the end-product is not the only way they should be able to interact with their government. By coding in FOSS, we help populate a larger commons that cities, states, businesses, and citizens can participate in. This creates real economic value through lowering the burden of replicating similar work or by allowing the private sector to build off of and create new businesses around code developed at 18F.

## Maximizing Community Involvement

The open source community requires active involvement from its members for code to be discussed and modified in a robust manner. 18F will be an active contributor to FOSS projects that it or its clients utilize, whether they are maintained or operated by 18F. Code written entirely by 18F staff, and by contractors who are developing software on behalf of 18F, are within the public domain. Because of this, 18F encourages gratuitous contributions to its open-source projects, whether it be code, commentary, bug reports, feature requests, or overall strategic direction.

Because all of 18F’s work is intended to be released for public use, forks or clones of our code repositories are free to be re-distributed. This means code created by 18F can be integrated into work that is under a more restrictive license, even those that are not considered open source licenses.

This changes when our code repositories include code that was not created by 18F and carries an open license. Code previously released under an open source license and then modified by 18F or its contractors is considered a ["joint work"] [1] and must be released under the terms of the original open source license.

  [1]: http://www.copyright.gov/title17/92chap1.html#101 "Joint Work"

The public can use our code as the basis of wholly proprietary and commercial systems. 18F would appreciate that users of our code disclose its lineage, but 18F maintains no legal right to require disclosure. Notifications that our work is being used in a new system are always greatly appreciated.

## Using Code Under a License

As previously mentioned, most work generated at 18F falls within the public domain. However, certain projects will require the usage of licensed open source software not created by 18F. Open source licenses make source code available under specific terms and conditions. These terms and conditions specify how the code may be used, modified, or shared. When 18F modifies licensed open source code, it is important to understand both the specifics of the open source license in question and how 18F intends to use and redistribute any modified FOSS.

For our international colleagues, 18F also permanently waives all copyright and related rights worldwide to code created by 18F or its contractors.

## Distribution of Code

There is a misconception that FOSS that is distributed to the public should not be integrated or modified for use in sensitive systems. This runs counter to how FOSS is often used. FOSS is often preferred for use in sensitive systems, due in part to its increased auditability because security in FOSS must be designed never to rely on obscurity in how the code works.

In addition, many open source licenses permit the user to modify OSS for internal use without being obligated to distribute source code to the public. However, if the user chooses to distribute the modified OSS outside the user's organization, then it is subject to whatever license it carries.

## Legal and Policy

Agencies have been encouraged to acquire the best information technology service to meet their needs. The Office of Management and Budget (OMB) has released memoranda indicating that policies surrounding procurement of new information technology are ["intentionally technology and vendor neutral,"] [1] and has [stated] [2] that open source software can and should be considered when procuring new services. In nearly every case, FOSS meets the definition of ["commercial computer software"] [3] and agencies are [required] [4] to include open source software in their market research.

  [1]: http://www.whitehouse.gov/omb/memoranda_fy04_m04-16 "OMB M-04-16"
  [2]: http://www.whitehouse.gov/sites/default/files/omb/assets/egov_docs/memotociostechnologyneutrality.pdf "OMB Memo on Tech Neutrality"
  [3]: http://www.gpo.gov/fdsys/pkg/CFR-2011-title48-vol1/pdf/CFR-2011-title48-vol1-sec27-405-3.pdf "Commercial computer software"
  [4]: http://www.whitehouse.gov/sites/default/files/omb/assets/egov_docs/memotociostechnologyneutrality.pdf "OMB Memo on Tech Neutrality"

Numerous agencies, most prominently the [Department of Defense (DoD)](http://en.wikipedia.org/wiki/Use_of_Free_and_Open_Source_Software_(FOSS)_in_the_U.S._Department_of_Defense), regularly use FOSS to meet their own needs and have updated their internal policies to take part in the communities built around FOSS.

## Exceptions

There are certain instances where 18F will not meet any or all of our positions where. Code shall not be released or developed in the open if any of the following conditions are met:

* The Government does not have the rights to reproduce and release the item.

* The public release of the item is restricted by other law or regulation, such as the Export Administration Regulations or the International Traffic in Arms Regulation.

* If open-sourcing the code or opening its development will result in privacy violations or security vulnerabilities.

* There is an overwhelming business need to not publish original or modified source code.

These decisions will be made as needed by the 18F DevOps team, which will lead an interdisciplinary team to review the conditions under which code will not be made available publicly. If an existing solution cannot be found in the open-source community, 18F may consider other options, including creating an open-source solution itself. Ultimately, the software that best meets the needs and mission of 18F should be used, regardless of whether the software is open source.

## Future Changes

We view this policy as a living document. 18F looks forward to approaching this document in the future and making changes, if necessary.

## Thanks

18F would like to thank the Consumer Financial Protection Bureau, Department of Defense, and Office of Management and Budget in their work in blazing the path for the use of FOSS in the Federal Government.

## Get in touch

Leave an issue, or make a pull request to this repository. To contact us privately, email <a href="mailto:18F@gsa.gov">18F@gsa.gov</a>.

<hr></hr>

<1 id="fn1">1. [FOSS is software that does not charge users a purchase or licensing fee for modifying or redistributing the source code.]<a href="#ref1" title="Jump back to footnote 1 in the text.">↩</a></sup>