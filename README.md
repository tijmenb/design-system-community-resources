# GOV.UK Design System Community Resources

This is a collection of examples and tools built by the cross-government developer community to use the GOV.UK Design System and GOV.UK Frontend.

You may also be interested in other [resources to help digital teams working in the public sector](https://github.com/MatMoore/digital-service-resources).

This list is maintained by the community. Please [raise an issue or Pull Request](https://github.com/tijmenb/design-system-community-resources/issues/new) to add something.

## Officially supported tools

These are the tools officially supported by the Design System team in GDS.

- [GOV.UK Design System](https://design-system.service.gov.uk/)
- [GOV.UK Frontend](https://github.com/alphagov/govuk-frontend)
- [GOV.UK Prototype Kit](https://govuk-prototype-kit.herokuapp.com/docs)

### HTML
You can copy and paste the HTML examples into your project if there is no templating support.

### Node.js
- [GOV.UK Frontend](https://github.com/alphagov/govuk-frontend) - supports Nunjucks templating language for Node.js

Examples:

- [GOV.UK Pay](https://github.com/alphagov/pay-frontend)
- [GDS Node.js boilerplate](https://github.com/alphagov/gds-nodejs-boilerplate)

## Unofficial tools & resources

### Figma

- You can import the [Sketch wireframing kit](#sketch) into Figma.

### Python

- [alphagov/govuk-frontend-jinja](https://github.com/alphagov/govuk-frontend-jinja) - Tools to use the GOV.UK Design System with Python webapps that use Jinja2 and Flask.
  - Example: [Digital Marketplace](https://github.com/alphagov/digitalmarketplace-user-frontend)
- [LandRegistry/govuk-frontend-jinja](https://github.com/LandRegistry/govuk-frontend-jinja) - Provides a complete set of Jinja macros that are kept up-to-date and 100% compliant with the govuk-frontend Nunjucks macros. Porting is intentionally manual rather than automated to make updates simpler than maintaining an automated conversion routine. A [comprehensive test suite](https://github.com/surevine/govuk-frontend-diff) ensures compliance against the latest, and every subsequent, GOV.UK Frontend release.
  - Package: https://pypi.org/project/govuk-frontend-jinja/
  - Example: https://github.com/matthew-shaw/govuk-frontend-jinja-example
  - Demo: https://govuk-frontend-jinja.herokuapp.com/

### PHP

- [GOV.UK Design System Drupal Theme](https://www.drupal.org/project/govuk_design_system)

### React
- [govuk-react/govuk-react](https://github.com/govuk-react/govuk-react) - GOV.UK Design System in React using CSSinJS
- [govuk-react-jsx](https://github.com/surevine/govuk-react-jsx) - A port of the govuk-frontend Nunjucks to lightweight JSX (Directly consuming govuk CSS/JS). See readme for more detailed comparison with govuk-react.

### Ruby

- [UKGovernmentBEIS/govuk-design-system-rails](https://github.com/UKGovernmentBEIS/govuk-design-system-rails) - Rails engine containing a Ruby on Rails port of some GOV.UK Design System components.
- [DFE-Digital/govuk_design_system_formbuilder](https://github.com/DFE-Digital/govuk_design_system_formbuilder) - GOV.UK-compliant form builder for Rails
- [Tech docs template](https://tdt-documentation.london.cloudapps.digital) - A template for building Middleman site for technical documentation

Examples:

- [GOV.UK](https://www.gov.uk) itself uses the Design System via [GOV.UK Publishing Components](https://github.com/alphagov/govuk_publishing_components) (GDS)
- [Find teacher training](https://github.com/DFE-Digital/find-teacher-training) (DfE)
- [Apply for teacher training](https://github.com/DFE-Digital/apply-for-postgraduate-teacher-training) (DfE)
- [Teacher Vacancy Service](https://github.com/DFE-Digital/teacher-vacancy-service) (DfE)
- [Office for Product Safety and Standards Services](https://github.com/UKGovernmentBEIS/beis-opss) (BEIS)
- [GovWifi Admin](https://github.com/alphagov/govwifi-admin) (GDS)

### R

- [ukgovdatascience/govdown](https://github.com/ukgovdatascience/govdown) - GOV.UK Design System theme for R Markdown

### Sketch

- [Sketch wireframing kit](https://github.com/abbott567/sketch_wireframing_kit) includes components and patterns from the GOV.UK Design System.

### C# / ASP.Net Core

- [GOV.UK Design System in C# / ASP.Net Core](https://github.com/cabinetoffice/govuk-design-system-dotnet) - GOV.UK Design System components in Razor components, with optional validation and error message generation

### Code editor plugins

- [daviddotto/govuk-design-system-snippets](https://github.com/daviddotto/govuk-design-system-snippets) - Nunjucks macro snippets for popular code editors
