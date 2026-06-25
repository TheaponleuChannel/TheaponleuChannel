```javascript
const me = {
  name: "Thea Ponleu",
  username: "TheaPonleuChannel",
  location: "Phnom Penh, Cambodia",
  title: "Frontend Developer",
  email: "ponleu.thea@gmail.com",
  website: "https://theaponleu.dev",
  availableForHire: true,
  
  languages: ["JavaScript", "C#", "TypeScript", "Java", "C++"],
  frameworks: ["Angular", "Node.js", "Express", "Django", "Next.js"],
  databases: ["PostgreSQL", "MongoDB", "MySQL", "Redis"],
  tools: ["Git", "Docker", "VS Code", "Figma", "Postman","Brono"],
  devops: ["Docker", "Nginx", "AWS"],
  
  currentlyLearning: ["Rust", "Kubernetes", "GraphQL"],
  interests: ["Open Source", "AI/ML", "Web Development", "Cloud Computing"],
  goals: [
    "Contribute to 10+ open source projects",
    "Build a full-stack SaaS application",
    "Get AWS Certified",
    "Write 12 technical blog posts",
    "Learn Rust and build a CLI tool"
  ],
  
  getStats() {
    return {
      repos: 42,
      followers: 128,
      following: 56,
      contributions: "1,200+"
    };
  },
  
  getTechStack() {
    return {
      frontend: ["Angular", "Vue", "HTML5", "CSS3", "Tailwind","PrimeVue","PrimgNg"],
      backend: ["Node.js", "Express","Mongoose"],
      database: this.databases,
      devops: this.devops,
      tools: this.tools
    };
  },
  
};
