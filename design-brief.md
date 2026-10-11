# Mi Pedigrí · Design brief

- Product: Independent Spanish-language web app for pigeon breeders, usable on iPhone, Android and desktop.
- Audience: Hobbyist and competition pigeon breeders who need clear, dependable genealogy records.
- Design read: A precise, calm breeding archive that feels like a modern field journal rather than a generic software dashboard.
- Concept spine: Archive / dossier. Every bird is a record, and every record belongs to a living family tree.
- Delivery tier: Editorial, with subtle transitions only.
- Animation mode: non-animated, user picked option B (light motion, prioritizing loading speed and accessibility).
- Palette: deep slate-green #141b1c, layered pine slate #202a2a, muted sage #c0d58b, soft ivory #e8eee9, secondary text #9baaa5. One muted sage accent signals ancestry links and primary actions; no neon glow.
- Typography: system sans with tight display tracking and clear 16px body copy; no decorative serif dependency.
- Signature interaction: the family tree is a navigable record map. Selecting a bird changes the visible ancestors and descendants.
- Responsive behavior: desktop top navigation; compact fixed five-item mobile navigation; stacked forms and cards on small screens.
- Accessibility: semantic headings, labels, keyboard focus, high contrast, reduced-motion CSS, meaningful image alt text and large touch targets.
- Section plan: hero archive cover; three-step workflow strip; pedigree example; FAQ; account and records workspace.
- CTA inventory: Registrar paloma for record creation; Explorar pedigrí for genealogy browsing; Crear cuenta for account registration; Publicar anuncio for community listings.
- Offline plan: service worker caches the application shell after first visit; bird records and compressed photos are stored locally. Network is required for account creation, community listings and cloud sync.
- Data model: users, sessions, birds, and ads in D1. Bird records include ring, breed, sex, color, birth date, parents, notes, and optional photo reference.
- Known first-release limit: photo binaries stay local on the device; cross-device photo sync requires a configured file-storage layer. Email verification and password recovery are not included yet.
- Asset plan: original SVG pigeon illustration for the hero; custom 3:2 launch cover and square favicon in sage/slate colors. No AI image generation is embedded in the product.
- Deployment target: standalone website with D1 persistence, no Higgsfield sign-in or in-product image-generation service.
