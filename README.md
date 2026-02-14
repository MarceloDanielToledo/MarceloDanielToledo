<h1 align="center">Marcelo Daniel Toledo</h1>
<h3 align="center">Software Developer | .NET Ecosystem Specialist</h3>

```csharp
public class MarceloDanielToledo : SoftwareDeveloper
{
    public string Role => "Software Developer"; // Specialized in .NET Ecosystem
    public string Education => "Bachelor's Degree in Computer Science";
    public string Contact => "https://www.linkedin.com/in/marcelodanieltoledo";

    public override string[] Skills => new[]
    {
        ".NET", "SQL", "Microservices", "Docker", "Oracle", "Go", "React", "Blazor", "Kubernetes", "Redis", "CI/CD", ".NET Framework"
    };

    public override string[] SoftSkills => new[]
    {
        "Effective Communication", "Problem Solving", "Team Collaboration", "Adaptability"
    };
    
    public void WeeklyActivity()
    {
        // 💼 +5 years of experience, currently working in the Fintech area
        // 🚀 Owner of SaaS solutions: handling maintenance & new features
        // 🌱 Deep diving into efficient Microservices Design & Architecture

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
        "Collaborate on scalable solutions",
        "Engage in full product lifecycle development",
        "Deliver impactful software products"
    };

    public string[] MusicTaste => new[] { "Lofi", "Rock", "R&B/Soul" };
}