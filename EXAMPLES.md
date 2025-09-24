# Ejemplos de Uso de Wildcards

## 🎯 Prompts de Ejemplo

### Retrato Básico
```
A __characters/professions/modern__ with __characters/animals/birds__ features, __technical/lighting/types__, __technical/camera_settings/settings__, __styles/photography/techniques__
```

### Escena de Fantasía
```
A __characters/professions/fantasy__ riding a __characters/animals/wild_mammals__ through __environments/landscapes/natural__, __technical/lighting/types__, __styles/art_movements/classic__ style
```

### Fotografía de Moda
```
A fashion model wearing __characters/clothing/general__, __actions/poses/general__, in __environments/interiors/residential__, __technical/lighting/types__, shot with __technical/camera_settings/models__
```

### Arte Digital
```
__characters/animals/wild_mammals__-inspired character in __styles/digital_art/styles__, __technical/composition/rules__, __modifiers/colors__, high quality, detailed
```

### Combinación Compleja
```
A __characters/professions/fantasy__ __characters/animals/wild_mammals__-rider wearing __characters/clothing/medieval__, __actions/poses/general__ on a cliff overlooking __environments/landscapes/natural__, __technical/lighting/types__, __technical/composition/rules__, rendered in __styles/digital_art/styles__, __modifiers/positive__
```

## 🔄 Variaciones Dinámicas

### Método 1: Wildcards Anidadas
```
__characters/{animals/wild_mammals,professions/fantasy,fantasy/}__
```

### Método 2: Construcción por Capas
```
Character: __characters/professions/modern__
Setting: __environments/locations/urban__
Style: __styles/photography/techniques__
Quality: __modifiers/positive__
```

### Método 3: Prompt Completo Dinámico
```
{__characters/professions/modern__|__characters/professions/fantasy__} in {__characters/clothing/casual__|__characters/clothing/general__}, {__actions/poses/general__|__actions/activities/general__}, {__environments/landscapes/natural__|__environments/locations/urban__}, {__technical/lighting/types__|natural lighting}, {__styles/photography/techniques__|__styles/digital_art/styles__}, {__modifiers/positive__|high quality}, detailed, masterpiece
```

## 🎨 Templates por Género

### Retrato
```
Template: A __characters/professions/modern__ portrait, __technical/lighting/types__, __technical/camera_settings/settings__, __styles/photography/techniques__

Ejemplo: A doctor portrait, soft lighting, f/2.8, portrait photography
```

### Paisaje
```
Template: __environments/landscapes/natural__ during __environments/time/period__, __technical/lighting/types__, __styles/photography/techniques__

Ejemplo: Mountain peak during golden hour, natural lighting, landscape photography
```

### Fantasía
```
Template: A __characters/professions/fantasy__ in __environments/landscapes/natural__, __styles/art_movements/classic__, __modifiers/positive__
 
Ejemplo: A wizard in enchanted forest, fantasy art, highly detailed
```

### Arte Digital
```
Template: __subjects__ in __styles/digital_art/styles__, __technical/composition/rules__, __modifiers/colors__, __modifiers/positive__

Ejemplo: Futuristic city in cyberpunk style, dynamic composition, neon colors, ultra detailed
```

## 🔧 Configuraciones Técnicas

### Para Fotografía Realista
```
__technical/camera_settings/models__, __technical/camera_settings/settings__, __technical/lighting/types__, __technical/composition/rules__, photorealistic, high resolution
```

### Para Arte Conceptual
```
__styles/digital_art/styles__, __technical/composition/rules__, concept art, detailed, __modifiers/positive__
```

### Para Arte Tradicional
```
__styles/traditional_media/techniques__, __styles/art_movements/classic__, traditional art, detailed
```

## 📝 Notas de Construcción

1. **Orden recomendado**: Sujeto → Acción → Entorno → Estilo → Técnico → Calidad
2. **Balancear pesos**: Usar paréntesis para enfatizar elementos importantes
3. **Combinar categorías**: Mezclar wildcards de diferentes carpetas
4. **Probar variaciones**: Experimentar con diferentes combinaciones

## 🚀 Prompts Avanzados

### Prompt Cinematográfico
```
A cinematic shot of __characters/professions/modern__ __actions/poses/general__ in __environments/locations/urban__, __technical/lighting/types__, shot with __technical/camera_settings/models__, __technical/composition/rules__, film grain, dramatic, __modifiers/positive__
```

### Prompt de Arte Conceptual
```
Concept art of a __characters/professions/fantasy__ hero in __environments/landscapes/natural__, __styles/digital_art/styles__, __technical/composition/rules__, detailed environment, atmospheric, __modifiers/positive__
```

### Prompt de Retrato Artístico
```
Artistic portrait of __characters/professions/fantasy__, __actions/expressions/general__, __technical/lighting/types__, __styles/art_movements/classic__, oil painting, masterpiece, detailed
```

### Prompt Emocional + Arquitectura
```
A __characters/professions/modern__ contemplating a facade in __architecture/styles/styles__, under __technical/lighting/moods__, with a(n) __emotions/tones/tones__ tone; details in __materials/metals/metals__ and __materials/woods/woods__, composed with __technical/composition/rules__
```

### Prompt Tecnológico + IA
```
Futuristic lab featuring __technology/ai/concepts__, powered by __technology/hardware/hardware__, protected by __descriptors/nouns/myth_tech__, photographed with __technical/camera_settings/models__, high detail, __quality/technical__
```

### Prompt Gastronómico + Estilo
```
Editorial food shot of __food/dishes/japanese__ from __food/cuisines/world__, styled with __styles/photography/techniques__, soft __technical/lighting/types__, background with __objects/nature/flowers__, appetizing, __quality/emotional__
```

### Prompt Deportivo
```
Action shot of __sports/types/sports__ using __sports/gear/gear__, in __environments/locations/urban__ at __environments/time/period__, dynamic angle __technical/composition/angles__, dramatic __technical/lighting/types__, sharp focus, __quality/technical__
```

### Prompt Storytelling (Género + Tema + Tropo)
```
__storytelling/genres/genres__ tale about __storytelling/themes/themes__, featuring __storytelling/tropes/tropes__, set in __worldbuilding/settings/settings__, mood __emotions/tones/tones__, rendered in __styles/digital_art/styles__, __quality/technical/image_quality__
```

### Prompt Worldbuilding (Cultura + Mitología)
```
Worldbuilding sheet for __worldbuilding/cultures/cultures__ influenced by __worldbuilding/mythology/mythology__, architecture __architecture/styles/styles__, materials __materials/fabrics/fabrics__, __materials/metals/metals__, color accents __modifiers/colors__, crisp __quality/technical/image_quality__
```

### Prompt Narrativa Cinemática
```
Cinematic scene in __worldbuilding/settings/settings__, genre __cinema/genres__, directed in the style of __cinema/directors_styles__, theme __storytelling/themes/themes__, atmospheric __technical/lighting/moods__, ultra __quality/technical/image_quality__
```

### Prompt Fashion Timeline
```
Fashion portrait wearing __fashion/decades/1950s__, inspired by __fashion/brands/regional__, posed __actions/poses/general__, shot in __environments/interiors/residential__, with __technical/lighting/types__, __aesthetics/vibes/vibes__ mood, __quality/emotional__
```

### Prompt Worldbuilding Encounter
```
__characters/fantasy/creatures__ from __worldbuilding/factions/factions__ encountering __worldbuilding/flora_fauna/fauna__ in __worldbuilding/settings/settings__, conflict __storytelling/conflicts/conflicts__, magic __worldbuilding/magic_systems/systems__, atmosphere __emotions/tones/tones__, rendered in __styles/digital_art/styles__
```

### Prompt Character Study
```
Portrait of a __characters/people/age__ __characters/professions/modern__ with __characters/people/features__, wearing __fashion/styles/styles__, expression __actions/expressions/general__, aesthetic __aesthetics/internet/internet__, background __environments/landscapes/natural__, __quality/technical/image_quality__
```

### Prompt Action Scene
```
Dynamic scene of __actions/movements/physical__ during __actions/scenarios/situations__, featuring __objects/weapons/swords__ and __objects/vehicles/automobiles__, rendered with __technical/post_processing/effects__, color palette __colors/palettes__, mood __music/moods__, ambient __sounds/ambience__
```

### Prompt Environment Study
```
Detailed environment showing __environments/locations/detailed_urban__ during __environments/weather/conditions__ at __environments/time/period__, textures __textures/surface__, patterns __patterns/designs__, lighting __technical/lighting/types__, post-processed with __technical/render_settings/techniques__
```

### Prompt Object Focus
```
Close-up of __objects/furniture/furniture__ made from __materials/woods/woods__ with __textures/surface__ finish, pattern __patterns/designs__, colors __colors/basic__, shot with __technical/camera_settings/models__, composition __technical/composition/rules__, __quality/technical/image_quality__
```