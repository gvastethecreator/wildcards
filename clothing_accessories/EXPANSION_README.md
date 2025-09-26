# Expansión de Categorías de Vestimenta para Wildcards

Esta expansión se enfoca en la creación detallada de personajes a través de un sistema completo de vestimenta, accesorios, marcas y outfits específicos.

## Nuevas Categorías Creadas

### 📁 designer_collections/
Colecciones de marcas y diseñadores icónicos:
- **luxury_fashion_houses.txt** - Casas de alta costura (Chanel, Gucci, Louis Vuitton, etc.)
- **streetwear_brands.txt** - Marcas de streetwear (Supreme, Off-White, BAPE, etc.) 
- **athletic_sportswear.txt** - Marcas deportivas (Nike, Adidas, Puma, etc.)
- **iconic_collaborations.txt** - Colaboraciones famosas entre marcas
- **hollywood_golden_age.txt** - Looks icónicos del cine clásico

### 📁 cosplay_detailed/
Cosplay con descripciones específicas y detalladas:
- **anime_characters_detailed.txt** - Personajes de anime con outfits completos
- **video_game_characters_detailed.txt** - Personajes de videojuegos detallados
- **superhero_characters_detailed.txt** - Superhéroes con descripciones específicas

### 📁 subcultures_detailed/
Subculturas de moda con variaciones específicas:
- **lolita_fashion.txt** - Todos los tipos de Lolita (Gothic, Sweet, Classic, etc.)
- **punk_variations.txt** - Variaciones de punk (Classic, Hardcore, Anarchist, etc.)
- **gothic_variations.txt** - Tipos de gótico (Traditional, Romantic, Cyber, etc.)

### 📁 accessories_detailed/
Accesorios organizados por categorías específicas:
- **luxury_jewelry.txt** - Joyería de lujo y relojes premium
- **designer_footwear.txt** - Zapatos de diseñador detallados
- **designer_handbags.txt** - Bolsos de marcas de lujo

### 📁 historical_fashion/
Moda a través de las épocas:
- **ancient_to_modern.txt** - Desde la antigüedad hasta 1960s
- **decades_1970s_to_now.txt** - Desde los 70s hasta la actualidad

### 📁 themed_outfits/
Outfits temáticos para situaciones específicas:
- **professional_uniforms.txt** - Uniformes profesionales detallados
- **travel_vacation.txt** - Outfits para diferentes tipos de viaje
- **special_events.txt** - Ropa para eventos especiales
- **kawaii_styles.txt** - Estilos kawaii japoneses específicos

## Características de la Expansión

### Nivel de Detalle
- Cada entrada incluye elementos específicos del outfit completo
- Descripciones de accesorios complementarios
- Referencias culturales y contextuales
- Colores, materiales y texturas específicas

### Organización Semántica
- Categorización por función, estilo y contexto
- Jerarquías claras para facilitar la navegación
- Compatibilidad con el sistema de wildcards existente

### Aplicación en Prompts
Los nuevos wildcards permiten generar:
- Personajes con outfits específicos y detallados
- Combinaciones de marca y estilo coherentes
- Referencias culturales y de época precisas
- Accesorios y complementos coordinados

## Uso Recomendado

### Estructura de Prompt Sugerida
```
__characters/professions/modern__ wearing __clothing_accessories/designer_collections/luxury_fashion_houses__ with __clothing_accessories/accessories_detailed/luxury_jewelry__, __clothing_accessories/themed_outfits/special_events__ setting
```

### Combinaciones Temáticas
- Cosplay: `__clothing_accessories/cosplay_detailed/*__ + __subcultures_detailed/*__`
- Moda Histórica: `__clothing_accessories/historical_fashion/*__ + __accessories_detailed/*__`
- Streetwear: `__clothing_accessories/designer_collections/streetwear_brands__ + __themed_outfits/*__`

## Compatibilidad
- Todas las nuevas categorías mantienen el formato estándar de wildcards
- Compatible con las categorías existentes
- Permite combinaciones cross-category para máxima creatividad

Esta expansión transforma el sistema de wildcards en una herramienta completa para la creación de personajes con vestuario detallado, desde streetwear contemporáneo hasta cosplay específico y moda de épocas históricas.