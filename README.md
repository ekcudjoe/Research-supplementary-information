<!-- Fixed-width, GitHub-friendly HTML table.
     Paste into a README.md (GitHub will render HTML) or an .html file.
     Notes:
     - Uses a colgroup for fixed column widths.
     - Uses fixed table layout + word wrapping to prevent overflow.
     - Includes optional sticky header (works in many browsers; GitHub may ignore sticky). -->

<style>
  .toe-table-wrap {
    max-width: 100%;
    overflow-x: auto;
    border: 1px solid #d0d7de;
    border-radius: 6px;
  }
  table.toe-table {
    width: 1600px;              /* fixed overall width; adjust as desired */
    table-layout: fixed;        /* critical for fixed column widths */
    border-collapse: collapse;
    font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Helvetica,Arial,sans-serif;
    font-size: 13px;
    line-height: 1.35;
  }
  table.toe-table th,
  table.toe-table td {
    border: 1px solid #d0d7de;
    padding: 10px 12px;
    vertical-align: top;
    word-wrap: break-word;
    overflow-wrap: anywhere;
    white-space: normal;
  }
  table.toe-table th {
    background: #f6f8fa;
    font-weight: 600;
    position: sticky;  /* may or may not apply on GitHub */
    top: 0;
    z-index: 2;
  }
  table.toe-table td:first-child {
    font-weight: 600;
  }
</style>

<div class="toe-table-wrap">
  <table class="toe-table" aria-label="TOE findings table (fixed widths)">
    <colgroup>
      <col style="width: 260px;">
      <col style="width: 450px;">
      <col style="width: 450px;">
      <col style="width: 440px;">
    </colgroup>
    <thead>
      <tr>
        <th>University</th>
        <th>Technology dimension</th>
        <th>Organizational dimension</th>
        <th>Environmental dimension</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>University of California, Berkeley (UC Berkeley)</td>
        <td>UC Berkeley demonstrates technological readiness for the DOJ April 2026 mandate. The university adopts WCAG 2.1 AA as its governing technical standard and applies it comprehensively across websites, online courses, podcasts, and video platforms. Its procedures outline detailed accessibility requirements, including accurate captions, transcripts, alt text, keyboard navigation, and proper HTML structure, showing a mature understanding of technical accessibility needs. Extensive developer guidance, mandatory training materials, and clear remediation timelines further strengthen the university’s technological capacity.</td>
        <td>UC Berkeley’s organizational readiness is supported by formal, enforceable procedures and a clearly defined governance structure. The Digital Accessibility Program (DAP) oversees policy implementation, while a designated Web Accessibility Coordinator provides leadership and decision-making authority. Responsibilities are clearly assigned to faculty, staff, and contractors, ensuring accountability for all public-facing content. Mandatory training for content creators, structured exception management processes, and systematic remediation workflows demonstrate strong institutional coordination. The availability of dedicated support channels and campus-wide guidance further reinforces Berkeley’s operational capacity to meet federal accessibility requirements.</td>
        <td>Environmental readiness is driven by direct legal obligations under a DOJ Consent Decree and long-standing ADA Title II and ITAP requirements. Berkeley’s digital accessibility strategy is shaped by strong external regulatory pressure and public accountability mechanisms, including public complaint portals, required 7-day response windows, and defined remediation timelines. The university also demonstrates awareness of third-party platform constraints and external stakeholder needs by clearly outlining when the institution bears responsibility for accessibility and when platform limitations apply. These environmental forces collectively ensure that Berkeley remains aligned with evolving federal accessibility standards and public expectations.</td>
      </tr>

      <tr>
        <td>University of California, Los Angeles (UCLA)</td>
        <td>UCLA demonstrates technological readiness for the April 2026 WCAG 2.1 AA mandate. The university explicitly acknowledges the DOJ requirement to meet WCAG 2.1 Level AA by April 24, 2026, and provides instructors with concrete examples of required accessible practices, including adding alt text, ensuring captions and transcripts, and preparing accessible PDFs. The institution is actively using Ally analytics to identify accessibility gaps in digital course materials. Although UCLA provides access to resources, training modules, and campus partner support, the material emphasizes course materials rather than systemwide digital platforms (e.g., public websites, audio/video repositories). Thus, while UCLA shows strong instructional-level technical preparation, the evidence presented does not fully reflect campuswide technical enforcement structures comparable to highly mature institutions.</td>
        <td>UCLA displays organizational readiness, supported by a multi-unit governance structure that includes the Teaching and Learning Center, Bruin Learn Center of Excellence, Disabilities and Computing Program (DCP), and other campus partners. The university is developing a new Digital Accessibility Governance structure to guide strategy, interventions, and campus-wide improvements. Responsibilities for accessibility are implicitly distributed across instructors, IT units, and accessibility specialists, with clear emphasis on updating course materials and following accessibility best practices. UCLA offers extensive organizational support through asynchronous modules, live training, consultations, and coordinated communication campaigns. The strong internal partnerships and governance redesign indicate substantial institutional commitment, although explicit enforcement mechanisms or timelines beyond training expectations were not visible in the provided content.</td>
        <td>UCLA exhibits environmental readiness, driven directly by the U.S. Department of Justice’s April 24, 2026, WCAG 2.1 AA mandate, which the university explicitly cites. The alignment with ADA, UCOP systemwide policy, and forthcoming updates to UC accessibility standards demonstrates strong engagement with external regulatory environments. Campuswide communications (Bruin Post announcements) indicate institutional transparency and stakeholder engagement. The integration of Ally analytics reflects attention to student accessibility needs and responsiveness to compliance pressure. Overall, UCLA is highly aware of the external legal and regulatory landscape and is actively adjusting policies and support structures to meet these requirements.</td>
      </tr>

      <tr>
        <td>University of Michigan–Ann Arbor (UMich)</td>
        <td>UMich is guided by updated ADA Title II requirements and U-M’s SPG 601.20 policy mandating accessible electronic technologies; scope includes public websites, vendor platforms (e.g., MiVideo, Google Workspace), course materials in Canvas, electronic documents, video/multimedia, social media, and mobile apps; technical requirements include headings, lists, alt text, captions, color contrast, and accessible document formatting; supported by remediation and evaluation tools such as Panorama, Grackle, web scanning platforms, expert reviews, and detailed “How to Make It Accessible” guides; structured workflows include the Compliance Roadmap (Learn → Review → Remediate → Monitor & Improve).</td>
        <td>Rooted in institutional policy SPG 601.20 and campus-wide ADA Title II obligations; governance supported by the Digital Accessibility Team, departmental leadership, and roles such as Digital Accessibility Analysts; responsibilities are explicitly shared across all faculty, staff, content developers, program managers, and operational units; extensive training infrastructure includes workshops, drop-in sessions, Panorama training, and “Teaching Accessibility” development programs; processes include structured compliance workflows, expectations for new vs. existing content, and a “Create it, Fix it, Remove it” approach; support services include accessibility tools, expert evaluations, themed guidance pages, and ongoing community engagement through Accessibility Spotlights.</td>
        <td>Federal regulatory drivers (ADA Title II, April 24, 2026 WCAG-aligned mandate) and reinforcement through U-M’s internal SPG policy; institutional emphasis on inclusive teaching, learning, and communication; stakeholder inclusion highlighted through community storytelling (Accessibility Spotlights) and guidance supporting students, instructors, staff, and campus users; recognizes third-party ecosystem responsibilities (Google Workspace, MiVideo, WolverineAccess, Mendeley) and provides evaluations and mitigation tools; transparent communication through public postings, training announcements, and the published Compliance Roadmap clarifying institutional expectations.</td>
      </tr>

      <tr>
        <td>University of North Carolina–Chapel Hill (UNC)</td>
        <td>UNC adopts WCAG 2.1 AA and indicates intent to exceed federal compliance by adopting WCAG 2.2 AA by April 2026. Digital accessibility applies to all websites, mobile apps, LMS content (Canvas), instructional materials, third-party platforms, and internal digital communications. Technical standards cover alt text, captions, document accessibility, assistive technology compatibility, and accessibility-first design principles. The university provides tools and learning resources such as Siteimprove, Microsoft remediation tools, ADA compliance modules, WordPress training, and vendor evaluation resources. Workflows are anchored in a Learn → Audit → Improve model, reinforced with scoring guides, self-paced trainings, prioritization timelines, and risk assessments.</td>
        <td>UNC’s organizational readiness is supported by an institutional ADA Digital Accessibility Compliance Plan, guided by the Digital Accessibility Office (DAO). Governance includes cross-unit leadership and departmental reviews. Responsibilities are shared among campus members (faculty, staff, students) and vendors. Training spans technical remediation, universal design (UDL), inclusive language, procurement, and accessibility justice. Processes include compliance planning, inventories, transformation timelines, remediation strategies, and vendor evaluation checklists. The DAO provides consultations, assessments, and ongoing support.</td>
        <td>Environmental readiness is exceptionally strong, driven by legal mandates (ADA Title II, DOJ 2026 ruling) and a commitment to exceed baseline WCAG 2.1 requirements. UNC’s culture of inclusion centers disability justice and accessibility as a universal benefit. Vendor limitations are addressed through VPAT training, risk scoring, and third-party reviews. Transparency mechanisms include public compliance alerts, webinars, FAQs, open Q&amp;As, and consultative workshops, with ongoing refinement based on campus feedback.</td>
      </tr>

      <tr>
        <td>University of Virginia (UVA)</td>
        <td>UVA adopts WCAG 2.1 AA and expresses a preference for WCAG 2.2 AA for all digital content, including websites, course materials, LMS platforms, mobile apps, student service portals, multimedia, and social media. Technical requirements include captions, transcripts, audio descriptions, accessible PDFs, screen-reader compatibility, keyboard navigation, and accessible social media formatting. Tools and resources support remediation and creation, including VPAT/ACR review support and an Accessible Programs &amp; Events hub. UVA also requires remediation of existing content and ongoing monitoring of third-party platforms.</td>
        <td>UVA has an established internal structure supporting compliance, centered around the Digital Accessibility Coordinator, who oversees VPAT/ACR reviews, evaluates product accessibility, and guides procurement decisions. Responsibilities are distributed across faculty, LMS administrators, event organizers, procurement teams, student service units, and content creators. Organizational processes include procurement checks, monitoring of third-party tools, remediation workflows, and provision of alternate access when immediate remediation is not possible.</td>
        <td>Environmental readiness is strong, driven by explicit acknowledgement of DOJ Title II requirements, WCAG standards (2.1 AA and 2.2 AA), and the April 24, 2026 federal deadline. UVA centers accessibility across programs, services, events, and communications. Vendor constraints are addressed through VPAT/ACR evaluation, contract reviews, and monitoring. Transparency is supported through public guidance pages and visible communication structures.</td>
      </tr>

      <tr>
        <td>University of California San Diego (UCSD)</td>
        <td>UC San Diego demonstrates technological readiness by adopting WCAG 2.1 AA (and anticipating updates under the UC Accessibility Policy), applying requirements to websites, LMS content, mobile apps, maps, media, documents, forms, and social media. Expectations include tagging, headings, alt text, captions, transcripts, audio descriptions, accessible HTML email, and assistive-technology compatibility. Tools and workflows include Siteimprove, CMS/Simple Sites, technical support, and a notice-based remediation process with timelines, suspension warnings, and exceptions for archived or third-party content.</td>
        <td>Organizational readiness is supported by institution-wide standards aligned with ADA Title II and the UC system. Governance is distributed across IT Services, content creators, developers, videographers, procurement teams, faculty, event coordinators, and leadership. Training includes Siteimprove modules, document remediation, accessibility-first design, inclusive language, and event accessibility workshops. Processes include remediation workflows, procurement reviews, scanning workflows, and role-specific compliance guidance supported by consultations and a training hub.</td>
        <td>Environmental readiness is exceptionally strong, grounded in ADA Title II, the DOJ April 24, 2026 mandate, WCAG 2.1 AA requirements, and UC systemwide policies. Stakeholder inclusion includes engagement with student government and community groups. Vendor constraints are addressed via procurement reviews and VPAT/ACR evaluation. Transparency includes public progress updates, escalation procedures, and compliance reporting.</td>
      </tr>

      <tr>
        <td>University of Florida (UF)</td>
        <td>UF demonstrates strong technological readiness for the April 24, 2026 mandate. The EITCA policy requires websites, web applications, and mobile apps to comply with WCAG 2.1 A/AA. UF outlines detailed technical expectations for online classes, emergency communications, Mediasite videos, documents, journals, and Canvas tools, including PDF tagging, heading structure, alt text, color contrast, metadata accuracy, and assistive-technology compatibility. Tools include Siteimprove, SensusAccess, Ally, PAVE, PAC, Recite Me, and UFIT consultations, supported by structured captioning and remediation workflows.</td>
        <td>Organizational readiness is supported by a comprehensive EITCA Policy citing ADA Title II, Section 504, and DOJ amendments. Governance includes compliance and IT leadership and an ADA Coordinator. Responsibilities extend across UF, DSOs, UF Health, faculty, staff, vendors, and journal publishers. Training includes Accessibility Basics, instructor-focused training, Siteimprove training, “Accessibility in 5,” and CITT consultations. Workflows include exception policies, journal accessibility processes, vendor requirements, and centralized support services.</td>
        <td>Environmental readiness is grounded in explicit alignment with ADA Title II, Section 504, DOJ 2024 amendments, and WCAG 2.1 A/AA. Policies emphasize nondiscrimination and accessibility for students, faculty, staff, and journal readers. Vendor expectations are addressed through requirements and exceptions. Transparency is supported through publicly posted policies and centralized accessibility resources.</td>
      </tr>

      <tr>
        <td>The University of Texas–Austin (UT Austin)</td>
        <td>UT Austin demonstrates strong technological readiness under ADA Title II and Texas state laws (TAC 206/213) and internal policy (HOP 3-3014). Coverage includes websites, applications, EIR, software, documents, course materials, videos, and social media. Requirements emphasize captioning, transcription, WCAG-aligned remediation, screen-reader compatibility, and accessible procurement. The Digital Accessibility Center (DAC) provides captioning, remediation, scanning, training, and consultations; DOJ audit recognition supports preparedness.</td>
        <td>UT Austin shows very strong organizational readiness, codified in policy and supported by centralized governance (DAC, Risk &amp; Compliance, committees, cross-unit working groups). Responsibilities extend to faculty, staff, students, web owners, developers, procurement officers, and content creators, with DAC providing oversight. Training programs include workshops for creators and developers, captioning/transcription support, and accessible design training. Processes include procurement integration, policy-driven workflows, and centralized support.</td>
        <td>Environmental readiness is shaped by federal and state regulations and DOJ oversight, with public communication of audit closure. Accessibility requirements are embedded into procurement. Transparency includes public policies, FAQs, audit updates, and guidance from committees and working groups.</td>
      </tr>

      <tr>
        <td>Georgia Institute of Technology (Georgia Tech)</td>
        <td>Georgia Tech’s technological readiness is driven by ADA Title II and WCAG 2.1 AA standards for Canvas sites, course materials, videos, and documents, including LaTeX-generated PDFs and interactive content. Requirements include headings, alt text, captioning, accessible PDFs, tables, color contrast, and assistive-technology compatibility. Tools include Ally, TidyUp, Canvas Accessibility Checker, Kaltura captions, and LaTeX remediation support, reinforced through checklists, workshops, and templates.</td>
        <td>Organizational readiness reflects accessibility as required practice under Title II. Governance involves instructional leaders, official checklists, and workshops (including PDF/LaTeX remediation). Responsibilities extend to instructors, content creators, and departments, supported by training resources, iterative remediation workflows, approved tools, and course templates.</td>
        <td>Environmental readiness is shaped by ADA Title II requirements and WCAG standards, with transparent public guidance, deadline communication, workshop announcements, and clear instructional messaging about expectations.</td>
      </tr>

      <tr>
        <td>University of California, Davis (UC Davis)</td>
        <td>UC Davis demonstrates strong technological readiness under the ADA Title II 2024 rule, requiring WCAG 2.1 A/AA conformance by April 24, 2026. Support includes Siteimprove, SensusAccess, Canvas checkers, and automated captioning (AggieVideo). Technical requirements emphasize structure, accessible documents, media captioning, and inclusive communication. Resources include developer guidelines, prioritization tools, checklists, and LinkedIn Learning modules, supported by content inventories and phased remediation.</td>
        <td>Organizational readiness is supported by ITAPP, campus workgroups, departmental roles, and UC systemwide governance. Responsibilities are defined for faculty, staff, developers, procurement teams, and designers. Capacity building includes workshops, office hours, Canvas and SensusAccess training, systemwide courses, newsletters, maturity frameworks, and accessibility champions.</td>
        <td>Environmental readiness is driven by ADA Title II, WCAG 2.1 AA requirements, Section 508 influences, and UC systemwide mandates. Vendor constraints are addressed through VPAT expectations and approved testing tools. Transparency is supported through public blogs, guidance pages, newsletters, and open office hours.</td>
      </tr>

      <tr>
        <td>University of California, Irvine (UCI)</td>
        <td>UC Irvine shows high technological readiness, requiring WCAG 2.1 AA compliance by April 24, 2026 across Canvas, apps, websites, documents, videos, graphics, syllabi, and communications. Expectations include alt text, headings, descriptive links, contrast, captions/transcripts, accessible PDFs, labeled fields, and structured navigation. Tools include WCAG-aligned WordPress themes, accessibility plugins, SiteImprove scanning, Canvas Accessibility Checker, Kaltura auto-captions, and AI-assisted alt-text tools, supported by remediation clinics and training cycles.</td>
        <td>Organizational readiness is supported by coordinated governance (DASH Team, DTEI, ADA Coordinator, Student Affairs IT, CampusPress). Responsibilities are defined across faculty, content creators, developers, and support units. Capacity building includes workshops, clinics, consultations, developer resources, WordPress training, modules, and a micro-credential program, supported by structured remediation workflows.</td>
        <td>Environmental readiness reflects DOJ Title II mandates and UC system expectations. Accessibility is framed as civil rights and equal opportunity, supported by broad stakeholder engagement, platform integrations, external training partnerships, and consistent public communication about deadlines and responsibilities.</td>
      </tr>

      <tr>
        <td>University of Illinois Urbana–Champaign (UIUC)</td>
        <td>UIUC shows strong technological readiness through explicit WCAG 2.1 AA references across websites, library systems, course materials, multimedia, slides, and documents. CARLI’s ADA Title II Toolkit provides step-by-step training for accessible documents, videos, audio, and websites, supplemented by demos and remediation support from Technology Services and the Lead Accessibility Engineer.</td>
        <td>Organizational readiness includes clear governance and extensive training. Leadership spans the ADA Coordinator, DRES, Office for Access and Equity, and Technology Services, with CARLI as a major capacity-building partner. Responsibilities are distributed across compliance offices, engineers, library/IT staff, and creators. Processes include testing, advisory committees, reporting pathways, and remediation workflows.</td>
        <td>Environmental readiness is driven by ADA Title II (2024), the April 24, 2026 deadline, Section 504, and civil rights structures. Stakeholder inclusion appears through multiple accommodation channels and library-specific emphasis. Transparency includes public accessibility pages, clear reporting pathways, session descriptions, and recordings.</td>
      </tr>

      <tr>
        <td>University of Wisconsin–Madison (UW–Madison)</td>
        <td>UW–Madison demonstrates technological readiness with alignment to ADA Title II (2024) and WCAG 2.2 AA standards across websites, apps, Canvas, materials, videos, documents, and social media. Tools include UDOIT, “Make It Accessible” guides, testing workflows, and detailed technical guidance, supported by structured remediation roadmaps.</td>
        <td>Organizational readiness is very strong, supported by long-standing policy history and updated digital accessibility policy. Governance includes DAUCC, implementation projects, UX, ADA coordination, disability resource offices, liaison networks, and communities of practice. Training and processes for prioritization, remediation, procurement, and phased implementation are well defined.</td>
        <td>Environmental readiness is driven by ADA Title II and long-standing obligations, framed as civil rights and equity. Stakeholder engagement spans students, staff, faculty, designers, and developers. Transparency is supported through roadmaps, timelines, and a centralized accessibility portal.</td>
      </tr>

      <tr>
        <td>University of California, Santa Barbara (UCSB)</td>
        <td>UCSB’s technological readiness is driven primarily by employee-wide training and practical resources aligned with DOJ WCAG 2.1 AA requirements. Guidance covers alt text, captions, accessible meetings, and social media, supported by adaptive technologies and external toolkits. Compared to some peers, UCSB shows less explicit centralized technical policy language.</td>
        <td>Organizational readiness is supported by leadership (ADA Compliance Officer), an advisory committee, DSP adaptive technology team, and student-led accessibility coalition. Training includes a multi-part support series, workshops, and adaptive technology training, with active coordination across units.</td>
        <td>Environmental readiness is shaped by ADA Title II (2024), the 2026 deadline, and UC-wide expectations. Disability justice and inclusion framing are prominent, supported by community partnerships and public guides. Transparency includes complaint pathways and openly shared resources.</td>
      </tr>

      <tr>
        <td>The Ohio State University (OSU)</td>
        <td>OSU shows one of the most structured technical ecosystems, requiring WCAG 2.1 A/AA conformance by April 24, 2026 across websites, apps, LMS content, documents, videos, and emails. Minimum Digital Accessibility Standards, enterprise scanning, LMS tools, and required audits create a formal compliance pipeline supported by clear remediation guidance.</td>
        <td>Organizational readiness is exceptionally strong, with centralized governance (Digital Accessibility Center, services teams, coordinators) and faculty-focused training. Responsibilities are assigned across institutional, unit, staff, faculty, and vendor levels, supported by mandatory training and institutionalized workflows.</td>
        <td>Environmental readiness reflects explicit DOJ deadlines and regulatory pressure. Transparency includes webinars, guidance, and documentation of unit responsibilities. Vendor compliance is enforced through procurement requirements, and audit-ready documentation supports accountability.</td>
      </tr>

      <tr>
        <td>Rutgers University–New Brunswick (Rutgers)</td>
        <td>Rutgers demonstrates technological readiness through WCAG 2.1 AA adoption, enterprise scanning, alternate-format tools, LMS accessibility tools, auto-captioning, and explicit supports for accessible math and STEM content. Detailed checklists and course accessibility planning embed WCAG into workflows.</td>
        <td>Organizational readiness is supported by a revised policy (effective June 2025), robust governance, and clearly mapped responsibilities across faculty, departments, and IT. Training includes Deque University, workshops, and remediation guides, supported by procurement review and audit workflows.</td>
        <td>Environmental readiness is driven by DOJ Title II requirements, ADA/Section 504 obligations, and ongoing policy updates. Consortium connections and public guidance support compliance; transparency includes checklists, policy pages, risk assessment processes, and news updates.</td>
      </tr>

      <tr>
        <td>University of Maryland, College Park (UMD)</td>
        <td>UMD adopts WCAG 2.1 AA across websites, apps, instructional content, documents, and multimedia in alignment with the DOJ rule. Tools include Siteimprove, Equidox, SensusAccess, captioning workflows, and assistive technology licenses. Interim guidelines and structured processes (prioritization, testing, exceptions) demonstrate maturity.</td>
        <td>Organizational readiness is supported by strong policies, leadership messaging, multi-layered governance (DAAC, IT office, ADA coordination, system collaborations), defined roles, and extensive training. Formal processes include procurement review, legacy content rules, and exception pathways.</td>
        <td>Environmental readiness is proactive and transparent, aligned with the DOJ rule and the April 24, 2026 transition. Stakeholder engagement includes senior leadership messaging and a Title II readiness conference. Public resources, timelines, and guidelines reinforce accountability.</td>
      </tr>

      <tr>
        <td>University of Washington (UW)</td>
        <td>UW demonstrates technological readiness through WCAG 2.1 AA adoption and alignment with the DOJ rule across academic, administrative, medical, research, and public-facing systems. Tools include Ally and DubBot, supported by checklists, archived content rules, social media guidance, and multi-phase compliance workflows.</td>
        <td>Organizational readiness is driven by strong governance (initiative, governance board, risk alignment, IT governance) with sponsorship across central offices and shared responsibility across units. Training and support desks reinforce coordination.</td>
        <td>Environmental readiness is strongly aligned with DOJ requirements and includes precise interpretation of legal exceptions. Stakeholder engagement is broad across roles and units. Transparency includes timelines, initiative overviews, resources, and compliance expectations.</td>
      </tr>

      <tr>
        <td>Purdue University (Purdue)</td>
        <td>Purdue demonstrates technological readiness through WCAG 2.1 AA adoption and clear scope covering websites, apps, mobile apps, instructional materials, and third-party technologies. Tools include Siteimprove, assistive technology supports, Microsoft 365 checkers, LMS guidance, and structured implementation initiatives.</td>
        <td>Organizational readiness is grounded in formal standards enforced by civil rights offices and supported by systemwide project teams and instructional innovation units. Responsibilities are clearly defined for instructors, content creators, departmental units, and vendors, supported by robust training and communications.</td>
        <td>Environmental readiness directly cites DOJ Title II requirements and the April 24, 2026 deadline. Accessibility is framed as shared responsibility and civil rights. Transparency includes reporting pathways and clear explanations of obligations, priorities, and preparation activities.</td>
      </tr>

      <tr>
        <td>University of Georgia (UGA)</td>
        <td>UGA demonstrates technological readiness through WCAG 2.1 AA adoption and broad scope across websites, apps, email, documents, video, social media, podcasts, and presentations. Tools include DubBot, PDF accessibility checkers, training courses, and WCAG-aligned templates, supported by extensive platform-specific guidance.</td>
        <td>Organizational readiness is supported by CAES-level governance and an official handbook, with required training and distributed responsibilities across content creators. OIT and the CAES Web Team provide support, training, and oversight.</td>
        <td>Environmental readiness is driven by DOJ Title II requirements, the 2026 deadline, and WCAG standards, reinforced through references to federal sources, broad stakeholder engagement, and public transparency (handbook, expectations, and support channels).</td>
      </tr>
    </tbody>
  </table>
</div>
