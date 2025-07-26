# Hi there 👋

It's time to break from tutorial hell and start working on real projects!

```typescript
namespace BahaRojbi {
  export class About extends Me {
    getCurrentPosition(): Record<string, any> {
      return {
        education: {
          university: 'The Private Higher School of Engineering and Technology',
          grade: 'Final Year Masters Degree',
          degree: 'Software Architecture Engineering',
        },
        currentJob: {
          position: 'R&D Software Engineer | Automation & CI/CD for Medium Voltage Drives',
          company: 'ABB Switzerland',
        },
      };
    }

    getDailyKnowledge(): Array<string> {
      return [
        'TypeScript',
        'C++',
        'PHP',
        'Java',
        'Python',
        'C#',
        'React',
        'Angular',
        'Spring Boot',
        'Node.js',
        'Next.js',
        '.NET',
        'FastAPI',
        'Kubernetes',
        'Docker',
        'Groovy',
      ];
    }

    getFutureGoal(): string {
      return 'Advance to a senior-level software engineer, focusing on automation and back-end development';
    }
  }
}
