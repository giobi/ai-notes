# AI Notes - Course Material Repository

AI Notes is a documentation repository for an Italian university course "Introduzione all'IA per l'Università della Terza Età" (Introduction to AI for the University of Third Age). This repository contains course materials, notes, chapters, presentations, and external resources organized in a structured workflow.

**ALWAYS reference these instructions first and fallback to search or bash commands only when you encounter unexpected information that does not match the info here.**

## Working Effectively

### Repository Structure and Workflow
- **ALWAYS** follow the content creation workflow: `appunti` → `capitoli` → `slides` → `risorse`
- **NEVER** skip the structured workflow - each stage serves a specific purpose in content development
- Create project directories if they don't exist:
  ```bash
  mkdir -p appunti capitoli risorse slides
  ```

### Content Organization Commands
- List all markdown files: `find . -name "*.md" | grep -v ".git"`
- Check repository status: `git --no-pager status`
- View file structure: `ls -la appunti/ capitoli/ risorse/ slides/`
- **Timing**: All operations are instant (no build/compilation required)

### File Creation and Editing
- **ALWAYS** create content in the correct directory based on development stage
- Use descriptive filenames with lowercase and hyphens: `capitolo-1-introduzione.md`
- **ALWAYS** include proper markdown headers (# ## ###) for structure
- Test markdown rendering: `cat filename.md` (visual inspection only - no automated validation available)

### Git Workflow for Content Management
- Check what files are tracked: `git --no-pager ls-files`
- View changes: `git --no-pager diff`
- Add new content: `git add .`
- Commit with descriptive messages: `git commit -m "Add chapter on AI fundamentals"`
- **Timing**: Git operations are instant

## Validation

### Content Quality Checks
- **ALWAYS** manually review markdown syntax by viewing files with `cat` or editor
- **ALWAYS** verify proper Italian language usage and technical accuracy
- **ALWAYS** ensure content follows the course structure defined in HOWTO.md
- **MANUAL VALIDATION REQUIREMENT**: Read through complete content to ensure pedagogical flow and accuracy
- Check file encoding: `file -i *.md` (should show UTF-8 for Italian characters)

### Workflow Validation Steps
1. Verify content exists in correct directory for its development stage
2. Check that chapter numbering follows logical sequence
3. Ensure cross-references between files are accurate
4. Validate that slides directory contains only final presentation materials

### Repository Integrity
- **ALWAYS** check .gitignore compliance: temporary files should not be committed
- Verify directory structure matches: `ls -la` should show appunti/, capitoli/, risorse/, slides/
- **NEVER** commit editor backup files (*.swp, *.tmp, *.bak)

## Common Tasks

### Adding New Course Content
1. **Start in appunti/**: Create initial notes and ideas
   ```bash
   echo "# New Topic Ideas" > appunti/new-topic.md
   ```
2. **Move to capitoli/**: Structure content into chapters
   ```bash
   cp appunti/new-topic.md capitoli/capitolo-X-topic.md
   # Edit and structure the content
   ```
3. **Create slides/**: Generate final presentations
   ```bash
   # Manual creation or conversion from chapters
   ```
4. **Update risorse/**: Add relevant external links and references

### Content Migration Workflow
- **From appunti to capitoli**: Restructure rough notes into formal chapters
- **From capitoli to slides**: Extract key points for presentation format
- **Always maintain traceability**: Keep original files when promoting content

### File Management
- Check for duplicate content: `grep -r "specific phrase" . --include="*.md"`
- Find files by content: `grep -l "keyword" *.md */*.md`
- View file sizes: `ls -lah appunti/ capitoli/ risorse/ slides/`

## Directory Structure Reference

```
.
├── README.md              # Project overview
├── HOWTO.md              # Course structure and organization guide
├── appunti/              # Raw notes and initial ideas
├── capitoli/             # Structured chapter content
├── slides/               # Final presentation materials
└── risorse/              # External resources and links
```

### Directory Contents Expectations
- **appunti/**: Markdown files with rough ideas, unstructured notes, draft content
- **capitoli/**: Well-structured markdown files following naming pattern `capitolo-N-topic.md`
- **slides/**: PDF, PowerPoint, or other presentation formats
- **risorse/**: Link collections, reference materials, external resources

## Key File Contents

### Repository Root Files
- **README.md**: Course overview and structure (2252 bytes)
- **HOWTO.md**: Detailed workflow and organization instructions (2022 bytes)
- **.gitignore**: Excludes temporary files, build artifacts, editor files, OS files

### Content Guidelines
- **Language**: All content is in Italian
- **Format**: Markdown for text content, various formats for presentations
- **Naming**: Use descriptive names with hyphens, no spaces
- **Structure**: Follow hierarchical organization with clear chapter numbering

## Troubleshooting

### Common Issues
- **Missing directories**: Run `mkdir -p appunti capitoli risorse slides`
- **Encoding issues**: Ensure UTF-8 encoding for Italian characters
- **Git tracking**: Use `git --no-pager ls-files` to see tracked files

### Content Development Issues
- **Workflow confusion**: Always refer to HOWTO.md for the official content development process
- **Chapter organization**: Follow the 4-chapter structure outlined in HOWTO.md
- **File placement**: When unsure, start in appunti/ and migrate forward through the workflow

### Performance Expectations
- **ALL operations are instant** - this is a documentation repository with no build/compile steps
- **File operations**: Instant (reading, writing, moving files)
- **Git operations**: Instant (status, diff, commit, push)
- **Content validation**: Manual review only, no automated tools available

## CRITICAL REMINDERS
- **NEVER** attempt to build, compile, or run code - this is a documentation repository
- **ALWAYS** follow the appunti → capitoli → slides → risorse workflow
- **ALWAYS** use Italian language for course content
- **ALWAYS** maintain proper markdown structure and formatting
- **VALIDATION**: Manual content review is the primary validation method
- **TIMING**: All operations complete instantly - no long-running processes exist