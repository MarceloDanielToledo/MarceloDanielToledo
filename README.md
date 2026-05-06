<h1 align="center">Marcelo Daniel Toledo</h1>

```csharp
public class MarceloDanielToledo : SoftwareDeveloper
{
    public string Role => "Software Developer"; // Specialized in .NET & Fintech
    public string Education => "Bachelor's Degree in Computer Science";
    public string Location => "Mar del Plata, Argentina 🇦🇷 (Remote)";
    public string Contact => "https://www.linkedin.com/in/marcelodanieltoledo";
    public string Portfolio => "https://www.marcelodanieltoledo.com";

    public override string[] TechStack => new[]
    {
        ".NET", "SQL Server", "RabbitMQ", "Blazor", "React",
        "Docker", "Azure", "SignalR", "Hangfire", "Polly",
        "OpenTelemetry", "Prometheus", "Grafana", "CI/CD"
    };

    public override string[] SoftSkills => new[]
    {
        "Leadership", "Effective Communication", "Strategic Problem-Solving", "Adaptability"
    };

    public void WeeklyActivity()
    {
        // 💼 +5 years of experience in Fintech & payments infrastructure
        // 🏗️ Leading greenfield projects & complex system migrations
        // 🤖 Integrating AI-driven development practices into daily workflows
        // 🚀 CTO & Co-founder of WSC Software — SaaS order & stock management

        if (DateTime.Now.DayOfWeek is DayOfWeek.Saturday or DayOfWeek.Sunday)
        {
            Maintain.SaaS();
            Do.Consulting();
            Collaborate.OnInterestingProjects();
        }
        else
        {
            Work.SoftwareDevelopment();
            Study.NewTechnologies();
            Play.WithMyDog();
        }
    }

    public string[] Goals => new[]
    {
        "Build high-performance, maintainable distributed systems",
        "Contribute to impactful fintech & payments solutions",
        "Deliver full product lifecycle software"
    };

    public string[] MusicTaste => new[] { "Lofi", "Rock", "R&B/Soul" };
}
```
