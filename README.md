# Field System Filament

Registers the content-type schema editor as the Field System’s Filament 5
administration surface.

<!-- module-presentation-guide:begin -->
## Presentation architecture and project hosts

- Capability/source key: `liberusoftware/module-cms-field-system`.
- Actual Composer identity: `liberusoftware/module-cms-field-system-filament`.
- [Filament capability plan](https://github.com/liberusoftware/documentation/blob/main/projects/cms/filament/field-system.md) · [Filament standard](https://github.com/liberusoftware/documentation/blob/main/standards/FILAMENT.md) · [Module architecture](https://github.com/liberusoftware/documentation/blob/main/architecture/MODULES.md).

The application owns panel composition, routing, session integration and deployment. This module owns its focused presentation and delegates domain behavior to reviewed public owner contracts. Keep host App aliases, duplicate records and client-only authorization outside reusable package boundaries.

Documented consumer project families:

- [CMS](https://github.com/liberusoftware/project-cms-laravel-filament): Content authoring, publishing and delivery.

Other web, mobile and desktop presentations are listed in the [project catalog](https://github.com/liberusoftware/documentation/blob/main/projects/REPOSITORIES.md). Those skeletons provide starting structures; links do not establish feature parity, compatible releases or completed device/API integrations. Independent presentation packages keep their own Composer, npm or pub metadata.
<!-- module-presentation-guide:end -->
