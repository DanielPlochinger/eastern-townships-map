# Eastern Townships Map — Memory

## Category Colors — v1 (original, saved 2026-05-21)
Described as "too random and garish." Saved here to revert if needed.
- brewery:      #D97706  (amber)
- vineyard:     #7C3AED  (bright purple)
- bike-loop:    #16A34A  (bright green)
- village:      #DC2626  (bright red)
- scenic-drive: #2563EB  (bright blue)
- lake:         #0891B2  (cyan)
- cafe:         #92400E  (dark brown)
- farm-table:   #059669  (medium green)

## Category Colors — v2 (saved 2026-05-21, superseded by v3 when applied)
More cohesive, muted, earthy palette. Bike loops changed to cobalt blue so
circles read better against green OSM map tiles.
- brewery:      #B45309  (copper/amber)
- vineyard:     #6D28D9  (deep grape)
- bike-loop:    #1D4ED8  (cobalt blue)
- village:      #BE123C  (deep crimson)
- scenic-drive: #0F766E  (dark teal)
- lake:         #0369A1  (ocean blue)
- cafe:         #A16207  (golden brown)
- farm-table:   #166534  (forest green)

To revert: replace the CATS color values in index.html with the v1 hex codes above.

## Category Colors — v3 (current, applied 2026-05-21)
User-supplied RGB palette. Note: lake and experience share #90C7BC (rows 6 & 9 were identical).
- brewery:      #DE6965  (coral/salmon red)
- vineyard:     #F19E47  (warm amber/orange)
- bike-loop:    #8575C1  (soft purple/lavender)
- village:      #7BC380  (soft green)
- scenic-drive: #3376CE  (medium blue)
- lake:         #90C7BC  (soft teal)
- cafe:         #C8A16E  (warm tan/caramel)
- farm-table:   #F4E47F  (soft yellow)
- experience:   #90C7BC  (soft teal — duplicate of lake; pending user decision)

## Category Added — v2 update (2026-05-21)
- experience: #BE185D (deep raspberry/rose) — added for "Other Notable Experiences"
  Entries: Spa Eastman, Missisquoi Museum & Walbridge Barn, Heritage & Literary Trails, Frontenac National Park

## Extra Links Added (2026-05-21)
Multi-location cafés and multi-beach lakes now have `extraLinks` arrays in PLACES data:
- c1 Café Hubert Saint-Jean: +Sherbrooke Bourque, +Magog
- c2 Brûlerie Faro: +Roastery, +Lennoxville
- c6 Géogène Micro-Torréfacteur: +Magog
- lk5 National-Park Beaches: +Lac Fraser, +Yamaska/Choinière, +Frontenac/Baie aux Rats-Musqués
- lk6 Lake Memphrémagog: +Plage Pointe-Merry, +Plage de l'Ouest
- lk7 Lake Massawippi: +Public Wharf
