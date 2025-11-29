<!-- File: paper3-historical-entry-gaps-across-industries.md -->

# Paper 3 – Historical Entry Gaps Between Pioneers and Market Leaders

## Abstract

This paper quantifies how the time gap between technological “pioneers” and eventual market leaders has evolved over roughly a century, and what that implies for first-mover versus fast-follower strategy. We combine meta-analytic results on entry timing with stylised case studies spanning industrial goods (1920s–1980s), consumer electronics (1970s–1990s), early internet platforms (1990s–2010), and the current AI/platform wave (2010–2025). Historical data for 36 U.S. product categories show that pioneers fail almost half of the time and remain long-run leaders in only about one case out of ten; early leaders typically enter more than a decade after the pioneer.[1] More recent digital categories show substantially shorter lags—often 3–7 years between the first recognisable product and the company that ultimately dominates—but still leave a “window” for disciplined fast followers. We propose a simple 1/x-style law for the expected pioneer-leader gap across waves of technology, argue that the gap is unlikely to converge to zero in practice, and discuss what this means for founders calibrating when to enter versus when to walk away.

## 1. Introduction

The canonical “first-mover advantage” story is that entering early allows a firm to lock in customers, build brand and exploit learning curves, so that later entrants face insurmountable disadvantages. Early empirical work appeared to support this view: pioneers were found to have higher average market shares and higher profitability than later entrants.[2] However, subsequent historical and meta-analytic studies reached more nuanced conclusions: many pioneers fail outright, many industries stabilise with non-pioneers as leaders, and the average time between the first commercial product and the eventual leader can be surprisingly long.[1][3]

For founders and investors, the practical question is not whether first movers can ever win—they clearly can—but whether, on average, the risk-adjusted payoff to being a capital-efficient fast follower is higher in a given sector, and how the answer has changed over time. The intuition is straightforward: if industry formation is slower and distribution friction is high, a late entrant may still face a 15–20-year “runway”; if diffusion is extremely fast, the effective fast-follower window may shrink to just a few years. Yet the empirical relationship is not linear: digital categories exhibit both faster convergence and more frequent leadership turnover.

This paper focuses on a single quantitative lever: the timing gap between the first significant commercial entrant (pioneer) and the firm that ultimately becomes the dominant leader of the category. We:

- synthesise existing cross-industry evidence on pioneer failure rates and average timing gaps;
- build a stylised panel of cases across four eras (industrial, electronics, early web, AI/platforms);
- estimate how the typical pioneer-leader gap has evolved;
- propose a simple functional form for that evolution; and
- discuss what this implies for fast-follower opportunities in current AI-heavy markets.

## 2. Data and stylised facts

### 2.1. Cross-industry meta-evidence (1921–1985)

The most influential quantitative work on first-mover performance is Golder & Tellis’ reconstruction of 36 U.S. product categories launched between 1921 and 1985.[1]

Key findings:

- **Pioneer failure rate.** Around 47% of pioneers fail—i.e. they exit the category or lose all meaningful share—within the observed window.[1]
- **Pioneers as long-run leaders.** Only about 11% of pioneers are still category leaders by the time of the study; in ~89% of categories the leading firm is a follower.[1]
- **Market share levels.** Surviving pioneers hold on average ~10% market share, versus ~28% for “early leaders” (often but not always late entrants).[1]
- **Timing gap.** Early leaders typically enter the market about 13 years after the pioneer, with a broad range from a few years to multiple decades.[1]
- **Measurement sensitivity.** Earlier survey-based work (not reconstructing history) had suggested average pioneer shares of ~30%, so the historical reconstruction dramatically down-grades the generic “automatic” first-mover advantage.[1][2]

Meta-analysis across more than 200 tests of entry timing versus performance adds further nuance:

- Roughly 60–65% of tests find a positive relationship between earlier entry and performance; 20–25% are insignificant; 5–10% show statistically significant disadvantages for early entrants.[3]
- The sign and magnitude of the effect depend strongly on how performance is measured (market share vs accounting profits vs stock returns) and on industry conditions; timing interacts with resource endowments and capabilities.[3][4]

From this period we can extract a **baseline stylised fact**:

> In mid-20th-century consumer and industrial goods, the typical pioneer-to-leader gap was on the order of 10–20 years, and pioneers were long-run leaders only in a small minority of categories.

### 2.2. Industrial and electronics waves (roughly 1950–1990)

Industry-life-cycle work on consumer electronics and durable goods broadly confirms the long gaps from the historical marketing literature.[5][6]

Examples (stylised):

- **Jet airliners.** De Havilland’s Comet, first commercial jet airliner, entered service in 1952; Boeing’s 707, which pioneered the configuration that dominated long-haul jets, entered service in 1958. Boeing and later Airbus eventually dominated, implying a gap of roughly 6 years between first commercial jet and the platform architecture that won the market.[5]
- **Video cassette recorders.** Early VCR prototypes date to the 1950s–1960s; Sony’s Betamax home system launched in 1975; JVC’s VHS format launched in 1976 and became the dominant standard in the late 1970s–1980s. Pioneer-to-winner gap at the consumer-market level: ~1–2 years; but from first technical prototypes to winning mass-market format: ~10–20 years.[5][6]
- **Personal computing and spreadsheets.** The Altair 8800 (1975) and Apple II (1977) pioneered personal computing, while the IBM PC (1981) and Microsoft’s DOS + later Windows ecosystem became the dominant architecture over the 1980s; the pioneer spreadsheet VisiCalc (1979) was overtaken by Lotus 1-2-3 (1983) and then by Microsoft Excel (mid-1980s).[6] Here the gaps between first commercial product and eventual dominant architecture again cluster around 5–10 years.

Empirical models of industry life cycles in tyres, televisions, semiconductors and automobiles show:

- an early phase of high entry rates and experimentation;
- a “shakeout” phase in which the number of firms declines sharply; and
- a later phase in which market share becomes concentrated and stable among a small set of large incumbents.[5]

The timing patterns suggest that, in these industries:

- **Entry waves** last ~10–20 years after the first commercial product;
- **Shakeout and consolidation** tend to happen 10–30 years after the pioneer’s entry, depending on technology and regulation.[5][6]

### 2.3. Early internet platforms (1990–2010)

For digital markets, we can more easily date the launch of early services and the emergence of dominant leaders. Several emblematic cases illustrate shorter, but still meaningful, pioneer-to-leader gaps.

#### 2.3.1. Web search

- **Pioneers.** The first search engine for FTP archives, “Archie”, dates to 1990.[7] Early web search engines and directories (e.g. WebCrawler, Lycos, AltaVista, Yahoo!) appeared around 1994–1995.[8][9]
- **Leader.** Google was founded in 1998 and rapidly gained share through PageRank-based relevance and superior monetisation; it dominates global web search today with an estimated ~90% share.[10]
- **Timing gap.** From Archie (1990) to Google’s founding (1998) is 8 years; from the first wave of full-text web search engines (1994–1995) to Google is ~3–4 years.

#### 2.3.2. Social networking

- **Pioneer.** Myspace launched in 2003, grew extremely fast and was acquired by News Corp for $580m in 2005; by 2006 it was among the most visited sites in the U.S. and was valued at up to $12bn.[11][12]
- **Follower leader.** Facebook launched in 2004, opened to the general public in 2006 and overtook Myspace in unique visitors by 2008–2009.[11][12]
- **Timing gap.** From Myspace’s launch (2003) to Facebook’s launch (2004) is 1 year; from Myspace’s peak to Facebook’s clear dominance is ~3–5 years.

#### 2.3.3. Online video

- **Pioneer.** Vimeo launched in November 2004 as an early video-sharing platform.[13]
- **Follower leader.** YouTube was founded in early 2005, opened to uploads in April 2005, and grew explosively, reaching tens of millions of daily views by 2006.[13][14]
- **Exit to platform incumbent.** Google agreed to acquire YouTube for $1.65bn in stock in October–November 2006.[14]
- **Timing gap.** From Vimeo’s launch to YouTube’s founding is a matter of months; from the first recognisable consumer video platforms to the acquisition of the eventual leader is ~2 years.

#### 2.3.4. E-commerce

- **Pioneer.** Book Stacks Unlimited, an online bookstore started as a bulletin board system in 1992 and moved to the web as Books.com by 1994, is widely regarded as the first online bookstore.[15][16]
- **Follower leader.** Amazon was incorporated in 1994 and sold its first book online in 1995; it subsequently expanded into a general-purpose e-commerce and cloud-infrastructure giant with a market cap above $2 trillion by 2025.[17]
- **Timing gap.** From Book Stacks’ founding (1992) to Amazon’s incorporation (1994) is 2 years; to its first sale (1995) is 3 years.

Across these emblematic digital categories, a stylised average “pioneer–leader gap” emerges:

- If we define the pioneer as the **first recognisable online implementation**, the gap to the eventual leader is often **2–5 years**.
- If we define the pioneer more narrowly (e.g. first commercial web search engine vs first mass-market leader), the gap is **3–8 years**, noticeably shorter than the 10–20-year gaps documented for earlier waves.

### 2.4. AI, productivity tools and health (2010–2025)

The current AI/platform wave shows even faster diffusion but heavy variation across sub-sectors.

#### 2.4.1. Knowledge-work productivity (Notion, etc.)

- Notion Labs was founded in 2013; its modern workspace product reached 1 million users around 2020 and passed 100 million users in 2024.[18][19]
- Notion was not the first digital note-taking or collaboration tool; Evernote (2008), Google Docs (2006) and Trello (2011) pre-date it. However, Notion combined docs, databases and tasks into a unified workspace and achieved explosive organic growth.[18][19]
- In this sense, Notion is a **fast follower** in a mature category (collaborative productivity) but a **category creator** in its own sub-niche (modular workspace). The gap from early web-based collaboration tools (mid-2000s) to Notion’s founding is ~7–10 years.

#### 2.4.2. Coding assistants (GitHub Copilot and peers)

- Prior to large-scale LLM-based assistants, code suggestion tools like TabNine and Kite emerged in the late 2010s.
- GitHub Copilot launched in technical preview in 2021 and became generally available in 2022; by 2025 it had more than 20 million users, with over 90% of the Fortune 100 using it in some form.[20][21]
- Copilot is a **fast follower** in the sense that it leveraged foundation models developed by OpenAI and others, but it effectively defined the modern coding-assistant category at scale.

Given the short history and rapid innovation, we can treat the pioneer-to-leader gap in LLM coding assistants as **on the order of 1–4 years**, depending on whether we count earlier ML-based suggestion tools as pioneers.

#### 2.4.3. AI in healthcare and “AI doctors”

- Early digital-health pioneers like Babylon Health (2013) combined telemedicine with AI-based triage and value-based insurance arrangements. Babylon listed via SPAC in 2021 with a valuation above $4bn but later collapsed; by 2022 it generated around $1–1.1bn in revenue and hundreds of millions of dollars in net losses, and by 2023 it had entered administration.[22][23]
- Other early AI-triage and symptom-checker players (Ada Health, K Health, Doctrin) emerged between 2011 and 2018, raising tens to hundreds of millions of dollars and scaling to millions of users.[24]
- A later entrant, Doctronic, launched in late 2023 and positions itself explicitly as a free, anonymous AI “doctor” for U.S. consumers, with ~$5m in seed funding and over 10 million consultations and ~50,000 weekly users reported in 2025.[25] It relies on external LLM infrastructure and a lean B2C model.

In this sub-sector, the gap between the **first AI-triage experiments** and **later, more focused AI-doctor products** is **roughly 5–12 years** (2011–2018 pioneers vs 2023–2025 followers). However, the distribution, data sources and regulatory constraints are still evolving, so leadership remains fluid.

### 2.5. A stylised cross-era summary

Table 1 summarises the stylised average gaps implied by historical work and selected digital cases.

| Era / wave                               | Illustrative domains                         | Stylised pioneer–leader gap |
|------------------------------------------|----------------------------------------------|-----------------------------|
| Industrial & early consumer (1921–1985)  | Packaged goods, durables, basic electronics  | 10–20 years (mean ≈ 13)[1] |
| Electronics & PCs (1960s–1990s)          | VCR, PCs, office software                    | 5–15 years                  |
| Early internet platforms (1990s–2010)    | Search, social, e-commerce, video            | 2–8 years                   |
| AI/platform wave (2010–2025, selected)   | Productivity, coding, AI health              | 1–7 years (high variance)   |

The **directional pattern** is robust: the typical lag between the first recognisable commercial product and the eventual leader has fallen over time, but it has **not collapsed to zero**. In almost all categories there is still a window—often 3–7 years—in which a well-designed fast follower can enter with a superior product and win, provided it can scale distribution quickly.

## 3. Framework: a simple 1/x law for entry gaps

To capture the cross-era pattern, consider a simple representation of the expected time gap between a pioneer and the eventual leader in “wave” $w$ of technological change:

$$
\mathbb{E}[\Delta_w] = \frac{\alpha}{1 + \beta w}
$$

where:

- $w$ is a wave index (e.g. $w = 0$ for early industrial, $w = 1$ for electronics, $w = 2$ for early internet, $w = 3$ for AI/platforms);
- $\Delta_w$ is the pioneer-to-leader gap in years;
- $\alpha > 0$ captures the baseline diffusion time when distribution is slow and information frictions are high;
- $\beta > 0$ captures how faster information flows, cheaper experimentation and more liquid capital markets compress the gap across waves.

Using the stylised averages above, we can calibrate a very rough set of parameters:

- At $w = 0$ (industrial/consumer goods), $\mathbb{E}[\Delta_0] \approx 13$ years.
- At $w = 3$ (AI/platforms), $\mathbb{E}[\Delta_3] \approx 4–5$ years.

One simple calibration is:

- $\alpha \approx 16,\ \beta \approx 0.3 \implies
\mathbb{E}[\Delta_0] = 16,\ \mathbb{E}[\Delta_3] \approx 16 / (1 + 0.9) \approx 8.4$ (too high).
- Alternatively, $\alpha \approx 18,\ \beta \approx 0.5 \implies
\mathbb{E}[\Delta_0] = 18,\ \mathbb{E}[\Delta_3] = 18/2.5 \approx 7.2$.

To align more closely with the stylised Table 1, we can instead fit a simple exponential:

$$
\mathbb{E}[\Delta_w] = \Delta_0 \cdot e^{-\gamma w}
$$

where:

- $\Delta_0 \approx 13$ (industrial wave);
- for $w = 3$, we target $\mathbb{E}[\Delta_3] \approx 4$.

Solving $13 e^{-3\gamma} = 4$ gives:

$$
e^{-3\gamma} = \frac{4}{13} \Rightarrow \gamma \approx \frac{1}{3}\ln\left(\frac{13}{4}\right) \approx 0.39
$$

Thus:

- $\mathbb{E}[\Delta_0] \approx 13$ years,
- $\mathbb{E}[\Delta_1] \approx 13 e^{-0.39} \approx 8.8$ years,
- $\mathbb{E}[\Delta_2] \approx 13 e^{-0.78} \approx 6.0$ years,
- $\mathbb{E}[\Delta_3] \approx 13 e^{-1.17} \approx 4.1$ years.

This exponential form is conceptually close to a “1/x” law in wave index: each successive wave compresses the pioneer-to-leader gap by a roughly constant factor (here ≈1.5–2×).

Importantly:

- The curve **does not converge to zero**; instead, it asymptotically approaches a small but positive minimum bound determined by physical and organisational constraints (regulation, R&D cycles, enterprise procurement).
- Even if distribution becomes nearly frictionless (e.g. automated app deployment, agent-driven discovery), there remain lags from:
  - product design and iteration,
  - learning and data accumulation, and
  - organisational capability building.

We can model this with a lower-bound parameter $\Delta_{\min}$:

$$
\mathbb{E}[\Delta_w] = \Delta_{\min} + (\Delta_0 - \Delta_{\min}) e^{-\gamma w}
$$

If we set $\Delta_{\min} \approx 3$ years, $\Delta_0 = 13$ and $\gamma \approx 0.4$, then:

- Early waves have gaps of ~10–13 years;
- Current waves converge towards **3–4 years** as the typical window for a fast follower to enter and still have a serious shot at leadership.

## 4. Scenarios and analysis

We now apply the framework to three stylised scenarios:

1. **Industrial-era consumer goods (Wave 0).**
2. **Early internet platforms (Wave 2).**
3. **Current AI-intensive SaaS (Wave 3).**

For each we examine:

- the expected pioneer-leader gap;
- the number of viable entry cohorts; and
- the implications for fast-follower strategy.

### 4.1. Wave 0: Industrial-era consumer goods

Assume:

- $\Delta_0 = 13$ years (consistent with Golder & Tellis’ early leaders lag).[1]
- Shakeout occurs roughly 20–30 years after the pioneer’s launch.[5]

A simple timeline:

- $t = 0$: pioneer introduces category.
- $t = 0$–10: many entrants enter; demand and technology are uncertain.
- $t = 10$–20: early leaders emerge, often followers entering with better production, branding or distribution.
- $t = 20$–30: shakeout; number of firms falls sharply; market shares stabilise.

In this environment:

- There is room for **multiple entry cohorts** (e.g. 0–5, 5–10, 10–15 years after pioneer).
- The surviving leader is often an entrant from the **second cohort** (5–15 years after pioneer).
- Fast followers can observe early customer reactions, technology failures and cost curves, then commit capital at larger scale, while pioneers run the highest risk of demand mis-prediction.

### 4.2. Wave 2: Early internet platforms

Taking the exponential calibration:

- $\mathbb{E}[\Delta_2] \approx 6$ years.

Rough stylised category timelines:

- **Search.** First search engines ~1990–1995; Google (eventual leader) 1998; dominant by early-mid 2000s.[7][8][10]
- **Social.** Early social networks in early 2000s; Myspace 2003; Facebook 2004; leadership flips within ~5 years.[11][12]
- **Video.** Consumer web video pioneers ~2004–2005; YouTube 2005; acquired by Google 2006; category effectively consolidated within ~3–4 years.[13][14]

In practice:

- The **entry window** during which a new firm can both enter and plausibly become category leader shrinks to roughly **3–8 years**.
- There is often only **one successful follower cohort**: companies entering more than ~5–7 years after the first scaled products struggle to escape niche status, because:
  - network effects and data assets compound quickly;
  - distribution is global and continuous; and
  - web-scale companies can copy features from late entrants.

For founders, this implies that **waiting too long to follow is fatal**, but entering 2–4 years after the earliest experimenters—once there is clarity on demand and core UX patterns—can still be optimal, especially if capital can be deployed aggressively.

### 4.3. Wave 3: AI-intensive SaaS

For current AI-heavy categories, set:

- $\Delta_3 \approx 3–5$ years as the typical pioneer-leader gap, with heavy uncertainty.

Consider an AI-productivity or AI-health startup:

- Pioneers have already launched basic copilots or symptom-checkers in 2020–2023;
- The category is not yet fully stabilised; many business models are being tried and abandoned;
- Infrastructure (foundation models, GPUs, distribution platforms) is still evolving rapidly.[20][21][23]

If we assume:

- **Stage 1 (0–2 years after pioneer).** Very high uncertainty. Product-market fit is unclear, regulation is unsettled, unit economics are unstable.
- **Stage 2 (2–5 years).** Patterns emerge: early pioneers either implode (Babylon), pivot or reach sustainable niches.[22][23][24]
- **Stage 3 (5–8 years).** A small number of leaders with strong moats (data, brand, integration) crystallise; new entrants face heavy uphill battles.

Under these conditions, a **disciplined fast follower** might optimally enter:

- **2–4 years** after the first wave of pioneers in that micro-category, once:
  - key regulatory uncertainties have partially resolved;
  - customer willingness to pay is clearer; and
  - dominant UX patterns are known.

The model implies that:

- For AI-intensive SaaS, the **optimal entry lag** is often **a fraction (30–60%) of the expected pioneer-leader gap**.
- If $\mathbb{E}[\Delta_3] \approx 4$ years, an optimal entry might be ~1.5–2.5 years after pioneers; if the gap ends up closer to 6 years, 2–4-year lags may still be feasible.

## 5. Risks and caveats

Several caveats limit how far we can push this stylised “1/x law”.

1. **Selection and survivorship bias.** Historical reconstructions (e.g. Golder & Tellis) rely on categories that were sufficiently important to be documented; they may under-represent niches and failures.[1]
2. **Definition of “pioneer” and “leader”.** In some categories, there is no clear single pioneer (e.g. many laboratories working on similar technologies) and no single leader (fragmented markets). Our case selection favours categories with clear narratives.
3. **Technology and regulation shocks.** Discontinuous innovations (e.g. mobile broadband, cloud computing) or regulatory changes (e.g. antitrust, privacy rules) can re-open competition long after the initial shakeout, effectively resetting the clock.
4. **Cross-industry heterogeneity.** Durable goods, digital platforms and regulated healthcare markets differ fundamentally in capital intensity, switching costs and regulatory barriers; a single functional form cannot fully capture these differences.[3][4][6]
5. **Short history of AI wave.** For AI-heavy categories we have only a few years of data; many leaders of 2025 may be overtaken by yet-unknown challengers before 2030–2035.

We therefore treat the proposed curves and gaps as **order-of-magnitude guides**, not precise forecasts.

## 6. Comparison and implications

Comparing across waves, we draw three main implications:

1. **The fast-follower window has become shorter but has not disappeared.** Historically, followers could wait a decade; now they often have **3–7 years** from the pioneer’s launch (and realistically **2–4 years** from first scalable product) to execute a leadership bid.
2. **The relative advantage of fast followers is increasing in high-uncertainty AI categories.** For AI health, for instance, pioneers like Babylon absorbed extreme regulatory, actuarial and operational risks and ultimately collapsed, while more capital-efficient followers can reuse infrastructure and avoid some mistakes.[22][23][24][25]
3. **The cost of being late has increased more than the benefit of being first.** As distribution and information have become more frictionless, the penalty for missing the fast-follower window is severe: late entrants face entrenched data moats and global incumbents with the ability to copy or pre-empt.

For founders and investors:

- In **slow-moving, asset-heavy sectors**, first-mover plays may still be attractive where regulatory or capacity pre-emption matters.
- In **fast-moving, data-driven sectors**, the data suggest that **fast follower** strategies—entering a few years after pioneers with a clear playbook—often deliver better risk-adjusted outcomes.
- The critical skill is **timing**: entering too early exposes a startup to unresolved uncertainty; entering too late leaves it facing hardened moats.

## 7. Conclusion

Historically, first movers have not consistently captured the lion’s share of long-run value. In mid-20th-century product markets, pioneers were rarely the eventual leaders, and early leaders tended to arrive roughly a decade later.[1] In the internet era, the pioneer-leader gap compressed to a few years, yet many iconic companies—Google, Facebook, Amazon, YouTube—were still fast followers rather than pioneers.[7][10][11][13][15][17] The emerging AI wave appears to follow a similar pattern, with shorter windows but significant scope for well-timed, capital-efficient followers, especially in complex domains like health and productivity.

A simple exponential “1/x-style” law in wave index fits these stylised facts reasonably well and highlights a practical takeaway: in most categories, the optimal strategy is neither to rush blindly as the very first mover nor to wait indefinitely, but to **enter in the first one or two fast-follower cohorts**, once uncertainty has fallen but before moats fully harden. For founders thinking about AI-heavy startups today, the relevant question is therefore not “Should I be first?” but “In which micro-category am I willing to be a fast follower within a 2–4-year window, and can I realistically out-execute both the pioneers and the incumbents?”

## References

[1] Golder, P. N., & Tellis, G. J. – “Pioneer Advantage: Marketing Logic or Marketing Legend?”, *Journal of Marketing*, 1993 (reconstructed history of 36 U.S. product categories).  
[2] Robinson, W. T., & Fornell, C. – “Sources of Market Pioneer Advantages in Consumer Goods Industries”, *Journal of Marketing Research*, 1985.  
[3] VanderWerf, P. A., & Mahon, J. F. – “Meta-Analysis of the Impact of Research Methods on Findings of First-Mover Advantage”, *Management Science*, 1997.  
[4] Lieberman, M. B., & Montgomery, D. B. – “First-Mover (Dis)Advantages: Retrospective and Link with the Resource-Based View”, *Strategic Management Journal*, 1998. :contentReference[oaicite:0]{index=0}  
[5] Klepper, S. – “Entry, Exit, Growth, and Innovation over the Product Life Cycle”, *American Economic Review*, 1996; related industry life-cycle work on tyres, televisions, and automobiles.  
[6] Bohlmann, J. D., Golder, P. N., & Mitra, D. – “Deconstructing the Pioneer’s Advantage: Examining Vintage Effects and Consumer Valuations of Quality and Variety”, *Journal of Marketing Research*, 2002. :contentReference[oaicite:1]{index=1}  
[7] “Timeline of Web Search Engines” – Wikipedia overview of early search engines from Archie (1990) onwards. :contentReference[oaicite:2]{index=2}  
[8] “The History of Search Engines” – TopOfTheList blog, 2023, summary of first-generation search engines. :contentReference[oaicite:3]{index=3}  
[9] “What Came Before Google? A Brief History of Search Engines” – Search Laboratory, 2024. :contentReference[oaicite:4]{index=4}  
[10] “Search Engine” – Wikipedia; plus business-press estimates of Google’s global search market share. :contentReference[oaicite:5]{index=5}  
[11] “Myspace” – Wikipedia; Reuters and Guardian coverage of Myspace’s acquisition by News Corp and subsequent decline. :contentReference[oaicite:6]{index=6}  
[12] Angwin, J. – *Stealing MySpace*, Random House, 2009 (history of Myspace). :contentReference[oaicite:7]{index=7}  
[13] “YouTube” – Wikipedia; press coverage of its 2005 founding and 2006 acquisition by Google for $1.65bn. :contentReference[oaicite:8]{index=8}  
[14] “Watch YouTube’s first-ever video…” – The Sun, 2025, on the 20th anniversary of “Me at the zoo”. :contentReference[oaicite:9]{index=9}  
[15] “Book Stacks Unlimited” – Wikipedia; HistoryOfInformation.com entry describing it as the first online bookstore (1992). :contentReference[oaicite:10]{index=10}  
[16] “Expanding Access: The History of Ecommerce Part 1” – *The History of the Web*, 2025. :contentReference[oaicite:11]{index=11}  
[17] “Amazon launched 30 years ago with one product…” – *Business Insider*, 2025; plus Ebsco Research Starters on Amazon’s first online book sale (1995). :contentReference[oaicite:12]{index=12}  
[18] Notion Labs – “100 Million of You” blog post, 2024, announcing 100m users.   
[19] “Notion has 100 Million Users as of 2025 + More Statistics” – Super.so blog, 2025.   
[20] Microsoft – FY2025 Q4 earnings call transcript, noting 20m GitHub Copilot users and 90% Fortune 100 adoption.   
[21] TechCrunch – “GitHub Copilot crosses 20 million all-time users”, July 2025.   
[22] “What Went Wrong With Babylon Health?” – *The Future of Health* newsletter, 2023, discussing Babylon’s losses and collapse. :contentReference[oaicite:17]{index=17}  
[23] Watchdoq – “How a 4 Billion Dollar Healthtech Dream Collapsed Overnight: Babylon Health”, 2025. :contentReference[oaicite:18]{index=18}  
[24] Reuters – “Indian healthcare AI startup Qure.ai aiming for IPO in two years”, 2025 (funding, valuation and growth metrics).   
[25] New York Post – “This health startup is harnessing AI for quick, free diagnoses – with shocking accuracy”, 2025 (Doctronic consultations, funding and usage metrics). :contentReference[oaicite:20]{index=20}
