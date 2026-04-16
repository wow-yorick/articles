# KNOWLEDGE BASE - AGENTS.md

**Generated:** 2026-04-16  
**Commit:** a397988  
**Branch:** master  
**Type:** Logseq Personal Knowledge Management

## OVERVIEW

Personal knowledge base in Chinese managed by Logseq. Contains daily journals, technical notes, and reflective writing. Uses mixed Org-mode (preferred) and Markdown formats.

## STRUCTURE

```
articles/
├── journals/          # Daily entries (1,090 files)
├── pages/             # Knowledge pages (130 files)
├── md-pages/          # Published markdown articles (18 files)
├── assets/            # Images and media
├── logseq/            # Logseq config and metadata
└── whiteboards/       # Empty (reserved)
```

## WHERE TO LOOK

| Task | Location | Notes |
|------|----------|-------|
| Daily notes | `journals/` | Dated entries (YYYY_MM_DD) |
| Technical articles | `pages/` | Programming, tools, concepts |
| Published content | `md-pages/` | Long-form markdown articles |
| Media files | `assets/` | Images referenced in notes |
| Logseq settings | `logseq/config.edn` | App configuration |

## CONVENTIONS

### File Formats
- **Preferred**: Org-mode (`.org`) - configured in `config.edn`
- **Accepted**: Markdown (`.md`) - for compatibility
- **Mixed usage**: Both formats coexist in same repo

### Naming
- **Journals**: `YYYY_MM_DD.org` or `YYYY_MM_DD.md`
- **Pages**: Descriptive Chinese or English titles
- **Example**: `2021_07_21.md`, `go备忘.org`, `学习方法论.md`

### Content Patterns
- Outliner-style with indentation hierarchy
- WikiLinks: `[[Page Name]]` for cross-references
- Tags: `#tag` for categorization
- TODO markers: `NOW`, `LATER`, `TODO`, `DOING`

## ANTI-PATTERNS (THIS PROJECT)

### Format Inconsistency
- **Issue**: Mixing `.org` and `.md` in same directory
- **Impact**: Complicates search and tooling
- **Status**: Historical, both actively used

### Directory Split
- **Issue**: `/pages/` and `/md-pages/` both contain articles
- **Impact**: Unclear separation of concerns
- **Workaround**: Treat `/md-pages/` as "published" subset

### Empty Directories
- **Issue**: `/whiteboards/` exists but empty
- **Status**: Reserved for future Logseq feature

## UNIQUE STYLES

### Bilingual Content
- Primary: Chinese (Simplified)
- Technical terms: Often English or mixed
- File names: Both Chinese and English

### Personal Knowledge Patterns
- Daily reflective journaling
- Technical learning notes (Go, Rust, Git, Docker)
- Life observations and career thoughts
- Skill development tracking (有声书/audiobook narration)

## COMMANDS

```bash
# No build process - this is content repository
git add .
git commit -m "feat: 日记"
git push origin master
```

## NOTES

- **No CI/CD**: Pure content repo, no automation
- **No tests**: Documentation, not code
- **Logseq workflow**: NOW/LATER task management
- **Auto-generated queries**: Shows NOW tasks from last 14 days
- **Backup**: Logseq creates `.bak/` copies automatically
