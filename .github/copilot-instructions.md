# Copilot Instructions for Wildcards Project

## Project Overview

This is a comprehensive collection of wildcards for ComfyUI, structured as a curated text-based prompt enhancement system. The project contains thousands of categorized terms organized in `.txt` files to dynamically generate creative AI prompts for image generation. **Updated with 2025 trends** including AI ethics, sustainability, hybrid spaces, and neurosciencewell

## Architecture & Organization

### Core Structure Pattern
- **Scale**: 100+ top-level directories following semantic domains
- **File Format**: Plain `.txt` files with one term/phrase per line
- **Naming Convention**: Descriptive directory names with snake_case for multi-word concepts
- **Hierarchical Organization**: Categories → Subcategories → Content files (max 3 levels deep)
- **Documentation Language**: Mixed Spanish/English (README in Spanish, instructions in English)

### Essential Directory Categories
```
characters/        # People, professions, creatures, archetypes
environments/      # Locations, weather, landscapes, liminal spaces
styles/           # Art movements, photography techniques, visual aesthetics
technical/        # Camera settings, lighting, composition, post-processing
modifiers/        # Quality terms, positive/negative descriptors
objects/          # Items, vehicles, weapons, furniture, impossible geometry
worldbuilding/    # Fantasy/sci-fi settings, mythology, impossible societies
ai_advanced/      # AI ethics, emerging roles, visualization (2025)
sustainability_advanced/  # Climate adaptation, green tech (2025)
neuroscience_wellness/    # Brain states, biofeedback (2025)
content_creation_advanced/ # Platform-specific, AI workflows (2025)
```

## Content Patterns

### Legacy Format (Pre-2025)
- **Format**: Pure content, one term per line, no metadata
- **Examples**: 
  - `characters/professions/modern.txt`: "Doctor", "Engineer", "Teacher"
  - `modifiers/positive.txt`: "high detail", "masterpiece", "ultra high quality"

### Modern Format (2025+)
- **Header Metadata**: Required for new categories
```
# Category: AI Advanced
# Subcategory: Emerging AI Roles - AI Artists  
# Updated: September 25, 2025
# Count: 40 entries
# Tags: ai-creativity, digital-artists, generative-art
```
- **Content**: Detailed descriptive phrases that work naturally in AI prompts
- **Examples**: `ai_advanced/emerging_ai_roles/ai_artists.txt`, `sustainability_advanced/*/`

### Specialized Content Types
- **Impossible Concepts**: Abstract geometries, surreal scenarios (`objects/impossible_geometry.txt`)
- **Technical Descriptors**: Camera settings, lighting, composition rules
- **Cultural References**: Gaming, cinema, fashion, platform-specific aesthetics
- **Scientific/Academic**: Neuroscience terms, climate data, AI ethics concepts

## Wildcard Usage System

### Basic Syntax
```
__category/subcategory/file__
```

### Complex Combinations  
```
__characters/professions/{modern,fantasy}__  # Choose from multiple files
{option1|option2}                          # Direct alternatives
```

### Recommended Prompt Structure
1. **Subject**: `__characters/professions/modern__`
2. **Action**: `__actions/poses/general__`
3. **Environment**: `__environments/locations/urban__`
4. **Style**: `__styles/photography/techniques__`
5. **Technical**: `__technical/lighting/types__`
6. **Quality**: `__modifiers/positive__`

## Development Guidelines

### Adding New Categories
1. **2025+ Format**: Always include metadata headers with Category, Subcategory, Updated date, Count, and Tags
2. **Directory Structure**: Use semantic names with snake_case, max 3 levels deep
3. **Documentation**: Update `README.md` with Spanish descriptions and examples
4. **Integration**: Add usage examples to the README's "Cómo Usar las Wildcards" section

### Content Standards
- **Legacy Files**: Pure content, one term per line, no metadata
- **Modern Files**: Metadata header + content (see format above)
- **Prompt Compatibility**: Terms must work naturally in ComfyUI wildcard syntax `__category/file__`
- **No Special Characters**: Avoid characters that break wildcard parsing
- **Descriptive Phrases**: Multi-word terms that enhance AI prompts naturally

### File Organization Patterns
- **Core Categories**: `characters/`, `environments/`, `styles/`, `technical/`, `modifiers/`
- **Advanced Categories**: `*_advanced/` naming for specialized 2025 content
- **Impossible Concepts**: Files containing surreal/abstract terms for creative prompts
- **Language Mixing**: Spanish README documentation, English instruction files

## Integration Points

### Critical Documentation Files
- `README.md`: Spanish-language comprehensive guide with category descriptions and usage examples
- No separate EXAMPLES.md - examples integrated into README sections
- Update both structure overview and "Cómo Usar las Wildcards" when adding categories

### Development Workflow
1. **Content Addition**: Prefer existing categories, use modern format for new 2025+ files
2. **Category Creation**: Requires README updates in Spanish with emoji icons and descriptions
3. **Quality Assurance**: Test wildcards in ComfyUI before committing
4. **Metadata Consistency**: Use consistent tagging and dating patterns for new content

## Domain Knowledge

This project specifically serves **AI image generation workflows**, where:
- Terms must work naturally in prompt contexts
- Quality and style modifiers significantly impact output
- Technical photography/art terminology is essential
- Creative/impossible concepts expand artistic possibilities
- Hierarchical organization enables complex prompt building

The content balances practical terms (professions, objects) with creative concepts (impossible geometries, abstract professions) to serve both realistic and fantastical image generation needs.

## Key Content Evolution Patterns

### Temporal Content Strategy
- **Legacy Content**: Traditional categories (characters, styles, environments) with simple term lists
- **2025 Expansion**: Advanced categories reflecting contemporary concerns (AI ethics, climate change, hybrid work)
- **Impossible/Surreal**: Specialized content for abstract artistic exploration
- **Cultural Integration**: Platform-specific aesthetics (TikTok, Instagram) and viral culture references

### Metadata Standards (2025+)
```
# Category: [Main Category Name]
# Subcategory: [Category - Specific Area]  
# Updated: [Month Day, Year]
# Count: [Number] entries
# Tags: [comma-separated, lowercase-with-hyphens]
```

### Usage Context Awareness
- Files are consumed by ComfyUI's wildcard extension using `__path/to/file__` syntax
- Content must be prompt-ready descriptive phrases, not just keywords
- Hierarchical categories enable complex prompt building: `__characters/professions/modern__ in __environments/locations/urban__ with __technical/lighting/dramatic__`