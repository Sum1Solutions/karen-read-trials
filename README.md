# The Right Side of Wrong: Bayes' Theorem in Action
## The Karen Read Case

This project is an open-source initiative to document and analyze the evidence and arguments presented to the jury in both the first Karen Read trial (2024) and the retrial (2025) through the lens of Bayesian reasoning.

## Analysis Approach

This project maintains a juror's perspective by focusing on evidence and testimony formally presented in court. Key aspects of our approach:

- **Evidence-Based Analysis**: All evaluations are grounded in testimony and exhibits admitted during trial
- **Trial-Specific Context**: Notes differences in evidence presentation between the first trial and retrial
- **Neutral Stance**: Presents competing interpretations without editorializing
- **Transparent Sourcing**: All facts are linked to trial testimony or official court documents

## Current Status (June 2025)

**Current Trial Status:** Jury deliberations began on June 13, 2025, after 31 total trial days. The prosecution presented its case over 23 days (38 witnesses), and the defense presented its case over 8 days (11 witnesses).

**Key Developments:**
- Defense presented crash reconstruction and forensic evidence challenging the prosecution's narrative
- Both sides delivered closing arguments on June 12, 2025
- Jury is currently deliberating on charges of second-degree murder, manslaughter, and leaving the scene

**Site Features:**
- **Evidence Comparison Table:** 19 key facts comparing prosecution vs defense arguments across both trials.
- **Daily Trial Timeline:** Comprehensive day-by-day breakdown of all 31 trial days (April 22 - June 13, 2025).
- **Enhanced Bayesian Analyzer:** An interactive tool to explore how evidence impacts belief, featuring:
  - Detailed reasoning for each piece of evidence
  - Default likelihood values based on evidential strength
  - Clear probability indicators (P(Evidence | H1) and P(Evidence | H2))
  - Visual representation of how each fact affects the overall probability
  - Collapsible explanations of Bayesian logic and mathematics
- **Updated References:** 30+ key reference pages from major news outlets and court coverage (see Links & References page).

## Project Features

### 1. **Comprehensive Evidence Analysis**
- **Main Evidence Table:** Side-by-side comparison of how each key fact was presented by prosecution and defense in both the 2024 trial and 2025 retrial
- **19 Key Evidence Items:** From the discovery of John O'Keefe's body to the final expert testimony
- **Cross-Referenced:** Each evidence item linked to original sources and news coverage

### 2. **Daily Trial Timeline**
- **Complete Day-by-Day Coverage:** Every trial day from opening statements to prosecution rest
- **Witness Details:** Who testified, what they said, and key points from each day
- **Prosecution vs Defense:** Daily breakdown of competing arguments and strategies
- **Evidence Correlation:** Each day linked to relevant facts in the main evidence table

### 3. **Enhanced Source Documentation**
- **30+ Key Reference Pages:** Curated links to Court TV, CNN, Boston Globe, WCVB, Fox News, and other major outlets (see Links & References page for full list)
- **Retrial-Specific Coverage:** Sources covering unique developments in the 2025 retrial
- **Timeline Tracking:** Key dates, witness counts, and trial phases documented

## How We Built It

### **Research & Data Collection**
- **AI-Assisted Analysis:** This project utilizes AI language models to synthesize and organize information while maintaining strict adherence to factual reporting
- **Web Search & Analysis:** Comprehensive search of major news outlets for daily trial coverage
- **Source Verification:** Cross-referenced multiple sources for accuracy

### **Technical Implementation**
- **Static HTML Site:** Clean, fast-loading pages optimized for mobile and desktop
- **Responsive Tables:** Custom CSS for readable tables across all device sizes
- **Cross-Linking:** Internal navigation between evidence table and daily timeline
- **Accessibility:** Proper semantic HTML and mobile-responsive design
- **AI-Assisted Analysis:** This project utilizes AI language models (Claude and ChatGPT) to help synthesize and organize complex trial information while maintaining strict adherence to factual reporting

### **Content Organization**
- **Evidence Synthesis:** Combined information from 38 witnesses and 23 days of testimony
- **Fact Correlation:** Each daily timeline entry references specific evidence table items
- **Balanced Presentation:** Equal space given to prosecution and defense arguments

## Project Purpose

- **Transparency:** Present the facts, exhibits, and legal arguments as they were known to the jury, with references to original sources and media coverage.
- **Comparison:** Allow side-by-side review of prosecution and defense narratives across both trials, highlighting how the evidence and arguments evolved.
- **Accessibility:** Make complex trial information readable and navigable for all audiences, including those on mobile devices.
- **Public Interest:** Support informed discussion and reporting by providing a single, well-organized resource with links to all major news and official sources.

## Key Retrial Developments Documented

### **Major Changes from First Trial:**
- **Key Difference in Retrial:** Michael Proctor did not testify in person; his prior testimony was read into the record
- **Enhanced Expert Testimony:** New crash reconstruction and digital forensics analysis
- **Expanded Defense Case:** "More robust" defense strategy with additional witnesses
- **New Evidence:** Rice-sized plastic debris, SUV scuff mark analysis, timeline discrepancies

### **Trial Timeline Captured:**
- **Jury Selection:** April 1-15, 2025 (18 jurors selected)
- **Prosecution Case:** April 22 - May 30, 2025 (38 witnesses, 23 days)
- **Defense Case:** Began May 30, 2025 with crash expert DiSogra
- **Key Witnesses:** Jennifer McCabe (3 days), Dr. Judson Welcher, Shanon Burgess

## Getting Started

### Local Development

1. Clone this repository:
   ```bash
   git clone https://github.com/Sum1Solutions/karen-read-trials.git
   cd karen-read-trials
   ```

2. Open the site in your browser:
   - Simply open `index.html` in any modern web browser
   - Or use a local server (e.g., `python3 -m http.server 8000`)

### For Contributors

We welcome contributions to enhance this project! Here's how you can help:

1. **Fork** the repository
2. Create a new branch for your feature/fix
3. Make your changes
4. Submit a pull request

Areas where we'd love contributions:
- Improving the Bayesian analysis model
- Adding new evidence or analysis
- Enhancing the UI/UX
- Fixing bugs or inaccuracies

### Customizing Your Analysis

This project allows you to adjust your own opinions and see how they affect the Bayesian probability calculations. The interactive Bayesian Analyzer lets you:

- Adjust the weight you give to each piece of evidence
- See how different interpretations affect the overall probability
- Save your custom analysis (coming soon)

To modify the analysis:
1. Open `index.html` in your browser
2. Navigate to the Bayesian Analyzer section
3. Use the sliders to adjust your confidence in each piece of evidence
4. Observe how the final probability changes based on your inputs

Your analysis is private and runs entirely in your browser - no data is sent to any server.

## Site Architecture

```
├── index.html          # Main evidence table + daily timeline
├── links.html          # Comprehensive source links & references  
├── style.css           # Responsive styling for all tables
└── README.md           # This documentation
```

---

## Reference Link Audit Log (Dead/Outdated Links)

This section tracks dead or outdated reference links that have been replaced or removed, to ensure ongoing transparency and historical traceability. Please update this list as new dead links are found and replaced.

| Date Found | Original URL | Supported Fact/Topic | Replacement/Notes |
|------------|-------------|----------------------|-------------------|
| 2025-06-01 | https://www.wcvb.com/article/karen-read-trial-apple-health-data/43123456 | Apple Health data, digital evidence | Replaced with https://particle.news/story/karen-read-retrial-highlights-key-testimony-and-forensic-evidence |
| 2025-06-01 | https://www.courttv.com/news/karen-read-trial-peggy-okeefe-testimony/ | Peggy O’Keefe testimony | Replaced with https://particle.news/story/karen-read-retrial-highlights-conflicting-testimonies-and-emotional-testimony-from-victims-mother |
| 2025-06-01 | https://www.boston.com/news/local-news/2024/11/12/karen-read-bac-analysis/ | BAC analysis & forensic testimony | Replaced with https://rigth.news/karen-read-trial-star-witness-testimony-key-updates/ |
| 2025-06-01 | https://nypost.com/2024/12/05/karen-read-trial-video-timestamp-error/ | Video timestamp error | Replaced with https://time.news/karen-read-trial-day-15-live-updates/ |
| 2025-06-01 | https://www.masslive.com/news/2025/05/karen-read-trial-jealous-rage-calls.html | “Jealous rage” calls/voicemail evidence | No direct replacement found yet (search ongoing) |

## Technical Details

**Built With:** HTML5, CSS3, AI-assisted analysis
**AI Assistants:** Claude and ChatGPT for content synthesis and organization
**Optimized For:** Mobile-first responsive design
**Sources:** 30+ verified news outlets and court coverage
**Updated:** June 17, 2025 (through start of jury deliberations)

## Contributing

This is an open-source project. Contributions are welcome for:
- Updated trial information as the defense case proceeds
- Additional verified source links
- Technical improvements to the site structure
- Corrections or clarifications to existing content


## AI Assistance Disclosure

This project utilizes AI language models, including OpenAI's ChatGPT, Anthropic's Claude, X.com's Grok, Windsurf IDE, and other AI tools to assist with:
- Synthesizing and organizing complex trial information
- Maintaining consistent formatting and cross-referencing
- Ensuring comprehensive coverage of trial developments
- Generating and organizing content for the README.md file
- Generating and organizing content for the bayesian analyzer.

This project is not affiliated with the court or any party. For educational and informational use only. This information may be incomplete or incorrect. It is not intended to be used as a substitute for anything other than thinking deeply about how perspective affects our understanding of events (Perspective = Reality. See https://www.youtube.com/@sum1namedjon for more information)
