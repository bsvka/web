---
hide:
  - toc
---

# Gramps Web development: overview

Gramps Web is a web application that consists of two components that are developed separately:

- **Gramps Web API** is a RESTful API written in Python and based on Flask. The source code is hosted at [github.com/gramps-project/gramps-webapi](https://github.com/gramps-project/gramps-webapi/). It manages database access and genealogical functions directly leveraging the Gramps Python library. It serves as the backend of Gramps Web. For development documentation, see [Backend](dev-backend/index.md).
- **Gramps.js** is a Javascript web application that serves as the frontend to Gramps Web. The source code is hosted at [github.com/gramps-project/Gramps.js](https://github.com/gramps-project/Gramps.js/). For development documentation, see [Frontend](dev-frontend/index.md).

A note on versioning: Gramps Web API and Gramps.js are versioned independently. At present, "Gramps Web" &ndash; the combined application &ndash; does not have a separate version number. Both projects adhere to [SemVer](https://semver.org/).

If you are not a Python or Javascript developer but would still like to contribute to Gramps Web, check out [Contribute](contribute.md).