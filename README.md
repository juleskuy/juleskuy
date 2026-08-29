```typescript
/**
 * @fileoverview Zulfan Nurrahman — Developer Profile
 * @author Zulfan Nurrahman <zulfann2299@gmail.com>
 * @see https://juleprod.cloud
 */

interface Profile {
  name: string;
  role: string;
  location: string;
  experienceYears: number;
  company: {
    name: string;
    role: string;
    url: string;
    services: string[];
  };
  activeProjects: Record<string, { description: string; scope: string[]; status: string }>;
  techStack: {
    languages: string[];
    frontend: string[];
    backend: string[];
    databases: string[];
    devOps: string[];
    design: string[];
  };
  contact: Record<string, string>;
}

export const zulfan: Profile = {
  name: "Zulfan Nurrahman",
  role: "Full-Stack Engineer & Systems Architect",
  location: "Indonesia",
  experienceYears: 6,

  company: {
    name: "JuleProd",
    role: "Founder & Lead Engineer",
    url: "https://juleprod.cloud",
    services: [
      "Custom Web Application Development",
      "API Architecture & System Integration",
      "Bilingual Solutions (EN/ID)",
    ],
  },

  activeProjects: {
    rensaId: {
      description: "Enterprise Digital Platform",
      scope: ["Company Profile Web App", "CMS", "Mobile App"],
      status: "in_active_development",
    },
    juleProd: {
      description: "Web App Development Services",
      scope: ["Founder-led Engineering", "Production Deployments"],
      status: "live",
    },
  },

  techStack: {
    languages: ["TypeScript", "JavaScript", "PHP", "Python"],
    frontend: ["Next.js", "React", "Tailwind CSS", "Motion", "shadcn/ui"],
    backend: ["Laravel", "FastAPI", "Express", "REST APIs", "OAuth2 / JWT"],
    databases: ["PostgreSQL", "MySQL", "SQLite", "Redis"],
    devOps: ["Vercel", "GitHub Actions", "Docker", "Linux"],
    design: ["Swiss / Editorial UI", "Design Systems", "Figma"],
  },

  contact: {
    web: "https://juleskuy.cloud",
    agency: "https://juleprod.cloud",
    email: "zulfann2299@gmail.com",
    whatsapp: "+6281222179661",
    linkedin: "https://linkedin.com/in/juleskuy",
    x: "https://x.com/zulfann22",
  },
};
```

---

<div align="center">

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=juleskuy&theme=dark&show_icons=true&hide_border=true&count_private=true&include_all_commits=true)](https://github.com/juleskuy)
[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=juleskuy&theme=dark&hide_border=true&layout=compact&include_all_commits=true&count_private=true)](https://github.com/juleskuy)

</div>
