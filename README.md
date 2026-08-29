<div align="center">

```
 ┌───────────────────────────────────────────────────────────────────────────┐
 │ 📁 zulfan-workspace  —  index.ts  —  Visual Studio Code                  │
 └───────────────────────────────────────────────────────────────────────────┘
```

</div>

```typescript
import { SeniorEngineer, AgencyFounder } from "@juleprod/core";
import { NextJS, TypeScript, Tailwind, Laravel, Python, PostgreSQL } from "@tech/stack";

interface Capabilities {
  architecture: "Monolithic" | "Microservices" | "Serverless" | "Edge";
  uiDesign: "Swiss / Editorial" | "Anti-AI-Slop" | "High Accessibility (A11y)";
  deployment: "Zero-Downtime CI/CD" | "Automated QA" | "Vercel / Docker";
}

/**
 * @class ZulfanEngineer
 * @description 6+ Years Experience Shipping Production-Grade Digital Systems.
 */
export class ZulfanEngine extends SeniorEngineer implements AgencyFounder {
  public readonly name = "Zulfan Nurrahman";
  public readonly handle = "@juleskuy";
  public readonly title = "Full-Stack Systems Engineer & Founder";
  public readonly location = "Indonesia 🇮🇩 (Operating Globally 🌍)";
  public readonly agency = "JuleProd (https://juleprod.cloud)";

  public currentFocus = {
    agency: {
      name: "JuleProd",
      role: "Founder & Lead Engineer",
      service: "Founder-Led Web App Engineering & High-Performance Client Delivery",
      url: "https://juleprod.cloud",
    },
    product: {
      name: "Rensa ID",
      scope: ["Company Profile Web App", "CMS Backoffice", "Mobile App Client"],
      status: "Active Production Pipeline",
    },
  };

  /**
   * Primary Engineering & Technical Matrix
   */
  public getCapabilities(): Capabilities {
    return {
      architecture: "Edge",
      uiDesign: "Swiss / Editorial",
      deployment: "Zero-Downtime CI/CD",
    };
  }

  public getTechStack() {
    return {
      frontend: [NextJS, TypeScript, "React", Tailwind, "Motion", "shadcn/ui"],
      backend: [Laravel, "PHP 8+", Python, "FastAPI", "Node.js", "Express"],
      database: [PostgreSQL, "MySQL", "SQLite", "Redis"],
      infrastructure: ["Vercel", "GitHub Actions", "Docker", "Linux (Ubuntu/Debian)"],
      design: ["Figma", "UI/UX Strategy", "System Architecture", "Performance Auditing"],
    };
  }

  /**
   * Executes client contract delivery pipeline
   */
  public async shipProductionApp(clientGoal: string): Promise<string> {
    const spec = await this.analyzeRequirements(clientGoal);
    const code = await this.buildWithPrecision(spec, this.getTechStack());
    const verified = await this.runAutomatedQA(code, { a11y: true, coverage: 80 });
    return this.deployToProduction(verified);
  }

  public getContactDetails() {
    return {
      portfolio: "https://juleskuy.cloud",
      agency: "https://juleprod.cloud",
      email: "zulfann2299@gmail.com",
      whatsapp: "+62 812 2217 9661",
      socials: {
        linkedin: "https://linkedin.com/in/juleskuy",
        twitter: "https://x.com/zulfann22",
        discord: "juleskuy",
      },
    };
  }
}

export default new ZulfanEngine();
```

<div align="center">

```
 ┌───────────────────────────────────────────────────────────────────────────┐
 │ 💬 Terminal  —  zulfan@juleprod:~ $ npx juleskuy --stats                  │
 └───────────────────────────────────────────────────────────────────────────┘
```

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=juleskuy&theme=tokyonight&show_icons=true&hide_border=true&count_private=true&include_all_commits=true)](https://github.com/juleskuy)
[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=juleskuy&theme=tokyonight&hide_border=true&layout=compact&include_all_commits=true&count_private=true)](https://github.com/juleskuy)

</div>

---

<div align="center">

```
> Status: 200 OK — Ready for contract engineering & technical consultation.
```

[🌐 Portfolio](https://juleskuy.cloud) · [🚀 JuleProd Agency](https://juleprod.cloud) · [💬 Book Consultation](https://wa.me/6281222179661)

</div>
