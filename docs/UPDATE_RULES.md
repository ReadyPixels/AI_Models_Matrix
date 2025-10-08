# 📋 Update Rules & Guidelines

> **Document Version:** 1.1  
> **Last Updated:** October 7, 2025  
> **Purpose:** Guidelines for maintaining and updating the Awesome AI Models Matrix

---

## 🎯 Core Principles

### 1. **Accuracy First** ✅
- All information MUST be verified from official sources
- No speculation or rumors
- Include verification date in changelog

### 2. **No Duplicates** 🚫
- Check existing entries before adding new models
- Same model with different versions = UPDATE, not new entry
- Use "Latest Updated" column to track version changes

### 3. **Awesome List Standards** ⭐
- Follow [awesome-list guidelines](https://github.com/sindresorhus/awesome/blob/main/pull_request_template.md)
- Include emojis for visual clarity
- Maintain consistent formatting
- Sort tables logically (latest first by default)

### 4. **User-Friendly** 👥
- Provide multiple sorting options (date, company, price, self-hosting)
- Use emojis to improve scannability
- Include direct links to official resources
- Clear categorization

---

## 📊 Table Structure & Sorting

### Main Comparison Table Columns

**Required Columns:**
1. 🏢 **Company** - Organization name with flag emoji if applicable
2. 🤖 **Model** - Model name
3. 📦 **Version** - Version identifier
4. 📅 **Release Date** - Initial release (YYYY-MM-DD format)
5. 🔄 **Latest Updated** - Most recent update (YYYY-MM-DD format) ⭐ PRIMARY SORT
6. 💻 **Coding** - Coding capability (✅ Excellent/Good/Basic)
7. 📊 **Benchmarks** - HumanEval / MMLU scores
8. 💰 **Price** - Input/output costs per 1M tokens (USD)
9. 🖥️ **Self-Host** - Yes (✅) or No (❌) with license
10. 🌟 **Usage Rank** - Real-world usage rank from OpenRouter (optional)
11. 🔗 **Official Site** - Direct link with 🔗 emoji

### Sorting Options Required

**1. Sort by Latest Update (Default)**
- Models with most recent updates appear FIRST
- Mark recently updated with ⭐ indicator
- Format: `2025-09-30 ⭐` for updates in last 30 days

**2. Sort by Company**
- Group all models by company
- Alphabetical order by company name
- Use company emoji consistently (🤖 OpenAI, 🔬 DeepSeek, 🇨🇳 Chinese companies)

**3. Sort by Self-Hosting**
- Two sections: ✅ Self-Hostable and ❌ API-Only
- Within each section, sort by license type
- Show pricing even for self-hostable (API option)

**4. Sort by Price**
- Free models (🆓) first
- Then by ascending cost
- Separate section for "Varies" pricing

---

## 🆕 Adding New Models

### Pre-Addition Checklist

- [ ] Verify model is officially released (not just announced)
- [ ] Confirm it's not already in the list
- [ ] Gather official documentation links
- [ ] Verify benchmarks from authoritative sources
- [ ] Check pricing from official documentation
- [ ] Determine license/self-hosting status
- [ ] Identify appropriate emojis for company

### Required Information

**Mandatory Fields:**
1. Model name and version
2. Company/organization
3. Release date (YYYY-MM-DD)
4. Pricing OR "Free" OR "Varies"
5. Self-hosting status and license
6. Official website link

**Highly Recommended:**
1. HumanEval and/or MMLU scores
2. Coding capability assessment
3. Context window size
4. Parameter count
5. Special features

### Where to Add

1. **Main Table** - Add to "Sort by Latest Update" (top if newest)
2. **Company Section** - Add to appropriate company group
3. **Category Sections** - Add to relevant categories:
   - 🏆 Frontier Models
   - 🧠 Reasoning Models
   - 🆓 Open-Source Models
   - 💻 Coding-Specialized Models
   - 🎨 Multimodal Models
   - 🏢 Enterprise Models
4. **Latest Updates Section** - If released in last 30 days
5. **Official Resources** - Add company if new

---

## 🔄 Updating Existing Models

### When to Update "Latest Updated" Date

**Update when:**
- ✅ New version released (e.g., V3.1 → V3.2)
- ✅ Significant architecture change
- ✅ Major capability improvement
- ✅ Pricing changes
- ✅ License changes
- ✅ Benchmark scores updated

**Don't update for:**
- ❌ Minor bug fixes
- ❌ Documentation updates only
- ❌ No material changes to model

### Update Process

1. **Locate all instances** - Model appears in multiple tables
2. **Update "Latest Updated" column** - Change to new date
3. **Update changed fields** - Version, price, benchmarks, etc.
4. **Add to "Latest Updates"** - If significant change
5. **Update CHANGELOG.md** - Document what changed
6. **Verify consistency** - Same data across all tables

---

## 🎨 Emoji Guidelines

### Company/Organization Emojis

- 🤖 **OpenAI** - Robot face (13.8% market share)
- 🤖 **Anthropic** - Robot face (13.6% market share)
- 🌐 **Google DeepMind** - Globe (18.9% market share)
- 🚀 **xAI** - Rocket (26.8% market share - #1)
- 🔬 **DeepSeek** - Microscope
- 🇨🇳 **Alibaba/Qwen** - China flag + Alibaba
- 🇨🇳 **Zhipu AI** - China flag
- 🌙 **Moonshot AI** - Crescent moon
- 🦙 **Meta** - Llama emoji
- 💻 **Mistral AI** - Computer
- 🏢 **IBM** - Office building
- 🪶 **Microsoft** - Feather (Phi)
- 🇪🇺 **Tilde AI** - EU flag

### Status Emojis

- ✅ **Yes/Good** - Check mark
- ❌ **No** - Cross mark
- 🆓 **Free** - Free badge
- ⭐ **Recently Updated** - Star
- 🔗 **Link** - Link symbol
- 💰 **Pricing** - Money bag
- 📊 **Benchmarks** - Chart
- 🖥️ **Self-Host** - Desktop computer
- 💻 **Coding** - Laptop

### Feature Emojis

- 🧠 **Reasoning** - Brain
- 🎨 **Multimodal** - Art palette
- 🏆 **Best/Leader** - Trophy
- ⚡ **Fast** - Lightning
- 📖 **Long Context** - Open book
- 🔒 **Privacy/Security** - Lock
- 🌍 **Multilingual** - Globe

---

## 📝 Formatting Standards

### Dates

- **Format:** YYYY-MM-DD (e.g., 2025-10-30)
- **Partial dates:** YYYY-MM if day unknown, YYYY if month unknown
- **Range:** Use "2025-Q1" for quarters if specific date unavailable

### Pricing

- **Format:** `$X.XX / $X.XX` (input/output per 1M tokens)
- **Free:** Use `🆓 Free` with emoji
- **Varies:** Use `Varies` with explanation in notes
- **API Only:** Specify if no self-hosting option

### Benchmarks

- **Format:** `XX% / XX%` (HumanEval / MMLU)
- **Approximation:** Use `~XX%` for estimated values
- **Unavailable:** Use `N/A` or leave blank with note

### Links

- **Format:** `[🔗](https://url)` - Just link emoji in tables
- **Full format:** `[openai.com](https://openai.com)` in text
- **Verify:** All links must work (test before committing)

### Model Names

- **Official names** - Use exact official name
- **Version** - Include in separate column
- **Consistency** - Same name across all tables

---

## 🔍 Verification Sources

### Acceptable Sources (Priority Order)

1. ✅ **Official company websites**
2. ✅ **Official documentation/API docs**
3. ✅ **Official GitHub repositories**
4. ✅ **Company press releases**
5. ✅ **Model cards on Hugging Face** (from official orgs)
6. ✅ **Academic papers** (from model creators)
7. ✅ **Major tech news** (TechCrunch, The Verge, etc.)
8. ✅ **Wikipedia** (as secondary verification)

### Unacceptable Sources

- ❌ Social media posts (unless official company accounts)
- ❌ Personal blogs without verification
- ❌ Reddit/forum discussions
- ❌ Unverified third-party sites
- ❌ Speculation or rumors

### Verification Tools

- **Brave Search** - Latest information with freshness filter
- **OpenRouter.ai** - Real-world usage statistics and rankings
- **LLM-Stats.com** - Live benchmarks and performance data
- **Official APIs** - Test pricing and availability
- **Hugging Face** - Model cards and official repos
- **GitHub** - Official repositories
- **arXiv** - Academic papers

---

## 📅 Update Schedule

### Regular Updates

- **Monthly** - Comprehensive review of all models (1st of month)
- **Weekly** - Check for major new releases
- **Daily** - Monitor major company announcements

### When to Add Immediately

- 🚨 New model from major company (OpenAI, Anthropic, Google, etc.)
- 🚨 Significant open-source release (new GPT-OSS, Llama, etc.)
- 🚨 Breakthrough pricing changes (>50% change)
- 🚨 Major capability improvements

### Changelog Requirements

**Every update MUST include:**
1. Date of update
2. What was changed (new model, price update, etc.)
3. Source of information
4. Version number increment

---

## 🚫 Common Mistakes to Avoid

### ❌ DON'T

1. **Don't add unreleased models** - Wait for official release
2. **Don't duplicate models** - Check first, update instead
3. **Don't use unofficial names** - Use exact official names
4. **Don't guess benchmarks** - Only use verified scores
5. **Don't skip verification** - Always verify from official sources
6. **Don't break links** - Test all links before committing
7. **Don't mix formats** - Keep consistent date/price formats
8. **Don't forget emojis** - They improve readability
9. **Don't skip changelog** - Document every change
10. **Don't remove old entries** - Mark as deprecated instead

### ✅ DO

1. **Do verify everything** - Multiple sources if possible
2. **Do update all tables** - Model appears in multiple places
3. **Do maintain consistency** - Same data everywhere
4. **Do use emojis properly** - Follow guidelines
5. **Do test links** - Every single link
6. **Do update changelog** - Every single change
7. **Do sort correctly** - Latest first by default
8. **Do categorize properly** - All relevant categories
9. **Do credit sources** - In changelog
10. **Do keep formatting** - Follow standards exactly

---

## 📂 File Structure

```
AI_Models_Matrix/
└── docs/
    ├── readme.md           # Main awesome list
    ├── CHANGELOG.md        # Version history
    ├── CONTRIBUTING.md     # Contribution guidelines
    └── UPDATE_RULES.md     # This file
```

### Which File to Update

**readme.md:**
- All model tables (sorted 4 ways)
- Category sections
- Official resources
- Benchmarks and analysis
- Everything user-facing

**CHANGELOG.md:**
- Date of each update
- What was added/changed/fixed
- Version numbering
- Future plans

**CONTRIBUTING.md:**
- How to contribute
- PR process
- Style guidelines
- Community guidelines

**UPDATE_RULES.md:**
- This document
- Update for process changes
- Add new rules as needed

---

## 🔄 Update Workflow

### Step-by-Step Process

1. **Research** 🔍
   - Find new model announcement
   - Gather official documentation
   - Verify benchmarks and pricing
   - Check if model already exists

2. **Check Duplicates** 🚫
   - Search readme.md for model name
   - Search for company name
   - Check if it's just a version update

3. **Prepare Information** 📝
   - Fill out all required fields
   - Verify all links work
   - Choose appropriate emojis
   - Format dates and prices correctly

4. **Update Main Table** 📊
   - Add to "Sort by Latest Update" (top if newest)
   - Add ⭐ if within last 30 days
   - Ensure all columns filled

5. **Update Company Section** 🏢
   - Add to correct company table
   - Maintain chronological order within company

6. **Update Category Sections** 🎯
   - Add to all relevant categories
   - Update category descriptions if needed

7. **Update Official Resources** 🔗
   - Add company section if new
   - Add links to documentation

8. **Update Latest Updates** 🆕
   - If released in last 30 days
   - Include in highlights table

9. **Update CHANGELOG.md** 📜
   - Add to top of changelog
   - Describe what was added
   - Include date and sources

10. **Verify Everything** ✅
    - Test all links
    - Check formatting
    - Verify no duplicates
    - Ensure consistency across all tables

---

## 🎓 Examples

### Example 1: Adding New Model

**Model:** Gemini 3.0 Pro (hypothetical)

```markdown
| 🌐 **Google** | Gemini 3.0 Pro | 3.0 Pro | 2025-11-15 | **2025-11-15** ⭐ | ✅ Excellent | 95% / 90% | $1.50 / $12.00 | ❌ | [🔗](https://deepmind.google/technologies/gemini/) |
```

**Add to:**
- Main table (top - newest)
- Google section
- Frontier Models category
- Latest Updates section
- CHANGELOG.md

### Example 2: Updating Existing Model

**Before:**
```markdown
| 🔬 **DeepSeek** | DeepSeek-V3.1 | V3.1 | 2025-08-21 | 2025-08-21 | ✅ Excellent | 82%+ / 85%+ | $0.27 / $0.41 | ✅ MIT | [🔗](https://www.deepseek.com) |
```

**After (new version V3.3):**
```markdown
| 🔬 **DeepSeek** | DeepSeek-V3.3 | V3.3 | 2025-08-21 | **2025-11-20** ⭐ | ✅ Excellent | 85% / 87% | $0.25 / $0.38 | ✅ MIT | [🔗](https://www.deepseek.com) |
```

**Update:**
- Version column (V3.1 → V3.3)
- Latest Updated (2025-08-21 → 2025-11-20 ⭐)
- Benchmarks (improved scores)
- Price (reduced)
- ALL tables where model appears

### Example 3: Changelog Entry

```markdown
## [2025-11] - November 2025

### Added
- **Gemini 3.0 Pro** (Google) - Released Nov 15, 2025, 95% HumanEval

### Changed
- **DeepSeek-V3.3** - Updated from V3.1, improved benchmarks, reduced pricing
- Updated pricing for 5 models based on official announcements

### Fixed
- Corrected Llama 4 Maverick benchmark scores
- Fixed broken link to Mistral AI documentation
```

---

## 🤝 Collaboration Guidelines

### For Multiple Contributors

1. **Communicate** - Announce major updates in discussions
2. **Avoid conflicts** - Check if someone else is updating
3. **Review PRs** - At least one other person reviews
4. **Test thoroughly** - All links and formatting
5. **Be consistent** - Follow these rules exactly

### PR Requirements

- [ ] All links tested and working
- [ ] No duplicate models
- [ ] Formatting follows standards
- [ ] Emojis used correctly
- [ ] Changelog updated
- [ ] All tables updated (if applicable)
- [ ] Verification sources provided
- [ ] No spelling/grammar errors

---

## 📞 Questions?

If you have questions about these rules:

1. Check [CONTRIBUTING.md](CONTRIBUTING.md) first
2. Review past changes in [CHANGELOG.md](CHANGELOG.md)
3. Look at existing examples in readme.md
4. Open an issue for clarification
5. Tag maintainers in discussions

---

## 📜 Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.1 | 2025-12-07 | Added OpenRouter.ai and LLM-Stats.com as data sources, updated dates |
| 1.0 | 2025-10-30 | Initial creation of UPDATE_RULES.md |

---

**Remember:** The goal is to maintain the most accurate, user-friendly, and comprehensive AI models matrix. Quality over speed! 🎯

**Data Sources:** OpenRouter Rankings, LLM-Stats.com, Official Documentation

*Last Updated: December 7, 2025*