# Making 18F Open Source by Default

<!---
Title changed to better reflect changes made herein and the tonal shift I was going for. . 
-->

18F, a new organization within the General Services Administration, provides in-house digital solutions to help agencies meet the needs of the citizens and businesses it serves. This requires flexibility in how we code and a focus on creating cost-savings for the American people while improving how they are able to interact with their government. 

The default position of 18F is to use Free and Open Source Software (FOSS) in our projects and to contribute back to the open source community. FOSS is software that does not charge users a purchase or licensing fee for modifying or redistributing the source code. FOSS creates a number of advantages in how we are able to work, including allowing for  product customization, advancing interoperability between tools, and improving the overall quality to the final product. Other benefits are:

<!---
1. Firming up the definition of FOSS to include how we define "free." Purpose is to differentiate the cost associated with hiring a developer to modify the code versus fees or licensing costs associated with acquiring. 
-->

1. **Flexible usage.** The benefits to using FOSS compels 18F to meet citizen and consumer needs by modifying existing or creating new FOSS. FOSS is particularly suitable for rapid prototyping and experimentation. The testing process creates minimal costs and the process encourages the identification and eliminiation of defects not recognized by the original development team. 

1. **Community involvement.** Publicly available source code enables continuous and broad peer review. Opening the review and testing process to an a larger audience than the development team ensures increased reliability in the software and its security. 

1. **Cost-Savings.** Being able to modify FOSS enables 18F to respond rapidly to changing missions and markets. Flexible licenses remove the traditional restrictions for who can use the software or how it is used, which will allow 18F to create new products and services to keep pace with industry best practices. This leads to cost-savings for our clients and the American people. Support and maintenance of the source code, as opposed to licensing, provides a real cost advantage where multiple copies of software is required or when the user base grows. The total cost of ownership is shared with a community, rather than solely 18F. 

+ In addition, the code we create belongs to the American people as a part of the public domain. The code we work on was paid for by the American people, but the end-product is not the only way they should be able to interact with their government. By coding in FOSS, we help populate a larger commons that cities, states, businesses, and citizens can take advantage of.

<!---
1. I removed "There are several positive aspects of FOSS that should compel 18F to seek out FOSS when
conducting market research:" because of the association "market research" has with procurement policy. 
2. Lots of stuff here was reworded, consolidated, and moved around. 
3. New addition for the case that the source code we create belongs to the taxpayer/American people. 
-->

## Community Involvement

The open source community requires active involvement from its members for it to thrive. 18F will be an active contributor to FOSS projects that it or its clients utilize, whether they are maintained or operated by 18F. 

18F encourages gratuitous contributions to its open-source projects, whether it be code, commentary, bug reports, feature requests, or overall strategic direction.

Because all of 18F’s work is intended to be released into the public domain, forks or clones of our code repositories are free to be re-distributed into more restrictive licenses, even those that are not considered to be open-source licenses. 

The public can use our code as the basis of wholly proprietary and commercial systems. 18F would appreciate that users of our code disclose its lineage, but 18F maintains no legal right to require disclosure. Notifications that our work is being used in a new system are always greatly appreciated.

## Legal and Policy

Agencies have been encouraged to acquire the best information technology service to meet their needs. The Office of Management and Budget (OMB) has released memoranda indicating that policies surrounding procurement of new information technology are ["intentionally technology and vendor neutral,"] [1] and has [stated] [2] that open source software can and should be considered when procuring new services. In nearly every case, FOSS meets the definition of ["commercial computer software"] [3] and agencies are [required] [4] to include open source software in their market research. 

  [1]: http://www.whitehouse.gov/omb/memoranda_fy04_m04-16        "OMB M-04-16"
  [2]: http://www.whitehouse.gov/sites/default/files/omb/assets/egov_docs/memotociostechnologyneutrality.pdf  "OMB Memo on Tech Neutrality"
  [3]: http://www.gpo.gov/fdsys/pkg/CFR-2011-title48-vol1/pdf/CFR-2011-title48-vol1-sec27-405-3.pdf "Commercial computer software"
  [4]: http://www.whitehouse.gov/sites/default/files/omb/assets/egov_docs/memotociostechnologyneutrality.pdf  "OMB Memo on Tech Neutrality"

Numerous agencies, most prominently the Department of Defense (DoD), regularly use FOSS to meet their own needs and have updated their internal policies to take part in the communities built around FOSS. 

## Code Made Public

Code written entirely by 18F staff, and by contractors who are developing software on behalf of 18F, is to be released as a public domain work.

Code previously released under an open source license and then modified by 18F or its contractors is considered a ["joint work"] [1] and must be released under the terms of the original open source license. 

  [1]: http://www.copyright.gov/title17/92chap1.html#101        "Joint Work"

## Distribution of Code

Open source licenses make source code available under specific terms and conditions. These terms and conditions specify how the code may be used, modified, or shared. When 18F modifies licensed open source code, it is important to understand both the specifics of the open source license in question and how 18F intends to use and redistribute any modified FOSS. 

There is a misconception that FOSS that is distributed to the public should not be integrated or modified for use in sensitive systems. FOSS is often preferred for use in sensitive systems. This is due in part to its increased auditability, and in part because security in FOSS must be designed never to rely on obscurity in how the code works.

In addition, many open source licenses permit the user to modify FOSS for internal use without being obligated to distribute source code to the public. 

However, if the user chooses to distribute the modified FOSS outside the user's organization (e.g., a Government user distributes the code outside the Government), then some FOSS licenses (such as the GNU General Public License) do require distribution of the corresponding source code to the recipient of the software.

## Exceptions

There are certain instances where it will not be permissible to release code. Code shall not be released if either of the following conditions are met:

* The Government does not have the rights to reproduce and release the item. The Government has public release rights when the software is developed by Government staff or its contractors, when the Government receives "unlimited rights" in software developed by a contractor at Government expense, or when pre-existing FOSS is modified by or for the Government.

* The public release of the item is restricted by other law or regulation, such as the Export Administration Regulations or the International Traffic in Arms Regulation.

## Conclusions

These considerations result in an **open-source by default policy** at 18F. If a solution cannot be found in the open-source community, 18F may consider other options. Ultimately, the software that best meets the needs and mission of 18F should be used, regardless of whether the software is open source.

18F also hereby adopts an **open-development first policy**. Whenever possible, 18F will begin development in the open. If code is developed first in private, the 18F DevOps team will lead an interdisciplinary review to ensure that open-sourcing the code will not result in privacy violations or security vulnerabilities.

When contracting developer services, **18F will require vendors to use FOSS and develop open-source code** wherever possible, given the rationale above.

18F would like to thank the Consumer Finance Protection Bureau, Department of Defense, and Office of Management and Budget in their work in blazing the path for the use of FOSS in the Federal Government. 

<!---
Adding a shout out.
--->

## Get in touch

Leave an issue, or make a pull request to this repository. To contact us privately, email 18F@gsa.gov.
