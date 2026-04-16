# PAGES - AGENTS.md

**Parent:** `../AGENTS.md`

## OVERVIEW

Knowledge base pages - technical notes, concepts, and reference material. Semi-permanent content organized by topic rather than date.

## STRUCTURE

```
pages/
├── 2018/                     # 2018 articles (with images/)
├── 2019/                     # 2019 articles
├── 2020/                     # 2020 articles
├── literature-programme/     # SICP study notes
├── *.org, *.md              # Root-level pages
└── images/                   # Page-specific images
```

## WHERE TO LOOK

| Topic Type | Files | Examples |
|------------|-------|----------|
| Go programming | `go备忘.org`, `go之==.org`, `channel.org` | Concurrency, syntax |
| Rust programming | `错误处理.org`, `借用与引用.org` | Ownership, errors |
| Tools | `git备忘.org`, `docker常用备忘.org` | Commands, workflows |
| Emacs/Editor | `spacemacs使用.md` | Editor configuration |
| Concepts | `学习方法论.md`, `文学编程.org` | Methodology |
| Personal | `annual-meeting.md`, `Logseq介绍.md` | Events, tools |

## CONVENTIONS

### File Naming
- Chinese titles: `学习方法论.md` (Learning methodology)
- English technical: `channel.org`, `go备忘.org`
- Year directories for dated archives

### Content Patterns
- **Cheat sheets**: Command references (备忘 = memo/cheat sheet)
- **Concept notes**: Explanations with examples
- **Learning logs**: Progress tracking

### Cross-References
- Use `[[Page Name]]` to link related pages
- Tags for categorization: `#programming`, `#learning`

## ANTI-PATTERNS

### Image Organization
- Some images in `pages/images/`
- Others in `pages/2018/images/`
- Inconsistent - check both locations

### Format Mixing
- Same topic may have both `.org` and `.md` versions
- Check extension when linking

## NOTES

- **130 files** across root and subdirectories
- **Programming focus** - Heavy technical content
- **Learning-oriented** - Notes from studying Go, Rust, SICP
- **Chinese + English** - Technical terms often in English
- **Organized by year** for archived content
