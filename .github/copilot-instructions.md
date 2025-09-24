# Copilot Instructions for Wildcards Project

## Project Overview

This is a comprehensive collection of wildcards for ComfyUI, structured as a curated text-based prompt enhancement system. The project contains thousands of categorized terms organized in `.txt` files to dynamically generate creative AI prompts for image generation.

## Architecture & Organization

### Core Structure Pattern
- **Categorization**: 80+ top-level directories following semantic domains (characters, environments, styles, technical, etc.)
- **File Format**: Plain `.txt` files with one term/phrase per line
- **Naming Convention**: Descriptive directory names with snake_case for multi-word concepts
- **Hierarchical Organization**: Categories → Subcategories → Content files

### Key Directory Categories
```
characters/        # People, professions, creatures
environments/      # Locations, weather, landscapes  
styles/           # Art movements, photography techniques
technical/        # Camera settings, lighting, composition
modifiers/        # Quality terms, positive/negative descriptors
objects/          # Items, vehicles, weapons, furniture
worldbuilding/    # Fantasy/sci-fi settings, mythology
impossible_*/     # Surreal/abstract concepts
```

## Content Patterns

### Standard Wildcard Files
- **Format**: Newline-separated terms, no quotes or special formatting
- **Content Style**: Descriptive phrases that work naturally in prompts
- **Examples**: 
  - `characters/professions/modern.txt`: "Doctor", "Engineer", "Teacher"
  - `technical/lighting/types.txt`: "natural lighting", "dramatic lighting"
  - `modifiers/positive.txt`: "high detail", "masterpiece", "ultra high quality"

### Advanced Concept Files
- **Impossible Concepts**: Creative abstract professions and surreal scenarios
- **Worldbuilding**: Detailed fantasy/sci-fi settings and mythology
- **Specialized**: Domain-specific terminology (gaming, cinema, fashion)

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
1. Create semantic directory names that align with existing patterns
2. Use lowercase with underscores for multi-word directories
3. Maintain hierarchical organization (max 3 levels deep recommended)
4. Add documentation to `README.md` structure section

### Content Standards
- One term per line in `.txt` files
- No empty lines or comments within content files
- Terms should be prompt-ready (no special characters that break wildcard parsing)
- Consistent terminology within categories
- Balance between specificity and variety

### File Naming
- Use descriptive names that clearly indicate content
- Maintain consistency within categories
- Prefer singular nouns for file names
- Use `general.txt` for broad collections within a category

## Integration Points

### Documentation Files
- `README.md`: Complete structure overview and usage guide
- `EXAMPLES.md`: Practical prompt templates and combinations
- Both files should be updated when adding major new categories

### Maintenance Workflow
1. New content goes in existing categories when possible
2. New categories require documentation updates
3. Test wildcards in actual ComfyUI workflows
4. Maintain semantic consistency across related categories

## Domain Knowledge

This project specifically serves **AI image generation workflows**, where:
- Terms must work naturally in prompt contexts
- Quality and style modifiers significantly impact output
- Technical photography/art terminology is essential
- Creative/impossible concepts expand artistic possibilities
- Hierarchical organization enables complex prompt building

The content balances practical terms (professions, objects) with creative concepts (impossible geometries, abstract professions) to serve both realistic and fantastical image generation needs.