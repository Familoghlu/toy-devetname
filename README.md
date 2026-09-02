# Toy Dəvətnamələri — GitHub Pages

## Quruluş
- `index.html` — əsas kataloq
- `admin.html` — şəxsi admin paneli
- `data/invitations.json` — kataloq siyahısı
- `demos/` — dəvətnamə HTML faylları
- `assets/style.css` — kataloq dizaynı
- `assets/previews/` — preview şəkilləri

## GitHub Pages
Repository Settings → Pages → Deploy from a branch → `main` / `/ (root)` seç.

## Admin token
Fine-grained GitHub Personal Access Token yaradarkən yalnız bu repository üçün `Contents: Read and write` icazəsi kifayətdir. Tokeni `admin.html`-ə yazma. Panel onu yalnız cari browser session-da saxlayır.

## Qeyd
Admin panel brauzerdən GitHub API-yə birbaşa müraciət edir. Bu, şəxsi istifadə üçün rahatdır; admin linkini açıq şəkildə paylaşmaq tövsiyə edilmir.
