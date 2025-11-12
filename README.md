# 3dStore — Next.js Demo

Ein minimalistisches Next.js (App Router) TypeScript-Projekt als Basis für einen 3D-Store / Showcase.

## Inhalt
- Kurze Projektbeschreibung
- Tech-Stack
- Lokale Entwicklung
- Build & Produktion
- Deployment (Vercel)
- Projektstruktur
- Contributing & Lizenz

## Projektbeschreibung

Dieses Repository enthält eine Next.js-Anwendung (App Router) mit TypeScript. Sie ist als Startpunkt für ein 3D-Store-Frontend gedacht — leichtgewichtig, mit klarer Struktur, damit schnell Features wie 3D-Model-Viewer, Produktseiten und Checkout ergänzt werden können.

## Tech-Stack
- Next.js (App Router)
- TypeScript
- PostCSS (Konfiguration liegt im Projekt)
- Deployment: idealerweise Vercel

Hinweis: Paketmanager und Versionsangaben stammen aus `package.json` — prüfe dort ggf. die exakten Skripte.

## Voraussetzungen
- Node.js (empfohlen LTS, z. B. 18+)
- npm oder pnpm/yarn
- Optional: Vercel CLI oder GitHub-Account für Deployment

## Lokale Entwicklung

1. Abhängigkeiten installieren

```bash
npm install
# oder falls du pnpm benutzt:
# pnpm install
```

2. Entwicklungsserver starten

```bash
npm run dev
# Öffne http://localhost:3000
```

3. Build & Preview

```bash
npm run build
npm run start
# oder zum lokalen Preview (Next.js):
# npm run start  # prüfe package.json-skripte
```

## Deployment

Empfohlen: Vercel — Next.js ist dort nativ unterstützt.

1. Verbinde dein GitHub-Repository mit Vercel
2. Wähle das Projekt, Vercel erkennt automatisch Next.js-Konfiguration
3. Setze Umgebungsvariablen (falls nötig)

Alternativ kannst du auch andere Plattformen nutzen, die Node.js/Next.js unterstützen.

## Projektstruktur (Auszug)

```
3dstore-app/
  app/                # Next.js App-Router Seiten & Layout
  public/             # Statische Assets (SVG, Bilder)
  next.config.ts
  package.json
  README.md
```

## Contributing

1. Forke das Projekt
2. Erstelle einen Branch: `git checkout -b feat/awesome`
3. Committe deine Änderungen: `git commit -m "feat: beschreibe"`
4. Erstelle ein Pull-Request

Bitte beschreibe Änderungen klar und halte Commits klein und thematisch.

## Lizenz

Dieses Repository hat derzeit keine Lizenzdatei. Wenn du eine Lizenz möchtest, füge z. B. eine `LICENSE` mit MIT oder einer anderen passenden Lizenz hinzu.

---

Wenn du möchtest, kann ich jetzt das lokale Git-Repository initialisieren, alle Dateien committen und (falls du mir erlaubst) ein GitHub-Repository anlegen und die Dateien dorthin pushen. Soll ich fortfahren und ein GitHub-Repo automatisch erstellen (benötigt `gh` CLI und Auth), oder soll ich dir stattdessen die genauen Befehle geben, die du lokal ausführen kannst?
This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
