1. Install Serilog.AspNetCore.
2. Install Serilog.Sinks.File.
3. Add .UseSerilog() to `CreateHostBuilder`.
4. Replace the "Logging" JSON object with "Serilog" inside of appsettings.json.
5. (Optional) Configure appsettings per environment.