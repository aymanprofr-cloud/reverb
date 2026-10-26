# Velvet Verb — Reverb vocale (VST3)

Reverb pensée pour les voix : son doux, queue sans résonance métallique, filtres pour garder la voix claire et un **ducking** qui baisse la reverb pendant que tu chantes et la laisse s'épanouir dans les silences.

## Les réglages

| Bouton | Rôle |
|---|---|
| **Size** | Taille de la pièce (petite cabine → cathédrale) |
| **Decay** | Durée de la queue (RT60, 0,2 s à 12 s) |
| **Pre-Delay** | Délai avant la reverb : plus il est long, plus la voix reste devant |
| **Mix** | Dosage dry/wet (le son sec reste à 100 % jusqu'à 50 % de mix) |
| **Damping** | Adoucit les aigus de la queue (plus chaud) |
| **Low Cut** | Coupe les basses de la reverb (évite la boue) |
| **High Cut** | Coupe les aigus de la reverb (évite les sifflantes) |
| **Width** | Largeur stéréo de la reverb (0 à 150 %) |
| **Ducking** | La reverb s'efface quand la voix joue |

Astuces : **double-clic** sur un bouton = valeur par défaut, **Shift + glisser** = réglage fin.

## Les 12 presets

Vocal Plate · Pop Shine · R&B Silk · Rap Ambiance · Small Room · Studio Booth · Big Hall · Ballade Long Tail · Cathedral · Ducked Hall (Clean Vox) · Lo-Fi Dream · Slapback Space

Ils sont dans le menu en haut du plugin (flèches < > pour passer de l'un à l'autre) et aussi dans le menu presets de FL Studio.

---

## Obtenir le fichier .vst3

### Option A — Sans rien installer (GitHub, gratuit)
1. Crée un compte sur github.com puis un **nouveau dépôt** (bouton « New »).
2. Clique sur **« uploading an existing file »** et glisse **tout le contenu** de ce dossier (y compris le dossier `.github`), puis « Commit changes ».
3. Va dans l'onglet **Actions** : la compilation démarre toute seule (≈ 10 min).
4. Quand c'est vert ✅, clique sur le build puis télécharge **VelvetVerb-VST3-Windows** en bas de la page.

### Option B — Sur ton PC
Installe Visual Studio 2022 Community (cocher « Développement Desktop en C++ »), CMake et Git, puis double-clique sur `build_windows.bat`.

## Installer dans FL Studio
1. Copie le dossier **`Velvet Verb.vst3`** dans `C:\Program Files\Common Files\VST3\`
2. FL Studio → **Options → Manage plugins → Find plugins** (scan).
3. Dans le **Mixer**, sur la piste de ta voix, clique un slot d'effet → **Velvet Verb**.

Conseil mix : sur la piste voix, garde le Mix autour de 15–30 %. Ou mets Velvet Verb sur une piste **send** avec Mix à 100 % et envoie-y une ou plusieurs voix.
