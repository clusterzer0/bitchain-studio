# Context — dlockamy/bitchain-studio
# Lockamy Studios · LS project

**What it is:** GUI desktop and mobile application for browsing and managing
bitchain artifact bundles. Companion app to the `bitchain` CLI.

**Status:** Stub — no code yet. Framework TBD (likely Flutter using Digital Zen
package, or Tauri + Rust for desktop-first).

**Depends on:**
- `dlockamy/bitchain` — CLI and data model
- `dlockamy/refraction` — server API (if remote manifest storage is needed)
- `lockamy-studios/digital-zen` — UI design system

**Planned features:**
- Browse manifests by artifact name / version
- Visual block diff between versions
- Upload / download artifacts via drag-and-drop
- Local store and Refraction server support

**CI:** Jenkinsfile present (placeholder Docker build — no-op until framework chosen).
**Nexus target:** `nexus.softsurve.com:5000/bitchain-studio` (Docker).
**Jira:** LS project (new work). Legacy: KAN-81.

**Next step:** Decide on framework (Flutter vs Tauri) before writing any code.
