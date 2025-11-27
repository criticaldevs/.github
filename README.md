# Critical Devs

**critical developers. critical developments.**

Two developers building modern software solutions. Passionate about gaming and clean code.

> ⚠️ **SITE UNDER CONSTRUCTION** - GREAT THINGS COMING SOON

🌐 [criticaldevs.de](https://criticaldevs.de/)

---

## What is criticaldevs?

We are criticaldevs - a focused software development team of two. We're passionate about gaming and building tools that solve real problems. Our mission is to create software with excellent developer experience, smart automation, and open source at its core.

We focus on quality over speed, building robust systems that scale. Our approach combines pragmatic architecture with modern best practices. We automate what can be automated and document through clean, self-explanatory code.

---

## Meet the Team

### Kazuto
**Co-Founder & Developer**

Full-stack developer with a strong design background and a passion for crafting beautiful, functional web experiences. Started as a graphic designer before diving into front-end development, then expanding to full-stack. Combines visual storytelling with technical expertise.

Works with Go, Vue, Nuxt, Node.js, and loves automating workflows. Passionate gamer and constantly exploring new technologies. Believes in clean code and building solutions that not only work great but also look stunning. Team player with an eye for detail.

`Full-Stack` `Go` `Vue` `Design` `DevOps` `Gaming`

### WlanKabL
**Co-Founder & Developer**

Full-stack developer with a perfectionist eye for detail and a passion for solving complex problems. Specializes in building fast, scalable web applications with Vue.js, Node.js, and C#. Strong focus on architecture, automation, and developer experience.

Creator of Crowd-Nation, an event platform with real-time features. Loves competitive gaming and continuously exploring new tech. Believes in self-documenting code, automated tooling, and building systems that just work. Lifelong learner with a deep interest in game development.

`Full-Stack` `Vue.js` `Node.js` `C#` `DevOps` `Architecture`

---

## Current Project: TMS-Alpha

**TMS-Alpha** (Translation Management System) is our answer to the frustrations we've experienced with existing translation tools. A modern, open-source platform for managing translations at scale, built for real development workflows.

Supports multiple i18n formats, integrates with popular translation APIs, and includes features like scoped translations, intelligent duplicate detection, and typed schemas. Developer-friendly API, automation-first approach, and built to actually solve the problems we face daily.

### Core Features

| Feature | Description |
|---------|-------------|
| 🌐 **API Integrations** | Seamless integration with DeepL, Phrase, and other translation providers for automated translations and synchronization |
| 📦 **Multi-Format Support** | Import/export JSON, XML, .resx (C#), .properties (Java), and more |
| 🔗 **Smart Placeholders** | Support for `{}`, `{{}}`, `{name}`, `{0}` and more. Transform placeholders dynamically based on target framework |
| 🎯 **Scoped Translations** | Manage multiple projects with scopes. Map translations to specific apps, environments, or features with granular control |
| 🔍 **Similar Detection** | Prevent duplicate translations with intelligent similarity detection |
| 📝 **Typed Schemas** | Define translation schemas with typed placeholders. Know exactly what parameters are expected and their types |
| 🚀 **Dynamic Loading** | Load translations dynamically via HTTP request or integrate releases as dependencies into your projects |
| 📦 **Release Management** | Create translation bundles (releases) that can be versioned, deployed, and consumed by client applications |
| 🧠 **Context-Aware Translation** | Intelligent context detection understands domain-specific terminology. Knows that "character" means game character in a gaming context, not letter |

### API Example

```http
GET /api/translations?scope=app-x&lang=de&format=json
```

```json
{
  "scope": "app-x",
  "language": "de",
  "format": "json",
  "translations": {
    "welcome": "Willkommen im {appName}",
    "goodbye": "Komm bald wieder!",
    "next": "Weiter"
  },
  "metadata": {
    "lastUpdated": "2025-11-26T12:00:00Z",
    "version": "1.0.0"
  }
}
```

### Roadmap

- **Phase 1: Core Infrastructure** - API server architecture, database schema, JSON/XML import/export, REST API, auth system
- **Phase 2: Translation Provider Integration** - DeepL & Phrase integration, translation history, conflict resolution
- **Phase 3: Scopes & Multi-Project Support** - Multi-project management, scope-based queries, dashboard UI
- **Phase 4: Typed Schemas & Advanced Features** - Typed translation schemas, placeholder transformation, release management, SDKs
- **Phase 5: Production & Open Source** - Performance optimization, documentation, open source release, community guidelines

> 📦 **Open Source & Community Driven** - TMS-Alpha will be fully open source. We're building this because we need it ourselves - and we believe others do too.

---

## What We Do

- **Developer Tools & Automation**: We solve real problems. Our first major project is TMS-Alpha, a translation management system that's actually fun to use.
- **Full-Stack Development**: From Vue.js to Node.js, Go, and C#. We move between technologies depending on what fits best.
- **Open Source**: We build in public, share our code, and contribute to the community. No unnecessary secrets.
- **Quality over Speed**: Pragmatic architecture that still makes sense in two years. Developer experience is our top priority.

---

## Our Philosophy

- **Pragmatic & Robust**: Code that explains itself. Automation where it makes sense. Documentation through clarity.
- **Gaming meets Engineering**: Our love for competitive gaming pushes us on performance, UX, and that final polish.
- **Never Stop Learning**: Trying new technologies, frameworks, and ways of thinking is just part of it.
- **Open Source by Conviction**: We build what we need and share it with the world.

---

**CriticalDevs** – Two developers. One mission. Building better tools.
