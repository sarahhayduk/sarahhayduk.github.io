---
layout: default
title: Enhancement Three Demo
---

# Enhancement Three Demo Video

<div style="text-align:center;">
  <iframe width="800" height="450"
          src="https://www.youtube.com/embed/wWMQ_aQp5QY"
          title="Enhancement Three Demo"
          frameborder="0"
          allowfullscreen>
  </iframe>
</div>

#### Description
This video demonstrates Enhancement Three of my Client Management System refactor. I replaced all hardcoded client and password data with a securely seeded SQLite database using the SQLite amalgamation files. The system now loads the stored hash and salt for authentication, initializes its schema automatically, and runs the external seed.sql file only on first use. These changes ensure sensitive information is never embedded in the executable and cannot be exposed through reverse engineering. The walkthrough shows the finalized program output using correct paths and focuses on the completed workflow rather than error‑handling routines.
