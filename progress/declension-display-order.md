# Default order for declension tables & drills (fixed)

This project uses **one fixed layout** for all German case grids (nouns, articles, adjectives, pronouns) in explanations, tables, and exercises unless a specific exam source dictates otherwise.

## Rows (cases)

Always in this order (with optional Goethe-style numbering):

1. **Nominativ (1)**
2. **Akkusativ (4)**
3. **Dativ (3)**
4. **Genitiv (2)**

Mnemonic in chat/docs: **nom1 — akk4 — dat3 — gen2**.

## Columns (genders / number)

Always:

1. **m** (maskulin) 阳性  
2. **n** (neutrum) 中性  
3. **f** (feminin) 阴性  
4. **pl** (Plural) 复数  

## Adjective ending color convention (always)

When adjective endings are shown in tables/explanations:

- **-e** → red + bold
- **-en** → blue + bold
- **-er** → orange + bold
- **-es** → green + bold

Use HTML spans in markdown where needed (for reliable rendering), e.g.:
- `gut<span style="color:#c0392b;font-weight:bold;">e</span>`
- `gut<span style="color:#2980b9;font-weight:bold;">en</span>`
- `gut<span style="color:#e67e22;font-weight:bold;">er</span>`
- `gut<span style="color:#27ae60;font-weight:bold;">es</span>`

## Coach / learner usage

- All new **adjective / article** summary tables follow this grid.  
- **Drills** that use a 4×4 case×gender layout list items **row by row** (16 items): Nom m,n,f,pl → Akk m,n,f,pl → Dat … → Gen ….

## Files

- Weak adjective drills: `sessions/2026-03-26/adjektiv-schwach-drills.md`  
- Broader summary (weak/mixed/strong unified): `sessions/2026-03-26/grammar-summary.md`
