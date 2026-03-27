# AutoDiag Pro Ultimate

Aplicatie nativa SwiftUI iOS pentru diagnosticare auto completa.

## Functii (7 tab-uri)

1. **Scan** — Foto diagnostic + AR Live overlay cu 5 sub-tab-uri rezultate
2. **VIN/Nr** — Citire VIN/numar inmatriculare + identificare vehicul
3. **Service** — Calendar intretinere 9 componente cu bare de progres
4. **Costuri** — Estimator costuri cu 25 operatii din 8 categorii
5. **Live** — 6 gauge-uri OBD2 animate cu simulare demo
6. **Voce** — Recunoastere vocala romana + diagnostic AI instant
7. **Mecanic** — Chat complet cu mecanic virtual AI

## Cerinte

- iOS 16+
- Xcode 15+
- Swift 5.9+

## Arhitectura

- **MVVM** cu `@StateObject` / `@EnvironmentObject`
- **19 fisiere Swift** organizate in Models, Views, Services, Utilities
- **Tema dark automotive** cu culori neon (albastru, verde, galben)
- **UI complet in romana**

## Permisiuni

- Camera (scanare diagnostic, citire VIN)
- Microfon (comanda vocala)
- Speech Recognition (recunoastere vocala ro-RO)
- Bluetooth (conectare OBD2 ELM327)

## Instalare

1. Deschide `AutoDiagPro.xcodeproj` in Xcode
2. Selecteaza target iOS 16+
3. Build & Run pe simulator sau device
