# Technical Requirements Overview

## Frontend Framework

All libraries must be bundled locally for air-gapped environment usage.

| Library | Purpose |
|---------|---------|
| **Basecoat UI** | UI built with Tailwind CSS, designed to be used with any traditional web stack |
| **Alpine.js** | Lightweight client-side interactivity |
| **HTMX** | Dynamic partial page updates |
| **jQuery 3.7.1** | Legacy component support |

## Backend Framework

| Technology | Purpose |
|------------|---------|
| **ASP.NET Core Web App (Razor Pages .NET 9)** | Server-side web framework |
| **Entity Framework Core** | ORM with code-first approach |
| **ErrorOr** | Error handling without exceptions |
| **Serilog + OpenTelemetry** | Logging and observability |

## Architecture

- Server-rendered UI enhanced with HTMX + Alpine.js
- Feature-based project structure
- Domain-driven design with CQRS pattern
- Forms/modals load partial HTML via HTMX

---
