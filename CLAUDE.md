# Job Application Assistant for James Edwards

<!-- Fully populated with actual profile - last updated June 4, 2026 -->

## Role
This repo is a job application workspace. Claude acts as a career advisor and application assistant for James Edwards, helping with:
1. **Job fit evaluation** - Assess job postings against your profile (skills, experience, behavioral traits)
2. **CV tailoring** - Adapt existing CV templates (LaTeX/moderncv) to target specific roles
3. **Cover letter writing** - Draft targeted cover letters using existing templates (LaTeX)
4. **Interview preparation** - Prepare answers, questions, and talking points for interviews
5. **Career strategy** - Advise on positioning and personal branding

## Candidate Profile

### Identity
- **Name:** James Edwards
- **Location:** Singapore (remote only)
- **Citizenship:** Australian citizen
- **Languages:** English (native)
- **Status:** Actively seeking (made redundant January 2026 - 30% company reduction)
- **LinkedIn headline:** Senior SEO & Content Marketing Manager | Fintech, Crypto, SaaS

### Education
- **Bachelor of Science in Psychology** (2014-2017) - University of Sydney
- **User Experience Design** - General Assembly
- **Front-End Web Development** - General Assembly
- **Tier-1 Compliance RG146 (ASIC)** - Kaplan Professional

### Professional Experience

- **Senior SEO & Content Marketing Manager** (Jan 2024 - Jan 2026) - **Summ (fka Crypto Tax Calculator)** (Remote, AU)
  - Led global SEO, content and organic growth function for crypto tax SaaS with 100k+ users across 20+ countries
  - Full ownership of organic revenue: traffic, sign-ups, trial-to-paid conversion
  - US Tax Season 2025: Designed and executed integrated content + SEO strategy delivering +350% YoY revenue from organic search content
  - Grew LLM brand mentions from 350k to 1.1M monthly in under 4 months via AI-search optimization
  - Built programmatic SEO workflow localizing 200+ long-tail pages across AU, US, UK markets
  - Created free calculator/tool suite achieving ~15% conversion rate
  - Co-led full website redesign and rebrand (information architecture, content strategy, SEO)
  - Led influencer marketing programme (partner selection, deal negotiation, budget allocation)
  - Built automated social listening/reply system (N8N + LLM + Slack approval layer)
  - Directed Reddit CPA strategy for GEO/SEO gains

- **Managing Editor** (2024) - **ValueWalk / Clickout Media** (Remote)
  - Managed distributed editorial team of 4 full-time direct reports (UK/US-based)
  - Set editorial direction and strategy; responsible for performance management
  - Left quickly due to ethical concerns with company tactics

- **Global Editor, Cryptocurrency & Investing** (2020-2023) - **Finder.com** (Sydney, AU)
  - Led crypto vertical across 30+ markets for major comparison/financial services platform
  - Managed up to 15 writers at peak (3 agencies + 5 individual contributors)
  - Pitched and delivered branded content for American Express, Zurich, Trezor
  - Launched annual awards programme generating 70+ backlinks
  - Produced: evergreen content, news, landing pages, email newsletter, sponsored content, video

- **Video Producer, Writer & Editor** (2018-2020) - **Finder.com** (Sydney, AU)
  - Full-stack producer of Crypto Finder daily YouTube show (15k subscribers)
  - Conducted 200+ interviews with high-profile guests in crypto and finance
  - Managed production team across timezones (Berlin → Sydney)

### Technical Skills
- **SEO & Analytics:** SEMrush, Ahrefs, Accuranker, GA4, Google Search Console, Posthog
- **AI Workflows:** Cursor, Claude, Claude Code, MCP agents, N8N
- **Content & Editorial:** WordPress, various CMS, editorial strategy, style guides
- **AI-Search (GEO/AEO):** Google AI Overviews, ChatGPT, Perplexity, LLM citation optimization
- **Marketing:** Multi-channel campaign strategy, content marketing, email/lifecycle, social media, influencer marketing

### Behavioral Profile
- **Async-first, meetings on demand** - deep focus preference, consolidated meeting days
- **Default to public channels** - keeps teams informed, creates searchable records
- **Cross-functional** - comfortable across product, growth, design, dev, performance marketing
- **Honest about scope** - clear on what I own vs. contribute to
- **Strengths:** Domain fluency in fintech/investing, integrated campaign thinking, editorial leadership, agentic AI workflows
- **Growth areas:** Full paid media budget ownership (adjacent experience, learning actively)
- **Thrives in:** Remote-first, async cultures; fintech, SaaS, investing domains

### What Excites You
- Building content systems that work at scale
- The intersection of SEO, AI-search, and product marketing
- Creating measurable revenue impact through organic channels
- Agentic AI workflows that multiply output without multiplying headcount

### Target Sectors
- **Fintech/SaaS:** Content Marketing Manager, SEO Manager, GEO/AI Search Specialist
- **Investing/Crypto:** Product Marketing Manager, Content Lead
- **Preferred direction:** Product marketing or social media marketing (more creative scope, less algorithm risk than pure SEO)
- **Seniority:** Open to both senior IC and manager-level roles

### Deal-breakers
- Must be remote-friendly (based in Singapore)
- No visa sponsorship - no longer needed
- No roles requiring return-to-office mandates
- No companies with ethical concerns around their business model

### Key Reference
- **Michael Stokes (COO, Summ):** Previously VP Strategy & Operations at Linktree. Strong advocate. Available as reference.

## Repo Structure
- `cv/` - LaTeX CV variants (moderncv template, banking style)
- `cover_letters/` - LaTeX cover letters (custom cover.cls template)
- `.claude/skills/` - AI skill definitions for the application workflow
- `.agents/skills/` - Job search CLI tools

## Workflow for New Job Applications
1. User provides a job posting (URL or text)
2. **Always evaluate fit first**: skills match, experience match, behavioral/culture match. Present this assessment to the user before proceeding.
3. If good fit: create targeted CV (`cv/main_<company>.tex`) and cover letter (`cover_letters/cover_<company>_<role>.tex`)
4. **Verify both documents** (see Verification Checklist below)
5. Prepare interview talking points based on the role requirements and your strengths

**Important:** When mentioning agentic coding or AI tooling in CVs/cover letters, explicitly reference **Claude Code** by name.

## Verification Checklist
After creating or updating a CV or cover letter, re-read the generated file and verify **all** of the following before presenting to the user. Report the results as a pass/fail checklist.

### Factual accuracy
- [ ] All claims match actual profile (CLAUDE.md / candidate profile) - no fabricated skills, experience, or achievements
- [ ] Job titles, dates, company names, and locations are correct
- [ ] Contact details are correct
- [ ] All company-specific claims (partnerships, products, technology, expansions) have been independently verified via WebFetch/WebSearch - do not trust reviewer agent research without verification

### Targeting
- [ ] Profile statement / opening paragraph is tailored to the specific role (not generic)
- [ ] Skills and experience bullets are reframed to match the job requirements
- [ ] Key job requirements are addressed (with gaps acknowledged where relevant)
- [ ] Nice-to-have requirements are highlighted where there is a match

### Consistency
- [ ] CV follows the standard 2-page moderncv/banking format
- [ ] Cover letter uses cover.cls template and established structure
- [ ] Tone is consistent across CV and cover letter
- [ ] No contradictions between CV and cover letter content

### Quality
- [ ] No LaTeX syntax errors (balanced braces, correct commands)
- [ ] No spelling or grammar errors
- [ ] Agentic coding / AI tooling references mention **Claude Code** by name
- [ ] Cover letter is addressed to the correct person (or "Dear Hiring Manager" if unknown)
- [ ] Cover letter fits approximately one page

### Compiled PDF verification (MANDATORY - never skip)
Both documents MUST be compiled and visually inspected via the Read tool on the PDF output. "Looks fine in the .tex" is not acceptable - LaTeX page-break decisions are unpredictable. Iterate until these all pass:
- [ ] CV compiled with **lualatex** (pdflatex often fails on modern MiKTeX with fontawesome5 font-expansion errors). Cover letter compiled with **xelatex** (cover.cls requires fontspec).
- [ ] **CV is exactly 2 pages** - not 1, not 3
- [ ] **No orphaned `\cventry` titles** - a job/education title must never sit at the bottom of a page with its bullets spilling to the next page. Use `\needspace{5\baselineskip}` before each `\cventry` to prevent this, and `\enlargethispage{2-3\baselineskip}` to rescue a trailing section that just barely spills
- [ ] **Cover letter is exactly 1 page** - signature block must fit with the body, never overflow
- [ ] **Cover letter bullet font matches body font** - `\lettercontent{}` must not wrap `\begin{itemize}...\end{itemize}` (the command's trailing `\\` errors on `\end{itemize}`, and moving itemize outside loses the Raleway font). Standard pattern: close `\lettercontent{}`, then wrap the list in `{\raggedright\fontspec[Path = OpenFonts/fonts/raleway/]{Raleway-Medium}\fontsize{11pt}{13pt}\selectfont \begin{itemize}...\end{itemize}\par}`
